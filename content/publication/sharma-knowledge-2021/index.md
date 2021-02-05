---
title : "Knowledge Representation and Learning of Operator Clinical Workflow from Full-length Routine Fetal Ultrasound Scan Videos"
date : 2021-01-23
authors:
- "__Harshita Sharma__"
- "Lior Drukker"
- "Pierre Chatelain"
- "Richard Droste"
- "Aris T. Papageorghiou"
- "J. Alison Noble"

publication_types: ["2"]

featured: true

publication: "*Medical Image Analysis (Elsevier)*"

abstract: "Ultrasound is a widely used imaging modality, yet it is well-known that scanning can be highly operator-dependent and difficult to perform, which limits its wider use in clinical practice. The literature on understanding what makes clinical sonography hard to learn and how sonography varies in the field is sparse, restricted to small-scale studies on the effectiveness of ultrasound training schemes, the role of ultrasound simulation in training, and the effect of introducing scanning guidelines and standards on diagnostic image quality. The Big Data era, and the recent and rapid emergence of machine learning as a more mainstream large-scale data analysis technique, presents a fresh opportunity to study sonography in the field at scale for the first time. Large-scale analysis of video recordings of full-length routine fetal ultrasound scans offers the potential to characterise differences between the scanning proficiency of experts and trainees that would be tedious and time-consuming to do manually due to the vast amounts of data. Such research would be informative to better understand operator clinical workflow when conducting ultrasound scans to support skills training, optimise scan times, and inform building better user-machine interfaces. This paper is to our knowledge the first to address sonography data science, which we consider in the context of second-trimester fetal sonography screening. Specifically, we present a fully-automatic framework to analyse operator clinical workflow solely from full-length routine second-trimester fetal ultrasound scan videos. An ultrasound video dataset containing more than 200 hours of scan recordings was generated for this study. We developed an original deep learning method to temporally segment the ultrasound video into semantically meaningful segments (the video description). The resulting semantic annotation was then used to depict operator clinical workflow (the knowledge representation). Machine learning was applied to the knowledge representation to characterise operator skills and assess operator variability. For video description, our best-performing deep spatio-temporal network shows favourable results in cross-validation (accuracy: 91.7%), statistical analysis (correlation: 0.98, p < 0.05) and retrospective manual validation (accuracy: 76.4%). For knowledge representation of operator clinical workflow, a three-level abstraction scheme consisting of a Subject-specific Timeline Model (STM), Summary of Timeline Features (STF), and an Operator Graph Model (OGM), was introduced that led to a significant decrease in dimensionality and computational complexity compared to raw video data. The workflow representations were learnt to discriminate between operator skills, where a proposed convolutional neural network-based model showed most promising performance (cross-validation accuracy: 98.5%, accuracy on unseen operators: 76.9%). These were further used to derive operator-specific scanning signatures and operator variability in terms of type, order and time distribution of constituent tasks."

tags:
- Clinical workflow
- Fetal ultrasonography
- Ultrasound image analysis
- Video understanding
- Knowledge representation
- Skill assessment
- Spatio-temporal analysis
- Deep learning
- Convolutional neural networks

links:
- name: DOI
  url: https://doi.org/10.1016/j.media.2021.101973
  icon_pack: ai
  icon: doi
- name: Elsevier
  url: https://www.sciencedirect.com/science/article/abs/pii/S1361841521000190
  icon_pack: fas
  icon: link
- name: BibTeX
  icon_pack: fas
  icon: quote-right
  url: publication/sharma-knowledge-2021/#bibtex 
---

---

# BibTex

```
@article{SHARMA2021101973,
title = "Knowledge Representation and Learning of Operator Clinical Workflow from Full-length Routine Fetal Ultrasound Scan Videos",
journal = "Medical Image Analysis",
volume = "69",
pages = "101973",
year = "2021",
issn = "1361-8415",
doi = "https://doi.org/10.1016/j.media.2021.101973",
url = "http://www.sciencedirect.com/science/article/pii/S1361841521000190",
author = "Harshita Sharma and Lior Drukker and Pierre Chatelain and Richard Droste and Aris T. Papageorghiou and J. Alison Noble",
keywords = "Clinical workflow, fetal ultrasonography, ultrasound image analysis, video understanding, knowledge representation, skill assessment, spatio-temporal analysis, deep learning, convolutional neural networks",
abstract = "Ultrasound is a widely used imaging modality, yet it is well-known that scanning can be highly operator-dependent and difficult to perform, which limits its wider use in clinical practice. The literature on understanding what makes clinical sonography hard to learn and how sonography varies in the field is sparse, restricted to small-scale studies on the effectiveness of ultrasound training schemes, the role of ultrasound simulation in training, and the effect of introducing scanning guidelines and standards on diagnostic image quality. The Big Data era, and the recent and rapid emergence of machine learning as a more mainstream large-scale data analysis technique, presents a fresh opportunity to study sonography in the field at scale for the first time. Large-scale analysis of video recordings of full-length routine fetal ultrasound scans offers the potential to characterise differences between the scanning proficiency of experts and trainees that would be tedious and time-consuming to do manually due to the vast amounts of data. Such research would be informative to better understand operator clinical workflow when conducting ultrasound scans to support skills training, optimise scan times, and inform building better user-machine interfaces. This paper is to our knowledge the first to address sonography data science, which we consider in the context of second-trimester fetal sonography screening. Specifically, we present a fully-automatic framework to analyse operator clinical workflow solely from full-length routine second-trimester fetal ultrasound scan videos. An ultrasound video dataset containing more than 200 hours of scan recordings was generated for this study. We developed an original deep learning method to temporally segment the ultrasound video into semantically meaningful segments (the video description). The resulting semantic annotation was then used to depict operator clinical workflow (the knowledge representation). Machine learning was applied to the knowledge representation to characterise operator skills and assess operator variability. For video description, our best-performing deep spatio-temporal network shows favourable results in cross-validation (accuracy: 91.7%), statistical analysis (correlation: 0.98, p < 0.05) and retrospective manual validation (accuracy: 76.4%). For knowledge representation of operator clinical workflow, a three-level abstraction scheme consisting of a Subject-specific Timeline Model (STM), Summary of Timeline Features (STF), and an Operator Graph Model (OGM), was introduced that led to a significant decrease in dimensionality and computational complexity compared to raw video data. The workflow representations were learnt to discriminate between operator skills, where a proposed convolutional neural network-based model showed most promising performance (cross-validation accuracy: 98.5%, accuracy on unseen operators: 76.9%). These were further used to derive operator-specific scanning signatures and operator variability in terms of type, order and time distribution of constituent tasks."
}
```
---
