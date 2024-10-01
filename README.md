# Unsupervised Learning and Dimensionality Reduction

## Introduction
This repository contains code for performing dimensionality reduction and clustering on datasets using various techniques such as PCA, t-SNE, KMeans, and GMM. Dimensionality reduction is a crucial step in data preprocessing, aiming to reduce the number of features while preserving important information. Clustering algorithms help identify natural groupings or clusters within the data, aiding in exploratory data analysis and classification tasks.

## Dependencies
Before running the code, make sure to install the required library using the following command:

```bash
pip install scikit-learn
```
```bash
pip install pandas
```
```bash
pip install numpy
```
```bash
pip install matplotlib
```

## Datasets

1. **Breast Cancer Dataset:**
   - Dataset file imported from Internet: sklearn.datasets.load_breast_cancer
   - Features (`X_cancer`): All columns except the first one
   - Labels (`y_cancer`): 'M' (Malignant) or 'B' (Benign)
  
2. **Wine Quality Dataset:**
   - Dataset file imported from Internet: https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-white.csv
   - Features (X_wine): All columns except the last one
   - Labels (y_wine): Quality Group (categorized as ‘Bad’ or ‘Good’)


## Usage

1. Open the Jupyter Notebook ([`UL_Assignment3.ipynb`](UL_Assignment3.ipynb)) in a compatible environment (e.g., Google Colab).
2. No need to adjust the file paths for the datasets, already imported from Internet.
3. Run the cells sequentially to execute the code and observe the results.
