# Noise-reduction-with-Autoencoders
This repository is a project I did while I was studying my master in Automation and Robotics. The goal of this project is to study how autoencoders are able to reduce noise in images.

This project is made up of three different jupyter notebooks. The first one is called: autoencoder_mnist. In this notebook, I implemented a simple autoencoder to remove noise (i added this noise to the data) from mnist dataset. The second notebook is called: autoencoder_unet_fer2013. In this second notebook, I changed the dataset from mnist to fer2013. This dataset is made up of images from people with different emotions, so it is more difficult to remove the noise because the images are rgb. Here, I compared the results using the model that I implemented in the first notebook and a Unet model. The last notebook, called unet_cifar, shows the performance of Unet model with cifar dataset.

In this reposiroty, you will also find a kind of summary of the project written in spanish (sorry).
