# Comparison_of_Libraries_for_Training_SNN

## About

This repository provides a comparison of different libraries for the possible application of training tasks for spiking neural networks. In total, three several libraries will be compared: [TensorFlow](https://www.tensorflow.org/), [Norse](https://github.com/norse/norse), ...

## Target task

We will use a simple cognitive task: DM (decision-making task). This task consists of two stages:
1. In the first stage, the network must receive an incentive.
2. In the second stage, the network generates a response.

For simplicity, we use a reduced version of the task, which will consist in the fact that the network must compare the value of the signal with a certain threshold.

## Neural network

We will use the network, which consists of LIF neurons. 

![Structure of network](./docs/images/sheme.png)

<p align="center">
<img src="./docs/images/neuron_equation.png" width="348">
</p>
 
