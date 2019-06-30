# ToeSegmentation2

The *ToeSegmentation* data were derived from the CMU Graphics Lab Motion Capture Database (see [1]). 

Motions in the database containing the keyword walk are classified by their motion descriptions into two categories. The first is the normal walk, with only walk in the motion descriptions. The other is the abnormal walk, with the motion descriptions containing: hobble walk, walk wounded leg, walk on toes bent forward,hurt leg walk, drag bad leg walk, or hurt stomach walk. In the abnormal walks, the actors were pretending to have difficulty walking normally. 

*ToeSegmentation1* is the x-axis; *ToeSegmentation2* is the y-axis. The data were used in [2]. For the archive, data have been length-normalised by truncating to the length of the shortest time series among all.

Train size: 36

Test size: 130

Missing value: No

Number of classses: 2

Time series length: 343

Data donated by Lexiang Ye and Eamonn Keogh (see [1], [2], [3]).

[1] http://mocap.cs.cmu.edu/  

[2] Ye, Lexiang, and Eamonn Keogh. "Time series shapelets: a novel technique that allows accurate, interpretable and fast classification." Data mining and knowledge discovery 22.1-2 (2011): 149-182.

[2] http://www.timeseriesclassification.com/description.php?Dataset=ToeSegmentation1