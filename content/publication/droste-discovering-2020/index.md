---
title: "Discovering Salient Anatomical Landmarks by Predicting Human Gaze"
date: 2020-01-01
authors:
- "Richard Droste"
- "Pierre Chatelain"
- "Lior Drukker"
- "__Harshita Sharma__"
- Aris T. Papageorghiou 
- J. Alison Noble

publication_types: ["2"]

abstract: "Anatomical landmarks are a crucial prerequisite for many medical imaging tasks. Usually, the set of landmarks for a given task is predefined by experts. The landmark locations for a given image are then annotated manually or via machine learning methods trained on manual annotations. In this paper, in contrast, we present a method to automatically discover and localize anatomical landmarks in medical images. Specifically, we consider landmarks that attract the visual attention of humans, which we term visually salient landmarks. We illustrate the method for fetal neurosonographic images. First, full-length clinical fetal ultrasound scans are recorded with live sonographer gaze-tracking. Next, a convolutional neural network (CNN) is trained to predict the gaze point distribution (saliency map) of the sonographers on scan video frames. The CNN is then used to predict saliency maps of unseen fetal neurosonographic images, and the landmarks are extracted as the local maxima of these saliency maps. Finally, the landmarks are matched across images by clustering the landmark CNN features. We show that the discovered landmarks can be used within affine image registration, with average landmark alignment errors between 4.1% and 10.9% of the fetal head long axis length."

featured: false

publication: "*2020 IEEE 17th International Symposium on Biomedical Imaging (ISBI)*, Iowa City, IA, USA, 2020, pp. 1711-1714. **Best Paper Awards Runner Up**"

tags:
- Computer Science 
- Computer Vision and Pattern Recognition
- Computer Science 
- Machine Learning
- Electrical Engineering and Systems Science 
- Image and Video Processing

links:
- name: PDF
  url: https://rdroste.com/files/droste-et-al_visually-salient-landmarks_ISBI-2020.pdf
  icon_pack: fas
  icon: file-pdf
- name: DOI
  url: https://doi.org/10.1109/ISBI45749.2020.9098505
  icon_pack: ai
  icon: doi
- name: arXiv
  url: https://arxiv.org/abs/2001.08188
  icon_pack: ai
  icon: arxiv
- name: ORA
  url: https://ora.ox.ac.uk/objects/uuid:ea5a4c52-85ec-4317-aeba-de8a61953722
  icon_pack: ai
  icon: open-access
- name: IEEE
  url: https://ieeexplore.ieee.org/abstract/document/9098505
  icon_pack: ai
  icon: ieee
- name: BibTeX
  icon_pack: fas
  icon: quote-right
  url: publication/droste-discovering-2020/#bibtex
---

---

# BibTex

```
@article{droste_discovering_2020,
 annote = {Comment: Accepted at IEEE International Symposium on Biomedical Imaging 2020 (ISBI 2020)},
 author = {Droste, Richard and Chatelain, Pierre and Drukker, Lior and Sharma, Harshita and Papageorghiou, Aris T. and Noble, J. Alison},
 title = {Discovering Salient Anatomical Landmarks by Predicting Human Gaze},
 journal = {arXiv:2001.08188 [cs, eess]},
 keywords = {Computer Science - Computer Vision and Pattern Recognition, Computer Science - Machine Learning, Electrical Engineering and Systems Science - Image and Video Processing},
 note = {arXiv: 2001.08188},
 url = {http://arxiv.org/abs/2001.08188},
 urldate = {2020-03-04},
 year = {2020}
}

```

---
