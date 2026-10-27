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

I am a Ph.D. student at Wuhan University (WHU), advised by [Prof. Lefei Zhang](https://scholar.google.ch/citations?user=BLKHwNwAAAAJ&hl=en), with an expected graduation date of December 2027. I am currently a research intern with the LongCat Team (Agent) at Meituan through the Beidou Program, working on reinforcement learning for large language models and agents. I have also been fortunate to work with [Dr. Sen Zhang](https://scholar.google.com/citations?user=-bJJNV0AAAAJ&hl=zh-CN), [Dr. Liang Ding](https://scholar.google.com/citations?user=lFCLvOAAAAAJ&hl=en), and [Prof. Dacheng Tao](https://scholar.google.com/citations?user=RwlJNLcAAAAJ&hl=en). Previously, I received my bachelor's degree in Mathematics and Applied Mathematics from the University of Electronic Science and Technology of China (UESTC) in 2022, advised by [Prof. Xile Zhao](https://scholar.google.com/citations?user=88Zs8pAAAAAJ&hl=zh-CN). I am sincerely grateful to all my mentors for their invaluable guidance, support, and inspiration throughout my academic journey.

I have authored or co-authored 20 papers, including work published in top-tier international journals and conferences such as IEEE TPAMI, ICML, NeurIPS, CVPR, ICCV, and EMNLP, as well as manuscripts currently under review. My research has received **1,000+ citations** on [Google Scholar](https://scholar.google.com/citations?user=-ec3mwUAAAAJ). In addition, I am supported by the Fundamental Research Project for Young Professional from NSFC (国自然博士生基金, [PR](https://sigma.whu.edu.cn/info/1051/4351.htm)). I have also received several honors, including the China Remote Sensing Outstanding Achievement First-Class Prize (2025 中国遥感优秀成果一等奖, [PR](https://sigma.whu.edu.cn/info/1051/4361.htm)) and the VALSE 2025 Popular Poster Award (VALSE 2025人气海报奖, [PR](https://mp.weixin.qq.com/s/jYDntHR05zu0YG9lMonYlQ)). 

My research focuses on understanding and improving the **stability of reinforcement learning for large language models through the lens of its underlying mechanisms**, progressing from **RLHF to RLVR and long-horizon RL**. My work also extends to **asynchronous RL systems**, **multi-agent systems**, **agent harness self-improvement**, and **safety**. Previously, I worked on tensor modeling and computation, high-dimensional image processing, and remote sensing.

📧 I am open to collaboration and welcome inquiries from anyone interested in my research topics. Feel free to reach out via <font color="#0D4884"> szmyc1@163.com </font> or <font color="#0D4884"> miaoyuchun@whu.edu.cn</font>.


# 🔥 News
- *2026.09*: &nbsp;🎉🎉 One paper has been accepted by NeurIPS 2026.
- *2026.05*: &nbsp;🎉🎉 HyperSIGMA was selected as an ESI Hot Paper (Top 0.1%).
- *2025.12*: &nbsp;🎉🎉 I was supported by the Fundamental Research Project for Young Professional from NSFC (国家自然科学基金博士生专项).
- *2025.11*: &nbsp;🎉🎉 HyperSIGMA was selected for the China Remote Sensing Outstanding Achievement First-Class Prize (2025 中国遥感优秀成果一等奖).
- *2025.11*: &nbsp;🎉🎉 HyperSIGMA has been selected as ESI Highly Cited Papers (TOP 1%).
- *2025.10*: &nbsp;🎉🎉 One paper has been accepted by IEEE GRSL.
- *2025.08*: &nbsp;🎉🎉 One paper has been accepted by EMNLP 2025.
- *2025.06*: &nbsp;🎉🎉 HyperSIGMA received the VALSE 2025 Popular Poster Award (VALSE 2025人气海报奖).
- *2025.04*: &nbsp;🎉🎉 One paper has been accepted by ICML 2025.
- *2025.03*: &nbsp;🎉🎉 One paper has been accepted by IEEE TPAMI.
- *2024.09*: &nbsp;🎉🎉 One paper has been accepted by NeurIPS 2024.
- *2024.01*: &nbsp;🎉🎉 One paper has been accepted by IEEE TCI.
- *2023.07*: &nbsp;🎉🎉 One paper has been accepted by ICCV 2023.
- *2023.02*: &nbsp;🎉🎉 One paper has been accepted by CVPR 2023.
- *2021.08*: &nbsp;🎉🎉 One paper has been accepted by IEEE TGRS. 

# 📝 Publications 

[1] <span style="color: #0D4884;">When to Stop Reusing: Dynamic Gradient Gating for Sample-Efficient RLVR</span><br>
&emsp;&emsp;**First author** · Under review · [Paper](https://arxiv.org/abs/2605.19425)

[2] <span style="color: #0D4884;">DORA: A Scalable Asynchronous Reinforcement Learning System for Language Model Training</span><br>
&emsp;&emsp;**Co-first author** · NeurIPS 2026 · **Deployed in LongCat production training** · [Paper](https://arxiv.org/abs/2604.26256)

[3] <span style="color: #0D4884;">The Energy Loss Phenomenon in RLHF: A New Perspective on Mitigating Reward Hacking</span><br>
&emsp;&emsp;**First author** · ICML 2025 · [Paper](https://icml.cc/virtual/2025/poster/46294) · [Code](https://github.com/miaoyuchun/Energy-Loss-Phenomenon)

[4] <span style="color: #0D4884;">InfoRM: Mitigating Reward Hacking in RLHF via Information-Theoretic Reward Modeling</span><br>
&emsp;&emsp;**First author** · NeurIPS 2024 · **130+ citations** · [Paper](https://nips.cc/virtual/2024/poster/96739) · [Code](https://github.com/miaoyuchun/InfoRM)

[5] <span style="color: #0D4884;">Information-Theoretic Latent Space Modeling for Robust RLHF under Imperfect Human Feedback</span><br>
&emsp;&emsp;**First author** · Under review · [Paper](https://arxiv.org/abs/2510.13694) · [Code](https://github.com/miaoyuchun/InfoRM)

[6] <span style="color: #0D4884;">HyperSIGMA: Hyperspectral Intelligence Comprehension Foundation Model</span><br>
&emsp;&emsp;**Co-first author** · IEEE TPAMI 2025 · **ESI Hot Paper (Top 0.1%)** · **350+ citations** · [Paper](https://ieeexplore.ieee.org/document/10949864) · [Code](https://github.com/WHU-Sigma/HyperSIGMA)

[7] <span style="color: #0D4884;">PluginRSI: Recursive Improvement of Agent Harnesses with Reusable Plugins</span><br>
&emsp;&emsp;**Second author** · Under review · [Paper](https://huggingface.co/papers/2609.32423)

[8] <span style="color: #0D4884;">Skill1: Unified evolution of skill-augmented agents via reinforcement learning</span><br>
&emsp;&emsp;**Fourth author** · Under review · [Paper](https://arxiv.org/abs/2605.06130)

[9] <span style="color: #0D4884;">AD-GRPO: Associative Diversity-Aware GRPO for Multimodal Reasoning</span><br>
&emsp;&emsp;**Second author** · Under review

[10] <span style="color: #0D4884;">AMIA: Automatic Masking and Joint Intention Analysis Makes LVLMs Robust Jailbreak Defenders</span><br>
&emsp;&emsp;**Second author** · EMNLP 2025 · [Paper](https://aclanthology.org/2025.findings-emnlp.651/)

[11] <span style="color: #0D4884;">DDS2M: Self-Supervised Denoising Diffusion Spatio-Spectral Model for Hyperspectral Image Restoration</span><br>
&emsp;&emsp;**First author** · ICCV 2023 · **110+ citations** · [Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Miao_DDS2M_Self-Supervised_Denoising_Diffusion_Spatio-Spectral_Model_for_Hyperspectral_Image_Restoration_ICCV_2023_paper.html) · [Code](https://github.com/miaoyuchun/DDS2M)

[12] <span style="color: #0D4884;">Snapshot Compressive Imaging Using Domain-Factorized Deep Video Prior</span><br>
&emsp;&emsp;**First author** · IEEE TCI 2023 · [Paper](https://ieeexplore.ieee.org/abstract/document/10388408) · [Code](https://github.com/miaoyuchun/FactorDVP-T)

[13] <span style="color: #0D4884;">Hyperspectral Denoising Using Unsupervised Disentangled Spatiospectral Deep Priors</span><br>
&emsp;&emsp;**First author** · IEEE TGRS 2022 · [Paper](https://arxiv.org/abs/2102.12310) · [Code](https://github.com/miaoyuchun/DS2DP)

[14] <span style="color: #0D4884;">Uncertainty-Aware Unsupervised Image Deblurring with Deep Residual Prior</span><br>
&emsp;&emsp;**Fifth author** · CVPR 2023 · [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Tang_Uncertainty-Aware_Unsupervised_Image_Deblurring_With_Deep_Residual_Prior_CVPR_2023_paper.pdf) · [Code](https://github.com/xl-tang3/UAUDeblur)

[15] <span style="color: #0D4884;">PHDMamba: Progressive Hybrid Mamba for Hyperspectral Image Classification</span><br>
&emsp;&emsp;**Fifth author** · IEEE GRSL 2025 · [Paper](https://ieeexplore.ieee.org/abstract/document/11222630) · [Code](https://github.com/YichuXu/PHDMamba)

[16] <span style="color: #0D4884;">Complex Video Completion Fusing Low-Rank Background and Deep Foreground Priors</span><br>
&emsp;&emsp;**Fourth author** · IEEE SPL 2022 · [Paper](https://ieeexplore.ieee.org/abstract/document/10024411)


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
-  <b>Wuhan University</b>, September 2022 -- Present (Expected graduation: December 2027)<br>
    Ph.D. Student in the School of Computer Science, Wuhan, China.<br>
    Supervised by <a href="https://scholar.google.ch/citations?user=BLKHwNwAAAAJ&hl=en" target="_blank">Lefei Zhang</a>.
- <b>University of Electronic Science and Technology of China</b>, September 2018 -- July 2022<br>
    Undergraduate Student in the School of Mathematical Science, Chengdu, China.<br>
    Supervised by <a href="https://scholar.google.com/citations?user=88Zs8pAAAAAJ&hl=zh-CN" target="_blank">Xile Zhao</a>.

# 💻 Internships
- <b>LongCat Team (Agent), Meituan</b>, January 2026 -- Present <br>
  Research Intern on Agentic RL (<b><font color="red">Beidou Program</font></b>), advised by <a href="" target="_blank">Qi Gu</a>.
- <b>A Generative AI Research Startup</b>, April 2023 -- October 2025 <br>
  Research Intern on LLM Alignment, advised by <a href="http://liamding.cc/" target="_blank">Liang Ding</a>.
  
<hr style="margin-top: 3em;">

<div id="footer" style="text-align: center; font-size: 0.9em; color: #666;">
  <div id="footer-text"></div>

  &copy; 2026 Yuchun Miao<br><br>
