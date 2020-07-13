# Data cleaning without domain knowledge
This article is going to throw light on, how to clean a data set with a large number of features, assuming someone not having domain expertise. For this article, our focus will be a very popular dataset "House Prices: Advanced Regression Techniques", available at Kaggle.

## Challange
If you normally ask a home buyer to describe their dream house, they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But it turns out that, these factors have much more influence on price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, the challenge is to predict the final price of each home.

This article will be divided into the following parts,

1. Importing the data sets with pandas
1. Visualizing the missing data
1. Dropping features with very high numbers of missing values
1. Filling up missing data with, column mean, mode, median
1. One-Hot-Encoding the categorical features
1. Dropping duplicate columns, if any
1. Training XG_Boost model with Grid search

Rank on kaggle after XG_boost model
![](image/image.jpg)
