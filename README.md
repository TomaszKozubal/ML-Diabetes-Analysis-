# Diabetes Prediction Using Logistic Regression

This project builds a machine learning model to predict diabetes based on patient data. The dataset is processed and modeled using **Logistic Regression**, with performance evaluated on both training and test datasets. The project also explores Ridge regularization (`L2` penalty) to try to improve model performance.

## Features

- **Data Preprocessing**: 
  - Handles missing values and standardizes features using `StandardScaler`.
  - Splits the dataset into training and testing sets.
- **Model Building**: Implements Logistic Regression to classify diabetes outcomes.
- **Performance Evaluation**: 
  - Evaluates model accuracy on both training and test sets.
  - Compares the base model with Ridge regularization to optimize performance.

## Dataset

The dataset used for this project is sourced from a CSV file: `diabetes.csv`. The dataset includes features such as age, glucose levels, BMI, etc., with the target variable indicating diabetes outcome (`1` for positive, `0` for negative).

### Example Data

| Feature       | Value1 | Value2 | ... | Outcome |
|---------------|--------|--------|-----|---------|
| Pregnancies   | 6      | 1      | ... | 0       |
| Glucose       | 148    | 85     | ... | 1       |
| BloodPressure | 72     | 66     | ... | 0       |

## Technologies Used

- **Python**: Programming language.
- **Pandas**: Data manipulation and loading.
- **NumPy**: Array processing.
- **scikit-learn**: 
  - `LogisticRegression` for classification.
  - `StandardScaler` for feature scaling.
  - `train_test_split` for splitting datasets.
- **Jupyter Notebook**: For interactive development.
