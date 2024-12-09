# CodSoft Internship Projects
----------
This repository showcases the machine learning projects completed during my Data Science internship at CodSoft. The projects focus on classification, regression, and handling imbalanced datasets. Each project explores different aspects of data analysis, preprocessing, feature engineering, and machine learning modeling.

## Projects
### 1. Titanic Survival Prediction
#### Objective: 
The goal of this project was to predict whether a passenger survived the Titanic disaster based on various features like age, gender, ticket class, and fare.

#### Approach:
This project uses the Titanic dataset to train machine learning models to predict survival. Multiple classification models were applied, and their performances were evaluated using various metrics.

#### Key Features:
* PassengerId: Unique identifier for each passenger (not used for prediction).
* Pclass: The class of the ticket the passenger purchased (1st, 2nd, or 3rd class).
* Name: The name of the passenger (could be used to extract titles like Mr, Mrs, Miss for feature engineering).
* Sex: Gender of the passenger (male/female).
* Age: The age of the passenger (numeric, may require handling missing values).
* SibSp: The number of siblings or spouses the passenger had aboard the Titanic.
* Parch: The number of parents or children the passenger had aboard.
* Ticket: Ticket number (could be useful for extracting information like ticket class, or left out in some cases).
* Fare: The fare paid by the passenger for the ticket.
* Cabin: The cabin where the passenger stayed (can be used to extract deck or cabin category).
* Embarked: The port where the passenger boarded the Titanic (C = Cherbourg, Q = Queenstown, S = Southampton).
* Survived: The target variable indicating whether the passenger survived (1 = Yes, 0 = No).


#### Techniques Used:
* Logistic Regression
* Random Forest Classifier
* Decision Tree Classifier
* KNN Classifier
* AdaBoost Classifier

#### Evaluation Metrics:
* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

## 2. Movie Rating Prediction with Python
#### Objective:
The objective of this project was to build a model that predicts the rating of a movie based on features like genre, director, and actors. The model uses regression techniques to estimate ratings.

#### Approach:
Several regression models were applied to predict movie ratings from historical data. Various preprocessing steps were done to handle categorical variables and missing data, followed by model training and evaluation.

#### Key Features:
* Name: The title of the movie (could be useful for text analysis or feature engineering, but not directly used in model building).
* Year: The release year of the movie (non numeric).
* Duration: The runtime of the movie in minutes (non numeric).
* Genre: The genre of the movie (categorical; can be encoded).
* Rating: The rating given to the movie by users or critics (target variable, numeric).
* Votes: The number of votes the movie received (non numeric).
* Director: The director(s) of the movie (categorical; can be encoded).
* Actor1, Actor2, Actor3: The main actors of the movie (categorical; can be encoded).

#### Techniques Used:
* Linear Regression
* Ridge Regression
* Lasso Regression
* Random Forest Regression
* Decision Tree Regression
* Gradient Boosting Regression

#### Evaluation Metrics:
* RMSE (Root Mean Squared Error)
* R2 Score

## 3. Credit Card Fraud Detection
#### Objective:
This project aimed to build a machine learning model to identify fraudulent credit card transactions using transaction data, with a focus on handling the imbalanced dataset.

#### Approach:
The dataset for this project was highly imbalanced, with only a small percentage of fraudulent transactions. To address this, models were trained using techniques like SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset. The models were then evaluated using classification metrics.

#### Key Features:
* Time: Helps track the sequence of transactions.
* V1-V28: Encoded features that capture transaction behavior and patterns.
* Amount: Critical for detecting outlier or unusually large transactions.
* Class: Used for training the model to classify transactions as fraudulent or genuine.

The features V1 to V28 in the Credit Card Fraud Detection dataset are anonymized variables generated through a process known as Principal Component Analysis (PCA). These features were originally derived from the transaction data but have been transformed to protect user privacy. The actual meanings or origins of these features are not disclosed, as they have been deliberately obfuscated to prevent any leakage of personally identifiable information (PII).

#### Techniques Used:

* Logistic Regression
* Random Forest Classifier
* Decision Tree Classifier
* KNN Classifier
* AdaBoost Classifier

#### Additional Techniques:

* SMOTE for handling class imbalance

#### Evaluation Metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

## Achievements
* Gained hands-on experience in implementing machine learning models for both classification and regression tasks.
* Successfully applied advanced techniques like SMOTE for handling imbalanced datasets.
* Enhanced knowledge in feature engineering, data preprocessing, and model evaluation.
* Developed a strong understanding of using machine learning for solving real-world problems like fraud detection and survival prediction.

## Conclusion
These projects helped solidify my understanding of various machine learning algorithms and evaluation metrics. I was able to explore classification, regression, and imbalance handling techniques to tackle real-world challenges. The results from these projects can be applied to similar datasets, and the learned techniques will be invaluable in future data science tasks.

## Acknowledgments
I would like to thank CodSoft for providing me with the opportunity to work on these exciting projects and for offering the mentorship and support throughout my internship.

