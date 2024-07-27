# US_Housing_Trends
Objective
This project aims to identify and analyze the key factors that have influenced U.S. home prices nationally over the past 20 years. By building a robust data science model, we aim to predict future home prices based on these influential economic factors.

Source of data collection:https://fred.stlouisfed.org/

Step 1: Data Collection

Home Prices Proxy: Utilized the S&P Case-Shiller Home Price Index, sourced from the Federal Reserve Economic Data (FRED) website, as a proxy for home prices.

Step 2:

Key Factors: Gathered publicly available data on various factors influencing home prices nationally, including:

The following variables are chosen for the study-
*Unemployment Rate
*Employment Rate
*Per Capita GDP
*Real Median Household Income
*Construction Prices
*CPI
*Interest Rates
*Number of new houses supplied
*Working Population
*Urban Population
*Percentage of population above 65
*Housing subsidies
*Number of Households

Step 3: Data Cleaning and Processing

Cleaned and processed the data, addressing missing values, converting date formats, and handling outliers.

Step 4: Exploratory Data Analysis (EDA)

Conducted EDA to understand the distribution of variables, identify correlations, and visualize trends over time.

Step 5: Model Selection

Explored various regression models, including:
*Linear Regression
*ElasticNet
*Random Forest
*Gradient Boosting
*Support Vector Regression (SVR)
*XGBoost

Step 6: Model Training and Evaluation

Trained each model using a subset of the data, evaluated performance using metrics such as Mean Squared Error (MSE) and R-squared.

Step 7: Feature Importance

Analyzed feature importance for models like Random Forest, XGBoost, and Gradient Boosting and identified key factors influencing home prices.

Step 8: Model Comparison

Compared the performance of different models based on MSE and R-squared metrics along side selecting the best-performing model that provides accurate predictions and insights into the factors influencing home prices over the last 20 years.

Step 9: Visualization

Created visualizations to illustrate the relationships between actual and predicted home prices for each model and visualized the importance of different features or coefficients in influencing home prices.

Conclusion

*Identified strong contenders for the best model based on low MSE and high R-squared values.

*Drew conclusions about the key factors that have historically influenced U.S. home prices.

Overall Implication

The project contributes to understanding the key factors influencing U.S. home prices over the last 20 years. It provides a foundation for building robust predictive models in the real estate domain, aiding in future forecasting and strategic planning.

Result 

![image](https://github.com/user-attachments/assets/f3a85ec5-061f-4272-9f04-925b1c6d30f9)
![image](https://github.com/user-attachments/assets/2a329908-fe04-44eb-ba39-b96c9819f3ec)
![image](https://github.com/user-attachments/assets/dab2504f-d0a1-4f4b-bdcd-5cbaab759fc2)

Based on the provided metrics, the Random Forest model is a strong candidate for the best model, with both a low MSE and a high R-squared value. Gradient Boosting and XGBoost also perform exceptionally well and could be considered strong alternatives. 

