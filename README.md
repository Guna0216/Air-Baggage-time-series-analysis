**Overview:**
- This project analyzes baggage complaints for American Eagle, Hawaiian, and United Airlines using advanced data preprocessing and Seasonal ARIMA (SARIMA) modeling. 
- The study focuses on identifying trends and seasonality in the data to forecast future complaint trends, aiding airlines in improving customer service.


**Data Preprocessing:**
- Adjusted Hawaiian Airlines complaints for flight volume.
- Scaled United Airlines complaints relative to enplaned trips, considering its larger size.


**Modeling Approach and Evaluation:**
- Identified stable/increasing trends and seasonal patterns for all airlines.
- Basic models (Drift, Mean, Naïve, Seasonal Naïve) and ETS(AAA) model were initially used but had limitations.
- SARIMA model chosen due to its effectiveness in handling seasonality.
- Residual analysis confirmed SARIMA's reliability, with random errors and normally distributed residuals.
  - The lower AIC and BIC values mathematically prove the efficiency of SARIMA models.
- The greater p_values for SARIMA indicate better performance among other models.


**Results and Conclusion:**
- SARIMA outperformed other models in predicting baggage complaint trends.
- Its accurate historical pattern reflection, significant p-value, and stationary residuals make it a robust forecasting tool.
- No time-dependent patterns in residuals indicate forecast reliability.
- Future work could include expanding datasets, integrating more predictors, or using machine learning for refinement.
