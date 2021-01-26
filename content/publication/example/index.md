---
abstract: Network traffic classification is essential in access network for
  end-to-end network management and measurement such as network intrusion
  detection, network resource allocation. State-of-the-art Deep Learning based
  classifiers have high accuracy even when processing encrypted data packets.
  Such classifiers would need to be updated when a new application is in the
  network traffic. However, it is challenging to build and label a dataset of
  the unknown application from active network traffic. In this paper, we propose
  an autonomous model update scheme to (i) filter the data packets of a new
  application from active network traffic and build a corresponding training
  dataset; and (ii) update the current network traffic classifier with transfer
  learning. In particular, the core of the proposed scheme is a discriminator
  that consists of a statistical filter and a convolutional neural network based
  binary classifier to filter and build a dataset of new application packets
  from active network traffic. Evaluation is conducted based on an open dataset
  (i.e., ISCX VPN-nonVPN dataset). The results demonstrated that our proposed
  autonomous classifier update scheme can successfully filter packets of a new
  application from network traffic and build a corresponding training dataset.
  Moreover, the packet classifier can be effectively updated through transfer
  learning. The proposed update scheme can contribute significantly in the
  access network for further end-to-end network measurement and management.
slides: ""
url_pdf: ""
publication_types:
  - "1"
authors:
  - admin
  - Fuhao Li
  - Hongyu Wu
  - Feng Ye
author_notes: []
publication: In 2019 IEEE Global Communications Conference
summary: ""
url_dataset: ""
url_project: ""
publication_short: 2019 IEEE GLOBECOM
url_source: ""
url_video: ""
title: Autonomous Model Update Scheme for Deep Learning Based Network Traffic
  Classifiers
doi: 10.1109/GLOBECOM38437.2019.9014036
featured: false
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2021-01-26T20:08:18.516Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
