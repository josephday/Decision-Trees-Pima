# Decision-Trees-Pima
An exercise in generating decision trees for means of determining likelihood that a member of the Pima Indian has diabetes (binary, categorical variable) from pre-existing conditions (nodes)

Modules required: csv, math, numpy, pandas, random, sys

decision_tree.py -- contains code for cleaning data provided from pima-indians-diabetes.csv and outputs the cleaned testing.csv and training.csv, which can also be found in data

transform.py -- uses training.csv for construction of most efficient decision tree adhering to project boundaries, which required specific gain ratios / split-info
