CIFAR-10 Image Classification: CNN & Transfer Learning
🚀 Project Overview

A deep learning project to classify images from the CIFAR-10 dataset using:

Custom Convolutional Neural Network (CNN)

Transfer Learning with VGG16

Data augmentation to improve generalization

Fine-tuning pre-trained models

Evaluation with accuracy, confusion matrices, and classification reports

📊 Dataset

CIFAR-10:

60,000 32x32 RGB images

10 classes: airplane, car, bird, cat, deer, dog, frog, horse, ship, truck

50,000 training images, 10,000 test images

🛠 Models
Custom CNN

Conv2D + ReLU

BatchNormalization + MaxPooling

Dropout for regularization

Dense layers for classification

Optimizer: Adam

Loss: Sparse Categorical Crossentropy

Transfer Learning: VGG16

Pre-trained on ImageNet

Custom top classifier added

Base layers frozen initially, fine-tuning applied later

📈 Results

CNN: ~77–78% validation accuracy

VGG16: Lower accuracy on small 32x32 images

Fine-tuning improves performance but depends on input resolution

Visualization includes:

Accuracy & loss curves

Confusion matrices

Sample predictions (green = correct, red = incorrect)
