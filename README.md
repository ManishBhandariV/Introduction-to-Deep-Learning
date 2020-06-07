# Introduction-to-Deep-Learning
This repository contains scripts to get started with Deep Learning. Apart for the low level implementation, it also contains implementations of the various Neural network architectures using the keras libraries. All the scripts use Tensorflow 2.x

## MLP

* 'mlp_with_relu': low level implemetation of a multilayer perceptron. 
* 'error_tracking': few failed scripts and their visualization using tensorboard. Visualizing the learning progress as well as the behavior of a deep model is extremely useful (if not necessary) for troubleshooting in case of unexpected outcomes (or just bad results). Here, TensorBoard, Tensorflow’s built-in visualization suite is used to diagnose some common problems with training deep models. 
* 'Tensorflowcore': various small programming tasks solved using Tensorflow functions.

## CNN

* 'cnn': CNN (built with Keras) using the Keras losses, optimizers and metrics. It is trained on MNIST and CIFAR10. It contains various observations noticed while playing with the model parameters.
* 'cnn_densenet': implementation of the famous DenseNet architecture. It includes computation graphs that Tensorflow uses internally in TensorBoard. The computation graphs are obtained by tracing computations explicitly. 

## RNN

* 'RNN': low-level implementation of RNN (trained with a custom loop) and a sequence generator from this trained network. The RNN is trained on the 'shakespeare.txt' corpus and generates sequences similar to shakespeare's writings. 
* 'RNN_lstm': lstm that can be trained on variable-length sequences with custom masking of the loss and the loss aggregation. It is then used to sample variable length sequences. 



