# credit_risk

## Project desctiption 

We built and evaluate several machine learning models to assess credit risk. We used imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. and make a recommendation on whether they should be used to predict credit risk.

## Analysis of the results (please see the jupiter notebook for more detailed analysis)

#### RandomOverSampler: 

This model produce a high precision score ( 0.01 ) but the recall score is on the lower end and indicates the model is not accurate enough to predict high risk borrowers.

#### SMOTE
       
This model produced a similar degree of accuracy as random over sampling  and is still not precise enogh to predict credit worthiness to acceptable degree.

#### Cluster Centroids


This is the worst performing model of all studies performed likely due to fewer observations caused by under sampling. Cluster centroids should not be used to predict credit worthiness

#### SMOTEENN
              
The recall score is the highest of all models thus far yet still not accurate enough.


#### Balanced Random Forest Classifier

The high risk recall of .67 indicated the model is lacking in accuracy.

####  Easy Ensemble AdaBoost Classifier

The combination of multiple learning models improves the accuracy score dramatically making this the best performing model in the study.

### Recommendations
We recommend using the easy ensemble classifier to evaluate credit risk. 
