# Classify-images-with-Conv2D-neural-network
Classify images with Conv2D neural  network with accuracy 80 % and good fitting 

Conv2D is a kind of neural network made to train pictures 
I use this kind of neural network to classify 10 class
Been used LeNet with some customization in parameters
optimizer = Adam with learning rate 0.0001 

Been used 100 epocks 

This layer creates a convolution kernel that is convolved with the layer input to produce a tensor of outputs. If use_bias is True, a bias vector is created and added to the outputs. Finally, if activation is not None, it is applied to the outputs as well.

When using this layer as the first layer in a model, provide the keyword argument input_shape (tuple of integers or None, does not include the sample axis), e.g. input_shape=(128, 128, 3) for 128x128 RGB pictures in data_format="channels_last". You can use None when a dimension has variable size.
