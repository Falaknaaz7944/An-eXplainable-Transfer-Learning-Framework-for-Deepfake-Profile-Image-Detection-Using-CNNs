# 📁 PROJECT STRUCTURE

## Clean, Professional Organization

```
deepfake_detection/
│
├── 📄 README.md                    # Main project documentation
├── 📄 requirements.txt             # Python dependencies
├── 📄 setup.bat                    # Windows quick setup
├── 📄 setup.sh                     # Linux/Mac quick setup
├── 📄 runtime.txt                  # Python version
├── 📄 .gitignore                   # Git ignore rules
├── 📄 .gitattributes              # Git LFS configuration
├── 📄 vercel.json                 # Vercel deployment config
│
├── 📂 config/                      # Configuration files
│   └── config.yaml                # Main configuration
│
├── 📂 src/                         # Source code
│   ├── __init__.py
│   ├── data/                      # Data processing
│   │   ├── __init__.py
│   │   ├── dataset.py
│   │   └── transforms.py
│   ├── models/                    # Model architecture
│   │   ├── __init__.py
│   │   └── model.py
│   ├── training/                  # Training logic
│   │   ├── __init__.py
│   │   └── trainer.py
│   └── utils/                     # Utilities
│       ├── __init__.py
│       ├── metrics.py
│       ├── logger.py
│       ├── visualize.py
│       └── explainable_ai.py
│
├── 📂 api/                         # Vercel API handlers
│   └── index.py
│
├── 📂 templates/                   # HTML templates
│   └── index.html                 # Web interface
│
├── 📂 static/                      # Static assets
│   ├── style.css                  # Styling
│   └── script.js                  # JavaScript
│
├── 📂 docs/                        # 📚 DOCUMENTATION
│   ├── COMPLETE_GUIDE.md          # Complete usage guide
│   ├── DEPLOYMENT_GUIDE.md        # Deployment instructions
│   ├── GITHUB_VERCEL_DEPLOY.md    # GitHub & Vercel guide
│   ├── WEB_APP_GUIDE.md           # Web app usage
│   ├── MODEL_PERFORMANCE.md       # Model metrics
│   ├── EXPLAINABLE_AI.md          # XAI explanation
│   ├── GPU_SETUP.md               # GPU configuration
│   ├── HEAT_SAFETY.md             # Temperature management
│   ├── OVERFITTING_PREVENTION.md  # Anti-overfitting info
│   ├── ULTRA_FAST_TRAINING.md     # Speed optimization
│   ├── STEP_BY_STEP.md            # Step-by-step guide
│   ├── QUICK_REFERENCE.md         # Quick commands
│   ├── GPU_READY.md               # GPU status
│   ├── DEPLOY_QUICK.md            # Quick deploy commands
│   ├── VERCEL_404_FIX.md          # Vercel troubleshooting
│   └── ZIPIGNORE.txt              # ZIP exclusion list
│
├── 📂 outputs/                     # Training outputs (preserved)
│   ├── checkpoints/               # Model checkpoints
│   │   └── best_model.pth        # ⭐ Trained model
│   ├── metrics/                   # Training metrics
│   │   ├── training_metrics.csv
│   │   └── training_history.png
│   ├── logs/                      # Training logs
│   └── evaluation/                # Evaluation results
│
├── 📂 data/                        # Dataset (not in Git)
│   ├── Train/
│   ├── Validation/
│   └── Test/
│
├── 📄 train.py                     # Training script
├── 📄 evaluate.py                  # Evaluation script
├── 📄 predict.py                   # Prediction script
└── 📄 app.py                       # Web application
```

## 🎯 Key Improvements

### ✅ What Changed:
- All documentation moved to `docs/` folder
- README.md stays at root (GitHub standard)
- Core functionality files at root level
- Source code organized in `src/`
- Configuration isolated in `config/`
- Outputs preserved in `outputs/`

### ✅ What Stayed Same:
- All scripts work exactly as before
- Outputs directory untouched
- Model predictions still work
- Web app still runs
- Training/evaluation unchanged

## 🚀 Usage (No Changes!)

**Everything works the same:**

```bash
# Training (unchanged)
python train.py

# Evaluation (unchanged)
python evaluate.py

# Prediction (unchanged)
python predict.py --image test.jpg

# Web app (unchanged)
python app.py
```

## 📚 Documentation

All guides are now in `docs/` folder:
- `docs/COMPLETE_GUIDE.md` - Everything you need
- `docs/DEPLOYMENT_GUIDE.md` - Deploy anywhere
- `docs/WEB_APP_GUIDE.md` - Use web interface
- `docs/MODEL_PERFORMANCE.md` - Check accuracy

## ✨ Benefits

- ✅ Clean root directory
- ✅ Professional structure
- ✅ Easy to navigate
- ✅ GitHub-friendly
- ✅ All functionality intact
- ✅ Better organization
