BUSINESS PROBLEM:
  Mercari asked us to build a machine learning model which
tries to best fit the given features of the products and predicts the
prices of those products. Since we are predicting the prices of
products,it poses a regression problem. If we predict the price to
be much lower than the actual market price the it would be a loss
for person who sells the product,if we predict the price to be
much higher than the actual market price then it would be a loss
for person who buys that product,so the model we are predicting
should be very precise i.e it should predict the prices within in the
within the close vicinity of the actual price.
strictly speaking there is no latency constraint because
people may wait for time to get the correct prices of the products
so that no one will get loss i.e both buyer and seller.





ML PROBLEM FORMULATION:
   here we have to predict the price of a product given with features,which is a numerical value,so it poses us a regression problem





PERFORMANC METRIC:
  performance metric here we are using is root mean squared logarithmic error,instead of mse because the prices in training dataset follows the lo_nrmal distribution. 
   ![metric](https://user-images.githubusercontent.com/48234359/140683629-bb4ecbc3-69c3-4891-83b9-05da72c879bc.png)





Approaches:
Machine learning is the fastest growing field in the world.
Everyday there will be a launch of bunch of new algorithms. Some of them may work and some may not work on the data.
Their is no such ML algorithm that gives the super result then all the existing models. If it exists then all the models will be gone into dustbin.
Basing on the Prior Knowlege, domain excepts, from the problem statement and even from the first price winners one chooses the algorithm to tackle their problem.
Let's try a bunch of regression models to apply on the dataset and we even try a ensemble MLP models on our data.
You can see my article on this here:https://medium.com/@pokuriraviteja2015/sentence-correction-using-recurrent-neural-networks-e06d7fe0212f    
