# Refactoring VBA

## Overview of Project

The purpose of this project was to refactor the previous solution code, to see if refactoring shortened the length of time for the code to run. The original code works well for the 12 stocks, but might not be efficient for a larger amount of stocks in the future.

## Results

Both codes produced the same results, showing 2017 was a much better year. By refactoring, and creating a ticker index, with the code Dim tickerIndex, it ran much faster. This allowed for all tickers to be run simutaneously. The differences in time are shown in the images below.

[![image](https://github.com/eric-blankinshp/stock-analysis/blob/main/Resources/Original_2017.png)      
[![image](https://github.com/eric-blankinshp/stock-analysis/blob/main/Resources/Original_2018.png)
[![image](https://github.com/eric-blankinshp/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png?raw=true)
[![image](https://github.com/eric-blankinshp/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png)




## Summary

The advantage of refactoring code, is to make it run more efficiently and faster. The disadvantage, is that you are more likely to run into errors. This also will take  more time to write.

The advantage for this challenge, was that it did run much faster. The results were the same. The disadvantage, was the time and difficulty it took to refactor it. The small data set that is being used, does not make this an affective use of time. For a larger data set, this would be a better use of time. 
