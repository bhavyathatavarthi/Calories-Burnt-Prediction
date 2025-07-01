# Calories-Burnt-Prediction
This Project focuses on Building a Machine learning model to predict the number of calories burnt during physical activities using machine learning algorithms.The model is trained using XGBRegressor for better Predictions.Cross validation is performed to select the best model from LinearRegression,SVR,RandomForestRegressor,Ridge,Lasso among them XGB Regressor has highest accuracy.The dataset obtained from Kaggle and preprocessing steps such as Label Encoding were applied.
## Dataset
The dataset used for this project is from kaggle: https://www.kaggle.com/datasets/fmendes/fmendesdat263xdemos? select=exercise.csv
https://www.kaggle.com/datasets/fmendes/fmendesdat263xdemos?select=calories.csv 
These  datasets gives us information about calories,gender,age,Height,Weight,Duration,Heart Rate,Body Temperature etc.
## Preprocessing Steps:
Before Training THe Model,following Preprocessing steps were applied:
Label Encoding: The Gender column is likely categorical with values "Male" and "Female",we use Label Encoding to convert these text values into numbers
## Model: XGB Regressor
XGBoost (Extreme Gradient Boosting) is one of the most efficient and accurate machine learning algorithms for structured data. It handles missing values, provides regularization, and performs well without extensive feature scaling.
This machine learning project uses the XGBoost Regressor to accurately predict the number of calories burnt during physical activity based on physiological and activity-related features.This regression task is useful in health and fitness applications like calorie trackers, fitness wearables, and personalized workout planning.
## Results:
📊 Model Performance for Training Data
| Metric              | Value    |
| ------------------- | -------- |
| Mean Squared Error  | `1.677` |
| Mean Absolute Error | `0.93`   |
| R² Score            | `0.99`   |

📊 Model Performance for Testing Data
| Metric              | Value    |
| ------------------- | -------- |
| Mean Squared Error  | `4.71` |
| Mean Absolute Error | `1.48`   |
| R² Score            | `0.99`   |

