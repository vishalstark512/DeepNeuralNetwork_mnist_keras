# DeepNeuralNetwork_mnist_keras

It contains 2 main files, be sure to install the necessary requirements before applying the model

* first is dnn_mnist.py which contains full code how deep neural network mode is applied to mnist
  data set, one of the most common dataset. Same code can be used with other training sets also.

* Second file is the trained modedl(trained on mnist), it will work for predicting numers between 0-9
  It is provided just to check how things look after completion.
  

HOW TO USE THE MODEL
from keras.models import load_model
model = load_model('my_model.h5')
yFit = model.predict(xVal, batch_size=10, verbose=1)
print()
print(yFit)

Enjoy learning 
