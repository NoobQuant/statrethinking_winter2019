# Lecture 3

## Geocentric models
 - Geocentric models of the solar system: are in inference-sense wrong, but are quite accurate in predictive sense; where the planets will be (from OUR perspective).
   - Descriptively accurate, mechanistically wrong.
 - Regression model is the same!
 - Statistical models can onlu *describe* things. Useless without substance knowledge.

## Why normal distribution is so "normal"?
 - Easy to calculate with
 - Common in nature (ontological perspective)
   -  Gaussian distribution are born from adding fluctuations, i.e. random variables. But note Taleb's point, that for some random variables adding summands takes way too long to borne a Gaussian! Need for pre-asymptotics.
 - Very conservative assumption (epistemological perspective)
   - Gaussian is the maximum entroy (most conservative) distribution of the mean-variance distributions (does this mean location-scale distributions as well?) -> leaves most possibilities open!

## Calculating posterior distribution
 - Calculating posterior = conditioning the prior to data.
 - Three different, numerical conditoning engines for computing the posterior:
   - Grid approximation
   - Quadratic approximation
   - MCMC

Grid approximation becomes infeasible very quickly. Quadratic approximation works well for linear regression. For GLMs for example, less so.

### Grid approximation
Means defining the support of posterior as a grid and applying Baye's rule for each grid element to calculate the value of posterior at that element.
 - Define grid for all parameters.
 - For each grid element
   - compute value of prior
   - compute value of likelihood
   - compute unstandardized poesterior
   - standardize by eerage likelihood to get posterior 




