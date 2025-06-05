# Breast-Cancer-logistic-Regression
**🧠 Breast Cancer Prediction using Logistic Regression**
This project is a machine learning implementation for predicting breast cancer using Logistic Regression, based on the Breast Cancer Wisconsin Diagnostic Dataset. It aims to classify tumors as malignant (M) or benign (B) using key features derived from digitized images of fine needle aspirates of breast masses.

**📌 Overview**
    **Algorithm:** Logistic Regression
    **Goal:** Classify tumors as malignant or benign
    **Dataset:** sklearn.datasets.load_breast_cancer
    **Labels:**
    M → Malignant (converted to 1)
    B → Benign (converted to 0)

**🔍 Project Workflow**
**Data Loading and Exploration**
**Preprocessing**
  Label Encoding (M → 1, B → 0)
  Feature Scaling with StandardScaler
**Train-Test Split**
  Model Training using Logistic Regression
**Model Evaluation**
  Accuracy
  Confusion Matrix
  Classification Report
**Threshold Tuning**
**Sigmoid Function Visualization**

**📊 Evaluation Metrics**
  Confusion Matrix
  Accuracy Score
  Precision, Recall, F1-score
  Visual Heatmap of Confusion Matrix
  Sigmoid Curve
  
**📈 Visualizations**
    Heatmap of the confusion matrix using Seaborn
    Sigmoid function curve to explain decision boundary
    Threshold tuning example

**🛠️ Technologies & Libraries Used**
  Python
  NumPy
  Pandas
  Matplotlib
  Seaborn
  Scikit-learn
