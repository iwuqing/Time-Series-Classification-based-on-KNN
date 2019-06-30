
# Missing values and variable lengths data sets

This folder concerns 14 data sets with missing values and variable lengths. We herewith include the equal length version that leads to the result published on the UCR archive website in the interest of reproducible research. 

We makes all time series of equal length with the following practices:
- Missing values are treated with linear interpolation.
- Variable lengths are reconciled by padding low amplitude random noise to the end of each time series to the length of the longest time series.

The need for making time series of equal length arises because:
- Euclidean distance is only defined for equal length time series.
- Some of the well-known lowerbounding techniques for DTW only work if time series are of equal length (even thougth DTW distance is possible between variable lengths time series).

The first three data sets (numbered 1-3) are data sets with missing values. The rest are datasets of unequal lengths. Within a data set, the difference between the length of the shortest and longest time series can be dramatic. For example, in case of PLAID, that is 101 vs. 1344. Some of the data sets might contain noisy examples, for which an ideal classifier should have the option to ignore or label them as 'not sure'. 

1. DodgerLoopDay
2. DodgerLoopGame
3. DodgerLoopWeekend
4. AllGestureWiimoteX
5. AllGestureWiimoteY
6. AllGestureWiimoteZ
7. GestureMidAirD1
8. GestureMidAirD2
9. GestureMidAirD3
10. GesturePebbleZ1
11. GesturePebbleZ2
12. PickupGestureWiimoteZ
13. PLAID
14. ShakeGestureWiimoteZ

We thank Germain Forestier and Hassan Ismail Fawaz at University of Haute Alsace for bringing this matter to our attention and other constructive comments.