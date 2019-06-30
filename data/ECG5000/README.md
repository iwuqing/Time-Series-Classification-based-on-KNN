# ECG5000

The original dataset for *ECG5000* is a 20-hour long ECG downloaded from Physionet_ATM [1]. The database is BIDMC Congestive Heart Failure Database(chfdb) and the record is chf07. It was originally published by Goldberger et al. [2]. The data were pre-processed in two steps, first extracting each heartbeat and then making each heartbeat equal length using interpolation. These data were originally used by Chen et al. [3]. After that, 5000 heartbeats were randomly selected to make the current dataset. Data are from a patient who has severe congestive heart failure and the class values were obtained by automated annotation.

Train size: 500

Test size: 4500

Missing value: No

Number of classses: 5

Time series length: 140

Data donated by Yanping Chen and Eamonn Keogh (see [3], [4]).

[1] https://physionet.org/cgi-bin/atm/ATM

[2] Goldberger, Ary L., et al. "PhysioBank, PhysioToolkit, and PhysioNet: components of a new research resource for complex physiologic signals." Circulation 101.23 (2000): e215-e220.

[3] Chen, Yanping, et al. "A general framework for never-ending learning from time series streams." Data Mining and Knowledge Discovery 29.6 (2015): 1622-1664.

[4] http://www.timeseriesclassification.com/description.php?Dataset=ECG5000