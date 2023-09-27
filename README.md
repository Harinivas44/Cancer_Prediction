
# Cancer Prediction 🩺

## Overview

Predicting whether a patient has cancer or not is crucial for timely diagnosis and treatment. This project utilizes machine learning to predict cancer based on various medical features. 📊🔬

This project aims to predict cancer using a dataset of medical attributes. It employs the K-Nearest Neighbors algorithm to classify patients into two categories: benign (B) and malignant (M). The dataset contains essential medical information such as radius, texture, perimeter, area, and more.




# Data Preprocessing 🧹

The initial data preprocessing steps include:

* Dropping the 'id' column as it is not relevant for prediction.

* Converting the 'diagnosis' column to categorical data.

* Scaling the feature data to ensure uniformity.

# Exploratory Data Analysis 📈

Understanding the data is essential. A heatmap is plotted to visualize the correlation between various attributes, helping identify potential patterns in cancer diagnosis.

# Model Training 🤖

The K-Nearest Neighbors (KNN) algorithm is chosen for classification. It's a simple yet effective algorithm for this binary classification task. The model is trained with 5 neighbors and weighted by distance.

# Model Evaluation 🧐

The trained model is used to make predictions on a test dataset. The results are compared to the actual diagnoses to evaluate the model's performance.

# Conclusion 🏁

This project provides a simple yet effective way to predict cancer based on medical attributes. It serves as a valuable tool for healthcare professionals in the early diagnosis of cancer cases. 🌟
## 🔗 Links
[![portfolio](https://img.shields.io/badge/view_my_notebook-000?style=for-the-badge&logo=github&logoColor=white)](https://nbviewer.org/github/Harinivas44/Cancer_Prediction/blob/main/KNN.ipynb)
