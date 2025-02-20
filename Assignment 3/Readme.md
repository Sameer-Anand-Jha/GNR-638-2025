# Assignment 3

## **Neha Shahu** - 24M2159
## **Sameer Anand Jha** - 24M1062

### Objectives

#### _i) Train a CNN for UCMerced Dataset_

#### _ii) Apply Grad-CAM for visualizations_

For task (i) we have used ReLU activations, with softmax at the last layer.  
We observe accuracy around 45% for 10 epochs on test data and almost no changes to the hyperparameters of ImageDataGenerator Function, which improved to ~80% for 90 epochs with some hyperparameter tweaking on test data.  
We also observed that there is no class imbalance in the dataset being used.

For task (ii) CAM implementation, we proceeded with the GradCAM approach.  
Class values are 1 and 15 (Aeroplane, Parking Lot respectively).
We also provide a plot each for number of epochs vs loss and epochs vs accuracy.
