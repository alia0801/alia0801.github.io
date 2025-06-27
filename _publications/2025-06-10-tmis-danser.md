---
title: "Dual Attention with Self-Adaptive Negative Sampling for Session-Based Recommendation"
collection: publications
category: manuscripts
permalink: /publication/2025-06-10-tmis-danser
# excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2025-06-10
venue: 'ACM Transactions on Management Information Systems'
slidesurl: ''
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3744348'
citation: "Yu-Chen Chen, Pei-Xuan Li, Hsun-Ping Hsieh, and Chris Shei. 2025. Dual Attention with Self-Adaptive Negative Sampling for Session-Based Recommendation. ACM Trans. Manage. Inf. Syst. Just Accepted (June 2025). https://doi.org/10.1145/3744348"
---

In the rapidly evolving landscape of online platforms and e-commerce websites, personalized recommendation plays a crucial role in optimizing user experience. Unlike traditional recommender systems that rely on users’ historical records, session-based recommendation systems aim to provide recommendations to anonymous users without requiring them to log in or expose their personal information. Recently, Graph Neural Networks (GNNs) have gained considerable attention in this field due to their effectiveness and remarkable performance. These graph-based methods often adopt a two-stage process that involves learning static item embeddings in the first stage and using these fixed embeddings to generate user intent in the second stage. However, this two-stage approach failed to leverage the hidden states of each item during information propagation, neglecting the item transitions within varying receptive fields. In this study, we propose a novel framework named Dual Attention with Self-Adaptive Negative Sampling for Session-based Recommendation (DANSeR). Our model employs a dual attention mechanism to capture complex user intent within different receptive fields. Also, we strengthen the discriminative power of our model by adaptively selecting the hard negatives for each session. Furthermore, we incorporate the user behavior on the item set for normalization to achieve personalized recommendations. Extensive experiments on five benchmark datasets demonstrate the superiority of DANSeR over existing session-based recommendation models.
