# Advanced Regression Assignment - House Price Prediction


A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

-   Which variables are significant in predicting the price of a house, and
    
-   How well those variables describe the price of a house.
    
Also, determine the optimal value of lambda for ridge and lasso regression.

**Business Goal**

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

# Solution
To solve this problem, I've taken a step-by-step approach, and with the help of the following steps, I've produced the best solution for addressing the business goals.

-   **Step 1: Reading the Data**
-   **Step 2: Data Quality, Duplicate Check and Cleansing**
-   **Step 3: Adding Feature Columns**
-   **Step 4: Converting Feature Values Into Categorical Values**
-   **Step 5: Understanding the Data by Visualizing**
-   **Step 6: Data Preparation**
-   **Step 7: Splitting the Data into Training, Testing Sets and Scaling**
-   **Step 8: Feature Selection**
-   **Step 9: Model Building (Linear, Ridge and Lasso Regression)**
-   **Step 10: Conclusion - Top 10 Feature Variables Affecting the House Price**

Also, this repository contains a PDF document answering the Subjective Questions.

## Technologies Used
python==3.9.12
- scikit-learn==1.2.1
- numpy==1.24.3
- pandas==2.0.1
- matplotlib==3.6.3
- statsmodels==0.14.0
- seaborn==0.12.2

