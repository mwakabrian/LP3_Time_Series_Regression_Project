
# Favorita Stores Sales Time Series Forecasting

## Introduction

Corporacion Favorita, based in Ecuador, focuses on organizing, installing, and managing stores, markets, and supermarkets. The project aims to optimize inventory management through accurate product demand forecasting. This involves predicting sales, aligning supply with demand, reducing waste, enhancing customer satisfaction, and ultimately increasing sales revenue. The key stakeholders are inventory managers, supply chain managers, and store managers relying on the predictive model for informed decision-making.

## Business Understanding

Accurate demand forecasting is crucial for brick-and-mortar grocery stores to manage inventory effectively. The challenge involves balancing stock levels to avoid overstocking perishable goods or running out of popular items. Machine learning offers a solution by providing more accurate forecasting, ensuring optimal product availability, reducing waste, and improving customer satisfaction.

## Statement Of The Problem

Brick-and-mortar grocery stores face challenges in forecasting product demand, leading to issues of overstocking or stockouts. Current subjective forecasting methods lack data support and automation. Machine learning, through more accurate forecasting, can address these challenges, reduce food waste, and enhance customer satisfaction.

## Project Description

The project employs regression, a supervised machine learning technique, to predict grocery store sales at Favorita stores in Ecuador. The model uses historical data, including dates, store and product information, and promotional activities. The objective is to develop an accurate predictive model that minimizes overstocking, reduces food waste, and improves customer satisfaction.

## The Task

This project deals with a Time Series Forecasting problem, predicting future values based on historical data patterns. Various machine learning models, including Time Series Forecasting techniques and Regression Models, will be explored, evaluated, and compared to select the best-performing model for predicting future grocery sales.

## Project Methodology

The project follows the CRISP-DM framework, consisting of phases like Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, Deployment, and Maintenance. Different machine learning algorithms will be considered, and the model's performance will be assessed using metrics like RMSLE, RMSE, and MAE.

## Explanation Of Features

### File Descriptions and Data Field Information

**1. train.csv:**
   - Contains time series data with features like store_nbr, family, onpromotion, and target sales.

**2. test.csv:**
   - Similar features as training data, used for predicting target sales for the subsequent 15 days after the last training data date.

**3. transaction.csv:**
   - Includes date, store_nbr, and transactions made on specific dates.

**4. sample_submission.csv:**
   - A sample submission file in the correct format.

**5. stores.csv:**
   - Store metadata, including city, state, type, and cluster.

**6. oil.csv:**
   - Daily oil prices during both train and test data timeframes.

**7. holidays_events.csv:**
   - Holidays and events metadata.

## Hypothesis

**Null Hypothesis (H0):**
   - "The presence of products on promotion does not have a statistically significant impact on store sales."

**Alternative Hypothesis (Ha):**
   - "There is a statistically significant relationship between the presence of products on promotion and store sales."

## Research Questions

1. Is the train dataset complete (has all the required dates)?
2. Which dates have the lowest and highest sales for each year?
3. Did the earthquake impact sales?
4. Are certain groups of stores selling more products? (Cluster, city, state, type)
5. Are sales affected by promotions, oil prices, and holidays?
6. What analysis can we get from the date and its extractable features?
7. What is the difference between RMSLE, RMSE, MSE (or why is the MAE greater than all of them)?
