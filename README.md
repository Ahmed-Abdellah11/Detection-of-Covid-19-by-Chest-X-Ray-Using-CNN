#  COVID-19 Detection from Chest X-Rays Using CNN

A deep learning project that classifies chest X-ray images to detect COVID-19, Viral Pneumonia, and Normal cases — achieving **98.33% accuracy** and **98% F1 Score** with VGG-16.

---

## 📌 Overview

Timely and accurate COVID-19 diagnosis saves lives. This project automates chest X-ray classification using a fine-tuned VGG-16 model, providing a fast, scalable diagnostic support tool based on 1,709 real clinical X-ray images.

**Classes:** COVID-19 · Viral Pneumonia · Normal

---

## 📊 Results

| Metric | Score |
|--------|-------|
| Accuracy | **98.33%** |
| F1 Score | **98%** |
| Model | VGG-16 (Transfer Learning) |

---

## 🏗️ Approach

- **Architecture:** VGG-16 pre-trained on ImageNet, fine-tuned for 3-class classification
- **Data Augmentation:** Rotation, flipping, zoom — to handle the small dataset size (1,709 images)
- **Preprocessing:** Resizing, normalization, train/val/test split
- **Evaluation:** Accuracy, F1 Score, Confusion Matrix, Classification Report

---

## 🗂️ Dataset

**1,709 posteroanterior (PA) chest X-ray images** collected from multiple research sources and used in the COVID Lite research paper.

| Class | Description |
|-------|-------------|
| COVID-19 | X-rays from confirmed COVID-19 patients |
| Viral Pneumonia | X-rays from non-COVID viral pneumonia patients |
| Normal | Healthy chest X-rays |

---

## 🛠️ Tech Stack

`Python` · `TensorFlow` · `Keras` · `OpenCV` · `scikit-learn` · `NumPy` · `Matplotlib`

---

## 🚀 How to Run

```bash
git clone https://github.com/Ahmed-Abdellah11/Detection-of-Covid-19-by-Chest-X-Ray-Using-CNN.git
jupyter notebook detection-of-covid-19-by-chest-x-ray-using-cnn.ipynb
```

---

## 📁 Project Structure

```
├── detection-of-covid-19-by-chest-x-ray-using-cnn.ipynb  # Full pipeline
└── README.md
```

---

## 👤 Author

**Ahmed Abdellah Ismail** — AI Engineer  
[GitHub](https://github.com/Ahmed-Abdellah11) · [Kaggle](https://kaggle.com/ahmedabdellahismail) · [LinkedIn](https://linkedin.com/in/ahmed-abdellah11)
