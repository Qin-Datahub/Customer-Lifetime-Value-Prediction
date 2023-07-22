![image](streamlit_1.png)
![image](streamlit_2.png)

## **Introduction**

This repo contains code and resources for predicting the Customer Lifetime Value, an essential metric that helps businesses understand the long-term value of their customers. By utilizing the power of XGBoost algorithm, this project aims to deliver accurate predictions to aid in strategic decision-making and customer segmentation.


### Explore Documents

* Data Transformation and Feature Engineering: The `main.ipynb` Jupyter Notebook provides a comprehensive pipeline for data transformation, exploratory data analysis (EDA), and feature engineering. Here, we calculate Recency, Frequency, and Monetary (RFM) features to quantify customer behavior and create informative predictors for the model.

* Model Training and Evaluation: The `main.ipynb` also encompasses the training and hyperparameter tuning of the XGBoost model using the `xgboost.cv` function. The model's performance is evaluated using appropriate metrics, ensuring its accuracy and reliability.

* Visualization using Streamlit: The `visualization.py` script contains the code to create an interactive Streamlit app that demonstrates the results of the CLV prediction model. The app allows users to understand and segment their customer base effectively.
