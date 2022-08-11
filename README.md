# Sales_Data_analysis
- - - -
Set of real world data science tasks completed using the Python Pandas library.

### Background Information
- - - -
In this repo, Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

We start by cleaning the data. Following are the steps taken to clean the data and format it:

* Dropping Null values from DataFrame
* Removing null rows based on a condition
* Change the datatypes of columns using (to_numeric, to_datetime, astype)

### Data Exploration
- - - -
Once the data is finished cleaning up the data a bit, moved to the data exploration section. In this section we explore 5 high level business questions related to the data:

* What was the best month for sales? How much was earned that month?
* What city sold the most product?
* What time should the advertisements are to be displayed to maximize the likelihood of customer’s buying product?
* What products are most often sold together?
* What product sold the most? Why do you think it sold the most?

To answer these questions worked through many different pandas & matplotlib methods which include:

* Concatenating multiple CSV's together to create a new DataFrame (pd.concat)
* Adding columns
* Parsing cells as strings to make new columns (.str)
* Using the .apply() method
* Using groupby to perform aggregate analysis
* Plotting bar charts and lines graphs to visualize our results
* Labeling our graphs
