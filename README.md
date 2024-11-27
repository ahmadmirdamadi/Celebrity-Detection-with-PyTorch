# Celebrity Face Classification using EfficientNet and PyTorch

This project is a celebrity face classification system that uses a deep learning model to classify images of celebrities into predefined classes. The model leverages EfficientNet-B0 (a pretrained convolutional neural network) for feature extraction and fine-tunes it for classification.

## Features
- <b> Pretrained Model: </b> Uses EfficientNet-B0 pretrained on ImageNet.
- <b> Image Augmentation: </b> Applies rotation, flipping, and color jitter for better generalization.
- <b> Fine-Tuning: </b> Freezes lower layers of the pretrained model and trains higher layers for celebrity classification.
- <b> Confidence Scores: </b> Outputs the class along with a confidence percentage.

Each folder name corresponds to a class label.
Images in each folder are used for training and validation.
Requirements
Before running the code, ensure you have the following libraries installed:

- Python >= 3.7
- PyTorch >= 1.9
- torchvision >= 0.10
- Pillow
- matplotlib
- numpy

>- <b> Data: </b> https://drive.google.com/file/d/1FfZfpOl292h9GUj5M_Zf0uc9pwPB0RzY/view?usp=sharing
>- <b> Source: </b> https://www.kaggle.com/datasets/vishesh1412/celebrity-face-image-dataset
