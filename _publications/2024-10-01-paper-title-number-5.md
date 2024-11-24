---
title: "Collaborative brightening and amplification of low-light imagery via bi-level adversarial learning"
collection: publications
category: manuscripts
permalink: /publication/2024-10-01-paper-title-number-5
excerpt: 'Poor light conditions constrain the high pursuit of clarity and visible quality of photography especially smartphone devices. Admittedly, existing specific image processing methods, whether super-resolution methods or low-light enhancement methods, can hardly simultaneously enhance the resolution and brightness of low-light images at the same time. This paper dedicates a specialized enhancer with a dual-path modulated-interactive structure to recover high-quality sharp images in conditions of near absence of light, dubbed CollaBA, which learns the direct mapping from low-resolution dark-light images to their high-resolution normal sharp version. Specifically, we construct the generative modulation prior, serving as illuminance attention information, to regulate the exposure level of the neighborhood range. In addition, we construct an interactive degradation removal branch that progressively embeds the generated intrinsic prior to recover high-frequency detail and contrast at the feature level. We also introduce a multi-substrate up-scaler to integrate multi-scale sampling features, effectively addressing artifact-related problems. Rather than adopting the naive time-consuming learning strategy, we design a novel bi-level implicit adversarial learning mechanism as our fast training strategy. Extensive experiments on benchmark datasets — demonstrate our model’s wide-ranging applicability in various ultra-low-light scenarios, across 8 key performance metrics with significant improvements, notably achieving a 35.8% improvement in LPIPS and a 23.1% increase in RMSE. The code will be available at https://github.com/moriyaya/CollaBA.'
date: 2024-10-01
venue: 'Pattern Recognition (PR)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://moriyaya.github.io/files/pr1.pdf'
citation: 'Gao J, Liu Y, Yue Z, et al. Collaborative brightening and amplification of low-light imagery via bi-level adversarial learning[J]. Pattern Recognition, 2024, 154: 110558.'
---

Poor light conditions constrain the high pursuit of clarity and visible quality of photography especially smartphone devices. Admittedly, existing specific image processing methods, whether super-resolution methods or low-light enhancement methods, can hardly simultaneously enhance the resolution and brightness of low-light images at the same time. This paper dedicates a specialized enhancer with a dual-path modulated-interactive structure to recover high-quality sharp images in conditions of near absence of light, dubbed CollaBA, which learns the direct mapping from low-resolution dark-light images to their high-resolution normal sharp version. Specifically, we construct the generative modulation prior, serving as illuminance attention information, to regulate the exposure level of the neighborhood range. In addition, we construct an interactive degradation removal branch that progressively embeds the generated intrinsic prior to recover high-frequency detail and contrast at the feature level. We also introduce a multi-substrate up-scaler to integrate multi-scale sampling features, effectively addressing artifact-related problems. Rather than adopting the naive time-consuming learning strategy, we design a novel bi-level implicit adversarial learning mechanism as our fast training strategy. Extensive experiments on benchmark datasets — demonstrate our model’s wide-ranging applicability in various ultra-low-light scenarios, across 8 key performance metrics with significant improvements, notably achieving a 35.8% improvement in LPIPS and a 23.1% increase in RMSE. The code will be available at https://github.com/moriyaya/CollaBA.