# Diffusion Models Project
![Diffusion Models](https://img.shields.io/badge/🌫️%20Diffusion%20Models-blue?style=for-the-badge&logo=cloud&logoColor=white)
![Python](https://img.shields.io/badge/🐍%20Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/🔥%20PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![U-Net](https://img.shields.io/badge/🧠%20U--Net-critical?style=for-the-badge&logo=data:image/png;base64&logoColor=white)
![Sinusoidal Embeddings](https://img.shields.io/badge/⏳%20Sinusoidal%20Embeddings-yellow?style=for-the-badge&logo=wave&logoColor=white)
![Image Generation](https://img.shields.io/badge/🖼️%20Image%20Generation-orange?style=for-the-badge&logo=image&logoColor=white)
![DDPM](https://img.shields.io/badge/🔄%20DDPM-green?style=for-the-badge&logo=data:image/png;base64&logoColor=white)
![Data Augmentation](https://img.shields.io/badge/📊%20Data%20Augmentation-red?style=for-the-badge&logo=augmentation&logoColor=white)
![Generative AI](https://img.shields.io/badge/🤖%20Generative%20AI-purple?style=for-the-badge&logo=artificial-intelligence&logoColor=white)
![MIT License](https://img.shields.io/badge/📜%20License-lightgrey?style=for-the-badge&logo=open-source-initiative&logoColor=black)
## Overview

The `diffusion_models` project offers a cutting-edge Python implementation of Denoising Diffusion Probabilistic Models (DDPMs), a prominent class of machine learning models designed for generating high-quality data. By mastering the art of reversing the diffusion process, this project stands at the forefront of image generation and data augmentation technologies. Aimed at researchers, developers, and hobbyists alike, `diffusion_models` provides comprehensive tools for training, evaluating, and deploying diffusion models across various applications.

## Features

- **State-of-the-Art Generation**: Utilize DDPMs for creating detailed, high-quality images from noise.
- **Custom Architecture Support**: Includes a customizable U-Net-like architecture for versatile model design.
- **Advanced Conditioning**: Leverages sinusoidal positional embeddings for precise time-step conditioning.
- **Extensive Evaluation Toolkit**: Offers robust tools for model testing and performance assessment.
- **Diverse Application Potential**: Ideal for tasks ranging from image synthesis to sophisticated data augmentation.

## Visual Demonstrations

Observe the remarkable capability of DDPMs to transform noise into detailed images through these stages:

| Noise Level | Visualization |
|-------------|---------------|
| 25% Noise | ![DDPM Noisy images 25%](noisy_image_25.png) |
| 50% Noise | ![DDPM Noisy images 50%](noisy_image_50.png) |
| 75% Noise | ![DDPM Noisy images 75%](noisy_image_75.png) |
| 100% Noise | ![DDPM Noisy images 100%](noisy_image_100.png) |
| Original Images | ![Original images](original_image.png) |

## Getting Started

## Usage
To run a diffusion model, use the following command:
[Code](diffusion_models.py)

## Acknowledgements

Special thanks to the original authors of the DDPM paper, [Ho et al.](https://arxiv.org/abs/2006.11239), for their groundbreaking work in the field. This project is inspired by their research and contributions to generative modeling.

### Installation

Clone the repository and install dependencies to get started with `diffusion_models`:

```bash
git clone https://github.com/chikap421/diffusion_models.git
cd diffusion_models
pip install -r requirements.txt
```

