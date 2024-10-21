# Predicting survival of hear failure patients using 11 clinical variables 

## Environment setup  
Please install `numpy`, `pandas`, `sklearn`, `seaborn`, `scipy`, `matplotlib`. You can use `pip install` or conda. 

## Data preprocessing and exploratory analysis 
The `preprocessing.ipynb` notebook contains the scripts used for data preprocessing and exploratory analysis. The notebook assumes the original CSV file provided by the instructor to be placed under the current working directory. 

## Modeling 
See `modeling.ipynb` for all models used in this assignment to predict survival, including logistic regression models, support vector machine models, cox proportional hazards models, and a multi-layer percepton model. 

## Analysis 
In this assignment, the cox model with ridge regularization was further explored. See `cox_ridge_analysis.ipynb` for this analysis. 