* Get noteboook 3.5 from the [book repo](https://github.com/fchollet/deep-learning-with-python-notebooks)
* Go through the notebook:
  * How the training time and accuracy change if you increase the size of middle layers from 16 to 32?
  * Does validation accuracy improve if you use 4 layers instead of 3?
  * In the loss and accuracy plots at the bottom the history object is used, explore that object. It contains information saved after each epoch of training.
  * history.history['acc'] may fail for some of you, find what name replaces 'acc'. (this depends on whether you use CNTK or Tensorflow backend)
* If done, train the same network on yelp data from yelp.ipynb from week 11 of the previous semester
