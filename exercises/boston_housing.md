* Open notebook 3.7 from the [book repo](https://github.com/fchollet/deep-learning-with-python-notebooks) in Jupyter (use CNTK icon if on lab desktop)
* Go through the notebook:
  * Training for 100 or 500 epochs as the notebook suggests is slow, reduce that to 30 and 200 respectively
  * Try using [sklearn.model_selection.KFold](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.KFold.html) instead of the manual validation data selection in the first big loop.
  * Does validation accuracy degrade if you use one less hidden layer?
  * Try using and `mae` loss function instead of the `mse`
  * When computing the smoothed version of the validation curve, try using a sliding window average (could be done via a convolution) instead of the exponential decay average used by the book author.
* When done, train the same network on house price data from the [Kaggle House Prices competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
