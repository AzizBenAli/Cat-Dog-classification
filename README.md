 ## Cat and Dog Image Classification
This project focuses on classifying images of cats and dogs using two different models - a custom CNN model and a pre-trained ResNet-50 model. The goal is to compare the performance of these models and select the one that yields the best accuracy.

## Dataset
The dataset used for this project consists of labeled images of cats and dogs. The images are stored in separate folders, one for cats and one for dogs. Due to the large size of the dataset, it is not included in this repository. You can download the dataset from the link below and organize it into the following structure:
'https://www.kaggle.com/competitions/dogs-vs-cats/data'
data/
    train/
        cat/
            cat_image_1.jpg
            cat_image_2.jpg
            ...
        dog/
            dog_image_1.jpg
            dog_image_2.jpg
            ...
    test/
        cat/
            cat_image_1.jpg
            cat_image_2.jpg
            ...
        dog/
            dog_image_1.jpg
            dog_image_2.jpg
            ...
Cat and Dog Image Classification Dataset: Download Link

## Requirements
Python 3.x
PyTorch
torchvision
NumPy
Matplotlib
You can install the required dependencies using pip:

pip install torch torchvision numpy matplotlib

## Custom CNN Model
The first model used for this project is a custom CNN model implemented using PyTorch. The model consists of multiple convolutional and pooling layers, followed by fully connected layers for classification. It has been designed to learn features from the images of cats and dogs and make predictions accordingly.

## Pre-trained ResNet-50 Model
The second model used for this project is the popular ResNet-50 architecture, which has been pre-trained on the ImageNet dataset. We replace the last fully connected layer of ResNet-50 with a custom linear layer having 2 output units to adapt it for our binary-class classification task .

## Usage
First, download the dataset from the provided link and organize it as described above.

Clone this repository to your local machine:

Train and evaluate the custom CNN model

Train and evaluate the pre-trained ResNet-50 model

Compare the performance of both models and select the one with better accuracy for your cat and dog image classification task.
## Contact
If you have any questions or suggestions, feel free to contact me at your.email@example.com.

Happy classifying! 🐱🐶
