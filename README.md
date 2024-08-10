Travel Insurance Classification Project

Created By: Hans Christian Don

Project Overview
This project focuses on classifying whether a travel insurance policyholder will make an insurance claim. The dataset used in this analysis contains historical data of policyholders, including their travel destinations, insurance products, and other related information. The target variable indicates whether a policyholder will make a claim (1) or not (0).

Business Problem Understanding
Context
Travel insurance is a type of insurance that provides protection while traveling, both domestically and internationally. Some countries, especially in Europe and America, require travelers to have travel insurance. The premium amount depends on the coverage, duration of travel, and destination. A travel insurance company aims to predict which policyholders are likely to file an insurance claim based on historical data.

Objective
The objective is to build a classification model that can predict whether a policyholder will file an insurance claim.

Data Description
The dataset includes the following features:

Agency: The name of the travel insurance agency.
Agency Type: The type of agency (e.g., Travel, Airlines).
Distribution Channel: The distribution channel used to sell the insurance (e.g., Online, Offline).
Product Name: The name of the insurance product.
Duration: The duration of the travel in days.
Destination: The destination country or region for the travel.
Net Sales: The net sales amount for the insurance policy.
Commission (in value): The commission earned by the agency for selling the policy.
Age: The age of the policyholder.
Claim: The target variable, indicating whether a claim was made (0 = No, 1 = Yes).

Target Variable:
0: No insurance claim
1: Insurance claim

Project Structure

Business Problem Understanding
Introduction to the problem and business context.

Data Understanding
Overview of the dataset, including data types, missing values, and exploratory data analysis.

Data Preprocessing
Handling missing values, feature engineering, and data transformation.

Modeling
Building and evaluating various classification models.

Model Evaluation
Comparing model performance using metrics such as accuracy, precision, recall, and F1-score.

Conclusion
Final insights and recommendations based on the model performance.
The notebook concludes with the best-performing model, along with detailed evaluation metrics. The final model can be used to predict whether a new policyholder will make an insurance claim.
