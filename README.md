# Electricity Fraud Detection Using Machine Learning
This project aims to **detect electricity theft** based on consumption patterns **using machine learning models**. The dataset is sourced from **Smart Grid Corporation China**, and various models have been tested to find the most accurate and efficient approach. The 1D CNN model provided the best results in terms of accuracy **(95.41%)** and performance.

# Table of Contents
- [Introduction](https://github.com/FariaParvinMegha/Electricity_fraud/blob/main/README.md#introduction)
- [Dataset](https://github.com/FariaParvinMegha/Electricity_fraud/blob/main/README.md#dataset)
- [Models Tested](https://github.com/FariaParvinMegha/Electricity_fraud/blob/main/README.md#models-tested)
- [Results](https://github.com/FariaParvinMegha/Electricity_fraud/blob/main/README.md#results)
- [Installation](https://github.com/FariaParvinMegha/Electricity_fraud/blob/main/README.md#installation)
- [Usage](https://github.com/FariaParvinMegha/Electricity_fraud/blob/main/README.md#installation)

# Introduction
Electricity theft is a significant issue that leads to energy losses and affects utility companies' operations and profitability. This project leverages machine learning to detect patterns in electricity consumption that may indicate theft. Multiple models were tested to determine the most effective approach, with 1D CNN yielding the highest accuracy.

# Dataset
The dataset for this project is provided by **Smart Grid Corporation China**. It contains consumption data and features relevant to identifying irregular usage patterns that may signify theft.

# Models Tested
The following models were implemented and tested to compare their effectiveness:
- Artificial Neural Network (ANN)
- 1D Convolutional Neural Network (1D CNN)
- 2D Convolutional Neural Network (2D CNN)
- Random Forest (RF)
- Decision Tree (DT)
- Support Vector Machine (SVM)
- XGBoost
After testing and comparing each model, 1D CNN was found to deliver the best results **(95.41% acuuracy)** in terms of both accuracy and computational efficiency.

# Results
The 1D CNN model demonstrated the highest accuracy and efficiency among all tested models, making it the most suitable for this application. It effectively detects patterns in consumption data that are indicative of theft, providing utility companies with a valuable tool to mitigate losses and enhance security.

# Installation
## Requirements
- Python 3.x
- Jupyter Notebook, Google Colab or any preferred IDE
- run the codes cellwise
# Usage
- Load the Dataset: Import the dataset from Smart Grid Corporation China into the working directory.
- Run Model Comparisons: Execute the notebook or script to train and test each model on the dataset.
- Evaluate Results: Compare the accuracy and performance of each model to verify the effectiveness of the 1D CNN model.
