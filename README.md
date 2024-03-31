# Predicting-Customer-Churn
The project aims to build a predictive model for Beta Bank to anticipate customer churn. By analyzing past behavior and contract terminations, the goal is to predict whether a customer is likely to leave the bank. The dataset includes features like credit score, geography, age, and balance.

Key steps:

1. Data Preparation: Download and prepare the dataset by handling missing values and encoding categorical variables.

2. Class Imbalance Examination: Assess the balance of classes to understand the distribution of the target variable ('Exited').

3. Initial Model Training: Train a baseline model without considering class imbalance to establish a performance baseline.

4. Improving Model Quality: Implement strategies to address class imbalance, such as oversampling or undersampling, and train different models to find the best performer.

5. Final Testing: Evaluate the model's performance using the test set, focusing on metrics like F1 score and AUC-ROC to assess predictive accuracy.

Through these steps, the project aims to develop a robust model that helps Beta Bank identify customers at risk of leaving, enabling proactive retention efforts.


## Environment Set Up
This project is Python in a Jupyter notebook. The following packages are required:
- Pandas
- NumPy
- Scikit Learn 
- Matplotlib.pyplot 