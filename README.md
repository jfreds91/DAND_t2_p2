# White Wine EDA in R
## DAND_t2_p2
Jesse Fredrickson

## Motivation
The purpose of this project is to perform and document exploratory data analysis (EDA) on a dataset concerning white wine, with the goal of identifying relationships between feature variables. I will by trying to examine the correlations between features and feature interactions that contribute to a wine's quality

## Files
**wineQualityWhites.csv:** this is the raw dataset

**wineQuality.Rmd:** this is the R markdown file in which I perform my analysis and show visualizations

**wineQuality.html:** this is an html representation of the R markdown file

## Results / Instructions
In order to recreate my analysis, you will need to have R and Rstudio installed. Running the first few cells will automatically download and install extra libraries that are necessary for the analysis.

This was a challenging dataset, because as was made clear by the scatter matrix, there are very few ostensible correlations between individual variables. Through some pseudo-random experimentation I was able to flesh out some interesting interactions, particularly relating to density, alcohol, residual sugar, total and free sulfur dioxide, and quality, but I was not able to tie them all together in an effective model. What was surprising to me was that of all variables, it seems that alcohol content by itself was easily the best predictor of quality. It would have been useful to have more info on wines beyond chemical composition, such as year, vineyard, price etc. Without more info to go on, my best advice when wine shopping is just to buy the strong stuff. According to this dataset, if you aim for >= 12.8% ABV, you are more likely than not to get above average quality wine!