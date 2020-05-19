# covid-global-forecast
Ipython Notebook for the Kaggle competition [COVID19 Global Forecasting (Week 4)](https://www.kaggle.com/c/covid19-global-forecasting-week-4) series, including weeks 1,2,3 & 4.
The aim of this repository is to provide a starting point to understand the COVID-19 spreading and how the cumulative infections and deceased cases evolve. 

The code includes a brief review of the simple [SIR](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology#The_SIR_model) epidemics model
Finally, data is modified and enriched to finally feed several machine learning models, which are responsible of the regression results. 


## Kaggle competition description
From the competition [homepage](https://www.kaggle.com/c/covid19-global-forecasting-week-4):
> Kaggle is launching a companion COVID-19 forecasting challenges to help answer a subset of the NASEM/WHO questions. While the challenge involves forecasting confirmed cases and fatalities between April 15 and May 14 by region, the primary goal isn't only to produce accurate forecasts. It’s also to identify factors that appear to impact the transmission rate of COVID-19.
> You are encouraged to pull in, curate and share data sources that might be helpful. If you find variables that look like they impact the transmission rate, please share your finding in a notebook.
> As the data becomes available, we will update the leaderboard with live results based on data made available from the Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE).
> We have received support and guidance from health and policy organizations in launching these challenges. We're hopeful the Kaggle community can make valuable contributions to developing a better understanding of factors that impact the transmission of COVID-19.

## Table of contents
1. Exploratory data analysis (EDA) 
2. SIR model
3. Data enrichment  
4. Predictions for the early stages of the transmission   
5. Predictions for the late stages of the transmission
6. Statement of the author

### Dependencies
- [IPython](http://ipython.org/)
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [SciKit-Learn](https://scikit-learn.org/stable/)
- [SciPy](https://www.scipy.org/)
- [Seaborn](https://seaborn.pydata.org/#)
- [Matplotlib](https://matplotlib.org/)
- [XGBoost](https://xgboost.readthedocs.io/en/latest/#)
- [LightGBM](https://lightgbm.readthedocs.io/en/latest/#)


## Contributors
Patrick Sánchez Galea ([Kaggle profile](https://www.kaggle.com/saga21))

