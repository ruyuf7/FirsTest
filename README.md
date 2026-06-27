# Iris Species Classification using Linear Discriminant Analysis (LDA) and Logistic Regression

## Overview

This project implements a complete machine learning workflow to classify Iris flower species using the famous Iris dataset from the UCI Machine Learning Repository.

The project covers data preprocessing, exploratory data analysis (EDA), dimensionality reduction using Linear Discriminant Analysis (LDA), and classification using Logistic Regression. Model performance is evaluated using Accuracy Score and a Confusion Matrix.

---

## Dataset

**Dataset:** Iris Dataset

Source:
https://archive.ics.uci.edu/ml/datasets/iris

The dataset contains **150 samples** of Iris flowers belonging to three different species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

Each sample includes four numerical features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## Project Workflow

### 1. Import Libraries

The following Python libraries are used:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

### 2. Data Loading

The dataset is loaded directly from the UCI repository using Pandas.

---

### 3. Data Preprocessing

- Feature extraction
- Label encoding of target classes
- Train/Test split

---

### 4. Exploratory Data Analysis (EDA)

Several visualizations are generated to better understand the dataset:

- Pair Plot
- Feature Histograms
- Correlation Heatmap

These visualizations help identify:

- Relationships between features
- Feature distributions
- Correlations among numerical variables

---

### 5. Dimensionality Reduction

Linear Discriminant Analysis (LDA) is applied to reduce the four original features into two linear components while maximizing class separability.

The transformed data is visualized using a scatter plot.

---

### 6. Model Training

A Logistic Regression classifier is trained using the LDA-transformed training data.

---

### 7. Model Evaluation

The trained model is evaluated using:

- Accuracy Score
- Confusion Matrix

Example result:

```
Accuracy: 0.93
```

This indicates that the model correctly classified approximately **93%** of the test samples.

---

## Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Techniques

- Label Encoding
- Train/Test Split
- Linear Discriminant Analysis (LDA)
- Logistic Regression
- Classification Metrics

---

## Project Structure

```
Iris-Classification/
│
├── Iris_Classification.ipynb
├── README.md
└── requirements.txt
```

---

## Results

The project demonstrates that applying Linear Discriminant Analysis before Logistic Regression produces a highly accurate classifier for the Iris dataset.

Performance achieved:

- Accuracy: **93%**

Visualization outputs include:

- Pair Plot
- Histograms
- Correlation Heatmap
- LDA Scatter Plot
- Confusion Matrix

---

## Future Improvements

- Compare LDA with PCA.
- Test additional classifiers such as:
  - Random Forest
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
  - Decision Tree
- Perform hyperparameter tuning.
- Apply cross-validation for more robust evaluation.

---

## Author

Developed as part of a Machine Learning project focusing on classification, dimensionality reduction, and data visualization.
