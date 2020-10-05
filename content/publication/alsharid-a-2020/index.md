---
title: "A Curriculum Learning Based Approach to Captioning Ultrasound Images"
date: 2020-10-01
authors:
- Mohammad Alsharid*
- Rasheed El-Bouri*
- __Harshita Sharma__
- Lior Drukker
- Aris T. Papageorghiou
- J. Alison Noble

publication_types: ["1"]

abstract: "We present a novel curriculum learning approach to train a natural language processing (NLP) based fetal ultrasound image captioning model. Datasets containing medical images and corresponding textual descriptions are relatively rare and hence, smaller-sized when compared to the datasets of natural images and their captions. This fact inspired us to develop an approach to train a captioning model suitable for small-sized medical data. Our datasets are prepared using real-world ultrasound video along with synchronised and transcribed sonographer speech recordings. We propose a dual-curriculum method for the ultrasound image captioning problem. The method relies on building and learning from curricula of image and text information for the ultrasound image captioning problem. We compare several distance measures for creating the dual curriculum and observe the best performance using the Wasserstein distance for image information and tf-idf metric for text information. The evaluation results show an improvement in all performance metrics when using curriculum learning over stochastic mini-batch training for the individual task of image classification as well as using a dual curriculum for image captioning."

featured: false

publication: "(MA and RE contributed equally.) *Medical Ultrasound, and Preterm, Perinatal and Paediatric Image Analysis. ASMUS 2020, PIPPI 2020.* **Best Presentation Award**"

links:
- name: DOI
  url: https://doi.org/10.1007/978-3-030-60334-2_8
  icon_pack: ai
  icon: doi
- name: Springer
  url: https://link.springer.com/chapter/10.1007/978-3-030-60334-2_8
  icon_pack: ai
  icon: springer
- name: BibTeX
  icon_pack: fas
  icon: quote-right
  url: publication/alsharid-a-2020/#bibtex

---

---
# BibTex

```
@InProceedings{10.1007/978-3-030-60334-2_8,
author="Alsharid, Mohammad
and El-Bouri, Rasheed
and Sharma, Harshita
and Drukker, Lior
and Papageorghiou, Aris T.
and Noble, J. Alison",
editor="Hu, Yipeng
and Licandro, Roxane
and Noble, J. Alison
and Hutter, Jana
and Aylward, Stephen
and Melbourne, Andrew
and Abaci Turk, Esra
and Torrents Barrena, Jordina",
title="A Curriculum Learning Based Approach to Captioning Ultrasound Images",
booktitle="Medical Ultrasound, and Preterm, Perinatal and Paediatric Image Analysis",
year="2020",
publisher="Springer International Publishing",
address="Cham",
pages="75--84",
abstract="We present a novel curriculum learning approach to train a natural language processing (NLP) based fetal ultrasound image captioning model. Datasets containing medical images and corresponding textual descriptions are relatively rare and hence, smaller-sized when compared to the datasets of natural images and their captions. This fact inspired us to develop an approach to train a captioning model suitable for small-sized medical data. Our datasets are prepared using real-world ultrasound video along with synchronised and transcribed sonographer speech recordings. We propose a ``dual-curriculum'' method for the ultrasound image captioning problem. The method relies on building and learning from curricula of image and text information for the ultrasound image captioning problem. We compare several distance measures for creating the dual curriculum and observe the best performance using the Wasserstein distance for image information and tf-idf metric for text information. The evaluation results show an improvement in all performance metrics when using curriculum learning over stochastic mini-batch training for the individual task of image classification as well as using a dual curriculum for image captioning.",
isbn="978-3-030-60334-2"
}

```

---
