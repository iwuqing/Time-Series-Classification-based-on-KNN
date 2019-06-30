# GestureWiimote dataset

The original data include 10 subjects, each perform 10 gestures 10 times. The gesture acquisition device is a Nintendo Wiimote remote controller with built-in three-axis accelerometer. Time series are of different lengths. There is no missing values.

The gestures are (class label. original label - English translation): 
1. poteg – pick-up
2. shake – shake
3. desno – one move to the right
4. levo – one move to the left
5. gor – one move to up
6. dol – one move to down
7. kroglevo – one left circle
8. krogdesno – one right circle
9. suneknot – one move toward the screen
10. sunekven – one move away from the screen

We make five datasets out of these data. 

## AllGestureWiimoteX

Data is acceleration in x-axis dimension. Each subject performs a set of gestures multiple times. Classes are based on gestures (see class labels above).

- Train size: 300

- Test size: 700

- Missing value: No

- Number of classses: 10

- Time series length: Vary

Each time series is padded with NaN to the length of the longest time series in the dataset.

## AllGestureWiimoteY

Data is acceleration in y-axis dimension. Each subject performs a set of gestures multiple times. Classes are based on gestures (see class labels above).

- Train size: 300

- Test size: 700

- Missing value: No

- Number of classses: 10

- Time series length: Vary

Each time series is padded with NaN to the length of the longest time series in the dataset.

## AllGestureWiimoteZ

Data is acceleration in z-axis dimension. Classes are based on gestures (see class labels above). 

- Train size: 300

- Test size: 700

- Missing value: No

- Number of classses: 10

- Time series length: Vary

Each time series is padded with NaN to the length of the longest time series in the dataset.

## PickupGestureWiimoteZ

Data is acceleration in z-axis dimension. Each subject performs "pick-up" gesture multiple times. Classes are based on subject. 

- Train size: 50

- Test size: 50

- Missing value: No

- Number of classses: 10

- Time series length: Vary

Each time series is padded with NaN to the length of the longest time series in the dataset.

## ShakeGestureWiimoteZ

Data is acceleration in z-axis dimension. Each subject performs "shake" gesture multiple times. Classes are based on subject. 

- Train size: 50

- Test size: 50

- Missing value: No

- Number of classses: 10

- Time series length: Vary

There is nothing to infer from the order of examples in the train and test set.

Each time series is padded with NaN to the length of the longest time series in the dataset.

Note that data are shuffled and randomly sampled so that instances across datasets do not sychronized by dimension or subject.

Data created by Guna Jože et al. (see [1]). Data edited by Hoang Anh Dau.

[1] Guna, Jože, Iztok Humar, and Matevž Pogačnik. "Intuitive gesture based user identification system." Telecommunications and Signal Processing (TSP), 2012 35th International Conference on. IEEE, 2012.

