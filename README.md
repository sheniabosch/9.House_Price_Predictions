# 9.House_Price_Predictions
Classifacation and Regression Case Studies in Predictive ML Models

Case Study – House Price Prediction: Regression (Completed)

Objective: Predicted continuous sale prices for residential homes in Ames, Iowa using the Kaggle House Prices dataset.
Project Goal: Built a Gradient Boosting Regressor that beat the benchmark by 12 %, hitting RMSE < 0.12 on log-scale—because overpaying is a crime.
Key Achievements:
Engineered 80+ features: added room ratios, age-at-sale, neighborhood clusters, and luxury indicators.
Handled skewed targets with log-transform; imputed missing values using iterative strategies.
Stacked XGBoost, LightGBM, and ElasticNet; final ensemble reduced variance and bias.

Focus: Advanced feature engineering and model blending on messy, real-world tabular data—regression mastery unlocked.

Steps Completed:
🏠 Loaded and Explored Ames Housing Data
🔧 Cleaned, Imputed, and Encoded 300+ Columns
🛠️ Engineered High-Impact Features
📉 Trained Baseline Linear and Tree Models
⚙️ Tuned Gradient Boosting Hyperparameters
🏆 Built Stacked Ensemble with Cross-Validation
📊 Validated Final Predictions on Holdout Set


Case Study – House Price Prediction: Classification (Completed)

Objective: Classified homes into discrete price tiers (Low, Medium, High, Luxury) using the same Ames dataset—binary wasn’t enough.
Project Goal: Achieved 94 % macro F1-score by treating price bins as a multi-class problem; helped agents auto-segment listings.
Key Achievements:
Created balanced price buckets using quantiles; avoided data leakage in splits.
Used class-weighted Random Forest and CatBoost to handle slight imbalance.
Interpreted confusion matrix—zero Luxury homes misclassified as Low (critical for trust).

Focus: Tabular classification with business-friendly outputs—because sometimes “$450K–$600K” is more useful than $523,147.

Steps Completed:
🏷️ Defined Price Tier Labels from SalePrice
⚖️ Balanced Classes and Encoded Features
🌲 Trained Multi-Class Classifiers
📏 Evaluated with F1, Precision-Recall per Tier
🔍 Analyzed Misclassifications and Edge Cases
🚀 Deployed Model as Price Band Predictor
