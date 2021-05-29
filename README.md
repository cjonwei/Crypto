# A Simple Exploration of the Cryptocurrency Market based on Historical Prices.

## Introduction

This project aims to utilise the available Crypto dataset to obtain a brief understanding of the market, its top coins, historical prices, volume movements and potential correlations between the dataset.

## Data Dictionary

|Field         | Description                                                       |
|:-------------| :-----------------------------------------------------------------|
|slug          | Name of the coin                                                  |
|symbol        | Symbol of the coin                                                |
|name          | Name of the coin                                                  |
|date          | Date of datapoint                                                 |
|ranknow       | Rank as of date of datapoint                                      |
|open          | Opening price as of date of datapoint                             |
|high          | Highest price as of date of datapoint                             |
|low           | Lowest price as of date of datapoint                              |
|close         | Closing price as of date of datapoint                             |
|volume        | Volume of coins transacted as of date of datapoint                |
|market        | Marketcap of coin as of date of datapoint                         |
|close_ratio   | Spread between close and open prices / spread field below         |
|spread        | Variance between highest and lowest price as of date of datapoint | 

*************************************************************************************************

## Milestone 1 and 2:

(1) Loaded data into book.

(2) Check out the shape, the columns, the data types. 

(3) Used head and describe to better understand available data set columns.

(4) Doesnt appear to have any missing data of inconsistent data. Used (null).

(5) Dont think i'll use all columns for the analysis but will retain the option to. Will not drop any datapoints.

(6) Things we know so far:-
     
     (a) There are 13 columns detailed out within the dictionary above.
     
     (b) There are 942,294 data points across multiple coins.
     
     (c) Data set begins on 2013-04-28 and ends on 2018-11-29. 
     
     (d) Bitcoin (BTC) has the most available data of all coins (2042 data points in total - eg. 5.6 years of data).
     
     (e) There are 2071 unique coins within the data set.

(7) Preliminary framing of the problem:-
     
     (a) It is a large data set with >2000 coins. We need to zero in on the Top / Top few to analyse trends. 
     
     (b) To understand importance of coins, we need to understand the value of top coins vs total market cap.
     
     (c) We can then dive deeper into the price and volume trends over time for selected coin.
     
     (d) We can then google news relating to selected coin for outlier timeframes to understand reason for movements.
     
     (e) We can also calculate the correlation between prices and volumes to better understand their relationship.
 
*************************************************************************************************

## Milestone 3:


*************************************************************************************************

## Important Links

* [Final Report Notebook](report.ipynb)
* [EDA Notebook](eda.ipynb)
* [Link 1](http://www.google.com) - Some cool stuff
* [Link 2](http://www.google.com) - More cool stuff
* [Link 3](http://www.google.com) - Even more cool stuff
