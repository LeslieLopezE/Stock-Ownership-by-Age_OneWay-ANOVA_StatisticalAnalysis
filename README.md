# Stock-Ownership-by-Age_OneWay-ANOVA_Analysis

In the last decade stockbrokers have drastically changed the way they do business.
Internet trading has become quite common and online trades can cost as little as $7.
It is now easier and cheaper to invest in the stock market than ever before.

What are the effects of these changes? To help answer this question,
a financial analyst randomly sampled 366 American households and asked each to report
the age of the head of the household and the proportion of their financial assets that
are invested in the stock market. The age categories are:

Young (under 35)

Early middle age (35 to 40)

Late middle age (50 to 65)

Senior (over 65)


The analyst was particularly interested in determining whether the ownership of stocks
varied by age. Do these data allow the analyst to determine that there are differences
in stock ownership between the four age groups? 

## Hypothesis for Analysis of Variance - ANOVA: 

Null hypothesis: There is no difference in the mean of Stock Investments by Age Group: H0 : 𝜇1= 𝜇2= 𝜇3= 𝜇4

Alternative hypothesis: At least one of the age groups differs in their mean of Stock Investments: H1: Not all the means are equal

## Findings and conclusions

1. The P value is less than 0.05. Thus we reject the Null Hypothesis -> The Ownership of Stock Investments varied by Age group

2. The fit of the model is not very good -> R Square = 0.0226

3. From the scatter plot and histogram of residuals, we conclude that the residuals are normally distributed.

4.  From the Levene's test results, we conclude that because the P value is higher than 0.05, we fail to reject the hypothesis of equal variance 
(homogeneity of variance). If he had obtained a value less than 0,05, we would have had to try alternative methods to analyse the data, which is not the case

5. From the analysis of box plots of stock ownership by age, we conclude that indeed, stock investment is lower for the young group and is higher for the older groups stayign at comparable levels.


