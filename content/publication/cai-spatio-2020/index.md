---
title : "Spatio-Temporal Visual Attention Modelling of Standard Biometry Plane-Finding Navigation"
date : 2020-06-20
authors:
- "Yifan Cai"
- "Richard Droste"
- "__Harshita Sharma__"
- "Pierre Chatelain"
- "Lior Drukker"
- "Aris T. Papageorghiou"
- "J. Alison Noble"

publication_types: ["2"]

featured: true

publication: "*Medical Image Analysis*"

abstract: "We present a novel multi-task neural network called Temporal SonoEyeNet (TSEN) with a primary task to describe the visual navigation process of sonographers by learning to generate visual attention maps of ultrasound images around standard biometry planes of the fetal abdomen, head (trans-ventricular plane) and femur. TSEN has three components: a feature extractor, a temporal attention module (TAM), and an auxiliary video classification module (VCM). A soft dynamic time warping (sDTW) loss function is used to improve visual attention modelling. Variants of the model are trained on a dataset of 280 video clips, each containing one of the three biometry planes and lasting 3-7 seconds, with corresponding real-time recorded gaze tracking data of an experienced sonographer. We report the performances of the different variants of TSEN for visual attention prediction at standard biometry plane detection. The best model performance is achieved using bi-directional convolutional long-short term memory (biCLSTM) in both TAM and VCM, and it outperforms a previous spatial model on all static and dynamic saliency metrics. As an auxiliary task to validate the clinical relevance of the visual attention modelling, the predicted visual attention maps were used to guide standard biometry plane detection in consecutive US video frames. All spatio-temporal TSEN models achieve higher scores compared to a spatial-only baseline; the best performing TSEN model achieves F1 scores on these standard biometry planes of 83.7%, 89.9% and 81.1%, respectively."

tags:
- Fetal ultrasound
- Gaze tracking
- Multi-task learning
- Saliency prediction
- Standard plane detection

links:
- name: DOI
  url: https://doi.org/10.1016/j.media.2020.101762
  icon_pack: ai
  icon: doi
- name: BibTeX
  icon_pack: fas
  icon: quote-right
  url: publication/cai-spatio-2020/#bibtex 
---

---

# BibTex

```
@article{cai2020spatio,
  title = "Spatio-temporal visual attention modelling of standard biometry plane-finding navigation",
journal = "Medical Image Analysis",
volume = "65",
pages = "101762",
year = "2020",
issn = "1361-8415",
doi = "https://doi.org/10.1016/j.media.2020.101762",
url = "http://www.sciencedirect.com/science/article/pii/S1361841520301262",
author = "Yifan Cai and Richard Droste and Harshita Sharma and Pierre Chatelain and Lior Drukker and Aris T. Papageorghiou and J. Alison Noble",
keywords = "Fetal ultrasound, Gaze tracking, Multi-task learning, Saliency prediction, Standard plane detection"
}

```
---

