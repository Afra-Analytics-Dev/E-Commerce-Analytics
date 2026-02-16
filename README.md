# E-Commerce Customer Analytics Platform
A comprehensive end-to-end data analytics project that processes synthetic e-commerce data through all four levels of analytics—descriptive, diagnostic, predictive, and prescriptive—delivering actionable business insights and machine learning models for customer behavior analysis.

# Project Overview
Dataset: Synthetically generated e-commerce data with 10,000 customers and 184,939 transactions spanning two years (2022-2024)

# Objective: Demonstrate mastery of the complete data analytics lifecycle by transforming raw transactional data into strategic business recommendations

# Tech Stack: Python, Pandas, Scikit-learn, XGBoost, Matplotlib/Seaborn, Plotly, StatsModels, Scipy

# Key Features
# 1. Descriptive Analytics
-Interactive KPI Dashboard: Real-time monitoring of total revenue ($98.4M), customer growth rates, and segment performance
-Periodic Reporting System: Automated daily, monthly, and quarterly business reports
-Alert System: Threshold-based monitoring for satisfaction scores, retention rates, and support ticket volumes

# 2. Diagnostic Analytics 
a. Multi-dimensional Drill-Down: Geographic, temporal, and customer segment analysis
b. Root Cause Investigation: Revenue decline analysis and customer churn pattern identification
c. Statistical Correlation Analysis: Feature correlation heatmaps revealing key business drivers

# 3. Predictive Analytics 
1. Customer Lifetime Value Prediction: Four regression models compared (Linear Regression, Random Forest, Gradient Boosting, XGBoost) with R² scores up to 0.96
2. Churn Risk Prediction: Random Forest classifier with probability scoring for customer retention
3. Time Series Forecasting: ARIMA and Exponential Smoothing models for revenue prediction
4. Scenario Analysis: Conservative, moderate, and aggressive growth projections

# 4. Prescriptive Analytics (What Should We Do?)
-Marketing Budget Optimization: Linear programming for optimal channel allocation
-Segment-Specific Strategies: Tailored retention programs for Premium, Standard, and Basic customer segments
-AI-Enhanced Insights: Natural language insights and automated pattern recognition
-Early Warning System: Identification of high-risk customers for proactive intervention

# Key Business Insights
a. Revenue Distribution: North region leads in profitability; South region shows growth opportunities
b. Customer Segments: Three distinct segments identified with varying CLV (Premium: $5,000, Standard: $2,000, Basic: $800)
c. Marketing Optimization: Search and Direct channels yield highest ROI based on optimization algorithms
d. Seasonal Patterns: Peak revenue in March, lowest in September—enabling targeted campaign planning

# Technical Implementation
-Data Pipeline: Automated ETL with Pandas, date standardization, missing value handling, feature engineering
-Machine Learning: GridSearchCV optimization, cross-validation, feature importance analysis with SHAP values
-Visualization: Static (Matplotlib/Seaborn) and interactive (Plotly) charts with comprehensive dashboards
-Export Functionality: Final analyzed dataset and project summary available for download

# Model Performance
1. Model	CLV Prediction (R²)	Application
2. Linear Regression	0.96	Baseline interpretable model
3. Gradient Boosting	0.95	Complex pattern detection
4. XGBoost	0.94	Scalable predictions
5. Random Forest	0.93	Feature importance analysis

# Future Enhancements
-Deep learning integration for advanced churn prediction
-Real-time streaming analytics pipeline
-Interactive web dashboard with Dash/Streamlit
-A/B testing framework for recommendation validation
