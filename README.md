# Advanced-GAN-Architectures-for-Image-Dehazing

## Project Overview
This project aims to compare advanced Generative Adversarial Network (GAN) architectures, specifically the traditional GAN and the Wasserstein GAN (WGAN), for the task of image dehazing. The study focuses on how these models perform in both synthetic and real-world hazy image scenarios.

## Motivation:
Haze is a common environmental phenomenon that significantly impairs image quality, leading to reduced visibility. This project explores how modern deep learning techniques, like GANs, can be applied to enhance image clarity by effectively removing haze. The potential applications span across domains such as security surveillance, autonomous vehicles, and satellite imagery.

## Methodology
The project involves building and training two GAN architectures: a traditional GAN and a WGAN. Both models are tested on benchmark datasets containing synthetic and real-world hazy images. The evaluation is conducted both quantitatively (using metrics like PSNR and SSIM) and qualitatively by visually inspecting the results.

## GAN Models:
1. GAN: A traditional GAN architecture is used to generate haze-free images by learning the mapping between hazy and clear images.
2. WGAN: An enhanced version of GAN that minimizes the Wasserstein distance, offering more stable training and superior performance in generating high-quality dehazed images.

## Dataset:
1. Synthetic Data: Created using the NYU Depth V2 and Make3D datasets, providing depth information to simulate hazy conditions.
2. Real-World Data: The O-Haze dataset is used, which contains real-world hazy images along with their haze-free ground truth for comparison.

## Results
The models were evaluated based on the following metrics:
1. Peak Signal-to-Noise Ratio (PSNR): Measures the quality of the dehazed images.
2. Structural Similarity Index (SSIM): Assesses the similarity between the dehazed and original images.
   
## Key Findings:
WGAN outperforms traditional GAN, delivering clearer, more natural dehazed images.
The incorporation of a patch-wise discriminator in WGAN helps reduce artifacts, improving the overall visual quality of the dehazed images.


