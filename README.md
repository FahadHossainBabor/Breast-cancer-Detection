# Breast Cancer Classification using Gaussian Naive Bayes

## 📌 Project Overview
This project implements a machine learning model to classify breast tumors as either **Malignant** or **Benign**. Using the Breast Cancer Wisconsin (Diagnostic) dataset, the model analyzes 30 clinical features to provide highly accurate predictions.

## 📊 Dataset Details
* **Source:** Scikit-learn built-in Breast Cancer dataset.
* **Instances:** 569.
* **Features:** 30 numerical features including mean radius, texture, perimeter, and area.
* **Target Classes:** * `0`: Malignant
    * `1`: Benign

## 🛠️ Technical Implementation
* **Language:** Python.
* **Libraries:** `pandas`, `numpy`, `scikit-learn`, `seaborn`, `matplotlib`.
* **Model:** Gaussian Naive Bayes (`GaussianNB`).
* **Data Split:** 80% Training and 20% Testing (`random_state=42`).

## 📈 Performance Results
The model demonstrated strong diagnostic performance on the test set:
* **Accuracy:** 97.37%.
* **Malignant Class:** 1.00 Precision and 0.93 Recall.
* **Benign Class:** 0.96 Precision and 1.00 Recall.



## 🚀 GitHub Deployment Instructions

To upload this project to your GitHub repository, follow these steps:

1. **Initialize Git:**
   ```bash
   git init

```

2. **Add Project Files:**
```bash
git add 2103114_source_code.ipynb README.md

```


3. **Commit Changes:**
```bash
git commit -m "Initial commit: Breast Cancer Classification with 97% Accuracy"

```


4. **Push to GitHub:**
```bash
git remote add origin [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
git branch -M main
git push -u origin main

```



---

**Author:** Fahad Hossain
**Affiliation:** RUET (Computer Science and Engineering)
