---
title:          "FastAvatar: Towards Unified and Fast 3D Avatar Reconstruction with Large Gaussian Reconstruction Transformers"
date:           2026-01-27 20:00:00 +0800
selected:       true
pub:            "International Conference on Learning Representations (ICLR)"
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2026"
semantic_scholar_id: cc2bf0662651d96bde60595597624d8511dd1e8c  # use this to retrieve citation count
abstract: >-
  Despite significant progress in 3D avatar reconstruction, it still faces challenges such as high time complexity, sensitivity to data quality, and low data utilization. We propose <strong>FastAvatar</strong>, a feedforward 3D avatar framework capable of flexibly leveraging diverse daily recordings (e.g., a single image, multi-view observations, or monocular video) to reconstruct a high-quality 3D Gaussian Splatting (3DGS) model within seconds, using only a single unified model. The core of FastAvatar is a Large Gaussian Reconstruction Transformer (LGRT) featuring three key designs: First, a 3DGS transformer aggregating multi-frame cues while injecting initial 3D prompt to predict the corresponding registered canonical 3DGS representations; Second, multi-granular guidance encoding (camera pose, expression coefficient, head pose) mitigating animation-induced misalignment for variable-length inputs; Third, incremental Gaussian aggregation via landmark tracking and sliced fusion losses. Integrating these features, FastAvatar enables incremental reconstruction, i.e., improving quality with more observations without wasting input data as in previous works. This yields a quality-speed-tunable paradigm for highly usable 3D avatar modeling. Extensive experiments show that FastAvatar has a higher quality and highly competitive speed compared to existing methods.
cover: /assets/images/covers/FastAvatar.jpg
authors:
  - Yue Wu
  - Xuanhong Chen
  - Yufan Wu
  - Wen Li
  - Yuxi Lu
  - Kairui Feng
links:
  Code: https://github.com/TyrionWuYue/FastAvatar
  Paper: https://arxiv.org/abs/2508.19754
  Project Page: https://tyrionwuyue.github.io/project_FastAvatar/
---

<!-- 
---
title:          "Convallis a cras semper auctor neque vitae rutrum quisque non tellus orci ac"
date:           2024-05-12 00:01:00 +0800
selected:       true
pub:            "International Conference on Machine Learning (ICML)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"
semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776  # use this to retrieve citation count
abstract: >-
  Photo by Pineapple Supply Co. on Unsplash. Please put a tldr (too-long-didnt-read, 1~2 sentences) of your publication here. It is not recommended to put the actual abstract here because it is usually too long to fit in. $\LaTeX$ is supported. $a=b+c$.
cover:          /assets/images/covers/cover3.jpg
authors:
  - Your Name
  - James Wang
  - Some Other Name
  - John Doe
links:
  Code: https://github.com/luost26/academic-homepage
  Unsplash: https://unsplash.com/photos/sliced-in-half-pineapple--_PLJZmHZzk
---
-->
