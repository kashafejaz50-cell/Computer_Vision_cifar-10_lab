# CIFAR-10 Mini Image Classifier
## Transfer Learning with ResNet18 and PyTorch

This project builds an image classifier using transfer learning (ResNet18) on the CIFAR-10 mini dataset (5,000 images).
The model is trained to classify 10 object categories such as airplanes, cars, cats, and trucks.

## Results
- Test Accuracy: 75.70%   
- Training time: ~3 minutes per epoch (Kaggle GPU)
- Dataset: CIFAR-10 Mini (5,000 images)

## Model Architecture
- Base Model: ResNet18 (pretrained on ImageNet)
- Method: Transfer Learning (feature extraction)
- Output Classes: 10
- Trainable Parameters: 5,130

## Training Settings
- Epochs: 10
- Batch Size: 32
- Optimizer: Adam (lr=0.001)
- Loss Function: CrossEntropyLoss

  
