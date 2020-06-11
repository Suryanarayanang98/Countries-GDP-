# Countries GDP Prediction
### Project Goal
The Goal of the project is to understand this dataset, geting insights from it and finally performing regression task on it to predict GDP of a country based on parameters like population, area, region, net migration etc.
### Data Source
This dataset is from kaggle named 'Countries of the world' uploaded by Fernando Lasso. The link to the dataset is :
https://www.kaggle.com/fernandol/countries-of-the-world

![output](https://user-images.githubusercontent.com/64247956/84409420-083ce080-ac2b-11ea-8c45-833d0a61de8e.png)

### Conclusion
In this project, we used countries_of_the_world dataset to build a <b>GDP</b> predictor. 5 different learning regressors (Linear Regression,SGD, SVM, Random Forest, and XGBoost) were tested, and we have acheived the best prediction performance using XGBoost on an average from the 7 Fold cross- validation, followed by Linear Regression, and then Random Forest , while SVM acheived the worst performance of the 5.

The best prediction performance was acheived using <b>XGBoost regressor</b>, using all features in the dataset, and resulted in the following metrics:
- Mean Absolute Error  <b> (MAE)</b> :0.3572660773680769
- Root mean Squared Error  <b>(RMSE)</b> :0.47540445296842687
- R-squared Score  <b>(R2_score)</b> :0.8332127481814264
