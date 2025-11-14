<pre>
# Heart Disease Prediction using Logistic Regression using Logistic Regression

This project builds a simple Logistic Regression model to predict heart disease based on clinical input features.

## Overview

The script loads the Heart dataset, cleans the data, encodes categorical features, trains a Logistic Regression model, and allows the user to enter values manually to get a prediction.

## Features Used

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise-induced Angina
* Oldpeak
* Slope
* Number of Major Vessels
* Thalassemia

## Steps Performed in Code

1. Load the dataset using pandas.
2. Drop unwanted and null values.
3. Encode categorical columns.
4. Split the dataset into training and testing sets.
5. Train a Logistic Regression model.
6. Collect user input and run prediction.
7. Print final diagnosis result.

## Requirements

Install required libraries:

```
pip install pandas numpy scikit-learn
```

## Running the Script

Run the Python file and enter the required values when prompted:

```
python heart_predict.py
```

The script will display whether there is a possibility of heart disease.

## Model Output

* **1**: High chance of heart disease
* **0**: No significant risk detected

## Notes

* Ensure `Heart.csv` is in the same directory as the script.
* Encoded values for each categorical field must match the dataset mapping.
</pre>