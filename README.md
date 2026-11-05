# Network Protocol Classification Using Machine Learning

## 1. Project Overview

This project focuses on classifying network protocols using Machine Learning algorithms.

The main objective is to predict the network protocol (such as TCP, UDP, QUIC, etc.) based on network packet information.

Machine Learning classification algorithms are used to train models and compare their performance.

## 2. Objectives

- Understand and analyse network packet data.
- Clean and preprocess the dataset.
- Explore the distribution of different network protocols.
- Apply Machine Learning classification algorithms.
- Evaluate and compare model performance.
- Predict the protocol of a new network packet.

## 3. Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## 4. Dataset Description

The project uses network packet data from the provided dataset archive.

The dataset contains information such as:

- Time
- Source
- Destination
- Protocol
- Length
- Info

The project initially works with a sample of up to 100,000 records to make data processing easier.

The dataset is cleaned and prepared before training the Machine Learning models.

**Note:** The original dataset is not included in this public repository. Upload the dataset separately when running the notebook in Google Colab.

## 5. Data Preprocessing

The following preprocessing steps are performed:

- Loading the dataset.
- Checking dataset information and dimensions.
- Handling missing values.
- Removing duplicate records.
- Analysing protocol distribution.
- Extracting Hour, Minute and Second from the Time column.
- Selecting relevant features.
- Encoding protocol labels.
- Splitting the dataset into training and testing sets.

## 6. Machine Learning Algorithms

The following classification algorithms are implemented:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree
4. Random Forest

The models are trained and evaluated to compare their classification performance.

## 7. Model Evaluation

The project uses the following evaluation techniques:

- Accuracy Score
- Classification Report
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Model Accuracy Comparison
- Feature Importance

The actual performance results depend on the dataset and experimental setup.

## 8. Project Workflow

1. Load the dataset.
2. Understand the data.
3. Clean the dataset.
4. Perform Exploratory Data Analysis (EDA).
5. Extract useful features.
6. Encode the target variable.
7. Split the dataset.
8. Train Machine Learning models.
9. Evaluate model performance.
10. Compare the models.
11. Predict the protocol of a new packet.

## 9. How to Run the Project

This project is designed to run in Google Colab.

1. Open [Google Colab](https://colab.research.google.com/).
2. Upload or open the project notebook.
3. Run the library installation and import cells.
4. Upload the original dataset ZIP when requested.
5. Execute the notebook cells in order.
6. View the data visualizations, evaluation results and predictions.

## 10. Project Outputs

The notebook generates:

- Dataset analysis and visualizations.
- Protocol distribution chart.
- Packet length analysis.
- Machine Learning model comparison.
- Confusion matrix.
- Classification reports.
- Feature importance visualization.
- New packet protocol prediction.

Depending on the notebook version, trained model and result files may also be saved.

## 11. Conclusion

This project demonstrates how Machine Learning can be used for network protocol classification.

By implementing and comparing multiple classification algorithms, the project provides practical experience in data preprocessing, exploratory data analysis, model training, evaluation and prediction.

## 12. Author

**Ankana Debnath**

BCA Student

Project: Network Protocol Classification Using Machine Learning
