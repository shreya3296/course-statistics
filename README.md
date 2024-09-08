# Advanced Quantitative Methods I (API-209)

**Institution**: Harvard Kennedy School  
**Course Instructor**: Professor Dan Levy  
**Course Description**:  
This course provides an in-depth study of advanced statistical and econometric techniques used in data analysis. The focus is on hypothesis testing, regression analysis, predictive analytics, and simulation methods. Practical applications in data science and quantitative analysis are explored through problem sets covering real-world datasets in domains like elections, labor markets, and public health. Students develop proficiency in statistical programming using R.

## Key Concepts and Applications

### 1. Hypothesis Testing
#### Concept:  
Hypothesis testing is a core statistical technique used to make decisions based on sample data. It involves formulating null and alternative hypotheses, calculating test statistics, and determining p-values to decide whether to reject the null hypothesis. Confidence intervals and chi-square tests are also essential in understanding statistical significance.
#### Techniques Covered:  
- One-sample and two-sample hypothesis tests for proportions and means.
- Confidence intervals for means and proportions.
- Chi-square goodness-of-fit and independence tests.
  
#### Applied In:  
**Problem Set 2: Venezuelan Election Fraud Analysis**  
In this problem, we applied hypothesis testing to evaluate whether the identical number of “Yes” votes across voting machines in Venezuela’s referendum was due to chance or indicative of fraud. Using the binomial distribution and chi-square test for goodness of fit, we analyzed voting patterns for multiple machines, calculating the probability of observing identical vote counts by random chance.

---

### 2. Probability and Sampling Distributions
#### Concept:  
Sampling distributions describe how a statistic (e.g., sample mean, sample proportion) behaves across repeated samples from the population. These distributions form the basis of inference, allowing us to understand the variability of sample statistics and make predictions about populations. We primarily used the binomial, normal, and t-distributions in this course.
#### Techniques Covered:  
- Central Limit Theorem and its role in approximating sampling distributions.
- Calculation of probabilities using the binomial and normal distributions.
- Confidence intervals and margins of error.

#### Applied In:  
**Problem Set 1: Elections in Venezuela**  
Using the binomial distribution, we simulated election results and calculated the probabilities of specific voting outcomes across multiple voting centers. This was critical in determining the likelihood of observing identical vote counts in two voting machines, providing a basis for inferring whether fraud could be suspected.

**Problem Set 3: Colombian Presidential Election Simulation**  
The probability of different election outcomes was modeled using random sampling techniques to simulate Petro’s win margin in the 2022 Colombian presidential election. Various sample sizes were used to explore how sample size impacts the accuracy of win margin estimates.

---

### 3. Regression Analysis
#### Concept:  
Regression analysis is used to model relationships between a dependent variable and one or more independent variables. The course covers both Ordinary Least Squares (OLS) for linear relationships and penalized regression methods like Lasso for variable selection and handling multicollinearity.
#### Techniques Covered:  
- Simple and multiple OLS regression.
- Interpretation of coefficients, R-squared, and adjusted R-squared.
- Hypothesis testing for regression coefficients.
- Introduction to Lasso regression for model selection and dealing with multicollinearity.

#### Applied In:  
**Problem Set 7: Predicting Injury Rates using Lasso**  
Using data from OSHA, we predicted workplace injury rates by fitting a series of models, including OLS and Lasso regression. Lasso was particularly useful in selecting important predictors from a large set of variables, penalizing less significant coefficients and improving the model's predictive accuracy. Cross-validation was used to select the optimal penalty parameter (lambda) for Lasso.

**Problem Set 10: U.S. Midterm Election Prediction**  
OLS was used to predict Republican win probabilities across congressional districts. The model's performance was evaluated using Mean Squared Error (MSE), and we simulated election outcomes using the predicted probabilities.

---

### 4. Predictive Analytics and Machine Learning
#### Concept:  
Predictive analytics uses historical data to make predictions about future outcomes. In this course, we explored machine learning models like Lasso regression, along with techniques for cross-validation and model evaluation. Predictive modeling focuses on improving out-of-sample performance.
#### Techniques Covered:  
- Cross-validation for model tuning.
- Lasso regression for variable selection.
- Predictive performance measures such as Mean Squared Error (MSE).

#### Applied In:  
**Problem Set 9: Worker Safety Prediction**  
Using OSHA data, we applied Lasso and Ridge regression to predict workplace injury rates. The model selection process was guided by cross-validation to ensure robust predictions, and the models were evaluated based on their predictive performance using MSE on both training and test datasets.

---

### 5. Simulation Methods
#### Concept:  
Simulation is a statistical technique used to model complex systems or processes by generating random samples from probability distributions. In this course, simulations were used to explore election outcomes, hypothesis testing results, and probabilities of rare events.
#### Techniques Covered:  
- Monte Carlo simulations to assess uncertainty and variability.
- Simulation-based inference to approximate probabilities of election outcomes.

#### Applied In:  
**Problem Set 8: U.S. Election Simulations**  
We used Monte Carlo simulations to model the U.S. midterm election outcomes by simulating results across congressional districts. By generating random samples from predefined probabilities, we predicted the number of seats won by Republicans and visualized the results through histograms.

---

### 6. Inequality Measurement: Gini Coefficient
#### Concept:  
The Gini coefficient is a measure of income inequality, ranging from 0 (perfect equality) to 1 (perfect inequality). We calculated Gini coefficients to assess income distribution across different populations.
#### Techniques Covered:  
- Calculation of Gini coefficients.
- Construction of Lorenz curves.
- Interpretation of income inequality metrics.

#### Applied In:  
**Problem Set 6: Namibia Labor Market Analysis**  
Using the Namibia Labor Force Survey, we calculated the Gini coefficient to measure income inequality. The analysis included weighted and unweighted Gini coefficients, allowing us to understand the distribution of income across the population and evaluate whether Namibia's income inequality was unusually high.

---

## Tools and Software:
- **R Programming**:  
   All problem sets and data analyses were conducted using R, with a focus on libraries like `ggplot2`, `dplyr`, `glmnet`, and `tidyverse` for data manipulation, visualization, and modeling.
  
- **Statistical Techniques**:  
   The course emphasized rigorous statistical techniques such as hypothesis testing, regression, Lasso, and simulation-based approaches, all central to advanced data science and quantitative analysis.
