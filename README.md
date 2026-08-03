# ♻️ Waste Image Classification using ResNet50

A deep learning project for classifying waste images into three categories—**Recyclable**, **Electronic**, and **Organic**—using **Transfer Learning** with **ResNet50**. This project applies **Adaptive Gaussian Bilateral Filter (AGBF)** for image preprocessing and fine-tuning to improve classification performance.

---

## 📌 Overview

Proper waste classification is an important step in supporting efficient recycling and waste management. This project develops an image classification model capable of recognizing three waste categories by leveraging a pretrained ResNet50 model and image preprocessing techniques.

---

## ✨ Features

- Image preprocessing using **Adaptive Gaussian Bilateral Filter (AGBF)**
- Transfer Learning with **ResNet50**
- Fine-Tuning pretrained layers
- Data Augmentation
- Mixed Precision Training
- Model Checkpoint for saving the best model
- Prediction on unseen test images

---

## 🛠️ Technologies

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-learn

---

## 📂 Project Structure

```
waste-classification-resnet50/
│
├── dataset/
│   ├── train/
│   ├── test/
│   └── sample_submission.csv
│
├── models/
│   └── best_model.keras
│
├── notebooks/
│   └── Waste_Classification_ResNet50.ipynb
│
├── images/
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📊 Model Performance

Validation Results

| Metric | Score |
|---------|-------|
| Accuracy | 95.78% |
| Precision | 95.78% |
| Recall | 95.78% |
| F1-Score | 95.78% |

> These results were obtained on the validation dataset used in this project and may vary on different datasets.

---

## Evaluation Results

The detailed evaluation metrics are available in:

- `classification_report.txt`

---  

## 🚀 How to Run

1. Clone this repository

```bash
git clone https://github.com/yourusername/waste-classification-resnet50.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Prepare the dataset inside the `dataset` folder.

4. Open the notebook and run all cells.

---

## 📁 Dataset

The dataset used in this project is **not included** in this repository due to its size.

Please place the dataset in the following structure:

```
dataset/
│
├── train/
└── test/
```

---

## 👤 Author

**Nadhira Haura Ramadhani**

Information Systems Student | Universitas Indraprasta PGRI

LinkedIn: *(linkedin.com/in/nadhirahr88)*
