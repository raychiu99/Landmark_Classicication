# Landmark Image Classification Project

## Overview

Welcome to the Landmark Image Classification Project! This repository houses the code and documentation for a collaborative effort undertaken as part of [DSCI-552 Machine Learning for Data Science] at USC. The project revolves around the fascinating world of computer vision and deep learning, with a focus on accurately classifying landmarks and their associated architectural styles using Convolutional Neural Networks (CNNs) and transfer learning techniques.

## Project Structure

- `data/`: Contains the dataset used for training and evaluation.
- `notebooks/`: Jupyter notebooks documenting data preprocessing, model training, and evaluation.
- `models/`: Saved model checkpoints and trained weights.
- `images/`: Images used for the README and project documentation.
- `README.md`: This project's README file.


## Motivation

Landmarks not only hold historical and cultural significance but are also a vital component of tourism and urban planning. This project stems from our curiosity to leverage modern technology for recognizing and categorizing landmarks, aiding fields like tourism, architecture, and urban development.

## Project Objectives

The primary objectives of this project are as follows:

- Develop a robust CNN model capable of categorizing architectural landmarks based on their distinctive styles.
- Implement a model that can accurately identify specific landmarks from input images, contributing to the field of automated landmark recognition.
- Explore and apply transfer learning to optimize model performance and address challenges posed by limited data availability.

## Approach

Our approach involves a series of carefully orchestrated steps:

1. **Data Collection and Preprocessing:** We amassed a custom dataset of landmark images, categorized by architectural styles and individual landmark names. The dataset was divided into training, validation, and testing sets. Data preprocessing techniques were applied to ensure uniformity and prepare the data for model training.

2. **Model Architecture Selection:** We embarked on an architecture exploration journey, initially experimenting with the EfficientNetB0 architecture. After rigorous experimentation, we concluded that the VGG16 architecture exhibited superior performance for our specific task.

3. **Transfer Learning and Fine-Tuning:** To tackle the challenge of limited dataset size, we leveraged transfer learning. We utilized TensorFlow's capabilities to retrain the chosen VGG16 architecture on our landmark dataset. Fine-tuning was employed to adapt the model to our task.

4. **Data Augmentation and Robustness:** Data augmentation was integrated into our workflow using TensorFlow's image manipulation functions. This step enhanced the model's ability to generalize across various inputs, contributing to overall robustness.

5. **Evaluation and Insights:** The trained model's performance was evaluated on the test set, yielding remarkable accuracy rates of 95.18% for architectural category classification and 91.57% for landmark identification. The results underscored the effectiveness of our chosen approach.

## Next Steps

While our project has yielded promising results, there is ample room for further exploration and improvement:

- Collecting a more diverse and comprehensive dataset to enhance the model's accuracy on unseen landmarks.
- Exploring additional deep learning architectures, such as Residual Neural Networks (ResNet), to potentially boost accuracy further.
- Extending the project to real-world applications, such as integrating the model into tourism and urban planning platforms.

We invite you to explore our code, documentation, and insights in this repository. Feel free to reach out with any questions, suggestions, or collaboration opportunities.

