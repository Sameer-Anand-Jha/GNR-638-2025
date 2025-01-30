# UCM Bag of Words with Three-Layer MLP

## Group Members
**Neha Shahu** - **24M2159**
**Sameer Anand Jha** - **24M1062**

## Overview

This project aims to apply a **bag of words** feature extraction method on images from the UCM (University of California Merced) dataset and use a three-layer Multi-Layer Perceptron (MLP) to classify the images. The objective is to experiment with various hyperparameters such as the number of nodes in the hidden layers, activation functions, and the downscaling process of images.

## Project Objectives

- **Feature Extraction**: Calculate the Bag of Words (BoW) features from the UCM dataset images.
- **MLP Classifier**: Implement and train a three-layer MLP using the extracted features.
- **Experimentation**: Experiment with different configurations for the number of nodes in the hidden layers, choice of activation functions, etc.
- **Downscaling**: Downscale the images of the UCM dataset to 72x72 pixels, linearize them, and then train another MLP on the downscaled features.
- **Classification Performance**: Report and compare the classification performance for both the original and downscaled image approaches.

## Dataset

The dataset used is the **UCM (University of California Merced) Land Use Dataset**, which contains 21 different land use categories, with each category consisting of 100 images of varying sizes. You can find the dataset [here](http://weegee.vision.ucmerced.edu/datasets/).

## Requirements

- Python 3.7+
- TensorFlow 2.x or PyTorch
- NumPy
- Scikit-learn
- OpenCV or Pillow (for image processing)
- Matplotlib (for plotting results)

You can install the required dependencies using `pip`:

```bash
pip install -r requirements.txt
