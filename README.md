# 2D Materials Prediction with Neural Networks

This repository houses a deep learning framework for analyzing and predicting properties of two-dimensional (2D) materials, with a special focus on graphene and related structures. Our project combines advanced neural network architectures with sophisticated image preprocessing techniques to unlock insights into these revolutionary materials.

## Project Overview

### Neural Networks
- Utilizes Convolutional Neural Networks (CNNs) for feature extraction from material structures
- Implements custom layers designed to capture unique characteristics of 2D materials
- Explores transfer learning techniques to leverage knowledge from well-studied materials

### 2D Materials Focus
- Primary emphasis on graphene and its derivatives (e.g., graphene oxides, doped graphene)
- Extends to other 2D materials such as transition metal dichalcogenides (TMDs)
- Predicts electronic, mechanical, and thermal properties crucial for next-gen applications

### Image Preprocessing
- Converts raw structural data of 2D materials into standardized image formats
- Implements data augmentation techniques specific to 2D material structures
- Utilizes advanced filtering and normalization methods to enhance feature detection

## Applications
- Rapid screening of novel 2D materials for specific properties
- Predicting behavior of graphene under various conditions or modifications
- Guiding experimental efforts in 2D material synthesis and characterization

This project aims to accelerate research and development in the exciting field of 2D materials, potentially leading to breakthroughs in electronics, energy storage, and beyond.

## Videos
- [Final Video](https://www.youtube.com/watch?v=en6OTQusNDI)

## Data

- The data is consumed from the Roboflow API (see Notebooks 1 and 4, for example). It can also be accessed publicly at the following [link](https://universe.roboflow.com/2d-materials-segmentation/2d-materials-segmentation).

## Models
The Notebook 4-UNet_128+Image_Augmentation contains the process for loading the trained model. However, the model in .keras format can be downloaded [here](https://drive.google.com/uc?id=1HCkZ6PzWRC_ZsiJaeiKUxBZ8rIsZDg6q)
