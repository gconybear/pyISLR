
### chapter 2 exercises 

<u>conceptual</u>



1. For each of parts (a) through (d), indicate whether we would generally
expect the performance of a flexible statistical learning method to be
better or worse than an inflexible method. Justify your answer.


(a) The sample size n is extremely large, and the number of predictors p is small. 
	- *answer*: flexible, we want to let the model learn 


(b) The number of predictors p is extremely large, and the number
of observations n is small. 
	- *answer*: inflexible, we may want to restrict to a linear model due to risk of overfitting to small sample space 


(c) The relationship between the predictors and response is highly
non-linear.
	- *answer*: flexible, restricting to an inflexible hypothesis class with reduce our model search space, and given the fact that the relationship is already known to be non-linear, we should allow to more freedom in the model 


(d) The variance of the error terms, i.e. σ2 = Var(), is extremely
high. 
	- *answer*: inflexible, not totally sure (consistency?) 

 

2. Explain whether each scenario is a classification or regression prob- lem, and indicate whether we are most interested in inference or pre- diction. Finally, provide n and p. 

(a) regression/inference – we're looking to understand effects on salary, not to predict salaries (inference) ; and salary ($) is a continous variable, so regression  

(b) classification/predict – we want to attempt to see the future success of our project ; success or failure is a binary/boolean value classification (either sucecss or failure, no in between) 

(c) regression/predict – predicting % change, not understanding why ; % change is a continuous value thus regression 


3. We now revisit the bias-variance decomposition. 

(a) No 

(b) skip 

4. skip 

5.*answer* 
	-  very flexible approaches can be useful... 
		- when the underlying target hypothesis can be estimated to be non-linear
		- when num observations is very large and num predictors relatively small 
			- meaning we want *to allow for* complex (polynomial, etc) combinations of features 
	- less flexible approaches can be useful... 
		- when a "white box" model is preffered (ex. linear regression) 
			- we want to **understand** the phenomena rather than just solely predict 
		- we can estimate the underlying target hypothesis to be linear 
			- OR any other specific mathematical  relationship (squared, cubed, wtc) 
		- large num of features in relation to observations  

6. see notes 

7		- large num of features in relation to observations  

6. see notes 

7. given data, do KNN and answer questions 

(a) simple dist calculation – see ipynb 

(b) green / obs 5 is closest 

(c) red / obs 2,5,6 are closest 

(d) small ; a large k will produce a roughly linear relationship, small k allows for flexibility bc fewer points


---- 

question 8 + are simple R implementations.... maybe later 

  
