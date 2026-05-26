## Pandas (DataFrames)

## What is Pandas?

1. In the world of data science, mastering Pandas is like learning to read before writing poetry.
2. `Wes Mckinney` created Pandas to make:
   1. Data Cleaning easier
   2. Data Analysis faster
   3. Data Manipulation more powerful

## DataFrame

1. A DataFrame is a two-dimensional labeled data structure.
2. Rows and columns format.
3. Most commonly used Pandas object.

## Use Cases of Pandas

1. Data Cleaning
2. Data Analysis
3. Data Transformation
4. Data Visualization (Basic Level)
5. Data Aggregation
6. File Handling
7. Data Filtering & Selection
8. Time Series Analysis

## Pandas Topics Index

1. Series
2. DataFrames
3. Missing Data
4. Merging, Joining, Concatenation
5. GroupBy and Aggregations
6. Pivot Tables and Crosstab
7. Operations
8. Working with Real Data
9. Capstone project

## Pandas Series

1. A Series is a one-dimensional labeled array capable of holding any data type.
2. The axis labels are collectively called the index.

## Creating Series

1. Using List
2. Using Dictionary
3. Using NumPy Array
4. Using Scalar Value2

## Creating a DataFrame

1. Using Dictionary
2. Using List of Lists
3. Using CSV/Excel/JSON files
4. Using NumPy Arrays

## Selection and Indexing of Columns

1. `Column Selection`:
   1. Single Column
   2. Multiple Columns
2. `Row Selection`:
   1. `loc[]`
   2. `iloc[]`
3. `Subset Selection`:
   1. Rows + Columns together

## Creating a New Column

1. Add column using assignment operator

## Removing Columns

1. Use `drop()` method

## Conditional Selection

1. Filtering rows using conditions
2. `Multiple conditions using`:
   1. `&` (AND)
   2. `|` (OR)

## Finding Missing Data

1. `isnull()`
2. `notnull()`

## Removing Missing Data

1. `dropna()`

## Filling the missing Data

1. `fillna()`

## Merging and Combining Data

1. `Merge`:
   1. Combines DataFrames using common columns.
2. `Concatenation`:
   1. Stacks DataFrames vertically or horizontally.
3. `Join`:
   1. Combines DataFrames using indexes.

## GroupBy Aggregation

1. Used for grouping data.
2. `Common aggregation functions`:
   1. `sum()`
   2. `mean()`
   3. `count()`
   4. `max()`
   5. `min()`

## Pivot Tables

1. Summarize and aggregate data.
2. Similar to Excel Pivot Table.

## Cross Tabs

1. Frequency table for categorical data.

## File Handling in Pandas

1. CSV (Comma-Separated Values)
   1. `Extension`: `.csv`
      1. pd.read_csv('file.csv')
2. Excel
   1. `Extension`:`.xls`,`.xlsx`
      1. pd.read_excel('file.xlsx')
3. JSON(JavaScript Object Notation)
   1. `Extension`: `.json`
      1. pd.read_json('file.json')
4. Text File
   1. `Extension`: `.txt`
      1. pd.read_csv('file.txt',delimiter=' ')(or other delimiter)
5. TSV (Tab-Separated Values)
   1. `Extension`: `.tsv`
      1. pd.read_csv('file.tsv',sep='\t')
6. HTML Tables
   1. `Extension`:`.html`
      1. pd_read_html('file.html')
7. SQL Databases
   1. `Extension`:`.db`,`.sqlite`
      1. pd.read_sql(query,connection)
8. Parquet
   1. `Extension`:`.parquet`
      1. pd.read_parquet('file.parquet')
9. Feather
   1. `Extension`:`.feather`
      1. pd.read_feather('file.parquet')
10. Pickle
    1. `Extension`:`.pkl`, `.pickle`
       1. pd.read_pickle('file.pkl')
11. HDF5 (Hierarchical Data Format)
    1. `Extension`:`.h5`
       1. pd.read_hdf('file.h5')
12. ORC(Optimized Row Columnar)
    1. `Extension`:`.orc`
       1. pd.read_orc('file.orc')
13. Google Sheets
    1. `Extension`:`Using URL/API`
       1. Use gsread or Google Sheets API

## Some Great Pandas Capstone Projects

1. Animation Data Analysis
2. Countries Data Analysis

## Commonly Used Functions

1. `head()`
2. `tail()`
3. `info()`
4. `describe()`
5. `shape`
6. `columns`
7. `dtypes`
8. `value_counts()`
9. `sort_values()`
10. `unique()`

## Real Data Operations

1. Cleaning raw datasets
2. Removing duplicates
3. Handling null values
4. Filtering records
5. Aggregating business data
6. Reporting and dashboards

## Practice Platforms

1. `Kaggle`: https://www.kaggle.com/
2. `Pandas Documentation`: https://pandas.pydata.org/docs/
