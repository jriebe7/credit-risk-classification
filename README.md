# Credit Risk Analysis Report

The purpose of this analysis was to look at credit lending data and determine if a logistic regression model would be a good option to use in determining creditworthiness of borrowers

## For healthy loan predictions the model produced the following:
  -Precision: 100%
  -Recall: 99%

## For high-risk loan predictions the model produced the following:
  -Precision: 84%
  -Recall:  94%

## Overall accuracy score: 92%

# Summary

When determining risk, lenders are primarily concerned with the likelihood someone is going to default on their loan, so even though the precision for healthy loans was 100%, the precicision for high-risk loans was only 84%, so this may not be the best model to use in making this decision.  This would ultimately need to come from the business on whether or not they are comfortable with accepting this level of precision or not, but personally I would not recommend it because it would likely be wrong 1 out of every 5 times or so.
