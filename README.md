# My Experience with Google Developer Product

So this can be counted as my first project using one of the amazing tools that Google has developed, which is Tensorflow.
![](https://user-images.githubusercontent.com/32363208/96848914-30f9a000-147f-11eb-9e63-df938815d256.png)

## What is this?
I've used Tensorflow to train a simple Artificial Neural Network model based on the Curn Model Table, using TensorFlow and Scikit-learn libraries as learning tools. Based on the codes I write, it can be described into 4 procedural steps:

1. Pre-process the data by firstly importing the chosen csv data using pandas. Then, wrangle the data into something we can analyze using pandas features and Scikit-learn's encoder. Finish the step by assigning the data used for training and testing, and transform-normalize it.
2. Build the Artificial Neural Network (ANN) using Keras' features in Tensorflow.
3. Train the ANN using the data chosen before. The amount of Epochs/iterations can be gained by setting it to a large value to make sure that the accuracy of the predicted results from ANN is good and converged.
4. Generalize the prediction results (because the outcome of them are between 0-1 with decimals in-between) by assuming that, if the prediction result is less than 0.5, the costumer will not exit/close their bank account. If the prediction result is 0.5 or larger than 0.5, the costumer will exit/close their bank account. Finally, we can re-check the ANN accuracy using predicted-real results comparison using Confusion Matrix.

## The results! :flushed:
Well, not every expectations will come to a reality. The model did not do a really great job since the Fashion MNIST dataset is a 32 by 32 pixels of image. So the model is not that robust to the live images given from the webcam. The only time that it will be able to predict correctly is when I point out the exact image from the dataset!

## Lessons that I learned :pencil:
In order to create a robust model, we need to insert different variations of the dataset when training the model so that the network will be able to recognize the objects in different conditions.
