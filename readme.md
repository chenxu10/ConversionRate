# PREDICTIVE MODELING ON CUSTOMER CONVERSION RATE

## THE PROBLEM

### WHAT ARE THE KEY FACTORS FOR CONVERSION RATE?

Optimizing conversion rate is essential to a facilitate a product's rapid growth. In this project, I used anonymous data from an american e-commerce website to figure out what are the good performing segments for a better conversion rate.

## THE SOLUTION

I used seaborn to do EDA on the behavioral and demographic variables and build a penalized logistic regression model and a random forest model to predict the conversion rate. I also checked the rank of feature importance to provide actionable insight to the marketing team.

## CONCLUSION

+ From both the penalized logistic regression model and random forest model, we can find that new_user and country might be the most two important factors contributing to the conversion rate.
+ Source is the most irrelevant variables.
+ The conversion rate from China is very low, this is a potentially huge market and our company should really work on this.
+ Counter intitutively, users coming from ads and seo tend to have a higher conversion rate than users coming directly.
+ German users have a high conversion rate.
+ The conversion rate has a positive correlation between the pages user viewed. We should remind users who have viewed a lot of our pages to buy things.