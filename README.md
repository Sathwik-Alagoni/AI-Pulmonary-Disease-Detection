# AI-Pulmonary-Disease-Detection


[![Python Version](https://img.shields.io/badge/python-3.8%2B-green.svg)](https://www.python.org/)

> **AI-Powered Pulmonary Disease Diagnosis**: A deep learning classifier to detect Pneumonia, COVID-19, Tuberculosis, and Normal from chest X-ray images.

---
<video width="600" controls>
  <source src="WhatsApp Video 2025-06-13 at 10.11.53.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

-----

## 📋 Table of Contents
- [🎯 Project Overview](#-project-overview)
- [🚀 Features](#-features)
- [🗂️ Dataset](#-dataset)
- [⚙️ Installation](#-installation)
- [🛠️ Usage](#-usage)
- [📈 Model Architecture](#-model-architecture)
- [🔍 Evaluation & Results](#-evaluation--results)
- [🎥 Demo](#-demo)
- [🧠 Future Work](#-future-work)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## 🎯 Project Overview
This repository contains code for an **AI-powered Pulmonary Disease Diagnosis** system that classifies chest X-ray images into four categories:

1. **Pneumonia**  
2. **COVID-19**  
3. **Tuberculosis**  
4. **Normal**  

The model leverages convolutional neural networks (CNNs) to learn discriminative patterns from radiographic images, enabling rapid and accurate screening.

---

## 🚀 Features
- **Multi-class classification**: Pneumonia, COVID-19, Tuberculosis, and Normal.  
- **Data augmentation**: Rotation, flip, zoom for robust training.  
- **Transfer Learning**: Option to use pre-trained backbones (e.g., ResNet, VGG).  
- **Performance metrics**: Accuracy, Precision, Recall, F1-score, and Confusion Matrix.  
- **Grad-CAM**: Visual explanations of model decision regions.  
- **Easy deployment**: Streamlit/Flask template for quick web demos.  

---

## 🗂️ Dataset
We used publicly available chest X‑ray datasets:  
- **Pneumonia & Normal**: [Kaggle Chest X‑Ray Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)  
- **COVID-19**: [COVID-19 Radiography Database](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database)  
- **Tuberculosis**: [Tuberculosis X‑ray Images](https://www.kaggle.com/adityaomkar/pediatric-tuberculosis-chest-xray)

**Directory Structure**:
## 📂 Project Structure

```plaintext
Chest_Xray_Classifier/
├── chest_xray_classifier/
│   ├── __pycache__/
│   ├── sample_images/
│   │   ├── NEUMONIA/
│   │   └── NORMAL/
│   ├── static/
│   │   ├── css/
│   │   │   └── styles.css
│   │   └── uploads/
│   ├── templates/
│   │   ├── index.html
│   │   └── result.html
│   ├── app.py
│   ├── data_preprocessing.py
│   ├── ensemble_model.py
│   ├── grad_cam.py
│   ├── model_loader.py
│   └── WhatsApp Video 2025-06-13 at XX-XX-XX.mp4
├── requirements.txt
├── README.md
└── LICENSE
```


