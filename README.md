# outliers
Using IQR methods

To find outliers using the Interquartile Range (IQR) method, you can follow these steps:

Calculate the IQR: The IQR is the range between the first quartile (Q1) and the third quartile (Q3) of the data. It represents the middle 50% of the data.

IQR = Q3 - Q1

Define the outlier boundaries: Multiply the IQR by a constant factor (typically 1.5) to determine the lower and upper boundaries for outliers.

Lower Bound = Q1 - 1.5 * IQR
Upper Bound = Q3 + 1.5 * IQR

Identify outliers: Any data point below the lower bound or above the upper bound is considered an outlier.
