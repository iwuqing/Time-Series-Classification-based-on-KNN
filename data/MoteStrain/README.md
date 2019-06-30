# MoteStrain

This sensor data was originally from Carlos Guestrin (CMU). It was subsequently used in [1] and later formatted for classification by Eamonn Keogh. The task is to distinguish between sensor q8calibHumid (a humidity measure) and sensor q8calibHumTemp (a temperature measure). The data has dropouts. In the original data the dropouts have value 0. This means they are difficult to detect with normalised data.

Train size: 20

Test size: 1252

Missing value: No

Number of classses: 2

Time series length: 84

Data donated by Carlos Guestrin, Jimeng Sun. Data edited by Eamonn Keogh. (see [1], [2])

[1] Sun, Jimeng, Spiros Papadimitriou, and Christos Faloutsos. "Online latent variable detection in sensor networks." Data Engineering, 2005. ICDE 2005. Proceedings. 21st International Conference on. IEEE, 2005.

[2] http://www.timeseriesclassification.com/description.php?Dataset=MoteStrain