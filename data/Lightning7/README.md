# Lightning7

The Fast On-orbit Recording of Transient Events satellite (FORTE) detects transient electromagnetic events associated with lightning using a suite of optical and radio-frequency (RF) instruments. Sampling rate was 50MHz over a period of 800 microseconds. A Fourier transform is performed on the input data to produce a spectrogram. The spectrograms are then collapsed in frequency to produce a power density time series, with 3181 samples in each time series. These are then smoothed to produce series of length 637. 

There are 7 classes as described in [1]: (label: name: description)
- CG: Positive: Initial Return Stroke A positive charge is lowered from a cloud to the ground. The characteristic feature of this type of event in the power density time series is a sharp turn-on of radiation, followed by a few hundreds of microseconds of noise. 
- IR: Negative Initial Return Stroke A negative charge is lowered from a cloud to ground. The power waveform slowly ramps up to a level known as an attachment point, where a large surge current causes the VHF power to 'spike'. This attachment is followed by an exponentially shaped decline in the waveform. 
- SR: Subsequent Negative Return Stroke A negative charge is lowered from a cloud to ground. As the name implies, subsequent return strokes come after initial return strokes. Note that subsequent positive return strokes don't exist. 
- I: Impulsive Event Typically an intra-cloud event characterized by a sudden peak in the waveform. 
- I2: Impulsive Event Pair Another intra-cloud event characterized by sudden peaks in the waveform that come in closely separated pairs. These are also called TIPPs (Trans-Ionospheric Pulse Pairs). 
- KM: Gradual Intra-Cloud Stroke An intra-cloud event which increases in power more gradually than an impulsive event. 
- O: Off-record 800 microseconds was not enough to fully capture the lightning event.

Train size: 70

Test size: 73

Missing value: No

Number of classses: 7

Time series length: 319

Data donated by Damian Eads (see [1], [2]).

[1] Eads, Damian R., et al. "Genetic algorithms and support vector machines for time series classification." Applications and Science of Neural Networks, Fuzzy Systems, and Evolutionary Computation V. Vol. 4787. International Society for Optics and Photonics, 2002.

[2] http://www.timeseriesclassification.com/description.php?Dataset=Lightning7