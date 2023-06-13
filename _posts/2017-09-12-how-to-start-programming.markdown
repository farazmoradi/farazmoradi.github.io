---
layout: post
title: Projects
date: 2017-09-12 00:00:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: how-to-start.jpg # Add image post (optional)
tags: [Programming, Learn] # add tag
---

### Arrhythmia Detection on ECG signals using Deep CNNs

<div style="text-align: justify;">

The methodology for classifying ECG signals in this study involved the following steps:

1. Data Acquisition and Selection: ECG signals were obtained from the MIT-BIH arrhythmia database. Five types of ECG signals were selected, each with a sampling rate of 125 Hz. A segment of 1.496 seconds was chosen from each signal for classification, resulting in a total of 87554 training and 21892 test samples.

2. ECG Data Pre-processing: The ECG signals were transformed from the time domain into 2D time-frequency spectrograms using the short-time Fourier transform (STFT). The STFT allows for the exploration of both instantaneous frequency and amplitude of localized waves with time-varying characteristics. A Hanning window function was used, and the resulting spectrograms were plotted as individual 25x25 pixel images.

3. ECG Arrhythmia Classifier: A deep two-dimensional convolutional neural network (2D-CNN) was employed as the ECG arrhythmia classifier. The CNN model is capable of extracting local features of the image by applying multiple filters and capturing the correlation of spatially adjacent pixels. The 2D-CNN model consisted of multiple layers, including convolutional, pooling, and activation layers. The input to the model was the ECG spectrogram images, and the output was the classification of the five types of arrhythmia: normal beat (NOR), left bundle branch block beat (LBB), right bundle branch block beat (RBB), premature ventricular contraction beat (PVC), and atrial premature contraction beat (APC).

4. Classification Process: The ECG spectrogram images were fed into the 2D-CNN model, which automatically and intelligently classified the five ECG types. The model utilized convolutional and pooling layers to filter the spatial locality of the ECG images and extract relevant features. The specific structure of the 2D-CNN model involved applying convolutional layers with different kernel sizes, activation functions (RELU), and max-pooling layers. The output shape of each layer was determined by the chosen parameters.

5. Optimization techniques and toolboxes such as Optuna, MLflow and Hydra was used reach the best hyperparameters. 

By following this methodology, the study aimed to accurately classify ECG signals into different arrhythmia types using the deep learning approach of the 2D-CNN model.

</div>





### Actively movement tracking of animals in the maze using DeepLabCut and OpenCV package <a href="https://github.com/Singular-Brain/CCSPNet" style="font-size: 20px;">(Code)</a>

<div style="text-align: justify;">

In this project, we utilized computer vision techniques and machine learning algorithms to track mice in a linear environment. The goal was to accurately track the movement and behavior of the mice to gain insights into their locomotion patterns and interactions.



We employed the following steps to track the mice:

1. Data Collection: High-resolution video footage of mice moving in a linear environment was captured. The videos were recorded using a suitable camera setup to ensure clear visibility of the mice.

2. Preprocessing: The video footage was preprocessed to enhance the quality and optimize it for tracking. This involved techniques such as denoising, contrast adjustment, and frame resizing.

3. Mouse Detection: We used OpenCV, a popular computer vision library, to detect and locate the mice within each frame of the video. Various algorithms were tested, including Haar cascades and HOG (Histogram of Oriented Gradients), to identify the mice accurately.

4. Tracking: To track the mice across frames, we employed DeepLabCut Pro, a state-of-the-art deep learning-based pose estimation tool. The tool utilizes convolutional neural networks (CNNs) to estimate the mouse's pose and track its movements robustly.

5. Algorithm Selection: We experimented with different tracking algorithms, including CSRT (Channel and Spatial Reliability Tracking), to find the most effective approach for our specific scenario. We evaluated factors such as tracking accuracy, speed, and robustness to occlusions or lighting variations.

6. Post-processing and Analysis: Once the tracking was complete, we analyzed the data to extract meaningful insights about the mice's behavior. This included measuring parameters like velocity, acceleration, distance traveled, and interaction patterns between mice.


</div>



<div style="display: flex;">
  <iframe width="50%" height="315" src="https://www.youtube.com/embed/QfiI5bEK1nM" frameborder="0" allowfullscreen></iframe>
  
  <iframe width="50%" height="315" src="https://www.youtube.com/embed/33UrbxL0jDs" frameborder="0" allowfullscreen></iframe>
</div>

<figure align="center">
  <img src="/assets/img/tracking.jpg" alt="Alt Text" width="550" height="400">
</figure>






### Implementing various Generative Adversarial Nets architectures (DGAN, WGAN, InfoGAN, Conditional GAN) on MNIST dataset. <a href="https://github.com/Singular-Brain/CCSPNet" style="font-size: 20px;">(Code)</a>


### Time-frequency analysis EEG and LFP signal using various methods like STFT, Wavelet and Filter Hilbert. <a href="https://github.com/Singular-Brain/CCSPNet" style="font-size: 20px;">(Code)</a>