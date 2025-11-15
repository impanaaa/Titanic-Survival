[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/impanaaa/Titanic-Survival/blob/main/TitanicSurvival.ipynb)

## Titanic Survival — Project Summary

I analyzed the Titanic dataset to understand which passenger features affected survival and to build a simple machine learning model that predicts whether a person would survive. The project mainly focuses on data cleaning, visual exploration, feature preparation, and model training using Logistic Regression. Everything is done step by step in a clear and structured way.

## What I Did in This Project

- Loaded the dataset and explored the first few rows and statistical summary to understand the data.

- Handled missing values by filling Age and Fare with the median, filling Embarked with the mode, and dropping the Cabin column due to too many missing values.

- Converted categorical columns: mapped Sex to numeric values and created dummy variables for Embarked.

- Selected important features such as Pclass, Sex, Age, Fare, SibSp, Parch, Embarked_Q, Embarked_S.

- Split the data into training and testing sets (80/20 split) and scaled the features using StandardScaler.

- Created multiple visualizations (histograms, countplots, bar plots) to see how survival varies by gender, passenger class, and other features.

- Trained a Logistic Regression model to predict survival based on the selected features.

- Evaluated the model using accuracy, confusion matrix, and classification report to understand how well the model performs.

- Added a small prediction section where I tested the model with a new passenger’s details to see if they would survive.

## Libraries Used

- pandas, numpy

- matplotlib.pyplot, seaborn

- scikit-learn

- train_test_split

- StandardScaler

- LogisticRegression

- accuracy_score, confusion_matrix, classification_report
