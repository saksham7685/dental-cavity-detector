# Dental Cavity Detection using Mask R-CNN
This project implements a Mask R-CNN model to detect and segment dental cavities in X-ray images. The model is fine-tuned on a custom dataset of dental X-rays and their corresponding cavity masks to perform instance segmentation.

## 🚀 Features
Instance Segmentation: Detects individual cavity instances and provides precise pixel-level masks for each.
Pre-trained Model: Leverages a pre-trained Mask R-CNN with a ResNet50-FPNv2 backbone for robust feature extraction and faster convergence.
Custom Dataset Handling: Includes a custom PyTorch Dataset to load images and their masks, generating bounding box and instance mask targets.
Training Loop: Provides a complete training pipeline with an SGD optimizer and StepLR scheduler.
Prediction Visualization: Offers a utility to visualize model predictions (bounding boxes and masks) on new images.
## 🛠️ Technologies Used
Python 3.x
PyTorch and Torchvision (for model, dataset, and transforms)
Pillow (PIL)
NumPy
OpenCV (cv2) (for mask processing and contour detection)
Matplotlib (for visualization)
