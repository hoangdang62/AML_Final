# Image Retrieval System
![ImageSearch](https://user-images.githubusercontent.com/89981980/148706285-c6d022b7-4a63-4991-800a-a9992759caea.gif)

The training dataset consisted of 10,000 sample images of size 224 x 224. For every image, there is are five descriptions and feature vectors extracted from the fc1000 layer of a state-of-the-art deep convoluted neural network (ResNet).  
The descriptions were converted to vectors using the word2vec algorithm, then mapped to the feature vectors of the images using Ridge regression.
