# Predicting Domestic Box Office for Movies 

## Abstract
The goal of this project is to predict the domestic gross of the movie based on their features using regression models. The result of this model is to help film investors make better strategic decision during the process of movie production that leads to high return investment. 

## Design

To build regression models and select the best model to predict the domestic gross of the movies based on their features. The evaluation metrics, such as R^2, RMSE, and MAE are evaluated for each model.

## Data

The data was scraped from BoxOfficeMojo.com which includes features, such as run time, budget, and MPAA rating. The datasets are from 2010~2019 in North America and contain 1803 movies. After performing exploratory data analysis, the dataset contains 1078 movies.  

## Algorithms
- Used BeautifulSoup to scrape movie website.
- Performed data cleaning and visualizations.  
- Feature Engineering: converted categorical feature to binary dummy variables. 
- Models: Linear regression, lasso, ridge, random forest regression and the log transformation of the target variable were evaluated. Evaluation metrics include R^2, RMSE, and MAE. 
- Performed K-fold cross validation for each model. 

## Tools
- BeautifulSoup for web scraping
- Pandas and Numpy for data manipulation 
- Statsmodels and Scikit-learn for modeling
- Seaborn and Matplotlib for data visualizations 

## Communication
The presentation slides, code, and details on the analysis are in this project’s repository. 

