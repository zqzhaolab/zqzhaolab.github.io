---
title: "Hierarchical Traffic Flow Prediction Model Based on Graph Autoencoder and GRUNetwork"
collection: publications
category: manuscripts
permalink: /publication/2024-6-15-Hierarchical Traffic Flow Prediction Model Based on Graph Autoencoder and GRUNetwork-number-1
#excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-06-15
venue: 'Computer Science'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://kns.cnki.net/kcms2/article/abstract?v=G9uEhVDeKuLnlDOmICwqK5A0RvmP1we762SP9w9kkbtpwC2ZPbtfUsLdlva9fh7HHFS4VdinRgpwKEKBzTO3Cr6UWoWB7lQbjD6tKpOZ85-RC0CjOWTZKHI6wXJe442Lom0l9sG7-h2engS-uurYjJyNIVNTQmu7EL_xD2PWD6wvaREWVA5bTQ==&uniplatform=NZKPT&language=CHS'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Zhao Z, Duan C, Song L, et al. MissPred: A Robust Two-Stage Radar Echo Extrapolation Algorithm for Incomplete Sequences[J]. Remote Sensing, 2025, 17(12): 2066.'
---
Accurate traffic flow prediction information not only provides traffic administrator with a strong foundation for traffic decisions, but also eases congestion. In traffic flow forecasting tasks, obtaining valid spatiotemporal characteristics of the traffic flow is a prerequisite to ensure the effectiveness of the forecast. Most of the existing methods use data from future moments for supervised learning, and the extracted features have limitations. To address the problem that existing prediction models cannot fully exploit the spatiotemporal characteristics of traffic flows, this paper proposes a hierarchical traffic prediction model based on an improved graph autoencoder and gated recurrent unit. The graph attention autoencoder is first used to deeply explore the spatial characteristics of the traffic flow in an unsupervised manner, and then the gated recurrent unit is used to extract temporal features. The hierarchical structure uses separate training for learning spatio-temporal dependencies, aiming to capture the naturally existing spatial topological features of the road network and make it compatible with traffic flow prediction tasks at different time steps. Extensive experiments demonstrate that the proposed GAE-GRU model achieves excellent performance in traffic prediction tasks on different datasets, with MAE, RMSE and MAPE outperforming the baseline model.