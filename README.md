# ML_Regression

## Data Set Description:

Title : Yacht Hydrodynamics Data Set

Link : https://archive.ics.uci.edu/ml/datasets/yacht+hydrodynamics

Data Set Information:

Prediction of residuary resistance of sailing yachts at the initial design stage is of a great value for evaluating the ships performance and for estimating the required propulsive power. Essential inputs include the basic hull dimensions and the boat velocity.

The Delft data set comprises 308 full-scale experiments, which were performed at the Delft Ship Hydromechanics Laboratory for that purpose. These experiments include 22 different hull forms, derived from a parent form closely related to the Standfast designed by Frans Maas.

## LSR 

The least squares method is a statistical procedure to find the best fit for a set of data points by minimizing the sum of the offsets or residuals of points from the plotted curve.


## GD

To minimize the cost function, the model needs to have the best value of θ1 and θ2. Initially model selects θ1 and θ2 values randomly and then iteratively update these value in order to minimize the cost function until it reaches the minimum. By the time model achieves the minimum cost function, it will have the best θ1 and θ2 values. Using these finally updated values of θ1 and θ2 in the hypothesis equation of linear equation, the model predicts the value of x in the best manner it can. 

**In the Gradient Descent algorithm, one can infer two points :** 
 

If slope is +ve : θj = θj – (+ve value). Hence value of θj decreases.

If slope is -ve : θj = θj – (-ve value). Hence value of θj increases.

**The choice of correct learning rate is very important as it ensures that Gradient Descent converges in a reasonable time. :**
 

If we choose α to be very large, Gradient Descent can overshoot the minimum. It may fail to converge or even diverge. 

If we choose α to be very small, Gradient Descent will take small steps to reach local minima and will take a longer time to reach minima. 

## Correlation

 Correlation quantifies the strength of the linear relationship between a pair of variables
 
## References

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC374386/#:~:text=The%20most%20commonly%20used%20techniques,the%20form%20of%20an%20equation.

https://www.geeksforgeeks.org/gradient-descent-in-linear-regression/

