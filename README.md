# Artificial Intelligence Neuroevolution
# Medical Image Processing
- Author: Jesus Ramseths Echeverria
<hr>

 [Data Source](https://www.kaggle.com/mateuszbuda/lgg-mri-segmentation)

 This project is for educational purposes, if you want to take it to production environments **300, 000** official **MRI** images are required, in addition to evaluate the metrics of each model implemented in this project.

<hr>

## What is image segmentation?

The objective is to understand and extract information from images at the pixel level. It is used for object localization and recognition, some applications are medical imaging and autonomous cars. A neural network is trained to produce a pixel mask.

State-of-the-art techniques are based on a deep learning approach that makes use of common architectures such as **CNN**, **TCN** and **deep encoder-decoders**. The **ResUNet** architecture was used in this project.

### Res-U-Net Architecture
![Res-U-Net Architecture](img/ResUNet-architecture.png)

* [More information](https://aditi-mittal.medium.com/introduction-to-u-net-and-res-net-for-image-segmentation-9afcb432ee2f)
<hr>

## ResNet

As the convolutional neural networks become deeper, gradient fading occurs and affects the performance of the network.

The residual neural network includes the "skip by connection" feature that allows training of 152 layers without problems such as gradient fading.

**ResNet** works by adding identity assignments in the main part of the convolutional neural network.

### ResNet Architecture
![ResNet](img/block.jpg)

* [Feature Extraction and Convolutions](https://setosa.io/ev/image-kernels/)
* [CNN Visualization](https://www.cs.ryerson.ca/~aharley/vis/conv/flat.html)





