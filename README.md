# Introduction-to-Deep-Learning
This repository contains scripts to get started with Deep Learning. Apart for the low level implementation, it also contains implementations of the various Neural network architectures using the keras libraries. All the scripts use Tensorflow 2.x

MLP
 Markup : * Bullet list
This folder contains low level implemetation of a multilayer perceptron. 
Further it also contains few failed scripts and their visualization using tensorboard. Visualizing the learning progress as well as the behavior of a deep model is extremely useful (if not necessary) for troubleshooting in case of unexpected outcomes (or just bad results). Here, TensorBoard, Tensorflow’s built-in visualization suite is used to diagnose some common problems with training deep models. 
The file Tensorflowcore contains various small programming tasks solved using Tensorflow functions.

The CNN folder contains a CNN (built with Keras) using the Keras losses, optimizers and metrics. It is trained on MNIST and CIFAR10. It contains various observations noticed while playing with the model parameters. Apart from that it also contains an implementation of the famous DenseNet architecture. It also includes computation graphs that Tensorflow uses internally in TensorBoard. The computation graphs are obtained by tracing computations explicitly. 

The RNN folder consists of low-level implementation of RNN (trained with a custom loop) and sequence generator from this trained network. This RNN is trained on the 'shakespeare.txt' corpus and generates sequences similar to how shakespeare's writings. The second script in the folder is an implementation of RNN that can be trained on variable-length sequences with custom masking of the loss and the loss aggregation. It is then used to sample variable length sequences. 



