---
title: "Weakly Supervised Captioning of Ultrasound Images"
date: 2022-07-25
authors:
- Mohammad Alsharid
- __Harshita Sharma__
- Lior Drukker
- Aris T. Papageorgiou
- J. Alison Noble

publication_types: ["1"]

featured: false

publication: "*Annual Conference on Medical Image Understanding and Analysis (MIUA) 2022*"

abstract: "Medical image captioning models generate text to describe the semantic contents of an image, aiding the non-experts in understanding and interpretation. We propose a weakly-supervised approach to improve the performance of image captioning models on small image-text datasets by leveraging a large anatomically-labelled image classification dataset. Our method generates pseudo-captions (weak labels) for caption-less but anatomically-labelled (class-labelled) images using an encoder-decoder sequence-to-sequence model. The augmented dataset is used to train an image-captioning model in a weakly supervised learning manner. For fetal ultrasound, we demonstrate that the proposed augmentation approach outperforms the baseline on semantics and syntax-based metrics, with nearly twice as much improvement in value on BLEU-1 and ROUGE-L. Moreover, we observe that superior models are trained with the proposed data augmentation, when compared with the existing regularization techniques. This work allows seamless automatic annotation of images that lack human-prepared descriptive captions for training image-captioning models. Using pseudo-captions in the training data is particularly useful for medical image captioning when significant time and effort of medical experts is required to obtain real image captions."

tags:
- Image captioning
- Fetal ultrasound
- Data augmentation
- Weakly supervised captioning

links:
- name: DOI
  url: https://doi.org/10.1007/978-3-031-12053-4_14
  icon_pack: ai
  icon: doi
- name: Springer
  url: https://link.springer.com/chapter/10.1007/978-3-031-12053-4_14
  icon_pack: fas
  icon: link
- name: BibTeX
  icon_pack: fas
  icon: quote-right
  url: publication/alsharid-weakly-2022/#bibtex 
---

---

# BibTex

```
@InProceedings{Alsharid2022,
author="Alsharid, Mohammad
and Sharma, Harshita
and Drukker, Lior
and Papageorgiou, Aris T.
and Noble, J. Alison",
editor="Yang, Guang
and Aviles-Rivero, Angelica
and Roberts, Michael
and Sch{\"o}nlieb, Carola-Bibiane",
title="Weakly Supervised Captioning ofÂ Ultrasound Images",
booktitle="Medical Image Understanding and Analysis",
year="2022",
publisher="Springer International Publishing",
address="Cham",
pages="187--198",
abstract="Medical image captioning models generate text to describe the semantic contents of an image, aiding the non-experts in understanding and interpretation. We propose a weakly-supervised approach to improve the performance of image captioning models on small image-text datasets by leveraging a large anatomically-labelled image classification dataset. Our method generates pseudo-captions (weak labels) for caption-less but anatomically-labelled (class-labelled) images using an encoder-decoder sequence-to-sequence model. The augmented dataset is used to train an image-captioning model in a weakly supervised learning manner. For fetal ultrasound, we demonstrate that the proposed augmentation approach outperforms the baseline on semantics and syntax-based metrics, with nearly twice as much improvement in value on BLEU-1 and ROUGE-L. Moreover, we observe that superior models are trained with the proposed data augmentation, when compared with the existing regularization techniques. This work allows seamless automatic annotation of images that lack human-prepared descriptive captions for training image-captioning models. Using pseudo-captions in the training data is particularly useful for medical image captioning when significant time and effort of medical experts is required to obtain real image captions.",
isbn="978-3-031-12053-4"
}

```
