***Titanic Survival Prediction Project for Kaggle competition***

This project aims to predict the survival of passengers aboard the Titanic using machine learning algorithms.

***Data***

The data for this project is divided into two parts: training and testing datasets.

    train.csv: Contains training data with features and labels (Survived column).
    test.csv: Contains testing data with features but without labels (Survived column).

***Functions***

    clean(df, col_list): Function to clean the DataFrame by dropping specified columns.
    calculate_mean_by_feature(data, target_variable, feature_variable): Function to calculate the mean of the target variable grouped by the feature variable.

***Analysis***

    1 Absolute Correlation of Numeric Variables with Survived: Analyzes the absolute correlation of numeric variables with the target variable (Survived).
    2 Chi-square Test for Categorical Variables and Survived: Conducts a chi-square test for categorical variables and the target variable to detect correlation.
    3 Mean Survival Rates: Calculates the mean survival rates based on different features.
    4 Extracting Titles from Names, Cleaning and Mapping Titles: Extracts titles from passenger names, cleans, and maps them to numerical values.
    5 Handling Missing Values and Creating Age Categories: Handles missing values in the Age feature and creates age categories.
    6 Creating FamilySize and IsAlone Features: Creates features for family size and whether a passenger is alone.
    7 Handling Missing Values in Embarked Feature and Mapping: Handles missing values in the Embarked feature and maps it to numerical values.
    8 Mapping Sex Feature: Maps the Sex feature to numerical values.
    9 Handling Missing Values in Fare Feature and Creating Fare Categories: Handles missing values in the Fare feature and creates fare categories.
    10 Dropping Irrelevant Columns: Drops irrelevant columns from the dataset.
    11 Splitting Data into Features and Target: Splits the data into features (X) and the target variable (Y).

***Machine Learning Workflow***

The project utilizes several machine learning algorithms to predict survival:

    Logistic Regression
    Support Vector Machines (SVM)
    K-Nearest Neighbors (KNN)
    Random Forest
    Naive Bayes
    Decision Tree

The accuracy of each model is evaluated and presented.
