# A-Novel-Framework-to-Generate-Synthetic-Video-for-Change-Detection-in-Highway-Surveillance-Scenarios

## Abstract

Change detection plays an important role in the domain of video surveillance for highway.
The design of advanced change detection algorithms requires large-scale and diverse video
dataset. However, collecting  and labeling real dataset is still time-consuming, labor-intensive,
and highly subjective. To address this issue, we first propose realistic synthetic scenes to
simulate real highway scenarios. Then, we design synthetic multi-challenge video datasets, 
called “Synthetic-HS (highway scenarios)”, automatically labeled with accurate pixel-level 
ground truth. The Synthetic-HS dataset contains eight imaging condition sequences for computer 
vision research. We use publicly available Synthetic-HS in combination with the corresponding 
real video sequence to conduct experiments. The experiment results suggest that: (1) It is 
necessary to further explore the annotation criteria of change detection dataset. (2) The synthetic
dataset enables us to provide precise quantitative evaluation of the drawbacks of change detection
methods, and can also be used to promote the visual perception in highway video surveillance.

## Description
Considering that change detection models have to deal with some challenges in highway surveillance
scenarios, we generate various synthetic multi-challenge video sequences, 
including Basic, Dynamic Background, Illumination Variations,  Light Switch, Foggy, Night, Thunder Storm and Noise. 
Note: Each specific sequence is also affected by other challenges, but one challenge is dominant.
This synthetic dataset is a photo-realistic vision laboratory that validates the performance of different methods.

## The overall framework of the proposed method
![image](https://github.com/PC-Lab-Virtual-Reality/A-Novel-Framework-to-Generate-Synthetic-Video-for-Change-Detection-in-Highway-Surveillance-Scenarios/blob/main/Figure/fig1.jpg)

## Examples of the real and synthetic dataset
![image](A-Novel-Framework-to-Generate-Synthetic-Video-for-Change-Detection-in-Highway-Surveillance-Scenarios/blob/main/Figure/fig2.jpg)


## Download
The Synthetic-HS is a highway video dataset designed to design and evaluate a variety of computer vision models for change detection.
We provide one [.rar] archive per type of data as described below. Our indexes always start from 000001. In the following,

Synthetic-HS_dataset_rbg_2021: Each area is simply a folder in the format: The compressed file contains the original image.

[Synthetic-HS_dataset_rbg_2021.rar](https://drive.google.com/file/d/1hQ4-aFxwLe4PU2GPFasYQ_oZBqV4jmUK/view?usp=sharing)

Synthetic-HS_dataset_gt_2021: The compressed file contains the ground truth of object detection. The per-pixel segmentation ground truth is encoded as per-frame .png files (standard 8-bit precision per channel).

[Synthetic-HS_dataset_gt_2021.rar](https://drive.google.com/file/d/1gEIApEnkggwoG6FLTbRzqGq6jgDRc6Of/view?usp=sharing)

## Sample images of Synthetic-HS sequences
![image](https://github.com/PC-Lab-Virtual-Reality/Biomimetic-Design-of-EECD-Method-for-Challenging-Water-Scenes/blob/main/Figure/fig3.jpg)

## Examples of change detection results on Synthetic-HS using different models
![image](https://github.com/PC-Lab-Virtual-Reality/Biomimetic-Design-of-EECD-Method-for-Challenging-Water-Scenes/blob/main/Figure/fig4.jpg)

## Citations
All rights of the Synthetic-HS Dataset are reversed by the Peng Cheng Laboratory. It is free for academic research, and your cooperation with us is appreciated. Feel free to contact us if you have any questions.
