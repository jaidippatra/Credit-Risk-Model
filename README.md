# Credit Risk Analysis

## Project Overview
This project analyzes credit risk using machine learning techniques. The objective is to predict whether an individual is likely to default based on various financial and demographic factors. The analysis is conducted using two datasets (`case_study1.xlsx` and `case_study2.xlsx`) which are merged and preprocessed for model training.

## Dataset
- **case_study1.xlsx**: Contains demographic and financial information about individuals.
- **case_study2.xlsx**: Contains additional financial details.
- The datasets are merged based on the `PROSPECTID` column.

## Methodology

### 1. Data Preprocessing
- Null and invalid values (e.g., `-99999`) are removed.
- The two datasets are merged to form a single dataset for analysis.
- Categorical columns and numerical columns are identified and processed.

### 2. Exploratory Data Analysis
- The dataset is explored to understand the distribution of features, detect outliers, and handle missing values.
- Feature selection and engineering are performed to improve the predictive power of the model.

### 3. Model Training
- A **Random Forest Classifier** is used to predict credit risk.
- The dataset is split into training and testing sets using an 80/20 ratio.
- The model is trained and evaluated based on accuracy, precision, recall, and F1-score.

### 4. Model Evaluation
- **Accuracy**: The percentage of correct predictions made by the model.
- **Precision, Recall, F1-Score**: Detailed classification metrics to assess model performance on predicting credit risk.

## Final Model
**XGBoost**: I have achived best accuracy using XGBoost with accuracy 78%

