# Concrete_Project
Developing a predictive model for the compressive strength of concrete given a set of 8 parameters. 
## Data
The public dataset used was gotten from kaggle and can be downloaded here https://www.kaggle.com/maajdl/yeh-concret-data .The link also contains a description of the dataset
## Analysis
The data analysis was carried out using the following python libraries;
<ul>
  <li>Pandas</li>
  <li>Numpy</li>
  <li>Matplotlib</>
  <li>Seaborn</>
  </ul>
 
 ## Model
 10 different models were first constructed using different scikit learn regression algorithms and evaluated on a singluar metric, which is their R2 scores. The models that showed the most promise are;
 <ul>
  <li>XGboostRegressor</li>
  <li>RandomForestRegressor</li>
  <li>GradientBoostingRegressor</li>
</ul>

## Hyperparameter tuning
Grid_searchCV, RandomsearchCV and a bit of intuitiveness were used to get the best hyperparameters for the models constructed with XGBoost,Randomforest and GradientBoost. The best performing model was constructed with the GradientBoosting regressor, with an R2score of 0.95
