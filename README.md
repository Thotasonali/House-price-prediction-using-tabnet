# 🏠 House Price Prediction using TabNet (Deep Learning)

This project presents an end-to-end deep learning pipeline for predicting housing prices using the **TabNet architecture**, a state-of-the-art model designed specifically for tabular data. The project focuses on improving prediction accuracy through model experimentation, feature engineering, and optimizer tuning.



 Overview

Accurate house price prediction is a critical task in real estate analytics. Traditional machine learning models often struggle to capture complex relationships in structured data.

In this project, we explore **deep learning approaches for tabular data**, with a primary focus on **TabNet**, which uses sequential attention to perform dynamic feature selection.



 Objectives

- Build a robust regression model for housing price prediction  
- Apply deep learning techniques to structured/tabular datasets  
- Compare multiple neural network architectures  
- Evaluate the impact of different optimization strategies  


Models Implemented

- Feedforward Neural Network (FNN)  
- Deep Neural Network (DNN)  
- Wide & Deep Model  
- ⭐ TabNet (Best performing model)



Methodology

1. Data Preprocessing
- Handled missing values and categorical encoding  
- Normalized numerical features  
- Structured dataset for deep learning models  

2. Feature Engineering
- Created meaningful feature combinations  
- Improved model generalization  

3. Model Training
- Implemented models using **PyTorch**  
- Trained multiple architectures for comparison  

4. Optimization Experiments
Tested multiple optimizers:
- Adam  
- AdamW  
- Ranger  
- Lion  


Tech Stack

- Python  
- PyTorch  
- pytorch-tabnet  
- Pandas, NumPy  
- Scikit-learn  

 Results

| Model        | Performance |
|-------------|------------|
| FNN         | Baseline   |
| DNN         | Improved   |
| Wide & Deep | Better     |
| TabNet  |  Best (RMSE ≈ 0.52) |


Evaluation Metrics

- Root Mean Squared Error (RMSE)  
- Mean Absolute Error (MAE)  



