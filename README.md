This repository is for visualize and analyze financial trading data using python.  In building them, we learn about stocks and commodities from different industries, such as education 教育 , technology 科技 and cybersecurity 网路安全, oil companies and oil prices 油价, and crypto currency Bitcoin 比特币. 

- technology stocks: Apple (APPL), Microsoft (MSFT), 
- cybersecurity: Zscaler
- oil: Exxon, BP, WTI crude oil prices

### Data sources:
1. For most financial data, we use Python library pandas_datareader to access financial data from different sources  most recent  trading data from Yahoo Finance
2. For oil prices, we use data from [Federal Reserve Bank of St. Louis](https://fred.stlouisfed.org/series/DCOILWTICO/). 

# See the data yourself than just hearing from other people. 百闻不如一见
Wouldn't it be cool if you develop a magical ability to tell which stock is going to do great like Warren Buffet?  Well, that will take a lot of learning of different kinds of subjects. But the most important is numbers. 

# *learning by doing*  
While we can go to sites such as Yahoo Finance, Google and many more to visualize the data, we want to be able to analyze the data anyway we want.  This is the zen of learning: learning by doing. 
 
We can apply the techniques we learn to any stock or other time series data and to develop new techniques and insights.   
 
# Trading prices and volume time series
## Plotting
Plotting is not just for pretty colors and shapes.  
It is impossible to read thousands of rows of prices and trading volumes and quickly get an idea how the stock or commodity has been traded.  That is why visualization is necessary.  
1. Different styling
2. Line plots
3. Bar plots
4. Area plots

## Basic data cleaning
No matter where the data comes from, we should do some basic checking for anomalies and errors.  If there is anything usual, we should try to find out why, which may uncover interesting stories that others may have missed.  Besides, we can trust our analysis only if we can reasonably assume the data is mostly error free. 
1. Remove duplicates
2. Check if there is any missing data
3. Error checking

## Time series data 时间序列 essential data mining tools
1. Rolling (moving) window 
2. Resampling
3. Select data with different frequencies
