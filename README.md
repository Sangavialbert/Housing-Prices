📌 Summary with Steps: Ridge Regression for Housing Price Prediction

This project aims to predict housing prices using the California Housing dataset. The dataset contains demographic and geographic features such as median income, house age, number of rooms, population, and location coordinates. Since these features may be correlated, Ridge Regression (L2 regularization) is used to handle multicollinearity and improve model stability.

First, the dataset is loaded and explored to check for missing values and understand basic statistics. Then, relevant features are selected, and the target variable (median house value) is defined. The data is split into training and testing sets in an 80:20 ratio. Feature scaling is applied using StandardScaler to normalize the data.

Next, a Ridge Regression model is built with a chosen alpha value and trained on the dataset. The model is evaluated using Mean Squared Error (MSE) and R² score to measure prediction performance. Finally, model coefficients are analyzed to understand the influence of each feature, and a plot is created to compare actual and predicted house prices.

🔹 Steps Involved
Load the California Housing dataset
Explore data (check null values, statistics, correlation)
Select features and target variable
Split dataset into training (80%) and testing (20%)
Normalize features using StandardScaler
Train Ridge Regression model with alpha value
Predict house prices on test data
Evaluate model using MSE and R² score
Analyze coefficients to understand feature importance
Plot actual vs predicted values

