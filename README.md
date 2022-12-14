# American-Express-Fraud-Detection

The target binary variable is calculated by observing 18 months performance window after the latest credit card statement, and if the customer does not pay due amount in 120 days after their latest statement date it is considered a default event.  The dataset contains aggregated profile features for each customer at each statement date. 

Features are anonymized and normalized, and fall into the following general categories:  
  - D_* = Delinquency variables 
  - S_* = Spend variables 
  - P_* = Payment variables 
  - B_* = Balance variables 
  - R_* = Risk variables Task is to predict, for each customer_ID, the probability of a future payment default (target = 1).  

Note: that the negative class has been subsampled for this dataset at 5%, and thus receives a 20x weighting in the scoring metric.

## Link to comp:
https://www.kaggle.com/competitions/amex-default-prediction
