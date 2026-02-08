# 🎯 Deepfake Detection System

**AI-powered deepfake image detector with 98.71% accuracy**

[![Python 3.11+](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-red.svg)](https://pytorch.org/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

---

## 🌟 Features

- ✅ **98.71% Accuracy** - State-of-the-art detection
- ✅ **EfficientNetB0** - Optimized CNN architecture  
- ✅ **Web Interface** - Beautiful drag-and-drop UI
- ✅ **Explainable AI** - Grad-CAM heatmap visualization
- ✅ **Fast Inference** - 50-100ms per image
- ✅ **Production Ready** - REST API + Frontend

---

## 🚀 Quick Start

### 1. Install Dependencies

```bash
pip install torch torchvision --index-url https://download.pytorch.org/whl/cpu
pip install -r requirements.txt
```

### 2. Run Web App

```bash
python app.py
```

### 3. Open Browser

Visit: http://localhost:5000

**That's it!** 🎉

---

## 📊 Model Performance

- **Architecture**: EfficientNetB0 (4M parameters)
- **Validation Accuracy**: 98.71%
- **Precision**: 98.71% | **Recall**: 98.71%
- **F1-Score**: 98.71% | **ROC-AUC**: 99.85%
- **Training Dataset**: 140,002 images
- **Training Time**: ~2.5-4 hours (GPU)

---

## 💻 Usage

### Command Line Prediction

```bash
# Single image
python predict.py --image path/to/image.jpg

# Multiple images
python predict.py --image_dir path/to/images/
```

### Web Interface

```bash
python app.py
# Open http://localhost:5000
# Upload image, get instant prediction with heatmap!
```

### Training (Optional)

```bash
python train.py
```

### Evaluation

```bash
python evaluate.py
```

---

## 📁 Project Structure

```
deepfake_detection/
├── app.py              # Web application
├── train.py            # Training script
├── predict.py          # CLI prediction
├── src/                # Source code
├── config/             # Configuration
├── outputs/            # Trained models
├── docs/               # Documentation
└── README.md          # This file
```

See [docs/STRUCTURE.md](docs/STRUCTURE.md) for complete structure.

---

## 📚 Documentation

**Getting Started:**
- [Complete Guide](docs/COMPLETE_GUIDE.md) - Full walkthrough
- [Quick Reference](docs/QUICK_REFERENCE.md) - Common commands
- [Web App Guide](docs/WEB_APP_GUIDE.md) - Use web interface

**Deployment:**
- [Deployment Guide](docs/DEPLOYMENT_GUIDE.md) - Deploy anywhere
- [GitHub & Vercel](docs/GITHUB_VERCEL_DEPLOY.md) - Cloud deployment

**Advanced:**
- [Model Performance](docs/MODEL_PERFORMANCE.md) - Detailed metrics
- [Explainable AI](docs/EXPLAINABLE_AI.md) - How Grad-CAM works
- [GPU Setup](docs/GPU_SETUP.md) - GPU acceleration

---

## 🎨 Demo

**Web Interface:**
- Upload any image
- Get instant Fake/Real prediction
- View AI attention heatmap
- See confidence scores

**Example Output:**
```
Prediction: Fake (AI-Generated)
Confidence: 94.32%
Heatmap: Shows which areas influenced the decision
```

---

## 🔧 Technical Stack

- **Framework**: PyTorch 2.0+
- **Model**: EfficientNetB0 (Transfer Learning)
- **Web**: Flask + HTML/CSS/JS
- **XAI**: Grad-CAM visualization
- **Deployment**: Vercel-ready, Docker-ready

---

## 📖 How It Works

1. **Input**: User uploads an image
2. **Preprocessing**: Resize to 160x160, normalize
3. **Inference**: EfficientNetB0 forward pass
4. **Prediction**: Softmax classification (Real/Fake)
5. **Explanation**: Grad-CAM generates attention heatmap
6. **Output**: Prediction + confidence + heatmap

---

## 🎯 Use Cases

- **Social Media**: Detect fake profile pictures
- **Dating Apps**: Verify authentic photos
- **Content Moderation**: Flag AI-generated content
- **Journalism**: Verify image authenticity
- **Security**: Prevent catfishing and fraud

---

## ⚙️ Requirements

- Python 3.8+
- 8GB+ RAM
- CPU (works) or GPU (faster)
- ~2GB disk space

---

## 📄 License

MIT License - see [LICENSE](LICENSE) file

---

## 🤝 Contributing

Contributions welcome! Please:
1. Fork the repository
2. Create feature branch
3. Commit changes
4. Push and create Pull Request

---

## 📞 Support

- **Documentation**: Check `docs/` folder
- **Issues**: Open GitHub issue
- **Questions**: Use GitHub Discussions

---

## 🙏 Acknowledgments

- EfficientNet architecture by Google Research
- Grad-CAM visualization technique
- PyTorch team for amazing framework

---

## ⭐ Star This Project

If you find this project useful, please give it a star! ⭐

---

**Built with ❤️ for online safety and authenticity**
