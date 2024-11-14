# Bankruptcy Prediction Model

This project aims to predict the bankruptcy status of companies listed on the Taiwan Stock Exchange based on financial metrics. By leveraging machine learning models, such as XGBoost and Random Forest, the project provides insights into key indicators of financial health, offering early detection that could aid stakeholders in proactive decision-making.

## Project Overview

Companies operate within a network of complex financial activities, influenced by numerous external factors. This complexity makes it challenging to predict bankruptcy. Our model helps forecast the bankruptcy risk, providing a valuable tool for financial managers, investors, and regulatory authorities.

### Key Features
- **High Accuracy**: Achieves an accuracy of **83%**, prioritizing both accuracy and recall to minimize false negatives.
- **Interpretability**: SHAP analysis is used to highlight feature importance, aiding in the understanding of critical financial metrics.
- **SMOTE Balancing**: Class imbalance is handled through Synthetic Minority Over-sampling Technique (SMOTE).
- **Efficient Preprocessing**: PCA is applied to reduce feature correlation while retaining predictive value.

## Dataset

The dataset originates from the [Taiwan Economic Journal](https://archive.ics.uci.edu/ml/datasets/Taiwanese+Bankruptcy+Prediction) and includes 95 features from 1999 to 2009, representing financial health metrics such as:
- Debt Ratio %
- Liability to Equity Ratio
- Cash Flow Rate
- Profitability Metrics

The target variable `Bankrupt?` is a binary classification where:
- **1** = Bankrupt
- **0** = Non-bankrupt




