---
title: "Sensing Intrusion Detection for Automatic Driving System based on Scene Semantic Centroid"
collection: publications
category: conferences
permalink: /publication/2022-09-01-Sensing Intrusion Detection for Automatic Driving System based on Scene Semantic Centroid-number-1
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2022-09-01
venue: '2022 IEEE 25th International Conference on Intelligent Transportation Systems (ITSC)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9922532'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Zhao Z, Duan C, Song L, et al. MissPred: A Robust Two-Stage Radar Echo Extrapolation Algorithm for Incomplete Sequences[J]. Remote Sensing, 2025, 17(12): 2066.'
---
Sensing intrusion is a new threat to information security of automatic driving system, which employs digital noise like adversarial sample to show sensors fake information, aiming to mislead decision making and eventually achieve the hacker's illegal intention. Unfortunately, it is difficult for most traditional information security techniques to deal with this novel risk. Even if the methods like outlier detection can pick out the abnormal sensing data, they still hardly tell the samples containing adversarial noise. In this paper, a method based on semantic similarity check is proposed to address this issue. Scene semantic centroid is introduced to represent the core semantics of a category of driving scene. Correspondingly, each component of the centroid is used to depict the standard sensing semantics for each sensor in this kind of scene. On this basis, a straightforward algorithm is proposed to simultaneously detect both abnormal driving scene and the sensors that may be hacked. Considering the raw sensing semantic space is too high dimensional and too sparse to handle efficiently, a scene semantic autoencoder is developed to extract scene semantic centroid by semantic embedding. The experiments on Nuscenes dataset show that the proposed method is not only feasible to identify the suspicious intruded sensors, but also more effective and accurate than the traditional abnormal sensing data detection.

