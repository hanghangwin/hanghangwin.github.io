---
permalink: /
title: "Biography"
excerpt: "About me"
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

<span class='anchor' id='-Biography'></span>

I'm a final year M.Eng. student at CQUPT, Chongqing, China, working toward the M.Eng. degree in Information and Communication Engineering supervised by Prof. [Xiaoge Huang](https://faculty.cqupt.edu.cn/huangxg/zh_CN/index.htm). I received my B.Eng degree in Communication Engineering from Shanghai Maritime University, Shanghai, China, in 2021. My current research interests are federated learning, edge computing network, blockchain, Internet of Vehicles and autonomous driving.

<span class='anchor' id='-Education'></span>

Education
======
- *2021.09 - 2024.06*, Chongqing University of Posts and Telecommunications, Information and communication engineering, M.Eng
- *2017.09 - 2021.06*, Shanghai Maritime University, Communication engineering, B.Eng

<span class='anchor' id='-Publications'></span>

Publications
======
<span style="color: #00369f;">**Published**</span>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE IoTJ</div><img src='images/DAHFL-view.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	Xiaoge Huang, **Yuhang Wu**, Chengchao Liang, Qianbin Chen, and Jie Zhang, "Distance-Aware Hierarchical Federated Learning in Blockchain-enabled Edge Computing Network," in **IEEE Internet of Things Journal**, vol. 10, no. 21, pp. 19163-19176, 1 Nov.1, 2023, doi: 10.1109/JIOT.2023.3279983. (JCR: Q1, IF: 10.6, first student author)  [[Website]](https://ieeexplore.ieee.org/document/10167763)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE WCSP 2022</div><img src='images/BHCFL-view.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	Xiaoge Huang, **Yuhang Wu**, Zhi Chen, Qianbin Chen, and Jie Zhang, "Blockchain-enabled Edge Computing Framework for Hierarchic Cluster-based Federated Learning," in 2022 14th International Conference on Wireless Communications and Signal Processing (**WCSP**), Nanjing, China, 2022, pp. 33-37. first student author)  [[Website]](https://ieeexplore.ieee.org/document/10039121)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE WCSP 2022</div><img src='images/MRASL-view.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- Hongbo Yin, Xiaoge Huang, **Yuhang Wu**, Chengchao Liang, and Qianbin Chen, "Multi-Region Asynchronous Swarm Learning for Data Sharing in Large-Scale Internet of Vehicles," in **IEEE Communications Letters**, vol. 27, no. 11, pp. 2978-2982, Nov. 2023, doi: 10.1109/LCOMM.2023.3314662. (JCR: Q1, IF: 4.1, second student author)  [[Website]](https://ieeexplore.ieee.org/abstract/document/10247620)

</div>
</div>

<span style="color: #00369f;">**Submited**</span>
- Xiaoge Huang, **Yuhang Wu**, Hongbo Yin, Chengchao Liang, and Qianbin Chen, "DAG Blockchain-based Personalized Federated Mutual Learning in Internet of Vehicles," Submited to Journal of Electronics & Information Technology, 2023. [[Techrxiv]](https://www.techrxiv.org/articles/preprint/DAG_Blockchain-based_Personalized_Federated_Mutual_learning_in_Internet_of_Vehicles/23757408)

<span style="color: #00369f;">**Patents**</span>
- Xiaoge Huang, **Yuhang Wu**, Hongbo Yin, "A Blockchain-enabled Distributed Intelligent for Assisting Autonomous Driving Method", Chinese Patent, No. 202310562721.0, 2023.
- Xiaoge Huang, **Yuhang Wu**, Hongbo Yin, "A Blockchain-enabled Hierarchical Federated Learning Method", Chinese Patent, No. 202210980496.8, 2022.
- Xiaoge Huang, Hongbo Yin, **Yuhang Wu**, "A Blockchain-Based Secure Data Sharing Method in Internet of Vehicles", No. 202310636636.4, 2023.
- Xiaoge Huang, Hongbo Yin, **Yuhang Wu**, "A Blockchain-Based Asynchronous Federated Learning Method in Internet of Vehicles" , No. 202210916511.2, 2022.
- 
<span class='anchor' id='-Researches'></span>

Researches
======
## <span style="color: #00369f;">1.Blockchain-enabled hierarchical federated learning</span>
<div class='paper-box-plus'><div class='paper-box-video'><video src='videos/WeBASE-video.mp4' alt="sym" width="100%" controls></video></div>
<div class='paper-box-text' markdown="1">
<b>Blockchain-enabled hierarchical federated learning</b>
</div>
</div>
The video shown a blockchain verification platform developed based on [WeBASE](https://github.com/WeBankBlockchain/WeBASE) and [FISCO-BCOS](https://github.com/FISCO-BCOS/FISCO-BCOS) provided by the WeBankBlockchain team. This platform is designed to verify and visualize transactions within the blockchain, recording the edge and global model updated information for blockchain-enable hierarchical federated learning (HFL).

## <span style="color: #00369f;">2.DAG blockchain-based federated learning</span>
<div class='paper-box-plus'><div class='paper-box-video'><video src='videos/DAG-view-fast.mp4' alt="sym" width="100%" controls></video></div>
<div class='paper-box-text' markdown="1">
<b>DAG blockchain-based federated learning</b>
</div>
</div>
The video shown a platform for recording the process of transaction verification and model training in directed acyclic graph (DAG) blockchain-based federated learning.  The execution logic of the platform was developed using the pySimuFL provided by Dr. Cao in [DAG-FL](https://arxiv.org/abs/2104.13092), while the presentation of information is based on the [Dash](https://github.com/plotly/dash) repositories. The code is accessible in [DashDAGView](https://github.com/hanghangwin/DashDAGView).

## <span style="color: #00369f;">3.Federated learning for autonomous driving</span>
<div class='paper-box-plus'><div class='paper-box-video'><video src='videos/TinyLong.mp4' alt="sym" width="100%" controls></video></div>
<div class='paper-box-text' markdown="1">
<b>Federated learning for autonomous driving</b>
</div>
</div>
The video shown an autonomous driving simulation developed by the [CARLA team](https://github.com/carla-simulator). 
This project is inspired by [Idrees Razak's work](https://github.com/idreesshaikh/Autonomous-Driving-in-Carla-using-Deep-Reinforcement-Learning), and I added federated learning as behaviour clonong for pre-training of Actor Network. This video is the later training stage of PPO for autonomous driving.

<span class='anchor' id='-Projects'></span>

Projects
======
- *2021.09 - 2023.12* **National Natural Science Foundation of China** (No. 61831002): Dynamic Collaborative Theory and Key Technologies for Fog-based Wireless Access 				Networks Targeting Intelligent Services
  - Responsible for designing the blockchain-enabled hierarchical federated learning algorithm.
  - Responsible for building the WeBASE Platform for visualizing transaction data in blockchain.
- *2020.04 - 2021.04* **National Training Program of Innovation for Undergraduates** (No. 202010254185): Forwarding Device for Marine Navigation Informations [[Website]](http://gjcxcy.bjtu.edu.cn/NewJTItemListForStudentDetail.aspx?ItemNo=677802&year=2021&type=student&IsLXItem=0)
  - Direct the design of the NMEA-0183 communication protocol parsing algorithm.
  - Direct the develop of the one-to-many transmission mechanism based on LoRa technology.

<span class='anchor' id='-Honors'></span>

Honors
======
- ***2023***
  - **National Scholarship** for postgraduate students
  - Chongqing 10th DatangCup Communication Technologies Contest, **Third Prize**
- ***2022***
  - **First Class** Academic Scholarship of Master's Second Year
  - National 13th LanqiaoCup Python Programming Contest, **Third Prize**
  - National 12th MathorCup Mathematical Contest in Modeling, **Second Prize**
  - National 3th HuashuCup Mathematical Contest in Modeling, **Third Prize**
- ***2021***
  - **First Class** Academic Scholarship of Master's First Year
  - International 11th Asia and Pacific Mathematical Contest in Modeling (APMCM), **Second Prize**
- ***2020***
  - International 2020 Mathematical Contest in Modeling (MCM), **Honorable Mention**

