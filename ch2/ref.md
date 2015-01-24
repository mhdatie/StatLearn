#2.1 R1

###In the expression Sales ≈ f(TV, Radio, Newspaper), "Sales" is the:

- Response

#2.2 R1

###While doing a homework assignment, you fit a Linear Model to your data set. You are thinking about changing the Linear Model to a Quadratic one. Which of the following is most likely true:

- Using the Quadratic Model will decrease the Bias of your model. 

	- Explanation: Introducing the quadratic term will make your model more complicated. More complicated models typically have lower bias at the cost of higher variance. This has an unclear effect on Reducible Error (could go up or down) and no effect on Irreducible Error.

#2.2 R2

###A hypercube with side length 1 in d dimensions is defined to be the set of points (x1, x2, ..., xd) such that 0≤xj≤1 for all j = 1, 2, ..., d. Define the boundary region of the hypercube to be the set of all points such that there exists a j for which 0≤xj≤.05 or .95≤xj≤1 (i.e., it is the set of all points that have at least one dimension in the most extreme 10% of possible values). What proportion of the volume of a hypercube of dimension 50 is in the boundary region?

###Please give your answer as a value between 0 and 1 with 3 significant digits. If you think the answer is 50.52%, you should say 0.505:

- 1 - (0.9)^d = 0.995

	- Explanation: We know that the volume of the whole hypercube is 150 = 1. The volume of the interior of the hypercube is 0.950 = 0.005. Thus, the volume of the boundary is 1-0.005 = 0.995.

#2.3 R1

###True or False: A fitted model with more predictors will necessarily have a lower Training Set Error than a model with fewer predictors.

- False

	- Explanation: While we typically expect a model with more predictors to have lower Training Set Error, it is not necessarily the case. An extreme counterexample would be a case where you have a model with one predictor that is always equal to the response, compared to a model with many predictors that are random.

#2.4.R1

###Look at the graph given on page 30 of the notes. Which of the following is most likely true of what would happen to the Test Error curve as we move 1/K further above 1?

- It does not make sense to have 1/K>1

	- Explanation: Since K is the number of neighbors, the value of K must be a Natural Number. This means that 1/K≤1.

#2.R.R1

###You are doing an analysis in R and need to use the 'summary()' function, but you are not exactly sure how it works. Which of the following commands should you run?

 - help(summary) 
 - ?summary
 - ?summary()

#2.Q.1

###For each of the following parts, indicate whether we would generally expect the performance of a flexible statistical learning method to be better or worse than an inflexible model.

###The sample size n is extremely large, and the number of predictors p is small:

- Flexible is better

	- Explanation: A flexible model will allow us to take full advantage of our large sample size. 

#2.Q.2

###The number of predictors p is extremely large, and the sample size n is small:

- Flexible is worse
	
	- Explanation: The flexible model will cause overfitting due to our small sample size.

#2.Q.3

###The relationship between the predictors and response is highly non-linear:

- Flexible is better
	
	- Explanation: A flexible model will be necessary to find the nonlinear effect.

#2.Q.4

###The variance of the error terms, i.e. σ2=Var(ϵ), is extremely high:

- Flexible is worse

	- A flexible model will cause us to fit too much of the noise in the problem.