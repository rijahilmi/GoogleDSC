# My Experience with Google Developer Product

So this can be counted as my first project using one of the amazing tools that Google has developed, which is Tensorflow.
![](https://user-images.githubusercontent.com/32363208/96848914-30f9a000-147f-11eb-9e63-df938815d256.png)

## What is this?
I've used Tensorflow to train a simple Artificial Neural Network model based on the Curn Model Table, using TensorFlow and Scikit-learn libraries as learning tools. The purpose of this project is to apllicate my knowledge (because I would never understand something I never try :cry:) and to create a basis model for a bank-related problem; will my costumers exit/close their bank account based on the parameters I know?

## Then, how does this program works?
The program works by following procedures.
1. Pre-process the data by firstly importing the chosen csv data using pandas. Then, wrangle the data into something we can analyze using pandas features and Scikit-learn's encoder. Finish the step by assigning the data used for training and testing, and transform-normalize it.
2. Build the Artificial Neural Network (ANN) using Keras' features in Tensorflow.
3. Train the ANN using the data chosen before. The amount of Epochs/iterations can be gained by setting it to a large value to make sure that the accuracy of the predicted results from ANN is good and converged.
4. Generalize the prediction results (because the outcome of them are between 0-1 with decimals in-between) by assuming that, if the prediction result is less than 0.5, the costumer will not exit/close their bank account. If the prediction result is 0.5 or larger than 0.5, the costumer will exit/close their bank account. Finally, we can re-check the ANN accuracy using predicted-real results comparison using Confusion Matrix.

## The results! :flushed:
Actually, the prediction accuracy is 'good' enough to be said 'accurate' (around 86%, which is good!). But you know, 14% error is still sooooooooo big, far from the typical-standard prediction accuracy that has less than 10% error!
I still appreciate my work though, at least it works :haha:.

## Lessons that I learned :pencil:
In order to create a more accurate model, I need to change my code and add other important features in the learning process. Not only that, I think we can get a better result if we get more parameters and samples. As somebody said, the more the merrier!
