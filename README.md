# NBA-Salary-Prediction<img width="350" height="350" src="https://user-images.githubusercontent.com/94552522/151256246-763c57e0-7193-48b4-ba39-8d319c68a233.png" align=right>

[Data Science I Project Presentation.pdf](https://github.com/Allanwaweru/NBA-Salary-Prediction/files/7946027/Data.Science.I.Project.Presentation.pdf)

The goal was to create a model and predict what salary should be given to the NBA players based on their statistics in the NBA. 

I found it intriguing to work on this because I am an avid NBA fan and because this translates to a  real-world problem 

The project's main objective was to conduct an exploratory analysis and develop models that are used in predicting how much salary should be given. The analysis and the models support each other in ensuring that the prediction is nearly accurate. The data sets used in this project are a training data set, which has a model of 353 players, and testing data set with 89 players


### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [sklearn](https://scikit-learn.org)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

## Data Source:

https://www.kaggle.com/rikdifos/nba-players-salary-prediction/data?select=NBA_season1718_salary.csv
https://www.kaggle.com/rikdifos/nba-players-salary-prediction/data?select=Players.csv
https://www.kaggle.com/rikdifos/nba-players-salary-prediction/data?select=Seasons_Stats.csv


## Analysis Steps:

- Exploratory Data Analysis
- Models Explored:
  - KNN Regressor Model
  - Multiple Linear Regression Model
  - Random Forest Model
 

## Model Comparison and Conclusion:

Overall, the results we obtained are significant because this was the most important part of our analysis. To understand the efficiency of the models, we used the R-Squared method to understand how much of the data is explained by the model built. The R-Squared values we got for each of the models were:

- Random Forest Regressor: 61.4%
- K-Nearest Neighbor: 61.8%
- Linear Regression: 40.4%
