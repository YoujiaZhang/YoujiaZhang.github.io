---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a PhD Student at the [School of Computer Science and Technology, Huazhong University of Science and Technology](http://www.cs.hust.edu.cn/), in the [HUST Media Lab](http://media.hust.edu.cn), advised by Prof. [Wei Yang](https://weiyang-hust.github.io/). My research focuses on the intersection of Computer Vision, Graphics, and Neural Rendering.

I am now a visiting student at [Inception3D Lab](http://www.inception3d.fun/), Westlake University, under the supervision of Prof. [Anpei Chen](https://apchenstu.github.io/).

# Services
- Conference Reviewer: CVPR, ICCV, NeurIPS, ICLR, ICML, ICME, AISTATS.

<span class='anchor' id='-publications'></span>

# Publications 
\* Equal contribution. † denotes corresponding author.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/Ref-GS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Ref-GS: Directional Factorization for 2D Gaussian Splatting](https://ref-gs.github.io/)

**Youjia Zhang**, Anpei Chen †, Yumin Wan, Zikai Song, Junqing Yu, Yawei Luo, Wei Yang †  
<em>Computer Vision and Pattern Recognition (CVPR), 2025</em>  
<em>Chinese Congress on Image and Graphics (CCIG), 2025 (Spotlight)</em>  

[**Project**](https://ref-gs.github.io/) | [**Code**](https://github.com/YoujiaZhang/Ref-GS) | [**Slides**](images/CCIG2025-Spotlight-Ref-GS-youjiazhang@hust.edu.cn.pdf)
- We propose Ref-GS, a method for directional light factorization in 2D Gaussian splatting, enabling photorealistic rendering and accurate geometry recovery. By applying directional encoding and spherical mip-grids, it reduces ambiguity and enhances roughness-aware shading. Our approach minimizes overhead and improves performance across open-world scenes.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2025</div> <video width="100%" height="100%" playsinline autoplay loop muted> <source src="images/USD.mp4" type="video/mp4"> </video> </div></div>
<div class='paper-box-text' markdown="1">

[Optimized View and Geometry Distillation from Multi-view Diffuser](https://youjiazhang.github.io/USD/)

**Youjia Zhang**, Zikai Song, Junqing Yu, Yawei Luo, Wei Yang †  
<em>International Joint Conference on Artificial Intelligence (IJCAI), 2025</em>

[**Project**](https://youjiazhang.github.io/USD/) | [**Code**](https://github.com/YoujiaZhang/USD)
- We propose USD, a method for consistent single-to-multi-view image synthesis and geometry recovery using image-conditioned diffusion and radiance fields. By treating the radiance field optimized during geometry extraction as a rigid multi-view consistency prior and introducing Unbiased Score Distillation (USD)—which leverages unconditioned noise from a 2D diffusion model to correct traditional optimization bias—we greatly enhance radiance field fidelity. Our two-step specialization of the 2D diffuser then performs object-specific denoising to generate high-quality multi-view images, from which we directly recover accurate geometry and texture. The result matches state-of-the-art performance on extensive datasets while preserving full freedom of camera positioning.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2025</div><img src='images/CA-Diff.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CA-Diff: Collaborative Anatomy Diffusion for Brain Tissue Segmentation](https://youjiazhang.github.io/)

Qilong Xing, Zikai Song*, Yuteng Ye, Yuke Chen, **Youjia Zhang**, Na Feng, Junqing Yu, Wei Yang †  
<em>International Conference on Multimedia & Expo (ICME), 2025</em>

[**Paper**](https://youjiazhang.github.io/) | [**Code**](https://youjiazhang.github.io/)
- We propose Collaborative Anatomy Diffusion (CA-Diff), a framework integrating spatial anatomical features to enhance segmentation accuracy of the diffusion model.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/reid.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic feature pruning and consolidation for occluded person re-identification](https://ojs.aaai.org/index.php/AAAI/article/view/28491)

YuTeng Ye, Jiale Cai, Chenxing Gao, **Youjia Zhang**, Junle Wang, Qiang Hu, Junqing Yu, Wei Yang †  
<em>AAAI Conference on Artificial Intelligence (AAAI), 2024</em>

[**Paper**](https://arxiv.org/pdf/2211.14742) | [**Code**](https://github.com/babahui/FPC)
- We propose a Feature Pruning and Consolidation (FPC) framework to circumvent explicit human structure parse, which consists of a sparse encoder, a global and local feature ranking module, and a feature consolidation decoder.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/pt2i.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Progressive Text-to-Image Diffusion with Soft Latent Direction](https://arxiv.org/abs/2309.09466)

YuTeng Ye, Jiale Cai, Hang Zhou, Guanwen Li, **Youjia Zhang**, Zikai Song, Chenxing Gao, Junqing Yu, Wei Yang †  
<em>AAAI Conference on Artificial Intelligence (AAAI), 2024</em>

[**Paper**](https://arxiv.org/pdf/2309.09466) | [**Code**](https://github.com/babahui/Progressive-Text-to-Image)
- We propose to harness the capabilities of a Large Language Model (LLM) to decompose text descriptions into coherent directives adhering to stringent formats and progressively generate the target image.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/AMD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AMD: anatomical motion diffusion with interpretable motion decomposition and fusion](https://arxiv.org/abs/2312.12763)

Beibei Jing, **Youjia Zhang**, Zikai Song, Junqing Yu, Wei Yang †  
<em>AAAI Conference on Artificial Intelligence (AAAI), 2024</em>

[**Paper**](https://arxiv.org/pdf/2312.12763)
- We propose the Adaptable Motion Diffusion (AMD) model, which leverages a Large Language Model (LLM) to parse the input text into a sequence of concise and interpretable anatomical scripts that correspond to the target motion.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/NeMF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[NeMF: Inverse volume rendering with neural microflake field](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_NeMF_Inverse_Volume_Rendering_with_Neural_Microflake_Field_ICCV_2023_paper.pdf)

**Youjia Zhang**, Teng Xu, Junqing Yu, Yuteng Ye, Yanqing Jing, Junle Wang, Jingyi Yu, Wei Yang †  
<em>International Conference on Computer Vision (ICCV), 2023</em>

[**Project**](https://youjiazhang.github.io/NeMF/) | [**Code**](https://github.com/YoujiaZhang/NeMF)
- We propose to conduct inverse volume rendering by representing a scene using microflake volume, which assumes the space is filled with infinite small flakes and light reflects or scattersat each spatial location according to microflake distributions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Communications Chemistry</div><img src='images/SigmaCCS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Highly accurate and large-scale collision cross sections prediction with graph neural networks](https://www.nature.com/articles/s42004-023-00939-w)

Renfeng Guo\*, **Youjia Zhang\***, Yuxuan Liao\*, Qiong Yang, Ting Xie, Xiaqiong Fan, Zhonglong Lin, Yi Chen, Hongmei Lu †, Zhimin Zhang †  
<em>Communications Chemistry (JCR Q1), 2023</em>

[**Code**](https://github.com/YoujiaZhang/SigmaCCS)
- We present SigmaCCS, a graph neural network-based method for CCS prediction from 3D conformers. It achieves high accuracy and chemical interpretability, enabling large-scale in-silico CCS estimation.
</div>
</div>

<span class='anchor' id='-honors-and-awards'></span>

# Honors and Awards
- *2023*: China National Scholarship (Top 1%).
- *2021*: Outstanding Graduates of Central South University.

<span class='anchor' id='-educations'></span>

# Educations
- *2017.09 - 2021.06*, Undergraduate, Central South University.
- *2021.09 - 2023.06*, Master, Huazhong University of Science and Technology.
- *2023.09 - Present*, Ph.D, Huazhong University of Science and Technology.
