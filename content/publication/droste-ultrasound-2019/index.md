+++
title = "Ultrasound Image Representation Learning by Modeling Sonographer Visual Attention"
date = 2019-01-01
authors = ["Richard Droste", "Yifan Cai", "Harshita Sharma", "Pierre Chatelain", "Lior Drukker", "Aris T. Papageorghiou", "J. Alison Noble"]
publication_types = ["1"]
abstract = "Image representations are commonly learned from class labels, which are a simplistic approximation of human image understanding. In this paper we demonstrate that transferable representations of images can be learned without manual annotations by modeling human visual attention. The basis of our analyses is a unique gaze tracking dataset of sonographers performing routine clinical fetal anomaly screenings. Models of sonographer visual attention are learned by training a convolutional neural network (CNN) to predict gaze on ultrasound video frames through visual saliency prediction or gaze-point regression. We evaluate the transferability of the learned representations to the task of ultrasound standard plane detection in two contexts. Firstly, we perform transfer learning by fine-tuning the CNN with a limited number of labeled standard plane images. We find that fine-tuning the saliency predictor is superior to training from random initialization, with an average F1-score improvement of 9.6% overall and 15.3% for the cardiac planes. Secondly, we train a simple softmax regression on the feature activations of each CNN layer in order to evaluate the representations independently of transfer learning hyper-parameters. We find that the attention models derive strong representations, approaching the precision of a fully-supervised baseline model for all but the last layer."
featured = false
publication = "*Information Processing in Medical Imaging*"
tags = ["Convolutional neural networks", "Fetal ultrasound", "Gaze tracking", "Representation learning", "Saliency prediction", "Self-supervised learning", "Transfer learning"]
doi = "10.1007/978-3-030-20351-1_46"
+++

