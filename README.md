# Data Science Final Project:
### Employee_-Attrition_Analysis

### Course: Data Science with Python 2025 - 2026
### Team Members:
### Anastasia Sulukhia
### Guga Gagloshvili

### Project Overview

This project is a data science pipeline developed as the final team project for the Data Science with Python course, 2025 - 2026.
The goal of the project is to transform raw data into meaningful insights through data cleaning, exploratory data analysis, visualization, and machine learning.

The project demonstrates practical skills in but not limited to:

1. Data preprocessing with Pandas and NumPy
2. Exploratory data analysis and visualization
3. Machine learning model implementation and evaluation
4. Collaborative development using GitHub

#### Problem Statement

The objective of this project is to analyze a real world dataset, uncover meaningful patterns and relationships, and build predictive machine learning models to solve specific problem defined by the team based on the dataset.

Key questions addressed include:

- What patterns and trends exist in the data?
- Which features are most influential?
- How accurately can machine learning models predict the target variable?
- Which ML model works best with given dataset and defined problem and how do they compare?

Dataset Source: real world anonymous data on employee attrition from Kaggle
Description:
The dataset contains structured data relevant to the project domain. It includes numerical and categorical features that require cleaning, transformation, and analysis before modeling. note that this dataset is very good example of how usually the dataset looks like in real world applications, it is highly
unbalanced which introduced new challenge in ML modeling.

data-science-final-project/
│
├── data/
│   ├── raw/                # Original dataset
│   └── processed/          # Cleaned and transformed data
│
├── notebooks/
│   ├── data_analysis_and_cleaning.ipynb # this unites EDA with cleaning, since it made more sense to plot step by step 
│   └── machine_learning_models.ipynb
│
├── logging/
│   ├── logging.log
│
├── reports/
│   ├── figures/
│   └── results/
│
├── requirements.txt
├── CONTRIBUTIONS.md
└── README.md

### Data Processing & Cleaning

The data preprocessing phase includes:

- Handling missing values
- Detecting and addressing outliers
- Data type conversions
- Feature engineering
- Creating reproducible preprocessing steps
All data cleaning decisions are documented and justified within the notebooks.

Exploratory Data Analysis
EDA was performed to understand:

-Feature distributions
Correlations between variables
Trends, patterns, and anomalies


### Machine Learning Models
The following machine learning models were implemented and evaluated:

Model 1: Logistic Regression 
Model 2: Random Forest

Model Evaluation

Models were evaluated using appropriate metrics: Accuracy, Precision, Recall, Confusion Matrix
A comparison of model performance is included, with discussion on which model performed better and why.


## Installation & Setup
To run this project locally:
### Clone the repository
git clone https://github.com/Anitasulukhia/Employee_attririon_Analysis.git

### Navigate to the project directory
cd Employee_attririon_Analysis

### Install dependencies
pip install -r requirements.txt

### Usage

Open Jupyter Notebook or JupyterLab
Run notebooks in the following order:

1. data_analysis_and_cleaning.ipynb
2. machine_learning_models.ipynb

Each notebook contains markdown explanations and results.

## Team Collaboration
This repository was developed collaboratively using GitHub:
Each team member worked on separate branches
Changes were merged using pull requests

Contributions are documented in CONTRIBUTIONS.md

## Results & Conclusions

After cleaning and preprocessing the data, exploratory analysis revealed clear patterns and correlations between key features and the target variable - Attrition. Several features showed strong influence, which guided feature selection for modeling.

Two machine learning models were implemented and evaluated. The results showed that ____ outperformed ____ based on [accuracy / R² / MSE/F1], making it the most effective model for this task. Overall, the models achieved reliable performance, demonstrating that proper data preparation and feature selection significantly improve prediction quality.

This project successfully demonstrates a data science workflow, from raw data processing to model evaluation, and meets the objectives of the course.

## Future Work
Possible extensions of this project include:

1. Trying additional machine learning models
2. Advanced feature engineering
3. Interactive dashboards
4. Working with larger or multiple datasets

## Academic Integrity
This project adheres to the course’s academic integrity policy.
All code is original or properly cited, and each team member’s contribution is clearly documented.

## License
This project is for educational purposes only.
