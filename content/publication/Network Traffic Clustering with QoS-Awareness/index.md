---
title: Network traffic clustering with QoS-awareness
publication_types:
  - "0"
authors:
  - Jielun Zhang
  - Fuhao Li
  - Feng Ye
doi: 10.23919/JCC.2022.03.015
publication: IEEE/CIC China Communications ( Volume: 19, Issue: 3, March 2022) 
publication_short: IEEE/CIC China Communication
abstract: Network traffic classification is essential in supporting network measurement and management. Many existing traffic classification approaches provide application-level results regardless of the network quality of service (QoS) requirements. In practice, traffic flows from the same application may have irregular network behaviors that should be identified to various QoS classes for best network resource management. To address the issues, we propose to conduct traffic classification with two newly defined QoS-aware features, i.e., inter-APP similarity and intra-APP diversity. The inter-APP similarity represents the close QoS association between the traffic flows that originate from the different Internet applications. The intra-APP diversity describes the QoS variety of the traffic even among those originated from the same Internet application. The core of performing the QoS-aware feature extraction is a Long-Short Term Memory neural network based Autoencoder (LSTM-AE). The QoS-aware features extracted by the encoder part of the LSTM-AE are then clustered into the corresponding QoS classes. Real-life data from multiple applications are collected to evaluate the proposed QoS-aware network traffic classification approach. The evaluation results demonstrate the efficacy of the extracted QoS-aware features in supporting the traffic classification, which can further contribute to future network measurement and management.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2022-03-30T20:18:00.000Z
---
