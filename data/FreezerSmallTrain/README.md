# Electrical Load Measurement dataset

The collection of this data was part of the project titled Personalised Retrofit Decision Support Tools for UK Homes using Smart Home Technology (REFIT). The REFIT dataset includes data from 20 households from Loughborough area over the period 2013-2014 (see [1], [2]).

We use data of freezers in House 1 to make two datasets. These two datasets share a same test set and only differ in the number of training instances. 

There are two classes, one representing the power demand of the fridge freezer in the kitchen, the other representing the power demand of the (less frequently used) freezer in the garage. They are hard to tell apart globally but they differ locally. 

## FreezerRegularTrain

Train size: 150

Test size: 2850

Missing value: No

Number of classses: 2

Time series length: 301

## FreezerSmallTrain

Train size: 28

Test size: 2850

Missing value: No

Number of classses: 2

Time series length: 301

We use data of House 20 to make one dataset. There are two classes. The first class is household aggregate usage of electricity. The second class is aggregate electricity load of Tumble Dryer and Washing Machine.

## HouseTwenty

Train size: 40

Test size: 119

Missing value: No

Number of classses: 2

Time series length: 2000

There is nothing to infer from the order of examples in the train and test set.

Data created by David Murray et al. (see [2]). Data edited by Shaghayegh Gharghabi, Hoang Anh Dau and Eamonn Keogh.

[1] http://www.refitsmarthomes.org/

[2] Murray, David et al., "A data management platform for personalised real-time energy
feedback", Proceedings of the 8th International Conference on Engery Efficiency in Domestic Appliances and Lighting, 2015.