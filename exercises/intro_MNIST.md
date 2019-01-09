## Your first neural net
 * If you are using your own laptop, make sure Keras is installed - See "Installing Keras" section in the top README file.
 * If using lab desktop, use localadmin user to log in - you student ID user doesn't yet have the right permissions 
 * Click the CNTK icon on desktop (balck icon, like the terminal), this will start a terminal with the right evnironment set up
 * Run `jupyter notebook` in that terminal
 * Download or clone book GitHub repo from https://github.com/fchollet/deep-learning-with-python-notebooks
 * Open the first notebook in Jupyter `2.1-a-first-look-at-a-neural-network.ipynb`
   * Make sure to use the Jupyter notebook started from CNTK terminal
   * If you get a permission error, most likely you didn't use the localadmin user
   * If you get `ModuleNotFoundError: No module named keras` - you probably didn't use the CNTK icon to start Jupyter
 * Go through the notebook with the following modifications
   * Draw some of the digits using `imshow()` function to see how they look like.
   * Why are the digits represented by 2D arrays?
   * Why imshow() draws a blue/yellow image? How to convert it to grayscale?
   * Use `time.time()` to measure exactly how long it takes to train the network (how long the `fit()` function runs)
   * After finishing the notebook, train a decision tree classifier using sklearn and compare the accuracy
   * Try to use sklearn train_test_split function to split the training data into training and validation set
