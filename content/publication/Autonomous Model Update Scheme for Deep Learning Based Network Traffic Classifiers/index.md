---
title: Autonomous Model Update Scheme for Deep Learning Based Network Traffic Classifiers
publication_types:
  - "1"
authors:
  - Jielun Zhang
  - Fuhao Li
  - Hongyu Wu
  - Feng Ye
doi: 10.1109/GLOBECOM38437.2019.9014036
publication: 2019 IEEE Global Communications Conference (GLOBECOM)
publication_short: IEEE GLOBECOM 2019
abstract: Network traffic classification is essential in access network for end-to-end network management and measurement such as network intrusion detection, network resource allocation. State-of- the-art Deep Learning based classifiers have high accuracy even when processing encrypted data packets. Such classifiers would need to be updated when a new application is in the network traffic. However, it is challenging to build and label a dataset of the unknown application from active network traffic. In this paper, we propose an autonomous model update scheme to (i) filter the data packets of a new application from active network traffic and build a corresponding training dataset; and (ii) update the current network traffic classifier with transfer learning. In particular, the core of the proposed scheme is a discriminator that consists of a statistical filter and a convolutional neural network based binary classifier to filter and build a dataset of new application packets from active network traffic. Evaluation is conducted based on an open dataset (i.e., ISCX VPN-nonVPN dataset). The results demonstrated that our proposed autonomous classifier update scheme can successfully filter packets of a new application from network traffic and build a corresponding training dataset. Moreover, the packet classifier can be effectively updated through transfer learning. The proposed update scheme can contribute significantly in the access network for further end-to-end network measurement and management.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2020-02-27T20:18:00.000Z
---
