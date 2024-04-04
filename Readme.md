# Customer Churn Prediction & Factors Identification Using Data Mining and Explainable AI

This repository contains the code for my undergraduate Capstone Project. The project aims to predict customer churn and identify the factors contributing to it using data mining techniques and Explainable AI.

## Project Overview

This project focuses on predicting customer churn, which is a critical issue for many businesses. By accurately predicting which customers are likely to churn, businesses can proactively take steps to improve customer retention. In addition to predicting churn, this project also aims to identify the key factors contributing to churn. This is achieved using Explainable AI techniques, which provide insights into the decision-making process of the predictive models.

## Datasets

The project uses the following datasets:

- Orange Dataset: This dataset contains customer data from Orange Telecom. [Link](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset/data)
- IBM Dataset: This dataset contains customer data from IBM Watson. [Link](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data)

## Methodology

The project follows these steps:

1. **Exploratory Data Analysis (EDA)**: Understanding the data by visualizing and summarizing it.
2. **Prerprocessing**: Data preprocessing for later use.
2. **Feature Selection**: Selecting the most relevant features for the predictive model. This is done using Correlation, Chi2 score, Sequential Feature Selection, and Recursive Feature Elimination.
3. **Modeling**: Training predictive models to predict customer churn.
4. **Explainable AI (SHAP)**: Using SHAP to understand the decision-making process of the predictive models.
5. **Clustering**: Grouping churned customers using clustering algorithms such as KMeans, Gaussian Mixture, and DBScan.

## Project Structure

- `Scripts/`: Contains the main code for the project.
- `Data & Outputs/`: Stores both the processed and original datasets, and outputs.

## Key Files

- `Scripts/EDA & Preprocessing.ipynb`: Exploratory data analysis & Preprocessing for both datasets.
- `Scripts/Feature Selection.ipynb`: Implements feature selection using Correlation, Chi2 score, Sequential Feature Selection, and Recursive Feature Elimination.
- `Scripts/Performance Evalutaion.ipynb`: Compares the performance of various models and feature selection methods across multiple metrics.
- `Scripts/SHAP.ipynb`: Implements Explanability for the project.
- `Scripts/Clustering.ipynb`: Implements clustering using KMeans, Gaussian Mixture, and DBScan.

## Setup

Please note that the dataframe-image library (used to visualize results) does not support Python 3.12.

## Usage

To run the project, follow these steps:

1. Clone the repository.
2. Install the required dependencies.
3. Run the .ipynb files in the `Scripts/` directory in the following order:
(i) EDA & Preprocessing.ipynb, (ii) Feature  Selection.ipynb, (iii) Performance Evalutaion.ipynb, (iv) SHAP.ipynb, (v) Clustering.ipynb.

## Contact

For any queries, please reach out at [sadmansakib26@iut-dhaka.edu](sadmansakib26@iut-dhaka.edu).