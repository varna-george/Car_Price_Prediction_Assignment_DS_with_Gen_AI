Data Science with Gen AI - Car Price Prediction - Coding - Intermediate Assessment

Problem Description:

A Chinese automobile company aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts. They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. Essentially, the company wants to know:

Which variables are significant in predicting the price of a car?

How well those variables describe the price of a car?

Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars across the American market.

Business Goal:

To model the price of cars with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy, etc., to meet certain price levels. Further, the model will be a good way for the management to understand the pricing dynamics of a new market.


Dataset Description – Car Price Assignment

The dataset contains information about 205 cars with 26 variables, including car specifications and their corresponding prices. The target variable is price, representing the car's market price in USD.

Key steps followed:
1. Loaded and Preprocessed [Dropped CarID, Inconsistencies in CarName were corrected, Outliers were removed, skewness of the numerical columns is within an acceptable range, so no transformations were applied]
2. Using heatmap it is understood that price is strongly influenced by size (weight, width, length), engine power, and inversely by fuel efficiency (MPG).
3. Models implemented: Linear Regression, Decision Tree Regressor, Random Forest Regressor, Gradient Boosting Regressor, Support Vector Regressor
