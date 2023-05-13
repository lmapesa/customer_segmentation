## Customer Lifetime value across segments to identify key segments.
## Data files
- Business table
- Transaction_subset

### Libraries used:

1. **Pandas:**
   - `read_csv()`: Used to read data from a CSV (Comma Separated Value) file and store it as a pandas DataFrame object.
   - `merge()`: Allows for the combination of two or more dataframes based on a common column or index.
   - `to_datetime()`: Converts columns to time format.
   - `DataFrame()`: Creates a DataFrame (a two-dimensional tabular data structure with labeled axes - rows and columns) from a dictionary or csv file.
   - `head()`: Pandas library method used to display the first n rows of a DataFrame, where n is a number passed as an argument. If n is not defined, it returns the first 5 rows by default.
   - `describe()`: Pandas library method that generates a statistical summary of the numerical columns of a DataFrame. They include count, mean, std, min, max, and percentiles – 25%, 50%, 75%.
   - `isnull()`: Pandas DataFrame method that returns a DataFrame of the same shape as the input df with boolean values indicating whether each element of df is NaN (Not a Number) or not.
   - `replace()`: A method in pandas library that allows replacing values in a DataFrame. It can replace values based on a single value, a list of values, or a dictionary of values.
   - `filter()`: A method of pandas DataFrame that is used to subset the DataFrame based on column labels or a boolean condition.
   - `corr()`: A method of a pandas DataFrame object that calculates the correlation between columns in the DataFrame. It returns a new DataFrame object that contains the pairwise correlation coefficients between all pairs of columns in the original DataFrame.
   - `get_dummies()`: Used for one-hot encoding categorical variables in a dataset. One-hot encoding is the process of converting categorical variables into a numerical representation. In this case, it takes the Pandas DataFrame as input and converts all categorical variables into dummy variables. It creates a new column for each unique value in the categorical variable and assigns a 1 or 0 to indicate whether that value is present or not in the original column.

2. **NumPy:**
   - `NaN`: Stands for "Not a Number" and is a special floating-point value. It has been used to represent missing or undefined values in numerical arrays.
   - `where()`: Returns an array of elements from one of two arrays, depending on whether a given condition is True or False.

3. **Seaborn:**
   - `heatmap()`: Used to visualize missing values in the data.

4. **Matplotlib:**
   - `pyplot()`: Used to plot various graphs.
