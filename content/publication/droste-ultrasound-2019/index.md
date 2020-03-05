---
title: "Ultrasound Image Representation Learning by Modeling Sonographer Visual Attention"
authors:
- Richard Droste
- Yifan Cai
- Harshita **Sharma**
- Pierre Chatelain
- Lior Drukker
- Aris T. Papageorghiou
- J. Alison Noble

date: " 2019-01-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Information Processing in Medical Imaging (IPMI 2020)* **Best Paper Award**

abstract: Image representations are commonly learned from class labels, which are a simplistic approximation of human image understanding. In this paper we demonstrate that transferable representations of images can be learned without manual annotations by modeling human visual attention. The basis of our analyses is a unique gaze tracking dataset of sonographers performing routine clinical fetal anomaly screenings. Models of sonographer visual attention are learned by training a convolutional neural network (CNN) to predict gaze on ultrasound video frames through visual saliency prediction or gaze-point regression. We evaluate the transferability of the learned representations to the task of ultrasound standard plane detection in two contexts. Firstly, we perform transfer learning by fine-tuning the CNN with a limited number of labeled standard plane images. We find that fine-tuning the saliency predictor is superior to training from random initialization, with an average F1-score improvement of 9.6% overall and 15.3% for the cardiac planes. Secondly, we train a simple softmax regression on the feature activations of each CNN layer in order to evaluate the representations independently of transfer learning hyper-parameters. We find that the attention models derive strong representations, approaching the precision of a fully-supervised baseline model for all but the last layer.

tags:
- Convolutional neural networks
- Fetal ultrasound
- Gaze tracking
- Representation learning
- Saliency prediction
- Self-supervised learning
- Transfer learning

featured: true

links:
- name: PDF
  url: https://arxiv.org/pdf/1903.02974.pdf
  icon_pack: fas
  icon: file-pdf
- name: DOI
  url: https://doi.org/10.1007/978-3-030-20351-1_46
  icon_pack: ai
  icon: doi
- name: arXiv
  url: https://arxiv.org/abs/1903.02974
  icon_pack: ai
  icon: arxiv
- name: ORA
  url: https://ora.ox.ac.uk/objects/uuid:a27fe42b-3a94-4b0f-bc7d-2173c0348b6f
  icon_pack: ai
  icon: open-access
- name: Springer
  url: https://link.springer.com/chapter/10.1007/978-3-030-20351-1_46
  icon_pack: ai
  icon: springer
- name: BibTeX
  icon_pack: fas
  icon: quote-right
  url: publication/droste-ultrasound-2019/#droste-ultrasound-2019
---

