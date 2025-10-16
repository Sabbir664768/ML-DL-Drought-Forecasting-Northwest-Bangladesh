# ML-DL-Drought-Forecasting-Northwest-Bangladesh

**Title:** Evaluation of machine learning and deep learning models for forecasting drought vulnerability in the northwestern region of Bangladesh 

**Abstract**

**Background**

Agriculture, a cornerstone of Bangladesh's economy, is highly susceptible to weather extremes and water shortages, notably drought. The northwestern region, with its semi-arid climate, faces significant drought vulnerability, impacting millions. The objective of this study is to evaluate and compare advanced machine learning and deep learning-based models for forecasting drought vulnerability in this region, addressing a critical gap in localized drought prediction. 

**Methods**

This study focuses on the northwestern region of Bangladesh, specifically using meteorological data from the Rangpur division. The primary data source is the daily rainfall time series from 1981 to 2021, provided by the Bangladesh Meteorological Department. The Standardized Precipitation Index (SPI) is employed to assess drought, with calculations facilitated by the Standardized Drought Analysis Toolbox (SDAT) for enhanced accuracy. Machine learning models, including K-Nearest Neighbors, Random Forest, XGBoost, AdaBoost, CatBoost, and Gradient Boosting, along with deep learning models such as Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks, are utilized to forecast drought vulnerability. The study emphasizes ensemble methods and uncertainty estimation techniques like Bayesian deep learning and Monte Carlo dropout to improve prediction accuracy and reliability. Data quality is ensured through rigorous testing, including the Augmented Dickey-Fuller test for stationarity. The performance of the model is assessed using metrics such as R², RMSE, MAE, and Pearson's correlation coefficient, alongside visual analyses to assess prediction accuracy and biases.

**Results**

The study discovered no specific trend in any of the SPI time series. Among the models, CNN and LSTM had the best fit for SPI-3, SPI6 and SPI-12. Particularly, CNN had R2 value of 58%, 57% and 56% for SPI-3, SPI-6 and SPI-12, respectively. Like R2, CNN also had superior performance metrics. In SPI-3, CNN had values of 69%, 58% and 85% for MAE, NSE and index of agreement, respectively. Similar results were found for SPI-6 and SPI-12 as well. Boosting algorithms such as XGBoost, Gradient Boosting also generally scored high on several performance metrics. On the other hand. KNN and Adaptive Boosting had consistently the worst fit among all the models. KNN had the lowest R2 values of 39% and 37% in SPI-3 and SPI-6, respectively. Adaptive Boosting had the worst fit in SPI-3 and had the lowest R2 value of 30%.

**Conclusion**
In the study, deep learning models have achieved better results than conventional machine learning models. Specifically, CNN and LSTM outperformed all other models in almost all performance metrics for all of SPI-3, SPI-6 and SPI-12. The study suggests using deep learning-based models like CNN and LSTM for predicting drought vulnerability.

