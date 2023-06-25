# ImageClassification

This code demonstrates a simple image classification task using TensorFlow and Keras. The dataset used for training and validation is the "Cats and Dogs" dataset obtained from Kaggle.

## Dataset

The dataset used for this project can be downloaded from the following link:

[Cat and Dog Dataset](https://download.microsoft.com/download/3/E/1/3E1C3F21-ECDB-4869-8368-6DEBA77B919F/kagglecatsanddogs_5340.zip)

After downloading the dataset, extract the contents into a folder named "PetImages". Make sure the dataset contains two subfolders named "Cat" and "Dog", which contain images of cats and dogs, respectively.

## Removing Corrupted Images

Some images in the dataset might be corrupted or improperly formatted. Before training the model, this code removes such corrupted images from the dataset.

## Model Training

The code uses TensorFlow's `image_dataset_from_directory` function to generate training and validation datasets. The images are resized to (180, 180) pixels and batched with a batch size of 128.

## Visualization

The code includes a visualization step to show a sample of the training dataset. It plots a 3x3 grid of images with their corresponding labels.

## Prerequisites

- Python 3.x
- TensorFlow
- Keras
- Matplotlib

## Usage

1. Download the dataset from the provided link and extract it into a folder named "PetImages".
2. Ensure the necessary dependencies are installed (TensorFlow, Keras, Matplotlib).
3. Run the code using a Python interpreter or IDE.
4. Monitor the training progress and observe the visualization of the dataset.

Note: Make sure to adjust the code and its parameters according to your specific requirements, such as changing the image size, batch size, or model architecture.

