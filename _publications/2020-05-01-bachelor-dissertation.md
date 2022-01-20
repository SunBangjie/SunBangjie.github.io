---
title: "A Real-time Caustics and Global illumination Rendering Framework with RTX Technology"
collection: publications
permalink: /publication/2020-05-01-bachelor-dissertation
excerpt: 
date: 2020-05-01
venue: "Bachelor's Dissertation, National University of Singapore"
paperurl: 
citation: "Bangjie Sun. 2020. A Real-time Caustics and Global illumination Rendering Framework with RTX Technology. Bachelor's Dissertation, National University of Singapore."
---
**Bangjie Sun.** 2020. *A Real-time Caustics and Global illumination Rendering Framework with RTX Technology.* Bachelor's Dissertation, National University of Singapore. \[[paper](https://sunbangjie.github.io/files/FYP.pdf)\] \[[repo](https://github.com/SunBangjie/FYP-BidirectionalPathTracer)\]


Abstract
=====
This dissertation presents a robust and noise-free rendering framework capable of generating caustics and global illumination in real time. It realizes path integral formulation of light transport with Microsoft’s DirectX Raytracing (DXR) application programming interfaces (APIs) and NVIDIA GeForce RTX 20-series GPUs. The NVIDIA RTX technology, by building ray-tracing cores in the GPU hardware, optimizes and accelerates the testing of intersections between rays and geometries such as triangle patches. It, in turn, greatly improves the speed of techniques like path-tracing, bidirectional path-tracing and photon mapping, which were mostly used in offline rendering and needed hours or even days to render photo-realistic images. However, in order to keep rendering within the real-time budget, the total number of rays spawn is still limited. Due to such limitation in sampling, the resultant image will contain an observable amount of noise, which can be visually unsatisfying. It then requires denoising techniques to remove the noise and reconstruct the image. We can see the application of path-tracing and A-SVGF in games such as Quake II RTX, where good image quality and real-time performance can be achieved. However, since the denoising quality is highly dependent on the noise level of the source image, we see opportunities where low-variance rendering techniques such as bidirectional path-tracing can be adopted to further reduce the noise in the source image. We conduct several experiments to compare image quality and rendering speed of various scenes, and perform algorithmic analysis on the rendering techniques.