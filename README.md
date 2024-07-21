# Dog vs Cat Image Classification

This project aims to predict whether a photo presents a dog or a cat. The model uses **Convolutional Neural Networks (CNNs)** to perform the classification. This project covers the area of **computer vision**.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Project Structure](#project-structure)
3. [Data Description](#data-description)
4. [Evaluation](#evaluation)
5. [Tools](#tools)
6. [Contributing](#contributing)
7. [License](#license)

## Project Overview
The goal of this project is to classify images as either containing a dog or a cat. To achieve this, we employ a Convolutional Neural Network (CNN), a type of deep learning model particularly well-suited for image classification tasks.

## Project Structure
The project consists of the following files:
- `code.ipynb`: Jupyter notebook containing the code for data preprocessing, model training, and evaluation.
- `data`: To run the model you will have to download the data from my Google Drive ([link](https://drive.google.com/file/d/1cFf_cUO8rYcsD_ZAn2huTIdN4RckI7ln/view?usp=sharing)) and place it in the folder which contains the 'code.ipynb' file.

## Data Description
The dataset used in this project consists of images of dogs and cats. Each image is labeled accordingly to indicate whether it contains a dog or a cat. The data is preprocessed and augmented to improve the model's performance.

## Evaluation
The performance of the model is evaluated using the following metrics:
- **Accuracy**: 92.17%, means that 92.17% of images are correctly classified. 

## Tools
The following statistical and machine learning techniques are used in this project:
- **Train-Test Split**: To divide the dataset into training and testing sets.
- **Convolutional Layer (Conv2D)**: To extract features from the images.
- **Max Pooling (MaxPooling2D)**: To reduce the dimensionality of the feature maps.
- **Flatten Layer**: To convert the 2D feature maps into a 1D vector.
- **Dense Layer**: To perform the final classification.
- **Adam Optimizer**: To optimize the model during training.
- **Binary Crossentropy Loss**: To calculate the error during training.
- **Accuracy Metric**: To evaluate the performance of the model.

## Contributing
Contributions are welcome! Please do not hesitate to contact me on LinkedIn!

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
