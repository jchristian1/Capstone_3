Enhancing Stock Market Prediction Models with Expanded Financial Data (2000-2022)
Author
Jasson Flórez
Date: October 11, 2024

Project Overview
This project aims to refine and enhance stock market prediction models by incorporating a comprehensive dataset from 2000 to 2022. By expanding the data and including additional financial metrics, the goal is to improve the model's predictive power, allowing investors to identify stocks that are more likely to outperform the S&P 500.

Objective
The primary objective is to develop a robust stock prediction model using an expanded dataset of financial indicators. The project aims to create a tool that helps investors make more informed decisions by predicting which stocks will outperform the S&P 500.

Dataset
The data was collected from the Financial Modeling Prep (FMP) API and covers the period from 2000 to 2022. The dataset includes:

Valuation ratios
Profitability metrics
Liquidity indicators
Debt ratios
Growth rates
Macroeconomic factors (e.g., inflation, interest rates)
Data Preprocessing
Cleaning: Missing data was handled using KNN and median imputation.
Feature Engineering: New features, including rolling averages and year-over-year growth rates, were created.
Outliers: Managed using the Interquartile Range (IQR) method.
Models Used
Several models were employed to predict stock outperformance:

Random Forest
XGBoost
Artificial Neural Networks (TensorFlow/Keras)
Logistic Regression
Decision Tree
Support Vector Classifier (SVC)
K-Nearest Neighbors (KNN)
Model Evaluation Metrics:
Accuracy
Precision & Recall
F1-Score
AUC (Area Under the Curve)
Key Findings
XGBoost showed the best balance between precision and recall, particularly for identifying outperforming stocks (Class 1).
Important financial indicators included profitability, leverage, and efficiency metrics, along with macroeconomic factors like inflation rates and GDP growth.
Random Forest also demonstrated reasonable performance but requires fine-tuning to improve precision for Class 1.
Limitations
Data Imbalance: Non-outperforming stocks were more prevalent, causing challenges in model precision for Class 1.
Market Noise: Volatility and noise in financial data impacted model generalization.
Future Generalization: Models trained on historical data may not perfectly predict future stock performance.
Recommendations
Stock Selection Strategy: Use the model to guide stock selection by focusing on strong financial performance during economic downturns.
Backtesting: Apply the model in backtesting to refine strategies before using it in real-world scenarios.
Continuous Data Collection: Update the model annually with new financial data to maintain its relevance in evolving markets.
Conclusion
By leveraging data from 2000 to 2022 and including additional financial metrics, the project successfully enhanced the predictive power of stock outperformance models. With further tuning and integration of additional macroeconomic factors, this tool can be invaluable for investors seeking to outperform the S&P 500.

References
Financial Modeling Prep API Documentation
Scikit-learn Documentation
XGBoost Documentation
TensorFlow Documentation
