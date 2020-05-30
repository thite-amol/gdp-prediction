# GDP-prediction

#### Data Source
We have 'Countries of The World' data set 
(from kaggle: Fernando Lasso: https://www.kaggle.com/fernandol/countries-of-the-world).

#### Data Description
This dataset have each country as a data point (227 countries in total), and for each, we have 20 columns, each column represents a different aspect or measure of the specific country. 

#### Project Goal
The goal of the project is to understand this dataset, get some insights from it, and finally to train a model that can predict GDP per capita for each country. 

![](/images/gdp-per-capita.png)
![](/images/regional-analysis.png)

#### Conclusion 
3 different learning regressor (Linear Regression, SVM and Random Forest) were tested, and we have achieved the best prediction performance using Random Forest, followed Linear Regression, while SVM achieved the worst performance of the three.

The best prediction performance was achieved with a Random Forest regressor, using all features in the dataset, and resulted in the following metrics:

* Mean Absolute Error (MAE): 2201.6739130434785
* Root mean squared error (RMSE): 2961.5842668351033
* R-squared Score (R2_Score): 0.8938497692158326

(gdp_per_capita values in the dataset ranges from 500 to 55100 USD).

![](/images/random-forest.png)
