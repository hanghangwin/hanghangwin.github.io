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

I'm a second year M.Eng. student at CQUPT, Chongqing, China, working toward the M.Eng. degree in Information and Communication Engineering supervised by Prof. [Xiaoge Huang](https://faculty.cqupt.edu.cn/huangxg/zh_CN/index.htm). I received my B.Eng degree in Communication Engineering from Shanghai Maritime University, Shanghai, China, in 2021. My current research interests are federated learning, edge computing network, blockchain, Internet of Vehicles and automatic driving.

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

-	Xiaoge Huang, **Yuhang Wu**, Chengchao Liang, Qianbin Chen, and Jie Zhang, "Distance-Aware Hierarchical Federated Learning in Blockchain-enabled Edge Computing Network," in **IEEE Internet of Things Journal**, doi: 10.1109/JIOT.2023.3279983. (JCR: Q1, IF: 10.6, 1st (supervisor), Early Access)  [[Website]](https://ieeexplore.ieee.org/document/10167763)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE WCSP 2022</div><img src='images/BHCFL-view.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	Xiaoge Huang, **Yuhang Wu**, Zhi Chen, Qianbin Chen, and Jie Zhang, "Blockchain-enabled Edge Computing Framework for Hierarchic Cluster-based Federated Learning," in 2022 14th International Conference on Wireless Communications and Signal Processing (**WCSP**), Nanjing, China, 2022, pp. 33-37. (1st (supervisor), Published)  [[Website]](https://ieeexplore.ieee.org/document/10039121)

</div>
</div>

<span style="color: #00369f;">**Submited**</span>
- **Yuhang Wu**, Xiaoge Huang, Hongbo Yin, Chengchao Liang, and Qianbin Chen, "DAG Blockchain-based Personalized Federated Mutual Learning in Internet of Vehicles," Submited to Journal of Electronics & Information Technology, 2023. [[Techrxiv]](https://www.techrxiv.org/articles/preprint/DAG_Blockchain-based_Personalized_Federated_Mutual_learning_in_Internet_of_Vehicles/23757408)

<span style="color: #00369f;">**Patents**</span>
- Xiaoge Huang, **Yuhang Wu**, Hongbo Yin, "A Blockchain-enabled Distributed Intelligent for Assisting Autonomous Driving Method", Chinese Patent, No. 202310562721.0, 2023.
- Xiaoge Huang, **Yuhang Wu**, Hongbo Yin, "A Blockchain-enabled Hierarchical Federated Learning Method", Chinese Patent, No. 202210980496.8, 2022.
- Xiaoge Huang, Hongbo Yin, **Yuhang Wu**, "A Blockchain-Based Secure Data Sharing Method in Internet of Vehicles", No. 202310636636.4, 2023.
- Xiaoge Huang, Hongbo Yin, **Yuhang Wu**, "A Blockchain-Based Asynchronous Federated Learning Method in Internet of Vehicles" , No. 202210916511.2, 2022.
- 
<span class='anchor' id='-Researches'></span>

Researches
======
## <span style="color: #00369f;">1.Blockchain-enabled HFL</span>
<div class='paper-box-plus'><div class='paper-box-video'><video src='videos/WeBASE-video.mp4' alt="sym" width="100%" controls></video></div>
<div class='paper-box-text' markdown="1">
<b>Blockchain-enabled HFL</b>
</div>
</div>
The video shown a blockchain verification platform developed based on [WeBASE](https://github.com/WeBankBlockchain/WeBASE) and [FISCO-BCOS](https://github.com/FISCO-BCOS/FISCO-BCOS) provided by the WeBankBlockchain team. This platform is designed to verify and visualize transactions within the blockchain, recording the edge and global model updated information for blockchain-enable hierarchical federated learning (HFL).

## <span style="color: #00369f;">2.DAG blockchain-based FL</span>
<div class='paper-box-plus'><div class='paper-box-video'><video src='videos/DAG-view-fast.mp4' alt="sym" width="100%" controls></video></div>
<div class='paper-box-text' markdown="1">
<b>DAG blockchain-based FL</b>
</div>
</div>
The video shown a platform for recording the process of transaction verification and model training in directed acyclic graph (DAG) blockchain-based federated learning.  The execution logic of the platform was developed using the pySimuFL provided by Dr. Cao in [DAG-FL](https://arxiv.org/abs/2104.13092), while the presentation of information is based on the [Dash](https://github.com/plotly/dash) repositories. The code is accessible in [DashDAGView](https://github.com/hanghangwin/DashDAGView).

## <span style="color: #00369f;">3.FL for automatic driving</span>
<div class='paper-box-plus'><div class='paper-box-video'><video src='videos/CARLA-easy-view.mp4' alt="sym" width="100%" controls></video></div>
<div class='paper-box-text' markdown="1">
<b>CARLA simulation</b>
</div>
</div>
The video shown an automatic driving simulation developed by the [CARLA team](https://github.com/carla-simulator). Currently, it enables simple environment construction and control of pedestrians and vehicles. In future research, the simulation will be utilized to verify the performance of federated learning in assisting automatic driving.
 
<span class='anchor' id='-Projects'></span>

Projects
======
- *2021.09 - 2023.12* **National Natural Science Foundation of China** (No. 61831002): Dynamic Collaborative Theory and Key Technologies for Fog-based Wireless Access 				Networks Targeting Intelligent Services
  - Responsible for designing the blockchain-enabled hierarchical federated learning algorithm.
  - Responsible for building the WeBASE Platform for visualizing transaction data in blockchain.
- *2020.04 - 2021.04* **National Training Program of Innovation for Undergraduates** (No. 202010254185): Forwarding Device for Marine Navigation Informations [[Website]](http://gjcxcy.bjtu.edu.cn/NewJTItemListForStudentDetail.aspx?ItemNo=677802&year=2021&type=student&IsLXItem=0)
  - Preside over designing the NMEA-0183 communication protocol parsing algorithm.
  - Preside over developing  the one-to-many transmission mechanism based on LoRa technology.

<span class='anchor' id='-Honors'></span>

Honors
======
- ***2023***
  - The 14th LanqiaoCup Python Programming Contest, **Provincial First Prize** <!--[[Certificate]](http://hanghangwin.github.io/files/Honors/2023/2023lanqiaoR1.jpg)-->
  - The 10th DatangCup Communication Technologies Contest, **Provincial Third Prize** <!--[[Certificate]](http://hanghangwin.github.io/files/Honors/2023/2023Datang.pdf)-->
- ***2022***
  - **Outstanding** Academic Scholarship of Master's Second Year <!--[[Certificate]](http://hanghangwin.github.io/files/Honors/2022/ScholarshipS.jpg)-->
  - The 13th LanqiaoCup Python Programming Contest, **National Third Prize** <!--[[Certificate]](http://hanghangwin.github.io/files/Honors/2022/2022lanqiaoR3Plus.jpg)-->
  - The 12th MathorCup Mathematical Contest in Modeling, **National Second Prize** <!--[[Certificate]](http://hanghangwin.github.io/files/Honors/2022/2022MathorCup.pdf)-->
  - The 3th HuashuCup Mathematical Contest in Modeling, **National Third Prize** <!--[[Certificate]](http://hanghangwin.github.io/files/Honors/2022/2022HuaShu.pdf)-->
- ***2021***
  - **Outstanding** Academic Scholarship of Master's First Year <!--[[Certificate]](http://hanghangwin.github.io/files/Honors/2021/ScholarshipS.jpg)-->
  - The 11th Asia and Pacific Mathematical Contest in Modeling (APMCM), **International Second Prize** <!--[[Certificate]](http://hanghangwin.github.io/files/Honors/2021/2021APMCM.pdf)-->
- ***2020***
  - 2020 Mathematical Contest in Modeling (MCM), **International Honorable Mention** <!--[[Certificate]](http://hanghangwin.github.io/files/Honors/2020/2020MCM.pdf)-->
- ***2019***
  - The 9th Asia and Pacific Mathematical Contest in Modeling (APMCM), **International Second Prize** <!--[[Certificate]](http://hanghangwin.github.io/files/Honors/2019/2019APMCM.pdf)-->
  - The 9th MathorCup Mathematical Contest in Modeling, **National Third Prize** <!--[[Certificate]](http://hanghangwin.github.io/files/Honors/2019/2019MathorCup.pdf)-->
  - The 10th LanqiaoCup C/C++ Programming Contest, **Provincial Second Prize** <!--[[Certificate]](http://hanghangwin.github.io/files/Honors/2019/2019lanqiao.jpg)-->

