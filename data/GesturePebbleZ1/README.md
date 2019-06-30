# GesturePebble dataset

The data are collected with Pebble smart watch featuring 3-axis accelerometer. Data collection involves 4 subjects perform 6 gestures in two sessions several days apart. 

There are 6 classes corresponding to distinct gestures (see the paper for gesture depiction and annotation).

- Class 1: hh
- Class 2: hu
- Class 3: ud
- Class 4: hud
- Class 5: hh2
- Class 6: hu2

We make two datasets out of these data.

## GesturePebbleZ1

This uses z-axis reading only. The train set contains data of all 4 subjects collected in the first session. The test set is data of all 4 subjects collected in the second session. 

Train size: 132

Test size: 172

Number of classes: 6

Missing value: No

Time series length: Vary

For processing convenience, we pad NaN to the end of each time series to the length of the longest time series.

## GesturePebbleZ2 

This uses z-axis reading only. The train set contains data of two subjects collected in both sessions. The test set is data of the other two subjects collected in both sessions. Note that in this case, a same subject does not appear in both train and test set. 

Train size: 146

Test size: 158

Number of classes: 6

Missing value: No

Time series length: Vary

There is nothing to infer from the order of examples in the train and test set.

For processing convenience, we pad NaN to the end of each time series to the length of the longest time series.

Data created by Mezari, Antigoni, and Ilias Maglogiannis (see [1]). Data edited by Hoang Anh Dau. 

[1] Mezari, Antigoni, and Ilias Maglogiannis. "Gesture recognition using symbolic aggregate approximation and dynamic time warping on motion data." Proceedings of the 11th EAI International Conference on Pervasive Computing Technologies for Healthcare. ACM, 2017.
