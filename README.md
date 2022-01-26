# NBA-Salary-Prediction
Predicting the salaries of NBA players based off their player stats

This project aims to explore how a wide variety of NBA statistics can be used to predict the salary of an NBA player from 1995 to 2017. My goals for this project are to:
- Discover which statistics are the best predictors of an NBA player’s salary
- Use a machine learning model to predict NBA salaries
- Determine which players have been overvalued and undervalued according to their given vs. predicted salary
- Determine which teams are the best and worst at extracting value from their players and if there is a correlation with the amount of games a team wins

### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [sklearn](https://scikit-learn.org)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

## Data Source:

https://www.kaggle.com/koki25ando/salary


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

The results may be misleading due to the data, how they are partitioned, the different machine learning models we used, and how the models are configured. The data was imported from a raw file which is not always the best form for analysis. Before any regression or analysis was done, we trained the models, used the specified datasets, and cleaned them to remove any null values. As for the most preventable part of the analysis, we separated it into X and Y for training and testing sets to partition our data. More information will be found in this report's Data Analysis/Preprocessing section. Overall, the models we build we reasonably reasonable to be used in an actual world situation but to improve it, we would need more data instead of just the 2017-18 season data. 


