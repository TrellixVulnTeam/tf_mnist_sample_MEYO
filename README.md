# TensorFlow MNIST Sample


## TensorFlow Install

### Anaconda Installation

- anaconda3-4.1.0
- TensorFlow 0.10

```
$ pyenv install anaconda3-4.1.0
$ conda create -n tensorflow python=3.5
```

```
$ source activate tensorflow
# $ source deactivate
```

```
$ conda install -c conda-forge tensorflow
```

### Docker Installation

- TensorFlow 0.10

```
$ docker run -it -p 8888:8888 gcr.io/tensorflow/tensorflow
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
