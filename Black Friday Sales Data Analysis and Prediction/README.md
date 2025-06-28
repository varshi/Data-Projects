# Black Friday Sales Data Analysis and Prediction

## Project Overview

This project analyzes the Black Friday sales dataset to understand customer purchasing behavior, identify key factors influencing sales, and build a predictive model for purchase amounts. The analysis involves data loading, exploration, cleaning, feature engineering, model training, and evaluation.

## Dataset

The dataset used in this project is `train.csv`, containing Black Friday sales transactions. It includes information about users, products, and purchase details.

## Analysis and Key Findings

The exploratory data analysis (EDA) revealed several insights into the sales data:

*   The distribution of purchase amounts is right-skewed, indicating a higher frequency of smaller purchases.
*   Males tend to have a slightly higher average purchase amount than females.
*   Customers in City Category 'C' show a higher average purchase amount.
*   Marital status and years in the current city have minimal impact on average purchase.
*   Product Category 1 significantly influences purchase amounts, with certain categories having much higher average purchases.

Missing values in `Product_Category_2` and `Product_Category_3` were handled by filling them with 0.

## Predictive Modeling

A Random Forest Regressor model was trained to predict the 'Purchase' amount.

### Model Performance

*   **Mean Absolute Error (MAE):** 2161.9225884252955
*   **Mean Squared Error (MSE):** 8999953.607929323
*   **Root Mean Squared Error (RMSE):** 2999.9922679782567
*   **R-squared (R2) Score:** 0.6418097129106892

### Feature Importance

The model's feature importance analysis highlighted the most influential factors for predicting purchase amount:

*   **Product\_Category\_1:** The most significant predictor.
*   **User-specific purchase history (average and total purchase):** Important indicators of future spending.
*   **Product\_Category\_2 and Product\_Category\_3:** Contribute to predictions, but less than Product Category 1.
*   Other features like Occupation, demographics (Gender, Age), and location (City Category, Stay in City Years, Marital Status) had lower importance in the model.

## Conclusion and Next Steps

The analysis confirms the strong influence of product categories and user purchase history on Black Friday sales.

Potential next steps include:

*   Focusing marketing strategies on high-value product categories and users with high historical spending.
*   Exploring alternative models or advanced feature engineering to potentially improve the prediction accuracy further.

## How to Run the Notebook

1.  Clone the repository to your local machine.
2.  Ensure you have Jupyter Notebook or Google Colab installed.
3.  Open the `your_notebook_name.ipynb` file (replace with your actual notebook name) in your preferred environment.
4.  Run the cells sequentially to replicate the analysis and modeling.

## Dependencies
*   Python 3.10.x
*   pandas
*   numpy
*   matplotlib
*   seaborn
*   scikit-learn

## Author

Varshith.A
[https://github.com/varshi]

