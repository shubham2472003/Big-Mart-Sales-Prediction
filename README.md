# Big-Mart-Sales-Prediction



# Objective

The aim is to build a predictive model and find out the sales of each product at a particular store. Create a model by which Big Mart can analyse and predict the outlet production sales.

A perfect project to learn Data Analytics and apply Machine Learning algorithms (Linear Regression, Random Forest Regressor, DecisionTreeRegressor, ExtraTreesRegressor) to predict the outlet production sales.

# Business Understanding

Big Mart aims to optimize product sales across its retail stores. By leveraging historical sales data, the objective is to build a predictive model that can forecast future sales of individual products at different outlets. Accurate predictions will help in inventory planning, demand forecasting, and strategic decision-making, ultimately leading to increased efficiency and profitability.
___

# Dataset Description

BigMart has collected sales data from the year 2013, for 1559 products across 10 stores in different cities. Where the dataset consists of 12 attributes like Item Fat, Item Type, Item MRP, Outlet Type, Item Visibility, Item Weight, Outlet Identifier, Outlet Size, Outlet Establishment Year, Outlet Location Type, Item Identifier and Item Outlet Sales. Out of these attributes response variable is the Item Outlet Sales attribute and remaining attributes are used as the predictor variables.

The data-set is also based on hypotheses of store level and product level. Where store level involves attributes like:- city, population density, store capacity, location, etc and the product level hypotheses involves attributes like:- brand, advertisement, promotional offer, etc.

Dataset Link: https://www.kaggle.com/datasets/yasserh/bigmartsalesdataset

# Processing of Analysis

1.Data Cleaning: Handled missing values (e.g., item weights, outlet sizes) and fixed inconsistent labels (e.g., fat content categories).

2.Exploratory Data Analysis (EDA): Analyzed distributions, relationships, and correlations to understand key patterns.

3.Feature Engineering: Created new features (e.g., item category, years of operation) and transformed variables for better modeling.

4.Data Encoding: Converted categorical variables using Label Encoding and One-Hot Encoding.

5.Modeling: Trained multiple regression models including Linear Regression, Ridge, Lasso, Random Forest Regressor, DecisionTreeRegressor, ExtraTreesRegressor.

6.Model Evaluation: Compared models using metrics like RMSE to select the best-performing one.

# Conclusion

Machine learning models were used to predict Big Mart product sales. After preprocessing and analysis, models like Linear Regression, Ridge, Lasso, Random Forest Regressor, DecisionTreeRegressor accurate results, helping support better inventory and sales planning.




