---
layout: post
title: Publications
date: Last Update March 2023
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: systemneurosci.png # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Holidays, Hawaii]
---
Welcome to my website! I am thrilled to share with you my ongoing exploration and research at the exciting intersection of neuroscience and machine learning. As a passionate enthusiast in both fields, I am constantly delving into the fascinating world of understanding the human brain and harnessing the power of cutting-edge technologies. Through my work, I aim to uncover the mysteries of the brain and develop innovative solutions that leverage machine learning algorithms to enhance our understanding of cognitive processes, brain disorders, and human behavior. Join me on this captivating journey as we explore the realms of neuroscience and machine learning, pushing the boundaries of knowledge and paving the way for groundbreaking advancements in these captivating fields.

## Towards Real-World BCI: CCSPNet, A Compact Subject-Independent Motor Imagery Framework
A conventional brain-computer interface (BCI) requires a complete data gathering, training, and cal- ibration phase for each user before it can be used. In recent years, a number of subject-independent (SI) BCIs have been developed. Many of these methods yield a weaker performance compared to the subject-dependent (SD) approach, and some are computationally expensive. A potential real- world application would greatly benefit from a more accurate, compact, and computationally efficient subject-independent BCI. In this work, we propose a novel subject-independent BCI framework, named CCSPNet (Convolutional Common Spatial Pattern Network) that is trained on the motor imagery (MI) paradigm of a large-scale electroencephalography (EEG) signals database consisting of 400 trials for every 54 subjects who perform two-class hand-movement MI tasks. The proposed framework applies a wavelet kernel convolutional neural network (WKCNN) and a temporal convolutional neural net- work (TCNN) in order to represent and extract the spectral features of EEG signals. A common spatial pattern (CSP) algorithm is implemented for spatial feature extraction, and the number of CSP features is reduced by a dense neural network. Finally, the class label is determined by a linear dis- criminant analysis (LDA) classifier. The CCSPNet evaluation results show that it is possible to have a compact BCI that achieves both SD and SI state-of-the-art performance comparable to complex and computationally expensive models.

![first]({{site.baseurl}}/assets/img/CCSP_model.png) {:width="400px" height="300px"})


## Early Electrophysiological Aberrations in the Hippocampus of the TgF344-AD Rat Model as a Potential Biomarker for Alzheimer’s Disease Prognosis

The hippocampus is thought to guide navigation and has an essential contribution to learning and memory. Hippocampus is one of the brain regions impaired in Alzheimer’s disease (AD), a neurodegenerative disease with progressive memory impairments and cognitive decline. Although successful treatments for AD are still not available, developing new strategies to detect AD at early stages before clinical manifestation is crucial for timely interventions. Here, we investigated in the TgF344-AD rat model the classification of AD-transgenic rats versus Wild-type littermates (WT) from electrophysiological activity recorded in the hippocampus of freely moving subjects at an early, pre-symptomatic stage of the disease (6 months old). To this end, recorded signals were filtered in two separate frequency regimes namely low frequency LFP signals and high frequency spiking activity and passed to machine learning (ML) classifiers to identify the genotype of the rats (TG vs. WT). For the low frequency analysis, we first filtered the signals and extracted the power spectra in different frequency bands known to carry differential information in the hippocampus (delta, theta, slow- and fast-gamma) while for the high frequency analysis, we extracted spike-trains of neurons and calculated different distance metrics between them, including Van Rossum (VR), Inter Spike Interval (ISI), and Event Synchronization (ES). These measures were then used as features for classification with different ML classifiers. We found that both low and high frequency signals were able to classify the rat genotype with a high accuracy with specific signals such as the gamma band power, providing an important fraction of information. In addition, when we combined information from both low and high frequency the classification was boosted indicating that independent information is present across the two bands. The results of this study offer a better insight into how different regions of the hippocampus are affected in earlier stages of AD.


## A Protocol for Isolating Neural Activity of Neurons and Analyzing Their Behavior in a Pattern Separation Task (Master Thesis)


Understanding how the human brain works can lead to new discoveries and improved treatments for brain related diseases and disabilities such as Alzheimer's and autism. One method for studying brain activity is through electrophysiological recordings, particularly through the use of in vivo recording techniques. While these techniques have advanced significantly over the years, data analysis tools have not kept pace, making it difficult to isolate the activity of individual neurons from the recordings. In this thesis, we propose a protocol for isolating the spike activity of a neuron from an electrophysiology recording. We compared various toolboxes in different phases of the protocol and ensured that the input and output formats were standardized and user-friendly for neuroscientists having limited background in computer science and programming. Additionally, we conducted further investigation of the recorded cells (Mossy and Granule Cell) during a pattern separation task using classical spike train analysis methods. We also tracked the behavior of each isolated cell to gain insight into their role in the experiment.



<p align="center">
  <img src="/assets/img/Cell_Stat.png" alt="Alt Text" width="500" height="300">
</p>



* Hexagon shoreditch beard
* Intelligentsia narwhal austin
* Literally meditation four
* Microdosing hoodie woke

## 
