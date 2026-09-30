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

I am a master’s student in Software Engineering at [Zhejiang University](https://www.zju.edu.cn/english/), advised by [Dr. Tianyu Du](https://tydusky.github.io/) and [Prof. Shouling Ji](https://nesa.zju.edu.cn/webpage/crew/jsl.html). Before that, I received my bachelor’s degree in Cyberspace Security from Nanjing University of Science and Technology.

My research focuses on **LLM post-training, reliable agents, and AI safety**. I am particularly interested in enhancing the reasoning and agentic capabilities of large language models through post-training and reinforcement learning, while improving their safety and reliability in real-world applications. My research spans multi-agent collaboration, multimodal understanding, and AI-generated content protection.

I have six first-author papers accepted at NeurIPS, ICLR, AAAI, WWW, ACL, and EMNLP. I am currently a research intern with the livestreaming technology team at Taotian Group, where I work on LLM and agent post-training.

**Open to LLM algorithm engineering opportunities.** My interests include LLM post-training, agents, intelligent customer service, and LLM safety. Feel free to [get in touch](mailto:xunaen@zju.edu.cn).



*<span style="color:red">Openings:</span> I am looking for motivated PhD/Master/intern students to join my research group. Please drop me an email if you are interested in working with me!*


# 🔥 News
- *2026.09*: &nbsp; 🎉 One paper was accepted by [NeurIPS 2026](https://nips.cc/).
- *2026.04*: &nbsp; 🎉 One paper was accepted by [ACL 2026](https://2026.aclweb.org/).
- *2026.01*: &nbsp; 🎉 One paper was accepted by [ICLR 2026](https://iclr.cc/).
- *2026.01*: &nbsp; 🎉 One paper was accepted by [WWW 2026](https://www2026.thewebconf.org/).
- *2025.11*: &nbsp; 🎉 One paper was selected for **ORAL** presentation at AAAI’26!
- *2025.11*: &nbsp; 🎉 One paper was accepted by [AAAI 2026](https://aaai.org/conference/aaai/aaai-26/).
- *2025.08*: &nbsp; 🎉 One paper was accepted by [EMNLP 2025](https://2025.emnlp.org/).

# 📝 Conference Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCS 2021</div><img src='images/cert-rnn.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cert-RNN: Towards Certifying the Robustness of Recurrent Neural Networks](https://dl.acm.org/doi/10.1145/3460120.3484538)

**Tianyu Du**, Shouling Ji, Lujia Shen, Yao Zhang, Jinfeng Li, Jie Shi, Chengfang Fang, Jianwei Yin, Raheem Beyah, Ting Wang

<strong><span class='show_paper_citations' data='kBqTzrwAAAAJ:5nxA0vEk-isC'></span></strong>
- This work proposes Cert-RNN, a general framework for certifying the robustness of RNNs. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">USENIX Security 2021</div><img src='images/textshield.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[TextShield: Robust Text Classification Based on Multimodal Embedding and Neural Machine Translation](https://www.usenix.org/system/files/sec20-li-jinfeng.pdf)

Jinfeng Li\*, **Tianyu Du\***, Shouling Ji, Rong Zhang, Quan Lu, Min Yang, and Ting Wang (\*Co-first authors)

<strong><span class='show_paper_citations' data='kBqTzrwAAAAJ:LkGwnXOMwfcC'></span></strong>
- This work proposes TextShield, a new adversarial defense framework specifically designed for Chinese deep learning-based text classification models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NDSS 2019</div><img src='images/textbugger.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[TextBugger: Generating Adversarial Text Against Real-world Applications](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_03A-5_Li_paper.pdf)
Jinfeng Li, Shouling Ji, **Tianyu Du**, Bo Li, and Ting Wang

<strong><span class='show_paper_citations' data='kBqTzrwAAAAJ:ufrVoPGSRksC'></span></strong>
- This work proposes TextBugger, a general attack framework for generating adversarial texts.
</div>
</div>

Authors with an <u>underline</u> are my supervised students, and * indicates the <span style="color:red">corresponding author</span>.

- ``NeurIPS 2026`` [StateTree: Enhancing Long-term Dialogue Reasoning via Reinforcement Learning](), <u>Naen Xu</u>, Wanqing Cui, Yibo Hu, Shixin Hong, <u>Hengyu An</u>, Meiguang Jin, Junfeng Ma, **Tianyu Du***, **NeurIPS 2026**. [CCF A]
- ``ACL 2026`` [“I See What You Did There”: Can Large Vision-Language Models Understand Multimodal Puns?](https://arxiv.org/pdf/2604.05930), <u>Naen Xu</u>, Jiayi Sheng, Changjiang Li, Chunyi Zhou, Yuyuan Li, Jun Wang, Zhihui Fu, **Tianyu Du***, Jinbao Li, Shouling Ji, **ACL Main 2026**. [CCF A]
- ``ICLR 2026`` [When Agents “Misremember” Collectively: Exploring the Mandela Effect in LLM-based Multi-Agent Systems](https://openreview.net/forum?id=yIoMqDes7O), <u>Naen Xu</u>, <u>Hengyu An</u>, <u>Shuo Shi</u>, Jinghuai Zhang, Chunyi Zhou, Changjiang Li, **Tianyu Du***, Zhihui Fu, Jun Wang, Shouling Ji, **ICLR 2026**. [CCF A]
- ``WWW 2026`` [FraudShield: Knowledge Graph Empowered Defense for LLMs against Fraud Attacks](https://arxiv.org/abs/2601.22485), <u>Naen Xu</u>, Jinghuai Zhang, Ping He, Chunyi Zhou, Jun Wang, Zhihui Fu, **Tianyu Du***, Zhaoxiang Wang, Shouling Ji, **WWW 2026**. [CCF A]
- ``AAAI 2026`` [Bridging the Copyright Gap: Do Large Vision-Language Models Recognize and Respect Copyrighted Content?](https://arxiv.org/abs/2512.21871), <u>Naen Xu</u>, Jinghuai Zhang, Changjiang Li, <u>Hengyu An</u>, Chunyi Zhou, Jun Wang, Boyu Xu, Yuyuan Li, **Tianyu Du***, Shouling Ji, **AAAI <span style="color:red">(Oral)</span> 2026**. [CCF A]
- ``EMNLP 2025`` [VideoEraser: Concept Erasure in Text-to-Video Diffusion Models](https://arxiv.org/abs/2508.15314), <u>Naen Xu</u>, Jinghuai Zhang, Changjiang Li, Zhi Chen, Chunyi Zhou, Qingming Li, **Tianyu Du***, Shouling Ji, **EMNLP (Main) 2025**. [CCF-B]

# 💻 Experience
- *2022.08 - 2023.08*, Postdoctoral Scholar, Penn State University.
- *2017.03 - 2018.03*, Research Scientist Intern, Alibaba, Hangzhou.

# 🎓 Education
- *2024.09 – 2027.06 (expected)*, M.E., Software Engineering, Zhejiang University, Hangzhou. 
- *2020.09 - 2024.06*, B.E., Cyberspace Security, Nanjing University of Science and Technology, Nanjing. 


# 🎖 Honors and Awards
- *2026.10* National Scholarship (Master)
- *2023.10* National Scholarship (Undergraduate)
