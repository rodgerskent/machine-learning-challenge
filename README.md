# machine-learning-challenge
## Exoplanet Identification 
Examined data collected from the NASA Keplar telescope program. Utilized NASA raw data and individual exoplanet determinations to build two predictive models. These two models take the raw data and predict confirmed or false positive status of a candidate planet:
* []()Imported and pre-processed the NASA data for model use
* []()Narrowed the dataset to key features for predictive modelling
* []()Split the dataset into both a training and testing set for model validation
* []()Scaled the feature data to ensure appropriate weighting and consideration
* []()Encoded the outcome data which effectively converts a text designation (Confirmed, False Positive, Candidate) into a numerical value for valid predictive modelling 
* []()Built, fit and tested a multi-variate regression model.
* []()Built, fit and tested a K nearest neighbor (KNN) model
* []()Hyper tuned each model using the GridSearchCV methodology


## The Jupyter Notebooks and related saved models are here:
The project git hub site: [https://rodgerskent.github.io/qualityDining-dashboard]

## Key Insights
The following key insights were brought to life in the assessment.
* []()The KNN model outperformed the multi-variate regression model.
* []()The KNN model is 83.0% accurate prior to hyper tuning and can be improved to 87.8% accuracy with the parameters set at {'C': 50, 'gamma': 0.0001}
* []()The multi-variate linear regression model is 66.0% accurate prior to hyper tuning and can be improved to 74.0% with the parameters set at {'C': 50, 'gamma': 0.0001}
* []()I am still seeking to run recursive feature elimination   

## Reference Items & Data source
The NASA website with the data and refence material is located here: [https//data.colorado.gov/Health/Restaurant-Inspections-in-Tri-County-Colorado/869n-zj3f]
