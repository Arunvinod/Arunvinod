# Arunvinod

This github repository is to learn and analyze the DS concepts from base to advanced DS methodsand and to work on hands on practice to various ML concepts , competions

Hope this is useful to me and for everyone.

DS:
1.Pandas+Numpy
# conventional way to import pandas
# read a dataset of Chipotle orders directly from a URL and store the results in a DataFrame
# examine the first 5 rows
# read_csv is equivalent to read_table, except it assumes a comma separator
# select the 'City' Series using bracket notation
# or equivalently, use dot notation
# create new data series(column) based on avalabe columns
# example method: calculate summary statistics
# example attribute: number of rows and columns
# example attribute: data type of each column
# use an optional parameter to the describe method to summarize only 'object' columns
# examine the column names
# rename two of the columns by using the 'rename' method
# replace all spaces with underscores in the column names by using the 'str.replace' method
# remove a single column (axis=1 refers to columns)
# remove multiple columns at once
# remove multiple rows at once (axis=0 refers to rows)
# sort the 'title' Series in ascending order (returns a Series)
# sort in descending order instead
# sort the entire DataFrame by the 'title' Series (returns a DataFrame)
# sort in descending order instead
# sort the DataFrame first by 'content_rating', then by 'duration'
# extract specific columns based on single/multiple condition
# select the 'genre' Series from the filtered DataFrame
# or equivalently, use the 'loc' method
# filter the DataFrame to only show movies with a 'duration' of at least 200 minutes
# CORRECT: use the '&' operator to specify that both conditions are required
# extract a column match any of the three criteria (isin)
# read a dataset of alcohol consumption into a DataFrame, and check the data types
# describe all of the numeric columns
# pass the string 'all' to describe all columns
# pass a list of data types to only describe certain types
# pass a list even if you only want to describe a single data type
# drop a column (temporarily)
# drop a row (temporarily)
# drop a row (temporarily)
# 'index' is an alias for axis 0
# 'columns' is an alias for axis 1
# use the boolean Series to filter the DataFrame
# examine the data type of each Series
# change the data type of an existing Series
# # groupby
# # calculate the mean beer servings for each continent
# other aggregation functions (such as 'max') can also be used with groupby
# multiple aggregation functions can be applied simultaneously
# count the non-null values, unique values, and frequency of the most common value
# count how many times each value in the Series occurs
# display percentages instead of raw counts
# display the unique values in the Series
# count the number of unique values in the Series
# compute a cross-tabulation of two Series
# 'value_counts' is primarily useful for categorical data, not numerical data
# handle missing values
# count the number of missing values in each Series
# if 'any' values are missing in a row, then drop that row
# if 'all' values are missing in a row, then drop that row (none are dropped in this case)
# if 'any' values are missing in a row (considering only 'City' and 'Shape Reported'), then drop that row
# if 'all' values are missing in a row (considering only 'City' and 'Shape Reported'), then drop that row
# 'value_counts' does not include missing values by default
# index
# selection: select a portion of the DataFrame using the index
# set an existing column as the index
# restore the index name, and move the index back to a column
# any Series can be sorted by its values
# any Series can also be sorted by its index
# loc & iloc method for slicing and dicing for index
# select multiple rows & columns
# select row 0, all columns
# rows 0 and 1 and 2, all columns
# rows 0 through 2 (inclusive), all columns
# rows 0 through 2 (inclusive), column 'City'
# rows 0 through 2 (inclusive), columns 'City' and 'State'
# rows 0 through 2 (inclusive), columns 'City' through 'State' (inclusive)
# rows in which the 'City' is 'Oakland', column 'State'
The iloc method is used to select rows and columns by integer position. You can pass it:
# rows in positions 0 and 1, columns in positions 0 and 3
# rows in positions 0 through 2 (exclusive), columns in positions 0 through 4 (exclusive)
# rows in positions 0 through 2 (exclusive), all columns
	# label-based slicing is inclusive of the start and stop
	# position-based slicing is inclusive of the start and exclusive of the stop
# create dummy variable in pandas
use 'get_dummies' to create one column for every possible value
# use 'get_dummies' with a feature that has 3 possible values
# use the 'drop_first' parameter (new in pandas 0.18) to drop the first dummy variable for each feature
# convert 'Time' to datetime format (# convenient Series attributes are now available -- hour ,day, month )
ufo.Time.dt.hour.head()
weekday
# find & remove duplicate rows in pandas
# count the duplicate rows
# count the duplicate items (True becomes 1, False becomes 0)
# examine the duplicate rows (ignoring the first occurrence)
# examine the duplicate rows (ignoring the last occurrence)
# only consider a subset of columns when identifying duplicates


# count the missing values in the 'content_rating' Series
# examine the DataFrame rows that contain those missing values
# examine the unique values in the 'content_rating' Series

# map 'female' to 0 and 'male' to 1
use a lambda function
# apply the 'max' function along axis 0 to calculate the maximum value in each column
# apply the 'max' function along axis 1 to calculate the maximum value in each row
# convert every DataFrame element into a float
# overwrite the existing DataFrame columns



2.Feautre Enginnering
3.Scikit
3.ML Algorithm
4.DL




