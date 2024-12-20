---
title: "Learning Adaptive Hyper-guidance via Proxy-based Bilevel Optimization for Image Enhancement"
collection: publications
category: manuscripts
permalink: /publication/2022-02-21-paper-title-number-6
excerpt: 'In recent years, image enhancement based on deep network plays a vital role and has become the mainstream research. However, current approaches are generally limited to the manual embedding of auxiliary components (e.g., hyper-parameters, appended modules) to train the network; thus, they can often lack flexibility, adaptability, or even fail to achieve the optimal settings. ...'
date: 2022-02-21
venue: 'The Visual Computer (TVC)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://moriyaya.github.io/files/tvc1.pdf'
citation: '<strong>Jiaxin Gao</strong>, Xiaokun Liu, Risheng Liu, et al. Learning adaptive hyper-guidance via proxy-based bilevel optimization for image enhancement[J]. The Visual Computer, 2023, 39(4): 1471-1484.'
---

In recent years, image enhancement based on deep network plays a vital role and has become the mainstream research. However, current approaches are generally limited to the manual embedding of auxiliary components (e.g., hyper-parameters, appended modules) to train the network; thus, they can often lack flexibility, adaptability, or even fail to achieve the optimal settings. Moreover, the straightforward learning-based architectures cannot adequately handle the complex latent image distributions in real-world scenarios. To partially address the above issues, in this work, a generic adaptive hyper-training scheme based on bilevel optimization is established. Specifically, we propose a completely new bilevel deep-unfolded strategy to collaboratively optimize the inner-level task-related hyper-guidance and the outer-level image reconstruction. The process can embed the differentiable proxy-based network with parameters to automatically learn the appended control mechanism. Instead of constructing the empirically manual interventions, our strategy can proactively learn to learn self-adaptive auxiliary modules. Extensive experiments demonstrate the superiority of our strategy to address different image enhancement tasks (i.e., image restoration, image rain removal and image haze removal) in terms of flexibility and effectiveness.