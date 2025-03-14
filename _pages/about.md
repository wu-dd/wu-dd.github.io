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

I am currently a <u>Research Assistant</u> in MBZUAI, advised by Assistant Professor [Zhiqiang Shen](https://zhiqiangshen.com/). Before that, I received my M.Eng. degree from [Southeast University](https://cse.seu.edu.cn/) under the supervision of [Prof. Min-Ling Zhang](http://palm.seu.edu.cn/zhangml). I received my B.Eng. degree from [Chongqing University](http://www.cse.cqu.edu.cn/).

My primary research focus is on **trustworthy weakly supervised learning** and **data-efficient learning**,   <a href='https://scholar.google.com/citations?user=_Vx3dZgAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. Here's my  <a href ="../certificates/CV.pdf">CV</a>.

<u>In April, I will begin my Ph.D. studies at the University of Tokyo under the supervision of</u> [Masashi Sugiyama](https://scholar.google.co.jp/citations?user=GkYIrlIAAAAJ&hl=en). If you are interested in discussing with me, welcome and feel free to email me at DongDong.Wu@mbzuai.ac.ae or dongdongwu1230@gmail.com, or reach out via WeChat (ID: kaefer1999).

# 🎈 Managed GitHub Repository

- [[Advances-in-Partial-and-Complementary-Label-Learning]](https://github.com/wu-dd/Advances-in-Partial-and-Complementary-Label-Learning) ![](https://img.shields.io/github/stars/wu-dd/Advances-in-Partial-and-Complementary-Label-Learning)
  - A curated list of most recent papers & codes in Learning with Partial/Complementary Labels.


# 📝 Publications
($\*$Equal contribution, $\dagger$Corresponding Author)
- [M-Attack: A Simple Baseline Achieving Over 90% Success Rate Against the Strong Black-box Models of GPT-4.5/4o/o1](https://arxiv.org/abs/2503.10635v1). [[Code]](https://vila-lab.github.io/M-Attack-Website)
  - Zhaoyi Li\*, Xiaohan Zhao\*, **Dong-Dong Wu**, Jiacheng Cui, Zhiqiang Shen$\dagger$
- Unleashing Potential of Mix Augmentation for Partial Label Learning.
  - **Dong-Dong Wu**, Zhaoyi Li, Xiang Li, Zhiqiang Shen$\dagger$.
- Dissimilarity-Driven Contrastive Learning for Robust Hashing in Partial Label Image Retrieval.
  - Zhiqiang Kou\*, Yucheng Xie\*, **Dong-Dong Wu**, Jing Wang, Yuheng Jia, Min-Ling Zhang, Xin Geng$\dagger$.
- [PLENCH: Realistic Evaluation of Deep Partial-Label Learning Algorithms](https://openreview.net/forum?id=FtX6oAW7Dd&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DICLR.cc%2F2025%2FConference%2FAuthors%23your-submissions)). (🌟Spotlight🌟) [[Code]](https://github.com/wwangwitsel/PLENCH)
  - Wei Wang, **Dong-Dong Wu**, Jindong Wang, Gang Niu, Min-Ling Zhang, Masashi Sugiyama$\dagger$.
  - *The 13th International Conference on Learning Representations (**ICLR’25**)*, accepted, 2025.
- [Efficient Model Stealing Defense with Noise Transition Matrix](https://palm.seu.edu.cn/zhangml/files/CVPR'24.pdf). [[Appendix]](https://palm.seu.edu.cn/zhangml/files/Appendix_CVPR'24.pdf) [[Code]](https://github.com/wu-dd/EMMA)
  - **Dong-Dong Wu**, Chilin Fu, Weichang Wu, Wenwen Xia, Xiaolu Zhang, Jun Zhou, Min-Ling Zhang$\dagger$.
  - *Proceedings of the 35th IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR'24**)*, accepted, 2024.
- [Robust Representation Learning for Unreliable Partial Label Learning](https://arxiv.org/pdf/2308.16718.pdf). [[Code]](https://github.com/wu-dd/URRL)
  - Yu Shi\*, **Dong-Dong Wu**\*, Xin Geng$\dagger$, Min-Ling Zhang$\dagger$.
  - *Preprint on arXiv*, 2024.
- [Distilling Reliable Knowledge for Instance-dependent Partial Label Learning](https://palm.seu.edu.cn/zhangml/files/AAAI'24d.pdf). [[Appendix]](https://palm.seu.edu.cn/zhangml/files/Appendix_AAAI'24d.pdf) [[Code]](https://github.com/wu-dd/DIRK)
  - **Dong-Dong Wu**\*, Deng-Bao Wang\*, Min-Ling Zhang$\dagger$.
  - *Proceedings of the 38th AAAI Conference on Artificial Intelligence (**AAAI'24**)*, accepted, 2023.
- [Revisiting consistency regularization for deep partial label learning](http://palm.seu.edu.cn/zhangml/files/ICML'22a.pdf). [[Code]](https://github.com/wu-dd/PLCR)
  - **Dong-Dong Wu**\*, Deng-Bao Wang\*, Min-Ling Zhang$\dagger$.
  - *Proceedings of the 39th International Conference on Machine Learning (**ICML'22**)*, accepted, 2022.
- [A new classification method based on the negation of a basic probability assignment in the evidence theory](https://www.sciencedirect.com/science/article/abs/pii/S0952197620302864) 
  - **Dongdong Wu**, Zijing Liu, Yongchuan Tang$\dagger$.
  - *Engineering Applications of Artificial Intelligence (EAAI)*. 2020, 96: 103985. https://doi.org/10.1016/j.engappai.2020.103985.
- [A new approach for generation of generalized basic probability  assignment in the evidence theory](https://link.springer.com/content/pdf/10.1007/s10044-021-00966-0.pdf).
  - Yongchuan Tang$\dagger$, **Dongdong Wu**, Zijing Liu.
  - *Pattern Analysis and Applications (PAA)*.  2021, 24(3): 1007-1023. https://doi.org/10.1007/s10044-021-00966-0.
  - **ESI Highly Cited Paper, top1%**.
- [An improved failure mode and effects analysis method based on uncertainty measure in the evidence theory](https://onlinelibrary.wiley.com/doi/epdf/10.1002/qre.2660)
  - **Dongdong Wu**, Yongchuan Tang$\dagger$.
  - *Quality and Reliability Engineering International (QRE)*. 2020; 36(5): 1786‐1807. https://doi.org/10.1002/qre.2660.
  - **ESI Highly Cited Paper [<a href ="../certificates/Top Cited Article 2020-2021.pdf">Certificate</a>], top1%.**

# 👨‍💻 Academic Experience

- *2024.09 - 2025.3*, Research Assistant, [MBZUAI](https://mbzuai.ac.ae/), UAE. [Advised by [Zhiqiang Shen](https://zhiqiangshen.com/)]
- *2023.06 - 2023.10*, Research Intern, [Ant Group](https://www.antgroup.com/), China. [Collaborated with [Chilin Fu](https://dblp.org/pid/245/1803.html), [Weichang Wu](https://openreview.net/profile?id=~Weichang_Wu1), [Xiaolu Zhang](https://scholar.google.com/citations?user=cAz9PToAAAAJ&hl=en), and [Jun Zhou](https://scholar.google.com/citations?user=mCVvloEAAAAJ&hl=en)]
- *2020.06 - 2021.09*, Research Intern, [Institute of Automation, Chinese Academy of Science](http://www.ia.cas.cn/), China.

# 👨‍🎓 Academic Educations

- *2021.09 - 2024.06*, Master, Southeast University (87.93/100), Nanjing city, China. 
- *2017.09 - 2021.06*, Undergraduate, Chongqing University (86.88/100), Chongqing city, China.

# 🌞 Academic Services

- Reviewer / PC Member: ICML (2022, 2025), ECML-PKDD (2023), CVPR (2024, 2025), ICCV(2025), IJCAI (2024, 2025), KDD (2024).
- Teaching Assistant: Machine Learning at Southeast University, spring 2022.

# 👻 Invited Talk

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
