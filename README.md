# Tensorflow-Datasets

The beauty of TensorFlow is in its simplicity. Basically, all we need to do is implement forward propagation through a computational graph. TensorFlow will compute the derivatives for us, by moving backwards through the graph recorded with GradientTape. All that's left for  to do then, is specify the cost function and optimizers.

When writing a TensorFlow program, the main object to get used and transformed is the tf.Tensor. These tensors are the TensorFlow equivalent of Numpy arrays, i.e. multidimensional arrays of a given data type that also contain information about the computational graph.

Here we have used Fashion Mnist Dataset that is available on the tensorflow dataset. 

We intend to implent following things, build a neural network using TensorFlow. Remember that there are two parts to implementing a TensorFlow model:

- Implement forward propagation and let tensorflow handle the backward propagation
- Retrieve the gradients and train the model
