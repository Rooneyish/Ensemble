# Ensemble
# Homogeneous Ensembling -> Base Estimator is Same
## Bagging = Bootstapping + Aggregration
> Eg:  Random Forest	
  - Row Sampling with or without replacement
  - Column Sampling with or without replacement
  - Row + Column Sampling with or without replacement

## Boosting
> Eg:
> - AdaBoost
> - Gradient Boost
> - XGBoost
> - LightGBM
> - CatBrust


# Heterogeneous Ensemble Learning -> Cause different models are used (Base Estimator is Different)
## Stacking & Blending
> Eg:
> - K-Fold Stacking 
> - Multi Layer Stacking

## Voting 
| Title | Definition |
| ----------- | ----------- |
| Classification | Ensemble of multiple ML models where the final results is the majority voted result by the models. |
| Regression | Gives the average of results from the ML models. |
 
### Types of Voting
| Type | Rule | Definition |
| ----------- | ----------- | ----------- |
| Hard Voting | Majority Rule | Majority is based on the weightage on the model prediction.|
| Soft Voting | Weighted Average | Majortiy is based on the average of the weightage on the model prediction. |
