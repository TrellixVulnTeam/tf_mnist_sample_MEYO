# TensorFlow MNIST Sample


## TensorFlow Install

### Pip Installation

Python 3.5.1
TensorFlow 0.10

```
# Ubuntu/Linux 64-bit
$ sudo apt-get install python-pip python-dev

# Mac OS X
$ sudo easy_install pip
$ sudo easy_install --upgrade six
```

```
# Ubuntu/Linux 64-bit, CPU only, Python 3.5
$ export TF_BINARY_URL=https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-0.10.0rc0-cp35-cp35m-linux_x86_64.whl

# Mac OS X, CPU only, Python 3.4 or 3.5:
$ export TF_BINARY_URL=https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-0.10.0rc0-py3-none-any.whl
```

```
# Python
$ pip install --upgrade $TF_BINARY_URL
```




## MNIST ML Sample

### Command

```
$ python tensorflow/examples/tutorials/mnist/fully_connected_feed.py
```

### Results

```
Training Data Eval:
  Num examples: 55000  Num correct: 49480  Precision @ 1: 0.8996
Validation Data Eval:
  Num examples: 5000  Num correct: 4521  Precision @ 1: 0.9042
Test Data Eval:
  Num examples: 10000  Num correct: 9059  Precision @ 1: 0.9059
```


## TensolBoard Sample

### Command

```
$ tensorboard --logdir=/xxxx/xxxx/ts_mnist_sample/data
```

### Results

```
Starting TensorBoard on port 6006
(You can navigate to http://0.0.0.0:6006)
```