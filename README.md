# 24CSEN2161P - Machine Learning Laboratory

This repository contains all laboratory experiments, Jupyter Notebooks, datasets, and documentation completed as part of the **Machine Learning Laboratory (24CSEN2161P)** coursework during **Semester 5**.

---

## 📚 Repository Overview

The coursework focuses on practical implementations of core machine learning paradigms, spanning exploratory data analysis, data pre-processing, feature scaling, regression modeling, classification techniques, unsupervised clustering algorithms, and dimensionality reduction using Principal Component Analysis (PCA).

A comprehensive documentation report covering aims, algorithms, source code, and outputs is available in [`ML LAB EXPERIMENTS DOCUMENTATION.docx`](./ML%20LAB%20EXPERIMENTS%20DOCUMENTATION.docx).

---

## 🧪 Experiments Index

| Exp # | Experiment Title | Key Techniques / Algorithms | Dataset | Notebook |
|:---:|:---|:---|:---|:---:|
| **01** | Iris Data Pre-processing | Data Cleaning, Missing Value Handling, Correlation Matrix & Heatmaps | Iris Dataset | [`ML_1.ipynb`](./ML_1.ipynb) |
| **02** | Titanic Data Preparation | Categorical Encoding (One-Hot), Feature Imputation & Scaling | Titanic Dataset | [`ML_2.ipynb`](./ML_2.ipynb) |
| **03** | Player Sold Price Prediction | Train-Test Split, Linear Regression Modeling, RMSE Evaluation | IPL 2013 Dataset | [`ML_3.ipynb`](./ML_3.ipynb) |
| **04** | Credit Risk Classification | Classification Modeling, Confusion Matrix & Accuracy Metrics | German Credit Dataset | [`ML_4.ipynb`](./ML_4.ipynb) |
| **05** | Glass Type Classification | Random Forest vs. KNN vs. Naïve Bayes Classifier Comparison | Glass Identification Dataset | [`ML_5.ipynb`](./ML_5.ipynb) |
| **06** | Hierarchical Clustering | Agglomerative Clustering, Dendrograms, Euclidean Distance Linkages | Online Retail Dataset | [`ML_6.ipynb`](./ML_6.ipynb) |
| **07** | Customer Segmentation via K-Means | RFM Analysis, Elbow Method, SSD (Inertia) Optimization | Online Retail Dataset | [`ML_7.ipynb`](./ML_7.ipynb) |
| **08** | Density-Based Clustering (DBSCAN) | DBSCAN Clustering, Epsilon ($\epsilon$) & MinPts Parameter Tuning | Mall Customers Dataset | [`ML_8.ipynb`](./ML_8.ipynb) |
| **09** | Principal Component Analysis on Iris | Dimensionality Reduction, Variance Explainability (2D vs. 3D PCs) | Iris Dataset | [`ML_9.ipynb`](./ML_9.ipynb) |
| **10** | Normalization & Feature Scaling | MinMaxScaler, StandardScaler, RobustScaler Comparison | Wine Quality (Red) Dataset | [`ML_10.ipynb`](./ML_10.ipynb) |
| **11** | PCA & 2D Projection on Wine Quality | Feature Standardization, Eigen Decomposition, 2D Visualization | Wine Quality (Red) Dataset | [`ML_11.ipynb`](./ML_11.ipynb) |

---

## 📁 Repository Structure

```text
24CSEN2161P-Machine-Learning-Lab/
├── ML LAB EXPERIMENTS DOCUMENTATION.docx   # Complete lab documentation report
├── README.md                              # Repository overview and index
├── ML_1.ipynb                             # Experiment 1: Iris Pre-processing
├── ML_2.ipynb                             # Experiment 2: Titanic Data Prep
├── ML_3.ipynb                             # Experiment 3: IPL Price Regression
├── ML_4.ipynb                             # Experiment 4: German Credit Classification
├── ML_5.ipynb                             # Experiment 5: Glass Identification Classifiers
├── ML_6.ipynb                             # Experiment 6: Hierarchical Clustering
├── ML_7.ipynb                             # Experiment 7: K-Means Customer Segmentation
├── ML_8.ipynb                             # Experiment 8: DBSCAN Clustering
├── ML_9.ipynb                             # Experiment 9: PCA on Iris
├── ML_10.ipynb                            # Experiment 10: Normalization Techniques
├── ML_11.ipynb                            # Experiment 11: PCA on Wine Quality
└── datasets/                              # Datasets used across all experiments
    ├── cleaned_titanic.csv
    ├── german_credit_data.csv
    ├── glass.csv
    ├── IPL IMB381IPL2013.csv
    ├── Iris.csv
    ├── Mall_Customers.csv
    └── winequality-red.csv
```

---

## 🛠️ Tools & Libraries

- **Language:** Python 3.x
- **Environment:** Jupyter Notebook / Google Colab
- **Libraries:**
  - `numpy` & `pandas`: Data manipulation and feature engineering
  - `scikit-learn`: Supervised and unsupervised machine learning algorithms
  - `scipy`: Hierarchical clustering and linkage matrices
  - `matplotlib` & `seaborn`: Data visualization, correlation heatmaps, and cluster plots
