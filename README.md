# Retail Sales Forecasting for Rossmann

Rossmann, a retail chain with over 3,000 drug stores across 7 European countries, faces the challenge of predicting daily sales for up to six weeks in advance. Various factors, such as promotions, competition, holidays, seasonality, and locality, contribute to the complexity of this prediction task. Given the diverse circumstances of individual store managers, the accuracy of sales predictions varies significantly.

## Problem Statement

The goal is to forecast the "Sales" column for the test set using historical sales data from 1,115 Rossmann stores. This dataset includes information on store characteristics, customer count, open status, holidays, and other relevant features. Some stores were temporarily closed for refurbishment, adding an additional layer of complexity.

## Data Overview

The dataset, consisting of 1,017,209 rows and 18 columns, represents Rossmann's operations in 7 European countries. The data contains essential information such as store ID, sales, customer count, open status, holiday indicators, store type, assortment level, competition distance, and promotional activities.

[Link to Dataset](https://www.kaggle.com/competitions/rossmann-store-sales/data)

## Variables Description

The dataset includes various variables such as store ID, sales turnover, customer count, open status, state holidays, school holidays, store type, assortment level, competition distance, and promotional information.

## Data Wrangling and Visualization

Data wrangling involves transforming raw data into a suitable format for analysis, including cleaning, organizing, and transforming data. Data visualization is used to represent information graphically for better understanding. Both processes are crucial for ensuring data quality and consistency.

## Hypothesis Testing

Hypothesis testing includes normality tests using the Shapiro-Wilk test and independent sample t-tests to compare means. The analysis involves exploring and validating assumptions, such as the average sale of one year being greater than the previous year.

## Feature Engineering & Data Pre-processing

Feature engineering and data pre-processing encompass handling missing values, outliers, categorical encoding, feature manipulation, data transformation, and data scaling. These steps contribute to creating a robust and accurate predictive model.

## ML Model Implementation

Various machine learning models, including linear regression, decision tree regression, random forest regressor, lasso, and ridge regression, were implemented. The random forest regressor demonstrated superior performance with the highest predictive accuracy.

## Model Performance

The Random Forest Regressor achieved an accuracy of 93.77%, outperforming other models like linear regression and decision tree regression. Hyperparameter tuning and cross-validation were employed to enhance the model's performance and generalization to unseen data.

## Conclusion

The Rossmann Store Sales prediction challenge involved selecting relevant store features and implementing various machine learning models. The Random Forest Regressor emerged as the most accurate model, achieving a prediction accuracy of 93.77%. Careful consideration of data trends, feature importance, and model selection contributed to the success of the sales forecasting task. The findings demonstrate the effectiveness of data-driven approaches in predicting retail sales for a large and diverse retail chain like Rossmann.
