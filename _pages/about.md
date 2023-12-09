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

Dong-Dong Wu (吴东冬) is currently a third-year master student in [School of computer science and engineering at Southeast University](https://cse.seu.edu.cn/). He is a member of [Pattern Learning and Mining Lab (PALM)](http://palm.seu.edu.cn/) supervised by [Prof. Min-Ling Zhang](http://palm.seu.edu.cn/zhangml/). Dong-Dong Wu received his B.Eng. degree in [School of Big Data & Software Engineering at Chongqing University](http://www.cse.cqu.edu.cn/) in Jun 2021. In the same year, he was admitted to study for an M.Eng. degree in Southeast University without entrance examination.

My primary research interest lies in the field of **trustworthy weakly supervised learning**,   <a href='https://scholar.google.com/citations?user=_Vx3dZgAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. Specially now I am focusing on partial label learning, dataset condensation, long-tailed learning, knowledge distillation, and uncertainty calibration, model defense. Here is my  <a href ="../certificates/CV.pdf">CV</a>.

If you are interested in discussing with me, feel free to drop me an email (dongdongwu@seu.edu.cn, dongdongwu1230@gmail.com) or add my wechat (kaefer1999).

# 🎈 Github

- [[Advances-in-Partial-and-Complementary-Label-Learning]](https://github.com/wu-dd/Advances-in-Partial-and-Complementary-Label-Learning)
  - A curated list of most recent papers & codes in Learning with Partial/Complementary Labels.


# 📝 Publications

- Efficient Model Stealing Defense with Noise Transition Matrix
  - **Dong-Dong Wu**, Chi-Lin Fu, Wei-Chang Wu, Wen-Wen Xia, Xiao-Lu Zhang, Jun Zhou, Min-Ling Zhang*.
- [Robust Representation Learning for Unreliable Partial Label Learning.](https://arxiv.org/pdf/2308.16718.pdf)
  - Yu Shi$\dagger$, **Dong-Dong Wu**$\dagger$, Xin Geng\*, Min-Ling Zhang\*
- Distilling Reliable Knowledge for Instance-dependent Partial Label Learning
  - **Dong-Dong Wu**, Deng-Bao Wang, Min-Ling Zhang\*.
  - *Proceedings of the 38th AAAI Conference on Artificial Intelligence (**AAAI'24**)*, accepted, 2023.
- [Revisiting consistency regularization for deep partial label learning](http://palm.seu.edu.cn/zhangml/files/ICML'22a.pdf). [[Code]](http://palm.seu.edu.cn/zhangml/Resources.htm#icml22a)
  - **Dong-Dong Wu**$\dagger$, Deng-Bao Wang$\dagger$, Min-Ling Zhang\*.
  - *Proceedings of the 39th International Conference on Machine Learning (**ICML'22**)*, accepted, 2022.
- [A new classification method based on the negation of a basic probability assignment in the evidence theory](https://www.sciencedirect.com/science/article/abs/pii/S0952197620302864) 
  - **Dongdong Wu**, Zijing Liu, Yongchuan Tang\*.
  - *Engineering Applications of Artificial Intelligence*. 2020, 96: 103985. https://doi.org/10.1016/j.engappai.2020.103985.
- [A new approach for generation of generalized basic probability  assignment in the evidence theory](https://link.springer.com/content/pdf/10.1007/s10044-021-00966-0.pdf).
  - Yongchuan Tang\*, **Dongdong Wu**, Zijing Liu.
  - *Pattern Analysis and Applications*.  2021, 24(3): 1007-1023. https://doi.org/10.1007/s10044-021-00966-0.
  - **ESI Highly Cited Paper, top1%**.
- [An improved failure mode and effects analysis method based on uncertainty measure in the evidence theory](https://onlinelibrary.wiley.com/doi/epdf/10.1002/qre.2660)
  - **Dongdong Wu**, Yongchuan Tang*.
  - *Quality and Reliability Engineering International*. 2020; 36(5): 1786‐1807. https://doi.org/10.1002/qre.2660.
  - **ESI Highly Cited Paper [<a href ="../certificates/Top Cited Article 2020-2021.pdf">Certificate</a>], top1%.**

# 👨‍💻 Internships

- *2023.06 - 2023.10*, Machine Intelligence Department, [Ant Group](https://www.antgroup.com/), China.
- *2020.06 - 2021.09*, [Institute of Automation, Chinese Academy of Science](http://www.ia.cas.cn/), China, [<a href ="../certificates/Institute of Automation-Admission.pdf">Admission</a>] [<a href ="../certificates/Institute of Automation-Proof.pdf">Certificate</a>].	

# 🌞 Professional Services

- Reviewer / PC Member: ICML (2022), ECML-PKDD (2023), CVPR (2024).
- Teaching Assistant: Machine Learning at Southeast University, spring 2022.

# 🏅 Honors and Awards

-  Outstanding Graduate Student Model in Southeast University, 2023.
-  Lenovo Research Institute Scholarship, 2023.
-  Outstanding Graduate Student in Southeast University, 2022.
- 7th place@Task 1-1(Image Classification) and 4th place@Task 1-2(Label Noise Detection) in the ***1st Learning and Mining with Noisy Labels (LMNL) challenge of IJCAI-ECAI2022*** [<a href ="../certificates/1st of LMNL challenge.pdf">Certificate</a>], [[Code]](https://github.com/wu-dd/LMNL), 2022.
-  Graduate Academic Scholarship of Southeast University (2-time), 2021-2022.
- Advanced Individual in Chongqing city, 2021.
- Outstanding Graduates in Chongqing University, 2020.
- First Prize (top 3%), National CCF Green Computing Contest, 2021.
- Third Prize  (top 5%), National WeChat Mini Program Development Contest, 2020.
- Outstanding Winner (top 0.1%), International Interdisciplinary Contest in Modeling (ICM), 2019.
- Individual Scholarship (4-time), including Huawei Scholarship, Seasky Land Scholarship, Texcel Scholarship, Qianrong Wang Scholarship).
- National Inspirational Scholarship of Chongqing University (3-time).
- Comprehensive Scholarship of Chongqing University (6-time).

# 👨‍🎓Educations

- *2021.09 - 2024.06 (now)*, Master, Southeast University (87.93/100), Nanjing. 
- *2017.09 - 2021.06*, Undergraduate, Chongqing University (86.88/100), Chongqing.
