# FittLyf Data Science Intern Assessment

This repository contains the solution to the FittLyf Data Science Intern Assessment. The notebook `Proccesing_FittLyf_Data_Science_Intern_Assessment.ipynb` includes exploratory data analysis, principal component analysis, time series forecasting, clustering, and anomaly detection. The aim is to analyze the productivity of workers and detect fraudulent transactions using various machine learning techniques.

## Table of Contents
- [Overview](#overview)
- [Data](#data)
- [Tasks and Analysis](#tasks-and-analysis)
- [Setup Instructions](#setup-instructions)
- [Results](#results)
- [Improvements](#improvements)
- [Conclusion](#conclusion)

## Overview
This project is an end-to-end analysis covering multiple aspects of data science. The key sections of the notebook include:
1. **Data Import and Exploration**: Initial data loading and exploratory analysis.
2. **Data Cleaning**: Handling missing values and preparing the data for further analysis.
3. **Principal Component Analysis (PCA)**: Dimensionality reduction to identify the most significant features.
4. **Predictive Modeling and Time Series Analysis**: Using ARIMA for time series forecasting of productivity.
5. **Clustering Analysis**: Segmentation of workers based on their productivity using K-Means clustering.
6. **Anomaly Detection**: Identifying fraudulent transactions using Isolation Forest.

## Data
The data used in this analysis is provided in an Excel file named `AssignmentData.xlsx`. The file contains three sheets:
- `WorkerFunnel`: Details of a garment manufacturing process and worker productivity over 70 days.
- `creditcard`: Credit card transactions used for anomaly detection.
- `creditcard_test`: A separate test set for evaluating the anomaly detection model.

## Tasks and Analysis
### 1. Funnel Analysis
- **Objective**: Understand the productivity of workers.
- **Methods**: PCA, ARIMA, K-Means clustering.
- **Outcome**: Insights into productivity dynamics and worker segmentation.

### 2. Anomaly Detection
- **Objective**: Detect fraudulent transactions.
- **Methods**: Isolation Forest, ROC-AUC, Precision, Recall, F1-Score.
- **Outcome**: Identification and analysis of potential frauds.

## Setup Instructions
### Prerequisites
- Python 3.x
- Jupyter Notebook or Google Colab
- Required Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `statsmodels`

### Running the Notebook
1. Clone the repository:
    ```bash
    git clone https://github.com/himanshugitcode/FittLyf_Data_Science_Assessment.git
    cd FittLyf_Data_Science_Assessment
    ```
2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Open the notebook:
    ```bash
    jupyter notebook Proccesing_FittLyf_Data_Science_Intern_Assessment.ipynb
    ```
4. Run the cells in sequence to replicate the analysis.

## Results
The notebook provides detailed results including:
- PCA component analysis.
- Time series forecasting with ARIMA.
- Worker clustering visualizations.
- Anomaly detection performance metrics.

## Improvements
Several improvements were made in the anomaly detection section to enhance the performance of the Isolation Forest model. Additional evaluation metrics and visualizations were included to better interpret the results.

## Conclusion
This notebook successfully demonstrates various data science techniques, providing actionable insights and identifying fraudulent activities in credit card transactions.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
