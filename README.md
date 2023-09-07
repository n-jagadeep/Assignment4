# Assignment4

PROBLEM 1:

Data Manipulation using pandas:

Reading the provided CSV file ‘data.csv' using the .read_csv function and assiging a variable df for it and showing the basic description for the dataframe using the description() function.
creating a seperate variable to store all the columns with null values and replacing the null values with the mean.
Selecting two columns(calories and duration) and aggregate the data using .agg() function and using seperate variables to filter the dataframe to select the rows with calories values between 500 and 1000 and to select the rows with calories values > 500 and pulse <100.Next, creating a new “df_modified” dataframe that contains all the columns from df except for “Maxpulse” and Deleting the “Maxpulse” column from the main df dataframe.Converting the datatype of Calories column to int datatype using the .astype() function and finally using pandas create a scatter plot for the two columns (Duration and Calories).

PROBLEM 2:

Training data using Linear Regression:

Importing the given “Salary_Data.csv” into a variable called data. Spliting the data using train_test_split() function, such that 1/3 of the data is reserved as test subset. Train the model using LinearRegression() function and predicting the values using the predict() function and calculating the mean_squared error of the predictied set and using pandas to Visualize both train and test data using scatter plot.

VIDEO LINK: https://drive.google.com/file/d/1yDcvIjJvZP1J2GJP3iEALmONrR4dQ-bq/view?usp=share_link
