Introduction

For my project, I will be exploring the total land precipitation trends within the Northeast United States through the years of 1990-2010. One of the most concerning aspects of climate change is how it will impact global weather patterns, and this is my main motivation in choosing precipitation as my research variable. My intention is to discover any conclusive changes in the Northeast U.S. on a recent scale, as this is a region with unusual patterns of precipitation compared to the rest of the U.S. This is mainly due to the Lake-Effect snowfall from the Great Lakes, as well as the strong and varied precipitation caused by the cold core cyclones that occur in the winter, known as "Nor'Easters." I also intend to indentify any changes in the precipitation trends for spring and summer, as it is important to include all forms of precipitation in my research since my dataset accounts for all of them.

Data

My project will make use of the ERA5 Global Reanalysis, which is a data set that covers a massive amount of atmospheric and weather data, including precipitation and temperature data, which spans as far back as the mid-1900s (Hersbach et al, 2020). The ERA5 Global Reanalysis was created by the European Center for Medium-Range Weather Forecasts with a resolution of 0.25 Degrees, and is consistently updated with both new and changing atmospheric data (ECMWF, n.d.). Because of the size of this data set, I will only be working with northeast region of the U.S., while focusing on the variable of total precipitation between the years of 1990-2010. The precipitation values compiled in my dataset are categorized as m/day, and I changed them to values of mm/day by multiplying the precipitation values by 1000.

Code Description

Aggregates

Over the entire time span, the average daily precipitation was around 3.311 mm/day for the entire area of land, with a standard deviation of 1.507. These values were calculated using the mean and standard deviation functions in numpy, and included the total precipitation values over the entire 1990-2010 time span. Figure 1 shows the mean total precipitation spread throughout the entire Northeast U.S., with a color scale of 2.5-4.5 mm/day that includes all the mean values. 

[Project Proposal](https://jstiles9552.github.io/CLIM_680_Project/Project_Proposal.html)

[Project Update](https://jstiles9552.github.io/CLIM_680_Project/Project_Update.html)
