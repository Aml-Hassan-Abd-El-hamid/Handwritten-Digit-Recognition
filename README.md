# Handwritten Digit Recognition
A handwritten digit recognizer built using: Python, Tensorflow and Keras.<br>
The dataset used in that project is the MNIST dataset which is a very famous and clean dataset and that's why I skipped the cleaning step in that project.<br>
The MNIST dataset is loaded first from the Keras dataset, you can load it using any other way.<br>
The MNIST dataset is split into a training set and a test set, the training set has 60k digits images represented by a 28X28 matrix and the test set has 10k images.<br>
Due to the fact that the data is already very clean the pre-processing step was a short and nice one, I have just normalized the data by dividing them by 255 and used the one-hot-encoding method to represent the labels.<br>
for the modelling step: <br>I've just started with a very basic neural network model - only 2 layers - and got a validation accuracy of 90% which was a good start due to the simplicity of that model.<br>
And then I started adding more complexity by adding more layers - also tried different optimizers: Adam, and different learning rates: .01,.1,.5 - until I reached a validation accuracy of %98.37, any changes after that was getting less accuracy<br>
After that I decided to try a convolutional neural network, once again I started with a very basic CNN model, and I was quite surprised - Note: that's my first deep learning project :) - as I got a validation accuracy of %98.43 which is even better than the second complex model.<br>
For my final model, I also used CNN but added more layers until I had an overfitting problem:), With that model, I managed to get a validation accuracy of %99.19.
