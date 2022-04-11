# Pyber Analysis #

## Overview of the analysis: ##

For this project we explored the different types of charts that we can generate based on RideSharing data iand how it can provide very quick overviews of larger amount of data.

For the riding share data 2 files in CSV format were read and later merged into 1 dataframe.

![](/images/merged_dataframe.png)

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
{Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
}

 Ride Count Data| Ride Fares Data | Driver Count Data
------------- | ------------- | -------------
 ![](/analysis/Fig2.png) |  ![](/analysis/Fig3.png)  | ![](/analysis/Fig4.png)
