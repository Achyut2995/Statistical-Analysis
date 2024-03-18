# Statistical-Analysis

This project performs multiple linear regressions on different combinations of predictor variables to predict the target variable (quality) of a dataset. It then evaluates the model performance using various metrics and visualizes the data through scatter plots, box plots, histograms, and Q-Q plots.

1. **Multiple Linear Regression**:
   - The code defines multiple predictor variables (e.g., volatile acidity, fixed acidity, pH, density) and the target variable (quality).
   - It performs multiple linear regressions using Ordinary Least Squares (OLS) for different combinations of predictor variables.

2. **Model Evaluation**:
   - The code calculates the adjusted R-squared values for each model to assess the goodness of fit.
   - It splits the data into training and testing sets to evaluate the model's performance on unseen data.
   - The mean squared error (MSE) is calculated to measure the average squared difference between the predicted and actual values.

3. **Visualization**:
   - Scatter plots are created to visualize the relationships between pairs of variables.
   - Box plots are used to visualize the distribution of individual variables.
   - Histograms show the frequency distribution of each variable.
   - Q-Q plots assess the normality of the data distribution.

4. **Interpretation**:
   - By analyzing the model summary, adjusted R-squared values, MSE, and visualizations, the code helps identify the best combination of predictor variables for predicting the target variable.
   - The plots provide insights into the relationships between variables and the distribution of the data.
