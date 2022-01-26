# NBA-Salary-Prediction
<img src="/assets/img/MarineGEO_logo.png" alt="MarineGEO circle logo" style="height: 100px; width:100px;"/>

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


