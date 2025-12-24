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

I am currently pursuing a Ph.D. degree in Computer Science at Wuhan University (WHU) under the supervision of [Prof. Lefei Zhang](https://scholar.google.ch/citations?user=BLKHwNwAAAAJ&hl=en). During this period, I am also fortunate to receive valuable guidance from [Dr. Sen Zhang](https://scholar.google.com/citations?user=-bJJNV0AAAAJ&hl=zh-CN), [Dr. Liang Ding](https://scholar.google.com/citations?user=lFCLvOAAAAAJ&hl=en), and [ Prof. Dacheng Tao](https://scholar.google.com/citations?user=RwlJNLcAAAAJ&hl=en). Before that, I received my bachelor's degree in Mathematical Sciences at the University of Electronic Science and Technology of China (UESTC) in 2022, under the supervision of [Prof. Xile Zhao](https://scholar.google.com/citations?user=88Zs8pAAAAAJ&hl=zh-CN). I am sincerely grateful to all my mentors for their invaluable guidance, support, and inspiration throughout my academic journey.

I have authored or co-authored over 10 papers published in top-tier international journals and conferences, including IEEE TPAMI, ICML, NeurIPS, CVPR, ICCV, and EMNLP. In addition, I am supported by the Fundamental Research Project for Young Professional from NSFC (国自然博士生基金, [PR](https://sigma.whu.edu.cn/info/1051/4351.htm)). I have also received several honors, including the China Remote Sensing Outstanding Achievement First-Class Prize (2025 中国遥感优秀成果一等奖, [PR](https://sigma.whu.edu.cn/info/1051/4361.htm)) and the VALSE 2025 Popular Poster Award (VALSE 2025人气海报奖, [PR](https://mp.weixin.qq.com/s/jYDntHR05zu0YG9lMonYlQ)). 

My current research interests mainly focus on Reinforcement Learning (RL) for LLMs, including Reinforcement Learning from Human Feedback (RLHF), reasoning RL, and agentic RL. Previously, my research primarily focused on tensor modeling and computing, high-dimensional image processing, and remote sensing.


# 🔥 News
- *2025.12*: &nbsp;🎉🎉 I was supported by the Fundamental Research Project for Young Professional from NSFC (国家自然科学基金博士生专项).
- *2025.11*: &nbsp;🎉🎉 HyperSIGMA was selected for the China Remote Sensing Outstanding Achievement First-Class Prize (2025 中国遥感优秀成果一等奖).
- *2025.11*: &nbsp;🎉🎉 HyperSIGMA has been selected as ESI Highly Cited Papers (TOP 1%).
- *2025.08*: &nbsp;🎉🎉 One paper has been accepted by EMNLP 2025.
- *2025.06*: &nbsp;🎉🎉 HyperSIGMA received the VALSE 2025 Popular Poster Award (VALSE 2025人气海报奖).
- *2025.05*: &nbsp;🎉🎉 One paper has been accepted by IEEE GRSL.
- *2025.04*: &nbsp;🎉🎉 One paper has been accepted by ICML 2025.
- *2025.03*: &nbsp;🎉🎉 One paper has been accepted by IEEE TPAMI.
- *2024.09*: &nbsp;🎉🎉 One paper has been accepted by NeurIPS 2024.
- *2024.01*: &nbsp;🎉🎉 One paper has been accepted by IEEE TCI.
- *2023.07*: &nbsp;🎉🎉 One paper has been accepted by ICCV 2023. 

# 📝 Publications 
†: equal contribution, * : corresponding author
<h3>Conference Papers</h3> 

- <font color="#0D4884"> The Energy Loss Phenomenon in RLHF: A New Perspective on Mitigating Reward Hacking </font>
<b>Yuchun Miao</b>, Sen Zhang, Liang Ding, Yuqi Zhang, Lefei Zhang, Dacheng Tao <br>
<i>International Conference on Machine Learning (<b>ICML</b>), 2025</i><br>
[<a href="https://icml.cc/virtual/2025/poster/46294">Paper</a>][<a href="https://github.com/miaoyuchun/Energy-Loss-Phenomenon">Code</a>]
- <font color="#0D4884"> InfoRM: Mitigating Reward Hacking in RLHF via Information-Theoretic Reward Modeling  </font>
<b>Yuchun Miao</b>, Sen Zhang, Liang Ding, Rong Bao, Lefei Zhang, Dacheng Tao <br>
<i>Conference on Neural Information Processing System (<b>NeurIPS</b>), 2024</i><br>
[<a href="https://nips.cc/virtual/2024/poster/96739">Paper</a>][<a href="https://github.com/miaoyuchun/InfoRM">Code</a>]
- <font color="#0D4884"> DDS2M: Self-Supervised Denoising Diffusion Spatio-Spectral Model for Hyperspectral Image Restoration  </font>
<b>Yuchun Miao</b>, Lefei Zhang, Liangpei Zhang, Dacheng Tao <br>
<i>IEEE/CVF International Conference on Computer Vision (<b>ICCV</b>), 2023</i><br>
[<a href="https://openaccess.thecvf.com/content/ICCV2023/html/Miao_DDS2M_Self-Supervised_Denoising_Diffusion_Spatio-Spectral_Model_for_Hyperspectral_Image_Restoration_ICCV_2023_paper.html">Paper</a>][<a href="https://github.com/miaoyuchun/DDS2M">Code</a>]
- <font color="#0D4884"> AMIA: Automatic Masking and Joint Intention Analysis Makes LVLMs Robust Jailbreak Defenders  </font>
Yuqi Zhang, <b>Yuchun Miao</b>, Zuchao Li, Liang Ding <br>
<i>Findings of Empirical Methods in Natural Language Processing (<b>EMNLP</b>), 2025</i><br>
[<a href="https://aclanthology.org/2025.findings-emnlp.651/">Paper</a>][<a href="">Code</a>]
- <font color="#0D4884"> Uncertainty-Aware Unsupervised Image Deblurring with Deep Residual Prior  </font>
Xiaole Tang, Xile Zhao, Jun Liu, Jianli Wang, <b>Yuchun Miao</b>, Tieyong Zeng  <br>
<i>IEEE/CVF Conference on Computer Vision and Pattern Recognition (<b>CVPR</b>), 2023</i><br>
[<a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Tang_Uncertainty-Aware_Unsupervised_Image_Deblurring_With_Deep_Residual_Prior_CVPR_2023_paper.pdf">Paper</a>][<a href="https://github.com/xl-tang3/UAUDeblur">Code</a>]

<h3>Journal Articles</h3>

- <font color="#0D4884"> HyperSIGMA: Hyperspectral Intelligence Comprehension Foundation Model  </font>
Di Wang<sup>†</sup>, Meiqi Hu<sup>†</sup>, Yao Jin<sup>†</sup>, <b>Yuchun Miao<sup>†</sup></b>, Jiaqi Yang<sup>†</sup>, Yichu Xu<sup>†</sup>, Xiaolei Qin<sup>†</sup>, Jiaqi Ma<sup>†</sup>, Lingyu Sun<sup>†</sup>, Chenxing Li,
Chuan Fu, Hongruixuan Chen, Chengxi Han, Naoto Yokoya, Jing Zhang, Minqiang Xu, Lin Liu, Lefei Zhang, Chen Wu, Bo Du, Dacheng Tao, Liangpei Zhang.  <br>
<i>IEEE Transactions on Pattern Analysis and Machine Intelligence (<b>IEEE TPAMI</b>), 2025</i><br>
[<a href="https://ieeexplore.ieee.org/document/10949864">Paper</a>][<a href="https://github.com/WHU-Sigma/HyperSIGMA">Code</a>]
- <font color="#0D4884"> Snapshot Compressive Imaging Using Domain-Factorized Deep Video Prior  </font>
<b>Yuchun Miao</b>, Xile Zhao, Jianli Wang, Xiao Fu, Yao Wang  <br>
<i>IEEE Transactions on Computational Imaging (<b>IEEE TCI</b>), 2024</i><br>
[<a href="https://ieeexplore.ieee.org/abstract/document/10388408">Paper</a>][<a href="https://github.com/miaoyuchun/FactorDVP-T">Code</a>]
- <font color="#0D4884"> Hyperspectral Denoising Using Unsupervised Disentangled Spatiospectral Deep Priors  </font>
<b>Yuchun Miao</b>, Xile Zhao, Xiao Fu, Jianli Wang, Yubang Zheng  <br>
<i>IEEE Transactions on Geoscience and Remote Sensing (<b>IEEE TGRS</b>), 2022</i><br>
[<a href="https://ieeexplore.ieee.org/abstract/document/10388408">Paper</a>][<a href="https://github.com/miaoyuchun/DS2DP">Code</a>]
- <font color="#0D4884"> PHDMamba: Progressive Hybrid Mamba for Hyperspectral Image Classification  </font>
Yichu Xu, Chengxi Han, Shi Chen, Yao Jin, <b>Yuchun Miao</b>, Haonan Guo, Di Wang  <br>
<i>IEEE Geoscience and Remote Sensing Letters (<b>IEEE GRSL</b>), 2025</i><br>
[<a href="https://ieeexplore.ieee.org/abstract/document/11222630">Paper</a>][<a href="https://github.com/YichuXu/PHDMamba">Code</a>]
- <font color="#0D4884"> Complex Video Completion Fusing Low-Rank Background and Deep Foreground Priors  </font>
Jianli Wang, Tingzhu Huang, Xile Zhao, <b>Yuchun Miao</b>  <br>
<i>IEEE Signal Processing Letters (<b>IEEE SPL</b>), 2022</i><br>
[<a href="https://ieeexplore.ieee.org/abstract/document/10024411">Paper</a>][<a href="">Code</a>]

<h3>Pre-prints</h3>

- <font color="#0D4884"> Information-Theoretic Reward Modeling for Stable RLHF: Detecting and Mitigating Reward Hacking   </font>
<b>Yuchun Miao</b>, Liang Ding, Sen Zhang, Rong Bao, Lefei Zhang, Dacheng Tao  <br>
<i>Submitted to IEEE Transactions on Pattern Analysis and Machine Intelligence (<b>IEEE TPAMI</b>)</i><br>
[<a href="https://arxiv.org/abs/2510.13694">Paper</a>][<a href="https://github.com/miaoyuchun/InfoRM">Code</a>]


# 🎖 Honors and Awards
- Fundamental Research Project for Young Professional from NSFC, 2025 December <br>
    (<b><font color="red">主持</font></b>国家自然科学基金青年学生基础研究项目（博士研究生), <b><a href="https://sigma.whu.edu.cn/info/1051/4351.htm">Link</a></b>)
- China Remote Sensing Outstanding Achievement First-Class Prize, 2025 December <br>
    (中国遥感优秀成果<b><font color="red">一等奖</font></b>, <b><a href="https://sigma.whu.edu.cn/info/1051/4361.htm">Link</a></b>)
- National Scholarship, Ministry of Education of China, 2025 October <br>
    (国家奖学金, <b><font color="red">Top 2% in Wuhan University</font></b>)
- VALSE Popular Poster Award, 2025 June <br>
    (VALSE 人气海报奖, <b><font color="red">11/398 </font></b>, <b><a href="https://mp.weixin.qq.com/s/jYDntHR05zu0YG9lMonYlQ">Link</a></b>)
- National Scholarship, Ministry of Education of China, 2024 October <br>
    (国家奖学金, <b><font color="red">Top 2% in Wuhan University</font></b>)


# 📖 Educations
-  <b>Wuhan University</b>, September 2022 -- Present<br>
    Ph.D. Student in School of Computer Science, Wuhan, China.<br>
    Supervised by <a href="https://scholar.google.ch/citations?user=BLKHwNwAAAAJ&hl=en" target="_blank">Lefei Zhang</a>.
- <b>University of Electronic Science and Technology of China</b>, September 2018 -- July 2022<br>
    Undergraduate Student in the School of Mathematical Science, Chengdu, China.<br>
    Supervised by <a href="https://scholar.google.com/citations?user=88Zs8pAAAAAJ&hl=zh-CN" target="_blank">Xile Zhao</a>.

# 💻 Internships
- <b>A Generative AI Research Startup</b>, April 2023 -- October 2025 <br>
  Research Intern on Alignment of Large Language Models, advised by <a href="http://liamding.cc/" target="_blank">Liang Ding</a>.
  
##
<footer>
  <p>Last update: 12/2025 by Yuchun Miao. </p>
</footer>
</body>


