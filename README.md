# Predicting Churn
## Goals:
- Build a model able to predict customers at risk of churning
- Identify the key drivers of churn
- Flag customers at high risk of churning 

## Approach:
### Build a model able to predict customers at risk of churning:
#### I built an optimized three models:
1) A random forest classifier
2) A support vector classifier
3) An SVC and random forest emsemble
#### Using recall and prediction as performance metrics, I found that SVC outperformed random forest and the ensemble method.

### Identify the key drivers of churn
#### I used feature drop-out to look for the most important predictors of churn for these customers and then plotted the top 15 features. Refer to the analysis notebook to look at the top 15 predictors.

### Flag customers at high risk of churning 
#### Using the probability for customers to churning and the unique customer ID, I flagg the customers with a probability of churning of more than 70%. This customers can then be targetted to try to prevent them from leaving the company.
