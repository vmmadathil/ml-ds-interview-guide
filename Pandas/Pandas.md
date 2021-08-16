# Pandas

Pandas is a popular dataframe and analysis library.

## Common Functions
* .head(n)/.tail(n) : peak at the first/last n rows
* .nunique() : return the number of unique values in a column(s)
* .describe() : provides basic statistics of columns
* .isna() : returns true if there are NA values in the column(s)
* .dropna() : drops NA values
* .groupby('Col') : groups the df by values
* .dtypes() : returns data type of each column
* .astype() : to cast the data type
* .drop_duplicates() : drops duplicate values
* .merge(df, on=, how=) : merges two df on a key
* .sort_values() : sorts dataframe by ascending order
* .fillna() : imputes missing values
* .iloc[:, :] : returns specific rows/columns
* .sample(n) : randomly samples n rows 
* .isin(x) : returns rows for columns values that are in list x