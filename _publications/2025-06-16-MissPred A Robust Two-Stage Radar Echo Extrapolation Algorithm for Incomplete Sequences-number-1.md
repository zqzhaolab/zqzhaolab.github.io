---
title: "MissPred: A Robust Two-Stage Radar Echo Extrapolation Algorithm for Incomplete Sequences"
collection: publications
category: manuscripts
permalink: /publication/2025-06-16-paper-title-number-1
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2025-06-16
venue: 'Remote Sensing'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://zqzhaolab.github.io/files/MissPred A Robust Two-Stage Radar Echo Extrapolation Algorithm for Incomplete Sequences.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Zhao Z, Duan C, Song L, et al. MissPred: A Robust Two-Stage Radar Echo Extrapolation Algorithm for Incomplete Sequences[J]. Remote Sensing, 2025, 17(12): 2066.'
---
Radar echo extrapolation based on real-world data is a fundamental problem
in meteorological forecasting. Existing extrapolation models typically assume complete
radar echo sequences, but in practice, data loss frequently occurs due to equipment failures
and communication disruptions. Although traditional solutions can handle missing values
through a interpolation-then-prediction pipeline, they suffer from a major limitation: interpolating the missing data and then extrapolating will introduce a cumulative error. To
address these issues, we propose MissPred, a radar echo extrapolation model specifically
designed for missing data patterns. MissPred employs a dual encoder–decoder architecture.
Specifically, the training process involves the sequential execution of interpolation and
extrapolation as two distinct serial tasks. In order to circumvent the occurrence of cumulative errors, interpolation and extrapolation are required to share encoder parameters.
Furthermore, a missing spatiotemporal feature fusion module (MSTF) that is absent has
been designed for the purpose of extracting fine-grained complete spatiotemporal features.
Finally, the incorporation of adversarial training is introduced to enhance the authenticity of
the prediction results. In order to evaluate the proposed model, case studies are conducted
on real radar datasets. Our dataset covers missing rates ranging from 10% to 50%. The
experimental results show that the model outperforms the baseline model with the prior
interpolation of missing data in the missing mode with stable robustness.
