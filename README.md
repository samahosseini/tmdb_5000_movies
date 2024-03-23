# Movie Financial Performance Analysis
This repository contains Python code for analyzing the financial performance of movies using machine learning classification algorithms. The analysis includes exploring various factors such as budget, revenue, popularity, and runtime to predict the profitability of movies.

**Overview**

The analysis involves the following steps:

1. Data Preprocessing: The dataset is loaded and preprocessed to handle missing values and convert categorical variables into numerical format.

2. Feature Engineering: Relevant features are selected for modeling, including movie release date, budget, runtime, popularity, and more.

3. Model Selection: Several classification algorithms are employed, including Logistic Regression, Decision Tree, Random Forest, and XGBoost, to predict movie profitability.

4. Model Evaluation: The models are evaluated using performance metrics such as accuracy, precision, recall, and F1-score. Additionally, the ROC-AUC curve is plotted to assess model performance.

5. Feature Importance: For tree-based models (Decision Tree, Random Forest, and XGBoost), feature importance analysis is conducted to identify the most significant predictors of movie profitability.

# File Structure
+ movie_financial_performance_analysis.ipynb: Jupyter Notebook containing the Python code for data preprocessing, feature engineering, model training, evaluation, and feature importance analysis.

+ README.md: This document provides an overview of the analysis and instructions for running the code.

# Usage

To run the analysis:

1. Clone this repository to your local machine.

2. Open the movie_financial_performance_analysis.ipynb file in Jupyter Notebook or any compatible environment.

3. Follow the instructions and run the code cells sequentially.

4. Review the results, including model performance metrics and feature importance analysis.

# Dependencies
Ensure you have the following Python packages installed:

* pandas
* scikit-learn
* xgboost
* matplotlib
You can install the dependencies using pip:

Copy code

`pip install pandas scikit-learn xgboost matplotlib`

**Author:**
Sama Hosseini