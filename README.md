# NYC-Airbnb-Price-Prediction
AIML Linear Regression Project
Predict New York City Airbnb Prices Using Linear Regression

Objective

The objective of this project is to predict Airbnb listing prices in New York City using Linear Regression and machine learning techniques.

Dataset

The project uses the New York City Airbnb Open Data dataset, containing information about listing prices, locations, room types, minimum nights, reviews, and availability.

Methodology

1. EDA: Examined dataset shape, columns, data types, and missing values.
2. Data Cleaning: Removed irrelevant columns and handled missing values.
3. Outlier Treatment: Used boxplots and the 95th percentile rule to reduce extreme prices and minimum-night values.
4. Feature Engineering: Applied one-hot encoding to categorical features.
5. Data Splitting: Divided the dataset into 80% training data and 20% testing data.
6. Model Training: Trained a Linear Regression model.
7. Evaluation: Used R², MAE, MSE, and RMSE to measure prediction performance.

Results

- R² Score: [Insert your actual R² score]
- Mean Absolute Error: $[Insert your actual MAE]
- Root Mean Squared Error: $[Insert your actual RMSE]

The R² score indicates how much variation in Airbnb prices is explained by the model. The MAE indicates the average absolute prediction error in US dollars.

Conclusion

The project demonstrates how Linear Regression can be used to estimate Airbnb prices using listing characteristics. Actual-versus-predicted plots and residual analysis help identify prediction errors and limitations. The comparison of errors across price groups determines whether the model performs better on cheaper or more expensive listings.

The model's effectiveness should be judged using the actual test results rather than assumed performance values.
