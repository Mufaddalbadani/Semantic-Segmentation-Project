# 🛣️:Semantic-Segmentation-Project

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Overview**
In this project we will be doing semantic image segmentation using a pre-trained model available in Tensorflow-Hub.
The primary goal of TensorFlow Hub is to simplify the process of reusing existing models, thereby promoting collaboration, reducing redundant work, and accelerating research and development in machine learning. Users can search for pre-trained models, called modules, that have been contributed by the community or provided by Google. These modules can be easily integrated into a user's own machine learning projects with just a few lines of code.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Model**
Tensorflow has many different pre-trained model, here I have used High-Resolution Network (HRNet) segmentation model trained on CamVid (camvid-hrnetv2-w48)
The model has been pre-trained on the Imagenet ILSVRC classification task and fine-tuned on CamVid.
model_url = "https://tfhub.dev/google/HRNet/camvid-hrnetv2-w48/1"

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 🟢:Project Overview

1. **Initialize Model and Load Pre-trained Weights:**:- Define the pre-trained model URL or file path. | Load the pre-trained semantic segmentation model using a deep learning framework (e.g., TensorFlow, PyTorch).
2. **Load and Preprocess Images:**:- Specify the directory containing the input images for segmentation. | Use a convenience function to load and preprocess images, ensuring proper resizing and normalization.
3. **Define Class Index**:- Define a class index mapping class IDs to RGB color labels. | This mapping will be used to convert model output to a color-coded segmentation mask.
4. **Run Inference (Forward Pass)**:-Iterate through the preprocessed images. | Use the pre-trained model to perform a forward pass and obtain segmentation masks. | Remove any background class if added by the model.
5. **Visualize Results**:-Create a visualization function to display the original image, predicted segmentation mask, and an overlay of the mask on the original image.
6. **Advancements/Updates**:- **Adjust Parameters and Fine-tuning**:- Hyperparameters and post-processing techniques to improve the segmentation performance.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Output**

The image below showcases the predicted mask of road and sky in the image. Displays how well the model segments diffrent classes.
![Asset 2](https://github.com/Mufaddalbadani/Image-Segmentation-Project/assets/62328487/099c85e1-4ad8-4d60-99a9-ef844a702ef6)

This image below shocases the grayscale segmentation and color segmentation for the image. Diffrent colors represent diffrent classes
![Asset 2 (2)](https://github.com/Mufaddalbadani/Image-Segmentation-Project/assets/62328487/82c95022-ca9f-424c-959c-1b26cab73a98)

The image below showcases the colored predicted mask and ovelay of the predicted mask on the original image.
![Asset 7](https://github.com/Mufaddalbadani/Image-Segmentation-Project/assets/62328487/21a201e2-7564-435a-b96b-3ab7f921976b)

