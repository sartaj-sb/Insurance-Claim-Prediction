🛡️ Insurance Claim Prediction (PRCP-1010)
📌 Project Overview

This project focuses on predicting whether an insurance policyholder is likely to file a claim, using customer demographics, policy details, and vehicle-related features.

The objective is to support insurance companies in:

risk assessment

pricing and underwriting decisions

reducing claim-related losses

The notebook implements a complete classification workflow, from data exploration to model evaluation and business interpretation.

🎯 Problem Statement

Insurance companies face financial risk due to uncertain claim behavior.
By analyzing historical policy and customer data, this project aims to:

classify policies into claim vs no-claim

identify key factors influencing claim occurrence

assist in proactive risk management

📊 Dataset

Dataset: Insurance Claim Dataset

Target Variable: Claim status

Feature Types:

Customer demographics

Vehicle characteristics

Policy-related attributes

Categorical and numerical variables

Key Observations

Dataset contains mixed feature types requiring careful preprocessing

Target variable shows class imbalance

Some features contain missing or inconsistent values

🔍 Exploratory Data Analysis (EDA)
Target Analysis

Majority of policyholders do not file claims

Minority class (claim cases) represents higher financial risk

Class imbalance impacts metric selection and model evaluation

Feature Insights

Certain customer demographics show different claim patterns

Categorical features demonstrate clear separation between claim and no-claim groups

Correlation Analysis

Limited linear correlation among numerical variables

Non-linear relationships justify the use of flexible classification models

🛠️ Data Preprocessing & Feature Engineering

Handled missing values appropriately

Encoded categorical variables into numerical form

Removed irrelevant or non-informative columns

Split data into training and testing sets

Ensured proper handling of imbalanced classes

🤖 Modeling Approach
Models Used

Classification models were trained and evaluated using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

Model Evaluation Strategy

Emphasis placed on recall for claim cases

Balanced trade-off between false positives and false negatives

Final model selected based on overall business relevance, not accuracy alone

📈 Model Interpretation
Key Claim Risk Drivers

Vehicle characteristics

Policy attributes

Customer demographic features

These features play a significant role in determining claim likelihood and align with domain expectations in insurance risk analysis.

💡 Business Insights

Not all customers carry equal risk
A small segment of policyholders accounts for a large portion of claims.

Vehicle and policy features matter significantly
Certain combinations increase claim probability.

Recall is critical for insurers
Missing a high-risk policyholder is costlier than flagging a low-risk one.

ML models can act as early warning systems
Predictions can support underwriting and pricing decisions.

⚠️ Challenges Faced

Class imbalance in claim data

Encoding multiple categorical features

Selecting business-relevant evaluation metrics

Avoiding overfitting on minority class patterns

🧰 Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

🚀 How to Run

Open PRCP-1010-InsClaimPred.ipynb

Install required Python libraries

Run all notebook cells sequentially
