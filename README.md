# Pima Indians Diabetes Analysis
## Project Overview
Using the diabetes.csv dataset provided by Kaggle and the libraries numpy, pandas, matplotlib, and scipy to analyse the data encased in the csv file. The dataset is used diagnostically to predict whether or not a patient has diabetes based on certain  measurements. The analysis follows the OSEMN pipeline (Obtain, Scrub, Explore, Model, Nterpret) to process the data, perform exploratory data analysis, and build a machine learning model.

## Data Context
The dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases.
Objective: Predict the Outcome (diabetes yes/no) based on medical predictor variables.
Subjects: Females at least 21 years old of Pima Indian heritage.
Features: Includes Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age.

## Technologies & Libraries
The analysis is performed using Python and the following libraries:
- Pandas: Data manipulation and analysis.
- NumPy: Numerical operations.
- Matplotlib / Seaborn: Data visualisation.
- Scikit-Learn: Machine learning modeling, metrics, and hyperparameter tuning.

## How to run
1. Clone this repo.
2. Install the required libraries using: pip install pandas numpy matplotlib scikit-learn
3. Open notebook: jupyter notebook diabetes.ipynb
4. Run all cells to reproduce the analysis and model results.

## Key Findings
- Certain features like Glucose and BMI showed strong correlations with diabetes outcomes.
- Data cleaning (handling zero values) was crucial for accurate model performance.
- The KNN model, after tuning, achieved a reliable predictive accuracy on the test set.
