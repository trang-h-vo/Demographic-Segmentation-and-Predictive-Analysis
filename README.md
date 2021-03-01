# French-departments-analysis

### Project goals
##### Explanatory analysis: 
Characterize 96 French departments using data about people who live and/or work there. 
Methods used include KMeans & Agglomerative Algorithm, visualization libraries such as matplotlib, seaborn and geopandas.
##### Predictive analysis: 
Predicting the wage of French citizens.
Models used include Linear Regression, Stochastic Gradient Descent, Random Forest Regressor and XGBRegressor.

### Data
The data sets used in this notebook contain more than 20.000 French citizens with their home & job information as follows:
- `Personal info`: Age (2019), educational level & gender
- `Home info`: household type, home city, home department & geolocation
- `Work info`: wage, company size & industry
- `French social-economic data`: average salary at department level, by job level, age group & gender

### Notebooks:
- `French_Departments_EDA_Geospartial.ipynb`: This notebook shows the exploratory analysis on French departments, characterized by their inhabitants and workers. 
- `Predictive_Analysis.ipynb`: This notebook shows the data preprocessing, treating categorical variables, modeling steps using pipeline and simple GridSearchCV. 

### Data source: 
The data sets were provided for a Machine Learning project at University Paris Dauphine. Raw data was extracted from <a href="https://statistiques-locales.insee.fr/?fbclid=IwAR3h1SgcWlg4H4R-btEWu7dnMjeO0dW9Mv-OfJ0IHf6yRI4ivAV2KNwOhd4#c=indicator&view=map2"> French National Institute for Statistics and Economic Studies (INSEE) </a>.
