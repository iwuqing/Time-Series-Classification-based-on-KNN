# GunPoint

This dataset involves one female actor and one male actor making a motion with their hand. The two classes are: Gun-Draw and Point. For Gun-Draw, the actors have their hands by their sides. They draw a replicate gun from a hip-mounted holster, point it at a target for approximately one second, then return the gun to the holster, and their hands to their sides. For Point the actors have their gun by their sides. They point with their index fingers to a target for approximately one second, and then return their hands to their sides. The motion streams are from tracking the centroid of the actor's right hands in both x- and y-axes, which appear to be highly correlated. The data in the archive are just the x-axis for simplicity. 

Train size: 50

Test size: 150

Missing value: No

Number of classses: 2

Time series length: 150

Data donated by Ann Ratanamahatana and Eamonn Keogh (see [1], [2]).

[1] Ratanamahatana, Chotirat Ann, and Eamonn Keogh. "Making time-series classification more accurate using learned constraints." Proceedings of the 2004 SIAM International Conference on Data Mining. Society for Industrial and Applied Mathematics, 2004.

[2] http://www.timeseriesclassification.com/description.php?Dataset=GunPoint