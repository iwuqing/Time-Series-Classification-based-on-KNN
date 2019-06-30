# EOG

# EOG dataset

The data are electrooculography signal (EOG). EOG is measurements of the electrical potential between electrodes placed at points close to the eyes. The EOG recording device is BlueGain, a commercial biomedical amplifier. Four measurement electrodes are attached to the left, right, upper and lower sides of the left eye. A two-channel (horizontal and vertical) EOG signal is obtained by taking the differences of the signals between the electrodes on the left and right sides and those between the upper and lower sides, respectively. The sampling rate was 1.0KHz.

We use the "Isolated data" described in the paper. This dataset includes 6 participants eye-writing 12 types of Japanese Katakana strokes. 

There are 12 classes. Class labels correspond to stroke ID. See Fig 7 in [1] for the mapping of stroke ID - stroke type.

We make two datasets out of these data.

## EOGHorizontalSignal

The horizontal eye movement (left-right)

Train size: 362

Test size: 362

Number of classes: 12

Missing value: No

Time series length: 1250

## EOGVerticalSignal

The vertical eye movement (up-down)

Train size: 362

Test size: 362

Number of classes: 12

Missing value: No

Time series length: 1250

There is nothing to infer from the order of examples in the train and test set.

Data created by Fang Fuming and Takahiro Shinozaki (see [1]. Data edited by Hoang Anh Dau. 

[1] Fang, Fuming, and Takahiro Shinozaki. "Electrooculography-based continuous eye-writing recognition system for efficient assistive communication systems." PloS one 13.2 (2018): e0192684.