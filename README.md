# Intro-to-Python-for-Finance

---
## Description
In this jupyter notebook, I have built some visualizations from Stocks dataset.

I have used Matplotlib package for creating visualizations - line plots, and histograms.

---
## Dataset info
Stocks dataset is available in this repository.

---
## Contents

- **Importing the required libraries**
  - ***pandas*** : pandas is a Python package that provides fast, flexible, and expressive data structures designed to make working with structured (tabular, multidimensional, potentially heterogeneous) and time series data both easy and intuitive.
  - ***Matplotlib*** : Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python. It is a multi-platform data visualization library built on NumPy arrays and designed to work with the broader SciPy stack.

- **Importing and Loading the dataset**
  - Stocks data (of 2 Companies: Company-1 and Company-2)
  
- **Exploratory Data Analysis**
  - `df.shape` -- Return a tuple representing the dimensionality of the DataFrame.
  - `df.head()` -- Return the first n rows. This function returns the first n rows for the object based on position. (default n=5)
  - `df.info()` -- Print a concise summary of a DataFrame. This method prints information about a DataFrame including the index dtype and columns, non-null values and memory usage
  - `df.describe()` -- Generate descriptive statistics. It is used to view some basic statistical details like percentile, mean, std etc. of a data frame or a series of numeric values.
  - `df.isna().sum()` -- Count missing values for each column of the dataframe.
- **Data Visualizations**
  - `df.plot()` -- Make plots of Series or DataFrame. default - Line plot/ graph.
  - Plotting Stock Prices of Company-1 vs Days (***Line plot***)
  - Plotting Stock Prices of Company-2 vs Days (***Line plot***)
  - Plotting both companies Stock Prices on same plot (***Adding 2 lines on the same plot***)
    - Adding Labels (***legend function***)
    - Different Linestyles and Colors
    - Adding axis labels (x-label, y-label) and title
  - Additional Line on the plot (***showing mean***)
  - Layering histograms on the same plot
    - Changing transpareny of histograms (***alpha***)
    
