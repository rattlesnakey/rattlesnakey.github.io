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

🤓 Hey folks! I am Hengyuan Zhang (张恒源 in Chinese). Before going to college, I grew up in Xiamen, a beautiful coastal city in China.

Currently, I am a master's student (3rd year) at Tsinghua University under the supervision of Prof. [Yong Jiang](https://www.semanticscholar.org/author/Yong-Jiang/101321464) and Prof. [Yujiu Yang](https://scholar.google.com/citations?user=4gH3sxsAAAAJ&hl=zh-CN). 


📚 My research interests revolve around the application of **Natural Language Processing (NLP)** and **Data Mining** in specialized domains such as *Multilingualism*, *Education*, and *Cognitive Science*. I aim to approach these studies in an **interpretable** manner, seeking deeper insights into complex phenomena.
I am also particularly intrigued by the decision-making mechanisms integrated within models, eager to unravel their inner workings and enhance transparency.
All in all, I aim to improve the **speciality** and **interpretability** of models, so as to make them more **powerful** and **trustworthy** in real-world applications.

📮 Looking ahead, I am exploring the possibility of **enrolling in a Ph.D. program for the Fall of 2025**. 
I am also keen on exploring opportunities for collaboration in research or projects. Please do not hesitate to contact me at your convenience.


<span class='anchor' id='-pub'></span>

<!-- # 📚 Preprint -->




# 📝 Publications
<!-- \* denotes equal contribution -->

<!-- ACL 2025 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/ShifCon.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**ShifCon: Enhancing Non-Dominant Language Capabilities with a Shift-based Contrastive Framework** 

`Hengyuan Zhang`, Chenming Shang, Sizhe Wang, Dongdong Zhang, Feng Yao, Renliang Sun, Yiyao Yu, Yujiu Yang, Furu Wei 

[[Paper]](https://arxiv.org/pdf/2410.19453) | [[Code]](https://github.com/rattlesnakey/ShifCon) | *Natural Language Processing, Multilingual, Interpretability in Parameter* | *Conference Preprint*

- This paper aims to enhance the performance of non-dominant languages by projecting their representations into the dominant language space. We pinpoint the optimal layer area for shifting representations via a subspace distance metric. <span style="color:red">(OpenReview Score: [4, 4, 4.5])</span>

</div>
</div>



<!-- ACL 2024 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/CoFiTune.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Balancing Speciality and Versatility: A Coarse to Fine Framework for Mitigating Catastrophic Forgetting in Large Language Models**

`Hengyuan Zhang`, Yanru Wu, Dawei Li, Zacc Yang, Rui Zhao, Yong Jiang, Fei Tan
<!-- `Hengyuan Zhang`, et al -->

[[Paper]](https://arxiv.org/pdf/2404.10306.pdf) | [[Code]](https://github.com/rattlesnakey/CoFiTune) | *Natural Language Processing, Fine-tuning Technique, Interpretability in Parameter* | *CCF-A Conference*

- This paper introduces a Coarse-to-Fine Fine-tuning framework (*CoFiTune*) that strikes a delicate balance between speciality and versatility. It pinpoints and updates specific modules that are crucial for speciality, while keeping other parameters frozen.
</div>
</div>

<!-- TKDD -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TKDD 2024</div><img src='images/Q-MCKT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**A Question-centric Multi-experts Contrastive Learning Framework for Improving the Accuracy and Interpretability of Deep Sequential Knowledge Tracing Models**

`Hengyuan Zhang`, Zitao Liu, Chenming Shang, Dawei Li, Yong Jiang

[[Paper]](https://arxiv.org/pdf/2403.07322.pdf) | [[Code]](https://github.com/rattlesnakey/Q-MCKT) | *Data Mining, Education Recommendation, Interpretability in Prediction* | *JCR Q1 Journal*

- This paper proposes Q-MCKT framework, which utilizes an item response theory-based prediction layer to generate interpretable prediction results by simultaneously modeling knowledge acquisition and question difficulty.
</div>
</div>


<!-- ACL 2025 yiyao-->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/LoReKT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
- <span style="background-color:rgba(2,34,141);color:white">ACL 2025</span>
 **Chain-of-Reasoning: Towards Unified Mathematical Reasoning in Large Language Models via a Multi-Paradigm Perspective** \\
Yiyao Yu, Yuxiang Zhang, Dongdong Zhang, Xiao Liang, `Hengyuan Zhang`, et al., Yujiu Yang, Furu Wei\\
[[Paper]](https://arxiv.org/pdf/2501.11110) | *Natural Language Processing, Fine-tuning Technique* | *Conference Preprint*



<!-- NAACL 2025-2 -->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/BPO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
- <span style="background-color:rgba(2,34,141);color:white">NAACL 2025</span>
 **BPO: Towards Balanced Preference Optimization between Knowledge Breadth and Depth in Alignment**\\
Sizhe Wang, Yongqi Tong, `Hengyuan Zhang`, Dawei Li, Xin Zhang, Tianlong Chen \\
[[Paper]](https://arxiv.org/pdf/2411.10914) | *Natural Language Processing, Fine-tuning Technique* | *CCF-B Conference*


<!-- ACL 2025 shiping-->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/LoReKT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
- <span style="background-color:rgba(2,34,141);color:white">Preprint 2025</span>
 **Quantifying the Robustness of Retrieval-Augmented Language Models Against Spurious Features in Grounding Data** \\
Shiping Yang, Jie Wu, Wenbiao Ding, et al., `Hengyuan Zhang`, Dongmei Zhang\\
[[Paper]](https://arxiv.org/pdf/2503.05587) | *Natural Language Processing, Phenomenon Analysis* | *Conference Preprint*


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
- <span style="background-color:rgba(2,34,141);color:white">Preprint 2024</span>
 **Compositional Generalization Through Neuroscience-inspired Geometric Constraints on Representation Structure**\\
Chenming Shang, Shiji Zhou, `Hengyuan Zhang`, Xinchen Zhang, Lei Ke, Yuwang Wang, Yujiu Yang\\
[[Paper]](https://ns7kunkhuh.feishu.cn/file/EI8jb6luDoiDQUxYosVc2q3enGd?from=from_copylink) | *Computer Vision, Cognitive Science, Interpretability in Representation* | *Conference Preprint*

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
- <span style="background-color:rgba(2,34,141);color:white">ACL 2022</span>
 **Multitasking Framework for Unsupervised Simple Definition Generation**\\
Cunliang Kong, Yun Chen, `Hengyuan Zhang`, Liner Yang, Erhong Yang\\
[[Paper]](https://arxiv.org/abs/2203.12926) | [[Code]](https://github.com/blcuicall/SimpDefiner) | *Natural Language Processing, Education, Interpretability in Representation* | *CCF-A Conference*



<!-- NAACL SemEval -->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">NAACL 2022 SemEval</div><img src='images/semeval.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
- <span style="background-color:rgba(2,34,141);color:white">NAACL 2022 SemEval</span>
 **SemEval-2022 Task 1: Cross-Attention Multitasking Framework for Definition Modeling**\\
Cunliang Kong, Yujie Wang, Ruining Chong, Liner Yang, `Hengyuan Zhang`, Erhong Yang\\
[[Paper]](https://arxiv.org/abs/2204.07701) | [[Code]](https://github.com/blcuicall/SemEval2022-Task1-DM) | *Natural Language Processing, Education, Interpretability in Representation* | *CCF-B Conference*




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
<img class="svg" src="/images/baidu.png" width="60pt">Baidu, Search Strategy Lab, Beijing
<br>
- *Mar. 2021 - Jul. 2021*, Engineering Intern

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
<img class="svg" src="/images/sensetime.png" width="85pt">Sensetime, Research, Shenzhen
<br>
- *Aug. 2023 - Mar. 2024*, Research Intern
<!-- <br> -->

<!--MSRA -->
<!-- <img class="svg" src="/images/MSRA.png" width="60pt">Microsoft Research Asia, NLC Group, Beijing
<br>
- *Mar. 2024 - Dec. 2024*, Research Intern, working with [DongDong Zhang](https://scholar.google.com/citations?user=w2qu71oAAAAJ&hl=en) 
  - I got the <span style="color:red">"Microsoft Stars of Tomorrow"</span> Award during the internship -->

<img class="svg" src="/images/MSRA.png" width="60pt">Microsoft Research Asia, NLC Group, Beijing
<br>
- *Mar. 2024 - Dec. 2024*, Research Intern
  - I got the <span style="color:red">"Microsoft Stars of Tomorrow"</span> Award during the internship


<!-- <br> -->




<br>
<span class='anchor' id='-honor'></span>

# 🏅 Selected Honors and Awards
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
- I once led the Academic Department of SIGS Student Union at Tsinghua University. During which, I organized academic activities such as academic forums and experience-sharing sessions. I am also a member of the Beijing Xiamen ECC (北京厦门企业商会), actively participating in sharing activities [[Link]](https://mp.weixin.qq.com/s/DFG97r0-hL12VYFAeshpHA).
- I also participated in social activities such as rural revitalization [[Photo]](images/fuding.jpg), representing Tsinghua in a Swiss "Global Warming" forum [[Photo]](images/swiss.jpg), and helping international students with Chinese, computer, and math [[Photo]](images/tutoring.jpg).
- I am actually a person with a strong desire to share. In my spare time, I like writing blogs and sharing experiences on [Rednote](https://www.xiaohongshu.com/user/profile/5b436cc5f7e8b976f413343f?xsec_token=YBv9botEIHUitz7ZFPPhcIIdqhpMeuw6qak58zvB3MiLc=&xsec_source=app_share&xhsshare=CopyLink&appuid=5b436cc5f7e8b976f413343f&apptime=1746533636&share_id=4cf62cfa0abb409ab33119e85f32af07), [Wechat Official Account](https://mp.weixin.qq.com/mp/profile_ext?action=home&__biz=Mzk0NTI3ODI2OQ==&scene=124#wechat_redirect), and [Bilibili](https://space.bilibili.com/14709944?spm_id_from=333.1007.0.0) (阿源的NLP碎碎念). The selected blogs are as follows:
  - [Interpreting Arithmetic Calculation Modules within LLMs](https://mp.weixin.qq.com/s/D4z8zHmr3cij5_d5rOgLwg)
  - [Interpreting Security Modules within Large Language Model](https://mp.weixin.qq.com/s/3693Q7NPnRoH0r4S0RiEDA?token=889452301&lang=zh_CN)
  - [Do Llama Work in English?](https://mp.weixin.qq.com/s/8EB1q8w9DmIw_M7msK_cgw?token=889452301&lang=zh_CN)
  - [Interpreting Linguistic Regions with in LLMs](https://mp.weixin.qq.com/s/-FHKqUieqJuO3VoTozS4Mw) 
  - [Prevent Catastrophic Forgetting via SoftMask Mechanism](https://mp.weixin.qq.com/s/udjiYzt7cwCdlH1a98ylbA)
  - [The Key Components in Transformer](https://mp.weixin.qq.com/s/hXMEQ7ZPF53-iyOzZRXXZg)
  - [The Evaluation of Instruction Following](https://mp.weixin.qq.com/s/m3RHJ9q-RCkGL33AewdDUg)
  - [Skill Localization of Large Language Model](https://mp.weixin.qq.com/s/x61tHD896Leoz8DO-0weAg)
  - [iMAge-guided Text GeneratIon with CLIP](https://mp.weixin.qq.com/s/fQ6t96aqAgvRDAIjIt9QYA)
- I used to be a guitarist 🎸 in a band when I was in high school. Also, I love playing badminton 🏸, table tennis 🏓 and, soccer ⚽️. During holidays, I will also seize any opportunity to travel around the world  ⛳️.

<div style="display: flex;">
  <img src="images/life1.png" alt="Image 1" width="50%" />
  <img src="images/life3.png" alt="Image 2" width="50%" />
</div>

<br>

<div style="display: flex;">
  <img src="images/life2.png" alt="Image 1" width="50%" />
  <img src="images/life4.png" alt="Image 2" width="50%" />
</div>


<!-- <span class='anchor' id='-posts'></span>

# 📜 Selected Posts -->

