# machine-learning-challenge
## Exoplanet Identification 
Examined data collected from the NASA Keplar telescope program. Utilized NASA raw data and individual exoplanet determinations to build two predictive models. These two models take the raw data and predict confirmed or false positive status of a candidate planet:
* []()Imported and pre-processed the NASA data for model use
* []()Narrowed the dataset to key features for predictive modelling
* []()Split the dataset into both a training and testing set for model validation
* []()Scaled the feature data to ensure appropriate weighting and consideration
* []()Encoded the outcome data converting text into a numerical value for valid predictive modelling 
* []()Built, fit and tested an SVC multi-variate linear regression model
* []()Built, fit and tested a K nearest neighbor (KNN) model
* []()Hyper tuned each model using the GridSearchCV methodology

## The Jupyter Notebooks and related saved models are here:
The project git hub site: [https://github.com/rodgerskent/machine-learning-challenge/edit/main]

## Key Insights
The following key insights were brought to life in the assessment.
* []()The SVC model with hyper tuning outperformed the KNN model.
* []()The SVC model scores 87.8% when tuned at {'C': 50, 'gamma': 0.0001}
* []()The KNN model scores 81.3% when tuned at {'algorithm': 'ball_tree', 'leaf_size': 15}
* []()Recursive feature elimination was run and presents an opportunity to make the models more efficient.   

## Reference Items & Data source
The NASA website with the data and refence material is located here: [https// www.kaggle.com/nasa/kepler-exoplanet-search-results]

