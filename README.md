# surfs_up
## OverView
This project is aimed to use SQLalchemy to filter the columns in ```hawaii.sqlite``` database. Create list and dataframe from the reuslt and retrieve climate statistics of specific date and plot it's data throughout pandas, matplotlib and numpy. After the collection, make an html file that would reflect the jasonified statistics.

## Background
> W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Result
#### June Temperature
![6_Stat](https://github.com/WilliamBHW/surfs_up/blob/main/Resources/6_Stat.png)
- Observations: 1700
- Mean Temperature: 74.94
- Minimum Temperature: 64.00
- Maximum Temperature: 85.00
- Standard Deviation: 3.26

#### December Temperature
![12_Stat](https://github.com/WilliamBHW/surfs_up/blob/main/Resources/12_Stat.png)
- Observations: 1517
- Mean Temperature: 71.04
- Minimum Temperature: 56.00
- Maximum Temperature: 83.00
- Standard Deviation: 3.75

## Summary
Bsed on the summary statistics from june and december data, there is a standard deviation of 3.26 at june and 3.75 at december. Making a difference of 0.49 between summer and winter month.

In addition, there is a function that is responsible for retriving min, max and average temperature from selected time period from ```climate_analysis.ipynb``` which will be able to runthrough SQLalchemy to collect required statistics.
#### Function calc_temps
![Claim_Stat](https://github.com/WilliamBHW/surfs_up/blob/main/Resources/Claim_Stat.png)
<br>

In the ```climate_analysis.ipynb```, it is able to retrieve percipitation information of given time interval and create graphs for analysis. With given statistics, it is possible to predict how it would like to build a shop and popular areas in the location to attact visitors for purchases.
#### Cliamte Retrial
![Climate_retrival](https://github.com/WilliamBHW/surfs_up/blob/main/Resources/2016-2017_Climate.png)
#### Active Station Retrival
![Active_Station](https://github.com/WilliamBHW/surfs_up/blob/main/Resources/Active_Station.png)
