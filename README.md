# Propensity to Fund for Soofi Money Card

Using LightGBM:

1. Identify whether a user is willing to fund in 3D since the user opens the sofi money account
2. On a daily basis, ranking each new registered users based on the predicted willingness
3. Based on the provided first fund amount in the mobile app, predicting whether a user will fund more than $100 for the first time
4. Tuning the parameter by using grid search and early stopping
5. Analyze the feature importance that would contributes to funding in 3 days

## Reference
LightGBM: https://lightgbm.readthedocs.io/en/latest/

Learning to Rank with LightGBM: https://medium.com/@tacucumides/learning-to-rank-with-lightgbm-code-example-in-python-843bd7b44574
