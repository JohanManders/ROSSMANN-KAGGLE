# Rossmann Store Sales
With this script you could have achieved the 13th place in the Rossmann Store Sales competition on Kaggle. No external data is used.

The script uses [XGBoost](https://github.com/dmlc/xgboost), [Pandas](https://github.com/pydata/pandas) and a bit [Scikit-learn](https://github.com/scikit-learn/scikit-learn).

If you would add Google Trends daily searches for 'Rossmann', State data and Weather data per State, you can get to the 7th place with just one model. But because that model would be useless for real world usage, that data is kept out of this model.

This script uses about 8Gb of RAM and takes some hour to run.
