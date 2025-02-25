<a name=top></a>
<a name=top></a>
---
<a href=../../../README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../datasets/datasets.md#top><l style="font-size:30px">Datasets</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Metrics</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
[Home](../../metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Video](../../video/video_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Action](../../action/action_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Trajectory](../../trajectory/trajectory_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Motion](../../motion/motion_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Other&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[Home](../other_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Alphabetical&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Ranking](../other_ranking/other_ranking_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
A-D&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[E-I](other_e-i_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[J-Z](other_j-z_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
<h2>A-D <small>[rank]</small></h2> 
<ul><a name=absrel></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Absolute Relative error (AbsRel)</strong><small> [12]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Pan et al., "LiDARGrid: Self-supervised 3D Opacity Grid from LiDAR for Scene Forecasting", CoRL, 2024.</em></strong> <a href=https://openreview.net/pdf?id=MfuzopqVOX>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#cd">CD</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#l1">L1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#absrel">AbsRel</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Pan_LiDARGrid_2024_CoRL,
    author = "Pan, Chuanyu and Xu, Aolin",
    title = "Li{DARG}rid: Self-supervised 3D Opacity Grid from Li{DAR} for Scene Forecasting",
    booktitle = "CoRL",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Khurana et al., "Point Cloud Forecasting as a Proxy for 4D Occupancy Forecasting", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Khurana_Point_Cloud_Forecasting_as_a_Proxy_for_4D_Occupancy_Forecasting_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2302.13130.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#l1">L1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#absrel">AbsRel</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#nfe">NFE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Khurana_2023_CVPR,
    author = "Khurana, Tarasha and Hu, Peiyun and Held, David and Ramanan, Deva",
    title = "Point Cloud Forecasting as a Proxy for 4D Occupancy Forecasting",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=acc></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Anomaly Correlation Coefficient (ACC)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Verma et al., "ClimODE: Climate and Weather Forecasting with Physics-informed Neural ODEs", ICLR, 2024.</em></strong> <a href=https://openreview.net/pdf?id=xuY33XhEGR>paper</a> <a href=https://arxiv.org/pdf/2404.10024>arxiv</a> <a href=https://github.com/Aalto-QuML/ClimODE>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#weatherbench">WeatherBench</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#rmse">RMSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#acc">ACC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{VermaCliMOD_2024_ICLR,
    author = "Verma, Yogesh and Heinonen, Markus and Garg, Vikas",
    title = "Clim{ODE}: Climate and Weather Forecasting with Physics-informed Neural {ODE}s",
    booktitle = "ICLR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=accuracy></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Accuracy</strong><small> [5]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Li et al., "Causally-Aware Intraoperative Imputation for Overall Survival Time Prediction", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Causally-Aware_Intraoperative_Imputation_for_Overall_Survival_Time_Prediction_CVPR_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2023_CVPR_1,
    author = "Li, Xiang and Qian, Xuelin and Liang, Litian and Kong, Lingjie and Dong, Qiaole and Chen, Jiejun and Liu, Dingxia and Yao, Xiuzhong and Fu, Yanwei",
    title = "Causally-Aware Intraoperative Imputation for Overall Survival Time Prediction",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Pan et al., "COPILOT: Human-Environment Collision Prediction and Localization from Egocentric Videos", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Pan_COPILOT_Human-Environment_Collision_Prediction_and_Localization_from_Egocentric_Videos_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.01781.pdf>arxiv</a> <a href=https://sites.google.com/stanford.edu/copilot>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#copilot">COPILOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#kld">KLD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Pan_2023_ICCV,
    author = "Pan, Boxiao and Shen, Bokui and Rempe, Davis and Paschalidou, Despoina and Mo, Kaichun and Yang, Yanchao and Guibas, Leonidas J.",
    title = "COPILOT: Human-Environment Collision Prediction and Localization from Egocentric Videos",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Looper et al., "3D VSG: Long-term Semantic Scene Change Prediction through 3D Variable Scene Graphs", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10161212>paper</a> <a href=https://arxiv.org/pdf/2209.07896.pdf>arxiv</a> <a href=https://github.com/ethz-asl/3d_vsg>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#3rscan">3RScan</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dssg">3DSSG</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Looper_2023_ICRA,
    author = "Looper, Samuel and Rodriguez-Puigvert, Javier and Siegwart, Roland and Cadena, Cesar and Schmid, Lukas",
    title = "3D VSG: Long-term Semantic Scene Change Prediction through 3D Variable Scene Graphs",
    booktitle = "ICRA",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Li et al., "Causal Hidden Markov Model for Time Series Disease Forecasting", CVPR, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Causal_Hidden_Markov_Model_for_Time_Series_Disease_Forecasting_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2103.16391.pdf>arxiv</a> <a href=https://github.com/LilJing/causal_hmm>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2021_CVPR,
    author = "Li, Jing and Wu, Botong and Sun, Xinwei and Wang, Yizhou",
    title = "Causal Hidden Markov Model for Time Series Disease Forecasting",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhu et al., "Improving Driver Situation Awareness Prediction using Human Visual Sensory and Memory Mechanism", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636112>paper</a> <a href=https://arxiv.org/pdf/2111.00087.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#tpr">TPR</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#fpr">FPR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhu_2021_IROS,
    author = "Zhu, Haibei and Misu, Teruhisa and Martin, Sujitha and Wu, Xingwei and Akash, Kumar",
    booktitle = "IROS",
    title = "Improving Driver Situation Awareness Prediction using Human Visual Sensory and Memory Mechanism",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Ramakrishnan et al., "Occupancy Anticipation for Efficient Exploration and Navigation", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500392.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.09285.pdf>arxiv</a> <a href=https://github.com/facebookresearch/OccupancyAnticipation>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#matterport3d">Matterport3D</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#gibson_env">Gibson Env</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#habitat">Habitat</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ramakrishnan_2020_ECCV,
    author = "Ramakrishnan, Santhosh K and Al-Halah, Ziad and Grauman, Kristen",
    title = "Occupancy Anticipation for Efficient Exploration and Navigation",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wang et al., "Self-supervised Video Representation Learning by Pace Prediction", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123620494.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.05861.pdf>arxiv</a> <a href=https://github.com/laura-wang/video-pace>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kinetics-400">Kinetics-400</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#hmdb">HMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2020_ECCV_2,
    author = "Wang, Jiangliu and Jiao, Jianbo and Liu, Yun-Hui",
    title = "Self-supervised Video Representation Learning by Pace Prediction",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Song et al., "Long-Term Visual Inertial SLAM Based On Time Series Map Prediction", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8968017>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Song_2019_IROS,
    author = "Song, Bowen and Chen, Weidong and Wang, Jingchuan and Wang, Hesheng",
    booktitle = "IROS",
    title = "Long-Term Visual Inertial {SLAM} Based On Time Series Map Prediction",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zeng et al., "Visual Forecasting By Imitating Dynamics In Natural Sequences", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Zeng_Visual_Forecasting_by_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.05827.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#vist">VIST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zeng_2017_ICCV,
    author = "Zeng, Kuo-Hao and Shen, William B. and Huang, De-An and Sun, Min and Carlos Niebles, Juan",
    title = "Visual Forecasting By Imitating Dynamics In Natural Sequences",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Carvajal et al., "Towards Miss Universe Automatic Prediction: The Evening Gown Competition", ICPR, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/7899781>paper</a> <a href=https://arxiv.org/pdf/1604.07547.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#mu">MU</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Carvajal_2016_ICPR,
    author = "Carvajal, J. and Wiliem, A. and Sanderson, C. and Lovell, B.",
    booktitle = "ICPR",
    title = "Towards Miss Universe Automatic Prediction: The Evening Gown Competition",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Joo et al., "Automated Facial Trait Judgment And Election Outcome Prediction: Social Dimensions Of Face", ICCV, 2015.</em></strong> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Joo_Automated_Facial_Trait_ICCV_2015_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Joo_2015_ICCV,
    author = "Joo, Jungseock and Steen, Francis F. and Zhu, Song-Chun",
    title = "Automated Facial Trait Judgment And Election Outcome Prediction: Social Dimensions Of Face",
    booktitle = "ICCV",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=ace></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Average Calibration Error (ACE)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Luo et al., "Safety-Oriented Pedestrian Occupancy Forecasting", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/document/9636691>paper</a> <a href=https://arxiv.org/pdf/2101.02385.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#map">mAP</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mce">MCE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#ace">ACE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Luo_2021_IROS,
    author = "Luo, Katie and Casas, Sergio and Liao, Renjie and Yan, Xinchen and Xiong, Yuwen and Zeng, Wenyuan and Urtasun, Raquel",
    booktitle = "IROS",
    title = "Safety-Oriented Pedestrian Occupancy Forecasting",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=ade></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Average Displacement Error (ADE)</strong><small> [12]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Zhang et al., "Bidirectional progressive transformer for interaction intention anticipation", ECCV, 2024.</em></strong> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/07631.pdf>paper</a> <a href=https://arxiv.org/pdf/2405.05552>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#ego4d">Ego4D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#auc">AUC</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#nss">NSS</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#similarity">Similarity</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Zhang_Bidirectional_2024_ECCV,
    author = "Zhang, Zichen and Luo, Hongchen and Zhai, Wei and Cao, Yang and Kang, Yu",
    title = "Bidirectional progressive transformer for interaction intention anticipation",
    booktitle = "ECCV",
    year = "2024"
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
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#ppfe">PPFE</a></li>
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
</ul>
</details>

</ul><ul><a name=aepe></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Average End-Point Error (AEPE)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Hu et al., "Probabilistic Future Prediction for Video Scene Understanding", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123610749.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.06409.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#ddm">DDM</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#aepe">AEPE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#sile">SILE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2020_ECCV,
    author = "Hu, Anthony and Cotter, Fergal and Mohan, Nikhil and Gurau, Corina and Kendall, Alex",
    title = "Probabilistic Future Prediction for Video Scene Understanding",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=ap></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Average Precision (AP)</strong><small> [11]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Graber et al., "Panoptic Segmentation Forecasting", CVPR, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Graber_Panoptic_Segmentation_Forecasting_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2104.03962.pdf>arxiv</a> <a href=https://github.com/nianticlabs/ panoptic-forecasting>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#ap">AP</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#sq">SQ</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#pq">PQ</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#rq">RQ</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Graber_2021_CVPR,
    author = "Graber, Colin and Tsai, Grace and Firman, Michael and Brostow, Gabriel and Schwing, Alexander G.",
    title = "Panoptic Segmentation Forecasting",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Hu et al., "Safe Local Motion Planning With Self-Supervised Freespace Forecasting", CVPR, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Hu_Safe_Local_Motion_Planning_With_Self-Supervised_Freespace_Forecasting_CVPR_2021_paper.pdf>paper</a> <a href=https://github.com/peiyunh/ff>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#ap">AP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2021_CVPR,
    author = "Hu, Peiyun and Huang, Aaron and Dolan, John and Held, David and Ramanan, Deva",
    title = "Safe Local Motion Planning With Self-Supervised Freespace Forecasting",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Lin et al., "Predictive Feature Learning for Future Segmentation Prediction", ICCV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Lin_Predictive_Feature_Learning_for_Future_Segmentation_Prediction_ICCV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscape">Cityscape</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#3d_movie">3D Movie</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#ap">AP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lin_2021_ICCV,
    author = "Lin, Zihang and Sun, Jiangxin and Hu, Jian-Fang and Yu, Qizhi and Lai, Jian-Huang and Zheng, Wei-Shi",
    title = "Predictive Feature Learning for Future Segmentation Prediction",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=auc></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Area Under the Curve (AUC)</strong><small> [6]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Zhang et al., "Bidirectional progressive transformer for interaction intention anticipation", ECCV, 2024.</em></strong> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/07631.pdf>paper</a> <a href=https://arxiv.org/pdf/2405.05552>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#ego4d">Ego4D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#auc">AUC</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#nss">NSS</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#similarity">Similarity</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Zhang_Bidirectional_2024_ECCV,
    author = "Zhang, Zichen and Luo, Hongchen and Zhai, Wei and Cao, Yang and Kang, Yu",
    title = "Bidirectional progressive transformer for interaction intention anticipation",
    booktitle = "ECCV",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Ferenczi et al., "MotionPerceiver: Real-Time Occupancy Forecasting for Embedded Systems", RAL, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10417132>paper</a> <a href=https://arxiv.org/pdf/2306.08879>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Ferenczi_MotionPerceiver_2024_RAL,
    author = "Ferenczi, Bryce and Burke, Michael and Drummond, Tom",
    journal = "RAL",
    title = "MotionPerceiver: Real-Time Occupancy Forecasting for Embedded Systems",
    year = "2024",
    volume = "9",
    number = "3",
    pages = "2822-2829"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Ferenczi et al., "MotionPerceiver: Real-Time Occupancy Forecasting for Embedded Systems", RAL, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10417132>paper</a> <a href=https://arxiv.org/pdf/2306.08879>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Ferenczi_MotionPreceiver_2024_RAL,
    author = "Ferenczi, Bryce and Burke, Michael and Drummond, Tom",
    journal = "RAL",
    title = "MotionPerceiver: Real-Time Occupancy Forecasting for Embedded Systems",
    year = "2024",
    volume = "9",
    number = "3",
    pages = "2822-2829"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Liu et al., "Multi-modal Hierarchical Transformer for Occupancy Flow Field Prediction in Autonomous Driving", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10160855>paper</a> <a href=https://arxiv.org/pdf/2208.00394.pdf>arxiv</a> <a href=: https://github.com/georgeliu233/STrajNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#auc">AUC</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#epe">EPE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#soft-iou">Soft-IoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2023_ICRA,
    author = "Liu, Haochen and Huang, Zhiyu and Lv, Chen",
    title = "Multi-modal Hierarchical Transformer for Occupancy Flow Field Prediction in Autonomous Driving",
    booktitle = "ICRA",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Asghar et al., "Vehicle Motion Forecasting Using Prior Information and Semantic-Assisted Occupancy Grid Maps", IROS, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10342507>paper</a> <a href=https://arxiv.org/pdf/2308.04303.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#auc">AUC</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#rov">RoV</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@INPROCEEDINGS{Asghar_2023_IROS,
    author = "Asghar, Rabbia and Diaz-Zapata, Manuel and Rummelhard, Lukas and Spalanzani, Anne and Laugier, Christian",
    booktitle = "IROS",
    title = "Vehicle Motion Forecasting Using Prior Information and Semantic-Assisted Occupancy Grid Maps",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Kim et al., "StopNet: Scalable Trajectory and Occupancy Prediction for Urban Autonomous Driving", ICRA, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/document/9811830>paper</a> <a href=https://arxiv.org/pdf/2206.00991.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kim_2022_ICRA,
    author = "Kim, Jinkyu and Mahjourian, Reza and Ettinger, Scott and Bansal, Mayank and White, Brandyn and Sapp, Ben and Anguelov, Dragomir",
    booktitle = "ICRA",
    title = "{StopNet}: Scalable Trajectory and Occupancy Prediction for Urban Autonomous Driving",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Fobi et al., "Predicting Levels of Household Electricity Consumption in Low-Access Settings", WACV, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/WACV2022/papers/Fobi_Predicting_Levels_of_Household_Electricity_Consumption_in_Low-Access_Settings_WACV_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2112.08497.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#auc">AUC</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#tp">TP</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#tn">TN</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Fobi_2022_WACV,
    author = "Fobi, Simone and Mugyenyi, Joel and Williams, Nathaniel J. and Modi, Vijay and Taneja, Jay",
    title = "Predicting Levels of Household Electricity Consumption in Low-Access Settings",
    booktitle = "WACV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Li et al., "Causal Hidden Markov Model for Time Series Disease Forecasting", CVPR, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Causal_Hidden_Markov_Model_for_Time_Series_Disease_Forecasting_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2103.16391.pdf>arxiv</a> <a href=https://github.com/LilJing/causal_hmm>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2021_CVPR,
    author = "Li, Jing and Wu, Botong and Sun, Xinwei and Wang, Yizhou",
    title = "Causal Hidden Markov Model for Time Series Disease Forecasting",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Choi et al., "Robust Modeling And Prediction In Dynamic Environments Using Recurrent Flow Networks", IROS, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/7759278>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#fcvl">FCVL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#auc">AUC</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#run_time">Run Time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Choi_2016_IROS,
    author = "Choi, S. and Lee, K. and Oh, S.",
    booktitle = "IROS",
    title = "Robust Modeling And Prediction In Dynamic Environments Using Recurrent Flow Networks",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=auprc></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Area Under the PrecisionRecall Curve (AUPRC)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Li et al., "Sim2Real-Fire: A Multi-modal Simulation Dataset for Forecast and Backtracking of Real-world Forest Fire", NeurIPS, 2024.</em></strong> <a href=https://openreview.net/pdf?id=DjCSjizgsH>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#auprc">AUPRC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Li_Simrealfire_2024_NeurIPS,
    author = "Li, Yanzhi and Li, Keqiu and GUOHUI, LI and zumin wang and Ji, Chanqing and Wang, Lubo and Zuo, Die and Guo, Qing and Zhang, Feng and Wang, Manyu and Lin, Di",
    title = "Sim2Real-Fire: A Multi-modal Simulation Dataset for Forecast and Backtracking of Real-world Forest Fire",
    booktitle = "NeurIPS",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=ave></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Average Velocity Error (AVE)</strong><small> [12]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Gui et al., "Fiptr: A simple yet effective transformer framework for future instance prediction in autonomous driving", ECCV, 2024.</em></strong> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/11758.pdf>paper</a> <a href=https://arxiv.org/pdf/2404.12867>arxiv</a> <a href=https://github.com/TabGuigui/FipTR>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#vpq">VPQ</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#map">mAP</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#ave">AVE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Gui_Fiptr_2024_ECCV,
    author = "Gui, Xingtai and Huang, Tengteng and Shao, Haonan and Yao, Haotian and Zhang, Chi",
    title = "Fiptr: A simple yet effective transformer framework for future instance prediction in autonomous driving",
    booktitle = "ECCV",
    year = "2024"
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
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#ave">AVE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#fve">FVE</a></li>
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
</ul>
</details>

</ul><ul><a name=bleu></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Bilingual Evaluation Understudy (BLEU)</strong><small> [11]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Mittal et al., "Can't Make an Omelette Without Breaking Some Eggs: Plausible Action Anticipation Using Large Video-Language Models", CVPR, 2024.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Mittal_Cant_Make_an_Omelette_Without_Breaking_Some_Eggs_Plausible_Action_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2405.20305>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#ego4d">Ego4D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#bleu">BLEU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#rs">RS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mittal_Cant_2024_CVPR,
    author = "Mittal, Himangi and Agarwal, Nakul and Lo, Shao-Yuan and Lee, Kwonjoon",
    title = "Can't Make an Omelette Without Breaking Some Eggs: Plausible Action Anticipation Using Large Video-Language Models",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Vo et al., "A-Cap: Anticipation Captioning With Commonsense Knowledge", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Vo_A-Cap_Anticipation_Captioning_With_Commonsense_Knowledge_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2304.06602.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#vist">VIST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#bleu">BLEU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#refclipscore">RefCLIPScore</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#clipscore">CLIPScore</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#spice">SPICE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#cider">CIDEr</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Vo_2023_CVPR,
    author = "Vo, Duc Minh and Luong, Quoc-An and Sugimoto, Akihiro and Nakayama, Hideki",
    title = "A-Cap: Anticipation Captioning With Commonsense Knowledge",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Abdelsalam et al., "GePSAn: Generative Procedure Step Anticipation in Cooking Videos", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Abdelsalam_GePSAn_Generative_Procedure_Step_Anticipation_in_Cooking_Videos_ICCV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#youcook2">YouCook2</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#recipe1m">Recipe1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#bleu">BLEU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#meteor">METEOR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Abdelsalam_2023_ICCV,
    author = "Abdelsalam, Mohamed A. and Rangrej, Samrudhdhi B. and Hadji, Isma and Dvornik, Nikita and Derpanis, Konstantinos G. and Fazly, Afsaneh",
    title = "GePSAn: Generative Procedure Step Anticipation in Cooking Videos",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=bss></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Brier Skill Score (BSS)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Kaneda et al., "Flare Transformer: Solar Flare Prediction using Magnetograms and Sunspot Physical Features", ACCV, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/ACCV2022/papers/Kaneda_Flare_Transformer_Solar_Flare_Prediction_using_Magnetograms_and_Sunspot_Physical_ACCV_2022_paper.pdf>paper</a> <a href=https://github.com/keio-smilab21/flare_transformer>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdo">SDO</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#bss">BSS</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#tss">TSS</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#gmgs">GMGS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kaneda_2022_ACCV,
    author = "Kaneda, Kanta and Wada, Yuiga and Iida, Tsumugi and Nishizuka, Naoto and Kubo, Y\^uki and Sugiura, Komei",
    title = "{Flare Transformer}: Solar Flare Prediction using Magnetograms and Sunspot Physical Features",
    booktitle = "ACCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=c-index></a>
<details close>
<summary><em><l style="font-size:20px"><strong>c-index</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Jaume et al., "Modeling Dense Multimodal Interactions Between Biological Pathways and Histology for Survival Prediction", CVPR, 2024.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Jaume_Modeling_Dense_Multimodal_Interactions_Between_Biological_Pathways_and_Histology_for_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2304.06819>arxiv</a> <a href=https://github.com/mahmoodlab/SurvPath>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#c-index">c-index</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jaume_Modeling_2024_CVPR,
    author = "Jaume, Guillaume and Vaidya, Anurag and Chen, Richard J. and Williamson, Drew F.K. and Liang, Paul Pu and Mahmood, Faisal",
    title = "Modeling Dense Multimodal Interactions Between Biological Pathways and Histology for Survival Prediction",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=c-index></a>
<details close>
<summary><em><l style="font-size:20px"><strong>C-index</strong><small> [12]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Song et al., "Multimodal Prototyping for cancer survival prediction", ICML, 2024.</em></strong> <a href=https://openreview.net/pdf?id=3MfvxH3Gia>paper</a> <a href=https://arxiv.org/pdf/2407.00224>arxiv</a> <a href=https://github.com/mahmoodlab/MMP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#tcga">TCGA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#c-index">C-index</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#p-value">p-value</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Song_Multimodal_2024_ICML,
    author = "Song, Andrew H. and Chen, Richard J. and Jaume, Guillaume and Vaidya, Anurag Jayant and Baras, Alexander and Mahmood, Faisal",
    title = "Multimodal Prototyping for cancer survival prediction",
    booktitle = "ICML",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhang et al., "Prototypical Information Bottlenecking and Disentangling for Multimodal Cancer Survival Prediction", ICLR, 2024.</em></strong> <a href=https://openreview.net/pdf?id=otHZ8JAIgh>paper</a> <a href=https://arxiv.org/pdf/2401.01646>arxiv</a> <a href=https://github.com/zylbuaa/PIBD.git>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#tcga">TCGA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#c-index">C-index</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Zhang_prototypical_2024_ICLR,
    author = "Zhang, Yilan and Xu, Yingxue and Chen, Jianqi and Xie, Fengying and Chen, Hao",
    title = "Prototypical Information Bottlenecking and Disentangling for Multimodal Cancer Survival Prediction",
    booktitle = "ICLR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=c-index></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Cross-validated concordance Index (C-Index)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Xu et al., "Multimodal Optimal Transport-based Co-Attention Transformer with Global Structure Consistency for Survival Prediction", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Xu_Multimodal_Optimal_Transport-based_Co-Attention_Transformer_with_Global_Structure_Consistency_for_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2306.08330.pdf>arxiv</a> <a href=https://github.com/Innse/MOTCat>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#c-index">C-Index</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2023_ICCV_2,
    author = "Xu, Yingxue and Chen, Hao",
    title = "Multimodal Optimal Transport-based Co-Attention Transformer with Global Structure Consistency for Survival Prediction",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=cd></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Chamfer Distance (CD)</strong><small> [8]</small></l>
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
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#cd">CD</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#vpq">VPQ</a></li>
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
<summary><strong><em>Agro et al., "UnO: Unsupervised Occupancy Fields for Perception and Forecasting", CVPR, 2024.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Agro_UnO_Unsupervised_Occupancy_Fields_for_Perception_and_Forecasting_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/abs/2406.08691>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#cd">CD</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#l1">L1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#nfcd">NFCD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Agro_UnO_2024_CVPR,
    author = "Agro, Ben and Sykora, Quinlan and Casas, Sergio and Gilles, Thomas and Urtasun, Raquel",
    title = "UnO: Unsupervised Occupancy Fields for Perception and Forecasting",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Pan et al., "LiDARGrid: Self-supervised 3D Opacity Grid from LiDAR for Scene Forecasting", CoRL, 2024.</em></strong> <a href=https://openreview.net/pdf?id=MfuzopqVOX>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#cd">CD</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#l1">L1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#absrel">AbsRel</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Pan_LiDARGrid_2024_CoRL,
    author = "Pan, Chuanyu and Xu, Aolin",
    title = "Li{DARG}rid: Self-supervised 3D Opacity Grid from Li{DAR} for Scene Forecasting",
    booktitle = "CoRL",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Chen et al., "Predicting Object Interactions with Behavior Primitives: An Application in Stowing Tasks", CoRL, 2023.</em></strong> <a href=https://openreview.net/pdf?id=VH6WIPF4Sj>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#cd">CD</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#emd">EMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2023_CoRL,
    author = "Chen, Haonan and Niu, Yilong and Hong, Kaiwen and Liu, Shuijing and Wang, Yixuan and Li, Yunzhu and Driggs-Campbell, Katherine Rose",
    title = "Predicting Object Interactions with Behavior Primitives: An Application in Stowing Tasks",
    booktitle = "CoRL",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Luo et al., "PCPNet: An Efficient and Semantic-Enhanced Transformer Network for Point Cloud Prediction", RAL, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10141631>paper</a> <a href=https://arxiv.org/pdf/2304.07773>arxiv</a> <a href=https://github.com/Blurryface0814/PCPNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#cd">CD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Luo_PCPNet_2023_RAL,
    author = "Luo, Zhen and Ma, Junyi and Zhou, Zijie and Xiong, Guangming",
    journal = "RAL",
    title = "PCPNet: An Efficient and Semantic-Enhanced Transformer Network for Point Cloud Prediction",
    year = "2023",
    volume = "8",
    number = "7",
    pages = "4267-4274"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Weng et al., "S2Net: Stochastic Sequential Pointcloud Forecasting", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136870541.pdf>paper</a> <a href=https://www.xinshuoweng.com/projects/S2Net>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#cd">CD</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#emd">EMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Weng_2022_ECCV,
    author = "Weng, Xinshuo and Nan, Junyu and Lee, Kuan-Hui and McAllister, Rowan and Gaidon, Adrien and Rhinehart, Nicholas and Kitani, Kris M.",
    title = "{S2Net}: Stochastic Sequential Pointcloud Forecasting",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Mersch et al., "Self-supervised Point Cloud Prediction Using 3D Spatio-temporal Convolutional Networks", CoRL, 2021.</em></strong> <a href=https://openreview.net/pdf?id=JvXqtLtAtMY>paper</a> <a href=https://download.arxiv.org/pdf/2110.04076v2>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#cd">CD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mersch_2021_CoRL,
    author = "Mersch, Benedikt and Chen, Xieyuanli and Behley, Jens and Stachniss, Cyrill",
    title = "Self-supervised Point Cloud Prediction Using {3D} Spatio-temporal Convolutional Networks",
    booktitle = "CoRL",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=cider></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Consensus-based image description evaluation (CIDEr)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Vo et al., "A-Cap: Anticipation Captioning With Commonsense Knowledge", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Vo_A-Cap_Anticipation_Captioning_With_Commonsense_Knowledge_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2304.06602.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#vist">VIST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#bleu">BLEU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#refclipscore">RefCLIPScore</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#clipscore">CLIPScore</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#spice">SPICE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#cider">CIDEr</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Vo_2023_CVPR,
    author = "Vo, Duc Minh and Luong, Quoc-An and Sugimoto, Akihiro and Nakayama, Hideki",
    title = "A-Cap: Anticipation Captioning With Commonsense Knowledge",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=clipscore></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Contrastive Language-Image Pre-training Score (CLIPScore)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Vo et al., "A-Cap: Anticipation Captioning With Commonsense Knowledge", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Vo_A-Cap_Anticipation_Captioning_With_Commonsense_Knowledge_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2304.06602.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#vist">VIST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#bleu">BLEU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#refclipscore">RefCLIPScore</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#clipscore">CLIPScore</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#spice">SPICE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#cider">CIDEr</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Vo_2023_CVPR,
    author = "Vo, Duc Minh and Luong, Quoc-An and Sugimoto, Akihiro and Nakayama, Hideki",
    title = "A-Cap: Anticipation Captioning With Commonsense Knowledge",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=corr></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Pearson Correlation Coefficient (Corr)</strong><small> [12]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Benson et al., "Multi-modal Learning for Geospatial Vegetation Forecasting", CVPR, 2024.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Benson_Multi-modal_Learning_for_Geospatial_Vegetation_Forecasting_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.16198>arxiv</a> <a href=https://github.com/vitusbenson/greenearthnet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#greenearthnet">GreenEarthNet</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#rmse">RMSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#corr">Corr</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#nse">NSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Benson_Multimodal_2024_CVPR,
    author = "Benson, Vitus and Robin, Claire and Requena-Mesa, Christian and Alonso, Lazaro and Carvalhais, Nuno and Cort\'es, Jos\'e and Gao, Zhihan and Linscheid, Nora and Weynants, M\'elanie and Reichstein, Markus",
    title = "Multi-modal Learning for Geospatial Vegetation Forecasting",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Lin et al., "MMST-ViT: Climate Change-aware Crop Yield Prediction via Multi-Modal Spatial-Temporal Vision Transformer", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Lin_MMST-ViT_Climate_Change-aware_Crop_Yield_Prediction_via_Multi-Modal_Spatial-Temporal_Vision_ICCV_2023_paper.pdf>paper</a> <a href=https://github.com/fudong03/MMST-ViT>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#rmse">RMSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#corr">Corr</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#r-squared">R-squared</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lin_2023_ICCV,
    author = "Lin, Fudong and Crawford, Summer and Guillot, Kaleb and Zhang, Yihe and Chen, Yan and Yuan, Xu and Chen, Li and Williams, Shelby and Minvielle, Robert and Xiao, Xiangming and Gholson, Drew and Ashwell, Nicolas and Setiyono, Tri and Tubana, Brenda and Peng, Lu and Bayoumi, Magdy and Tzeng, Nian-Feng",
    title = "MMST-ViT: Climate Change-aware Crop Yield Prediction via Multi-Modal Spatial-Temporal Vision Transformer",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=cq></a>
<details close>
<summary><em><l style="font-size:20px"><strong>CQ</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Shi et al., "StreamingFlow: Streaming Occupancy Forecasting with Asynchronous Multi-modal Data Streams via Neural Ordinary Differential Equation", CVPR, 2024.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Shi_StreamingFlow_Streaming_Occupancy_Forecasting_with_Asynchronous_Multi-modal_Data_Streams_via_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2302.09585>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#vpq">VPQ</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#sq">SQ</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#pq">PQ</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#cq">CQ</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shi_StreamingFlow_2024_CVPR,
    author = "Shi, Yining and Jiang, Kun and Wang, Ke and Li, Jiusi and Wang, Yunlong and Yang, Mengmeng and Yang, Diange",
    title = "StreamingFlow: Streaming Occupancy Forecasting with Asynchronous Multi-modal Data Streams via Neural Ordinary Differential Equation",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=cross-entropy></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Cross-entropy</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Khurana et al., "Differentiable Raycasting for Self-Supervised Occupancy Forecasting", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136980349.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.01917.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#once">ONCE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#cross-entropy">Cross-entropy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Khurana_2022_ECCV,
    author = "Khurana, Tarasha and Hu, Peiyun and Dave, Achal and Ziglar, Jason and Held, David and Ramanan, Deva",
    title = "Differentiable Raycasting for Self-Supervised Occupancy Forecasting",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=ddm></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Diversity Distance Metric (DDM)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Hu et al., "Probabilistic Future Prediction for Video Scene Understanding", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123610749.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.06409.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#ddm">DDM</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#aepe">AEPE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#sile">SILE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2020_ECCV,
    author = "Hu, Anthony and Cotter, Fergal and Mohan, Nikhil and Gurau, Corina and Kendall, Alex",
    title = "Probabilistic Future Prediction for Video Scene Understanding",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=dmse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Dynamic MSE (DMSE)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Toyungyernsub et al., "Double-Prong ConvLSTM for Spatiotemporal Occupancy Prediction in Dynamic Environments", ICRA, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9561940>paper</a> <a href=https://arxiv.org/pdf/2011.09045.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#way">Way</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#ims">ImS</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_a-d_metrics.md#dmse">DMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Toyungyernsub_2021_ICRA,
    author = "Toyungyernsub, Maneekwan and Itkina, Masha and Senanayake, Ransalu and Kochenderfer, Mykel J.",
    booktitle = "ICRA",
    title = "Double-Prong {ConvLSTM} for Spatiotemporal Occupancy Prediction in Dynamic Environments",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul>