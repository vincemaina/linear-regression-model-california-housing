# About the dataset

The california housing dataset is famous, and often used in beginner machine learning projects to practise linear regression.

It is a great dataset as it strikes a good balance between being managable for a beginner, but also requiring some preprocessing and cleaning of the data.

## First things first...

In order to achieve the best results, we must start by studying the dataset to ensure we fully understand what it represents, how it relates to the real-world entities it is based on, how it was obtained.

### Context

This is a dataset obtained from the StatLib repository. Here is the included description:

> We collected information on the variables using all the block groups in California from the 1990 Cens us. In this sample a block group on average includes 1425.5 individuals living in a geographically co mpact area. Naturally, the geographical area included varies inversely with the population density. W e computed distances among the centroids of each block group as measured in latitude and longitude. W e excluded all the block groups reporting zero entries for the independent and dependent variables. T he final data contained 20,640 observations on 9 variables. The dependent variable is ln(median house value).

### Variables

1. **Longitude**: A measure of how far west a block is; a higher value is farther west

2. **Latitude**: A measure of how far north a block is; a higher value is farther north

3. **Housing median age**: Median age of a house within the block; a lower number is a newer building

4. **Total rooms**: Total number of rooms within a block

5. **Total bedrooms**: Total number of bedrooms within a block

6. **Population**: Total number of people residing within a block

7. **Households**: Total number of households, a group of people residing within a home unit, for a block

8. **Median income**: Median income for households within a block of houses (measured in tens of thousands of US Dollars)

9. **Median house value**: Median house value for households within a block (measured in US Dollars)

10. **Ocean proximity**: Location of the house w.r.t ocean/sea