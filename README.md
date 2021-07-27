# HackerEarth_Contest-2ndRank-MLReg_MentalFatigueScore
**Predict the mental fatigue score for employees using a regression model for a work life balance integration theme contest in Accenture by HackerEarth.**
***
![HackerEarth Leader Board Score 93.07017% Accuracy](https://github.com/Qadir92/HackerEarth_Contest-2ndRank-MLReg_MentalFatigueScore/blob/main/Leaders%20Board.jpg?raw=true)
***
### Steps in the notebook:
1. Loading the data into colab notebook. 
2. Dropping rows having missing values in target and independent variables.
3. Dropping columns 'Date of Joining', 'Age', 'Tenure', 'Vacations taken', 'Company Type' due to correlation.
4. Training the models and comparing the RMSE and R2 for
    LinearRegression, Lars, Lasso, Ridge, BayesianRidge, KernelRidge,
    ElasticNet, DecisionTreeRegressor, RandomForestRegressor, SVR,
    KNeighborsRegressor, PassiveAggressiveRegressor, SGDRegressor.
5. Hypertuning top performing models RandomForestRegressor, SVR, KNN, KernelRidge, SGDRegressor, Ridge, BayesianRidge, Decision Trees Reg.
6. Training Boosting models and comparing RMSE and R2 for
    LGBMRegressor, GradientBoostingRegressor, XGBRegressor,
    CatBoostRegressor, ExtraTreesRegressor, AdaBoostRegressor.
7. Hypertuning top performing boosting models LGBMRegressor,
    GradientBoostingRegressor, XGBRegressor, CatBoostRegressor.
    
  7.  Comparing performance of all tuned models.
    
 8.   Applying Stacking Regressor on CatBoostRegressor, LGBMRegressor, KernelRidge, SVR, GradientBoostingRegressor, XGBRegressor, RandomForestRegressor, KNeighborsRegressor and final estimator as SGD Regressor.
    
 9.   Predictions using stacked reg model.
***
To check out my notebook, please click [here](https://github.com/Qadir92/HackerEarth_Contest-2ndRank-MLReg_MentalFatigueScore/blob/main/Work_Life_Integration.ipynb)
