# COMP 3132 - Python ML, part 2

## Course outline
 * [Draft](https://docs.google.com/document/d/13-xZCzKXh8en7wyOvsfpQGjdO1qTJFZuh_56rYE5Ymg/view)

## Book
 - [Deep Learning with Python](https://www.manning.com/books/deep-learning-with-python) by François Chollet
   - [Online audio version](https://livebook.manning.com/#!/book/deep-learning-with-python/chapter-1/) (karaoke style, first 3 chapters are free)
   - The audio version is also [available on Audible](https://www.audible.com/pd/Deep-Learning-with-Python-Audiobook/B07H5TZ6KN)
   - [Book GitHub page](https://github.com/fchollet/deep-learning-with-python-notebooks)
 
## Introductory videos
 - [Neural networks playlist](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) by Grant Sanderson of 3blue1brown.com
 - [Hello World Canada: The Rise of AI](https://www.youtube.com/watch?v=Dk7h22mRYHQ&t=1523s) - a motivating 50 minute documentary by Bloomberg
 - [The Neuron](https://www.youtube.com/watch?v=6qS83wD29PY) - how real neurons in our brain work (2 min). Remember that artificial neural networks are only "inspired" by biological neurons, and don't fully mimic how brain works. Moreover, we don't yet fully understand how brain works.
 - [Overview of DL tools](https://www.youtube.com/watch?v=j_pJmXJwMLA) by [Siraj Raval](https://www.youtube.com/channel/UCWN3xxRkmTPmbKwht9FuE5A)
 
## Installing Keras on your laptop
Note: This will take some time and download several hundred MB.

If you already have Anacanoda, open Anaconda prompt and first update conda by running
```
conda update conda
```
Then install keras 
```
conda install keras
```

Test it by running `import keras` in python, you should see output like `Using TensorFlow backend` or `Using CNTK backend` - either is good. If you see any warnings about lack of GPU, that's also ok.

If you have a recent Nvidia GPU you can try following the [CNTK instructions](CNTK.md) to istall the GPU version of CNTK but this is optional.

## Week 1
 * Lab - [exercises/intro_MNIST.md](exercises/intro_MNIST.md)
 * Reading for next week:
   * Chapter 1 of the book (available free on book website)
   * First 2 videos of the [Neural networks playlist from 3Blue1Brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)
 * Home assignment 1 - [exercises/home_assignment1.md](exercises/home_assignment1.md)  (due Jan 23rd)

## Week 2
 * [Lecture slides](slides/02_week.ipynb)
   * [Animation of 2D convolution](https://i.stack.imgur.com/uEoXw.gif)
   * [How Blurs & Filters Work - Computerphile](https://www.youtube.com/watch?v=C_zFhWdM4ic) (8 min)
 * Lab - [exercises/convolution.ipynb](exercises/convolution.ipynb)
 * Reading for next week:
   * Chapter 2 of the book (skip the heavy math)
   * The remaining 2 videos of the [Neural networks playlist from 3Blue1Brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)
 * Reminder: home assignment 1 is due Jan 23rd

## Week 3
 * [Lecture slides](slides/03_week.ipynb)
 * Lab - [exercises/imdb_reviews.md](exercises/imdb_reviews.md)
 * Reading for next week:
   * Review model evaluation techiques - videos #5 and #7 from [Kevin's sklearn videos](https://github.com/justmarkham/scikit-learn-videos)
   * Chapter 3 intro and sections 3.1, 3.2 and 3.4
   
## Week 4
 * [Lecture slides](slides/04_week.ipynb)
 * Lab - [exercises/boston_housing.md](exercises/boston_housing.md)
 * Reading for next week:
   * Book sections 3.5, 3.6, 3.7
   * [Walkthrough of the MNIST example with Keras](https://www.youtube.com/watch?v=wQ8BIBpya2k)

## Week 5
 * [Lecture slides](slides/05_week.ipynb)
 * Lab - [exercises/kaggle_housing.md](exercises/kaggle_housing.md)
 
## Week 6
 - There was no lecture
 - Lab. Revising the MPG dataset using [this notebook](https://github.com/kamrik/ML1/blob/master/exercises/mpg_revisited.ipynb) from the previous semester. Replace the decision tree with a neural network.

## Week 7 - Midterm
#### Prep advice
 - Solve lab exercises
 - Go over the [MNIST video from sentdex](https://www.youtube.com/watch?v=wQ8BIBpya2k)
 - Read chapters 3 of the book (skip section 3.3)
 - Solve more lab exercises
 - From chapter 4 read till section 4.3
 - Read chapters 1 and 2 of the book
#### Main topics and concepts to be familiar with
 - Data manipulation in NumPy and Pandas
 - Metrics used for evaluating and comparing ML models of different types
 - Overfitting
 - Train/validation/test data splitting and why we do this
 - Concepts about neural nets - weights, layers, activation functions, loss functions
 
## Home assignment 2 - due March 13
 - [Instructions](exercises/home_assignment2.md)
 - This home assignment is also an excellent practice exercise for the midterm
 
## Week 8 - Intersession
## Week 9
 * [Lecture slides](slides/09_week.ipynb)
 * Lab - [exercises/convnets_mnist.md](exercises/convnets_mnist.md)
 * Reading:
   - Chapter 5, sections 5.1 & 5.2
   - A great [article about convnets](https://www.codementor.io/james_aka_yale/convolutional-neural-networks-the-biologically-inspired-model-iq6s48zms) with historical background and intuitive explanation of how they work.
   - Videos:
     - [3 minute explanatioin of the convolution in convnets](https://www.youtube.com/watch?v=jajksuQW4mc) - from [this Udacity course](https://www.udacity.com/course/deep-learning--ud730)
     - [Animation of 2D convolution](https://i.stack.imgur.com/uEoXw.gif)
     - [How Blurs & Filters Work - Computerphile](https://www.youtube.com/watch?v=C_zFhWdM4ic) (8 min)
     - [Lecture on convnets by Siraj Raval](https://www.youtube.com/watch?v=FTr3n7uBIuE)  (46 min)
     
## Week 10
 * [Lecture slides](slides/10_week.ipynb)
 * Lab - [exercises/pretrained.md](exercises/pretrained.md)

## Week 11
 * [Lecture slides](slides/11_week.ipynb)
 * Lab - continue wroking on [exercises/pretrained.md](exercises/pretrained.md)
 

## Home assignment 3 - due April 10
 - [Instructions](exercises/home_assignment3.md)
  
## Week 12
 * [Lecture slides](slides/12_week.ipynb)
 * * Lab - [exercises/rnn.ipynb](exercises/rnn.ipynb)
