🛒 Supermarket Sales Forecasting
Developed a sales forecasting model using historical supermarket data extracted from SQL Server. The project focused on improving forecast accuracy through rigorous preprocessing and model tuning.

Data Preprocessing: Detected and removed anomalies to enhance data quality. Applied Box-Cox transformation to stabilize variance in sales data.

Modeling: Explored multiple time series models including Holt-Winters, ARIMA, and SARIMA. However, these models struggled to capture yearly seasonality present in daily sales data.

Prophet Optimization: Transitioned to Facebook Prophet and significantly improved performance by incorporating custom seasonality components. This adjustment allowed the model to capture demand spikes during key periods like December–January (Christmas) and April–May (Easter).

Result: Achieved a MAPE of 18.34%, reflecting strong predictive capability after incorporating domain-specific seasonality.
