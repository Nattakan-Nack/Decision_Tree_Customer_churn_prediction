# Decision_Tree_Customer_churn_prediction
Data Science Project by Using Python 

# Customer Churn Prediction Project

This project aims to predict customer churn using a **Decision Tree** model. The model is evaluated using **10-fold Cross Validation** to ensure robustness in performance.

### Dataset
The dataset contains information about customers, including:
- Gender
- Age
- Payment Method
- Last Transaction Date

The target column is `Churn`, which indicates whether a customer churned or not.

### Steps Involved:

1. **Data Cleaning and Preprocessing**:
   - Handle missing values
   - Convert categorical columns to numerical using Label Encoding

2. **Feature Selection**:
   - Selected features for the model: `Gender`, `Age`, `Payment Method`, `LastTransaction`
   - The target feature is `Churn`

3. **Model Building**:
   - A **Decision Tree Classifier** is used to build the model
   - Performed **10-fold Cross Validation** to evaluate model performance

4. **Model Evaluation**:
   - Confusion Matrix is used to evaluate model performance
   - Metrics include **Precision**, **Recall**, and **F1-score**

5. **Conclusion**:
   - The model achieved a satisfactory accuracy using the Decision Tree algorithm.
   - For further improvements, other algorithms like Random Forest or Gradient Boosting can be tried.


