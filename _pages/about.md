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

I am a Ph.D. student in School of Intelligence Science and Technology at Peking University (PKU), advised by [Prof. Yitao Liang](https://web.cs.ucla.edu/~yliang/). 
Before joining PKU, I received my MSc and BA degrees in Control Science and Technology from Beijing Institute of Technology.
I work on building open-ended embodied agents with multi-task skills, including visual localization, task planning and decision making.  
In particular, I am interested in leveraging large pre-trained *Foundation Models* to improve generalization of agent capabilities.


# 🔥 News
- Sep 2023: &nbsp;🎉🎉 Our paper [Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents](https://arxiv.org/pdf/2302.01560.pdf) is accepted by Neural Information Processing Systems (NeurIPS) 2023.
- Jul 2023: &nbsp;🎉🎉 Our paper [Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents](https://arxiv.org/pdf/2302.01560.pdf) received Best Paper Award at ICML 2023 TEACH Workshop! 
- Feb 2023: &nbsp;🎉🎉 Two papers are accepted by CVPR 2023. 

# 📝 Publications 

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">arXiv</div><img src='images/papers/2310.08235.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[<font size="5">GROOT: Learning to Follow Instructions by Watching Gameplay Videos</font>](https://craftjarvis-groot.github.io/)

[Shaofei Cai](https://phython96.github.io/), Bowei Zhang, **Zihao Wang**, [Xiaojian Ma](https://web.cs.ucla.edu/~xm/), [Anji Liu](https://web.cs.ucla.edu/~yliang/), [Yitao Liang](https://web.cs.ucla.edu/~yliang/)
  
**arXiv** \| [Project](https://craftjarvis-groot.github.io/) \| [Paper](https://arxiv.org/pdf/2310.08235.pdf) \| [Code](https://github.com/CraftJarvis/GROOT) 

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">arXiv</div><img src='images/papers/2310.08367.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[MCU: A Task-centric Framework for Open-ended Agent Evaluation in Minecraft](https://arxiv.org/pdf/2310.08367.pdf)

[Haowei Lin](https://linhaowei1.github.io/), **Zihao Wang**, [Jianzhu Ma](https://majianzhu.com/), [Yitao Liang](https://web.cs.ucla.edu/~yliang/)
  
**arXiv** \| [Paper](https://arxiv.org/pdf/2310.08367.pdf) \| [Code](https://github.com/CraftJarvis/MCU) 

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">arXiv</div><img src='images/papers/2308.11339.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[ProAgent: Building Proactive Cooperative AI with Large Language Models](https://arxiv.org/pdf/2308.11339.pdf)

Ceyao Zhang, Kaijie Yang, Siyi Hu, **Zihao Wang**, Guanghe Li, Yihang Sun, Cheng Zhang, Zhaowei Zhang, Anji Liu, Song-Chun Zhu, Xiaojun Chang, Junge Zhang, Feng Yin, Yitao Liang, Yaodong Yang
  
**arXiv** \| [Project](https://pku-proagent.github.io/) \| [Paper](https://arxiv.org/pdf/2308.11339.pdf) \| [Code](https://github.com/PKU-Alignment/ProAgent) 

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">NeurIPS 2023</div><img src='images/papers/2302.01560.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents](https://arxiv.org/pdf/2302.01560.pdf)

<font color='red'> Best Paper Award, ICML 2023 TEACH Workshop </font>

<!--TLDR: *We propose a novel interactive planning approach using LLMs that brings a planning-based agent to the apex of open-world Minecraft for the first time.*-->

**Zihao Wang**, [Shaofei Cai](https://phython96.github.io/), [Anji Liu](https://liuanji.github.io/), [Xiaojian Ma](https://web.cs.ucla.edu/~xm/), [Yitao Liang](https://web.cs.ucla.edu/~yliang/)
  
**NeurIPS 2023, ICMLW Best Paper** \| [Paper](https://arxiv.org/pdf/2302.01560.pdf) \| [Code](https://github.com/CraftJarvis/MC-Planner) 

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">CVPR 2023</div><img src='images/papers/2301.10034.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Open-World Multi-Task Control Through Goal-Aware Representation Learning and Adaptive Horizon Prediction](https://arxiv.org/pdf/2301.10034.pdf)

[Shaofei Cai](https://phython96.github.io/), **Zihao Wang**, [Xiaojian Ma](https://web.cs.ucla.edu/~xm/), [Anji Liu](https://liuanji.github.io/), [Yitao Liang](https://web.cs.ucla.edu/~yliang/)

**CVPR 2023** \| [Paper](https://arxiv.org/pdf/2301.10034.pdf) \| [Code](https://github.com/CraftJarvis/MC-Controller)

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">CVPR 2023</div><img src='images/papers/CVPR23.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Learning Transformation-Predictive Representations for Detection and Description of Local Features](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Learning_Transformation-Predictive_Representations_for_Detection_and_Description_of_Local_Features_CVPR_2023_paper.pdf)

**Zihao Wang**, Chunxu Wu, Yifei Yang, Zhen Li

**CVPR 2023** 

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">TNNLS</div><img src='images/papers/TNNLS22.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Graph-Based Contrastive Learning for Description and Detection of Local Features](https://ieeexplore.ieee.org/abstract/document/9906927/)

**Zihao Wang**, Zhen Li, Xueyi Li, Wenjie Chen, Xiangdong Liu

**IEEE Trans. Neural Netw. Learn. Syst. (TNNLS 2022)** 

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">IJCAI 2021</div><img src='images/papers/IJCAI21.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Local Representation is NOT Enough: Soft Point-wise Transformer for descriptor and Detector of Local Features](https://www.ijcai.org/proceedings/2021/0159.pdf)

**Zihao Wang**, Xueyi Li, Zhen Li

**IJCAI 2021** 

</div>
</div>

<!--
- [Local Representation is NOT Enough: Soft Point-wise Transformer for descriptor and Detector of Local Features](https://www.ijcai.org/proceedings/2021/0159.pdf)

  **Zihao Wang**, Xueyi Li, Zhen Li

  **IJCAI 2021** \| [Paper](https://www.ijcai.org/proceedings/2021/0159.pdf)
-->

# 💬 Invited Talks
- *2023.03*, Invited talk at City University of Hong Kong and The Hong Kong Polytechnic University on ["open-ended embodied agents with multi-task skills"](http://cccn.ee.cityu.edu.hk/webinar/)
- *2022.08*, Invited talk at Beijing Institute of General Artificial Intelligence on "learning detection and description of local features".

# 🔭 Academic Service 
- Reviewer for ICML, NeurIPS, ICLR.
- Teaching Assistant for "Introduction to AI" Fall 2023, Peking University.

# 💻 Internships
- *2021.05 - 2021.08*, Alibaba Inc, Beijing.

# 📖 Educations
- *2022.09 - now*, PhD student of Computer Science, Peking University
- *2019.09 - 2022.06*, Master of Control Science and Technology, Beijing Institute of Technology 
- *2015.09 - 2019.06*, Bachelor of Automation, Beijing Institute of Technology

# 🎖 Honors and Awards
- *2021.10* Chinese National Scholarship
- *2019.06* Outstanding Graduate of Beijing
- *2018.11* Autonomy Prize of Indoor Event on 10th International Micro Air Vehicle Competition and Conference, Melbourne.
- *2018.08* First Prize on China National Robot Competition 2018.
- *2018.04* Meritorious Winner on American Mathematical Contest In Modeling (MCM) 2018. 
