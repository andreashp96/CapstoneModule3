# ABSTRACT

In response to the overwhelming demand for apartments in Daegu, South Korea, the project addresses challenges faced by real estate agencies in setting competitive prices. With 57.4% of settlements being apartments and approximately 240,000 new units constructed, the need for an accurate pricing model is evident. 
The goal is to create a regression model that predicts apartment prices based on various specifications, enhancing customer satisfaction and maximizing agency profits.

The analytic approach involves dataset analysis to identify key features influencing property prices. The models considered for evaluation include k-NN Regressor, Decision Tree Regressor, Support Vector Regression, Linear, Ridge, and Lasso Regression, as well as Random Forest and XGBoost Regressor models. 
Evaluation metrics encompass RMSE, MAE, and MAPE, with a focus on minimizing errors to enhance model accuracy.

After benchmarking, the top three models are XGBoost Regressor, k-NN Regressor, and Random Forest Regressor. Hyperparameter tuning reveals XGBoost Regressor as the optimal model, achieving a MAPE of 18.4%. Key influential features include Hallway Type, Year Built, and Size (sqf). Recommendations for model improvement include advanced feature selection, utilizing Grid Search for hyperparameter tuning, establishing a user feedback loop, providing model understanding training for real estate professionals, and expanding the model for application in other cities or regions. The regression model, coupled with these recommendations, offers a comprehensive solution for determining optimal apartment prices in Daegu's dynamic real estate market.
