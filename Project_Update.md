For my maps that show precipitation data, I have managed to mask out the data that was previously displayed within Canada. I accomplished this by the using the "ShapelyFeature" package within cartopy to import the Canada shape, and then assigning it the entire shape a white color so that it masks out the data within Canada.

![ERA5 Mask](ERA5_Mask.png)

This also works with my 12-Month Climatology Plot.

![Climatology Mask](Climatology_Mask.png)
