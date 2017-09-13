Convolutional Neural Network for MNIST Dataset

The network consists of 2 Convolutional layers and pooling layers, finishing up with 2 dense layers.

Structure of the CNN:
Convolutional Layer #1: Applies 32 5x5 filters (extracting 5x5-pixel subregions), with ReLU activation function
Pooling Layer #1: Performs max pooling with a 2x2 filter and stride of 2 (which specifies that pooled regions do not overlap)
Convolutional Layer #2: Applies 64 5x5 filters, with ReLU activation function
Pooling Layer #2: Again, performs max pooling with a 2x2 filter and stride of 2
Dense Layer #1: 1,024 neurons, with dropout regularization rate of 0.4 (probability of 0.4 that any given element will be dropped during training)
Dense Layer #2 (Logits Layer): 10 neurons, one for each digit target class (0–9).




Creative Commons Attribution 3.0 License of Tensorflow
