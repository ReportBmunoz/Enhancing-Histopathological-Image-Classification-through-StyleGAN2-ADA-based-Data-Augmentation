# Proyect Enhancing-Histopathological-Image-Classification-through-StyleGAN2-ADA-based-Data-Augmentation

## Abstract

The precise classification of histopathological images is crucial for the diagnosis and treatment of cancer, yet it is often limited by
the scarcity of labeled data. This study investigates the efficacy of using
StyleGAN2-ADA (Adaptive Discriminator Augmentation) for data augmentation in histopathological image classification. Our objectives were:
(1) to evaluate the capability of StyleGAN2-ADA to generate realistic
synthetic histopathological images, (2) to implement a data augmentation strategy using these images, and (3) to compare the performance
of a binary classifier trained with and without the proposed augmentation. The methodology involved training StyleGAN2-ADA in a highperformance computing (HPC) environment to generate high-quality
synthetic images, which were then used to augment histopathological
datasets. Binary classifiers were trained using the augmented datasets
for the PCAM and IDC datasets, and their performance was compared
to classifiers trained only with original data. Results showed a significant improvement in classifier accuracy, with a 5.9% increase in ROC
(AUC) for the PCAM dataset at 3% data availability and an 11.3% increase at 20% data availability. For the IDC dataset, the ROC (AUC)
improved by 3.4% at 3% data availability and by 2.4% at 20% data
availability. Notable enhancements were observed in cancer class metrics, particularly in low-data scenarios, demonstrating the effectiveness
of StyleGAN2-ADA in improving classifier robustness and generalization. We conclude that StyleGAN2-ADA is an effective tool for generating high-quality synthetic histopathological images and that the proposed data augmentation strategy substantially enhances classifier performance. This approach addresses the data scarcity in histopathology,
improving the robustness and generalization of classification models in
this critical medical field. Furthermore, it highlights the importance of
HPC in accelerating deep learning research applied to complex medical
problems.

## Comments

1. The jupyter file contains an example for reproducibility
2. Downloading this [file.zip](https://drive.google.com/file/d/1WoWJgM1OrvlHc88gznvGkP1RwRH51p7g/view?usp=sharing) you can use stylegan 2 ada models trained on PCAM and IDC. (They are the ones used in the paper and in the example Jupyter notebook)
