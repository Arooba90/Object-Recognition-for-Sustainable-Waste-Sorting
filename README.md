# Waste Management System

## Project Overview

The central focus of our initiative is to effectively categorize various types of waste, including electrical components, organic matter, and other recyclable materials. Each waste type presents unique environmental challenges, emphasizing the importance of accurate identification and classification.

## Technology Stack

To address these challenges, our approach incorporates advanced object recognition techniques using OpenCV and Keras. Object recognition plays a crucial role in our waste management solution, allowing the system to analyze visual data and distinguish between various materials commonly found in household waste.

The integration of Keras, a powerful deep learning API, further enhances the system's capabilities by facilitating the training of a neural network. This network can recognize and classify waste items based on learned patterns and features. The combination of waste type categorization and advanced object recognition technologies empowers our system to contribute significantly to sustainable waste management practices, reducing environmental impact and promoting efficient recycling.

## Dataset

### Waste Classification Dataset

The dataset selected for this project is the "Waste Classification Dataset" available on Kaggle, accessible [here](https://www.kaggle.com/datasets/shubhamdivakar/waste-classification-dataset). This database is composed of images representing different types of waste: electrical, organic, and other recyclable materials. The database has two folders, "train" and "test," each containing subfolders "E," "O," and "R" for electrical, organic, and recyclable materials, respectively.

#### Number of Files in Each Folder

##### Test
- E with 26 files
- O with 1401 files
- R with 1112 files

##### Train
- E with 124 files
- O with 12.6k files
- R with 9999 files

## Repository Contents

This repository contains two Jupyter Source Files (.ipynb):
1. `train_model.ipynb`: Used for training the models.
2. `test_model.ipynb`: Used for testing the models.
