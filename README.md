# Analysis of Real-Time Hostile Activitiy Detection from Spatiotemporal Features Using Time Distributed Deep CNNs, RNNs and Attention-Based Mechanisms

## Overview

This repo contains code my academic thesis ' Analysis of Real-Time Hostile Activitiy Detection from Spatiotemporal Features Using Time Distributed Deep CNNs, RNNs and Attention-Based Mechanisms' using state-of-the-art video classification algorithms implemented with TensorFlow 2.6.0 and Keras API 2.6.0. 

## Algorithms Used

The following video classification algorithms have been implemented:

- **LRCN (Long-term Recurrent Convolutional Networks)**
- **ConvLSTM (Convolutional Long Short-Term Memory)**
- **C3D (3D Convolutional Networks)**
- **CNN-Transformer**

## Special Cases Consideration

To enhance the model's performance, special cases like hugging, greeting, and waving have been taken into consideration. The models are designed to distinguish between violent and non-violent actions, including these specific scenarios, to minimize false positives.

## paper abstract 

Real-time video surveillance, through CCTV camera systems has become essential for ensuring public safety which is a priority today. Although CCTV cameras help a lot in increasing security, these systems require constant human interaction and monitoring. To eradicate this issue, intelligent surveillance systems can be built using deep learning video classification techniques that can help us automate surveillance systems to detect violence as it happens. In this research, we explore deep learning video classification techniques to detect violence as they are happening. Traditional image classification techniques fall short when it comes to classifying videos as they attempt to classify each frame separately for which the predictions start to flicker. Therefore, many researchers are coming up with video classification techniques that consider spatiotemporal features while classifying. However, deploying these deep learning models with methods such as skeleton points obtained through pose estimation and optical flow obtained through depth sensors, are not always practical in an IoT environment. Although these techniques ensure a higher accuracy score, they are computationally heavier. Keeping these constraints in mind, we experimented with various video classification and action recognition techniques such as ConvLSTM, LRCN (with both custom CNN layers and VGG-16 as feature extractor) CNNTransformer and C3D. We achieved a test accuracy of 80% on ConvLSTM, 83.33% on CNN-BiLSTM, 70% on VGG16-BiLstm, 76.76% on CNN-Transformer and 80% on C3D.

[Paper Link](https://ieeexplore.ieee.org/document/10053001)
