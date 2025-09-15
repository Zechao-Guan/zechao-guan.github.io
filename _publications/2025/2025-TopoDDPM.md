---
title:          "TopoDDPM: Diffusion Probabilistic Models using Persistent Homology for 3D Point Cloud Generation"
date:           2025-07-01 00:01:00 +0800
selected:       true
#pub:            ""
#pub_pre:        ""
pub_post:       'UnderReview'
#pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
  Recently, diffusion model has emerged as a powerful paradigm for 3D point cloud generation. However, existing methods primarily focus on local geometric features while neglecting global topological features that are critical for structural fidelity, resulting in incomplete structures of the generated results. To address these limitations, we propose TopoDDPM, a novel diffusion probabilistic model that explicitly integrates persistent homology to improve the structural quality of the generated point clouds. Specifically, we introduce a topology latent, extracted by persistent homology, and a shape latent, parameterized through a normalizing flow. These serve as the conditions during the denoising process, enabling the model to learn both geometric and topological characteristics. Additionally, we design a topological loss function to enforce structural consistency throughout the diffusion process. Experimental results on the ShapeNet dataset demonstrate that TopoDDPM outperforms most existing methods in terms of fidelity, diversity, and training efficiency, while better preserving topological integrity. Furthermore, TopoDDPM highlights the importance of rich topological information in improving 3D point cloud generation.

cover:  assets/images/covers/2025-TopoDDPM.PNG
authors:
  - Zechao Guan*
  - Shuai Du*
  - Qingshan Liu#

links:
# Paper: https://arxiv.org/abs/2505.09140
# Code: https://github.com/Zechao-Guan/TopoDiT-3D
# Videos: https://github.com/Zechao-Guan/TopoDiT-3D
#  Unsplash: https://unsplash.com/photos/sliced-in-half-pineapple--_PLJZmHZzk
---
