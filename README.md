# CODSOFT
Contains the tasks/project completed during the period of internship at CODSOFT

## #_Task 1_
### :ship::bar_chart:TITANIC SURVIVAL PREDICTION :bar_chart::ship::  
Using the Titanic dataset to a build a predictive model to find out what sort of people survived the wreck by using the passenger data.

The data has been split into two groups:
- training set (train.csv)
- test set (test.csv)

The training set should be used to build your machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. Your model will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features.

The test set should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.

Dataset Link: https://www.kaggle.com/datasets/brendan45774/test-file

## #_Task 2_
### 🎥📈 MOVIE RATING PREDICTION WITH PYTHON 📈🎥:  
Analyzing historical movie data and developing a model that accurately estimates the rating given to a movie by users or critics by making us of the datasets
The files of dataset:
- movies.dat
- ratings.dat
- users.dat

**USERS FILE DESCRIPTION**   
User information is in the file "users.dat" and is in the following
format:  

UserID::Gender::Age::Occupation::Zip-code

Gender is denoted by a "M" for male and "F" for female

Age is chosen from the following ranges:
Age  | Range
------------- | -------------
01 |  "Under 18"
18 | "18-24"
25  | "25-34"
35  | "35-44"
45  | "45-49"
50  | "50-55"
56  | "56+"    

Occupation is chosen from the following choices:

0: "other" or not specified  
1: "academic/educator"  
2: "artist"  
3: "clerical/admin"  
4: "college/grad student"  
5: "customer service"  
6: "doctor/health care"  
7: "executive/managerial"  
8: "farmer"  
9: "homemaker"  
10: "K-12 student"  
11: "lawyer"  
12: "programmer"  
13: "retired"  
14: "sales/marketing"  
15: "scientist"  
16: "self-employed"  
17: "technician/engineer"  
18: "tradesman/craftsman"  
19: "unemployed"  
20: "writer"  

__RATINGS FILE DESCRIPTION__  
All ratings are contained in the file "ratings.dat" and are in the
following format:

UserID::MovieID::Rating::Timestamp

-UserIDs range between 1 and 6040  
-MovieIDs range between 1 and 3952  
-Ratings are made on a 5-star scale (whole-star ratings only)  
-Timestamp is represented in seconds since the epoch as returned by time(2)  
-Each user has at least 20 ratings  

__MOVIES FILE DESCRIPTION__  
Movie information is in the file "movies.dat" and is in the following
format:

-MovieID::Title::Genres  
-Titles are identical to titles provided by the IMDB (including
year of release)    
-Genres are pipe-separated 

Dataset Link: https://www.kaggle.com/code/sherinclaudia/movie-rating-prediction/notebook

## #_Task 3_
### 🌺📐 IRIS FLOWER CLASSIFICATION 📐🌺:  
The data set contains 3 classes of 50 instances each, where each class refers to a type of iris plant. One class is linearly separable from the other 2; the latter are NOT linearly separable from each other.

__Content:-__

sepal length in cm  
sepal width in cm  
petal length in cm  
petal width in cm  
species: -- Iris Setosa -- Iris Versicolour -- Iris Virginica

Dataset Link: https://www.kaggle.com/uciml/iris

## [*#Task 5*](https://github.com/tronn-ankush/CODSOFT/tree/master/Task%205)
### 💳⚠️ CREDIT CARD FRAUD DETECTION ⚠️💳:  
__Content__
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Dataset Link:https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
