# Outliers-Detection
This notebook contains the implementations of Outlier or anomaly detection with multivariate normal distribution and interquartile range method


## keypoints
1) The reason I compared these 2 methods was that most of the time the first method and another method called z-score method were used to remove outliers as preprocessing in regression or classification problems.

2) As z-score method and interquartile range methods doesn't consider the relationship between multiple variables when detecting outliers, some outliers will be very hard to detect with these methods when multiple variables are involved

3) wheras, Multivariate normal distribution uses covariance matrix to find how a variable changes with respect to other and hence is able to detec outliers

4) z-score method and interquartile method can also detect outliers when multiple variables are involved but, the datapoint of the outlier must far away from the entire range of data in the dataset but it will not be able to detect outliers both the co-ordinates are not far away from the range of values of the co-ordinate of all the data in the dataset

5) I might be wrong , but the reason why z-score and interquartile range methods are used in pre-processing is that because they are easier to implement and also they can remove outliers that exist far away from the entire range of dataset which would be more than enough for machine learning models to fit
