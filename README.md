# Sales Data Analysis Project

## Introduction
This project focuses on building and evaluating various regression models to analyze a given sales dataset. The objective was to predict sales and analyze the effectiveness of various boosting and regression models to optimize prediction accuracy.

## Process

### Data Cleaning and Preprocessing:
- Imported the dataset and performed necessary preprocessing steps like handling missing values, scaling numerical features, and encoding categorical variables.
  
### Regression Models:
- Multiple models were implemented and tested on the sales dataset, including:
  - **Simple Linear Regression**
  - **Multiple Linear Regression**
  - **Ridge Regression**
  - **Polynomial Regression with grid search**
  - **Random Forest Regressor**
  - **XGB Regressor**
  - **Decision Tree Regressor**
  - **AdaBoost Regressor with Decision Tree Regressor**
  
### Model Evaluation:
- Each model was evaluated based on its R-squared score. Hyperparameter tuning was done using GridSearchCV for models like Adaboost and XGBoost.

### Tools and Libraries:
- Python
- Scikit-learn
- XGBoost
- Pandas, NumPy for data handling
- Matplotlib, Seaborn for visualization

## Conclusion
1. After comparing multiple models, **XGB Regressor** yielded the highest R-squared score of **0.36**, suggesting it explained a significant portion of the variance in sales data.
2. Models like **Adaboost Regressor** with a decision tree base performed well but did not surpass XGB in terms of R-squared value.
3. **Future Work**: To further improve prediction accuracy, deep learning models could be explored to increase the R-squared value.

---
