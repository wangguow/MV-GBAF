## **MV-GBAF:** **Multi-View Granular-Ball Attention Fusion Network for Robust Brain Disease Classification**



This repository contains the code for the paper "MV-GBAF: Multi-View Granular-Ball Attention Fusion Network for Robust Brain Disease Classification".

### Abstract

Functional connectivity (FC) networks derived from resting-state functional magnetic resonance imaging (rs-fMRI) provide a noninvasive basis for brain disorder classification. However, their analysis faces two complementary challenges: subject-level heterogeneity in the informativeness of FC views and local topological noise arising from physiological fluctuations and head-motion artifacts. Static fusion strategies offer limited adaptation to individual network organization, while conventional graph message passing can propagate noise through unreliable connections. To address both challenges, we propose the multi-view granular-ball attention fusion network (MV-GBAF), an end-to-end framework combining granular-ball graph convolution with reliability-gated multi-view attention fusion (RG-MAF). Within each view, adaptive soft clustering organizes node neighborhoods into granular-ball units whose centers and radii guide aggregation, capturing local functional coherence while mitigating noise propagation. Across views, RG-MAF uses graph-level representations and topological reliability statistics to refine global view weights through subject-specific residual corrections. Experiments on four public multicenter datasets, ADNI, ADHD-200, ABIDE, and REST-meta-MDD, demonstrate improved classification performance over the evaluated baselines. On ADNI, MV-GBAF achieves an accuracy of 91.29% and an area under the receiver operating characteristic curve of 92.97%. Whole-brain region-of-interest occlusion analysis identifies regions contributing to model predictions, including the supplementary motor area, fusiform gyrus, and precuneus. These findings support the value of combining locally coherent graph representations with subject-adaptive fusion for brain disorder classification.



