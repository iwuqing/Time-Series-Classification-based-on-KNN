# GunPoint dataset

This dataset is a remake of the famous GunPoint dataset released in 2003. We strive to mimic in every aspect the recording of the original GunPoint. The actors include one male and one female. They are the same actors who created the original GunPoint.

We record two scenarios, Gun and Point (also known as Gun and NoGun). In each scenario, the actors aim at a eye-level target. The difference between Gun and Point is that for the Gun scenario, the actors hold a gun, and in the Point scenario, the actors point with just their fingers. A complete Gun action involves the actor moves hand from an initial rest position, points the gun at target, puts gun back to waist holster and then brings free hand to the initial rest position. Each complete action conforms to a five-second cycle. With 30fps, this translates into 150 frames per action. We extract the centroid of the hand from each frame and use its x-axis coordinate to form a time series.

We refer to the old GunPoint as GunPoint 2003 and the new GunPoint as Gunpoint 2018. We merged GunPoint 2003 and GunPoint 2018 to make three datasets.

Let us denote:
- G: Gun
- P: Point
- M: Male
- F: Female
- 03: The year 2003
- 18: The year 2018

## GunPointAgeSpan 

The task is to classify Gun and Point. There are 4 flavors of each class.
- Class 1: Gun (FG03, MG03, FG18, MG18)
- Class 2: Point (FP03, MP03, FP18, MP18)

Train size: 135

Test size: 316

Number of classes: 2

Missing value: No

Time series length: 150

## GunPointMaleVersusFemale

The task is to classify Male and Female. There are 4 flavors of each class.
- Class 1: Female (FG03, FP03, FG18, FP18)
- Class 2: Male (MG03, MP03, MG18, MP18)

Train size: 135

Test size: 316

Number of classes: 2

Missing value: No

Time series length: 150

## GunPointOldVersusYoung

The task is to classify the older and younger version of the actors. There are 4 flavors of each class.
- Class 1: Young (FG03, MG03, FP03, MP03)
- Class 2: Old (FG18, MG18, FP18, MP18)

Train size: 135

Test size: 316

Number of classes: 2

Missing value: No

Time series length: 150

There is nothing to infer from the order of examples in the train and test set.

Data created by Ann Ratanamahatana and Eamonn Keogh. Data edited by Hoang Anh Dau.

