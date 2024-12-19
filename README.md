# NeRF with InstantNGP

This repository provides an implementation of Neural Radiance Fields (NeRF) based on the method proposed in [Instant Neural Graphics Primitives (InstantNGP)](https://arxiv.org/abs/2201.05989). The code has been streamlined into a notebook format for easy execution on Google Colab or Kaggle.

## Features
- **InstantNGP Implementation**: Leverages the latest techniques for efficient NeRF rendering.
- **Ready-to-Use Notebooks**: Simplifies the setup process, enabling seamless integration with cloud-based platforms.

## Quick Links
- [Research Paper: Instant Neural Graphics Primitives](https://arxiv.org/abs/2201.05989)
- [Kaggle Notebook](https://www.kaggle.com/code/qwerty197/cuda12-1-t4): Preloaded with CUDA 12.1 and optimized for T4 GPUs.

## How to Use
1. **Kaggle**:
   - Open the [Kaggle Notebook](https://www.kaggle.com/code/qwerty197/cuda12-1-t4).
   - Modify Config as the path of the object you want to train.
    ```python
   self.path = "/kaggle/input/nerf-synthetic-dataset/nerf_synthetic/lego"
    ```
   - In Dataset, there has included Nerf Synthetic Dataset and Custom-NeRF (our dataset captured from realworld).
   - Just run all to install dependencies and run the training and see results.
   - Check out other trained model in other version, including video and validation on both datasets.

## Requirements
- **Hardware**: NVIDIA GPU (e.g., T4 or better recommended).
- **Software**:
  - CUDA 12.1. (We just only tested on this version).
  - Dependencies as listed in the notebook.

