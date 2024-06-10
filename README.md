# Supply Chain Analytics and Demand Forecasting

## Project Overview
This project is divided into two main parts: Supply Chain Analytics and Demand Forecasting. The objective is to leverage advanced analytics and forecasting models to provide insights for better decision-making in supply chain management.

## Business Understanding
Effective demand forecasting is crucial for maintaining optimal inventory levels, reducing stockouts, and minimizing excess inventory. This project addresses the business problem of predicting weekly sales units for various store-SKU combinations, which helps in making informed decisions regarding inventory management and promotional planning.

## Modeling and Evaluation
The following models were used for demand forecasting:
1. MSTL (Multiple Seasonal-Trend decomposition using Loess) is a statistical model for decomposing time series data into its trend, seasonal, and residual components.
2. TimeGPT, a generative pre-trained transformer model for time series forecasting.

**Evaluation Metrics**:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
### Model Comparison

![Model Evaluation](modelres.png)

- The MSTL model generally provides more accurate and robust predictions compared to the TimeGPT model, as evidenced by the
tighter distribution of residuals around zero and fewer extreme residuals.


## Conclusion
The demand forecasting model developed in this project provides valuable insights into future product demand, enabling retail managers to make informed inventory decisions. The model's predictions help in reducing both stockouts and overstock situations, ultimately leading to cost savings and improved customer satisfaction. Future steps include incorporating additional features such as promotional events and competitor pricing to further enhance the model's accuracy and applicability.


