# DATA-DRIVEN-FORECASTING-OF-RICE-PRODUCTION-IN-SRI-LANKA-USING-SARIMAX-AND-MACHINE-LEARNING-MODELS-





##### This project presents a comprehensive forecasting model for rice production in Sri Lanka, integrating time series analysis and machine learning techniques. Focusing on the Yala and Maha cultivation seasons, the study investigates how seasonal patterns, climatic conditions (like rainfall and temperature), and agricultural inputs (harvested area) influence rice yield.

##### Objective
###### To develop an accurate and data-driven rice production forecasting model that incorporates external climatic variables, improves forecasting performance, and supports better agricultural decision-making in Sri Lanka.

##### Key Highlights
###### Collected and preprocessed historical data on rice production, rainfall, temperature, and harvested area.

###### Identified key influential features using correlation analysis.

###### Applied log transformation to normalize data and improve model performance.

##### Built and compared:

###### SARIMAX(1,1,1)(1,1,0,2) – Best statistical model based on AIC/BIC and diagnostics.

###### Random Forest Regressor

###### XGBoost Regressor

###### Evaluated models using RMSE, MAE, and R² score.

###### Found SARIMAX to perform best overall in capturing seasonal trends and producing consistent forecasts.

##### Results
###### SARIMAX showed better performance in time-dependent forecasting compared to machine learning models.

###### Forecasts generated for:

###### Maha 2024

###### Yala 2025

###### Maha 2025

##### Tools & Libraries
###### Python

###### statsmodels (for SARIMAX)

###### scikit-learn (for Random Forest)

###### XGBoost

###### Pandas, NumPy, Matplotlib, Seaborn

##### Visualizations
###### Time series decomposition and stationarity testing

###### Feature correlation heatmaps

###### Model evaluation plots (Actual vs. Predicted)

###### Forecast charts for future seasons

##### Impact
###### This project supports evidence-based agricultural planning, helping policymakers and farmers anticipate seasonal yield variations and make informed decisions using data science.

