# Time Series Decomposition .R
ts-decomposition.R

Decomposition methods allow us to break time series into their components
* compare the trend-cycle component to the full data
* STL Decomposition components
* seasonally-adjusted series 
* Moving Averages


Classical time series decomposition uses moving averages to deconstruct a time series into trend, season, and remainder components
* Step 1 - calculate the trend component with an MA
* Step 2 - deduct the trend component from the time series (de-trend)
* Step 3 - calculate the average of the de-trended series for each season
* Step 4 - deduct the trend and season components from the time series

![image](https://user-images.githubusercontent.com/65502025/156649563-cdbe2a03-7589-40ab-bae2-e402b5a424d4.png)


![image](https://user-images.githubusercontent.com/65502025/156649512-07b5e4cc-0e3b-489e-b974-c5e98e187c04.png)
