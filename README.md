# Image Classification Using Transfer Learning 

This project aims to develop an image classification model using transfer learning techniques with TensorFlow and Keras. Transfer learning involves leveraging pre-trained neural network models and fine-tuning them to suit specific tasks, reducing the need for training from scratch and improving efficiency.

## Key Features:

### Dataset: 
The dataset used in this project comprises 12500 images each of cats and dogs, totaling 25000 images.

### Pre-processing: 
Images were resized to 224x224 pixels and standardized to ensure uniformity in input dimensions.

### Model Architecture: 
The MobileNet V2 pre-trained model, available via TensorFlow Hub, was employed as the base model. This model was augmented with a dense output layer for binary classification (cats vs. dogs).

### Training: 
The model was trained on a sampled set of 2000 images, achieving an accuracy of 97.2% on the test set.

### Evaluation: 
Evaluation metrics included loss and accuracy computed during model training and testing phases.

### Predictive System: 
The trained model was integrated into a predictive system capable of classifying input images as either cats or dogs with high accuracy.

Special thanks to Siddharthan for providing me with the resources and knowledge that facilitated the development of this project.
