# Breast Cancer Prediction using KNN and K-Means
In this project, i worked with the Breast Cancer dataset to identify whether a given tumor is **Benign (0)** or **Malignant (1)**.  
The main goal was to apply basic machine learning steps and use two algorithms: **K-Means** and **KNN**.
---
## Steps i Followed

### 1. Dataset Preparation
- Loaded the dataset inside Google Colab.
- Removed two columns that were not needed: `id` and `Unnamed: 32`.
- Converted the diagnosis values so the model can understand them easily:
  - M → 1  
  - B → 0
--

### 2. Preprocessing
- Separated the data into:
  - **X** (all features)
  - **y** (diagnosis)
- Applied **Min-Max Scaling** to bring all feature values into the same range.
- Split the data into:
  - **80% training data**
  - **20% testing data**
---
### 3. K-Means Clustering (k = 2)
- Used K-Means to divide the dataset into 2 groups.
- Since K-Means is unsupervised, it clusters based on similarities.
- Compared the cluster results with the actual diagnosis using a confusion matrix.
---
### 4. KNN Classification (k = 5)
- Trained a KNN model using the training data.
- Used **k = 5** neighbors.
- Made predictions on the test data.
---
### 5. Evaluation
Printed these scores:
- Accuracy  
- Precision  
- Recall  
- F1 Score  

Each shows how well the model predicted cancer types.

## Summary
- K-Means gives an idea of natural grouping.
- KNN works well for diagnosis prediction.
- Scaling and proper splitting helped improve performance.

## Files
- Dataset  
- Notebook with all code  
- README


---

## Summary
- K-Means clustering gives
