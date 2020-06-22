# Credit_Risk

## Analysis

### Logistic Regression Classifier

Both Naive oversampleing and SMOTE oversampling had relatively similar accurcy scores of 65% and 66%. The precision and recall scores
of both models are still very similar with an extremely high false negative(low risk) and an extremely low true positive(determining
high risk). It has a 63% chance of determining a true negative. In this scenario of determining whether someone has high or low credit
risk, the model was able to determine 63% of the people were truly at low risk and 69% were false positives for being at high risk 
which isnt a bad thing considering it is better to error on that side due to the fact that the company is trying to determine who to
lend money too. The undersampling had a lower accuracy result with 53% and the most noticable change was in the 40% of 
true negatives detected for individuals at low risk. This is worse in the sense that the undersampled model only determines 40% 
of the low risk individuals compared to 63%.


### Balanced Random Forest Classifier

The performance of this model out performed the previous logistic regression models(over and undersampling) significantly. The accuracy 
of this model is at 78% and was able to determine the true negatives(people at low risk) at 90%. This model also was able to safely predict the individuals that were truly at high risk with 4% precision.

### Easy Ensemble Classifier

The last model had the highest performance with a 91% accuracy and the a 90% for true negatives( people at low risk for lending at 
loans). This should be the model to be used in determining whether a company should lend money to an individual or not.

