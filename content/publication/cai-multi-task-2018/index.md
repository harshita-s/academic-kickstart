+++
title = "Multi-task SonoEyeNet: Detection of Fetal Standardized Planes Assisted by Generated Sonographer Attention Maps"
date = 2018-01-01
authors = ["Yifan Cai", "Harshita Sharma", "Pierre Chatelain", "J. Alison Noble"]
publication_types = ["1"]
abstract = "We present a novel multi-task convolutional neural network called Multi-task SonoEyeNet (M-SEN) that learns to generate clinically relevant visual attention maps using sonographer gaze tracking data on input ultrasound (US) video frames so as to assist standardized abdominal circumference (AC) plane detection. Our architecture consists of a generator and a discriminator, which are trained in an adversarial scheme. The generator learns sonographer attention on a given US video frame to predict the frame label (standardized AC plane/background). The discriminator further fine-tunes the predicted attention map by encouraging it to mimick the ground-truth sonographer attention map. The novel model expands the potential clinical usefulness of a previous model by eliminating the requirement of input gaze tracking data during inference without compromising its plane detection performance (Precision: 96.8, Recall: 96.2, F-1 score: 96.5)."
featured = false
publication = "*Medical Image Computing and Computer Assisted Intervention – MICCAI 2018*"
tags = ["Fetal ultrasound", "Gaze tracking", "Generative Adversarial Network", "Multi-task learning", "Saliency prediction", "Standardized plane detection"]
doi = "10.1007/978-3-030-00928-1_98"
+++
