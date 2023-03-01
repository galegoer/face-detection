# handwritten-classification

Application utilizing a Convolutional Neural Network (CNN) for handwritten digit classification. Currently has a test accuracy of 98.6%.
Images of numbers can either be analyzed locally from a hand drawn image or if a data uri is provided through a text file (Provide the path of the local text file). The below example uses a paint like canvas which can also be analyzed after the data uri is extracted.

Note: The data this model was trained against is from the [MNIST dataset](https://en.wikipedia.org/wiki/MNIST_database) and is trained against these images. The python script currently uses this model along with the preprocessing of an image so that it may more closely resemble the images it was trained against. Using images from the database in conjuction with the python script will lead to inaccuracy as these images do not need to be preprocessed but the script attempts to do so.

# Working live example with a canvas
Site: http://ec2-3-128-207-4.us-east-2.compute.amazonaws.com/canvas

![Image of live-example](example-images/live-example.png)
