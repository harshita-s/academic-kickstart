+++
title = "Discovering Salient Anatomical Landmarks by Predicting Human Gaze"
date = 2020-01-01
authors = ["Richard Droste", "Pierre Chatelain", "Lior Drukker", "Harshita Sharma", "Aris T. Papageorghiou", "J. Alison Noble"]
publication_types = ["2"]
abstract = "Anatomical landmarks are a crucial prerequisite for many medical imaging tasks. Usually, the set of landmarks for a given task is predefined by experts. The landmark locations for a given image are then annotated manually or via machine learning methods trained on manual annotations. In this paper, in contrast, we present a method to automatically discover and localize anatomical landmarks in medical images. Specifically, we consider landmarks that attract the visual attention of humans, which we term visually salient landmarks. We illustrate the method for fetal neurosonographic images. First, full-length clinical fetal ultrasound scans are recorded with live sonographer gaze-tracking. Next, a convolutional neural network (CNN) is trained to predict the gaze point distribution (saliency map) of the sonographers on scan video frames. The CNN is then used to predict saliency maps of unseen fetal neurosonographic images, and the landmarks are extracted as the local maxima of these saliency maps. Finally, the landmarks are matched across images by clustering the landmark CNN features. We show that the discovered landmarks can be used within affine image registration, with average landmark alignment errors between 4.1% and 10.9% of the fetal head long axis length."
featured = false
publication = "*arXiv:2001.08188 [cs, eess]*"
tags = ["Computer Science - Computer Vision and Pattern Recognition", "Computer Science - Machine Learning", "Electrical Engineering and Systems Science - Image and Video Processing"]
url_pdf = "http://arxiv.org/abs/2001.08188"
+++
