# Lightning2

The Fast On-orbit Recording of Transient Events satellite (FORTE) detects transient electromagnetic events associated with lightning using a suite of optical and radio-frequency (RF) instruments. Sampling rate was 50 MHz over 800 microseconds. A Fourier transform is performed on the input data to produce a spectrogram. The spectrograms are then collapsed in frequency to produce a power density time series with 3181 samples in each time series. These are then smoothed to produce series of length 637. It is not known what the two classes are.

Train size: 60

Test size: 61

Missing value: No

Number of classses: 2

Time series length: 637

Data donated by Damian Eads (see [1], [2]).

[1] Eads, Damian R., et al. "Genetic algorithms and support vector machines for time series classification." Applications and Science of Neural Networks, Fuzzy Systems, and Evolutionary Computation V. Vol. 4787. International Society for Optics and Photonics, 2002.

[2] http://www.timeseriesclassification.com/description.php?Dataset=Lightning2