# Bone Image datasets - MiddlePhalanxOutlineAgeGroup

The dataset is in the series of 10 classification problems created as part of Luke Davis's PhD thesis (see [1], [2]). They are all derived from the same images from Cao et al. (see [3]). They are designed to test the efficacy of hand and bone outline detection and whether these outlines could be helpful in bone age prediction. 

The hand outlines and then the outlines of three bones of the middle finger (proximal, middle and distal phalanges) were extracted automatically (by algorithms) from over 1300 images. Three human evaluators then labelled the output of the image outlining as correct or incorrect. This generated three classification problems: *DistalPhalanxOutlineCorrect*, *MiddlePhalanxOutlineCorrect* and *ProximalPhalanxOutlineCorrect*. 

The next stage of the project was to use the outlines to predict statistics about the subjects age. The three problems *DistalPhalanxOutlineAgeGroup*, *MiddlePhalanxOutlineAgeGroup* and *ProximalPhalanxOutlineAgeGroup* involve using the outline of one of the phalanges to predict whether the subject is from one of three age groups: 0-6 years old, 7-12 years old and 13-19 years old. Note that these problems are aligned by subject, and hence can be treated as a multi dimensional time series classification problem. Dataset *PhalangesOutlinesCorrect* contains the concatenation of all three problems. 

Bone age estimation is usually performed by an expert with an algorithm called Tanner-Whitehouse (TW). This involves scoring each bone into one of seven categories based on the stage of development. The final three bone image classification problems: *DistalPhalanxTW*, *MiddlePhalanxTW* and *ProximalPhalanxTW* are about predicting the Tanner-Whitehouse score from the outlines as labelled by a human expert.

Train size: 400

Test size: 154

Missing value: No

Number of classses: 3

Time series length: 80

Data donated by Luke Davis and Anthony Bagnall (see [1], [2], [3], [4]).

[1] Davis, Luke M. Predictive modelling of bone ageing. Diss. University of East Anglia, 2013.

[2] https://www.uea.ac.uk/computing/machine-learning/predictive-modelling-of-bone-ageing

[3] Cao, Fei, et al. "Digital hand atlas and web-based bone age assessment: system design and implementation." Computerized medical imaging and graphics 24.5 (2000): 297-307.

[4] http://www.timeseriesclassification.com/dataset.php