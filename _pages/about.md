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

I am currently a <u>Research Assistant</u> in Mohamed bin Zayed University of Artificial Intelligence (MBZUAI), supervised by Assistant Professor [Zhiqiang SHEN](https://zhiqiangshen.com/). Before that, I received my M.Eng. degree from [Southeast University](https://cse.seu.edu.cn/) under the supervision of [Prof. Min-Ling Zhang](http://palm.seu.edu.cn/zhangml). I received my B.Eng. degree from [Chongqing University](http://www.cse.cqu.edu.cn/).

My primary research interest lies in the field of **trustworthy weakly supervised learning**,   <a href='https://scholar.google.com/citations?user=_Vx3dZgAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. Currently, I am particularly interested in areas such as partial label learning, dataset condensation, long-tailed learning, knowledge distillation, uncertainty calibration, and model defense. Here is my  <a href ="../certificates/CV.pdf">CV</a>.

<u>Next year (2025 April), I will begin my Ph.D. studies at the University of Tokyo under the supervision of</u> [Masashi Sugiyama](https://scholar.google.co.jp/citations?user=GkYIrlIAAAAJ&hl=en). If you are interested in discussing with me, welcome and feel free to email me at DongDong.Wu@mbzuai.ac.ae or dongdongwu1230@gmail.com, or reach out via WeChat (ID: kaefer1999).

# 🎈 GitHub Repositories

- [[Advances-in-Partial-and-Complementary-Label-Learning]](https://github.com/wu-dd/Advances-in-Partial-and-Complementary-Label-Learning) ![](https://img.shields.io/github/stars/wu-dd/Advances-in-Partial-and-Complementary-Label-Learning)
  - A curated list of most recent papers & codes in Learning with Partial/Complementary Labels.


# 📝 Publications

- [Efficient Model Stealing Defense with Noise Transition Matrix](https://palm.seu.edu.cn/zhangml/files/CVPR'24.pdf). [[Appendix]](https://palm.seu.edu.cn/zhangml/files/Appendix_CVPR'24.pdf) [[Code]](https://github.com/wu-dd/EMMA)
  - **Dong-Dong Wu**, Chilin Fu, Weichang Wu, Wenwen Xia, Xiaolu Zhang, Jun Zhou, Min-Ling Zhang*.
  - *Proceedings of the 35th IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR'24**)*, accepted, 2024.
- [Robust Representation Learning for Unreliable Partial Label Learning.](https://arxiv.org/pdf/2308.16718.pdf)
  - Yu Shi$\dagger$, **Dong-Dong Wu**$\dagger$, Xin Geng\*, Min-Ling Zhang\*
- [Distilling Reliable Knowledge for Instance-dependent Partial Label Learning](https://palm.seu.edu.cn/zhangml/files/AAAI'24d.pdf). [[Appendix]](https://palm.seu.edu.cn/zhangml/files/Appendix_AAAI'24d.pdf) [[Code]](https://github.com/wu-dd/DIRK)
  - **Dong-Dong Wu**, Deng-Bao Wang, Min-Ling Zhang\*.
  - *Proceedings of the 38th AAAI Conference on Artificial Intelligence (**AAAI'24**)*, accepted, 2023.
- [Revisiting consistency regularization for deep partial label learning](http://palm.seu.edu.cn/zhangml/files/ICML'22a.pdf). [[Code]](https://github.com/wu-dd/PLCR)
  - **Dong-Dong Wu**$\dagger$, Deng-Bao Wang$\dagger$, Min-Ling Zhang\*.
  - *Proceedings of the 39th International Conference on Machine Learning (**ICML'22**)*, accepted, 2022.
- [A new classification method based on the negation of a basic probability assignment in the evidence theory](https://www.sciencedirect.com/science/article/abs/pii/S0952197620302864) 
  - **Dongdong Wu**, Zijing Liu, Yongchuan Tang\*.
  - *Engineering Applications of Artificial Intelligence (EAAI)*. 2020, 96: 103985. https://doi.org/10.1016/j.engappai.2020.103985.
- [A new approach for generation of generalized basic probability  assignment in the evidence theory](https://link.springer.com/content/pdf/10.1007/s10044-021-00966-0.pdf).
  - Yongchuan Tang\*, **Dongdong Wu**, Zijing Liu.
  - *Pattern Analysis and Applications (PAA)*.  2021, 24(3): 1007-1023. https://doi.org/10.1007/s10044-021-00966-0.
  - **ESI Highly Cited Paper, top1%**.
- [An improved failure mode and effects analysis method based on uncertainty measure in the evidence theory](https://onlinelibrary.wiley.com/doi/epdf/10.1002/qre.2660)
  - **Dongdong Wu**, Yongchuan Tang*.
  - *Quality and Reliability Engineering International (QRE)*. 2020; 36(5): 1786‐1807. https://doi.org/10.1002/qre.2660.
  - **ESI Highly Cited Paper [<a href ="../certificates/Top Cited Article 2020-2021.pdf">Certificate</a>], top1%.**

# 👨‍💻 Academic Experience

- *2024.09 - now*, Research Assistant, [MBZUAI](https://mbzuai.ac.ae/), UAE. [Advised by [Zhiqiang SHEN](https://zhiqiangshen.com/)]
- *2023.06 - 2023.10*, Machine Intelligence Department, [Ant Group](https://www.antgroup.com/), China. [Collaborated with [Chilin FU](https://dblp.org/pid/245/1803.html), [Xiaolu ZHANG](https://scholar.google.com/citations?user=cAz9PToAAAAJ&hl=en), and [Jun ZHOU](https://scholar.google.com/citations?user=mCVvloEAAAAJ&hl=en)]
- *2020.06 - 2021.09*, [Institute of Automation, Chinese Academy of Science](http://www.ia.cas.cn/), China.

# 🌞 Academic Services

- Reviewer / PC Member: ICML (2022), ECML-PKDD (2023), CVPR (2024, 2025), IJCAI (2024), KDD (2024).
- Teaching Assistant: Machine Learning at Southeast University, spring 2022.

# 👨‍🎓 Educations

- *2021.09 - 2024.06*, Master, Southeast University (87.93/100), Nanjing. 
- *2017.09 - 2021.06*, Undergraduate, Chongqing University (86.88/100), Chongqing.

# 👻 Invited Talk

- "ATEC2023 Competition Review and Sharing", Meituan, 2024

# 🏅 Awards

- (Competition)
- 1st place team (Top 1/1901) in the **ATEC2023 - LLM application and security** [[Report]](https://tech.cnr.cn/techph/20240423/t20240423_526677850.shtml), 2024.
- 7th place@Task 1-1(Image Classification) and 4th place@Task 1-2(Label Noise Detection) in the ***1st Learning and Mining with Noisy Labels (LMNL) challenge of IJCAI-ECAI2022*** [<a href ="../certificates/1st of LMNL challenge.pdf">Certificate</a>], [[Code]](https://github.com/wu-dd/LMNL), 2022.
- First Prize, National CCF Green Computing Contest, 2021.
- Third Prize, National WeChat Mini Program Development Contest, 2020.
- Outstanding Winner (Top 0.1%), International Interdisciplinary Contest in Modeling (ICM), 2019.
- (Honors)
- Outstanding Graduate in Southeast University, 2024.
- Excellent Master Student Model in Southeast University, 2023.
- Excellent Master Student in Southeast University, 2022.
- Outstanding Graduate in Chongqing University, 2021.
- Advanced Individual in Chongqing city, 2021.
- (Scholarship)
- Individual Scholarship (2-time), including Lenovo Research Institute Scholarship (2023), Huawei Scholarship (2024).
- Graduate Academic Scholarship of Southeast University (3-time), 2021-2023.
- Individual Scholarship (4-time), including Huawei Scholarship (2021), Seasky Land Scholarship (2017), Texcel Scholarship (2019), Qianrong Wang Scholarship (2019).
- National Inspirational Scholarship of Chongqing University (3-time), 2017-2020.
- Comprehensive Scholarship of Chongqing University (6-time), 2017-2021.
