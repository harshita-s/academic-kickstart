---
title : "Machine Learning-based Analysis of Operator Pupillary Response to Assess Cognitive Workload in Clinical Ultrasound Imaging"
date : 2021-06-26
authors:
- "__Harshita Sharma__"
- "Lior Drukker"
- "Aris T. Papageorghiou"
- "J. Alison Noble"

publication_types: ["2"]

featured: true

publication: "*Computers in Biology and Medicine*"

abstract: "Introduction
Pupillometry, the measurement of eye pupil diameter, is a well-established and objective modality correlated with cognitive workload. In this paper, we analyse the pupillary response of ultrasound imaging operators to assess their cognitive workload, captured while they undertake routine fetal ultrasound examinations. Our experiments and analysis are performed on real-world datasets obtained using remote eye-tracking under natural clinical environmental conditions.
Methods
Our analysis pipeline involves careful temporal sequence (time-series) extraction by retrospectively matching the pupil diameter data with tasks captured in the corresponding ultrasound scan video in a multi-modal data acquisition setup. This is followed by the pupil diameter pre-processing and the calculation of pupillary response sequences. Exploratory statistical analysis of the operator pupillary responses and comparisons of the distributions between ultrasonographic tasks (fetal heart versus fetal brain) and operator expertise (newly-qualified versus experienced operators) are performed. Machine learning is explored to automatically classify the temporal sequences into the corresponding ultrasonographic tasks and operator experience using temporal, spectral, and time-frequency features with classical (shallow) models, and convolutional neural networks as deep learning models.
Results
Preliminary statistical analysis of the extracted pupillary response shows a significant variation for different ultrasonographic tasks and operator expertise, suggesting different extents of cognitive workload in each case, as measured by pupillometry. The best-performing machine learning models achieve receiver operating characteristic (ROC) area under curve (AUC) values of 0.98 and 0.80, for ultrasonographic task classification and operator experience classification, respectively.
Conclusion
We conclude that we can successfully assess cognitive workload from pupil diameter changes measured while ultrasound operators perform routine scans. The machine learning allows the discrimination of the undertaken ultrasonographic tasks and scanning expertise using the pupillary response sequences as an index of the operators' cognitive workload. A high cognitive workload can reduce operator efficiency and constrain their decision-making, hence, the ability to objectively assess cognitive workload is a first step towards understanding these effects on operator performance in biomedical applications such as medical imaging."

tags:
- Eye-tracking
- Pupillometry
- Cognitive Workload
- Ultrasound Imaging
- Time-series Analysis
- Sonography Data Science
- Fetal Ultrasound
- Machine Learning
- Deep Learning
- Convolutional Neural Network
- Multi-modal Data

links:
- name: DOI
  url: https://doi.org/10.1016/j.compbiomed.2021.104589
  icon_pack: ai
  icon: doi
- name: Elsevier
  url: https://www.sciencedirect.com/science/article/pii/S0010482521003838
  icon_pack: fas
  icon: link
- name: BibTeX
  icon_pack: fas
  icon: quote-right
  url: publication/sharma-machine-2021/#bibtex 
---

---

# BibTex

```
@article{SHARMA2021104589,
title = {Machine learning-based analysis of operator pupillary response to assess cognitive workload in clinical ultrasound imaging},
journal = {Computers in Biology and Medicine},
volume = {135},
pages = {104589},
year = {2021},
issn = {0010-4825},
doi = {https://doi.org/10.1016/j.compbiomed.2021.104589},
url = {https://www.sciencedirect.com/science/article/pii/S0010482521003838},
author = {Harshita Sharma and Lior Drukker and Aris T. Papageorghiou and J. Alison Noble},
}
```
---
