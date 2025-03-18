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

I am currently a <u>Research Assistant</u> in MBZUAI, advised by Assistant Professor <a href="https://zhiqiangshen.com/" style="text-decoration: none;">Zhiqiang Shen</a>. Before that, I received my M.Eng. degree from <a href="https://cse.seu.edu.cn/" style="text-decoration: none;">Southeast University</a> under the supervision of Prof. <a href="http://palm.seu.edu.cn/zhangml" style="text-decoration: none;">Min-Ling Zhang</a>. I received my B.Eng. degree from <a href="http://www.cse.cqu.edu.cn/" style="text-decoration: none;">Chongqing University</a>.

My primary research focus is on **trustworthy weakly supervised learning** and **data-efficient learning**,   <a href='https://scholar.google.com/citations?user=_Vx3dZgAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. Here's my  <a href ="../certificates/CV.pdf" style="text-decoration: none;">CV</a>.

<u>In April, I will begin my Ph.D. studies at the University of Tokyo under the supervision of Prof. <a href="https://scholar.google.co.jp/citations?user=GkYIrlIAAAAJ&hl=en" style="text-decoration: none;">Masashi Sugiyama</a></u>. If you are interested in discussing with me, welcome and feel free to email me at dongdongwu1230@gmail.com, or reach out via WeChat (ID: kaefer1999).


# 📝 Publications
($\*$Equal contribution, $\dagger$Corresponding Author)
- <span class='paper-prebadge'>Submitted</span> **M-Attack: A Simple Baseline Achieving Over 90% Success Rate Against the Strong Black-box Models of GPT-4.5/4o/o1**<br>*Zhaoyi Li\*, Xiaohan Zhao\*, <u>Dong-Dong Wu</u>, Jiacheng Cui, Zhiqiang Shen$\dagger$*<br><span class='paper-asset'><a href="https://arxiv.org/pdf/2503.10635v1">PDF</a></span> <span class='paper-asset'><a href="https://github.com/VILA-Lab/M-Attack">Code</a></span> <span class='paper-asset'><a href="https://vila-lab.github.io/M-Attack-Website/">Website</a></span>
- <span class='paper-prebadge'>Submitted</span> **Unleashing Potential of Mix Augmentation for Partial Label Learning**<br>*<u>Dong-Dong Wu</u>, Zhaoyi Li, Xiang Li, Zhiqiang Shen$\dagger$*<br>
- <span class='paper-prebadge'>Submitted</span> **Dissimilarity-Driven Contrastive Learning for Robust Hashing in Partial Label Image Retrieval**<br>*Zhiqiang Kou\*, Yucheng Xie\*, <u>Dong-Dong Wu</u>, Jing Wang, Yuheng Jia, Min-Ling Zhang, Xin Geng$\dagger$*
- <span class='paper-badge'>ICLR 2025</span> **PLENCH: Realistic Evaluation of Deep Partial-Label Learning Algorithms**<br>*Wei Wang, <u>Dong-Dong Wu</u>, Jindong Wang, Gang Niu, Min-Ling Zhang, Masashi Sugiyama$\dagger$*<br>*Proceedings of the 13th International Conference on Learning Representations (ICLR), 2025*<br><span class='paper-asset'><a href="https://arxiv.org/pdf/2502.10184">PDF</a></span> <span class='paper-asset'><a href="https://github.com/wwangwitsel/PLENCH">Code</a></span> <span class='paper-highlight'>Spotlight</span> 
- <span class='paper-badge'>CVPR 2024</span> **Efficient Model Stealing Defense with Noise Transition Matrix**<br>*<u>Dong-Dong Wu</u>, Chilin Fu, Weichang Wu, Wenwen Xia, Xiaolu Zhang, Jun Zhou, Min-Ling Zhang$\dagger$*<br>*Proceedings of the 35th IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024*<br><span class='paper-asset'><a href="https://palm.seu.edu.cn/zhangml/files/CVPR'24.pdf">PDF</a></span> <span class='paper-asset'><a href="https://github.com/wu-dd/EMMA">Code</a></span> <span class='paper-asset'><a href="https://palm.seu.edu.cn/zhangml/files/Appendix_CVPR'24.pdf">Appendix</a></span>
- <span class='paper-badge'>arXiv 2024</span> **Robust Representation Learning for Unreliable Partial Label Learning**<br>*Yu Shi\*, <u>Dong-Dong Wu</u>\*, Xin Geng$\dagger$, Min-Ling Zhang$\dagger$*<br><span class='paper-asset'><a href="https://arxiv.org/pdf/2308.16718.pdf">PDF</a></span> <span class='paper-asset'><a href="https://github.com/wu-dd/URRL">Code</a></span>
- <span class='paper-badge'>AAAI 2024</span> **Distilling Reliable Knowledge for Instance-dependent Partial Label Learning**<br>*<u>Dong-Dong Wu</u>\*, Deng-Bao Wang\*, Min-Ling Zhang$\dagger$*<br>*Proceedings of the 38th AAAI Conference on Artificial Intelligence (AAAI), 2023*<br><span class='paper-asset'><a href="https://palm.seu.edu.cn/zhangml/files/AAAI'24d.pdf">PDF</a></span> <span class='paper-asset'><a href="https://github.com/wu-dd/DIRK">Code</a></span> <span class='paper-asset'><a href="https://palm.seu.edu.cn/zhangml/files/Appendix_AAAI'24d.pdf">Appendix</a></span>
- <span class='paper-badge'>ICML 2022</span> **Revisiting consistency regularization for deep partial label learning**<br>*<u>Dong-Dong Wu</u>\*, Deng-Bao Wang\*, Min-Ling Zhang$\dagger$*<br>*Proceedings of the 39th International Conference on Machine Learning (ICML)*, 2022<br><span class='paper-asset'><a href="http://palm.seu.edu.cn/zhangml/files/ICML'22a.pdf">PDF</a></span> <span class='paper-asset'><a href="https://github.com/wu-dd/PLCR">Code</a></span>
- <span class='paper-badge'>EAAI</span> **A new classification method based on the negation of a basic probability assignment in the evidence theory**<br>*<u>Dongdong Wu</u>, Zijing Liu, Yongchuan Tang$\dagger$*<br>*Engineering Applications of Artificial Intelligence (EAAI). 2020, 96: 103985. https://doi.org/10.1016/j.engappai.2020.103985*<br><span class='paper-asset'><a href="https://www.sciencedirect.com/science/article/abs/pii/S0952197620302864">PDF</a></span>
- <span class='paper-badge'>PAA</span>  **A new approach for generation of generalized basic probability  assignment in the evidence theory**<br>*Yongchuan Tang$\dagger$, <u>Dongdong Wu</u>, Zijing Liu*<br>*Pattern Analysis and Applications (PAA).  2021, 24(3): 1007-1023. https://doi.org/10.1007/s10044-021-00966-0*<br><span class='paper-asset'><a href="https://link.springer.com/content/pdf/10.1007/s10044-021-00966-0.pdf">PDF</a></span> <span class='paper-highlight'>ESI Highly Cited Paper (top1%)</span>
- <span class='paper-badge'>QRE</span> **An improved failure mode and effects analysis method based on uncertainty measure in the evidence theory**<br>*<u>Dongdong Wu</u>, Yongchuan Tang$\dagger$*<br>*Quality and Reliability Engineering International (QRE). 2020; 36(5): 1786‐1807. https://doi.org/10.1002/qre.2660*<br><span class='paper-asset'><a href="https://onlinelibrary.wiley.com/doi/epdf/10.1002/qre.2660">PDF</a></span> <span class='paper-asset'><a href="../certificates/Top Cited Article 2020-2021.pdf">Certificate</a></span> <span class='paper-highlight'>ESI Highly Cited Paper (top1%)</span>

# 🎈 Maintained GitHub Repositories

- <a href="https://github.com/wu-dd/Advances-in-Partial-and-Complementary-Label-Learning" style="text-decoration: none;">[Advances-in-Partial-and-Complementary-Label-Learning]</a> ![](https://img.shields.io/github/stars/wu-dd/Advances-in-Partial-and-Complementary-Label-Learning)
  - A curated list of most recent papers & codes in Learning with Partial/Complementary Labels.

# 👨‍💻 Academic Experience

- *2024.09 - 2025.3*, Research Assistant, <a href="https://mbzuai.ac.ae/" style="text-decoration: none;">MBZUAI</a>, UAE. [Advised by <a href="https://zhiqiangshen.com/" style="text-decoration: none;">Zhiqiang Shen</a>]
- *2023.06 - 2023.10*, Research Intern, <a href="https://www.antgroup.com/" style="text-decoration: none;">Ant Group</a>, China. [Collaborated with <a href="https://dblp.org/pid/245/1803.html" style="text-decoration: none;">Chilin Fu</a>, <a href="https://openreview.net/profile?id=~Weichang_Wu1" style="text-decoration: none;">Weichang Wu</a>, <a href="https://scholar.google.com/citations?user=cAz9PToAAAAJ&hl=en" style="text-decoration: none;">Xiaolu Zhang</a>, and <a href="https://scholar.google.com/citations?user=mCVvloEAAAAJ&hl=en" style="text-decoration: none;">Jun Zhou</a>]

- *2020.06 - 2021.09*, Research Intern, <a href="http://www.ia.cas.cn/" style="text-decoration: none;">Institute of Automation, Chinese Academy of Science</a>, China.

# 🌞 Academic Services

- Reviewer / PC Member: ICML (2022, 2025), ECML-PKDD (2023), CVPR (2024, 2025), ICCV(2025), IJCAI (2024, 2025), KDD (2024).
- Teaching Assistant: Machine Learning at Southeast University, spring 2022.

# 👻 Invited Talks

- "ATEC2023 Competition Review and Sharing", Meituan, 2024

# 🏅 Awards

- Competition
  - Team Champion (Rank 1/1901), **ATEC2023** - LLM Application and Security, 2024. [[Report]](https://tech.cnr.cn/techph/20240423/t20240423_526677850.shtml)
  - Rank 6, **ATEC2023** - AI-Generated News Detection Track, 2024.
  - Rank 6, **CCF BDCI** - Conversational RAG Track, 2024. [[Code]](https://github.com/wu-dd/BDCI-Solution) 
  - Rank 7, ***1st Learning and Mining with Noisy Labels (LMNL) Challenge of IJCAI-ECAI2022*** - Image Classification Task, 2022. [<a href="../certificates/1st of LMNL challenge.pdf">Certificate</a>], [[Code]](https://github.com/wu-dd/LMNL)
  - Rank 4, ***1st Learning and Mining with Noisy Labels (LMNL) Challenge of IJCAI-ECAI2022*** - Label Noise Detection Task, 2022.
  - First Prize, National CCF Green Computing Contest, 2021.
  - Third Prize, National WeChat Mini Program Development Contest, 2020.
  - Outstanding Winner (Top 1%), International Interdisciplinary Contest in Modeling (ICM), 2019. [[Report]](https://wmxy.cqu.edu.cn/info/1016/1173.htm)
- Honors
  - Outstanding Graduate in Southeast University, 2024.
  - Excellent Master Student Model in Southeast University, 2023.
  - Outstanding Undergraduate in Chongqing University, 2021.
  - Advanced Undergraduate in Chongqing city, 2021.
- Scholarship
  - Huawei Scholarship (2024), Lenovo Research Institute Scholarship (2023), Huawei Scholarship (2021)
