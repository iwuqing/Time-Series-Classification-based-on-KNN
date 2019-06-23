# PedestrianCountingSystem dataset

The City of Melbourne, Australia has developed an automated pedestrian counting system to better understand pedestrian activity within the municipality, such as how people use different city locations at different time of the day. The data analysis can facility decision making and urban planning for the future. 

We extract data of 10 locations for the whole year 2017. We make two datasets from these data.

## MelbournePedestrian

Data are pedestrian count for 12 months of the year 2017. Classes correspond location of sensor placement.

- Class 1: Bourke Street Mall (North)
- Class 2: Southern Cross Station
- Class 3: New Quay
- Class 4: Flinders St Station Underpass
- Class 5: QV Market-Elizabeth (West)
- Class 6: Convention/Exhibition Centre
- Class 7: Chinatown-Swanston St (North)
- Class 8: Webb Bridge
- Class 9: Tin Alley-Swanston St (West)
- Class 10: Southbank

Train size: 1200

Test size: 2450

Missing value: No

Number of classses: 10

Time series length: 24

## Chinatown

Data are pedestrian count in Chinatown-Swanston St (North for 12 months of the year 2017. Classes are based on whether data are from a normal day or a weekend day.  

- Class 1: Weekend
- Class 2: Weekday

Train size: 20

Test size: 345

Missing value: No

Number of classses: 2

Time series length: 24

There is nothing to infer from the order of examples in the train and test set.

Data source: City of Melbourne (see [1]). Data edited by Hoang Anh Dau.

[1] http://www.pedestrian.melbourne.vic.gov.au/#date=11-06-2018&time=4