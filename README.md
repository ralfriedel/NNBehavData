# NNBehavData
Data used to generate results for the paper "Unraveling the black-box: exploring the accretion during training of influential neural network nodes as a means toward transparency"

NNBehaviorData: training data for reference
NNBehaviorFigs: code and data to generate figures.

## Abstract

The growing complexity of the artificial intelligence field has led to broad research toward neural network transparency, much of it focused on manipulating input data to evaluate its effects on the output, or on model pruning following an often lengthy and time-consuming training process. This study investigates the behavior of neural network nodes, the fundamental units of neural networks, during training to gain insight into node patterns for a better understanding of the inner workings of neural networks, thus assisting in model transparency possibly through simplification. Herein, node positional stability, defined as the number of epochs during which node weights maintained their absolute value rank, was the variable of investigation. To test node behavior, the study used a manipulated and two biological data sets, run on convolutional neural network (CNN) and deep neural network (DNN) models. To assess model simplification efficiency, simplification based on positional stability was compared against the exponential decay method using the MNIST publicly available data set. The results suggested neural network progress toward stabilization varying by model, with CNNs adding nodes influential to model accuracy more evenly during training. The positional stability approach also demonstrated superior time efficiency in model simplification, especially for DNN models.
