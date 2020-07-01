**Materials for the supervised tutorial at EEML 2020**

**Authors**: Viorica Patraucean and Carl Doersch

**Description**:
In supervised learning, we are given a dataset with many pairs of inputs and outputs and the goal is to find a (approximate) function which maps each input to the correct output for the examples in that dataset. The hope is that the function would generalize to new examples: i.e., it produces the correct output even for inputs that weren't available while we were searching for the function. In this tutorial, we will focus on how supervised learning is used in computer vision to classify what object is depicted in an image. We'll start with a standard neural network (Resnet-18) as a baseline and we'll train it on CIFAR10 dataset. Next, we'll examine how this process can fail through adversarial examples: images that have been manipulated in ways that are almost invisible to humans, but cause large changes in the network output. Finally, we will look at self-attention and its ability to improve generalization. Specifically, we will implement a recent self-attention module called Squeeze-and-Excitation. All exercises will be implemented using Jax and haiku.
