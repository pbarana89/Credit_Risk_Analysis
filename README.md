# Credit_Risk_Analysis
The goal of this project was to try and use different tools to create a model that used Machine Learning that would allow us to look at credit card risk and see if we could make predictions to determine who might be more likely to default on their credit cards. Using information received from LendingClub, we used the RandomOverSampler and SMOTE algorithms to oversample the data, used ClusterCentroids to undersample, and used Smoteenn to use a combinational approach. Finally, we used two Machine Learning models, BalancedRandomForestClassifier and EasyEnsembleClassifier, to try and predict our credit risks.

## Analysis of the Report
![](https://github.com/pbarana89/Credit_Risk_Analysis/blob/main/Images/Oversampled_Model.PNG)
- The oversampled model had a balanced accuracy score of 64.13%. Precision for high credit risk was 1% and low risk was 100%. Recall was 60% for high credit risk and 68% for low credit risk.

![](https://github.com/pbarana89/Credit_Risk_Analysis/blob/main/Images/SMOTE_Oversampled_Model.PNG)
- The oversampled SMOTE model had a balanced accuracy score of 63.74%. Precision for high credit risk was 1% and low risk was 100%. Recall was 60% for high credit risk and 68% for low credit risk.

![](https://github.com/pbarana89/Credit_Risk_Analysis/blob/main/Images/Undersampled_Model.PNG)
- The undersampled model had a balanced accuracy score of 59.55%. Precision for high credit risk was 1% and low risk was 100%. Recall was 62% for high credit risk and 57% for low credit risk.

![](https://github.com/pbarana89/Credit_Risk_Analysis/blob/main/Images/Combo_Model.PNG)
- The combo model had a balanced accuracy score of 59.55%. Precision for high credit risk was 1% and low risk was 100%. Recall was 60% for high credit risk and 43% for low credit risk.

![](https://github.com/pbarana89/Credit_Risk_Analysis/blob/main/Images/BRF_Model.PNG)
- The Balanced Random Forest algorithm had a balanced accuracy score of 76.72%. Precision for high credit risk was 2% and low risk was 100%. Recall was 67% for high credit risk and 87% for low credit risk.

![](https://github.com/pbarana89/Credit_Risk_Analysis/blob/main/Images/EEC_Model.PNG)

- The Ensemble AdaBoost algorithm had a balanced accuracy score of 86.30%. Precision for high credit risk was 4% and low risk was 100%. Recall was 83% for high credit risk and 90% for low credit risk.

### Summary of the Report
- The models provided some interesting information that would need further clarification before deciding if they could be used to determine if they would be worth using to determine credit risk. The sheer precision on the models for low credit risk is great, but being so near perfect is naturally worth looking to make sure everything is correct. 

- The most accurate model was the Ensemble AdaBoost and that could be used as it had an accuracy score of 86%, however I'd want further information on how much of a margin lenders are getting on loans, because if margins are very small, a 14% error rate, could not be accurate enough, but if they are very high margins, this would be the model to use.    