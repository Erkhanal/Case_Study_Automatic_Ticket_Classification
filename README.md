# Case Study : Automatic Ticket Classification

## Table of Contents:
* [Introduction](#introduction)
* [Problem Statement](#problem-statement)
* [Business Goal](#business-goal)
* [Dataset](#dataset)
* [Analysis Approach](#analysis-approach) 
* [Conclusion](#conclusion) 
* [Technologies Used](#technologies-used)
* [References](#references)
* [Contact Information](#contact-information)

## Introduction:  
<div align="justify">In this repository contains the case study on ‘Automatic Ticket Classification’. In this case study we will build a model to automatically classify customer complaints for a financial company based on the products and services mentioned in the tickets.</div> 

## Problem Statement: 
<div align="justify">For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and services. Efficient resolution of these complaints minimizes customer dissatisfaction and enhances loyalty. This also gives them an idea of how to continuously improve their services/products to attract more customers. Customer complaints are unstructured text data so Traditionally, evaluating and assigning each ticket to the relevant department is a manual and tedious process, especially for large companies with a vast customer base.</div><br>

<div align="justify">In this case study, we will be working as an NLP engineer for a financial company that wants to automate its customer support tickets system. As a financial company, the firm has many products and services such as credit cards, banking and mortgages/loans.</div>

## Business Goal:
<div align="justify">The goal is to build a model that can classify customer complaints based on the products/services. This will help in quickly segregating tickets into relevant categories, thereby enabling faster resolution of issues. By using non-negative matrix factorization (NMF) for topic modeling, we will detect patterns and recurring words in the tickets to understand important features for each category. This information will be used to train a supervised model for automatic classification of new complaints.</div>

## Dataset:
The dataset is provided in “.json” format and contains customer complaints with features. we will convert this to a data frame for processing.

## Analysis Approach:

<div align="justify">To tackle this problem effectively, I have established a structured data analysis approach.</div>
<br>

**1. Data Loading:** Loading the data from the .json file into a data frame.<br>

**2. Text Preprocessing:** Cleaning and preprocessing the text data.<br>

**3. Exploratory Data Analysis (EDA):** Performing EDA to understand the structure and characteristics of the data.<br>

**4. Feature Extraction:** Extracting relevant features from the text data for modeling.<br>

**5. Topic Modeling:** Applying NMF to analyze patterns and classify tickets into five clusters:<br>

- Credit card / Prepaid card
- Bank account services
- Theft/Dispute reporting
- Mortgages/loans
- Others

**6. Model Building Using Supervised Learning:** Using the labelled data from topic modelling to train supervised models.<br>

**7. Model Training and Evaluation:** Training and evaluating the models based on appropriate metrics.<br>

**8. Model Inference:** Using the trained model to classify new customer complaints.</div>

 ## Conclusion: 
 <div align="justify"> This project aims to provide insights into the effectiveness of different models for automatic ticket classification. We can observe that Logistic Regression is performing the best. Therefore, we will use Logistic Regression model to predict the topics for the new complaints.</div>

## Technologies Used:
- Python, version 3 
- NumPy for numerical computations
- Matplotlib and seaborn for data visualization
- Pandas for data manipulation
- Statsmodels for statistical modeling
- Sklearn for machine learning tasks
- NLTK (Natural Language Toolkit) and spaCy
- Jupyter Notebook for interactive analysis

## References:
- Python documentations
- Exploratory Data Analysis
- Stack Overflow
- NLTK (Natural Language Toolkit)
- spaCy 
- Medium NLP Articles 

## Contact Information:
Created by https://github.com/Erkhanal - feel free to contact!
