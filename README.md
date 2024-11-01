# Neural Style Transfer Project

## Overview and Goal
This project implements neural style transfer techniques, inspired by the paper [A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576). The objective is to blend the artistic style of one image with the content of another, creating a visually compelling result that merges elements from both images. Using the VGG network as a feature extractor, this project reconstructs artistic styles in a way that mimics the work detailed in the referenced paper.

---

## Dependencies
To run this project, you’ll need:
- Python 3.x
- Jupyter Notebook
- Required Python libraries:
  ```bash
  pip install torch torchvision opencv-python numpy matplotlib
  ```
---

## Usage and File Description

- **nueral_style_transform.ipynb**: The primary notebook that implements neural style transfer, using deep learning techniques and the VGG model as a feature extractor.
- **vgg.ipynb** : A supporting notebook focused on loading and visualizing VGG network layers, used in feature extraction for style transfer.

