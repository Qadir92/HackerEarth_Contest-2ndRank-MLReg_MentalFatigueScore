1. Loading the data into colab notebook.
2. Dropping rows having missing values in target and independent variables.
3. Dropping columns 'Date of Joining','Age','Tenure','Vacations taken','Company Type' due to correlation.
4. Training the models and comparing the RMSE and R2 for LinearRegression, Lars, Lasso, Ridge, BayesianRidge, 
KernelRidge, ElasticNet, DecisionTreeRegressor, RandomForestRegressor, SVR, KNeighborsRegressor, 
PassiveAggressiveRegressor, SGDRegressor.
5. Hypertuning top performing models RandomForestRegressor, SVR, KNN, KernelRidge, SGDRegressor, Ridge, 
BayesianRidge, Decision Trees Reg.
6. Training Boosting models and comparing RMSE and R2 for LGBMRegressor, GradientBoostingRegressor, XGBRegressor, 
CatBoostRegressor, ExtraTreesRegressor, AdaBoostRegressor.
7. Hypertuning top performing boosting models LGBMRegressor, GradientBoostingRegressor, XGBRegressor, CatBoostRegressor.
8. Comparing performance of all tuned models.
9. Applying Stacking Regressor on CatBoostRegressor, LGBMRegressor, KernelRidge, SVR, GradientBoostingRegressor, 
XGBRegressor, RandomForestRegressor, KNeighborsRegressor and final estimator as SGD Regressor.
10. Predictions using stacked reg model.