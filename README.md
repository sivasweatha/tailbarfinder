# Tailbar Finder

Tailbar Finder uses Keras to identify tailbars ([bottoming and topping](https://static.incrediblecharts.com/images/png_images/candle_shadow_tail.png) tails). This is to be integrated with a charting system that plots the candles to use it in real-time.

### Model

The model is built using a Sequential model from Keras. This involves stacking layers of neural networks one over the other. The output from one layer is input to the next layer.

### Activation Function

This is a function that determines the output from the layers which would be feed to the next layer as input.

ReLU, a simple mathematical function, is used, which is the commonly used activation function for image classification. It deals with vanishing gradient problem where the loss function becomes so small, the earlier layers no longer learn anything meaningful.

### Optimizer

Optimizer is the function that adjusts the weights to decrease the loss function. This way the model learns and performes better.

Adam, known for its ability to dynamically adjust the learning rate based on the first and second moments of the gradient, is the optimizer used.

## Usage

1. The `data` folder contains some tailbar images. The dataset needs to be larger for this to be used.
2. This does not contain the charting system. So it is not trading ready yet.

## References

[This](https://www.tensorflow.org/tutorials/images/classification) tutorial from TensorFlow was my reference.