# Experiment-13
# Aim
To perform preprocessing on a dataset and dealing with missing values.
# Theory
1. Data preprocessing in Python involves cleaning, transforming, and preparing raw data for analysis using tools like Pandas.
2. import pandas- This line imports the pandas library.Pandas is used for data handling and analysis.
3. import numpy- This line imports the NumPy library to perform numerical and array operations in python.
4. pd.DataFrame- pd.DataFrame is used to create a structured table (rows and columns) from data like lists, dictionaries, or arrays.
5. df1.isna ()- df1.isna() checks the DataFrame and returns a table showing True for missing (NaN) values and False for non-missing values.
6. df1.notna()- df1.notna() returns a DataFrame showing True for non-missing values and False for missing (NaN) values.
7. df1.isna().sum()- df1.isna().sum() counts the total number of missing (NaN) values in each column of the DataFrame.
8. df1.isna().sum(axis=1)- It counts the number of missing (NaN) values in each row of the DataFrame.
9. df1.dropna ()- df1.dropna() (in Pandas) removes rows containing any missing (NaN) values from the DataFrame.
