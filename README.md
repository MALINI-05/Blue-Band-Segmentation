Water Detection using Blue Spectral Band
Overview

This project implements a Convolutional Neural Network (CNN) based semantic segmentation model to detect surface water in satellite imagery using the blue spectral band.
The model performs pixel-wise classification to identify water regions and generates quantitative analysis of water coverage within the image.
This approach is useful for remote sensing applications such as environmental monitoring, flood assessment, and water resource analysis.

Features

Blue-band based water segmentation
Pixel-wise classification: Water / No Water
Surface water percentage estimation
Visual segmentation maps
Bar chart analysis for water distribution
Lightweight CNN architecture suitable for real-time or edge deployments

Methodology

Extract the blue spectral band from satellite images
Preprocess images for model training
Train a CNN-based segmentation model
Generate pixel-level water masks
Compute percentage distribution of water regions
Visualize results using segmentation maps and statistical plots

Technologies Used

Programming

Python
Deep Learning
CNN

Libraries

TensorFlow / PyTorch
OpenCV
NumPy
Matplotlib

Output

The model produces:

Segmented water mask
Water coverage percentage
Visual water distribution maps
Statistical bar chart representation

Applications

Flood monitoring
Surface water mapping
Environmental monitoring
Satellite image analysis

Future Improvements

Multi-spectral water detection using NDWI
Integration with transformer-based vision models
Real-time satellite data processing pipelines
