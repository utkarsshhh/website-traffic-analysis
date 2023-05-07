# website-traffic-analysis

__The code is analysing the web traffic on a website over the period of 7 days. It can be used to develop ideas on how to increase the click rates__


## Introduction

I have build this project based on the data provided by [Stratascratch](https://www.stratascratch.com) as part of a business analysis data project. It contains the web-traffic data for different over 7 days. To increase the click-rate of the links I have done the following analysis on the data:
1. How many total pageview events did the links in the provided dataset receive in the full period, how many per day?
2. How many total other events did the links in the provided dataset receive in the full period?
3. Which countries did the pageviews come from?
4. What was the overall click rate (clicks/pageviews)?
5. How does the clickrate distribute across different links?
6. Is there any correlation between clicks and previews on a link? How large is the effect? What is the relation between the          categorical variables?


## Usage

### Installation

The code is present in a Jupyter Notebook __Business_Analysis.ipynb__ and requires Python 3.9 to run it. The Jupyter Notebook can be run in the browser or can be installed from [here](https://jupyter.org)

### Data

The data is present in the datasets folder in the root directory. It consists of a single csv file __traffic.csv__ which contains all the website-traffic.

### Libraries
The following libraries have been used in the code:
1. [pandas](https://pandas.pydata.org)
2. [datetime](https://docs.python.org/3/library/datetime.html)
3. [matplotlib](https://matplotlib.org)
4. [numpy](http://numpy.org)
5. [SciPy](https://scipy.org)


## Result

I have performed Exploratory Data Analysis(EDA) on the data using pandas and numpy to identify the characteristics useful to the business requirements. I have used the maplotlib library to visualise the analysis. The SciPy library has been used to identify the correlation of the features and variables.





