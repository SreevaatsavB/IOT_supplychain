# IOT_supplychain

# Problem Statement:
One of the largest retail chains in the world seeks to accurately forecast sales for each SKU in its 76 different stores using historical sales and promotional data. Despite limited information about products and stores, this project aims to provide precise sales predictions for the next 12 weeks.


# Approach:
Formulated the problem as a regression task with 'units_sold' as the target variable.
Engineered essential features, including counts, averages, and temporal data (weeks, months, and year) to enhance model performance.
Applied sine and cosine transformations to capture cyclic trends in the data.
Utilized MEstimateEncoder for categorical encoding of 'sku-id' and 'store-id.'
Trained and tuned Random Forest and LightGBM Regressors to achieve accurate sales forecasts.

# Final Prediction:
File is named as "sales_forecast_submission.csv" which contains the final outputs we got.
