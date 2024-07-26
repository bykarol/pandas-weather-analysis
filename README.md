# Overview

Software made using Python pandas, to analyze a set of data (Weather history) to answer the following questions:
1. What is the average temperature for each month?
2. How does humidity correlate with temperature?
3. How does temperature vary over time?


[Software Demo Video](https://youtu.be/vzKXLfYAJxA)

# Guidance
1. Virtual environment to manage dependencies (optional):
  - Set virtual environment: `python -m venv venv`
  - Activate the virtual environment: `.\venv\Scripts\activate`
2. Use pip to install Pandas and Matplotlib: 
  - `python -m pip install pandas`
  - `python -m pip install matplotlib`
3. Follow these steps:
  - Load and inspect de dataset
  - Identify the questions to be answered.
  - Analyze the data (using Python pandas)
4. Things to remember:
  - Import the package, `import pandas as pd`
  - A table of data is stored as a pandas `DataFrame`
  - Each column in a DataFrame is a `Series`
  - Getting data in to pandas from many different file formats or data sources is supported by `read_*` functions.
  - Exporting data out of pandas is provided by different `to_*methods`.
  - The `head/tail/info` methods and the dtypes attribute are convenient for a first check.
  - You can do things by applying a method to a `DataFrame` or `Series`

# Data Analysis Results

1. What is the average temperature for each month?
The data highlights that the winter season encompasses the months with the lowest temperatures, particularly in January and February, which tend to be the coldest months of the year. The temperature gradually increases through spring, peaking in the summer months. July is identified as the hottest month of the year, followed closely by August, where temperatures begin to slightly decrease.


2. How does humidity correlate with temperature?
The correlation coefficient will be a value between -1 and 1:
  - 1 indicates a perfect positive correlation.
  - 0 indicates no correlation.
  - -1 indicates a perfect negative correlation.

  For example, in this dataset, the correlation coefficient of -0.6 would suggest a moderate negative correlation, meaning that as the temperature increases, the humidity tends to decrease moderately.

3. How does temperature vary over time?
  - Seasonal Changes: There's a clear pattern of temperature changes repeating every year. Warm temperatures peak during the summer months, and cold temperatures drop during the winter months.
  - Temperature Range: The difference between the highest and lowest temperatures is quite large, indicating distinct seasons with very warm and very cold periods.
  - Yearly Consistency: The annual temperature pattern remains stable over the years, suggesting consistent seasonal changes without major shifts over the time period analyzed.

# Development Environment

- Visual Studio Code
- Git / GitHub
- Python
- Pandas (statistics library)
- Matplotlib (Data visualization)
- Kaggle - [weather dataset](https://www.kaggle.com/datasets/muthuj7/weather-dataset)
- Jupyter extension (Notebooks)

>> A notebook for writing in Pandas refers to a Jupyter Notebook, an open-source web application that allows you to create and share documents containing live code, equations, visualizations, and narrative text. Jupyter Notebooks are widely used for data analysis, scientific research, and machine learning. The Jupyter extension in VS Code brings the functionality of Jupyter Notebooks into a powerful, integrated development environment.

# Useful Websites

* [Dataset - Kaggle](https://www.kaggle.com/)
* [Pandas - documentation](https://pandas.pydata.org/docs/)
* [Pandas Repository - Cookbook](https://pandas.pydata.org/docs/user_guide/cookbook.html#cookbook)
* [Pandas - Essential basic functionality](https://pandas.pydata.org/docs/user_guide/basics.html#basics)
* [Matplotlib - statistical data visualization](https://matplotlib.org/stable/)
* [Seaborn - statistical data visualization](https://seaborn.pydata.org/index.html)

# Future Work

* No future work for now