# Stock-price-of-Google

[Recurrent Neural Networks](https://github.com/rjnp2/Data-Science/tree/main/tutorial/7.%20Deep%20Learning/RNN) for predicting Times Series

We will make an LSTM that will try to capture the downward and the upward
trend of the Google stock price because LSTM is the only powerful model that can do this as it performs way better than the traditional models. Apart from this, we are not going to perform a simple LSTM model. It's going to be super robust with some high-dimensionality, several layers as well as it is going to be a stacked LSTM, and then we will add some dropout regularization to avoid overfitting. Also, we will use the most powerful optimizer that we have in the Keras library.

In order to approach this problem, we will train our LSTM model on five years of the Google stock price, which is from the beginning of 2012 to the end of 2016 and then based on this training as well as on the identified correlations or captured by the LSTM of the Google stock price, we will try to predict the first month of 2017. We will try to predict January 2017, and again we are not going to predict exactly the stock price, but we are trying to predict the upward and downward trend of the Google stock price.

## Making the predictions and visualizing the results

![image](https://github.com/rjnp2/Stock-price-of-Google/blob/main/images/vis.png)
