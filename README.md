# Neural Style Transfer

This repository contains the implementation of a Neural Style Transfer model that applies the artistic style of one image to the content of another image using deep learning techniques.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [Examples](#examples)
- [Project Structure](#project-structure)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction
Neural Style Transfer is a technique in deep learning where the style of one image is applied to the content of another image to create a new, stylized image. This project uses a pre-trained convolutional neural network (CNN) to achieve this transfer by minimizing the content and style loss functions.

## Features
- Transfer artistic styles from a style image to a content image.
- Use pre-trained VGG19 network for feature extraction.
- Customize the level of style and content blending.
- Supports high-resolution images.


### Arguments
- `--content_image`: Path to the content image.
- `--style_image`: Path to the style image.
- `--output_image`: Path to save the output image.
- `--iterations`: Number of iterations for optimization (default: 1000).
## Examples
Here are some examples of the Neural Style Transfer results:

|[example](download (1).png) |

## Acknowledgements – 
This project uses the VGG19 model pre-trained on the ImageNet dataset. 
- Inspired by the original Neural Style Transfer paper by Gatys et al.
