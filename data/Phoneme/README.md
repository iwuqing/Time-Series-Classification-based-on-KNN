# Phoneme

This dataset is a subsample of the data used in [1]. Each series is extracted from the segmented audio collected from Google Translate, oxforddictionaries.com and the Merrriam-Webster online dictionary. Each of these sources have different features. Audio files collected from Google translate, Oxford, and Merrriam-Webster dictionaries are recorded at 22050, 44100 and 11025 samples per second respectively. All of them have male and female speakers in different ratios. The Oxford dictionary includes British and American accent pronunciation for each word. After data collection, waveforms of the words are segmented to generate phonemes using the Forced Aligner tool from the Penn Phonetics Laboratory.

Train size: 214

Test size: 1896

Missing value: No

Number of classses: 39

Time series length: 1024

Data donated by Hossein Hamooni and Abdullah Mueen (see [1], [2], [3]).

[1] Hamooni, Hossein, and Abdullah Mueen. "Dual-domain hierarchical classification of phonetic time series." Data Mining (ICDM), 2014 IEEE International Conference on. IEEE, 2014.

[2] https://www.cs.unm.edu/~hamooni/papers/Dual_2014/index.html

[3] http://www.timeseriesclassification.com/description.php?Dataset=Phoneme