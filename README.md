# Semantic-Segmentation-Project

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Overview**
In this project we will be doing semantic image segmentation using a pre-trained model available in Tensorflow-Hub.
The primary goal of TensorFlow Hub is to simplify the process of reusing existing models, thereby promoting collaboration, reducing redundant work, and accelerating research and development in machine learning. Users can search for pre-trained models, called modules, that have been contributed by the community or provided by Google. These modules can be easily integrated into a user's own machine learning projects with just a few lines of code.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Model**
Tensorflow has many different pre-trained model, here I have used High-Resolution Network (HRNet) segmentation model trained on CamVid (camvid-hrnetv2-w48)
The model has been pre-trained on the Imagenet ILSVRC classification task and fine-tuned on CamVid.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Project Overview

1**Initialize Model and Load Pre-trained Weights:**:- Define the pre-trained model URL or file path. | Load the pre-trained semantic segmentation model using a deep learning framework (e.g., TensorFlow, PyTorch).
2.**Load and Preprocess Images:**:- Specify the directory containing the input images for segmentation. | Use a convenience function to load and preprocess images, ensuring proper resizing and normalization.

