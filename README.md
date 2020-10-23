# My Experience with Google Developer Product

So this can be counted as my first project using one of the amazing tools that Google has developed, which is Tensorflow.
![](https://user-images.githubusercontent.com/32363208/96848914-30f9a000-147f-11eb-9e63-df938815d256.png)

## What is this?
I've used Tensorflow to train a Convolutional Neural Network model based on the Fashion MNIST dataset, which is a built - in dataset from Keras. I used the model to predict the type of clothes that you are wearing through the webcam in real time. I also used an additional library which is OpenCV which helps a lot in the data preprocessing and format the video from the webcam to be able to be feed in the model. Since the dataset is a 32 by 32 pixel sized image, I had to tune down the image size from the webcam to the same size as the dataset in the backend in order to be able to feed in the network.

## The results! :flushed:
Well, not every expectations will come to a reality. The model did not do a really great job since the Fashion MNIST dataset is a 32 by 32 pixels of image. So the model is not that robust to the live images given from the webcam. The only time that it will be able to predict correctly is when I point out the exact image from the dataset!

## Lessons that I learned :pencil:
In order to create a robust model, we need to insert different variations of the dataset when training the model so that the network will be able to recognize the objects in different conditions.
