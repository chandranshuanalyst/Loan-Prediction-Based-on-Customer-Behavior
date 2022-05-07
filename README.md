# Loan-Prediction-Based-on-Customer-Behavior
Predict who possible Defaulters are for the Consumer Loans Product

![0_lAkevA6upQBq-NCk](https://user-images.githubusercontent.com/91171166/167246492-acc99f97-2aff-41ec-baad-f925b3ab7c19.jpg)

## About the Dataset
1) income            :	 Income of the user	int<br />
2) age	              :  Age of the user	int<br />
3) experience        :  Professional experience of the user in years	int<br />
4) profession        :  Profession	string<br />
5) married	          :  Whether married or single	string<br />
6) house_ownership  	:  Owned or rented or neither	string<br />
7) car_ownership	    :  Does the person own a car	string<br />
8) risk_flag	        :  Defaulted on a loan	string<br />
9) currentjobyears	  :  Years of experience in the current job	int<br />
10) currenthouseyears :	 Number of years in the current residence	int<br />
11) city	            :  City of residence	string<br />
12) state	            :  State of residence	string<br />

The risk_flag indicates whether there has been a default in the past or not.

# Problem Statement 
An organization wants to predict who possible defaulters are for the consumer loans product. They have data about historic customer behavior based on what they have observed. Hence when they acquire new customers they want to predict who is riskier and who is not.

# Roadmap

### The project flow is as follows
1) Checking for missing values and dulplicate values
2) Univariate analysis and observing for patterns in the variables with respect to risk_factor
3) Finding correlations ,if any, in the data
4) Applying statistical tests (chi square and t test )
5) Encoding the categorical variables and scaling them
6) Appling train test split and using SMOTE to make data balanced
7) Fitting different models and checking for best model

# Conclusions

We know that in the case of bank loans , 
recall will reduce the number of false negatives (FN) i.e. the cases where there are chances of default/risk of loss 
while
precision will reduce the number of false positives (FP) i.e. the cases where there are chances of gain/profit
So here there is trade off and depends n business stratigy.
Here we use F1 score and accuracy as the mesaure of models.
#### Best model : random forest(gini) has the best scores and is therefore the best model for predictions
