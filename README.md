# rossmann-store-sales

## CONTEXT:
Sales forecasting plays an integral role in setting expectations and making plans for your business. It’s your best shot at predicting the future. Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. You are provided with historical sales data for 1,115 Rossmann stores. 

## Project objective:
   Forecast sales using store, promotion, and competitor data
   
## Approch:
Importing the required libraries and reading the dataset.

a. Merging of the two datasets

b. Understanding the dataset

Exploratory Data Analysis (EDA) –

a. Data Visualizatiom

Feature Engineering

a. Dropping of unwanted columns and values (closed stores)

b. Filling Missing Values with Imputation

c. Outliers Detection and removal

Further Exploratory Data Analysis to find out a few exceptional cases.

Label Encoding (Converting categorical variables to numerical values)

Model Building

a. Performing train test split

b. Linear Regression Model

c. SGD Regression Model

d. Decision Tree Regression Model

e. Random Forest Regression Model

Model Validation

a. r2 score

b. Mean absolute error

c. Root mean squared error

Creating the final right model and making predictions

Feature Importance Analysis

ConclusionI will be performing an exhaustive analysis in order to gain insights and engineer features with an interactive exploratory analysis and finally will use XGB to predict.
