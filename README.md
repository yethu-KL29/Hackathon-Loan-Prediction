# Loan Prediction Hackathon

## Overview

Optimize the Loan eligibility process by predicting loan eligibility for Dream Housing Finance Company. Dream Housing Finance Company deals in all kinds of home loans. They have a presence across all urban, semi-urban, and rural areas. Customers first apply for a home loan, and then the company validates the customer's eligibility for the loan.

## Objective

The objective of this hackathon is to build a model that can predict the loan eligibility for Dream Housing Finance Company based on the customer's information.

## Problem Statement

You are provided with the dataset that contains information about the customers who applied for loans. Your task is to build a predictive model that will help the company to automate the loan eligibility process.

## Data Description

The dataset contains the following columns:

- **Loan_ID**: Unique Loan ID
- **Gender**: Male / Female
- **Married**: Applicant married (Y/N)
- **Dependents**: Number of dependents
- **Education**: Applicant Education (Graduate/Undergraduate)
- **Self_Employed**: Self-employed (Y/N)
- **ApplicantIncome**: Applicant income
- **CoapplicantIncome**: Coapplicant income
- **LoanAmount**: Loan amount in thousands
- **Loan_Amount_Term**: Term of loan in months
- **Credit_History**: Credit history meets guidelines
- **Property_Area**: Urban / Semi-Urban / Rural
- **Loan_Status**: Loan approved (Y/N)

## Evaluation Metric

The evaluation metric for this competition is accuracy. The model should be able to accurately predict the loan eligibility of the customers.

## Submission Format

The submission file should be a CSV file with the following columns:

- **Loan_ID**
- **Loan_Status**

## Steps to Follow

1. **Data Exploration and Cleaning**: 
    - Understand the data.
    - Handle missing values.
    - Encode categorical variables.

2. **Feature Engineering**: 
    - Create new features if necessary.
    - Perform feature scaling.

3. **Model Building**: 
    - Split the data into training and testing sets.
    - Train various machine learning models.
    - Evaluate the models.

4. **Model Selection**: 
    - Select the best-performing model based on accuracy.

5. **Prediction and Submission**: 
    - Use the selected model to make predictions on the test data.
    - Prepare the submission file.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook or any other IDE

### Libraries

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

### Installation

Install the required libraries using pip:

```sh
pip install pandas numpy scikit-learn matplotlib seaborn
