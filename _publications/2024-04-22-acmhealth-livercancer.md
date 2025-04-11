---
title: "Enhancing Robust Liver Cancer Diagnosis: A Contrastive Multi-Modality Learner with Lightweight Fusion and Effective Data Augmentation"
collection: publications
category: manuscripts
permalink: /publication/2024-04-22-acmhealth-livercancer
# excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2024-04-22
venue: 'ACM Transactions on Computing for Healthcare'
slidesurl: ''
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3639414'
citation: "Pei-Xuan Li, Hsun-Ping Hsieh, Yang Fan-Chiang, Ding-You Wu, and Ching-Chung Ko. 2024. Enhancing Robust Liver Cancer Diagnosis: A Contrastive Multi-Modality Learner with Lightweight Fusion and Effective Data Augmentation. ACM Trans. Comput. Healthcare 5, 2, Article 6 (April 2024), 13 pages. https://doi.org/10.1145/3639414"
---

This article explores the application of self-supervised contrastive learning in the medical domain, focusing on classification of multi-modality Magnetic Resonance (MR) images. To address the challenges of limited and hard-to-annotate medical data, we introduce multi-modality data augmentation (MDA) and cross-modality group convolution (CGC). In the pre-training phase, we leverage Simple Siamese networks to maximize the similarity between two augmented MR images from a patient, without a handcrafted pretext task. Our approach also combines 3D and 2D group convolution with a channel shuffle operation to efficiently incorporate different modalities of image features. Evaluation on liver MR images from a well-known hospital in Taiwan demonstrates a significant improvement over previous methods. This work contributes to advancing multi-modality contrastive learning, particularly in the context of medical imaging, offering enhanced tools for analyzing complex image data.