# Diabetes Progression Prediction

## Project Overview

This project uses Machine Learning to predict diabetes disease progression using a Linear Regression model.

The project uses the diabetes dataset containing 442 observations and 10 input features. Exploratory Data Analysis (EDA), correlation analysis, model development, evaluation, and feature influence analysis were performed.

## Dataset

The dataset contains the following input features:

- Age
- Sex
- BMI
- Blood Pressure (BP)
- S1
- S2
- S3
- S4
- S5
- S6

### Target Variable

- Disease Progression

The dataset contains:

- **442 observations**
- **10 input features**
- **1 target variable**
- **No missing values**

## Project Workflow

The project follows these steps:

1. Load the diabetes dataset
2. Inspect the dataset structure
3. Check for missing values
4. Perform Exploratory Data Analysis
5. Analyze feature correlations
6. Split the data into training and testing sets
7. Build a Linear Regression model
8. Generate predictions
9. Evaluate model performance
10. Analyze feature influence
11. Compare actual and predicted values
12. Draw conclusions

## Machine Learning Model

A **Linear Regression** model was developed to predict diabetes disease progression.

### Model Performance

| Metric | Score |
|---|---:|
| R² Score | 0.4526 |
| MAE | 42.79 |
| RMSE | 53.85 |

The R² score of **0.4526** indicates that the model explains approximately **45.3% of the variation** in disease progression in the test dataset.

The MAE of **42.79** represents the average absolute prediction error, while the RMSE of **53.85** gives greater weight to larger prediction errors.

## Feature Influence

The regression coefficients were analyzed to identify influential features.

The three strongest features based on the absolute coefficient values were:

1. **S1** — coefficient: -931.49
2. **S5** — coefficient: 736.20
3. **BMI** — coefficient: 542.43

The negative coefficient for S1 indicates a negative relationship with predicted disease progression when the other features are held constant.

The positive coefficients for S5 and BMI indicate positive relationships with the prediction.

## Visualizations

The project includes visual analysis such as:

- Feature distributions
- Correlation analysis
- Correlation heatmap
- Actual vs Predicted visualization
- Feature influence analysis

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project File

The complete analysis and model implementation are available in:

`Diabetes_Progression_Prediction.ipynb`

## Conclusion

A Linear Regression model was successfully developed to predict diabetes disease progression using 10 input features.

The model achieved an R² score of **0.4526**, with an MAE of **42.79** and an RMSE of **53.85**.

The results indicate that Linear Regression provides a useful baseline model for predicting disease progression, although a substantial amount of variation remains unexplained.
