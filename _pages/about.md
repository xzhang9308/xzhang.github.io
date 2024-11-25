---
permalink: /
title: ""
excerpt: ""
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

I am currently a Research Scientist in the Alibaba-NTU Global e-Sustainability CorpLab (ANGEL) at Nanyang Technological University (NTU), 
working with Prof. <a href="https://personal.ntu.edu.sg/wslin/Home.html">Weisi Lin</a>. 
Before that, I was a postdoctoral fellow at McMaster University (Mac), Canada from July 2022 to August 2024, 
supervised by Prof. <a href="https://scholar.google.com/citations?user=ZuQnEIgAAAAJ">Xiaolin Wu</a>.
I was also an assistant researcher at Department of Electronic Engineering, Shanghai Jiao Tong University (SJTU), 
supervised by Prof. <a href="https://min.sjtu.edu.cn/En/FacultyShow/4?Vid=14">Hongkai Xiong</a>.
I earned my PhD from SJTU in June 2022 and my bachelor’s degree in Mathematics and Physics Basic Science from UESTC in 2015.

My current research interests focus on green and energy-efficient AI technologies that prioritize sustainable ecosystems and lifestyles. 
Previously, I concentrated on learning-based data compression techniques, particularly for visual data such as images, videos, point clouds, and light fields. 
Additionally, I am interested in core deep learning challenges, including domain generalization and visual reasoning.
<!-- I have published more than 10 papers at the top AI Journals and conferences such as T-PAMI, T-IP, NeurIPS, CVPR, ECCV, AAAI, etc. -->
<!-- with total <a href='https://scholar.google.com/citations?user=78WvEjMAAAAJ'>google scholar citations <strong><span id='total_cit'>600+</span></strong></a>  -->
  <!-- <a href='https://scholar.google.com/citations?user=78WvEjMAAAAJ'>
  <img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> -->



# 🔥 News
- *2024.09*: &nbsp;🎉 One paper on optimal lattice vector quantizer is accepted by NeurIPS 2024. 
- *2024.07*: &nbsp;🎉 One paper on point cloud compression is accepted by ECCV 2024. 
- *2024.01*: &nbsp;🎉 One paper on light field image compression is accepted by JVCI. 
- *2023.03*: &nbsp;🎉 One paper on vector quantization for image compression is accepted by CVPR 2023. 
- *2022.03*: &nbsp;🎉 One paper on multi-modality face video restoration is accepted by TPAMI. 
- *2021.02*: &nbsp;🎉 One paper on ROI image compression is accepted by CVPR 2021. 
- *2020.12*: &nbsp;🎉 One paper on high fidelity image compression is accepted by TIP. 
- *2020.09*: &nbsp;🎉 One paper on numerosity is accepted by NeurIPS 2020. 
- *2020.07*: &nbsp;🎉 One paper on multi-modality video restoration is accepted by ACMMM 2020. 
- *2020.02*: &nbsp;🎉 One paper on face video decompression is accepted by CVPR 2020. 


# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

<!-- ## Preprints

- ``arXiv``[FLLIC: Functionally Lossless Image Compression](https://arxiv.org/pdf/2401.13616.pdf).
**Xi Zhang**, Xiaolin Wu.

- ``arXiv``[Dual-layer Image Compression via Adaptive Downsampling and Spatially Varying Upconversion](https://arxiv.org/pdf/2302.06096.pdf).
**Xi Zhang**, Xiaolin Wu.

- ``arXiv``[Asymmetric Coding for Ultrahigh Throughput Encoding (ACUTE)]().Seyed Mehdi Ayyoubzadeh, **Xi Zhang**, Xiaolin Wu. -->


## Published
<!-- (+ means equal contribution, * means corresponding author(s)) -->

- ``NeurIPS 2024`` [Learning Optimal Lattice Vector Quantizers for End-to-end Neural Image Compression](). \
&emsp; &emsp; &emsp; &emsp; 
**Xi Zhang**, Xiaolin Wu.

- ``ECCV 2024`` [Fast Point Cloud Geometry Compression with Context-based Residual Coding and INR-based Refinement](https://arxiv.org/pdf/2408.02966). \
&emsp; &emsp; &emsp; &emsp; 
Hao Xu, **Xi Zhang**, Xiaolin Wu.
  
- ``JVCI 2024`` [Low-complexity L∞--compression of Light Field Images with a Deep-Decompression Stage](https://doi.org/10.1016/j.jvcir.2024.104072). \
&emsp; &emsp; &emsp; &emsp; 
Muhammad Umair Mukati, **Xi Zhang**, Xiaolin Wu, Søren Forchhammer.

- ``CVPR 2023`` [Lattice Vector Quantization Coupled with Spatially Adaptive Companding for Efficient Learned Image Compression](https://openaccess.thecvf.com/content/CVPR2023/html/Zhang_LVQAC_Lattice_Vector_Quantization_Coupled_With_Spatially_Adaptive_Companding_for_CVPR_2023_paper.html). \
&emsp; &emsp; &emsp; &emsp; 
**Xi Zhang**, Xiaolin Wu.

- ``TPAMI 2023`` [Multi-modality Deep Restoration of Extremely Compressed Face Videos](https://ieeexplore.ieee.org/abstract/document/9730053). \
&emsp; &emsp; &emsp; &emsp; 
**Xi Zhang**, Xiaolin Wu.

- ``TIP 2022`` [Ultra High Fidelity Deep Image Decompression with L∞-constrained Compression](https://ieeexplore.ieee.org/abstract/document/9277919). \
&emsp; &emsp; &emsp; &emsp; 
**Xi Zhang**, Xiaolin Wu.

- ``CVPR 2021`` [Attention-guided Image Compression by Deep Reconstruction of Compressive Sensed Saliency Skeleton](https://openaccess.thecvf.com/content/CVPR2021/html/Zhang_Attention-Guided_Image_Compression_by_Deep_Reconstruction_of_Compressive_Sensed_Saliency_CVPR_2021_paper.html). \
&emsp; &emsp; &emsp; &emsp; 
**Xi Zhang**, Xiaolin Wu.

- ``CVPR 2020`` <span style="color:red">(Oral)</span> [DAVD-Net: Deep Audio-aided Video Decompression of Talking Heads](https://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_DAVD-Net_Deep_Audio-Aided_Video_Decompression_of_Talking_Heads_CVPR_2020_paper.html). \
&emsp; &emsp; &emsp; &emsp; 
**Xi Zhang**, Xiaolin Wu, Xinliang Zhai, Xianye Ben and Chengjie Tu.

- ``NeurIPS 2020`` [On Numerosity of Deep Neural Networks](https://proceedings.neurips.cc/paper/2020/hash/13e36f06c66134ad65f532e90d898545-Abstract.html). \
&emsp; &emsp; &emsp; &emsp; 
**Xi Zhang**, Xiaolin Wu.

- ``ACMMM 2020`` [Deep Multi-modality Soft-decoding of Very Low Bit-rate Face Videos](https://dl.acm.org/doi/abs/10.1145/3394171.3413709). \
&emsp; &emsp; &emsp; &emsp; 
Yanhui Guo, **Xi Zhang**, Xiaolin Wu.

- ``AAAI 2019`` <span style="color:red">(Spotlight)</span> [Cognitive Deficit of Deep Learning in Numerosity](https://ojs.aaai.org/index.php/AAAI/article/view/3928). \
&emsp; &emsp; &emsp; &emsp; 
**Xi Zhang**, Xiaolin Wu, Xiao Shu.

- ``ICASSP 2019`` [Nonlinear Prediction of Multidimensional Signals via Deep Regression with Applications to Image Coding](https://ieeexplore.ieee.org/abstract/document/8683863). \
&emsp; &emsp; &emsp; &emsp; 
**Xi Zhang**, Xiaolin Wu.

- ``DCC 2019`` [Near-Lossless L∞-Constrained Image Decompression via Deep Neural Network](https://ieeexplore.ieee.org/abstract/document/8712819). \
&emsp; &emsp; &emsp; &emsp; 
**Xi Zhang**, Xiaolin Wu.

- ``VCIP 2017`` [Illumination invariant feature based on neighboring radiance ratio](https://ieeexplore.ieee.org/abstract/document/8305111). \
&emsp; &emsp; &emsp; &emsp; 
**Xi Zhang**, Xiaolin Wu.



# 🎨 Working Experience
- *2024.09 - Present*, Research Scientist, Nanyang Technological University (NTU), Singapore.
- *2022.07 - 2024.08*, Postdoctoral Fellow, McMaster University (Mac), Canada.
- *2022.06 - 2024.08*, Assistant Researcher, Shanghai Jiao Tong University, China.



# 📖 Educations
- *2015.09 - 2022.06*, PhD, Shanghai Jiao Tong University, China.
- *2019.10 - 2020.09*, Visiting PhD, McMaster University (Mac), Canada. 
- *2011.09 - 2015.06*, Undergraduate, University of Electronic Science and Technology of China.



<!-- # 💰 Grants -->



# 🎖 Honors and Awards
- *2014.10*, National Scholarship (Undergraduate) (Top 1%)
- *2013.10*, National Scholarship (Undergraduate) (Top 1%)



<!-- # 💬 Invited Talks -->



# 💻 Internships
- *2021.03 - 2021.06*, Shannon Lab, Tencent.
- *2019.06 - 2019.09*, Video R&D Center, Tencent. 


# 💬 Academic Service


## Journal Reviewer
- T-PAMI, T-IP, T-NNLS, T-MM, T-CSVT


## Conference Reviewer
- CVPR 2021-2024, NeurIPS 2023-2024, ICLR 2024, ICCV 2021-2023, ECCV 2022-2024, WACV 2024-2025, AISTATS 2025