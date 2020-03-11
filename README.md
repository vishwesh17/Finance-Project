# Finance-Project

The project deals with 5 bank stock data from 1st Jan 2006 - 1st Jan 2016. The project includes exploratory data analysis and visualization.
Libraries used:pandas_datareader, pandas,n umpy, datatime, seaborn, plotly, cufflinks

Getting the Data: We have used pandas to directly read data from Yahoo finance. pandas_datareader allows us to read stock information directly from internet.
for installing pandas_datareader (pip install pandas-datareader) 

Data: We will get the data using pandas_datareader for following banks(we can get data of any listed companies):
* Bank of America
* CitiGroup
* Goldman Sachs
* JPMorgan Chase
* Morgan Stanley
* Wells Fargo

1. Use datetime to set start and end datetime object(we can use any dates, checck 2nd cell in .ipynb file)
2. Figure out the ticker symbol for each bank ( we can find ticker symbol through google search)
3. Figure out how to use datareader to grab info of the stock 
https://pandas-datareader.readthedocs.io/en/latest/remote_data.html
Use the above documentation link for hints and instruction (in this project I have used yahoo finance)

for example:

Bank of America

BAC = data.DataReader("BAC", 'yahoo', start, end)

NOTE: Make sure to check the link above for latest working API. 'yahoo' may not work always. 


