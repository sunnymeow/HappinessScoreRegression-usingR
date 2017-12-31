# HappinessScoreRegression
Construct multivariate linear regression to predict the determinant factors for the Happiness Score in World's Happiness Report 2015

# 1. Data collection and preparation
* The data was collected from Kaggle.com based on World Happiness Report 2015
* 158 countries ranked by happiness scores following by 6 factors
* Remove all the NA values
* Investigate the predictors

# 2. Model selection
* AIC test (assume linear relation w/ interactions between factors)
* Linear Regression model based on correlation
  - ANOVA(full, reduced)

# 3. Model diagnosis
* Residual properties
* Residual normality
* Residual vs. predictors
* Constancy of error variance
* Data vs. model
* Outlier & Leverage

# 4. Model validation
* Used the fitted model to predict 2016 data and compare with the actual 2016 data


# Sample graphical analysis

![analysis](https://github.com/sunnymeow/HappinessScoreRegression/blob/master/res/HS_vs_Predictor.png)

# Comparison between predicted result and actual 2016 data

![prediction](https://github.com/sunnymeow/HappinessScoreRegression/blob/master/res/prediction.png)
