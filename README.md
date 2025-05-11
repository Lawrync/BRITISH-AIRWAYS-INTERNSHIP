![image](https://github.com/user-attachments/assets/ce663485-7a86-4a9c-92ee-98393a994d20)
# British Airways Internship Project 
# Introduction

In today’s competitive airline industry, customer experience and satisfaction play a critical role in shaping brand loyalty and business growth. At British Airways, data scientists harness the power of analytics and predictive modeling to understand customer sentiment, identify service gaps, and support strategic decisions. This project explores customer reviews by analyzing patterns in star ratings, review content, and user verification status. The goal is to build a machine learning model that evaluates sentiment or satisfaction levels, offering insights that can help British Airways proactively engage with customers—even before their journey begins.
# Objective

The primary objective of this project is to leverage customer review data to build a machine learning model that can evaluate and predict customer satisfaction. By analyzing structured features such as star ratings, review dates, country of origin, and verification status, the model aims to uncover patterns that influence customer sentiment. These insights will help British Airways refine its customer engagement strategies, improve onboard and ground services, and ultimately enhance customer retention and acquisition efforts.
# Methodology

To address the project objectives, the following steps were undertaken:

Data Collection & Preparation
The dataset provided included the following features:

reviews: Textual feedback from customers

stars: Numerical rating of the experience (1–10 scale)

date: Review date

country: Customer's country

verification_status: Indicates whether the review was from a verified user

Initial steps included cleaning the data (e.g., removing special characters in reviews), converting date formats, and ensuring consistency in verification status labels.

Feature Engineering
For modeling purposes, the textual reviews were excluded and the focus was placed on numerical and categorical features such as:

stars (as the target variable or for classification)

country (encoded)

verification_status (encoded)

Model Selection & Training
Multiple models were evaluated, and the Random Forest Classifier was selected for its performance and interpretability. The dataset was split into training and testing subsets, and the model was trained to predict star ratings based on the given features.

Model Evaluation
Accuracy, confusion matrix, and classification reports were used to assess the performance of the model. The final model was saved using joblib for later use.

Results Interpretation
The importance of each feature was examined to understand what most significantly influenced the ratings. These insights were translated into actionable recommendations for British Airways.
