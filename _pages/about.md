---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a second-year Ph.D. student in the School of Computer Science and Technology at Anhui University, under the supervision of Professor Yiwen Zhang. Additionally, I am undertaking a one-year visiting research program at the University of Queensland, under the guidance of Professor Hongzhi Yin, from November 2024 to November 2025. I received my Bachelor's and Master's degrees in Computer Science and Technology from Anhui University in 2020 and 2023, respectively. My research interests primarily focus on graph recommendation systems, social recommendation, and generative recommendation:

1. **Graph Recommendation**: Graph recommender systems leverage graph structures to enhance recommendation quality. Users, items, and other entities are represented as nodes, while their relationships, such as interactions, similarities, or social connections, form edges in the graph. Graph neural networks (such as graph convolutional networks) are widely applied in graph recommendation to obtain high-quality embeddings for users and items.
2. **Social Recommendation**: Social recommendation is an important branch of graph recommender systems. It builds upon interaction relationships by introducing social networks to additionally consider the social connections between users. Social recommender systems leverage the principles of social homophily and social influence to enhance collaborative filtering.
3.  **Generative recommendatio**:Generative recommender system utilizes generative models to produce personalized recommendation. Unlike traditional recommendation methods that rely heavily on user-item interaction data, generative recommendation models aim to learn the underlying data distribution and generate new content or recommendations directly.
   
Main Publications
======
### [1. Exploring the Individuality and Collectivity of Intents behind Interactions for Graph Collaborative Filtering](https://dl.acm.org/doi/abs/10.1145/3626772.3657738)
**Yi Zhang**, Lei Sang, Yiwen Zhang. Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR'24)

### [2. Simplify to the Limit! Embedding-less Graph Collaborative Filtering for Recommender Systems](https://dl.acm.org/doi/abs/10.1145/3701230)
**Yi Zhang**, Yiwen Zhang, Lei Sang, Victor S Sheng. ACM Transactions on Information Systems (TOIS'24)

### [3. Dual Variational Graph Reconstruction Learning for Social Recommendation](https://ieeexplore.ieee.org/abstract/document/10506644)
**Yi Zhang**, Yiwen Zhang, Yuchuan Zhao, Shuiguang Deng, Yun Yang. IEEE Transactions on Knowledge and Data Engineering (TKDE'24)

### [4. NIE-GCN: Neighbor Item Embedding-Aware Graph Convolutional Network for Recommendation](https://ieeexplore.ieee.org/abstract/document/10413999)
**Yi Zhang**, Yiwen Zhang, Dengcheng Yan, Qiang He, Yun Yang. IEEE Transactions on Systems, Man, and Cybernetics: Systems (TSMC'24)

### [5. Revisiting graph-based recommender systems from the perspective of variational auto-encoder](https://dl.acm.org/doi/full/10.1145/3573385)
**Yi Zhang**, Yiwen Zhang, Dengcheng Yan, Shuiguang Deng, Yun Yang. ACM Transactions on Information Systems (TOIS'23)

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
