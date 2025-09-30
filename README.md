# 🎓 Explainable AI Deepfake Detection  
**Using CNNs + SHAP to Detect AI-Generated Imagery**  
*Sara Alghamdi | MSc Artificial Intelligence – Aston University*



## 📌 Project Summary

This project demonstrates how a custom-built **Convolutional Neural Network (CNN)** combined with **SHAP (SHapley Additive exPlanations)** can accurately detect and explain AI-generated (deepfake) imagery.

- 🔍 Binary classification: Real vs. AI-generated images  
- 📊 92.94% Accuracy | 0.981 AUC  
- 💡 Fully explainable using SHAP XAI visualizations  
- 🧠 Dataset: CIFAR-10 (real) + Synthetic (Stable Diffusion-based)

---

## 🔍 Features

- ✅ Convolutional Neural Network (CNN) in TensorFlow/Keras  
- ✅ SHAP (XAI) for visualizing feature importance  
- ✅ Trained on 120,000 images (100K training / 20K test)  
- ✅ Includes evaluation metrics + confusion matrix + SHAP heatmaps
