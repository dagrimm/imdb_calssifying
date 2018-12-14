# imdb_calssifying

Using Keras with Tensorflow backend. 

Binary classification of the Keras imdb dataset using tanh for activation and sigmoid output layer for optimizing accuracy.
Optimizer is rmsprop.
Have a look at https://towardsdatascience.com/a-look-at-gradient-descent-and-rmsprop-optimizers-f77d483ef08b for more Information on rmsprop optimizer. 
Loss is calculated with binary crossentropy, due to classifying problem is binary. The network predicts if review is positive or not. 
Metric for Optimization is accuracy. 

Learning rate is plotted with Matplotlib - Of course you could insert a callback for Tensorflow. 
