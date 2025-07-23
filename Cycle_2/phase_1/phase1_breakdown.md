# Breast Cancer DataSet-Phase1
- Imported the esssential libraries required(ex:pandas, seaborn,numpy,etc..)
## DataProcessing
- Loaded the dataset: breast-cancer.csv
- Separated column types
  - Numerical columns identified using select_dtypes(include=["number"])
  - Categorical columns identified using select_dtypes(include=["object"])
- Handled the missing values
- Encoded the target variable diagnosis using LabelEncoder.
- Scaled features using StandardScaler for better model performance.

## Model Training
- Split the dataset into training and test sets (70-30 split) using train_test_split().
- Trained 3 Classification models:
   - Random Forest Classifier
   - Ada Boost Classifier
   - XGBoost Classifier
- Evaluated the acuuracy

## Results:
- After training and testing the models, the accuracy scores were:
  - Random Forest Accuracy: 97.66%
  - AdaBoost Accuracy: 98.24%
  - XGBoost Accuracy: 97.07%

- After trainig the three modesl we can see that AdaBoost Classifier has the highest accuracy
