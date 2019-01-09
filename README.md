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
conda updata conda
```
Then install keras 
```
conda install keras
```

Test it by running `import keras` in python, you should see output like `Using TensorFlow backend` or `Using CNTK backend` - either is good. If you see any warnings about lack of GPU, that's also ok.
