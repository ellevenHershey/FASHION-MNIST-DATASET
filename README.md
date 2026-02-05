# FASHION-MNIST-DATASET

This repository is about MNIST fashion dataset.You can explore and run the MNIST dataset code directly in my Google Colab.

## [My Fashion MNIST dataset colab link..](https://colab.research.google.com/drive/1ima0UK2xL9Z99nfRljvNSBzewxOc7TGV?usp=sharing)  

## What is Fashion MNIST dataset? 
The Fashion MNIST is a collection of grayscale images of clothing and accessories, each sized at 28x28 pixels. It has 10 categories such as shirts, trousers, dresses, shoes, and bags. 

| **Label** | **Category** | 
|-----------|--------------| 
| 0         | T-shirt/Top | 
| 1         | Trouser | 
| 2         | Pullover | 
| 3         | Dress | 
| 4         | Coat | 
| 5         | Sandal | 
| 6         | Shirt | 
| 7         | Sneaker | 
| 8         | Bag | 
| 9         | Ankle Boot |

The dataset is widely used in machine learning and computer vision as a benchmark for image classification tasks because it is lightweight yet complex enough to challenge models to recognize subtle differences in shapes and textures. 

-------------------------------------
##  Why do we normalize image pixel values before training? 
Image pixel value are notmalized to scale them between 0 and 1, which helps the neural network learn more efficiently. Normalization improves training speed, stabilizes the learning process, and prevents large input values from negatively affecting the optimization of the model. 

## List the layers used in the neural network and their functions.
#### Flatten Layer: 
Converts the 28x28 image into a one-dimensional arrays so it can be processed by dense layers 
 #### Dense Hidden Layers (ReLU): 
 Learn impostant features and patterns from the image data using nonlinear activation functions. 
 #### Output Dense Layer: 
 Produces raw prediction scores for 10 clothing categories. 
