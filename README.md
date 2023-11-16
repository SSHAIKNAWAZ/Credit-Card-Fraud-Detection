# Credit Card Fraud Detection Project

## Overview
> This project focuses on building a `credit card fraud detection model` using machine learning techniques. The dataset contains transactions made by European cardholders in September 2013. The primary goal is to develop a model that accurately identifies fraudulent transactions while `minimizing false positives`.

## Understanding and Defining Fraud
Credit card fraud involves any dishonest act to obtain information without proper authorization for financial gain. Skimming, manipulation of genuine cards, creation of counterfeit cards, stealing/loss of credit cards, and fraudulent telemarketing are common methods.

## Dataset Information
- **Number of Instances** : 284,807
- **Features** : Numerical input variables resulting from a PCA transformation, with 'Time' and 'Amount' being the only features not transformed.
- **Target Variable** : 'Class' (1 for fraud, 0 otherwise)
- **Class Imbalance** : The dataset is highly unbalanced, with frauds accounting for 0.172% of all transactions.

## Project Pipeline
> The project follows a structured pipeline:

**1. Data Understanding** :
  - Load and understand the dataset.
  - Choose relevant features for the final model.
    
**2. Exploratory Data Analytics (EDA)** :
  -  Perform univariate and bivariate analyses.
  -  Check for skewness in the data and address if necessary.
    
**3. Train/Test Split** :
  -  Split the data for model validation.
  -  Utilize k-fold cross-validation with an appropriate k value.
    
**4. Model Building / Hyperparameter Tuning**:
  -  Experiment with different models.
  -  Fine-tune hyperparameters for optimal performance.
  -  Explore various sampling techniques to enhance model accuracy.
    
**5. Model Evaluation** :
  -  Assess models using appropriate evaluation metrics.
  -  Choose metrics reflecting the importance of accurately identifying fraudulent transactions.

## Model Selection
After thorough exploration and evaluation of different models, the selected model for this project is XGBoost with SMOTE. The decision is based on the model's high accuracy, balanced sensitivity and specificity, and competitive performance metrics.

## Model Evaluation
The model's evaluation results are as follows:
  -  Accuracy: 0.99
  -  Sensitivity (Recall): 0.88
  -  Specificity: 0.99
  -  ROC Curve: 0.98
These metrics indicate strong overall model performance, demonstrating its effectiveness in distinguishing between fraudulent and non-fraudulent transactions.

### Contributors
- **Shaik Nawaz**
