<a name=top></a>
<a name=top></a>
---
<a href=../../README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Datasets</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../metrics/metrics.md#top><l style="font-size:30px">Metrics</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
[Home](../datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Alphabetical](../alphabetical/alphabetical_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Year&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Application](../application/application_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Task](../task/task_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Annotation](../annotation_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[2018-present](2018-Present_year_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;2014-2017&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Before-2013](Before-2013_year_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
<h2>2014-2017</h2> 
<h2>2017</h2>
<ul><a name=jaad></a>
<details close>
<summary><l style="font-size:20px"><strong>Joint Attention in Autonomous Driving (JAAD)</strong></l> <a href=http://data.nvision2.eecs.yorku.ca/JAAD_dataset/>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w3/Rasouli_Are_They_Going_ICCV_2017_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of pedestrians with 346 video sequences showing pedestrians at the time of crossing in different geographical locations and under different weather conditions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a>, <a href=../../papers/action/action_papers.md#top>Action prediction<application></a>, <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, attribute, temporal segment, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chaabane et al., "Looking Ahead: Anticipating Pedestrians Crossing with Future Frames Prediction", WACV, 2020.</em> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Chaabane_Looking_Ahead_Anticipating_Pedestrians_Crossing_with_Future_Frames_Prediction_WACV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.09077.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#l1">L1</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chaabane_2020_WACV,
    author = "Chaabane, Mohamed and Trabelsi, Ameni and Blanchard, Nathaniel and Beveridge, Ross",
    title = "Looking Ahead: Anticipating Pedestrians Crossing with Future Frames Prediction",
    booktitle = "WACV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Gujjar et al., "Classifying Pedestrian Actions In Advance Using Predicted Video Of Urban Driving Scenes", ICRA, 2019.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8794278>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#l1">L1</a></li>
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
<summary><em>Rasouli et al., "PedFormer: Pedestrian Behavior Prediction via Cross-Modal Attention Modulation and Gated Multitask Learning", ICRA, 2023.</em> <a href=https://ieeexplore.ieee.org/document/10161318>paper</a> <a href=https://arxiv.org/pdf/2210.07886.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#auc">AUC</a></li>
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
<summary><em>Song et al., "Pedestrian Intention Prediction Based on Traffic-Aware Scene Graph Model", IROS, 2022.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9981690>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#auc">AUC</a></li>
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
<summary><em>Zhai et al., "Social Aware Multi-Modal Pedestrian Crossing Behavior Prediction", ACCV, 2022.</em> <a href=https://openaccess.thecvf.com/content/ACCV2022/papers/Zhai_Social_Aware_Multi-Modal_Pedestrian_Crossing_Behavior_Prediction_ACCV_2022_paper.pdf>paper</a> <a href=https://github.com/zxll0106/Pedestrian_Crossing_Behavior_Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#auc">AUC</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#map">mAP</a></li>
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
<summary><em>Rasouli et al., "Bifold and Semantic Reasoning for Pedestrian Behavior Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Rasouli_Bifold_and_Semantic_Reasoning_for_Pedestrian_Behavior_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2012.03298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#auc">AUC</a></li>
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
<summary><em>Sui et al., "Joint Intention and Trajectory Prediction Based on Transformer", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636241>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#ap">AP</a></li>
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
<summary><em>Kotseruba et al., "Benchmark for Evaluating Pedestrian Action Prediction", WACV, 2021.</em> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Kotseruba_Benchmark_for_Evaluating_Pedestrian_Action_Prediction_WACV_2021_paper.pdf>paper</a> <a href=https://github.com/ykotseruba/PedestrianActionBenchmark>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kotseruba_2021_WACV,
    author = "Kotseruba, Iuliia and Rasouli, Amir and Tsotsos, John K.",
    title = "Benchmark for Evaluating Pedestrian Action Prediction",
    booktitle = "WACV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liu et al., "Spatiotemporal Relationship Reasoning for Pedestrian Intent Prediction", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9013045>paper</a> <a href=https://arxiv.org/pdf/2002.08945.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#stip">STIP</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Liu_2020_RAL,
    author = "Liu, B. and Adeli, E. and Cao, Z. and Lee, K. and Shenoi, A. and Gaidon, A. and Niebles, J. C.",
    journal = "RAL",
    title = "Spatiotemporal Relationship Reasoning for Pedestrian Intent Prediction",
    year = "2020",
    volume = "5",
    number = "2",
    pages = "3485-3492"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Saleh et al., "Real-Time Intent Prediction Of Pedestrians For Autonomous Ground Vehicles Via Spatio-Temporal DenseNet", ICRA, 2019.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8793991>paper</a> <a href=https://arxiv.org/pdf/1904.09862.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#ap">AP</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#run_time">Run Time</a></li>
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
<details close>
<summary><em>Aliakbarian et al., "VIENA2: A Driving Anticipation Dataset", ACCV, 2018.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20887-5_28>paper</a> <a href=https://arxiv.org/pdf/1810.09044.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#viena">VIENA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Aliakbarian_2018_ACCV,
    author = "Aliakbarian, Mohammad Sadegh and Saleh, Fatemeh Sadat and Salzmann, Mathieu and Fernando, Basura and Petersson, Lars and Andersson, Lars",
    editor = "Jawahar, C. V. and Li, Hongdong and Mori, Greg and Schindler, Konrad",
    title = "{VIENA2}: A Driving Anticipation Dataset",
    booktitle = "ACCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Rasouli et al., "Are They Going To Cross? A Benchmark Dataset And Baseline For Pedestrian Crosswalk Behavior", ICCVW, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w3/Rasouli_Are_They_Going_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#map">mAP</a></li>
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
<summary><em>Rasouli, "A Novel Benchmarking Paradigm and a Scale- and Motion-Aware Model for Egocentric Pedestrian Trajectory Prediction", ICRA, 2024.</em> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10610614>paper</a> <a href=https://arxiv.org/pdf/2310.10424>arxiv</a> <a href=https://github.com/aras62/PIE/tree/master/scenarioEval>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#sminade">sminADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#sade">sADE</a></li>
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
<summary><em>Feng et al., "Multimodal Forward Generation Transformer Network for Inconspicuous Pedestrian Trajectory Prediction", RAL, 2024.</em> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10382571>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Feng_Multimodal_2024_RAL,
    author = "Feng, Ang and Qiu, Ruiqi and Wang, Jinglong and Gong, Jun and Yi, Yang and Dong, Mingtao",
    journal = "RAL",
    title = "Multimodal Forward Generation Transformer Network for Inconspicuous Pedestrian Trajectory Prediction",
    year = "2024",
    volume = "9",
    number = "3",
    pages = "2224-2231"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Huynh et al., "Online Adaptive Temporal Memory With Certainty Estimation for Human Trajectory Prediction", WACV, 2023.</em> <a href=https://openaccess.thecvf.com/content/WACV2023/papers/Huynh_Online_Adaptive_Temporal_Memory_With_Certainty_Estimation_for_Human_Trajectory_WACV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Halawa et al., "Action-Based Contrastive Learning for Trajectory Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136990140.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.08664.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#titan">TITAN</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Wang et al., "Stepwise Goal-Driven Networks for Trajectory Prediction", RAL, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9691856>paper</a> <a href=https://arxiv.org/pdf/2103.14107.pdf>arxiv</a> <a href=https://github.com/ChuhuaW/SGNet.pytorch>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#hev-i">HEV-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
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
<summary><em>Neumann et al., "Pedestrian and Ego-Vehicle Trajectory Prediction From Monocular Camera", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Neumann_Pedestrian_and_Ego-Vehicle_Trajectory_Prediction_From_Monocular_Camera_CVPR_2021_paper.pdf>paper</a> <a href=https://gitlab.com/lukeN86/pedFutureTracking>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Neumann_2021_CVPR,
    author = "Neumann, Lukas and Vedaldi, Andrea",
    title = "Pedestrian and Ego-Vehicle Trajectory Prediction From Monocular Camera",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yao et al., "BiTraP: Bi-Directional Pedestrian Trajectory Prediction With Multi-Modal Goal Estimation", RAL, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9345445>paper</a> <a href=https://arxiv.org/pdf/2007.14558.pdf>arxiv</a> <a href=https://github.com/umautobots/bidireaction-trajectory-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Mangalam et al., "Disentangling Human Dynamics for Pedestrian Locomotion Forecasting with Noisy Supervision", WACV, 2020.</em> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Mangalam_Disentangling_Human_Dynamics_for_Pedestrian_Locomotion_Forecasting_with_Noisy_Supervision_WACV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.01138.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#kde">KDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mangalam_2020_WACV,
    author = "Mangalam, Karttikeya and Adeli, Ehsan and Lee, Kuan-Hui and Gaidon, Adrien and Niebles, Juan Carlos",
    title = "Disentangling Human Dynamics for Pedestrian Locomotion Forecasting with Noisy Supervision",
    booktitle = "WACV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ansari et al., "Simple means Faster: Real-Time Human Motion Forecasting in Monocular First Person Videos on CPU", IROS, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9340999>paper</a> <a href=https://arxiv.org/pdf/2011.04943.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#fpl">FPL</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#citywalks">CityWalks</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Rasouli et al., "PIE: A Large-Scale Dataset And Models For Pedestrian Intention Estimation And Trajectory Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.pdf>paper</a> <a href=https://github.com/aras62/PIEPredict>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Du et al., "Unsupervised Pedestrian Pose Prediction: A Deep Predictive Coding Network-Based Approach for Autonomous Vehicle Perception", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9042808>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pedx">PedX</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Du_2020_RAL,
    author = "Du, X. and Vasudevan, R. and Johnson-Roberson, M.",
    journal = "RAL",
    title = "Unsupervised Pedestrian Pose Prediction: A Deep Predictive Coding Network-Based Approach for Autonomous Vehicle Perception",
    year = "2020",
    volume = "27",
    number = "2",
    pages = "129-138"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Afolabi et al., "People As Sensors: Imputing Maps From Human Actions", IROS, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8594511>paper</a> <a href=https://arxiv.org/pdf/1711.01022.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#psi">Psi</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#ism">ISM</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Afolabi_2018_IROS,
    author = "Afolabi, O. and Driggs–Campbell, K. and Dong, R. and Kochenderfer, M. J. and Sastry, S. S.",
    booktitle = "IROS",
    title = "People As Sensors: Imputing Maps From Human Actions",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Rasouli_2017_ICCVW,
    author = "Rasouli, Amir and Kotseruba, Iuliia and Tsotsos, John K.",
    title = "Are They Going To Cross? A Benchmark Dataset And Baseline For Pedestrian Crosswalk Behavior",
    booktitle = "ICCVW",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=dad></a>
<details close>
<summary><l style="font-size:20px"><strong>Dashcam Accident Dataset (DAD)</strong></l> <a href=https://aliensunmin.github.io/project/dashcam/>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-54190-7_9>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 620 video sequences of traffic accidents recorded in six cities
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, object class, temporal segment, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Bao et al., "DRIVE: Deep Reinforced Accident Anticipation With Visual Explanation", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Bao_DRIVE_Deep_Reinforced_Accident_Anticipation_With_Visual_Explanation_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2107.10189.pdf>arxiv</a> <a href=https://github.com/Cogito2012/DRIVE>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#dada-2000">DADA-2000</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#auc">AUC</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#tta">TTA</a></li>
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
<summary><em>Suzuki et al., "Anticipating Traffic Accidents With Adaptive Loss And Large-Scale Incident Db", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0494.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.02675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#map">mAP</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#attc">ATTC</a></li>
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
<summary><em>Zeng et al., "Agent-Centric Risk Assessment: Accident Anticipation And Risky Region Localization", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Zeng_Agent-Centric_Risk_Assessment_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.06560.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-fail">Epic-Fail</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#map">mAP</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#tta">TTA</a></li>
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
<summary><em>Yao et al., "Unsupervised Traffic Accident Detection in First-Person Videos", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8967556>paper</a> <a href=https://arxiv.org/pdf/1903.00618.pdf>arxiv</a> <a href=https://github.com/MoonBlvd/tad-IROS2019>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#hev-i">HEV-I</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#a3d">A3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Chan_2017_ACCV,
    author = "Chan, Fu-Hsiang and Chen, Yu-Ting and Xiang, Yu and Sun, Min",
    editor = "Lai, Shang-Hong and Lepetit, Vincent and Nishino, Ko and Sato, Yoichi",
    title = "Anticipating Accidents In Dashcam Videos",
    booktitle = "ACCV",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=jigsaws></a>
<details close>
<summary><l style="font-size:20px"><strong>JIGSAWS</strong></l> <a href=https://cirl.lcsr.jhu.edu/research/hmm/datasets/jigsaws_release/>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/7805258>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 3 surgical operation actions performed by 8 subjects using robotic arms
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, Activity Label, Temporal Segment</li>
<li><em><strong>Task:</strong></em> Robot</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Gao et al., "Accurate Grid Keypoint Learning for Efficient Video Prediction", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636874>paper</a> <a href=https://arxiv.org/pdf/2107.13170.pdf>arxiv</a> <a href=https://github.com/xjgaocs/Grid-Keypoint-Learning>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jigsaws">JIGSAWS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2021_IROS,
    author = "Gao, Xiaojie and Jin, Yueming and Dou, Qi and Fu, Chi-Wing and Heng, Pheng-Ann",
    booktitle = "IROS",
    title = "Accurate Grid Keypoint Learning for Efficient Video Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Weerasinghe et al., "Multimodal Transformers for Real-Time Surgical Activity Prediction", ICRA, 2024.</em> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10611048>paper</a> <a href=https://arxiv.org/pdf/2403.06705>arxiv</a> <a href=https://github.com/UVA-DSA/MTRSAP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jigsaws">JIGSAWS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_e-i_metrics.md#edist">EDist</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Weerasinghe_Multimodal_2024_ICRA,
    author = "Weerasinghe, Keshara and Reza Roodabeh, Seyed Hamid and Hutchinson, Kay and Alemzadeh, Homa",
    booktitle = "ICRA",
    title = "Multimodal Transformers for Real-Time Surgical Activity Prediction",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Park et al., "Recognition and Prediction of Surgical Actions Based on Online Robotic Tool Detection", RAL, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9357894>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jigsaws">JIGSAWS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Park_2021_RAL,
    author = "Park, Juyoun and Park, Chung Hyuk",
    journal = "RAL",
    title = "Recognition and Prediction of Surgical Actions Based on Online Robotic Tool Detection",
    year = "2021",
    volume = "6",
    number = "2",
    pages = "2365-2372"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Ahmidi_2017_BE,
    author = "Ahmidi, Narges and Tao, Lingling and Sefati, Shahin and Gao, Yixin and Lea, Colin and Haro, Benjamín Béjar and Zappella, Luca and Khudanpur, Sanjeev and Vidal, René and Hager, Gregory D.",
    journal = "IEEE Transactions on Biomedical Engineering",
    title = "A Dataset and Benchmarks for Segmentation and Recognition of Gestures in Robotic Surgery",
    year = "2017",
    volume = "64",
    number = "9",
    pages = "2025-2041"
}
</pre>
</details>

</ul></details>
<a name=smtsmt></a>
<details close>
<summary><l style="font-size:20px"><strong>Something Something (SmtSmt)</strong></l> <a href=https://developer.qualcomm.com/software/ai-datasets/something-something>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Goyal_The_Something_Something_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1706.04261.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 220+ K videos of different actors interacting with various objects
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity Label</li>
<li><em><strong>Task:</strong></em> Object interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Gu et al., "Seer: Language Instructed Video Prediction with Latent Diffusion Models", ICLR, 2024.</em> <a href=https://openreview.net/pdf?id=qHGgNyQk31>paper</a> <a href=https://arxiv.org/pdf/2303.14897>arxiv</a> <a href=https://seervideodiffusion.github.io/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#smtsmt">SmtSmt</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bridgedata">BridgeData</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#kvd">KVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Gu_seer_2024_ICLR,
    author = "Gu, Xianfan and Wen, Chuan and Ye, Weirui and Song, Jiaming and Gao, Yang",
    title = "Seer: Language Instructed Video Prediction with Latent Diffusion Models",
    booktitle = "ICLR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chang et al., "MAU: A Motion-Aware Unit for Video Prediction and Beyond", NeurIPS, 2021.</em> <a href=https://papers.nips.cc/paper/2021/file/e25cfa90f04351958216f97e3efdabe9-Paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#town_center">Town Center</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#smtsmt">SmtSmt</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chang_2021_NeurIPS,
    author = "Chang, Zheng and Zhang, Xinfeng and Wang, Shanshe and Ma, Siwei and Ye, Yan and Xinguang, Xiang and Gao, Wen",
    booktitle = "NeurIPS",
    title = "{MAU}: A Motion-Aware Unit for Video Prediction and Beyond",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Stergiou et al., "The Wisdom of Crowds: Temporal Progressive Attention for Early Action Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Stergiou_The_Wisdom_of_Crowds_Temporal_Progressive_Attention_for_Early_Action_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.13340.pdf>arxiv</a> <a href=https://alexandrosstergiou.github.io/project_pages/TemPr/index.html>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#smtsmt">SmtSmt</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Stergiou_2023_CVPR,
    author = "Stergiou, Alexandros and Damen, Dima",
    title = "The Wisdom of Crowds: Temporal Progressive Attention for Early Action Prediction",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Goya_2017_CVPR,
    author = "Goyal, Raghav and Ebrahimi Kahou, Samira and Michalski, Vincent and Materzynska, Joanna and Westphal, Susanne and Kim, Heuna and Haenel, Valentin and Fruend, Ingo and Yianilos, Peter and Mueller-Freitag, Moritz and others",
    title = "The {Something Something} Video Database for Learning and Evaluating Visual Common Sense",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=kinetics-400></a>
<details close>
<summary><l style="font-size:20px"><strong>Kinetics-400</strong></l> <a href=https://deepmind.com/research/open-source/kinetics>link</a> <a href=https://arxiv.org/pdf/1705.06950.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale dataset 300K+ video clips of 400 human action classes, e.g. drawing, drinking, laughing,  each containing ~10s clips
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Suris et al., "Learning the Predictability of the Future", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Suris_Learning_the_Predictability_of_the_Future_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2101.01600.pdf>arxiv</a> <a href=https://github.com/cvlab-columbia/hyperfuture/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kinetics-400">Kinetics-400</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#finegym">FineGym</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Suris_2021_CVPR,
    author = "Suris, Didac and Liu, Ruoshi and Vondrick, Carl",
    title = "Learning the Predictability of the Future",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "Self-supervised Video Representation Learning by Pace Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123620494.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.05861.pdf>arxiv</a> <a href=https://github.com/laura-wang/video-pace>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kinetics-400">Kinetics-400</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#hmdb">HMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#accuracy">Accuracy</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Kay_2017_arxiv,
    author = "Kay, Will and Carreira, Joao and Simonyan, Karen and Zhang, Brian and Hillier, Chloe and Vijayanarasimhan, Sudheendra and Viola, Fabio and Green, Tim and Back, Trevor and Natsev, Paul and Suleyman, Mustafa and Zisserman, Andrew",
    title = "The Kinetics Human Action Video Dataset",
    journal = "arXiv:1705.06950",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=md17></a>
<details close>
<summary><l style="font-size:20px"><strong>MD17</strong></l> <a href=http://quantum-machine.org/datasets/>link</a> <a href=https://arxiv.org/pdf/1611.04678.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of simulated dynamic objects.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Trajectory</li>
<li><em><strong>Task:</strong></em> Simulation</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Xu et al., "Uncovering the Missing Pattern: Unified Framework Towards Trajectory Imputation and Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Xu_EqMotion_Equivariant_Multi-Agent_Motion_Prediction_With_Invariant_Interaction_Reasoning_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.10876.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/EqMotion>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#md17">MD17</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Yu et al., "Pose-Transformed Equivariant Network for 3D Point Trajectory Prediction", CVPR, 2024.</em> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Yu_Pose-Transformed_Equivariant_Network_for_3D_Point_Trajectory_Prediction_CVPR_2024_paper.pdf>paper</a> <a href=https://github.com/yuruixuan/PTEvNet.>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#md17">MD17</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yu_Pose_2024_CVPR,
    author = "Yu, Ruixuan and Sun, Jian",
    title = "Pose-Transformed Equivariant Network for 3D Point Trajectory Prediction",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@article{Chmiela_2017_SA,
    author = "Chmiela, Stefan and Tkatchenko, Alexandre and Sauceda, Huziel E and Poltavsky, Igor and Schutt, Kristof T and Muller, Klaus-Robert",
    title = "Machine learning of accurate energy-conserving molecular force fields",
    journal = "Science Advances",
    volume = "3",
    number = "5",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=mouse_fish></a>
<details close>
<summary><l style="font-size:20px"><strong>Mouse Fish</strong></l> <a href=https://web.bii.a-star.edu.sg/archive/machine_learning/Projects/behaviorAnalysis/Lie-X/Lie-X.html>link</a> <a href=https://link.springer.com/article/10.1007/s11263-017-0998-6>paper</a> <a href=https://arxiv.org/pdf/1609.03773.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of fishes and mice in a lab environment with corresponding 2D poses
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/motion/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Depth, 3D pose</li>
<li><em><strong>Task:</strong></em> Animal</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liu et al., "Motion Prediction Using Trajectory Cues", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Liu_Motion_Prediction_Using_Trajectory_Cues_ICCV_2021_paper.pdf>paper</a> <a href=https://github.com/Pose-Group/MPT>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mouse_fish">Mouse Fish</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2021_ICCV,
    author = "Liu, Zhenguang and Su, Pengxiang and Wu, Shuang and Shen, Xuanjing and Chen, Haipeng and Hao, Yanbin and Wang, Meng",
    title = "Motion Prediction Using Trajectory Cues",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liu et al., "Towards Natural And Accurate Future Motion Prediction Of Humans And Animals", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Liu_Towards_Natural_and_Accurate_Future_Motion_Prediction_of_Humans_and_CVPR_2019_paper.pdf>paper</a> <a href=https://github.com/BII-wushuang/Lie-Group-Motion-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mouse_fish">Mouse Fish</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#run_time">Run Time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2019_CVPR,
    author = "Liu, Zhenguang and Wu, Shuang and Jin, Shuyuan and Liu, Qi and Lu, Shijian and Zimmermann, Roger and Cheng, Li",
    title = "Towards Natural And Accurate Future Motion Prediction Of Humans And Animals",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Xu_2017_IJCV,
    author = "Xu, Chi and Govindarajan, Lakshmi Narasimhan and Zhang, Yu and Cheng, Li",
    title = "{Lie-X}: Depth Image Based Articulated Object Pose Estimation, Tracking, And Action Recognition On Lie Groups",
    journal = "IJCV",
    volume = "123",
    number = "3",
    pages = "454--478",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=orc></a>
<details close>
<summary><l style="font-size:20px"><strong>Oxford Robot Car (ORC)</strong></l> <a href=https://robotcar-dataset.robots.ox.ac.uk/>link</a> <a href=https://journals.sagepub.com/doi/abs/10.1177/0278364916679498>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset containing 100 repetitions of a consistent route through Oxford driving by a vehicle under different weather and traffic conditions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, LIDAR, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Marchetti et al., "MANTRA: Memory Augmented Networks for Multiple Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Marchetti_MANTRA_Memory_Augmented_Networks_for_Multiple_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.03340.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#orc">ORC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Marchetti_2020_CVPR,
    author = "Marchetti, Francesco and Becattini, Federico and Seidenari, Lorenzo and Del Bimbo, Alberto",
    title = "{MANTRA}: Memory Augmented Networks for Multiple Trajectory Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Srikanth et al., "INFER: INtermediate Representations For FuturE PRediction", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8968553>paper</a> <a href=https://arxiv.org/pdf/1903.10641.pdf>arxiv</a> <a href=https://rebrand.ly/INFER-results>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#oxford">Oxford</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Srikanth_2019_IROS,
    author = "Srikanth, Shashank and Ansari, Junaid Ahmed and Sharma, Sarthak and others",
    booktitle = "IROS",
    title = "{INFER}: {IN}termediate Representations For {F}utur{E} P{R}ediction",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Maddern_2017_IJRR,
    Author = "Maddern, Will and Pascoe, Geoff and Linegar, Chris and Newman, Paul",
    Title = "1 Year, 1000Km: The {O}xford Robotcar Dataset",
    Journal = "IJRR",
    Volume = "36",
    Number = "1",
    Pages = "3-15",
    Year = "2017"
}
</pre>
</details>

</ul></details>
<a name=pku-mmd></a>
<details close>
<summary><l style="font-size:20px"><strong>PKU-MMD</strong></l> <a href=http://www.icst.pku.edu.cn/struct/Projects/PKUMMD.html>link</a> <a href=https://arxiv.org/pdf/1703.07475.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A multimodal dataset of 41 daily activities and 10 interaction actions recorded from 3 camera views using 60 subjects
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, IR, 3D pose, multiview, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity, Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liu et al., "SSNet: Scale Selection Network For Online 3D Action Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_SSNet_Scale_Selection_CVPR_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pku-mmd">PKU-MMD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#oad">OAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2018_CVPR_ssnet,
    author = "Liu, Jun and Shahroudy, Amir and Wang, Gang and Duan, Ling-Yu and Kot, Alex C.",
    title = "{SSNet}: Scale Selection Network For Online {3D} Action Prediction",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Mao et al., "Masked Motion Predictors are Strong 3D Action Representation Learners", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Mao_Masked_Motion_Predictors_are_Strong_3D_Action_Representation_Learners_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.07092.pdf>arxiv</a> <a href=https://github.com/maoyunyao/MAMP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pku-mmd">PKU-MMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mao_2023_ICCV,
    author = "Mao, Yunyao and Deng, Jiajun and Zhou, Wengang and Fang, Yao and Ouyang, Wanli and Li, Houqiang",
    title = "Masked Motion Predictors are Strong 3D Action Representation Learners",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Liu_2017_arxiv,
    author = "Chunhui, Liu and Yueyu, Hu and Yanghao, Li and Sijie, Song and Jiaying, Liu",
    title = "{PKU-MMD}: A Large Scale Benchmark For Continuous Multi-Modal Human Action Understanding",
    journal = "arXiv:1703.07475",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=recipe1m></a>
<details close>
<summary><l style="font-size:20px"><strong>Recipe1M</strong></l> <a href=http://pic2recipe.csail.mit.edu/>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Learning_Cross-Modal_Embeddings_With_Adversarial_Networks_for_Cooking_Recipes_and_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.01273.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 1M+ cooking recipes with 13M food images
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, text</li>
<li><em><strong>Task:</strong></em> Cooking</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sener et al., "Zero-Shot Anticipation For Instructional Activities", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Sener_Zero-Shot_Anticipation_for_Instructional_Activities_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.02501.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#youcook2">YouCook2</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#recipe1m">Recipe1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
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
<summary><em>Abdelsalam et al., "GePSAn: Generative Procedure Step Anticipation in Cooking Videos", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Abdelsalam_GePSAn_Generative_Procedure_Step_Anticipation_in_Cooking_Videos_ICCV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#youcook2">YouCook2</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#recipe1m">Recipe1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#bleu">BLEU</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#meteor">METEOR</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Salvador_2017_CVPR,
    author = "Salvador, Amaia and Hynes, Nicholas and Aytar, Yusuf and Marin, Javier and Ofli, Ferda and Weber, Ingmar and Torralba, Antonio",
    title = "Learning Cross-Modal Embeddings For Cooking Recipes And Food Images",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=l-cas></a>
<details close>
<summary><l style="font-size:20px"><strong>L-CAS</strong></l> <a href=https://lcas.lincoln.ac.uk/wp/research/data-sets-software/l-cas-3d-point-cloud-people-dataset/>link</a> <a href=https://ieeexplore.ieee.org/document/8202247>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 28K indoor LIDAR scans showing the surroundings of a mobile robot in stationary or moving states
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> LIDAR, 3D bounding box, attribute</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sun et al., "3Dof Pedestrian Trajectory Prediction Learned From Long-Term Autonomous Mobile Robot Deployment Data", ICRA, 2018.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8461228>paper</a> <a href=https://arxiv.org/pdf/1710.00126.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#strands">STRANDS</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#l-cas">L-CAS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#aede">AEDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2018_ICRA,
    author = "Sun, L. and Yan, Z. and Mellado, S. M. and Hanheide, M. and Duckett, T.",
    booktitle = "ICRA",
    title = "{3Dof} Pedestrian Trajectory Prediction Learned From Long-Term Autonomous Mobile Robot Deployment Data",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Yan_2017_IROS,
    author = "Yan, Zhi and Duckett, Tom and Bellotto, Nicola",
    title = "Online Learning For Human Classification In {3D} Lidar-Based Tracking",
    booktitle = "IROS",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=epic-fail></a>
<details close>
<summary><l style="font-size:20px"><strong>Epic-Fail</strong></l> <a href=http://aliensunmin.github.io/project/video-Forecasting/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Zeng_Agent-Centric_Risk_Assessment_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.06560.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A risk-assessment dataset of failed activity videos with 3K samples annotated at every 15 frames with bounding boxes around risky regions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, trajectory, temporal segment</li>
<li><em><strong>Task:</strong></em> Risk assessment</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zeng et al., "Agent-Centric Risk Assessment: Accident Anticipation And Risky Region Localization", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Zeng_Agent-Centric_Risk_Assessment_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.06560.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-fail">Epic-Fail</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#map">mAP</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#tta">TTA</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Zeng_2017_CVPR,
    author = "Zeng, Kuo-Hao and Chou, Shih-Han and Chan, Fu-Hsiang and Carlos Niebles, Juan and Sun, Min",
    title = "Agent-Centric Risk Assessment: Accident Anticipation And Risky Region Localization",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=cityperson></a>
<details close>
<summary><l style="font-size:20px"><strong>CityPersons</strong></l> <a href=https://bitbucket.org/shanshanzhang/citypersons/src/default/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_CityPersons_A_Diverse_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1702.05693.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A subset of Cityscapes dataset with fine-grained annotations for pedestrians and vehicles in additional 20K images with a total of 35K+ bounding boxes for pedestrians
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, bounding box, semantic segment</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Bhattacharyya et al., "Long-Term On-Board Prediction Of People In Traffic Scenes Under Uncertainty", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Bhattacharyya_Long-Term_On-Board_Prediction_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1711.09026.pdf>arxiv</a> <a href=https://github.com/apratimbhattacharyya18/onboard_long_term_prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityperson">CityPerson</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bhattacharyya_2018_CVPR,
    author = "Bhattacharyya, Apratim and Fritz, Mario and Schiele, Bernt",
    title = "Long-Term On-Board Prediction Of People In Traffic Scenes Under Uncertainty",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Shanshan_2017_CVPR,
    Author = "Zhang, Shanshan and Benenson, Rodrigo and Schiele, Bernt",
    Title = "Citypersons: A Diverse Dataset For Pedestrian Detection",
    Booktitle = "CVPR",
    Year = "2017"
}
</pre>
</details>

</ul></details>
<a name=strands></a>
<details close>
<summary><l style="font-size:20px"><strong>STRANDS</strong></l> <a href=https://strands.readthedocs.io/en/latest/datasets/>link</a> <a href=https://ieeexplore.ieee.org/document/7948740>paper</a> <a href=https://arxiv.org/pdf/1604.04384.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An RGBD dataset of objects with corresponding 3D bounding boxes collected using a mobile robot
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D bounding box</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sun et al., "3Dof Pedestrian Trajectory Prediction Learned From Long-Term Autonomous Mobile Robot Deployment Data", ICRA, 2018.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8461228>paper</a> <a href=https://arxiv.org/pdf/1710.00126.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#strands">STRANDS</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#l-cas">L-CAS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#aede">AEDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2018_ICRA,
    author = "Sun, L. and Yan, Z. and Mellado, S. M. and Hanheide, M. and Duckett, T.",
    booktitle = "ICRA",
    title = "{3Dof} Pedestrian Trajectory Prediction Learned From Long-Term Autonomous Mobile Robot Deployment Data",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Hawes_2017_RAM,
    author = "Hawes, Nick and Burbridge, Christopher and Jovan, Ferdian and Kunze, Lars and Lacerda, Bruno and Mudrova, Lenka and Young, Jay and Wyatt, Jeremy and Hebesberger, Denise and Kortner, Tobias and others",
    title = "The Strands Project: Long-Term Autonomy In Everyday Environments",
    journal = "IEEE Robotics \\\& Automation Magazine",
    volume = "24",
    number = "3",
    pages = "146--156",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=mapillary_vistas></a>
<details close>
<summary><l style="font-size:20px"><strong>Mapillary Vistas</strong></l> <a href=https://www.mapillary.com/dataset/vistas?lat=-12.95419285181812&lng=-39.89899730092117&z=0.6853800234619407&pKey=H1P0sKnFsYu1MkfcjGUZTg>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Neuhold_The_Mapillary_Vistas_ICCV_2017_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of street-level images with the corresponding instance and semantic segmentation
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Bounding Box, Semantic Segment</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Makansi et al., "Multimodal Future Localization and Emergence Prediction for Objects in Egocentric View With a Reachability Prior", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Makansi_Multimodal_Future_Localization_and_Emergence_Prediction_for_Objects_in_Egocentric_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.04700.pdf>arxiv</a> <a href=https://github.com/lmb-freiburg/FLN-EPN-RPN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#fit">FIT</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mapillary_vistas">Mapillary Vistas</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iou">IoU</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Neuhold_2017_ICCV,
    author = "Neuhold, Gerhard and Ollmann, Tobias and Rota Bulo, Samuel and Kontschieder, Peter",
    title = "The Mapillary Vistas Dataset for Semantic Understanding of Street Scenes",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=matterport3d></a>
<details close>
<summary><l style="font-size:20px"><strong>Matterport3D</strong></l> <a href=https://niessner.github.io/Matterport/>link</a> <a href=https://ieeexplore.ieee.org/document/8374622>paper</a> <a href=https://arxiv.org/pdf/1709.06158.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of photo realistic 194K+ RGBD images of 90 indoor environments
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, Semantic Segment</li>
<li><em><strong>Task:</strong></em> Simulation</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ramakrishnan et al., "Occupancy Anticipation for Efficient Exploration and Navigation", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500392.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.09285.pdf>arxiv</a> <a href=https://github.com/facebookresearch/OccupancyAnticipation>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#matterport3d">Matterport3D</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#gibson_env">Gibson Env</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#habitat">Habitat</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#accuracy">Accuracy</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Chang_2017_3DV,
    author = "Chang, Angel and Dai, Angela and Funkhouser, Thomas and Halber, Maciej and Niessner, Matthias and Savva, Manolis and Song, Shuran and Zeng, Andy and Zhang, Yinda",
    title = "{Matterport3D}: Learning from {RGB-D} Data in Indoor Environments",
    booktitle = "3DV",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=bdd100k></a>
<details close>
<summary><l style="font-size:20px"><strong>Berkeley DeepDrive (BDD100K)</strong></l> <a href=https://bair.berkeley.edu/blog/2018/05/30/bdd/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Xu_End-To-End_Learning_of_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1612.01079.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 100K driving sequences with annotations fo 10 traffic objects annotated at 10Hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Bounding Box, Semantic Segment, Lane Marking, Drivable Areas</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Schmeckpeper et al., "Learning Predictive Models From Observation and Interaction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650698.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.12773.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#htud">HTUD</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bdd100k">BDD100K</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Schmeckpeper_2020_ECCV,
    author = "Schmeckpeper, Karl and Xie, Annie and Rybkin, Oleh and Tian, Stephen and Daniilidis, Kostas and Levine, Sergey and Finn, Chelsea",
    title = "Learning Predictive Models From Observation and Interaction",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Xu_2017_CVPR,
    author = "Xu, Huazhe and Gao, Yang and Yu, Fisher and Darrell, Trevor",
    title = "End-To-End Learning of Driving Models From Large-Scale Video Datasets",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=20bn></a>
<details close>
<summary><l style="font-size:20px"><strong>20BN</strong></l> <a href=https://20bn.com/datasets/something-something/v2>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Goyal_The_Something_Something_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1706.04261.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 220K+ videos of 174 different activities
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity Label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Rothfuss et al., "Deep Episodic Memory: Encoding, Recalling, and Predicting Episodic Experiences for Robot Action Execution", RAL, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8421022>paper</a> <a href=https://arxiv.org/pdf/1801.04134.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#activitynet">ActivityNet</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#20bn">20BN</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Rothfuss_2018_RAL,
    author = "Rothfuss, J. and Ferreira, F. and Aksoy, E. E. and Zhou, Y. and Asfour, T.",
    journal = "RAL",
    title = "Deep Episodic Memory: Encoding, Recalling, and Predicting Episodic Experiences for Robot Action Execution",
    year = "2018",
    volume = "3",
    number = "4",
    pages = "4007-4014"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Goyal_2017_ICCV,
    author = "Goyal, Raghav and Kahou, Samira Ebrahimi and Michalski, Vincent and Materzynska, Joanna and Westphal, Susanne and Kim, Heuna and Haenel, Valentin and Fruend, Ingo and Yianilos, Peter and Mueller-Freitag, Moritz and others",
    title = "The Something Something Video Database for Learning and Evaluating Visual Common Sense.",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=dfaust></a>
<details close>
<summary><l style="font-size:20px"><strong>DFAUST</strong></l> <a href=https://dfaust.is.tue.mpg.de/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Bogo_Dynamic_FAUST_Registering_CVPR_2017_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 3D poses recorded over time (3D) at 60 fps
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/motion/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> 3D Pose</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yuan et al., "3DMotion-Net: Learning Continuous Flow Function for 3D Motion Prediction", IROS, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9341671>paper</a> <a href=https://arxiv.org/pdf/2006.13906.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tosca">TOSCA</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#scape">SCAPE</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#dfaust">DFAUST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#cma">CMA</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yuan_2020_IROS,
    author = "Yuan, S. and Li, X. and Tzes, A. and Fang, Y.",
    booktitle = "IROS",
    title = "{3DMotion-Net}: Learning Continuous Flow Function for {3D} Motion Prediction",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Bogo_2017_CVPR,
    author = "Bogo, Federica and Romero, Javier and Pons-Moll, Gerard and Black, Michael J.",
    title = "Dynamic {FAUST}: Registering Human Bodies in Motion",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=davis17></a>
<details close>
<summary><l style="font-size:20px"><strong>DAVIS17</strong></l> <a href=https://davischallenge.org/davis2017/code.html>link</a> <a href=https://arxiv.org/pdf/1704.00675.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset consisting of 150 video sequences with over 10K frames and 376 objects with associated segmentation masks.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Segmentation</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hu et al., "A Dynamic Multi-Scale Voxel Flow Network for Video Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Hu_A_Dynamic_Multi-Scale_Voxel_Flow_Network_for_Video_Prediction_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.09875.pdf>arxiv</a> <a href=https://huxiaotaostasy.github.io/DMVFN/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#davis17">DAVIS17</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#vimeo-90k">Vimeo-90K</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2023_CVPR,
    author = "Hu, Xiaotao and Huang, Zhewei and Huang, Ailin and Xu, Jun and Zhou, Shuchang",
    title = "A Dynamic Multi-Scale Voxel Flow Network for Video Prediction",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@article{Pont_2017_Arxiv,
    author = "Pont-Tuset, Jordi and Perazzi, Federico and Caelles, Sergi and Arbelaez, Pablo and Sorkine-Hornung, Alex and Van Gool, Luc",
    title = "The 2017 davis challenge on video object segmentation",
    journal = "arXiv:1704.00675",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=bu_action></a>
<details close>
<summary><l style="font-size:20px"><strong>BU Action (BUA)</strong></l> <a href=http://cs-people.bu.edu/sbargal/BU-action/>link</a> <a href=https://www.sciencedirect.com/science/article/abs/pii/S0031320317300353>paper</a> <a href=https://arxiv.org/pdf/1512.07155.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of action images with 23K+ images and 101 activity classes collected from existing action video datasets
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Safaei et al., "Still Image Action Recognition By Predicting Spatial-Temporal Pixel Evolution", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8658386>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#willow_action">Willow Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wider">WIDER</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#stanford-40">Stanford-40</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bu_action">BU Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#map">mAP</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Ma_2017_PR,
    author = "Ma, Shugao and Bargal, Sarah Adel and Zhang, Jianming and Sigal, Leonid and Sclaroff, Stan",
    title = "Do Less And Achieve More: Training Cnns For Action Recognition Utilizing Action Images From The Web",
    journal = "Pattern Recognition",
    volume = "68",
    pages = "334--345",
    year = "2017"
}
</pre>
</details>

</ul></details>
</ul><h2>2016</h2>
<ul><a name=sdd></a>
<details close>
<summary><l style="font-size:20px"><strong>Stanford Drone Dataset (SDD)</strong></l> <a href=http://cvgl.stanford.edu/projects/uav_data/>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46484-8_33>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of pedestrians and cyclists movements recorded using an aerial drone with 3K+ tracks
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, object class, Tracking ID</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Bae et al., "Can Language Beat Numerical Regression? Language-Based Multimodal Trajectory Prediction", CVPR, 2024.</em> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Bae_Can_Language_Beat_Numerical_Regression_Language-Based_Multimodal_Trajectory_Prediction_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2403.18447>arxiv</a> <a href=https://github.com/InhwanBae/LMTrajectory>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bae_Can_2024_CVPR,
    author = "Bae, Inhwan and Lee, Junoh and Jeon, Hae-Gon",
    title = "Can Language Beat Numerical Regression? Language-Based Multimodal Trajectory Prediction",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wong et al., "SocialCircle: Learning the Angle-based Social Interaction Representation for Pedestrian Trajectory Prediction", CVPR, 2024.</em> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Wong_SocialCircle_Learning_the_Angle-based_Social_Interaction_Representation_for_Pedestrian_Trajectory_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2310.05370>arxiv</a> <a href=https://github.com/cocoon2wong/SocialCircle>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wong_SocialCircle_2024_CVPR,
    author = "Wong, Conghao and Xia, Beihao and Zou, Ziqian and Wang, Yulong and You, Xinge",
    title = "SocialCircle: Learning the Angle-based Social Interaction Representation for Pedestrian Trajectory Prediction",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Kim et al., "Higher-order Relational Reasoning for Pedestrian Trajectory Prediction", CVPR, 2024.</em> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Kim_Higher-order_Relational_Reasoning_for_Pedestrian_Trajectory_Prediction_CVPR_2024_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kim_Higher_2024_CVPR,
    author = "Kim, Sungjune and Chi, Hyung-gun and Lim, Hyerin and Ramani, Karthik and Kim, Jinkyu and Kim, Sangpil",
    title = "Higher-order Relational Reasoning for Pedestrian Trajectory Prediction",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Lin et al., "Progressive pretext task learning for human trajectory prediction", ECCV, 2024.</em> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04345.pdf>paper</a> <a href=https://arxiv.org/pdf/2407.11588>arxiv</a> <a href=https://github.com/iSEE-Laboratory/PPT>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Lin_Progressive_2024_ECCV,
    author = "Lin, Xiaotong and Liang, Tianming and Lai, Jianhuang and Hu, Jian-Fang",
    title = "Progressive pretext task learning for human trajectory prediction",
    booktitle = "ECCV",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Lee et al., "MART: MultiscAle Relational Transformer Networks for Multi-agent Trajectory Prediction", ECCV, 2024.</em> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/08288.pdf>paper</a> <a href=https://arxiv.org/pdf/2407.21635>arxiv</a> <a href=https://github.com/gist-ailab/MART>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Lee_Mart_2024_ECCV,
    author = "Lee, Seongju and Lee, Junseok and Yu, Yeonguk and Kim, Taeri and Lee, Kyoobin",
    title = "MART: MultiscAle Relational Transformer Networks for Multi-agent Trajectory Prediction",
    booktitle = "ECCV",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>chib et al., "Pedestrian Trajectory Prediction with Missing Data: Datasets, Imputation, and Benchmarking", NeurIPS, 2024.</em> <a href=https://openreview.net/pdf?id=XukWe15QCi>paper</a> <a href=https://arxiv.org/pdf/2411.00174>arxiv</a> <a href=https://github.com/Pranav-chib/TrajImpute>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rmse">RMSE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mrr">MRR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Chib_Pedestrian_2024_NeurIPS,
    author = "singh chib, Pranav and Singh, Pravendra",
    title = "Pedestrian Trajectory Prediction with Missing Data: Datasets, Imputation, and Benchmarking",
    booktitle = "NeurIPS",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Lin et al., "DyHGDAT: Dynamic Hypergraph Dual Attention Network for multi-agent trajectory prediction", ICRA, 2024.</em> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10609870>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Lin_DyHGDAT_2024_ICRA,
    author = "Lin, Weilong and Zeng, Xinhua and Pang, Chengxin and Teng, Jing and Liu, Jing",
    booktitle = "ICRA",
    title = "DyHGDAT: Dynamic Hypergraph Dual Attention Network for multi-agent trajectory prediction",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chen et al., "Goal-Guided and Interaction-Aware State Refinement Graph Attention Network for Multi-Agent Trajectory Prediction", RAL, 2024.</em> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10313963>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Chen_Goal_2024_RAL,
    author = "Chen, Xiaobo and Luo, Fengbo and Zhao, Feng and Ye, Qiaolin",
    journal = "RAL",
    title = "Goal-Guided and Interaction-Aware State Refinement Graph Attention Network for Multi-Agent Trajectory Prediction",
    year = "2024",
    volume = "9",
    number = "1",
    pages = "57-64",
    keywords = "Trajectory;Predictive models;Feature extraction;Transformers;Generative adversarial networks;Behavioral sciences;Task analysis;Graph attention;multi-agent trajectory prediction;multimodal prediction;state refinement",
    doi = "10.1109/LRA.2023.3331651"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Mao et al., "Leapfrog Diffusion Model for Stochastic Trajectory Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Mao_Leapfrog_Diffusion_Model_for_Stochastic_Trajectory_Prediction_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.10895.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/LED>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nfl">NFL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mao_2023_CVPR,
    author = "Mao, Weibo and Xu, Chenxin and Zhu, Qi and Chen, Siheng and Wang, Yanfeng",
    title = "Leapfrog Diffusion Model for Stochastic Trajectory Prediction",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Bae et al., "EigenTrajectory: Low-Rank Descriptors for Multi-Modal Trajectory Forecasting", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Bae_EigenTrajectory_Low-Rank_Descriptors_for_Multi-Modal_Trajectory_Forecasting_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2307.09306.pdf>arxiv</a> <a href=https://github.com/inhwanbae/EigenTrajectory>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#tcr">TCR</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#tcc">TCC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bae_2023_ICCV,
    author = "Bae, Inhwan and Oh, Jean and Jeon, Hae-Gon",
    title = "EigenTrajectory: Low-Rank Descriptors for Multi-Modal Trajectory Forecasting",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Dong et al., "Sparse Instance Conditioned Multimodal Trajectory Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Dong_Sparse_Instance_Conditioned_Multimodal_Trajectory_Prediction_ICCV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Dong_2023_ICCV,
    author = "Dong, Yonghao and Wang, Le and Zhou, Sanping and Hua, Gang",
    title = "Sparse Instance Conditioned Multimodal Trajectory Prediction",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Maeda et al., "Fast Inference and Update of Probabilistic Density Estimation on Trajectory Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Maeda_Fast_Inference_and_Update_of_Probabilistic_Density_Estimation_on_Trajectory_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.08824.pdf>arxiv</a> <a href=https://github.com/meaten/FlowChain-ICCV2023>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Shi et al., "Trajectory Unified Transformer for Pedestrian Trajectory Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Shi_Trajectory_Unified_Transformer_for_Pedestrian_Trajectory_Prediction_ICCV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minade">b-minADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shi_2023_ICCV,
    author = "Shi, Liushuai and Wang, Le and Zhou, Sanping and Hua, Gang",
    title = "Trajectory Unified Transformer for Pedestrian Trajectory Prediction",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Weng et al., "Joint Metrics Matter: A Better Standard for Trajectory Forecasting", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Weng_Joint_Metrics_Matter_A_Better_Standard_for_Trajectory_Forecasting_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2305.06292.pdf>arxiv</a> <a href=https://github.com/ericaweng/joint-metrics-matter>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minjointfde">minJointFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minjointade">minJointADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#cd">CD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Weng_2023_ICCV,
    author = "Weng, Erica and Hoshino, Hana and Ramanan, Deva and Kitani, Kris",
    title = "Joint Metrics Matter: A Better Standard for Trajectory Forecasting",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhang et al., "TrajPAC: Towards Robustness Verification of Pedestrian Trajectory Prediction Models", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_TrajPAC_Towards_Robustness_Verification_of_Pedestrian_Trajectory_Prediction_Models_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.05985.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2023_ICCV,
    author = "Zhang, Liang and Xu, Nathaniel and Yang, Pengfei and Jin, Gaojie and Huang, Cheng-Chao and Zhang, Lijun",
    title = "TrajPAC: Towards Robustness Verification of Pedestrian Trajectory Prediction Models",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Huang et al., "HyperTraj: Towards Simple and Fast Scene-Compliant Endpoint Conditioned Trajectory Prediction", IROS, 2023.</em> <a href=https://ieeexplore.ieee.org/document/10341647>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#virat">VIRAT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#time">Time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@INPROCEEDINGS{Huang_2023_IROS,
    author = "Huang, Renhao and Pagnucco, Maurice and Song, Yang",
    booktitle = "IROS",
    title = "HyperTraj: Towards Simple and Fast Scene-Compliant Endpoint Conditioned Trajectory Prediction",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Bae et al., "Non-Probability Sampling Network for Stochastic Human Trajectory Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Bae_Non-Probability_Sampling_Network_for_Stochastic_Human_Trajectory_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.13471.pdf>arxiv</a> <a href=https://github.com/inhwanbae/NPSN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#tcc">TCC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bae_2022_CVPR,
    author = "Bae, Inhwan and Park, Jin-Hwi and Jeon, Hae-Gon",
    title = "Non-Probability Sampling Network for Stochastic Human Trajectory Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Gu et al., "Stochastic Trajectory Prediction via Motion Indeterminacy Diffusion", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Gu_Stochastic_Trajectory_Prediction_via_Motion_Indeterminacy_Diffusion_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.13777.pdf>arxiv</a> <a href=https://github.com/gutianpei/MID>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gu_2022_CVPR,
    author = "Gu, Tianpei and Chen, Guangyi and Li, Junlong and Lin, Chunze and Rao, Yongming and Zhou, Jie and Lu, Jiwen",
    title = "Stochastic Trajectory Prediction via Motion Indeterminacy Diffusion",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Guo et al., "End-to-End Trajectory Distribution Prediction Based on Occupancy Grid Maps", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_End-to-End_Trajectory_Distribution_Prediction_Based_on_Occupancy_Grid_Maps_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.16910.pdf>arxiv</a> <a href=https://github.com/Kguo-cs/TDOR>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#ind">inD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#orr">ORR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Guo_2022_CVPR,
    author = "Guo, Ke and Liu, Wenxi and Pan, Jia",
    title = "End-to-End Trajectory Distribution Prediction Based on Occupancy Grid Maps",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Monti et al., "How Many Observations Are Enough? Knowledge Distillation for Trajectory Forecasting", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Monti_How_Many_Observations_Are_Enough_Knowledge_Distillation_for_Trajectory_Forecasting_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.04781.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Xu et al., "Remember Intentions: Retrospective-Memory-Based Trajectory Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_Remember_Intentions_Retrospective-Memory-Based_Trajectory_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.11474.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/MemoNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2022_CVPR,
    author = "Xu, Chenxin and Mao, Weibo and Zhang, Wenjun and Chen, Siheng",
    title = "Remember Intentions: Retrospective-Memory-Based Trajectory Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sun et al., "Human Trajectory Prediction With Momentary Observation", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Sun_Human_Trajectory_Prediction_With_Momentary_Observation_CVPR_2022_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2022_CVPR_2,
    author = "Sun, Jianhua and Li, Yuxuan and Chai, Liang and Fang, Hao-Shu and Li, Yong-Lu and Lu, Cewu",
    title = "Human Trajectory Prediction With Momentary Observation",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Bae et al., "Learning Pedestrian Group Representations for Multi-modal Trajectory Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820263.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.09953.pdf>arxiv</a> <a href=https://github.com/inhwanbae/GPGraph>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#tcr">TCR</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#tcc">TCC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bae_2022_ECCV,
    author = "Bae, Inhwan and Park, Jin-Hwi and Jeon, Hae-Gon",
    title = "Learning Pedestrian Group Representations for Multi-modal Trajectory Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Tsao et al., "Social-SSL: Self-Supervised Cross-Sequence Representation Learning Based on Transformers for Multi-agent Trajectory Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820227.pdf>paper</a> <a href=https://github.com/Sigta678/Social-SSL>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Wong et al., "View Vertically: A Hierarchical Network for Trajectory Prediction via Fourier Spectrums", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820661.pdf>paper</a> <a href=https://arxiv.org/pdf/2110.07288.pdf>arxiv</a> <a href=https://github.com/cocoon2wong/Vertical>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wong_2022_ECCV,
    author = "Wong, Conghao and Xia, Beihao and Hong, Ziming and Peng, Qinmu and Yuan, Wei and Cao, Qiong and Yang, Yibo and You, Xinge",
    title = "View Vertically: A Hierarchical Network for Trajectory Prediction via Fourier Spectrums",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "SocialVAE: Human Trajectory Prediction Using Timewise Latents", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136640504.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.08207.pdf>arxiv</a> <a href=https://motion-lab.github.io/SocialVAE/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2022_ECCV,
    author = "Xu, Pei and Hayet, Jean-Bernard and Karamouzas, Ioannis",
    title = "{SocialVAE}: Human Trajectory Prediction Using Timewise Latents",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yue et al., "Human Trajectory Prediction via Neural Social Physics", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940368.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.10435.pdf>arxiv</a> <a href=https://github.com/realcrane/Human-Trajectory-Prediction-via-Neural-Social-Physics>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yue_2022_ECCV,
    author = "Yue, Jiangbei and Manocha, Dinesh and Wang, He",
    title = "Human Trajectory Prediction via Neural Social Physics",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhang et al., "D2-TPred: Discontinuous Dependency for Trajectory Prediction under Traffic Lights", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136680512.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.10398.pdf>arxiv</a> <a href=https://github.com/VTP-TL/D2-TPred>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#vtp-tl">VTP-TL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2022_ECCV,
    author = "Zhang, Yuzhen and Wang, Wentong and Guo, Weizhi and Lv, Pei and Xu, Mingliang and Chen, Wei and Manocha, Dinesh",
    title = "{D2-TPred}: Discontinuous Dependency for Trajectory Prediction under Traffic Lights",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Kothari et al., "Motion Style Transfer: Modular Low-Rank Adaptation for Deep Motion Forecasting", CoRL, 2022.</em> <a href=https://openreview.net/pdf?id=tVgD4METs6o>paper</a> <a href=https://arxiv.org/pdf/2211.03165.pdf>arxiv</a> <a href=https://github.com/vita-epfl/motion-style-transfer>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#ind">inD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kothari_2022_CoRL,
    author = "Kothari, Parth and Li, Danya and Liu, Yuejiang and Alahi, Alexandre",
    title = "Motion Style Transfer: Modular Low-Rank Adaptation for Deep Motion Forecasting",
    booktitle = "CoRL",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Meng et al., "Forecasting Human Trajectory from Scene History", NeurIPS, 2022.</em> <a href=https://openreview.net/pdf?id=RW-OOBU11xl>paper</a> <a href=https://arxiv.org/pdf/2210.08732.pdf>arxiv</a> <a href=https://github.com/MaKaRuiNah/SHENet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mot">MOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Meng_2022_NeurIPS,
    author = "Meng, Mancheng and Wu, Ziyan and Chen, Terrence and Cai, Xiran and Zhou, Xiang Sean and Yang, Fan and Shen, Dinggang",
    title = "Forecasting Human Trajectory from Scene History",
    booktitle = "NeurIPS",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xie et al., "Synchronous Bi-Directional Pedestrian Trajectory Prediction with Error Compensation", ACCV, 2022.</em> <a href=https://openaccess.thecvf.com/content/ACCV2022/papers/Xie_Synchronous_Bi-Directional_Pedestrian_Trajectory_Prediction_with_Error_Compensation_ACCV_2022_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xie_2022_ACCV,
    author = "Xie, Ce and Li, Yuanman and Liang, Rongqin and Dong, Li and Li, Xia",
    title = "Synchronous Bi-Directional Pedestrian Trajectory Prediction with Error Compensation",
    booktitle = "ACCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sun et al., "Unified and Fast Human Trajectory Prediction Via Conditionally Parameterized Normalizing Flow", RAL, 2022.</em> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9645303>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Sun_Unified_2022_RAL,
    author = "Sun, Jianhua and Wang, Zehao and Li, Jiefeng and Lu, Cewu",
    journal = "RAL",
    title = "Unified and Fast Human Trajectory Prediction Via Conditionally Parameterized Normalizing Flow",
    year = "2022",
    volume = "7",
    number = "2",
    pages = "842-849"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhao et al., "Where Are You Heading? Dynamic Trajectory Prediction With Expert Goal Examples", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Zhao_Where_Are_You_Heading_Dynamic_Trajectory_Prediction_With_Expert_Goal_ICCV_2021_paper.pdf>paper</a> <a href=https://github.com/JoeHEZHAO/expert_traj>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhao_2021_ICCV,
    author = "Zhao, He and Wildes, Richard P.",
    title = "Where Are You Heading? Dynamic Trajectory Prediction With Expert Goal Examples",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yu et al., "Towards Robust Human Trajectory Prediction in Raw Videos", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636831>paper</a> <a href=https://arxiv.org/pdf/2108.08259.pdf>arxiv</a> <a href=https://github.com/rui-yu-public/Retracking-by-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mota">MOTA</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yu_2021_IROS_2,
    author = "Yu, Rui and Zhou, Zihan",
    booktitle = "IROS",
    title = "Towards Robust Human Trajectory Prediction in Raw Videos",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liang et al., "SimAug: Learning Robust Representations from Simulation for Trajectory Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580273.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.02022.pdf>arxiv</a> <a href=https://github.com/JunweiLiang/Multiverse/tree/master/SimAug>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#virat/actev">VIRAT/ActEV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liang_2020_ECCV,
    author = "Liang, Junwei and Jiang, Lu and Hauptmann, Alexander",
    title = "{SimAug}: Learning Robust Representations from Simulation for Trajectory Prediction",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Tao et al., "Dynamic and Static Context-aware LSTM for Multi-agent Motion Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660545.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.00777.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#tcc">TCC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tao_2020_ECCV,
    author = "Tao, Chaofan and Jiang, Qinhong and Duan, Lixin and Luo, Ping",
    title = "Dynamic and Static Context-aware {LSTM} for Multi-agent Motion Prediction",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Li et al., "EvolveGraph: Multi-Agent Trajectory Prediction with Dynamic Relational Reasoning", NeurIPS, 2020.</em> <a href=https://papers.nips.cc/paper/2020/file/e4d8163c7a068b65a64c89bd745ec360-Paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.13924.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#h3d">H3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2020_NeurIPS,
    author = "Li, Jiachen and Yang, Fan and Tomizuka, Masayoshi and Choi, Chiho",
    booktitle = "NeurIPS",
    title = "{EvolveGraph}: Multi-Agent Trajectory Prediction with Dynamic Relational Reasoning",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Dendorfer et al., "Goal-GAN: Multimodal Trajectory Prediction Based on Goal Position Estimation", ACCV, 2020.</em> <a href=https://openaccess.thecvf.com/content/ACCV2020/papers/Dendorfer_Goal-GAN_Multimodal_Trajectory_Prediction_Based_on_Goal_Position_Estimation_ACCV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2010.01114.pdf>arxiv</a> <a href=https://github.com/dendorferpatrick/GoalGAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mc">MC</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#f">F</a></li>
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
<details close>
<summary><em>Dwivedi et al., "SSP: Single Shot Future Trajectory Prediction", IROS, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9340754>paper</a> <a href=https://arxiv.org/pdf/2004.05846.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Berlati et al., "Ambiguity in Sequential Data: Predicting Uncertain Futures With Recurrent Models", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9001185>paper</a> <a href=https://arxiv.org/pdf/2003.10381.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Ridel et al., "Scene Compliant Trajectory Forecast With Agent-Centric Spatio-Temporal Grids", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9000540>paper</a> <a href=https://arxiv.org/pdf/1909.03895.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Choi et al., "DROGON: A Trajectory Prediction Model Based on Intention-conditioned Behavior Reasoning", CoRL, 2020.</em> <a href=https://proceedings.mlr.press/v155/choi21a/choi21a.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.00024.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#maxd">MaxD</a></li>
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
<summary><em>Zhao et al., "TNT: Target-driven Trajectory Prediction", CoRL, 2020.</em> <a href=https://proceedings.mlr.press/v155/zhao21b/zhao21b.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.08294.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhao_2020_CORL,
    author = "Zhao, Hang and Gao, Jiyang and Lan, Tian and Sun, Chen and Sapp, Benjamin and Varadarajan, Balakrishnan and Shen, Yue and Shen, Yi and Chai, Yuning and Schmid, Cordelia and others",
    title = "{TNT}: Target-driven Trajectory Prediction",
    booktitle = "CoRL",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Makansi et al., "Overcoming Limitations of Mixture Density Networks: A Sampling and Fitting Framework for Multimodal Future Prediction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Makansi_Overcoming_Limitations_of_Mixture_Density_Networks_A_Sampling_and_Fitting_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.03631.pdf>arxiv</a> <a href=https://github.com/lmb-freiburg/Multimodal-Future-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cpi">CPI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#emd">EMD</a></li>
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
<summary><em>Zhao et al., "Multi-Agent Tensor Fusion For Contextual Trajectory Prediction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhao_Multi-Agent_Tensor_Fusion_for_Contextual_Trajectory_Prediction_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.04776.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhao_2019_CVPR,
    author = "Zhao, Tianyang and Xu, Yifei and Monfort, Mathew and Choi, Wongun and Baker, Chris and Zhao, Yibiao and Wang, Yizhou and Wu, Ying Nian",
    title = "Multi-Agent Tensor Fusion For Contextual Trajectory Prediction",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Choi et al., "Looking To Relations For Future Trajectory Forecast", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Choi_Looking_to_Relations_for_Future_Trajectory_Forecast_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.08855.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Li et al., "Conditional Generative Neural System For Probabilistic Trajectory Prediction", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8967822>paper</a> <a href=https://arxiv.org/pdf/1905.01631.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2019_IROS,
    author = "Li, Jiachen and Ma, Hengbo and Tomizuka, Masayoshi",
    booktitle = "IROS",
    title = "Conditional Generative Neural System For Probabilistic Trajectory Prediction",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xue et al., "Location-Velocity Attention For Pedestrian Trajectory Prediction", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8659060>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pets2009">PETS2009</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Bhattacharyya et al., "Accurate and Diverse Sampling of Sequences based on a “best of many” Sample Objective", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Bhattacharyya_Accurate_and_Diverse_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1806.07772.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#cll">CLL</a></li>
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
<summary><em>Sadeghian et al., "CAR-Net: Clairvoyant Attentive Recurrent Network", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Amir_Sadeghian_CAR-Net_Clairvoyant_Attentive_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1711.10061.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Lee et al., "DESIRE: Distant Future Prediction In Dynamic Scenes With Interacting Agents", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lee_DESIRE_Distant_Future_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1704.04394.pdf>arxiv</a> <a href=https://github.com/yadrimz/DESIRE>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ed">ED</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#maxd">maxD</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mined">minED</a></li>
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
<summary><em>Ballan et al., "Knowledge Transfer For Scene-Specific Motion Prediction", ECCV, 2016.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46448-0_42>paper</a> <a href=https://arxiv.org/pdf/1603.06987.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ballan_2016_ECCV,
    author = "Ballan, Lamberto and Castaldo, Francesco and Alahi, Alexandre and Palmieri, Francesco and Savarese, Silvio",
    editor = "Leibe, Bastian and Matas, Jiri and Sebe, Nicu and Welling, Max",
    title = "Knowledge Transfer For Scene-Specific Motion Prediction",
    booktitle = "ECCV",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Robicquet_2016_ECCV,
    author = "Robicquet, Alexandre and Sadeghian, Amir and Alahi, Alexandre and Savarese, Silvio",
    title = "Learning Social Etiquette: Human Trajectory Understanding in Crowded Scenes",
    booktitle = "ECCV",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=cmu_mocap></a>
<details close>
<summary><l style="font-size:20px"><strong>CMU Mocap</strong></l> <a href=http://mocap.cs.cmu.edu/>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A motion dataset consists of various activities including human interaction, interaction with the environment, locomotion, sports, etc.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a>, <a href=../../papers/motion/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Butepage et al., "Deep Representation Learning For Human Motion Prediction And Classification", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Butepage_Deep_Representation_Learning_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1702.07486.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Butepage_2017_CVPR,
    author = "Butepage, Judith and Black, Michael J. and Kragic, Danica and Kjellstrom, Hedvig",
    title = "Deep Representation Learning For Human Motion Prediction And Classification",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Dax et al., "Disentangled Neural Relational Inference for Interpretable Motion Prediction", RAL, 2024.</em> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10356778>paper</a> <a href=https://arxiv.org/pdf/2401.03599>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#ind">inD</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Dax_Disentangled_2024_RAL,
    author = "Dax, Victoria M. and Li, Jiachen and Sachdeva, Enna and Agarwal, Nakul and Kochenderfer, Mykel J.",
    journal = "RAL",
    title = "Disentangled Neural Relational Inference for Interpretable Motion Prediction",
    year = "2024",
    volume = "9",
    number = "2",
    pages = "1452-1459",
    keywords = "Predictive models;Trajectory;Vehicle dynamics;Decoding;Data models;Computational modeling;Training;AI-Based Methods;Behavior-Based Systems;Probabilistic Inference",
    doi = "10.1109/LRA.2023.3342554"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sun et al., "MoML: Online Meta Adaptation for 3D Human Motion Prediction", CVPR, 2024.</em> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Sun_MoML_Online_Meta_Adaptation_for_3D_Human_Motion_Prediction_CVPR_2024_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_MoML_2024_CVPR,
    author = "Sun, Xiaoning and Sun, Huaijiang and Li, Bin and Wei, Dong and Li, Weiqing and Lu, Jianfeng",
    title = "MoML: Online Meta Adaptation for 3D Human Motion Prediction",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yu et al., "Pose-Transformed Equivariant Network for 3D Point Trajectory Prediction", CVPR, 2024.</em> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Yu_Pose-Transformed_Equivariant_Network_for_3D_Point_Trajectory_Prediction_CVPR_2024_paper.pdf>paper</a> <a href=https://github.com/yuruixuan/PTEvNet.>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#md17">MD17</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yu_Pose_2024_CVPR,
    author = "Yu, Ruixuan and Sun, Jian",
    title = "Pose-Transformed Equivariant Network for 3D Point Trajectory Prediction",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chen et al., "Rethinking Human Motion Prediction with Symplectic Integral", CVPR, 2024.</em> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_Rethinking_Human_Motion_Prediction_with_Symplectic_Integral_CVPR_2024_paper.pdf>paper</a> <a href=https://github.com/adamlyu789/SINN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_Rethinking_2024_CVPR,
    author = "Chen, Haipeng and Lyu, Kedi and Liu, Zhenguang and Yin, Yifang and Yang, Xun and Lyu, Yingda",
    title = "Rethinking Human Motion Prediction with Symplectic Integral",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Jeong et al., "Multi-agent Long-term 3D Human Pose Forecasting via Interaction-aware Trajectory Conditioning", CVPR, 2024.</em> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Jeong_Multi-agent_Long-term_3D_Human_Pose_Forecasting_via_Interaction-aware_Trajectory_Conditioning_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2404.05218>arxiv</a> <a href=https://github.com/Jaewoo97/T2P>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jrdb">JRDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#jpe">JPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ape">APE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jeong_Multi_2024_CVPR,
    author = "Jeong, Jaewoo and Park, Daehee and Yoon, Kuk-Jin",
    title = "Multi-agent Long-term 3D Human Pose Forecasting via Interaction-aware Trajectory Conditioning",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wei et al., "NeRMo: Learning Implicit Neural Representations for 3D Human Motion Prediction", ECCV, 2024.</em> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06076.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Wei_Nermo_2024_ECCV,
    author = "Wei, Dong and Sun, Huaijiang and Sun, Xiaoning and Hu, Shengxiang",
    title = "NeRMo: Learning Implicit Neural Representations for 3D Human Motion Prediction",
    booktitle = "ECCV",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xiao et al., "Multi-person Pose Forecasting with Individual Interaction Perceptron and Prior Learning", ECCV, 2024.</em> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/02808.pdf>paper</a> <a href=https://github.com/ArcticPole/IAFormer>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#chi3d">CHI3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#jpe">JPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ape">APE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Xiao_Multi_2024_ECCV,
    author = "Xiao, Peng and Xie, Yi and Xu, Xuemiao and Chen, Weihong and Zhang, Huaidong",
    title = "Multi-person Pose Forecasting with Individual Interaction Perceptron and Prior Learning",
    booktitle = "ECCV",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Gao et al., "Decompose More and Aggregate Better: Two Closer Looks at Frequency Representation Learning for Human Motion Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Gao_Decompose_More_and_Aggregate_Better_Two_Closer_Looks_at_Frequency_CVPR_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2023_CVPR,
    author = "Gao, Xuehao and Du, Shaoyi and Wu, Yang and Yang, Yang",
    title = "Decompose More and Aggregate Better: Two Closer Looks at Frequency Representation Learning for Human Motion Prediction",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Peng et al., "Trajectory-Aware Body Interaction Transformer for Multi-Person Pose Forecasting", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Peng_Trajectory-Aware_Body_Interaction_Transformer_for_Multi-Person_Pose_Forecasting_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.05095.pdf>arxiv</a> <a href=https://github.com/xiaogangpeng/TBIFormer>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mupots-3d">MuPoTS-3D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#umpm">UMPM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mape">MAPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Peng_2023_CVPR,
    author = "Peng, Xiaogang and Mao, Siyuan and Wu, Zizhao",
    title = "Trajectory-Aware Body Interaction Transformer for Multi-Person Pose Forecasting",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Tanke et al., "Social Diffusion: Long-term Multiple Human Motion Anticipation", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Tanke_Social_Diffusion_Long-term_Multiple_Human_Motion_Anticipation_ICCV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mupots-3d">MuPoTS-3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tanke_2023_ICCV,
    author = "Tanke, Julian and Zhang, Linguang and Zhao, Amy and Tang, Chengcheng and Cai, Yujun and Wang, Lezi and Wu, Po-Chen and Gall, Juergen and Keskin, Cem",
    title = "Social Diffusion: Long-term Multiple Human Motion Anticipation",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Joint-Relation Transformer for Multi-Person Motion Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Xu_Joint-Relation_Transformer_for_Multi-Person_Motion_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.04808.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/JRTransformer>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mupots-3d">MuPoTS-3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#vim">VIM</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2023_ICCV,
    author = "Xu, Qingyao and Mao, Weibo and Gong, Jingze and Xu, Chenxin and Chen, Siheng and Xie, Weidi and Zhang, Ya and Wang, Yanfeng",
    title = "Joint-Relation Transformer for Multi-Person Motion Prediction",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chen et al., "HumanMAC: Masked Motion Completion for Human Motion Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_HumanMAC_Masked_Motion_Completion_for_Human_Motion_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2302.03665.pdf>arxiv</a> <a href=https://lhchen.top/Human-MAC/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmade">MMADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmfde">MMFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2023_ICCV_1,
    author = "Chen, Ling-Hao and Zhang, JiaWei and Li, Yewen and Pang, Yiren and Xia, Xiaobo and Liu, Tongliang",
    title = "HumanMAC: Masked Motion Completion for Human Motion Prediction",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Auxiliary Tasks Benefit 3D Skeleton-based Human Motion Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Xu_Auxiliary_Tasks_Benefit_3D_Skeleton-based_Human_Motion_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.08942.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/AuxFormer>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2023_ICCV_1,
    author = "Xu, Chenxin and Tan, Robby T. and Tan, Yuhong and Chen, Siheng and Wang, Xinchao and Wang, Yanfeng",
    title = "Auxiliary Tasks Benefit 3D Skeleton-based Human Motion Prediction",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ma et al., "Progressively Generating Better Initial Guesses Towards Next Stages for High-Quality Human Motion Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Ma_Progressively_Generating_Better_Initial_Guesses_Towards_Next_Stages_for_High-Quality_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.16051.pdf>arxiv</a> <a href=https://github.com/705062791/PGBIG>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ma_2022_CVPR,
    author = "Ma, Tiezheng and Nie, Yongwei and Long, Chengjiang and Zhang, Qing and Li, Guiqing",
    title = "Progressively Generating Better Initial Guesses Towards Next Stages for High-Quality Human Motion Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Li et al., "Skeleton-Parted Graph Scattering Networks for 3D Human Motion Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136660018.pdf>paper</a> <a href=https://arxiv.org/pdf/2208.00368.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/SPGSN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2022_ECCV,
    author = "Li, Maosen and Chen, Siheng and Zhang, Zijing and Xie, Lingxi and Tian, Qi and Zhang, Ya",
    title = "Skeleton-Parted Graph Scattering Networks for {3D} Human Motion Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sun et al., "Overlooked Poses Actually Make Sense: Distilling Privileged Knowledge for Human Motion Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136650668.pdf>paper</a> <a href=https://arxiv.org/pdf/2208.01302.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2022_ECCV,
    author = "Sun, Xiaoning and Cui, Qiongjie and Sun, Huaijiang and Li, Bin and Li, Weiqing and Lu, Jianfeng",
    title = "Overlooked Poses Actually Make Sense: Distilling Privileged Knowledge for Human Motion Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "Multi-Person 3D Motion Prediction with Multi-Range Transformers", NeurIPS, 2021.</em> <a href=https://papers.nips.cc/paper/2021/file/2fd5d41ec6cfab47e32164d5624269b1-Paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2111.12073.pdf>arxiv</a> <a href=https://github.com/jiashunwang/MRT>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mupots-3d">MuPoTS-3D</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2021_NeurIPS,
    author = "Wang, Jiashun and Xu, Huazhe and Narasimhan, Medhini and Wang, Xiaolong",
    booktitle = "NeurIPS",
    title = "Multi-Person {3D} Motion Prediction with Multi-Range Transformers",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Cui et al., "Towards Accurate 3D Human Motion Prediction From Incomplete Observations", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Cui_Towards_Accurate_3D_Human_Motion_Prediction_From_Incomplete_Observations_CVPR_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cui_2021_CVPR,
    author = "Cui, Qiongjie and Sun, Huaijiang",
    title = "Towards Accurate {3D} Human Motion Prediction From Incomplete Observations",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Aliakbarian et al., "Contextually Plausible and Diverse 3D Human Motion Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Aliakbarian_Contextually_Plausible_and_Diverse_3D_Human_Motion_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.08521.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#kld">KLD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Aliakbarian_2021_ICCV,
    author = "Aliakbarian, Sadegh and Saleh, Fatemeh and Petersson, Lars and Gould, Stephen and Salzmann, Mathieu",
    title = "Contextually Plausible and Diverse {3D} Human Motion Prediction",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Dang et al., "MSR-GCN: Multi-Scale Residual Graph Convolution Networks for Human Motion Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Dang_MSR-GCN_Multi-Scale_Residual_Graph_Convolution_Networks_for_Human_Motion_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://github.com/Droliven/MSRGCN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Dang_2021_ICCV,
    author = "Dang, Lingwei and Nie, Yongwei and Long, Chengjiang and Zhang, Qing and Li, Guiqing",
    title = "{MSR-GCN}: Multi-Scale Residual Graph Convolution Networks for Human Motion Prediction",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liu et al., "Motion Prediction Using Trajectory Cues", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Liu_Motion_Prediction_Using_Trajectory_Cues_ICCV_2021_paper.pdf>paper</a> <a href=https://github.com/Pose-Group/MPT>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mouse_fish">Mouse Fish</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2021_ICCV,
    author = "Liu, Zhenguang and Su, Pengxiang and Wu, Shuang and Shen, Xuanjing and Chen, Haipeng and Hao, Yanbin and Wang, Meng",
    title = "Motion Prediction Using Trajectory Cues",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Li et al., "Directed Acyclic Graph Neural Network for Human Motion Prediction", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561540>paper</a> <a href=https://github.com/Qinli-zz/DA-GNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2021_ICRA,
    author = "Li, Qin and Chalvatzaki, Georgia and Peters, Jan and Wang, Yong",
    booktitle = "ICRA",
    title = "Directed Acyclic Graph Neural Network for Human Motion Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhang et al., "Non-local Graph Convolutional Network for Joint Activity Recognition and Motion Prediction", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636107>paper</a> <a href=https://arxiv.org/pdf/2108.01518.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2021_IROS,
    author = "Zhang, Dianhao and Vien, Ngo Anh and Van, Mien and McLoone, Seán",
    booktitle = "IROS",
    title = "Non-local Graph Convolutional Network for Joint Activity Recognition and Motion Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Aliakbarian et al., "A Stochastic Conditioning Scheme for Diverse Human Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Aliakbarian_A_Stochastic_Conditioning_Scheme_for_Diverse_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://github.com/mix-and-match/mix-and-match-tutorial>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#kld">KLD</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#si">SI</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#kl">KL</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#s-mse">S-MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Aliakbarian_2020_CVPR,
    author = "Aliakbarian, Sadegh and Saleh, Fatemeh Sadat and Salzmann, Mathieu and Petersson, Lars and Gould, Stephen",
    title = "A Stochastic Conditioning Scheme for Diverse Human Motion Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Cui et al., "Learning Dynamic Relationships for 3D Human Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Cui_Learning_Dynamic_Relationships_for_3D_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://github.com/cuiqiongjie/LDRGCN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cui_2020_CVPR,
    author = "Cui, Qiongjie and Sun, Huaijiang and Yang, Fei",
    title = "Learning Dynamic Relationships for 3D Human Motion Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Li et al., "Dynamic Multiscale Graph Neural Networks for 3D Skeleton Based Human Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Dynamic_Multiscale_Graph_Neural_Networks_for_3D_Skeleton_Based_Human_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.08802.pdf>arxiv</a> <a href=https://github.com/limaosen0/DMGNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2020_CVPR,
    author = "Li, Maosen and Chen, Siheng and Zhao, Yangheng and Zhang, Ya and Wang, Yanfeng and Tian, Qi",
    title = "Dynamic Multiscale Graph Neural Networks for {3D} Skeleton Based Human Motion Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Cai et al., "Learning Progressive Joint Propagation for Human Motion Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520222.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cai_2020_ECCV,
    author = "Cai, Yujun and Huang, Lin and Wang, Yiwei and Cham, Tat-Jen and Cai, Jianfei and Yuan, Junsong and Liu, Jun and Yang, Xu and Zhu, Yiheng and Shen, Xiaohui and Liu, Ding and Liu, Jing and Thalmann, Nadia M",
    title = "Learning Progressive Joint Propagation for Human Motion Prediction",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chao et al., "Adversarial Refinement Network for Human Motion Prediction", ACCV, 2020.</em> <a href=https://openaccess.thecvf.com/content/ACCV2020/papers/Chao_Adversarial_Refinement_Network_for_Human_Motion_Prediction_ACCV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2011.11221.pdf>arxiv</a> <a href=https://github.com/Xianjin111/ARNet-for-human-motion-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chao_2020_ACCV,
    author = "Chao, Xianjin and Bin, Yanrui and Chu, Wenqing and Cao, Xuan and Ge, Yanhao and Wang, Chengjie and Li, Jilin and Huang, Feiyue and Leung, Howard",
    title = "Adversarial Refinement Network for Human Motion Prediction",
    booktitle = "ACCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Lebailly et al., "Motion Prediction Using Temporal Inception Module", ACCV, 2020.</em> <a href=https://openaccess.thecvf.com/content/ACCV2020/papers/Lebailly_Motion_Prediction_Using_Temporal_Inception_Module_ACCV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2010.03006.pdf>arxiv</a> <a href=https://github.com/tileb1/motion-prediction-tim>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lebailly_2020_ACCV,
    author = "Lebailly, Tim and Kiciroglu, Sena and Salzmann, Mathieu and Fua, Pascal and Wang, Wei",
    title = "Motion Prediction Using Temporal Inception Module",
    booktitle = "ACCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Mao et al., "Learning Trajectory Dependencies For Human Motion Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Mao_Learning_Trajectory_Dependencies_for_Human_Motion_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.05436.pdf>arxiv</a> <a href=https://github.com/wei-mao-2019/LearnTrajDep>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mao_2019_ICCV,
    author = "Mao, Wei and Liu, Miaomiao and Salzmann, Mathieu and Li, Hongdong",
    title = "Learning Trajectory Dependencies For Human Motion Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Misc{CMU_Mocap_2016,
    author = "CMU",
    title = "{CMU} Graphics Lab Motion Capture Database",
    howpublished = "http://mocap.cs.cmu.edu/",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=cityscapes></a>
<details close>
<summary><l style="font-size:20px"><strong>Cityscapes</strong></l> <a href=https://www.cityscapes-dataset.com/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Cordts_The_Cityscapes_Dataset_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1604.01685.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A driving dataset of street images with annotations for 30 traffic objects in 5k frames and weak annotations in 20k frames
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a>, <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, bounding box, semantic segment, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhang et al., "ExtDM: Distribution Extrapolation Diffusion Model for Video Prediction", CVPR, 2024.</em> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_ExtDM_Distribution_Extrapolation_Diffusion_Model_for_Video_Prediction_CVPR_2024_paper.pdf>paper</a> <a href=https://github.com/nku-zhichengzhang/ExtDM>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair">BAIR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_ExtDM_2024_CVPR,
    author = "Zhang, Zhicheng and Hu, Junyao and Cheng, Wentao and Paudel, Danda and Yang, Jufeng",
    title = "ExtDM: Distribution Extrapolation Diffusion Model for Video Prediction",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yarram et al., "Forecasting Future Videos from Novel Views via Disentangled 3D Scene Representation", ECCV, 2024.</em> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/09842.pdf>paper</a> <a href=https://arxiv.org/pdf/2407.21450>arxiv</a> <a href=https://skrya.github.io/projects/ffn-dsr/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Yarram_Forecasting_2024_ECCV,
    author = "Yarram, Sudhir and Yuan, Junsong",
    title = "Forecasting Future Videos from Novel Views via Disentangled 3D Scene Representation",
    booktitle = "ECCV",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Hu et al., "A Dynamic Multi-Scale Voxel Flow Network for Video Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Hu_A_Dynamic_Multi-Scale_Voxel_Flow_Network_for_Video_Prediction_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.09875.pdf>arxiv</a> <a href=https://huxiaotaostasy.github.io/DMVFN/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#davis17">DAVIS17</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#vimeo-90k">Vimeo-90K</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2023_CVPR,
    author = "Hu, Xiaotao and Huang, Zhewei and Huang, Ailin and Xu, Jun and Zhou, Shuchang",
    title = "A Dynamic Multi-Scale Voxel Flow Network for Video Prediction",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Geng et al., "Comparing Correspondences: Video Prediction With Correspondence-Wise Losses", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Geng_Comparing_Correspondences_Video_Prediction_With_Correspondence-Wise_Losses_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2104.09498.pdf>arxiv</a> <a href=https://github.com/dangeng/CorrWiseLosses>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Geng_2022_CVPR,
    author = "Geng, Daniel and Hamilton, Max and Owens, Andrew",
    title = "Comparing Correspondences: Video Prediction With Correspondence-Wise Losses",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wu et al., "Optimizing Video Prediction via Video Frame Interpolation", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Wu_Optimizing_Video_Prediction_via_Video_Frame_Interpolation_CVPR_2022_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wu_2022_CVPR,
    author = "Wu, Yue and Wen, Qiang and Chen, Qifeng",
    title = "Optimizing Video Prediction via Video Frame Interpolation",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Lee et al., "Revisiting Hierarchical Approach for Persistent Long-Term Video Prediction", ICLR, 2021.</em> <a href=https://openreview.net/pdf?id=3RLN4EPMdYd>paper</a> <a href=https://arxiv.org/pdf/2104.06697.pdf>arxiv</a> <a href=https://github.com/1Konny/HVP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#dancing">Dancing</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_a-d_metrics.md#csim">CSIM</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wonkwang_2021_ICLR,
    author = "Lee, Wonkwang and Jung, Whie and Zhang, Han and Chen, Ting and Koh, Jing Yu and Huang, Thomas and Yoon, Hyungsuk and Lee, Honglak and Hong, Seunghoon",
    booktitle = "ICLR",
    title = "Revisiting Hierarchical Approach for Persistent Long-Term Video Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Bei et al., "Learning Semantic-Aware Dynamics for Video Prediction", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Bei_Learning_Semantic-Aware_Dynamics_for_Video_Prediction_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2104.09762.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bei_2021_CVPR,
    author = "Bei, Xinzhu and Yang, Yanchao and Soatto, Stefano",
    title = "Learning Semantic-Aware Dynamics for Video Prediction",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wu et al., "Future Video Synthesis With Object Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Wu_Future_Video_Synthesis_With_Object_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.00542.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ms-ssim">MS-SSIM</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wu_2020_CVPR,
    author = "Wu, Yue and Gao, Rongrong and Park, Jaesik and Chen, Qifeng",
    title = "Future Video Synthesis With Object Motion Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Castrejon et al., "Improved Conditional VRNNs For Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Castrejon_Improved_Conditional_VRNNs_for_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.12165.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Castrejon_2019_ICCV,
    author = "Castrejon, Lluis and Ballas, Nicolas and Courville, Aaron",
    title = "Improved Conditional {VRNNs} For Video Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Structure Preserving Video Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers_backup/Xu_Structure_Preserving_Video_CVPR_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2018_CVPR,
    author = "Xu, Jingwei and Ni, Bingbing and Li, Zefan and Cheng, Shuo and Yang, Xiaokang",
    title = "Structure Preserving Video Prediction",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Marchetti et al., "MANTRA: Memory Augmented Networks for Multiple Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Marchetti_MANTRA_Memory_Augmented_Networks_for_Multiple_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.03340.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#orc">ORC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Marchetti_2020_CVPR,
    author = "Marchetti, Francesco and Becattini, Federico and Seidenari, Lorenzo and Del Bimbo, Alberto",
    title = "{MANTRA}: Memory Augmented Networks for Multiple Trajectory Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Srikanth et al., "INFER: INtermediate Representations For FuturE PRediction", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8968553>paper</a> <a href=https://arxiv.org/pdf/1903.10641.pdf>arxiv</a> <a href=https://rebrand.ly/INFER-results>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#oxford">Oxford</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Srikanth_2019_IROS,
    author = "Srikanth, Shashank and Ansari, Junaid Ahmed and Sharma, Sarthak and others",
    booktitle = "IROS",
    title = "{INFER}: {IN}termediate Representations For {F}utur{E} P{R}ediction",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Graber et al., "Joint Forecasting of Panoptic Segmentations With Difference Attention", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Graber_Joint_Forecasting_of_Panoptic_Segmentations_With_Difference_Attention_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.07157.pdf>arxiv</a> <a href=https://github.com/cgraber/psf-diffattn>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Graber_2022_CVPR,
    author = "Graber, Colin and Jazra, Cyril and Luo, Wenjie and Gui, Liangyan and Schwing, Alexander G.",
    title = "Joint Forecasting of Panoptic Segmentations With Difference Attention",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Graber et al., "Panoptic Segmentation Forecasting", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Graber_Panoptic_Segmentation_Forecasting_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2104.03962.pdf>arxiv</a> <a href=https://github.com/nianticlabs/ panoptic-forecasting>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#ap">AP</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#sq">SQ</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#pq">PQ</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#rq">RQ</a></li>
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
<summary><em>Lin et al., "Predictive Feature Learning for Future Segmentation Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Lin_Predictive_Feature_Learning_for_Future_Segmentation_Prediction_ICCV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscape">Cityscape</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3d_movie">3D Movie</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#ap">AP</a></li>
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
<details close>
<summary><em>Saric et al., "Warp to the Future: Joint Forecasting of Features and Feature Motion", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Saric_Warp_to_the_Future_Joint_Forecasting_of_Features_and_Feature_CVPR_2020_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Saric_2020_CVPR,
    author = "Saric, Josip and Orsic, Marin and Antunovic, Tonci and Vrazic, Sacha and Segvic, Sinisa",
    title = "Warp to the Future: Joint Forecasting of Features and Feature Motion",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Hu et al., "Probabilistic Future Prediction for Video Scene Understanding", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123610749.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.06409.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#ddm">DDM</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#aepe">AEPE</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#sile">SILE</a></li>
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
<details close>
<summary><em>Terwilliger et al., "Recurrent Flow-Guided Semantic Forecasting", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8658639>paper</a> <a href=https://arxiv.org/pdf/1809.08318.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Terwilliger_2019_WACV,
    author = "Terwilliger, A. and Brazil, G. and Liu, X.",
    booktitle = "WACV",
    title = "Recurrent Flow-Guided Semantic Forecasting",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Luc et al., "Predicting Future Instance Segmentation By Forecasting Convolutional Features", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Pauline_Luc_Predicting_Future_Instance_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1803.11496.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#voi">VoI</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#gce">GCE</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#ri">RI</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Luc_2018_ECCV,
    author = "Luc, Pauline and Couprie, Camille and LeCun, Yann and Verbeek, Jakob",
    title = "Predicting Future Instance Segmentation By Forecasting Convolutional Features",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Luc et al., "Predicting Deeper Into The Future Of Semantic Segmentation", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Luc_Predicting_Deeper_Into_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1703.07684.pdf>arxiv</a> <a href=https://github.com/facebookresearch/SegmPred>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Luc_2017_ICCV,
    author = "Luc, Pauline and Neverova, Natalia and Couprie, Camille and Verbeek, Jakob and LeCun, Yann",
    title = "Predicting Deeper Into The Future Of Semantic Segmentation",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Jin et al., "Predicting Scene Parsing And Motion Dynamics In The Future", NeurIPS, 2017.</em> <a href=https://papers.nips.cc/paper/7267-predicting-scene-parsing-and-motion-dynamics-in-the-future.pdf>paper</a> <a href=https://arxiv.org/pdf/1711.03270.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#epe">EPE</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#miou">MIoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jin_2017_NeurIPS,
    author = "Jin, Xiaojie and Xiao, Huaxin and Shen, Xiaohui and Yang, Jimei and Lin, Zhe and Chen, Yunpeng and Jie, Zequn and Feng, Jiashi and Yan, Shuicheng",
    title = "Predicting Scene Parsing And Motion Dynamics In The Future",
    booktitle = "NeurIPS",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Cordts_2016_CVPR,
    author = "Cordts, Marius and Omran, Mohamed and Ramos, Sebastian and Rehfeld, Timo and Enzweiler, Markus and Benenson, Rodrigo and Franke, Uwe and Roth, Stefan and Schiele, Bernt",
    title = "The Cityscapes Dataset For Semantic Urban Scene Understanding",
    booktitle = "CVPR",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=nba></a>
<details close>
<summary><l style="font-size:20px"><strong>NBA</strong></l> <a href=https://github.com/linouk23/NBA-Player-Movements>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of trajectories of NBA players from games at a given season.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Trajectory</li>
<li><em><strong>Task:</strong></em> Sport</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Wong et al., "SocialCircle: Learning the Angle-based Social Interaction Representation for Pedestrian Trajectory Prediction", CVPR, 2024.</em> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Wong_SocialCircle_Learning_the_Angle-based_Social_Interaction_Representation_for_Pedestrian_Trajectory_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2310.05370>arxiv</a> <a href=https://github.com/cocoon2wong/SocialCircle>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wong_SocialCircle_2024_CVPR,
    author = "Wong, Conghao and Xia, Beihao and Zou, Ziqian and Wang, Yulong and You, Xinge",
    title = "SocialCircle: Learning the Angle-based Social Interaction Representation for Pedestrian Trajectory Prediction",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Lee et al., "MART: MultiscAle Relational Transformer Networks for Multi-agent Trajectory Prediction", ECCV, 2024.</em> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/08288.pdf>paper</a> <a href=https://arxiv.org/pdf/2407.21635>arxiv</a> <a href=https://github.com/gist-ailab/MART>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Lee_Mart_2024_ECCV,
    author = "Lee, Seongju and Lee, Junseok and Yu, Yeonguk and Kim, Taeri and Lee, Kyoobin",
    title = "MART: MultiscAle Relational Transformer Networks for Multi-agent Trajectory Prediction",
    booktitle = "ECCV",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>chib et al., "Enhancing Trajectory Prediction through Self-Supervised Waypoint Distortion Prediction", ICML, 2024.</em> <a href=https://openreview.net/pdf?id=OQ7TlOphGX>paper</a> <a href=https://arxiv.org/pdf/2312.09466>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rt">RT</a></li>
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
<summary><em>Dax et al., "Disentangled Neural Relational Inference for Interpretable Motion Prediction", RAL, 2024.</em> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10356778>paper</a> <a href=https://arxiv.org/pdf/2401.03599>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#ind">inD</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Dax_Disentangled_2024_RAL,
    author = "Dax, Victoria M. and Li, Jiachen and Sachdeva, Enna and Agarwal, Nakul and Kochenderfer, Mykel J.",
    journal = "RAL",
    title = "Disentangled Neural Relational Inference for Interpretable Motion Prediction",
    year = "2024",
    volume = "9",
    number = "2",
    pages = "1452-1459",
    keywords = "Predictive models;Trajectory;Vehicle dynamics;Decoding;Data models;Computational modeling;Training;AI-Based Methods;Behavior-Based Systems;Probabilistic Inference",
    doi = "10.1109/LRA.2023.3342554"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Mao et al., "Leapfrog Diffusion Model for Stochastic Trajectory Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Mao_Leapfrog_Diffusion_Model_for_Stochastic_Trajectory_Prediction_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.10895.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/LED>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nfl">NFL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mao_2023_CVPR,
    author = "Mao, Weibo and Xu, Chenxin and Zhu, Qi and Chen, Siheng and Wang, Yanfeng",
    title = "Leapfrog Diffusion Model for Stochastic Trajectory Prediction",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "EqMotion: Equivariant Multi-Agent Motion Prediction With Invariant Interaction Reasoning", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Xu_Uncovering_the_Missing_Pattern_Unified_Framework_Towards_Trajectory_Imputation_and_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.16005.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nfl">NFL</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#omni-mot">Omni-MOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2023_CVPR_1,
    author = "Xu, Chenxin and Tan, Robby T. and Tan, Yuhong and Chen, Siheng and Wang, Yu Guang and Wang, Xinchao and Wang, Yanfeng",
    title = "EqMotion: Equivariant Multi-Agent Motion Prediction With Invariant Interaction Reasoning",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sun et al., "Stimulus Verification Is a Universal and Effective Sampler in Multi-Modal Human Trajectory Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Sun_Stimulus_Verification_Is_a_Universal_and_Effective_Sampler_in_Multi-Modal_CVPR_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2023_CVPR_2,
    author = "Sun, Jianhua and Li, Yuxuan and Chai, Liang and Lu, Cewu",
    title = "Stimulus Verification Is a Universal and Effective Sampler in Multi-Modal Human Trajectory Prediction",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Remember Intentions: Retrospective-Memory-Based Trajectory Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_Remember_Intentions_Retrospective-Memory-Based_Trajectory_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.11474.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/MemoNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2022_CVPR,
    author = "Xu, Chenxin and Mao, Weibo and Zhang, Wenjun and Chen, Siheng",
    title = "Remember Intentions: Retrospective-Memory-Based Trajectory Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "GroupNet: Multiscale Hypergraph Neural Networks for Trajectory Prediction With Relational Reasoning", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_GroupNet_Multiscale_Hypergraph_Neural_Networks_for_Trajectory_Prediction_With_Relational_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.08770.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/GroupNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2022_CVPR_2,
    author = "Xu, Chenxin and Li, Maosen and Ni, Zhenyang and Zhang, Ya and Chen, Siheng",
    title = "{GroupNet}: Multiscale Hypergraph Neural Networks for Trajectory Prediction With Relational Reasoning",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Hu et al., "Entry-Flipped Transformer for Inference and Prediction of Participant Behavior", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136640433.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.06235.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#ceilidh_dance">Ceilidh Dance</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Xu et al., "SocialVAE: Human Trajectory Prediction Using Timewise Latents", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136640504.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.08207.pdf>arxiv</a> <a href=https://motion-lab.github.io/SocialVAE/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2022_ECCV,
    author = "Xu, Pei and Hayet, Jean-Bernard and Karamouzas, Ioannis",
    title = "{SocialVAE}: Human Trajectory Prediction Using Timewise Latents",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Fassmeyer et al., "Semi-Supervised Generative Models for Multiagent Trajectories", NeurIPS, 2022.</em> <a href=https://openreview.net/pdf?id=KpuObEWvvOX>paper</a> <a href=https://github.com/fassmeyer/MAT_NeurIPS22>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Fassmeyer_2022_NeurIPS,
    author = "Fassmeyer, Dennis and Fassmeyer, Pascal and Brefeld, Ulf",
    title = "Semi-Supervised Generative Models for Multiagent Trajectories",
    booktitle = "NeurIPS",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Makansi et al., "You Mostly Walk Alone: Analyzing Feature Attribution in Trajectory Prediction", ICLR, 2022.</em> <a href=https://openreview.net/pdf?id=POxF-LEqnF>paper</a> <a href=https://arxiv.org/pdf/2110.05304.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Makansi_2022_ICLR,
    author = "Makansi, Osama and Kugelgen, Julius Von and Locatello, Francesco and Gehler, Peter Vincent and Janzing, Dominik and Brox, Thomas and Scholkopf, Bernhard",
    title = "You Mostly Walk Alone: Analyzing Feature Attribution in Trajectory Prediction",
    booktitle = "ICLR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Navarro et al., "Social-PatteRNN: Socially-Aware Trajectory Prediction Guided by Motion Patterns", IROS, 2022.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9981486>paper</a> <a href=https://arxiv.org/pdf/2209.05649.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#trajair">TrajAir</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Li et al., "GRIN: Generative Relation and Intention Network for Multi-agent Trajectory Prediction", NeurIPS, 2021.</em> <a href=https://papers.nips.cc/paper/2021/file/e3670ce0c315396e4836d7024abcf3dd-Paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#charges">Charges</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mmd">MMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2021_NeurIPS,
    author = "Li, Longyuan and Yao, Jian and Wenliang, Li and He, Tong and Xiao, Tianjun and Yan, Junchi and Wipf, David and Zhang, Zheng",
    booktitle = "NeurIPS",
    title = "{GRIN}: Generative Relation and Intention Network for Multi-agent Trajectory Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Kamra et al., "Multi-agent Trajectory Prediction with Fuzzy Query Attention", NeurIPS, 2020.</em> <a href=https://papers.nips.cc/paper/2020/file/fe87435d12ef7642af67d9bc82a8b3cd-Paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2010.15891.pdf>arxiv</a> <a href=https://github.com/nitinkamra1992/FQA>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#charges">Charges</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kamra_2020_NeurIPS,
    author = "Kamra, Nitin and Zhu, Hao and Trivedi, Dweep Kumarbhai and Zhang, Ming and Liu, Yan",
    editor = "Larochelle, H. and Ranzato, M. and Hadsell, R. and Balcan, M. F. and Lin, H.",
    booktitle = "NeurIPS",
    title = "Multi-agent Trajectory Prediction with Fuzzy Query Attention",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Li et al., "EvolveGraph: Multi-Agent Trajectory Prediction with Dynamic Relational Reasoning", NeurIPS, 2020.</em> <a href=https://papers.nips.cc/paper/2020/file/e4d8163c7a068b65a64c89bd745ec360-Paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.13924.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#h3d">H3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2020_NeurIPS,
    author = "Li, Jiachen and Yang, Fan and Tomizuka, Masayoshi and Choi, Chiho",
    booktitle = "NeurIPS",
    title = "{EvolveGraph}: Multi-Agent Trajectory Prediction with Dynamic Relational Reasoning",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ivanovic et al., "Generative Modeling of Multimodal Multi-human Behavior", IROS, 2018.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8594393>paper</a> <a href=https://arxiv.org/pdf/1803.02015.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ivanovic_2018_IROS,
    author = "Ivanovic, Boris and Schmerling, Edward and Leung, Karen and Pavone, Marco",
    title = "Generative Modeling of Multimodal Multi-human Behavior",
    booktitle = "IROS",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhan et al., "Generating Multi-agent Trajectories using Programmatic Weak Supervision", ICLR, 2017.</em> <a href=https://openreview.net/pdf?id=rkxw-hAcFQ>paper</a> <a href=https://arxiv.org/pdf/1803.07612.pdf>arxiv</a> <a href=https://github.com/ezhan94/multiagent-programmatic-supervision>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#ll">LL</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#human">Human</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Misc{Linou_2016,
    author = "Luo, K",
    Title = "{NBA}-Player-Movements",
    HowPublished = "Online",
    year = "2016",
    url = "https://github.com/linouk23/NBA-Player-Movements"
}
</pre>
</details>

</ul></details>
<a name=ntu_rgb-d></a>
<details close>
<summary><l style="font-size:20px"><strong>NTU RGB-D</strong></l> <a href=http://rose1.ntu.edu.sg/Datasets/actionRecognition.asp>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Shahroudy_NTU_RGBD_A_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1604.02808.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An action dataset of 60 daily activities in 56K+ video samples
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, IR, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Rupprecht et al., "Learning in an Uncertain World: Representing Ambiguity Through Multiple Hypotheses", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Rupprecht_Learning_in_an_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1612.00197.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#sharpness">Sharpness</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rupprecht_2017_ICCV,
    author = "Rupprecht, Christian and Laina, Iro and DiPietro, Robert and Baust, Maximilian and Tombari, Federico and Navab, Nassir and Hager, Gregory D",
    title = "Learning in an Uncertain World: Representing Ambiguity Through Multiple Hypotheses",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Stergiou et al., "The Wisdom of Crowds: Temporal Progressive Attention for Early Action Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Stergiou_The_Wisdom_of_Crowds_Temporal_Progressive_Attention_for_Early_Action_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.13340.pdf>arxiv</a> <a href=https://alexandrosstergiou.github.io/project_pages/TemPr/index.html>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#smtsmt">SmtSmt</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Stergiou_2023_CVPR,
    author = "Stergiou, Alexandros and Damen, Dima",
    title = "The Wisdom of Crowds: Temporal Progressive Attention for Early Action Prediction",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Foo et al., "ERA: Expert Retrieval and Assembly for Early Action Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940657.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.09675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Foo_2022_ECCV,
    author = "Foo, Lin Geng and Li, Tianjiao and Rahmani, Hossein and Ke, Qiuhong and Liu, Jun",
    title = "{ERA}: Expert Retrieval and Assembly for Early Action Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Li et al., "HARD-Net: Hardness-AwaRe Discrimination Network for 3D Early Activity Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123560409.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#fpha">FPHA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2020_ECCV,
    author = "Li, Tianjiao and Liu, Jun and Zhang, Wei and Duan, Lingyu",
    title = "{HARD-Net}: Hardness-AwaRe Discrimination Network for {3D} Early Activity Prediction",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "Progressive Teacher-Student Learning For Early Action Prediction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Progressive_Teacher-Student_Learning_for_Early_Action_Prediction_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2019_CVPR,
    author = "Wang, Xionghui and Hu, Jian-Fang and Lai, Jian-Huang and Zhang, Jianguo and Zheng, Wei-Shi",
    title = "Progressive Teacher-Student Learning For Early Action Prediction",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Mao et al., "Masked Motion Predictors are Strong 3D Action Representation Learners", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Mao_Masked_Motion_Predictors_are_Strong_3D_Action_Representation_Learners_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.07092.pdf>arxiv</a> <a href=https://github.com/maoyunyao/MAMP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pku-mmd">PKU-MMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mao_2023_ICCV,
    author = "Mao, Yunyao and Deng, Jiajun and Zhou, Wengang and Fang, Yao and Ouyang, Wanli and Li, Houqiang",
    title = "Masked Motion Predictors are Strong 3D Action Representation Learners",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yasar et al., "VADER: Vector-Quantized Generative Adversarial Network for Motion Prediction", IROS, 2023.</em> <a href=https://ieeexplore.ieee.org/document/10342324>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth-hrc">KTH-HRC</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#utd-mhad">UTD-MHAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@INPROCEEDINGS{Yasar_2023_IROS,
    author = "Yasar, Mohammad Samin and Iqbal, Tariq",
    booktitle = "IROS",
    title = "VADER: Vector-Quantized Generative Adversarial Network for Motion Prediction",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Mao et al., "Weakly-Supervised Action Transition Learning for Stochastic Human Motion Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Mao_Weakly-Supervised_Action_Transition_Learning_for_Stochastic_Human_Motion_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://github.com/wei-mao-2019/WAT>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#grab">GRAB</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#babel">BABEL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fid">FID</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#div">Div</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mao_2022_CVPR,
    author = "Mao, Wei and Liu, Miaomiao and Salzmann, Mathieu",
    title = "Weakly-Supervised Action Transition Learning for Stochastic Human Motion Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhang et al., "Non-local Graph Convolutional Network for Joint Activity Recognition and Motion Prediction", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636107>paper</a> <a href=https://arxiv.org/pdf/2108.01518.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2021_IROS,
    author = "Zhang, Dianhao and Vien, Ngo Anh and Van, Mien and McLoone, Seán",
    booktitle = "IROS",
    title = "Non-local Graph Convolutional Network for Joint Activity Recognition and Motion Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yasar et al., "A Scalable Approach to Predict Multi-Agent Motion for Human-Robot Collaboration", RAL, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9353218>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth-hrc">KTH-HRC</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#utd-mhad">UTD-MHAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Yasar_2021_RAL,
    author = "Yasar, Mohammad Samin and Iqbal, Tariq",
    journal = "RAL",
    title = "A Scalable Approach to Predict Multi-Agent Motion for Human-Robot Collaboration",
    year = "2021",
    volume = "6",
    number = "2",
    pages = "1686-1693"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Adeli et al., "Socially and Contextually Aware Human Motion and Pose Forecasting", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9145701>paper</a> <a href=https://arxiv.org/pdf/2007.06843.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#posetrack">PoseTrack</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Adeli_2020_RAL,
    author = "Adeli, V. and Adeli, E. and Reid, I. and Niebles, J. C. and Rezatofighi, H.",
    journal = "RAL",
    title = "Socially and Contextually Aware Human Motion and Pose Forecasting",
    year = "2020",
    volume = "5",
    number = "4",
    pages = "6033-6040"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Shahroudy_2016_CVPR,
    author = "Shahroudy, Amir and Liu, Jun and Ng, Tian-Tsong and Wang, Gang",
    title = "{NTU RGB+D}: A Large Scale Dataset For 3D Human Activity Analysis",
    booktitle = "CVPR",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=bair_push></a>
<details close>
<summary><l style="font-size:20px"><strong>BAIR Push</strong></l> <a href=https://sites.google.com/site/brainrobotdata/home/push-dataset>link</a> <a href=https://papers.nips.cc/paper/6161-unsupervised-learning-for-physical-interaction-through-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1605.07157.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of object manipulation using a robot arm with 59k object pushing motion samples
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Robot object manipulation</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Shrivastava et al., "Video Prediction by Modeling Videos as Continuous Multi-Dimensional Processes", CVPR, 2024.</em> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Shrivastava_Video_Prediction_by_Modeling_Videos_as_Continuous_Multi-Dimensional_Processes_CVPR_2024_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shrivastava_Video_2024_CVPR,
    author = "Shrivastava, Gaurav and Shrivastava, Abhinav",
    title = "Video Prediction by Modeling Videos as Continuous Multi-Dimensional Processes",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhang et al., "ExtDM: Distribution Extrapolation Diffusion Model for Video Prediction", CVPR, 2024.</em> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_ExtDM_Distribution_Extrapolation_Diffusion_Model_for_Video_Prediction_CVPR_2024_paper.pdf>paper</a> <a href=https://github.com/nku-zhichengzhang/ExtDM>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair">BAIR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_ExtDM_2024_CVPR,
    author = "Zhang, Zhicheng and Hu, Junyao and Cheng, Wentao and Paudel, Danda and Yang, Jufeng",
    title = "ExtDM: Distribution Extrapolation Diffusion Model for Video Prediction",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Davtyan et al., "Efficient Video Prediction via Sparsely Conditioned Flow Matching", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Davtyan_Efficient_Video_Prediction_via_Sparsely_Conditioned_Flow_Matching_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2211.14575.pdf>arxiv</a> <a href=https://araachie.github.io/river/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair">BAIR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Davtyan_2023_ICCV,
    author = "Davtyan, Aram and Sameni, Sepehr and Favaro, Paolo",
    title = "Efficient Video Prediction via Sparsely Conditioned Flow Matching",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chatterjee et al., "A Hierarchical Variational Neural Uncertainty Model for Stochastic Video Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Chatterjee_A_Hierarchical_Variational_Neural_Uncertainty_Model_for_Stochastic_Video_Prediction_ICCV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chatterjee_2021_ICCV,
    author = "Chatterjee, Moitreya and Ahuja, Narendra and Cherian, Anoop",
    title = "A Hierarchical Variational Neural Uncertainty Model for Stochastic Video Prediction",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Jin et al., "Exploring Spatial-Temporal Multi-Frequency Analysis for High-Fidelity and Temporal-Consistency Video Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Jin_Exploring_Spatial-Temporal_Multi-Frequency_Analysis_for_High-Fidelity_and_Temporal-Consistency_Video_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2002.09905.pdf>arxiv</a> <a href=https://github.com/Bei-Jin/STMFANet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair">BAIR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jin_2020_CVPR,
    author = "Jin, Beibei and Hu, Yu and Tang, Qiankun and Niu, Jingyu and Shi, Zhiping and Han, Yinhe and Li, Xiaowei",
    title = "Exploring Spatial-Temporal Multi-Frequency Analysis for High-Fidelity and Temporal-Consistency Video Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Franceschi et al., "Stochastic Latent Residual Video Prediction", ICML, 2020.</em> <a href=http://proceedings.mlr.press/v119/franceschi20a/franceschi20a.pdf>paper</a> <a href=https://arxiv.org/pdf/2002.09219.pdf>arxiv</a> <a href=https://github.com/edouardelasalles/srvp>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Franceschi_2020_ICML,
    author = {Franceschi, Jean-Yves and Delasalles, Edouard and Chen, Micka{\"e}l and Lamprier, Sylvain and Gallinari, Patrick},
    title = "Stochastic Latent Residual Video Prediction",
    booktitle = "ICML",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Video Prediction via Example Guidance", ICML, 2020.</em> <a href=http://proceedings.mlr.press/v119/xu20j/xu20j.pdf>paper</a> <a href=https://arxiv.org/pdf/2007.01738.pdf>arxiv</a> <a href=https://github.com/xjwxjw/VPEG>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2020_ICML,
    author = "Xu, Jingwei and Xu, Huazhe and Ni, Bingbing and Yang, Xiaokang and Darrell, Trevor",
    title = "Video Prediction via Example Guidance",
    booktitle = "ICML",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Castrejon et al., "Improved Conditional VRNNs For Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Castrejon_Improved_Conditional_VRNNs_for_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.12165.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Castrejon_2019_ICCV,
    author = "Castrejon, Lluis and Ballas, Nicolas and Courville, Aaron",
    title = "Improved Conditional {VRNNs} For Video Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Video Prediction Via Selective Sampling", NeurIPS, 2018.</em> <a href=https://papers.nips.cc/paper/7442-video-prediction-via-selective-sampling.pdf>paper</a> <a href=https://github.com/xjwxjw/VPSS>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2018_NeurIPS,
    author = "Xu, Jingwei and Ni, Bingbing and Yang, Xiaokang",
    title = "Video Prediction Via Selective Sampling",
    booktitle = "NeurIPS",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Finn et al., "Unsupervised Learning For Physical Interaction Through Video Prediction", NeurIPS, 2016.</em> <a href=https://papers.nips.cc/paper/6161-unsupervised-learning-for-physical-interaction-through-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1605.07157.pdf>arxiv</a> <a href=https://github.com/tensorflow/models/tree/master/research/video_prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Finn_2016_NeurIPS,
    author = "Finn, Chelsea and Goodfellow, Ian and Levine, Sergey",
    title = "Unsupervised Learning For Physical Interaction Through Video Prediction",
    booktitle = "NeurIPS",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Finn_2016_NeurIPS,
    author = "Finn, Chelsea and Goodfellow, Ian and Levine, Sergey",
    title = "Unsupervised Learning For Physical Interaction Through Video Prediction",
    booktitle = "NeurIPS",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=vist></a>
<details close>
<summary><l style="font-size:20px"><strong>Visual Storytelling (VIST)</strong></l> <a href=http://visionandlanguage.net/VIST/>link</a> <a href=https://www.aclweb.org/anthology/N16-1147.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 80K+ images collected from 21K+ sequences with corresponding text captions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, text</li>
<li><em><strong>Task:</strong></em> Visual story</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Vo et al., "A-Cap: Anticipation Captioning With Commonsense Knowledge", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Vo_A-Cap_Anticipation_Captioning_With_Commonsense_Knowledge_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2304.06602.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#vist">VIST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#bleu">BLEU</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#refclipscore">RefCLIPScore</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#clipscore">CLIPScore</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#spice">SPICE</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#cider">CIDEr</a></li>
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
<summary><em>Zeng et al., "Visual Forecasting By Imitating Dynamics In Natural Sequences", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Zeng_Visual_Forecasting_by_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.05827.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#vist">VIST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#accuracy">Accuracy</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Huang_2016_NAACL,
    author = "Huang, Ting-Hao K. and Ferraro, Francis and Mostafazadeh, Nasrin and Misra, Ishan and Devlin, Jacob and Agrawal, Aishwarya and Girshick, Ross and He, Xiaodong and Kohli, Pushmeet and Batra, Dhruv and others",
    title = "Visual Storytelling",
    booktitle = "NAACL",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=tcga></a>
<details close>
<summary><l style="font-size:20px"><strong>The Cancer Genome Atlas Program (TCGA)</strong></l> <a href=https://www.cancer.gov/ccg/research/genome-sequencing/tcga>link</a> <a href=https://link.springer.com/protocol/10.1007/978-1-4939-3578-9_6>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 20K genomics for 33 types of cancers.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Label</li>
<li><em><strong>Task:</strong></em> Risk assessment</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Song et al., "Multimodal Prototyping for cancer survival prediction", ICML, 2024.</em> <a href=https://openreview.net/pdf?id=3MfvxH3Gia>paper</a> <a href=https://arxiv.org/pdf/2407.00224>arxiv</a> <a href=https://github.com/mahmoodlab/MMP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tcga">TCGA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#c-index">C-index</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#p-value">p-value</a></li>
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
<summary><em>Zhang et al., "Prototypical Information Bottlenecking and Disentangling for Multimodal Cancer Survival Prediction", ICLR, 2024.</em> <a href=https://openreview.net/pdf?id=otHZ8JAIgh>paper</a> <a href=https://arxiv.org/pdf/2401.01646>arxiv</a> <a href=https://github.com/zylbuaa/PIBD.git>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tcga">TCGA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#c-index">C-index</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@article{Wang_practical_2024_SGMP,
    author = "Wang, Zhining and Jensen, Mark A and Zenklusen, Jean Claude",
    title = "A practical guide to the cancer genome atlas (TCGA)",
    journal = "Statistical Genomics: Methods and Protocols",
    pages = "111--141",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=tv_series></a>
<details close>
<summary><l style="font-size:20px"><strong>TV Series</strong></l> <a href=https://github.com/zhenyangli/online_action>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46454-1_17>paper</a> <a href=https://arxiv.org/pdf/1604.06506.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A collection of sequences collected from TV series for the purpose of action detection
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Gao et al., "RED: Reinforced Encoder-Decoder Networks For Action Anticipation", BMVC, 2017.</em> <a href=http://www.bmva.org/bmvc/2017/papers/paper092/paper092.pdf>paper</a> <a href=https://arxiv.org/pdf/1707.04818.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_series">TV Series</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#map">mAP</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#cap">cAP</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{De_2016_ECCV,
    author = "De Geest, Roeland and Gavves, Efstratios and Ghodrati, Amir and Li, Zhenyang and Snoek, Cees and Tuytelaars, Tinne",
    title = "Online Action Detection",
    booktitle = "ECCV",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=oad></a>
<details close>
<summary><l style="font-size:20px"><strong>Online Action Detection (OAD)</strong></l> <a href=http://www.icst.pku.edu.cn/struct/Projects/OAD.html>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46478-7_13>paper</a> <a href=https://arxiv.org/pdf/1604.05633.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 10 indoor activities in 59 sequences collected using a Kinect V2 sensor
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D pose, activity label, temporal segment, Tracking ID</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liu et al., "SSNet: Scale Selection Network For Online 3D Action Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_SSNet_Scale_Selection_CVPR_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pku-mmd">PKU-MMD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#oad">OAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2018_CVPR_ssnet,
    author = "Liu, Jun and Shahroudy, Amir and Wang, Gang and Duan, Ling-Yu and Kot, Alex C.",
    title = "{SSNet}: Scale Selection Network For Online {3D} Action Prediction",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Li_2016_ECCV,
    author = "Li, Yanghao and Lan, Cuiling and Xing, Junliang and Zeng, Wenjun and Yuan, Chunfeng and Liu, Jiaying",
    title = "Online Human Action Detection Using Joint Classification-Regression Recurrent Neural Networks",
    journal = "ECCV",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=oa></a>
<details close>
<summary><l style="font-size:20px"><strong>Ongoing Activity (OA)</strong></l> <a href=http://www.mpii.de/ongoing-activity>link</a> <a href=https://ieeexplore.ieee.org/document/7477586>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 450+ activities, such as cooking, house chores, etc.,  videos collected from public video sharing websites
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Li et al., "Recognition Of Ongoing Complex Activities By Sequence Prediction Over A Hierarchical Label Space", WACV, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7477586>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#oa">OA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2016_WACV,
    author = "Li, W. and Fritz, M.",
    booktitle = "WACV",
    title = "Recognition Of Ongoing Complex Activities By Sequence Prediction Over A Hierarchical Label Space",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Li_2016_WACV,
    author = "Li, W. and Fritz, M.",
    booktitle = "WACV",
    title = "Recognition Of Ongoing Complex Activities By Sequence Prediction Over A Hierarchical Label Space",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=youtube-8m></a>
<details close>
<summary><l style="font-size:20px"><strong>Youtube-8M</strong></l> <a href=https://research.google.com/youtube8m/>link</a> <a href=https://arxiv.org/pdf/1609.08675.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale dataset of videos collected from YouTube with corresponding machine-generated annotations from a vocabulary of 3.8K+ visual entities
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Reda et al., "SDC-Net: Video Prediction Using Spatially-Displaced Convolution", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Fitsum_Reda_SDC-Net_Video_prediction_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1811.00684.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#youtube-8m">Youtube-8M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#l1">L1</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Reda_2018_ECCV,
    author = "Reda, Fitsum A. and Liu, Guilin and Shih, Kevin J. and Kirby, Robert and Barker, Jon and Tarjan, David and Tao, Andrew and Catanzaro, Bryan",
    title = "{SDC-Net}: Video Prediction Using Spatially-Displaced Convolution",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Abu_2016_arxiv,
    author = "Abu-El-Haija, Sami and Kothari, Nisarg and Lee, Joonseok and Natsev, Paul and Toderici, George and Varadarajan, Balakrishnan and Vijayanarasimhan, Sudheendra",
    title = "{YouTube-8M}: A Large-Scale Video Classification Benchmark",
    journal = "arXiv:1609.08675",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=mu></a>
<details close>
<summary><l style="font-size:20px"><strong>Miss Universe (MU)</strong></l> <a href=http://staff.itee.uq.edu.au/lovell/MissUniverse/>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/7899781>paper</a> <a href=https://arxiv.org/pdf/1604.07547.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of catwalks by Miss Universe contestants during the evening gown competition from 1996 to 2010
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, scores</li>
<li><em><strong>Task:</strong></em> Miss universe</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Carvajal et al., "Towards Miss Universe Automatic Prediction: The Evening Gown Competition", ICPR, 2016.</em> <a href=https://ieeexplore.ieee.org/abstract/document/7899781>paper</a> <a href=https://arxiv.org/pdf/1604.07547.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mu">MU</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#accuracy">Accuracy</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Carvajal_2016_ICPR,
    author = "Carvajal, J. and Wiliem, A. and Sanderson, C. and Lovell, B.",
    booktitle = "ICPR",
    title = "Towards Miss Universe Automatic Prediction: The Evening Gown Competition",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=bouncing_ball></a>
<details close>
<summary><l style="font-size:20px"><strong>Bouncing Ball (BB)</strong></l> <a href=https://github.com/mbchang/dynamics>link</a> <a href=https://openreview.net/pdf?id=Bkab5dqxe>paper</a> <a href=https://arxiv.org/pdf/1612.00341.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A simulated dataset of bounding balls generated using Neural Physics Engine
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Object (simulation)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hsieh et al., "Learning To Decompose And Disentangle Representations For Video Prediction", NeurIPS, 2018.</em> <a href=https://papers.nips.cc/paper/7333-learning-to-decompose-and-disentangle-representations-for-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1806.04166.pdf>arxiv</a> <a href=https://github.com/jthsieh/DDPAE-video-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bouncing_ball">Bouncing Ball</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_a-d_metrics.md#bce">BCE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hsieh_2018_NeurIPS,
    author = "Hsieh, Jun-Ting and Liu, Bingbin and Huang, De-An and Fei-Fei, Li F and Niebles, Juan Carlos",
    title = "Learning To Decompose And Disentangle Representations For Video Prediction",
    booktitle = "NeurIPS",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Chang_2016_arxiv,
    author = "Chang, Michael B and Ullman, Tomer and Torralba, Antonio and Tenenbaum, Joshua B",
    title = "A Compositional Object-Based Approach To Learning Physical Dynamics",
    journal = "arXiv:1612.00341",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=charades></a>
<details close>
<summary><l style="font-size:20px"><strong>Charades</strong></l> <a href=https://prior.allenai.org/projects/charades>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46448-0_31>paper</a> <a href=https://arxiv.org/pdf/1604.01753.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of ~10K indoor videos with 157 action  and 46 object classes
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity label, Object Class, Temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Piergiovanni et al., "Adversarial Generative Grammars for Human Activity Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470494.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.04888.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#charades">Charades</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#map">mAP</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Sigurdsson_2016_ECCV,
    author = {Sigurdsson, Gunnar A and Varol, G{\"u}l and Wang, Xiaolong and Farhadi, Ali and Laptev, Ivan and Gupta, Abhinav},
    title = "Hollywood in Homes: Crowdsourcing Data Collection for Activity Understanding",
    booktitle = "ECCV",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=volleyball></a>
<details close>
<summary><l style="font-size:20px"><strong>Volleyball</strong></l> <a href=https://github.com/mostafa-saad/deep-activity-rec#dataset>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Ibrahim_A_Hierarchical_Deep_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.06040.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 4830 frames from 55 videos with 9 player action labels and 8 team activity labels
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a>, <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity label, Bounding box</li>
<li><em><strong>Task:</strong></em> Sport</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chen et al., "Group Activity Prediction with Sequential Relational Anticipation Model", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660579.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.02441.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#ca">CA</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#volleyball">Volleyball</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Ibrahim_2016_CVPR,
    author = "Ibrahim, Mostafa S and Muralidharan, Srikanth and Deng, Zhiwei and Vahdat, Arash and Mori, Greg",
    title = "A Hierarchical Deep Temporal Model for Group Activity Recognition",
    booktitle = "CVPR",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=ceilidh_dance></a>
<details close>
<summary><l style="font-size:20px"><strong>Ceilidh Dance</strong></l> <a href=https://homepages.inf.ed.ac.uk/rbf/CEILIDHDATA/>link</a> <a href=https://homepages.inf.ed.ac.uk/rbf/CEILIDHDATA/msc_20161996.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of Ceilidh Scottish dance sequences performed by 16 dancers in two styles recorded from bird’s eye view.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a>, <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity Label, Trajectory</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hu et al., "Entry-Flipped Transformer for Inference and Prediction of Participant Behavior", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136640433.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.06235.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#ceilidh_dance">Ceilidh Dance</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@mastersthesis{Aizeboje_2016_masc,
    author = "Aizeboje, Jeremiah",
    title = "Ceilidh Dance Recognition from an Overhead Camera",
    year = "2016",
    school = "University of Edinburgh"
}
</pre>
</details>

</ul></details>
<a name=flyingthings3d></a>
<details close>
<summary><l style="font-size:20px"><strong>FlyingThings3D</strong></l> <a href=https://lmb.informatik.uni-freiburg.de/resources/datasets/SceneFlowDatasets.en.html>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Mayer_A_Large_Dataset_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1512.02134>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of randomized 3D trajectories generated using 25K synthetic stereo frames.
</li>
<li>
<em><strong>Applications:</strong></em> </li>
<li><em><strong>Data type and annotations:</strong></em> RGBD</li>
<li><em><strong>Task:</strong></em> Object (simulation)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Dong et al., "MemFlow: Optical Flow Estimation and Prediction with Memory", CVPR, 2024.</em> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Dong_MemFlow_Optical_Flow_Estimation_and_Prediction_with_Memory_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2404.04808>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sintel">Sintel</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#flyingthings3d">FlyingThings3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#epe">EPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Dong_MemFlow_2024_CVPR,
    author = "Dong, Qiaole and Fu, Yanwei",
    title = "MemFlow: Optical Flow Estimation and Prediction with Memory",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Mayer_Large_2016_CVPR,
    author = "Mayer, Nikolaus and Ilg, Eddy and Hausser, Philip and Fischer, Philipp and Cremers, Daniel and Dosovitskiy, Alexey and Brox, Thomas",
    title = "A Large Dataset to Train Convolutional Networks for Disparity, Optical Flow, and Scene Flow Estimation",
    booktitle = "CVPR",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=kit_wbhm></a>
<details close>
<summary><l style="font-size:20px"><strong>KIT Whole-Body Human Motion (KIT WBHM)</strong></l> <a href=https://motion-database.humanoids.kit.edu/>link</a> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7506114>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 6.7K recordings of human-object interactions performed by 53 subjects.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/motion/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> 3D Pose, Activity Label</li>
<li><em><strong>Task:</strong></em> Pose</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Lee, "Commonsense Spatial Knowledge-aware 3-D Human Motion and Object Interaction Prediction", ICRA, 2024.</em> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10610161>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kit_wbhm">KIT WBHM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Lee_Commonsense_2024_ICRA,
    author = "Lee, Sang Uk",
    booktitle = "ICRA",
    title = "Commonsense Spatial Knowledge-aware 3-D Human Motion and Object Interaction Prediction",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@ARTICLE{Mandery_Unifying_2016_ToR,
    author = {Mandery, Christian and Terlemez, \"Omer and Do, Martin and Vahrenkamp, Nikolaus and Asfour, Tamim},
    title = "Unifying Representations and Large-Scale Whole-Body Motion Databases for Studying Human Motion",
    pages = "796--809",
    volume = "32",
    number = "4",
    journal = "IEEE Transactions on Robotics",
    year = "2016"
}
</pre>
</details>

</ul></details>
</ul><h2>2015</h2>
<ul><a name=mmnist></a>
<details close>
<summary><l style="font-size:20px"><strong>Moving MNIST (MMNIST)</strong></l> <a href=http://www.cs.toronto.edu/~nitish/unsupervised_video/>link</a> <a href=http://proceedings.mlr.press/v37/srivastava15.pdf>paper</a> <a href=https://arxiv.org/pdf/1502.04681.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of moving digits on a simple uniform background
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Grayscale</li>
<li><em><strong>Task:</strong></em> Digit</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhang et al., "ExtDM: Distribution Extrapolation Diffusion Model for Video Prediction", CVPR, 2024.</em> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_ExtDM_Distribution_Extrapolation_Diffusion_Model_for_Video_Prediction_CVPR_2024_paper.pdf>paper</a> <a href=https://github.com/nku-zhichengzhang/ExtDM>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair">BAIR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_ExtDM_2024_CVPR,
    author = "Zhang, Zhicheng and Hu, Junyao and Cheng, Wentao and Paudel, Danda and Yang, Jufeng",
    title = "ExtDM: Distribution Extrapolation Diffusion Model for Video Prediction",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhong et al., "MMVP: Motion-Matrix-Based Video Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Zhong_MMVP_Motion-Matrix-Based_Video_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.16154.pdf>arxiv</a> <a href=https://github.com/Kay1794/MMVP-motion-matrix-based-video-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf_sports">UCF Sports</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhong_2023_ICCV,
    author = "Zhong, Yiqi and Liang, Luming and Zharkov, Ilya and Neumann, Ulrich",
    title = "MMVP: Motion-Matrix-Based Video Prediction",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Gao et al., "SimVP: Simpler Yet Better Video Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Gao_SimVP_Simpler_Yet_Better_Video_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2206.05099.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#taxi_bj">Taxi BJ</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2022_CVPR,
    author = "Gao, Zhangyang and Tan, Cheng and Wu, Lirong and Li, Stan Z.",
    title = "{SimVP}: Simpler Yet Better Video Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Pourheydari et al., "TaylorSwiftNet: Taylor Driven Temporal Modeling for Swift Future Frame Prediction", BMVC, 2022.</em> <a href=https://bmvc2022.mpi-inf.mpg.de/0389.pdf>paper</a> <a href=https://arxiv.org/pdf/2110.14392.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#taxi_bj">Taxi BJ</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sst">SST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Pourheydari_2022_BMVC,
    author = "Pourheydari, Mohammad Saber and Bahrami, Emad and Fayyaz, Mohsen and Francesca, Gianpiero and Noroozi, Mehdi and Gall, Jürgen",
    title = "{TaylorSwiftNet}: Taylor Driven Temporal Modeling for Swift Future Frame Prediction",
    booktitle = "BMVC",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Villar-Corrales et al., "MSPred: Video Prediction at Multiple Spatio-Temporal Scales with Hierarchical Recurrent Networks", BMVC, 2022.</em> <a href=https://bmvc2022.mpi-inf.mpg.de/0034.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.09303.pdf>arxiv</a> <a href=https://github.com/AIS-Bonn/MSPred>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Villar-Corrales_2022_BMVC,
    author = "Villar-Corrales, Angel and Karapetyan, Ani and Boltres, Andreas and Behnke, Sven",
    title = "{MSPred}: Video Prediction at Multiple Spatio-Temporal Scales with Hierarchical Recurrent Networks",
    booktitle = "BMVC",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "Towards Unified Multi-Excitation for Unsupervised Video Prediction", BMVC, 2022.</em> <a href=https://bmvc2022.mpi-inf.mpg.de/0587.pdf>paper</a> <a href=https://github.com/captaincj/UMENet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#taxi_bj">Taxi BJ</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sst">SST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2022_BMVC,
    author = "Wang, Junyan and Likun, Qin and Zhang, Peng and Long, Yang and Hu, Bingzhang and Pagnucco, Maurice and Wang, Shizheng and Song, Yang",
    title = "Towards Unified Multi-Excitation for Unsupervised Video Prediction",
    booktitle = "BMVC",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ben et al., "PhyLoNet: Physically-Constrained Long Term Video Prediction", ACCV, 2022.</em> <a href=https://openaccess.thecvf.com/content/ACCV2022/papers/Zikri_PhyLoNet_Physically-Constrained_Long_Term_Video_Prediction_ACCV_2022_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ben_Zikri_2022_ACCV,
    author = "Ben Zikri, Nir and Sharf, Andrei",
    title = "{PhyLoNet}: Physically-Constrained Long Term Video Prediction",
    booktitle = "ACCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chang et al., "MAU: A Motion-Aware Unit for Video Prediction and Beyond", NeurIPS, 2021.</em> <a href=https://papers.nips.cc/paper/2021/file/e25cfa90f04351958216f97e3efdabe9-Paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#town_center">Town Center</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#smtsmt">SmtSmt</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chang_2021_NeurIPS,
    author = "Chang, Zheng and Zhang, Xinfeng and Wang, Shanshe and Ma, Siwei and Ye, Yan and Xinguang, Xiang and Gao, Wen",
    booktitle = "NeurIPS",
    title = "{MAU}: A Motion-Aware Unit for Video Prediction and Beyond",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Lee et al., "Video Prediction Recalling Long-Term Motion Context via Memory Alignment Learning", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Lee_Video_Prediction_Recalling_Long-Term_Motion_Context_via_Memory_Alignment_Learning_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2104.00924.pdf>arxiv</a> <a href=https://github.com/sangmin-git/LMC-Memory>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lee_2021_CVPR,
    author = "Lee, Sangmin and Kim, Hak Gu and Choi, Dae Hwi and Kim, Hyung-Il and Ro, Yong Man",
    title = "Video Prediction Recalling Long-Term Motion Context via Memory Alignment Learning",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chatterjee et al., "A Hierarchical Variational Neural Uncertainty Model for Stochastic Video Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Chatterjee_A_Hierarchical_Variational_Neural_Uncertainty_Model_for_Stochastic_Video_Prediction_ICCV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chatterjee_2021_ICCV,
    author = "Chatterjee, Moitreya and Ahuja, Narendra and Cherian, Anoop",
    title = "A Hierarchical Variational Neural Uncertainty Model for Stochastic Video Prediction",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Le et al., "Disentangling Physical Dynamics From Unknown Factors for Unsupervised Video Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Le_Guen_Disentangling_Physical_Dynamics_From_Unknown_Factors_for_Unsupervised_Video_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.01460.pdf>arxiv</a> <a href=https://github.com/vincent-leguen/PhyDNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#taxi_bj">Taxi BJ</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sst">SST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Guen_2020_CVPR,
    author = "Le Guen, Vincent and Thome, Nicolas",
    title = "Disentangling Physical Dynamics From Unknown Factors for Unsupervised Video Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "Probabilistic Video Prediction From Noisy Data With a Posterior Confidence", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_Probabilistic_Video_Prediction_From_Noisy_Data_With_a_Posterior_Confidence_CVPR_2020_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2020_CVPR,
    author = "Wang, Yunbo and Wu, Jiajun and Long, Mingsheng and Tenenbaum, Joshua B.",
    title = "Probabilistic Video Prediction From Noisy Data With a Posterior Confidence",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Franceschi et al., "Stochastic Latent Residual Video Prediction", ICML, 2020.</em> <a href=http://proceedings.mlr.press/v119/franceschi20a/franceschi20a.pdf>paper</a> <a href=https://arxiv.org/pdf/2002.09219.pdf>arxiv</a> <a href=https://github.com/edouardelasalles/srvp>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Franceschi_2020_ICML,
    author = {Franceschi, Jean-Yves and Delasalles, Edouard and Chen, Micka{\"e}l and Lamprier, Sylvain and Gallinari, Patrick},
    title = "Stochastic Latent Residual Video Prediction",
    booktitle = "ICML",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Video Prediction via Example Guidance", ICML, 2020.</em> <a href=http://proceedings.mlr.press/v119/xu20j/xu20j.pdf>paper</a> <a href=https://arxiv.org/pdf/2007.01738.pdf>arxiv</a> <a href=https://github.com/xjwxjw/VPEG>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2020_ICML,
    author = "Xu, Jingwei and Xu, Huazhe and Ni, Bingbing and Yang, Xiaokang and Darrell, Trevor",
    title = "Video Prediction via Example Guidance",
    booktitle = "ICML",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yao et al., "Unsupervised Transfer Learning for Spatiotemporal Predictive Networks", ICML, 2020.</em> <a href=http://proceedings.mlr.press/v119/yao20a/yao20a.pdf>paper</a> <a href=https://arxiv.org/pdf/2009.11763.pdf>arxiv</a> <a href=https://github.com/thuml/transferable-memory>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#weizmann">Weizmann</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yao_2020_ICML,
    author = "Yao, Zhiyu and Wang, Yunbo and Long, Mingsheng and Wang, Jianmin",
    title = "Unsupervised Transfer Learning for Spatiotemporal Predictive Networks",
    booktitle = "ICML",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Castrejon et al., "Improved Conditional VRNNs For Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Castrejon_Improved_Conditional_VRNNs_for_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.12165.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Castrejon_2019_ICCV,
    author = "Castrejon, Lluis and Ballas, Nicolas and Courville, Aaron",
    title = "Improved Conditional {VRNNs} For Video Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Lee et al., "Mutual Suppression Network For Video Prediction Using Disentangled Features", BMVC, 2019.</em> <a href=https://bmvc2019.org/wp-content/uploads/papers/0336-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.04810.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lee_2019_BMVC,
    author = "Lee, Jungbeom and Lee, Jangho and Lee, Sungmin and Yoon, Sungroh",
    title = "Mutual Suppression Network For Video Prediction Using Disentangled Features",
    year = "2019",
    booktitle = "BMVC"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "Order Matters: Shuffling Sequence Generation For Video Prediction", BMVC, 2019.</em> <a href=https://bmvc2019.org/wp-content/uploads/papers/1023-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1907.08845.pdf>arxiv</a> <a href=https://github.com/andrewjywang/SEENet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#msr">MSR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2019_BMVC,
    author = "Wang, Junyan and Hu, Bingzhang and Long, Yang and Guan, Yu",
    title = "Order Matters: Shuffling Sequence Generation For Video Prediction",
    year = "2019",
    booktitle = "BMVC"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Oliu et al., "Folded Recurrent Neural Networks For Future Video Prediction", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Marc_Oliu_Folded_Recurrent_Neural_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1712.00311.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Oliu_2018_ECCV,
    author = "Oliu, Marc and Selva, Javier and Escalera, Sergio",
    title = "Folded Recurrent Neural Networks For Future Video Prediction",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Hsieh et al., "Learning To Decompose And Disentangle Representations For Video Prediction", NeurIPS, 2018.</em> <a href=https://papers.nips.cc/paper/7333-learning-to-decompose-and-disentangle-representations-for-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1806.04166.pdf>arxiv</a> <a href=https://github.com/jthsieh/DDPAE-video-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bouncing_ball">Bouncing Ball</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_a-d_metrics.md#bce">BCE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hsieh_2018_NeurIPS,
    author = "Hsieh, Jun-Ting and Liu, Bingbin and Huang, De-An and Fei-Fei, Li F and Niebles, Juan Carlos",
    title = "Learning To Decompose And Disentangle Representations For Video Prediction",
    booktitle = "NeurIPS",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Video Prediction Via Selective Sampling", NeurIPS, 2018.</em> <a href=https://papers.nips.cc/paper/7442-video-prediction-via-selective-sampling.pdf>paper</a> <a href=https://github.com/xjwxjw/VPSS>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2018_NeurIPS,
    author = "Xu, Jingwei and Ni, Bingbing and Yang, Xiaokang",
    title = "Video Prediction Via Selective Sampling",
    booktitle = "NeurIPS",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Lu et al., "Flexible Spatio-Temporal Networks For Video Prediction", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lu_Flexible_Spatio-Temporal_Networks_CVPR_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sports-1m">Sports-1M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#visor">ViSOR</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#prost">PROST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lu_2017_CVPR,
    author = "Lu, Chaochao and Hirsch, Michael and Scholkopf, Bernhard",
    title = "Flexible Spatio-Temporal Networks For Video Prediction",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zeng et al., "Visual Forecasting By Imitating Dynamics In Natural Sequences", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Zeng_Visual_Forecasting_by_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.05827.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#human">Human</a></li>
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
<summary><em>Wang et al., "PredRNN: Recurrent Neural Networks For Predictive Learning Using Spatiotemporal LSTMs", NeurIPS, 2017.</em> <a href=https://papers.nips.cc/paper/6689-predrnn-recurrent-neural-networks-for-predictive-learning-using-spatiotemporal-lstms.pdf>paper</a> <a href=https://github.com/ujjax/pred-rnn>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2017_NeurIPS,
    author = "Wang, Yunbo and Long, Mingsheng and Wang, Jianmin and Gao, Zhifeng and Yu, Philip S",
    title = "{PredRNN}: Recurrent Neural Networks For Predictive Learning Using Spatiotemporal {LSTMs}",
    booktitle = "NeurIPS",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yoon et al., "Probabilistic Weather Forecasting with Deterministic Guidance-Based Diffusion Model", ECCV, 2024.</em> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04326.pdf>paper</a> <a href=https://github.com/DongGeun-Yoon/DGDM>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#weatherbench">WeatherBench</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pnw-typhoon">PNW-Typhoon</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Yoon_Probabilistic_2024_ECCV,
    author = "Yoon, Donggeun and Seo, Minseok and Kim, Doyi and Choi, Yeji and Cho, Donghyeon",
    title = "Probabilistic Weather Forecasting with Deterministic Guidance-Based Diffusion Model",
    booktitle = "ECCV",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Oh et al., "HCNAF: Hyper-Conditioned Neural Autoregressive Flow and its Application for Probabilistic Occupancy Map Forecasting", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Oh_HCNAF_Hyper-Conditioned_Neural_Autoregressive_Flow_and_its_Application_for_Probabilistic_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.08111.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mnist">MNIST</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Oh_2020_CVPR,
    author = "Oh, Geunseob and Valois, Jean-Sebastien",
    title = "{HCNAF}: Hyper-Conditioned Neural Autoregressive Flow and its Application for Probabilistic Occupancy Map Forecasting",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Srivastava_2015_ICML,
    author = "Srivastava, Nitish and Mansimov, Elman and Salakhudinov, Ruslan",
    title = "Unsupervised Learning Of Video Representations Using {LSTMs}",
    booktitle = "ICML",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=mot></a>
<details close>
<summary><l style="font-size:20px"><strong>MOT</strong></l> <a href=https://motchallenge.net/>link</a> <a href=https://arxiv.org/pdf/1504.01942.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A collection of videos from existing datasets for the purpose of object tracking
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Thakkar et al., "Adaptive human trajectory prediction via latent corridors", ECCV, 2024.</em> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/05542.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mot">MOT</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wildtrack">WILDTRACK</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#motsynth">MOTSynth</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Chen et al., "S2F2: Single-Stage Flow Forecasting for Future Multiple Trajectories Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820593.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mot">MOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fiou">FIoU</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iou">IoU</a></li>
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
<summary><em>Dendorfer et al., "Quo Vadis: Is Trajectory Forecasting the Key Towards Long-Term Multi-Object Tracking?", NeurIPS, 2022.</em> <a href=https://openreview.net/pdf?id=3r0yLLCo4fF>paper</a> <a href=https://arxiv.org/pdf/2210.07681.pdf>arxiv</a> <a href=https://github.com/dendorferpatrick/QuoVadis>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mot">MOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Dendorfer_2022_NeurIPS,
    author = "Dendorfer, Patrick and Yugay, Vladimir and Osep, Aljosa and Leal-Taix{\'e}, Laura",
    title = "{Quo Vadis}: Is Trajectory Forecasting the Key Towards Long-Term Multi-Object Tracking?",
    booktitle = "NeurIPS",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Meng et al., "Forecasting Human Trajectory from Scene History", NeurIPS, 2022.</em> <a href=https://openreview.net/pdf?id=RW-OOBU11xl>paper</a> <a href=https://arxiv.org/pdf/2210.08732.pdf>arxiv</a> <a href=https://github.com/MaKaRuiNah/SHENet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mot">MOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Meng_2022_NeurIPS,
    author = "Meng, Mancheng and Wu, Ziyan and Chen, Terrence and Cai, Xiran and Zhou, Xiang Sean and Yang, Fan and Shen, Dinggang",
    title = "Forecasting Human Trajectory from Scene History",
    booktitle = "NeurIPS",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sanchez-Matilla et al., "A Predictor Of Moving Objects For First-Person Vision", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8803140>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mot">MOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sanchez_2019_ICIP,
    author = "Sanchez-Matilla, R. and Cavallaro, A.",
    booktitle = "ICIP",
    title = "A Predictor Of Moving Objects For First-Person Vision",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Leal_2015_arxiv,
    author = "Leal-Taix\'e, Laura and Milan, Anton and Reid, Ian and Roth, Stefan and Schindler, Konrad",
    title = "Motchallenge 2015: Towards A Benchmark For Multi-Target Tracking",
    journal = "arXiv:1504.01942",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=thumos></a>
<details close>
<summary><l style="font-size:20px"><strong>THUMOS</strong></l> <a href=http://www.thumos.info/home.html>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 20K+ videos of 101 diverse action classes
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a>, <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liang et al., "Dual Motion GAN For Future-Flow Embedded Video Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Liang_Dual_Motion_GAN_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00284.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liang_2017_ICCV,
    author = "Liang, Xiaodan and Lee, Lisa and Dai, Wei and Xing, Eric P.",
    title = "Dual Motion {GAN} For Future-Flow Embedded Video Prediction",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Piergiovanni et al., "Adversarial Generative Grammars for Human Activity Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470494.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.04888.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#charades">Charades</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#map">mAP</a></li>
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
<summary><em>Zhong et al., "Unsupervised Learning For Forecasting Action Representations", ICIP, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8451428>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhong_2018_ICIP,
    author = "Zhong, Y. and Zheng, W.",
    booktitle = "ICIP",
    title = "Unsupervised Learning For Forecasting Action Representations",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Gao et al., "RED: Reinforced Encoder-Decoder Networks For Action Anticipation", BMVC, 2017.</em> <a href=http://www.bmva.org/bmvc/2017/papers/paper092/paper092.pdf>paper</a> <a href=https://arxiv.org/pdf/1707.04818.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_series">TV Series</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#map">mAP</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#cap">cAP</a></li>
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
<details close>
<summary><em>Vondrick et al., "Anticipating Visual Representations From Unlabeled Video", CVPR, 2016.</em> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Vondrick_Anticipating_Visual_Representations_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1504.08023.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Vondrick_2016_CVPR_2,
    author = "Vondrick, Carl and Pirsiavash, Hamed and Torralba, Antonio",
    title = "Anticipating Visual Representations From Unlabeled Video",
    booktitle = "CVPR",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Misc{Gorban_2015,
    author = "Gorban, A. and Idrees, H. and Jiang, Y.-G. and Roshan Zamir, A. and Laptev, I. and Shah, M. and Sukthankar, R.",
    title = "Thumos Challenge: Action Recognition With A Large Number Of Classes",
    howpublished = "\url{http://www.thumos.info/}",
    Year = "2015"
}
</pre>
</details>

</ul></details>
<a name=brain4cars></a>
<details close>
<summary><l style="font-size:20px"><strong>Brain4Cars</strong></l> <a href=https://github.com/asheshjain399/ICCV2015_Brain4Cars>link</a> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Jain_Car_That_Knows_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1504.02789.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 700 driving events using inside and outside looking cameras with annotated actions for various driving maneuvers
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, attribute, temporal segment, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kung et al., "Looking Inside Out: Anticipating Driver Intent From Videos", ICRA, 2024.</em> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10610257>paper</a> <a href=https://arxiv.org/pdf/2312.01444>arxiv</a> <a href=https://github.com/yaorong0921/Driver-Intention-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Kung_looking_2024_ICRA,
    author = "Kung, Yung-Chi and Zhang, Arthur and Wang, Junmin and Biswas, Joydeep",
    booktitle = "ICRA",
    title = "Looking Inside Out: Anticipating Driver Intent From Videos",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Jain et al., "Structural-RNN: Deep Learning On Spatio-Temporal Graphs", CVPR, 2016.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.05298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#ttm">TTM</a></li>
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
<summary><em>Jain et al., "Recurrent Neural Networks For Driver Activity Anticipation Via Sensory-Fusion Architecture", ICRA, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7487478>paper</a> <a href=https://arxiv.org/pdf/1509.05016.pdf>arxiv</a> <a href=https://github.com/asheshjain399/RNNexp>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#ttm">TTM</a></li>
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
<summary><em>Jain et al., "Car That Knows Before You Do: Anticipating Maneuvers Via Learning Temporal Driving Models", ICCV, 2015.</em> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Jain_Car_That_Knows_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1504.02789.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#ttm">TTM</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_e-i_metrics.md#fp">FP</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Jain_2015_ICCV,
    author = "Jain, Ashesh and Koppula, Hema S. and Raghavan, Bharad and Soh, Shane and Saxena, Ashutosh",
    title = "Car That Knows Before You Do: Anticipating Maneuvers Via Learning Temporal Driving Models",
    booktitle = "ICCV",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=cmu_panoptic></a>
<details close>
<summary><l style="font-size:20px"><strong>CMU Panoptic</strong></l> <a href=http://domedb.perception.cs.cmu.edu/index.html>link</a> <a href=https://openaccess.thecvf.com/content_iccv_2015/papers/Joo_Panoptic_Studio_A_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1612.03153.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A multiview group activity dataset recorded with 10 RGB-D sensors and 30+ HD views with the corresponding 3D annotations
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a>, <a href=../../papers/motion/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, multiview, 3D pose, 3D facial landmark, Transcripts</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Joo et al., "Towards Social Artificial Intelligence: Nonverbal Social Signal Prediction In A Triadic Interaction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Joo_Towards_Social_Artificial_Intelligence_Nonverbal_Social_Signal_Prediction_in_a_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.04158.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Joo_2019_CVPR,
    author = "Joo, Hanbyul and Simon, Tomas and Cikara, Mina and Sheikh, Yaser",
    title = "Towards Social Artificial Intelligence: Nonverbal Social Signal Prediction In A Triadic Interaction",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Choudhury et al., "TEMPO: Efficient Multi-View Pose Estimation, Tracking, and Forecasting", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Choudhury_TEMPO_Efficient_Multi-View_Pose_Estimation_Tracking_and_Forecasting_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2309.07910.pdf>arxiv</a> <a href=https://rccchoudhury.github.io/tempo2023/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cas">CaS</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egohumans">EgoHumans</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pcp3d">PCP3D</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Choudhury_2023_ICCV,
    author = "Choudhury, Rohan and Kitani, Kris M. and Jeni, Laszlo A.",
    title = "TEMPO: Efficient Multi-View Pose Estimation, Tracking, and Forecasting",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "Multi-Person 3D Motion Prediction with Multi-Range Transformers", NeurIPS, 2021.</em> <a href=https://papers.nips.cc/paper/2021/file/2fd5d41ec6cfab47e32164d5624269b1-Paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2111.12073.pdf>arxiv</a> <a href=https://github.com/jiashunwang/MRT>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mupots-3d">MuPoTS-3D</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2021_NeurIPS,
    author = "Wang, Jiashun and Xu, Huazhe and Narasimhan, Medhini and Wang, Xiaolong",
    booktitle = "NeurIPS",
    title = "Multi-Person {3D} Motion Prediction with Multi-Range Transformers",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yasar et al., "A Scalable Approach to Predict Multi-Agent Motion for Human-Robot Collaboration", RAL, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9353218>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth-hrc">KTH-HRC</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#utd-mhad">UTD-MHAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Yasar_2021_RAL,
    author = "Yasar, Mohammad Samin and Iqbal, Tariq",
    journal = "RAL",
    title = "A Scalable Approach to Predict Multi-Agent Motion for Human-Robot Collaboration",
    year = "2021",
    volume = "6",
    number = "2",
    pages = "1686-1693"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Joo_2015_ICCV_2,
    author = "Joo, Hanbyul and Liu, Hao and Tan, Lei and Gui, Lin and Nabbe, Bart and Matthews, Iain and Kanade, Takeo and Nobuhara, Shohei and Sheikh, Yaser",
    title = "Panoptic Studio: A Massively Multiview System For Social Motion Capture",
    booktitle = "ICCV",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=sysu_3dhoi></a>
<details close>
<summary><l style="font-size:20px"><strong>SYSU 3DHOI</strong></l> <a href=http://www.isee-ai.cn/~hujianfang/ProjectJOULE.html>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Hu_Jointly_Learning_Heterogeneous_2015_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 12 simple activities in 480 video clips with depth maps
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Object interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Foo et al., "ERA: Expert Retrieval and Assembly for Early Action Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940657.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.09675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Foo_2022_ECCV,
    author = "Foo, Lin Geng and Li, Tianjiao and Rahmani, Hossein and Ke, Qiuhong and Liu, Jun",
    title = "{ERA}: Expert Retrieval and Assembly for Early Action Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "Progressive Teacher-Student Learning For Early Action Prediction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Progressive_Teacher-Student_Learning_for_Early_Action_Prediction_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2019_CVPR,
    author = "Wang, Xionghui and Hu, Jian-Fang and Lai, Jian-Huang and Zhang, Jianguo and Zheng, Wei-Shi",
    title = "Progressive Teacher-Student Learning For Early Action Prediction",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Hu et al., "Real-Time RGB-D Activity Prediction By Soft Regression", ECCV, 2016.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46448-0_17>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#orgbd">ORGBD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2016_ECCV,
    author = "Hu, Jian-Fang and Zheng, Wei-Shi and Ma, Lianyang and Wang, Gang and Lai, Jianhuang",
    editor = "Leibe, Bastian and Matas, Jiri and Sebe, Nicu and Welling, Max",
    title = "Real-Time {RGB-D} Activity Prediction By Soft Regression",
    booktitle = "ECCV",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Hu_2015_CVPR,
    author = "Hu, Jian-Fang and Zheng, Wei-Shi and Lai, Jianhuang and Zhang, Jianguo",
    title = "Jointly Learning Heterogeneous Features For {RGB-D} Activity Recognition",
    booktitle = "CVPR",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=activitynet></a>
<details close>
<summary><l style="font-size:20px"><strong>ActivityNet</strong></l> <a href=http://activity-net.org/>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Heilbron_ActivityNet_A_Large-Scale_2015_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 648 hours of video with 100 videos per 200 different activity classes
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity Label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Rothfuss et al., "Deep Episodic Memory: Encoding, Recalling, and Predicting Episodic Experiences for Robot Action Execution", RAL, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8421022>paper</a> <a href=https://arxiv.org/pdf/1801.04134.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#activitynet">ActivityNet</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#20bn">20BN</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Rothfuss_2018_RAL,
    author = "Rothfuss, J. and Ferreira, F. and Aksoy, E. E. and Zhou, Y. and Asfour, T.",
    journal = "RAL",
    title = "Deep Episodic Memory: Encoding, Recalling, and Predicting Episodic Experiences for Robot Action Execution",
    year = "2018",
    volume = "3",
    number = "4",
    pages = "4007-4014"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Hosseinzadeh et al., "Video Captioning of Future Frames", WACV, 2021.</em> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Hosseinzadeh_Video_Captioning_of_Future_Frames_WACV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#activitynet">ActivityNet</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#swag">SWAG</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#cider">CIDEr</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#rouge-l">ROUGE-L</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#meteor">METEOR</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#bleu@n">BLEU@N</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Caba_2015_CVPR,
    author = "Fabian Caba Heilbron, Victor Escorcia, Bernard Ghanem and Niebles, Juan Carlos",
    title = "{ActivityNet}: A Large-Scale Video Benchmark for Human Activity Understanding",
    booktitle = "CVPR",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=utd-mhad></a>
<details close>
<summary><l style="font-size:20px"><strong>UTD-MHAD</strong></l> <a href=https://personal.utdallas.edu/~kehtar/UTD-MHAD.html>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/7350781>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 27 actions performed by 8 subjects collected using Kinect sensor.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/motion/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Depth, 3D pose, Inertial sensor</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yasar et al., "VADER: Vector-Quantized Generative Adversarial Network for Motion Prediction", IROS, 2023.</em> <a href=https://ieeexplore.ieee.org/document/10342324>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth-hrc">KTH-HRC</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#utd-mhad">UTD-MHAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@INPROCEEDINGS{Yasar_2023_IROS,
    author = "Yasar, Mohammad Samin and Iqbal, Tariq",
    booktitle = "IROS",
    title = "VADER: Vector-Quantized Generative Adversarial Network for Motion Prediction",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yasar et al., "A Scalable Approach to Predict Multi-Agent Motion for Human-Robot Collaboration", RAL, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9353218>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth-hrc">KTH-HRC</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#utd-mhad">UTD-MHAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Yasar_2021_RAL,
    author = "Yasar, Mohammad Samin and Iqbal, Tariq",
    journal = "RAL",
    title = "A Scalable Approach to Predict Multi-Agent Motion for Human-Robot Collaboration",
    year = "2021",
    volume = "6",
    number = "2",
    pages = "1686-1693"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Chen_2015_ICIP,
    author = "Chen, Chen and Jafari, Roozbeh and Kehtarnavaz, Nasser",
    booktitle = "ICIP",
    title = "{UTD-MHAD}: A Multimodal Dataset for Human Action Recognition Utilizing a Depth Camera and a Wearable Inertial Sensor",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=wnp></a>
<details close>
<summary><l style="font-size:20px"><strong>Watch-n-Push (WnP)</strong></l> <a href=http://watchnpatch.cs.cornell.edu/>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Wu_Watch-n-Patch_Unsupervised_Understanding_2015_CVPR_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1603.03541.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 458 videos of 21 daily actions in office and kitchen environments recorded using a Kinect V2 sensor
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D pose, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kataoka et al., "Recognition Of Transitional Action For Short-Term Action Prediction Using Discriminative Temporal CNN Feature", BMVC, 2016.</em> <a href=http://www.bmva.org/bmvc/2016/papers/paper012/paper012.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wnp">WnP</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#utka">UTKA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kataoka_2016_BMVC,
    author = "Kataoka, Hirokatsu and Miyashita, Yudai and Hayashi, Masaki and Iwata, Kenji and Satoh, Yutaka",
    title = "Recognition Of Transitional Action For Short-Term Action Prediction Using Discriminative Temporal {CNN} Feature",
    year = "2016",
    booktitle = "BMVC"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Park et al., "HMPO: Human Motion Prediction in Occluded Environments for Safe Motion Planning", RSS, 2020.</em> <a href=http://www.roboticsproceedings.org/rss16/p051.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.00424.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wnp">WnP</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#utka">UTKA</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#occlusion_mocap">Occlusion MoCap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Park_2020_RSS,
    AUTHOR = "Park, Jaesung and Manocha, Dinesh",
    TITLE = "{HMPO}: Human Motion Prediction in Occluded Environments for Safe Motion Planning",
    BOOKTITLE = "RSS",
    YEAR = "2020"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Wu_2015_CVPR,
    author = "Wu, Chenxia and Zhang, Jiemi and Savarese, Silvio and Saxena, Ashutosh",
    title = "{Watch-N-Patch}: Unsupervised Understanding Of Actions And Relations",
    booktitle = "CVPR",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=wider></a>
<details close>
<summary><l style="font-size:20px"><strong>WIDER</strong></l> <a href=http://yjxiong.me/event_recog/WIDER/>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Xiong_Recognize_Complex_Events_2015_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A complex event dataset of 61 event categories in 50K+ images
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Safaei et al., "Still Image Action Recognition By Predicting Spatial-Temporal Pixel Evolution", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8658386>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#willow_action">Willow Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wider">WIDER</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#stanford-40">Stanford-40</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bu_action">BU Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#map">mAP</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Xiong_2015_CVPR,
    author = "Xiong, Yuanjun and Zhu, Kai and Lin, Dahua and Tang, Xiaoou",
    title = "Recognize Complex Events From Static Images By Fusing Deep Channels",
    booktitle = "CVPR",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=gtea_gaze+></a>
<details close>
<summary><l style="font-size:20px"><strong>Georgia Tech Egocentric Activity Gaze+ (GTEA Gaze+)</strong></l> <a href=http://www.cbi.gatech.edu/fpv/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2015/papers/Li_Delving_Into_Egocentric_2015_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An egocentric dataset of 37 videos of 7 cooking activities recorded from 26 subjects with the corresponding gaze tracking information
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, gaze, mask, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Shen et al., "Egocentric Activity Prediction Via Event Modulated Attention", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Shen_Egocentric_Activity_Prediction_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#gtea_gaze">GTEA Gaze</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#gtea_gaze+">GTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shen_2018_ECCV,
    author = "Shen, Yang and Ni, Bingbing and Li, Zefan and Zhuang, Ning",
    title = "Egocentric Activity Prediction Via Event Modulated Attention",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Li_2015_CVPR,
    author = "Li, Yin and Ye, Zhefan and Rehg, James M",
    title = "Delving Into Egocentric Actions",
    booktitle = "CVPR",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=fppa></a>
<details close>
<summary><l style="font-size:20px"><strong>First Person Personalized Activities (FPPA)</strong></l> <a href=http://bvision11.cs.unc.edu/bigpen/yipin/ICCV2015/prediction_webpage/Prediction.html>link</a> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Zhou_Temporal_Perception_and_ICCV_2015_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An egocentric dataset of 5 daily activities, such as drinking water, using a fridge, etc.,  consists of 591 video clips recorded at 30fps
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhou et al., "Temporal Perception And Prediction In Ego-Centric Video", ICCV, 2015.</em> <a href=https://openaccess.thecvf.com/content_iccv_2015/papers/Zhou_Temporal_Perception_and_ICCV_2015_paper.pdf>paper</a> <a href=https://github.com/aditya7874/Activity-Prediction-in-EgoCentric-Videos>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#fppa">FPPA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhou_2015_ICCV,
    author = "Zhou, Yipin and Berg, Tamara L.",
    title = "Temporal Perception And Prediction In Ego-Centric Video",
    booktitle = "ICCV",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Zhou_2015_ICCV,
    author = "Zhou, Yipin and Berg, Tamara L.",
    title = "Temporal Perception And Prediction In Ego-Centric Video",
    booktitle = "ICCV",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=sun_rgb-d></a>
<details close>
<summary><l style="font-size:20px"><strong>SUN RGB-D</strong></l> <a href=http://rgbd.cs.princeton.edu/>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Song_SUN_RGB-D_A_2015_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 10K RGB-D images of indoor environments with the corresponding 2D and 3D annotations
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D bounding box, object class</li>
<li><em><strong>Task:</strong></em> Place</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Mottaghi et al., "What Happens If... Learning To Predict The Effect Of Forces In Images", ECCV, 2016.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46493-0_17>paper</a> <a href=https://arxiv.org/pdf/1603.05600.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sun_rgb-d">SUN RGB-D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#pcp">PCP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mottaghi_2016_ECCV,
    author = "Mottaghi, Roozbeh and Rastegari, Mohammad and Gupta, Abhinav and Farhadi, Ali",
    editor = "Leibe, Bastian and Matas, Jiri and Sebe, Nicu and Welling, Max",
    title = "What Happens If... Learning To Predict The Effect Of Forces In Images",
    booktitle = "ECCV",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Song_2015_CVPR_2,
    author = "Song, Yale and Vallmitjana, J. and Stent, A. and Jaimes, A.",
    booktitle = "CVPR",
    title = "{TVSum}: Summarizing Web Videos Using Titles",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=amazon></a>
<details close>
<summary><l style="font-size:20px"><strong>Amazon</strong></l> <a href=http://jmcauley.ucsd.edu/data/amazon/index_2014.html>link</a> <a href=https://dl.acm.org/doi/abs/10.1145/2766462.2767755>paper</a> <a href=https://arxiv.org/pdf/1506.04757.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 142M+ product reviews from Amazon with corresponding metadata including price, brand, descriptions, category information, etc.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Features, attribute, text</li>
<li><em><strong>Task:</strong></em> Fashion</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Al-Halah et al., "Fashion Forward: Forecasting Visual Style In Fashion", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Al-Halah_Fashion_Forward_Forecasting_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.06394.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amazon">Amazon</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#mape">MAPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Al-Halah_2017_ICCV,
    author = "Al-Halah, Ziad and Stiefelhagen, Rainer and Grauman, Kristen",
    title = "Fashion Forward: Forecasting Visual Style In Fashion",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Mcauley_2015_CRDIR,
    author = "McAuley, Julian and Targett, Christopher and Shi, Qinfeng and Van Den Hengel, Anton",
    title = "Image-Based Recommendations On Styles And Substitutes",
    booktitle = "SIGIR",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=wbhm></a>
<details close>
<summary><l style="font-size:20px"><strong>Whole-Body Human Motion (WBHM)</strong></l> <a href=https://motion-database.humanoids.kit.edu/>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/7251476>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A human motion dataset consists of 2.4K+ experiments using 224 subjects and 135 objects
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/motion/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, 3D Pose</li>
<li><em><strong>Task:</strong></em> Pose</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Corona et al., "Context-Aware Human Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Corona_Context-Aware_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.03419.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wbhm">WBHM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Corona_2020_CVPR,
    author = "Corona, Enric and Pumarola, Albert and Alenya, Guillem and Moreno-Noguer, Francesc",
    title = "Context-Aware Human Motion Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@inproceedings{Mandery_2015_ICAR,
    author = "Mandery, Christian and Terlemez, Omer and Do, Martin and Vahrenkamp, Nikolaus and Asfour, Tamim",
    title = "The {KIT} whole-body human motion database",
    booktitle = "ICAR",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=occlusion_mocap></a>
<details close>
<summary><l style="font-size:20px"><strong>Occlusion MoCap</strong></l> <a href=https://team.inria.fr/larsen/software/datasets/>link</a> <a href=https://ieeexplore.ieee.org/document/7354068>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
The dataset of 12 RGB-D video sequences of a person moving in front of a Kinect in a scene with obstacles
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/motion/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D Pose</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Park et al., "HMPO: Human Motion Prediction in Occluded Environments for Safe Motion Planning", RSS, 2020.</em> <a href=http://www.roboticsproceedings.org/rss16/p051.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.00424.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wnp">WnP</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#utka">UTKA</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#occlusion_mocap">Occlusion MoCap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Park_2020_RSS,
    AUTHOR = "Park, Jaesung and Manocha, Dinesh",
    TITLE = "{HMPO}: Human Motion Prediction in Occluded Environments for Safe Motion Planning",
    BOOKTITLE = "RSS",
    YEAR = "2020"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Dib_IROS_2015,
    author = "Dib, Abdallah and Charpillet, François",
    title = "Pose Estimation For A Partially Observable Human Body From {RGB-D} Camera",
    booktitle = "IROS",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=mbi-1m></a>
<details close>
<summary><l style="font-size:20px"><strong>MicroBlog-Images (MBI-1M)</strong></l> <a href=http://academic.mywebsiteontheinternet.com/data/>link</a> <a href=https://dl.acm.org/doi/abs/10.1145/2671188.2749405>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An activity dataset of 1M images and the content of the corresponding tweets collected in years 2013-14
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, attribute, text</li>
<li><em><strong>Task:</strong></em> Tweet</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Wang et al., "Retweet Wars: Tweet Popularity Prediction Via Dynamic Multimodal Regression", WACV, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8354308>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mbi-1m">MBI-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#mape">MAPE</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#src">SRC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2018_WACV,
    author = "Wang, K. and Bansal, M. and Frahm, J.",
    booktitle = "WACV",
    title = "Retweet Wars: Tweet Popularity Prediction Via Dynamic Multimodal Regression",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Cappallo_2015_ICMR,
    author = "Cappallo, Spencer and Mensink, Thomas and Snoek, Cees GM",
    title = "Latent Factors Of Visual Popularity Prediction",
    booktitle = "ICMR",
    year = "2015"
}
</pre>
</details>

</ul></details>
</ul><h2>2014</h2>
<ul><a name=human3.6m></a>
<details close>
<summary><l style="font-size:20px"><strong>Human3.6M</strong></l> <a href=http://vision.imar.ro/human3.6m/description.php>link</a> <a href=https://ieeexplore.ieee.org/document/6682899>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale dataset of 3D human poses with 3M+ images captured using 11 professional actors in 17 scenarios, such as discussion, smoking, taking photo, etc.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a>, <a href=../../papers/action/action_papers.md#top>Action prediction<application></a>, <a href=../../papers/motion/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Shrivastava et al., "Video Prediction by Modeling Videos as Continuous Multi-Dimensional Processes", CVPR, 2024.</em> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Shrivastava_Video_Prediction_by_Modeling_Videos_as_Continuous_Multi-Dimensional_Processes_CVPR_2024_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shrivastava_Video_2024_CVPR,
    author = "Shrivastava, Gaurav and Shrivastava, Abhinav",
    title = "Video Prediction by Modeling Videos as Continuous Multi-Dimensional Processes",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chang et al., "STRPM: A Spatiotemporal Residual Predictive Model for High-Resolution Video Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Chang_STRPM_A_Spatiotemporal_Residual_Predictive_Model_for_High-Resolution_Video_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.16084.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf_sports">UCF Sports</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sjtu4k">SJTU4K</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chang_2022_CVPR,
    author = "Chang, Zheng and Zhang, Xinfeng and Wang, Shanshe and Ma, Siwei and Gao, Wen",
    title = "{STRPM}: A Spatiotemporal Residual Predictive Model for High-Resolution Video Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Gao et al., "SimVP: Simpler Yet Better Video Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Gao_SimVP_Simpler_Yet_Better_Video_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2206.05099.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#taxi_bj">Taxi BJ</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2022_CVPR,
    author = "Gao, Zhangyang and Tan, Cheng and Wu, Lirong and Li, Stan Z.",
    title = "{SimVP}: Simpler Yet Better Video Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Pourheydari et al., "TaylorSwiftNet: Taylor Driven Temporal Modeling for Swift Future Frame Prediction", BMVC, 2022.</em> <a href=https://bmvc2022.mpi-inf.mpg.de/0389.pdf>paper</a> <a href=https://arxiv.org/pdf/2110.14392.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#taxi_bj">Taxi BJ</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sst">SST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Pourheydari_2022_BMVC,
    author = "Pourheydari, Mohammad Saber and Bahrami, Emad and Fayyaz, Mohsen and Francesca, Gianpiero and Noroozi, Mehdi and Gall, Jürgen",
    title = "{TaylorSwiftNet}: Taylor Driven Temporal Modeling for Swift Future Frame Prediction",
    booktitle = "BMVC",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "Towards Unified Multi-Excitation for Unsupervised Video Prediction", BMVC, 2022.</em> <a href=https://bmvc2022.mpi-inf.mpg.de/0587.pdf>paper</a> <a href=https://github.com/captaincj/UMENet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#taxi_bj">Taxi BJ</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sst">SST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2022_BMVC,
    author = "Wang, Junyan and Likun, Qin and Zhang, Peng and Long, Yang and Hu, Bingzhang and Pagnucco, Maurice and Wang, Shizheng and Song, Yang",
    title = "Towards Unified Multi-Excitation for Unsupervised Video Prediction",
    booktitle = "BMVC",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Lee et al., "Video Prediction Recalling Long-Term Motion Context via Memory Alignment Learning", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Lee_Video_Prediction_Recalling_Long-Term_Motion_Context_via_Memory_Alignment_Learning_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2104.00924.pdf>arxiv</a> <a href=https://github.com/sangmin-git/LMC-Memory>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lee_2021_CVPR,
    author = "Lee, Sangmin and Kim, Hak Gu and Choi, Dae Hwi and Kim, Hyung-Il and Ro, Yong Man",
    title = "Video Prediction Recalling Long-Term Motion Context via Memory Alignment Learning",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wu et al., "Greedy Hierarchical Variational Autoencoders for Large-Scale Video Prediction", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Wu_Greedy_Hierarchical_Variational_Autoencoders_for_Large-Scale_Video_Prediction_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2103.04174.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#robonet">RoboNet</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#human">Human</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wu_2021_CVPR,
    author = "Wu, Bohan and Nair, Suraj and Martin-Martin, Roberto and Fei-Fei, Li and Finn, Chelsea",
    title = "Greedy Hierarchical Variational Autoencoders for Large-Scale Video Prediction",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wu et al., "MotionRNN: A Flexible Model for Video Prediction With Spacetime-Varying Motions", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Wu_MotionRNN_A_Flexible_Model_for_Video_Prediction_With_Spacetime-Varying_Motions_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2103.02243.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_a-d_metrics.md#csi">CSI</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#gdl">GDL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wu_2021_CVPR_2,
    author = "Wu, Haixu and Yao, Zhiyu and Wang, Jianmin and Long, Mingsheng",
    title = "{MotionRNN}: A Flexible Model for Video Prediction With Spacetime-Varying Motions",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Gao et al., "Accurate Grid Keypoint Learning for Efficient Video Prediction", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636874>paper</a> <a href=https://arxiv.org/pdf/2107.13170.pdf>arxiv</a> <a href=https://github.com/xjgaocs/Grid-Keypoint-Learning>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jigsaws">JIGSAWS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2021_IROS,
    author = "Gao, Xiaojie and Jin, Yueming and Dou, Qi and Fu, Chi-Wing and Heng, Pheng-Ann",
    booktitle = "IROS",
    title = "Accurate Grid Keypoint Learning for Efficient Video Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Le et al., "Disentangling Physical Dynamics From Unknown Factors for Unsupervised Video Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Le_Guen_Disentangling_Physical_Dynamics_From_Unknown_Factors_for_Unsupervised_Video_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.01460.pdf>arxiv</a> <a href=https://github.com/vincent-leguen/PhyDNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#taxi_bj">Taxi BJ</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sst">SST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Guen_2020_CVPR,
    author = "Le Guen, Vincent and Thome, Nicolas",
    title = "Disentangling Physical Dynamics From Unknown Factors for Unsupervised Video Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Franceschi et al., "Stochastic Latent Residual Video Prediction", ICML, 2020.</em> <a href=http://proceedings.mlr.press/v119/franceschi20a/franceschi20a.pdf>paper</a> <a href=https://arxiv.org/pdf/2002.09219.pdf>arxiv</a> <a href=https://github.com/edouardelasalles/srvp>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Franceschi_2020_ICML,
    author = {Franceschi, Jean-Yves and Delasalles, Edouard and Chen, Micka{\"e}l and Lamprier, Sylvain and Gallinari, Patrick},
    title = "Stochastic Latent Residual Video Prediction",
    booktitle = "ICML",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yao et al., "Unsupervised Transfer Learning for Spatiotemporal Predictive Networks", ICML, 2020.</em> <a href=http://proceedings.mlr.press/v119/yao20a/yao20a.pdf>paper</a> <a href=https://arxiv.org/pdf/2009.11763.pdf>arxiv</a> <a href=https://github.com/thuml/transferable-memory>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#weizmann">Weizmann</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yao_2020_ICML,
    author = "Yao, Zhiyu and Wang, Yunbo and Long, Mingsheng and Wang, Jianmin",
    title = "Unsupervised Transfer Learning for Spatiotemporal Predictive Networks",
    booktitle = "ICML",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Structure Preserving Video Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers_backup/Xu_Structure_Preserving_Video_CVPR_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2018_CVPR,
    author = "Xu, Jingwei and Ni, Bingbing and Li, Zefan and Cheng, Shuo and Yang, Xiaokang",
    title = "Structure Preserving Video Prediction",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Byeon et al., "Contextvp: Fully Context-Aware Video Prediction", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Wonmin_Byeon_ContextVP_Fully_Context-Aware_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Byeon_2018_ECCV,
    author = "Byeon, Wonmin and Wang, Qin and Kumar Srivastava, Rupesh and Koumoutsakos, Petros",
    title = "Contextvp: Fully Context-Aware Video Prediction",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Cai et al., "Deep Video Generation, Prediction And Completion Of Human Action Sequences", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Chunyan_Bai_Deep_Video_Generation_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1711.08682.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cai_2018_ECCV,
    author = "Cai, Haoye and Bai, Chunyan and Tai, Yu-Wing and Tang, Chi-Keung",
    title = "Deep Video Generation, Prediction And Completion Of Human Action Sequences",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Video Prediction Via Selective Sampling", NeurIPS, 2018.</em> <a href=https://papers.nips.cc/paper/7442-video-prediction-via-selective-sampling.pdf>paper</a> <a href=https://github.com/xjwxjw/VPSS>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2018_NeurIPS,
    author = "Xu, Jingwei and Ni, Bingbing and Yang, Xiaokang",
    title = "Video Prediction Via Selective Sampling",
    booktitle = "NeurIPS",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wichers et al., "Hierarchical Long-Term Video Prediction Without Supervision", ICML, 2018.</em> <a href=http://proceedings.mlr.press/v80/wichers18a.html>paper</a> <a href=https://arxiv.org/pdf/1806.04768.pdf>arxiv</a> <a href=https://bit.ly/2HqiHqx>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#human">Human</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wichers_2018_ICML,
    author = "Wichers, Nevan and Villegas, Ruben and Erhan, Dumitru and Lee, Honglak",
    title = "Hierarchical Long-Term Video Prediction Without Supervision",
    booktitle = "ICML",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ying et al., "Better Guider Predicts Future Better: Difference Guided Generative Adversarial Networks", ACCV, 2018.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20876-9_18>paper</a> <a href=https://arxiv.org/pdf/1901.01649.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ying_2018_ACCV,
    author = "Ying, Guohao and Zou, Yingtian and Wan, Lin and Hu, Yiming and Feng, Jiashi",
    editor = "Jawahar, C.V. and Li, Hongdong and Mori, Greg and Schindler, Konrad",
    title = "Better Guider Predicts Future Better: Difference Guided Generative Adversarial Networks",
    booktitle = "ACCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ji et al., "Dynamic Visual Sequence Prediction With Motion Flow Networks", WACV, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8354223>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ji_2018_WACV,
    author = "Ji, D. and Wei, Z. and Dunn, E. and Frahm, J. M.",
    booktitle = "WACV",
    title = "Dynamic Visual Sequence Prediction With Motion Flow Networks",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Villegas et al., "Learning To Generate Long-Term Future Via Hierarchical Prediction", ICML, 2017.</em> <a href=http://proceedings.mlr.press/v70/villegas17a.html>paper</a> <a href=https://arxiv.org/pdf/1704.05831.pdf>arxiv</a> <a href=https://github.com/rubenvillegas/icml2017hierchvid>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#human">Human</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Villegas_2017_ICML,
    author = "Villegas, Ruben and Yang, Jimei and Zou, Yuliang and Sohn, Sungryull and Lin, Xunyu and Lee, Honglak",
    title = "Learning To Generate Long-Term Future Via Hierarchical Prediction",
    booktitle = "ICML",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Finn et al., "Unsupervised Learning For Physical Interaction Through Video Prediction", NeurIPS, 2016.</em> <a href=https://papers.nips.cc/paper/6161-unsupervised-learning-for-physical-interaction-through-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1605.07157.pdf>arxiv</a> <a href=https://github.com/tensorflow/models/tree/master/research/video_prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Finn_2016_NeurIPS,
    author = "Finn, Chelsea and Goodfellow, Ian and Levine, Sergey",
    title = "Unsupervised Learning For Physical Interaction Through Video Prediction",
    booktitle = "NeurIPS",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Mascaro et al., "Intention-Conditioned Long-Term Human Egocentric Action Anticipation", WACV, 2023.</em> <a href=https://openaccess.thecvf.com/content/WACV2023/papers/Mascaro_Intention-Conditioned_Long-Term_Human_Egocentric_Action_Anticipation_WACV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#ego4d">Ego4D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_e-i_metrics.md#eid">EiD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mascaro_2023_WACV,
    author = "Mascaro, Esteve Valls and Ahn, Hyemin and Lee, Dongheui",
    title = "Intention-Conditioned Long-Term Human Egocentric Action Anticipation",
    booktitle = "WACV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Butepage et al., "Deep Representation Learning For Human Motion Prediction And Classification", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Butepage_Deep_Representation_Learning_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1702.07486.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Butepage_2017_CVPR,
    author = "Butepage, Judith and Black, Michael J. and Kragic, Danica and Kjellstrom, Hedvig",
    title = "Deep Representation Learning For Human Motion Prediction And Classification",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Eltouny et al., "DE-TGN: Uncertainty-Aware Human Motion Forecasting Using Deep Ensembles", RAL, 2024.</em> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10409503>paper</a> <a href=https://arxiv.org/pdf/2307.03610>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Mahdavian et al., "STPOTR: Simultaneous Human Trajectory and Pose Prediction Using a Non-Autoregressive Transformer for Robot Follow-Ahead", ICRA, 2023.</em> <a href=https://ieeexplore.ieee.org/document/10160538>paper</a> <a href=https://arxiv.org/pdf/2209.07600.pdf>arxiv</a> <a href=https://github.com/mmahdavian/STPOTR>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Nikdel et al., "DMMGAN: Diverse Multi Motion Prediction of 3D Human Joints using Attention-Based Generative Adversarial Network", ICRA, 2023.</em> <a href=https://ieeexplore.ieee.org/document/10160401>paper</a> <a href=https://arxiv.org/pdf/2209.09124.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Sun et al., "MoML: Online Meta Adaptation for 3D Human Motion Prediction", CVPR, 2024.</em> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Sun_MoML_Online_Meta_Adaptation_for_3D_Human_Motion_Prediction_CVPR_2024_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_MoML_2024_CVPR,
    author = "Sun, Xiaoning and Sun, Huaijiang and Li, Bin and Wei, Dong and Li, Weiqing and Lu, Jianfeng",
    title = "MoML: Online Meta Adaptation for 3D Human Motion Prediction",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chen et al., "Rethinking Human Motion Prediction with Symplectic Integral", CVPR, 2024.</em> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_Rethinking_Human_Motion_Prediction_with_Symplectic_Integral_CVPR_2024_paper.pdf>paper</a> <a href=https://github.com/adamlyu789/SINN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_Rethinking_2024_CVPR,
    author = "Chen, Haipeng and Lyu, Kedi and Liu, Zhenguang and Yin, Yifang and Yang, Xun and Lyu, Yingda",
    title = "Rethinking Human Motion Prediction with Symplectic Integral",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wei et al., "NeRMo: Learning Implicit Neural Representations for 3D Human Motion Prediction", ECCV, 2024.</em> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06076.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Wei_Nermo_2024_ECCV,
    author = "Wei, Dong and Sun, Huaijiang and Sun, Xiaoning and Hu, Shengxiang",
    title = "NeRMo: Learning Implicit Neural Representations for 3D Human Motion Prediction",
    booktitle = "ECCV",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sun et al., "CoMusion: Towards Consistent Stochastic Human Motion Prediction via Motion Diffusion", ECCV, 2024.</em> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/07969.pdf>paper</a> <a href=https://arxiv.org/pdf/2305.12554>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fid">FID</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#cmd">CMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Sun_Comusion_2024_ECCV,
    author = "Sun, Jiarui and Chowdhary, Girish",
    title = "CoMusion: Towards Consistent Stochastic Human Motion Prediction via Motion Diffusion",
    booktitle = "ECCV",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xiao et al., "Multi-person Pose Forecasting with Individual Interaction Perceptron and Prior Learning", ECCV, 2024.</em> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/02808.pdf>paper</a> <a href=https://github.com/ArcticPole/IAFormer>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#chi3d">CHI3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#jpe">JPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ape">APE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Xiao_Multi_2024_ECCV,
    author = "Xiao, Peng and Xie, Yi and Xu, Xuemiao and Chen, Weihong and Zhang, Huaidong",
    title = "Multi-person Pose Forecasting with Individual Interaction Perceptron and Prior Learning",
    booktitle = "ECCV",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Cui et al., "Human Motion Forecasting in Dynamic Domain Shifts: A Homeostatic Continual Test-Time Adaptation Framework", ECCV, 2024.</em> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04599.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#grab">GRAB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Cui_Human_2024_ECCV,
    author = "Cui, Qiongjie and Sun, Huaijiang and Li, Weiqing and Lu, Jianfeng and Li, Bin",
    title = "Human Motion Forecasting in Dynamic Domain Shifts: A Homeostatic Continual Test-Time Adaptation Framework",
    booktitle = "ECCV",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Learning semantic latent directions for accurate and controllable human motion prediction", ECCV, 2024.</em> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/03098.pdf>paper</a> <a href=https://arxiv.org/pdf/2407.11494>arxiv</a> <a href=https://github.com/GuoweiXu368/SLD-HMP/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmade">MMADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmfde">MMFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Xu_Learning_2024_ECCV,
    author = "Xu, Guowei and Tao, Jiale and Li, Wen and Duan, Lixin",
    title = "Learning semantic latent directions for accurate and controllable human motion prediction",
    booktitle = "ECCV",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Tian et al., "TransFusion: A Practical and Effective Transformer-Based Diffusion Model for 3D Human Motion Prediction", RAL, 2024.</em> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10530938>paper</a> <a href=https://github.com/sibotian96/TransFusion>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmade">MMADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmfde">MMFDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#adp">ADP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Tian_TransFusion_2024_RAL,
    author = "Tian, Sibo and Zheng, Minghui and Liang, Xiao",
    journal = "RAL",
    title = "TransFusion: A Practical and Effective Transformer-Based Diffusion Model for 3D Human Motion Prediction",
    year = "2024",
    volume = "9",
    number = "7",
    pages = "6232-6239"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Gao et al., "Decompose More and Aggregate Better: Two Closer Looks at Frequency Representation Learning for Human Motion Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Gao_Decompose_More_and_Aggregate_Better_Two_Closer_Looks_at_Frequency_CVPR_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2023_CVPR,
    author = "Gao, Xuehao and Du, Shaoyi and Wu, Yang and Yang, Yang",
    title = "Decompose More and Aggregate Better: Two Closer Looks at Frequency Representation Learning for Human Motion Prediction",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sun et al., "DeFeeNet: Consecutive 3D Human Motion Prediction With Deviation Feedback", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Sun_DeFeeNet_Consecutive_3D_Human_Motion_Prediction_With_Deviation_Feedback_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2304.04496.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#babel">BABEL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2023_CVPR,
    author = "Sun, Xiaoning and Sun, Huaijiang and Li, Bin and Wei, Dong and Li, Weiqing and Lu, Jianfeng",
    title = "DeFeeNet: Consecutive 3D Human Motion Prediction With Deviation Feedback",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Uncovering the Missing Pattern: Unified Framework Towards Trajectory Imputation and Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Xu_EqMotion_Equivariant_Multi-Agent_Motion_Prediction_With_Invariant_Interaction_Reasoning_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.10876.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/EqMotion>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
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
<summary><em>Barquero et al., "BeLFusion: Latent Diffusion for Behavior-Driven Human Motion Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Barquero_BeLFusion_Latent_Diffusion_for_Behavior-Driven_Human_Motion_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2211.14304.pdf>arxiv</a> <a href=https://barquerogerman.github.io/BeLFusion/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmade">MMADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmfde">MMFDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fid">FID</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#cmd">CMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Barquero_2023_ICCV,
    author = "Barquero, German and Escalera, Sergio and Palmero, Cristina",
    title = "BeLFusion: Latent Diffusion for Behavior-Driven Human Motion Prediction",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Choudhury et al., "TEMPO: Efficient Multi-View Pose Estimation, Tracking, and Forecasting", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Choudhury_TEMPO_Efficient_Multi-View_Pose_Estimation_Tracking_and_Forecasting_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2309.07910.pdf>arxiv</a> <a href=https://rccchoudhury.github.io/tempo2023/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cas">CaS</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egohumans">EgoHumans</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pcp3d">PCP3D</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Choudhury_2023_ICCV,
    author = "Choudhury, Rohan and Kitani, Kris M. and Jeni, Laszlo A.",
    title = "TEMPO: Efficient Multi-View Pose Estimation, Tracking, and Forecasting",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Cui et al., "Test-time Personalizable Forecasting of 3D Human Poses", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Cui_Test-time_Personalizable_Forecasting_of_3D_Human_Poses_ICCV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#grab">GRAB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpble">MPBLE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#p-mpjpe">P-MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cui_2023_ICCV,
    author = "Cui, Qiongjie and Sun, Huaijiang and Lu, Jianfeng and Li, Weiqing and Li, Bin and Yi, Hongwei and Wang, Haofan",
    title = "Test-time Personalizable Forecasting of 3D Human Poses",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xing et al., "HDG-ODE: A Hierarchical Continuous-Time Model for Human Pose Forecasting", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Xing_HDG-ODE_A_Hierarchical_Continuous-Time_Model_for_Human_Pose_Forecasting_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.05859.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mupots-3d">MuPoTS-3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xing_2023_ICCV,
    author = "Xing, Yucheng and Wang, Xin",
    title = "HDG-ODE: A Hierarchical Continuous-Time Model for Human Pose Forecasting",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chen et al., "HumanMAC: Masked Motion Completion for Human Motion Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_HumanMAC_Masked_Motion_Completion_for_Human_Motion_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2302.03665.pdf>arxiv</a> <a href=https://lhchen.top/Human-MAC/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmade">MMADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmfde">MMFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2023_ICCV_1,
    author = "Chen, Ling-Hao and Zhang, JiaWei and Li, Yewen and Pang, Yiren and Xia, Xiaobo and Liu, Tongliang",
    title = "HumanMAC: Masked Motion Completion for Human Motion Prediction",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Auxiliary Tasks Benefit 3D Skeleton-based Human Motion Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Xu_Auxiliary_Tasks_Benefit_3D_Skeleton-based_Human_Motion_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.08942.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/AuxFormer>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2023_ICCV_1,
    author = "Xu, Chenxin and Tan, Robby T. and Tan, Yuhong and Chen, Siheng and Wang, Xinchao and Wang, Yanfeng",
    title = "Auxiliary Tasks Benefit 3D Skeleton-based Human Motion Prediction",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ahn et al., "Can We Use Diffusion Probabilistic Models for 3D Motion Prediction?", ICRA, 2023.</em> <a href=https://ieeexplore.ieee.org/document/10160722>paper</a> <a href=https://arxiv.org/pdf/2302.14503.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#sde">sDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ahn_2023_ICRA,
    author = "Ahn, Hyemin and Mascaro, Esteve Valls and Lee, Dongheui",
    title = "Can We Use Diffusion Probabilistic Models for 3D Motion Prediction?",
    booktitle = "ICRA",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Saadatnejad et al., "A generic diffusion-based approach for 3D human pose prediction in the wild", ICRA, 2023.</em> <a href=https://ieeexplore.ieee.org/document/10160399>paper</a> <a href=https://arxiv.org/pdf/2210.05669.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmade">MMADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Saadatnejad_2023_ICRA,
    author = "Saadatnejad, Saeed and Rasekh, Ali and Mofayezi, Mohammadreza and Medghalchi, Yasamin and Rajabzadeh, Sara and Mordan, Taylor and Alahi, Alexandre",
    title = "A generic diffusion-based approach for 3D human pose prediction in the wild",
    booktitle = "ICRA",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Guo et al., "Back to MLP: A Simple Baseline for Human Motion Prediction", WACV, 2023.</em> <a href=https://openaccess.thecvf.com/content/WACV2023/papers/Guo_Back_to_MLP_A_Simple_Baseline_for_Human_Motion_Prediction_WACV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.01567.pdf>arxiv</a> <a href=https://github.com/dulucas/siMLPe>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Guo_2023_WACV,
    author = "Guo, Wen and Du, Yuming and Shen, Xi and Lepetit, Vincent and Alameda-Pineda, Xavier and Moreno-Noguer, Francesc",
    title = "Back to MLP: A Simple Baseline for Human Motion Prediction",
    booktitle = "WACV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ma et al., "Multi-Objective Diverse Human Motion Prediction With Knowledge Distillation", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Ma_Multi-Objective_Diverse_Human_Motion_Prediction_With_Knowledge_Distillation_CVPR_2022_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ma_2022_CVPR_2,
    author = "Ma, Hengbo and Li, Jiachen and Hosseini, Ramtin and Tomizuka, Masayoshi and Choi, Chiho",
    title = "Multi-Objective Diverse Human Motion Prediction With Knowledge Distillation",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Diller et al., "Forecasting Characteristic 3D Poses of Human Actions", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Diller_Forecasting_Characteristic_3D_Poses_of_Human_Actions_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2011.15079.pdf>arxiv</a> <a href=https://github.com/chrdiller/characteristic3dposes>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#grab">GRAB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#is">IS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Diller_2022_CVPR,
    author = "Diller, Christian and Funkhouser, Thomas and Dai, Angela",
    title = "Forecasting Characteristic {3D} Poses of Human Actions",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ma et al., "Progressively Generating Better Initial Guesses Towards Next Stages for High-Quality Human Motion Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Ma_Progressively_Generating_Better_Initial_Guesses_Towards_Next_Stages_for_High-Quality_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.16051.pdf>arxiv</a> <a href=https://github.com/705062791/PGBIG>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ma_2022_CVPR,
    author = "Ma, Tiezheng and Nie, Yongwei and Long, Chengjiang and Zhang, Qing and Li, Guiqing",
    title = "Progressively Generating Better Initial Guesses Towards Next Stages for High-Quality Human Motion Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Salzmann et al., "Motron: Multimodal Probabilistic Human Motion Forecasting", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Salzmann_Motron_Multimodal_Probabilistic_Human_Motion_Forecasting_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.04132.pdf>arxiv</a> <a href=https://github.com/TUM-AAS/motron-cvpr22>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#kde">KDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Salzmann_2022_CVPR,
    author = "Salzmann, Tim and Pavone, Marco and Ryll, Markus",
    title = "Motron: Multimodal Probabilistic Human Motion Forecasting",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhong et al., "Spatio-Temporal Gating-Adjacency GCN for Human Motion Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Zhong_Spatio-Temporal_Gating-Adjacency_GCN_for_Human_Motion_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.01474.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhong_2022_CVPR,
    author = "Zhong, Chongyang and Hu, Lei and Zhang, Zihao and Ye, Yongjing and Xia, Shihong",
    title = "Spatio-Temporal Gating-Adjacency {GCN} for Human Motion Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Li et al., "Skeleton-Parted Graph Scattering Networks for 3D Human Motion Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136660018.pdf>paper</a> <a href=https://arxiv.org/pdf/2208.00368.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/SPGSN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2022_ECCV,
    author = "Li, Maosen and Chen, Siheng and Zhang, Zijing and Xie, Lingxi and Tian, Qi and Zhang, Ya",
    title = "Skeleton-Parted Graph Scattering Networks for {3D} Human Motion Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sampieri et al., "Pose Forecasting in Industrial Human-Robot Collaboration", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136980051.pdf>paper</a> <a href=https://arxiv.org/pdf/2208.07308.pdf>arxiv</a> <a href=https://github.com/federicocunico/human-robot-collaboration>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#chico">CHICO</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sampieri_2022_ECCV,
    author = "Sampieri, Alessio and di Melendugno, Guido Maria D’Amely and Avogaro, Andrea and Cunico, Federico and Setti, Francesco and Skenderi, Geri and Cristani, Marco and Galasso, Fabio",
    title = "Pose Forecasting in Industrial Human-Robot Collaboration",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sun et al., "Overlooked Poses Actually Make Sense: Distilling Privileged Knowledge for Human Motion Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136650668.pdf>paper</a> <a href=https://arxiv.org/pdf/2208.01302.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2022_ECCV,
    author = "Sun, Xiaoning and Cui, Qiongjie and Sun, Huaijiang and Li, Bin and Li, Weiqing and Lu, Jianfeng",
    title = "Overlooked Poses Actually Make Sense: Distilling Privileged Knowledge for Human Motion Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Diverse Human Motion Prediction Guided by Multi-level Spatial-Temporal Anchors", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820244.pdf>paper</a> <a href=https://github.com/Sirui-Xu/STARS>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#minade">minADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2022_ECCV_2,
    author = "Xu, Sirui and Wang, Yu-Xiong and Gui, Liang-Yan",
    title = "Diverse Human Motion Prediction Guided by Multi-level Spatial-Temporal Anchors",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Mascaro et al., "Robust Human Motion Forecasting using Transformer-based Model", IROS, 2022.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9981877>paper</a> <a href=https://arxiv.org/pdf/2302.08274.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mascaro_2022_IROS,
    author = "Mascaro, Esteve Valls and Ma, Shuo and Ahn, Hyemin and Lee, Dongheui",
    booktitle = "IROS",
    title = "Robust Human Motion Forecasting using Transformer-based Model",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhang et al., "IMNet: Physics-Infused Neural Network for Human Motion Prediction", RAL, 2022.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9816127>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Zhang_2022_RAL,
    author = "Zhang, Zhibo and Zhu, Yanjun and Rai, Rahul and Doermann, David",
    journal = "RAL",
    title = "{IMNet}: Physics-Infused Neural Network for Human Motion Prediction",
    volume = "7",
    number = "4",
    pages = "8949-8955",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sun et al., "Action-guided 3D Human Motion Prediction", NeurIPS, 2021.</em> <a href=https://papers.nips.cc/paper/2021/file/fd9dd764a6f1d73f4340d570804eacc4-Paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2021_NeurIPS,
    author = "Sun, Jiangxin and Lin, Zihang and Han, Xintong and Hu, Jian-Fang and Xu, Jia and Zheng, Wei-Shi",
    booktitle = "NeurIPS",
    title = "Action-guided {3D} Human Motion Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Cui et al., "Towards Accurate 3D Human Motion Prediction From Incomplete Observations", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Cui_Towards_Accurate_3D_Human_Motion_Prediction_From_Incomplete_Observations_CVPR_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cui_2021_CVPR,
    author = "Cui, Qiongjie and Sun, Huaijiang",
    title = "Towards Accurate {3D} Human Motion Prediction From Incomplete Observations",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Li et al., "RAIN: Reinforced Hybrid Attention Inference Network for Motion Forecasting", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Li_RAIN_Reinforced_Hybrid_Attention_Inference_Network_for_Motion_Forecasting_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2108.01316.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2021_ICCV_2,
    author = "Li, Jiachen and Yang, Fan and Ma, Hengbo and Malla, Srikanth and Tomizuka, Masayoshi and Choi, Chiho",
    title = "{RAIN}: Reinforced Hybrid Attention Inference Network for Motion Forecasting",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Aliakbarian et al., "Contextually Plausible and Diverse 3D Human Motion Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Aliakbarian_Contextually_Plausible_and_Diverse_3D_Human_Motion_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.08521.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#kld">KLD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Aliakbarian_2021_ICCV,
    author = "Aliakbarian, Sadegh and Saleh, Fatemeh and Petersson, Lars and Gould, Stephen and Salzmann, Mathieu",
    title = "Contextually Plausible and Diverse {3D} Human Motion Prediction",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Dang et al., "MSR-GCN: Multi-Scale Residual Graph Convolution Networks for Human Motion Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Dang_MSR-GCN_Multi-Scale_Residual_Graph_Convolution_Networks_for_Human_Motion_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://github.com/Droliven/MSRGCN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Dang_2021_ICCV,
    author = "Dang, Lingwei and Nie, Yongwei and Long, Chengjiang and Zhang, Qing and Li, Guiqing",
    title = "{MSR-GCN}: Multi-Scale Residual Graph Convolution Networks for Human Motion Prediction",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liu et al., "Motion Prediction Using Trajectory Cues", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Liu_Motion_Prediction_Using_Trajectory_Cues_ICCV_2021_paper.pdf>paper</a> <a href=https://github.com/Pose-Group/MPT>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mouse_fish">Mouse Fish</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2021_ICCV,
    author = "Liu, Zhenguang and Su, Pengxiang and Wu, Shuang and Shen, Xuanjing and Chen, Haipeng and Hao, Yanbin and Wang, Meng",
    title = "Motion Prediction Using Trajectory Cues",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Mao et al., "Generating Smooth Pose Sequences for Diverse Human Motion Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Mao_Generating_Smooth_Pose_Sequences_for_Diverse_Human_Motion_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2108.08422.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mao_2021_ICCV,
    author = "Mao, Wei and Liu, Miaomiao and Salzmann, Mathieu",
    title = "Generating Smooth Pose Sequences for Diverse Human Motion Prediction",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sofianos et al., "Space-Time-Separable Graph Convolutional Network for Pose Forecasting", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Sofianos_Space-Time-Separable_Graph_Convolutional_Network_for_Pose_Forecasting_ICCV_2021_paper.pdf>paper</a> <a href=https://github.com/FraLuca/STSGCN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sofianos_2021_ICCV,
    author = "Sofianos, Theodoros and Sampieri, Alessio and Franco, Luca and Galasso, Fabio",
    title = "Space-Time-Separable Graph Convolutional Network for Pose Forecasting",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Li et al., "Directed Acyclic Graph Neural Network for Human Motion Prediction", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561540>paper</a> <a href=https://github.com/Qinli-zz/DA-GNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2021_ICRA,
    author = "Li, Qin and Chalvatzaki, Georgia and Peters, Jan and Wang, Yong",
    booktitle = "ICRA",
    title = "Directed Acyclic Graph Neural Network for Human Motion Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Probabilistic Human Motion Prediction via A Bayesian Neural Network", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561665>paper</a> <a href=https://arxiv.org/pdf/2107.06564.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2021_ICRA,
    author = "Xu, Jie and Chen, Xingyu and Lan, Xuguang and Zheng, Nanning",
    booktitle = "ICRA",
    title = "Probabilistic Human Motion Prediction via A Bayesian Neural Network",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhang et al., "Non-local Graph Convolutional Network for Joint Activity Recognition and Motion Prediction", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636107>paper</a> <a href=https://arxiv.org/pdf/2108.01518.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2021_IROS,
    author = "Zhang, Dianhao and Vien, Ngo Anh and Van, Mien and McLoone, Seán",
    booktitle = "IROS",
    title = "Non-local Graph Convolutional Network for Joint Activity Recognition and Motion Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Aliakbarian et al., "A Stochastic Conditioning Scheme for Diverse Human Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Aliakbarian_A_Stochastic_Conditioning_Scheme_for_Diverse_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://github.com/mix-and-match/mix-and-match-tutorial>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#kld">KLD</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#si">SI</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#kl">KL</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#s-mse">S-MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Aliakbarian_2020_CVPR,
    author = "Aliakbarian, Sadegh and Saleh, Fatemeh Sadat and Salzmann, Mathieu and Petersson, Lars and Gould, Stephen",
    title = "A Stochastic Conditioning Scheme for Diverse Human Motion Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Cui et al., "Learning Dynamic Relationships for 3D Human Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Cui_Learning_Dynamic_Relationships_for_3D_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://github.com/cuiqiongjie/LDRGCN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cui_2020_CVPR,
    author = "Cui, Qiongjie and Sun, Huaijiang and Yang, Fei",
    title = "Learning Dynamic Relationships for 3D Human Motion Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Li et al., "Dynamic Multiscale Graph Neural Networks for 3D Skeleton Based Human Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Dynamic_Multiscale_Graph_Neural_Networks_for_3D_Skeleton_Based_Human_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.08802.pdf>arxiv</a> <a href=https://github.com/limaosen0/DMGNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2020_CVPR,
    author = "Li, Maosen and Chen, Siheng and Zhao, Yangheng and Zhang, Ya and Wang, Yanfeng and Tian, Qi",
    title = "Dynamic Multiscale Graph Neural Networks for {3D} Skeleton Based Human Motion Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Cai et al., "Learning Progressive Joint Propagation for Human Motion Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520222.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cai_2020_ECCV,
    author = "Cai, Yujun and Huang, Lin and Wang, Yiwei and Cham, Tat-Jen and Cai, Jianfei and Yuan, Junsong and Liu, Jun and Yang, Xu and Zhu, Yiheng and Shen, Xiaohui and Liu, Ding and Liu, Jing and Thalmann, Nadia M",
    title = "Learning Progressive Joint Propagation for Human Motion Prediction",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Mao et al., "History Repeats Itself: Human Motion Prediction via Motion Attention", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590460.pdf>paper</a> <a href=https://arxiv.org/pdf/2007.11755.pdf>arxiv</a> <a href=https://github.com/wei-mao-2019/HisRepItself>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mao_2020_ECCV,
    author = "Mao, Wei and Liu, Miaomiao and Salzmann, Mathieu",
    title = "History Repeats Itself: Human Motion Prediction via Motion Attention",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Piergiovanni et al., "Adversarial Generative Grammars for Human Activity Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470494.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.04888.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
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
<summary><em>Yuan et al., "DLow: Diversifying Latent Flows for Diverse Human Motion Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123540324.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.08386.pdf>arxiv</a> <a href=https://github.com/Khrylx/DLow>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmade">MMADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmfde">MMFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yuan_2020_ECCV,
    author = "Yuan, Ye and Kitani, Kris",
    title = "{DLow}: Diversifying Latent Flows for Diverse Human Motion Prediction",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chao et al., "Adversarial Refinement Network for Human Motion Prediction", ACCV, 2020.</em> <a href=https://openaccess.thecvf.com/content/ACCV2020/papers/Chao_Adversarial_Refinement_Network_for_Human_Motion_Prediction_ACCV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2011.11221.pdf>arxiv</a> <a href=https://github.com/Xianjin111/ARNet-for-human-motion-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chao_2020_ACCV,
    author = "Chao, Xianjin and Bin, Yanrui and Chu, Wenqing and Cao, Xuan and Ge, Yanhao and Wang, Chengjie and Li, Jilin and Huang, Feiyue and Leung, Howard",
    title = "Adversarial Refinement Network for Human Motion Prediction",
    booktitle = "ACCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Lebailly et al., "Motion Prediction Using Temporal Inception Module", ACCV, 2020.</em> <a href=https://openaccess.thecvf.com/content/ACCV2020/papers/Lebailly_Motion_Prediction_Using_Temporal_Inception_Module_ACCV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2010.03006.pdf>arxiv</a> <a href=https://github.com/tileb1/motion-prediction-tim>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lebailly_2020_ACCV,
    author = "Lebailly, Tim and Kiciroglu, Sena and Salzmann, Mathieu and Fua, Pascal and Wang, Wei",
    title = "Motion Prediction Using Temporal Inception Module",
    booktitle = "ACCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Gopalakrishnan et al., "A Neural Temporal Model For Human Motion Prediction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Gopalakrishnan_A_Neural_Temporal_Model_for_Human_Motion_Prediction_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1809.03036.pdf>arxiv</a> <a href=https://github.com/cr7anand/neural_temporal_models>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#npss">NPSS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gopalakrishnan_2019_CVPR,
    author = "Gopalakrishnan, Anand and Mali, Ankur and Kifer, Dan and Giles, Lee and Ororbia, Alexander G.",
    title = "A Neural Temporal Model For Human Motion Prediction",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liu et al., "Towards Natural And Accurate Future Motion Prediction Of Humans And Animals", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Liu_Towards_Natural_and_Accurate_Future_Motion_Prediction_of_Humans_and_CVPR_2019_paper.pdf>paper</a> <a href=https://github.com/BII-wushuang/Lie-Group-Motion-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mouse_fish">Mouse Fish</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#run_time">Run Time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2019_CVPR,
    author = "Liu, Zhenguang and Wu, Shuang and Jin, Shuyuan and Liu, Qi and Lu, Shijian and Zimmermann, Roger and Cheng, Li",
    title = "Towards Natural And Accurate Future Motion Prediction Of Humans And Animals",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Hernandez et al., "Human Motion Prediction Via Spatio-Temporal Inpainting", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Hernandez_Human_Motion_Prediction_via_Spatio-Temporal_Inpainting_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.05478.pdf>arxiv</a> <a href=https://github.com/magnux/MotionGAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#human">Human</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pskl">PSKL</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#psent">PSEnt</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hernandez_2019_ICCV,
    author = "Hernandez, Alejandro and Gall, Jurgen and Moreno-Noguer, Francesc",
    title = "Human Motion Prediction Via Spatio-Temporal Inpainting",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Mao et al., "Learning Trajectory Dependencies For Human Motion Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Mao_Learning_Trajectory_Dependencies_for_Human_Motion_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.05436.pdf>arxiv</a> <a href=https://github.com/wei-mao-2019/LearnTrajDep>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mao_2019_ICCV,
    author = "Mao, Wei and Liu, Miaomiao and Salzmann, Mathieu and Li, Hongdong",
    title = "Learning Trajectory Dependencies For Human Motion Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "Imitation Learning For Human Pose Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Imitation_Learning_for_Human_Pose_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1909.03449.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2019_ICCV,
    author = "Wang, Borui and Adeli, Ehsan and Chiu, Hsu-kuang and Huang, De-An and Niebles, Juan Carlos",
    title = "Imitation Learning For Human Pose Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhang et al., "Predicting 3D Human Dynamics From Video", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Predicting_3D_Human_Dynamics_From_Video_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.04781.pdf>arxiv</a> <a href=https://github.com/jasonyzhang/phd>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#instavariety">InstaVariety</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#re">RE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2019_ICCV,
    author = "Zhang, Jason Y. and Felsen, Panna and Kanazawa, Angjoo and Malik, Jitendra",
    title = "Predicting {3D} Human Dynamics From Video",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chiu et al., "Action-Agnostic Human Pose Forecasting", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8658717>paper</a> <a href=https://arxiv.org/pdf/1810.09676.pdf>arxiv</a> <a href=https://github.com/eddyhkchiu/pose_forecast_wacv/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chiu_2019_WACV,
    author = "Chiu, H. and Adeli, E. and Wang, B. and Huang, D. and Niebles, J. C.",
    booktitle = "WACV",
    title = "Action-Agnostic Human Pose Forecasting",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Gui et al., "Few-Shot Human Motion Prediction Via Meta-Learning", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Liangyan_Gui_Few-Shot_Human_Motion_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gui_2018_ECCV,
    author = "Gui, Liang-Yan and Wang, Yu-Xiong and Ramanan, Deva and Moura, Jose M. F.",
    title = "Few-Shot Human Motion Prediction Via Meta-Learning",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Gui et al., "Adversarial Geometry-Aware Human Motion Prediction", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Liangyan_Gui_Adversarial_Geometry-Aware_Human_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#human">Human</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gui_2018_ECCV_2,
    author = "Gui, Liang-Yan and Wang, Yu-Xiong and Liang, Xiaodan and Moura, Jose M. F.",
    title = "Adversarial Geometry-Aware Human Motion Prediction",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Gui et al., "Teaching Robots To Predict Human Motion", IROS, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8594452>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gui_2018_IROS,
    author = "Gui, L. and Zhang, K. and Wang, Y. and Liang, X. and Moura, J. M. F. and Veloso, M.",
    booktitle = "IROS",
    title = "Teaching Robots To Predict Human Motion",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chao et al., "Forecasting Human Dynamics From Static Images", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Chao_Forecasting_Human_Dynamics_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1704.03432.pdf>arxiv</a> <a href=https://github.com/ywchao/image-play>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mpii_human_pose">MPII Human Pose</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chao_2017_CVPR,
    author = "Chao, Yu-Wei and Yang, Jimei and Price, Brian and Cohen, Scott and Deng, Jia",
    title = "Forecasting Human Dynamics From Static Images",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Martinez et al., "On Human Motion Prediction Using Recurrent Neural Networks", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Martinez_On_Human_Motion_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.02445.pdf>arxiv</a> <a href=https://github.com/una-dinosauria/human-motion-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Martinez_2017_CVPR,
    author = "Martinez, Julieta and Black, Michael J. and Romero, Javier",
    title = "On Human Motion Prediction Using Recurrent Neural Networks",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Jain et al., "Structural-RNN: Deep Learning On Spatio-Temporal Graphs", CVPR, 2016.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.05298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
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
<summary><em>Fragkiadaki et al., "Recurrent Network Models For Human Dynamics", ICCV, 2015.</em> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Fragkiadaki_Recurrent_Network_Models_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1508.00271.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Fragkiadaki_2015_ICCV,
    author = "Fragkiadaki, Katerina and Levine, Sergey and Felsen, Panna and Malik, Jitendra",
    title = "Recurrent Network Models For Human Dynamics",
    booktitle = "ICCV",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Ionescu_2014_PAMI,
    author = "Ionescu, Catalin and Papava, Dragos and Olaru, Vlad and Sminchisescu, Cristian",
    title = "{Human3.6M}: Large Scale Datasets And Predictive Methods For {3D} Human Sensing In Natural Environments",
    journal = "PAMI",
    volume = "36",
    number = "7",
    pages = "1325-1339",
    year = "2014"
}
</pre>
</details>

</ul></details>
<a name=breakfast></a>
<details close>
<summary><l style="font-size:20px"><strong>Breakfast</strong></l> <a href=http://serre-lab.clps.brown.edu/resource/breakfast-actions-dataset/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2014/papers/Kuehne_The_Language_of_2014_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 77 hours of a video recording showing 10 breakfast preparation actions performed by 52 subjects in 18 different locations
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Gong et al., "ActFusion: a Unified Diffusion Model for Action Segmentation and Anticipation", NeurIPS, 2024.</em> <a href=https://openreview.net/pdf?id=NN9U0lEcAn>paper</a> <a href=https://arxiv.org/pdf/2412.04353>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#gtea_gaze">GTEA Gaze</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Gong_Actfusion_2024_NeurIPS,
    author = "Gong, Dayoung and Kwak, Suha and Cho, Minsu",
    title = "ActFusion: a Unified Diffusion Model for Action Segmentation and Anticipation",
    booktitle = "NeurIPS",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Girase et al., "Latency Matters: Real-Time Action Forecasting Transformer", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Girase_Latency_Matters_Real-Time_Action_Forecasting_Transformer_CVPR_2023_paper.pdf>paper</a> <a href=https://karttikeya.github.io/publication/RAFTformer/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#rt">RT</a></li>
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
<summary><em>Nawhal et al., "Rethinking Learning Approaches for Long-Term Action Anticipation", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940547.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.11566.pdf>arxiv</a> <a href=https://github.com/Nmegha2601/anticipatr>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#map">mAP</a></li>
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
<summary><em>Roy et al., "Action Anticipation Using Latent Goal Learning", WACV, 2022.</em> <a href=https://openaccess.thecvf.com/content/WACV2022/papers/Roy_Action_Anticipation_Using_Latent_Goal_Learning_WACV_2022_paper.pdf>paper</a> <a href=https://github.com/debadityaroy/LatentGoal>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Roy_2022_WACV,
    author = "Roy, Debaditya and Fernando, Basura",
    title = "Action Anticipation Using Latent Goal Learning",
    booktitle = "WACV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhao et al., "On Diverse Asynchronous Activity Anticipation", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123740766.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhao_2020_ECCV,
    author = "Zhao, He and Wildes, Richard P.",
    title = "On Diverse Asynchronous Activity Anticipation",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Morais et al., "Learning to Abstract and Predict Human Actions", BMVC, 2020.</em> <a href=https://www.bmvc2020-conference.com/assets/papers/0979.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.09234.pdf>arxiv</a> <a href=https://github.com/RomeroBarata/hierarchical_action_prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#mof">MoF</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#moc">MoC</a></li>
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
<details close>
<summary><em>Gammulle et al., "Forecasting Future Action Sequences With Neural Memory Networks", BMVC, 2019.</em> <a href=https://bmvc2019.org/wp-content/uploads/papers/0585-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1909.09278.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gammulle_2019_BMVC,
    author = "Gammulle, Harshala and Denman, Simon and Sridharan, Sridha and Fookes, Clinton",
    title = "Forecasting Future Action Sequences With Neural Memory Networks",
    year = "2019",
    booktitle = "BMVC"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Alati et al., "Help By Predicting What To Do", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8803155>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mpii_cooking">MPII Cooking</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
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
<summary><em>Abu et al., "When Will You Do What? - Anticipating Temporal Occurrences Of Activities", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Abu_Farha_When_Will_You_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.00892.pdf>arxiv</a> <a href=https://github.com/yabufarha/anticipating-activities>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Farha_2018_CVPR,
    author = "Abu Farha, Yazan and Richard, Alexander and Gall, Juergen",
    title = "When Will You Do What? - Anticipating Temporal Occurrences Of Activities",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Kuehne_2014_CVPR,
    author = "Kuehne, H. and Arslan, A. B. and Serre, T.",
    title = "The Language Of Actions: Recovering The Syntax And Semantics Of Goal-Directed Human Activities",
    booktitle = "CVPR",
    year = "2014"
}
</pre>
</details>

</ul></details>
<a name=sports-1m></a>
<details close>
<summary><l style="font-size:20px"><strong>Sports-1M</strong></l> <a href=https://cs.stanford.edu/people/karpathy/deepvideo/>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Karpathy_Large-scale_Video_Classification_2014_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale dataset of 1M sports videos with 487 classes
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a>, <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Sport</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Lu et al., "Flexible Spatio-Temporal Networks For Video Prediction", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lu_Flexible_Spatio-Temporal_Networks_CVPR_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sports-1m">Sports-1M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#visor">ViSOR</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#prost">PROST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lu_2017_CVPR,
    author = "Lu, Chaochao and Hirsch, Michael and Scholkopf, Bernhard",
    title = "Flexible Spatio-Temporal Networks For Video Prediction",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Bhattacharjee et al., "Temporal Coherency Based Criteria For Predicting Video Frames Using Deep Multi-Stage Generative Adversarial Networks", NeurIPS, 2017.</em> <a href=https://papers.nips.cc/paper/7014-temporal-coherency-based-criteria-for-predicting-video-frames-using-deep-multi-stage-generative-adversarial-networks.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bhattacharjee_2017_NeurIPS,
    author = "Bhattacharjee, Prateep and Das, Sukhendu",
    title = "Temporal Coherency Based Criteria For Predicting Video Frames Using Deep Multi-Stage Generative Adversarial Networks",
    booktitle = "NeurIPS",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Kong et al., "Deep Sequential Context Networks For Action Prediction", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Kong_Deep_Sequential_Context_CVPR_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bit">BIT</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kong_2017_CVPR,
    author = "Kong, Yu and Tao, Zhiqiang and Fu, Yun",
    title = "Deep Sequential Context Networks For Action Prediction",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Karpathy_2014_CVPR,
    author = "Karpathy, Andrej and Toderici, George and Shetty, Sanketh and Leung, Thomas and Sukthankar, Rahul and Fei-Fei, Li",
    title = "Large-Scale Video Classification With Convolutional Neural Networks",
    year = "2014",
    booktitle = "CVPR"
}
</pre>
</details>

</ul></details>
<a name=mpii_human_pose></a>
<details close>
<summary><l style="font-size:20px"><strong>MPII Human Pose</strong></l> <a href=http://human-pose.mpi-inf.mpg.de/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2014/papers/Andriluka_2D_Human_Pose_2014_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A pose detection dataset with 25K images containing 40K subjects performing 410 different activities
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/motion/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chao et al., "Forecasting Human Dynamics From Static Images", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Chao_Forecasting_Human_Dynamics_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1704.03432.pdf>arxiv</a> <a href=https://github.com/ywchao/image-play>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mpii_human_pose">MPII Human Pose</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chao_2017_CVPR,
    author = "Chao, Yu-Wei and Yang, Jimei and Price, Brian and Cohen, Scott and Deng, Jia",
    title = "Forecasting Human Dynamics From Static Images",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Andriluka_2014_CVPR,
    author = "Andriluka, Mykhaylo and Pishchulin, Leonid and Gehler, Peter and Schiele, Bernt",
    title = "{2D} Human Pose Estimation: New Benchmark And State Of The Art Analysis",
    booktitle = "CVPR",
    year = "2014"
}
</pre>
</details>

</ul></details>
<a name=spmd></a>
<details close>
<summary><l style="font-size:20px"><strong>Safety Pilot Model Deployment (SPMD)</strong></l> <a href=https://catalog.data.gov/dataset/safety-pilot-model-deployment-data>link</a> <a href=https://www.nhtsa.gov/sites/nhtsa.dot.gov/files/812171-safetypilotmodeldeploydeltestcondrtmrep.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of vehicle data collected in Ann Arbor at 10Hz with associated GPS and vehicle data
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> GPS, Vehicle sensor</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Oh et al., "Impact of Traffic Lights on Trajectory Forecasting of Human-driven Vehicles near Signalized Intersections", IROS, 2020.</em> <a href=http://ras.papercept.net/images/temp/IROS/files/3159.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.00486.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#spmd">SPMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#apad">APaD</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#twae">TWAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Oh_2020_IROS,
    author = "Oh, Geunseob and Peng, Huei",
    title = "Impact of Traffic Lights on Trajectory Forecasting of Human-driven Vehicles near Signalized Intersections",
    booktitle = "IROS",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Techreport{Bezzina_2014_tech,
    author = "Bezzina, Debby and Sayer, James",
    title = "Safety Pilot Model Deployment: Test Conductor Team Report",
    institution = "NHTSA",
    year = "2014"
}
</pre>
</details>

</ul></details>
<a name=orgbd></a>
<details close>
<summary><l style="font-size:20px"><strong>Online RGBD Action Dataset (ORGBD)</strong></l> <a href=https://sites.google.com/site/skicyyu/orgbd>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-16814-2_4>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of RGBD sequences capturing 7  human-object interaction activities including drinking, eating, using a laptop, reading on a cellphone, etc.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, bounding box, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hu et al., "Real-Time RGB-D Activity Prediction By Soft Regression", ECCV, 2016.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46448-0_17>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#orgbd">ORGBD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2016_ECCV,
    author = "Hu, Jian-Fang and Zheng, Wei-Shi and Ma, Lianyang and Wang, Gang and Lai, Jianhuang",
    editor = "Leibe, Bastian and Matas, Jiri and Sebe, Nicu and Welling, Max",
    title = "Real-Time {RGB-D} Activity Prediction By Soft Regression",
    booktitle = "ECCV",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Yu_2015_ACCV,
    author = "Yu, Gang and Liu, Zicheng and Yuan, Junsong",
    editor = "Cremers, Daniel and Reid, Ian and Saito, Hideo and Yang, Ming-Hsuan",
    title = "Discriminative Orderlet Mining For Real-Time Recognition Of Human-Object Interaction",
    booktitle = "ACCV",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=cas></a>
<details close>
<summary><l style="font-size:20px"><strong>Campus and Shelf (CaS)</strong></l> <a href=https://campar.in.tum.de/Chair/MultiHumanPose>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2014/papers/Belagiannis_3D_Pictorial_Structures_2014_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of multiple actors engaging in group activities with associated 3D poses recorded in two different environments.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/motion/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> 3D Pose, RGB</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Choudhury et al., "TEMPO: Efficient Multi-View Pose Estimation, Tracking, and Forecasting", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Choudhury_TEMPO_Efficient_Multi-View_Pose_Estimation_Tracking_and_Forecasting_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2309.07910.pdf>arxiv</a> <a href=https://rccchoudhury.github.io/tempo2023/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cas">CaS</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egohumans">EgoHumans</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pcp3d">PCP3D</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Choudhury_2023_ICCV,
    author = "Choudhury, Rohan and Kitani, Kris M. and Jeni, Laszlo A.",
    title = "TEMPO: Efficient Multi-View Pose Estimation, Tracking, and Forecasting",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@inproceedings{Belagian_2014_CVPR,
    author = "Belagiannis, Vasileios and Amin, Sikandar and Andriluka, Mykhaylo and Schiele, Bernt and Navab, Nassir and Ilic, Slobodan",
    title = "{3D} Pictorial Structures for Multiple Human Pose Estimation",
    booktitle = "CVPR",
    year = "2014"
}
</pre>
</details>

</ul></details>
</ul>