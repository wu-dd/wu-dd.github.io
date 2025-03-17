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

- <span class='paper-badge'>SData 2024</span> **Sm-Nd Isotope Data Compilation from Geoscientific Literature Using an Automated Tabular Extraction Method**<br>
  _Zhixin Guo, Tao Wang, Chaoyang Wang, <u><b>Jianping Zhou</b></u>, Guanjie Zheng, Xinbing Wang, Chenghu Zhou_<br>
  _Scientific data_, 2024 (Nature 子刊)<br>
  <span class='paper-asset'><a href="https://arxiv.org/abs/2403.18306">Page</a></span> <span class='paper-asset'><a href="https://arxiv.org/pdf/2403.18306">PDF</a></span> <span class='paper-asset'><a href="https://github.com/sjtugzx/tabularDataCollection">Code</a></span>

- <span class='paper-badge'>ICASSP 2024</span> **Towards Controlled Table-to-Text Generation with Scientific Reasoning**<br>
  _Zhixin Guo, <u><b>Jianping Zhou</b></u>, Jiexing Qi, Mingxuan Yan, Ziwei He, Guanjie Zheng, Zhouhan Lin, Xinbing Wang, Chenghu Zhou_<br>
  _IEEE International Conference on Acoustics, Speech and Signal Processing_, 2024 (CCF-B)<br>
  <span class='paper-asset'><a href="https://arxiv.org/abs/2312.05402">Page</a></span> <span class='paper-asset'><a href="https://arxiv.org/pdf/2312.05402.pdf">PDF</a></span> <span class='paper-asset'><a href="https://github.com/sjtugzx/CTRLSciTab">Code</a></span>

- <span class='paper-badge'>ICPR 2024</span> **SWave: Improving Vocoder Efficiency by Straightening the Waveform Generation Path**<br>
  _Pan Liu, <u><b>Jianping Zhou</b></u>, Xiaohua Tian, Zhouhan Lin_<br>
  _International Conference on Pattern Recognition_, 2024 (交大 A 类)<br>
  <span class='paper-asset'><a href="https://swave-demo.github.io/">Page</a></span> <span class='paper-asset'><a href="https://link.springer.com/chapter/10.1007/978-3-031-78172-8_26">PDF</a></span> <span class='paper-asset'><a href="https://github.com/swave-demo/swave">Code</a></span>

- <span class='paper-badge'>TASLP 2023</span> **Adapting Knowledge for Few-shot Table-to-Text Generation**<br>
  _Zhixin Guo, Minyxuan Yan, Jiexing Qi, <u><b>Jianping Zhou</b></u>, Ziwei He, Guanjie Zheng, Xinbing Wang, Chenghu Zhou_<br>
  _Transactions on Audio, Speech and Language Processing_, 2023 (CCF-B)<br>
  <span class='paper-asset'><a href="https://arxiv.org/abs/2302.12468">Page</a></span> <span class='paper-asset'><a href="https://arxiv.org/pdf/2302.12468.pdf">PDF</a></span> <span class='paper-asset'><a href="https://github.com/sjtugzx/akg">Code</a></span>

- <span class='paper-prebadge'>arXiv 2024</span> **MagiNet: Mask-Aware Graph Imputation Network for Incomplete Traffic Data**<br>
  _<u><b>Jianping Zhou</b></u>, Bin Lu, Zhanyu Liu, Siyu Pan, Xuejun Feng, Hua Wei,
  Guanjie Zheng, Xinbing Wang, Chenghu Zhou_<br>
  _arXiv (preprint)_, 2024<br>
  <span class='paper-asset'><a href="https://arxiv.org/abs/2406.03511">Page</a></span> <span class='paper-asset'><a href="https://arxiv.org/pdf/2406.03511">PDF</a></span>

- <span class='paper-prebadge'>arXiv 2024</span> **GeoViz: A Multi-View Visualization Platform for Spatio-temporal Knowledge Graph**<br>
  _<u><b>Jianping Zhou</b></u>, Junhao Li, Guanjie Zheng, Yunqiang Zhu, Xinbing Wang, Chenghu Zhou_<br>
  _arXiv (preprint)_, 2024<br>
  <span class='paper-asset'><a href="https://arxiv.org/abs/2405.03697">Page</a></span> <span class='paper-asset'><a href="https://arxiv.org/pdf/2405.03697">PDF</a></span> <span class='paper-asset'><a href="https://github.com/JeremyChou28/GeoViz">Code</a></span> <span class='paper-asset'><a href="https://www.youtube.com/watch?v=o31xlMEmcl4">Video</a></span>

- <span class='paper-prebadge'>arXiv 2024</span> **AceMap: Knowledge Discovery through Academic Graph**<br>
  _Xinbing Wang, <u><b>Jianping Zhou</b></u>, et al._<br> _arXiv (preprint)_, 2024<br>
  <span class='paper-asset'><a href="https://www.acemap.info/">Page</a></span> <span class='paper-asset'><a href="https://arxiv.org/pdf/2403.02576">PDF</a></span> <span class='paper-asset'><a href="https://github.com/Acemap">Code</a></span>

# 🚀 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">beta</div><img src='images/geoknowledgefusion.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Knowledge Fusion: An Advanced Platform for Efficient Multimodal Data Integration from Geoscience Literature](https://knowledgefusion.acemap.info/#/index)

- DDE Knowledge Fusion is a one-stop multimodal knowledge fusion system for geoscientific literature, supporting the table extraction and table fusion from geoscience literature, as well as the extraction of knowledge tuples from text to construct knowledge graphs. We have completed the fusion of global Sm-Nd isotope tabular data and the construction of a global knowledge graph of debris flow. This project is supported by [Deep-time Digital Earth (DDE) International Big Science Program](https://deep-time.org/).

- <span class='paper-badge'>Remote Sensing 2024</span> **GeoKnowledgeFusion: A Platform for Multimodal Data Compilation from Geoscience Literature** (SCI Q2)<br>
  <span class='paper-asset'><a href="https://www.mdpi.com/2072-4292/16/9/1484">Page</a></span> <span class='paper-asset'><a href="https://www.mdpi.com/2072-4292/16/9/1484/pdf">PDF</a></span> <span class='paper-asset'><a href="https://github.com/sjtugzx/GeoKnowledgeFusion">Code</a></span>

- <span class='paper-badge'>EGU 2024</span> **Accelerating Geoscience Research: An Advanced Platform for Efficient Multimodal Data Integration from Geoscience Literature** (清华 A 类)<br>
  <span class='paper-asset'><a href="https://meetingorganizer.copernicus.org/EGU24/EGU24-13715.html">Page</a></span> <span class='paper-asset'><a href="https://jeremychou28.github.io/files/EGU2024-poster.pdf">Poster</a></span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/pollutants.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Global Environmental Pollutants Database

- We want to build the global pollutant-centric databases involving pollutant molecular descriptors, mass spectrometry data, toxicity data and behavioral disease data. Based on this database, we want to realize causal reasoning and scientific discovery of emerging pollutants. This project is supported by the Innovative Research Group Program "GeoScience Knowledge Graph" from NSFC.

</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">beta</div><img src='images/geoviz.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Geoviz: Spatio-temporal knowledge graph visualizations platform](https://mdkg.acemap.cn/#/index)

- GeoViz is a one-stop Spatio-temporal knowledge graph (STKG) visualization platform. We developed three customized visualization views for STKG: **knowledge tree**, **knowledge network** and **knowledge map**. This project is supported by the [National key research and development plan](http://www.igsnrr.cas.cn/news/zhxw/202303/t20230303_6688038.html) and [Deep-time Digital Earth (DDE) International Big Science Program](https://deep-time.org/).

</div>
</div> -->

<!-- **Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun -->

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->

# 💻 Internships

- _2020.06 - 2020.09_, Hardware Engineer Intern, [Xilinx](https://xupsh.github.io/camp/), China.
- _2021.09 - 2021.12_, MindSpore Excellent Developer, [Huawei MindSpore](https://www.mindspore.cn/), China. [\[Certificate\]](https://www.mindspore.cn/community/developer)

# 📖 Teaching

- Teaching Assistant, Communication Theory (EST3306), Shanghai Jiao Tong University. (Fall 2023, Fall 2024)

# 📑 Academic Services

- Conference Reviewer: ICLR'25, IJCAI'25
- Journal Reviewer: TKDD'24

# 🎖 Honors and Awards

- _2020.12_, _2021.12_ National Scholarship in China (top 1%)
- _2021.12_ President's Award of Shandong University (top 1%) [\[news\]](https://mp.weixin.qq.com/s/kg9RxqXPaxizK5F9qemySg)
- _2021.12_ Outstanding Student of Shandong Province (top 1%)
- _2020.12_ Outstanding Student Leader of Shandong Province (top 1%)
- _2019.10_ First Prize of the 11th College Student Mathematics Competition
- _2020.12_ First Prize of the 14th International Contest of innovAtionN [\[news\]](https://www.view.sdu.edu.cn/info/1003/144886.htm)

<!-- # 📖 Educations


- _2019.06 - 2022.04 (now)_, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- _2015.09 - 2019.06_, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

<!-- # 💬 Invited Talks

- _2021.06_, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- _2021.03_, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. \| [\[video\]](https://github.com/) -->

# 📫 Contact

Location: Room 441, Building 1, No. 800 Dongchuan Road, Minhang District, Shanghai, China, 200240

Email: jianpingzhou0927@gmail.com

<div>

<a href='https://clustrmaps.com/site/1bxrr'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=ffffff&w=600&t=tt&d=0M8kPkKxBLYWYMx2sN62-gal633opUGy56vm6VlWAz8&co=2d78ad&ct=ffffff'/></a>

</div>
