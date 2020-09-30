# DataScience_RiskPrediction

My first DataScience Project

There is a file to pre-process table and combine 2 secondary table into 1
  In this case i don't really understand ti process raw data analyze the raw data to find the connection of data.
  The task to do is to find the risk but, the available data is only Id that will not pay loan in time.
  
After pre process raw data, other 3 code is the model i create to make prediction
  1. Using Number only data with Random Forest
        - without using SMOTE
        - weight Balance
        - Feature selection with Boruta
  2. Using All_feature with Random Forest
       The result is slightly better but neew more time to run
        - Without SMOTE
        - Weight Balance
        - All feature converted into numerical by using Pd.get_dummies
        - Feature selection with boruta
  3. Using numerical feature only with Gradient Boost Classifier
        - Use SMOTE to class balance
        - Without Weight Balacne
        - Boruta
  
Other code is all feature with GDC but takes very long time to feature selection. 

The result from code this is disapointing because of lack pre-processing data in raw data, and i dont really have a enough experiene with data analyst.
