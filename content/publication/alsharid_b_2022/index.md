---
title: "Gaze-assisted automatic captioning of fetal ultrasound videos using three-way multi-modal deep neural networks"
date: 2022-11-01
authors:
- Mohammad Alsharid
- Yifan Cai
- __Harshita Sharma__
- Lior Drukker
- Aris T. Papageorghiou
- J. Alison Noble

publication_types: ["2"]

featured: false

publication: "*Medical Image Analysis*"

tags:
- video captioning
- gaze tracking
- fetal ultrasound
- audio–visual
- multi-modal

links:
- name: DOI
  url: https://doi.org/10.1016/j.media.2022.102630
  icon_pack: ai
  icon: doi
- name: Elsevier
  url: https://www.sciencedirect.com/science/article/pii/S1361841522002584?via%3Dihub
  icon_pack: fas
  icon: link
- name: BibTeX
  icon_pack: fas
  icon: quote-right
  url: publication/alsharid_b_2022/#bibtex 
---

---

# BibTex

```
@article{ALSHARID2022102630,
title = {Gaze-assisted automatic captioning of fetal ultrasound videos using three-way multi-modal deep neural networks},
journal = {Medical Image Analysis},
volume = {82},
pages = {102630},
year = {2022},
issn = {1361-8415},
doi = {https://doi.org/10.1016/j.media.2022.102630},
url = {https://www.sciencedirect.com/science/article/pii/S1361841522002584},
author = {Mohammad Alsharid and Yifan Cai and Harshita Sharma and Lior Drukker and Aris T. Papageorghiou and J. Alison Noble},
keywords = {Video captioning, Gaze tracking, Fetal ultrasound, Audio–visual, Multi-modal},
abstract = {In this work, we present a novel gaze-assisted natural language processing (NLP)-based video captioning model to describe routine second-trimester fetal ultrasound scan videos in a vocabulary of spoken sonography. The primary novelty of our multi-modal approach is that the learned video captioning model is built using a combination of ultrasound video, tracked gaze and textual transcriptions from speech recordings. The textual captions that describe the spatio-temporal scan video content are learnt from sonographer speech recordings. The generation of captions is assisted by sonographer gaze-tracking information reflecting their visual attention while performing live-imaging and interpreting a frozen image. To evaluate the effect of adding, or withholding, different forms of gaze on the video model, we compare spatio-temporal deep networks trained using three multi-modal configurations, namely: (1) a gaze-less neural network with only text and video as input, (2) a neural network additionally using real sonographer gaze in the form of attention maps, and (3) a neural network using automatically-predicted gaze in the form of saliency maps instead. We assess algorithm performance through established general text-based metrics (BLEU, ROUGE-L, F1 score), a domain-specific metric (ARS), and metrics that consider the richness and efficiency of the generated captions with respect to the scan video. Results show that the proposed gaze-assisted models can generate richer and more diverse captions for clinical fetal ultrasound scan videos than those without gaze at the expense of the perceived sentence structure. The results also show that the generated captions are similar to sonographer speech in terms of discussing the visual content and the scanning actions performed.}
}
```
---

