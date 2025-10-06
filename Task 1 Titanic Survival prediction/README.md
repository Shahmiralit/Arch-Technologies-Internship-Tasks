#     TitanicSurvival-Prediction
Project Overview:
This project aims to predict passenger survival on the Titanic using machine learning. The dataset includes features like age, gender, passenger class, and fare. The model helps identify factors that influenced survival and provides a predictive tool for classification.

#  Dataset:
The dataset used in this project is the Titanic dataset from Kaggle.

Training set: Passenger data with survival labels.

Test set: Passenger data without survival labels.

#  Key features used in this project:
• PassengerId Unique ID for each passenger.

• Pclass Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).

• Name Passenger.

• Sex Gender of the passenger.

• Age in years.

• SibSp Number of siblings/spouses aboard.

• Parch Number of parents/children aboard.

• Ticket number.

• Passenger fare.

• Cabin number.

• Embarked Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

#  Data Preprocessing:

Steps performed before modeling:
Handling missing values.

1.Filled missing ages using median values based on passenger class and gender.

2.Imputed missing embarkation points with mode.

3.Dropped Cabin column due to excessive missing values.


#  Feature engineering.
1.Extracted Title from passenger names.

2.Converted categorical variables (Sex, Embarked, Title) to numerical labels.

3.Scaling and normalization.

4.Scaled numerical features (Age, Fare) for model consistency.

#  Exploratory Data Analysis (EDA):

1.Visualized survival rate by gender, class, and age.

2.Identified correlations between features and survival.

3.Explored distributions of numerical features using histograms and boxplots.


#  Modeling:
• Algorithms used: Logistic Regression, Random Forest Classifier.

• Selected model: Random Forest Classifier (best performance on validation set).

• Hyperparameter tuning: GridSearchCV used to optimize model parameters.

#  Technologies Used:
Python 3.x.

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn.

Jupyter Notebook for step-by-step development.


#  Evaluation:
Performance metrics on the validation set:

• Metric    Score

Accuracy    82%

Precision   81%

Recall      78%

F1-Score    79%
