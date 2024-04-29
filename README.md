# Quark/Gluon Event Analysis

## Dataset

The dataset consists of data regarding Quark/Gluon jet events. It includes three channels: ECAL, HCAL and Tracks, each containing 125x125 images.

Dataset Download Link: <a href="https://drive.google.com/file/d/1WO2K-SfU2dntGU4Bb3IYBp9Rh7rtTYEr/view?usp=sharing">Quark/Gluon Jet Event Dataset</a>

## Jets as Graphs

Solving the classification of jets using the simple graph convolution network from the PyTorch Geometric examples. The graph representations were constructed from the images converted to point clouds by considering only the non-zero pixels for each event.

## Auto-encoder of the Quark/Gluon Events

The auto-encoder learns representations based on the three image channels - "Tracks", "ECAL", "HCAL".

### Sample 0

![](imgs/0.png)
![](imgs/1.png)

### Sample 1

![](imgs/2.png)
![](imgs/3.png)

### Sample 2

![](imgs/4.png)
![](imgs/5.png)

### Sample 3

![](imgs/6.png)
![](imgs/7.png)

## Sample 4

![](imgs/8.png)
![](imgs/9.png)
