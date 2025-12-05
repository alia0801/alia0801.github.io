---
title: "A Two-Stage Anomaly-Aware Framework for Robust Traffic Forecasting with Memory-Guided GNNs"
collection: publications
category: conferences
permalink: /publication/2026-02-22-wsdm-adaop
# excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2026-02-22
venue: 'Proceedings of the 19th ACM International Conference on Web Search and Data Mining'
slidesurl: ''
paperurl: ''
citation: "Pei-Xuan Li, Cheng-Ru Chou, Jhe-Wei Tsai, Hsun-Ping Hsieh. A Two-Stage Anomaly-Aware Framework for Robust Traffic Forecasting with Memory-Guided GNNs. In Proceedings of the 19th ACM International Conference on Web Search and Data Mining (WSDM '26)."
---

Accurate traffic forecasting plays a critical role in modern transportation systems by enabling effective congestion management and route optimization. Although recent deep learning-based models have shown substantial progress in modeling complex spatiotemporal dependencies, most existing methods overlook the challenges posed by anomalous traffic conditions. To address this gap, we propose a two-stage anomaly-aware forecasting correction framework. The first stage employs an unsupervised auto-regressive anomaly detector that combines representation learning and spatiotemporal attention to capture normal traffic patterns and filter anomalous inputs through error thresholding. In the second stage, an anomaly optimization predictor leverages a memory module and a sparsity regularization learning strategy to enhance the representation of normal patterns and suppress noise. It models spatiotemporal dependencies using an information propagation layer composed of sequential small-kernel temporal convolutions and memory-guided graph convolutions. Extensive experiments on real-world traffic flow datasets demonstrate that our framework outperforms state-of-the-art models under anomalous conditions.
