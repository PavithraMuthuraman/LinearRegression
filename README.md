# LinearRegression
A linear regression model for predicting insurance costs

**Description:** This project involves predicting insurance costs based on various features using a Linear Regression model. The dataset used contains information about individuals and their insurance expenses. By applying linear regression, the goal is to estimate insurance costs based on features such as age, gender, and health conditions.

**Project Overview:**
- **Objective**: Estimate the insurance cost for individuals based on their characteristics using the trained Linear Regression model.
- **Model**: Linear Regression is used to model the relationship between the input features and insurance costs.
- **Dataset**: The dataset includes various features that influence insurance costs, such as age, sex, BMI, number of children, and smoking status.

**Files Included**:
-	`LinearRegression.ipynb`: The Python script that performs data preprocessing, model training, and cost estimation.
-	`insurance.csv`: The dataset containing details about individuals and their insurance costs.

**Code Execution:**

1. **Setup Environment:** Install required libraries (numpy, pandas, scikit-learn).

2. **Data Loading:** Place `insurance.csv` in the appropriate directory, then load and inspect the dataset.
3. **Preprocessing:** Handle missing values, encode categorical variables, and split the data into features and labels.  
4. **Model Training:** Execute the script to train the Linear Regression model.  
5. **Prediction & Evaluation:** Predict insurance costs and assess the model's performance using Mean Absolute Error (MAE) and R-squared score.  
6. **Customize Input:** Modify the script's input data for different insurance cost estimates.
