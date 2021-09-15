# Image-Classification

I have used a convolutional network to produce a meaningful representation of flower images,
that would then be fed to a clustering algorithm for separation. In order for the convolutional
network to generalise the images, I intend to use pre-trained networks such as VGG19 with
weights based on ImageNet classification. Since these are world leading networks in
classification accuracy, it is possible to assume that they are able to detect patterns in images
well. The top fully connected layer of these classifiers would be removed so that the clustering
algorithm can have direct access to the representations built by the convolutional network.
Different clustering algorithms are then compared in order to arrive at the best model.
