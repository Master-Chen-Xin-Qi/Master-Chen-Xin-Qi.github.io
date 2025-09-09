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

# 👨‍💻 About me

I am Xinqi Chen, a fourth-year Ph.D student in Department of Computer Science and Engineering at [Shanghai Jiao Tong University](https://en.sjtu.edu.cn/), advised by Professor [Guangtao Xue](https://scholar.google.com/citations?user=vTC9TSQAAAAJ&hl=zh-CN&oi=ao), Professor [Erci Xu](https://scholar.google.com/citations?user=7Yc6A1QAAAAJ&hl=zh-CN&oi=ao), and Professor [Yi-Chao Chen](https://scholar.google.com/citations?user=LdNIR90AAAAJ). Since July 2022, I have served as a research intern in the Alibaba Innovative Research (AIR) program at Alibaba Cloud, where I collaborated with Pangu AutoOps, Elastic Block Storage, and PolarDB teams. Currently, I am a visiting student in the Department of Computer Science and Engineering at [The Chinese University of Hong Kong](https://www.cuhk.edu.hk/english/index.html), advised by Professor [Patrick P. C. Lee](https://scholar.google.com.hk/citations?user=gyRtVVEAAAAJ&hl=zh-CN&oi=ao).

My current research interests focus on scheduling and resource management in modern storage systems and LLM systems, as well as reliability for systems. Specifically, I have been working on designing efficient schedulers and data prefetchers for key components of distributed storage systems, with the goal of optimizing performance and resource utilization. Before that, I was actively engaged in the research of mobile computing and wireless sensing. My work in this area centered on security-related topics, including current signal attacks on power supplies and electromagnetic side-channel attacks, where I explored vulnerabilities of mobile devices.
<!-- Find my CV [here](cv/resume.pdf). -->

# 📖 Educations

- *2021.09 - 2026.06 (Expected)*, Shanghai Jiao Tong University, Computer Science (CS)
- *2017.08 - 2021.06*, Sun Yat-Sen University, Electronic Engineering (EE)

# 🔥 News

- *2025.08*: &nbsp;🎉 Our paper ***Omar*** is accepted by **ACM EuroSys 2026**!
- *2024.12*: &nbsp;🎉 Our paper ***MasterPlan*** is accepted by **ACM TACO**!
- *2024.08*: &nbsp;🎉 Our paper ***Hey Hey, My My*** is accepted by **ACM EuroSys 2025**!

# 📝 Publications

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

- <span style="font-weight: bold;">[EuroSys'26] Scheduling Cloud Block Storage Proactively and Reactively with Omar</span>

    **<u>Xinqi Chen</u>**, Weidong Zhang, Zhongyu Wang, Erci Xu, Dong Wu, Xiaolu Zhang, Haonan Wu, Yaheng Song, Chaolei Hu, Lijun Ding, Guangtao Xue, Patrick P. C. Lee.

    Proceedings of the 21<sup>st</sup> European Conference on Computer Systems, <span style="color: #de1f00; font-weight: bold;">CCF-A</span>. (Accept rate: 79/467 = 16.9%, spring cycle)

- <span style="font-weight: bold;">[TACO'25] MasterPlan: A Reinforcement Learning Based Scheduler for Archive Storage</span>
  
    **<u>Xinqi Chen</u>**, Erci Xu, Dengyao Mo, Ruiming Lu, Haonan Wu, Dian Ding, Guangtao Xue.

    ACM Transaction on Architecture and Code Optimization 22 (1) 2025, <span style="color: #de1f00; font-weight: bold;">CCF-A</span>.

- <span style="font-weight: bold;">[TMC'25] MagPrint++: Continuous User Fingerprinting On Mobile Devices Using Electromagnetic Signals</span>

    Lanqing Yang\*, **<u>Xinqi Chen</u>\***, Hao Pan, Yi-Chao Chen, Guangtao Xue, Zechen Li, Yiheng Bian, Zhen Chen, Dian Ding, Linghe Kong, Jiadi Yu, Feng Lyu, Minglu Li, Ziyu Shen, Bo Zhang **(\*Co-first)**.

    IEEE Transaction on Mobile Computing, <span style="color: #de1f00; font-weight: bold;">CCF-A</span>.

- <span style="font-weight: bold;">[EuroSys'25] Hey Hey, My My, Skewness Is Here to Stay: Challenges and Opportunities in Cloud Block Store Traffic</span>

    Haonan Wu, Erci Xu, Ligang Wang, Yuandong Hong, Changsheng Niu, Bo Shi, Lingjun Zhu, Jinnian He, Dong Wu, Weidong Zhang, Qiuping Wang, Changhong Wang, **<u>Xinqi Chen</u>**, Guangtao Xue, Yi-Chao Chen, Dian Ding.

    Proceedings of the 20<sup>th</sup> European Conference on Computer Systems, <span style="color: #de1f00; font-weight: bold;">CCF-A</span>. (Accept rate: 30/367 = 8.2%, spring cycle)

- <span style="font-weight: bold;">[Security'23] Remote Attacks on Speech Recognition Systems Using Sound from Power Supply</span>

    Lanqing Yang, **<u>Xinqi Chen</u>**, Xiangyong Jian, Leping Yang, Yijie Li, Qianfei Ren, Yi-Chao Chen, Guangtao Xue, Xiaoyu Ji.

    Proceedings of the 32<sup>nd</sup> USENIX Security Symposium, <span style="color: #de1f00; font-weight: bold;">CCF-A</span>.

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships

- *2025.09 - 2026.06*, Alibaba Cloud, PolarDB Team, Hangzhou, China.
- *2025.03 - 2026.03*, The Chinese University of Hong Kong, Department of Computer Science and Engineering, Hong Kong, China.
- *2023.09 - 2025.09*, Alibaba Cloud, Elastic Block Storage Team, Hangzhou, China.
- *2022.07 - 2023.09*, Alibaba Cloud, Pangu AutoOps Team, Hangzhou, China.
- *2020.10 - 2021.01*, Pudu Robotics, Algorithm Development Team, Shenzhen, China.

# 👻 Misc

- Services: ICIC 2024 (Reviewer), ATC 2025、EuroSys 2025、NSDI 2025、FAST 2025、ICDCS 2025 (Help to review)
- Hobbies: Basketball, Music
