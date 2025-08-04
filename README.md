# Elevate_labs-internship
1. What are missing values and how do you handle them?
Missing values are empty or null entries in a dataset. I handled them using dropna() to remove rows or fillna() to replace with mean, median, or a constant.

2. How do you treat duplicate records?
I used df.duplicated() to identify duplicates and df.drop_duplicates() to remove them.

3. Difference between dropna() and fillna() in Pandas?

    dropna() removes rows or columns with missing values.

    fillna() fills missing values with a specific value like mean, median, or a fixed number.

4. What is outlier treatment and why is it important?
Outlier treatment involves identifying and handling extreme values. It's important to avoid skewed analysis or incorrect model results. I used IQR or z-score methods.

5. Explain the process of standardizing data.
Standardizing means scaling features to have a mean of 0 and standard deviation of 1 using StandardScaler or manual z-score formula.

6. How do you handle inconsistent data formats (e.g., date/time)?
I used pd.to_datetime() to convert date columns into a consistent datetime format.

7. What are common data cleaning challenges?
Common challenges include missing values, inconsistent formats, duplicates, incorrect data types, outliers, and human entry errors.

8. How can you check data quality?
By using functions like df.info(), df.describe(), checking nulls (isnull().sum()), value counts, data types, and visual inspections like boxplots.
