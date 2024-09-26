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

I am a Ph.D. student in the Institute for Artificial Intelligence at Peking University (PKU), advised by [Prof. Yitao Liang](https://scholar.google.com/citations?user=KVzR1XEAAAAJ). 
Before joining PKU, I received my MSc and BA degrees in Control Science and Technology from Beijing Institute of Technology.
I work on building open-ended embodied agents with multi-task skills, including visual localization, task planning, and decision-making. In particular, I am interested in building and leveraging large pre-trained *Foundation Models* to improve the generalization of agent capabilities.

Recently, we have developed a series of open-world multi-task agents, including [OmniJARVIS](https://omnijarvis.github.io/) (pretrained end-to-end Vision-Language-Action models with self-supervised quantified tokenizer), [JARVIS-1](https://craftjarvis.github.io/JARVIS-1/) (self-improving with multimodal memory), [DEPS](https://github.com/CraftJarvis/MC-Planner) (interactive long-horizon planning agent), [RAT](https://craftjarvis.github.io/RAT) (tool-use agent with retrieval-augmented thought), [GROOT](https://craftjarvis.github.io/GROOT) (self-supervised vision-based multitask policy), and [ProAgent](https://pku-proagent.github.io/) (collaborating agents).


# 🔥 News
- Sep 2024: &nbsp;🎉🎉 Our latest Vision-Language-Action models [OmniJARVIS](https://omnijarvis.github.io) is accepted by NeurIPS 2024.
- Aug 2024: &nbsp;📢📢 We will organize the 1st [Open-world Agent Workshop](https://sites.google.com/view/open-world-agents/) in NeurIPS 2024 (Vancouver, BC, Canada). [Calling for papers](https://sites.google.com/view/open-world-agents/call-for-papers?authuser=0) NOW! 🔥🔥🔥
- Jun 2024: &nbsp;🎉🎉 [Rectified Scaling Law](https://rectified-scaling-law.github.io/) is accepted by ICML 2024.
- Jan 2024: &nbsp;🎉🎉 [GROOT](https://craftjarvis.github.io/GROOT) is accepted by ICLR 2024 for spotlight presentation (top 5%).
- Jan 2024: &nbsp;🎉🎉 [ProAgent](https://pku-proagent.github.io/) is accepted by AAAI 2024 for oral presentation.
- Sep 2023: &nbsp;🎉🎉 [DEPS](https://arxiv.org/pdf/2302.01560.pdf) is accepted by NeurIPS 2023.
- Jul 2023: &nbsp;🎉🎉 [DEPS](https://arxiv.org/pdf/2302.01560.pdf) received Best Paper Award at ICML 2023 TEACH Workshop! 
- Feb 2023: &nbsp;🎉🎉 Two papers are accepted by CVPR 2023. 

# 📝 Publications 

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">NeurIPS 2024</div><img src='images/papers/2407.00114.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**OmniJARVIS: Unified Vision-Language-Action Tokenization Enables Open-World Instruction Following Agents**

An end-to-end open-ended agent based on Vision-Language-Action (VLA) models with self-supervised behavior tokenizer, that can answer questions and follow instructions in open-world Minecraft.

**Zihao Wang**, [Shaofei Cai](https://phython96.github.io/), [Zhancun Mu](https://zhancunmu.owlstown.net/), [Haowei Lin](https://linhaowei1.github.io/), [Ceyao Zhang](https://scholar.google.com/citations?user=OadTFGMAAAAJ), [Xuejie Liu](https://scholar.google.com/citations?user=vxqpWKUAAAAJ), [Qing Li](https://scholar.google.com/citations?user=iwdFZBEAAAAJ), [Anji Liu](https://liuanji.github.io/), [Xiaojian Ma](https://web.cs.ucla.edu/~xm/), [Yitao Liang](https://web.cs.ucla.edu/~yliang/)
  
**NeurIPS 2024** \| [Project](https://omnijarvis.github.io/) \| [Paper](https://arxiv.org/pdf/2407.00114) \| [Twitter](https://x.com/jeasinema/status/1808346701205516395) 

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">arXiv</div><img src='images/papers/2403.05313.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**RAT: Retrieval Augmented Thoughts Elicit Context-Aware Reasoning in Long-Horizon Generation**

An agent with retrieval-augmented thought that can conduct code generation, math reasoning, embodied planning and open-ended question answering.

**Zihao Wang**, [Anji Liu](https://liuanji.github.io/), [Haowei Lin](https://linhaowei1.github.io/), Jiaqi Li, [Xiaojian Ma](https://web.cs.ucla.edu/~xm/), [Yitao Liang](https://web.cs.ucla.edu/~yliang/)
  
**arXiv** \| [Project](https://craftjarvis.github.io/RAT) \| [Demo](https://huggingface.co/spaces/jeasinema/RAT) \| [Paper](https://arxiv.org/pdf/2403.05313.pdf) \| [Code](https://github.com/CraftJarvis/RAT) \| [Twitter](https://x.com/AndyLin2001/status/1767075865127719101) 

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">arXiv</div><img src='images/papers/2311.05997.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

<!--font size="4">JARVIS-1: Open-World Multi-task Agents with Memory-Augmented Multimodal Language Models</font-->
**JARVIS-1: Open-World Multi-task Agents with Memory-Augmented Multimodal Language Models**

A multi-task agent that can self-improve in open-ended Minecraft and accomplish up to 200+ tasks.

**Zihao Wang**, [Shaofei Cai](https://phython96.github.io/), [Anji Liu](https://liuanji.github.io/), Yonggang Jin, Jinbing Hou, Bowei Zhang, Haowei Lin, Zhaofeng He, Zilong Zheng, Yaodong Yang, [Xiaojian Ma](https://web.cs.ucla.edu/~xm/), [Yitao Liang](https://web.cs.ucla.edu/~yliang/)
  
**arXiv** \| [Project](https://craftjarvis.github.io/JARVIS-1/) \| [Paper](https://arxiv.org/pdf/2311.05997.pdf) \| [Code](https://github.com/CraftJarvis/JARVIS1) \| [Twitter](https://twitter.com/jeasinema/status/1723900032653643796) \| [Media](https://mp.weixin.qq.com/s/4SyX4QCdu9rBptRvOQIwXg)

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">NeurIPS 2023</div><img src='images/papers/2302.01560.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

<!-- <font size="4">Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents</font> -->

**Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents**

<!-- <font color='red'> <br> Best Paper Award, ICML 2023 TEACH Workshop </font> -->
<font color='red'> Best Paper Award, ICML 2023 TEACH Workshop </font>

**Zihao Wang**, [Shaofei Cai](https://phython96.github.io/), [Anji Liu](https://liuanji.github.io/), [Xiaojian Ma](https://web.cs.ucla.edu/~xm/), [Yitao Liang](https://web.cs.ucla.edu/~yliang/)
  
**NeurIPS 2023** \| [Paper](https://arxiv.org/pdf/2302.01560.pdf) \| [Code](https://github.com/CraftJarvis/MC-Planner) \| [Twitter](https://twitter.com/jeasinema/status/1622428535897067521)

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">ICLR 2024</div><img src='images/papers/2310.08235.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

<!-- <font size="4">GROOT: Learning to Follow Instructions by Watching Gameplay Videos</font> -->
**GROOT: Learning to Follow Instructions by Watching Gameplay Videos**

[Shaofei Cai](https://phython96.github.io/), Bowei Zhang, **Zihao Wang**, [Xiaojian Ma](https://web.cs.ucla.edu/~xm/), [Anji Liu](https://web.cs.ucla.edu/~yliang/), [Yitao Liang](https://web.cs.ucla.edu/~yliang/)
  
**ICLR 2024 (Spotlight)** \| [Project](https://craftjarvis.github.io/GROOT/) \| [Paper](https://arxiv.org/pdf/2310.08235.pdf) \| [Code](https://github.com/CraftJarvis/GROOT) \| [Twitter](https://twitter.com/jeasinema/status/1712526192665047493) \| [Media](https://mp.weixin.qq.com/s/IqIRxFYDpCi3_Iy1FUg9DQ)

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">ICML 2024</div><img src='images/papers/2402.02314.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

<!-- <font size="4">MCU: A Task-centric Framework for Open-ended Agent Evaluation in Minecraft</font> -->
**Selecting Large Language Model to Fine-tune via Rectified Scaling Law**

[Haowei Lin](https://linhaowei1.github.io/), Baizhou Huang, [Haotian Ye](https://haotianye.com/), Qinyu Chen, **Zihao Wang**, [Sujian Li](https://pku-tangent.github.io/), [Jianzhu Ma](https://majianzhu.com/), [Xiaojun Wan](https://wanxiaojun.github.io/), [James Zou](https://www.james-zou.com/), [Yitao Liang](https://web.cs.ucla.edu/~yliang/)
  
**ICML 2024** \| [Project](https://rectified-scaling-law.github.io/) \| [Paper](https://arxiv.org/pdf/2402.02314) \| [Code](https://github.com/linhaowei1/Fine-tuning-Scaling-Law) 

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">arXiv</div><img src='images/papers/2310.08367.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

<!-- <font size="4">MCU: A Task-centric Framework for Open-ended Agent Evaluation in Minecraft</font> -->
**MCU: A Task-centric Framework for Open-ended Agent Evaluation in Minecraft**

[Haowei Lin](https://linhaowei1.github.io/), **Zihao Wang**, [Jianzhu Ma](https://majianzhu.com/), [Yitao Liang](https://web.cs.ucla.edu/~yliang/)
  
**NeurIPSW 2024** \| [Paper](https://arxiv.org/pdf/2310.08367.pdf) \| [Code](https://github.com/CraftJarvis/MCU) 

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">AAAI 2024</div><img src='images/papers/2308.11339.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

<!-- <font size="4">ProAgent: Building Proactive Cooperative AI with Large Language Models</font> -->
**ProAgent: Building Proactive Cooperative AI with Large Language Models**

Ceyao Zhang, Kaijie Yang, Siyi Hu, **Zihao Wang**, Guanghe Li, Yihang Sun, Cheng Zhang, Zhaowei Zhang, Anji Liu, Song-Chun Zhu, Xiaojun Chang, Junge Zhang, Feng Yin, Yitao Liang, Yaodong Yang
  
**AAAI 2024 (Oral)** \| [Project](https://pku-proagent.github.io/) \| [Paper](https://arxiv.org/pdf/2308.11339.pdf) \| [Code](https://github.com/PKU-Alignment/ProAgent) 

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">CVPR 2023</div><img src='images/papers/2301.10034.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

<!-- <font size="4">Open-World Multi-Task Control Through Goal-Aware Representation Learning and Adaptive Horizon Prediction</font> -->
**Open-World Multi-Task Control Through Goal-Aware Representation Learning and Adaptive Horizon Prediction**

[Shaofei Cai](https://phython96.github.io/), **Zihao Wang**, [Xiaojian Ma](https://web.cs.ucla.edu/~xm/), [Anji Liu](https://liuanji.github.io/), [Yitao Liang](https://web.cs.ucla.edu/~yliang/)

**CVPR 2023** \| [Paper](https://arxiv.org/pdf/2301.10034.pdf) \| [Code](https://github.com/CraftJarvis/MC-Controller)

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">CVPR 2023</div><img src='images/papers/CVPR23.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

<!-- [<font size="4">Learning Transformation-Predictive Representations for Detection and Description of Local Features</font>](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Learning_Transformation-Predictive_Representations_for_Detection_and_Description_of_Local_Features_CVPR_2023_paper.pdf) -->

[**Learning Transformation-Predictive Representations for Detection and Description of Local Features**](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Learning_Transformation-Predictive_Representations_for_Detection_and_Description_of_Local_Features_CVPR_2023_paper.pdf)

<!--a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Learning_Transformation-Predictive_Representations_for_Detection_and_Description_of_Local_Features_CVPR_2023_paper.pdf" style="font-size: 2em;">Learning Transformation-Predictive Representations for Detection and Description of Local Features</a-->

**Zihao Wang**, Chunxu Wu, Yifei Yang, Zhen Li

**CVPR 2023** 

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">TNNLS</div><img src='images/papers/TNNLS22.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

<!-- [<font size="4">Graph-Based Contrastive Learning for Description and Detection of Local Features</font>](https://ieeexplore.ieee.org/abstract/document/9906927/) -->

[**Graph-Based Contrastive Learning for Description and Detection of Local Features**](https://ieeexplore.ieee.org/abstract/document/9906927/)

<!--a href="https://ieeexplore.ieee.org/abstract/document/9906927/" style="font-size: 2em;">Graph-Based Contrastive Learning for Description and Detection of Local Features</a-->

**Zihao Wang**, Zhen Li, Xueyi Li, Wenjie Chen, Xiangdong Liu

**IEEE Trans. Neural Netw. Learn. Syst. (TNNLS 2022)** 

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div class="badge">IJCAI 2021</div><img src='images/papers/IJCAI21.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

<!-- [<font size="4">Local Representation is NOT Enough: Soft Point-wise Transformer for descriptor and Detector of Local Features</font>](https://www.ijcai.org/proceedings/2021/0159.pdf) -->

[**Local Representation is NOT Enough: Soft Point-wise Transformer for descriptor and Detector of Local Features**](https://www.ijcai.org/proceedings/2021/0159.pdf)

<!--a href="https://www.ijcai.org/proceedings/2021/0159.pdf" style="font-size: 2em;">Local Representation is NOT Enough: Soft Point-wise Transformer for descriptor and Detector of Local Features</a-->


**Zihao Wang**, Xueyi Li, Zhen Li

**IJCAI 2021** 

</div>
</div>

<!--
- [Local Representation is NOT Enough: Soft Point-wise Transformer for descriptor and Detector of Local Features](https://www.ijcai.org/proceedings/2021/0159.pdf)

  ***Zihao Wang***, Xueyi Li, Zhen Li

  **IJCAI 2021** \| [Paper](https://www.ijcai.org/proceedings/2021/0159.pdf)
-->

# 💬 Talks
- \[Dec 2023\] Invited Talks at [BAAI](https://mp.weixin.qq.com/s/Cv8I2dzW-aI1c6aZSUFi-g), [Peking University](https://mp.weixin.qq.com/s/ycrWF-4cUeh-pMCT0wO3uA) on "Building Autonmous Agents in Open World".
- \[Jul 2023\] Invited Talk at NVIDIA on "Towards Multi-task Agents in Open World".
- \[Mar 2023\] Invited Talk at [City University of Hong Kong](http://cccn.ee.cityu.edu.hk/webinar) and The Hong Kong Polytechnic University on "Open-Ended Embodied Agents with Multi-Task Skills".
- \[Aug 2022*\] Invited Talk at Beijing Institute of General Artificial Intelligence (BIGAI) on "Learning Detection and Description of Local Features"
<!-- - \[Aug 2021\], Invited Talk at Alibaba Inc on "Learning Detection and Description of Local Features" -->

<!-- # 🔭 Academic Service 
- Reviewer for ICML, NeurIPS, ICLR.
- Teaching Assistant for "Introduction to AI" Fall 2023, Peking University.

# 💻 Internships
- 2021.05 - 2021.08, Alibaba Inc, Beijing. -->

# 🔭 Experience
- Organizer for 1st [Open-world Agent Workshop](https://sites.google.com/view/open-world-agents/) in NeurIPS 2024.
- Reviewer for ICML, NeurIPS, ICLR, ECCV, AAAI.
- Intern in Alibaba Inc, Beijing, 2021.05 - 2021.08.
- Teaching Assistant for "Introduction to AI" Fall 2023, Peking University.

<!-- # 📖 Educations
- *2022.09 - now*, PhD student of Computer Science, Peking University
- *2019.09 - 2022.06*, Master of Control Science and Technology, Beijing Institute of Technology 
- *2015.09 - 2019.06*, Bachelor of Automation, Beijing Institute of Technology -->

# 🎖 Honors and Awards
- \[Jul 2023\] Best Paper Award, ICML 2023 TEACH Workshop
- \[Oct 2021\] Chinese National Scholarship
- \[Jun 2019\] Outstanding Graduate of Beijing
- \[Nov 2018\] Autonomy Prize of Indoor Event on 10th International Micro Air Vehicle Competition and Conference, Melbourne.
<!-- - \[Aug 2018\] First Prize on China National Robot Competition 2018. -->
- \[Apr 2018\] Meritorious Winner on American Mathematical Contest In Modeling (MCM) 2018. 
