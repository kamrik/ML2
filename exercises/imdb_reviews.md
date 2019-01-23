* Get noteboook 3.5 from the [book repo](https://github.com/fchollet/deep-learning-with-python-notebooks)
* Go through the notebook:
  * How the training time and accuracy change if you increase the size of middle layers from 16 to 32?
  * Does validation accuracy improve if you add another hidden layer?
  * In the loss and accuracy plots at the bottom the history object is used, explore that object. It contains information saved after each epoch of training.
  * Try usig and `mse` loss function instead of the `binary_crossentropy` 
  * history.history['acc'] may fail for some of you, find what name replaces 'acc'. (Thie depends on how the network was compiled, there are 3 compilation examples in the notebook)
* If done, train the same network on yelp data from yelp.ipynb from week 11 of the previous semester
