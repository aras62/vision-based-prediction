<a name=top></a>
<a name=top></a>
---
<a href=../../../README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../datasets/datasets.md#top><l style="font-size:30px">Datasets</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Metrics</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
[Home](../../metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Video](../../video/video_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Action&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Trajectory](../../trajectory/trajectory_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Motion](../../motion/motion_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Other](../../other/other_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[Home](../action_metrics.md"#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Alphabetical&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Ranking](../action_ranking/action_ranking_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[A-D](action_a-d_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[E-I](action_e-i_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;J-Z&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
<h2>J-Z <small>[rank]</small></h2> 
<ul><a name=kld></a>
<details close>
<summary><em><l style="font-size:20px"><strong>KullbackLeibler Divergence (KLD)</strong><small> [11]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Liu et al., "Forecasting Human Object Interaction: Joint Prediction of Motor Attention and Actions in First Person Video", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460681.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.10967.pdf>arxiv</a> <a href=https://github.com/2020aptx4869lm/Forecasting-Human-Object-Interaction-in-FPV>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_e-i_datasets.md#fde">FDE</a></li>
<li><a href="action_a-d_datasets.md#ade">ADE</a></li>
<li><a href="action_j-z_datasets.md#kld">KLD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2020_ECCV,
    author = "Liu, Miao and Tang, Siyu and Li, Yin and Rehg, James",
    title = "Forecasting Human Object Interaction: Joint Prediction of Motor Attention and Actions in First Person Video",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=mae></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Absolute Error (MAE)</strong><small> [11]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Manglik et al., "Forecasting Time-To-Collision From Monocular Video: Feasibility, Dataset, And Challenges", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8967730>paper</a> <a href=https://arxiv.org/pdf/1903.09102.pdf>arxiv</a> <a href=https://github.com/aashi7/NearCollision>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#luggage">Luggage</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Manglik_2019_IROS,
    author = "Manglik, Aashi and Weng, Xinshuo and Ohn-Bar, Eshed and Kitani, Kris M",
    booktitle = "IROS",
    title = "Forecasting Time-To-Collision From Monocular Video: Feasibility, Dataset, And Challenges",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=map></a>
<details close>
<summary><em><l style="font-size:20px"><strong>mean Average Precision (mAP)</strong><small> [5]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Mascaro et al., "HOI4ABOT: Human-Object Interaction Anticipation for Human Intention Reading Collaborative roBOTs", CoRL, 2023.</em></strong> <a href=https://openreview.net/pdf?id=rYZBdBytxBx>paper</a> <a href=https://arxiv.org/pdf/2309.16524.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#vidhoi">VidHOI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mascaro_2023_CoRL,
    author = "Mascaro, Esteve Valls and Sliwowski, Daniel and Lee, Dongheui",
    title = "HOI4ABOT: Human-Object Interaction Anticipation for Human Intention Reading Collaborative ro{BOT}s",
    booktitle = "CoRL",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Nawhal et al., "Rethinking Learning Approaches for Long-Term Action Anticipation", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940547.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.11566.pdf>arxiv</a> <a href=https://github.com/Nmegha2601/anticipatr>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Nawhal_2022_ECCV,
    author = "Nawhal, Megha and Jyothi, Akash Abdu and Mori, Greg",
    title = "Rethinking Learning Approaches for Long-Term Action Anticipation",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhai et al., "Social Aware Multi-Modal Pedestrian Crossing Behavior Prediction", ACCV, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/ACCV2022/papers/Zhai_Social_Aware_Multi-Modal_Pedestrian_Crossing_Behavior_Prediction_ACCV_2022_paper.pdf>paper</a> <a href=https://github.com/zxll0106/Pedestrian_Crossing_Behavior_Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
<li><a href="action_a-d_datasets.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhai_2022_ACCV,
    author = "Zhai, Xiaolin and Hu, Zhengxi and Yang, Dingye and Zhou, Lei and Liu, Jingtai",
    title = "Social Aware Multi-Modal Pedestrian Crossing Behavior Prediction",
    booktitle = "ACCV",
    year = "2022"
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
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#virat/actev">VIRAT/ActEV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
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
<summary><strong><em>Piergiovanni et al., "Adversarial Generative Grammars for Human Activity Prediction", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470494.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.04888.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#charades">Charades</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Piergiovanni_2020_ECCV,
    author = "Piergiovanni, AJ and Angelova, Anelia and Toshev, Alexander and Ryoo, Michael S",
    title = "Adversarial Generative Grammars for Human Activity Prediction",
    booktitle = "ECCV",
    year = "2020"
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
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#virat/actev">VIRAT/ActEV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
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
<summary><strong><em>Safaei et al., "Still Image Action Recognition By Predicting Spatial-Temporal Pixel Evolution", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8658386>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#willow_action">Willow Action</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#wider">WIDER</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#stanford-40">Stanford-40</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#bu_action">BU Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Safaei_2019_WACV,
    author = "Safaei, M. and Foroosh, H.",
    booktitle = "WACV",
    title = "Still Image Action Recognition By Predicting Spatial-Temporal Pixel Evolution",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Suzuki et al., "Anticipating Traffic Accidents With Adaptive Loss And Large-Scale Incident Db", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0494.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.02675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
<li><a href="action_a-d_datasets.md#attc">ATTC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Suzuki_2018_CVPR,
    author = "Suzuki, Tomoyuki and Kataoka, Hirokatsu and Aoki, Yoshimitsu and Satoh, Yutaka",
    title = "Anticipating Traffic Accidents With Adaptive Loss And Large-Scale Incident Db",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Casas et al., "IntentNet: Learning To Predict Intention From Raw Sensor Data", CORL, 2018.</em></strong> <a href=http://proceedings.mlr.press/v87/casas18a/casas18a.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Casas_2018_CORL,
    author = "Casas, Sergio and Luo, Wenjie and Urtasun, Raquel",
    title = "{IntentNet}: Learning To Predict Intention From Raw Sensor Data",
    booktitle = "CORL",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zeng et al., "Agent-Centric Risk Assessment: Accident Anticipation And Risky Region Localization", CVPR, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Zeng_Agent-Centric_Risk_Assessment_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.06560.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#epic-fail">Epic-Fail</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
<li><a href="action_j-z_datasets.md#tta">TTA</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zeng_2017_CVPR,
    author = "Zeng, Kuo-Hao and Chou, Shih-Han and Chan, Fu-Hsiang and Carlos Niebles, Juan and Sun, Min",
    title = "Agent-Centric Risk Assessment: Accident Anticipation And Risky Region Localization",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Singh et al., "Online Real-Time Multiple Spatiotemporal Action Localisation And Prediction", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Singh_Online_Real-Time_Multiple_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1611.08563.pdf>arxiv</a> <a href=https://github.com/gurkirt/realtime-action-detection>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
<li><a href="action_a-d_datasets.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Singh_2017_ICCV,
    author = "Singh, Gurkirt and Saha, Suman and Sapienza, Michael and Torr, Philip H. S. and Cuzzolin, Fabio",
    title = "Online Real-Time Multiple Spatiotemporal Action Localisation And Prediction",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Rasouli et al., "Are They Going To Cross? A Benchmark Dataset And Baseline For Pedestrian Crosswalk Behavior", ICCVW, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w3/Rasouli_Are_They_Going_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rasouli_2017_ICCVW,
    author = "Rasouli, Amir and Kotseruba, Iuliia and Tsotsos, John K.",
    title = "Are They Going To Cross? A Benchmark Dataset And Baseline For Pedestrian Crosswalk Behavior",
    booktitle = "ICCVW",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Gao et al., "RED: Reinforced Encoder-Decoder Networks For Action Anticipation", BMVC, 2017.</em></strong> <a href=http://www.bmva.org/bmvc/2017/papers/paper092/paper092.pdf>paper</a> <a href=https://arxiv.org/pdf/1707.04818.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#tv_series">TV Series</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
<li><a href="action_a-d_datasets.md#cap">cAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2017_BMVC,
    author = "Gao, Jiyang and Yang, Zhenheng and Nevatia, Ram",
    title = "{RED}: Reinforced Encoder-Decoder Networks For Action Anticipation",
    year = "2017",
    booktitle = "BMVC"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=mcc></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Matthews Correlation Coefficient (MCC)</strong><small> [11]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Strickland et al., "Deep Predictive Models For Collision Risk Assessment In Autonomous Driving", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8461160>paper</a> <a href=https://arxiv.org/pdf/1711.10453.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#mcc">MCC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Strickland_2018_ICRA,
    author = "Strickland, M. and Fainekos, G. and Amor, H. B.",
    booktitle = "ICRA",
    title = "Deep Predictive Models For Collision Risk Assessment In Autonomous Driving",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=meteor></a>
<details close>
<summary><em><l style="font-size:20px"><strong>METEOR</strong><small> [11]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Hosseinzadeh et al., "Video Captioning of Future Frames", WACV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Hosseinzadeh_Video_Captioning_of_Future_Frames_WACV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#activitynet">ActivityNet</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#swag">SWAG</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#cider">CIDEr</a></li>
<li><a href="action_j-z_datasets.md#rouge-l">ROUGE-L</a></li>
<li><a href="action_j-z_datasets.md#meteor">METEOR</a></li>
<li><a href="action_a-d_datasets.md#bleu@n">BLEU@N</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hosseinzadeh_2021_WACV,
    author = "Hosseinzadeh, Mehrdad and Wang, Yang",
    title = "Video Captioning of Future Frames",
    booktitle = "WACV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=moc></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean-over-class (MoC)</strong><small> [11]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Morais et al., "Learning to Abstract and Predict Human Actions", BMVC, 2020.</em></strong> <a href=https://www.bmvc2020-conference.com/assets/papers/0979.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.09234.pdf>arxiv</a> <a href=https://github.com/RomeroBarata/hierarchical_action_prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#mof">MoF</a></li>
<li><a href="action_j-z_datasets.md#moc">MoC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Morais_2020_BMVC,
    author = "Morais, Romero and Le, Vuong and Tran, Truyen and Venkatesh, Svetha",
    title = "Learning to Abstract and Predict Human Actions",
    booktitle = "BMVC",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=mof></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean-over-frame (MoF)</strong><small> [11]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Morais et al., "Learning to Abstract and Predict Human Actions", BMVC, 2020.</em></strong> <a href=https://www.bmvc2020-conference.com/assets/papers/0979.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.09234.pdf>arxiv</a> <a href=https://github.com/RomeroBarata/hierarchical_action_prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#mof">MoF</a></li>
<li><a href="action_j-z_datasets.md#moc">MoC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Morais_2020_BMVC,
    author = "Morais, Romero and Le, Vuong and Tran, Truyen and Venkatesh, Svetha",
    title = "Learning to Abstract and Predict Human Actions",
    booktitle = "BMVC",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=mrr></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Reciprocal Rank (MRR)</strong><small> [11]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Xu et al., "Activity Auto-Completion: Predicting Human Activities From Partial Videos", ICCV, 2015.</em></strong> <a href=https://openaccess.thecvf.com/content_iccv_2015/papers/Xu_Activity_Auto-Completion_Predicting_ICCV_2015_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#uti">UTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#mrr">MRR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2015_ICCV,
    author = "Xu, Zhen and Qing, Laiyun and Miao, Jun",
    title = "Activity Auto-Completion: Predicting Human Activities From Partial Videos",
    booktitle = "ICCV",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=nll></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Negative Log-Likelihood (NLL)</strong><small> [11]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Ke et al., "Future Moment Assessment for Action Query", WACV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Ke_Future_Moment_Assessment_for_Action_Query_WACV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_a-d_datasets.md#auc">AUC</a></li>
<li><a href="action_j-z_datasets.md#rmse">RMSE</a></li>
<li><a href="action_j-z_datasets.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ke_2021_WACV,
    author = "Ke, Qiuhong and Fritz, Mario and Schiele, Bernt",
    title = "Future Moment Assessment for Action Query",
    booktitle = "WACV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=pp></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Prediction Power (PP)</strong><small> [11]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Ziaeetabar et al., "Prediction Of Manipulation Action Classes Using Semantic Spatial Reasoning", IROS, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8593717>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#maniac">MANIAC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#pp">PP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ziaeetabar_2018_IROS,
    author = "Ziaeetabar, F. and Kulvicius, T. and Tamosiunaite, M. and Wörgötter, F.",
    booktitle = "IROS",
    title = "Prediction Of Manipulation Action Classes Using Semantic Spatial Reasoning",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=precision></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Precision</strong><small> [3]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Mascaro et al., "HOI4ABOT: Human-Object Interaction Anticipation for Human Intention Reading Collaborative roBOTs", CoRL, 2023.</em></strong> <a href=https://openreview.net/pdf?id=rYZBdBytxBx>paper</a> <a href=https://arxiv.org/pdf/2309.16524.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#vidhoi">VidHOI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mascaro_2023_CoRL,
    author = "Mascaro, Esteve Valls and Sliwowski, Daniel and Lee, Dongheui",
    title = "HOI4ABOT: Human-Object Interaction Anticipation for Human Intention Reading Collaborative ro{BOT}s",
    booktitle = "CoRL",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Song et al., "Pedestrian Intention Prediction Based on Traffic-Aware Scene Graph Model", IROS, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9981690>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_a-d_datasets.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Song_2022_IROS,
    author = "Song, Xingchen and Kang, Miao and Zhou, Sanping and Wang, Jianji and Mao, Yishu and Zheng, Nanning",
    booktitle = "IROS",
    title = "Pedestrian Intention Prediction Based on Traffic-Aware Scene Graph Model",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhai et al., "Social Aware Multi-Modal Pedestrian Crossing Behavior Prediction", ACCV, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/ACCV2022/papers/Zhai_Social_Aware_Multi-Modal_Pedestrian_Crossing_Behavior_Prediction_ACCV_2022_paper.pdf>paper</a> <a href=https://github.com/zxll0106/Pedestrian_Crossing_Behavior_Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
<li><a href="action_a-d_datasets.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhai_2022_ACCV,
    author = "Zhai, Xiaolin and Hu, Zhengxi and Yang, Dingye and Zhou, Lei and Liu, Jingtai",
    title = "Social Aware Multi-Modal Pedestrian Crossing Behavior Prediction",
    booktitle = "ACCV",
    year = "2022"
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
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_a-d_datasets.md#auc">AUC</a></li>
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
<summary><strong><em>Yau et al., "Graph-SIM: A Graph-based Spatiotemporal Interaction Modelling for Pedestrian Action Prediction", ICRA, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9561107>paper</a> <a href=https://arxiv.org/pdf/2012.02148.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#pepscenes">PepScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_a-d_datasets.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yau_2021_ICRA,
    author = "Yau, Tiffany and Malekmohammadi, Saber and Rasouli, Amir and Lakner, Peter and Rohani, Mohsen and Luo, Jun",
    booktitle = "ICRA",
    title = "{Graph-SIM}: A Graph-based Spatiotemporal Interaction Modelling for Pedestrian Action Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Liu et al., "Forecasting Human Object Interaction: Joint Prediction of Motor Attention and Actions in First Person Video", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460681.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.10967.pdf>arxiv</a> <a href=https://github.com/2020aptx4869lm/Forecasting-Human-Object-Interaction-in-FPV>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_e-i_datasets.md#fde">FDE</a></li>
<li><a href="action_a-d_datasets.md#ade">ADE</a></li>
<li><a href="action_j-z_datasets.md#kld">KLD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2020_ECCV,
    author = "Liu, Miao and Tang, Siyu and Li, Yin and Rehg, James",
    title = "Forecasting Human Object Interaction: Joint Prediction of Motor Attention and Actions in First Person Video",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Jayaraman et al., "Analysis and Prediction of Pedestrian Crosswalk Behavior during Automated Vehicle Interactions", ICRA, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9197347>paper</a> <a href=https://arxiv.org/pdf/2003.09996.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jayaraman_2020_ICRA,
    author = "Jayaraman, S. K. and Tilbury, D. M. and Yang, X. Jessie and Pradhan, A. K. and Robert, L. P.",
    booktitle = "ICRA",
    title = "Analysis and Prediction of Pedestrian Crosswalk Behavior during Automated Vehicle Interactions",
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
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
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
<summary><strong><em>Ke et al., "Time-Conditioned Action Anticipation In One Shot", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Ke_Time-Conditioned_Action_Anticipation_in_One_Shot_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ke_2019_CVPR,
    author = "Ke, Qiuhong and Fritz, Mario and Schiele, Bernt",
    title = "Time-Conditioned Action Anticipation In One Shot",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Rasouli et al., "Pedestrian Action Anticipation Using Contextual Feature Fusion In Stacked Rnns", BMVC, 2019.</em></strong> <a href=https://bmvc2019.org/wp-content/uploads/papers/0283-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.06582.pdf>arxiv</a> <a href=https://github.com/aras62/SF-GRU>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_a-d_datasets.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rasouli_2019_BMVC,
    author = "Rasouli, Amir and Kotseruba, Iuliia and Tsotsos, John K",
    title = "Pedestrian Action Anticipation Using Contextual Feature Fusion In Stacked Rnns",
    year = "2019",
    booktitle = "BMVC"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Ding et al., "Predicting Vehicle Behaviors Over An Extended Horizon Using Behavior Interaction Network", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8794146>paper</a> <a href=https://arxiv.org/pdf/1903.00848.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ding_2019_ICRA,
    author = "Ding, W. and Chen, J. and Shen, S.",
    booktitle = "ICRA",
    title = "Predicting Vehicle Behaviors Over An Extended Horizon Using Behavior Interaction Network",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Gujjar et al., "Classifying Pedestrian Actions In Advance Using Predicted Video Of Urban Driving Scenes", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8794278>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_a-d_datasets.md#ap">AP</a></li>
<li><a href="action_j-z_datasets.md#run_time">Run Time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gujjar_2019_ICRA,
    author = "Gujjar, P. and Vaughan, R.",
    booktitle = "ICRA",
    title = "Classifying Pedestrian Actions In Advance Using Predicted Video Of Urban Driving Scenes",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Scheel et al., "Attention-Based Lane Change Prediction", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8793648>paper</a> <a href=https://arxiv.org/pdf/1903.01246.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_j-z_datasets.md#ttm">TTM</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Scheel_2019_ICRA,
    author = "Scheel, O. and Nagaraja, N. S. and Schwarz, L. and Navab, N. and Tombari, F.",
    booktitle = "ICRA",
    title = "Attention-Based Lane Change Prediction",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Alati et al., "Help By Predicting What To Do", ICIP, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8803155>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#mpii_cooking">MPII Cooking</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Alati_2019_ICIP,
    author = "Alati, E. and Mauro, L. and Ntouskos, V. and Pirri, F.",
    booktitle = "ICIP",
    title = "Help By Predicting What To Do",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wang et al., "A Learning-Based Prediction Model For Baby Accidents", ICIP, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8803820>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_a-d_datasets.md#ap">AP</a></li>
<li><a href="action_j-z_datasets.md#tta">TTA</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2019_ICIP,
    author = "Wang, P. and Lien, S. and Lee, M.",
    booktitle = "ICIP",
    title = "A Learning-Based Prediction Model For Baby Accidents",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Suzuki et al., "Anticipating Traffic Accidents With Adaptive Loss And Large-Scale Incident Db", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0494.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.02675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
<li><a href="action_a-d_datasets.md#attc">ATTC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Suzuki_2018_CVPR,
    author = "Suzuki, Tomoyuki and Kataoka, Hirokatsu and Aoki, Yoshimitsu and Satoh, Yutaka",
    title = "Anticipating Traffic Accidents With Adaptive Loss And Large-Scale Incident Db",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Mahmud et al., "Joint Prediction Of Activity Labels And Starting Times In Untrimmed Videos", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Mahmud_Joint_Prediction_of_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#mpii_cooking">MPII Cooking</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#virat">VIRAT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_j-z_datasets.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mahmud_2017_ICCV,
    author = "Mahmud, Tahmida and Hasan, Mahmudul and Roy-Chowdhury, Amit K.",
    title = "Joint Prediction Of Activity Labels And Starting Times In Untrimmed Videos",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Qi et al., "Predicting Human Activities Using Stochastic Grammar", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Qi_Predicting_Human_Activities_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00945.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Qi_2017_ICCV,
    author = "Qi, Siyuan and Huang, Siyuan and Wei, Ping and Zhu, Song-Chun",
    title = "Predicting Human Activities Using Stochastic Grammar",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Kwak et al., "Pedestrian Intention Prediction Based On Dynamic Fuzzy Automata For Vehicle Driving At Nighttime", Infrared Physics & Technology, 2017.</em></strong> <a href=https://www.sciencedirect.com/science/article/abs/pii/S1350449516304935>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Kwak_2017_IPT,
    author = "Kwak, Joon-Young and Ko, Byoung Chul and Nam, Jae-Yeal",
    title = "Pedestrian Intention Prediction Based On Dynamic Fuzzy Automata For Vehicle Driving At Nighttime",
    journal = "Infrared Physics \& Technology",
    volume = "81",
    pages = "41--51",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Jain et al., "Structural-RNN: Deep Learning On Spatio-Temporal Graphs", CVPR, 2016.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.05298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_j-z_datasets.md#ttm">TTM</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jain_2016_CVPR,
    author = "Jain, Ashesh and Zamir, Amir R. and Savarese, Silvio and Saxena, Ashutosh",
    title = "{Structural-RNN}: Deep Learning On Spatio-Temporal Graphs",
    booktitle = "CVPR",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Jain et al., "Recurrent Neural Networks For Driver Activity Anticipation Via Sensory-Fusion Architecture", ICRA, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7487478>paper</a> <a href=https://arxiv.org/pdf/1509.05016.pdf>arxiv</a> <a href=https://github.com/asheshjain399/RNNexp>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_j-z_datasets.md#ttm">TTM</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jain_2016_ICRA,
    author = "Jain, A. and Singh, A. and Koppula, H. S. and Soh, S. and Saxena, A.",
    booktitle = "ICRA",
    title = "Recurrent Neural Networks For Driver Activity Anticipation Via Sensory-Fusion Architecture",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Hu et al., "Human Intent Forecasting Using Intrinsic Kinematic Constraints", IROS, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7759141>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2016_IROS,
    author = "Hu, N. and Bestick, A. and Englebienne, G. and Bajscy, R. and Kröse, B.",
    booktitle = "IROS",
    title = "Human Intent Forecasting Using Intrinsic Kinematic Constraints",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Schneemann et al., "Context-Based Detection Of Pedestrian Crossing Intention For Autonomous Driving In Urban Environments", IROS, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7759351>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Schneemann_2016_IROS,
    author = "Schneemann, F. and Heinemann, P.",
    booktitle = "IROS",
    title = "Context-Based Detection Of Pedestrian Crossing Intention For Autonomous Driving In Urban Environments",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Jain et al., "Car That Knows Before You Do: Anticipating Maneuvers Via Learning Temporal Driving Models", ICCV, 2015.</em></strong> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Jain_Car_That_Knows_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1504.02789.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_j-z_datasets.md#ttm">TTM</a></li>
<li><a href="action_e-i_datasets.md#fp">FP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jain_2015_ICCV,
    author = "Jain, Ashesh and Koppula, Hema S. and Raghavan, Bharad and Soh, Shane and Saxena, Ashutosh",
    title = "Car That Knows Before You Do: Anticipating Maneuvers Via Learning Temporal Driving Models",
    booktitle = "ICCV",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Galceran et al., "Multipolicy Decision-Making for Autonomous Driving via Changepoint-based Behavior Prediction", RSS, 2015.</em></strong> <a href=http://www.roboticsproceedings.org/rss11/p43.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Galceran_2015_RSS,
    author = "Galceran, Enric and Cunningham, Alexander G and Eustice, Ryan M and Olson, Edwin",
    title = "Multipolicy Decision-Making for Autonomous Driving via Changepoint-based Behavior Prediction",
    booktitle = "RSS",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=recall></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Recall</strong><small> [2]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Girase et al., "Latency Matters: Real-Time Action Forecasting Transformer", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Girase_Latency_Matters_Real-Time_Action_Forecasting_Transformer_CVPR_2023_paper.pdf>paper</a> <a href=https://karttikeya.github.io/publication/RAFTformer/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Girase_2023_CVPR,
    author = "Girase, Harshayu and Agarwal, Nakul and Choi, Chiho and Mangalam, Karttikeya",
    title = "Latency Matters: Real-Time Action Forecasting Transformer",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Mascaro et al., "HOI4ABOT: Human-Object Interaction Anticipation for Human Intention Reading Collaborative roBOTs", CoRL, 2023.</em></strong> <a href=https://openreview.net/pdf?id=rYZBdBytxBx>paper</a> <a href=https://arxiv.org/pdf/2309.16524.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#vidhoi">VidHOI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mascaro_2023_CoRL,
    author = "Mascaro, Esteve Valls and Sliwowski, Daniel and Lee, Dongheui",
    title = "HOI4ABOT: Human-Object Interaction Anticipation for Human Intention Reading Collaborative ro{BOT}s",
    booktitle = "CoRL",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhong et al., "Anticipative Feature Fusion Transformer for Multi-Modal Action Anticipation", WACV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/WACV2023/papers/Zhong_Anticipative_Feature_Fusion_Transformer_for_Multi-Modal_Action_Anticipation_WACV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.12649.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhong_2023_WACV,
    author = "Zhong, Zeyun and Schneider, David and Voit, Michael and Stiefelhagen, Rainer and Beyerer, Jurgen",
    title = "Anticipative Feature Fusion Transformer for Multi-Modal Action Anticipation",
    booktitle = "WACV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Song et al., "Pedestrian Intention Prediction Based on Traffic-Aware Scene Graph Model", IROS, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9981690>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_a-d_datasets.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Song_2022_IROS,
    author = "Song, Xingchen and Kang, Miao and Zhou, Sanping and Wang, Jianji and Mao, Yishu and Zheng, Nanning",
    booktitle = "IROS",
    title = "Pedestrian Intention Prediction Based on Traffic-Aware Scene Graph Model",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Liu et al., "Forecasting Human Object Interaction: Joint Prediction of Motor Attention and Actions in First Person Video", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460681.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.10967.pdf>arxiv</a> <a href=https://github.com/2020aptx4869lm/Forecasting-Human-Object-Interaction-in-FPV>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_e-i_datasets.md#fde">FDE</a></li>
<li><a href="action_a-d_datasets.md#ade">ADE</a></li>
<li><a href="action_j-z_datasets.md#kld">KLD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2020_ECCV,
    author = "Liu, Miao and Tang, Siyu and Li, Yin and Rehg, James",
    title = "Forecasting Human Object Interaction: Joint Prediction of Motor Attention and Actions in First Person Video",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Jayaraman et al., "Analysis and Prediction of Pedestrian Crosswalk Behavior during Automated Vehicle Interactions", ICRA, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9197347>paper</a> <a href=https://arxiv.org/pdf/2003.09996.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jayaraman_2020_ICRA,
    author = "Jayaraman, S. K. and Tilbury, D. M. and Yang, X. Jessie and Pradhan, A. K. and Robert, L. P.",
    booktitle = "ICRA",
    title = "Analysis and Prediction of Pedestrian Crosswalk Behavior during Automated Vehicle Interactions",
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
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
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
<summary><strong><em>Ke et al., "Time-Conditioned Action Anticipation In One Shot", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Ke_Time-Conditioned_Action_Anticipation_in_One_Shot_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ke_2019_CVPR,
    author = "Ke, Qiuhong and Fritz, Mario and Schiele, Bernt",
    title = "Time-Conditioned Action Anticipation In One Shot",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Furnari et al., "What Would You Expect? Anticipating Egocentric Actions With Rolling-Unrolling LSTMs And Modality Attention", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Furnari_What_Would_You_Expect_Anticipating_Egocentric_Actions_With_Rolling-Unrolling_LSTMs_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.09035.pdf>arxiv</a> <a href=https://github.com/fpv-iplab/rulstm>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Furnari_2019_ICCV,
    author = "Furnari, Antonino and Farinella, Giovanni Maria",
    title = "What Would You Expect? Anticipating Egocentric Actions With Rolling-Unrolling {LSTMs} And Modality Attention",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Sener et al., "Zero-Shot Anticipation For Instructional Activities", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Sener_Zero-Shot_Anticipation_for_Instructional_Activities_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.02501.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#youcook2">YouCook2</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#recipe1m">Recipe1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sener_2019_ICCV,
    author = "Sener, Fadime and Yao, Angela",
    title = "Zero-Shot Anticipation For Instructional Activities",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Rasouli et al., "Pedestrian Action Anticipation Using Contextual Feature Fusion In Stacked Rnns", BMVC, 2019.</em></strong> <a href=https://bmvc2019.org/wp-content/uploads/papers/0283-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.06582.pdf>arxiv</a> <a href=https://github.com/aras62/SF-GRU>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_a-d_datasets.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rasouli_2019_BMVC,
    author = "Rasouli, Amir and Kotseruba, Iuliia and Tsotsos, John K",
    title = "Pedestrian Action Anticipation Using Contextual Feature Fusion In Stacked Rnns",
    year = "2019",
    booktitle = "BMVC"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Ding et al., "Predicting Vehicle Behaviors Over An Extended Horizon Using Behavior Interaction Network", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8794146>paper</a> <a href=https://arxiv.org/pdf/1903.00848.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ding_2019_ICRA,
    author = "Ding, W. and Chen, J. and Shen, S.",
    booktitle = "ICRA",
    title = "Predicting Vehicle Behaviors Over An Extended Horizon Using Behavior Interaction Network",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Gujjar et al., "Classifying Pedestrian Actions In Advance Using Predicted Video Of Urban Driving Scenes", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8794278>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_a-d_datasets.md#ap">AP</a></li>
<li><a href="action_j-z_datasets.md#run_time">Run Time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gujjar_2019_ICRA,
    author = "Gujjar, P. and Vaughan, R.",
    booktitle = "ICRA",
    title = "Classifying Pedestrian Actions In Advance Using Predicted Video Of Urban Driving Scenes",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Scheel et al., "Attention-Based Lane Change Prediction", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8793648>paper</a> <a href=https://arxiv.org/pdf/1903.01246.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_j-z_datasets.md#ttm">TTM</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Scheel_2019_ICRA,
    author = "Scheel, O. and Nagaraja, N. S. and Schwarz, L. and Navab, N. and Tombari, F.",
    booktitle = "ICRA",
    title = "Attention-Based Lane Change Prediction",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Alati et al., "Help By Predicting What To Do", ICIP, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8803155>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#mpii_cooking">MPII Cooking</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Alati_2019_ICIP,
    author = "Alati, E. and Mauro, L. and Ntouskos, V. and Pirri, F.",
    booktitle = "ICIP",
    title = "Help By Predicting What To Do",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Furnari et al., "Egocentric Action Anticipation By Disentangling Encoding And Inference", ICIP, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8803534>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Furnari_2019_ICIP,
    author = "Furnari, A. and Farinella, G. M.",
    booktitle = "ICIP",
    title = "Egocentric Action Anticipation By Disentangling Encoding And Inference",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wang et al., "A Learning-Based Prediction Model For Baby Accidents", ICIP, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8803820>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_a-d_datasets.md#ap">AP</a></li>
<li><a href="action_j-z_datasets.md#tta">TTA</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2019_ICIP,
    author = "Wang, P. and Lien, S. and Lee, M.",
    booktitle = "ICIP",
    title = "A Learning-Based Prediction Model For Baby Accidents",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Suzuki et al., "Anticipating Traffic Accidents With Adaptive Loss And Large-Scale Incident Db", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0494.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.02675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
<li><a href="action_a-d_datasets.md#attc">ATTC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Suzuki_2018_CVPR,
    author = "Suzuki, Tomoyuki and Kataoka, Hirokatsu and Aoki, Yoshimitsu and Satoh, Yutaka",
    title = "Anticipating Traffic Accidents With Adaptive Loss And Large-Scale Incident Db",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Casas et al., "IntentNet: Learning To Predict Intention From Raw Sensor Data", CORL, 2018.</em></strong> <a href=http://proceedings.mlr.press/v87/casas18a/casas18a.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Casas_2018_CORL,
    author = "Casas, Sergio and Luo, Wenjie and Urtasun, Raquel",
    title = "{IntentNet}: Learning To Predict Intention From Raw Sensor Data",
    booktitle = "CORL",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Mahmud et al., "Joint Prediction Of Activity Labels And Starting Times In Untrimmed Videos", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Mahmud_Joint_Prediction_of_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#mpii_cooking">MPII Cooking</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#virat">VIRAT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_j-z_datasets.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mahmud_2017_ICCV,
    author = "Mahmud, Tahmida and Hasan, Mahmudul and Roy-Chowdhury, Amit K.",
    title = "Joint Prediction Of Activity Labels And Starting Times In Untrimmed Videos",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Qi et al., "Predicting Human Activities Using Stochastic Grammar", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Qi_Predicting_Human_Activities_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00945.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Qi_2017_ICCV,
    author = "Qi, Siyuan and Huang, Siyuan and Wei, Ping and Zhu, Song-Chun",
    title = "Predicting Human Activities Using Stochastic Grammar",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Kwak et al., "Pedestrian Intention Prediction Based On Dynamic Fuzzy Automata For Vehicle Driving At Nighttime", Infrared Physics & Technology, 2017.</em></strong> <a href=https://www.sciencedirect.com/science/article/abs/pii/S1350449516304935>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Kwak_2017_IPT,
    author = "Kwak, Joon-Young and Ko, Byoung Chul and Nam, Jae-Yeal",
    title = "Pedestrian Intention Prediction Based On Dynamic Fuzzy Automata For Vehicle Driving At Nighttime",
    journal = "Infrared Physics \& Technology",
    volume = "81",
    pages = "41--51",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Jain et al., "Structural-RNN: Deep Learning On Spatio-Temporal Graphs", CVPR, 2016.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.05298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_j-z_datasets.md#ttm">TTM</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jain_2016_CVPR,
    author = "Jain, Ashesh and Zamir, Amir R. and Savarese, Silvio and Saxena, Ashutosh",
    title = "{Structural-RNN}: Deep Learning On Spatio-Temporal Graphs",
    booktitle = "CVPR",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Jain et al., "Recurrent Neural Networks For Driver Activity Anticipation Via Sensory-Fusion Architecture", ICRA, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7487478>paper</a> <a href=https://arxiv.org/pdf/1509.05016.pdf>arxiv</a> <a href=https://github.com/asheshjain399/RNNexp>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_j-z_datasets.md#ttm">TTM</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jain_2016_ICRA,
    author = "Jain, A. and Singh, A. and Koppula, H. S. and Soh, S. and Saxena, A.",
    booktitle = "ICRA",
    title = "Recurrent Neural Networks For Driver Activity Anticipation Via Sensory-Fusion Architecture",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Hu et al., "Human Intent Forecasting Using Intrinsic Kinematic Constraints", IROS, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7759141>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2016_IROS,
    author = "Hu, N. and Bestick, A. and Englebienne, G. and Bajscy, R. and Kröse, B.",
    booktitle = "IROS",
    title = "Human Intent Forecasting Using Intrinsic Kinematic Constraints",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Schneemann et al., "Context-Based Detection Of Pedestrian Crossing Intention For Autonomous Driving In Urban Environments", IROS, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7759351>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Schneemann_2016_IROS,
    author = "Schneemann, F. and Heinemann, P.",
    booktitle = "IROS",
    title = "Context-Based Detection Of Pedestrian Crossing Intention For Autonomous Driving In Urban Environments",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Jain et al., "Car That Knows Before You Do: Anticipating Maneuvers Via Learning Temporal Driving Models", ICCV, 2015.</em></strong> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Jain_Car_That_Knows_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1504.02789.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_j-z_datasets.md#ttm">TTM</a></li>
<li><a href="action_e-i_datasets.md#fp">FP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jain_2015_ICCV,
    author = "Jain, Ashesh and Koppula, Hema S. and Raghavan, Bharad and Soh, Shane and Saxena, Ashutosh",
    title = "Car That Knows Before You Do: Anticipating Maneuvers Via Learning Temporal Driving Models",
    booktitle = "ICCV",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=rmse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Root Mean Square Error (RMSE)</strong><small> [8]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Ke et al., "Future Moment Assessment for Action Query", WACV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Ke_Future_Moment_Assessment_for_Action_Query_WACV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_a-d_datasets.md#auc">AUC</a></li>
<li><a href="action_j-z_datasets.md#rmse">RMSE</a></li>
<li><a href="action_j-z_datasets.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ke_2021_WACV,
    author = "Ke, Qiuhong and Fritz, Mario and Schiele, Bernt",
    title = "Future Moment Assessment for Action Query",
    booktitle = "WACV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Mahmud et al., "Joint Prediction Of Activity Labels And Starting Times In Untrimmed Videos", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Mahmud_Joint_Prediction_of_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#mpii_cooking">MPII Cooking</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#virat">VIRAT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_j-z_datasets.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mahmud_2017_ICCV,
    author = "Mahmud, Tahmida and Hasan, Mahmudul and Roy-Chowdhury, Amit K.",
    title = "Joint Prediction Of Activity Labels And Starting Times In Untrimmed Videos",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Mahmud et al., "A Poisson Process Model For Activity Forecasting", ICIP, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7532978>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#mpii_cooking">MPII Cooking</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mahmud_2016_ICIP,
    author = "Mahmud, T. and Hasan, M. and Chakraborty, A. and Roy-Chowdhury, A. K.",
    booktitle = "ICIP",
    title = "A Poisson Process Model For Activity Forecasting",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Volz et al., "A Data-Driven Approach For Pedestrian Intention Estimation", ITSC, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7795975>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Volz_2016_ITSC,
    author = "Volz, Benjamin and Behrendt, Karsten and Mielenz, Holger and Gilitschenski, Igor and Siegwart, Roland and Nieto, Juan",
    title = "A Data-Driven Approach For Pedestrian Intention Estimation",
    booktitle = "ITSC",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=rouge-l></a>
<details close>
<summary><em><l style="font-size:20px"><strong>ROUGE-L</strong><small> [11]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Hosseinzadeh et al., "Video Captioning of Future Frames", WACV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Hosseinzadeh_Video_Captioning_of_Future_Frames_WACV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#activitynet">ActivityNet</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#swag">SWAG</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#cider">CIDEr</a></li>
<li><a href="action_j-z_datasets.md#rouge-l">ROUGE-L</a></li>
<li><a href="action_j-z_datasets.md#meteor">METEOR</a></li>
<li><a href="action_a-d_datasets.md#bleu@n">BLEU@N</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hosseinzadeh_2021_WACV,
    author = "Hosseinzadeh, Mehrdad and Wang, Yang",
    title = "Video Captioning of Future Frames",
    booktitle = "WACV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=rt></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Run Time (RT)</strong><small> [10]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Girase et al., "Latency Matters: Real-Time Action Forecasting Transformer", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Girase_Latency_Matters_Real-Time_Action_Forecasting_Transformer_CVPR_2023_paper.pdf>paper</a> <a href=https://karttikeya.github.io/publication/RAFTformer/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Girase_2023_CVPR,
    author = "Girase, Harshayu and Agarwal, Nakul and Choi, Chiho and Mangalam, Karttikeya",
    title = "Latency Matters: Real-Time Action Forecasting Transformer",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Ito et al., "Anticipating the Start of User Interaction for Service Robot in the Wild", ICRA, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9196548>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#ap">AP</a></li>
<li><a href="action_j-z_datasets.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ito_2020_ICRA,
    author = "Ito, K. and Kong, Q. and Horiguchi, S. and Sumiyoshi, T. and Nagamatsu, K.",
    booktitle = "ICRA",
    title = "Anticipating the Start of User Interaction for Service Robot in the Wild",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=run_time></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Run Time</strong><small> [9]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Driess et al., "Deep Visual Reasoning: Learning to Predict Action Sequences for Task and Motion Planning from an Initial Scene Image", RSS, 2020.</em></strong> <a href=http://www.roboticsproceedings.org/rss16/p003.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.05398.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#run_time">Run Time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Driess_2020_RSS,
    author = "Driess, Danny and Ha, Jung-Su and Toussaint, Marc",
    title = "Deep Visual Reasoning: Learning to Predict Action Sequences for Task and Motion Planning from an Initial Scene Image",
    booktitle = "RSS",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Gujjar et al., "Classifying Pedestrian Actions In Advance Using Predicted Video Of Urban Driving Scenes", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8794278>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_a-d_datasets.md#ap">AP</a></li>
<li><a href="action_j-z_datasets.md#run_time">Run Time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gujjar_2019_ICRA,
    author = "Gujjar, P. and Vaughan, R.",
    booktitle = "ICRA",
    title = "Classifying Pedestrian Actions In Advance Using Predicted Video Of Urban Driving Scenes",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Saleh et al., "Real-Time Intent Prediction Of Pedestrians For Autonomous Ground Vehicles Via Spatio-Temporal DenseNet", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8793991>paper</a> <a href=https://arxiv.org/pdf/1904.09862.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#ap">AP</a></li>
<li><a href="action_j-z_datasets.md#run_time">Run Time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Saleh_2019_ICRA,
    author = "Saleh, K. and Hossny, M. and Nahavandi, S.",
    booktitle = "ICRA",
    title = "Real-Time Intent Prediction Of Pedestrians For Autonomous Ground Vehicles Via Spatio-Temporal {DenseNet}",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=tnr></a>
<details close>
<summary><em><l style="font-size:20px"><strong>TNR</strong><small> [11]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Volz et al., "Feature Relevance Estimation For Learning Pedestrian Behavior At Crosswalks", ITSC, 2015.</em></strong> <a href=https://ieeexplore.ieee.org/document/7313236>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#tnr">TNR</a></li>
<li><a href="action_j-z_datasets.md#tpr">TPR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Volz_2015_ITSC,
    author = "Volz, Benjamin and Mielenz, Holger and Agamennoni, Gabriel and Siegwart, Roland",
    title = "Feature Relevance Estimation For Learning Pedestrian Behavior At Crosswalks",
    booktitle = "ITSC",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=tpr></a>
<details close>
<summary><em><l style="font-size:20px"><strong>True Positive Rate (TPR)</strong><small> [11]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Volz et al., "Feature Relevance Estimation For Learning Pedestrian Behavior At Crosswalks", ITSC, 2015.</em></strong> <a href=https://ieeexplore.ieee.org/document/7313236>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#tnr">TNR</a></li>
<li><a href="action_j-z_datasets.md#tpr">TPR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Volz_2015_ITSC,
    author = "Volz, Benjamin and Mielenz, Holger and Agamennoni, Gabriel and Siegwart, Roland",
    title = "Feature Relevance Estimation For Learning Pedestrian Behavior At Crosswalks",
    booktitle = "ITSC",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=tta></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Time To Accident (TTA)</strong><small> [9]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Bao et al., "DRIVE: Deep Reinforced Accident Anticipation With Visual Explanation", ICCV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Bao_DRIVE_Deep_Reinforced_Accident_Anticipation_With_Visual_Explanation_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2107.10189.pdf>arxiv</a> <a href=https://github.com/Cogito2012/DRIVE>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#dada-2000">DADA-2000</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#auc">AUC</a></li>
<li><a href="action_j-z_datasets.md#tta">TTA</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bao_2021_ICCV,
    author = "Bao, Wentao and Yu, Qi and Kong, Yu",
    title = "{DRIVE}: Deep Reinforced Accident Anticipation With Visual Explanation",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wang et al., "A Learning-Based Prediction Model For Baby Accidents", ICIP, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8803820>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_a-d_datasets.md#ap">AP</a></li>
<li><a href="action_j-z_datasets.md#tta">TTA</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2019_ICIP,
    author = "Wang, P. and Lien, S. and Lee, M.",
    booktitle = "ICIP",
    title = "A Learning-Based Prediction Model For Baby Accidents",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zeng et al., "Agent-Centric Risk Assessment: Accident Anticipation And Risky Region Localization", CVPR, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Zeng_Agent-Centric_Risk_Assessment_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.06560.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#epic-fail">Epic-Fail</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#map">mAP</a></li>
<li><a href="action_j-z_datasets.md#tta">TTA</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zeng_2017_CVPR,
    author = "Zeng, Kuo-Hao and Chou, Shih-Han and Chan, Fu-Hsiang and Carlos Niebles, Juan and Sun, Min",
    title = "Agent-Centric Risk Assessment: Accident Anticipation And Risky Region Localization",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=ttm></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Time To Maneuver (TTM)</strong><small> [7]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Scheel et al., "Attention-Based Lane Change Prediction", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8793648>paper</a> <a href=https://arxiv.org/pdf/1903.01246.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_j-z_datasets.md#ttm">TTM</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Scheel_2019_ICRA,
    author = "Scheel, O. and Nagaraja, N. S. and Schwarz, L. and Navab, N. and Tombari, F.",
    booktitle = "ICRA",
    title = "Attention-Based Lane Change Prediction",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wu et al., "Gaze-Based Intention Anticipation Over Driving Manoeuvres In Semi-Autonomous Vehicles", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8967779>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="action_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="action_j-z_datasets.md#ttm">TTM</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wu_2019_IROS,
    author = "Wu, Min and Louw, Tyron and Lahijanian, Morteza and Ruan, Wenjie and Huang, Xiaowei and Merat, Natasha and Kwiatkowska, Marta",
    booktitle = "IROS",
    title = "Gaze-Based Intention Anticipation Over Driving Manoeuvres In Semi-Autonomous Vehicles",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Jain et al., "Structural-RNN: Deep Learning On Spatio-Temporal Graphs", CVPR, 2016.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.05298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_e-i_datasets.md#f1">F1</a></li>
<li><a href="action_j-z_datasets.md#ttm">TTM</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jain_2016_CVPR,
    author = "Jain, Ashesh and Zamir, Amir R. and Savarese, Silvio and Saxena, Ashutosh",
    title = "{Structural-RNN}: Deep Learning On Spatio-Temporal Graphs",
    booktitle = "CVPR",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Jain et al., "Recurrent Neural Networks For Driver Activity Anticipation Via Sensory-Fusion Architecture", ICRA, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7487478>paper</a> <a href=https://arxiv.org/pdf/1509.05016.pdf>arxiv</a> <a href=https://github.com/asheshjain399/RNNexp>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_j-z_datasets.md#ttm">TTM</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jain_2016_ICRA,
    author = "Jain, A. and Singh, A. and Koppula, H. S. and Soh, S. and Saxena, A.",
    booktitle = "ICRA",
    title = "Recurrent Neural Networks For Driver Activity Anticipation Via Sensory-Fusion Architecture",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Jain et al., "Car That Knows Before You Do: Anticipating Maneuvers Via Learning Temporal Driving Models", ICCV, 2015.</em></strong> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Jain_Car_That_Knows_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1504.02789.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="action_j-z_datasets.md#recall">Recall</a></li>
<li><a href="action_j-z_datasets.md#precision">Precision</a></li>
<li><a href="action_j-z_datasets.md#ttm">TTM</a></li>
<li><a href="action_e-i_datasets.md#fp">FP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jain_2015_ICCV,
    author = "Jain, Ashesh and Koppula, Hema S. and Raghavan, Bharad and Soh, Shane and Saxena, Ashutosh",
    title = "Car That Knows Before You Do: Anticipating Maneuvers Via Learning Temporal Driving Models",
    booktitle = "ICCV",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul>