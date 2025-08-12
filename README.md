# 🫁 Pneumonia Detection using Deep Learning

## 📌 Project Overview
This project focuses on building a **Deep Learning-based Pneumonia Detection System** that classifies chest X-ray images into **Pneumonia** or **Normal** categories. It leverages Convolutional Neural Networks (CNNs) to automatically extract features and provide accurate predictions for early diagnosis.

---

## 🎯 Objectives
- To assist radiologists in detecting pneumonia from chest X-ray images.
- To build a robust, automated, and accurate pneumonia classification model.
- To reduce diagnostic delays and support better healthcare decisions.

---

## 🛠️ Tech Stack
- **Programming Language:** Python
- **Frameworks & Libraries:** TensorFlow, Keras, NumPy, Pandas, Matplotlib, OpenCV
- **Dataset:** Chest X-ray dataset from Kaggle (Pneumonia vs Normal images)

---

## 📂 Dataset
- **Source:** [Kaggle - Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
- **Classes:** Pneumonia / Normal
- **Preprocessing Steps:**
  - Image resizing to uniform dimensions.
  - Normalization for faster convergence.
  - Data augmentation (rotation, flipping, zoom) to avoid overfitting.

---

## ⚙️ Methodology
1. **Data Collection & Preprocessing**
   - Download dataset.
   - Apply augmentation and normalization.
2. **Model Design**
   - CNN architecture with convolutional, pooling, and dropout layers.
3. **Training & Validation**
   - Model trained with binary cross-entropy loss and Adam optimizer.
4. **Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC.
5. **Prediction**
   - Predicts pneumonia presence from new X-ray images.

---

## 📊 Results
- **Training Accuracy:** 98%
- **Validation Accuracy:** 96%
- **F1-Score:** 0.95
- **ROC-AUC:** 0.97

---

## 📌 How to Run
```bash
# Clone the repository
git clone https://github.com/yourusername/pneumonia-detection.git

# Navigate to project directory
cd pneumonia-detection

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Pneumonia_Detection.ipynb
