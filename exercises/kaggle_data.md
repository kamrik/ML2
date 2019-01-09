## Getting data into Kaggle kernels
Sometimes keras built in datasets fail to load when working in a Kaggle kernel. 
For example the following code can trhow an error while downloading the mnist.npz file from amazon:
```
from keras.datasets import mnist
all_data = mnist.load_data()
```

To work around this:
Click "Add data" on the right side, search for mnist.npz and add it. This will put mnist.npz in your `inputs` idrectory which can be accessed as `../inputs`.
Then run
 ```
 !mkdir -p /tmp/.keras/datasets/
 !cp ../input/mnist.npz /tmp/.keras/datasets/
 ```
This puts mnist.npz file in keras cache dir, the next time you run the `mnist.load_data()` function it will take the file from this cache.
 
