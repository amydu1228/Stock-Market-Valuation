# Stock-Market-Valuation

## Goal:
Applied cyclically-adjusted price-to-earnings (CAPE) ratio to evaluate whether a S&P 500 stock index market is overvalued, undervalued, or fairly-valued. 

## Data:
Downloaded the Data From Robert Shiller Online Database. http://www.econ.yale.edu/~shiller/data.htm

The following features were gathered:
* S&P_Composite
* Dividends
* Earnings
* Consumer_Price_Index

Tools & Packages Required:
* Python
* Numpy
* Pandas
* Pandas_datareader
* Matplotlib

## Project Approach:
There are four steps that in this project:
* Step 1: Download the Data From Robert Shiller Online Database
* Step 2: Adjust for Inflation
* Step 3: Add Recession Indicator through accessing data from the St. Louis Federal Reserve data service
* Step 4: Plot CAPE Model through mattplotlib

## Final Results and Future Improvements:
CAPE ratio employs the average earnings over the past business cycle, not just one year that may have bad or good earnings.
The ratio is also important for identifying potential bubbles and market crashes and would be a great guidance for investors in determining investment strategies at various market valuation.

CAPE limitation:
1. It is not quite helpful since it is essentially backward-looking, more than it is forward-looking. 
2. The ratio relies on GAAP earnings, which have been changed in recent years. 
