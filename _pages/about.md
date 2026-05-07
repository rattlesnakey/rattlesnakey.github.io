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
🤓 Hey folks! I am Hengyuan Zhang (张恒源 in Chinese), a first-year PhD student in the [Ngai Lab](https://hku-ngai.github.io/) at the University of Hong Kong. Before going to college, I grew up in Xiamen, a beautiful coastal city in China.
<!-- [HKU NGai Lab](https://hku-ngai.github.io/) -->
<!-- Currently, I am a master's student (3rd year) at Tsinghua University under the supervision of Prof. [Yong Jiang](https://www.semanticscholar.org/author/Yong-Jiang/101321464) and Prof. [Yujiu Yang](https://scholar.google.com/citations?user=4gH3sxsAAAAJ&hl=zh-CN).  -->
<!-- Currently, I am a master's student (3rd year) at Tsinghua University. -->
 <!-- such as *Multilingualism*, *Education*, and *Cognitive Science*. -->
📚 My research interests revolve around the application of **Natural Language Processing (NLP)** and **Data Mining** in specialized domains.
 <!-- I aim to approach these studies in an **interpretable** manner, seeking deeper insights into complex phenomena. -->

🧐 I am particularly intrigued by the decision-making mechanisms integrated within models, eager to unravel their inner workings and enhance transparency.
All in all, I aim to improve the **speciality** and **interpretability** of models, so as to make them more **powerful** and **trustworthy** in real-world applications.

<!-- Looking ahead, I am exploring the possibility of **enrolling in a Ph.D. program for the Fall of 2025**.  -->
📮 I am keen on exploring opportunities for collaboration in research or projects 😊. Please do not hesitate to contact me at your convenience!


<span class='anchor' id='-pub'></span>

<!-- # 📚 Preprint -->



# 📝 Publications
<!-- \* denotes equal contribution -->

<!-- Preprint 2026 Survey -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Locate, Steer, and Improve: A Practical Survey of Actionable Mechanistic Interpretability in Large Language Models** 

`Hengyuan Zhang`, Zhihao Zhang, Mingyang Wang, et al., Sophia Ananiadou, Tao Gui, Ruobing Xie, Hayden Kwok-Hay So, Hinrich Schütze, Xuanjing Huang, Qi Zhang, Ngai Wong

[[Paper]](https://arxiv.org/pdf/2601.14004) | [[Code]](https://github.com/rattlesnakey/Awesome-Actionable-MI-Survey) | [机器之心](https://mp.weixin.qq.com/s/Nrd-hpkkN9HT6cfickVY0Q) | *Natural Language Processing, Actionable Mechanistic Interpretability* | *Journal Preprint*

- This paper presents a practical survey that reframes mechanistic interpretability under a unified “Locate, Steer, and Improve” pipeline, systematically transforming MI from an observational analysis into an actionable framework for model intervention and improvement.

</div>
</div>

<!-- Preprint 2026 Survey -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/AS-Survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Attention Sink in Transformers: A Survey on Utilization, Interpretation, and Mitigation** 

Zunhai Su, `Hengyuan Zhang`, et al., Jing Xiong, Hui Shen, Chaofan Tao, Taiqiang Wu, Zhongwei Wan, Yulei Qian, Yuchen Xie, Ngai Wong

[[Paper]](https://arxiv.org/pdf/2604.10098) | [[Code]](https://github.com/ZunhaiSu/Awesome-Attention-Sink) | [机器之心](https://mp.weixin.qq.com/s/lu8qvvJujGShtM7eHLeyBA) | *Natural Language Processing, Attention Sink Interpretability* | *Journal Preprint*

- This paper presents the first comprehensive survey on Attention Sink (AS) in Transformers, systematically organizing existing research along three core dimensions—Fundamental Utilization, Mechanistic Interpretation, and Strategic Mitigation.

</div>
</div>


<!-- Preprint 2026 NSDS -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/NSDS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Beyond Outliers: A Data-Free Layer-wise Mixed-Precision Quantization Approach Driven by Numerical and Structural Dual-Sensitivity** 

`Hengyuan Zhang`, Xinrong Chen, Zunhai Su, Xiao Liang, et al., Wei Zhang, Ruobing Xie, Lei Jiang, Hayden Kwok-Hay So, Ngai Wong

[[Paper]](https://arxiv.org/pdf/2603.17354) | [[Code]](https://github.com/rattlesnakey/NSDS) | *Natural Language Processing, Interpretability in Quantization* | *Preprint*

- This paper proposes NSDS, a data-free layer-wise mixed-precision quantization approach that leverages the dual-sensitivity of numerical and structural features to guide the bit allocation process.

</div>
</div>



<!-- ACL 2025 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026</div><img src='images/PerSyn.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Find Your Optimal Teacher: Personalized Data Synthesis via Router-Guided Multi-Teacher Distillation** 

`Hengyuan Zhang`, Shiping Yang, Xiao Liang, et al., Chaofan Tao, Jing Xiong, Hayden Kwok-Hay So, Ruobing Xie, Angel X. Chang, Ngai Wong

[[Paper]](https://arxiv.org/pdf/2510.10925) | [[Code]](https://github.com/rattlesnakey/PerSyn) | *Natural Language Processing, Interpretability in Data Synthesis* | *CCF-A Conference*

- This paper proposes PerSyn, a novel data synthesis strategy that operates under a new "Route then Generate" paradigm to create data tailored to each student model, enabling it to learn more effectively.

</div>
</div>


<!-- ACL 2025 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/ShifCon.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**ShifCon: Enhancing Non-Dominant Language Capabilities with a Shift-based Contrastive Framework** 

`Hengyuan Zhang`, Chenming Shang, Sizhe Wang, Dongdong Zhang, Feng Yao, Renliang Sun, Yiyao Yu, Yujiu Yang, Furu Wei 

[[Paper]](https://arxiv.org/pdf/2410.19453) | [[Code]](https://github.com/rattlesnakey/ShifCon) | *Natural Language Processing, Interpretability in Multilingualism* | *CCF-A Conference*

- This paper aims to enhance the performance of non-dominant languages by projecting their representations into the dominant language space. We pinpoint the optimal layer area for shifting representations via a subspace distance metric. <span style="color:red">(OpenReview Score: [4, 4, 4.5])</span>

</div>
</div>

<!-- EMNLP 2025 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025</div><img src='images/GuiLoMo.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**GuiLoMo: Allocating Expert Number and Rank for LoRA-MoE via Bilevel Optimization with GuidedSelection Vectors** 

`Hengyuan Zhang`, Xinrong Chen, Xiao Liang, Ziyue Li, et al., Ngai Wong

[[Paper]](https://arxiv.org/pdf/2506.14646?) | [[Code]](https://github.com/Liar406/Gui-LoMo) | *Natural Language Processing, Interpretability in Efficient Training* | *CCF-B Conference*

- This paper introduces a fine-grained strategy, i.e., GuiLoMo, for jointly allocating optimal layer-wise expert numbers and ranks in LoRA-MoE based on bilevel optimization with GuidedSelection vectors.

</div>
</div>


<!-- ACL 2024 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/CoFiTune.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Balancing Speciality and Versatility: A Coarse to Fine Framework for Mitigating Catastrophic Forgetting in Large Language Models**

`Hengyuan Zhang`, Yanru Wu, Dawei Li, Zacc Yang, Rui Zhao, Yong Jiang, Fei Tan
<!-- `Hengyuan Zhang`, et al -->

[[Paper]](https://arxiv.org/pdf/2404.10306.pdf) | [[Code]](https://github.com/rattlesnakey/CoFiTune) | *Natural Language Processing, Interpretability in Knowledge Management* | *CCF-A Conference*

- This paper introduces a Coarse-to-Fine Fine-tuning framework (*CoFiTune*) that strikes a delicate balance between speciality and versatility. It pinpoints and updates specific modules that are crucial for speciality, while keeping other parameters frozen.
</div>
</div>

<!-- TKDD -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TKDD 2024</div><img src='images/Q-MCKT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**A Question-centric Multi-experts Contrastive Learning Framework for Improving the Accuracy and Interpretability of Deep Sequential Knowledge Tracing Models**

`Hengyuan Zhang`, Zitao Liu, Chenming Shang, Dawei Li, Yong Jiang

[[Paper]](https://arxiv.org/pdf/2403.07322.pdf) | [[Code]](https://github.com/rattlesnakey/Q-MCKT) | *Data Mining, Interpretability in Education Recommendation* | *JCR Q1 Journal*

- This paper proposes Q-MCKT framework, which utilizes an item response theory-based prediction layer to generate interpretable prediction results by simultaneously modeling knowledge acquisition and question difficulty.
</div>
</div>



- <span style="background-color:rgba(2,34,141);color:white">ACL 2026</span>
 **Training LLMs for Divide-and-Conquer Reasoning Elevates Test-Time Scalability** \\
Xiao Liang, Zhong-Zhi Li, Zhenghao Lin, `Hengyuan Zhang`, Yelong Shen, Kai-Wei Chang, Ying Nian Wu, Yeyun Gong, Weizhu Chen\\
[[Paper]](https://arxiv.org/pdf/2602.02477) | [[Code]](https://github.com/MasterVito/DAC-RL) | *Natural Language Processing, Reasoning Enhancement* | *CCF-A Conference*

- <span style="background-color:rgba(2,34,141);color:white">ACL 2026</span>
 **Quantifying the Robustness of Retrieval-Augmented Language Models Against Spurious Features in Grounding Data** \\
Shiping Yang, Jie Wu, Wenbiao Ding, et al., `Hengyuan Zhang`, Dongmei Zhang\\
[[Paper]](https://arxiv.org/pdf/2503.05587) | *Natural Language Processing, Phenomenon Analysis* | *CCF-A Conference*

- <span style="background-color:rgba(2,34,141);color:white">Preprint 2026</span>
 **MMFormalizer: Multimodal Autoformalization in the Wild** \\
 Jing Xiong, Qi Han, Yunta Hsieh, Hui Shen, et al., `Hengyuan Zhang`, Taiqiang Wu, Haochen Wang, Zhongwei Wan, Lingpeng Kong, Ngai Wong\\
[[Paper]](https://arxiv.org/pdf/2601.03017) | *Natural Language Processing, Multimodal Analysis* | *Conference Preprint*



- <span style="background-color:rgba(2,34,141);color:white">CVPR 2026</span>
 **Residual Decoding: Mitigating Hallucinations in Large Vision-Language Models via History-Aware Residual Guidance** \\
Xinrong Chen, Xu Chu, Yingmin Qiu, `Hengyuan Zhang`, Jing Xiong, et al., Hayden Kwok-Hay So, Ngai Wong\\
[[Paper]](https://arxiv.org/pdf/2602.01047) | *Natural Language Processing, Multimodal Analysis* | *CCF-A Conference*

<!-- NIPS Sws-->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/LoReKT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
- <span style="background-color:rgba(2,34,141);color:white">NeurIPS 2025</span>
 **SwS: Self-aware Weakness-driven Problem Synthesis in Reinforcement Learning for LLM Reasoning** \\
 Xiao Liang, Zhong-Zhi Li, Yeyun Gong, Yang Wang, `Hengyuan Zhang`, Yelong Shen, Ying Nian Wu, Weizhu Chen\\
[[Paper]](https://arxiv.org/pdf/2506.08989?) | *Natural Language Processing, Data Synthesis* | *CCF-A Conference*

<!-- ACL 2025 yiyao-->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/LoReKT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
- <span style="background-color:rgba(2,34,141);color:white">ACL 2025</span>
 **Chain-of-Reasoning: Towards Unified Mathematical Reasoning in Large Language Models via a Multi-Paradigm Perspective** \\
Yiyao Yu, Yuxiang Zhang, Dongdong Zhang, Xiao Liang, `Hengyuan Zhang`, et al., Yujiu Yang, Furu Wei\\
[[Paper]](https://arxiv.org/pdf/2501.11110) | *Natural Language Processing, Fine-tuning Technique* | *CCF-A Conference*


<!-- EMNLP TreeReview-->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/LoReKT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
- <span style="background-color:rgba(2,34,141);color:white">EMNLP 2025</span>
**TreeReview: A Dynamic Tree of Questions Framework for Deep and Efficient LLM-based Scientific Peer Review** \\
Yuan Chang, Ziyue Li, `Hengyuan Zhang`, Yuanbo Kong, Yanru Wu, Zhijiang Guo, Ngai Wong\\
[[Paper]](https://arxiv.org/pdf/2506.07642) | *Natural Language Processing* | *CCF-B Conference*

<!-- NAACL 2025-2 -->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/BPO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
- <span style="background-color:rgba(2,34,141);color:white">NAACL 2025</span>
 **BPO: Towards Balanced Preference Optimization between Knowledge Breadth and Depth in Alignment**\\
Sizhe Wang, Yongqi Tong, `Hengyuan Zhang`, Dawei Li, Xin Zhang, Tianlong Chen \\
[[Paper]](https://arxiv.org/pdf/2411.10914) | *Natural Language Processing, Fine-tuning Technique* | *CCF-B Conference*


<!-- EMNLP GuiLoMo-->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/LoReKT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
<!-- - <span style="background-color:rgba(2,34,141);color:white">Preprint 2025</span>
 **GuiLoMo: Allocating Expert Number and Rank for LoRA-MoE via Bilevel Optimization with GuidedSelection Vectors** \\
`Hengyuan Zhang`, Xinrong Chen, Yingmin Qiu, Xiao Liang, et al., Hayden Kwok-Hay So, Ngai Wong\\
[[Paper]](https://arxiv.org/pdf/2506.14646?) | *Natural Language Processing, Fine-tuning Technique* | *Conference Preprint* -->




<!-- ACL 2025 shiping-->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/LoReKT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->


<!-- TKDE -->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/LoReKT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
- <span style="background-color:rgba(2,34,141);color:white">Preprint 2024</span>
 **Improving Low-Resource Knowledge Tracing Tasks by Supervised Pre-training and Importance Mechanism Fine-tuning**\\
`Hengyuan Zhang`, Zitao Liu, Shuyan Huang, Chenming Shang, Bojun Zhan, Yong Jiang\\
[[Paper]](https://arxiv.org/pdf/2403.06725.pdf) | [[Code]](https://anonymous.4open.science/r/LoReKT-C619/README.md) | *Data Mining, Education Recommendation* | *Journal Preprint*

<!-- ICLR 2025 -->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/LoReKT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
<!-- - <span style="background-color:rgba(2,34,141);color:white">Preprint 2024</span>
 **Compositional Generalization Through Neuroscience-inspired Geometric Constraints on Representation Structure**\\
Chenming Shang, Shiji Zhou, `Hengyuan Zhang`, Xinchen Zhang, Lei Ke, Yuwang Wang, Yujiu Yang\\
[[Paper]](https://ns7kunkhuh.feishu.cn/file/EI8jb6luDoiDQUxYosVc2q3enGd?from=from_copylink) | *Computer Vision, Cognitive Science, Interpretability in Representation* | *Conference Preprint* -->

<!-- CogSci CBM -->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CogSci 2024</div><img src='images/CogSci.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
- <span style="background-color:rgba(2,34,141);color:white">CogSci 2024</span>
 **Understanding Multimodal Deep Neural Networks: A Concept Selection View**\\
Chenming Shang, `Hengyuan Zhang`, Hao Wen, Yujiu Yang\\
[[Paper]](https://arxiv.org/pdf/2404.08964.pdf) | *Computer Vision, Cognitive Science, Interpretability in Prediction* | *CCF-B Conference*



<!-- CVPR Res-CBM -->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/Res-CBM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
- <span style="background-color:rgba(2,34,141);color:white">CVPR 2024</span>
 **Incremental Residual Concept Bottleneck Model**\\
Chenming Shang, Shiji Zhou, `Hengyuan Zhang`, Yujiu Yang, Xinzhe Ni, Yuwang Wang\\
[[Paper]](https://arxiv.org/pdf/2404.08978.pdf) | [[Code]](https://github.com/HelloSCM/Res-CBM) | *Computer Vision, Cognitive Science, Interpretability in Prediction* | *CCF-A Conference*




<!-- emnlp character -->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2023</div><img src='images/emnlp2023-character.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
- <span style="background-color:rgba(2,34,141);color:white">EMNLP 2023</span>
 **Multi-level Contrastive Learning for Script-based Character Understanding**\\
Dawei Li, `Hengyuan Zhang`, Yanran Li, Shiping Yang\\
[[Paper]](https://arxiv.org/pdf/2310.13231v1.pdf) | [[Code]](https://github.com/David-Li0406/Script-based-Character-Understanding) | *Natural Language Processing, Cognitive Science* | *CCF-B Conference*


<!-- ACL BEA workshop -->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2023 BEA</div><img src='images/prompt-contrast-def-gen.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
- <span style="background-color:rgba(2,34,141);color:white">ACL 2023 BEA</span>
 **Assisting Language Learners: Automated Trans-Lingual Definition Generation via Contrastive Prompt Learning**\\
`Hengyuan Zhang`, Dawei Li, Yanran Li, Chenming Shang, Chufan Shi, Yong Jiang\\
[[Paper]](https://arxiv.org/abs/2306.06058) | [[Code]](https://github.com/rattlesnakey/Prompt-Contrastive-Def-Gen) | *Natural Language Processing, Education, Interpretability in Representation* | *CCF-A Conference*



<!-- AACL 2022 def-gen -->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">AACL 2022 Oral</div><img src='images/def-gen-contrast.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
- <span style="background-color:rgba(2,34,141);color:white">AACL 2022</span><span style="color:red">(Oral)</span>
 **Fine-grained Contrastive Learning for Definition Generation**\\
`Hengyuan Zhang`, Dawei Li, Shiping Yang, Yanran Li\\
[[Paper]](https://arxiv.org/abs/2210.00543) | [[Code]](https://github.com/rattlesnakey/Definition-Gneration-Contrastive) | *Natural Language Processing, Education, Interpretability in Representation* | *Conference*



<!-- - <span style="background-color:rgba(2,34,141);color:white">AACL 2022</span><span style="color:red">(Oral)</span>
**Fine-grained Contrastive Learning for Definition Generation**\\ 
`Hengyuan Zhang`, Dawei Li, Shiping Yang, Yanran Li\\
[[Paper]](https://arxiv.org/abs/2210.00543) | [[Code]](https://github.com/rattlesnakey/Definition-Gneration-Contrastive) | *Natural Language Processing, Education, Interpretability in Representation* | *Conference* -->


<!-- ACL 2022 multitask -->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2022</div><img src='images/multitask-def-gen.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
<!-- - <span style="background-color:rgba(2,34,141);color:white">ACL 2022</span>
 **Multitasking Framework for Unsupervised Simple Definition Generation**\\
Cunliang Kong, Yun Chen, `Hengyuan Zhang`, Liner Yang, Erhong Yang\\
[[Paper]](https://arxiv.org/abs/2203.12926) | [[Code]](https://github.com/blcuicall/SimpDefiner) | *Natural Language Processing, Education, Interpretability in Representation* | *CCF-A Conference* -->



<!-- NAACL SemEval -->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">NAACL 2022 SemEval</div><img src='images/semeval.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
<!-- - <span style="background-color:rgba(2,34,141);color:white">NAACL 2022 SemEval</span>
 **SemEval-2022 Task 1: Cross-Attention Multitasking Framework for Definition Modeling**\\
Cunliang Kong, Yujie Wang, Ruining Chong, Liner Yang, `Hengyuan Zhang`, Erhong Yang\\
[[Paper]](https://arxiv.org/abs/2204.07701) | [[Code]](https://github.com/blcuicall/SemEval2022-Task1-DM) | *Natural Language Processing, Education, Interpretability in Representation* | *CCF-B Conference* -->




<span class='anchor' id='-intern'></span>
# 💻 Interships
<!-- icall -->
<!-- <img class="svg" src="/images/icall.png" width="60pt">Advanced Innovation Center for Language Resources, Beijing 
<br>
- *Mar. 2019 - Oct. 2021*, Research Assistant, working with [Cunliang Kong](https://scholar.google.com/citations?hl=zh-CN&user=XMkdWRwAAAAJ&view_op=list_works&sortby=pubdate) and [Liner Yang](https://tianlinyang.github.io/index_en.html) -->


<!-- baidu -->
<!-- <img class="svg" src="/images/baidu.png" width="60pt">Baidu, Search Strategy Lab, Beijing
<br>
- *Mar. 2021 - Jul. 2021*, Engineering Intern, working with Ge Chen -->
<!-- <img class="svg" src="/images/baidu.png" width="60pt">Baidu, Search Strategy Lab, Beijing
<br>
- *Mar. 2021 - Jul. 2021*, Engineering Intern -->

<!-- <br> -->
<!-- xiaomi -->
<!-- <img class="svg" src="/images/xiaomi-logo.png" width="30pt"> Xiaomi, AI Lab, Beijing
<br>
- *Mar. 2022 - Sept. 2022*, Research Intern, working with Tong Chen and [Yanran Li](https://scholar.google.com/citations?user=URdBBQUAAAAJ&hl=zh-CN) -->
<img class="svg" src="/images/xiaomi-logo.png" width="30pt"> Xiaomi, AI Lab, Beijing
<br>
- *Mar. 2022 - Sept. 2022*, Research Intern



<!-- <br> -->
<!-- tencent -->
<!-- <img class="svg" src="/images/tencent.png" width="70pt"> Tencent, AI Lab, Shenzhen
<br>
- *Mar. 2023 - Jul. 2023*, Research Intern, working with [Wei Bi](https://scholar.google.com/citations?hl=zh-CN&user=aSJcgQMAAAAJ&view_op=list_works&sortby=pubdate) -->
<img class="svg" src="/images/tencent.png" width="70pt"> Tencent, AI Lab, Shenzhen
<br>
- *Mar. 2023 - Jul. 2023*, Research Intern

<!-- <br> -->
<!-- sensetime -->
<!-- <img class="svg" src="/images/sensetime.png" width="85pt">Sensetime, Research, Shenzhen
<br>
- *Aug. 2023 - Mar. 2024*, Research Intern, working with [Fei Tan](https://scholar.google.com/citations?hl=zh-CN&user=IhYATC0AAAAJ&view_op=list_works&sortby=pubdate) -->
<img class="svg" src="/images/sensetime.png" width="85pt"> Sensetime, Research, Shenzhen
<br>
- *Aug. 2023 - Mar. 2024*, Research Intern
<!-- <br> -->

<!--MSRA -->
<!-- <img class="svg" src="/images/MSRA.png" width="60pt">Microsoft Research Asia, NLC Group, Beijing
<br>
- *Mar. 2024 - Dec. 2024*, Research Intern, working with [DongDong Zhang](https://scholar.google.com/citations?user=w2qu71oAAAAJ&hl=en) 
  - I got the <span style="color:red">"Microsoft Stars of Tomorrow"</span> Award during the internship -->

<img class="svg" src="/images/MSRA.png" width="60pt"> Microsoft Research Asia, NLC Group, Beijing
<br>
- *Mar. 2024 - Dec. 2024*, Research Intern
  - I got the <span style="color:red">"Microsoft Stars of Tomorrow"</span> Award during the internship

<img class="svg" src="/images/AMD_logo.svg" width="60pt"> AMD, Quantization Group, Beijing
<br>
- *Feb. 2025 - Aug. 2025*, Research Intern
  
<img class="svg" src="/images/tencent-logo.png" width="60pt"> Tencent Rhino-Bird Elite Research Program, Shenzhen
<br>
- *Sept. 2025 - Present*, Research Intern

<!-- <br> -->




<br>
<span class='anchor' id='-honor'></span>

# 🏅 Selected Honors and Awards
👉  HKU Y S and Christabel Lung Postgraduate Scholarship (Top 3%, HKD $ 20,000) \| *2025*

👉  Tsinghua University Comprehensive First-Class Scholarship (Top 3%, RMB ¥ 10,000) \| *2024*

👉  Tsinghua University General Excellence Scholarship (Top 5%, RMB ¥ 4,000) \| *2023*

👉  National Scholarship (Top 1%, 3 Times, RMB ¥ 24,000) \| *2019, 2020, 2021*

👉  Outstanding Graduate Student of Beijing (Top 3%) \| *2022*

👉  Excellent League Member of Beijing (Top 3%) \| *2021*

👉  Merit Student of Beijing (Top 3%) \| *2021*

👉  Meritorious Winner of Interdisciplinary Contest in Modeling (Top 5%) \| *2021*

👉  Computer Design Competition National Second Prize (Top 5%) \| *2020*

👉  CUMCM-Beijing Area First Prize (Top 5%) \| *2020*     

👉  Xiaomi Third Hacker Marathon Excellence (Top 7%, RMB ¥ 3,000) \| *2022*



<!-- <br>
<span class='anchor' id='-miscellaneous'></span>
# ⛳️ Extracurricular Activities
- Vice Minister of the Academic Department, SIGS Student Union, Tsinghua University  -->


<br>
<span class='anchor' id='-miscellaneous'></span>
# 📌 Miscellaneous
 <!-- [[**Rednote**]] -->
## 📖 Academic & Community Engagement
- I once led the Academic Department of SIGS Student Union at Tsinghua University. During which, I organized academic activities such as academic forums and experience-sharing sessions. I am also a member of the Beijing Xiamen ECC (北京厦门企业商会), actively participating in sharing activities [[Link]](https://mp.weixin.qq.com/s/DFG97r0-hL12VYFAeshpHA). Furthermore, I am keen on participating in academic events to present my ideas and making a positive impact on the community.

<div style="display: flex; justify-content: space-between; gap: 2%; margin-top: 15px;">
  <!-- 注意：请将这里的 src 替换为你真实的学术活动照片路径 -->
  <img src="images/academic1.jpg" alt="Academic Activity 1" style="width: 32%; border-radius: 8px; object-fit: cover; aspect-ratio: 4/3;" />
  <img src="images/academic2.jpg" alt="Academic Activity 2" style="width: 32%; border-radius: 8px; object-fit: cover; aspect-ratio: 4/3;" />
  <img src="images/academic3.jpg" alt="Academic Activity 3" style="width: 32%; border-radius: 8px; object-fit: cover; aspect-ratio: 4/3;" />
</div>


- I am actually a person with a strong desire to share. In my spare time, I actively write blogs on [[<img src="https://cdn.simpleicons.org/xiaohongshu/FF2442" width="27" style="vertical-align: middle; margin-bottom: 2px;"> **Rednote**]](https://www.xiaohongshu.com/user/profile/5b436cc5f7e8b976f413343f?xsec_token=YBv9botEIHUitz7ZFPPhcIIdqhpMeuw6qak58zvB3MiLc=&xsec_source=app_share&xhsshare=CopyLink&appuid=5b436cc5f7e8b976f413343f&apptime=1746533636&share_id=4cf62cfa0abb409ab33119e85f32af07), [[<img src="https://cdn.simpleicons.org/wechat/07C160" width="22" style="vertical-align: middle; margin-bottom: 2px;"> **Wechat Official Account**]](https://mp.weixin.qq.com/mp/profile_ext?action=home&__biz=Mzk0NTI3ODI2OQ==&scene=124#wechat_redirect), and [[<img src="https://cdn.simpleicons.org/bilibili/FB7299" width="22" style="vertical-align: middle; margin-bottom: 2px;"> **Bilibili**]](https://space.bilibili.com/14709944?spm_id_from=333.1007.0.0) (阿源的NLP碎碎念) to share knowledge and experiences. The selected blogs are as follows:
  - [Interpreting Arithmetic Calculation Modules within LLMs](https://mp.weixin.qq.com/s/D4z8zHmr3cij5_d5rOgLwg)
  - [Interpreting Security Modules within Large Language Model](https://mp.weixin.qq.com/s/3693Q7NPnRoH0r4S0RiEDA?token=889452301&lang=zh_CN)
  - [Do Llama Work in English?](https://mp.weixin.qq.com/s/8EB1q8w9DmIw_M7msK_cgw?token=889452301&lang=zh_CN)
  - [Interpreting Linguistic Regions with in LLMs](https://mp.weixin.qq.com/s/-FHKqUieqJuO3VoTozS4Mw) 
  - [Prevent Catastrophic Forgetting via SoftMask Mechanism](https://mp.weixin.qq.com/s/udjiYzt7cwCdlH1a98ylbA)
  - [The Key Components in Transformer](https://mp.weixin.qq.com/s/hXMEQ7ZPF53-iyOzZRXXZg)
  - [The Evaluation of Instruction Following](https://mp.weixin.qq.com/s/m3RHJ9q-RCkGL33AewdDUg)
  - [Skill Localization of Large Language Model](https://mp.weixin.qq.com/s/x61tHD896Leoz8DO-0weAg)
  - [iMAge-guided Text GeneratIon with CLIP](https://mp.weixin.qq.com/s/fQ6t96aqAgvRDAIjIt9QYA)


- I also participated in social activities such as rural revitalization, representing Tsinghua in a Swiss "Global Warming" forum, and helping international students with Chinese, computer, and math.

<div style="display: flex; justify-content: space-between; gap: 2%; margin-top: 15px;">
  <!-- 注意：请将这里的 src 替换为你真实的学术活动照片路径 -->
  <img src="images/fuding.jpg" alt="Extra Activity 1" style="width: 32%; border-radius: 8px; object-fit: cover; aspect-ratio: 4/3;" />
  <img src="images/swiss.jpg" alt="Extra Activity 2" style="width: 32%; border-radius: 8px; object-fit: cover; aspect-ratio: 4/3;" />
  <img src="images/tutoring.jpg" alt="Extra Activity 3" style="width: 32%; border-radius: 8px; object-fit: cover; aspect-ratio: 4/3;" />
</div>

<br>

## 🎸 Hobbies & Life
- I used to be a guitarist 🎸 in a band when I was in high school. Also, I love playing badminton 🏸, table tennis 🏓 and, soccer ⚽️. During holidays, I will also seize any opportunity to travel around the world ⛳️.

<p style="margin-top: 20px; font-weight: bold; color: #555;">🎤 Band & Singing</p>
<div style="display: flex; flex-wrap: wrap; gap: 15px; justify-content: center; margin-top: 15px;">
<!-- 带有 Video 标签的 4 张唱歌照片 -->
  <div style="width: 22%; text-align: center; position: relative;">
    <!-- <img src="images/singing1.jpg" alt="Singing 1" style="width: 100%; border-radius: 8px; aspect-ratio: 1; object-fit: cover;" /> -->
    <img src="images/singing4_1.png" alt="Singing 1" style="width: 100%; border-radius: 8px; aspect-ratio: 1; object-fit: contain; background-color: #f8f9fa;" />
    <!-- 注意：请将这里的 href 替换为你真实的视频链接 -->
    <a href="https://www.bilibili.com/video/BV1T4411a7KH/?spm_id_from=333.1387.upload.video_card.click" target="_blank" style="display: inline-block; margin-top: 8px; padding: 4px 8px; background-color: #f8f9fa; border-radius: 4px; font-size: 0.85em; color: #d9534f; text-decoration: none; font-weight: bold; border: 1px solid #ddd; transition: 0.3s;">▶️ Watch Video</a>
  </div>
  <div style="width: 22%; text-align: center; position: relative;">
    <img src="images/singing3_1.jpg" alt="Singing 2" style="width: 100%; border-radius: 8px; aspect-ratio: 1; object-fit: cover;" />
    <a href="https://www.bilibili.com/video/BV1d7411z7YY/?spm_id_from=333.1387.upload.video_card.click" target="_blank" style="display: inline-block; margin-top: 8px; padding: 4px 8px; background-color: #f8f9fa; border-radius: 4px; font-size: 0.85em; color: #d9534f; text-decoration: none; font-weight: bold; border: 1px solid #ddd; transition: 0.3s;">▶️ Watch Video</a>
  </div>
  <div style="width: 22%; text-align: center; position: relative;">
    <img src="images/singing1.jpg" alt="Singing 3" style="width: 100%; border-radius: 8px; aspect-ratio: 1; object-fit: cover;" />
    <a href="https://www.xiaohongshu.com/discovery/item/67efe4ac000000001202d0c5?source=webshare&xhsshare=pc_web&xsec_token=ABX0dqg2iOwWFvi88JTOIgudhF40KsyZs8E6nDRT_b9Y0=&xsec_source=pc_share" target="_blank" style="display: inline-block; margin-top: 8px; padding: 4px 8px; background-color: #f8f9fa; border-radius: 4px; font-size: 0.85em; color: #d9534f; text-decoration: none; font-weight: bold; border: 1px solid #ddd; transition: 0.3s;">▶️ Watch Video</a>
  </div>
  <div style="width: 22%; text-align: center; position: relative;">
    <img src="images/singing2.jpg" alt="Singing 4" style="width: 100%; border-radius: 8px; aspect-ratio: 1; object-fit: cover;" />
    <a href="https://www.xiaohongshu.com/explore/6873c7f300000000100252be?source=webshare&xhsshare=pc_web&xsec_token=ABOo4uYc8fjwpZi8TWiDAk6hU3L_YocGmsJwrDj0MQxjw=&xsec_source=pc_share" target="_blank" style="display: inline-block; margin-top: 8px; padding: 4px 8px; background-color: #f8f9fa; border-radius: 4px; font-size: 0.85em; color: #d9534f; text-decoration: none; font-weight: bold; border: 1px solid #ddd; transition: 0.3s;">▶️ Watch Video</a>
  </div>
</div>

<p style="margin-top: 35px; font-weight: bold; color: #555;">🏸 Sports & Travel</p>
<div style="display: flex; flex-wrap: wrap; gap: 15px; justify-content: center;">
  <!-- 原有的 4 张图片 -->
  <div style="width: 22%; text-align: center;">
    <img src="images/badminton.jpg" alt="Life 1" style="width: 100%; border-radius: 8px; aspect-ratio: 1; object-fit: cover;" />
  </div>
  <div style="width: 22%; text-align: center;">
    <img src="images/life2_1.png" alt="Life 2" style="width: 100%; border-radius: 8px; aspect-ratio: 1; object-fit: cover;" />
  </div>
  <div style="width: 22%; text-align: center;">
    <img src="images/life3_1.png" alt="Life 3" style="width: 100%; border-radius: 8px; aspect-ratio: 1; object-fit: cover;" />
  </div>
  <div style="width: 22%; text-align: center;">
    <img src="images/life4.png" alt="Life 4" style="width: 100%; border-radius: 8px; aspect-ratio: 1; object-fit: cover;" />
  </div>


  <!-- 剩余的 6 张兴趣/生活照片 -->
  <div style="width: 22%; text-align: center;">
    <img src="images/life5.jpg" alt="Life 5" style="width: 100%; border-radius: 8px; aspect-ratio: 1; object-fit: cover;" />
  </div>
  <div style="width: 22%; text-align: center;">
    <img src="images/life6.jpg" alt="Life 6" style="width: 100%; border-radius: 8px; aspect-ratio: 1; object-fit: cover;" />
  </div>
  <div style="width: 22%; text-align: center;">
    <img src="images/life7.jpg" alt="Life 7" style="width: 100%; border-radius: 8px; aspect-ratio: 1; object-fit: cover;" />
  </div>
  <div style="width: 22%; text-align: center;">
    <img src="images/life8_2.jpg" alt="Life 8" style="width: 100%; border-radius: 8px; aspect-ratio: 1; object-fit: cover;" />
  </div>
</div>




