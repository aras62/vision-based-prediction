<a name=top></a>
<a name=top></a>
---
<a href=../../../README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../datasets/datasets.md#top><l style="font-size:30px">Datasets</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Metrics</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
[Home](../../metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Video](../../video/video_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Action&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Trajectory](../../trajectory/trajectory_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Motion](../../motion/motion_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Other](../../other/other_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[Home](../action_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Alphabetical&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Ranking](../action_ranking/action_ranking_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[A-D](action_a-d_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;E-I&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[J-Z](action_j-z_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
<h2>E-I <small>[rank]</small></h2> 
<ul><a name=ed></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Euclidean Distance (ED)</strong><small> [11]</small></l>
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
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#ed">ED</a></li>
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
<summary><strong><em>Zhao et al., "AntGPT: Can Large Language Models Help Long-term Action Anticipation from Videos?", ICLR, 2024.</em></strong> <a href=https://openreview.net/pdf?id=Bb21JPnhhr>paper</a> <a href=https://arxiv.org/pdf/2307.16368>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#ego4d">Ego4D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#map">mAP</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Zhao_AntGPT_2024_ICLR,
    author = "Zhao, Qi and Wang, Shijie and Zhang, Ce and Fu, Changcheng and Do, Minh Quan and Agarwal, Nakul and Lee, Kwonjoon and Sun, Chen",
    title = "Ant{GPT}: Can Large Language Models Help Long-term Action Anticipation from Videos?",
    booktitle = "ICLR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=eid></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Edit Distance (EiD)</strong><small> [12]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Mascaro et al., "Intention-Conditioned Long-Term Human Egocentric Action Anticipation", WACV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/WACV2023/papers/Mascaro_Intention-Conditioned_Long-Term_Human_Egocentric_Action_Anticipation_WACV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#ego4d">Ego4D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#eid">EiD</a></li>
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
</ul>
</details>

</ul><ul><a name=f1></a>
<details close>
<summary><em><l style="font-size:20px"><strong>F1</strong><small> [4]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Kochakarn et al., "Explainable Action Prediction through Self-Supervision on Scene Graphs", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10161132>paper</a> <a href=https://arxiv.org/pdf/2302.03477.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#road">ROAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kochakarn_2023_ICRA,
    author = "Kochakarn, Pawit and De Martini, Daniele and Omeiza, Daniel and Kunze, Lars",
    title = "Explainable Action Prediction through Self-Supervision on Scene Graphs",
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
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#auc">AUC</a></li>
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
<summary><strong><em>Mascaro et al., "HOI4ABOT: Human-Object Interaction Anticipation for Human Intention Reading Collaborative roBOTs", CoRL, 2023.</em></strong> <a href=https://openreview.net/pdf?id=rYZBdBytxBx>paper</a> <a href=https://arxiv.org/pdf/2309.16524.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#vidhoi">VidHOI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#map">mAP</a></li>
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
<summary><strong><em>Hu et al., "Entry-Flipped Transformer for Inference and Prediction of Participant Behavior", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136640433.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.06235.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#ceilidh_dance">Ceilidh Dance</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
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
<summary><strong><em>Song et al., "Pedestrian Intention Prediction Based on Traffic-Aware Scene Graph Model", IROS, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9981690>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#auc">AUC</a></li>
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
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#map">mAP</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#auc">AUC</a></li>
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
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#auc">AUC</a></li>
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
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pepscenes">PepScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#auc">AUC</a></li>
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
<summary><strong><em>Kotseruba et al., "Benchmark for Evaluating Pedestrian Action Prediction", WACV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Kotseruba_Benchmark_for_Evaluating_Pedestrian_Action_Prediction_WACV_2021_paper.pdf>paper</a> <a href=https://github.com/ykotseruba/PedestrianActionBenchmark>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#auc">AUC</a></li>
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
<summary><strong><em>Liu et al., "Forecasting Human Object Interaction: Joint Prediction of Motor Attention and Actions in First Person Video", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460681.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.10967.pdf>arxiv</a> <a href=https://github.com/2020aptx4869lm/Forecasting-Human-Object-Interaction-in-FPV>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#kld">KLD</a></li>
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
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
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
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
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
<summary><strong><em>Rasouli et al., "Pedestrian Action Anticipation Using Contextual Feature Fusion In Stacked Rnns", BMVC, 2019.</em></strong> <a href=https://bmvc2019.org/wp-content/uploads/papers/0283-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.06582.pdf>arxiv</a> <a href=https://github.com/aras62/SF-GRU>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#auc">AUC</a></li>
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
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
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
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#ap">AP</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#run_time">Run Time</a></li>
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
<summary><strong><em>Suzuki et al., "Anticipating Traffic Accidents With Adaptive Loss And Large-Scale Incident Db", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0494.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.02675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#map">mAP</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#attc">ATTC</a></li>
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
<summary><strong><em>Schydlo et al., "Anticipation In Human-Robot Cooperation: A Recurrent Neural Network Approach For Multiple Action Sequences Prediction", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8460924>paper</a> <a href=https://arxiv.org/pdf/1802.10503.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#acticipate">ACTICIPATE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
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
<summary><strong><em>Qi et al., "Predicting Human Activities Using Stochastic Grammar", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Qi_Predicting_Human_Activities_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00945.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
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
<summary><strong><em>Jain et al., "Structural-RNN: Deep Learning On Spatio-Temporal Graphs", CVPR, 2016.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.05298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#ttm">TTM</a></li>
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
<summary><strong><em>Hu et al., "Human Intent Forecasting Using Intrinsic Kinematic Constraints", IROS, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7759141>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
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
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
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
</ul>
</details>

</ul><ul><a name=fde></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Final Displacement Error (FDE)</strong><small> [12]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Liu et al., "Forecasting Human Object Interaction: Joint Prediction of Motor Attention and Actions in First Person Video", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460681.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.10967.pdf>arxiv</a> <a href=https://github.com/2020aptx4869lm/Forecasting-Human-Object-Interaction-in-FPV>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#kld">KLD</a></li>
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

</ul><ul><a name=fp></a>
<details close>
<summary><em><l style="font-size:20px"><strong>False positive (FP)</strong><small> [12]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Jain et al., "Car That Knows Before You Do: Anticipating Maneuvers Via Learning Temporal Driving Models", ICCV, 2015.</em></strong> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Jain_Car_That_Knows_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1504.02789.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_j-z_metrics.md#ttm">TTM</a></li>
<li><a href="../../../metrics/action/action_alphabetical/action_e-i_metrics.md#fp">FP</a></li>
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