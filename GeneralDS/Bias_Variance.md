### Bias/Variance TradeOff: 

* The error of a model can be written as the sum of 3 components. 
  1. Bias - error caused by the assumptions of our model. Eg assuming linear model Vs quadratic. 
  2. Variance - Error caused by instability in model due to training data. A model with high variance is likely one with that has many degrees of freedom. Can think of DoF as number of trained parameters a model has. More DoF implies more likely to be overfit. Can also think of Variance, as how quickly does our data change if the training data is changed. If you have 2 datapoints and using a polynomial of 5 degrees, the model becomes very reliant on those 2 points, and thus can vary if the input data is changed. 
  3. Irreducible error - errors due to dataset. Eg having duplicates, mislabelled data etc. 
* A model that has more DoF is likely to have fewer assumptions. Eg assuming data is linear is stronger/harder than assuming data is quadratic. This is because quadratic models are also linear if the quadratic coefficient is 0. Therefore the increase in model complexity reduces the bias. 
* However increasing model complexity allows for more over fitting to take place, thus you get an increased variance. 
* This is known as the bias/variance tradeoff. 