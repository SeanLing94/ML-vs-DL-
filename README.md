# ML-vs-DL-
Advanced Time Series Demand Forecasting for Retail Using Artificial Intelligence and External Factors

Objectives
•	To evaluate the impact of external factors, such as holidays and oil price, on the accuracy of retail demand forecasting using advanced machine learning and deep learning models.
•	To systematically compare the performance of machine learning and deep learning models, using RMSLE as the primary evaluation metric, to identify the most accurate and efficient approach for demand forecasting.
•	To identify the optimal model that balances predictive accuracy and computational efficiency, ensuring scalability and practical application for retail demand forecasting.

•	Data Collection: Combining different datasets (sales, store, holiday, oil, etc.).
•	Feature Engineering: Featurization for temporal and contextual understanding, including lagged, rolling, and interaction features.
•	Model Development: Both ML models (e.g. RFR, XGB, GBR, SVR), DL architectures (e.g. CNN, LSTM, Transformer) are described.
•	Selection of Best Models: The data was split using 70:15:15 ratio, and evaluation metrics were presented for the models with basic setting, with a focus on RMSLE. Additional issues such as computational limitations and overfitting are discussed, as well as ethical implications of using data.
•	Comparison with and without Dataset with External Factors: Finally, Evaluation Metrics is discussed on the hyperparameter tuning with set up best setting and focus on the best models from ML and DL categories.

Summary of Key Findings 
This study explored advanced demand forecasting techniques by evaluating a combination of machine learning (ML) and deep learning (DL) models, with and without the integration of external factors. Among ML models, Random Forest Regressor (RFR) consistently provided the best balance between accuracy and computational efficiency, achieving a notable RMSLE of 0.1807 with external factors. In the meantime, although XGBoost was efficient, it couldn't match the accuracy of RFR and even after hyperparameter tuning its RMSLE became 0.2977 over 0.2597 prior to tuning. For DL models, Convolutional Neural Networks (CNN) emerged as the top performer, demonstrating competitive RMSLE values of 0.8343 with external factors and 0.8354 without, combined with significantly faster training times compared to LSTM and Transformer models.
The inclusion of external factors yielded mixed results. Their impact was marginal for XGBoost and CNN though, thus implying that it’s a challenge to effectively bring in such factors. RMSLE was validated as a primary metric for use, as it allows the proportional errors to be more effectively evaluated than RMSE and MAE. These results are consistent with the goal of the project, and provide a thorough comparison of decision making using ML and DL in demand forecasting. 
