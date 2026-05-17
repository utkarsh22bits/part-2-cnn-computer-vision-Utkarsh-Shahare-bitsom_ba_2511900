#part-2-cnn-computer-vision-formulation-and-CNN-prototype-Utkarsh-Shahare-bitsom_ba_2511900

## Overview
CNN-based image classifier to detect surface defects in manufactured products.

## Results
- Test Accuracy: 98.96%
- F1-Score: 0.99 across all classes

## CNN Concepts

**What is Convolution?**
Convolution is a process where the CNN scans small parts of an image to detect features like edges, shapes, and textures. It helps the model understand patterns in images.

**Why is Pooling Used?**
Pooling reduces the size of the image data while keeping important features. This makes the model faster and helps reduce overfitting.

**Why is ReLU Commonly Used in CNNs?**
ReLU (Rectified Linear Unit) is an activation function that changes negative values to zero. It helps the model learn complex patterns faster and improves training speed.

**Why are CNNs Better than Regular Feed-Forward Networks for Images?**
CNNs are designed specifically for image data. They can automatically detect important visual features and preserve spatial relationships in images, while regular neural networks treat all pixels independently and require many more parameters.

**Why CNNs over regular networks?** CNNs use shared weights through convolution, dramatically reducing parameters. They also preserve spatial relationships between pixels, which regular networks ignore by flattening images.

## Business Use Case: Manufacturing Quality Control
This CNN can be deployed on a production line to automatically inspect products for surface defects. A camera captures images of each product; the model classifies them as normal or defective (dent/scratch/stain). This reduces manual inspection costs and improves detection speed and consistency.


