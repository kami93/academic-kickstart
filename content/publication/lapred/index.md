---
draft: false
featured: false
title: "LaPred: Lane-Aware Prediction of Multi-Modal Future Trajectories of
  Dynamic Agents"
date: 2021-03-22
publication: IEEE Conference on Computer Vision and Pattern Recognition (CVPR) 2021
authors:
  - ByeongDo Kim
  - Seong Hyeon Park
  - Seokhwan Lee
  - Elbek Khoshimjonov
  - Dongsuk Kum
  - Junsoo Kim
  - Jeong Soo Kim
  - Jun Won Choi
abstract: In this paper, we address the problem of predicting the future motion
  of a dynamic agent (called target agent) given its present and past states and
  the information on its environment. It is paramount to develop a prediction
  model that can exploit the contextual information in both static and dynamic
  environments around the target agent and output diverse trajectory samples
  meaningful in a traffic context. We propose a novel prediction model, referred
  to as the lane-aware prediction (LaPred) network, which uses the
  instance-level lane entities extracted from a semantic map to predict the
  multi-modal future trajectories. For each lane candidate found in the
  neighborhood of the target agent, LaPred extracts the joint features relating
  the lane and the trajectories of the neighboring agents. Then, the features
  for all lane candidates are fused with the attention weights learned through a
  self-supervised learning task that identifies the lane candidate likely to be
  followed by the target agent. Using the instance-level lane information,
  LaPred can produce the trajectories compliant with the surroundings better
  than 2D raster image-based methods and generate the diverse future
  trajectories given multiple lane candidates. The experiments conducted on the
  public nuScenes dataset and Argoverse dataset demonstrate that the proposed
  LaPred method significantly outperforms the existing prediction models,
  achieving state-of-the-art performance in the benchmarks.
publication_types:
  - "1"
image:
  placement: 1
  caption: "Results"
  focal_point: "Center"
  preview_only: false
---
