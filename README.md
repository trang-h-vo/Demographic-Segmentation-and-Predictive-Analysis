# French-departments-analysis

### Project goals
##### Explanatory analysis: 
Characterize 96 French departments using data about people who live and/or work there. 
Methods used include KMeans & Agglomerative Algorithm, visualization libraries such as matplotlib, seaborn and geopandas.
##### Predictive analysis: 
Predicting the wage of French citizens.
Main models used are Random Forest Regressor and XGBRegressor.

### Credit:
This project is an extension from a group assignment at the University Paris Dauphine. Special thanks to my groupmate Zichuan LI for such a fun collaboration.

### Data
The data sets used in this notebook contain more than 20.000 French citizens with their home & job information as follows:
- `Personal info`: Age (2019), educational level & gender
- `Home info`: household type, home city, home department & geolocation
- `Work info`: wage, company size & industry
- `French social-economic data`: average salary at department level, by job level, age group & gender

### Notebooks:
You can find the complete notebooks in this repository or click the links below for a quick view: 
- <a href="https://nbviewer.jupyter.org/github/trang-h-vo/French-Departments-Analysis/blob/main/French_departments_EDA_Geospartial.ipynb"> French_Departments_EDA_Geospartial.ipynb </a>: This notebook shows the exploratory analysis on French departments, characterized by their inhabitants and workers. 
- <a href="https://nbviewer.jupyter.org/github/trang-h-vo/French-Departments-Analysis/blob/main/French_Departments_Predictive_Analysis.ipynb"> French_Departments_Predictive_Analysis.ipynb </a>: This notebook shows the data preprocessing, treating categorical variables, modeling steps using pipeline, RandomizedSearchCV and GridSearchCV. 

### Data source: 
The data sets were provided for a Machine Learning project at University Paris Dauphine. Raw data was extracted from <a href="https://statistiques-locales.insee.fr/?fbclid=IwAR3h1SgcWlg4H4R-btEWu7dnMjeO0dW9Mv-OfJ0IHf6yRI4ivAV2KNwOhd4#c=indicator&view=map2"> French National Institute for Statistics and Economic Studies (INSEE) </a>.

### References:
The hyperparameter tuning steps were adapted from these useful tutorials: <a href="https://towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74"> Hyperparameter tuning the Random Forest in Python </a> and <a href="https://www.analyticsvidhya.com/blog/2016/03/complete-guide-parameter-tuning-xgboost-with-codes-python/"> Complete guide parameter tuning XGBoost with codes in Python </a>.
