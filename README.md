# Generative-modelling-case-study-GANs-
# Pathology Simulation with GANs using MedMNIST

This project explores the use of Generative Adversarial Networks (GANs) to generate synthetic medical pathology images using the [PathMNIST](https://medmnist.com) dataset. It includes both basic and conditional GAN models built with PyTorch, evaluated using visual and training-based metrics.

---

## Project Structure

---

## Part 1: GAN on 2D Synthetic Data

- Implemented a GAN from scratch
- Trained on:
  - Sine Wave (y = sin(x))
  - Spiral Data (parametric)
- Compared basic and modified architectures (deeper networks, activations)
- Visualized real vs generated samples and loss curves

---

## Part 2: GAN on PathMNIST

- Used MedMNIST's `PathMNIST` (3×28×28, 9-class)
- Trained:
  - **DCGAN** for general image synthesis
  - **Conditional GAN (cGAN)** to generate class-specific tissue samples
- Visualized generated images and class-conditional outputs
- Loss curves tracked during training
- Evaluated realism through side-by-side visual comparison

---

## Installation & Setup

### Requirements
- Python 3.8+
- `torch`, `torchvision`
- `matplotlib`, `numpy`
- `medmnist`

### Install packages
pip install torch torchvision matplotlib numpy medmnist
## Run Part 1 (2D synthetic data)
python part1_synthetic_gan.py
python part2_dcgan_cgan_pathmnist.py
## Run Part 2 (PathMNIST)
# Outputs
Real vs Generated Samples (Sine & Spiral)

DCGAN Sample Images from PathMNIST

cGAN Class-Conditional Samples (e.g., lymphocytes, cancer)

Generator/Discriminator Loss Plots

# References
Goodfellow et al., 2014. Generative Adversarial Networks
Radford et al., 2016. Unsupervised Representation Learning with DCGAN
Mirza & Osindero, 2014. Conditional GANs
Yang et al., 2023. MedMNIST v2 Benchmark
MedMNIST Homepage: https://medmnist.com
PyTorch Documentation: https://pytorch.org





