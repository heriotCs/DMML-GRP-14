# DMML-GRP-14  
### Indoor Plant Health & Growth Prediction  
*Data Mining and Machine Learning Coursework*

---

## 🧠 Project Overview
This project focuses on predicting indoor plant health and growth using both **tabular** (sensor-based) and **image** (visual) datasets.  
We apply a variety of machine learning and deep learning techniques to analyze, cluster, and model plant health indicators.

The project explores the full ML pipeline - from **EDA and preprocessing**, to **clustering**, **baseline modeling**, and **neural networks**.

---

## 🧾 Notebook Structure

### 🧩 1. EDA and Preprocessing (R2)
**Folder:** [`R2_EDA_Preprocessing`](R2_EDA_Preprocessing/)  
- **Tabular:** Data cleaning, feature selection, outlier removal, normalization.  
- **Image:** .  
- **Goal:** Prepare both datasets for clustering and modeling.

---

### 🔍 2. Clustering (R2)
**Folder:** [`R2_Clustering`](R2_Clustering/)  
- **Tabular:** K-Means Models applied to sensor data.  
- **Image:**  
- **Goal:** Identify natural groups or patterns in plant conditions.

---

### 📊 3. Baseline Models (R3)
**Folder:** [`R3_Baseline_Models`](R3_Baseline_Models/)  
- **Tabular Models:** Logistic Regression, Decision Tree, KNN.  
- **Image Models:** Decision Trees, Naive Bayes, KNN.  
- **Goal:** Evaluate baseline model performance before deep learning.

---

### 🤖 4. Neural Networks (R4)
**Folder:** [`R4_Neural_Networks`](R4_Neural_Networks/)   

---

### 🗄 5. Archive
**Folder:** [`Archive`](Archive/)  
Contains older versions of datasets and notebooks retained for reference.

---

## 📂 Datasets
**Folder:** [`Datasets`](Datasets/)  
- **Tabular Dataset:** Indoor sensor readings (temperature, humidity, soil moisture, etc.).  
- **Image Dataset:** Labeled plant images with various health conditions.

---

## 👥 Group Members
| Name | Role / Contribution |
|------|---------------------|
| **Muhammad Saad** | R2 - Clusteing & Preprocessing of Tabular Datatset, R3 - Baseline Models for Tabular Dataset|
| **Sharaf** | |
| **Sufyaan** | |
| **Hassan** | |
| **Abdullah** | |

---

## 🧩 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/heriotCs/DMML-GRP-14.git
2. Navigate to the Project Directory
   ```bash
   cd DMML-GRP-14
3.	Open the notebooks in Jupyter or VS Code and run them in order:
• R2_EDA_Preprocessing
• R2_Clustering
• R3_Baseline_Models
• R4_Neural_Networks
