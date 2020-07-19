**Materials for the supervised tutorial at EEML 2020**

**Authors**: Viorica Patraucean and Carl Doersch

**Description**:
In supervised learning, we are given a dataset with many pairs of inputs and outputs and the goal is to find a (approximate) function which maps each input to the correct output for the examples in that dataset. The hope is that the function would generalize to new examples: i.e., it produces the correct output even for inputs that weren't available while we were searching for the function. In this tutorial, we will focus on how supervised learning is used in computer vision to classify what object is depicted in an image. We'll start with a standard neural network (Resnet-18) as a baseline and we'll train it on CIFAR10 dataset. Next, we'll examine how this process can fail through adversarial examples: images that have been manipulated in ways that are almost invisible to humans, but cause large changes in the network output. Finally, we will look at self-attention and its ability to improve generalization. Specifically, we will implement a recent self-attention module called Squeeze-and-Excitation. All exercises will be implemented using Jax and haiku.

Designed for education purposes. Please do not distribute without permission. Write at contact@eeml.eu if you have any question.

You are welcome to reuse this material in other courses or schools, but please reach out to contact@eeml.eu if you plan to do so. We would appreciate it if you could acknowledge that the materials come from EEML2020 and give credits to the authors. Also please keep a link in your materials to the original repo, in case updates occur.

MIT License

Copyright (c) 2020 EEML

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
