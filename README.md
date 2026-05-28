# diamond-price-prediction
Regression model to predict diamond prices and find undervalued stones. Business logic layered on top of ML output. Stack: Python, Pandas, Scikit-learn.
📊 About
Regression model to predict the fair market price of diamonds and a deal-finding system to identify undervalued stones.
🎯 Goal
Predict a diamond's fair price and identify the top 5 stones where the actual price is below the predicted value.
📁 Data

Diamond characteristics dataset: carat weight, cut, color, clarity, polish, symmetry, certificate, price

🛠️ Stack
Python Pandas Scikit-learn (RandomForestRegressor, LabelEncoder, StandardScaler)
🔍 What was done

Categorical feature encoding via LabelEncoder with saved encoders for inverse transformation
Feature scaling, train/test split (80/20)
Random Forest Regressor training, evaluation via MAE and R²
Applied model to full dataset to generate predicted prices for all diamonds
Filtered undervalued diamonds: cut Very Good or above, color up to H, clarity up to VS1, actual price below predicted
Output top 5 diamonds with the largest discount vs predicted price

📌 Results

Business logic layered on top of ML: model outputs translate directly into investment decisions
Demonstrates ability to move from model building to actionable recommendations
