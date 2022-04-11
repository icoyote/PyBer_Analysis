# Pyber Analysis #

## Overview of the analysis: ##

For this project we explored the different types of charts that we can generate based on RideSharing data and how it can provide quick overviews of larger amounts of data.

For the riding share data 2 files in CSV format were read and later merged into 1 dataframe.

![](/images/merged_dataframe.png)

The Bubble plot (aka Scatter Plot) was selected because 3 series of values could be represented.
on the X axis: the total number of rides per city type
Yaxis: the Average Fare
and the 3rd data is the total number of Drivers represented by the size of the Bubbble


 Bubble urban | Bubble Suburban  | Bubble rural 
------------- | ------------- | -------------
 ![](/images/bubble_urban.png) |  ![](/images/bubble_suburban.png)  | ![](/images/bubble_rural.png)

all 3 city types graphed in the same bubble chart
![](/analysis/Fig1.png)

Presented in this format we notice that the URBAN Rides have the greatest amount of Drivers and number of Rides However the price ranges for the Urban rides are on the lower spectrum of the prices.


## Results: ##

### Deliverable 1: Summary DataFrame ###

This Ride-Sharing Summary was built by performing different **GROUPBY** operations on the merged DataFrame, During the preparation module the same summary by City types was achieved by creating 3 separate dataFrames filtered by the type "Urban","Suburban","Rural"

![](/images/SummaryDataFrame.png)

While obtaining these values, the total numbers were matching the ones obtained in the first part of the Analysis and therefore would be a visual aid for the Summary table presented

 % Fares by City Type | % Total Rides by City Type | % Total drivers by City Type
------------- | ------------- | -------------
 ![](/analysis/Fig5.png) |  ![](/analysis/Fig6.png)  | ![](/analysis/Fig7.png)


### Deliverable 2: multiple line plot that shows the total weekly of the fares for each type of city ###
![](/analysis/PyBer_fare_summary.png)



## Summary ##

Total weekly Fares by city type| Ride Sharing data for 2019
------------- | ------------- 
 ![](/analysis/PyBer_fare_summary.png) |  ![](/images/Bubble_Screen.png) 
 
 These 2 graphs side by side  leads us to the conclusion that
 
 - The Urban City Type is the most profitable sector for the company with a total amount of fares of ** Urban $39,854.38 **
 - The rural Sector is the leat profitable with a total amount of fares of ** Rural  $4,327.93 **
 - It has the largest amount of Drivers (**Urban drivers 2405**) and also completes the largest number of rides (**Urban rides 1625**).
 - Despite having the highest average fare per ride (**Average Rural Fare $34.62**) and the highest fare per driver (**Average Rural Fare per driver $55.49**) the total revenue for the Rural type of rides is the lowest overall and can be found as the blue line at the bottom of the Line graph.

 Ride Count Data| Ride Fares Data | Driver Count Data
------------- | ------------- | -------------
 ![](/analysis/Fig2.png) |  ![](/analysis/Fig3.png)  | ![](/analysis/Fig4.png)
 
 Based on these figures these are my recommendations:
 
 - focus on recruitement of new drivers for the Rural Areas.
 - An increase in Drivers availability for the Rural area, will also bring the average Proce per Ride lower closer to the Suburban and Urban areas.
 - the driver count in compared to the Urban are for the Suburban city type is also on the loer range. It would be interesting to also recruit drivers for the Urban to also service the Suburban areas.
 
