Simple Linear Regression: Key Notes
Definition
Simple Linear Regression is a statistical method used to model the relationship between two variables by fitting a linear equation to observed data. One variable is considered the independent variable (
𝑋
X), and the other is the dependent variable (
𝑌
Y).

Equation
The general form of the linear regression equation is:

𝑌
=
𝛽
0
+
𝛽
1
𝑋
+
𝜖
Y=β 
0
​
 +β 
1
​
 X+ϵ
𝑌
Y: Dependent variable (response variable)
𝑋
X: Independent variable (predictor variable)
𝛽
0
β 
0
​
 : Intercept (value of 
𝑌
Y when 
𝑋
=
0
X=0)
𝛽
1
β 
1
​
 : Slope (change in 
𝑌
Y for a one-unit change in 
𝑋
X)
𝜖
ϵ: Error term (accounts for the variation in 
𝑌
Y not explained by 
𝑋
X)
Assumptions
Linearity: The relationship between 
𝑋
X and 
𝑌
Y is linear.
Independence: Observations are independent of each other.
Homoscedasticity: Constant variance of errors (
𝜖
ϵ).
Normality: The residuals (
𝑌
observed
−
𝑌
predicted
Y 
observed
​
 −Y 
predicted
​
 ) are normally distributed.
Steps in Simple Linear Regression
Data Collection: Gather data for 
𝑋
X and 
𝑌
Y.
Exploratory Data Analysis: Visualize the data (e.g., scatter plot) to check for a linear relationship.
Model Fitting: Estimate the parameters (
𝛽
0
β 
0
​
  and 
𝛽
1
β 
1
​
 ) using methods like Ordinary Least Squares (OLS).
Model Evaluation:
Coefficient of Determination (
𝑅
2
R 
2
 ): Measures the proportion of variance in 
𝑌
Y explained by 
𝑋
X.
Residual Analysis: Check assumptions (e.g., normality, homoscedasticity).
Prediction: Use the fitted model to predict 
𝑌
Y for new values of 
𝑋
X.
Key Metrics
Slope (
𝛽
1
β 
1
​
 ): Indicates the strength and direction of the relationship.
Intercept (
𝛽
0
β 
0
​
 ): Provides the starting value of 
𝑌
Y when 
𝑋
=
0
X=0.
𝑅
2
R 
2
 : Ranges from 0 to 1; higher values indicate a better fit.
Mean Squared Error (MSE): Measures the average squared difference between observed and predicted 
𝑌
Y.
Limitations
Sensitive to outliers.
Only models linear relationships.
Assumes the relationship between 
𝑋
X and 
𝑌
Y is causal (which may not always be true).
Applications
Predicting sales based on advertising spend.
Estimating the effect of temperature on ice cream sales.
Analyzing the relationship between study hours and exam scores.
Let me know if you'd like to dive deeper into any specific topic!
