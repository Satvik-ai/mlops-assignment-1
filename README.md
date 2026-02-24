# 🌸 Iris Classification ML Project (Vertex AI)

This project implements an **end-to-end machine learning pipeline** for classifying Iris flower species using **Google Cloud Platform (GCP) Vertex AI**.  
It demonstrates the full lifecycle of an ML model — from data retrieval and training to deployment and inference.

The repository is designed to showcase practical experience with **cloud-based ML workflows**, reproducible pipelines, and model serving.

---

## 📌 Project Overview

The objective of this project is to build a classification model that predicts the species of an Iris flower based on its features.

The workflow includes:

1. Data retrieval from **Google Cloud Storage (GCS)**
2. Model training and evaluation  
3. Model storage and deployment  
4. Running inference on unseen data  

---

## 🗂️ Repository Structure

```
├── Iris_Classification_ML_Training_Pipeline.ipynb # Training + deployment pipeline
├── Inference.ipynb # Inference workflow
└── README.md # Project documentation
```

---

## 📁 Files Description

### 1️⃣ Iris_Classification_ML_Training_Pipeline.ipynb

**Purpose:**  
Implements the training and deployment pipeline.

**Key Steps:**

- Loads the Iris dataset from a GCS bucket  
- Performs preprocessing and model training  
- Evaluates model performance  
- Uploads the trained model artifact to GCS  
- Prepares the model for deployment on Vertex AI  

---

### 2️⃣ Inference.ipynb

**Purpose:**  
Runs predictions using the trained model.

**Key Steps:**

- Retrieves dataset from GCS  
- Creates train–test split  
- Downloads and loads the trained model  
- Performs predictions on test data  
- Evaluates inference results  

---

## ⚙️ Tech Stack

- Python  
- Jupyter Notebook  
- Scikit-learn  
- Google Cloud Platform (GCP)
  - Vertex AI  
  - Cloud Storage  

---

## 🎥 Video Presentation  
[▶️ Click Here](https://drive.google.com/file/d/1KykcSTpzdW-mQ6WkBKMx3iWu6J81MX7k/view?usp=drive_link)
