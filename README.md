# Credit Card Fraud Detection System

## Overview

This project focuses on developing an AI-powered system to accurately detect and prevent fraudulent credit card transactions in real time. By analyzing user behavior and transaction patterns, this system aims to overcome the limitations of traditional fraud detection methods, which are often slow and ineffective against increasingly sophisticated fraudulent activities.

## Problem Statement

Credit card fraud poses a significant threat in the realm of digital transactions, leading to substantial financial losses for both financial institutions and consumers. Existing fraud detection systems, relying on static rules and manual reviews, struggle to keep pace with the evolving tactics of fraudsters. This project addresses this challenge by leveraging artificial intelligence to enhance fraud detection capabilities.

## Abstract

The rapid expansion of digital payments has made credit card fraud a critical concern. Traditional fraud detection systems are often inadequate against the complex and adaptive nature of fraudulent activities. This project proposes an AI-powered solution utilizing machine learning algorithms to analyze transaction data, identify unusual behavior, and detect potential fraud in real time. The system learns from historical patterns and continuously updates its detection model to significantly improve accuracy and efficiency.

## Project Structure

The project includes the following key stages:

-   **Data Cleaning:** (Responsibility: Trisha .M)
-   **Exploratory Data Analysis (EDA):** (Responsibility: Varuneesri.A)
-   **Feature Engineering:** (Responsibility: Pavithra.S.Y)
-   **Model Development:** (Responsibility: Sruthi.L)
-   **Documentation and Reporting:** (Responsibility: Swetha .J and Priyanka .P)

## Model Development

The project utilizes a `RandomForestClassifier` for fraud detection. The model is trained and evaluated using a train-test split of the data (80% train, 20% test) with a `random_state` of 42 for reproducibility.

Key steps in the model development include:

1.  **Data Encoding:** Categorical features are likely encoded (as suggested by `df_encoded`).
2.  **Feature Importance:** Feature importances are calculated and visualized to understand the contribution of each feature to the model's predictions. A bar plot of feature importances is generated and saved as `feature_importances.png`.
3.  **Correlation Analysis:** A correlation matrix is computed and visualized as a heatmap to understand the relationships between different features. The heatmap is saved as `heatmap_modelling.png`.
4.  **Model Training:** The `RandomForestClassifier` is trained on the training data (`X_train`, `y_train`).
5.  **Model Evaluation:** The trained model is evaluated on the test data (`X_test`) using metrics such as the classification report and confusion matrix. The predictions are stored in `y_pred`.

## Future Scope

This project lays the foundation for further enhancements in real-time fraud detection. Potential future developments include:

1.  Real-time deep learning for dynamic fraud detection
2.  Federated learning for privacy-preserving training
3.  Adaptive models that learn new fraud patterns continuously
4.  Behavioral biometrics for enhanced user verification
5.  Graph analytics to detect fraud networks
6.  Explainable AI to build user trust
7.  Blockchain for secure, traceable transactions

## Repository Link

[https://github.com/swetha18084/Phase-3-credit-card-fraud-detection-.git](https://github.com/swetha18084/Phase-3-credit-card-fraud-detection-.git)

## Team Members and Roles

-   **Data cleaning:** Trisha .M
-   **EDA:** Varuneesri.A
-   **Feature engineering:** Pavithra.S.Y
-   **Model development:** Sruthi.L
-   **Documentation and reporting:** Swetha .J, Priyanka .P

## Institution and Department

-   **Institution:** C.Abdul hakeem college of engineering and technology
-   **Department:** Computer science and engineering

## Date of Submission

09/05/2025

## Student Information

-   **Student Name:** Swetha.J
-   **Register Number
