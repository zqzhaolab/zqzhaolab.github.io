---
title: "RaDiT: A Differential Transformer-Based Hybrid Deep Learning Model for Radar Echo Extrapolation"
collection: publications
category: manuscripts
permalink: /publication/2025-06-06-RaDiT A Differential Transformer-Based Hybrid Deep Learning Model for Radar Echo Extrapolation-number-1
#excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2025-06-06
venue: 'Remote Sensing'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://zqzhaolab.github.io/files/RaDiT A Differential Transformer-Based Hybrid Deep Learning Model for Radar Echo Extrapolation.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Zhao Z, Duan C, Song L, et al. MissPred: A Robust Two-Stage Radar Echo Extrapolation Algorithm for Incomplete Sequences[J]. Remote Sensing, 2025, 17(12): 2066.'
---
Radar echo extrapolation, a critical spatiotemporal sequence forecasting task, requires precise modeling of motion trajectories and intensity evolution from sequential radar reflectivity inputs. Contemporary deep learning implementations face two operational limitations: progressive attenuation of predicted echo intensities during autoregressive inference and spectral leakage-induced diffusion at high-intensity echo boundaries. This study presents RaDiT, a hybrid architecture combining differential transformer with adversarial training for radar echo extrapolation. The framework employs a U-Net backbone augmented with vision transformer blocks, utilizing differential attention mechanisms to govern spatiotemporal interactions. Our differential attention mechanism enhances noise suppression under high-threshold conditions, effectively minimizing spurious feature generation while improving metric reliability. A conditional GAN discriminator is integrated to maintain microphysical consistency in generated sequences, simultaneously addressing spectral blurring and intensity dissipation. Comprehensive evaluations demonstrate RaDiT’s superior performance in preserving spatiotemporal coherence and intensity across 0–90 min forecasting horizons. The proposed architecture achieves CSI improvements of 10.23% and 2.88% at 4 × 4 and 16 × 16 spatial pooling scales, respectively, for ≥30 dBZ thresholds on the CMARC dataset compared to PreDiff. To our knowledge, this represents the first successful implementation of differential transformers for radar echo extrapolation.

