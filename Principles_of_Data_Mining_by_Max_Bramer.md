## Principles of Data Mining

by Max Bremer

### Chapter 0: Introduction
* pg 6: Supervised learning (classification and numerical prediction) vs Unsupervised learning (clustering and association rules).

### Chapter 1: Data for Data Mining
* pg 13: Types of variables include Nominal (categories such as 1-wood, 2-steel, etc.), Binary, Ordinal (same as Nominal but can be arranged in meaningful order like small, medium and large), Integer (num of children for example), Interval-scaled (measured from zero-point or origin, like Celcius or Fahrenheit), Ratio-scaled (same as previous but the zero-point DOES reflect the absence of measured characteristic like 10kg is twice one of 5kg). 
* pg 14: categorical corresponding to nominal, binary and ordinal variables, continuous corresponding to integer, interval-scaled and ratio-scaled variables.
* pg 15: many kinds of errors may happen to real world data-sets like people typing in numbers incorrectly (potentially noise) or adding a characer where an integer should be (we consider these invalid values). Note: Albania example is interesting, 10% of collected data from this country which is surprisingly large which could also mean that people we're selecting their country but instead just skipped it and, since Albania is first on the list, it was automatically selected. 
* pg 18: When dealing with missing values, we can consider either deleting the rows in which have missing values or replacing them with the average value. 