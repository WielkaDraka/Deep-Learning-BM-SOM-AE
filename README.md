# Neural Network Architectures

This repository provides an overview of various neural network architectures, including Self-Organizing Maps (SOM), Boltzmann Machines, and Autoencoders. Each type of neural network has its unique structure and application areas. Below is a detailed description of each architecture.

## Table of Contents

- [Self-Organizing Maps (SOM)](#self-organizing-maps-som)
- [Boltzmann Machines](#boltzmann-machines)
- [Autoencoders](#autoencoders)

## Self-Organizing Maps (SOM)

Self-Organizing Maps (SOMs) are a type of unsupervised learning network used for clustering and visualizing high-dimensional data.

### Key Features:
- **Topology Preservation:** Maintain the spatial relationships of input data.
- **Competitive Learning:** Neurons compete to respond to a subset of the input data.

### Applications:
- Clustering
- Data visualization
- Dimensionality reduction

## Boltzmann Machines

Boltzmann Machines are stochastic neural networks capable of learning internal representations. They consist of visible and hidden units with symmetric connections.

### Key Features:
- **Energy-Based Model:** The network assigns an energy to each configuration of the variables.
- **Restricted Boltzmann Machines (RBM):** A variant with a restricted topology to facilitate learning.

### Applications:
- Dimensionality reduction
- Collaborative filtering
- Feature learning

## Autoencoders

Autoencoders are unsupervised neural networks used for learning efficient codings of input data. They consist of an encoder and a decoder.

### Key Features:
- **Encoder:** Maps input data to a lower-dimensional latent space.
- **Decoder:** Reconstructs the input data from the latent representation.
- **Loss Function:** Measures the difference between the input and its reconstruction (e.g., Mean Squared Error).

### Applications:
- Data denoising
- Dimensionality reduction
- Anomaly detection

## References

- [Deep Learning by Ian Goodfellow, Yoshua Bengio, and Aaron Courville](https://www.deeplearningbook.org/)
- [Neural Networks and Deep Learning by Michael Nielsen](http://neuralnetworksanddeeplearning.com/)
- [MIT Deep Learning for Self-Driving Cars](http://selfdrivingcars.mit.edu/)

