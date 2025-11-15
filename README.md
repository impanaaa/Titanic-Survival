[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/impanaaa/Titanic-Survival/blob/main/TitanicSurvival.ipynb)

Titanic Survival — Project Summary
I analyzed the Titanic dataset (titanic.csv) to find which passenger features affected survival and to build a model that predicts survival. I focused on clean, clear steps: prepare the data, explore it with visuals, train a model, and evaluate results.

Key actions I took

Loaded the data from titanic.csv and inspected the first rows and summary statistics.

Handled missing values: filled Age and Fare with the median, filled Embarked with the mode, and dropped the Cabin column because it had too many missing values.

Converted categories: mapped Sex to numbers and created dummy variables for Embarked.

Selected features: used Pclass, Sex, Age, Fare, SibSp, Parch, Embarked_Q, Embarked_S for the model.

Train-test split: split data with test_size=0.2 and random_state=42.

Scaled features using StandardScaler before modeling.

Visualized data with histograms, countplots, and bar plots to compare survival by gender and passenger class, and to inspect distributions and relationships.

Trained a Logistic Regression model on the prepared data.

Evaluated the model with accuracy, confusion matrix, and classification report.

Added a small prediction demo to predict survival for a new/specific passenger using the trained model.

Libraries used

pandas, numpy

matplotlib.pyplot, seaborn (visualizations)

scikit-learn: train_test_split, StandardScaler, LogisticRegression, accuracy_score, confusion_matrix, classification_report
