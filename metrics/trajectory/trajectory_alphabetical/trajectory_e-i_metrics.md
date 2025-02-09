<a name=top></a>
<a name=top></a>
---
<a href=../../../README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../datasets/datasets.md#top><l style="font-size:30px">Datasets</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Metrics</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
[Home](../../metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Video](../../video/video_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Action](../../action/action_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Trajectory&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Motion](../../motion/motion_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Other](../../other/other_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[Home](../trajectory_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Alphabetical&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Ranking](../trajectory_ranking/trajectory_ranking_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[A-D](trajectory_a-d_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;E-I&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[J-Z](trajectory_j-z_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
<h2>E-I <small>[rank]</small></h2> 
<ul><a name=ece></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Expected Calibration Error (ECE)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Ivanovic et al., "Expanding the Deployment Envelope of Behavior Prediction via Adaptive Meta-Learning", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10161155>paper</a> <a href=https://arxiv.org/pdf/2209.11820.pdf>arxiv</a> <a href=https://github.com/ NVlabs/adaptive-prediction.>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ece">ECE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ivanovic_2023_ICRA,
    author = "Ivanovic, Boris and Harrison, James and Pavone, Marco",
    title = "Expanding the Deployment Envelope of Behavior Prediction via Adaptive Meta-Learning",
    booktitle = "ICRA",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Jain et al., "Discrete Residual Flow For Probabilistic Pedestrian Behavior Prediction", CoRL, 2019.</em></strong> <a href=http://proceedings.mlr.press/v100/jain20a/jain20a.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.08041.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ece">ECE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jain_2019_CORL,
    author = "Jain, Ajay and Casas, Sergio and Liao, Renjie and Xiong, Yuwen and Feng, Song and Segal, Sean and Urtasun, Raquel",
    title = "Discrete Residual Flow For Probabilistic Pedestrian Behavior Prediction",
    booktitle = "CoRL",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=ecfl></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Environment Collision-Free Likelihood (ECFL)</strong><small> [22]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Lee et al., "MUSE-VAE: Multi-Scale VAE for Environment-Aware Long Term Trajectory Prediction", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Lee_MUSE-VAE_Multi-Scale_VAE_for_Environment-Aware_Long_Term_Trajectory_Prediction_CVPR_2022_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#kde">KDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ecfl">ECFL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lee_2022_CVPR,
    author = "Lee, Mihee and Sohn, Samuel S. and Moon, Seonghyeon and Yoon, Sejong and Kapadia, Mubbasir and Pavlovic, Vladimir",
    title = "{MUSE-VAE}: Multi-Scale {VAE} for Environment-Aware Long Term Trajectory Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=ed></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Euclidean Distance (ED)</strong><small> [8]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Wang et al., "Trajectory and Sway Prediction Towards Fall Prevention", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10161361>paper</a> <a href=https://arxiv.org/pdf/2209.11886.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2023_ICRA,
    author = "Wang, Weizhuo and Raitor, Michael and Collins, Steve and Liu, C. Karen and Kennedy, Monroe",
    title = "Trajectory and Sway Prediction Towards Fall Prevention",
    booktitle = "ICRA",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Li et al., "Efficient Game-Theoretic Planning With Prediction Heuristic for Socially-Compliant Autonomous Driving", RAL, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9830854>paper</a> <a href=https://arxiv.org/pdf/2207.03673.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Li_2022_RAL,
    author = "Li, Chenran and Trinh, Tu and Wang, Letian and Liu, Changliu and Tomizuka, Masayoshi and Zhan, Wei",
    journal = "RAL",
    title = "Efficient Game-Theoretic Planning With Prediction Heuristic for Socially-Compliant Autonomous Driving",
    volume = "7",
    number = "4",
    pages = "10248--10255",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Mitjans et al., "Koopman Pose Predictions for Temporally Consistent Human Walking Estimations", IROS, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9981204>paper</a> <a href=https://arxiv.org/pdf/2205.02737.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mitjans_2022_IROS,
    author = "Mitjans, Marc and Levine, David M. and Awad, Louis N. and Tron, Roberto",
    booktitle = "IROS",
    title = "Koopman Pose Predictions for Temporally Consistent Human Walking Estimations",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Tang et al., "Collaborative Uncertainty in Multi-Agent Trajectory Forecasting", NeurIPS, 2021.</em></strong> <a href=https://papers.nips.cc/paper/2021/file/31ca0ca71184bbdb3de7b20a51e88e90-Paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2110.13947.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#kld">KLD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#l1">L1</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tang_2021_NeurIPS,
    author = "Tang, Bohan and Zhong, Yiqi and Neumann, Ulrich and Wang, Gang and Chen, Siheng and Zhang, Ya",
    booktitle = "NeurIPS",
    title = "Collaborative Uncertainty in Multi-Agent Trajectory Forecasting",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Walters et al., "Trajectory Prediction using Equivariant Continuous Convolution", ICLR, 2021.</em></strong> <a href=https://openreview.net/pdf?id=J8_GttYLFgr>paper</a> <a href=https://arxiv.org/pdf/2010.11344.pdf>arxiv</a> <a href=https://github.com/Rose-STL-Lab/ECCO>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#trajnet++">Trajnet++</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Walters_2021_ICLR,
    author = "Walters, Robin and Li, Jinxi and Yu, Rose",
    booktitle = "ICLR",
    title = "Trajectory Prediction using Equivariant Continuous Convolution",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Phillips et al., "Deep Multi-Task Learning for Joint Localization, Perception, and Prediction", CVPR, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Phillips_Deep_Multi-Task_Learning_for_Joint_Localization_Perception_and_Prediction_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2101.06720.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#tcr">TCR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Phillips_2021_CVPR,
    author = "Phillips, John and Martinez, Julieta and Barsan, Ioan Andrei and Casas, Sergio and Sadat, Abbas and Urtasun, Raquel",
    title = "Deep Multi-Task Learning for Joint Localization, Perception, and Prediction",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhang et al., "Foot Placement Prediction for Assistive Walking by Fusing Sequential 3D Gaze and Environmental Context", RAL, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9362175>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Zhang_2021_RAL,
    author = "Zhang, Kuangen and Liu, Haiyuan and Fan, Zixuan and Chen, Xinxing and Leng, Yuquan and de Silva, Clarence W. and Fu, Chenglong",
    journal = "RAL",
    title = "Foot Placement Prediction for Assistive Walking by Fusing Sequential {3D} Gaze and Environmental Context",
    year = "2021",
    volume = "6",
    number = "2",
    pages = "2509-2516"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhu et al., "Learning Interaction-Aware Trajectory Predictions for Decentralized Multi-Robot Motion Planning in Dynamic Environments", RAL, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9360433>paper</a> <a href=https://arxiv.org/pdf/2102.05382.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Zhu_2021_RAL,
    author = "Zhu, Hai and Claramunt, Francisco Martinez and Brito, Bruno and Alonso-Mora, Javier",
    journal = "RAL",
    title = "Learning Interaction-Aware Trajectory Predictions for Decentralized Multi-Robot Motion Planning in Dynamic Environments",
    year = "2021",
    volume = "6",
    number = "2",
    pages = "2256-2263"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Ankit et al., "Multi-Variable State Prediction: HMM Based Approach for Real-Time Trajectory Prediction", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636556>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ankit_2021_IROS,
    author = "Ankit and Narayanan, Karthik and Ghosh, Dibyendu and Honkote, Vinayak and Nandakumar, Ganeshram",
    booktitle = "IROS",
    title = "Multi-Variable State Prediction: {HMM} Based Approach for Real-Time Trajectory Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Ji et al., "Model-Based Trajectory Prediction and Hitting Velocity Control for a New Table Tennis Robot", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636000>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ji_2021_IROS,
    author = "Ji, Yunfeng and Hu, Xiaoyi and Chen, Yutao and Mao, Yue and Wang, Gang and Li, Qingdu and Zhang, Jianwei",
    booktitle = "IROS",
    title = "Model-Based Trajectory Prediction and Hitting Velocity Control for a New Table Tennis Robot",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Laddha et al., "RV-FuseNet: Range View Based Fusion of Time-Series LiDAR Data for Joint 3D Object Detection and Motion Forecasting", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636083>paper</a> <a href=https://arxiv.org/pdf/2005.10863.pdf?ref=https://githubhelp.com>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Laddha_2021_IROS,
    author = "Laddha, Ankit and Gautam, Shivam and Meyer, Gregory P. and Vallespi-Gonzalez, Carlos and Wellington, Carl K.",
    booktitle = "IROS",
    title = "{RV-FuseNet}: Range View Based Fusion of Time-Series {LiDAR} Data for Joint {3D} Object Detection and Motion Forecasting",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Yu et al., "Neural Motion Prediction for In-flight Uneven Object Catching", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9635983>paper</a> <a href=https://arxiv.org/pdf/2103.08368.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yu_2021_IROS,
    author = "Yu, Hongxiang and Guo, Dashun and Yin, Huan and Chen, Anzhe and Xu, Kechun and Chen, Zexi and Wang, Minhang and Tan, Qimeng and Wang, Yue and Xiong, Rong",
    booktitle = "IROS",
    title = "Neural Motion Prediction for In-flight Uneven Object Catching",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Su et al., "Temporally-Continuous Probabilistic Prediction using Polynomial Trajectory Parameterization", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636751>paper</a> <a href=https://arxiv.org/pdf/2011.00399.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Su_2021_IROS_2,
    author = "Su, Zhaoen and Wang, Chao and Cui, Henggang and Djuric, Nemanja and Vallespi-Gonzalez, Carlos and Bradley, David",
    booktitle = "IROS",
    title = "Temporally-Continuous Probabilistic Prediction using Polynomial Trajectory Parameterization",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Djuric et al., "Uncertainty-aware Short-term Motion Prediction of Traffic Actors for Autonomous Driving", WACV, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Djuric_Uncertainty-aware_Short-term_Motion_Prediction_of_Traffic_Actors_for_Autonomous_Driving_WACV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1808.05819.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Djuric_2020_WACV,
    author = "Djuric, Nemanja and Radosavljevic, Vladan and Cui, Henggang and Nguyen, Thi and Chou, Fang-Chieh and Lin, Tsung-Han and SINGH, NITIN and Schneider, Jeff",
    title = "Uncertainty-aware Short-term Motion Prediction of Traffic Actors for Autonomous Driving",
    booktitle = "WACV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Casas et al., "SpAGNN: Spatially-Aware Graph Neural Networks for Relational Behavior Forecasting from Sensor Data", ICRA, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9196697>paper</a> <a href=https://arxiv.org/pdf/1910.08233.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Casas_2020_ICRA,
    author = "Casas, S. and Gulino, C. and Liao, R. and Urtasun, R.",
    booktitle = "ICRA",
    title = "{SpAGNN}: Spatially-Aware Graph Neural Networks for Relational Behavior Forecasting from Sensor Data",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Cui et al., "Deep Kinematic Models for Kinematically Feasible Vehicle Trajectory Predictions", ICRA, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9197560>paper</a> <a href=https://arxiv.org/pdf/1908.00219.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cui_2020_ICRA,
    author = "Cui, H. and Nguyen, T. and Chou, F. -C. and Lin, T. -H. and Schneider, J. and Bradley, D. and Djuric, N.",
    booktitle = "ICRA",
    title = "Deep Kinematic Models for Kinematically Feasible Vehicle Trajectory Predictions",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Tekden et al., "Belief Regulated Dual Propagation Nets for Learning Action Effects on Groups of Articulated Objects", ICRA, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9196878>paper</a> <a href=https://arxiv.org/pdf/1909.03785.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tekden_2020_ICRA,
    author = "Tekden, A. E. and Erdem, A. and Erdem, E. and Imre, M. and Seker, M. Y. and Ugur, E.",
    booktitle = "ICRA",
    title = "Belief Regulated Dual Propagation Nets for Learning Action Effects on Groups of Articulated Objects",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Gomez-Gonzalez et al., "Real Time Trajectory Prediction Using Deep Conditional Generative Models", RAL, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/8957482>paper</a> <a href=https://arxiv.org/pdf/1909.03895.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Gonzalez_2020_RAL,
    author = "Gomez-Gonzalez, S. and Prokudin, S. and Schölkopf, B. and Peters, J.",
    journal = "RAL",
    title = "Real Time Trajectory Prediction Using Deep Conditional Generative Models",
    year = "2020",
    volume = "5",
    number = "2",
    pages = "970-976"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Carvalho et al., "Long-Term Prediction Of Motion Trajectories Using Path Homology Clusters", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8968125>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eifp">EIFP</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Carvalho_2019_IROS,
    author = "Carvalho, J Frederico and Vejdemo-Johansson, Mikael and Pokorny, Florian T and Kragic, Danica",
    booktitle = "IROS",
    title = "Long-Term Prediction Of Motion Trajectories Using Path Homology Clusters",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Bhattacharyya et al., "Accurate and Diverse Sampling of Sequences based on a “best of many” Sample Objective", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Bhattacharyya_Accurate_and_Diverse_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1806.07772.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#cll">CLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bhattacharyya_2018_CVPR_2,
    author = "Bhattacharyya, Apratim and Schiele, Bernt and Fritz, Mario",
    title = "Accurate and Diverse Sampling of Sequences based on a “best of many” Sample Objective",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Baumann et al., "Predicting Ego-Vehicle Paths From Environmental Observations With A Deep Neural Network", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8460704>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Baumann_2018_ICRA,
    author = "Baumann, U. and Guiser, C. and Herman, M. and Zollner, J. M.",
    booktitle = "ICRA",
    title = "Predicting Ego-Vehicle Paths From Environmental Observations With A Deep Neural Network",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Lee et al., "Robust Human Following By Deep Bayesian Trajectory Prediction For Home Service Robots", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8462969>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lee_2018_ICRA,
    author = "Lee, B. and Choi, J. and Baek, C. and Zhang, B.",
    booktitle = "ICRA",
    title = "Robust Human Following By Deep Bayesian Trajectory Prediction For Home Service Robots",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Pfeiffer et al., "A Data-Driven Model For Interaction-Aware Pedestrian Motion Prediction In Object Cluttered Environments", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8461157>paper</a> <a href=https://arxiv.org/pdf/1709.08528.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Pfeiffer_2018_ICRA,
    author = "Pfeiffer, M. and Paolo, G. and Sommer, H. and Nieto, J. and Siegwart, R. and Cadena, C.",
    booktitle = "ICRA",
    title = "A Data-Driven Model For Interaction-Aware Pedestrian Motion Prediction In Object Cluttered Environments",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Lee et al., "DESIRE: Distant Future Prediction In Dynamic Scenes With Interacting Agents", CVPR, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lee_DESIRE_Distant_Future_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1704.04394.pdf>arxiv</a> <a href=https://github.com/yadrimz/DESIRE>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#maxd">maxD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mined">minED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lee_2017_CVPR,
    author = "Lee, Namhoon and Choi, Wongun and Vernaza, Paul and Choy, Christopher B. and Torr, Philip H. S. and Chandraker, Manmohan",
    title = "{DESIRE}: Distant Future Prediction In Dynamic Scenes With Interacting Agents",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Karasev et al., "Intent-Aware Long-Term Prediction Of Pedestrian Motion", ICRA, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7487409>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Karasev_2016_ICRA,
    author = "Karasev, V. and Ayvaci, A. and Heisele, B. and Soatto, S.",
    booktitle = "ICRA",
    title = "Intent-Aware Long-Term Prediction Of Pedestrian Motion",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Pfeiffer et al., "Predicting Actions To Act Predictably: Cooperative Partial Motion Planning With Maximum Entropy Models", IROS, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7759329>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Pfeiffer_2016_IROS,
    author = "Pfeiffer, M. and Schwesinger, U. and Sommer, H. and Galceran, E. and Siegwart, R.",
    booktitle = "IROS",
    title = "Predicting Actions To Act Predictably: Cooperative Partial Motion Planning With Maximum Entropy Models",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Vo et al., "Augmenting Physical State Prediction Through Structured Activity Inference", ICRA, 2015.</em></strong> <a href=https://ieeexplore.ieee.org/document/7139262>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#tum_kitchen">TUM Kitchen</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Vo_2015_ICRA,
    author = "Vo, N. N. and Bobick, A. F.",
    booktitle = "ICRA",
    title = "Augmenting Physical State Prediction Through Structured Activity Inference",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Akbarzadeh et al., "Kernel Density Estimation For Target Trajectory Prediction", IROS, 2015.</em></strong> <a href=https://ieeexplore.ieee.org/document/7353858>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#mitt">MITT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#run_time">Run Time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Akbarzadeh_2015_IROS,
    author = "Akbarzadeh, V. and Gagné, C. and Parizeau, M.",
    booktitle = "IROS",
    title = "Kernel Density Estimation For Target Trajectory Prediction",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Schulz et al., "A Controlled Interactive Multiple Model Filter For Combined Pedestrian Intention Recognition And Path Prediction", ITSC, 2015.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/7313129>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#daimler_path">Daimler Path</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Schulz_2015_ITSC,
    author = "Schulz, Andreas and Stiefelhagen, Rainer",
    title = "A Controlled Interactive Multiple Model Filter For Combined Pedestrian Intention Recognition And Path Prediction",
    booktitle = "ITSC",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=emd></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Earth Mover's Distance (EMD)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Narayanan et al., "Divide-and-Conquer for Lane-Aware Diverse Trajectory Prediction", CVPR, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Narayanan_Divide-and-Conquer_for_Lane-Aware_Diverse_Trajectory_Prediction_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2104.08277.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cpi">CPI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#orr">ORR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#emd">EMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Narayanan_2021_CVPR,
    author = "Narayanan, Sriram and Moslemi, Ramin and Pittaluga, Francesco and Liu, Buyu and Chandraker, Manmohan",
    title = "Divide-and-Conquer for Lane-Aware Diverse Trajectory Prediction",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Makansi et al., "Overcoming Limitations of Mixture Density Networks: A Sampling and Fitting Framework for Multimodal Future Prediction", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Makansi_Overcoming_Limitations_of_Mixture_Density_Networks_A_Sampling_and_Fitting_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.03631.pdf>arxiv</a> <a href=https://github.com/lmb-freiburg/Multimodal-Future-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cpi">CPI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#emd">EMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Makansi_2019_CVPR,
    author = "Makansi, Osama and Ilg, Eddy and Cicek, Ozgun and Brox, Thomas",
    title = "Overcoming Limitations of Mixture Density Networks: A Sampling and Fitting Framework for Multimodal Future Prediction",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=entropy></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Entropy</strong><small> [22]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Kuo et al., "Trajectory Prediction with Linguistic Representations", ICRA, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/document/9811928>paper</a> <a href=https://arxiv.org/pdf/2110.09741.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#entropy">Entropy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kuo_2022_ICRA,
    author = "Kuo, Yen-Ling and Huang, Xin and Barbu, Andrei and McGill, Stephen G. and Katz, Boris and Leonard, John J. and Rosman, Guy",
    booktitle = "ICRA",
    title = "Trajectory Prediction with Linguistic Representations",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=epa></a>
<details close>
<summary><em><l style="font-size:20px"><strong>End-to-end Prediction Accuracy (EPA)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Yang et al., "Visual Point Cloud Forecasting enables Scalable Autonomous Driving", CVPR, 2024.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Yang_Visual_Point_Cloud_Forecasting_enables_Scalable_Autonomous_Driving_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2312.17655>arxiv</a> <a href=https://github.com/OpenDriveLab/ViDAR>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#epa">EPA</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yang_Visual_2024_CVPR,
    author = "Yang, Zetong and Chen, Li and Sun, Yanan and Li, Hongyang",
    title = "Visual Point Cloud Forecasting enables Scalable Autonomous Driving",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Gu et al., "ViP3D: End-to-End Visual Trajectory Prediction via 3D Agent Queries", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Gu_ViP3D_End-to-End_Visual_Trajectory_Prediction_via_3D_Agent_Queries_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2208.01582.pdf>arxiv</a> <a href=https://tsinghua-mars-lab.github.io/ViP3D/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#epa">EPA</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gu_2023_CVPR,
    author = "Gu, Junru and Hu, Chenxu and Zhang, Tianyuan and Chen, Xuanyao and Wang, Yilun and Wang, Yue and Zhao, Hang",
    title = "ViP3D: End-to-End Visual Trajectory Prediction via 3D Agent Queries",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=epe></a>
<details close>
<summary><em><l style="font-size:20px"><strong>End-Point Error (EPE)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Mahjourian et al., "Occupancy Flow Fields for Motion Forecasting in Autonomous Driving", RAL, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9713950>paper</a> <a href=https://arxiv.org/pdf/2203.03875>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#epe">EPE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Mahjourian_Occupancy_2022_RAL,
    author = "Mahjourian, Reza and Kim, Jinkyu and Chai, Yuning and Tan, Mingxing and Sapp, Ben and Anguelov, Dragomir",
    journal = "RAL",
    title = "Occupancy Flow Fields for Motion Forecasting in Autonomous Driving",
    year = "2022",
    volume = "7",
    number = "2",
    pages = "5639-5646"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Filatov et al., "Any Motion Detector: Learning Class-agnostic Scene Dynamics from a Sequence of LiDAR Point Clouds", ICRA, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9196716>paper</a> <a href=https://arxiv.org/pdf/2004.11647.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#epe">EPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Filatov_2020_ICRA,
    author = "Filatov, A. and Rykov, A. and Murashkin, V.",
    booktitle = "ICRA",
    title = "Any Motion Detector: Learning Class-agnostic Scene Dynamics from a Sequence of {LiDAR} Point Clouds",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=epe3d></a>
<details close>
<summary><em><l style="font-size:20px"><strong>3D Endpoint Error (EPE3D)</strong><small> [22]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Najibi et al., "Motion Inspired Unsupervised Perception and Prediction in Autonomous Driving", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136980416.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.08061.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#epe3d">EPE3D</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Najibi_2022_ECCV,
    author = "Najibi, Mahyar and Ji, Jingwei and Zhou, Yin and Qi, Charles R. and Yan, Xinchen and Ettinger, Scott and Anguelov, Dragomir",
    title = "Motion Inspired Unsupervised Perception and Prediction in Autonomous Driving",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=es></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Energy Score (ES)</strong><small> [22]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Shahroudi et al., "Evaluation of Trajectory Distribution Predictions with Energy Score", ICML, 2024.</em></strong> <a href=https://openreview.net/pdf?id=FCmWhJQ14I>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#es">ES</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Shahroudi_evaluation_2024_ICML,
    author = "Shahroudi, Novin and Lepson, Mihkel and Kull, Meelis",
    title = "Evaluation of Trajectory Distribution Predictions with Energy Score",
    booktitle = "ICML",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=f></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Feasibility (F)</strong><small> [22]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Dendorfer et al., "Goal-GAN: Multimodal Trajectory Prediction Based on Goal Position Estimation", ACCV, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content/ACCV2020/papers/Dendorfer_Goal-GAN_Multimodal_Trajectory_Prediction_Based_on_Goal_Position_Estimation_ACCV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2010.01114.pdf>arxiv</a> <a href=https://github.com/dendorferpatrick/GoalGAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mc">MC</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#f">F</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Dendorfer_2020_ACCV,
    author = "Dendorfer, Patrick and Osep, Aljosa and Leal-Taixe, Laura",
    title = "{Goal-GAN}: Multimodal Trajectory Prediction Based on Goal Position Estimation",
    booktitle = "ACCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=fde></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Final Displacement Error (FDE)</strong><small> [4]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Lou et al., "Multimodal Sense-Informed Forecasting of 3D Human Motions", CVPR, 2024.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Lou_Multimodal_Sense-Informed_Forecasting_of_3D_Human_Motions_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2405.02911>arxiv</a> <a href=https://github.com/kjle6/SIF3D-master>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#gta-im">GTA-IM</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#gimo">GIMO</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lou_Multimodal_2024_CVPR,
    author = "Lou, Zhenyu and Cui, Qiongjie and Wang, Haofan and Tang, Xu and Zhou, Hong",
    title = "Multimodal Sense-Informed Forecasting of 3D Human Motions",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Bae et al., "SingularTrajectory: Universal Trajectory Predictor Using Diffusion Model", CVPR, 2024.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Bae_SingularTrajectory_Universal_Trajectory_Predictor_Using_Diffusion_Model_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2403.18452>arxiv</a> <a href=https://github.com/inhwanbae/SingularTrajectory>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bae_SingularTrajectory_2024_CVPR,
    author = "Bae, Inhwan and Park, Young-Jae and Jeon, Hae-Gon",
    title = "SingularTrajectory: Universal Trajectory Predictor Using Diffusion Model",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Nakamura et al., "Not All Errors Are Made Equal: A Regret Metric for Detecting System-level Trajectory Prediction Failures", CoRL, 2024.</em></strong> <a href=https://openreview.net/pdf?id=G0jqGG8Tta>paper</a> <a href=https://arxiv.org/pdf/2403.04745>arxiv</a> <a href=https://cmu-intentlab.github.io/not-all-errors/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Nakamura_Not_2024_CoRL,
    author = "Nakamura, Kensuke and Tian, Thomas and Bajcsy, Andrea",
    title = "Not All Errors Are Made Equal: A Regret Metric for Detecting System-level Trajectory Prediction Failures",
    booktitle = "CoRL",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wang et al., "EscIRL: Evolving Self-Contrastive IRL for Trajectory Prediction in Autonomous Driving", CoRL, 2024.</em></strong> <a href=https://openreview.net/pdf?id=1IzW0aniyg>paper</a> <a href=https://github.com/SiyueWang-CiDi/EscIRL>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#citysim">CitySim</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#cr">CR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#hp">HP</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#afd">AFD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Wang_EscIRL_2024_CoRL,
    author = "Wang, Siyue and Chen, Zhaorun and Zhao, Zhuokai and Mao, Chaoli and Zhou, Yiyang and He, Jiayu and Hu, Albert Sibo",
    title = "Esc{IRL}: Evolving Self-Contrastive {IRL} for Trajectory Prediction in Autonomous Driving",
    booktitle = "CoRL",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Thakkar et al., "Adaptive human trajectory prediction via latent corridors", ECCV, 2024.</em></strong> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/05542.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#mot">MOT</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#wildtrack">WILDTRACK</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#motsynth">MOTSynth</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Thakkar_Adaptive_2024_ECCV,
    author = "Thakkar, Neerja and Mangalam, Karttikeya and Bajcsy, Andrea and Malik, Jitendra",
    title = "Adaptive human trajectory prediction via latent corridors",
    booktitle = "ECCV",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zheng et al., "Large Language Models Powered Context-aware Motion Prediction in Autonomous Driving", IROS, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10802397>paper</a> <a href=https://arxiv.org/pdf/2403.11057>arxiv</a> <a href=https://github.com/AIR-DISCOVER/LLM-Augmented-MTR>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Zheng_Large_2024_IROS,
    author = "Zheng, Xiaoji and Wu, Lixiu and Yan, Zhijie and Tang, Yuanrong and Zhao, Hao and Zhong, Chen and Chen, Bokui and Gong, Jiangtao",
    booktitle = "IROS",
    title = "Large Language Models Powered Context-aware Motion Prediction in Autonomous Driving",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Fan et al., "Adversarial Attack on Trajectory Prediction for Autonomous Vehicles with Generative Adversarial Networks", IROS, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10802234>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Fan_Adversarial_2024_IROS,
    author = "Fan, Jiping and Wang, Zhenpo and Li, Guoqiang",
    booktitle = "IROS",
    title = "Adversarial Attack on Trajectory Prediction for Autonomous Vehicles with Generative Adversarial Networks",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Chen et al., "MGF: Mixed Gaussian Flow for Diverse Trajectory Prediction", NeurIPS, 2024.</em></strong> <a href=https://openreview.net/pdf?id=muYhNDlxWc>paper</a> <a href=https://arxiv.org/pdf/2402.12238>arxiv</a> <a href=https://github.com/mulplue/MGF>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fpd">FPD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#apd">APD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Chen_Mgf_2024_NeurIPS,
    author = "Chen, Jiahe and Cao, Jinkun and Lin, Dahua and Kitani, Kris M. and Pang, Jiangmiao",
    title = "{MGF}: Mixed Gaussian Flow for Diverse Trajectory Prediction",
    booktitle = "NeurIPS",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Yao et al., "TrajCLIP: Pedestrian trajectory prediction method using contrastive learning and idempotent networks", NeurIPS, 2024.</em></strong> <a href=https://openreview.net/pdf?id=fUBFy8tb3z>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Yao_Trajclip_2024_NeurIPS,
    author = "Yao, Pengfei and Zhu, Yinglong and Bi, Huikun and Mao, Tianlu and Wang, Zhaoqi",
    title = "Traj{CLIP}: Pedestrian trajectory prediction method using contrastive learning and idempotent networks",
    booktitle = "NeurIPS",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>chib et al., "MS-TIP: Imputation Aware Pedestrian Trajectory Prediction", ICML, 2024.</em></strong> <a href=https://openreview.net/pdf?id=s4Hy0L4mml>paper</a> <a href=https://github.com/Pranav-chib/MS-TIP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Chip_MSTIP_2024_ICML,
    author = "singh chib, Pranav and Nath, Achintya and Kabra, Paritosh and Gupta, Ishu and Singh, Pravendra",
    title = "{MS}-{TIP}: Imputation Aware Pedestrian Trajectory Prediction",
    booktitle = "ICML",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>chib et al., "Enhancing Trajectory Prediction through Self-Supervised Waypoint Distortion Prediction", ICML, 2024.</em></strong> <a href=https://openreview.net/pdf?id=OQ7TlOphGX>paper</a> <a href=https://arxiv.org/pdf/2312.09466>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Chib_Enhancing_2024_ICML,
    author = "singh chib, Pranav and Singh, Pravendra",
    title = "Enhancing Trajectory Prediction through Self-Supervised Waypoint Distortion Prediction",
    booktitle = "ICML",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Park et al., "Long-Term Typhoon Trajectory Prediction: A Physics-Conditioned Approach Without Reanalysis Data", ICLR, 2024.</em></strong> <a href=https://openreview.net/pdf?id=ziDFH8TPPK>paper</a> <a href=https://arxiv.org/pdf/2401.15726>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#era5">ERA5</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#um">UM</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#best_track">Best Track</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Park_longterm_2024_ICLR,
    author = "Park, Young-Jae and Seo, Minseok and Kim, Doyi and Kim, Hyeri and Choi, Sanghoon and Choi, Beomkyu and Ryu, Jeongwon and Son, Sohee and Jeon, Hae-Gon and Choi, Yeji",
    title = "Long-Term Typhoon Trajectory Prediction: A Physics-Conditioned Approach Without Reanalysis Data",
    booktitle = "ICLR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Saadatnejad et al., "Social-Transmotion: Promptable Human Trajectory Prediction", ICLR, 2024.</em></strong> <a href=https://openreview.net/pdf?id=SQpnEfv9WH>paper</a> <a href=https://arxiv.org/pdf/2312.16168>arxiv</a> <a href=https://github.com/vita-epfl/social-transmotion>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jrdb">JRDB</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jta">JTA</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pcrt">PCRT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Saadatnejad_socialtransmotion_2024_ICLR,
    author = "Saadatnejad, Saeed and Gao, Yang and Messaoud, Kaouther and Alahi, Alexandre",
    title = "Social-Transmotion: Promptable Human Trajectory Prediction",
    booktitle = "ICLR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Rasouli, "A Novel Benchmarking Paradigm and a Scale- and Motion-Aware Model for Egocentric Pedestrian Trajectory Prediction", ICRA, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10610614>paper</a> <a href=https://arxiv.org/pdf/2310.10424>arxiv</a> <a href=https://github.com/aras62/PIE/tree/master/scenarioEval>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#sminade">sminADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#sade">sADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Rasouli_Novel_2024_ICRA,
    author = "Rasouli, Amir",
    booktitle = "ICRA",
    title = "A Novel Benchmarking Paradigm and a Scale- and Motion-Aware Model for Egocentric Pedestrian Trajectory Prediction",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Huang et al., "DTPP: Differentiable Joint Conditional Prediction and Cost Evaluation for Tree Policy Planning in Autonomous Driving", ICRA, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10610550>paper</a> <a href=https://arxiv.org/pdf/2310.05885>arxiv</a> <a href=https://github.com/MCZhi/DTPP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuplan">nuPlan</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Huang_DTPP_2024_ICRA,
    author = "Huang, Zhiyu and Karkus, Peter and Ivanovic, Boris and Chen, Yuxiao and Pavone, Marco and Lv, Chen",
    booktitle = "ICRA",
    title = "DTPP: Differentiable Joint Conditional Prediction and Cost Evaluation for Tree Policy Planning in Autonomous Driving",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Thuremella et al., "Risk-aware Trajectory Prediction by Incorporating Spatio-temporal Traffic Interaction Analysis", ICRA, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10611023>paper</a> <a href=https://www.arxiv.org/pdf/2407.10639>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Thuremella_Risk_2024_ICRA,
    author = "Thuremella, Divya and Ince, Lewis and Kunze, Lars",
    booktitle = "ICRA",
    title = "Risk-aware Trajectory Prediction by Incorporating Spatio-temporal Traffic Interaction Analysis",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Bhaskara et al., "Trajectory Prediction for Robot Navigation using Flow-Guided Markov Neural Operator", ICRA, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10611154>paper</a> <a href=https://arxiv.org/pdf/2309.09137>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Bhaskara_Trajectory_2024_ICRA,
    author = "Bhaskara, Rashmi and Viswanath, Hrishikesh and Bera, Aniket",
    booktitle = "ICRA",
    title = "Trajectory Prediction for Robot Navigation using Flow-Guided Markov Neural Operator",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Liu et al., "STAGP: Spatio-Temporal Adaptive Graph Pooling Network for Pedestrian Trajectory Prediction", RAL, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10373049>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Liu_STAGP_2024_RAL,
    author = "Liu, Zhening and He, Li and Yuan, Liang and Lv, Kai and Zhong, Runhao and Chen, Yaohua",
    journal = "RAL",
    title = "STAGP: Spatio-Temporal Adaptive Graph Pooling Network for Pedestrian Trajectory Prediction",
    year = "2024",
    volume = "9",
    number = "3",
    pages = "2001-2007"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Eltouny et al., "DE-TGN: Uncertainty-Aware Human Motion Forecasting Using Deep Ensembles", RAL, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10409503>paper</a> <a href=https://arxiv.org/pdf/2307.03610>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Eltouny_DETGN_2024_RAL,
    author = "Eltouny, Kareem A. and Liu, Wansong and Tian, Sibo and Zheng, Minghui and Liang, Xiao",
    journal = "RAL",
    title = "DE-TGN: Uncertainty-Aware Human Motion Forecasting Using Deep Ensembles",
    year = "2024",
    volume = "9",
    number = "3",
    pages = "2192-2199"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Almeida et al., "Trajectory Prediction for Heterogeneous Agents: A Performance Analysis on Small and Imbalanced Datasets", RAL, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10545544>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#thor-magni">THOR-MAGNI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Almeida_Trajectory_2024_RAL,
    author = "de Almeida, Tiago Rodrigues and Zhu, Yufei and Rudenko, Andrey and Kucner, Tomasz P. and Stork, Johannes A. and Magnusson, Martin and Lilienthal, Achim J.",
    journal = "RAL",
    title = "Trajectory Prediction for Heterogeneous Agents: A Performance Analysis on Small and Imbalanced Datasets",
    year = "2024",
    volume = "9",
    number = "7",
    pages = "6576-6583"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wang et al., "FEND: A Future Enhanced Distribution-Aware Contrastive Learning Framework for Long-Tail Trajectory Prediction", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_FEND_A_Future_Enhanced_Distribution-Aware_Contrastive_Learning_Framework_for_Long-Tail_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.16574.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2023_CVPR,
    author = "Wang, Yuning and Zhang, Pu and Bai, Lei and Xue, Jianru",
    title = "FEND: A Future Enhanced Distribution-Aware Contrastive Learning Framework for Long-Tail Trajectory Prediction",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Xu et al., "Uncovering the Missing Pattern: Unified Framework Towards Trajectory Imputation and Prediction", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Xu_EqMotion_Equivariant_Multi-Agent_Motion_Prediction_With_Invariant_Interaction_Reasoning_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.10876.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/EqMotion>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#md17">MD17</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2023_CVPR,
    author = "Xu, Yi and Bazarjani, Armin and Chi, Hyung-gun and Choi, Chiho and Fu, Yun",
    title = "Uncovering the Missing Pattern: Unified Framework Towards Trajectory Imputation and Prediction",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Maeda et al., "Fast Inference and Update of Probabilistic Density Estimation on Trajectory Prediction", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Maeda_Fast_Inference_and_Update_of_Probabilistic_Density_Estimation_on_Trajectory_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.08824.pdf>arxiv</a> <a href=https://github.com/meaten/FlowChain-ICCV2023>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Maeda_2023_ICCV,
    author = "Maeda, Takahiro and Ukita, Norimichi",
    title = "Fast Inference and Update of Probabilistic Density Estimation on Trajectory Prediction",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Bagi et al., "Generative Causal Representation Learning for Out-of-Distribution Motion Forecasting", ICML, 2023.</em></strong> <a href=https://proceedings.mlr.press/v202/shirahmad-gale-bagi23a/shirahmad-gale-bagi23a.pdf>paper</a> <a href=https://arxiv.org/pdf/2302.08635.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#crowdnav">CrowdNav</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bagi_2023_ICML,
    author = "Bagi, Shayan Shirahmad Gale and Gharaee, Zahra and Schulte, Oliver and Crowley, Mark",
    title = "Generative Causal Representation Learning for Out-of-Distribution Motion Forecasting",
    booktitle = "ICML",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Mahdavian et al., "STPOTR: Simultaneous Human Trajectory and Pose Prediction Using a Non-Autoregressive Transformer for Robot Follow-Ahead", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10160538>paper</a> <a href=https://arxiv.org/pdf/2209.07600.pdf>arxiv</a> <a href=https://github.com/mmahdavian/STPOTR>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mahdavian_2023_ICRA,
    author = "Mahdavian, Mohammad and Nikdel, Payam and TaherAhmadi, Mahdi and Chen, Mo",
    title = "STPOTR: Simultaneous Human Trajectory and Pose Prediction Using a Non-Autoregressive Transformer for Robot Follow-Ahead",
    booktitle = "ICRA",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Nikdel et al., "DMMGAN: Diverse Multi Motion Prediction of 3D Human Joints using Attention-Based Generative Adversarial Network", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10160401>paper</a> <a href=https://arxiv.org/pdf/2209.09124.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Nikdel_2023_ICRA,
    author = "Nikdel, Payam and Mahdavian, Mohammad and Chen, Mo",
    title = "DMMGAN: Diverse Multi Motion Prediction of 3D Human Joints using Attention-Based Generative Adversarial Network",
    booktitle = "ICRA",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Rasouli et al., "PedFormer: Pedestrian Behavior Prediction via Cross-Modal Attention Modulation and Gated Multitask Learning", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10161318>paper</a> <a href=https://arxiv.org/pdf/2210.07886.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#frb">FRB</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#arb">ARB</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rasouli_2023_ICRA,
    author = "Rasouli, Amir and Kotseruba, Iuliia",
    title = "PedFormer: Pedestrian Behavior Prediction via Cross-Modal Attention Modulation and Gated Multitask Learning",
    booktitle = "ICRA",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Kiss et al., "Constrained Gaussian Processes With Integrated Kernels for Long-Horizon Prediction of Dense Pedestrian Crowd Flows", RAL, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/document/9782121>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#atc">ATC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Kiss_2023_RAL,
    author = "Kiss, Stefan H. and Katuwandeniya, Kavindie and Alempijevic, Alen and Vidal-Calleja, Teresa",
    journal = "RAL",
    title = "Constrained Gaussian Processes With Integrated Kernels for Long-Horizon Prediction of Dense Pedestrian Crowd Flows",
    year = "2022",
    volume = "7",
    number = "3",
    pages = "7343-7350"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Hsu et al., "Interpretable Trajectory Prediction for Autonomous Vehicles via Counterfactual Responsibility", IROS, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10341712>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@INPROCEEDINGS{Hsu_2023_IROS,
    author = "Hsu, Kai-Chieh and Leung, Karen and Chen, Yuxiao and Fisac, Jaime F. and Pavone, Marco",
    booktitle = "IROS",
    title = "Interpretable Trajectory Prediction for Autonomous Vehicles via Counterfactual Responsibility",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Kedia et al., "A Game-Theoretic Framework for Joint Forecasting and Planning", IROS, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10341265>paper</a> <a href=https://arxiv.org/pdf/2308.06137.pdf>arxiv</a> <a href=https://github.com/portal-cornell/Game-Theoretic-Forecasting-Planning>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@INPROCEEDINGS{Kedia_2023_IROS,
    author = "Kedia, Kushal and Dan, Prithwish and Choudhury, Sanjiban",
    booktitle = "IROS",
    title = "A Game-Theoretic Framework for Joint Forecasting and Planning",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Poddar et al., "From Crowd Motion Prediction to Robot Navigation in Crowds", IROS, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10341464>paper</a> <a href=https://arxiv.org/pdf/2303.01424.pdf>arxiv</a> <a href=https://github.com/cmavrogiannis/Pred2Nav>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@INPROCEEDINGS{Poddar_2023_IROS,
    author = "Poddar, Sriyash and Mavrogiannis, Christoforos and Srinivasa, Siddhartha S.",
    booktitle = "IROS",
    title = "From Crowd Motion Prediction to Robot Navigation in Crowds",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Stoler et al., "T2FPV: Dataset and Method for Correcting First-Person View Errors in Pedestrian Trajectory Prediction", IROS, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10341874>paper</a> <a href=https://arxiv.org/pdf/2209.11294.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#t2fpv-eth">T2FPV-ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@INPROCEEDINGS{Stoler_2023_IROS,
    author = "Stoler, Benjamin and Jana, Meghdeep and Hwang, Soonmin and Oh, Jean",
    booktitle = "IROS",
    title = "T2FPV: Dataset and Method for Correcting First-Person View Errors in Pedestrian Trajectory Prediction",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhu et al., "CLiFF-LHMP: Using Spatial Dynamics Patterns for Long- Term Human Motion Prediction", IROS, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10342031>paper</a> <a href=https://arxiv.org/pdf/2309.07066.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#atc">ATC</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#thor">THOR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@INPROCEEDINGS{Zhu_2023_IROS,
    author = "Zhu, Yufei and Rudenko, Andrey and Kucner, Tomasz P. and Palmieri, Luigi and Arras, Kai O. and Lilienthal, Achim J. and Magnusson, Martin",
    booktitle = "IROS",
    title = "CLiFF-LHMP: Using Spatial Dynamics Patterns for Long- Term Human Motion Prediction",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Huynh et al., "Online Adaptive Temporal Memory With Certainty Estimation for Human Trajectory Prediction", WACV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/WACV2023/papers/Huynh_Online_Adaptive_Temporal_Memory_With_Certainty_Estimation_for_Human_Trajectory_WACV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Huynh_2023_WACV,
    author = "Huynh, Manh and Alaghband, Gita",
    title = "Online Adaptive Temporal Memory With Certainty Estimation for Human Trajectory Prediction",
    booktitle = "WACV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Liu et al., "Towards Robust and Adaptive Motion Forecasting: A Causal Representation Perspective", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Towards_Robust_and_Adaptive_Motion_Forecasting_A_Causal_Representation_Perspective_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2111.14820.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2022_CVPR,
    author = "Liu, Yuejiang and Cadei, Riccardo and Schweizer, Jonas and Bahmani, Sherwin and Alahi, Alexandre",
    title = "Towards Robust and Adaptive Motion Forecasting: A Causal Representation Perspective",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Monti et al., "How Many Observations Are Enough? Knowledge Distillation for Trajectory Forecasting", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Monti_How_Many_Observations_Are_Enough_Knowledge_Distillation_for_Trajectory_Forecasting_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.04781.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Monti_2022_CVPR,
    author = "Monti, Alessio and Porrello, Angelo and Calderara, Simone and Coscia, Pasquale and Ballan, Lamberto and Cucchiara, Rita",
    title = "How Many Observations Are Enough? Knowledge Distillation for Trajectory Forecasting",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Cao et al., "AdvDO: Realistic Adversarial Attacks for Trajectory Prediction", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136650036.pdf>paper</a> <a href=https://arxiv.org/pdf/2209.08744.pdf>arxiv</a> <a href=https://robustav.github.io/RobustPred/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#orr">ORR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cao_2022_ECCV,
    author = "Cao, Yulong and Xiao, Chaowei and Anandkumar, Anima and Xu, Danfei and Pavone, Marco",
    title = "{AdvDO}: Realistic Adversarial Attacks for Trajectory Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Chen et al., "S2F2: Single-Stage Flow Forecasting for Future Multiple Trajectories Prediction", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820593.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#mot">MOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iou">IoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2022_ECCV,
    author = "Chen, Yu-Wen and Yang, Hsuan-Kung and Chiu, Chu-Chi and Lee, Chun-Yi",
    title = "{S2F2}: Single-Stage Flow Forecasting for Future Multiple Trajectories Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Halawa et al., "Action-Based Contrastive Learning for Trajectory Prediction", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136990140.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.08664.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#titan">TITAN</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Halawa_2022_ECCV,
    author = "Halawa, Marah and Hellwich, Olaf and Bideau, Pia",
    title = "Action-Based Contrastive Learning for Trajectory Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Hu et al., "Entry-Flipped Transformer for Inference and Prediction of Participant Behavior", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136640433.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.06235.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#ceilidh_dance">Ceilidh Dance</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2022_ECCV,
    author = "Hu, Bo and Cham, Tat-Jen",
    title = "Entry-Flipped Transformer for Inference and Prediction of Participant Behavior",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Tsao et al., "Social-SSL: Self-Supervised Cross-Sequence Representation Learning Based on Transformers for Multi-agent Trajectory Prediction", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820227.pdf>paper</a> <a href=https://github.com/Sigta678/Social-SSL>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tsao_2022_ECCV,
    author = "Tsao, Li-Wu and Wang, Yan-Kai and Lin, Hao-Siang and Shuai, Hong-Han and Wong, Lai-Kuan and Cheng, Wen-Huang",
    title = "{Social-SSL}: Self-Supervised Cross-Sequence Representation Learning Based on Transformers for Multi-agent Trajectory Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Cao et al., "Leveraging Smooth Attention Prior for Multi-Agent Trajectory Prediction", ICRA, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/document/9811718>paper</a> <a href=https://arxiv.org/pdf/2203.04421.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cao_2022_ICRA,
    author = "Cao, Zhangjie and Biyik, Erdem and Rosman, Guy and Sadigh, Dorsa",
    booktitle = "ICRA",
    title = "Leveraging Smooth Attention Prior for Multi-Agent Trajectory Prediction",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Ivanovic et al., "Propagating State Uncertainty Through Trajectory Forecasting", ICRA, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/document/9811776>paper</a> <a href=https://arxiv.org/pdf/2110.03267.pdf>arxiv</a> <a href=https://github.com/StanfordASL/PSU-TF>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#deltaesv">DeltaESV</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ivanovic_2022_ICRA,
    author = "Ivanovic, Boris and Lin, Yifeng and Shrivastava, Shubham and Chakravarty, Punarjay and Pavone, Marco",
    booktitle = "ICRA",
    title = "Propagating State Uncertainty Through Trajectory Forecasting",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Kamenev et al., "PredictionNet: Real-Time Joint Probabilistic Traffic Prediction for Planning, Control, and Simulation", ICRA, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/document/9812223>paper</a> <a href=https://arxiv.org/pdf/2109.11094.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kamenev_2022_ICRA,
    author = "Kamenev, Alexey and Wang, Lirui and Bohan, Ollin Boer and Kulkarni, Ishwar and Kartal, Bilal and Molchanov, Artem and Birchfield, Stan and Nistér, David and Smolyanskiy, Nikolai",
    booktitle = "ICRA",
    title = "{PredictionNet}: Real-Time Joint Probabilistic Traffic Prediction for Planning, Control, and Simulation",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Fadadu et al., "Multi-View Fusion of Sensor Data for Improved Perception and Prediction in Autonomous Driving", WACV, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/WACV2022/papers/Fadadu_Multi-View_Fusion_of_Sensor_Data_for_Improved_Perception_and_Prediction_WACV_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.11901.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Fadadu_2022_WACV,
    author = "Fadadu, Sudeep and Pandey, Shreyash and Hegde, Darshan and Shi, Yi and Chou, Fang-Chieh and Djuric, Nemanja and Vallespi-Gonzalez, Carlos",
    title = "Multi-View Fusion of Sensor Data for Improved Perception and Prediction in Autonomous Driving",
    booktitle = "WACV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Knoedler et al., "Improving Pedestrian Prediction Models With Self-Supervised Continual Learning", RAL, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9705542>paper</a> <a href=https://arxiv.org/pdf/2202.07606>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Knoedler_Improving_2022_RAL,
    author = "Knoedler, Luzia and Salmi, Chadi and Zhu, Hai and Brito, Bruno and Alonso-Mora, Javier",
    journal = "RAL",
    title = "Improving Pedestrian Prediction Models With Self-Supervised Continual Learning",
    year = "2022",
    volume = "7",
    number = "2",
    pages = "4781-4788"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wang et al., "Stepwise Goal-Driven Networks for Trajectory Prediction", RAL, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/document/9691856>paper</a> <a href=https://arxiv.org/pdf/2103.14107.pdf>arxiv</a> <a href=https://github.com/ChuhuaW/SGNet.pytorch>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#hev-i">HEV-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Wang_2022_RAL_2,
    author = "Wang, Chuhua and Wang, Yuchen and Xu, Mingze and Crandall, David J.",
    journal = "RAL",
    title = "Stepwise Goal-Driven Networks for Trajectory Prediction",
    year = "2022",
    volume = "7",
    number = "2",
    pages = "2716-2723"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhou et al., "GA-STT: Human Trajectory Prediction with Group Aware Spatial-temporal Transformer", RAL, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9779572>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Zhou_2022_RAL,
    author = "Zhou, Lei and Yang, Dingye and Zhai, Xiaolin and Wu, Shichao and Hu, ZhengXi and Liu, Jingtai",
    journal = "RAL",
    title = "{GA-STT}: Human Trajectory Prediction with Group Aware Spatial-temporal Transformer",
    volume = "7",
    number = "3",
    pages = "7660--7667",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Antonello et al., "Flash: Fast and Light Motion Prediction for Autonomous Driving with Bayesian Inverse Planning and Learned Motion Profiles", IROS, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9981347>paper</a> <a href=https://arxiv.org/pdf/2203.08251.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Antonello_2022_IROS,
    author = "Antonello, Morris and Dobre, Mihai and Albrecht, Stefano V and Redford, John and Ramamoorthy, Subramanian",
    booktitle = "IROS",
    title = "Flash: Fast and Light Motion Prediction for Autonomous Driving with Bayesian Inverse Planning and Learned Motion Profiles",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Bhatt et al., "MPC-PF: Social Interaction Aware Trajectory Prediction of Dynamic Objects for Autonomous Driving Using Potential Fields", IROS, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9981046>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ap">AP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bhatt_2022_IROS,
    author = "Bhatt, Neel P and Khajepour, Amir and Hashemi, Ehsan",
    booktitle = "IROS",
    title = "{MPC-PF}: Social Interaction Aware Trajectory Prediction of Dynamic Objects for Autonomous Driving Using Potential Fields",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Chen et al., "HGCN-GJS: Hierarchical Graph Convolutional Network with Groupwise Joint Sampling for Trajectory Prediction", IROS, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/document/9981037>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2022_IROS,
    author = "Chen, Yuying and Liu, Congcong and Mei, Xiaodong and Shi, Bertram E. and Liu, Ming",
    booktitle = "IROS",
    title = "{HGCN-GJS}: Hierarchical Graph Convolutional Network with Groupwise Joint Sampling for Trajectory Prediction",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Ivanovic et al., "Heterogeneous-agent Trajectory Forecasting Incorporating Class Uncertainty", IROS, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9982283>paper</a> <a href=https://arxiv.org/pdf/2104.12446.pdf>arxiv</a> <a href=https://github.com/TRI-ML/HAICU>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pup">PUP</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ivanovic_2022_IROS,
    author = "Ivanovic, Boris and Lee, Kuan-Hui and Tokmakov, Pavel and Wulfe, Blake and Mcllister, Rowan and Gaidon, Adrien and Pavone, Marco",
    booktitle = "IROS",
    title = "Heterogeneous-agent Trajectory Forecasting Incorporating Class Uncertainty",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Navarro et al., "Social-PatteRNN: Socially-Aware Trajectory Prediction Guided by Motion Patterns", IROS, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9981486>paper</a> <a href=https://arxiv.org/pdf/2209.05649.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#trajair">TrajAir</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Navarro_2022_IROS,
    author = "Navarro, Ingrid and Oh, Jean",
    booktitle = "IROS",
    title = "{Social-PatteRNN}: Socially-Aware Trajectory Prediction Guided by Motion Patterns",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Tang et al., "Collaborative Uncertainty in Multi-Agent Trajectory Forecasting", NeurIPS, 2021.</em></strong> <a href=https://papers.nips.cc/paper/2021/file/31ca0ca71184bbdb3de7b20a51e88e90-Paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2110.13947.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#kld">KLD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#l1">L1</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tang_2021_NeurIPS,
    author = "Tang, Bohan and Zhong, Yiqi and Neumann, Ulrich and Wang, Gang and Chen, Siheng and Zhang, Ya",
    booktitle = "NeurIPS",
    title = "Collaborative Uncertainty in Multi-Agent Trajectory Forecasting",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Walters et al., "Trajectory Prediction using Equivariant Continuous Convolution", ICLR, 2021.</em></strong> <a href=https://openreview.net/pdf?id=J8_GttYLFgr>paper</a> <a href=https://arxiv.org/pdf/2010.11344.pdf>arxiv</a> <a href=https://github.com/Rose-STL-Lab/ECCO>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#trajnet++">Trajnet++</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Walters_2021_ICLR,
    author = "Walters, Robin and Li, Jinxi and Yu, Rose",
    booktitle = "ICLR",
    title = "Trajectory Prediction using Equivariant Continuous Convolution",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Kothari et al., "Interpretable Social Anchors for Human Trajectory Forecasting in Crowds", CVPR, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Kothari_Interpretable_Social_Anchors_for_Human_Trajectory_Forecasting_in_Crowds_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2105.03136.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#trajnet++">Trajnet++</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#tcr">TCR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kothari_2021_CVPR,
    author = "Kothari, Parth and Sifringer, Brian and Alahi, Alexandre",
    title = "Interpretable Social Anchors for Human Trajectory Forecasting in Crowds",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Rasouli et al., "Bifold and Semantic Reasoning for Pedestrian Behavior Prediction", ICCV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Rasouli_Bifold_and_Semantic_Reasoning_for_Pedestrian_Behavior_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2012.03298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#frb">FRB</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#arb">ARB</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rasouli_2021_ICCV,
    author = "Rasouli, Amir and Rohani, Mohsen and Luo, Jun",
    title = "Bifold and Semantic Reasoning for Pedestrian Behavior Prediction",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zheng et al., "Unlimited Neighborhood Interaction for Heterogeneous Trajectory Prediction", ICCV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Zheng_Unlimited_Neighborhood_Interaction_for_Heterogeneous_Trajectory_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2108.00238.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zheng_2021_ICCV,
    author = "Zheng, Fang and Wang, Le and Zhou, Sanping and Tang, Wei and Niu, Zhenxing and Zheng, Nanning and Hua, Gang",
    title = "Unlimited Neighborhood Interaction for Heterogeneous Trajectory Prediction",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Cheng et al., "Exploring Dynamic Context for Multi-path Trajectory Prediction", ICRA, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9562034>paper</a> <a href=https://arxiv.org/pdf/2010.16267.pdf>arxiv</a> <a href=https://github.com/wtliao/DCENet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#trajnet++">Trajnet++</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cheng_2021_ICRA,
    author = "Cheng, Hao and Liao, Wentong and Tang, Xuejiao and Yang, Michael Ying and Sester, Monika and Rosenhahn, Bodo",
    booktitle = "ICRA",
    title = "Exploring Dynamic Context for Multi-path Trajectory Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Dulian et al., "Exploiting Latent Representation of Sparse Semantic Layers for Improved Short-term Motion Prediction with Capsule Networks", ICRA, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9561467>paper</a> <a href=https://arxiv.org/pdf/2103.01644.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Dulian_2021_ICRA,
    author = "Dulian, Albert and Murray, John C.",
    booktitle = "ICRA",
    title = "Exploiting Latent Representation of Sparse Semantic Layers for Improved Short-term Motion Prediction with Capsule Networks",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Majcherczyk et al., "Flow-FL: Data-Driven Federated Learning for Spatio-Temporal Predictions in Multi-Robot Systems", ICRA, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9560791>paper</a> <a href=https://arxiv.org/pdf/2010.08595.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Majcherczyk_2021_ICRA,
    author = "Majcherczyk, Nathalie and Srishankar, Nishan and Pinciroli, Carlo",
    booktitle = "ICRA",
    title = "{Flow-FL}: Data-Driven Federated Learning for Spatio-Temporal Predictions in Multi-Robot Systems",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Malla et al., "Social-STAGE: Spatio-Temporal Multi-Modal Future Trajectory Forecast", ICRA, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9561582>paper</a> <a href=https://arxiv.org/pdf/2011.04853.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Malla_2021_ICRA,
    author = "Malla, Srikanth and Choi, Chiho and Dariush, Behzad",
    booktitle = "ICRA",
    title = "{Social-STAGE}: Spatio-Temporal Multi-Modal Future Trajectory Forecast",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhu et al., "Star Topology based Interaction for Robust Trajectory Forecasting in Dynamic Scene", ICRA, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9561067>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhu_2021_ICRA,
    author = "Zhu, Yanliang and Ren, Dongchun and Qian, Deheng and Fan, Mingyu and Li, Xin and Xia, Huaxia",
    booktitle = "ICRA",
    title = "Star Topology based Interaction for Robust Trajectory Forecasting in Dynamic Scene",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Xu et al., "Tra2Tra: Trajectory-to-Trajectory Prediction With a Global Social Spatial-Temporal Attentive Neural Network", RAL, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9347678>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#charges">Charges</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Xu_2021_RAL,
    author = "Xu, Yi and Ren, Dongchun and Li, Mingxia and Chen, Yuehai and Fan, Mingyu and Xia, Huaxia",
    journal = "RAL",
    title = "Tra2Tra: Trajectory-to-Trajectory Prediction With a Global Social Spatial-Temporal Attentive Neural Network",
    year = "2021",
    volume = "6",
    number = "2",
    pages = "1574-1581"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Yao et al., "BiTraP: Bi-Directional Pedestrian Trajectory Prediction With Multi-Modal Goal Estimation", RAL, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9345445>paper</a> <a href=https://arxiv.org/pdf/2007.14558.pdf>arxiv</a> <a href=https://github.com/umautobots/bidireaction-trajectory-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Yao_2021_RAL,
    author = "Yao, Yu and Atkins, Ella and Johnson-Roberson, Matthew and Vasudevan, Ram and Du, Xiaoxiao",
    journal = "RAL",
    title = "{BiTraP}: Bi-Directional Pedestrian Trajectory Prediction With Multi-Modal Goal Estimation",
    year = "2021",
    volume = "6",
    number = "2",
    pages = "3459-3466"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhao et al., "Noticing Motion Patterns: A Temporal CNN With a Novel Convolution Operator for Human Trajectory Prediction", RAL, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9309403>paper</a> <a href=https://arxiv.org/pdf/2007.00862.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Zhao_2021_RAL,
    author = "Zhao, Dapeng and Oh, Jean",
    journal = "RAL",
    title = "Noticing Motion Patterns: A Temporal {CNN} With a Novel Convolution Operator for Human Trajectory Prediction",
    volume = "6",
    number = "2",
    pages = "628--634",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Li et al., "Attentional-GCNN: Adaptive Pedestrian Trajectory Prediction towards Generic Autonomous Vehicle Use Cases", ICRA, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9561480>paper</a> <a href=https://arxiv.org/pdf/2011.11190.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#usyd">USyd</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2021_ICRA_2,
    author = "Li, Kunming and Eiffert, Stuart and Shan, Mao and Gomez-Donoso, Francisco and Worrall, Stewart and Nebot, Eduardo",
    booktitle = "ICRA",
    title = "{Attentional-GCNN}: Adaptive Pedestrian Trajectory Prediction towards Generic Autonomous Vehicle Use Cases",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Chen et al., "Simultaneous Prediction of Pedestrian Trajectory and Actions based on Context Information Iterative Reasoning", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636252>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#virat/actev">VIRAT/ActEV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2021_IROS,
    author = "Chen, Bo and Li, Decai and He, Yuqing",
    booktitle = "IROS",
    title = "Simultaneous Prediction of Pedestrian Trajectory and Actions based on Context Information Iterative Reasoning",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Kumar et al., "Interaction-Based Trajectory Prediction Over a Hybrid Traffic Graph", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636143>paper</a> <a href=https://arxiv.org/pdf/2009.12916.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#tcr">TCR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kumar_2021_IROS,
    author = "Kumar, Sumit and Gu, Yiming and Hoang, Jerrick and Haynes, Galen Clark and Marchetti-Bowick, Micol",
    booktitle = "IROS",
    title = "Interaction-Based Trajectory Prediction Over a Hybrid Traffic Graph",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Postnikov et al., "CovarianceNet: Conditional Generative Model for Correct Covariance Prediction in Human Motion Prediction", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9635968>paper</a> <a href=https://arxiv.org/pdf/2109.02965.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#ppei">PPEI</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Postnikov_2021_IROS,
    author = "Postnikov, Aleksey and Gamayunov, Aleksander and Ferrer, Gonzalo",
    booktitle = "IROS",
    title = "{CovarianceNet}: Conditional Generative Model for Correct Covariance Prediction in Human Motion Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Su et al., "CR-LSTM: Collision-prior Guided Social Refinement for Pedestrian Trajectory Prediction", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636722>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Su_2021_IROS,
    author = "Su, Zhaoxin and Zhang, Sanyuan and Hua, Wei",
    booktitle = "IROS",
    title = "{CR-LSTM}: Collision-prior Guided Social Refinement for Pedestrian Trajectory Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Sui et al., "Joint Intention and Trajectory Prediction Based on Transformer", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636241>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sui_2021_IROS,
    author = "Sui, Ze and Zhou, Yue and Zhao, Xu and Chen, Ao and Ni, Yiyang",
    booktitle = "IROS",
    title = "Joint Intention and Trajectory Prediction Based on Transformer",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhi et al., "Probabilistic Trajectory Prediction with Structural Constraints", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636003>paper</a> <a href=https://arxiv.org/pdf/2107.04193.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#thor">THOR</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#lankershim_boulevard">Lankershim Boulevard</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#al">AL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhi_2021_IROS,
    author = "Zhi, Weiming and Ott, Lionel and Ramos, Fabio",
    booktitle = "IROS",
    title = "Probabilistic Trajectory Prediction with Structural Constraints",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Huang et al., "Long-Term Pedestrian Trajectory Prediction Using Mutable Intention Filter and Warp LSTM", RAL, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9309334>paper</a> <a href=https://arxiv.org/pdf/2007.00113>arxiv</a> <a href=https://github.com/tedhuang96/mifwlstm>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eifp">EIFP</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#maxd">maxD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Huang_Long_2021_RAL,
    author = "Huang, Zhe and Hasan, Aamir and Shin, Kazuki and Li, Ruohua and Driggs-Campbell, Katherine",
    journal = "RAL",
    title = "Long-Term Pedestrian Trajectory Prediction Using Mutable Intention Filter and Warp LSTM",
    year = "2021",
    volume = "6",
    number = "2",
    pages = "542-549"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Davchev et al., "Learning Structured Representations of Spatial and Interactive Dynamics for Trajectory Prediction in Crowded Scenes", RAL, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9309332>paper</a> <a href=https://arxiv.org/pdf/1911.13044>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Davchev_Learning_2021_RAL,
    author = "Davchev, Todor and Burke, Michael and Ramamoorthy, Subramanian",
    journal = "RAL",
    title = "Learning Structured Representations of Spatial and Interactive Dynamics for Trajectory Prediction in Crowded Scenes",
    year = "2021",
    volume = "6",
    number = "2",
    pages = "707-714"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Li et al., "Vehicle Trajectory Prediction Using Generative Adversarial Network With Temporal Logic Syntax Tree Features", RAL, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9366373>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#maxd">maxD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Li_Vehicle_2021_RAL,
    author = "Li, Xiao and Rosman, Guy and Gilitschenski, Igor and Vasile, Cristian-Ioan and DeCastro, Jonathan A. and Karaman, Sertac and Rus, Daniela",
    journal = "RAL",
    title = "Vehicle Trajectory Prediction Using Generative Adversarial Network With Temporal Logic Syntax Tree Features",
    year = "2021",
    volume = "6",
    number = "2",
    pages = "3459-3466"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Weng et al., "PTP: Parallelized Tracking and Prediction With Graph Neural Networks and Diversity Sampling", RAL, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9387598&tag=1>paper</a> <a href=https://arxiv.org/pdf/2003.07847>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fsd">FSD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#asd">ASD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Weng_PTP_2021_RAL,
    author = "Weng, Xinshuo and Yuan, Ye and Kitani, Kris",
    journal = "RAL",
    title = "PTP: Parallelized Tracking and Prediction With Graph Neural Networks and Diversity Sampling",
    year = "2021",
    volume = "6",
    number = "3",
    pages = "4640-4647"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Jia et al., "Multi-Agent Trajectory Prediction by Combining Egocentric and Allocentric Views", CoRL, 2021.</em></strong> <a href=https://openreview.net/pdf?id=lAtePxetBNb>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#trajnet++">Trajnet++</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jia_2021_CoRL,
    author = "Jia, Xiaosong and Sun, Liting and Zhao, Hang and Tomizuka, Masayoshi and Zhan, Wei",
    title = "Multi-Agent Trajectory Prediction by Combining Egocentric and Allocentric Views",
    booktitle = "CoRL",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhu et al., "Motion Forecasting with Unlikelihood Training in Continuous Space", CoRL, 2021.</em></strong> <a href=https://openreview.net/pdf?id=4u25M570Iji>paper</a> <a href=https://github.com/Vision-CAIR/UnlikelihoodMotionForecasting>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#orr">ORR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhu_2021_CoRL,
    author = "Zhu, Deyao and Zahran, Mohamed and Li, Li Erran and Elhoseiny, Mohamed",
    title = "Motion Forecasting with Unlikelihood Training in Continuous Space",
    booktitle = "CoRL",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Hauri et al., "Multi-Modal Trajectory Prediction of NBA Players", WACV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Hauri_Multi-Modal_Trajectory_Prediction_of_NBA_Players_WACV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.07870.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#basketball">Basketball</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hauri_2021_WACV,
    author = "Hauri, Sandro and Djuric, Nemanja and Radosavljevic, Vladan and Vucetic, Slobodan",
    title = "Multi-Modal Trajectory Prediction of {NBA} Players",
    booktitle = "WACV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Tran et al., "Goal-Driven Long-Term Trajectory Prediction", WACV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Tran_Goal-Driven_Long-Term_Trajectory_Prediction_WACV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/abs/2011.02751>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tran_2021_WACV,
    author = "Tran, Hung and Le, Vuong and Tran, Truyen",
    title = "Goal-Driven Long-Term Trajectory Prediction",
    booktitle = "WACV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Weng et al., "Inverting the Pose Forecasting Pipeline with SPF2: Sequential Pointcloud Forecasting for Sequential Pose Forecasting", CoRL, 2021.</em></strong> <a href=https://proceedings.mlr.press/v155/weng21a/weng21a.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.08376.pdf>arxiv</a> <a href=https://github.com/xinshuoweng/SPF2>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Weng_2021_CORL,
    author = "Weng, Xinshuo and Wang, Jianren and Levine, Sergey and Kitani, Kris and Rhinehart, Nick",
    title = "Inverting the Pose Forecasting Pipeline with {SPF2}: Sequential Pointcloud Forecasting for Sequential Pose Forecasting",
    booktitle = "CoRL",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Fang et al., "TPNet: Trajectory Proposal Network for Motion Prediction", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Fang_TPNet_Trajectory_Proposal_Network_for_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.12255.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#dac">DAC</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#wsfde">WSFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#wsade">WSADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Fang_2020_CVPR,
    author = "Fang, Liangji and Jiang, Qinhong and Shi, Jianping and Zhou, Bolei",
    title = "{TPNet}: Trajectory Proposal Network for Motion Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Gao et al., "VectorNet: Encoding HD Maps and Agent Dynamics From Vectorized Representation", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Gao_VectorNet_Encoding_HD_Maps_and_Agent_Dynamics_From_Vectorized_Representation_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.04259.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2020_CVPR,
    author = "Gao, Jiyang and Sun, Chen and Zhao, Hang and Shen, Yi and Anguelov, Dragomir and Li, Congcong and Schmid, Cordelia",
    title = "VectorNet: Encoding HD Maps and Agent Dynamics From Vectorized Representation",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Hu et al., "Collaborative Motion Prediction via Neural Motion Message Passing", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Hu_Collaborative_Motion_Prediction_via_Neural_Motion_Message_Passing_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.06594.pdf>arxiv</a> <a href=https://github.com/PhyllisH/NMMP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2020_CVPR,
    author = "Hu, Yue and Chen, Siheng and Zhang, Ya and Gu, Xiao",
    title = "Collaborative Motion Prediction via Neural Motion Message Passing",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Liang et al., "PnPNet: End-to-End Perception and Prediction With Tracking in the Loop", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Liang_PnPNet_End-to-End_Perception_and_Prediction_With_Tracking_in_the_Loop_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.14711.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liang_2020_CVPR,
    author = "Liang, Ming and Yang, Bin and Zeng, Wenyuan and Chen, Yun and Hu, Rui and Casas, Sergio and Urtasun, Raquel",
    title = "{PnPNet}: End-to-End Perception and Prediction With Tracking in the Loop",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Makansi et al., "Multimodal Future Localization and Emergence Prediction for Objects in Egocentric View With a Reachability Prior", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Makansi_Multimodal_Future_Localization_and_Emergence_Prediction_for_Objects_in_Egocentric_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.04700.pdf>arxiv</a> <a href=https://github.com/lmb-freiburg/FLN-EPN-RPN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#fit">FIT</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#mapillary_vistas">Mapillary Vistas</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iou">IoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Makansi_2020_CVPR,
    author = "Makansi, Osama and Cicek, Ozgun and Buchicchio, Kevin and Brox, Thomas",
    title = "Multimodal Future Localization and Emergence Prediction for Objects in Egocentric View With a Reachability Prior",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Malla et al., "TITAN: Future Forecast Using Action Priors", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Malla_TITAN_Future_Forecast_Using_Action_Priors_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.13886.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#titan">TITAN</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rmse">RMSE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Malla_2020_CVPR,
    author = "Malla, Srikanth and Dariush, Behzad and Choi, Chiho",
    title = "{TITAN}: Future Forecast Using Action Priors",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Phan-Minh et al., "CoverNet: Multimodal Behavior Prediction Using Trajectory Sets", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Phan-Minh_CoverNet_Multimodal_Behavior_Prediction_Using_Trajectory_Sets_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.10298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Phan-Minh_2020_CVPR,
    author = "Phan-Minh, Tung and Grigore, Elena Corina and Boulton, Freddy A. and Beijbom, Oscar and Wolff, Eric M.",
    title = "{CoverNet}: Multimodal Behavior Prediction Using Trajectory Sets",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Sun et al., "Recursive Social Behavior Graph for Trajectory Prediction", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Sun_Recursive_Social_Behavior_Graph_for_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.10402.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2020_CVPR,
    author = "Sun, Jianhua and Jiang, Qinhong and Lu, Cewu",
    title = "Recursive Social Behavior Graph for Trajectory Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Liang et al., "The Garden of Forking Paths: Towards Multi-Future Trajectory Prediction", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Liang_The_Garden_of_Forking_Paths_Towards_Multi-Future_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.06445.pdf>arxiv</a> <a href=https://github.com/JunweiLiang/Multiverse>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#virat/actev">VIRAT/ActEV</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#forking_paths">Forking Paths</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liang_2020_CVPR_2,
    author = "Liang, Junwei and Jiang, Lu and Murphy, Kevin and Yu, Ting and Hauptmann, Alexander",
    title = "The Garden of Forking Paths: Towards Multi-Future Trajectory Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Liang et al., "Learning Lane Graph Representations for Motion Forecasting", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470528.pdf>paper</a> <a href=https://arxiv.org/pdf/2007.13732.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liang_2020_ECCV_2,
    author = "Liang, Ming and Yang, Bin and Hu, Rui and Chen, Yun and Liao, Renjie and Feng, Song and Urtasun, Raquel",
    title = "Learning Lane Graph Representations for Motion Forecasting",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Liu et al., "SMART: Simultaneous Multi-Agent Recurrent Trajectory Prediction", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123720460.pdf>paper</a> <a href=https://arxiv.org/pdf/2007.13078.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2020_ECCV_2,
    author = "Liu, Buyu and Pittaluga, Francesco and Chandraker, Manmohan and others",
    title = "{SMART}: Simultaneous Multi-Agent Recurrent Trajectory Prediction",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Chen et al., "Group Activity Prediction with Sequential Relational Anticipation Model", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660579.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.02441.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#volleyball">Volleyball</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2020_ECCV,
    author = "Chen, Junwen and Bao, Wentao and Kong, Yu",
    title = "Group Activity Prediction with Sequential Relational Anticipation Model",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Ma et al., "AutoTrajectory: Label-free Trajectory Extraction and Prediction from Videos using Dynamic Points", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580630.pdf>paper</a> <a href=https://arxiv.org/pdf/2007.05719.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ma_2020_ECCV,
    author = "Ma, Yuexin and Zhu, Xinge and Cheng, Xinjing and Yang, Ruigang and Liu, Jiming and Manocha, Dinesh",
    title = "{AutoTrajectory}: Label-free Trajectory Extraction and Prediction from Videos using Dynamic Points",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Park et al., "Diverse and Admissible Trajectory Forecasting through Multimodal Context Understanding", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123560273.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.03212.pdf>arxiv</a> <a href=https://github.com/kami93/CMU-DATF>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#meanfde">meanFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#meanade">meanADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Park_2020_ECCV,
    author = "Park, Seong Hyeon and Lee, Gyubok and Bhat, Manoj and Seo, Jimin and Kang, Minseok and Francis, Jonathan and Jadhav, Ashwin R and Liang, Paul Pu and Morency, Louis-Philippe",
    title = "Diverse and Admissible Trajectory Forecasting through Multimodal Context Understanding",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Salzmann et al., "Trajectron++: Multi-agent Generative Trajectory Forecasting with Heterogeneous Data for Control", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123630664.pdf>paper</a> <a href=https://arxiv.org/pdf/2001.03093.pdf>arxiv</a> <a href=https://github.com/StanfordASL/Trajectron-plus-plus>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Salzmann_2020_ECCV,
    author = "Salzmann, Tim and Ivanovic, Boris and Chakravarty, Punarjay and Pavone, Marco",
    title = "Trajectron++: Multi-agent Generative Trajectory Forecasting with Heterogeneous Data for Control",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wong et al., "Testing the Safety of Self-driving Vehicles by Simulating Perception and Prediction", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123710307.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.06020.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wong_2020_ECCV,
    author = "Wong, Kelvin and Zhang, Qiang and Liang, Ming and Yang, Bin and Liao, Renjie and Sadat, Abbas and Urtasun, Raquel",
    title = "Testing the Safety of Self-driving Vehicles by Simulating Perception and Prediction",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Yu et al., "Spatio-Temporal Graph Transformer Networks for Pedestrian Trajectory Prediction", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123570494.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.08514.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yu_2020_ECCV,
    author = "Yu, Cunjun and Ma, Xiao and Ren, Jiawei and Zhao, Haiyu and Yi, Shuai",
    title = "Spatio-Temporal Graph Transformer Networks for Pedestrian Trajectory Prediction",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Biktairov et al., "PRANK: Motion Prediction Based on RANKing", NeurIPS, 2020.</em></strong> <a href=https://papers.nips.cc/paper/2020/file/1b0251ccb8bd5f9ccf444e4bda7713e3-Paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2010.12007.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#ll">LL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Biktairov_2020_NeurIPS,
    author = "Biktairov, Yuriy and Stebelev, Maxim and Rudenko, Irina and Shliazhko, Oleh and Yangel, Boris",
    booktitle = "NeurIPS",
    title = "{PRANK}: Motion Prediction Based on {RANKing}",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Huynh et al., "AOL: Adaptive Online Learning for Human Trajectory Prediction in Dynamic Video Scenes", BMVC, 2020.</em></strong> <a href=https://www.bmvc2020-conference.com/assets/papers/0493.pdf>paper</a> <a href=https://arxiv.org/pdf/2002.06666.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth_pedestrian">ETH Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Huynh_2020_BMVC,
    author = "Huynh, Manh and Alaghband, Gita",
    title = "{AOL}: Adaptive Online Learning for Human Trajectory Prediction in Dynamic Video Scenes",
    booktitle = "BMVC",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Haddad et al., "Self-Growing Spatial Graph Networks for Pedestrian Trajectory Prediction", WACV, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Haddad_Self-Growing_Spatial_Graph_Networks_for_Pedestrian_Trajectory_Prediction_WACV_2020_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Haddad_2020_WACV,
    author = "Haddad, Sirin and Lam, Siew-Kei",
    title = "Self-Growing Spatial Graph Networks for Pedestrian Trajectory Prediction",
    booktitle = "WACV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Styles et al., "Multiple Object Forecasting: Predicting Future Object Locations in Diverse Environments", WACV, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Styles_Multiple_Object_Forecasting_Predicting_Future_Object_Locations_in_Diverse_Environments_WACV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1909.11944.pdf>arxiv</a> <a href=https://github.com/olly-styles/Multiple-Object-Forecasting>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#citywalks">CityWalks</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#aiou">AIoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Styles_2020_WACV,
    author = "Styles, Oliver and Sanchez, Victor and Guha, Tanaya",
    title = "Multiple Object Forecasting: Predicting Future Object Locations in Diverse Environments",
    booktitle = "WACV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Katyal et al., "Intent-Aware Pedestrian Prediction for Adaptive Crowd Navigation", ICRA, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9197434>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Katyal_2020_ICRA,
    author = "Katyal, K. D. and Hager, G. D. and Huang, C. -M.",
    booktitle = "ICRA",
    title = "Intent-Aware Pedestrian Prediction for Adaptive Crowd Navigation",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Kawasaki et al., "Multimodal Trajectory Predictions for Urban Environments Using Geometric Relationships between a Vehicle and Lanes", ICRA, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9196738>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kawasaki_2020_ICRA,
    author = "Kawasaki, A. and Seki, A.",
    booktitle = "ICRA",
    title = "Multimodal Trajectory Predictions for Urban Environments Using Geometric Relationships between a Vehicle and Lanes",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Mercat et al., "Multi-Head Attention for Multi-Modal Joint Vehicle Motion Forecasting", ICRA, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9197340>paper</a> <a href=https://arxiv.org/pdf/1910.03650.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mercat_2020_ICRA,
    author = "Mercat, J. and Gilles, T. and Zoghby, N. El and Sandou, G. and Beauvois, D. and Gil, G. P.",
    booktitle = "ICRA",
    title = "Multi-Head Attention for Multi-Modal Joint Vehicle Motion Forecasting",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Ansari et al., "Simple means Faster: Real-Time Human Motion Forecasting in Monocular First Person Videos on CPU", IROS, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9340999>paper</a> <a href=https://arxiv.org/pdf/2011.04943.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#fpl">FPL</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#citywalks">CityWalks</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ansari_2020_IROS,
    author = "Ansari, J. A. and Bhowmick, B.",
    booktitle = "IROS",
    title = "Simple means Faster: Real-Time Human Motion Forecasting in Monocular First Person Videos on {CPU}",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Dwivedi et al., "SSP: Single Shot Future Trajectory Prediction", IROS, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9340754>paper</a> <a href=https://arxiv.org/pdf/2004.05846.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Dwivedi_2020_IROS,
    author = "Dwivedi, I. and Malla, S. and Dariush, B. and Choi, C.",
    booktitle = "IROS",
    title = "{SSP}: Single Shot Future Trajectory Prediction",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Li et al., "End-to-end Contextual Perception and Prediction with Interaction Transformer", IROS, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9341392>paper</a> <a href=https://arxiv.org/pdf/2008.05927.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#tcr">TCR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2020_IROS,
    author = "Li, L. L. and Yang, B. and Liang, M. and Zeng, W. and Ren, M. and Segal, S. and Urtasun, R.",
    booktitle = "IROS",
    title = "End-to-end Contextual Perception and Prediction with Interaction Transformer",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Luo et al., "Probabilistic Multi-modal Trajectory Prediction with Lane Attention for Autonomous Vehicles", IROS, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9341034>paper</a> <a href=https://arxiv.org/pdf/2007.02574.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Luo_2020_IROS,
    author = "Luo, C. and Sun, L. and Dabiri, D. and Yuille, A.",
    booktitle = "IROS",
    title = "Probabilistic Multi-modal Trajectory Prediction with Lane Attention for Autonomous Vehicles",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Pan et al., "Lane-Attention: Predicting Vehicles’ Moving Trajectories by Learning Their Attention Over Lanes", IROS, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9341233>paper</a> <a href=https://arxiv.org/pdf/1909.13377.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Pan_2020_IROS,
    author = "Pan, Jiacheng and Sun, Hongyi and Xu, Kecheng and Jiang, Yifei and Xiao, Xiangquan and Hu, Jiangtao and Miao, Jinghao",
    booktitle = "IROS",
    title = "{Lane-Attention}: Predicting Vehicles’ Moving Trajectories by Learning Their Attention Over Lanes",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Berlati et al., "Ambiguity in Sequential Data: Predicting Uncertain Futures With Recurrent Models", RAL, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9001185>paper</a> <a href=https://arxiv.org/pdf/2003.10381.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Berlati_2020_RAL,
    author = "Berlati, A. and Scheel, O. and Stefano, L. D. and Tombari, F.",
    journal = "RAL",
    title = "Ambiguity in Sequential Data: Predicting Uncertain Futures With Recurrent Models",
    year = "2020",
    volume = "5",
    number = "2",
    pages = "2935-2942"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Chandra et al., "Forecasting Trajectory and Behavior of Road-Agents Using Spectral Clustering in Graph-LSTMs", RAL, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9126166>paper</a> <a href=https://arxiv.org/pdf/1912.01118.pdf>arxiv</a> <a href=https://github.com/rohanchandra30/Spectral-Trajectory-and-Behavior-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Chandra_2020_RAL,
    author = "Chandra, R. and Guan, T. and Panuganti, S. and Mittal, T. and Bhattacharya, U. and Bera, A. and Manocha, D.",
    journal = "RAL",
    title = "Forecasting Trajectory and Behavior of Road-Agents Using Spectral Clustering in {Graph-LSTMs}",
    year = "2020",
    volume = "5",
    number = "3",
    pages = "4882-4890"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Eiffert et al., "Probabilistic Crowd GAN: Multimodal Pedestrian Trajectory Prediction Using a Graph Vehicle-Pedestrian Attention Network", RAL, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9123560>paper</a> <a href=https://arxiv.org/pdf/2006.12906.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#usyd">USyd</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#vci">VCI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mhd">MHD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Eiffert_2020_RAL,
    author = "Eiffert, S. and Li, K. and Shan, M. and Worrall, S. and Sukkarieh, S. and Nebot, E.",
    journal = "RAL",
    title = "Probabilistic Crowd {GAN}: Multimodal Pedestrian Trajectory Prediction Using a Graph Vehicle-Pedestrian Attention Network",
    year = "2020",
    volume = "5",
    number = "4",
    pages = "5026-5033"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Gilitschenski et al., "Deep Context Maps: Agent Trajectory Prediction Using Location-Specific Latent Maps", RAL, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9126143>paper</a> <a href=https://arxiv.org/pdf/1912.06785.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Gilitschenski_2020_RAL,
    author = "Gilitschenski, I. and Rosman, G. and Gupta, A. and Karaman, S. and Rus, D.",
    journal = "RAL",
    title = "Deep Context Maps: Agent Trajectory Prediction Using Location-Specific Latent Maps",
    year = "2020",
    volume = "5",
    number = "4",
    pages = "5097-5104"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Ridel et al., "Scene Compliant Trajectory Forecast With Agent-Centric Spatio-Temporal Grids", RAL, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9000540>paper</a> <a href=https://arxiv.org/pdf/1909.03895.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Ridel_2020_RAL,
    author = "Ridel, D. and Deo, N. and Wolf, D. and Trivedi, M.",
    journal = "RAL",
    title = "Scene Compliant Trajectory Forecast With Agent-Centric Spatio-Temporal Grids",
    year = "2020",
    volume = "5",
    number = "2",
    pages = "2816-2823"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Schöller et al., "What the Constant Velocity Model Can Teach Us About Pedestrian Motion Prediction", RAL, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/8972605>paper</a> <a href=https://arxiv.org/pdf/1903.07933.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Scholler_2020_RAL,
    author = "Schöller, C. and Aravantinos, V. and Lay, F. and Knoll, A.",
    journal = "RAL",
    title = "What the Constant Velocity Model Can Teach Us About Pedestrian Motion Prediction",
    year = "2020",
    volume = "5",
    number = "2",
    pages = "1696-1703"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Choi et al., "DROGON: A Trajectory Prediction Model Based on Intention-conditioned Behavior Reasoning", CoRL, 2020.</em></strong> <a href=https://proceedings.mlr.press/v155/choi21a/choi21a.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.00024.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#maxd">MaxD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Choi_2020_CORL,
    author = "Choi, Chiho and Malla, Srikanth and Patil, Abhishek and Choi, J Hee",
    title = "{DROGON}: A Trajectory Prediction Model Based on Intention-conditioned Behavior Reasoning",
    booktitle = "CoRL",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Ivanovic et al., "MATS: An Interpretable Trajectory Forecasting Representation for Planning and Control", CoRL, 2020.</em></strong> <a href=https://proceedings.mlr.press/v155/ivanovic21a/ivanovic21a.pdf>paper</a> <a href=https://arxiv.org/pdf/2009.07517.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ivanovic_2020_CORL,
    author = "Ivanovic, Boris and Elhafsi, Amine and Rosman, Guy and Gaidon, Adrien and Pavone, Marco",
    title = "{MATS}: An Interpretable Trajectory Forecasting Representation for Planning and Control",
    booktitle = "CoRL",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Li et al., "Differentiable Logic Layer for Rule Guided Trajectory Prediction", CoRL, 2020.</em></strong> <a href=https://proceedings.mlr.press/v155/li21b/li21b.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#maxd">MaxD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2020_CORL,
    author = "Li, Xiao and Rosman, Guy and Gilitschenski, Igor and DeCastro, Jonathan and Vasile, Cristian-Ioan and Rus, Sertac Karaman Daniela",
    title = "Differentiable Logic Layer for Rule Guided Trajectory Prediction",
    year = "2020",
    booktitle = "CoRL"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Shah et al., "LiRaNet: End-to-End Trajectory Prediction using Spatio-Temporal Radar Fusion", CoRL, 2020.</em></strong> <a href=https://proceedings.mlr.press/v155/shah21a/shah21a.pdf>paper</a> <a href=https://arxiv.org/pdf/2010.00731.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shah_2020_CORL,
    author = "Shah, Meet and Huang, Zhiling and Laddha, Ankit and Langford, Matthew and Barber, Blake and Zhang, Sidney and Vallespi-Gonzalez, Carlos and Urtasun, Raquel",
    title = "{LiRaNet}: End-to-End Trajectory Prediction using Spatio-Temporal Radar Fusion",
    booktitle = "CoRL",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Chandra et al., "TraPHic: Trajectory Prediction In Dense And Heterogeneous Traffic Using Weighted Interactions", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Chandra_TraPHic_Trajectory_Prediction_in_Dense_and_Heterogeneous_Traffic_Using_Weighted_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.04767.pdf>arxiv</a> <a href=https://go.umd.edu/TraPHic>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#traf">TRAF</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chandra_2019_CVPR,
    author = "Chandra, Rohan and Bhattacharya, Uttaran and Bera, Aniket and Manocha, Dinesh",
    title = "{TraPHic}: Trajectory Prediction In Dense And Heterogeneous Traffic Using Weighted Interactions",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Liang et al., "Peeking Into The Future: Predicting Future Person Activities And Locations In Videos", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Liang_Peeking_Into_the_Future_Predicting_Future_Person_Activities_and_Locations_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1902.03748.pdf>arxiv</a> <a href=https://github.com/google/next-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#virat/actev">VIRAT/ActEV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liang_2019_CVPR,
    author = "Liang, Junwei and Jiang, Lu and Niebles, Juan Carlos and Hauptmann, Alexander G. and Fei-Fei, Li",
    title = "Peeking Into The Future: Predicting Future Person Activities And Locations In Videos",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Makansi et al., "Overcoming Limitations of Mixture Density Networks: A Sampling and Fitting Framework for Multimodal Future Prediction", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Makansi_Overcoming_Limitations_of_Mixture_Density_Networks_A_Sampling_and_Fitting_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.03631.pdf>arxiv</a> <a href=https://github.com/lmb-freiburg/Multimodal-Future-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cpi">CPI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#emd">EMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Makansi_2019_CVPR,
    author = "Makansi, Osama and Ilg, Eddy and Cicek, Ozgun and Brox, Thomas",
    title = "Overcoming Limitations of Mixture Density Networks: A Sampling and Fitting Framework for Multimodal Future Prediction",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhang et al., "SR-LSTM: State Refinement For LSTM Towards Pedestrian Trajectory Prediction", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_SR-LSTM_State_Refinement_for_LSTM_Towards_Pedestrian_Trajectory_Prediction_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1903.02793.pdf>arxiv</a> <a href=https://github.com/zhangpur/SR-LSTM>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2019_CVPR,
    author = "Zhang, Pu and Ouyang, Wanli and Zhang, Pengfei and Xue, Jianru and Zheng, Nanning",
    title = "{SR-LSTM}: State Refinement For {LSTM} Towards Pedestrian Trajectory Prediction",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Bi et al., "Joint Prediction For Kinematic Trajectories In Vehicle-Pedestrian-Mixed Scenes", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Bi_Joint_Prediction_for_Kinematic_Trajectories_in_Vehicle-Pedestrian-Mixed_Scenes_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bi_2019_ICCV,
    author = "Bi, Huikun and Fang, Zhong and Mao, Tianlu and Wang, Zhaoqi and Deng, Zhigang",
    title = "Joint Prediction For Kinematic Trajectories In Vehicle-Pedestrian-Mixed Scenes",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Choi et al., "Looking To Relations For Future Trajectory Forecast", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Choi_Looking_to_Relations_for_Future_Trajectory_Forecast_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.08855.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Choi_2019_ICCV,
    author = "Choi, Chiho and Dariush, Behzad",
    title = "Looking To Relations For Future Trajectory Forecast",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Ivanovic et al., "The Trajectron: Probabilistic Multi-Agent Trajectory Modeling With Dynamic Spatiotemporal Graphs", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ivanovic_The_Trajectron_Probabilistic_Multi-Agent_Trajectory_Modeling_With_Dynamic_Spatiotemporal_Graphs_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1810.05993.pdf>arxiv</a> <a href=https://github.com/StanfordASL/Trajectron>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ivanovic_2019_ICCV,
    author = "Ivanovic, Boris and Pavone, Marco",
    title = "The Trajectron: Probabilistic Multi-Agent Trajectory Modeling With Dynamic Spatiotemporal Graphs",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Rasouli et al., "PIE: A Large-Scale Dataset And Models For Pedestrian Intention Estimation And Trajectory Prediction", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.pdf>paper</a> <a href=https://github.com/aras62/PIEPredict>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rasouli_2019_ICCV,
    author = "Rasouli, Amir and Kotseruba, Iuliia and Kunic, Toni and Tsotsos, John K.",
    title = "{PIE}: A Large-Scale Dataset And Models For Pedestrian Intention Estimation And Trajectory Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Kosaraju et al., "Social-BiGAT: Multimodal Trajectory Forecasting Using Bicycle-GAN And Graph Attention Networks", NeurIPS, 2019.</em></strong> <a href=http://papers.nips.cc/paper/8308-social-bigat-multimodal-trajectory-forecasting-using-bicycle-gan-and-graph-attention-networks.pdf>paper</a> <a href=https://arxiv.org/pdf/1907.03395.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kosaraju_2019_NeurIPS,
    author = "Kosaraju, Vineet and Sadeghian, Amir and Mart\'\in-Mart\'\in, Roberto and Reid, Ian and Rezatofighi, Hamid and Savarese, Silvio",
    title = "{Social-BiGAT}: Multimodal Trajectory Forecasting Using {Bicycle-GAN} And Graph Attention Networks",
    booktitle = "NeurIPS",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Yao et al., "Egocentric Vision-based Future Vehicle Localization for Intelligent Driving Assistance Systems", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8794474>paper</a> <a href=https://arxiv.org/pdf/1809.07408.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#hev-i">HEV-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yao_2019_ICRA,
    author = "Yao, Y. and Xu, M. and Choi, C. and Crandall, D. J. and Atkins, E. M. and Dariush, B.",
    booktitle = "ICRA",
    title = "Egocentric Vision-based Future Vehicle Localization for Intelligent Driving Assistance Systems",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Anderson et al., "Stochastic Sampling Simulation For Pedestrian Trajectory Prediction", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8967857>paper</a> <a href=https://arxiv.org/pdf/1903.01860.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Anderson_2019_IROS,
    author = "Anderson, Cyrus and Du, Xiaoxiao and Vasudevan, Ram and Johnson-Roberson, Matthew",
    booktitle = "IROS",
    title = "Stochastic Sampling Simulation For Pedestrian Trajectory Prediction",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Yao et al., "Unsupervised Traffic Accident Detection in First-Person Videos", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8967556>paper</a> <a href=https://arxiv.org/pdf/1903.00618.pdf>arxiv</a> <a href=https://github.com/MoonBlvd/tad-IROS2019>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#hev-i">HEV-I</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#a3d">A3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yao_2019_IROS,
    author = "Yao, Y. and Xu, M. and Wang, Y. and Crandall, D. J. and Atkins, E. M.",
    booktitle = "IROS",
    title = "Unsupervised Traffic Accident Detection in First-Person Videos",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhu et al., "StarNet: Pedestrian Trajectory Prediction Using Deep Neural Network In Star Topology", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8967811>paper</a> <a href=https://arxiv.org/pdf/1906.01797.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhu_2019_IROS,
    author = "Zhu, Yanliang and Qian, Deheng and Ren, Dongchun and Xia, Huaxia",
    booktitle = "IROS",
    title = "{StarNet}: Pedestrian Trajectory Prediction Using Deep Neural Network In Star Topology",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Chai et al., "MultiPath: Multiple Probabilistic Anchor Trajectory Hypotheses For Behavior Prediction", CoRL, 2019.</em></strong> <a href=http://proceedings.mlr.press/v100/chai20a/chai20a.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.05449.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#ll">LL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chai_2019_CORL,
    author = "Chai, Yuning and Sapp, Benjamin and Bansal, Mayank and Anguelov, Dragomir",
    title = "{MultiPath}: Multiple Probabilistic Anchor Trajectory Hypotheses For Behavior Prediction",
    booktitle = "CoRL",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Jain et al., "Discrete Residual Flow For Probabilistic Pedestrian Behavior Prediction", CoRL, 2019.</em></strong> <a href=http://proceedings.mlr.press/v100/jain20a/jain20a.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.08041.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ece">ECE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jain_2019_CORL,
    author = "Jain, Ajay and Casas, Sergio and Liao, Renjie and Xiong, Yuwen and Feng, Song and Segal, Sean and Urtasun, Raquel",
    title = "Discrete Residual Flow For Probabilistic Pedestrian Behavior Prediction",
    booktitle = "CoRL",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhi et al., "Kernel Trajectory Maps For Multi-Modal Probabilistic Motion Prediction", CoRL, 2019.</em></strong> <a href=http://proceedings.mlr.press/v100/zhi20a/zhi20a.pdf>paper</a> <a href=https://arxiv.org/pdf/1907.05127.pdf>arxiv</a> <a href=https://github.com/wzhi/KernelTrajectoryMaps>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eifp">EIFP</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#lankershim_boulevard">Lankershim Boulevard</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhi_2019_CORL,
    author = "Zhi, Weiming and Ott, Lionel and Ramos, Fabio",
    title = "Kernel Trajectory Maps For Multi-Modal Probabilistic Motion Prediction",
    booktitle = "CoRL",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Xue et al., "Location-Velocity Attention For Pedestrian Trajectory Prediction", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8659060>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pets2009">PETS2009</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xue_2019_WACV,
    author = "Xue, H. and Huynh, D. and Reynolds, M.",
    booktitle = "WACV",
    title = "Location-Velocity Attention For Pedestrian Trajectory Prediction",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Gupta et al., "Social GAN: Socially Acceptable Trajectories With Generative Adversarial Networks", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Gupta_Social_GAN_Socially_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1803.10892.pdf>arxiv</a> <a href=https://github.com/agrimgupta92/sgan>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gupta_2018_CVPR,
    author = "Gupta, Agrim and Johnson, Justin and Fei-Fei, Li and Savarese, Silvio and Alahi, Alexandre",
    title = "Social {GAN}: Socially Acceptable Trajectories With Generative Adversarial Networks",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Hasan et al., "MX-LSTM: Mixing Tracklets And Vislets To Jointly Forecast Trajectories And Head Poses", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Hasan_MX-LSTM_Mixing_Tracklets_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1805.00652.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#town_center">Town Center</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hasan_2018_CVPR,
    author = "Hasan, Irtiza and Setti, Francesco and Tsesmelis, Theodore and Del Bue, Alessio and Galasso, Fabio and Cristani, Marco",
    title = "{MX-LSTM}: Mixing Tracklets And Vislets To Jointly Forecast Trajectories And Head Poses",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Yagi et al., "Future Person Localization in First-Person Videos", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Yagi_Future_Person_Localization_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1711.11217.pdf>arxiv</a> <a href=https://github.com/takumayagi/fpl>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#fpl">FPL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yagi_2018_CVPR,
    author = "Yagi, Takuma and Mangalam, Karttikeya and Yonetani, Ryo and Sato, Yoichi",
    title = "Future Person Localization in First-Person Videos",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Xu et al., "Encoding Crowd Interaction With Deep Neural Network For Pedestrian Trajectory Prediction", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/2136.pdf>paper</a> <a href=https://github.com/svip-lab/CIDNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cuhk_avenue">CUHK Avenue</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ande">ANDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2018_CVPR_encoding,
    author = "Xu, Yanyu and Piao, Zhixin and Gao, Shenghua",
    title = "Encoding Crowd Interaction With Deep Neural Network For Pedestrian Trajectory Prediction",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Sadeghian et al., "CAR-Net: Clairvoyant Attentive Recurrent Network", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Amir_Sadeghian_CAR-Net_Clairvoyant_Attentive_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1711.10061.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sadeghian_2018_ECCV,
    author = "Sadeghian, Amir and Legros, Ferdinand and Voisin, Maxime and Vesel, Ricky and Alahi, Alexandre and Savarese, Silvio",
    title = "{CAR-Net}: Clairvoyant Attentive Recurrent Network",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Fernando et al., "GD-GAN: Generative Adversarial Networks For Trajectory Prediction And Group Detection In Crowds", ACCV, 2018.</em></strong> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20887-5_20>paper</a> <a href=https://arxiv.org/pdf/1812.07667.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Fernando_2018_ACCV,
    author = "Fernando, Tharindu and Denman, Simon and Sridharan, Sridha and Fookes, Clinton",
    editor = "Jawahar, C. V. and Li, Hongdong and Mori, Greg and Schindler, Konrad",
    title = "{GD-GAN}: Generative Adversarial Networks For Trajectory Prediction And Group Detection In Crowds",
    booktitle = "ACCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Vemula et al., "Social Attention: Modeling Attention In Human Crowds", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8460504>paper</a> <a href=https://arxiv.org/pdf/1710.04689.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Vemula_2018_ICRA,
    author = "Vemula, Anirudh and Muelling, Katharina and Oh, Jean",
    title = "Social Attention: Modeling Attention In Human Crowds",
    booktitle = "ICRA",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Hasan et al., "Seeing Is Believing: Pedestrian Trajectory Forecasting Using Visual Frustum Of Attention", WACV, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8354238>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#town_center">Town Center</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hasan_2018_WACV,
    author = "Hasan, I. and Setti, F. and Tsesmelis, T. and Del Bue, A. and Cristani, M. and Galasso, F.",
    booktitle = "WACV",
    title = "{Seeing Is Believing}: Pedestrian Trajectory Forecasting Using Visual Frustum Of Attention",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Xue et al., "SS-LSTM: A Hierarchical LSTM Model For Pedestrian Trajectory Prediction", WACV, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8354239>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xue_2018_WACV,
    author = "Xue, H. and Huynh, D. Q. and Reynolds, M.",
    booktitle = "WACV",
    title = "{SS-LSTM}: A Hierarchical {LSTM} Model For Pedestrian Trajectory Prediction",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Alahi et al., "Social LSTM: Human Trajectory Prediction In Crowded Spaces", CVPR, 2016.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Alahi_Social_LSTM_Human_CVPR_2016_paper.pdf>paper</a> <a href=https://github.com/quancore/social-lstm>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ande">ANDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Alahi_2016_CVPR,
    author = "Alahi, Alexandre and Goel, Kratarth and Ramanathan, Vignesh and Robicquet, Alexandre and Fei-Fei, Li and Savarese, Silvio",
    title = "Social {LSTM}: Human Trajectory Prediction In Crowded Spaces",
    booktitle = "CVPR",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Yi et al., "Pedestrian Behavior Understanding And Prediction With Deep Neural Networks", ECCV, 2016.</em></strong> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46448-0_16>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yi_2016_ECCV,
    author = "Yi, Shuai and Li, Hongsheng and Wang, Xiaogang",
    editor = "Leibe, Bastian and Matas, Jiri and Sebe, Nicu and Welling, Max",
    title = "Pedestrian Behavior Understanding And Prediction With Deep Neural Networks",
    booktitle = "ECCV",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=fgt></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Averge Forgeting (FGT)</strong><small> [22]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Ma et al., "Continual Multi-Agent Interaction Behavior Prediction With Conditional Generative Memory", RAL, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9512468>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#ind">inD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#round">rounD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fgt">FGT</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#aer">AER</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Ma_Continual_2021_RAL,
    author = "Ma, Hengbo and Sun, Yaofeng and Li, Jiachen and Tomizuka, Masayoshi and Choi, Chiho",
    journal = "RAL",
    title = "Continual Multi-Agent Interaction Behavior Prediction With Conditional Generative Memory",
    year = "2021",
    volume = "6",
    number = "4",
    pages = "8410-8417"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=fiou></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Final IoU (FIoU)</strong><small> [14]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Rasouli et al., "PedFormer: Pedestrian Behavior Prediction via Cross-Modal Attention Modulation and Gated Multitask Learning", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10161318>paper</a> <a href=https://arxiv.org/pdf/2210.07886.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#frb">FRB</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#arb">ARB</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rasouli_2023_ICRA,
    author = "Rasouli, Amir and Kotseruba, Iuliia",
    title = "PedFormer: Pedestrian Behavior Prediction via Cross-Modal Attention Modulation and Gated Multitask Learning",
    booktitle = "ICRA",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Chen et al., "S2F2: Single-Stage Flow Forecasting for Future Multiple Trajectories Prediction", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820593.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#mot">MOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iou">IoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2022_ECCV,
    author = "Chen, Yu-Wen and Yang, Hsuan-Kung and Chiu, Chu-Chi and Lee, Chun-Yi",
    title = "{S2F2}: Single-Stage Flow Forecasting for Future Multiple Trajectories Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wang et al., "Stepwise Goal-Driven Networks for Trajectory Prediction", RAL, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/document/9691856>paper</a> <a href=https://arxiv.org/pdf/2103.14107.pdf>arxiv</a> <a href=https://github.com/ChuhuaW/SGNet.pytorch>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#hev-i">HEV-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Wang_2022_RAL_2,
    author = "Wang, Chuhua and Wang, Yuchen and Xu, Mingze and Crandall, David J.",
    journal = "RAL",
    title = "Stepwise Goal-Driven Networks for Trajectory Prediction",
    year = "2022",
    volume = "7",
    number = "2",
    pages = "2716-2723"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Qiu et al., "Indoor Future Person Localization from an Egocentric Wearable Camera", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9635868>paper</a> <a href=https://arxiv.org/pdf/2103.04019.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eilt">EILT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#miou">MIoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Qiu_2021_IROS,
    author = "Qiu, Jianing and Lo, Frank P-W and Gu, Xiao and Sun, Yingnan and Jiang, Shuo and Lo, Benny",
    booktitle = "IROS",
    title = "Indoor Future Person Localization from an Egocentric Wearable Camera",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wang et al., "Group-based Motion Prediction for Navigation in Crowded Environments", CoRL, 2021.</em></strong> <a href=https://openreview.net/pdf?id=knObbYqSowX>paper</a> <a href=https://arxiv.org/pdf/2107.11637.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#miou">MIoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2021_CoRL,
    author = "Wang, Allan and Mavrogiannis, Christoforos and Steinfeld, Aaron",
    title = "Group-based Motion Prediction for Navigation in Crowded Environments",
    booktitle = "CoRL",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Malla et al., "TITAN: Future Forecast Using Action Priors", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Malla_TITAN_Future_Forecast_Using_Action_Priors_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.13886.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#titan">TITAN</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rmse">RMSE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Malla_2020_CVPR,
    author = "Malla, Srikanth and Dariush, Behzad and Choi, Chiho",
    title = "{TITAN}: Future Forecast Using Action Priors",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Styles et al., "Multiple Object Forecasting: Predicting Future Object Locations in Diverse Environments", WACV, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Styles_Multiple_Object_Forecasting_Predicting_Future_Object_Locations_in_Diverse_Environments_WACV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1909.11944.pdf>arxiv</a> <a href=https://github.com/olly-styles/Multiple-Object-Forecasting>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#citywalks">CityWalks</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#aiou">AIoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Styles_2020_WACV,
    author = "Styles, Oliver and Sanchez, Victor and Guha, Tanaya",
    title = "Multiple Object Forecasting: Predicting Future Object Locations in Diverse Environments",
    booktitle = "WACV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Yao et al., "Egocentric Vision-based Future Vehicle Localization for Intelligent Driving Assistance Systems", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8794474>paper</a> <a href=https://arxiv.org/pdf/1809.07408.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#hev-i">HEV-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yao_2019_ICRA,
    author = "Yao, Y. and Xu, M. and Choi, C. and Crandall, D. J. and Atkins, E. M. and Dariush, B.",
    booktitle = "ICRA",
    title = "Egocentric Vision-based Future Vehicle Localization for Intelligent Driving Assistance Systems",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Yao et al., "Unsupervised Traffic Accident Detection in First-Person Videos", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8967556>paper</a> <a href=https://arxiv.org/pdf/1903.00618.pdf>arxiv</a> <a href=https://github.com/MoonBlvd/tad-IROS2019>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#hev-i">HEV-I</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#a3d">A3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yao_2019_IROS,
    author = "Yao, Y. and Xu, M. and Wang, Y. and Crandall, D. J. and Atkins, E. M.",
    booktitle = "IROS",
    title = "Unsupervised Traffic Accident Detection in First-Person Videos",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=fle></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Final Lane Error (FLE)</strong><small> [22]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Casas et al., "The Importance of Prior Knowledge in Precise Multimodal Prediction", IROS, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9341199>paper</a> <a href=https://arxiv.org/pdf/2006.02636.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fle">FLE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Casas_2020_IROS,
    author = "Casas, S. and Gulino, C. and Suo, S. and Urtasun, R.",
    booktitle = "IROS",
    title = "The Importance of Prior Knowledge in Precise Multimodal Prediction",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=fnm></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Fraction of Near Misses (FNM)</strong><small> [22]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Bai et al., "Intention-Aware Online POMDP Planning For Autonomous Driving In A Crowd", ICRA, 2015.</em></strong> <a href=https://ieeexplore.ieee.org/document/7139219>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fnm">FNM</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bai_2015_ICRA,
    author = "Bai, Haoyu and Cai, Shaojun and Ye, Nan and Hsu, David and Lee, Wee Sun",
    title = "Intention-Aware Online {POMDP} Planning For Autonomous Driving In A Crowd",
    booktitle = "ICRA",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=fpd></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Final Pairwise Displacement (FPD)</strong><small> [22]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Chen et al., "MGF: Mixed Gaussian Flow for Diverse Trajectory Prediction", NeurIPS, 2024.</em></strong> <a href=https://openreview.net/pdf?id=muYhNDlxWc>paper</a> <a href=https://arxiv.org/pdf/2402.12238>arxiv</a> <a href=https://github.com/mulplue/MGF>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fpd">FPD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#apd">APD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Chen_Mgf_2024_NeurIPS,
    author = "Chen, Jiahe and Cao, Jinkun and Lin, Dahua and Kitani, Kris M. and Pang, Jiangmiao",
    title = "{MGF}: Mixed Gaussian Flow for Diverse Trajectory Prediction",
    booktitle = "NeurIPS",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=frb></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Final RMSE of Bounding box (FRB)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Rasouli et al., "PedFormer: Pedestrian Behavior Prediction via Cross-Modal Attention Modulation and Gated Multitask Learning", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10161318>paper</a> <a href=https://arxiv.org/pdf/2210.07886.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#frb">FRB</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#arb">ARB</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rasouli_2023_ICRA,
    author = "Rasouli, Amir and Kotseruba, Iuliia",
    title = "PedFormer: Pedestrian Behavior Prediction via Cross-Modal Attention Modulation and Gated Multitask Learning",
    booktitle = "ICRA",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Rasouli et al., "Bifold and Semantic Reasoning for Pedestrian Behavior Prediction", ICCV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Rasouli_Bifold_and_Semantic_Reasoning_for_Pedestrian_Behavior_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2012.03298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#frb">FRB</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#arb">ARB</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rasouli_2021_ICCV,
    author = "Rasouli, Amir and Rohani, Mohsen and Luo, Jun",
    title = "Bifold and Semantic Reasoning for Pedestrian Behavior Prediction",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=fsd></a>
<details close>
<summary><em><l style="font-size:20px"><strong>FSD</strong><small> [22]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Weng et al., "PTP: Parallelized Tracking and Prediction With Graph Neural Networks and Diversity Sampling", RAL, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9387598&tag=1>paper</a> <a href=https://arxiv.org/pdf/2003.07847>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fsd">FSD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#asd">ASD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Weng_PTP_2021_RAL,
    author = "Weng, Xinshuo and Yuan, Ye and Kitani, Kris",
    journal = "RAL",
    title = "PTP: Parallelized Tracking and Prediction With Graph Neural Networks and Diversity Sampling",
    year = "2021",
    volume = "6",
    number = "3",
    pages = "4640-4647"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=hit_rate></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Hit Rate</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Hong et al., "Rules Of The Road: Predicting Driving Behavior With A Convolutional Model Of Semantic Interactions", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Hong_Rules_of_the_Road_Predicting_Driving_Behavior_With_a_Convolutional_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.08945.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#hit_rate">Hit Rate</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mined">minED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hong_2019_CVPR,
    author = "Hong, Joey and Sapp, Benjamin and Philbin, James",
    title = "Rules Of The Road: Predicting Driving Behavior With A Convolutional Model Of Semantic Interactions",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Chen et al., "Augmented Dictionary Learning For Motion Prediction", ICRA, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/7487407>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#hit_rate">Hit Rate</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2016_ICRA,
    author = "Chen, Y. F. and Liu, M. and How, J. P.",
    booktitle = "ICRA",
    title = "Augmented Dictionary Learning For Motion Prediction",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=hor></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Hard Off-road Rate (HOR)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Karim et al., "DESTINE: Dynamic Goal Queries with Temporal Transductive Alignment for Trajectory Prediction", ICRA, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10611124>paper</a> <a href=https://arxiv.org/pdf/2310.07438>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#sor">SOR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#hor">HOR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Karim_DESTINE_2024_ICRA,
    author = "Karim, Rezaul and Shabestary, Soheil Mohamad Alizadeh and Rasouli, Amir",
    booktitle = "ICRA",
    title = "DESTINE: Dynamic Goal Queries with Temporal Transductive Alignment for Trajectory Prediction",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Bahari et al., "Vehicle Trajectory Prediction Works, but Not Everywhere", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Bahari_Vehicle_Trajectory_Prediction_Works_but_Not_Everywhere_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2112.03909.pdf>arxiv</a> <a href=https://s-attack.github.io/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#sor">SOR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#hor">HOR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bahari_2022_CVPR,
    author = "Bahari, Mohammadhossein and Saadatnejad, Saeed and Rahimi, Ahmad and Shaverdikondori, Mohammad and Shahidzadeh, Amir Hossein and Moosavi-Dezfooli, Seyed-Mohsen and Alahi, Alexandre",
    title = "Vehicle Trajectory Prediction Works, but Not Everywhere",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=hp></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Human Probability (HP)</strong><small> [22]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Wang et al., "EscIRL: Evolving Self-Contrastive IRL for Trajectory Prediction in Autonomous Driving", CoRL, 2024.</em></strong> <a href=https://openreview.net/pdf?id=1IzW0aniyg>paper</a> <a href=https://github.com/SiyueWang-CiDi/EscIRL>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#citysim">CitySim</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#cr">CR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#hp">HP</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#afd">AFD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Wang_EscIRL_2024_CoRL,
    author = "Wang, Siyue and Chen, Zhaorun and Zhao, Zhuokai and Mao, Chaoli and Zhou, Yiyang and He, Jiayu and Hu, Albert Sibo",
    title = "Esc{IRL}: Evolving Self-Contrastive {IRL} for Trajectory Prediction in Autonomous Driving",
    booktitle = "CoRL",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=human></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Human Judgement (Human)</strong><small> [22]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Zhan et al., "Generating Multi-agent Trajectories using Programmatic Weak Supervision", ICLR, 2017.</em></strong> <a href=https://openreview.net/pdf?id=rkxw-hAcFQ>paper</a> <a href=https://arxiv.org/pdf/1803.07612.pdf>arxiv</a> <a href=https://github.com/ezhan94/multiagent-programmatic-supervision>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#ll">LL</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#human">Human</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Zhan_2017_ICLR,
    author = "Zhan, Eric and Zheng, Stephan and Yue, Yisong and Sha, Long and Lucey, Patrick",
    title = "Generating Multi-agent Trajectories using Programmatic Weak Supervision",
    booktitle = "ICLR",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=iminade></a>
<details close>
<summary><em><l style="font-size:20px"><strong>iminADE</strong><small> [22]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Rowe et al., "FJMP: Factorized Joint Multi-Agent Motion Prediction Over Learned Directed Acyclic Interaction Graphs", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Rowe_FJMP_Factorized_Joint_Multi-Agent_Motion_Prediction_Over_Learned_Directed_Acyclic_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2211.16197.pdf>arxiv</a> <a href=https://rluke22.github.io/FJMP/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#scr">SCR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#smr">SMR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iminfde">iminFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iminade">iminADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#cmr">CMR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#cross-col">Cross-Col</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rowe_2023_CVPR,
    author = "Rowe, Luke and Ethier, Martin and Dykhne, Eli-Henry and Czarnecki, Krzysztof",
    title = "FJMP: Factorized Joint Multi-Agent Motion Prediction Over Learned Directed Acyclic Interaction Graphs",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=iminfde></a>
<details close>
<summary><em><l style="font-size:20px"><strong>iminFDE</strong><small> [22]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Rowe et al., "FJMP: Factorized Joint Multi-Agent Motion Prediction Over Learned Directed Acyclic Interaction Graphs", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Rowe_FJMP_Factorized_Joint_Multi-Agent_Motion_Prediction_Over_Learned_Directed_Acyclic_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2211.16197.pdf>arxiv</a> <a href=https://rluke22.github.io/FJMP/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#scr">SCR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#smr">SMR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iminfde">iminFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iminade">iminADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#cmr">CMR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#cross-col">Cross-Col</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rowe_2023_CVPR,
    author = "Rowe, Luke and Ethier, Martin and Dykhne, Eli-Henry and Czarnecki, Krzysztof",
    title = "FJMP: Factorized Joint Multi-Agent Motion Prediction Over Learned Directed Acyclic Interaction Graphs",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=inace></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Image Normalized Average Centroid Error (INACE)</strong><small> [22]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Agarwal et al., "Predicting the Future Motion of Divers for Enhanced Underwater Human-Robot Collaboration", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636374>paper</a> <a href=https://github.com/IRVLab/diver-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#vdd-c">VDD-C</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#bnace">BNACE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#inace">INACE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Agarwal_2021_IROS,
    author = "Agarwal, Tanmay and Fulton, Michael and Sattar, Junaed",
    booktitle = "IROS",
    title = "Predicting the Future Motion of Divers for Enhanced Underwater Human-Robot Collaboration",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=iou></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Intersection over Union (IoU)</strong><small> [15]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Pasca et al., "Summarize the Past to Predict the Future: Natural Language Descriptions of Context Boost Multimodal Object Interaction Anticipation", CVPR, 2024.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Pasca_Summarize_the_Past_to_Predict_the_Future_Natural_Language_Descriptions_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2301.09209>arxiv</a> <a href=https://github.com/algvr/transfusion>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#ego4d">Ego4D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iou">IoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Pasca_Summarize_2024_CVPR,
    author = "Pasca, Razvan-George and Gavryushin, Alexey and Hamza, Muhammad and Kuo, Yen-Ling and Mo, Kaichun and Van Gool, Luc and Hilliges, Otmar and Wang, Xi",
    title = "Summarize the Past to Predict the Future: Natural Language Descriptions of Context Boost Multimodal Object Interaction Anticipation",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Fang et al., "TBP-Former: Learning Temporal Bird's-Eye-View Pyramid for Joint Perception and Prediction in Vision-Centric Autonomous Driving", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Fang_TBP-Former_Learning_Temporal_Birds-Eye-View_Pyramid_for_Joint_Perception_and_Prediction_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.09998.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/TBP-Former>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#vpq">VPQ</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Fang_2023_CVPR,
    author = "Fang, Shaoheng and Wang, Zi and Zhong, Yiqi and Ge, Junhao and Chen, Siheng",
    title = "TBP-Former: Learning Temporal Bird's-Eye-View Pyramid for Joint Perception and Prediction in Vision-Centric Autonomous Driving",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Chen et al., "S2F2: Single-Stage Flow Forecasting for Future Multiple Trajectories Prediction", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820593.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#mot">MOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iou">IoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2022_ECCV,
    author = "Chen, Yu-Wen and Yang, Hsuan-Kung and Chiu, Chu-Chi and Lee, Chun-Yi",
    title = "{S2F2}: Single-Stage Flow Forecasting for Future Multiple Trajectories Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Mahjourian et al., "Occupancy Flow Fields for Motion Forecasting in Autonomous Driving", RAL, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9713950>paper</a> <a href=https://arxiv.org/pdf/2203.03875>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#epe">EPE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Mahjourian_Occupancy_2022_RAL,
    author = "Mahjourian, Reza and Kim, Jinkyu and Chai, Yuning and Tan, Mingxing and Sapp, Ben and Anguelov, Dragomir",
    journal = "RAL",
    title = "Occupancy Flow Fields for Motion Forecasting in Autonomous Driving",
    year = "2022",
    volume = "7",
    number = "2",
    pages = "5639-5646"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Adeli et al., "TRiPOD: Human Trajectory and Pose Dynamics Forecasting in the Wild", ICCV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Adeli_TRiPOD_Human_Trajectory_and_Pose_Dynamics_Forecasting_in_the_Wild_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2104.04029.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#posetrack">PoseTrack</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#vam">VAM</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#vim">VIM</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Adeli_2021_ICCV,
    author = "Adeli, Vida and Ehsanpour, Mahsa and Reid, Ian and Niebles, Juan Carlos and Savarese, Silvio and Adeli, Ehsan and Rezatofighi, Hamid",
    title = "{TRiPOD}: Human Trajectory and Pose Dynamics Forecasting in the Wild",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Agarwal et al., "Predicting the Future Motion of Divers for Enhanced Underwater Human-Robot Collaboration", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636374>paper</a> <a href=https://github.com/IRVLab/diver-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#vdd-c">VDD-C</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#bnace">BNACE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#inace">INACE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Agarwal_2021_IROS,
    author = "Agarwal, Tanmay and Fulton, Michael and Sattar, Junaed",
    booktitle = "IROS",
    title = "Predicting the Future Motion of Divers for Enhanced Underwater Human-Robot Collaboration",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Makansi et al., "Multimodal Future Localization and Emergence Prediction for Objects in Egocentric View With a Reachability Prior", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Makansi_Multimodal_Future_Localization_and_Emergence_Prediction_for_Objects_in_Egocentric_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.04700.pdf>arxiv</a> <a href=https://github.com/lmb-freiburg/FLN-EPN-RPN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#fit">FIT</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#mapillary_vistas">Mapillary Vistas</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iou">IoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Makansi_2020_CVPR,
    author = "Makansi, Osama and Cicek, Ozgun and Buchicchio, Kevin and Brox, Thomas",
    title = "Multimodal Future Localization and Emergence Prediction for Objects in Egocentric View With a Reachability Prior",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Sun et al., "See the Future: A Semantic Segmentation Network Predicting Ego-Vehicle Trajectory With a Single Monocular Camera", RAL, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9004469>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Sun_See_2020_RAL,
    author = "Sun, Yuxiang and Zuo, Weixun and Liu, Ming",
    journal = "RAL",
    title = "See the Future: A Semantic Segmentation Network Predicting Ego-Vehicle Trajectory With a Single Monocular Camera",
    year = "2020",
    volume = "5",
    number = "2",
    pages = "3066-3073"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul>