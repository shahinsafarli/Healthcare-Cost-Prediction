# Healthcare-Cost-Prediction

This project predicts patient medical expenses based on demographic and health attributes. 

## Goal

The main goal is to build a regression model that accurately predicts the `charges` (annual medical costs) for a patient given their `age`, `sex`, `bmi`, `children`, `smoker` status, and `region`.

## Steps 

1. Load Data: Loaded the insurance dataset for analysis.

2. Explore Data (EDA): Explored data statistics, distributions, and feature relationships. Normalized the skewed charges target using a log transformation.

3. Preprocess Data: Prepared data for the model. Encoded categorical features (sex, smoker, region) numerically.

4. Split Data: Split data into training and testing sets for model evaluation.

5. Train Model: Trained a tree-based regression model on the training data. 

6. Evaluate Model: Evaluated the model on the test set. Converted predictions back to currency. Calculated RMSE and MAE metrics.

7. Analyze Importance: Identified key cost drivers (e.g., age, BMI, smoker).

## Results 📊

* **RMSE**: `4359.25`
* **MAE**: `2089.53`

* **Key Cost Drivers**:
    1.  `smoker` 
    2.  `age`
    3.  `bmi`
