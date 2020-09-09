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
### Denoising Autoencoder
