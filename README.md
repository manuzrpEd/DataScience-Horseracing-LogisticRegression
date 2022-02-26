# Horseracing exercise

The given sample dataset (‘datatests.csv’) contains information on racing. Table 1 describes the variables that are included in the sample dataset provided. With this dataset, you are asked to employ a statistical regression model to identify the factors that are associated with predicting race winners. 


![image](https://user-images.githubusercontent.com/69723856/155848993-a5d5ad4d-cb55-4b6c-9d86-239f5be98ee2.png)

My exercise attempt is [here](https://github.com/manuzrpEd/Horseracing/blob/main/Horseracing.ipynb).
The findings, or summary of my exercise is as follows:

<li>1.	I provided relevant descriptive statistics on explanatory variables. I produced graphs and displayed descriptive statistics. </li>
<li>2.	I have used the logistic regression as I believe is the more appropriate model to predict race winners, constructing a model for the probability of winning. The linear regression model has the problem that it can produce probabilities that are outside the range of (0,1).</li>
<li>3.	I have estimated the model and I have added one constructed variable to the regression model selected. This variable is 'Cumulated Wins' by Horse. My hypothesis is that past wins help predict future wins. By reestimating the model with this variable, I find a positive relation between Cumulated Wins and the probability of winning.</li>
<li>4.	I have displayed the results of the regression model selected with graphs for selected variables and with coefficient estimates, t-statistics and p-values. Other variables that help predict the probability of winning are: numberOfRunners, ageInDays, nPastRaces and raceClass. All these variables are negatively associated with the probability of winning. </li>
<li>5.	The model still produces little variability in the probability of winning a race. More variables could be incorporated, like a rolling ranking of the horse in past races. </li>
