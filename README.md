# AIvians
### A GAN Birds Generator

A Generative Adversarial Network (GAN) implementation for generating bird images using PyTorch.

## Overview

This project implements a GAN to generate synthetic bird images. It consists of two neural networks:
- Generator (netg): Creates synthetic bird images from random noise
- Discriminator (netd): Distinguishes between real and generated bird images

## Requirements

- PyTorch
- Google Drive (for model storage)
- GPU support recommended

## Model Storage

The trained models are saved to Google Drive:
- Generator model: `/content/drive/MyDrive/datasets/netg`
- Discriminator model: `/content/drive/MyDrive/datasets/netd`

## Usage

1. Mount Google Drive
2. Load the required dependencies
3. Train the GAN model
4. Generate new bird images using the trained generator

## Model Architecture

The implementation uses:
- Generator: Creates synthetic images from random noise
- Discriminator: Binary classifier to distinguish real/fake images
- Training loop with adversarial loss functions

## Save/Load Models

Models are automatically saved to Google Drive for later use or transfer learning.
