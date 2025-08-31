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

 I am currently a PhD student at the University of Melbourne in Australia. My research journey is fully supported by the Melbourne Research Scholarship, and I'm incredibly fortunate to be supervised by Dr. [Ting Dang](https://tingdang90.github.io/) and Prof. [Eun-Jung Holden](https://findanexpert.unimelb.edu.au/profile/1053597-eun-jung-holden). Before joining Unimelb, I was an AI engineer at [Fortemedia](https://www.fortemedia.com/) working with Dr. [Rohan Kumar Das](https://sites.google.com/view/rohankumardas). I graduated as a CS Master student at [NTU](https://www.ntu.edu.sg/) advised by Prof. [Chng Eng Siong](https://personal.ntu.edu.sg/aseschng/default.html). I obtained my B.Eng degree from Jilin University. 

I am contributing to building “adaptive”, “efficient”, and “robust” next-generation speech AI systems. At this moment, I mainly work in the post training paradigms for speech learning systems. Specifically, by merging continual learning, domain adaptation, knowledge editing, and reinforcement fine-tuning, we pave the way for speech models that continuously adapt, specialize efficiently, and self-correct in real-world environments. I have published more than 20 papers at the top international AI conferences and journals such as ACL, SPL, ICME, ICASSP, and INTERSPEECH.  <a href='https://scholar.google.com/citations?user=lgcOwb4AAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fswagshaw%2Fswagshaw.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> 


# 🔥 News
- *2025.09*: &nbsp;🎉🎉 Our ICASSP grand challenge [ESDD 2026](https://sites.google.com/view/esdd-challenge) has been launched. 
- *2025.08*: &nbsp;🎉🎉  I joined the University of Melbourne as a PhD student in Australia!
- *2025.05*: &nbsp;🎉🎉  Four papers have been accepted to Interspeech 2025!

# 🔍 Research Area

**Speech and Audio Processing**: Sound Event Detection, Spoken Keyword Spotting, Speech Foundation Model, DeepFake Detection

**Algorithm**: Continual learning, Test time adaptation, Knowledge editing

# 🎓 Education
- 08.2025 - Now, Doctor of Philosophy - Engineering and IT, The University of Melbourne, Australia  
- 08.2021 - 01.2023,  Master of Science (Artificial Intelligence), Nanyang Technological University, Singapore  
- 08.2016 - 07.2020, B.E. in Internet of Things Engineering, Jilin University, Changchun, China

# 💼 Work Experience
- 01.2023 - 08.2025, AI Engineer, Fortemedia Singapore
- 07.2020 - 05.2021, Software Engineer, China Mobile (Chengdu) Industrial Research Institute

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INTERSPEECH 2025</div><img src='/images/EnvSDD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EnvSDD: Benchmarking Environmental Sound Deepfake Detection](https://www.isca-archive.org/interspeech_2025/yin25_interspeech.pdf)

Han Yin, **Yang Xiao**, Rohan Kumar Das, Jisheng Bai, Haohe Liu, Wenwu Wang, Mark D Plumbley.

[**Project**](https://envsdd.github.io/) | [**Code**](https://github.com/apple-yinhan/EnvSDD/)
- The first large-scale curated dataset designed for Environmental Sound Deepfake Detection.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SPL 2025</div><img src='/images/xlsr_mamba_plot.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[XLSR-Mamba: A Dual-Column Bidirectional State Space Model for Spoofing Attack Detection](https://ieeexplore.ieee.org/document/10909468)

**Yang Xiao**, Rohan Kumar Das.

[**Code**](https://github.com/swagshaw/XLSR-Mamba/)
</div>
</div>


## Continual Learning for Speech / Audio

- ``INTERSPEECH 2025`` [Listen, Analyze, and Adapt to Learn New Attacks: An Exemplar-Free Class Incremental Learning Method for Audio Deepfake Source Tracing](https://www.isca-archive.org/interspeech_2025/xiao25c_interspeech.pdf), **Yang Xiao**, Rohan Kumar Das.
- ``ACL 2025`` [AnalyticKWS: Towards Exemplar-Free Analytic Class Incremental Learning for Small-footprint Keyword Spotting](https://aclanthology.org/2025.findings-acl.728.pdf), **Yang Xiao**, Peng Tianyi, Rohan Kumar Das, Yuchen Hu, Huiping Zhuang
- ``ICME 2025`` [Where's That Voice Coming? Continual Learning for Sound Source Localization](https://arxiv.org/pdf/2407.03661), **Yang Xiao**, Rohan Kumar Das.
- ``ICASSP 2025`` [UCIL: An Unsupervised Class Incremental Learning Approach for Sound Event Detection](https://ieeexplore.ieee.org/document/10887631/), **Yang Xiao**, Rohan Kumar Das.
- ``ICASSP 2025`` [Dark Experience for Incremental Keyword Spotting](https://ieeexplore.ieee.org/document/10890228), Tianyi Peng, **Yang Xiao**.
- ``DCASE 2022`` [Continual Learning For On-Device Environmental Sound Classification](https://dcase.community/documents/workshop2022/proceedings/DCASE2022Workshop_Xiao_47.pdf), **Yang Xiao\***, Xubo Liu\*, James King, Arshdeep Singh, Eng Siong Chng, Mark D. Plumbley, Wenwu Wang.
- ``INTERSPEECH 2022`` [Rainbow Keywords: Efficient Incremental Learning for Online Spoken Keyword Spotting](https://www.isca-archive.org/interspeech_2022/xiao22_interspeech.pdf), **Yang Xiao**, Nana Hou, Eng Siong Chng.

## Domain adaptation for Speech / Audio
- ``INTERSPEECH 2025`` [AdaKWS: Towards Robust Keyword Spotting with Test-Time Adaptation](https://www.isca-archive.org/interspeech_2025/xiao25b_interspeech.pdf), **Yang Xiao**, Tianyi Peng, Yanghao Zhou, Rohan Kumar Das.
- ``APSIPA ASC 2025`` [DG-SED: Domain Generalization for Sound Event Detection with Heterogeneous Training Data](https://arxiv.org/abs/2407.03654), **Yang Xiao**, Han Yin, Jisheng Bai, Rohan Kumar Das.
- ``DCASE 2024`` [WildDESED: An LLM-Powered Dataset for Wild Domestic Environment Sound Event Detection System](https://arxiv.org/pdf/2407.03656.pdf), **Yang Xiao**, Rohan Kumar Das.


## Others
### 2025
- ``INTERSPEECH 2025`` [TF-Mamba: A Time-Frequency Network for Sound Source Localization](https://www.isca-archive.org/interspeech_2025/xiao25_interspeech.pdf), **Yang Xiao**, Rohan Kumar Das.
- ``SPSC 2025``[Multilingual Source Tracing of Speech Deepfakes: A First Benchmark](https://arxiv.org/pdf/2508.04143), Xi Xuan, **Yang Xiao**, Rohan Kumar Das, Tomi Kinnunen.
- ``APSIPA ASC 2025`` [RawTFNet: A Lightweight CNN Architecture for Speech Anti-spoofing](https://arxiv.org/pdf/2507.08227), **Yang Xiao**, Ting Dang, Rohan Kumar Das.

### Before 2024
- ``INTERSPEECH 2023`` [Small Footprint Multi-channel Network for Keyword Spotting with Centroid Based Awareness](https://www.isca-archive.org/interspeech_2023/ng23b_interspeech.pdf), Dianwen Ng, **Yang Xiao**, Jia Qi Yip, Zhao Yang, Biao Tian, Qiang Fu, Eng Siong Chng, Bin Ma.

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2025.07* ISCA (International Speech Communication Association) Grant, Interspeech, Rotterdam
- *2025.03* Melbourne Research Scholarship, University of Melbourne

