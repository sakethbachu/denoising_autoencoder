# Denoising Autoencoder

## Description
### Autoencoder
* An autoencoder is a type of artificial neural network used to learn efficient data codings in an unsupervised manner. 
* The aim of an autoencoder is to learn a representation (encoding) for a set of data, typically for dimensionality reduction, by training the network to ignore signal “noise”.
* It has one encoding and a decoding function.
* <img src="https://render.githubusercontent.com/render/math?math=\large h = g(Wx_{i} %2B  b)"> 

* <img src="https://render.githubusercontent.com/render/math?math=\large x^'_{i} = f(W^*h_{i} %2B  c)"> 
* Where g is the encoding function and f is the decoding function.
* The encoding and decoding is done in order to take the most important things that represents the input.
* The below given image represents an autoencoder.
![alt text](https://github.com/sakethbachu/denoising_autoencoder/blob/master/img/autoencoder.png)

### Denoising Autoencoder
* There is always a risk that the autoencoders learn the identity function.
* Denoising autoencoder solves this problem by corrupting the input images by adding noise in them.
* And also other ways of corrupting is by randomly turning some of the input values to zero.
* When calculating the Loss function, it is important to compare the output values with the original input, not with the corrupted input.
* That way, the risk of learning the identity function instead of extracting features is eliminated.
* The below given images represents the gaussian noise that is added, the left one is a random image without noise and the right one is with noise.

![alt text](https://github.com/sakethbachu/denoising_autoencoder/blob/master/img/without%20noise.jpg)&nbsp;&nbsp;&nbsp;![alt text](https://github.com/sakethbachu/denoising_autoencoder/blob/master/img/with%20noise.jpg)

* The below given image describes another type of noise called the speckle noise.
![alt text](https://github.com/sakethbachu/denoising_autoencoder/blob/master/img/speckle%20noise.jpg)

## Methods

## Features

## Demo

## Usage

## Requirements
