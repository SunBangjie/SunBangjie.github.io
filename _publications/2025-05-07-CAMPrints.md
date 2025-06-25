---
title: "CAMPrints: Leveraging the \"Fingerprints\" of Digital Cameras to Combat Image Theft"
collection: publications
permalink: /publication/2025-05-07-CAMPrints
excerpt: 
date: 2025-05-07
venue: "The 23rd ACM International Conference on Mobile Systems, Applications, and Services (MobiSys '25)"
paperurl: 
citation: "Bangjie Sun, Mun Choon Chan, and Jun Han. 2025. CAMPrints: Leveraging the “Fingerprints” of Digital Cameras to Combat Image Theft. In The 23rd Annual International Conference on Mobile Systems, Applications and Services (MobiSys ’25), June 23–27, 2025, Anaheim, CA, USA. ACM, New York, NY, USA, 14 pages."
---
Bangjie Sun, Mun Choon Chan, and Jun Han. 2025. CAMPrints: Leveraging the “Fingerprints” of Digital Cameras to Combat Image Theft. In The 23rd Annual International Conference on Mobile Systems, Applications and Services (MobiSys ’25), June 23–27, 2025, Anaheim, CA, USA. ACM, New York, NY, USA, 14 pages. \[[paper](https://sunbangjie.github.io/files/CAMPrints.pdf)\]\[[poster](https://sunbangjie.github.io/files/CAMPrintsPoster.pdf)\]


Abstract
=====
Photo sharing is increasingly popular, driven by social media platforms like Instagram and services such as Flickr and Google Photos. However, this growth has been accompanied by significant issues, particularly image theft. To address this issue, we introduce CAMPrints, a robust system for detecting image theft. CAMPrints verifies whether edited images found online contain camera fingerprints matching those of user-provided reference images. The system overcomes the challenges of identifying images altered by diverse image processing operations. We select a small yet representative set of operations by categorizing them based on their impact on pixel values and locations. A deep-learning model is trained to recognize and compare camera noise patterns pre- and post-editing. We conduct real-world evaluations involving 36 cameras across eight make-and-model combinations, along with over 40 image processing operations applied to more than 4,000 images. CAMPrints achieves an average AUC of 0.92, significantly outperforming the state-of-the-art methods by up to 1.8 times.