# Ship-Classification-in-Port-Environments

**Project Overview**

This project focuses on the automatic classification of ship images captured in port environments. The system aims to improve real-time monitoring of maritime operations, assisting in the efficient management and safety of ports. The complex task of identifying and categorizing ships is addressed using advanced deep learning techniques, specifically Convolutional Neural Networks (CNN), with a focus on the ResNet-152 architecture.

**Problem Statement**

Managing maritime ports involves monitoring and classifying ships based on various characteristics such as type, size, and condition. This process is often prone to human error, especially in challenging weather conditions or overcrowded ports. The goal of this project is to create a system that automates the classification of ships, enhancing port management and operational efficiency.

**Objectives**

Develop a system to automatically classify ships using image data from maritime ports.
Utilize deep learning techniques, particularly CNNs, to analyze ship characteristics.
Improve port logistics and security by providing accurate real-time information about incoming and outgoing vessels.

**Methodology**

***Dataset***

We utilized the "Game of Deep Learning Ship" dataset, which consists of 8,932 images of five ship categories: Cargo, Military, Carrier, Cruise, and Tanker. The dataset was pre-processed to balance class distribution, and various data augmentation techniques were applied, including image resizing, flipping, and color adjustments.

***Model Architecture: ResNet-152***

The ResNet-152 architecture was chosen for its ability to handle complex image classification tasks by leveraging deep residual learning. It has 152 layers, making it a robust model for feature extraction and learning. Pre-trained on ImageNet, ResNet-152 was fine-tuned for the specific task of ship classification in this project, adapting the final layer to classify the five ship categories.

  ***Evaluation***
  
Key metrics used for evaluation include:

* Accuracy

* Precision

* Recall

* F1-Score

***Model Performance***
The ResNet-152 model showed the highest performance, achieving the following results:

* Training Accuracy: 92.5%
* Validation Accuracy: 90%
* F1-Scores:
 * Cargo: 84%
 * Military: 94%
 * Carrier: 96%
 * Cruise: 95%
 * Tankers: 83%
