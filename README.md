# Lego Brick Classification Project

Training a CNN for LEGO Bricks Recognition

https://medium.com/rocket-science-team/training-a-cnn-for-lego-bricks-recognition-f285ffab3327


![image](https://github.com/user-attachments/assets/fb93140d-6005-4dcc-a5c2-2df2ee04f9ab)


## Project Description

This project focuses on building a convolutional neural network (CNN) model to classify LEGO bricks. The model is trained on a dataset of images, aiming to recognize 20 different types of LEGO bricks. It was developed as part of a Data Science bootcamp and is designed to help LEGO collectors and enthusiasts identify pieces quickly.

The full project description can be found in `PROJECT_DESCRIPTION.md`.

---

## Team Composition

- **Aleksandra Baran** - [LinkedIn](http://linkedin.com/in/alexabaran) | [GitHub](https://github.com/alexabaran)
- **Dariusz Balcer** - [LinkedIn](https://www.linkedin.com/in/dariuszbalcer/) | [GitHub](https://github.com/montenegro-db)
- **Grzegorz Gomza** - [LinkedIn](https://www.linkedin.com/in/gregory-gomza/) | [GitHub](https://github.com/grzegorz-gomza/)

---

## Project Overview

### Motivation

LEGO is a globally recognized brand, and with this project, we aim to create a system that can recognize individual LEGO bricks from photos. This recognition could be helpful for collectors, enthusiasts, and even in app development for various LEGO-related functionalities.

### Methodology

We used convolutional neural networks (CNNs) for this image classification project. Two models were implemented:

1. **RocketNet**: A custom CNN designed for this project.
2. **AlexNet**: A scaled-down version of the well-known AlexNet architecture.

Both models were trained on a subset of the B200C LEGO Classification Dataset from Kaggle, which contains approximately 4,000 images per class for 20 different LEGO brick types.

### Model Design

- **RocketNet**:
  - Simple architecture with three convolutional layers, dropout, and dense layers.
  - Achieved an accuracy of 88.9% on the validation set.

- **AlexNet**:
  - More complex architecture with five convolutional layers and two dense layers.
  - Achieved an accuracy of 90.9% on the validation set but had some concentrated errors.

### Grad-CAM Visualization

We used **Grad-CAM** (Gradient-weighted Class Activation Mapping) to visualize which parts of the images were being focused on by the models during classification. This helped in understanding the decision-making process of the models.

---

## Applications

The trained model has several potential applications, such as:

1. **LEGO Building App**: To recognize available bricks and suggest models to build.
2. **Assistive Technology for Visually Impaired**: LEGO recognition with voice prompts for easy building.
3. **Collection Management App**: For sorting and categorizing bricks.
4. **LEGO Shopping and Exchange App**: To help identify and catalog LEGO pieces for easy transactions.

---

## Conclusion

The project demonstrates the effectiveness of CNNs in classifying LEGO bricks. Despite hardware limitations, the models showed good performance, with the simpler RocketNet providing comparable results to the more complex AlexNet. This approach could be further improved and expanded for real-world applications.
