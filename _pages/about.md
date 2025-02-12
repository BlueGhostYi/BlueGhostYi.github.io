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

I am currently a second-year Ph.D. student in the School of Computer Science and Technology at Anhui University, under the supervision of Professor Yiwen Zhang. Additionally, I am undertaking a one-year visiting research program at the University of Queensland, under the guidance of Professor Hongzhi Yin, from November 2024 to November 2025. I received my Bachelor's and Master's degrees in Computer Science and Technology from Anhui University in 2020 and 2023, respectively. I have been invited to serve as reviewer for IEEE TKDE, IEEE TSMC, IEEE TII, ACM TOIS, ACM TKDD, and Neural Network journals. My research interests primarily focus on graph recommender systems, social recommendation, and generative recommendation:

1. **Graph Recommendation**: Graph recommender systems leverage graph structures to enhance recommendation quality. Users, items, and other entities are represented as nodes, while their relationships, such as interactions, similarities, or social connections, form edges in the graph. Graph neural networks (such as graph convolutional networks) are widely applied in graph recommendation to obtain high-quality embeddings for users and items.
2. **Social Recommendation**: Social recommendation is an important branch of graph recommender systems. It builds upon interaction relationships by introducing social networks to additionally consider the social connections between users. Social recommender systems leverage the principles of social homophily and social influence to enhance collaborative filtering.
3.  **Generative recommendation**: Generative recommender system utilizes generative models to produce personalized recommendation. Unlike traditional recommendation methods that rely heavily on user-item interaction data, generative recommendation models aim to learn the underlying data distribution and generate new content or recommendations directly.


# 🔥 News
- *2025.01*: &nbsp;🎉🎉 One paper is accepted by ACM the Web conference 2025 (WWW'25) on data augmentation for recommendation.
- *2024.12*: &nbsp;🎉🎉 We have integrated a graph recommendation framework, [**ID-GRec**](https://github.com/BlueGhostYi/ID-GRec), which has now been released on GitHub. ID-GRec is built on the classic graph recommendation method LightGCN and draws on several related frameworks. Currently, ID-GRec includes over 20 graph recommendation models, all of which have been published in various flagship conferences and journals (e.g., SIGIR, WWW, KDD, TOIS, and TKDE).

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2025</div><img src='images/MixRec.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**MixRec: Individual and Collective Mixing Empowers Data Augmentation for Recommender Systems**](https://arxiv.org/abs/2501.13579)

**Yi Zhang**, Yiwen Zhang. 
Proceedings of the ACM Web Conference 2025 (**WWW'25, CCF A**) [[Code](https://github.com/BlueGhostYi/ID-GRec/)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGIR 2024</div><img src='images/BIGCF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Exploring the Individuality and Collectivity of Intents behind Interactions for Graph Collaborative Filtering**](https://dl.acm.org/doi/abs/10.1145/3626772.3657738)

**Yi Zhang**, Lei Sang, Yiwen Zhang.
Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval (**SIGIR'24, CCF A**) [[Code](https://github.com/BlueGhostYi/BIGCF)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TOIS 2024</div><img src='images/EGCF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Simplify to the Limit! Embedding-less Graph Collaborative Filtering for Recommender Systems**](https://dl.acm.org/doi/abs/10.1145/3701230)

**Yi Zhang**, Yiwen Zhang, Lei Sang, Victor S Sheng.
ACM Transactions on Information Systems (**TOIS'24, CCF A**) [[Code](https://github.com/BlueGhostYi/ID-GRec/blob/main/models/EGCF.py)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TKDE 2024</div><img src='images/DVGRL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Dual Variational Graph Reconstruction Learning for Social Recommendation**](https://ieeexplore.ieee.org/abstract/document/10506644)

**Yi Zhang**, Yiwen Zhang, Yuchuan Zhao, Shuiguang Deng, Yun Yang. 
IEEE Transactions on Knowledge and Data Engineering (**TKDE'24, CCF A**) [[Code](https://github.com/BlueGhostYi/DVGRL)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TSMC 2024</div><img src='images/NIE-GCN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**NIE-GCN: Neighbor Item Embedding-Aware Graph Convolutional Network for Recommendation**](https://ieeexplore.ieee.org/abstract/document/10413999)
 
**Yi Zhang**, Yiwen Zhang, Dengcheng Yan, Qiang He, Yun Yang. 
IEEE Transactions on Systems, Man, and Cybernetics: Systems (**TSMC'24, CCF B**) [[Code](https://github.com/BlueGhostYi/NIE-GCN)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TOIS 2023</div><img src='images/CVGA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Revisiting graph-based recommender systems from the perspective of variational auto-encoder**](https://dl.acm.org/doi/full/10.1145/3573385)

**Yi Zhang**, Yiwen Zhang, Dengcheng Yan, Shuiguang Deng, Yun Yang. 
ACM Transactions on Information Systems (**TOIS'23, CCF A**) [[Code](https://github.com/BlueGhostYi/ID-GRec/blob/main/models/CVGA.py)]
</div>
</div>

# 📝 Other Publications 

1. [**Intent-guided Heterogeneous Graph Contrastive Learning for Recommendation**](https://arxiv.org/pdf/2407.17234).
Lei Sang, Yu Wang, **Yi Zhang**, Yiwen Zhang, Xindong Wu. IEEE Transactions on Knowledge and Data Engineering (TKDE'25) **TKDE 2025**

1. [**Federated Contrastive Learning for Cross-Domain Recommendation**](https://ieeexplore.ieee.org/document/10842506).
Qingren Wang, Yuchuan Zhao, **Yi Zhang**, Yiwen Zhang, Shuiguang Deng, Yun Yang. IEEE Transactions on Services Computing (TSC'25)

1. [**Dual-domain Collaborative Denoising for Social Recommendation**](https://arxiv.org/pdf/2405.04942).
Wenjie Chen, **Yi Zhang**, Honghao Li, Lei Sang, Yiwen Zhang. IEEE Transactions on Computational Social Systems (TCSS'25)

1. [**Revisiting Alignment and Uniformity for Recommendation via Discrimination and Reliable Assessment**](https://ieeexplore.ieee.org/abstract/document/10833758).
Xinzhe Jiang, Lei Sang, Shun Lian, **Yi Zhang**, Yiwen Zhang. IEEE Transactions on Consumer Electronics (TCE'25)

1. [**SimCEN: Simple Contrast-enhanced Network for CTR Prediction**](https://dl.acm.org/doi/abs/10.1145/3664647.3681203).
Honghao Li, Lei Sang, **Yi Zhang**, Yiwen Zhang. Proceedings of the 32nd ACM International Conference on Multimedia (ACM MM'24)

1. [**AdaGIN: Adaptive Graph Interaction Network for Click-Through Rate Prediction**](https://dl.acm.org/doi/full/10.1145/3681785).
Lei Sang, Honghao Li, Yiwen Zhang, **Yi Zhang**, Yun Yang. ACM Transactions on Information Systems (TOIS'24)

1. [**Towards Similar Alignment and Unique Uniformity in Collaborative Filtering**](https://www.sciencedirect.com/science/article/pii/S0957417424022139).
Lei Sang, Yu Zhang, **Yi Zhang**, Honghao Li, Yiwen Zhang. Expert Systems with Applications (ESWA'24)

1. [**Bi-Directional Transfer Graph Contrastive Learning for Social Recommendation**](https://www.sciencedirect.com/science/article/pii/S0957417424022139).
Lei Sang, Mingyuan Liu, **Yi Zhang**, Yuee Huang, Yiwen Zhang. IEEE Transactions on Big Data (TBD'24)

1. [**CETN: Contrast-enhanced Through Network for Click-Through Rate Prediction**](https://dl.acm.org/doi/10.1145/3688571).
Honghao Li, Lei Sang, **Yi Zhang**, Xuyun Zhang, Yiwen Zhang. ACM Transactions on Information Systems (TOIS'24)

1. [**Multi-view Denoising Contrastive Learning for Bundle Recommendation**](https://link.springer.com/article/10.1007/s10489-024-05825-z).
Lei Sang, Yang Hu, **Yi Zhang**, Yiwen Zhang. Applied Intelligence, 2024.

# 🎖 Honors and Awards

🏆China National Scholarship (Ranked 1st in the School of Computer Science and Technology, Anhui University, 2024)

🏆First-Class Academic Scholarship (Awarded consecutively from 2020 to 2024, Anhui University)

🏆Outstanding Graduate of Higher Education Institutions in Anhui Province, China (Anhui Provincial Department of Education, 2023)

🏆National Second Prize in the CCF China Software Service Innovation Contest (China Computer Federation, 2022)

#
<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=300&t=m&d=34taVYypIaftBuBTVtFkhL1Jql8xXlrWROpcbKDStLA'></script>
