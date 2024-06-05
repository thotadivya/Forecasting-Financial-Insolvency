# Forecasting Financial Insolvency 

This project focuses on predicting bankruptcy risk in companies by analyzing past financial data using machine learning models. It aims to build a model that can accurately forecast the likelihood of insolvency in the future based on historical financial information.

## Team Members
- **Divya Lakshmi Thota** (divyalakshmithota@my.unt.edu)
- Sreekar Thanda 
- Pranavi Itharaj 
- Sindhuvyshnavi Kodakandla 
- Sai Meghana Reddy Chukka 

## Abstract
The project utilizes various financial indicators like current assets, liabilities, sales, and return on investments to predict the risk of bankruptcy. The main machine learning models employed are Decision Trees, Random Forests, and K-Nearest Neighbors (K-NN). The Random Forest model showed the best performance with an accuracy of 98%.

## Key Features
- **Current Assets to Current Liabilities (CA_CL)**: Indicates short-term liquidity.
- **Net Income to Total Assets (NI_TA)**: Measures profitability relative to total assets.
- **Total Debt to Total Assets (TD_TA)**: Shows the extent of asset financing by debt.
- **Sales to Total Assets (S_TA)**: Reflects efficiency in generating sales relative to total assets.

## Dataset
The dataset used in this project was sourced from Kaggle and includes financial details of various companies. It contains over 20,000 records with multiple financial features.

## Preprocessing
The dataset underwent extensive preprocessing, including:
- Treatment of missing values
- Feature selection and engineering
- Outlier detection and treatment
- Exploratory Data Analysis (EDA)

## Models and Methodology
The following models were used to predict financial insolvency:
1. **Decision Tree Classifier**: Achieved an accuracy of 83.48%.
2. **Random Forest Classifier**: Achieved the highest accuracy of 98.64%.
3. **K-Nearest Neighbors (K-NN) Classifier**: Performed competitively with various parameter settings.

## Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Area Under the ROC Curve (AUC-ROC)
- Confusion Matrices

## Results
- **Random Forest**: The best performing model with an accuracy of 98.64% and the lowest RMSE.
- **Decision Tree**: Provided good interpretability and insights into key predictors of insolvency.
- **K-NN**: Showed responsive performance to local patterns with competitive accuracy.

## Conclusion
The project demonstrated that machine learning models could effectively predict financial insolvency. The Random Forest model is recommended for predicting bankruptcy risk due to its high accuracy and robustness.

