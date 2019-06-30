# Trace

This dataset is a subset of the Transient Classification Benchmark (Trace project), an initiative at the turn of the twentieth century to collate data from the application domain of the process industry (e.g. nuclear, chemical, etc.). It is a synthetic dataset designed to simulate instrumentation failures in a nuclear power plant, created by Davide Roverso (see [1]). The full dataset consists of 16 classes, with 50 instances in each class. Each instance has four features. 

The *Trace* subset is a four-class time series classification problem. It only uses the second feature of class 2 and 6, and the third feature of class 3 and 7. All instances are linearly interpolated to have the same length of 275 data points, and are z-normalized. The data were used in [2].

Train size: 100

Test size: 100

Missing value: No

Number of classses: 4

Time series length: 275

Data donated by Davide Roverso (see [1], [2], [3]).

[1] Roverso, Davide. "Multivariate temporal classification by windowed wavelet decomposition and recurrent neural networks." 3rd ANS international topical meeting on nuclear plant instrumentation, control and human-machine interface. Vol. 20. 2000.

[2] Ratanamahatana, Chotirat Ann, and Eamonn Keogh. "Making time-series classification more accurate using learned constraints." Proceedings of the 2004 SIAM International Conference on Data Mining. Society for Industrial and Applied Mathematics, 2004.

[3] http://www.timeseriesclassification.com/description.php?Dataset=Trace