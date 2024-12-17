# DataCleaninginPandas

This project demonstrates common data cleaning techniques using Python and Pandas. Below is an outline of the operations performed:

Actions Performed:
1. Removing Duplicates: 
- Identified and removed duplicate rows to ensure data uniqueness.
Utilized Pandas' drop_duplicates() function.

2. Dropping Columns:
- Removed unnecessary columns to streamline the dataset.
- Applied the drop() method with axis parameters.

3. Stripping Whitespace:
- Stripped extra whitespace from strings in the dataset using the str.strip() method to ensure consistency.

4. Cleaning/Standardizing Phone Numbers
- Transformed and standardized phone number formats to maintain uniformity
- Used string operations and regular expressions.

5. Splitting Columns:
- Split a single column into multiple columns for better data granularity, e.g., separating full names into first and last names.

6. Standardizing Column Values:
- Replaced inconsistent values in specific columns with a standard representation using the replace() function.

7. Filling Null Values:
- Handled missing data by filling null values with appropriate defaults or calculated values using fillna().

8. Filtering Rows:
- Filtered rows based on specific conditions to focus on relevant data subsets.


