# Car Prices

The objective is to understand how the characteristics of a car could impact its price. 

The dataset contains 205 observations representing cars with 26 variables 
defining its characteristics. This dataset was downloaded from the University of California, 
Irvine Machine Learning repository (the original file and description can be downloaded [here](https://archive.ics.uci.edu/ml/datasets/automobile).)

Description of the dataset including the definition of each variable is also given.
Your task is to build a model that implements machine learning linear regression on the received data. 
To get the work done, you need to: 

1. Read the dataset and perform an Exploratory Data Analysis
    - Read the file
    - Check the column names and first rows
    - Check for missing values
    - Check the datatypes
2. Read the dataset again, specifying that the dataset doesn't have a header row, indicating the column names
and the correct interpretation of missing data
    - Read the file
    - Check the column names and first rows
    - Check for missing values
    - Check the datatypes
    - Analyze the categorical data
3. Remove unused columns
4. Deal with missing data
    - num_of_doors column
    - bore column
    - stroke column
    - horsepower column
    - peak_rpm column
    - price column
5. Deal with categorical columns
    - num_of_cylinders column
    - Other categorical columns
6. Split your data into train (80%) and test (20%) data, and separe the dependent variables of the independent
variables
    - Split the original data into train and test datasets
    - Separate your dependent variable of the training data
    - Separate your dependent variable of the test data
7. Train and execute your model
    - Create the linear regression object
    - Train the model using the training sets
    - Make predictions using the testing set
8. Assess the performance of your model
    - Print the R-Squared of your model
    - Print the comparison between the prediction of the model and the actual data

