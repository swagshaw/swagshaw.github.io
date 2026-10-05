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

 I am currently a PhD candidate at the University of Melbourne in Australia. My research journey is fully supported by the Melbourne Research Scholarship, and I'm incredibly fortunate to be supervised by Dr. [Ting Dang](https://tingdang90.github.io/) and Prof. [Eun-Jung Holden](https://findanexpert.unimelb.edu.au/profile/1053597-eun-jung-holden). Before joining Unimelb, I was an AI engineer at [Fortemedia](https://www.fortemedia.com/) working with Dr. [Rohan Kumar Das](https://sites.google.com/view/rohankumardas). I graduated as a CS Master student at [NTU](https://www.ntu.edu.sg/) advised by Prof. [Chng Eng Siong](https://personal.ntu.edu.sg/aseschng/default.html). I obtained my B.Eng degree from Jilin University. 

I am contributing to building “adaptive”, “efficient”, and “robust” next-generation speech AI systems. At this moment, I mainly work on post-training paradigms for speech learning systems. Specifically, by merging continual learning, domain adaptation, knowledge editing, and reinforcement fine-tuning, we pave the way for speech models that continuously adapt, specialize efficiently, and self-correct in real-world environments. I have published more than 20 papers at top international AI conferences and journals such as ACL, EMNLP, ICASSP, and INTERSPEECH.  <a href='https://scholar.google.com/citations?user=lgcOwb4AAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fswagshaw%2Fswagshaw.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> 


# 🔥 News
- *2026.09*: &nbsp;🎉🎉  One paper has been accepted to NeurIPS 2026!
- *2026.09*: &nbsp;🎉🎉  One paper has been accepted to IEEE SLT 2026!
- *2026.08*: &nbsp;🎉🎉  One paper has been accepted to EMNLP 2026 as an Oral presentation!
- *2026.06*: &nbsp;🎉🎉  I am honored to serve as a session chair at ACL 2026!
- *2026.05*: &nbsp;🎉🎉  Five papers have been accepted to Interspeech 2026!
- *2026.05*: &nbsp;🎉🎉  Two papers have been accepted to the ICML 2026 Workshop on Machine Learning for Audio!
- *2026.04*: &nbsp;🎉🎉  One paper has been accepted to ACL 2026!
- *2026.01*: &nbsp;🎉🎉  Four papers have been accepted to IEEE ICASSP 2026!
- *2025.12*: &nbsp;🎉🎉  Our ICME grand challenge [ESDD 2](https://sites.google.com/view/esdd-challenge/esdd-challenges/esdd-2?authuser=0) has been launched.
- *2025.11*: &nbsp;🎉🎉  Call for Papers: We will launch "[Post-Training of Speech Foundation Models](https://sites.google.com/view/ptsfm/)" at INTERSPEECH 2026 Special Sessions.
- *2025.10*: &nbsp;🎉🎉  I am honored to serve as a session chair at APSIPA ASC 2025!
- *2025.09*: &nbsp;🎉🎉  One paper has been accepted to IEEE Signal Processing Letters 2025!
- *2025.09*: &nbsp;🎉🎉  Our ICASSP grand challenge [ESDD 2026](https://sites.google.com/view/esdd-challenge) has been launched. 

# 🔍 Research Area

**Speech and Audio Processing**: Sound Event Detection, Spoken Keyword Spotting, Speech Foundation Model, DeepFake Detection

**Algorithm**: Continual learning, Test-time adaptation, Knowledge editing

# 🎓 Educations
- 08.2025 - Now, Doctor of Philosophy - Engineering and IT, The University of Melbourne, Australia  
- 08.2021 - 01.2023,  Master of Science (Artificial Intelligence), Nanyang Technological University, Singapore  
- 08.2016 - 07.2020, B.E. in Internet of Things Engineering, Jilin University, Changchun, China

# 💼 Work Experience
- 01.2023 - 08.2025, AI Engineer, Fortemedia Singapore
- 07.2020 - 05.2021, Software Engineer, China Mobile (Chengdu) Industrial Research Institute

# 📝 Publications 
Highlighted papers are shown first, followed by publications grouped by topic (click to expand). See [Google Scholar](https://scholar.google.com/citations?user=lgcOwb4AAAAJ) for the full list.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2026 Oral</div><img src='/images/EnvMem.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Why Can't They Remember? Uncovering Representation and Retrieval Bottlenecks in Multi-Turn Acoustic Memory](https://arxiv.org/pdf/2605.27039)

**<u>Yang Xiao</u>**, Siyi Wang, Han Yin, Hong Jia, Vidhyasaharan Sethu, Eun-Jung Holden, Ting Dang.

- EnvMem, a controlled multi-turn benchmark revealing that large audio language models fail to recall early non-speech acoustic cues, with representational trajectory drift as the key failure mode.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='/images/VoxMem.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VoxMem: Benchmarking Multimodal Memory in Large Audio Language Models](https://arxiv.org/pdf/2609.32607)

**<u>Yang Xiao</u>**, Vidhyasaharan Sethu, Eun-Jung Holden, Ting Dang.

[**Project**](https://swagshaw.github.io/voxmem/) | [**Code**](https://github.com/swagshaw/voxmem) | [**Dataset**](https://huggingface.co/datasets/AudioMemory/voxmembench)
- A multi-session spoken memory benchmark crossing four acoustic evidence types with four memory operations; across 15 LALMs, no model exceeds 40% at 32K context.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INTERSPEECH 2025</div><img src='/images/EnvSDD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EnvSDD: Benchmarking Environmental Sound Deepfake Detection](https://www.isca-archive.org/interspeech_2025/yin25_interspeech.pdf)

Han Yin, **<u>Yang Xiao</u>**, Rohan Kumar Das, Jisheng Bai, Haohe Liu, Wenwu Wang, Mark D Plumbley.

[**Project**](https://envsdd.github.io/) | [**Code**](https://github.com/apple-yinhan/EnvSDD/)
- The first large-scale curated dataset designed for Environmental Sound Deepfake Detection.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SPL 2025</div><img src='/images/xlsr_mamba_plot.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[XLSR-Mamba: A Dual-Column Bidirectional State Space Model for Spoofing Attack Detection](https://ieeexplore.ieee.org/document/10909468)

**<u>Yang Xiao</u>**, Rohan Kumar Das.

[**Code**](https://github.com/swagshaw/XLSR-Mamba/)
</div>
</div>


<details class="pub-group" markdown="1">
<summary>Large Audio Language Models</summary>

- **RAIL: Rethinking Auditory Intelligence in Large Audio-Language Models with a CHC-Grounded Benchmark**<br>
  Hongyu Jin\*, Siyi Wang\*, **<u>Yang Xiao</u>\***, Jiaheng Dong\*, Shihong Tan, Kaiyuan Peng, Georgiana Juravle, Shanquan Chen, Gongping Huang, Hong Jia, Eun-Jung Holden, James Bailey, Ting Dang<br>
  NeurIPS 2026<br>
  [[paper](https://arxiv.org/pdf/2606.11260)]

- **PolyBench: A Benchmark for Compositional Reasoning in Polyphonic Audio**<br>
  Yuanjian Chen, **<u>Yang Xiao</u>**, Han Yin, Xubo Liu, Jinjie Huang, Ting Dang<br>
  INTERSPEECH 2026<br>
  [[paper](https://arxiv.org/pdf/2603.05128)]

- **Focus Then Listen: An Empirical Study of Plug-and-Play Audio Enhancer for Noise-Robust Large Audio Language Models**<br>
  Han Yin, **<u>Yang Xiao</u>**, Younghoo Kwon, Ting Dang, Jung-Woo Choi<br>
  ICML 2026 Workshop<br>
  [[paper](https://arxiv.org/pdf/2603.04862)]

- **Titans-as-a-Layer: Test-Time Memory for Conversational Speech Emotion Recognition**<br>
  Daniel Chen, Qicong Hu, **<u>Yang Xiao</u>**, Ting Dang, Hong Jia<br>
  ICML 2026 Workshop<br>
  [[paper](https://arxiv.org/pdf/2606.08573)]

</details>

<details class="pub-group" markdown="1">
<summary>Continual Learning</summary>

- **Continual Adaptation for Pacific Indigenous Speech Recognition**<br>
  **<u>Yang Xiao</u>**, Aso Mahmudi, Nick Thieberger, Eliathamby Ambikairajah, Eun-Jung Holden, Ting Dang<br>
  INTERSPEECH 2026<br>
  [[paper](https://arxiv.org/pdf/2603.06310)]

- **Adapting Where It Matters: Depth-Aware Adaptation for Efficient Multilingual Speech Recognition in Low-Resource Languages**<br>
  **<u>Yang Xiao</u>**, Eun-Jung Holden, Ting Dang<br>
  ACL 2026<br>
  [[paper](https://arxiv.org/pdf/2602.01008)]

- **AFT: An Exemplar-Free Class Incremental Learning Method for Environmental Sound Classification**<br>
  Xinyi Chen, Xi Chen, Zhenyu Weng, **<u>Yang Xiao</u>**<br>
  ICASSP 2026<br>
  [[paper](https://arxiv.org/pdf/2509.15523)]

- **Listen, Analyze, and Adapt to Learn New Attacks: An Exemplar-Free Class Incremental Learning Method for Audio Deepfake Source Tracing**<br>
  **<u>Yang Xiao</u>**, Rohan Kumar Das<br>
  INTERSPEECH 2025<br>
  [[paper](https://www.isca-archive.org/interspeech_2025/xiao25c_interspeech.pdf)]

- **AnalyticKWS: Towards Exemplar-Free Analytic Class Incremental Learning for Small-footprint Keyword Spotting**<br>
  **<u>Yang Xiao</u>**, Peng Tianyi, Rohan Kumar Das, Yuchen Hu, Huiping Zhuang<br>
  ACL 2025<br>
  [[paper](https://aclanthology.org/2025.findings-acl.728.pdf)]

- **Where's That Voice Coming? Continual Learning for Sound Source Localization**<br>
  **<u>Yang Xiao</u>**, Rohan Kumar Das<br>
  ICME 2025<br>
  [[paper](https://arxiv.org/pdf/2407.03661)]

- **UCIL: An Unsupervised Class Incremental Learning Approach for Sound Event Detection**<br>
  **<u>Yang Xiao</u>**, Rohan Kumar Das<br>
  ICASSP 2025<br>
  [[paper](https://ieeexplore.ieee.org/document/10887631/)]

- **Dark Experience for Incremental Keyword Spotting**<br>
  Tianyi Peng, **<u>Yang Xiao</u>**<br>
  ICASSP 2025<br>
  [[paper](https://ieeexplore.ieee.org/document/10890228)]

- **Continual Learning For On-Device Environmental Sound Classification**<br>
  **<u>Yang Xiao</u>\***, Xubo Liu\*, James King, Arshdeep Singh, Eng Siong Chng, Mark D. Plumbley, Wenwu Wang<br>
  DCASE 2022<br>
  [[paper](https://dcase.community/documents/workshop2022/proceedings/DCASE2022Workshop_Xiao_47.pdf)]

- **Rainbow Keywords: Efficient Incremental Learning for Online Spoken Keyword Spotting**<br>
  **<u>Yang Xiao</u>**, Nana Hou, Eng Siong Chng<br>
  INTERSPEECH 2022<br>
  [[paper](https://www.isca-archive.org/interspeech_2022/xiao22_interspeech.pdf)]

</details>

<details class="pub-group" markdown="1">
<summary>Domain & Test-Time Adaptation</summary>

- **QuaSR: Quality-Aware Sample Reweighting for Pacific Indigenous Speech Recognition**<br>
  Yishun Li, **<u>Yang Xiao</u>**, Gongping Huang, Eun-Jung Holden, Nick Thieberger, Ting Dang<br>
  SLT 2026<br>
  [[paper](https://arxiv.org/pdf/2607.03658)]

- **ImKWS: Test-Time Adaptation for Keyword Spotting with Class Imbalance**<br>
  Hanyu Ding\*, **<u>Yang Xiao</u>\***, Jiaheng Dong, Ting Dang<br>
  INTERSPEECH 2026<br>
  [[paper](https://arxiv.org/pdf/2603.05821)]

- **Activation Steering for Accent Adaptation in Large Audio Language Models**<br>
  Jinuo Sun\*, **<u>Yang Xiao</u>\***, Sung Kyun Chung, Qiuchi Hu, Gongping Huang, Eun-Jung Holden, Ting Dang<br>
  INTERSPEECH 2026<br>
  [[paper](https://arxiv.org/pdf/2603.05813)]

- **AdaKWS: Towards Robust Keyword Spotting with Test-Time Adaptation**<br>
  **<u>Yang Xiao</u>**, Tianyi Peng, Yanghao Zhou, Rohan Kumar Das<br>
  INTERSPEECH 2025<br>
  [[paper](https://www.isca-archive.org/interspeech_2025/xiao25b_interspeech.pdf)]

- **DG-SED: Domain Generalization for Sound Event Detection with Heterogeneous Training Data**<br>
  **<u>Yang Xiao</u>**, Han Yin, Jisheng Bai, Rohan Kumar Das<br>
  APSIPA ASC 2025<br>
  [[paper](https://arxiv.org/abs/2407.03654)]

- **WildDESED: An LLM-Powered Dataset for Wild Domestic Environment Sound Event Detection System**<br>
  **<u>Yang Xiao</u>**, Rohan Kumar Das<br>
  DCASE 2024<br>
  [[paper](https://arxiv.org/pdf/2407.03656.pdf)]

</details>

<details class="pub-group" markdown="1">
<summary>Audio Deepfake Detection</summary>

- **The First Environmental Sound Deepfake Detection Challenge: Benchmarking Robustness, Evaluation, and Insights**<br>
  Han Yin, **<u>Yang Xiao</u>**, Rohan Kumar Das, Jisheng Bai, Ting Dang<br>
  INTERSPEECH 2026<br>
  [[paper](https://arxiv.org/pdf/2603.04865)]

- **Environmental Sound Deepfake Detection Challenge: An Overview**<br>
  Han Yin, **<u>Yang Xiao</u>**, Rohan Kumar Das, Jisheng Bai, Ting Dang<br>
  ICASSP 2026<br>
  [[paper](https://arxiv.org/pdf/2512.24140)]

- **Multilingual Source Tracing of Speech Deepfakes: A First Benchmark**<br>
  Xi Xuan, **<u>Yang Xiao</u>**, Rohan Kumar Das, Tomi Kinnunen<br>
  SPSC 2025<br>
  [[paper](https://arxiv.org/pdf/2508.04143)]

- **RawTFNet: A Lightweight CNN Architecture for Speech Anti-spoofing**<br>
  **<u>Yang Xiao</u>**, Ting Dang, Rohan Kumar Das<br>
  APSIPA ASC 2025<br>
  [[paper](https://arxiv.org/pdf/2507.08227)]

</details>

<details class="pub-group" markdown="1">
<summary>Sound Event Detection & Localization</summary>

- **Temporally Heterogeneous Graph Contrastive Learning for Multimodal Acoustic event Classification**<br>
  Yuanjian Chen, **<u>Yang Xiao</u>**, Jinjie Huang<br>
  ICASSP 2026<br>
  [[paper](https://arxiv.org/pdf/2509.14893)]

- **Noise-Robust Sound Event Detection and Counting via Language-Queried Sound Separation**<br>
  Yuanjian Chen, **<u>Yang Xiao</u>**, Han Yin, Yadong Guan, Xubo Liu<br>
  SPL 2025<br>
  [[paper](https://arxiv.org/pdf/2508.07176)]

- **TF-Mamba: A Time-Frequency Network for Sound Source Localization**<br>
  **<u>Yang Xiao</u>**, Rohan Kumar Das<br>
  INTERSPEECH 2025<br>
  [[paper](https://www.isca-archive.org/interspeech_2025/xiao25_interspeech.pdf)]

- **Exploring Text-Queried Sound Event Detection with Audio Source Separation**<br>
  Han Yin, Jisheng Bai, **<u>Yang Xiao</u>**, Hui Wang, Siqi Zheng, Yafeng Chen, Rohan Kumar Das, Chong Deng, Jianfeng Chen<br>
  ICASSP 2025<br>
  [[paper](https://ieeexplore.ieee.org/abstract/document/10889789/)]

</details>

<details class="pub-group" markdown="1">
<summary>Others</summary>

- **MoEScore: Mixture-of-Experts-Based Text-Audio Relevance Score Prediction for Text-to-Audio System Evaluation**<br>
  Bochao Sun, **<u>Yang Xiao</u>**, Han Yin<br>
  ICASSP 2026<br>
  [[paper](https://arxiv.org/pdf/2601.06829)]

- **Small Footprint Multi-channel Network for Keyword Spotting with Centroid Based Awareness**<br>
  Dianwen Ng, **<u>Yang Xiao</u>**, Jia Qi Yip, Zhao Yang, Biao Tian, Qiang Fu, Eng Siong Chng, Bin Ma<br>
  INTERSPEECH 2023<br>
  [[paper](https://www.isca-archive.org/interspeech_2023/ng23b_interspeech.pdf)]

</details>

<p class="pub-note">* indicates equal contribution.</p>

# 😁 Academic Services
- Session Chair: ACL, APSIPA ASC, INTERSPEECH, ICASSP
- Organizer: APSIPA ASC Special Session ([ESPRESSO 2025](https://sites.google.com/view/espresso2025)), ICASSP Grand Challenge ([ESDD 2026](https://sites.google.com/view/esdd-challenge/esdd-challenges/esdd-2/description)), ICME Challenge ([ESDD 2](https://sites.google.com/view/esdd-challenge/esdd-challenges/esdd-2/description)), INTERSPEECH Special Session ([PTSFM](https://sites.google.com/view/ptsfm))
- Conference Reviewer: INTERSPEECH, ICASSP, ICME, IJCNN, APSIPA ASC, DCASE
- Journal Reviewer: IEEE TASLP, IEEE SPL, Pattern Recognition, EURASIP

# 🎖 Honors and Awards
- *2026* IEEE Signal Processing Society Travel Grant, ICASSP 2026, Barcelona 
- *2025* ISCA (International Speech Communication Association) Grant, Interspeech, Rotterdam
- *2025* Melbourne Research Scholarship, University of Melbourne

