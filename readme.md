# Welcome to this simple test

## Files description

- *"Hourly_consumption_MW.csv"*: Hourly power consumption in MegaWatt
- *"readme.md"* : This file

## Tasks 

_For the tasks 3,4,5,6,7 compute and save in a csv file "timing.csv" the execution time required for the code to run_

1) Import datas into pandas from the .csv file 
2) Explore them with the features you consider relevant and perform, evenually, data cleaning to remove data inconsistency
3) Print and save a stacked line graph ("Graph1") representing the weekly consumption in MW/h and comparing the years from 2006 to 2016
4) For each year identify the day with the highest consumptions and the day with the lowest consumptions. Plot a graph that represents the evolution of the consumption during these days, in order to obtain a comparison between "peak-days" over the years.
6) Identify the 10 days where the delta between the energy consumed in that day and in the day after is greater (that means higher adaptation stress on the production plants).
5) Create and export as a CSV a dataset called "ProductionSchedule". Set it up with a daily basis and for each day provide:
	- The total energetic production needed to cover the full consumption of the next day.
	- The average power consumption during the next day 
	- The standard deviation of the consumption during the next day
7) OPTIONAL: On an hour basis mark the time periods where the consumption is higher than: *average + 3\*standard deviation* of the prediciton for that days. And plot the data for one month of your choice.


Thanks for your time

Miraitek Srl.