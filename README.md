# The-Triad_psno-4
Machine learning system for digital marketing campaign revenue prediction and ROI optimization. Uses Random Forest, XGBoost, and 6 ML models with 5-fold cross-validation. Features interactive Gradio dashboard, SHAP explainability, budget optimizer, and real-time revenue forecasting. Achieves 95%+ prediction accuracy.

Digital Marketing Campaign Revenue Prediction and ROI Optimization

This project presents an end-to-end machine learning system designed to predict digital marketing campaign performance and optimize return on investment (ROI). It leverages historical campaign data to generate accurate revenue predictions and provide actionable insights for better decision-making.

Project Overview

The system analyzes campaign-level data such as impressions, clicks, conversions, spend, and revenue to:

Predict campaign revenue
Identify high-performing campaigns
Optimize marketing budget allocation
Provide interpretable insights into campaign success and failure
Key Features
Multiple Machine Learning Models (6 models evaluated)
Linear Regression (baseline)
Random Forest (best-performing model)
XGBoost
Additional models for comparison and validation
5-Fold Cross Validation
Ensures model stability and reduces overfitting by evaluating performance across multiple data splits
Advanced Feature Engineering
CPC (Cost per Click)
CPA (Cost per Acquisition)
ROAS (Return on Ad Spend)
Time-based features such as month and day of week
Performance Evaluation Metrics
R² Score (>95%)
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
Explainability (XAI)
SHAP (SHapley Additive Explanations)
Provides global interpretability through feature importance and summary plots
LIME (Local Interpretable Model-Agnostic Explanations)
Explains individual predictions for specific campaigns

These techniques ensure that the model is transparent and interpretable for business stakeholders.

Interactive Dashboard

An interactive interface built using Gradio enables:

Real-time revenue prediction
User input for campaign parameters
Visualization of campaign performance metrics
Business Impact
Improves return on investment by identifying high-performing campaigns
Enables efficient budget allocation across channels and regions
Supports data-driven marketing decisions
Enhances transparency through explainable AI
Results
Achieved over 95% R² score for revenue prediction
Random Forest selected as the best model based on performance and stability
Consistent results across cross-validation folds
Tech Stack
Python
Pandas, NumPy
Scikit-learn
XGBoost
SHAP, LIME
Gradio
Conclusion

This project demonstrates the application of machine learning in marketing analytics to predict campaign performance, optimize spending, and provide interpretable insights. The system is designed to be scalable and adaptable for real-world marketing environments.
