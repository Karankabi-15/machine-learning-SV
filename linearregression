Linear regression is a fundamental and widely used statistical method in machine learning for modeling the relationship between a dependent variable and one or more independent variables. Here’s an overview of linear regression:

### Simple Linear Regression

**Concept:**
- Simple linear regression models the relationship between a single independent variable \( x \) and a dependent variable \( y \).
- The relationship is assumed to be linear, represented by the equation:
  \[
  y = \beta_0 + \beta_1 x + \epsilon
  \]
  where:
  - \( y \) is the dependent variable.
  - \( x \) is the independent variable.
  - \( \beta_0 \) is the y-intercept (the value of \( y \) when \( x = 0 \)).
  - \( \beta_1 \) is the slope of the line (the change in \( y \) for a one-unit change in \( x \)).
  - \( \epsilon \) is the error term (the difference between the observed and predicted values of \( y \)).

**Goal:**
- To find the best-fitting line that minimizes the sum of the squared differences (residuals) between the observed values and the values predicted by the line.

**Fitting the Model:**
- The coefficients \( \beta_0 \) and \( \beta_1 \) are estimated using the least squares method, which minimizes the sum of squared residuals:
  \[
  \text{Residual Sum of Squares (RSS)} = \sum_{i=1}^{n} (y_i - (\beta_0 + \beta_1 x_i))^2
  \]

### Multiple Linear Regression

**Concept:**
- Multiple linear regression extends simple linear regression by modeling the relationship between a dependent variable \( y \) and multiple independent variables \( x_1, x_2, \ldots, x_p \).
- The relationship is represented by the equation:
  \[
  y = \beta_0 + \beta_1 x_1 + \beta_2 x_2 + \ldots + \beta_p x_p + \epsilon
  \]

**Goal:**
- To find the best-fitting hyperplane that minimizes the sum of squared residuals in the multi-dimensional space formed by the independent variables.

**Fitting the Model:**
- The coefficients \( \beta_0, \beta_1, \beta_2, \ldots, \beta_p \) are estimated using the least squares method, similar to simple linear regression but extended to multiple dimensions.

### Assumptions of Linear Regression
1. **Linearity:** The relationship between the dependent and independent variables is linear.
2. **Independence:** The residuals (errors) are independent of each other.
3. **Homoscedasticity:** The residuals have constant variance at every level of the independent variables.
4. **Normality:** The residuals of the model are normally distributed.

### Evaluation Metrics
- **R-squared (R²):** Measures the proportion of the variance in the dependent variable that is predictable from the independent variables. Ranges from 0 to 1, with 1 indicating perfect prediction.
- **Mean Squared Error (MSE):** The average of the squared differences between the observed and predicted values.
- **Root Mean Squared Error (RMSE):** The square root of MSE, providing an error metric in the same units as the dependent variable.

### Applications of Linear Regression
- Predicting continuous outcomes (e.g., predicting house prices based on features like size, location).
- Understanding relationships between variables (e.g., studying the effect of marketing spend on sales).
- Trend analysis and forecasting (e.g., analyzing time series data to predict future values).

Linear regression is a powerful yet simple method that provides interpretable results and serves as a foundation for more complex machine learning models.
