# Predicting Hazardous NEOs (Nearest Earth Objects)

## Project Overview
This project aims to predict whether a Near-Earth Object (NEO) is hazardous using a dataset provided by NASA. The dataset contains 338,199 records of NEOs observed from 1910 to 2024.

## Steps
1. **Data Cleaning**: Handled missing values and removed irrelevant columns.
2. **Exploratory Data Analysis (EDA)**: Analyzed distributions, correlations, and class imbalance.
3. **Data Preprocessing**: Scaled features and addressed class imbalance using SMOTE.
4. **Model Training and Evaluation**: Trained Logistic Regression, Random Forest, and XGBoost models. Evaluated using ROC-AUC, Precision, Recall, and F1-Score.
5. **Hyperparameter Tuning**: Optimized the Random Forest model using GridSearchCV.
6. **Final Model**: Saved the best-performing model for future use.

## Results
- The Random Forest model achieved the highest ROC-AUC score of 0.94.
- Key features for prediction: `absolute_magnitude`, `estimated_diameter_min`, and `relative_velocity`.

## Repository Structure
- `Random Forest.pkl`: Trained model.
- `Predicting Hazardous NEOs (Nearest Earth Objects.ipynb`: Jupyter Notebook with the code.
- `README.md`: Project documentation.

## How to Run
1. Clone the repository.
2. Run the Jupyter Notebook: `Predicting Hazardous NEOs (Nearest Earth Objects).ipynb`.
