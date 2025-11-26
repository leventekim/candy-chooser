# candy-chooser
The aim of this project to recommend a brand-new product based on structured market research data.

A prerequisite to run the scripts is the data, which is accessible in the following repository: https://github.com/fivethirtyeight/data/tree/master/candy-power-ranking

The scripts should be run in the following order:

1/ 0_eda.ipynb: exploratory data analysis and graphs

2/ 1_data_preparation: transforming the dependent variable to the range [0,1]

3/ 2_fit_model.ipynb: fits a logistic and a linear regression model