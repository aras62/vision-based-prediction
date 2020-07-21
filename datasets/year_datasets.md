<a name=top></a>
<a name=top></a>
---
<a href=README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Datasets</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=metrics.md#top><l style="font-size:30px">Metrics</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
[Home](papers.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Year&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Application](application_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Task](task_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Annotation](annotation_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
<h2>Datasets by Year</h2> 
Below is the list of datasets grouped according to their years.Within each group, the datasets are **sorted** based on their **popularity**, (i.e how often they are used in prediction papers).
<a name=datasets_2019></a>
<h2>2019</h2> <a href=#top>&uarr; top</a>
<ul><a name=data_pie></a>
<details close>
<summary><l style="font-size:20px"><strong>Pedestrian Intention Estimation (PIE)</strong></l> <a href=http://data.nvision2.eecs.yorku.ca/PIE_dataset/>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a>,<a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box, object class, attribute, temporal segment, vehicle sensors,</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Rasouli et al., "Pedestrian Action Anticipation Using Contextual Feature Fusion In Stacked Rnns", BMVC, 2019.</em> <a href=https://bmvc2019.org/wp-content/uploads/papers/0283-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.06582.pdf>arxiv</a> <a href=https://github.com/aras62/SF-GRU>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_pie">PIE</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_recall">Recall</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
<li><a href="metrics.md#metric_f1">F1</a></li>
<li><a href="metrics.md#metric_auc">AUC</a></li>
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
<summary><em>Rasouli et al., "Pie: A Large-Scale Dataset And Models For Pedestrian Intention Estimation And Trajectory Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.pdf>paper</a> <a href=https://github.com/aras62/PIEPredict>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_jaad">JAAD</a></li>
<li><a href="datasets.md#data_pie">PIE</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rasouli_2019_ICCV,
    author = "Rasouli, Amir and Kotseruba, Iuliia and Kunic, Toni and Tsotsos, John K.",
    title = "Pie: A Large-Scale Dataset And Models For Pedestrian Intention Estimation And Trajectory Prediction",
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
@InProceedings{Rasouli_2019_ICCV,
    author = "Rasouli, Amir and Kotseruba, Iuliia and Kunic, Toni and Tsotsos, John K.",
    title = "Pie: A Large-Scale Dataset And Models For Pedestrian Intention Estimation And Trajectory Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=data_carla></a>
<details close>
<summary><l style="font-size:20px"><strong>CARLA</strong></l> <a href=https://sites.google.com/view/precog>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rhinehart_PRECOG_PREdiction_Conditioned_on_Goals_in_Visual_Multi-Agent_Settings_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.01296.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Driving (simulation)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Rhinehart et al., "Precog: Prediction Conditioned On Goals In Visual Multi-Agent Settings", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rhinehart_PRECOG_PREdiction_Conditioned_on_Goals_in_Visual_Multi-Agent_Settings_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.01296.pdf>arxiv</a> <a href=https://sites.google.com/view/precog>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_carla">CARLA</a></li>
<li><a href="datasets.md#data_nuscenes">nuScenes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_meanmsd">meanMSD</a></li>
<li><a href="metrics.md#metric_minmsd">minMSD</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rhinehart_2019_ICCV,
    author = "Rhinehart, Nicholas and McAllister, Rowan and Kitani, Kris and Levine, Sergey",
    title = "Precog: Prediction Conditioned On Goals In Visual Multi-Agent Settings",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ding et al., "Online Vehicle Trajectory Prediction Using Policy Anticipation Network And Optimization-Based Context Reasoning", ICRA, 2019.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8793568>paper</a> <a href=https://arxiv.org/pdf/1903.00847.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_carla">CARLA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_run_time">Run Time</a></li>
<li><a href="metrics.md#metric_rmse">RMSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ding_2019_ICRA_2,
    author = "Ding, W. and Shen, S.",
    booktitle = "ICRA",
    title = "Online Vehicle Trajectory Prediction Using Policy Anticipation Network And Optimization-Based Context Reasoning",
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
@InProceedings{Rhinehart_2019_ICCV,
    author = "Rhinehart, Nicholas and McAllister, Rowan and Kitani, Kris and Levine, Sergey",
    title = "Precog: Prediction Conditioned On Goals In Visual Multi-Agent Settings",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=data_traf></a>
<details close>
<summary><l style="font-size:20px"><strong>TRAF</strong></l> <a href=https://drive.google.com/drive/folders/1LqzJuRkx5yhOcjWFORO5WZ97v6jg8RHN>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Chandra_TraPHic_Trajectory_Prediction_in_Dense_and_Heterogeneous_Traffic_Using_Weighted_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.04767.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box, object class, time-of-day</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chandra et al., "Traphic: Trajectory Prediction In Dense And Heterogeneous Traffic Using Weighted Interactions", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Chandra_TraPHic_Trajectory_Prediction_in_Dense_and_Heterogeneous_Traffic_Using_Weighted_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.04767.pdf>arxiv</a> <a href=https://go.umd.edu/TraPHic>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ngsim">NGSIM</a></li>
<li><a href="datasets.md#data_traf">TRAF</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chandra_2019_CVPR,
    author = "Chandra, Rohan and Bhattacharya, Uttaran and Bera, Aniket and Manocha, Dinesh",
    title = "Traphic: Trajectory Prediction In Dense And Heterogeneous Traffic Using Weighted Interactions",
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
@InProceedings{Chandra_2019_CVPR,
    author = "Chandra, Rohan and Bhattacharya, Uttaran and Bera, Aniket and Manocha, Dinesh",
    title = "Traphic: Trajectory Prediction In Dense And Heterogeneous Traffic Using Weighted Interactions",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=data_vpm></a>
<details close>
<summary><l style="font-size:20px"><strong>Vehicle-Pedestrian-Mixed (VPM)</strong></l> <a href=http://vr.ict.ac.cn/vp-lstm.>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Bi_Joint_Prediction_for_Kinematic_Trajectories_in_Vehicle-Pedestrian-Mixed_Scenes_ICCV_2019_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Bi et al., "Joint Prediction For Kinematic Trajectories In Vehicle-Pedestrian-Mixed Scenes", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Bi_Joint_Prediction_for_Kinematic_Trajectories_in_Vehicle-Pedestrian-Mixed_Scenes_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ngsim">NGSIM</a></li>
<li><a href="datasets.md#data_vpm">VPM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Bi_2019_ICCV,
    author = "Bi, Huikun and Fang, Zhong and Mao, Tianlu and Wang, Zhaoqi and Deng, Zhigang",
    title = "Joint Prediction For Kinematic Trajectories In Vehicle-Pedestrian-Mixed Scenes",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=data_nuscenes></a>
<details close>
<summary><l style="font-size:20px"><strong>nuScenes</strong></l> <a href=https://www.nuscenes.org/>link</a> <a href=>paper</a> <a href=https://arxiv.org/pdf/1903.11027.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, LIDAR, 3D bounding box, vehicle sensors, map</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Rhinehart et al., "Precog: Prediction Conditioned On Goals In Visual Multi-Agent Settings", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rhinehart_PRECOG_PREdiction_Conditioned_on_Goals_in_Visual_Multi-Agent_Settings_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.01296.pdf>arxiv</a> <a href=https://sites.google.com/view/precog>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_carla">CARLA</a></li>
<li><a href="datasets.md#data_nuscenes">nuScenes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_meanmsd">meanMSD</a></li>
<li><a href="metrics.md#metric_minmsd">minMSD</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rhinehart_2019_ICCV,
    author = "Rhinehart, Nicholas and McAllister, Rowan and Kitani, Kris and Levine, Sergey",
    title = "Precog: Prediction Conditioned On Goals In Visual Multi-Agent Settings",
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
@Article{Caesar_2019_arxiv,
    author = "Caesar, Holger and Bankiti, Varun and Lang, Alex H. and Vora, Sourabh and Liong, Venice Erin and Xu, Qiang and Krishnan, Anush and Pan, Yu and Baldan, Giancarlo and Beijbom, Oscar",
    title = "Nuscenes: A Multimodal Dataset For Autonomous Driving",
    journal = "arXiv:1903.11027",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=data_mgif></a>
<details close>
<summary><l style="font-size:20px"><strong>MGIF</strong></l> <a href=https://github.com/AliaksandrSiarohin/monkey-net>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Siarohin_Animating_Arbitrary_Objects_via_Deep_Motion_Transfer_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.08861.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kim et al., "Unsupervised Keypoint Learning For Guiding Class-Conditional Video Prediction", NeurIPS, 2019.</em> <a href=https://papers.nips.cc/paper/8637-unsupervised-keypoint-learning-for-guiding-class-conditional-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.02027.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
<li><a href="datasets.md#data_uva-nemo">UvA-NEMO</a></li>
<li><a href="datasets.md#data_mgif">MGIF</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_fvd">FVD</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kim_2019_NeurIPS,
    author = "Kim, Yunji and Nam, Seonghyeon and Cho, In and Kim, Seon Joo",
    title = "Unsupervised Keypoint Learning For Guiding Class-Conditional Video Prediction",
    booktitle = "NeurIPS",
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
@InProceedings{Siarohin_2019_CVPR,
    author = "Siarohin, Aliaksandr and Lathuilière, Stéphane and Tulyakov, Sergey and Ricci, Elisa and Sebe, Nicu",
    title = "Animating Arbitrary Objects Via Deep Motion Transfer",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=data_luggage></a>
<details close>
<summary><l style="font-size:20px"><strong>Luggage</strong></l> <a href=https://aashi7.github.io/NearCollision.html>link</a> <a href=https://ieeexplore.ieee.org/document/8967730>paper</a> <a href=https://arxiv.org/pdf/1903.09102.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> Stereo RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Robot</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Manglik et al., "Forecasting Time-To-Collision From Monocular Video: Feasibility, Dataset, And Challenges", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8967730>paper</a> <a href=https://arxiv.org/pdf/1903.09102.pdf>arxiv</a> <a href=https://github.com/aashi7/NearCollision>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_luggage">Luggage</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mae">MAE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Manglik_2019_IROS,
    author = "Manglik, Aashi and Weng, Xinshuo and Ohn-Bar, Eshed and Kitani, Kris M",
    booktitle = "IROS",
    title = "Forecasting Time-To-Collision From Monocular Video: Feasibility, Dataset, And Challenges",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=data_interaction></a>
<details close>
<summary><l style="font-size:20px"><strong>INTERACTION</strong></l> <a href=https://interaction-dataset.com>link</a> <a href=>paper</a> <a href=https://arxiv.org/pdf/1910.03088.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> Map, trajectory</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Li et al., "Conditional Generative Neural System For Probabilistic Trajectory Prediction", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8967822>paper</a> <a href=https://arxiv.org/pdf/1905.01631.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
<li><a href="datasets.md#data_interaction">INTERACTION</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Zhan_2019_arxiv,
    author = "Zhan, Wei and Sun, Liting and Wang, Di and Shi, Haojie and Clausse, Aubrey and Naumann, Maximilian and Kummerle, Julius and Konigshof, Hendrik and Stiller, Christoph and de La Fortelle, Arnaud and others",
    title = "Interaction Dataset: An International, Adversarial And Cooperative Motion Dataset In Interactive Driving Scenarios With Semantic Maps",
    journal = "arXiv:1910.03088",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=data_instavariety></a>
<details close>
<summary><l style="font-size:20px"><strong>InstaVariety</strong></l> <a href=https://github.com/akanazawa/human_dynamics>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kanazawa_Learning_3D_Human_Dynamics_From_Video_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.01601.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#motion>Motion prediction<application></a></li>
<li><em><strong>Data type:</strong></em> Rgb, Bounding Box, Pose</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhang et al., "Predicting 3D Human Dynamics From Video", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Predicting_3D_Human_Dynamics_From_Video_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.04781.pdf>arxiv</a> <a href={https://jasonyzhang.com/phd/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
<li><a href="datasets.md#data_instavariety">InstaVariety</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_pck">PCK</a></li>
<li><a href="metrics.md#metric_mpjpe">MPJPE</a></li>
<li><a href="metrics.md#metric_re">RE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2019_ICCV,
    author = "Zhang, Jason Y. and Felsen, Panna and Kanazawa, Angjoo and Malik, Jitendra",
    title = "Predicting 3D Human Dynamics From Video",
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
@InProceedings{Kanazawa_2019_CVPR,
    author = "Kanazawa, Angjoo and Zhang, Jason Y. and Felsen, Panna and Malik, Jitendra",
    title = "Learning 3D Human Dynamics From Video",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=data_fm></a>
<details close>
<summary><l style="font-size:20px"><strong>Future Motion (FM)</strong></l> <a href=https://mcl.korea.ac.kr/~krkim/iccv2019/index.html>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Kim_Instance-Level_Future_Motion_Estimation_in_a_Single_Image_Based_on_ICCV_2019_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box, attribute</li>
<li><em><strong>Task:</strong></em> Mix</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kim et al., "Instance-Level Future Motion Estimation In A Single Image Based On Ordinal Regression", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Kim_Instance-Level_Future_Motion_Estimation_in_a_Single_Image_Based_on_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_fm">FM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kim_2019_ICCV,
    author = "Kim, Kyung-Rae and Choi, Whan and Koh, Yeong Jun and Jeong, Seong-Gyun and Kim, Chang-Su",
    title = "Instance-Level Future Motion Estimation In A Single Image Based On Ordinal Regression",
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
@InProceedings{Kim_2019_ICCV,
    author = "Kim, Kyung-Rae and Choi, Whan and Koh, Yeong Jun and Jeong, Seong-Gyun and Kim, Chang-Su",
    title = "Instance-Level Future Motion Estimation In A Single Image Based On Ordinal Regression",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=data_egopose></a>
<details close>
<summary><l style="font-size:20px"><strong>EgoPose</strong></l> <a href=https://github.com/Khrylx/EgoPose>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Yuan_Ego-Pose_Estimation_and_Forecasting_As_Real-Time_PD_Control_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.03173.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#motion>Motion prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, 3D pose</li>
<li><em><strong>Task:</strong></em> Pose (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yuan et al., "Ego-Pose Estimation And Forecasting As Real-Time Pd Control", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Yuan_Ego-Pose_Estimation_and_Forecasting_As_Real-Time_PD_Control_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.03173.pdf>arxiv</a> <a href=https://github.com/Khrylx/EgoPose>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_egopose">EgoPose</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mje">MJE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yuan_2019_ICCV,
    author = "Yuan, Ye and Kitani, Kris",
    title = "Ego-Pose Estimation And Forecasting As Real-Time Pd Control",
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
@InProceedings{Yuan_2019_ICCV,
    author = "Yuan, Ye and Kitani, Kris",
    title = "Ego-Pose Estimation And Forecasting As Real-Time Pd Control",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=data_argoverse></a>
<details close>
<summary><l style="font-size:20px"><strong>ARGOVerse</strong></l> <a href=https://www.argoverse.org/data.html>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_Argoverse_3D_Tracking_and_Forecasting_With_Rich_Maps_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.02620.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, LIDAR, 3D bounding box, Map</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chang et al., "Argoverse: 3D Tracking And Forecasting With Rich Maps", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_Argoverse_3D_Tracking_and_Forecasting_With_Rich_Maps_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.02620.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_argoverse">ARGOVerse</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_minade">minADE</a></li>
<li><a href="metrics.md#metric_minfde">minFDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chang_2019_CVPR,
    author = "Chang, Ming-Fang and Lambert, John and Sangkloy, Patsorn and Singh, Jagjeet and Bak, Slawomir and Hartnett, Andrew and Wang, De and Carr, Peter and Lucey, Simon and Ramanan, Deva and Hays, James",
    title = "Argoverse: 3D Tracking And Forecasting With Rich Maps",
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
@InProceedings{Chang_2019_CVPR,
    author = "Chang, Ming-Fang and Lambert, John and Sangkloy, Patsorn and Singh, Jagjeet and Bak, Slawomir and Hartnett, Andrew and Wang, De and Carr, Peter and Lucey, Simon and Ramanan, Deva and Hays, James",
    title = "Argoverse: 3D Tracking And Forecasting With Rich Maps",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul></details>
</ul><a name=datasets_2018></a>
<h2>2018</h2> <a href=#top>&uarr; top</a>
<ul><a name=data_epic-kitchens></a>
<details close>
<summary><l style="font-size:20px"><strong>Epic-Kitchens</strong></l> <a href=https://epic-kitchens.github.io/2019>link</a> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Dima_Damen_Scaling_Egocentric_Vision_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.02748.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, audio,  bounding box, object class, text, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking  (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ke et al., "Time-Conditioned Action Anticipation In One Shot", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Ke_Time-Conditioned_Action_Anticipation_in_One_Shot_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets.md#data_50salad">50Salad</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_recall">Recall</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
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
<summary><em>Furnari et al., "What Would You Expect? Anticipating Egocentric Actions With Rolling-Unrolling Lstms And Modality Attention", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Furnari_What_Would_You_Expect_Anticipating_Egocentric_Actions_With_Rolling-Unrolling_LSTMs_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.09035.pdf>arxiv</a> <a href=https://github.com/fpv-iplab/rulstm>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets.md#data_egtea_gaze+">EGTEA Gaze+</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_recall">Recall</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Furnari_2019_ICCV,
    author = "Furnari, Antonino and Farinella, Giovanni Maria",
    title = "What Would You Expect? Anticipating Egocentric Actions With Rolling-Unrolling Lstms And Modality Attention",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Furnari et al., "Egocentric Action Anticipation By Disentangling Encoding And Inference", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8803534>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_epic-kitchens">Epic-Kitchens</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_recall">Recall</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Damen_2018_ECCV,
    author = "Damen, Dima and Doughty, Hazel and Farinella, Giovanni Maria and Fidler, Sanja and Furnari, Antonino and Kazakos, Evangelos and Moltisanti, Davide and Munro, Jonathan and Perrett, Toby and Price, Will and Wray, Michael",
    title = "Scaling Egocentric Vision: The Epic-Kitchens Dataset",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul></details>
<a name=data_youcook2></a>
<details close>
<summary><l style="font-size:20px"><strong>YouCook2</strong></l> <a href=http://youcook2.eecs.umich.edu/>link</a> <a href=https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/17344/16367>paper</a> <a href=https://arxiv.org/pdf/1703.09788.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, audio, text, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sener et al., "Zero-Shot Anticipation For Instructional Activities", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Sener_Zero-Shot_Anticipation_for_Instructional_Activities_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.02501.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_youcook2">YouCook2</a></li>
<li><a href="datasets.md#data_recipe1m">Recipe1M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_recall">Recall</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Zhou_2018_AI,
    author = "Zhou, Luowei and Xu, Chenliang and Corso, Jason J",
    title = "Towards Automatic Learning Of Procedures From Web Instructional Videos",
    booktitle = "AI",
    year = "2018"
}
</pre>
</details>

</ul></details>
<a name=data_viena></a>
<details close>
<summary><l style="font-size:20px"><strong>VIENA</strong></l> <a href=https://sites.google.com/view/viena2-project/home>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20887-5_28>paper</a> <a href=https://arxiv.org/pdf/1810.09044.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, activity label, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving (simulation)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Aliakbarian et al., "Viena: A Driving Anticipation Dataset", ACCV, 2019.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20887-5_28>paper</a> <a href=https://arxiv.org/pdf/1810.09044.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_jaad">JAAD</a></li>
<li><a href="datasets.md#data_viena">VIENA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Aliakbarian_2018_ACCV,
    author = "Aliakbarian, Mohammad Sadegh and Saleh, Fatemeh Sadat and Salzmann, Mathieu and Fernando, Basura and Petersson, Lars and Andersson, Lars",
    editor = "Jawahar, C. V. and Li, Hongdong and Mori, Greg and Schindler, Konrad",
    title = "Viena: A Driving Anticipation Dataset",
    booktitle = "ACCV",
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
@InProceedings{Aliakbarian_2018_ACCV,
    author = "Aliakbarian, Mohammad Sadegh and Saleh, Fatemeh Sadat and Salzmann, Mathieu and Fernando, Basura and Petersson, Lars and Andersson, Lars",
    editor = "Jawahar, C. V. and Li, Hongdong and Mori, Greg and Schindler, Konrad",
    title = "Viena: A Driving Anticipation Dataset",
    booktitle = "ACCV",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=data_shapestack></a>
<details close>
<summary><l style="font-size:20px"><strong>ShapeStack</strong></l> <a href=https://shapestacks.robots.ox.ac.uk/>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ye_Compositional_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.08522.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGBD, mask, stability</li>
<li><em><strong>Task:</strong></em> Object (simulation)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ye et al., "Compositional Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ye_Compositional_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.08522.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
<li><a href="datasets.md#data_shapestack">ShapeStack</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_lpips">LPIPS</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ye_2019_ICCV,
    author = "Ye, Yufei and Singh, Maneesh and Gupta, Abhinav and Tulsiani, Shubham",
    title = "Compositional Video Prediction",
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
@InProceedings{Groth_2018_arxiv,
    author = "Groth, Oliver and Fuchs, Fabian B and Posner, Ingmar and Vedaldi, Andrea",
    title = "Shapestacks: Learning Vision-Based Physical Intuition For Generalised Object Stacking",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul></details>
<a name=data_shanghaitech_campus></a>
<details close>
<summary><l style="font-size:20px"><strong>ShanghaiTech Campus (STC)</strong></l> <a href=https://svip-lab.github.io/dataset/campus_dataset.html>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_Future_Frame_Prediction_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1712.09867.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, anomaly</li>
<li><em><strong>Task:</strong></em> Surveillance, anomaly</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle Gan", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_chuk_avenue">CHUK Avenue</a></li>
<li><a href="datasets.md#data_shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kwon_2019_CVPR,
    author = "Kwon, Yong-Hoon and Park, Min-Gyu",
    title = "Predicting Future Frames Using Retrospective Cycle Gan",
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
@InProceedings{Liu_2018_CVPR,
    author = "Liu, Wen and Luo, Weixin and Lian, Dongze and Gao, Shenghua",
    title = "Future Frame Prediction For Anomaly Detection – A New Baseline",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul></details>
<a name=data_egtea_gaze+></a>
<details close>
<summary><l style="font-size:20px"><strong>Extended Georgia Tech Egocentric Activity Gaze+ (EGTEA Gaze+)</strong></l> <a href=http://www.cbi.gatech.edu/fpv/>link</a> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yin_Li_In_the_Eye_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.00626.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, gaze, mask, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking  (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Furnari et al., "What Would You Expect? Anticipating Egocentric Actions With Rolling-Unrolling Lstms And Modality Attention", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Furnari_What_Would_You_Expect_Anticipating_Egocentric_Actions_With_Rolling-Unrolling_LSTMs_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.09035.pdf>arxiv</a> <a href=https://github.com/fpv-iplab/rulstm>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets.md#data_egtea_gaze+">EGTEA Gaze+</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_recall">Recall</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Furnari_2019_ICCV,
    author = "Furnari, Antonino and Farinella, Giovanni Maria",
    title = "What Would You Expect? Anticipating Egocentric Actions With Rolling-Unrolling Lstms And Modality Attention",
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
@InProceedings{Li_2018_ECCV_2,
    author = "Li, Yin and Liu, Miao and Rehg, James M",
    title = "In The Eye Of Beholder: Joint Learning Of Gaze And Actions In First Person Video",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul></details>
<a name=data_ava></a>
<details close>
<summary><l style="font-size:20px"><strong>Atomic Visual Actions (AVA)</strong></l> <a href=https://research.google.com/ava/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Gu_AVA_A_Video_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.08421.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sun et al., "Relational Action Forecasting", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Sun_Relational_Action_Forecasting_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.04231.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_jhmdb">JHMDB</a></li>
<li><a href="datasets.md#data_ava">AVA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ap">AP</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2019_CVPR,
    author = "Sun, Chen and Shrivastava, Abhinav and Vondrick, Carl and Sukthankar, Rahul and Murphy, Kevin and Schmid, Cordelia",
    title = "Relational Action Forecasting",
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
@InProceedings{Gu_2018_CVPR,
    author = "Gu, Chunhui and Sun, Chen and Ross, David A and Vondrick, Carl and Pantofaru, Caroline and Li, Yeqing and Vijayanarasimhan, Sudheendra and Toderici, George and Ricco, Susanna and Sukthankar, Rahul and others",
    title = "Ava: A Video Dataset Of Spatio-Temporally Localized Atomic Visual Actions",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul></details>
<a name=data_acticipate></a>
<details close>
<summary><l style="font-size:20px"><strong>ACTICIPATE</strong></l> <a href=http://vislab.isr.tecnico.ulisboa.pt/datasets/>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/8460924/>paper</a> <a href=https://arxiv.org/pdf/1802.10503.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, gaze, pose</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Schydlo et al., "Anticipation In Human-Robot Cooperation: A Recurrent Neural Network Approach For Multiple Action Sequences Prediction", ICRA, 2018.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8460924>paper</a> <a href=https://arxiv.org/pdf/1802.10503.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_cad-120">CAD-120</a></li>
<li><a href="datasets.md#data_acticipate">ACTICIPATE</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_f1">F1</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Schydlo_2018_ICRA_2,
    author = "Schydlo, P. and Rakovic, M. and Jamone, L. and Santos-Victor, J.",
    booktitle = "ICRA",
    title = "Anticipation In Human-Robot Cooperation: A Recurrent Neural Network Approach For Multiple Action Sequences Prediction",
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
@InProceedings{Schydlo_2018_ICRA,
    author = "Schydlo, Paul and Rakovic, Mirko and Jamone, Lorenzo and Santos-Victor, Jos{\'e}",
    title = "Anticipation In Human-Robot Cooperation: A Recurrent Neural Network Approach For Multiple Action Sequences Prediction",
    booktitle = "ICRA",
    year = "2018"
}
</pre>
</details>

</ul></details>
<a name=data_actev/virat></a>
<details close>
<summary><l style="font-size:20px"><strong>ActEV/VIRAT</strong></l> <a href=https://actev.nist.gov/trecvid19>link</a> <a href=https://www-nlpir.nist.gov/projects/tvpubs/tv18.papers/tv18overview.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a>,<a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liang et al., "Peeking Into The Future: Predicting Future Person Activities And Locations In Videos", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPRW_2019/papers/Precognition/Liang_Peeking_Into_the_Future_Predicting_Future_Person_Activities_and_Locations_CVPRW_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1902.03748.pdf>arxiv</a> <a href=https://github.com/google/next-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_actev/virat">ActEV/VIRAT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_map">mAP</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Awad_2018_Trecvid,
    author = "Awad, George and Butt, Asad and Curtis, Keith and Lee, Yooyoung and Fiscus, Jonathan and Godil, Afzad and Joy, David and Delgado, Andrew and Smeaton, Alan and Graham, Yvette and others",
    title = "Benchmarking Video Activity Detection, Video Captioning And Matching, Video Storytelling Linking And Video Search",
    booktitle = "TRECVID",
    year = "2018"
}
</pre>
</details>

</ul></details>
<a name=data_3dpw></a>
<details close>
<summary><l style="font-size:20px"><strong>3D POSES IN THE WILD (3DPW)</strong></l> <a href=https://virtualhumans.mpi-inf.mpg.de/3DPW/>link</a> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Timo_von_Marcard_Recovering_Accurate_3D_ECCV_2018_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#motion>Motion prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, 2D/3D pose, models</li>
<li><em><strong>Task:</strong></em> Outdoor</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Mao et al., "Learning Trajectory Dependencies For Human Motion Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Mao_Learning_Trajectory_Dependencies_for_Human_Motion_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.05436.pdf>arxiv</a> <a href=https://github.com/wei-mao-2019/LearnTrajDep>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_cmu_mocap">CMU Mocap</a></li>
<li><a href="datasets.md#data_3dpw">3DPW</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mane">MAnE</a></li>
<li><a href="metrics.md#metric_mpjpe">MPJPE</a></li>
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
@InProceedings{vonMarcard_2018_ECCV,
    author = "von Marcard, Timo and Henschel, Roberto and Black, Michael and Rosenhahn, Bodo and Pons-Moll, Gerard",
    title = "Recovering Accurate 3D Human Pose In The Wild Using Imus And A Moving Camera",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul></details>
</ul><a name=datasets_2017></a>
<h2>2017</h2> <a href=#top>&uarr; top</a>
<ul><a name=data_jaad></a>
<details close>
<summary><l style="font-size:20px"><strong>Joint Attention in Autonomous Driving (JAAD)</strong></l> <a href=http://data.nvision2.eecs.yorku.ca/JAAD_dataset/>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w3/Rasouli_Are_They_Going_ICCV_2017_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a>,<a href=papers.md#action>Action prediction<application></a>,<a href=papers.md#trajectory>Trajectory prediction<application></a>,<a href=papers.md#other>Other prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box, attribute, temporal segment</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Gujjar et al., "Classifying Pedestrian Actions In Advance Using Predicted Video Of Urban Driving Scenes", ICRA, 2019.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8794278>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_jaad">JAAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_l1">L1</a></li>
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
<summary><em>Saleh et al., "Real-Time Intent Prediction Of Pedestrians For Autonomous Ground Vehicles Via Spatio-Temporal Densenet", ICRA, 2019.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8793991>paper</a> <a href=https://arxiv.org/pdf/1904.09862.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_jaad">JAAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ap">AP</a></li>
<li><a href="metrics.md#metric_run_time">Run Time</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Saleh_2019_ICRA,
    author = "Saleh, K. and Hossny, M. and Nahavandi, S.",
    booktitle = "ICRA",
    title = "Real-Time Intent Prediction Of Pedestrians For Autonomous Ground Vehicles Via Spatio-Temporal Densenet",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Aliakbarian et al., "Viena: A Driving Anticipation Dataset", ACCV, 2019.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20887-5_28>paper</a> <a href=https://arxiv.org/pdf/1810.09044.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_jaad">JAAD</a></li>
<li><a href="datasets.md#data_viena">VIENA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Aliakbarian_2018_ACCV,
    author = "Aliakbarian, Mohammad Sadegh and Saleh, Fatemeh Sadat and Salzmann, Mathieu and Fernando, Basura and Petersson, Lars and Andersson, Lars",
    editor = "Jawahar, C. V. and Li, Hongdong and Mori, Greg and Schindler, Konrad",
    title = "Viena: A Driving Anticipation Dataset",
    booktitle = "ACCV",
    year = "2019"
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
<li><a href="datasets.md#data_jaad">JAAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_map">mAP</a></li>
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
<summary><em>Rasouli et al., "Pie: A Large-Scale Dataset And Models For Pedestrian Intention Estimation And Trajectory Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.pdf>paper</a> <a href=https://github.com/aras62/PIEPredict>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_jaad">JAAD</a></li>
<li><a href="datasets.md#data_pie">PIE</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rasouli_2019_ICCV,
    author = "Rasouli, Amir and Kotseruba, Iuliia and Kunic, Toni and Tsotsos, John K.",
    title = "Pie: A Large-Scale Dataset And Models For Pedestrian Intention Estimation And Trajectory Prediction",
    booktitle = "ICCV",
    year = "2019"
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
<li><a href="datasets.md#data_jaad">JAAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psi">Psi</a></li>
<li><a href="metrics.md#metric_ism">ISM</a></li>
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
<a name=data_strands></a>
<details close>
<summary><l style="font-size:20px"><strong>STRANDS</strong></l> <a href=https://strands.readthedocs.io/en/latest/datasets/>link</a> <a href=https://ieeexplore.ieee.org/document/7948740>paper</a> <a href=https://arxiv.org/pdf/1604.04384.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGBD, 3D bounding box</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sun et al., "3Dof Pedestrian Trajectory Prediction Learned From Long-Term Autonomous Mobile Robot Deployment Data", ICRA, 2018.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8461228>paper</a> <a href=https://arxiv.org/pdf/1710.00126.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_strands">STRANDS</a></li>
<li><a href="datasets.md#data_l-cas">L-CAS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_aede">AEDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2018_ICRA,
    author = "Sun, L. and Yan, Z. and Mellado, S. M. and Hanheide, M. and Duckett, T.",
    booktitle = "ICRA",
    title = "3Dof Pedestrian Trajectory Prediction Learned From Long-Term Autonomous Mobile Robot Deployment Data",
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
<a name=data_recipe1m></a>
<details close>
<summary><l style="font-size:20px"><strong>Recipe1M</strong></l> <a href=http://pic2recipe.csail.mit.edu/>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Learning_Cross-Modal_Embeddings_With_Adversarial_Networks_for_Cooking_Recipes_and_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.01273.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB (image), text</li>
<li><em><strong>Task:</strong></em> Cooking</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sener et al., "Zero-Shot Anticipation For Instructional Activities", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Sener_Zero-Shot_Anticipation_for_Instructional_Activities_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.02501.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_youcook2">YouCook2</a></li>
<li><a href="datasets.md#data_recipe1m">Recipe1M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_recall">Recall</a></li>
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
<a name=data_pku-mmd></a>
<details close>
<summary><l style="font-size:20px"><strong>PKU-MMD</strong></l> <a href=http://www.icst.pku.edu.cn/struct/Projects/PKUMMD.html>link</a> <a href=>paper</a> <a href=https://arxiv.org/pdf/1703.07475.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGBD, IR, 3D pose, multiview, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity, interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liu et al., "Ssnet: Scale Selection Network For Online 3D Action Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_SSNet_Scale_Selection_CVPR_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_pku-mmd">PKU-MMD</a></li>
<li><a href="datasets.md#data_oad">OAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2018_CVPR_ssnet,
    author = "Liu, Jun and Shahroudy, Amir and Wang, Gang and Duan, Ling-Yu and Kot, Alex C.",
    title = "Ssnet: Scale Selection Network For Online 3D Action Prediction",
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
@Article{Liu_2017_arxiv,
    author = "Chunhui, Liu and Yueyu, Hu and Yanghao, Li and Sijie, Song and Jiaying, Liu",
    title = "Pku-Mmd: A Large Scale Benchmark For Continuous Multi-Modal Human Action Understanding",
    journal = "arXiv:1703.07475",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=data_oxford></a>
<details close>
<summary><l style="font-size:20px"><strong>Oxford Robot Car (ORC)</strong></l> <a href=https://robotcar-dataset.robots.ox.ac.uk/>link</a> <a href=https://journals.sagepub.com/doi/abs/10.1177/0278364916679498>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> Stereo RGB, LIDAR, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Srikanth et al., "Infer: Intermediate Representations For Future Prediction", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8968553>paper</a> <a href=https://arxiv.org/pdf/1903.10641.pdf>arxiv</a> <a href=https://rebrand.ly/INFER-results>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_cityscapes">Cityscapes</a></li>
<li><a href="datasets.md#data_oxford">Oxford</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Srikanth_2019_IROS,
    author = "Srikanth, Shashank and Ansari, Junaid Ahmed and Sharma, Sarthak and others",
    booktitle = "IROS",
    title = "Infer: Intermediate Representations For Future Prediction",
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
    Title = "1 Year, 1000Km: The Oxford Robotcar Dataset",
    Journal = "IJRR",
    Volume = "36",
    Number = "1",
    Pages = "3-15",
    Year = "2017"
}
</pre>
</details>

</ul></details>
<a name=data_mouse_fish></a>
<details close>
<summary><l style="font-size:20px"><strong>Mouse Fish</strong></l> <a href=https://web.bii.a-star.edu.sg/archive/machine_learning/Projects/behaviorAnalysis/Lie-X/Lie-X.html>link</a> <a href=https://link.springer.com/article/10.1007/s11263-017-0998-6>paper</a> <a href=https://arxiv.org/pdf/1609.03773.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#motion>Motion prediction<application></a></li>
<li><em><strong>Data type:</strong></em> Depth, 3D pose</li>
<li><em><strong>Task:</strong></em> Animal</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liu et al., "Towards Natural And Accurate Future Motion Prediction Of Humans And Animals", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Liu_Towards_Natural_and_Accurate_Future_Motion_Prediction_of_Humans_and_CVPR_2019_paper.pdf>paper</a> <a href=https://github.com/BII-wushuang/Lie-Group-Motion-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_mouse_fish">Mouse Fish</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mje">MJE</a></li>
<li><a href="metrics.md#metric_run_time">Run Time</a></li>
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
    title = "Lie-X: Depth Image Based Articulated Object Pose Estimation, Tracking, And Action Recognition On Lie Groups",
    journal = "IJCV",
    volume = "123",
    number = "3",
    pages = "454--478",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=data_l-cas></a>
<details close>
<summary><l style="font-size:20px"><strong>L-CAS</strong></l> <a href=https://lcas.lincoln.ac.uk/wp/research/data-sets-software/l-cas-3d-point-cloud-people-dataset/>link</a> <a href=https://ieeexplore.ieee.org/document/8202247>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> LIDAR, 3D bounding box, attribute</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sun et al., "3Dof Pedestrian Trajectory Prediction Learned From Long-Term Autonomous Mobile Robot Deployment Data", ICRA, 2018.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8461228>paper</a> <a href=https://arxiv.org/pdf/1710.00126.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_strands">STRANDS</a></li>
<li><a href="datasets.md#data_l-cas">L-CAS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_aede">AEDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2018_ICRA,
    author = "Sun, L. and Yan, Z. and Mellado, S. M. and Hanheide, M. and Duckett, T.",
    booktitle = "ICRA",
    title = "3Dof Pedestrian Trajectory Prediction Learned From Long-Term Autonomous Mobile Robot Deployment Data",
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
    title = "Online Learning For Human Classification In 3D Lidar-Based Tracking",
    booktitle = "IROS",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=data_epic-fail></a>
<details close>
<summary><l style="font-size:20px"><strong>Epic-Fail</strong></l> <a href=http://aliensunmin.github.io/project/video-Forecasting/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Zeng_Agent-Centric_Risk_Assessment_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.06560.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box, trajectory, temporal segment</li>
<li><em><strong>Task:</strong></em> Risk assessment</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zeng et al., "Agent-Centric Risk Assessment: Accident Anticipation And Risky Region Localization", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Zeng_Agent-Centric_Risk_Assessment_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.06560.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_dad">DAD</a></li>
<li><a href="datasets.md#data_epic-fail">Epic-Fail</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_map">mAP</a></li>
<li><a href="metrics.md#metric_tta">TTA</a></li>
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
<a name=data_cityperson></a>
<details close>
<summary><l style="font-size:20px"><strong>CityPersons</strong></l> <a href=https://bitbucket.org/shanshanzhang/citypersons/src/default/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_CityPersons_A_Diverse_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1702.05693.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> Stereo RGB, bounding box, semantic segment</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Bhattacharyya et al., "Long-Term On-Board Prediction Of People In Traffic Scenes Under Uncertainty", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Bhattacharyya_Long-Term_On-Board_Prediction_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1711.09026.pdf>arxiv</a> <a href=https://github.com/apratimbhattacharyya18/onboard_long_term_prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_cityperson">CityPerson</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_nll">NLL</a></li>
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
<a name=data_bu_action></a>
<details close>
<summary><l style="font-size:20px"><strong>BU Action (BUA)</strong></l> <a href=http://cs-people.bu.edu/sbargal/BU-action/>link</a> <a href=https://www.sciencedirect.com/science/article/abs/pii/S0031320317300353>paper</a> <a href=https://arxiv.org/pdf/1512.07155.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB (image), activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Safaei et al., "Still Image Action Recognition By Predicting Spatial-Temporal Pixel Evolution", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8658386>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_willow_action">Willow Action</a></li>
<li><a href="datasets.md#data_wider">WIDER</a></li>
<li><a href="datasets.md#data_stanford-40">Stanford-40</a></li>
<li><a href="datasets.md#data_bu_action">BU Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_map">mAP</a></li>
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
</ul><a name=datasets_2016></a>
<h2>2016</h2> <a href=#top>&uarr; top</a>
<ul><a name=data_sd></a>
<details close>
<summary><l style="font-size:20px"><strong>Stanford Drone (SD)</strong></l> <a href=http://cvgl.stanford.edu/projects/uav_data/>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46484-8_33>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box, object class</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Li, "Which Way Are You Going? Imitative Decision Learning For Path Forecasting In Dynamic Scenes", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Which_Way_Are_You_Going_Imitative_Decision_Learning_for_Path_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_minade">minADE</a></li>
<li><a href="metrics.md#metric_minfde">minFDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2019_CVPR,
    author = "Li, Yuke",
    title = "Which Way Are You Going? Imitative Decision Learning For Path Forecasting In Dynamic Scenes",
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
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_ngsim">NGSIM</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
<li><a href="metrics.md#metric_rmse">RMSE</a></li>
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
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
<li><a href="datasets.md#data_interaction">INTERACTION</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
<li><a href="datasets.md#data_pets2009">PETS2009</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
<summary><em>Lee et al., "Desire: Distant Future Prediction In Dynamic Scenes With Interacting Agents", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lee_DESIRE_Distant_Future_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1704.04394.pdf>arxiv</a> <a href=https://github.com/yadrimz/DESIRE>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ed">ED</a></li>
<li><a href="metrics.md#metric_mined">minED</a></li>
<li><a href="metrics.md#metric_maxd">maxD</a></li>
<li><a href="metrics.md#metric_miss_rate">Miss rate</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lee_2017_CVPR,
    author = "Lee, Namhoon and Choi, Wongun and Vernaza, Paul and Choy, Christopher B. and Torr, Philip H. S. and Chandraker, Manmohan",
    title = "Desire: Distant Future Prediction In Dynamic Scenes With Interacting Agents",
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
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
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
    title = "Learning Social Etiquette: Human Trajectory Understanding In Crowded Scenes",
    booktitle = "ECCV",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=data_cityscapes></a>
<details close>
<summary><l style="font-size:20px"><strong>Cityscapes</strong></l> <a href=https://www.cityscapes-dataset.com/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Cordts_The_Cityscapes_Dataset_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1604.01685.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a>,<a href=papers.md#trajectory>Trajectory prediction<application></a>,<a href=papers.md#other>Other prediction<application></a></li>
<li><em><strong>Data type:</strong></em> Stereo RGB, bounding box, semantic segment, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Castrejon et al., "Improved Conditional Vrnns For Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Castrejon_Improved_Conditional_VRNNs_for_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.12165.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_cityscapes">Cityscapes</a></li>
<li><a href="datasets.md#data_bair_push">BAIR Push</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_lpips">LPIPS</a></li>
<li><a href="metrics.md#metric_fvd">FVD</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Castrejon_2019_ICCV,
    author = "Castrejon, Lluis and Ballas, Nicolas and Courville, Aaron",
    title = "Improved Conditional Vrnns For Video Prediction",
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<summary><em>Srikanth et al., "Infer: Intermediate Representations For Future Prediction", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8968553>paper</a> <a href=https://arxiv.org/pdf/1903.10641.pdf>arxiv</a> <a href=https://rebrand.ly/INFER-results>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_cityscapes">Cityscapes</a></li>
<li><a href="datasets.md#data_oxford">Oxford</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Srikanth_2019_IROS,
    author = "Srikanth, Shashank and Ansari, Junaid Ahmed and Sharma, Sarthak and others",
    booktitle = "IROS",
    title = "Infer: Intermediate Representations For Future Prediction",
    year = "2019"
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
<li><a href="datasets.md#data_cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_iou">IoU</a></li>
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
<li><a href="datasets.md#data_cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_iou">IoU</a></li>
<li><a href="metrics.md#metric_voi">VoI</a></li>
<li><a href="metrics.md#metric_gce">GCE</a></li>
<li><a href="metrics.md#metric_ri">RI</a></li>
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
<li><a href="datasets.md#data_cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_iou">IoU</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
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
<li><a href="datasets.md#data_cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mse">MSE</a></li>
<li><a href="metrics.md#metric_miou">MIoU</a></li>
<li><a href="metrics.md#metric_epe">EPE</a></li>
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
<a name=data_bair_push></a>
<details close>
<summary><l style="font-size:20px"><strong>BAIR Push</strong></l> <a href=https://sites.google.com/site/brainrobotdata/home/push-dataset>link</a> <a href=https://papers.nips.cc/paper/6161-unsupervised-learning-for-physical-interaction-through-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1605.07157.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Robot object manipulation</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Castrejon et al., "Improved Conditional Vrnns For Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Castrejon_Improved_Conditional_VRNNs_for_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.12165.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_cityscapes">Cityscapes</a></li>
<li><a href="datasets.md#data_bair_push">BAIR Push</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_lpips">LPIPS</a></li>
<li><a href="metrics.md#metric_fvd">FVD</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Castrejon_2019_ICCV,
    author = "Castrejon, Lluis and Ballas, Nicolas and Courville, Aaron",
    title = "Improved Conditional Vrnns For Video Prediction",
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_bair_push">BAIR Push</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_bair_push">BAIR Push</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<a name=data_dad></a>
<details close>
<summary><l style="font-size:20px"><strong>Dashcam Accident Dataset (DAD)</strong></l> <a href=https://aliensunmin.github.io/project/dashcam/>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-54190-7_9>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box, object class,  temporal segment</li>
<li><em><strong>Task:</strong></em> Driving (accident)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Suzuki et al., "Anticipating Traffic Accidents With Adaptive Loss And Large-Scale Incident Db", The CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0494.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.02675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_dad">DAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_recall">Recall</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
<li><a href="metrics.md#metric_f1">F1</a></li>
<li><a href="metrics.md#metric_map">mAP</a></li>
<li><a href="metrics.md#metric_attc">ATTC</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Suzuki_2018_CVPR,
    author = "Suzuki, Tomoyuki and Kataoka, Hirokatsu and Aoki, Yoshimitsu and Satoh, Yutaka",
    title = "Anticipating Traffic Accidents With Adaptive Loss And Large-Scale Incident Db",
    booktitle = "The CVPR",
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
<li><a href="datasets.md#data_dad">DAD</a></li>
<li><a href="datasets.md#data_epic-fail">Epic-Fail</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_map">mAP</a></li>
<li><a href="metrics.md#metric_tta">TTA</a></li>
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
@InProceedings{Chan_2016_ACCV,
    author = "Chan, Fu-Hsiang and Chen, Yu-Ting and Xiang, Yu and Sun, Min",
    editor = "Lai, Shang-Hong and Lepetit, Vincent and Nishino, Ko and Sato, Yoichi",
    title = "Anticipating Accidents In Dashcam Videos",
    booktitle = "ACCV",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=data_cmu_mocap></a>
<details close>
<summary><l style="font-size:20px"><strong>CMU Mocap</strong></l> <a href=http://mocap.cs.cmu.edu/>link</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a>,<a href=papers.md#motion>Motion prediction<application></a></li>
<li><em><strong>Data type:</strong></em> 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Butepage et al., "Deep Representation Learning For Human Motion Prediction And Classification", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Butepage_Deep_Representation_Learning_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1702.07486.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_cmu_mocap">CMU Mocap</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<summary><em>Mao et al., "Learning Trajectory Dependencies For Human Motion Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Mao_Learning_Trajectory_Dependencies_for_Human_Motion_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.05436.pdf>arxiv</a> <a href=https://github.com/wei-mao-2019/LearnTrajDep>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_cmu_mocap">CMU Mocap</a></li>
<li><a href="datasets.md#data_3dpw">3DPW</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mane">MAnE</a></li>
<li><a href="metrics.md#metric_mpjpe">MPJPE</a></li>
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
    title = "Cmu Graphics Lab Motion Capture Database",
    howpublished = "http://mocap.cs.cmu.edu/",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=data_youtube-8m></a>
<details close>
<summary><l style="font-size:20px"><strong>Youtube-8M</strong></l> <a href=https://research.google.com/youtube8m/>link</a> <a href=>paper</a> <a href=https://arxiv.org/pdf/1609.08675.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Reda et al., "Sdc-Net: Video Prediction Using Spatially-Displaced Convolution", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Fitsum_Reda_SDC-Net_Video_prediction_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1811.00684.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_youtube-8m">Youtube-8M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
<li><a href="metrics.md#metric_l1">L1</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Reda_2018_ECCV,
    author = "Reda, Fitsum A. and Liu, Guilin and Shih, Kevin J. and Kirby, Robert and Barker, Jon and Tarjan, David and Tao, Andrew and Catanzaro, Bryan",
    title = "Sdc-Net: Video Prediction Using Spatially-Displaced Convolution",
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
    title = "Youtube-8M: A Large-Scale Video Classification Benchmark",
    journal = "arXiv:1609.08675",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=data_vist></a>
<details close>
<summary><l style="font-size:20px"><strong>Visual Storytelling (VIST)</strong></l> <a href=http://visionandlanguage.net/VIST/>link</a> <a href=https://www.aclweb.org/anthology/N16-1147.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#other>Other prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, text</li>
<li><em><strong>Task:</strong></em> Visual story</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zeng et al., "Visual Forecasting By Imitating Dynamics In Natural Sequences", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Zeng_Visual_Forecasting_by_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.05827.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_vist">VIST</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<a name=data_tv_series></a>
<details close>
<summary><l style="font-size:20px"><strong>TV Series</strong></l> <a href=https://github.com/zhenyangli/online_action>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46454-1_17>paper</a> <a href=https://arxiv.org/pdf/1604.06506.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Gao et al., "Red: Reinforced Encoder-Decoder Networks For Action Anticipation", BMVC, 2017.</em> <a href=http://www.bmva.org/bmvc/2017/papers/paper092/paper092.pdf>paper</a> <a href=https://arxiv.org/pdf/1707.04818.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_tv_human_interaction">TV Human Interaction</a></li>
<li><a href="datasets.md#data_thumos">THUMOS</a></li>
<li><a href="datasets.md#data_tv_series">TV Series</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_map">mAP</a></li>
<li><a href="metrics.md#metric_cap">cAP</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2017_BMVC,
    author = "Gao, Jiyang and Yang, Zhenheng and Nevatia, Ram",
    title = "Red: Reinforced Encoder-Decoder Networks For Action Anticipation",
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
<a name=data_oad></a>
<details close>
<summary><l style="font-size:20px"><strong>Online Action Detection (OAD)</strong></l> <a href=http://www.icst.pku.edu.cn/struct/Projects/OAD.html>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46478-7_13>paper</a> <a href=https://arxiv.org/pdf/1604.05633.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGBD, 3D pose, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liu et al., "Ssnet: Scale Selection Network For Online 3D Action Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_SSNet_Scale_Selection_CVPR_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_pku-mmd">PKU-MMD</a></li>
<li><a href="datasets.md#data_oad">OAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2018_CVPR_ssnet,
    author = "Liu, Jun and Shahroudy, Amir and Wang, Gang and Duan, Ling-Yu and Kot, Alex C.",
    title = "Ssnet: Scale Selection Network For Online 3D Action Prediction",
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
<a name=data_oa></a>
<details close>
<summary><l style="font-size:20px"><strong>Ongoing Activity (OA)</strong></l> <a href=http://www.mpii.de/ongoing-activity>link</a> <a href=https://ieeexplore.ieee.org/document/7477586>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Li et al., "Recognition Of Ongoing Complex Activities By Sequence Prediction Over A Hierarchical Label Space", WACV, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7477586>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_oa">OA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<a name=data_ntu_rgb-d></a>
<details close>
<summary><l style="font-size:20px"><strong>NTU RGB-D</strong></l> <a href=http://rose1.ntu.edu.sg/Datasets/actionRecognition.asp>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Shahroudy_NTU_RGBD_A_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1604.02808.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGBD, IR, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Wang et al., "Progressive Teacher-Student Learning For Early Action Prediction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Progressive_Teacher-Student_Learning_for_Early_Action_Prediction_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_sysu_3dhoi">SYSU 3DHOI</a></li>
<li><a href="datasets.md#data_ntu_rgb-d">NTU RGB-D</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Shahroudy_2016_CVPR,
    author = "Shahroudy, Amir and Liu, Jun and Ng, Tian-Tsong and Wang, Gang",
    title = "Ntu Rgb+D: A Large Scale Dataset For 3D Human Activity Analysis",
    booktitle = "CVPR",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=data_mu></a>
<details close>
<summary><l style="font-size:20px"><strong>Miss Universe (MU)</strong></l> <a href=http://staff.itee.uq.edu.au/lovell/MissUniverse/>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/7899781>paper</a> <a href=https://arxiv.org/pdf/1604.07547.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#other>Other prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box, scores</li>
<li><em><strong>Task:</strong></em> Miss universe</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Carvajal et al., "Towards Miss Universe Automatic Prediction: The Evening Gown Competition", ICPR, 2016.</em> <a href=https://ieeexplore.ieee.org/abstract/document/7899781>paper</a> <a href=https://arxiv.org/pdf/1604.07547.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_mu">MU</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<a name=data_bouncing_ball></a>
<details close>
<summary><l style="font-size:20px"><strong>Bouncing Ball (BB)</strong></l> <a href=https://github.com/mbchang/dynamics>link</a> <a href=https://openreview.net/pdf?id=Bkab5dqxe>paper</a> <a href=https://arxiv.org/pdf/1612.00341.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Object (simulation)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hsieh et al., "Learning To Decompose And Disentangle Representations For Video Prediction", NeurIPS, 2018.</em> <a href=https://papers.nips.cc/paper/7333-learning-to-decompose-and-disentangle-representations-for-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1806.04166.pdf>arxiv</a> <a href=https://github.com/jthsieh/DDPAE-video-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_bouncing_ball">Bouncing Ball</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mse">MSE</a></li>
<li><a href="metrics.md#metric_bce">BCE</a></li>
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
</ul><a name=datasets_2015></a>
<h2>2015</h2> <a href=#top>&uarr; top</a>
<ul><a name=data_mmnist></a>
<details close>
<summary><l style="font-size:20px"><strong>Moving MNIST (MMNIST)</strong></l> <a href=http://www.cs.toronto.edu/~nitish/unsupervised_video/>link</a> <a href=http://proceedings.mlr.press/v37/srivastava15.pdf>paper</a> <a href=https://arxiv.org/pdf/1502.04681.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a></li>
<li><em><strong>Data type:</strong></em> Grayscale</li>
<li><em><strong>Task:</strong></em> Digit</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Castrejon et al., "Improved Conditional Vrnns For Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Castrejon_Improved_Conditional_VRNNs_for_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.12165.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_cityscapes">Cityscapes</a></li>
<li><a href="datasets.md#data_bair_push">BAIR Push</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_lpips">LPIPS</a></li>
<li><a href="metrics.md#metric_fvd">FVD</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Castrejon_2019_ICCV,
    author = "Castrejon, Lluis and Ballas, Nicolas and Courville, Aaron",
    title = "Improved Conditional Vrnns For Video Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Lee et al., "Mutual Suppression Network For Video Prediction Using Disentangled Features", BMVC, 2019.</em> <a href=https://bmvc2019.org/wp-content/uploads/papers/0336-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.04810.pdf>arxiv</a> <a href=https://github.com/aras62/SF-GRU>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_kth">KTH</a></li>
<li><a href="datasets.md#data_msr">MSR</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
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
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_bouncing_ball">Bouncing Ball</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mse">MSE</a></li>
<li><a href="metrics.md#metric_bce">BCE</a></li>
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_bair_push">BAIR Push</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_sports-1m">Sports-1M</a></li>
<li><a href="datasets.md#data_visor">ViSOR</a></li>
<li><a href="datasets.md#data_prost">PROST</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
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
<summary><em>Zeng et al., "Visual Forecasting By Imitating Dynamics In Natural Sequences", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/supplemental/Zeng_Visual_Forecasting_by_ICCV_2017_supplemental.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.05827.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_human">Human</a></li>
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
<summary><em>Wang et al., "Predrnn: Recurrent Neural Networks For Predictive Learning Using Spatiotemporal Lstms", NeurIPS, 2017.</em> <a href=https://papers.nips.cc/paper/6689-predrnn-recurrent-neural-networks-for-predictive-learning-using-spatiotemporal-lstms.pdf>paper</a> <a href=https://github.com/ujjax/pred-rnn>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2017_NeurIPS,
    author = "Wang, Yunbo and Long, Mingsheng and Wang, Jianmin and Gao, Zhifeng and Yu, Philip S",
    title = "Predrnn: Recurrent Neural Networks For Predictive Learning Using Spatiotemporal Lstms",
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
@InProceedings{Srivastava_2015_ICML,
    author = "Srivastava, Nitish and Mansimov, Elman and Salakhudinov, Ruslan",
    title = "Unsupervised Learning Of Video Representations Using Lstms",
    booktitle = "ICML",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=data_thumos></a>
<details close>
<summary><l style="font-size:20px"><strong>THUMOS</strong></l> <a href=http://www.thumos.info/home.html>link</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a>,<a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liang et al., "Dual Motion Gan For Future-Flow Embedded Video Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Liang_Dual_Motion_GAN_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00284.pdf>arxiv</a> <a href=https://github.com/gurkirt/realtime-action-detection>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_thumos">THUMOS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liang_2017_ICCV,
    author = "Liang, Xiaodan and Lee, Lisa and Dai, Wei and Xing, Eric P.",
    title = "Dual Motion Gan For Future-Flow Embedded Video Prediction",
    booktitle = "ICCV",
    year = "2017"
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
<li><a href="datasets.md#data_tv_human_interaction">TV Human Interaction</a></li>
<li><a href="datasets.md#data_thumos">THUMOS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<summary><em>Gao et al., "Red: Reinforced Encoder-Decoder Networks For Action Anticipation", BMVC, 2017.</em> <a href=http://www.bmva.org/bmvc/2017/papers/paper092/paper092.pdf>paper</a> <a href=https://arxiv.org/pdf/1707.04818.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_tv_human_interaction">TV Human Interaction</a></li>
<li><a href="datasets.md#data_thumos">THUMOS</a></li>
<li><a href="datasets.md#data_tv_series">TV Series</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_map">mAP</a></li>
<li><a href="metrics.md#metric_cap">cAP</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2017_BMVC,
    author = "Gao, Jiyang and Yang, Zhenheng and Nevatia, Ram",
    title = "Red: Reinforced Encoder-Decoder Networks For Action Anticipation",
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
<li><a href="datasets.md#data_tv_human_interaction">TV Human Interaction</a></li>
<li><a href="datasets.md#data_thumos">THUMOS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<a name=data_brain4cars></a>
<details close>
<summary><l style="font-size:20px"><strong>Brain4Cars</strong></l> <a href=https://github.com/asheshjain399/ICCV2015_Brain4Cars>link</a> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Jain_Car_That_Knows_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1504.02789.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box, attribute, temporal segment, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Jain et al., "Structural-Rnn: Deep Learning On Spatio-Temporal Graphs", CVPR, 2016.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.05298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_cad-120">CAD-120</a></li>
<li><a href="datasets.md#data_brain4cars">Brain4Cars</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_recall">Recall</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
<li><a href="metrics.md#metric_f1">F1</a></li>
<li><a href="metrics.md#metric_ttm">TTM</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jain_2016_CVPR,
    author = "Jain, Ashesh and Zamir, Amir R. and Savarese, Silvio and Saxena, Ashutosh",
    title = "Structural-Rnn: Deep Learning On Spatio-Temporal Graphs",
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
<li><a href="datasets.md#data_brain4cars">Brain4Cars</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_recall">Recall</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
<li><a href="metrics.md#metric_ttm">TTM</a></li>
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
<li><a href="datasets.md#data_brain4cars">Brain4Cars</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_recall">Recall</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
<li><a href="metrics.md#metric_ttm">TTM</a></li>
<li><a href="metrics.md#metric_fp">FP</a></li>
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
<a name=data_sysu_3dhoi></a>
<details close>
<summary><l style="font-size:20px"><strong>SYSU 3DHOI</strong></l> <a href=http://www.isee-ai.cn/~hujianfang/ProjectJOULE.html>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Hu_Jointly_Learning_Heterogeneous_2015_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGBD, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Object interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Wang et al., "Progressive Teacher-Student Learning For Early Action Prediction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Progressive_Teacher-Student_Learning_for_Early_Action_Prediction_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_sysu_3dhoi">SYSU 3DHOI</a></li>
<li><a href="datasets.md#data_ntu_rgb-d">NTU RGB-D</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<summary><em>Hu et al., "Real-Time Rgb-D Activity Prediction By Soft Regression", ECCV, 2016.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46448-0_17>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_sysu_3dhoi">SYSU 3DHOI</a></li>
<li><a href="datasets.md#data_orgbd">ORGBD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2016_ECCV,
    author = "Hu, Jian-Fang and Zheng, Wei-Shi and Ma, Lianyang and Wang, Gang and Lai, Jianhuang",
    editor = "Leibe, Bastian and Matas, Jiri and Sebe, Nicu and Welling, Max",
    title = "Real-Time Rgb-D Activity Prediction By Soft Regression",
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
    title = "Jointly Learning Heterogeneous Features For Rgb-D Activity Recognition",
    booktitle = "CVPR",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=data_wider></a>
<details close>
<summary><l style="font-size:20px"><strong>WIDER</strong></l> <a href=http://yjxiong.me/event_recog/WIDER/>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Xiong_Recognize_Complex_Events_2015_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB (image), activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Safaei et al., "Still Image Action Recognition By Predicting Spatial-Temporal Pixel Evolution", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8658386>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_willow_action">Willow Action</a></li>
<li><a href="datasets.md#data_wider">WIDER</a></li>
<li><a href="datasets.md#data_stanford-40">Stanford-40</a></li>
<li><a href="datasets.md#data_bu_action">BU Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_map">mAP</a></li>
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
<a name=data_wnp></a>
<details close>
<summary><l style="font-size:20px"><strong>Watch-n-Push (WnP)</strong></l> <a href=http://watchnpatch.cs.cornell.edu/>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Wu_Watch-n-Patch_Unsupervised_Understanding_2015_CVPR_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1603.03541.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGBD, 3D pose, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kataoka et al., "Recognition Of Transitional Action For Short-Term Action Prediction Using Discriminative Temporal Cnn Feature", BMVC, 2016.</em> <a href=http://www.bmva.org/bmvc/2016/papers/paper012/paper012.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_wnp">WnP</a></li>
<li><a href="datasets.md#data_utka">UTKA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kataoka_2016_BMVC,
    author = "Kataoka, Hirokatsu and Miyashita, Yudai and Hayashi, Masaki and Iwata, Kenji and Satoh, Yutaka",
    title = "Recognition Of Transitional Action For Short-Term Action Prediction Using Discriminative Temporal Cnn Feature",
    year = "2016",
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
@InProceedings{Wu_2015_CVPR,
    author = "Wu, Chenxia and Zhang, Jiemi and Savarese, Silvio and Saxena, Ashutosh",
    title = "Watch-N-Patch: Unsupervised Understanding Of Actions And Relations",
    booktitle = "CVPR",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=data_sun_rgb-d></a>
<details close>
<summary><l style="font-size:20px"><strong>SUN RGB-D</strong></l> <a href=http://rgbd.cs.princeton.edu/>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Song_TVSum_Summarizing_Web_2015_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#other>Other prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGBD, 3D bounding box , object class</li>
<li><em><strong>Task:</strong></em> Place</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Mottaghi et al., "What Happens If... Learning To Predict The Effect Of Forces In Images", ECCV, 2016.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46493-0_17>paper</a> <a href=https://arxiv.org/pdf/1603.05600.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_sun_rgb-d">SUN RGB-D</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_pcp">PCP</a></li>
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
    title = "Tvsum: Summarizing Web Videos Using Titles",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=data_mot></a>
<details close>
<summary><l style="font-size:20px"><strong>MOT</strong></l> <a href=https://motchallenge.net/>link</a> <a href=>paper</a> <a href=https://arxiv.org/pdf/1504.01942.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sanchez-Matilla et al., "A Predictor Of Moving Objects For First-Person Vision", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8803140>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_mot">MOT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
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
<a name=data_mbi-1m></a>
<details close>
<summary><l style="font-size:20px"><strong>MicroBlog-Images (MBI-1M)</strong></l> <a href=http://academic.mywebsiteontheinternet.com/data/>link</a> <a href=https://dl.acm.org/doi/abs/10.1145/2671188.2749405>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#other>Other prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB (image), attribute, text</li>
<li><em><strong>Task:</strong></em> Tweet</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Wang et al., "Retweet Wars: Tweet Popularity Prediction Via Dynamic Multimodal Regression", WACV, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8354308>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_mbi-1m">MBI-1M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mape">MAPE</a></li>
<li><a href="metrics.md#metric_src">SRC</a></li>
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
<a name=data_gtea_gaze+></a>
<details close>
<summary><l style="font-size:20px"><strong>Georgia Tech Egocentric Activity Gaze+ (GTEA Gaze+)</strong></l> <a href=http://www.cbi.gatech.edu/fpv/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2015/papers/Li_Delving_Into_Egocentric_2015_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, gaze, mask, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Shen et al., "Egocentric Activity Prediction Via Event Modulated Attention", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Shen_Egocentric_Activity_Prediction_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_gtea_gaze+">GTEA Gaze+</a></li>
<li><a href="datasets.md#data_gtea_gaze">GTEA Gaze</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<a name=data_fppa></a>
<details close>
<summary><l style="font-size:20px"><strong>First Person Personalized Activities (FPPA)</strong></l> <a href=http://bvision11.cs.unc.edu/bigpen/yipin/ICCV2015/prediction_webpage/Prediction.html>link</a> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Zhou_Temporal_Perception_and_ICCV_2015_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhou et al., "Temporal Perception And Prediction In Ego-Centric Video", ICCV, 2015.</em> <a href=https://openaccess.thecvf.com/content_iccv_2015/papers/Zhou_Temporal_Perception_and_ICCV_2015_paper.pdf>paper</a> <a href=https://github.com/aditya7874/Activity-Prediction-in-EgoCentric-Videos>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_fppa">FPPA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<a name=data_cmu_panoptic></a>
<details close>
<summary><l style="font-size:20px"><strong>CMU Panoptic</strong></l> <a href=http://domedb.perception.cs.cmu.edu/dataset.html>link</a> <a href=https://openaccess.thecvf.com/content_iccv_2015/papers/Joo_Panoptic_Studio_A_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1612.03153.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a>,<a href=papers.md#motion>Motion prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGBD, multiview, 3D pose, 3D facial landmark</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Joo et al., "Towards Social Artificial Intelligence: Nonverbal Social Signal Prediction In A Triadic Interaction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Joo_Towards_Social_Artificial_Intelligence_Nonverbal_Social_Signal_Prediction_in_a_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.04158.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_cmu_panoptic">CMU Panoptic</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<a name=data_atari></a>
<details close>
<summary><l style="font-size:20px"><strong>Atari</strong></l> <a href=https://github.com/junhyukoh/nips2015-action-conditional-video-prediction>link</a> <a href=https://papers.nips.cc/paper/5859-action-conditional-video-prediction-using-deep-networks-in-atari-games.pdf>paper</a> <a href=https://arxiv.org/pdf/1507.08750.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Game</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Oh et al., "Action-Conditional Video Prediction Using Deep Networks In Atari Games", NeurIPS, 2015.</em> <a href=https://papers.nips.cc/paper/5859-action-conditional-video-prediction-using-deep-networks-in-atari-games.pdf>paper</a> <a href=https://arxiv.org/pdf/1507.08750.pdf>arxiv</a> <a href=https://github.com/junhyukoh/nips2015-action-conditional-video-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_atari">Atari</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Oh_2015_NeurIPS,
    author = "Oh, Junhyuk and Guo, Xiaoxiao and Lee, Honglak and Lewis, Richard L and Singh, Satinder",
    title = "Action-Conditional Video Prediction Using Deep Networks In Atari Games",
    booktitle = "NeurIPS",
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
@InProceedings{Oh_2015_NeurIPS,
    author = "Oh, Junhyuk and Guo, Xiaoxiao and Lee, Honglak and Lewis, Richard L and Singh, Satinder",
    title = "Action-Conditional Video Prediction Using Deep Networks In Atari Games",
    booktitle = "NeurIPS",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=data_amazon></a>
<details close>
<summary><l style="font-size:20px"><strong>Amazon</strong></l> <a href=http://jmcauley.ucsd.edu/data/amazon/index_2014.html>link</a> <a href=https://dl.acm.org/doi/abs/10.1145/2766462.2767755>paper</a> <a href=https://arxiv.org/pdf/1506.04757.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#other>Other prediction<application></a></li>
<li><em><strong>Data type:</strong></em> Features, attribute, text</li>
<li><em><strong>Task:</strong></em> Fashion</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Al-Halah et al., "Fashion Forward: Forecasting Visual Style In Fashion", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Al-Halah_Fashion_Forward_Forecasting_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.06394.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_amazon">Amazon</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mae">MAE</a></li>
<li><a href="metrics.md#metric_mape">MAPE</a></li>
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
</ul><a name=datasets_2014></a>
<h2>2014</h2> <a href=#top>&uarr; top</a>
<ul><a name=data_human3.6m></a>
<details close>
<summary><l style="font-size:20px"><strong>Human3.6M</strong></l> <a href=http://vision.imar.ro/human3.6m/description.php>link</a> <a href=https://ieeexplore.ieee.org/document/6682899>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a>,<a href=papers.md#action>Action prediction<application></a>,<a href=papers.md#motion>Motion prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Xu et al., "Structure Preserving Video Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers_backup/Xu_Structure_Preserving_Video_CVPR_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_bair_push">BAIR Push</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_human">Human</a></li>
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mse">MSE</a></li>
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_human">Human</a></li>
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_bair_push">BAIR Push</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<summary><em>Butepage et al., "Deep Representation Learning For Human Motion Prediction And Classification", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Butepage_Deep_Representation_Learning_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1702.07486.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_cmu_mocap">CMU Mocap</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<summary><em>Gopalakrishnan et al., "A Neural Temporal Model For Human Motion Prediction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Gopalakrishnan_A_Neural_Temporal_Model_for_Human_Motion_Prediction_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1809.03036.pdf>arxiv</a> <a href=https://github.com/cr7anand/neural_temporal_models>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mane">MAnE</a></li>
<li><a href="metrics.md#metric_npss">NPSS</a></li>
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_mouse_fish">Mouse Fish</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mje">MJE</a></li>
<li><a href="metrics.md#metric_run_time">Run Time</a></li>
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mane">MAnE</a></li>
<li><a href="metrics.md#metric_human">Human</a></li>
<li><a href="metrics.md#metric_pskl">PSKL</a></li>
<li><a href="metrics.md#metric_psent">PSEnt</a></li>
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_cmu_mocap">CMU Mocap</a></li>
<li><a href="datasets.md#data_3dpw">3DPW</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mane">MAnE</a></li>
<li><a href="metrics.md#metric_mpjpe">MPJPE</a></li>
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mane">MAnE</a></li>
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
<summary><em>Zhang et al., "Predicting 3D Human Dynamics From Video", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Predicting_3D_Human_Dynamics_From_Video_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.04781.pdf>arxiv</a> <a href={https://jasonyzhang.com/phd/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
<li><a href="datasets.md#data_instavariety">InstaVariety</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_pck">PCK</a></li>
<li><a href="metrics.md#metric_mpjpe">MPJPE</a></li>
<li><a href="metrics.md#metric_re">RE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2019_ICCV,
    author = "Zhang, Jason Y. and Felsen, Panna and Kanazawa, Angjoo and Malik, Jitendra",
    title = "Predicting 3D Human Dynamics From Video",
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mje">MJE</a></li>
<li><a href="metrics.md#metric_pck">PCK</a></li>
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mane">MAnE</a></li>
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mane">MAnE</a></li>
<li><a href="metrics.md#metric_human">Human</a></li>
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mane">MAnE</a></li>
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
<li><a href="datasets.md#data_mpii_human_pose">MPII Human Pose</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_pck">PCK</a></li>
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mane">MAnE</a></li>
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
<summary><em>Jain et al., "Structural-Rnn: Deep Learning On Spatio-Temporal Graphs", CVPR, 2016.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.05298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mane">MAnE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jain_2016_CVPR,
    author = "Jain, Ashesh and Zamir, Amir R. and Savarese, Silvio and Saxena, Ashutosh",
    title = "Structural-Rnn: Deep Learning On Spatio-Temporal Graphs",
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mane">MAnE</a></li>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
    title = "Human3.6M: Large Scale Datasets And Predictive Methods For 3D Human Sensing In Natural Environments",
    journal = "PAMI",
    volume = "36",
    number = "7",
    pages = "1325-1339",
    year = "2014"
}
</pre>
</details>

</ul></details>
<a name=data_sports-1m></a>
<details close>
<summary><l style="font-size:20px"><strong>Sports-1M</strong></l> <a href=https://cs.stanford.edu/people/karpathy/deepvideo/>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Karpathy_Large-scale_Video_Classification_2014_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a>,<a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Sport</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Lu et al., "Flexible Spatio-Temporal Networks For Video Prediction", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lu_Flexible_Spatio-Temporal_Networks_CVPR_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_sports-1m">Sports-1M</a></li>
<li><a href="datasets.md#data_visor">ViSOR</a></li>
<li><a href="datasets.md#data_prost">PROST</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_sports-1m">Sports-1M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_bit">BIT</a></li>
<li><a href="datasets.md#data_sports-1m">Sports-1M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<a name=data_breakfast></a>
<details close>
<summary><l style="font-size:20px"><strong>Breakfast</strong></l> <a href=http://serre-lab.clps.brown.edu/resource/breakfast-actions-dataset/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2014/papers/Kuehne_The_Language_of_2014_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Gammulle et al., "Forecasting Future Action Sequences With Neural Memory Networks", BMVC, 2019.</em> <a href=https://bmvc2019.org/wp-content/uploads/papers/0585-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1909.09278.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_breakfast">Breakfast</a></li>
<li><a href="datasets.md#data_50salad">50Salad</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<li><a href="datasets.md#data_cad-120">CAD-120</a></li>
<li><a href="datasets.md#data_mpii_cooking">MPII Cooking</a></li>
<li><a href="datasets.md#data_breakfast">Breakfast</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_recall">Recall</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
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
<li><a href="datasets.md#data_breakfast">Breakfast</a></li>
<li><a href="datasets.md#data_50salad">50Salad</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<a name=data_orgbd></a>
<details close>
<summary><l style="font-size:20px"><strong>Online RGBD Action Dataset (ORGBD)</strong></l> <a href=https://sites.google.com/site/skicyyu/orgbd>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-16814-2_4>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGBD, bounding box, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hu et al., "Real-Time Rgb-D Activity Prediction By Soft Regression", ECCV, 2016.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46448-0_17>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_sysu_3dhoi">SYSU 3DHOI</a></li>
<li><a href="datasets.md#data_orgbd">ORGBD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2016_ECCV,
    author = "Hu, Jian-Fang and Zheng, Wei-Shi and Ma, Lianyang and Wang, Gang and Lai, Jianhuang",
    editor = "Leibe, Bastian and Matas, Jiri and Sebe, Nicu and Welling, Max",
    title = "Real-Time Rgb-D Activity Prediction By Soft Regression",
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
@InProceedings{Yu_2014_ACCV,
    author = "Yu, Gang and Liu, Zicheng and Yuan, Junsong",
    editor = "Cremers, Daniel and Reid, Ian and Saito, Hideo and Yang, Ming-Hsuan",
    title = "Discriminative Orderlet Mining For Real-Time Recognition Of Human-Object Interaction",
    booktitle = "ACCV",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=data_mpii_human_pose></a>
<details close>
<summary><l style="font-size:20px"><strong>MPII Human Pose</strong></l> <a href=http://human-pose.mpi-inf.mpg.de/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2014/papers/Andriluka_2D_Human_Pose_2014_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#motion>Motion prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chao et al., "Forecasting Human Dynamics From Static Images", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Chao_Forecasting_Human_Dynamics_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1704.03432.pdf>arxiv</a> <a href=https://github.com/ywchao/image-play>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
<li><a href="datasets.md#data_mpii_human_pose">MPII Human Pose</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_pck">PCK</a></li>
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
    title = "2D Human Pose Estimation: New Benchmark And State Of The Art Analysis",
    booktitle = "CVPR",
    year = "2014"
}
</pre>
</details>

</ul></details>
</ul><a name=datasets_2013></a>
<h2>2013</h2> <a href=#top>&uarr; top</a>
<ul><a name=data_penn_action></a>
<details close>
<summary><l style="font-size:20px"><strong>Penn Action</strong></l> <a href=http://dreamdragon.github.io/PennAction/>link</a> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2013/papers/Zhang_From_Actemes_to_2013_ICCV_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a>,<a href=papers.md#motion>Motion prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box, pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ye et al., "Compositional Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ye_Compositional_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.08522.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
<li><a href="datasets.md#data_shapestack">ShapeStack</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_lpips">LPIPS</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ye_2019_ICCV,
    author = "Ye, Yufei and Singh, Maneesh and Gupta, Abhinav and Tulsiani, Shubham",
    title = "Compositional Video Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Kim et al., "Unsupervised Keypoint Learning For Guiding Class-Conditional Video Prediction", NeurIPS, 2019.</em> <a href=https://papers.nips.cc/paper/8637-unsupervised-keypoint-learning-for-guiding-class-conditional-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.02027.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
<li><a href="datasets.md#data_uva-nemo">UvA-NEMO</a></li>
<li><a href="datasets.md#data_mgif">MGIF</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_fvd">FVD</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kim_2019_NeurIPS,
    author = "Kim, Yunji and Nam, Seonghyeon and Cho, In and Kim, Seon Joo",
    title = "Unsupervised Keypoint Learning For Guiding Class-Conditional Video Prediction",
    booktitle = "NeurIPS",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Tang et al., "Pose Guided Global And Local Gan For Appearance Preserving Human Video Prediction", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8803792>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
<li><a href="datasets.md#data_jhmdb">JHMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tang_2019_ICIP,
    author = "Tang, J. and Hu, H. and Zhou, Q. and Shan, H. and Tian, C. and Quek, T. Q. S.",
    booktitle = "ICIP",
    title = "Pose Guided Global And Local Gan For Appearance Preserving Human Video Prediction",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhao et al., "Learning To Forecast And Refine Residual Motion For Image-To-Video Generation", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Long_Zhao_Learning_to_Forecast_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1807.09951.pdf>arxiv</a> <a href=https://github.com/garyzhao/FRGAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
<li><a href="datasets.md#data_mug">MUG</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhao_2018_ECCV,
    author = "Zhao, Long and Peng, Xi and Tian, Yu and Kapadia, Mubbasir and Metaxas, Dimitris",
    title = "Learning To Forecast And Refine Residual Motion For Image-To-Video Generation",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Walker et al., "The Pose Knows: Video Forecasting By Generating Pose Futures", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Walker_The_Pose_Knows_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.00053.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_is">IS</a></li>
<li><a href="metrics.md#metric_mmd">MMD</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Walker_2017_ICCV,
    author = "Walker, Jacob and Marino, Kenneth and Gupta, Abhinav and Hebert, Martial",
    title = "The Pose Knows: Video Forecasting By Generating Pose Futures",
    booktitle = "ICCV",
    year = "2017"
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_human">Human</a></li>
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
<summary><em>Zhang et al., "Predicting 3D Human Dynamics From Video", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Predicting_3D_Human_Dynamics_From_Video_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.04781.pdf>arxiv</a> <a href={https://jasonyzhang.com/phd/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
<li><a href="datasets.md#data_instavariety">InstaVariety</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_pck">PCK</a></li>
<li><a href="metrics.md#metric_mpjpe">MPJPE</a></li>
<li><a href="metrics.md#metric_re">RE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2019_ICCV,
    author = "Zhang, Jason Y. and Felsen, Panna and Kanazawa, Angjoo and Malik, Jitendra",
    title = "Predicting 3D Human Dynamics From Video",
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
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mje">MJE</a></li>
<li><a href="metrics.md#metric_pck">PCK</a></li>
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
<summary><em>Chao et al., "Forecasting Human Dynamics From Static Images", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Chao_Forecasting_Human_Dynamics_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1704.03432.pdf>arxiv</a> <a href=https://github.com/ywchao/image-play>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
<li><a href="datasets.md#data_mpii_human_pose">MPII Human Pose</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_pck">PCK</a></li>
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
@InProceedings{Zhang_2013_ICCV,
    author = "Zhang, Weiyu and Zhu, Menglong and Derpanis, Konstantinos G",
    title = "From Actemes To Action: A Strongly-Supervised Representation For Detailed Action Understanding",
    booktitle = "ICCV",
    year = "2013"
}
</pre>
</details>

</ul></details>
<a name=data_jhmdb></a>
<details close>
<summary><l style="font-size:20px"><strong>Joint-Annotated Human Motion Data Base (JHMDB)</strong></l> <a href=http://jhmdb.is.tue.mpg.de/>link</a> <a href=https://openaccess.thecvf.com/content_iccv_2013/papers/Jhuang_Towards_Understanding_Action_2013_ICCV_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a>,<a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, mask, activity label, pose, optical flow</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Tang et al., "Pose Guided Global And Local Gan For Appearance Preserving Human Video Prediction", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8803792>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
<li><a href="datasets.md#data_jhmdb">JHMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tang_2019_ICIP,
    author = "Tang, J. and Hu, H. and Zhou, Q. and Shan, H. and Tian, C. and Quek, T. Q. S.",
    booktitle = "ICIP",
    title = "Pose Guided Global And Local Gan For Appearance Preserving Human Video Prediction",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sun et al., "Relational Action Forecasting", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Sun_Relational_Action_Forecasting_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.04231.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_jhmdb">JHMDB</a></li>
<li><a href="datasets.md#data_ava">AVA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ap">AP</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2019_CVPR,
    author = "Sun, Chen and Shrivastava, Abhinav and Vondrick, Carl and Sukthankar, Rahul and Murphy, Kevin and Schmid, Cordelia",
    title = "Relational Action Forecasting",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhao et al., "Spatiotemporal Feature Residual Propagation For Action Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhao_Spatiotemporal_Feature_Residual_Propagation_for_Action_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://github.com/JoeHEZHAO/Spatiotemporal-Residual-Propagation>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_jhmdb">JHMDB</a></li>
<li><a href="datasets.md#data_bit">BIT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhao_2019_ICCV,
    author = "Zhao, He and Wildes, Richard P.",
    title = "Spatiotemporal Feature Residual Propagation For Action Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Shi et al., "Action Anticipation With Rbf Kernelized Feature Mapping Rnn", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yuge_Shi_Action_Anticipation_with_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.07806.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_uti">UTI</a></li>
<li><a href="datasets.md#data_jhmdb">JHMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shi_2018_ECCV,
    author = "Shi, Yuge and Fernando, Basura and Hartley, Richard",
    title = "Action Anticipation With Rbf Kernelized Feature Mapping Rnn",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sadegh et al., "Encouraging Lstms To Anticipate Actions Very Early", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Aliakbarian_Encouraging_LSTMs_to_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_uti">UTI</a></li>
<li><a href="datasets.md#data_jhmdb">JHMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Aliakbarian_2017_ICCV,
    author = "Sadegh Aliakbarian, Mohammad and Sadat Saleh, Fatemeh and Salzmann, Mathieu and Fernando, Basura and Petersson, Lars and Andersson, Lars",
    title = "Encouraging Lstms To Anticipate Actions Very Early",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Singh et al., "Online Real-Time Multiple Spatiotemporal Action Localisation And Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Singh_Online_Real-Time_Multiple_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1611.08563.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_jhmdb">JHMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_map">mAP</a></li>
<li><a href="metrics.md#metric_auc">AUC</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Jhuang_2013_ICCV,
    author = "Jhuang, H. and Gall, J. and Zuffi, S. and Schmid, C. and Black, M. J.",
    title = "Towards Understanding Action Recognition",
    booktitle = "ICCV",
    year = "2013"
}
</pre>
</details>

</ul></details>
<a name=data_cad-120></a>
<details close>
<summary><l style="font-size:20px"><strong>CAD-120</strong></l> <a href=http://pr.cs.cornell.edu/humanactivities/data.php>link</a> <a href=https://journals.sagepub.com/doi/abs/10.1177/0278364913478446>paper</a> <a href=https://arxiv.org/pdf/1210.1207.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGBD, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Alati et al., "Help By Predicting What To Do", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8803155>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_cad-120">CAD-120</a></li>
<li><a href="datasets.md#data_mpii_cooking">MPII Cooking</a></li>
<li><a href="datasets.md#data_breakfast">Breakfast</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_recall">Recall</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
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
<summary><em>Schydlo et al., "Anticipation In Human-Robot Cooperation: A Recurrent Neural Network Approach For Multiple Action Sequences Prediction", ICRA, 2018.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8460924>paper</a> <a href=https://arxiv.org/pdf/1802.10503.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_cad-120">CAD-120</a></li>
<li><a href="datasets.md#data_acticipate">ACTICIPATE</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_f1">F1</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Schydlo_2018_ICRA_2,
    author = "Schydlo, P. and Rakovic, M. and Jamone, L. and Santos-Victor, J.",
    booktitle = "ICRA",
    title = "Anticipation In Human-Robot Cooperation: A Recurrent Neural Network Approach For Multiple Action Sequences Prediction",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Qi et al., "Predicting Human Activities Using Stochastic Grammar", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Qi_Predicting_Human_Activities_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00945.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_cad-120">CAD-120</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_recall">Recall</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
<li><a href="metrics.md#metric_f1">F1</a></li>
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
<summary><em>Jain et al., "Structural-Rnn: Deep Learning On Spatio-Temporal Graphs", CVPR, 2016.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.05298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_cad-120">CAD-120</a></li>
<li><a href="datasets.md#data_brain4cars">Brain4Cars</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_recall">Recall</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
<li><a href="metrics.md#metric_f1">F1</a></li>
<li><a href="metrics.md#metric_ttm">TTM</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jain_2016_CVPR,
    author = "Jain, Ashesh and Zamir, Amir R. and Savarese, Silvio and Saxena, Ashutosh",
    title = "Structural-Rnn: Deep Learning On Spatio-Temporal Graphs",
    booktitle = "CVPR",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Hu et al., "Human Intent Forecasting Using Intrinsic Kinematic Constraints", IROS, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7759141>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_cad-120">CAD-120</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_recall">Recall</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
<li><a href="metrics.md#metric_f1">F1</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Koppula_2013_IJRR,
    author = "Koppula, Hema Swetha and Gupta, Rudhir and Saxena, Ashutosh",
    title = "Learning Human Activities And Object Affordances From Rgb-D Videos",
    journal = "IJRR",
    volume = "32",
    number = "8",
    pages = "951--970",
    year = "2013"
}
</pre>
</details>

</ul></details>
<a name=data_50salad></a>
<details close>
<summary><l style="font-size:20px"><strong>50Salads</strong></l> <a href=https://cvip.computing.dundee.ac.uk/datasets/foodpreparation/50salads/>link</a> <a href=https://dl.acm.org/doi/abs/10.1145/2493432.2493482>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGBD, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ke et al., "Time-Conditioned Action Anticipation In One Shot", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Ke_Time-Conditioned_Action_Anticipation_in_One_Shot_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets.md#data_50salad">50Salad</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_recall">Recall</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
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
<summary><em>Gammulle et al., "Forecasting Future Action Sequences With Neural Memory Networks", BMVC, 2019.</em> <a href=https://bmvc2019.org/wp-content/uploads/papers/0585-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1909.09278.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_breakfast">Breakfast</a></li>
<li><a href="datasets.md#data_50salad">50Salad</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<summary><em>Abu et al., "When Will You Do What? - Anticipating Temporal Occurrences Of Activities", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Abu_Farha_When_Will_You_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.00892.pdf>arxiv</a> <a href=https://github.com/yabufarha/anticipating-activities>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_breakfast">Breakfast</a></li>
<li><a href="datasets.md#data_50salad">50Salad</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
@InProceedings{Stein_2013_IJCPUC,
    author = "Stein, Sebastian and McKenna, Stephen J",
    title = "Combining Embedded Accelerometers With Computer Vision For Recognizing Food Preparation Activities",
    booktitle = "UbiComp",
    year = "2013"
}
</pre>
</details>

</ul></details>
<a name=data_daimler_path></a>
<details close>
<summary><l style="font-size:20px"><strong>Daimler Path</strong></l> <a href=http://www.gavrila.net/Datasets/Daimler_Pedestrian_Benchmark_D/Pedestrian_Path_Predict_GCPR_1/pedestrian_path_predict_gcpr_1.html>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-642-40602-7_18>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> Stereo grayscale, bounding box, temporal segment , vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Schulz et al., "Pedestrian Intention Recognition Using Latent-Dynamic Conditional Random Fields", IV, 2015.</em> <a href=https://ieeexplore.ieee.org/document/7225754>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_daimler_path">Daimler Path</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Schulz_2015_IV,
    author = "Schulz, Andreas Th and Stiefelhagen, Rainer",
    title = "Pedestrian Intention Recognition Using Latent-Dynamic Conditional Random Fields",
    booktitle = "IV",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Schulz et al., "A Controlled Interactive Multiple Model Filter For Combined Pedestrian Intention Recognition And Path Prediction", ITSC, 2015.</em> <a href=https://ieeexplore.ieee.org/abstract/document/7313129>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_daimler_path">Daimler Path</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_ed">ED</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Schneider_2013_GCPR,
    author = "Schneider, Nicolas and Gavrila, Dariu M",
    title = "Pedestrian Path Prediction With Recursive Bayesian Filters: A Comparative Study",
    booktitle = "GCPR",
    year = "2013"
}
</pre>
</details>

</ul></details>
<a name=data_chuk_avenue></a>
<details close>
<summary><l style="font-size:20px"><strong>CHUK Avenue</strong></l> <a href=http://www.cse.cuhk.edu.hk/leojia/projects/detectabnormal/dataset.html>link</a> <a href=https://openaccess.thecvf.com/content_iccv_2013/papers/Lu_Abnormal_Event_Detection_2013_ICCV_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a>,<a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box, anomaly, temporal segment</li>
<li><em><strong>Task:</strong></em> Surveillance, anomaly</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle Gan", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_chuk_avenue">CHUK Avenue</a></li>
<li><a href="datasets.md#data_shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kwon_2019_CVPR,
    author = "Kwon, Yong-Hoon and Park, Min-Gyu",
    title = "Predicting Future Frames Using Retrospective Cycle Gan",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Encoding Crowd Interaction With Deep Neural Network For Pedestrian Trajectory Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/2136.pdf>paper</a> <a href=https://github.com/svip-lab/CIDNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_gc">GC</a></li>
<li><a href="datasets.md#data_chuk">CHUK</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
<li><a href="metrics.md#metric_ande">ANDE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Lu_2013_ICCV,
    author = "Lu, Cewu and Shi, Jianping and Jia, Jiaya",
    title = "Abnormal Event Detection At 150 Fps In Matlab",
    booktitle = "ICCV",
    year = "2013"
}
</pre>
</details>

</ul></details>
<a name=data_atc></a>
<details close>
<summary><l style="font-size:20px"><strong>ATC</strong></l> <a href=https://irc.atr.jp/crest2010_HRI/ATC_dataset/>link</a> <a href=https://ieeexplore.ieee.org/document/6636027>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, trajectory, attribute</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Rudenko et al., "Joint Long-Term Prediction Of Human Motion Using A Planning-Based Social Force Approach", ICRA, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8460527>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_atc">ATC</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_run_time">Run Time</a></li>
<li><a href="metrics.md#metric_mhd">MHD</a></li>
<li><a href="metrics.md#metric_nlp">NLP</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rudenko_2018_ICRA,
    author = "Rudenko, A. and Palmieri, L. and Arras, K. O.",
    booktitle = "ICRA",
    title = "Joint Long-Term Prediction Of Human Motion Using A Planning-Based Social Force Approach",
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
@Article{Brvsvcic_2013_HMS,
    author = "Br\vs\vci\'c, Dra{\v{z}}en and Kanda, Takayuki and Ikeda, Tetsushi and Miyashita, Takahiro",
    title = "Person Tracking In Large Public Spaces Using 3-D Range Sensors",
    journal = "Transactions on Human-Machine Systems",
    volume = "43",
    number = "6",
    pages = "522--534",
    year = "2013"
}
</pre>
</details>

</ul></details>
</ul><a name=datasets_2012></a>
<h2>2012</h2> <a href=#top>&uarr; top</a>
<ul><a name=data_ucf-101></a>
<details close>
<summary><l style="font-size:20px"><strong>UCF-101</strong></l> <a href=https://www.crcv.ucf.edu/data/UCF101.php>link</a> <a href=>paper</a> <a href=https://arxiv.org/pdf/1212.0402.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a>,<a href=papers.md#action>Action prediction<application></a>,<a href=papers.md#motion>Motion prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle Gan", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_chuk_avenue">CHUK Avenue</a></li>
<li><a href="datasets.md#data_shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kwon_2019_CVPR,
    author = "Kwon, Yong-Hoon and Park, Min-Gyu",
    title = "Predicting Future Frames Using Retrospective Cycle Gan",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ho et al., "Sme-Net: Sparse Motion Estimation For Parametric Video Prediction Through Reinforcement Learning", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ho_SME-Net_Sparse_Motion_Estimation_for_Parametric_Video_Prediction_Through_Reinforcement_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_yuv">YUV</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ho_2019_ICCV,
    author = "Ho, Yung-Han and Cho, Chuan-Yuan and Peng, Wen-Hsiao and Jin, Guo-Lun",
    title = "Sme-Net: Sparse Motion Estimation For Parametric Video Prediction Through Reinforcement Learning",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhang et al., "Looking-Ahead: Neural Future Video Frame Prediction", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8803151>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2019_ICIP,
    author = "Zhang, C. and Chen, T. and Liu, H. and Shen, Q. and Ma, Z.",
    booktitle = "ICIP",
    title = "Looking-Ahead: Neural Future Video Frame Prediction",
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<summary><em>Liu et al., "Dyan: A Dynamical Atoms-Based Network For Video Prediction", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Wenqian_Liu_DYAN_A_Dynamical_ECCV_2018_paper.pdf)>paper</a> <a href=https://github.com/liuem607/DYAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2018_ECCV,
    author = "Liu, Wenqian and Sharma, Abhishek and Camps, Octavia and Sznaier, Mario",
    title = "Dyan: A Dynamical Atoms-Based Network For Video Prediction",
    booktitle = "ECCV",
    year = "2018"
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
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
<summary><em>Bhattacharjee et al., "Predicting Video Frames Using Feature Based Locally Guided Objectives", ACCV, 2019.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20870-7_42>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bhattacharjee_2018_ACCV,
    author = "Bhattacharjee, Prateep and Das, Sukhendu",
    editor = "Jawahar, C.V. and Li, Hongdong and Mori, Greg and Schindler, Konrad",
    title = "Predicting Video Frames Using Feature Based Locally Guided Objectives",
    booktitle = "ACCV",
    year = "2019"
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
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
<summary><em>Lu et al., "Flexible Spatio-Temporal Networks For Video Prediction", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lu_Flexible_Spatio-Temporal_Networks_CVPR_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_sports-1m">Sports-1M</a></li>
<li><a href="datasets.md#data_visor">ViSOR</a></li>
<li><a href="datasets.md#data_prost">PROST</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
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
<summary><em>Liang et al., "Dual Motion Gan For Future-Flow Embedded Video Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Liang_Dual_Motion_GAN_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00284.pdf>arxiv</a> <a href=https://github.com/gurkirt/realtime-action-detection>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_thumos">THUMOS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liang_2017_ICCV,
    author = "Liang, Xiaodan and Lee, Lisa and Dai, Wei and Xing, Eric P.",
    title = "Dual Motion Gan For Future-Flow Embedded Video Prediction",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Walker et al., "The Pose Knows: Video Forecasting By Generating Pose Futures", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Walker_The_Pose_Knows_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.00053.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_is">IS</a></li>
<li><a href="metrics.md#metric_mmd">MMD</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Walker_2017_ICCV,
    author = "Walker, Jacob and Marino, Kenneth and Gupta, Abhinav and Hebert, Martial",
    title = "The Pose Knows: Video Forecasting By Generating Pose Futures",
    booktitle = "ICCV",
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_sports-1m">Sports-1M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<summary><em>Wang et al., "Progressive Teacher-Student Learning For Early Action Prediction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Progressive_Teacher-Student_Learning_for_Early_Action_Prediction_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_sysu_3dhoi">SYSU 3DHOI</a></li>
<li><a href="datasets.md#data_ntu_rgb-d">NTU RGB-D</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<summary><em>Gammulle et al., "Predicting The Future: A Jointly Learnt Model For Action Anticipation", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Gammulle_Predicting_the_Future_A_Jointly_Learnt_Model_for_Action_Anticipation_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.07148.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_uti">UTI</a></li>
<li><a href="datasets.md#data_tv_human_interaction">TV Human Interaction</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gammulle_2019_ICCV,
    author = "Gammulle, Harshala and Denman, Simon and Sridharan, Sridha and Fookes, Clinton",
    title = "Predicting The Future: A Jointly Learnt Model For Action Anticipation",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhao et al., "Spatiotemporal Feature Residual Propagation For Action Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhao_Spatiotemporal_Feature_Residual_Propagation_for_Action_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://github.com/JoeHEZHAO/Spatiotemporal-Residual-Propagation>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_jhmdb">JHMDB</a></li>
<li><a href="datasets.md#data_bit">BIT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhao_2019_ICCV,
    author = "Zhao, He and Wildes, Richard P.",
    title = "Spatiotemporal Feature Residual Propagation For Action Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Safaei et al., "Still Image Action Recognition By Predicting Spatial-Temporal Pixel Evolution", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8658386>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_willow_action">Willow Action</a></li>
<li><a href="datasets.md#data_wider">WIDER</a></li>
<li><a href="datasets.md#data_stanford-40">Stanford-40</a></li>
<li><a href="datasets.md#data_bu_action">BU Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_map">mAP</a></li>
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
<summary><em>Chen et al., "Part-Activated Deep Reinforcement Learning For Action Prediction", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Lei_Chen_Part-Activated_Deep_Reinforcement_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_uti">UTI</a></li>
<li><a href="datasets.md#data_bit">BIT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2018_ECCV,
    author = "Chen, Lei and Lu, Jiwen and Song, Zhanjie and Zhou, Jie",
    title = "Part-Activated Deep Reinforcement Learning For Action Prediction",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Shi et al., "Action Anticipation With Rbf Kernelized Feature Mapping Rnn", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yuge_Shi_Action_Anticipation_with_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.07806.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_uti">UTI</a></li>
<li><a href="datasets.md#data_jhmdb">JHMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shi_2018_ECCV,
    author = "Shi, Yuge and Fernando, Basura and Hartley, Richard",
    title = "Action Anticipation With Rbf Kernelized Feature Mapping Rnn",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Cho et al., "A Temporal Sequence Learning For Action Recognition And Prediction", WACV, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8354149>paper</a> <a href=https://arxiv.org/pdf/1906.06813.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_hmdb">HMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cho_2018_WACV,
    author = "Cho, S. and Foroosh, H.",
    booktitle = "WACV",
    title = "A Temporal Sequence Learning For Action Recognition And Prediction",
    year = "2018"
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_bit">BIT</a></li>
<li><a href="datasets.md#data_sports-1m">Sports-1M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<details close>
<summary><em>Sadegh et al., "Encouraging Lstms To Anticipate Actions Very Early", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Aliakbarian_Encouraging_LSTMs_to_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_uti">UTI</a></li>
<li><a href="datasets.md#data_jhmdb">JHMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Aliakbarian_2017_ICCV,
    author = "Sadegh Aliakbarian, Mohammad and Sadat Saleh, Fatemeh and Salzmann, Mathieu and Fernando, Basura and Petersson, Lars and Andersson, Lars",
    title = "Encouraging Lstms To Anticipate Actions Very Early",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Singh et al., "Online Real-Time Multiple Spatiotemporal Action Localisation And Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Singh_Online_Real-Time_Multiple_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1611.08563.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_jhmdb">JHMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_map">mAP</a></li>
<li><a href="metrics.md#metric_auc">AUC</a></li>
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
<summary><em>Xu et al., "Human Activities Prediction By Learning Combinatorial Sparse Representations", ICIP, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7532452>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_uti">UTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2016_ICIP,
    author = "Xu, K. and Qin, Z. and Wang, G.",
    booktitle = "ICIP",
    title = "Human Activities Prediction By Learning Combinatorial Sparse Representations",
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
@Article{Soomro_2012_arxiv,
    author = "Soomro, Khurram and Zamir, Amir Roshan and Shah, Mubarak",
    title = "Ucf101: A Dataset Of 101 Human Actions Classes From Videos In The Wild",
    journal = "arXiv:1212.0402",
    year = "2012"
}
</pre>
</details>

</ul></details>
<a name=data_kitti></a>
<details close>
<summary><l style="font-size:20px"><strong>KITTI</strong></l> <a href=http://www.cvlibs.net/datasets/kitti/>link</a> <a href=https://ieeexplore.ieee.org/document/6248074>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a>,<a href=papers.md#trajectory>Trajectory prediction<application></a>,<a href=papers.md#other>Other prediction<application></a></li>
<li><em><strong>Data type:</strong></em> Stereo RGB, LIDAR, bounding box,  optical flow, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle Gan", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_chuk_avenue">CHUK Avenue</a></li>
<li><a href="datasets.md#data_shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kwon_2019_CVPR,
    author = "Kwon, Yong-Hoon and Park, Min-Gyu",
    title = "Predicting Future Frames Using Retrospective Cycle Gan",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Gao et al., "Disentangling Propagation And Generation For Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Gao_Disentangling_Propagation_and_Generation_for_Video_Prediction_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2019_ICCV,
    author = "Gao, Hang and Xu, Huazhe and Cai, Qi-Zhi and Wang, Ruth and Yu, Fisher and Darrell, Trevor",
    title = "Disentangling Propagation And Generation For Video Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ho et al., "Deep Reinforcement Learning For Video Prediction", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8803825>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_yuv">YUV</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ho_2019_ICIP,
    author = "Ho, Y. and Cho, C. and Peng, W.",
    booktitle = "ICIP",
    title = "Deep Reinforcement Learning For Video Prediction",
    year = "2019"
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<summary><em>Liu et al., "Dyan: A Dynamical Atoms-Based Network For Video Prediction", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Wenqian_Liu_DYAN_A_Dynamical_ECCV_2018_paper.pdf)>paper</a> <a href=https://github.com/liuem607/DYAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2018_ECCV,
    author = "Liu, Wenqian and Sharma, Abhishek and Camps, Octavia and Sznaier, Mario",
    title = "Dyan: A Dynamical Atoms-Based Network For Video Prediction",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Bhattacharjee et al., "Predicting Video Frames Using Feature Based Locally Guided Objectives", ACCV, 2019.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20870-7_42>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bhattacharjee_2018_ACCV,
    author = "Bhattacharjee, Prateep and Das, Sukhendu",
    editor = "Jawahar, C.V. and Li, Hongdong and Mori, Greg and Schindler, Konrad",
    title = "Predicting Video Frames Using Feature Based Locally Guided Objectives",
    booktitle = "ACCV",
    year = "2019"
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
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
<summary><em>Jin et al., "Varnet: Exploring Variations For Unsupervised Video Prediction", IROS, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8594264>paper</a> <a href=https://github.com/jinbeibei/VarNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jin_2018_IROS,
    author = "Jin, B. and Hu, Y. and Zeng, Y. and Tang, Q. and Liu, S. and Ye, J.",
    booktitle = "IROS",
    title = "Varnet: Exploring Variations For Unsupervised Video Prediction",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liang et al., "Dual Motion Gan For Future-Flow Embedded Video Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Liang_Dual_Motion_GAN_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00284.pdf>arxiv</a> <a href=https://github.com/gurkirt/realtime-action-detection>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_thumos">THUMOS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liang_2017_ICCV,
    author = "Liang, Xiaodan and Lee, Lisa and Dai, Wei and Xing, Eric P.",
    title = "Dual Motion Gan For Future-Flow Embedded Video Prediction",
    booktitle = "ICCV",
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_sports-1m">Sports-1M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<summary><em>Srikanth et al., "Infer: Intermediate Representations For Future Prediction", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8968553>paper</a> <a href=https://arxiv.org/pdf/1903.10641.pdf>arxiv</a> <a href=https://rebrand.ly/INFER-results>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_cityscapes">Cityscapes</a></li>
<li><a href="datasets.md#data_oxford">Oxford</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Srikanth_2019_IROS,
    author = "Srikanth, Shashank and Ansari, Junaid Ahmed and Sharma, Sarthak and others",
    booktitle = "IROS",
    title = "Infer: Intermediate Representations For Future Prediction",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Rhinehart et al., "R2P2: A Reparameterized Pushforward Policy For Diverse, Precise Generative Path Forecasting", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Nicholas_Rhinehart_R2P2_A_ReparameteRized_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_meanmsd">meanMSD</a></li>
<li><a href="metrics.md#metric_minmsd">minMSD</a></li>
<li><a href="metrics.md#metric_ce">CE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rhinehart_2018_ECCV,
    author = "Rhinehart, Nicholas and Kitani, Kris M. and Vernaza, Paul",
    title = "R2P2: A Reparameterized Pushforward Policy For Diverse, Precise Generative Path Forecasting",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Lee et al., "Desire: Distant Future Prediction In Dynamic Scenes With Interacting Agents", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lee_DESIRE_Distant_Future_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1704.04394.pdf>arxiv</a> <a href=https://github.com/yadrimz/DESIRE>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ed">ED</a></li>
<li><a href="metrics.md#metric_mined">minED</a></li>
<li><a href="metrics.md#metric_maxd">maxD</a></li>
<li><a href="metrics.md#metric_miss_rate">Miss rate</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lee_2017_CVPR,
    author = "Lee, Namhoon and Choi, Wongun and Vernaza, Paul and Choy, Christopher B. and Torr, Philip H. S. and Chandraker, Manmohan",
    title = "Desire: Distant Future Prediction In Dynamic Scenes With Interacting Agents",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Mohajerin et al., "Multi-Step Prediction Of Occupancy Grid Maps With Recurrent Neural Networks", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Mohajerin_Multi-Step_Prediction_of_Occupancy_Grid_Maps_With_Recurrent_Neural_Networks_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.09395.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_run_time">Run Time</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_tp">TP</a></li>
<li><a href="metrics.md#metric_tn">TN</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mohajerin_2019_CVPR,
    author = "Mohajerin, Nima and Rohani, Mohsen",
    title = "Multi-Step Prediction Of Occupancy Grid Maps With Recurrent Neural Networks",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Guizilini et al., "Dynamic Hilbert Maps: Real-Time Occupancy Predictions In Changing Environments", ICRA, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8793914>paper</a> <a href=https://arxiv.org/pdf/1912.02149.pdf>arxiv</a> <a href=https://bitbucket.org/vguizilini/cvpp/src>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_f1">F1</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Guizilini_2019_ICRA,
    author = "Guizilini, V. and Senanayake, R. and Ramos, F.",
    booktitle = "ICRA",
    title = "Dynamic Hilbert Maps: Real-Time Occupancy Predictions In Changing Environments",
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
@InProceedings{Geiger_2012_CVPR,
    author = "Geiger, Andreas and Lenz, Philip and Urtasun, Raquel",
    title = "Are We Ready For Autonomous Driving? The Kitti Vision Benchmark Suite",
    booktitle = "CVPR",
    year = "2012"
}
</pre>
</details>

</ul></details>
<a name=data_gc></a>
<details close>
<summary><l style="font-size:20px"><strong>New York Grand Central (GC)</strong></l> <a href=http://www.ee.cuhk.edu.hk/~xgwang/grandcentral.html>link</a> <a href=https://ieeexplore.ieee.org/document/6248013>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, trajectory</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Xu et al., "Encoding Crowd Interaction With Deep Neural Network For Pedestrian Trajectory Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/2136.pdf>paper</a> <a href=https://github.com/svip-lab/CIDNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_gc">GC</a></li>
<li><a href="datasets.md#data_chuk">CHUK</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
<li><a href="metrics.md#metric_ande">ANDE</a></li>
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
<summary><em>Yoo et al., "Visual Path Prediction In Complex Scenes With Crowded Moving Objects", CVPR, 2016.</em> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Yoo_Visual_Path_Prediction_CVPR_2016_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_gc">GC</a></li>
<li><a href="datasets.md#data_qmul">QMUL</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yoo_2016_CVPR,
    author = "Yoo, YoungJoon and Yun, Kimin and Yun, Sangdoo and Hong, JongHee and Jeong, Hawook and Young Choi, Jin",
    title = "Visual Path Prediction In Complex Scenes With Crowded Moving Objects",
    booktitle = "CVPR",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yi et al., "Pedestrian Behavior Understanding And Prediction With Deep Neural Networks", ECCV, 2016.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46448-0_16>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_gc">GC</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
<details close>
<summary><em>Akbarzadeh et al., "Kernel Density Estimation For Target Trajectory Prediction", IROS, 2015.</em> <a href=https://ieeexplore.ieee.org/document/7353858>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_gc">GC</a></li>
<li><a href="datasets.md#data_mitt">MITT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ed">ED</a></li>
<li><a href="metrics.md#metric_run_time">Run Time</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Zhou_2012_CVPR,
    author = "Zhou, Bolei and Wang, Xiaogang and Tang, Xiaoou",
    title = "Understanding Collective Crowd Behaviors: Learning A Mixture Model Of Dynamic Pedestrian-Agents",
    booktitle = "CVPR",
    year = "2012"
}
</pre>
</details>

</ul></details>
<a name=data_bit></a>
<details close>
<summary><l style="font-size:20px"><strong>BIT</strong></l> <a href=https://sites.google.com/site/alexkongy/software>link</a> <a href=https://link.springer.com/content/pdf/10.1007%2F978-3-642-33718-5_22.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhao et al., "Spatiotemporal Feature Residual Propagation For Action Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhao_Spatiotemporal_Feature_Residual_Propagation_for_Action_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://github.com/JoeHEZHAO/Spatiotemporal-Residual-Propagation>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_jhmdb">JHMDB</a></li>
<li><a href="datasets.md#data_bit">BIT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhao_2019_ICCV,
    author = "Zhao, He and Wildes, Richard P.",
    title = "Spatiotemporal Feature Residual Propagation For Action Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chen et al., "Part-Activated Deep Reinforcement Learning For Action Prediction", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Lei_Chen_Part-Activated_Deep_Reinforcement_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_uti">UTI</a></li>
<li><a href="datasets.md#data_bit">BIT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2018_ECCV,
    author = "Chen, Lei and Lu, Jiwen and Song, Zhanjie and Zhou, Jie",
    title = "Part-Activated Deep Reinforcement Learning For Action Prediction",
    booktitle = "ECCV",
    year = "2018"
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_bit">BIT</a></li>
<li><a href="datasets.md#data_sports-1m">Sports-1M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<details close>
<summary><em>Lee et al., "Human Activity Prediction Based On Sub-Volume Relationship Descriptor", ICPR, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7899939>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_uti">UTI</a></li>
<li><a href="datasets.md#data_bit">BIT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lee_2016_ICPR,
    author = "Lee, Dong-Gyu and Lee, Seong-Whan",
    booktitle = "ICPR",
    title = "Human Activity Prediction Based On Sub-Volume Relationship Descriptor",
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
@InProceedings{Kong_2012_ECCV,
    author = "Kong, Yu and Jia, Yunde and Fu, Yun",
    year = "2012",
    booktitle = "ECCV",
    title = "Learning Human Interaction By Interactive Phrases"
}
</pre>
</details>

</ul></details>
<a name=data_mpii_cooking></a>
<details close>
<summary><l style="font-size:20px"><strong>MPII Cooking</strong></l> <a href=https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/human-activity-recognition/mpii-cooking-activities-dataset/>link</a> <a href=https://ieeexplore.ieee.org/document/6247801>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, 3D pose, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Alati et al., "Help By Predicting What To Do", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8803155>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_cad-120">CAD-120</a></li>
<li><a href="datasets.md#data_mpii_cooking">MPII Cooking</a></li>
<li><a href="datasets.md#data_breakfast">Breakfast</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_recall">Recall</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
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
<summary><em>Mahmud et al., "Joint Prediction Of Activity Labels And Starting Times In Untrimmed Videos", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Mahmud_Joint_Prediction_of_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_mpii_cooking">MPII Cooking</a></li>
<li><a href="datasets.md#data_virat">VIRAT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_recall">Recall</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
<li><a href="metrics.md#metric_rmse">RMSE</a></li>
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
<summary><em>Mahmud et al., "A Poisson Process Model For Activity Forecasting", ICIP, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7532978>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_mpii_cooking">MPII Cooking</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_rmse">RMSE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Rohrbach_2012_CVPR,
    author = "Rohrbach, Marcus and Amin, Sikandar and Andriluka, Mykhaylo and Schiele, Bernt",
    title = "A Database For Fine Grained Activity Detection Of Cooking Activities",
    booktitle = "CVPR",
    year = "2012"
}
</pre>
</details>

</ul></details>
<a name=data_uva-nemo></a>
<details close>
<summary><l style="font-size:20px"><strong>UvA-NEMO</strong></l> <a href=https://www.uva-nemo.org/>link</a> <a href=https://link.springer.com/content/pdf/10.1007%2F978-3-642-33712-3_38.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Face (smile)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kim et al., "Unsupervised Keypoint Learning For Guiding Class-Conditional Video Prediction", NeurIPS, 2019.</em> <a href=https://papers.nips.cc/paper/8637-unsupervised-keypoint-learning-for-guiding-class-conditional-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.02027.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
<li><a href="datasets.md#data_uva-nemo">UvA-NEMO</a></li>
<li><a href="datasets.md#data_mgif">MGIF</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_fvd">FVD</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kim_2019_NeurIPS,
    author = "Kim, Yunji and Nam, Seonghyeon and Cho, In and Kim, Seon Joo",
    title = "Unsupervised Keypoint Learning For Guiding Class-Conditional Video Prediction",
    booktitle = "NeurIPS",
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
@InProceedings{Dibeklio_2012_ECCV,
    author = "Dibeklio\uglu, Hamdi and Salah, Albert Ali and Gevers, Theo",
    editor = "Fitzgibbon, Andrew and Lazebnik, Svetlana and Perona, Pietro and Sato, Yoichi and Schmid, Cordelia",
    title = "Are You Really Smiling At Me? Spontaneous Versus Posed Enjoyment Smiles",
    booktitle = "ECCV",
    year = "2012"
}
</pre>
</details>

</ul></details>
<a name=data_utka></a>
<details close>
<summary><l style="font-size:20px"><strong>UTKinect-Action (UTKA)</strong></l> <a href=http://cvrc.ece.utexas.edu/KinectDatasets/HOJ3D.html>link</a> <a href=https://ieeexplore.ieee.org/document/6239233>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGBD, 3D pose, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kataoka et al., "Recognition Of Transitional Action For Short-Term Action Prediction Using Discriminative Temporal Cnn Feature", BMVC, 2016.</em> <a href=http://www.bmva.org/bmvc/2016/papers/paper012/paper012.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_wnp">WnP</a></li>
<li><a href="datasets.md#data_utka">UTKA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kataoka_2016_BMVC,
    author = "Kataoka, Hirokatsu and Miyashita, Yudai and Hayashi, Masaki and Iwata, Kenji and Satoh, Yutaka",
    title = "Recognition Of Transitional Action For Short-Term Action Prediction Using Discriminative Temporal Cnn Feature",
    year = "2016",
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
@InProceedings{Xia_2012_CVPRW,
    author = "Xia, L. and Chen, C.C. and Aggarwal, JK",
    title = "View Invariant Human Action Recognition Using Histograms Of 3D Joints",
    booktitle = "CVPRW",
    year = "2012"
}
</pre>
</details>

</ul></details>
<a name=data_sbuki></a>
<details close>
<summary><l style="font-size:20px"><strong>SBU Kinetic Interction (SBUKI)</strong></l> <a href=https://www3.cs.stonybrook.edu/~kyun/research/kinect_interaction/index.html>link</a> <a href=https://ieeexplore.ieee.org/document/6239234>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a>,<a href=papers.md#trajectory>Trajectory prediction<application></a>,<a href=papers.md#motion>Motion prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGBD, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yao et al., "Multiple Granularity Group Interaction Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0721.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_sbuki">SBUKI</a></li>
<li><a href="datasets.md#data_ca">CA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yao_2018_CVPR,
    author = "Yao, Taiping and Wang, Minsi and Ni, Bingbing and Wei, Huawei and Yang, Xiaokang",
    title = "Multiple Granularity Group Interaction Prediction",
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
@InProceedings{kiwon_2012_CVPR,
    author = "Yun, Kiwon and Honorio, Jean and Chattopadhyay, Debaleena and Berg, Tamara L. and Samaras, Dimitris",
    title = "Two-Person Interaction Detection Using Body-Pose Features And Multiple Instance Learning",
    booktitle = "CVPRW",
    year = "2012"
}
</pre>
</details>

</ul></details>
<a name=data_msrda></a>
<details close>
<summary><l style="font-size:20px"><strong>MSR Daily Activity (MSRDA)</strong></l> <a href=https://documents.uow.edu.au/~wanqing/#MSRAction3DDatasets>link</a> <a href=https://ieeexplore.ieee.org/document/6247813>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> Depth, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhang et al., "Bio-Inspired Predictive Orientation Decomposition Of Skeleton Trajectories For Real-Time Human Activity Prediction", ICRA, 2015.</em> <a href=https://ieeexplore.ieee.org/document/7139618>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_msrda">MSRDA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2015_ICRA,
    author = "Zhang, H. and Parker, L. E.",
    booktitle = "ICRA",
    title = "Bio-Inspired Predictive Orientation Decomposition Of Skeleton Trajectories For Real-Time Human Activity Prediction",
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
@InProceedings{Wang_2012_CVPR,
    author = "Wang, Jiang and Liu, Zicheng and Wu, Ying and Yuan, Junsong",
    title = "Mining Actionlet Ensemble For Action Recognition With Depth Cameras",
    booktitle = "CVPR",
    year = "2012"
}
</pre>
</details>

</ul></details>
<a name=data_maniac></a>
<details close>
<summary><l style="font-size:20px"><strong>MANIAC</strong></l> <a href=https://alexandria.physik3.uni-goettingen.de/cns-group/datasets/maniac/>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/6163000>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGBD, semantic segment, activity label</li>
<li><em><strong>Task:</strong></em> Object interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ziaeetabar et al., "Prediction Of Manipulation Action Classes Using Semantic Spatial Reasoning", IROS, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8593717>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_maniac">MANIAC</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_pp">PP</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Abramov_2012_WACV,
    author = "Abramov, Alexey and Pauwels, Karl and Papon, Jeremie and Worgotter, Florentin and Dellen, Babette",
    title = "Depth-Supported Real-Time Video Segmentation With The Kinect",
    booktitle = "WACV",
    year = "2012"
}
</pre>
</details>

</ul></details>
<a name=data_gtea_gaze></a>
<details close>
<summary><l style="font-size:20px"><strong>Georgia Tech Egocentric Activity Gaze (GTEA Gaze)</strong></l> <a href=http://www.cbi.gatech.edu/fpv/>link</a> <a href=https://link.springer.com/content/pdf/10.1007%2F978-3-642-33718-5_23.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, gaze,  mask, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Shen et al., "Egocentric Activity Prediction Via Event Modulated Attention", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Shen_Egocentric_Activity_Prediction_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_gtea_gaze+">GTEA Gaze+</a></li>
<li><a href="datasets.md#data_gtea_gaze">GTEA Gaze</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
@InProceedings{Fathi_2012_ECCV,
    author = "Fathi, Alireza and Li, Yin and Rehg, James M",
    title = "Learning To Recognize Daily Actions Using Gaze",
    booktitle = "ECCV",
    year = "2012"
}
</pre>
</details>

</ul></details>
</ul><a name=datasets_2011></a>
<h2>2011</h2> <a href=#top>&uarr; top</a>
<ul><a name=data_town_center></a>
<details close>
<summary><l style="font-size:20px"><strong>Town Center</strong></l> <a href=http://www.robots.ox.ac.uk/ActiveVision/Research/Projects/2009bbenfold_headpose/project.html#datasets>link</a> <a href=https://ieeexplore.ieee.org/document/5995667>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hasan et al., "Mx-Lstm: Mixing Tracklets And Vislets To Jointly Forecast Trajectories And Head Poses", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Hasan_MX-LSTM_Mixing_Tracklets_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1805.00652.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_town_center">Town Center</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hasan_2018_CVPR,
    author = "Hasan, Irtiza and Setti, Francesco and Tsesmelis, Theodore and Del Bue, Alessio and Galasso, Fabio and Cristani, Marco",
    title = "Mx-Lstm: Mixing Tracklets And Vislets To Jointly Forecast Trajectories And Head Poses",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Hasan et al., ""Seeing Is Believing": Pedestrian Trajectory Forecasting Using Visual Frustum Of Attention", WACV, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8354238>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_town_center">Town Center</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
<li><a href="metrics.md#metric_mane">MAnE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hasan_2018_WACV,
    author = "Hasan, I. and Setti, F. and Tsesmelis, T. and Del Bue, A. and Cristani, M. and Galasso, F.",
    booktitle = "WACV",
    title = "Seeing Is Believing": Pedestrian Trajectory Forecasting Using Visual Frustum Of Attention,
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ma et al., "Forecasting Interactive Dynamics Of Pedestrians With Fictitious Play", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Ma_Forecasting_Interactive_Dynamics_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1604.01431.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_town_center">Town Center</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_nll">NLL</a></li>
<li><a href="metrics.md#metric_scr">SCR</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ma_2017_CVPR,
    author = "Ma, Wei-Chiu and Huang, De-An and Lee, Namhoon and Kitani, Kris M.",
    title = "Forecasting Interactive Dynamics Of Pedestrians With Fictitious Play",
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
@InProceedings{Benfold_2011_CVPR,
    author = "Benfold, Ben and Reid, Ian",
    title = "Stable Multi-Target Tracking In Real-Time Surveillance Video",
    booktitle = "CVPR",
    year = "2011"
}
</pre>
</details>

</ul></details>
<a name=data_virat></a>
<details close>
<summary><l style="font-size:20px"><strong>VIRAT</strong></l> <a href=http://viratdata.org/>link</a> <a href=https://ieeexplore.ieee.org/document/5995586>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a>,<a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Surveillance, Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Mahmud et al., "Joint Prediction Of Activity Labels And Starting Times In Untrimmed Videos", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Mahmud_Joint_Prediction_of_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_mpii_cooking">MPII Cooking</a></li>
<li><a href="datasets.md#data_virat">VIRAT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_recall">Recall</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
<li><a href="metrics.md#metric_rmse">RMSE</a></li>
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
<summary><em>Vasquez, "Novel Planning-Based Algorithms For Human Motion Prediction", ICRA, 2016.</em> <a href=https://ieeexplore.ieee.org/abstract/document/7487505>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_virat">VIRAT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_nll">NLL</a></li>
<li><a href="metrics.md#metric_run_time">Run Time</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Vasquez_2016_ICRA,
    author = "Vasquez, D.",
    booktitle = "ICRA",
    title = "Novel Planning-Based Algorithms For Human Motion Prediction",
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
@InProceedings{Oh_2011_CVPR,
    author = "Oh, Sangmin and Hoogs, Anthony and Perera, Amitha and Cuntoor, Naresh and Chen, Chia-Chih and Lee, Jong Taek and Mukherjee, Saurajit and Aggarwal, JK and Lee, Hyungtae and Davis, Larry and others",
    title = "A Large-Scale Benchmark Dataset For Event Recognition In Surveillance Video",
    booktitle = "CVPR",
    year = "2011"
}
</pre>
</details>

</ul></details>
<a name=data_stanford-40></a>
<details close>
<summary><l style="font-size:20px"><strong>Stanford-40</strong></l> <a href=http://vision.stanford.edu/Datasets/40actions.html>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/6126386>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB (image), bounding box, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Safaei et al., "Still Image Action Recognition By Predicting Spatial-Temporal Pixel Evolution", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8658386>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_willow_action">Willow Action</a></li>
<li><a href="datasets.md#data_wider">WIDER</a></li>
<li><a href="datasets.md#data_stanford-40">Stanford-40</a></li>
<li><a href="datasets.md#data_bu_action">BU Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_map">mAP</a></li>
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
@InProceedings{Yao_2011_ICCV,
    author = "Yao, Bangpeng and Jiang, Xiaoye and Khosla, Aditya and Lin, Andy Lai and Guibas, Leonidas and Fei-Fei, Li",
    title = "Human Action Recognition By Learning Bases Of Action Attributes And Parts",
    booktitle = "ICCV",
    year = "2011"
}
</pre>
</details>

</ul></details>
<a name=data_hmdb></a>
<details close>
<summary><l style="font-size:20px"><strong>Human Motion Database (HMDB)</strong></l> <a href=http://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database/>link</a> <a href=https://ieeexplore.ieee.org/document/6126543>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box,  mask, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Cho et al., "A Temporal Sequence Learning For Action Recognition And Prediction", WACV, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8354149>paper</a> <a href=https://arxiv.org/pdf/1906.06813.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_hmdb">HMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cho_2018_WACV,
    author = "Cho, S. and Foroosh, H.",
    booktitle = "WACV",
    title = "A Temporal Sequence Learning For Action Recognition And Prediction",
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
@InProceedings{Kuehne_2011_ICCV,
    author = "Kuehne, H. and Jhuang, H. and Garrote, E. and Poggio, T. and Serre, T.",
    title = "Hmdb: A Large Video Database For Human Motion Recognition",
    booktitle = "ICCV",
    year = "2011"
}
</pre>
</details>

</ul></details>
<a name=data_fcvl></a>
<details close>
<summary><l style="font-size:20px"><strong>Ford Campus Vision LiDAR (FCVL)</strong></l> <a href=http://robots.engin.umich.edu/SoftwareData/Ford>link</a> <a href=https://journals.sagepub.com/doi/pdf/10.1177/0278364911400640>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#other>Other prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, LIDAR, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Choi et al., "Robust Modeling And Prediction In Dynamic Environments Using Recurrent Flow Networks", IROS, 2016.</em> <a href=https://ieeexplore.ieee.org/abstract/document/7759278>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_fcvl">FCVL</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_run_time">Run Time</a></li>
<li><a href="metrics.md#metric_recall">Recall</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
<li><a href="metrics.md#metric_auc">AUC</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Pandey_2011_IJRR,
    author = "Pandey, Gaurav and McBride, James R and Eustice, Ryan M",
    title = "Ford Campus Vision And Lidar Data Set",
    journal = "The International Journal of Robotics Research (IJRR)",
    volume = "30",
    number = "13",
    pages = "1543--1552",
    year = "2011"
}
</pre>
</details>

</ul></details>
</ul><a name=datasets_2010></a>
<h2>2010</h2> <a href=#top>&uarr; top</a>
<ul><a name=data_uti></a>
<details close>
<summary><l style="font-size:20px"><strong>UT Interaction (UTI)</strong></l> <a href=http://cvrc.ece.utexas.edu/SDHA2010/Human_Interaction.html>link</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Gammulle et al., "Predicting The Future: A Jointly Learnt Model For Action Anticipation", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Gammulle_Predicting_the_Future_A_Jointly_Learnt_Model_for_Action_Anticipation_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.07148.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_uti">UTI</a></li>
<li><a href="datasets.md#data_tv_human_interaction">TV Human Interaction</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gammulle_2019_ICCV,
    author = "Gammulle, Harshala and Denman, Simon and Sridharan, Sridha and Fookes, Clinton",
    title = "Predicting The Future: A Jointly Learnt Model For Action Anticipation",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chen et al., "Part-Activated Deep Reinforcement Learning For Action Prediction", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Lei_Chen_Part-Activated_Deep_Reinforcement_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_uti">UTI</a></li>
<li><a href="datasets.md#data_bit">BIT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2018_ECCV,
    author = "Chen, Lei and Lu, Jiwen and Song, Zhanjie and Zhou, Jie",
    title = "Part-Activated Deep Reinforcement Learning For Action Prediction",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Shi et al., "Action Anticipation With Rbf Kernelized Feature Mapping Rnn", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yuge_Shi_Action_Anticipation_with_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.07806.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_uti">UTI</a></li>
<li><a href="datasets.md#data_jhmdb">JHMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shi_2018_ECCV,
    author = "Shi, Yuge and Fernando, Basura and Hartley, Richard",
    title = "Action Anticipation With Rbf Kernelized Feature Mapping Rnn",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sadegh et al., "Encouraging Lstms To Anticipate Actions Very Early", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Aliakbarian_Encouraging_LSTMs_to_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_uti">UTI</a></li>
<li><a href="datasets.md#data_jhmdb">JHMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Aliakbarian_2017_ICCV,
    author = "Sadegh Aliakbarian, Mohammad and Sadat Saleh, Fatemeh and Salzmann, Mathieu and Fernando, Basura and Petersson, Lars and Andersson, Lars",
    title = "Encouraging Lstms To Anticipate Actions Very Early",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Human Activities Prediction By Learning Combinatorial Sparse Representations", ICIP, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7532452>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_uti">UTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2016_ICIP,
    author = "Xu, K. and Qin, Z. and Wang, G.",
    booktitle = "ICIP",
    title = "Human Activities Prediction By Learning Combinatorial Sparse Representations",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Lee et al., "Human Activity Prediction Based On Sub-Volume Relationship Descriptor", ICPR, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7899939>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_uti">UTI</a></li>
<li><a href="datasets.md#data_bit">BIT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lee_2016_ICPR,
    author = "Lee, Dong-Gyu and Lee, Seong-Whan",
    booktitle = "ICPR",
    title = "Human Activity Prediction Based On Sub-Volume Relationship Descriptor",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Activity Auto-Completion: Predicting Human Activities From Partial Videos", ICCV, 2015.</em> <a href=https://openaccess.thecvf.com/content_iccv_2015/papers/Xu_Activity_Auto-Completion_Predicting_ICCV_2015_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_uti">UTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_mrr">MRR</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Misc{Ryoo_2010_UT,
    author = "Ryoo, M. S. and Aggarwal, J. K.",
    title = "Ut-INteraction Dataset, Icpr Contest On Semantic Description Of HUman ACtivities (Sdha)",
    year = "2010",
    url = "http://cvrc.ece.utexas.edu/SDHA2010/Human\\\_Interaction.html"
}
</pre>
</details>

</ul></details>
<a name=data_tv_human_interaction></a>
<details close>
<summary><l style="font-size:20px"><strong>TV Human Interaction (THI)</strong></l> <a href=http://www.robots.ox.ac.uk/~alonso/tv_human_interactions.html>link</a> <a href=http://www.bmva.org/bmvc/2010/conference/paper50/abstract50.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box, head pose, activity label</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Gammulle et al., "Predicting The Future: A Jointly Learnt Model For Action Anticipation", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Gammulle_Predicting_the_Future_A_Jointly_Learnt_Model_for_Action_Anticipation_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.07148.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_uti">UTI</a></li>
<li><a href="datasets.md#data_tv_human_interaction">TV Human Interaction</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gammulle_2019_ICCV,
    author = "Gammulle, Harshala and Denman, Simon and Sridharan, Sridha and Fookes, Clinton",
    title = "Predicting The Future: A Jointly Learnt Model For Action Anticipation",
    booktitle = "ICCV",
    year = "2019"
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
<li><a href="datasets.md#data_tv_human_interaction">TV Human Interaction</a></li>
<li><a href="datasets.md#data_thumos">THUMOS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<summary><em>Zeng et al., "Visual Forecasting By Imitating Dynamics In Natural Sequences", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Zeng_Visual_Forecasting_by_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.05827.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_tv_human_interaction">TV Human Interaction</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
<summary><em>Gao et al., "Red: Reinforced Encoder-Decoder Networks For Action Anticipation", BMVC, 2017.</em> <a href=http://www.bmva.org/bmvc/2017/papers/paper092/paper092.pdf>paper</a> <a href=https://arxiv.org/pdf/1707.04818.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_tv_human_interaction">TV Human Interaction</a></li>
<li><a href="datasets.md#data_thumos">THUMOS</a></li>
<li><a href="datasets.md#data_tv_series">TV Series</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_map">mAP</a></li>
<li><a href="metrics.md#metric_cap">cAP</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2017_BMVC,
    author = "Gao, Jiyang and Yang, Zhenheng and Nevatia, Ram",
    title = "Red: Reinforced Encoder-Decoder Networks For Action Anticipation",
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
<li><a href="datasets.md#data_tv_human_interaction">TV Human Interaction</a></li>
<li><a href="datasets.md#data_thumos">THUMOS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
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
@InProceedings{Patron_2010_BMVC,
    author = "Patron-Perez, Alonso and Marszalek, Marcin and Zisserman, Andrew and Reid, Ian D",
    title = "High Five: Recognising Human Interactions In Tv Shows",
    booktitle = "BMVC",
    year = "2010"
}
</pre>
</details>

</ul></details>
<a name=data_willow_action></a>
<details close>
<summary><l style="font-size:20px"><strong>Willow Action</strong></l> <a href=https://www.di.ens.fr/willow/research/stillactions/>link</a> <a href=http://www.bmva.org/bmvc/2010/conference/paper97/paper97.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB (image), activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Safaei et al., "Still Image Action Recognition By Predicting Spatial-Temporal Pixel Evolution", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8658386>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_willow_action">Willow Action</a></li>
<li><a href="datasets.md#data_wider">WIDER</a></li>
<li><a href="datasets.md#data_stanford-40">Stanford-40</a></li>
<li><a href="datasets.md#data_bu_action">BU Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_map">mAP</a></li>
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
@InProceedings{Delaitre_2010_BMVC,
    author = "Delaitre, V. and Laptev, I. and Sivic, J.",
    title = "Recognizing Human Actions In Still Images: A Study Of Bag-Of-Features And Part-Based Representations",
    booktitle = "BMVC",
    year = "2010"
}
</pre>
</details>

</ul></details>
<a name=data_visor></a>
<details close>
<summary><l style="font-size:20px"><strong>ViSOR</strong></l> <a href=imagelab.ing.unimore.it/visor>link</a> <a href=https://link.springer.com/Article/10.1007/s11042-009-0402-9>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box, pose, attribute</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Lu et al., "Flexible Spatio-Temporal Networks For Video Prediction", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lu_Flexible_Spatio-Temporal_Networks_CVPR_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_sports-1m">Sports-1M</a></li>
<li><a href="datasets.md#data_visor">ViSOR</a></li>
<li><a href="datasets.md#data_prost">PROST</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Vezzani_2010_MTA,
    author = "Vezzani, Roberto and Cucchiara, Rita",
    title = "Video Surveillance Online Repository (Visor): An Integrated Framework",
    journal = "Multimedia Tools and Applications",
    volume = "50",
    number = "2",
    pages = "359--380",
    year = "2010"
}
</pre>
</details>

</ul></details>
<a name=data_prost></a>
<details close>
<summary><l style="font-size:20px"><strong>PROST</strong></l> <a href=www.gpu4vision.com>link</a> <a href=https://ieeexplore.ieee.org/document/5540145>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Object</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Lu et al., "Flexible Spatio-Temporal Networks For Video Prediction", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lu_Flexible_Spatio-Temporal_Networks_CVPR_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_sports-1m">Sports-1M</a></li>
<li><a href="datasets.md#data_visor">ViSOR</a></li>
<li><a href="datasets.md#data_prost">PROST</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Santner_2010_CVPR,
    author = "Santner, Jakob and Leistner, Christian and Saffari, Amir and Pock, Thomas and Bischof, Horst",
    title = "Prost: Parallel Robust Online Simple Tracking",
    booktitle = "CVPR",
    year = "2010"
}
</pre>
</details>

</ul></details>
<a name=data_mug></a>
<details close>
<summary><l style="font-size:20px"><strong>MUG</strong></l> <a href=https://mug.ee.auth.gr/fed/>link</a> <a href=https://ieeexplore.ieee.org/document/5617662>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, keypoints, motion label</li>
<li><em><strong>Task:</strong></em> Face (expression)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhao et al., "Learning To Forecast And Refine Residual Motion For Image-To-Video Generation", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Long_Zhao_Learning_to_Forecast_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1807.09951.pdf>arxiv</a> <a href=https://github.com/garyzhao/FRGAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_penn_action">Penn Action</a></li>
<li><a href="datasets.md#data_mug">MUG</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhao_2018_ECCV,
    author = "Zhao, Long and Peng, Xi and Tian, Yu and Kapadia, Mubbasir and Metaxas, Dimitris",
    title = "Learning To Forecast And Refine Residual Motion For Image-To-Video Generation",
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
@Article{Aifanti_2010_WIAMIS,
    author = "Aifanti, Niki and Papachristou, Christos and Delopoulos, Anastasios",
    title = "The Mug Facial Expression Database",
    journal = "WIAMIS",
    year = "2010"
}
</pre>
</details>

</ul></details>
<a name=data_msr></a>
<details close>
<summary><l style="font-size:20px"><strong>MSR</strong></l> <a href=https://www.microsoft.com/en-us/download/details.aspx?id=52315>link</a> <a href=https://ieeexplore.ieee.org/document/5543273>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a></li>
<li><em><strong>Data type:</strong></em> Depth, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Wang et al., "Order Matters: Shuffling Sequence Generation For Video Prediction", BMVC, 2019.</em> <a href=https://bmvc2019.org/wp-content/uploads/papers/1023-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1907.08845.pdf>arxiv</a> <a href=https://github.com/andrewjywang/SEENet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_kth">KTH</a></li>
<li><a href="datasets.md#data_msr">MSR</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Li_2010_CVPRW,
    author = "Li, Wanqing and Zhang, Zhengyou and Liu, Zicheng",
    title = "Action Recognition Based On A Bag Of 3D Points",
    booktitle = "CVPRW",
    year = "2010"
}
</pre>
</details>

</ul></details>
<a name=data_diplecs></a>
<details close>
<summary><l style="font-size:20px"><strong>DIPLECS</strong></l> <a href=https://cvssp.org/data/diplecs/>link</a> <a href=https://link.springer.com/content/pdf/10.1007%2F978-3-642-15567-3_12.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#other>Other prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>He et al., "Aggregated Sparse Attention For Steering Angle Prediction", ICPR, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8546051>paper</a> <a href=https://arxiv.org/pdf/1803.05785.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_diplecs">DIPLECS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_mae">MAE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{He_2018_ICPR,
    author = "He, S. and Kangin, D. and Mi, Y. and Pugeault, N.",
    booktitle = "ICPR",
    title = "Aggregated Sparse Attention For Steering Angle Prediction",
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
@InProceedings{Pugeault_2010_ECCV,
    author = "Pugeault, Nicolas and Bowden, Richard",
    title = "Learning Pre-Attentive Driving Behaviour From Holistic Visual Features",
    booktitle = "ECCV",
    year = "2010"
}
</pre>
</details>

</ul></details>
</ul><a name=datasets_2009></a>
<h2>2009</h2> <a href=#top>&uarr; top</a>
<ul><a name=data_eth></a>
<details close>
<summary><l style="font-size:20px"><strong>ETH</strong></l> <a href=http://www.vision.ee.ethz.ch/en/datasets/>link</a> <a href=https://ieeexplore.ieee.org/document/5459260>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, trajectory</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Li, "Which Way Are You Going? Imitative Decision Learning For Path Forecasting In Dynamic Scenes", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Which_Way_Are_You_Going_Imitative_Decision_Learning_for_Path_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_minade">minADE</a></li>
<li><a href="metrics.md#metric_minfde">minFDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2019_CVPR,
    author = "Li, Yuke",
    title = "Which Way Are You Going? Imitative Decision Learning For Path Forecasting In Dynamic Scenes",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liang et al., "Peeking Into The Future: Predicting Future Person Activities And Locations In Videos", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPRW_2019/papers/Precognition/Liang_Peeking_Into_the_Future_Predicting_Future_Person_Activities_and_Locations_CVPRW_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1902.03748.pdf>arxiv</a> <a href=https://github.com/google/next-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_actev/virat">ActEV/VIRAT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
<summary><em>Sadeghian et al., "Sophie: An Attentive Gan For Predicting Paths Compliant To Social And Physical Constraints", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Sadeghian_SoPhie_An_Attentive_GAN_for_Predicting_Paths_Compliant_to_Social_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1806.01482.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sadeghian_2019_CVPR,
    author = "Sadeghian, Amir and Kosaraju, Vineet and Sadeghian, Ali and Hirose, Noriaki and Rezatofighi, Hamid and Savarese, Silvio",
    title = "Sophie: An Attentive Gan For Predicting Paths Compliant To Social And Physical Constraints",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhang et al., "Sr-Lstm: State Refinement For Lstm Towards Pedestrian Trajectory Prediction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_SR-LSTM_State_Refinement_for_LSTM_Towards_Pedestrian_Trajectory_Prediction_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1903.02793.pdf>arxiv</a> <a href=https://github.com/zhangpur/SR-LSTM>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2019_CVPR,
    author = "Zhang, Pu and Ouyang, Wanli and Zhang, Pengfei and Xue, Jianru and Zheng, Nanning",
    title = "Sr-Lstm: State Refinement For Lstm Towards Pedestrian Trajectory Prediction",
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
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_ngsim">NGSIM</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
<li><a href="metrics.md#metric_rmse">RMSE</a></li>
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
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
<summary><em>Huang et al., "Stgat: Modeling Spatial-Temporal Interactions For Human Trajectory Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Huang_STGAT_Modeling_Spatial-Temporal_Interactions_for_Human_Trajectory_Prediction_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Huang_2019_ICCV,
    author = "Huang, Yingfan and Bi, Huikun and Li, Zhaoxin and Mao, Tianlu and Wang, Zhaoqi",
    title = "Stgat: Modeling Spatial-Temporal Interactions For Human Trajectory Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Kosaraju et al., "Social-Bigat: Multimodal Trajectory Forecasting Using Bicycle-Gan And Graph Attention Networks", NeurIPS, 2019.</em> <a href=http://papers.nips.cc/paper/8308-social-bigat-multimodal-trajectory-forecasting-using-bicycle-gan-and-graph-attention-networks.pdf>paper</a> <a href=https://arxiv.org/pdf/1907.03395.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kosaraju_2019_NeurIPS,
    author = "Kosaraju, Vineet and Sadeghian, Amir and Mart\'\in-Mart\'\in, Roberto and Reid, Ian and Rezatofighi, Hamid and Savarese, Silvio",
    title = "Social-Bigat: Multimodal Trajectory Forecasting Using Bicycle-Gan And Graph Attention Networks",
    booktitle = "NeurIPS",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Anderson et al., "Stochastic Sampling Simulation For Pedestrian Trajectory Prediction", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8967857>paper</a> <a href=https://arxiv.org/pdf/1903.01860.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
<li><a href="metrics.md#metric_minade">minADE</a></li>
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
<summary><em>Li et al., "Conditional Generative Neural System For Probabilistic Trajectory Prediction", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8967822>paper</a> <a href=https://arxiv.org/pdf/1905.01631.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
<li><a href="datasets.md#data_interaction">INTERACTION</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
<summary><em>Zhu et al., "Starnet: Pedestrian Trajectory Prediction Using Deep Neural Network In Star Topology", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8967811>paper</a> <a href=https://arxiv.org/pdf/1906.01797.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhu_2019_IROS,
    author = "Zhu, Yanliang and Qian, Deheng and Ren, Dongchun and Xia, Huaxia",
    booktitle = "IROS",
    title = "Starnet: Pedestrian Trajectory Prediction Using Deep Neural Network In Star Topology",
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
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
<li><a href="datasets.md#data_pets2009">PETS2009</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
<summary><em>Gupta et al., "Social Gan: Socially Acceptable Trajectories With Generative Adversarial Networks", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Gupta_Social_GAN_Socially_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1803.10892.pdf>arxiv</a> <a href=https://github.com/agrimgupta92/sgan>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gupta_2018_CVPR,
    author = "Gupta, Agrim and Johnson, Justin and Fei-Fei, Li and Savarese, Silvio and Alahi, Alexandre",
    title = "Social Gan: Socially Acceptable Trajectories With Generative Adversarial Networks",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Encoding Crowd Interaction With Deep Neural Network For Pedestrian Trajectory Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/2136.pdf>paper</a> <a href=https://github.com/svip-lab/CIDNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_gc">GC</a></li>
<li><a href="datasets.md#data_chuk">CHUK</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
<li><a href="metrics.md#metric_ande">ANDE</a></li>
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
<summary><em>Fernando et al., "Gd-Gan: Generative Adversarial Networks For Trajectory Prediction And Group Detection In Crowds", ACCV, 2019.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20887-5_20>paper</a> <a href=https://arxiv.org/pdf/1812.07667.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Fernando_2018_ACCV,
    author = "Fernando, Tharindu and Denman, Simon and Sridharan, Sridha and Fookes, Clinton",
    editor = "Jawahar, C. V. and Li, Hongdong and Mori, Greg and Schindler, Konrad",
    title = "Gd-Gan: Generative Adversarial Networks For Trajectory Prediction And Group Detection In Crowds",
    booktitle = "ACCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Pfeiffer et al., "A Data-Driven Model For Interaction-Aware Pedestrian Motion Prediction In Object Cluttered Environments", ICRA, 2018.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8461157>paper</a> <a href=https://arxiv.org/pdf/1709.08528.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ed">ED</a></li>
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
<summary><em>Vemula et al., "Social Attention: Modeling Attention In Human Crowds", ICRA, 2018.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8460504>paper</a> <a href=https://arxiv.org/pdf/1710.04689.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
<summary><em>Xue et al., "Ss-Lstm: A Hierarchical Lstm Model For Pedestrian Trajectory Prediction", WACV, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8354239>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xue_2018_WACV,
    author = "Xue, H. and Huynh, D. Q. and Reynolds, M.",
    booktitle = "WACV",
    title = "Ss-Lstm: A Hierarchical Lstm Model For Pedestrian Trajectory Prediction",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Alahi et al., "Social Lstm: Human Trajectory Prediction In Crowded Spaces", CVPR, 2016.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Alahi_Social_LSTM_Human_CVPR_2016_paper.pdf>paper</a> <a href=https://github.com/quancore/social-lstm>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
<li><a href="metrics.md#metric_ande">ANDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Alahi_2016_CVPR,
    author = "Alahi, Alexandre and Goel, Kratarth and Ramanathan, Vignesh and Robicquet, Alexandre and Fei-Fei, Li and Savarese, Silvio",
    title = "Social Lstm: Human Trajectory Prediction In Crowded Spaces",
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
@InProceedings{Pellegrini_2009_ICCV,
    author = "Pellegrini, Stefano and Ess, Andreas and Schindler, Konrad and Van Gool, Luc",
    title = "You'Ll Never Walk Alone: Modeling Social Behavior For Multi-Target Tracking",
    booktitle = "ICCV",
    year = "2009"
}
</pre>
</details>

</ul></details>
<a name=data_caltech_pedestrian></a>
<details close>
<summary><l style="font-size:20px"><strong>Caltech Pedestrian</strong></l> <a href=http://www.vision.caltech.edu/Image_Datasets/CaltechPedestrians/>link</a> <a href=https://ieeexplore.ieee.org/document/5206631>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a>,<a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle Gan", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_chuk_avenue">CHUK Avenue</a></li>
<li><a href="datasets.md#data_shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kwon_2019_CVPR,
    author = "Kwon, Yong-Hoon and Park, Min-Gyu",
    title = "Predicting Future Frames Using Retrospective Cycle Gan",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Gao et al., "Disentangling Propagation And Generation For Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Gao_Disentangling_Propagation_and_Generation_for_Video_Prediction_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2019_ICCV,
    author = "Gao, Hang and Xu, Huazhe and Cai, Qi-Zhi and Wang, Ruth and Yu, Fisher and Darrell, Trevor",
    title = "Disentangling Propagation And Generation For Video Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ho et al., "Sme-Net: Sparse Motion Estimation For Parametric Video Prediction Through Reinforcement Learning", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ho_SME-Net_Sparse_Motion_Estimation_for_Parametric_Video_Prediction_Through_Reinforcement_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_yuv">YUV</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ho_2019_ICCV,
    author = "Ho, Yung-Han and Cho, Chuan-Yuan and Peng, Wen-Hsiao and Jin, Guo-Lun",
    title = "Sme-Net: Sparse Motion Estimation For Parametric Video Prediction Through Reinforcement Learning",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ho et al., "Deep Reinforcement Learning For Video Prediction", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8803825>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_yuv">YUV</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ho_2019_ICIP,
    author = "Ho, Y. and Cho, C. and Peng, W.",
    booktitle = "ICIP",
    title = "Deep Reinforcement Learning For Video Prediction",
    year = "2019"
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_human3.6m">Human3.6M</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<summary><em>Liu et al., "Dyan: A Dynamical Atoms-Based Network For Video Prediction", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Wenqian_Liu_DYAN_A_Dynamical_ECCV_2018_paper.pdf)>paper</a> <a href=https://github.com/liuem607/DYAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2018_ECCV,
    author = "Liu, Wenqian and Sharma, Abhishek and Camps, Octavia and Sznaier, Mario",
    title = "Dyan: A Dynamical Atoms-Based Network For Video Prediction",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Reda et al., "Sdc-Net: Video Prediction Using Spatially-Displaced Convolution", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Fitsum_Reda_SDC-Net_Video_prediction_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1811.00684.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_youtube-8m">Youtube-8M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
<li><a href="metrics.md#metric_l1">L1</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Reda_2018_ECCV,
    author = "Reda, Fitsum A. and Liu, Guilin and Shih, Kevin J. and Kirby, Robert and Barker, Jon and Tarjan, David and Tao, Andrew and Catanzaro, Bryan",
    title = "Sdc-Net: Video Prediction Using Spatially-Displaced Convolution",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liang et al., "Dual Motion Gan For Future-Flow Embedded Video Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Liang_Dual_Motion_GAN_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00284.pdf>arxiv</a> <a href=https://github.com/gurkirt/realtime-action-detection>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_thumos">THUMOS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liang_2017_ICCV,
    author = "Liang, Xiaodan and Lee, Lisa and Dai, Wei and Xing, Eric P.",
    title = "Dual Motion Gan For Future-Flow Embedded Video Prediction",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Hariyono et al., "Estimation Of Collision Risk For Improving Driver'S Safety", IECON, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7793743>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_eth_pedestrian">ETH Pedestrian</a></li>
<li><a href="datasets.md#data_daimler">Daimler</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_auc">AUC</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hariyono_2016_IES,
    author = "Hariyono, Joko and Shahbaz, Ajmal and Kurnianggoro, Laksono and Jo, Kang-Hyun",
    title = "Estimation Of Collision Risk For Improving Driver'S Safety",
    booktitle = "IECON",
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
@InProceedings{Dollar_2009_CVPR,
    author = "Doll\'ar, P. and Wojek, C. and Schiele, B. and Perona, P.",
    title = "Pedestrian Detection: A Benchmark",
    booktitle = "CVPR",
    year = "2009"
}
</pre>
</details>

</ul></details>
<a name=data_yuv></a>
<details close>
<summary><l style="font-size:20px"><strong>YUV Videos</strong></l> <a href=http://trace.kom.aau.dk/yuv/index.html>link</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Mix videos</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ho et al., "Sme-Net: Sparse Motion Estimation For Parametric Video Prediction Through Reinforcement Learning", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ho_SME-Net_Sparse_Motion_Estimation_for_Parametric_Video_Prediction_Through_Reinforcement_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_yuv">YUV</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ho_2019_ICCV,
    author = "Ho, Yung-Han and Cho, Chuan-Yuan and Peng, Wen-Hsiao and Jin, Guo-Lun",
    title = "Sme-Net: Sparse Motion Estimation For Parametric Video Prediction Through Reinforcement Learning",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ho et al., "Deep Reinforcement Learning For Video Prediction", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8803825>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_yuv">YUV</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ho_2019_ICIP,
    author = "Ho, Y. and Cho, C. and Peng, W.",
    booktitle = "ICIP",
    title = "Deep Reinforcement Learning For Video Prediction",
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
@Misc{ASU_2009_YUV,
    author = "Library, ASU Video Trace",
    title = "Yuv Video Sequences",
    year = "2009",
    howpublished = "http://trace.kom.aau.dk/yuv/index.html"
}
</pre>
</details>

</ul></details>
<a name=data_eifp></a>
<details close>
<summary><l style="font-size:20px"><strong>Edinburgh Informatics Forum Pedestrian (EIFP)</strong></l> <a href=http://homepages.inf.ed.ac.uk/rbf/FORUMTRACKING/>link</a> <a href=https://homepages.inf.ed.ac.uk/rbf/FORUMTRACKING/IM090734.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Carvalho et al., "Long-Term Prediction Of Motion Trajectories Using Path Homology Clusters", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8968125>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_eifp">EIFP</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ed">ED</a></li>
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
<summary><em>Zhi et al., "Kernel Trajectory Maps For Multi-Modal Probabilistic Motion Prediction", CoRL, 2019.</em> <a href=http://proceedings.mlr.press/v100/zhi20a/zhi20a.pdf>paper</a> <a href=https://arxiv.org/pdf/1907.05127.pdf>arxiv</a> <a href=https://github.com/wzhi/KernelTrajectoryMaps>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_eifp">EIFP</a></li>
<li><a href="datasets.md#data_lankershim_boulevard">Lankershim Boulevard</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@mastersthesis{Majecka_2009,
    author = "Majecka, Barbara",
    title = "Statistical Models Of Pedestrian Behaviour In The Forum",
    school = "School of Informatics, University of Edinburgh",
    year = "2009"
}
</pre>
</details>

</ul></details>
<a name=data_tum_kitchen></a>
<details close>
<summary><l style="font-size:20px"><strong>TUM Kitchen</strong></l> <a href=https://ias.in.tum.de/dokuwiki/software/kitchen-activity-data>link</a> <a href=https://ieeexplore.ieee.org/document/5457583>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, RFID, 3D pose, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Vo et al., "Augmenting Physical State Prediction Through Structured Activity Inference", ICRA, 2015.</em> <a href=https://ieeexplore.ieee.org/document/7139262>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_tum_kitchen">TUM Kitchen</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ed">ED</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Tenorth_2009_ICCVW,
    author = "Tenorth, Moritz and Bandouch, Jan and Beetz, Michael",
    title = "The Tum Kitchen Data Set Of Everyday Manipulation Activities For Motion Tracking And Action Recognition",
    booktitle = "ICCVW",
    year = "2009"
}
</pre>
</details>

</ul></details>
<a name=data_qmul></a>
<details close>
<summary><l style="font-size:20px"><strong>QMUL</strong></l> <a href=http://personal.ie.cuhk.edu.hk/~ccloy/downloads_qmul_junction.html>link</a> <a href=http://www.bmva.org/bmvc/2009/Papers/Paper077/Paper077.pdf>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, trajectory</li>
<li><em><strong>Task:</strong></em> Driving, Anomaly</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yoo et al., "Visual Path Prediction In Complex Scenes With Crowded Moving Objects", CVPR, 2016.</em> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Yoo_Visual_Path_Prediction_CVPR_2016_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_gc">GC</a></li>
<li><a href="datasets.md#data_qmul">QMUL</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yoo_2016_CVPR,
    author = "Yoo, YoungJoon and Yun, Kimin and Yun, Sangdoo and Hong, JongHee and Jeong, Hawook and Young Choi, Jin",
    title = "Visual Path Prediction In Complex Scenes With Crowded Moving Objects",
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
@InProceedings{Loy_2009_BMVC,
    author = "Loy, Chen Change and Xiang, Tao and Gong, Shaogang",
    title = "Modelling Multi-Object Activity By Gaussian Processes",
    booktitle = "BMVC",
    year = "2009"
}
</pre>
</details>

</ul></details>
<a name=data_pets2009></a>
<details close>
<summary><l style="font-size:20px"><strong>PETS2009</strong></l> <a href=http://www.cvg.reading.ac.uk/PETS2009/a.html>link</a> <a href=https://ieeexplore.ieee.org/document/5399556>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Xue et al., "Location-Velocity Attention For Pedestrian Trajectory Prediction", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8659060>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
<li><a href="datasets.md#data_pets2009">PETS2009</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Ferryman_2009_PETS,
    author = "Ferryman, J. and Shahrokni, A.",
    booktitle = "PETS",
    title = "Pets2009: Dataset And Challenge",
    year = "2009"
}
</pre>
</details>

</ul></details>
<a name=data_osu></a>
<details close>
<summary><l style="font-size:20px"><strong>OSU</strong></l> <a href=http://eecs.oregonstate.edu/football/tracking/dataset>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/5206801>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box, attribute</li>
<li><em><strong>Task:</strong></em> Sport</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Lee et al., "Predicting Wide Receiver Trajectories In American Football", WACV, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7477732>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_osu">OSU</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_nll">NLL</a></li>
<li><a href="metrics.md#metric_kld">KLD</a></li>
<li><a href="metrics.md#metric_mhd">MHD</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
<li><a href="metrics.md#metric_dtg">DtG</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lee_2016_WACV,
    author = "Lee, N. and Kitani, K. M.",
    booktitle = "WACV",
    title = "Predicting Wide Receiver Trajectories In American Football",
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
@InProceedings{Hess_2009_CVPR,
    author = "Hess, Rob and Fern, Alan",
    title = "Discriminatively Trained Particle Filters For Complex Multi-Object Tracking",
    booktitle = "CVPR",
    year = "2009"
}
</pre>
</details>

</ul></details>
<a name=data_ca></a>
<details close>
<summary><l style="font-size:20px"><strong>Collective Activity (CA)</strong></l> <a href=http://www-personal.umich.edu/~wgchoi/eccv12/wongun_eccv12.html>link</a> <a href=https://ieeexplore.ieee.org/document/5457461>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a>,<a href=papers.md#trajectory>Trajectory prediction<application></a>,<a href=papers.md#motion>Motion prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box, attribute, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yao et al., "Multiple Granularity Group Interaction Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0721.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_sbuki">SBUKI</a></li>
<li><a href="datasets.md#data_ca">CA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yao_2018_CVPR,
    author = "Yao, Taiping and Wang, Minsi and Ni, Bingbing and Wei, Huawei and Yang, Xiaokang",
    title = "Multiple Granularity Group Interaction Prediction",
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
@InProceedings{Choi_2009_ICCVW,
    author = "Choi, Wongun and Shahid, Khuram and Savarese, Silvio",
    title = "What Are They Doing? : Collective Activity Classification Using Spatio-Temporal Relationship Among People",
    booktitle = "ICCVW",
    year = "2009"
}
</pre>
</details>

</ul></details>
</ul><a name=datasets_2008></a>
<h2>2008</h2> <a href=#top>&uarr; top</a>
<ul><a name=data_mitt></a>
<details close>
<summary><l style="font-size:20px"><strong>MIT Trajectory (MITT)</strong></l> <a href=http://www.ee.cuhk.edu.hk/~xgwang/MITtrajsingle.html>link</a> <a href=https://ieeexplore.ieee.org/document/4587718>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, trajectory</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Akbarzadeh et al., "Kernel Density Estimation For Target Trajectory Prediction", IROS, 2015.</em> <a href=https://ieeexplore.ieee.org/document/7353858>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_gc">GC</a></li>
<li><a href="datasets.md#data_mitt">MITT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ed">ED</a></li>
<li><a href="metrics.md#metric_run_time">Run Time</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Grimson_2008_CVPR,
    author = "Grimson, Eric and Wang, Xiaogang and Ng, Gee-Wah and Ma, Keng Teck",
    title = "Trajectory Analysis And Semantic Region Modeling Using A Nonparametric Bayesian Model",
    booktitle = "CVPR",
    year = "2008"
}
</pre>
</details>

</ul></details>
<a name=data_daimler></a>
<details close>
<summary><l style="font-size:20px"><strong>Daimler</strong></l> <a href=http://www.gavrila.net/Datasets/Daimler_Pedestrian_Benchmark_D/Daimler_Mono_Ped__Detection_Be/daimler_mono_ped__detection_be.html>link</a> <a href=https://ieeexplore.ieee.org/document/4657363>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> Grayscale, bounding box</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hariyono et al., "Estimation Of Collision Risk For Improving Driver'S Safety", IECON, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7793743>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_eth_pedestrian">ETH Pedestrian</a></li>
<li><a href="datasets.md#data_daimler">Daimler</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_auc">AUC</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hariyono_2016_IES,
    author = "Hariyono, Joko and Shahbaz, Ajmal and Kurnianggoro, Laksono and Jo, Kang-Hyun",
    title = "Estimation Of Collision Risk For Improving Driver'S Safety",
    booktitle = "IECON",
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
@Article{Enzweiler_2008_PAMI,
    author = "Enzweiler, Markus and Gavrila, Dariu M",
    title = "Monocular Pedestrian Detection: Survey And Experiments",
    journal = "transactions on pattern analysis and machine intelligence (PAMI)",
    volume = "31",
    number = "12",
    pages = "2179--2195",
    year = "2008"
}
</pre>
</details>

</ul></details>
</ul><a name=datasets_2007></a>
<h2>2007</h2> <a href=#top>&uarr; top</a>
<ul><a name=data_ucy></a>
<details close>
<summary><l style="font-size:20px"><strong>UCY</strong></l> <a href=https://graphics.cs.ucy.ac.cy/research/downloads/crowd-data>link</a> <a href=https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1467-8659.2007.01089.x>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, trajectory, gaze</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Li, "Which Way Are You Going? Imitative Decision Learning For Path Forecasting In Dynamic Scenes", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Which_Way_Are_You_Going_Imitative_Decision_Learning_for_Path_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_minade">minADE</a></li>
<li><a href="metrics.md#metric_minfde">minFDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2019_CVPR,
    author = "Li, Yuke",
    title = "Which Way Are You Going? Imitative Decision Learning For Path Forecasting In Dynamic Scenes",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liang et al., "Peeking Into The Future: Predicting Future Person Activities And Locations In Videos", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPRW_2019/papers/Precognition/Liang_Peeking_Into_the_Future_Predicting_Future_Person_Activities_and_Locations_CVPRW_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1902.03748.pdf>arxiv</a> <a href=https://github.com/google/next-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_actev/virat">ActEV/VIRAT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
<summary><em>Sadeghian et al., "Sophie: An Attentive Gan For Predicting Paths Compliant To Social And Physical Constraints", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Sadeghian_SoPhie_An_Attentive_GAN_for_Predicting_Paths_Compliant_to_Social_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1806.01482.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sadeghian_2019_CVPR,
    author = "Sadeghian, Amir and Kosaraju, Vineet and Sadeghian, Ali and Hirose, Noriaki and Rezatofighi, Hamid and Savarese, Silvio",
    title = "Sophie: An Attentive Gan For Predicting Paths Compliant To Social And Physical Constraints",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhang et al., "Sr-Lstm: State Refinement For Lstm Towards Pedestrian Trajectory Prediction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_SR-LSTM_State_Refinement_for_LSTM_Towards_Pedestrian_Trajectory_Prediction_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1903.02793.pdf>arxiv</a> <a href=https://github.com/zhangpur/SR-LSTM>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2019_CVPR,
    author = "Zhang, Pu and Ouyang, Wanli and Zhang, Pengfei and Xue, Jianru and Zheng, Nanning",
    title = "Sr-Lstm: State Refinement For Lstm Towards Pedestrian Trajectory Prediction",
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
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_ngsim">NGSIM</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
<li><a href="metrics.md#metric_rmse">RMSE</a></li>
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
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
<summary><em>Huang et al., "Stgat: Modeling Spatial-Temporal Interactions For Human Trajectory Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Huang_STGAT_Modeling_Spatial-Temporal_Interactions_for_Human_Trajectory_Prediction_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Huang_2019_ICCV,
    author = "Huang, Yingfan and Bi, Huikun and Li, Zhaoxin and Mao, Tianlu and Wang, Zhaoqi",
    title = "Stgat: Modeling Spatial-Temporal Interactions For Human Trajectory Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Thiede et al., "Analyzing The Variety Loss In The Context Of Probabilistic Trajectory Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Thiede_Analyzing_the_Variety_Loss_in_the_Context_of_Probabilistic_Trajectory_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1907.10178.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ll">LL</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Thiede_2019_ICCV,
    author = "Thiede, Luca Anthony and Brahma, Pratik Prabhanjan",
    title = "Analyzing The Variety Loss In The Context Of Probabilistic Trajectory Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Kosaraju et al., "Social-Bigat: Multimodal Trajectory Forecasting Using Bicycle-Gan And Graph Attention Networks", NeurIPS, 2019.</em> <a href=http://papers.nips.cc/paper/8308-social-bigat-multimodal-trajectory-forecasting-using-bicycle-gan-and-graph-attention-networks.pdf>paper</a> <a href=https://arxiv.org/pdf/1907.03395.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kosaraju_2019_NeurIPS,
    author = "Kosaraju, Vineet and Sadeghian, Amir and Mart\'\in-Mart\'\in, Roberto and Reid, Ian and Rezatofighi, Hamid and Savarese, Silvio",
    title = "Social-Bigat: Multimodal Trajectory Forecasting Using Bicycle-Gan And Graph Attention Networks",
    booktitle = "NeurIPS",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Anderson et al., "Stochastic Sampling Simulation For Pedestrian Trajectory Prediction", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8967857>paper</a> <a href=https://arxiv.org/pdf/1903.01860.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
<li><a href="metrics.md#metric_minade">minADE</a></li>
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
<summary><em>Li et al., "Conditional Generative Neural System For Probabilistic Trajectory Prediction", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8967822>paper</a> <a href=https://arxiv.org/pdf/1905.01631.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
<li><a href="datasets.md#data_interaction">INTERACTION</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
<summary><em>Zhu et al., "Starnet: Pedestrian Trajectory Prediction Using Deep Neural Network In Star Topology", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8967811>paper</a> <a href=https://arxiv.org/pdf/1906.01797.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhu_2019_IROS,
    author = "Zhu, Yanliang and Qian, Deheng and Ren, Dongchun and Xia, Huaxia",
    booktitle = "IROS",
    title = "Starnet: Pedestrian Trajectory Prediction Using Deep Neural Network In Star Topology",
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
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
<li><a href="datasets.md#data_pets2009">PETS2009</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
<summary><em>Gupta et al., "Social Gan: Socially Acceptable Trajectories With Generative Adversarial Networks", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Gupta_Social_GAN_Socially_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1803.10892.pdf>arxiv</a> <a href=https://github.com/agrimgupta92/sgan>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gupta_2018_CVPR,
    author = "Gupta, Agrim and Johnson, Justin and Fei-Fei, Li and Savarese, Silvio and Alahi, Alexandre",
    title = "Social Gan: Socially Acceptable Trajectories With Generative Adversarial Networks",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Hasan et al., "Mx-Lstm: Mixing Tracklets And Vislets To Jointly Forecast Trajectories And Head Poses", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Hasan_MX-LSTM_Mixing_Tracklets_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1805.00652.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_town_center">Town Center</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hasan_2018_CVPR,
    author = "Hasan, Irtiza and Setti, Francesco and Tsesmelis, Theodore and Del Bue, Alessio and Galasso, Fabio and Cristani, Marco",
    title = "Mx-Lstm: Mixing Tracklets And Vislets To Jointly Forecast Trajectories And Head Poses",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Encoding Crowd Interaction With Deep Neural Network For Pedestrian Trajectory Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/2136.pdf>paper</a> <a href=https://github.com/svip-lab/CIDNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_gc">GC</a></li>
<li><a href="datasets.md#data_chuk">CHUK</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
<li><a href="metrics.md#metric_ande">ANDE</a></li>
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
<summary><em>Fernando et al., "Gd-Gan: Generative Adversarial Networks For Trajectory Prediction And Group Detection In Crowds", ACCV, 2019.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20887-5_20>paper</a> <a href=https://arxiv.org/pdf/1812.07667.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Fernando_2018_ACCV,
    author = "Fernando, Tharindu and Denman, Simon and Sridharan, Sridha and Fookes, Clinton",
    editor = "Jawahar, C. V. and Li, Hongdong and Mori, Greg and Schindler, Konrad",
    title = "Gd-Gan: Generative Adversarial Networks For Trajectory Prediction And Group Detection In Crowds",
    booktitle = "ACCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Vemula et al., "Social Attention: Modeling Attention In Human Crowds", ICRA, 2018.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8460504>paper</a> <a href=https://arxiv.org/pdf/1710.04689.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
<summary><em>Hasan et al., ""Seeing Is Believing": Pedestrian Trajectory Forecasting Using Visual Frustum Of Attention", WACV, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8354238>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_town_center">Town Center</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
<li><a href="metrics.md#metric_mane">MAnE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hasan_2018_WACV,
    author = "Hasan, I. and Setti, F. and Tsesmelis, T. and Del Bue, A. and Cristani, M. and Galasso, F.",
    booktitle = "WACV",
    title = "Seeing Is Believing": Pedestrian Trajectory Forecasting Using Visual Frustum Of Attention,
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xue et al., "Ss-Lstm: A Hierarchical Lstm Model For Pedestrian Trajectory Prediction", WACV, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8354239>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xue_2018_WACV,
    author = "Xue, H. and Huynh, D. Q. and Reynolds, M.",
    booktitle = "WACV",
    title = "Ss-Lstm: A Hierarchical Lstm Model For Pedestrian Trajectory Prediction",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Bartoli et al., "Context-Aware Trajectory Prediction", ICPR, 2018.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8545447>paper</a> <a href=https://arxiv.org/pdf/1705.02503.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bartoli_2018_ICPR,
    author = "Bartoli, F. and Lisanti, G. and Ballan, L. and Del Bimbo, A.",
    booktitle = "ICPR",
    title = "Context-Aware Trajectory Prediction",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ma et al., "Forecasting Interactive Dynamics Of Pedestrians With Fictitious Play", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Ma_Forecasting_Interactive_Dynamics_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1604.01431.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_town_center">Town Center</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_nll">NLL</a></li>
<li><a href="metrics.md#metric_scr">SCR</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ma_2017_CVPR,
    author = "Ma, Wei-Chiu and Huang, De-An and Lee, Namhoon and Kitani, Kris M.",
    title = "Forecasting Interactive Dynamics Of Pedestrians With Fictitious Play",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Alahi et al., "Social Lstm: Human Trajectory Prediction In Crowded Spaces", CVPR, 2016.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Alahi_Social_LSTM_Human_CVPR_2016_paper.pdf>paper</a> <a href=https://github.com/quancore/social-lstm>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
<li><a href="metrics.md#metric_ande">ANDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Alahi_2016_CVPR,
    author = "Alahi, Alexandre and Goel, Kratarth and Ramanathan, Vignesh and Robicquet, Alexandre and Fei-Fei, Li and Savarese, Silvio",
    title = "Social Lstm: Human Trajectory Prediction In Crowded Spaces",
    booktitle = "CVPR",
    year = "2016"
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
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
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
@Article{Lerner_2007_CGF,
    author = "Lerner, Alon and Chrysanthou, Yiorgos and Lischinski, Dani",
    title = "Crowds By Example",
    journal = "Computer graphics forum",
    volume = "26",
    number = "3",
    pages = "655--664",
    year = "2007"
}
</pre>
</details>

</ul></details>
<a name=data_ngsim></a>
<details close>
<summary><l style="font-size:20px"><strong>Next Generation simulationulation (NGSIM)</strong></l> <a href=https://ops.fhwa.dot.gov/trafficanalysistools/ngsim.htm>link</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a>,<a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> Map, trajectory</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ding et al., "Predicting Vehicle Behaviors Over An Extended Horizon Using Behavior Interaction Network", ICRA, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8794146>paper</a> <a href=https://arxiv.org/pdf/1903.00848.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_recall">Recall</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
<li><a href="metrics.md#metric_f1">F1</a></li>
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
<summary><em>Scheel et al., "Attention-Based Lane Change Prediction", ICRA, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8793648>paper</a> <a href=https://arxiv.org/pdf/1903.01246.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_recall">Recall</a></li>
<li><a href="metrics.md#metric_precision">Precision</a></li>
<li><a href="metrics.md#metric_ttm">TTM</a></li>
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
<summary><em>Scheel et al., "Situation Assessment For Planning Lane Changes: Combining Recurrent Models And Prediction", ICRA, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8462838/>paper</a> <a href=https://arxiv.org/pdf/1805.06776.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Scheel_2018_ICRA,
    author = "Scheel, O. and Schwarz, L. and Navab, N. and Tombari, F.",
    booktitle = "ICRA",
    title = "Situation Assessment For Planning Lane Changes: Combining Recurrent Models And Prediction",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chandra et al., "Traphic: Trajectory Prediction In Dense And Heterogeneous Traffic Using Weighted Interactions", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Chandra_TraPHic_Trajectory_Prediction_in_Dense_and_Heterogeneous_Traffic_Using_Weighted_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.04767.pdf>arxiv</a> <a href=https://go.umd.edu/TraPHic>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ngsim">NGSIM</a></li>
<li><a href="datasets.md#data_traf">TRAF</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chandra_2019_CVPR,
    author = "Chandra, Rohan and Bhattacharya, Uttaran and Bera, Aniket and Manocha, Dinesh",
    title = "Traphic: Trajectory Prediction In Dense And Heterogeneous Traffic Using Weighted Interactions",
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
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_eth">ETH</a></li>
<li><a href="datasets.md#data_ngsim">NGSIM</a></li>
<li><a href="datasets.md#data_sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
<li><a href="metrics.md#metric_rmse">RMSE</a></li>
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
<summary><em>Bi et al., "Joint Prediction For Kinematic Trajectories In Vehicle-Pedestrian-Mixed Scenes", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Bi_Joint_Prediction_for_Kinematic_Trajectories_in_Vehicle-Pedestrian-Mixed_Scenes_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ngsim">NGSIM</a></li>
<li><a href="datasets.md#data_vpm">VPM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
<summary><em>Thiede et al., "Analyzing The Variety Loss In The Context Of Probabilistic Trajectory Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Thiede_Analyzing_the_Variety_Loss_in_the_Context_of_Probabilistic_Trajectory_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1907.10178.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucy">UCY</a></li>
<li><a href="datasets.md#data_ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ll">LL</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Thiede_2019_ICCV,
    author = "Thiede, Luca Anthony and Brahma, Pratik Prabhanjan",
    title = "Analyzing The Variety Loss In The Context Of Probabilistic Trajectory Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Li et al., "Interaction-Aware Multi-Agent Tracking And Probabilistic Behavior Prediction Via Adversarial Learning", ICRA, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8793661>paper</a> <a href=https://arxiv.org/pdf/1904.02390.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2019_ICRA,
    author = "Li, J. and Ma, H. and Tomizuka, M.",
    booktitle = "ICRA",
    title = "Interaction-Aware Multi-Agent Tracking And Probabilistic Behavior Prediction Via Adversarial Learning",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Tang et al., "Adaptive Probabilistic Vehicle Trajectory Prediction Through Physically Feasible Bayesian Recurrent Neural Network", ICRA, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8794130>paper</a> <a href=https://arxiv.org/pdf/1911.04597.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ll">LL</a></li>
<li><a href="metrics.md#metric_kld">KLD</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tang_2019_ICRA,
    author = "Tang, C. and Chen, J. and Tomizuka, M.",
    booktitle = "ICRA",
    title = "Adaptive Probabilistic Vehicle Trajectory Prediction Through Physically Feasible Bayesian Recurrent Neural Network",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Cho et al., "Deep Predictive Autonomous Driving Using Multi-Agent Joint Trajectory Prediction And Traffic Rules", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8967708>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cho_2019_IROS,
    author = "Cho, Kyunghoon and Ha, Timothy and Lee, Gunmin and Oh, Songhwai",
    booktitle = "IROS",
    title = "Deep Predictive Autonomous Driving Using Multi-Agent Joint Trajectory Prediction And Traffic Rules",
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
@Misc{NGSIM_2007,
    author = "of Transporation, U.S. Department",
    Title = "Next Generation Simulation (Ngsim)",
    HowPublished = "Online",
    accessed = "2019-11-29",
    year = "2007"
}
</pre>
</details>

</ul></details>
<a name=data_lankershim_boulevard></a>
<details close>
<summary><l style="font-size:20px"><strong>Lankershim Boulevard</strong></l> <a href=https://www.fhwa.dot.gov/publications/research/operations/07029/index.cfm>link</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#trajectory>Trajectory prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, trajectory</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhi et al., "Kernel Trajectory Maps For Multi-Modal Probabilistic Motion Prediction", CoRL, 2019.</em> <a href=http://proceedings.mlr.press/v100/zhi20a/zhi20a.pdf>paper</a> <a href=https://arxiv.org/pdf/1907.05127.pdf>arxiv</a> <a href=https://github.com/wzhi/KernelTrajectoryMaps>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_eifp">EIFP</a></li>
<li><a href="datasets.md#data_lankershim_boulevard">Lankershim Boulevard</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_ade">ADE</a></li>
<li><a href="metrics.md#metric_fde">FDE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Misc{US_2007_Lankershim,
    author = "of Transportation, U.S. Department",
    title = "Lankershim Boulevard Dataset",
    url = "https://www.fhwa.dot.gov/publications/research/operations/07029/index.cfm",
    year = "2007"
}
</pre>
</details>

</ul></details>
<a name=data_eth_pedestrian></a>
<details close>
<summary><l style="font-size:20px"><strong>ETH Pedestrian</strong></l> <a href=https://data.vision.ee.ethz.ch/cvl/aess/>link</a> <a href=https://ieeexplore.ieee.org/document/4409092>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#action>Action prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hariyono et al., "Estimation Of Collision Risk For Improving Driver'S Safety", IECON, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7793743>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets.md#data_eth_pedestrian">ETH Pedestrian</a></li>
<li><a href="datasets.md#data_daimler">Daimler</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_accuracy">Accuracy</a></li>
<li><a href="metrics.md#metric_auc">AUC</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hariyono_2016_IES,
    author = "Hariyono, Joko and Shahbaz, Ajmal and Kurnianggoro, Laksono and Jo, Kang-Hyun",
    title = "Estimation Of Collision Risk For Improving Driver'S Safety",
    booktitle = "IECON",
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
@InProceedings{Ess_2007_ICCV,
    author = "Ess, Andreas and Leibe, Bastian and Van Gool, Luc",
    title = "Depth And Appearance For Mobile Scene Analysis",
    booktitle = "ICCV",
    year = "2007"
}
</pre>
</details>

</ul></details>
<a name=data_amos></a>
<details close>
<summary><l style="font-size:20px"><strong>AMOS</strong></l> <a href=http://amos.cse.wustl.edu/>link</a> <a href=https://ieeexplore.ieee.org/document/4270283>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#other>Other prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB, temperature, time</li>
<li><em><strong>Task:</strong></em> Weather</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chu et al., "Visual Weather Temperature Prediction", WACV, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8354136>paper</a> <a href=https://arxiv.org/pdf/1801.08267.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_amos">AMOS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_rmse">RMSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chu_2018_WACV,
    author = "Chu, W. and Ho, K. and Borji, A.",
    booktitle = "WACV",
    title = "Visual Weather Temperature Prediction",
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
@InProceedings{Jacobs_2007_CVPR,
    author = "Jacobs, Nathan and Roman, Nathaniel and Pless, Robert",
    title = "Consistent Temporal Variations In Many Outdoor Scenes",
    booktitle = "CVPR",
    year = "2007"
}
</pre>
</details>

</ul></details>
</ul><a name=datasets_2006></a>
<h2>2006</h2> <a href=#top>&uarr; top</a>
<ul><a name=data_tuscan></a>
<details close>
<summary><l style="font-size:20px"><strong>Tuscan, Arizona</strong></l> <a href=http://www.mmto.org/>link</a> <a href=https://www.spiedigitallibrary.org/conference-proceedings-of-spie/6267/62671A/The-MMT-all-sky-camera/10.1117/12.672508.short?SSO=1>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#other>Other prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Weather</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Siddiqui et al., "A Deep Learning Approach To Solar-Irradiance Forecasting In Sky-Videos", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8659184>paper</a> <a href=https://arxiv.org/pdf/1901.04881.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_arizona">Arizona</a></li>
<li><a href="datasets.md#data_tuscan">Tuscan</a></li>
<li><a href="datasets.md#data_golden_colorado">Golden Colorado</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_nmape">nMAPE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Siddiqui_2019_WACV,
    author = "Siddiqui, T. A. and Bharadwaj, S. and Kalyanaraman, S.",
    booktitle = "WACV",
    title = "A Deep Learning Approach To Solar-Irradiance Forecasting In Sky-Videos",
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
@Article{Pickering_2006,
    author = "Pickering, TE",
    title = "The Mmt All-Sky Camera",
    journal = "Ground-based and Airborne Telescopes",
    volume = "6267",
    pages = "62671A",
    year = "2006"
}
</pre>
</details>

</ul></details>
</ul><a name=datasets_2004></a>
<h2>2004</h2> <a href=#top>&uarr; top</a>
<ul><a name=data_kth></a>
<details close>
<summary><l style="font-size:20px"><strong>KTH</strong></l> <a href=http://www.nada.kth.se/cvap/actions/>link</a> <a href=https://ieeexplore.ieee.org/document/1334462>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#video>Video prediction<application></a></li>
<li><em><strong>Data type:</strong></em> Grayscale, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Lee et al., "Mutual Suppression Network For Video Prediction Using Disentangled Features", BMVC, 2019.</em> <a href=https://bmvc2019.org/wp-content/uploads/papers/0336-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.04810.pdf>arxiv</a> <a href=https://github.com/aras62/SF-GRU>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_kth">KTH</a></li>
<li><a href="datasets.md#data_msr">MSR</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
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
<summary><em>Li et al., "Flow-Grounded Spatial-Temporal Video Prediction From Still Images", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yin_Li_In_the_Eye_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.00626.pdf>arxiv</a> <a href=https://github.com/Yijunmaverick/FlowGrounded-VideoPrediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_human">Human</a></li>
<li><a href="metrics.md#metric_lpips">LPIPS</a></li>
<li><a href="metrics.md#metric_rmse">RMSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2018_ECCV,
    author = "Li, Yijun and Fang, Chen and Yang, Jimei and Wang, Zhaowen and Lu, Xin and Yang, Ming-Hsuan",
    title = "Flow-Grounded Spatial-Temporal Video Prediction From Still Images",
    booktitle = "ECCV",
    year = "2018"
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
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
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
<summary><em>Bhattacharjee et al., "Predicting Video Frames Using Feature Based Locally Guided Objectives", ACCV, 2019.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20870-7_42>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_ucf-101">UCF-101</a></li>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bhattacharjee_2018_ACCV,
    author = "Bhattacharjee, Prateep and Das, Sukhendu",
    editor = "Jawahar, C.V. and Li, Hongdong and Mori, Greg and Schindler, Konrad",
    title = "Predicting Video Frames Using Feature Based Locally Guided Objectives",
    booktitle = "ACCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Jin et al., "Varnet: Exploring Variations For Unsupervised Video Prediction", IROS, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8594264>paper</a> <a href=https://github.com/jinbeibei/VarNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_kitti">KITTI</a></li>
<li><a href="datasets.md#data_kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jin_2018_IROS,
    author = "Jin, B. and Hu, Y. and Zeng, Y. and Tang, Q. and Liu, S. and Ye, J.",
    booktitle = "IROS",
    title = "Varnet: Exploring Variations For Unsupervised Video Prediction",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "Predrnn: Recurrent Neural Networks For Predictive Learning Using Spatiotemporal Lstms", NeurIPS, 2017.</em> <a href=https://papers.nips.cc/paper/6689-predrnn-recurrent-neural-networks-for-predictive-learning-using-spatiotemporal-lstms.pdf>paper</a> <a href=https://github.com/ujjax/pred-rnn>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_mmnist">MMNIST</a></li>
<li><a href="datasets.md#data_kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_psnr">PSNR</a></li>
<li><a href="metrics.md#metric_ssim">SSIM</a></li>
<li><a href="metrics.md#metric_mse">MSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2017_NeurIPS,
    author = "Wang, Yunbo and Long, Mingsheng and Wang, Jianmin and Gao, Zhifeng and Yu, Philip S",
    title = "Predrnn: Recurrent Neural Networks For Predictive Learning Using Spatiotemporal Lstms",
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
@InProceedings{Schuldt_2004_ICPR,
    author = "Schuldt, Christian and Laptev, Ivan and Caputo, Barbara",
    title = "Recognizing Human Actions: A Local Svm Approach",
    booktitle = "ICPR",
    volume = "3",
    year = "2004"
}
</pre>
</details>

</ul></details>
</ul><a name=datasets_1981></a>
<h2>1981</h2> <a href=#top>&uarr; top</a>
<ul><a name=data_golden_colorado></a>
<details close>
<summary><l style="font-size:20px"><strong>Golden Colorado</strong></l> <a href=https://www.osti.gov/dataexplorer/biblio/dataset/1052221>link</a> <a href=>paper</a></summary> 
<ul><li>
<em><strong>Applications:</strong></em> <a href=papers.md#other>Other prediction<application></a></li>
<li><em><strong>Data type:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Weather</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Siddiqui et al., "A Deep Learning Approach To Solar-Irradiance Forecasting In Sky-Videos", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8659184>paper</a> <a href=https://arxiv.org/pdf/1901.04881.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets.md#data_arizona">Arizona</a></li>
<li><a href="datasets.md#data_tuscan">Tuscan</a></li>
<li><a href="datasets.md#data_golden_colorado">Golden Colorado</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#metric_nmape">nMAPE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Siddiqui_2019_WACV,
    author = "Siddiqui, T. A. and Bharadwaj, S. and Kalyanaraman, S.",
    booktitle = "WACV",
    title = "A Deep Learning Approach To Solar-Irradiance Forecasting In Sky-Videos",
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
@techreport{Stoffel_1981,
    author = "Stoffel, T and Andreas, A",
    title = "Nrel Solar Radiation Research Laboratory (Srrl): Baseline Measurement System (Bms); Golden, Colorado (Data)",
    year = "1981",
    institution = "National Renewable Energy Lab.(NREL)"
}
</pre>
</details>

</ul></details>
</ul>