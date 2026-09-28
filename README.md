# 🐱🐶 Cat vs Dog Image Classification using SVM

## 📌 Project Overview

This project implements a **Support Vector Machine (SVM)** to classify images into two categories: **Cats 🐱 and Dogs 🐶**. The project demonstrates the complete machine learning workflow, including image preprocessing, feature extraction, model training, testing, prediction, and accuracy evaluation.

## 🎯 Objective

* Classify images as **Cat** or **Dog**
* Preprocess and resize images
* Convert images into numerical features
* Train an SVM classifier
* Evaluate model accuracy
* Predict new images

## 🛠️ Technologies Used

* Python
* NumPy
* OpenCV
* Matplotlib
* Scikit-learn
* Google Colab

## 🔄 Workflow

```text
Images
   ↓
Image Preprocessing
   ↓
Resize Images
   ↓
Feature Extraction
   ↓
Train/Test Split
   ↓
SVM Training
   ↓
Prediction
   ↓
Accuracy Evaluation
```

## 🧠 Algorithm

### Support Vector Machine (SVM)

SVM is a supervised machine learning algorithm used for classification. It finds a decision boundary that separates different classes of data.

In this project:

```text
0 → Cat 🐱
1 → Dog 🐶
```

## 📊 Model Evaluation

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Classification Report

## 🚀 How to Run

1. Open the project in **Google Colab**.
2. Install/import the required libraries.
3. Load and preprocess the images.
4. Split the data into training and testing sets.
5. Train the SVM model.
6. Run predictions.
7. Check the classification accuracy.

## 📁 Project Structure

```text
Cat-Dog-SVM/
│
├── README.md
├── cat_dog_svm.ipynb
└── images/
```

## 📌 Result

The trained SVM model predicts whether an input image belongs to the **Cat** or **Dog** class and provides performance metrics for evaluation.

## 👨‍💻 Author

**Sohil Pasha**

---

> **Note:** If you are using the synthetic/no-dataset version we created earlier, change the dataset section to explicitly say **“Synthetic image data generated using Python”** rather than claiming that the Kaggle dataset was used.
