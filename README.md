---

# Multiple Linear Regression Model

## Overview
This project demonstrates the implementation of a **Multiple Linear Regression** model using Python and the `scikit-learn` library. 
The objective is to predict the dependent variable (target) based on multiple independent variables using data stored in a CSV file.

## Methodology

### Data Collection
- The dataset used in this project is stored in a CSV file named `company_.csv`.
- The dataset consists of multiple independent variables (features) and one dependent variable (target).

### Data Preprocessing
- The dataset is loaded using the `pandas` library.
- It is separated into independent features (`x`) and dependent labels (`y`).
- The dataset is then split into **75% training data** and **25% test data** using `train_test_split`.

### Data Visualization
- **Scatter plots** are drawn to display the relationship between individual features and the target variable.
- These visualizations help in identifying any linear trends between features and the target.

### Model Training
- A **Linear Regression** model is instantiated using `scikit-learn`.
- The model is trained on the training data to learn the relationship between the features and the target.
- The model's coefficients (slopes) and intercept are printed for better understanding.

### Prediction
- The trained model is used to make predictions on the test dataset.
- A table is created to compare the **actual** values with the **predicted** values.

### Evaluation
- The model’s performance is evaluated using:
  - **Mean Absolute Error (MAE)**: Measures the average absolute difference between the actual and predicted values.
  - **Mean Squared Error (MSE)**: Measures the average squared difference.
  - **R-squared (R²)**: Indicates how well the independent variables explain the variance in the dependent variable.

## Requirements
```bash
pip install pandas matplotlib scikit-learn
```

## Results
This project produces the following outputs:
- **Regression Coefficient** (Slope) and **Intercept** of the trained model.
- A table showing a comparison between **Actual** and **Predicted** values on the test set.
- The evaluation metrics:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R-squared (R²)

---
