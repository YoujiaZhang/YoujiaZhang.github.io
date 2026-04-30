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

My name is Youjia Zhang (张由甲), a PhD Student at the [School of Computer Science and Technology, Huazhong University of Science and Technology](http://www.cs.hust.edu.cn/), in the [HUST Media Lab](http://media.hust.edu.cn), advised by Prof. [Wei Yang](https://weiyang-hust.github.io/). My research focuses on the intersection of Computer Vision, Graphics, and Neural Rendering.

I am now a visiting student at [Inception3D Lab](http://www.inception3d.fun/), Westlake University, under the supervision of Prof. [Anpei Chen](https://apchenstu.github.io/).

# Services
- Conference Reviewer: CVPR, ECCV, ICCV, NeurIPS, ICLR, ICML, ICME, AISTATS, ICASSP.
- Journal Reviewer: TPAMI

<span class='anchor' id='-publications'></span>

# Publications 
**Equal contribution**$^\star$
**Corresponding author**$^\dagger$

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/LATO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LATO: 3D Mesh Flow Matching with Structured TOpology Preserving LAtents](https://youjiazhang.github.io/)

Tianhao Zhao\*, **Youjia Zhang\***, Hang Long, Jinshen Zhang, Wenbing Li, Yang Yang, Gongbo Zhang, Jozef Hladký, Matthias Nießner, Wei Yang †    
<span style="color:blue"><em>International Conference on Machine Learning (ICML), 2026</em></span>

[**Paper**](https://arxiv.org/pdf/2603.06357)
- We propose LATO, a topology-aware latent representation for explicit mesh synthesis that encodes meshes as vertex displacement fields within a sparse voxel VAE and predicts edge connectivity from voxel latents, enabling efficient two-stage flow-matching generation of structured meshes.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/Jigsaw3D.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Jigsaw3D: Disentangled 3D Style Transfer via Patch Shuffling and Masking](https://babahui.github.io/jigsaw3D.github.io/)
 
Yuteng Ye, Zheng Zhang, Qinchuan Zhang, Di Wang, **Youjia Zhang**, Wenxiao Zhang, Wei Yang, Yuan Liu †    

[**Project**](https://babahui.github.io/jigsaw3D.github.io) | [**Paper**](https://arxiv.org/pdf/2510.10497) | [**Code**](https://github.com/babahui/JIGSAW3D)
- We propose Jigsaw3D, a framework for 3D style transfer consisting of a jigsaw operation to isolate style statistics, a multi-view diffusion model with reference-to-view cross-attention, and a style-baking step to produce view-consistent textures.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/Motion3-to-4.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Motion 3-to-4: 3D Motion Reconstruction for 4D Synthesis](https://motion3-to-4.github.io/)

Hongyuan Chen, Xingyu Chen, **Youjia Zhang**, Zexiang Xu, Anpei Chen †      
<span style="color:blue"><em>Computer Vision and Pattern Recognition (CVPR), 2026</em></span>

[**Project**](https://motion3-to-4.github.io/) | [**Paper**](https://arxiv.org/abs/2601.14253) | [**Code**](https://github.com/Inception3D/Motion324)
- We present Motion 3-to-4, a feed-forward framework for monocular 4D object synthesis that decomposes dynamic geometry into canonical shape generation and motion reconstruction, learning compact motion latents to predict temporally coherent vertex trajectories.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/Ref-GS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Ref-GS: Directional Factorization for 2D Gaussian Splatting](https://ref-gs.github.io/)

**Youjia Zhang**, Anpei Chen †, Yumin Wan, Zikai Song, Junqing Yu, Yawei Luo, Wei Yang †  
<span style="color:blue"><em>Computer Vision and Pattern Recognition (CVPR), 2025</em></span>

[**Project**](https://ref-gs.github.io/) | [**Paper**](https://arxiv.org/abs/2412.00905) | [**Code**](https://github.com/YoujiaZhang/Ref-GS) | [**Slides**](images/CCIG2025-Spotlight-Ref-GS-youjiazhang@hust.edu.cn.pdf) | [**Poster**](images/Ref-GS-poster.pdf)
- Ref-GS builds upon the deferred rendering of Gaussian splatting and applies directional encoding to the deferred-rendered surface, effectively reducing the ambiguity between orientation and viewing angle. We introduce a spherical Mip-grid to capture varying levels of surface roughness, enabling roughness-aware Gaussian shading.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2025</div> <video width="100%" height="100%" playsinline autoplay loop muted> <source src="images/USD.mp4" type="video/mp4"> </video> </div></div>
<div class='paper-box-text' markdown="1">

[Optimized View and Geometry Distillation from Multi-view Diffuser](https://youjiazhang.github.io/USD/)

**Youjia Zhang**, Zikai Song, Junqing Yu, Yawei Luo, Wei Yang †  
<span style="color:blue"><em>International Joint Conference on Artificial Intelligence (IJCAI), 2025</em></span>

[**Project**](https://youjiazhang.github.io/USD/) | [**Paper**](https://arxiv.org/abs/2312.06198) | [**Code**](https://github.com/YoujiaZhang/USD)
- We propose the USD, which achieves consistent single-to-multi-view synthesis and geometry recovery by using a radiance-field consistency prior and Unbiased Score Distillation—injecting unconditioned 2D diffusion noise to debias optimization—followed by a two-step, object-aware denoising process that yields high-quality views for accurate geometry and texture.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2025</div><img src='images/MICCAI2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MCA-RG: Enhance LLM with Medical Concept Alignment for Radiology Report Generation](https://youjiazhang.github.io/)

Qilong Xing, Zikai Song, **Youjia Zhang**, Na Feng, Junqing Yu, Wei Yang †  
<span style="color:blue"><em>Medical Image Computing and Computer Assisted Intervention (MICCAI), 2025</em></span>

[**Paper**](https://youjiazhang.github.io/) | [**Code**](https://youjiazhang.github.io/)
- We propose MCA-RG, a knowledge-driven framework for radiology report generation that aligns visual features with curated pathology and anatomy concept banks, employs contrastive and matching losses, and leverages feature gating to guide accurate, clinically relevant report synthesis.
</div>
</div>


<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2025</div><img src='images/CA-Diff.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CA-Diff: Collaborative Anatomy Diffusion for Brain Tissue Segmentation](https://youjiazhang.github.io/)

Qilong Xing, Zikai Song †, Yuteng Ye, Yuke Chen, **Youjia Zhang**, Na Feng, Junqing Yu, Wei Yang †  
<span style="color:blue"><em>International Conference on Multimedia & Expo (ICME), 2025</em></span>

[**Paper**](https://youjiazhang.github.io/) | [**Code**](https://youjiazhang.github.io/)
- We propose Collaborative Anatomy Diffusion (CA-Diff), a framework integrating spatial anatomical features to enhance segmentation accuracy of the diffusion model.
</div>
</div> -->


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/reid.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic feature pruning and consolidation for occluded person re-identification](https://ojs.aaai.org/index.php/AAAI/article/view/28491)

YuTeng Ye, Jiale Cai, Chenxing Gao, **Youjia Zhang**, Junle Wang, Qiang Hu, Junqing Yu, Wei Yang †  
<span style="color:blue"><em>AAAI Conference on Artificial Intelligence (AAAI), 2024</em></span>

[**Paper**](https://arxiv.org/pdf/2211.14742) | [**Code**](https://github.com/babahui/FPC)
- We propose a Feature Pruning and Consolidation (FPC) framework to circumvent explicit human structure parse, which consists of a sparse encoder, a global and local feature ranking module, and a feature consolidation decoder.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/pt2i.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Progressive Text-to-Image Diffusion with Soft Latent Direction](https://arxiv.org/abs/2309.09466)

YuTeng Ye, Jiale Cai, Hang Zhou, Guanwen Li, **Youjia Zhang**, Zikai Song, Chenxing Gao, Junqing Yu, Wei Yang †  
<span style="color:blue"><em>AAAI Conference on Artificial Intelligence (AAAI), 2024</em></span>

[**Paper**](https://arxiv.org/pdf/2309.09466) | [**Code**](https://github.com/babahui/Progressive-Text-to-Image)
- We propose to harness the capabilities of a Large Language Model (LLM) to decompose text descriptions into coherent directives adhering to stringent formats and progressively generate the target image.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/AMD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AMD: anatomical motion diffusion with interpretable motion decomposition and fusion](https://arxiv.org/abs/2312.12763)

Beibei Jing, **Youjia Zhang**, Zikai Song, Junqing Yu, Wei Yang †  
<span style="color:blue"><em>AAAI Conference on Artificial Intelligence (AAAI), 2024</em></span>

[**Paper**](https://arxiv.org/pdf/2312.12763)
- We propose the Adaptable Motion Diffusion (AMD) model, which leverages a Large Language Model (LLM) to parse the input text into a sequence of concise and interpretable anatomical scripts that correspond to the target motion.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/NeMF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[NeMF: Inverse volume rendering with neural microflake field](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_NeMF_Inverse_Volume_Rendering_with_Neural_Microflake_Field_ICCV_2023_paper.pdf)

**Youjia Zhang**, Teng Xu, Junqing Yu, Yuteng Ye, Yanqing Jing, Junle Wang, Jingyi Yu, Wei Yang †  
<span style="color:blue"><em>International Conference on Computer Vision (ICCV), 2023</em></span>

[**Project**](https://youjiazhang.github.io/NeMF/) | [**Paper**](https://arxiv.org/abs/2304.00782) | [**Code**](https://github.com/YoujiaZhang/NeMF)
- We propose to conduct inverse volume rendering by representing a scene using microflake volume, which assumes the space is filled with infinite small flakes and light reflects or scattersat each spatial location according to microflake distributions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Nature Communications Chemistry</div><img src='images/SigmaCCS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Highly accurate and large-scale collision cross sections prediction with graph neural networks](https://www.nature.com/articles/s42004-023-00939-w)

Renfeng Guo\*, **Youjia Zhang\***, Yuxuan Liao\*, Qiong Yang, Ting Xie, Xiaqiong Fan, Zhonglong Lin, Yi Chen, Hongmei Lu †, Zhimin Zhang †  
<span style="color:blue"><em>Nature Communications Chemistry (JCR-Q1), 2023</em></span>

[**Paper**](https://www.nature.com/articles/s42004-023-00939-w) | [**Code**](https://github.com/YoujiaZhang/SigmaCCS)
- We present SigmaCCS, a graph neural network-based method for CCS prediction from 3D conformers. It achieves high accuracy and chemical interpretability, enabling large-scale in-silico CCS estimation.
</div>
</div>

<span class='anchor' id='-honors-and-awards'></span>

# Honors and Awards
- *2026*: [Meshy AI Fellowship 2026](https://www.meshy.ai/blog/fellowship-2026) Outstanding Prize Recipient.
- *2023*: China National Scholarship (Top 1%).
- *2021*: Outstanding Graduates of Central South University.

<span class='anchor' id='-educations'></span>

# Educations
- *2017.09 - 2021.06*, Undergraduate, Central South University.
- *2021.09 - 2023.06*, Master, Huazhong University of Science and Technology.
- *2023.09 - Present*, Ph.D, Huazhong University of Science and Technology.
