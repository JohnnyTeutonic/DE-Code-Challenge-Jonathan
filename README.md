# Data-Engineering-Challenge
Take home assignment based on Demyst Python libraries and building a model

## Structure
Final models selected are found in the Models/ directory. There is a Voting Classifier from the Scikit-Learn library named 'voting_classifier', as well as a hyperparameter-tuned Random Forest named 'tuned_forest' present in this directory
Final DataFrame used is found in Data/ directory - it is named 'final_enriched_results.csv'

## Requirements
Python 3.7 was used and every library was installed using pip.
There is a requirements file present that can be used to download every external library i.e.
```pip3 install -r requirements.txt```
Models can be re-loaded using 'joblib's *dump* function

## Extra Libraries

- rgf-python (found on PyPI using pip) - this uses Regularised Greedy Forests c.f. https://github.com/RGF-team/rgf/tree/master/python-package
- imblearn (found on PyPi using pip) - this is a 'sklearn-contrib' library specialised for imbalanced data sets. This was used to over-sample the minority class using a technique known as SMOTE c.f. https://github.com/scikit-learn-contrib/imbalanced-learn/tree/master/imblearn
- mlxtend (found on PyPi using pip) - this library contains an easy-to-use out-of-the-box Stacking Classifier that can be used for stacking predictions from one classifier onto another i.e. using the outputs from one classifier cas a feature for another classifier c.f. https://github.com/rasbt/mlxtend
- keras (found on PyPi using pip) - this was used to build a basic neural network (of the MLP architecture) as a classifier.
- xgboost (found on PyPi using pip) - well-known boosting library used both to create a classification model as well as for its in-built feature importance functionality