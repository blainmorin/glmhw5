# glmhw5
multilevel models, simulation


## Gellman + Hill Chpt7 #2:
### (question 1 on hw)

Continuous probability simulation: the logarithms of weights (in pounds) of men
in the United States are approximately normally distributed with mean 5.13
and standard deviation 0.17; women with mean 4.96 and standard deviation
0.20. Suppose 10 adults selected at random step on an elevator with a capacity
of 1750 pounds. What is the probability that the elevator cable breaks?

## Gellman + Hill Chpt 7 #8:
### (question 2 on hw)

Inference for the ratio of parameters: a (hypothetical) study compares the costs
and effectiveness of two different medical treatments.

- In the first part of the study, the difference in costs between treatments A
and B is estimated at 600 per patient, with a standard error of 400, based
on a regression with 50 degrees of freedom.

- In the second part of the study, the difference in effectiveness is estimated
at 3.0 (on some relevant measure), with a standard error of 1.0, based on a
regression with 100 degrees of freedom.


- For simplicity, assume that the data from the two parts of the study were
collected independently.

Inference is desired for the incremental cost-effectiveness ratio: the difference
between the average costs of the two treatments, divided by the difference be-
tween their average effectiveness. (This problem is discussed further by Heitjan,
Moskowitz, and Whang, 1999.)

(a) Create 1000 simulation draws of the cost difference and the effectiveness dif-
ference, and make a scatterplot of these draws.

(b) Use simulation to come up with an estimate, 50% interval, and 95% interval
for the incremental cost-effectiveness ratio.

(c) Repeat this problem, changing the standard error on the difference in effec-
tiveness to 2.0.

## Gellman + Hill Chpt 8 #1:
### (question 3 on hw)

Fitting the wrong model: suppose you have 100 data points that arose from the
following model: y = 3+0.1x1 + 0.5x2 + error, with errors having a t distribution
with mean 0, scale 5, and 4 degrees of freedom.We shall explore the implications
of fitting a standard linear regression to these data.

(a) Simulate data from this model. For simplicity, suppose the values of x1 are
simply the integers from 1 to 100, and that the values of x2 are random and
equally likely to be 0 or 1. Fit a linear regression (with normal errors) to these
data and see if the 68% confidence intervals for the regression coefficients (for
each, the estimates ±1 standard error) cover the true values.

(b) Put the above step in a loop and repeat 1000 times. Calculate the confidence
coverage for the 68% intervals for each of the three coefficients in the model.

(c) Repeat this simulation, but instead fit the model using t errors (see Exercise
6.6).