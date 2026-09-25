# Variational Autoencoder — Hackathon Project

Machine learning hackathon project focused on generative modeling using a
**Variational Autoencoder (VAE)** implemented in PyTorch.

The goal was to learn a latent representation of the **SVHN (Street View House Numbers)**
dataset and generate new labeled digit images. The generated samples were evaluated
using a pretrained classifier.

## Approach

The model consists of a convolutional encoder and decoder implementing a Variational
Autoencoder. Images are mapped to a probabilistic latent representation and reconstructed
or sampled to generate new digit images.

The project includes:

- Convolutional VAE architecture
- Latent-space sampling
- Training on the SVHN dataset
- Generation of labeled digit images
- Visualization of generated samples
- Evaluation using a pretrained image classifier

## Technologies

Python · PyTorch · torchvision · NumPy · Matplotlib

## Team

Gian Lampert · Olle

## Files

`Final_Evaluation.ipynb` — VAE architecture, image generation, visualization, and evaluation.

## Note

The original datasets and trained model checkpoints are not included in this repository.
