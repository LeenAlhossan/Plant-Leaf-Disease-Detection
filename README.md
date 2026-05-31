# 🌿 Plant Leaf Disease Detection Using AI Models

## 📌 Overview
This project uses Artificial Intelligence and Deep Learning techniques to detect plant leaf diseases from images. The system classifies plant leaves into healthy or diseased categories and provides a diagnosis based on image analysis.

The project was developed as part of a machine learning and image classification study to compare traditional machine learning models with deep learning approaches.

---

## 🎯 Objectives
- Detect plant diseases from leaf images.
- Compare multiple classification models.
- Evaluate model performance using standard metrics.
- Build a simple user-friendly application for disease prediction.

---

## 📊 Dataset
The project uses the PlantVillage dataset, which contains:

- 20,638 plant leaf images
- 15 disease and healthy classes
- Tomato, Potato, and Pepper plant categories

Data preprocessing included:
- Image resizing
- Normalization
- Train-test splitting

---

## 🤖 Models Used

### 1. Decision Tree
- F1-Score: 39.38%

### 2. Random Forest
- F1-Score: 65.11%

### 3. Convolutional Neural Network (CNN)
- Accuracy: 85.63%
- Precision: 87.16%
- Recall: 85.63%
- F1-Score: 85.57%

The CNN achieved the best performance and was selected as the final model.

---

## 🛠 Technologies & Libraries

- Python
- TensorFlow / Keras
- Scikit-learn
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Gradio

---

## 🚀 Application Features

- Upload a plant leaf image
- AI-based disease prediction
- Confidence score display
- Health status indication
- Disease information and recommendations

---

## 📈 Results

The CNN model significantly outperformed the traditional machine learning models due to its ability to automatically learn image features and patterns.

| Model | Accuracy |
|---------|---------|
| CNN | 85.63% |
| Random Forest | 67.78% |
| Decision Tree | 39.24% |

---

## 👩‍💻 Author

Leen Alhossan

Computer Science
