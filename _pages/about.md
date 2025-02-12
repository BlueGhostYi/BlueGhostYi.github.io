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

I am currently a second-year Ph.D. student in the School of Computer Science and Technology at Anhui University, under the supervision of Professor Yiwen Zhang. Additionally, I am undertaking a one-year visiting research program at the University of Queensland, under the guidance of Professor Hongzhi Yin, from November 2024 to November 2025. I received my Bachelor's and Master's degrees in Computer Science and Technology from Anhui University in 2020 and 2023, respectively. My research interests primarily focus on graph recommender systems, social recommendation, and generative recommendation:

1. **Graph Recommendation**: Graph recommender systems leverage graph structures to enhance recommendation quality. Users, items, and other entities are represented as nodes, while their relationships, such as interactions, similarities, or social connections, form edges in the graph. Graph neural networks (such as graph convolutional networks) are widely applied in graph recommendation to obtain high-quality embeddings for users and items.
2. **Social Recommendation**: Social recommendation is an important branch of graph recommender systems. It builds upon interaction relationships by introducing social networks to additionally consider the social connections between users. Social recommender systems leverage the principles of social homophily and social influence to enhance collaborative filtering.
3.  **Generative recommendation**: Generative recommender system utilizes generative models to produce personalized recommendation. Unlike traditional recommendation methods that rely heavily on user-item interaction data, generative recommendation models aim to learn the underlying data distribution and generate new content or recommendations directly.


# 🔥 News
- *2025.01*: &nbsp;🎉🎉 One paper is accepted by ACM the Web conference 2025 (WWW'25) on data augmentation for recommendation.
- *2024.12*: &nbsp;🎉🎉 We have integrated a graph recommendation framework, [**ID-GRec**](https://github.com/BlueGhostYi/ID-GRec), which has now been released on GitHub. ID-GRec is built on the classic graph recommendation method LightGCN and draws on several related frameworks. Currently, ID-GRec includes over 20 graph recommendation models, all of which have been published in various flagship conferences and journals (e.g., SIGIR, WWW, KDD, TOIS, and TKDE).

# 📝 Main Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2025</div><img src='images/MixRec.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MixRec: Individual and Collective Mixing Empowers Data Augmentation for Recommender Systems](https://arxiv.org/abs/2501.13579)

**Yi Zhang**, Yiwen Zhang. 
Proceedings of the ACM Web Conference 2025 (**WWW'25, CCF A**) [[Code](https://github.com/BlueGhostYi/ID-GRec/)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGIR 2024</div><img src='images/BIGCF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring the Individuality and Collectivity of Intents behind Interactions for Graph Collaborative Filtering](https://dl.acm.org/doi/abs/10.1145/3626772.3657738)

**Yi Zhang**, Lei Sang, Yiwen Zhang.
Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval (**SIGIR'24, CCF A**) [[Code](https://github.com/BlueGhostYi/BIGCF)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TOIS 2024</div><img src='images/EGCF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Simplify to the Limit! Embedding-less Graph Collaborative Filtering for Recommender Systems](https://dl.acm.org/doi/abs/10.1145/3701230)

**Yi Zhang**, Yiwen Zhang, Lei Sang, Victor S Sheng.
ACM Transactions on Information Systems (**TOIS'24, CCF A**) [[Code](https://github.com/BlueGhostYi/ID-GRec/blob/main/models/EGCF.py)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TKDE 2024</div><img src='images/DVGRL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dual Variational Graph Reconstruction Learning for Social Recommendation](https://ieeexplore.ieee.org/abstract/document/10506644)

**Yi Zhang**, Yiwen Zhang, Yuchuan Zhao, Shuiguang Deng, Yun Yang. 
IEEE Transactions on Knowledge and Data Engineering (**TKDE'24, CCF A**) [[Code](https://github.com/BlueGhostYi/DVGRL)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TSMC 2024</div><img src='images/NIE-GCN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[NIE-GCN: Neighbor Item Embedding-Aware Graph Convolutional Network for Recommendation](https://ieeexplore.ieee.org/abstract/document/10413999)

**Yi Zhang**, Yiwen Zhang, Yuchuan Zhao, Shuiguang Deng, Yun Yang. 
**Yi Zhang**, Yiwen Zhang, Dengcheng Yan, Qiang He, Yun Yang. 
IEEE Transactions on Systems, Man, and Cybernetics: Systems (**TSMC'24, CCF B**) [[Code](https://github.com/BlueGhostYi/NIE-GCN)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TOIS 2023</div><img src='images/CVGA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Revisiting graph-based recommender systems from the perspective of variational auto-encoder](https://dl.acm.org/doi/full/10.1145/3573385)

**Yi Zhang**, Yiwen Zhang, Yuchuan Zhao, Shuiguang Deng, Yun Yang. 
**Yi Zhang**, Yiwen Zhang, Dengcheng Yan, Shuiguang Deng, Yun Yang. 
ACM Transactions on Information Systems (**TOIS'23, CCF A**) [[Code](https://github.com/BlueGhostYi/ID-GRec/blob/main/models/CVGA.py)]
</div>
</div>

# 📝 Other Publications 

- [1. Intent-guided Heterogeneous Graph Contrastive Learning for Recommendation](https://arxiv.org/pdf/2407.17234)
Lei Sang, Yu Wang, **Yi Zhang**, Yiwen Zhang, Xindong Wu. IEEE Transactions on Knowledge and Data Engineering (TKDE'25) **TKDE 2025**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
