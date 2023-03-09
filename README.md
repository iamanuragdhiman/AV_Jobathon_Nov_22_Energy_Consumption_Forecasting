# AV_Jobathon_Nov_22_Energy_Consumption_Forecasting
Analytics Vidhya Jobathon for November 2022:
* Create a time series forecasting model to forecast the energy consumption in the state for next 3 years.
* Evaluation metric for the problem is RMSE.

## Approach:
* This data is heavy and it contains 95K observations, and it would be difficult to process such huge data with ML algorithms.
* I have used Fb-Prophet for this forecasting problem.
* We have to predict for next 3 years, so I have kept 3 years of training data as validation set to tune the hyperparameters.

## Results:
* Final Rank on Private leaderboard : **110**/6388
* RMSE on test data for private leaderboard : 478.9774951111

## Dataset:
![image](https://user-images.githubusercontent.com/96112553/224008243-8de833d4-edaa-41b2-a0e3-67e7fe143443.png)

## Predictions on Validation set before hyperparameter tuning:
![image](https://user-images.githubusercontent.com/96112553/224008362-b183dfa6-d899-4502-a562-1e703349450c.png)
![image](https://user-images.githubusercontent.com/96112553/224008389-24a30cf3-b6b0-4bb6-b38e-f597b4057048.png)

## Prediction on Validation set after hyperparameter tuning:
![image](https://user-images.githubusercontent.com/96112553/224008683-c64a6206-fc05-4d40-8e10-d1b6c9453ed5.png)

## Prediction on Final Test Set:
![image](https://user-images.githubusercontent.com/96112553/224014566-4edf3a04-b92b-4124-953c-208c315e5dc1.png)


