# 🧠 Diabetic Retinopathy Diagnosis — Explainable AI (XAI)

> A deep learning model for automated detection of diabetic retinopathy using CNN, with Explainable AI techniques (Grad-CAM, SHAP, LIME) for transparent and interpretable medical predictions.

## 🛠️ Tech Stack

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

## ✨ Key Features

- 🔬 **CNN Model** — Automated detection across diabetic retinopathy severity grades
- 👁️ **Grad-CAM** — Visual heatmaps highlighting retinal regions driving predictions
- 📊 **SHAP & LIME** — Feature attribution scores for model transparency
- 🔄 **Data Augmentation** — Rotation, flips, brightness normalization via OpenCV (~15% overfitting reduction)
- ☁️ **AWS Deployment** — Real-time inference via REST API endpoint
- 🏥 **Medical Interpretability** — XAI outputs designed for medical stakeholder review

## 🧪 Model Architecture

- **Base Model:** Convolutional Neural Network (CNN)
- **Framework:** TensorFlow + Keras
- **XAI Methods:** Grad-CAM, LIME, SHAP
- **Preprocessing:** OpenCV pipeline with augmentation
- **Deployment:** AWS cloud with REST API

## 📁 Project Structure

```
Diabetic-Retinopathy-XAI/
├── model/
│   ├── train.py            # CNN model training script
│   ├── predict.py          # Inference and prediction
│   └── model.h5            # Saved trained model
├── xai/
│   ├── gradcam.py          # Grad-CAM visualization
│   ├── shap_explain.py     # SHAP feature attribution
│   └── lime_explain.py     # LIME local explanations
├── preprocessing/
│   ├── augment.py          # Data augmentation pipeline
│   └── preprocess.py       # Image preprocessing with OpenCV
├── api/
│   └── app.py              # Flask REST API for deployment
├── requirements.txt
└── README.md
```

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/SujanP20/Diabetic-Retinopathy-XAI.git
cd Diabetic-Retinopathy-XAI

# Install dependencies
pip install -r requirements.txt

# Train the model
python model/train.py

# Run the API
python api/app.py
```

## 👤 Author

**Sujan P** — AI/ML Developer & Software Engineer
- 📧 sujan.p4444@gmail.com
- 💼 [LinkedIn](https://linkedin.com/in/sujan-p)
- 🌐 [Portfolio](https://sujan.me)
- 🐙 [GitHub](https://github.com/SujanP20)
