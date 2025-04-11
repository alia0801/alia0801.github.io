---
title: "Exploring Feature Fusion from A Contrastive Multi-Modality Learner for Liver Cancer Diagnosis"
collection: publications
category: conferences
permalink: /publication/2023-12-06-sigmmasia-livercancer
# excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2023-12-06
venue: 'Proceedings of the 5th ACM International Conference on Multimedia in Asia'
slidesurl: ''
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3595916.3626383'
citation: "Yang Fan Chiang, Pei-Xuan Li, Ding-You Wu, Hsun-Ping Hsieh, and Ching-Chung Ko. 2024. Exploring Feature Fusion from A Contrastive Multi-Modality Learner for Liver Cancer Diagnosis. In Proceedings of the 5th ACM International Conference on Multimedia in Asia (MMAsia '23). Association for Computing Machinery, New York, NY, USA, Article 14, 1–7. https://doi.org/10.1145/3595916.3626383"
---

Self-supervised contrastive learning has achieved promising results in computer vision, and recently it also received attention in the medical domain. In practice, medical data is hard to collect and even harder to annotate, but leveraging multi-modality medical images to make up for small datasets has proved to be helpful. In this work, we focus on mining multi-modality Magnetic Resonance (MR) images to learn multi-modality contrastive representations. We first present multi-modality data augmentation (MDA) to adapt contrastive learning to multi-modality learning. Then, the proposed cross-modality group convolution (CGC) is used for multi-modality features in the downstream fine-tune task. Specifically, in the pre-training stage, considering different behaviors from each MRI modality with the same anatomic structure, yet without designing a handcrafted pretext task, we select two augmented MR images from a patient as a positive pair, and then directly maximize the similarity between positive pairs using Simple Siamese networks. To further exploit multi-modality representation, we combine 3D and 2D group convolution with a channel shuffle operation to efficiently incorporate different modalities of image features. We evaluate our proposed methods on liver MR images collected from a well-known hospital in Taiwan. Experiments show our framework has significantly improved from previous methods.
