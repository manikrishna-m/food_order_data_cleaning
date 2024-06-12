# Data Cleaning in Data Science: Practical Guide
Data cleaning is a crucial step in ensuring the accuracy and quality of data for analysis. This guide provides practical methods for data cleaning using Python, illustrated with a dataset based on food delivery costs.

Data Cleaning Methods
1. Removing Duplicates
Duplicate records can mislead the results of your analysis. Always ensure your data doesn't contain any duplicate records by checking and removing them as necessary.

2. Handling Missing Values
Missing values can occur in any dataset and need to be handled appropriately. Common strategies include:

Removal: Deleting rows or columns with missing values.
Filling: Imputing missing values using the mean, median, mode, or a constant value.
Interpolation: Estimating missing values using interpolation methods.
3. Dealing with Outliers
Outliers can distort statistical analyses and affect the performance of machine learning models. Methods to handle outliers include:

Removal: Deleting rows with outliers.
Capping: Limiting outliers to a specific range.
Transformation: Applying transformations like log or square root.
4. Converting Data Types
Ensure columns have the appropriate data types for analysis. This may involve converting strings to dates, floats to integers, etc.

5. Handling Categorical Data
Categorical data often needs to be converted to numerical format for analysis. This can be done using techniques like one-hot encoding or label encoding.

6. Dealing with Inconsistent Data
Inconsistencies in data, such as different formats or typos, need to be corrected. This can be done manually or by using predefined rules.