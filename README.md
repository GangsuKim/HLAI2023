# Hallym AI Competition 2023
This repo is code of Hallym AI Competition 2023
> 3rd place of the competition

## System environment
### System 1.
i5-13600KF
24 GB Memory
RTX 3060 with 12GB VRAM 
### System 2.
i7-8700K
16 GB Memory
RTX 3090 with 24GB VRAM

## Models
### Using 2 models
 - ViT-B+ResNet50 (224,224)  
 - Xception 41p
### Using 4 different methods
 - [Method 1](./train/train_vit_base_resnet50_cos.ipynb) - ViT-B+ResNet50  
 - [Method 2](./train/train_vit_base_resnet50d_224_cutMix.ipynb) - ViT-B+ResNet50  
 - [Method 3](./train/train_vit_base_resnet50d_224_cutMix_2.ipynb) - ViT-B+ResNet50
 - [Method 4](./train/train_xception41p.ipynb) - Xception 41p
