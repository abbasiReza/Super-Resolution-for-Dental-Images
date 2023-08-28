# Super Resolution for Dental Images using LTE and MIRNet

## Description

This project applies super resolution models to improve the resolution of dental images.

The LTE and MIRNet models are trained and evaluated on a dataset of dental images collected at Shahid Beheshti University. 

Generating higher resolution dental images can help in procedures like diagnosis, treatment planning etc.

## Models

The following super resolution models are used:

- **LTE** - Learned Texture Encoder model based on a texture encoder-decoder network.

- **MIRNet** - Model with Image Reconstruction Network and Image Regularity Network components.

These models learn to increase image resolution while preserving necessary details.

## Dataset  

- Dental image dataset collected at Shahid Beheshti University
- Contains intraoral X-ray, CT, panoramic X-ray, and photographs  
- Used for training and evaluation of super resolution models

## Training 

The LTE and MIRNet models are trained on downsampled versions of images from the dataset to learn super resolution.

## Evaluation

The models are evaluated on upsampling factors of 2x, 3x and 4x using metrics like PSNR and SSIM.

## Usage

The trained super resolution models can be applied to enhance the resolution of new dental images.

## References

- LTE Paper: https://arxiv.org/abs/2111.08918
- MIRNet Paper: https://arxiv.org/abs/2205.01649
