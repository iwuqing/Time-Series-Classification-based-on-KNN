# SemgHand dataset

The data are surface electromyography (sEMG) signal, which captures electric activity of groups of muscle at rest or during activity. Data collection involves five healthy subjects conducting six movements of hand grasps. Collection device is Delsys' 2-channel EMG system.

We extract the power spectrum from the raw data to make three datasets.

## SemgHandSubjectCh2

We use data of channel 2 only. Classes correspond to subjects.

- Class 1: Female 1
- Class 2: Female 2
- Class 3: Female 3
- Class 4: Male 1
- Class 5: Male 2

Train size: 450

Test size: 450

Number of classes: 5

Missing value: No

Time series length: 1500

## SemgHandMovementCh2

We use data of channel 2 only. Classes correspond to movements of hand grasps.

- Class 1: Cylindrical
- Class 2: Hook
- Class 3: Tip
- Class 4: Palmar
- Class 5: Spherical
- Class 6: Lateral

Train size: 450

Test size: 450

Number of classes: 6

Missing value: No

Time series length: 1500

## SemgHandGenderCh2

We use data of channel 2 only. Classes correspond to gender. 

- Class 1: Female
- Class 2: Male

Train size: 300

Test size: 600

Number of classes: 2

Missing value: No

Time series length: 1500

There is nothing to infer from the order of examples in the train and test set.

Data created by Sapsanis, Christos, et al. (see [1], [2]. Data edited by Chin-Chia Michael Yeh.

[1] Sapsanis, Christos, et al. "Improving EMG based classification of basic hand movements using EMD." Engineering in Medicine and Biology Society (EMBC), 2013 35th Annual International Conference of the IEEE. IEEE, 2013.

[2] “UCI Machine Learning Repository: SEMG for Basic Hand Movements Data Set.” UCI Machine Learning Repository, URL archive.ics.uci.edu/ml/datasets/sEMG+for+Basic+Hand+movements.
