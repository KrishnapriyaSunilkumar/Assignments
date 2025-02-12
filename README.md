# Assignments
 focused on Git, GitHub, and ML
# Breast Cancer Classification Using Random Forest

## Overview
This project implements a **Random Forest Classifier** to predict whether a tumor is **benign** or **malignant** using the **Breast Cancer Wisconsin Diagnostic** dataset. The dataset is loaded from `sklearn.datasets`, and the model is trained and evaluated for performance.

## Dataset
- The dataset consists of **30 numerical features** extracted from **digitized images of breast mass samples**.
- The target variable:
  - `0` → Benign (Non-cancerous)
  - `1` → Malignant (Cancerous)

## Model and Methodology
- The dataset is split into **training (80%)** and **testing (20%)** sets.
- **Standardization** is applied using `StandardScaler` for better model performance.
- A **Random Forest Classifier** is trained with:
  - `n_estimators=100` (100 decision trees)
  - `random_state=42` for reproducibility
- Performance is evaluated using:
  - **Accuracy Score**
  - **Confusion Matrix**
  - **Classification Report** (Precision, Recall, F1-score)

## Installation
To run the model, install the required dependencies:

```bash
pip install -r requirements.txt
