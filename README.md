# **Unit 4 Homeowork: Pandas**
### *This is a read me file for homework 4*
---
## Quantitative Analysis:
We first read the 3 files provided and combine them into a dataframe called *combined_df*. After sorting and cleaning the dataframe we plot the combined dataframe and it appears that **TIGER GLOBAL MANAGEMENT LLC** may have the most variablity. 

However, after plotting the box plot of each peortfolio we can see that **TIGER GLOBAL MANAGEMENT LLC** has the farthest outliers but isnt neccesaryily the most risky portfolio. The caluculation of the standard deviation of the combined dataframe shows that **BERKSHIRE HATHAWAY INC** is actually the most risky portfolio since it has the largest standard deviation. The order of the most risky to least risky portfolio goes as follows:

>`BERKSHIRE HATHAWAY INC; TIGER GLOBAL MANAGEMENT LLC; S&P 500;
Algo 2; SOROS FUND MANAGEMENT LLC; Algo 1; PAULSON & CO.INC.`

The Sharpe ratios of the portfolios provided show that 4 of the 7 portfolios perform well. The PAULSON & CO.INC. portfolio is the most simmilar portfolio to the S&P 500 portfolio; but both of these portfolios perform the worst among all the portfolios.

## CCustom Portfolio:
We first clean and combine the data from the three protfolios that were provided: GOOG, AAPL, COST. My custom portfolio was crated using ewual weights of 1/3 from each of the given stock data. The risk analysis of the custom portfolio that we crated showed that all the portfolios have a negative sharpe ratio. However the protfolio that performs the worst in this custom portfolio is the Costco portfolio.