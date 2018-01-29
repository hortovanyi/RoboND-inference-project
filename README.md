# Robotic Inference
Robotics Nano Degree

[![Udacity - Robotics NanoDegree Program](https://s3-us-west-1.amazonaws.com/udacity-robotics/Extra+Images/RoboND_flag.png)](https://www.udacity.com/robotics)

[//]: # (Written by Nick Hortovanyi Jan 29th 2018)

This project is split into two sections. The first being an inference project against supplied training and test data. It is described under Basic Requirements and Numerical Requirements. With the second section being for a conceptual inference project from captured data. It is documented in the Write Up Requirements section. 

## Basic Requirements

Data was supplied in a hosted environment where students had access to [Nvidia Digits](https://developer.nvidia.com/digits). A google LeNet model was chosen with the Adam optimiser and an initial learning rate of 0.001. 5 epochs were used.

![Training Graph](https://github.com/hortovanyi/RoboND-inference-project/blob/master/output/training_graph.png?raw=true)

The trained model can be found [here](http://localhost:8888/tree/roboticst2/RoboND-inference-project/output/20180128-220532-bf99_epoch_5.0).

A script was supplied to evaluate the trained model. A screen shot of the output follows

![Evaluate Output](https://github.com/hortovanyi/RoboND-inference-project/blob/master/output/Robotics_Software_Engineer_-_Udacity.png?raw=true) 

## Numerical Requirements
All average inference times in the Evaluate output fall below 10 ms.

The accuracy is just greater than 75 % at 75.40984 %
