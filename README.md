# Crowdfunding_ETL

For this ETL mini project, we to build an ETL pipeline to clean and organise data using Python, Pandas, and either Python dictionary methods to extract and transform the data. 
By the end, we have four tidy CSV files i.e. campaign, contacts, category and subcategory ready to transform into database schema. 

We succesfully created the following:
1. Category DataFrame
2. Subcategory DataFrame
3. Campaign DataFrame
4. Contacts DataFrame
5. Crowdfunding Database

**Hints**
- To split each "category & sub-category" column value into "category" and "subcategory" column values, use  df[["new_column1","new_column2"]] = df["column"].str.split() . Make sure to pass the correct parameters to the  split()  function.
- To get the unique category and subcategory values from the "category" and "subcategory" columns, create a NumPy array where the array length equals the number of unique categories and unique subcategories from each column. For information about how to do so, see numpy.arange  (https://numpy.org/doc/stable/reference/generated/numpy.arange.html) in the NumPy documentation.
- To create the category and subcategory identi cation numbers, use a list comprehension to add the "cat" string or the "subcat" string to each number in the category or the subcategory array, respectively.
- For more information about creating a new Pandas DataFrame, see the pandas.DataFrame (https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html) in the Pandas documentation.
- To convert the "goal" and "pledged" columns to the  float  data type, use the  astype()  method.
- To convert the "launch_date" and "end_date" UTC times to the  datetime  format, see the  Transform_Grocery_Orders_Solved.ipynb  activity solution.
- For more information about how to add the "category_id" and "subcategory_id" unique identi cation numbers to the campaign DataFrame, see the pandas.DataFrame.merge  (https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.merge.html) in the Pandas documentation.

