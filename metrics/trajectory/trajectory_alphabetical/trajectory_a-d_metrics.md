<a name=top></a>
<a name=top></a>
---
<a href=../../../README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../datasets/datasets.md#top><l style="font-size:30px">Datasets</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Metrics</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
[Home](../../metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Video](../../video/video_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Action](../../action/action_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Trajectory&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Motion](../../motion/motion_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Other](../../other/other_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[Home](../trajectory_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Alphabetical&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Ranking](../trajectory_ranking/trajectory_ranking_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
A-D&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[E-I](trajectory_e-i_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[J-Z](trajectory_j-z_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
<h2>A-D <small>[rank]</small></h2> 
<ul><a name=aae></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Average Angular Expansion (AAE)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Chen et al., "CRITERIA: a New Benchmarking Paradigm for Evaluating Trajectory Prediction Models for Autonomous Driving", ICRA, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10610911>paper</a> <a href=https://arxiv.org/pdf/2310.07794>arxiv</a> <a href=https://github.com/huawei-noah/SMARTS/tree/CRITERIA-latest/papers/CRITERIA>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#dac">DAC</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#dao">DAO</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#amv">AMV</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minasd">minASD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfsd">minFSD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rf">RF</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#att">ATT</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#aae">AAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Chen_CRITERIA_2024_ICRA,
    author = "Chen, Changhe and Pourkeshavarz, Mozhgan and Rasouli, Amir",
    booktitle = "ICRA",
    title = "CRITERIA: a New Benchmarking Paradigm for Evaluating Trajectory Prediction Models for Autonomous Driving",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=absdelta></a>
<details close>
<summary><em><l style="font-size:20px"><strong>absDelta</strong><small> [20]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Pourkeshavarz et al., "CaDeT: a Causal Disentanglement Approach for Robust Trajectory Prediction in Autonomous Driving", CVPR, 2024.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Pourkeshavarz_CaDeT_a_Causal_Disentanglement_Approach_for_Robust_Trajectory_Prediction_in_CVPR_2024_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#absdelta">absDelta</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#prs">PRS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Pourkeshavarz_CaDeT_2024_CVPR,
    author = "Pourkeshavarz, Mozhgan and Zhang, Junrui and Rasouli, Amir",
    title = "CaDeT: a Causal Disentanglement Approach for Robust Trajectory Prediction in Autonomous Driving",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Sun et al., "CausalAgents: A Robustness Benchmark for Motion Forecasting", ICRA, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10610186>paper</a> <a href=https://arxiv.org/pdf/2207.03586>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#absdelta">absDelta</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Sun_CausalAgents_2024_ICRA,
    author = "Sun, Liting and Roelofs, Rebecca and Caine, Ben and Refaat, Khaled S. and Sapp, Ben and Ettinger, Scott and Chai, Wei",
    booktitle = "ICRA",
    title = "CausalAgents: A Robustness Benchmark for Motion Forecasting",
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
<summary><em><l style="font-size:20px"><strong>Accuracy</strong><small> [16]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Wang et al., "ESP: Extro-Spective Prediction for Long-term Behavior Reasoning in Emergency Scenarios", ICRA, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10610002>paper</a> <a href=https://arxiv.org/pdf/2405.04100>arxiv</a> <a href=https://github.com/Dingrui-Wang/ESP-Dataset>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#esp">ESP</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mincte">minCTE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Wang_ESP_2024_ICRA,
    author = "Wang, Dingrui and Lai, Zheyuan and Li, Yuda and Wu, Yi and Ma, Yuexin and Betz, Johannes and Yang, Ruigang and Li, Wei",
    booktitle = "ICRA",
    title = "ESP: Extro-Spective Prediction for Long-term Behavior Reasoning in Emergency Scenarios",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wang et al., "BE-STI: Spatial-Temporal Integrated Network for Class-Agnostic Motion Prediction With Bidirectional Enhancement", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_BE-STI_Spatial-Temporal_Integrated_Network_for_Class-Agnostic_Motion_Prediction_With_Bidirectional_CVPR_2022_paper.pdf>paper</a> <a href=https://github.com/be-sti/be-sti>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2022_CVPR_2,
    author = "Wang, Yunlong and Pan, Hongyu and Zhu, Jun and Wu, Yu-Huan and Zhan, Xin and Jiang, Kun and Yang, Diange",
    title = "{BE-STI}: Spatial-Temporal Integrated Network for Class-Agnostic Motion Prediction With Bidirectional Enhancement",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wu et al., "MotionNet: Joint Perception and Motion Prediction for Autonomous Driving Based on Bird's Eye View Maps", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Wu_MotionNet_Joint_Perception_and_Motion_Prediction_for_Autonomous_Driving_Based_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.06754.pdf>arxiv</a> <a href=https://www.merl.com/research/license#MotionNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wu_2020_CVPR_2,
    author = "Wu, Pengxiang and Chen, Siheng and Metaxas, Dimitris N.",
    title = "{MotionNet}: Joint Perception and Motion Prediction for Autonomous Driving Based on Bird's Eye View Maps",
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
<details close>
<summary><strong><em>Kim et al., "Instance-Level Future Motion Estimation In A Single Image Based On Ordinal Regression", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Kim_Instance-Level_Future_Motion_Estimation_in_a_Single_Image_Based_on_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#fm">FM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#accuracy">Accuracy</a></li>
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
<details close>
<summary><strong><em>Solaimanpour et al., "A Layered HMM For Predicting Motion Of A Leader In Multi-Robot Settings", ICRA, 2017.</em></strong> <a href=https://ieeexplore.ieee.org/document/7989097>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#kld">KLD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Solaimanpour_2017_ICRA,
    author = "Solaimanpour, S. and Doshi, P.",
    booktitle = "ICRA",
    title = "A Layered {HMM} For Predicting Motion Of A Leader In Multi-Robot Settings",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=ade></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Average Displacement Error (ADE)</strong><small> [3]</small></l>
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
<summary><strong><em>Wang et al., "Self-Supervised Class-Agnostic Motion Prediction with Spatial and Temporal Consistency Regularizations", CVPR, 2024.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Wang_Self-Supervised_Class-Agnostic_Motion_Prediction_with_Spatial_and_Temporal_Consistency_Regularizations_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2403.13261>arxiv</a> <a href=https://github.com/kwwcv/SelfMotion>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_Self_2024_CVPR,
    author = "Wang, Kewei and Wu, Yizheng and Cen, Jun and Pan, Zhiyu and Li, Xingyi and Wang, Zhe and Cao, Zhiguo and Lin, Guosheng",
    title = "Self-Supervised Class-Agnostic Motion Prediction with Spatial and Temporal Consistency Regularizations",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Yang et al., "Generalized Predictive Model for Autonomous Driving", CVPR, 2024.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Yang_Generalized_Predictive_Model_for_Autonomous_Driving_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2403.09630>arxiv</a> <a href=https://github.com/OpenDriveLab/DriveAGI>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#opendv-2k">OpenDV-2K</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yang_Generalized_2024_CVPR,
    author = "Yang, Jiazhi and Gao, Shenyuan and Qiu, Yihang and Chen, Li and Li, Tianyu and Dai, Bo and Chitta, Kashyap and Wu, Penghao and Zeng, Jia and Luo, Ping and Zhang, Jun and Geiger, Andreas and Qiao, Yu and Li, Hongyang",
    title = "Generalized Predictive Model for Autonomous Driving",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhang et al., "OOSTraj: Out-of-Sight Trajectory Prediction With Vision-Positioning Denoising", CVPR, 2024.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_OOSTraj_Out-of-Sight_Trajectory_Prediction_With_Vision-Positioning_Denoising_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2404.02227>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jrdb">JRDB</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#vi-fi">Vi-Fi</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_OOSTraj_2024_CVPR,
    author = "Zhang, Haichao and Xu, Yi and Lu, Hongsheng and Shimizu, Takayuki and Fu, Yun",
    title = "OOSTraj: Out-of-Sight Trajectory Prediction With Vision-Positioning Denoising",
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
<summary><strong><em>Xiao et al., "Multi-Camera Asynchronous Ball Localization and Trajectory Prediction with Factor Graphs and Human Poses", ICRA, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10610631>paper</a> <a href=https://arxiv.org/pdf/2401.17185>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Xiao_Multi_2024_ICRA,
    author = "Xiao, Qingyu and Zaidi, Zulfiqar and Gombolay, Matthew",
    booktitle = "ICRA",
    title = "Multi-Camera Asynchronous Ball Localization and Trajectory Prediction with Factor Graphs and Human Poses",
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
<summary><strong><em>Si et al., "Trajectory-prediction-based Dynamic Tracking of a UGV to a Moving Target under Multi-disturbed Conditions", ICRA, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10611690>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Si_Trajectory_2024_ICRA,
    author = "Si, Jinge and Li, Bin and Xu, Yongkang and Wang, Liang and Deng, Chencheng and Wang, Shoukun and Wang, Junzheng",
    booktitle = "ICRA",
    title = "Trajectory-prediction-based Dynamic Tracking of a UGV to a Moving Target under Multi-disturbed Conditions",
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
<summary><strong><em>Feng et al., "Multimodal Forward Generation Transformer Network for Inconspicuous Pedestrian Trajectory Prediction", RAL, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10382571>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
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
<summary><strong><em>Xu et al., "EqMotion: Equivariant Multi-Agent Motion Prediction With Invariant Interaction Reasoning", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Xu_Uncovering_the_Missing_Pattern_Unified_Framework_Towards_Trajectory_Imputation_and_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.16005.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nfl">NFL</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#omni-mot">Omni-MOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
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
<summary><strong><em>Jiao et al., "Semi-supervised Semantics-guided Adversarial Training for Robust Trajectory Prediction", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Jiao_Semi-supervised_Semantics-guided_Adversarial_Training_for_Robust_Trajectory_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2205.14230.pdf>arxiv</a> <a href=https://github.com/jrcblue/SSAT-for-Motion-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#l2">L2</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jiao_2023_ICCV,
    author = "Jiao, Ruochen and Liu, Xiangguo and Sato, Takami and Chen, Qi Alfred and Zhu, Qi",
    title = "Semi-supervised Semantics-guided Adversarial Training for Robust Trajectory Prediction",
    booktitle = "ICCV",
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
<summary><strong><em>Xie et al., "A Critical view of Vision-based Long-term Dynamics Prediction under Environment Misalignment", ICML, 2023.</em></strong> <a href=http://proceedings.mlr.press/v202/xie23e/xie23e.pdf>paper</a> <a href=https://arxiv.org/pdf/2305.07648.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#vdp-emc">VDP-EMC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xie_2023_ICML,
    author = "Xie, Hanchen and Zhu, Jiageng and Khayatkhoei, Mahyar and Li, Jiazhi and Hussein, Mohamed E and AbdAlmageed, Wael",
    title = "A Critical view of Vision-based Long-term Dynamics Prediction under Environment Misalignment",
    booktitle = "ICML",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
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
<summary><strong><em>Wakulicz et al., "Topological Trajectory Prediction with Homotopy Classes", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10160250>paper</a> <a href=https://arxiv.org/pdf/2301.09821.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#atc">ATC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#kld">KLD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#amd">AMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wakulicz_2023_ICRA,
    author = "Wakulicz, Jennifer and Brian Lee, Ki Myung and Vidal-Calleja, Teresa and Fitch, Robert",
    title = "Topological Trajectory Prediction with Homotopy Classes",
    booktitle = "ICRA",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Knittel et al., "DiPA: Probabilistic Multi-Modal Interactive Prediction for Autonomous Driving", RAL, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10146507>paper</a> <a href=https://arxiv.org/pdf/2210.06106>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Knittel_DiPA_2023_RAL,
    author = "Knittel, Anthony and Hawasly, Majd and Albrecht, Stefano V. and Redford, John and Ramamoorthy, Subramanian",
    journal = "RAL",
    title = "DiPA: Probabilistic Multi-Modal Interactive Prediction for Autonomous Driving",
    year = "2023",
    volume = "8",
    number = "8",
    pages = "4887-4894"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Atkins et al., "MIntNet: Rapid Motion Intention Forecasting of Coupled Human-Robot Systems With Simulation-to-Real Autoregressive Neural Networks", RAL, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10224287>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Atkins_MIntNet_2023_RAL,
    author = "Atkins, John and Lee, Hyunglae",
    journal = "RAL",
    title = "MIntNet: Rapid Motion Intention Forecasting of Coupled Human-Robot Systems With Simulation-to-Real Autoregressive Neural Networks",
    year = "2023",
    volume = "8",
    number = "10",
    pages = "6363-6370"
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
<summary><strong><em>Wen et al., "Social ODE: Multi-agent Trajectory Forecasting with Neural Ordinary Differential Equations", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820211.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#ind">inD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#round">rounD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wen_2022_ECCV,
    author = "Wen, Song and Wang, Hao and Metaxas, Dimitris N.",
    title = "{Social ODE}: Multi-agent Trajectory Forecasting with Neural Ordinary Differential Equations",
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
<summary><strong><em>Liao et al., "Online Prediction of Lane Change with a Hierarchical Learning-Based Approach", ICRA, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/document/9812269>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liao_2022_ICRA,
    author = "Liao, Xishun and Wang, Ziran and Zhao, Xuanpeng and Zhao, Zhouqiao and Han, Kyungtae and Tiwari, Prashant and Barth, Matthew J. and Wu, Guoyuan",
    booktitle = "ICRA",
    title = "Online Prediction of Lane Change with a Hierarchical Learning-Based Approach",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>McAllister et al., "Control-Aware Prediction Objectives for Autonomous Driving", ICRA, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/document/9811884>paper</a> <a href=https://arxiv.org/pdf/2204.13319.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{McAllister_2022_ICRA,
    author = "McAllister, Rowan and Wulfe, Blake and Mercat, Jean and Ellis, Logan and Levine, Sergey and Gaidon, Adrien",
    booktitle = "ICRA",
    title = "Control-Aware Prediction Objectives for Autonomous Driving",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Cheng et al., "Long-Term Trajectory Prediction of the Human Hand and Duration Estimation of the Human Action", RAL, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9599389>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Cheng_Long_2022_RAL,
    author = "Cheng, Yujiao and Tomizuka, Masayoshi",
    journal = "RAL",
    title = "Long-Term Trajectory Prediction of the Human Hand and Duration Estimation of the Human Action",
    year = "2022",
    volume = "7",
    number = "1",
    pages = "247-254"
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
<summary><strong><em>Tang et al., "Interventional Behavior Prediction: Avoiding Overly Confident Anticipation in Interactive Prediction", IROS, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9981524>paper</a> <a href=https://arxiv.org/pdf/2204.08665.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tang_2022_IROS,
    author = "Tang, Chen and Zhan, Wei and Tomizuka, Masayoshi",
    booktitle = "IROS",
    title = "Interventional Behavior Prediction: Avoiding Overly Confident Anticipation in Interactive Prediction",
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
<summary><strong><em>Bergamini et al., "SimNet: Learning Reactive Self-driving Simulations from Real-world Observations", ICRA, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9561666>paper</a> <a href=https://arxiv.org/pdf/2105.12332.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bergamini_2021_ICRA,
    author = "Bergamini, Luca and Ye, Yawei and Scheel, Oliver and Chen, Long and Hu, Chih and Del Pero, Luca and Osiński, Błażej and Grimmett, Hugo and Ondruska, Peter",
    booktitle = "ICRA",
    title = "{SimNet}: Learning Reactive Self-driving Simulations from Real-world Observations",
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
<summary><strong><em>Anderson et al., "A Kinematic Model for Trajectory Prediction in General Highway Scenarios", RAL, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/document/9472993>paper</a> <a href=https://arxiv.org/pdf/2103.16673.pdf>arxiv</a> <a href=https://github.com/umautobots/kinematic_highway>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rmse">RMSE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#qde">QDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Anderson_2021_RAL,
    author = "Anderson, Cyrus and Vasudevan, Ram and Johnson-Roberson, Matthew",
    journal = "RAL",
    title = "A Kinematic Model for Trajectory Prediction in General Highway Scenarios",
    year = "2021",
    volume = "6",
    number = "4",
    pages = "6757-6764"
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
<summary><strong><em>Yu et al., "Towards Robust Human Trajectory Prediction in Raw Videos", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636831>paper</a> <a href=https://arxiv.org/pdf/2108.08259.pdf>arxiv</a> <a href=https://github.com/rui-yu-public/Retracking-by-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mota">MOTA</a></li>
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
<summary><strong><em>Sun et al., "On Complementing End-to-end Human Behavior Predictors with Planning", RSS, 2021.</em></strong> <a href=http://www.roboticsproceedings.org/rss17/p037.pdf>paper</a> <a href=https://arxiv.org/pdf/2103.05661.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2021_RSS,
    AUTHOR = "Sun, Liting and Jia, Xiaogang and Dragan, Anca",
    TITLE = "On Complementing End-to-end Human Behavior Predictors with Planning",
    BOOKTITLE = "RSS",
    YEAR = "2021"
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
<summary><strong><em>Zhang et al., "STINet: Spatio-Temporal-Interactive Network for Pedestrian Detection and Trajectory Prediction", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_STINet_Spatio-Temporal-Interactive_Network_for_Pedestrian_Detection_and_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.04255.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#bev_ap">BEV AP</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#de">DE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2020_CVPR,
    author = "Zhang, Zhishuai and Gao, Jiyang and Mao, Junhua and Liu, Yukai and Anguelov, Dragomir and Li, Congcong",
    title = "{STINet}: Spatio-Temporal-Interactive Network for Pedestrian Detection and Trajectory Prediction",
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
<summary><strong><em>Wang et al., "V2VNet: Vehicle-to-vehicle Communication for Joint Perception and Prediction", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470596.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.07519.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#tcr">TCR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2020_ECCV,
    author = "Wang, Tsun-Hsuan and Manivasagam, Sivabalan and Liang, Ming and Yang, Bin and Zeng, Wenyuan and Tu, James and Urtasun, Raquel",
    title = "{V2VNet}: Vehicle-to-vehicle Communication for Joint Perception and Prediction",
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
<summary><strong><em>Anderson et al., "Off the Beaten Sidewalk: Pedestrian Prediction in Shared Spaces for Autonomous Vehicles", RAL, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9195734>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#ind">inD</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#dut">DUT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Anderson_Off_2020_RAL,
    author = "Anderson, Cyrus and Vasudevan, Ram and Johnson-Roberson, Matthew",
    journal = "RAL",
    title = "Off the Beaten Sidewalk: Pedestrian Prediction in Shared Spaces for Autonomous Vehicles",
    year = "2020",
    volume = "5",
    number = "4",
    pages = "6892-6899"
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
<summary><strong><em>Houston et al., "One Thousand and One Hours: Self-driving Motion Prediction Dataset", CoRL, 2020.</em></strong> <a href=https://proceedings.mlr.press/v155/houston21a/houston21a.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.14480.pdf>arxiv</a> <a href=https://github.com/lyft/l5kit>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#otoh">OTOH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Houston_2020_CORL,
    author = "Houston, John and Zuidhof, Guido and Bergamini, Luca and Ye, Yawei and Chen, Long and Jain, Ashesh and Omari, Sammy and Iglovikov, Vladimir and Ondruska, Peter",
    title = "One Thousand and One Hours: Self-driving Motion Prediction Dataset",
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
<summary><strong><em>Henaff et al., "Model-Predictive Policy Learning with Uncertainty Regularization for Driving in Dense Traffic", ICLR, 2019.</em></strong> <a href=https://openreview.net/pdf?id=HygQBn0cYm>paper</a> <a href=https://openreview.net/pdf?id=HygQBn0cYm>arxiv</a> <a href=https://github.com/atcold/pytorch-PPUU>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Henaff_2019_ICLR,
    author = "Henaff, Mikael and Canziani, Alfredo and LeCun, Yann",
    title = "Model-Predictive Policy Learning with Uncertainty Regularization for Driving in Dense Traffic",
    booktitle = "ICLR",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Huang et al., "Uncertainty-Aware Driver Trajectory Prediction At Urban Intersections", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8794282>paper</a> <a href=https://arxiv.org/pdf/1901.05105.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Huang_2019_ICRA,
    author = "Huang, X. and McGill, S. G. and Williams, B. C. and Fletcher, L. and Rosman, G.",
    booktitle = "ICRA",
    title = "Uncertainty-Aware Driver Trajectory Prediction At Urban Intersections",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Li et al., "Interaction-Aware Multi-Agent Tracking And Probabilistic Behavior Prediction Via Adversarial Learning", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8793661>paper</a> <a href=https://arxiv.org/pdf/1904.02390.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
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
<summary><strong><em>Cho et al., "Deep Predictive Autonomous Driving Using Multi-Agent Joint Trajectory Prediction And Traffic Rules", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8967708>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
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
<details close>
<summary><strong><em>Srikanth et al., "INFER: INtermediate Representations For FuturE PRediction", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8968553>paper</a> <a href=https://arxiv.org/pdf/1903.10641.pdf>arxiv</a> <a href=https://rebrand.ly/INFER-results>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#oxford">Oxford</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
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
<summary><strong><em>Zhou et al., "Clone Swarms: Learning To Predict And Control Multi-Robot Systems By Imitation", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8967824>paper</a> <a href=https://arxiv.org/pdf/1912.02811.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhou_2019_IROS,
    author = "Zhou, Siyu and Phielipp, Mariano J and Sefair, Jorge A and Walker, Sara I and Amor, Heni Ben",
    booktitle = "IROS",
    title = "Clone Swarms: Learning To Predict And Control Multi-Robot Systems By Imitation",
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
<summary><strong><em>Sanchez-Matilla et al., "A Predictor Of Moving Objects For First-Person Vision", ICIP, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8803140>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#mot">MOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
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
<details close>
<summary><strong><em>Bhattacharyya et al., "Long-Term On-Board Prediction Of People In Traffic Scenes Under Uncertainty", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Bhattacharyya_Long-Term_On-Board_Prediction_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1711.09026.pdf>arxiv</a> <a href=https://github.com/apratimbhattacharyya18/onboard_long_term_prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityperson">CityPerson</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
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
<summary><strong><em>Yao et al., "Multiple Granularity Group Interaction Prediction", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0721.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#ca">CA</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sbuki">SBUKI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
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
<summary><strong><em>Felsen et al., "Where Will They Go? Predicting Fine-Grained Adversarial Multi-Agent Motion Using Conditional Variational Autoencoders", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Panna_Felsen_Where_Will_They_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#btd">BTD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#maxd">maxD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Felsen_2018_ECCV,
    author = "Felsen, Panna and Lucey, Patrick and Ganguly, Sujoy",
    title = "Where Will They Go? Predicting Fine-Grained Adversarial Multi-Agent Motion Using Conditional Variational Autoencoders",
    booktitle = "ECCV",
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
<summary><strong><em>Sun et al., "3Dof Pedestrian Trajectory Prediction Learned From Long-Term Autonomous Mobile Robot Deployment Data", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8461228>paper</a> <a href=https://arxiv.org/pdf/1710.00126.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#strands">STRANDS</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#l-cas">L-CAS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#aede">AEDE</a></li>
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
<summary><strong><em>Shen et al., "Transferable Pedestrian Motion Prediction Models At Intersections", IROS, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8593783>paper</a> <a href=https://arxiv.org/pdf/1804.00495.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#run_time">Run Time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shen_2018_IROS,
    author = "Shen, M. and Habibi, G. and How, J. P.",
    booktitle = "IROS",
    title = "Transferable Pedestrian Motion Prediction Models At Intersections",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhang et al., "Integrating Kinematics And Environment Context Into Deep Inverse Reinforcement Learning For Predicting Off-Road Vehicle Trajectories", CoRL, 2018.</em></strong> <a href=http://proceedings.mlr.press/v87/zhang18a/zhang18a.pdf>paper</a> <a href=https://arxiv.org/pdf/1810.07225.pdf>arxiv</a> <a href=https://github.com/yfzhang/vehicle-motion-forecasting>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2018_CORL,
    author = "Zhang, Yanfu and Wang, Wenshan and Bonatti, Rogerio and Maturana, Daniel and Scherer, Sebastian",
    title = "Integrating Kinematics And Environment Context Into Deep Inverse Reinforcement Learning For Predicting Off-Road Vehicle Trajectories",
    booktitle = "CoRL",
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
<summary><strong><em>Bartoli et al., "Context-Aware Trajectory Prediction", ICPR, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8545447>paper</a> <a href=https://arxiv.org/pdf/1705.02503.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
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
<details close>
<summary><strong><em>Solaimanpour et al., "A Layered HMM For Predicting Motion Of A Leader In Multi-Robot Settings", ICRA, 2017.</em></strong> <a href=https://ieeexplore.ieee.org/document/7989097>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#kld">KLD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Solaimanpour_2017_ICRA,
    author = "Solaimanpour, S. and Doshi, P.",
    booktitle = "ICRA",
    title = "A Layered {HMM} For Predicting Motion Of A Leader In Multi-Robot Settings",
    year = "2017"
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
<summary><strong><em>Yoo et al., "Visual Path Prediction In Complex Scenes With Crowded Moving Objects", CVPR, 2016.</em></strong> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Yoo_Visual_Path_Prediction_CVPR_2016_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#qmul">QMUL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#precision">Precision</a></li>
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
<summary><strong><em>Ballan et al., "Knowledge Transfer For Scene-Specific Motion Prediction", ECCV, 2016.</em></strong> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46448-0_42>paper</a> <a href=https://arxiv.org/pdf/1603.06987.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdd">SDD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
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
<details close>
<summary><strong><em>Robicquet et al., "Learning Social Etiquette: Human Trajectory Understanding in Crowded Scenes", ECCV, 2016.</em></strong> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46484-8_33>paper</a></summary>
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
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Robicquet_2016_ECCV,
    author = "Robicquet, Alexandre and Sadeghian, Amir and Alahi, Alexandre and Savarese, Silvio",
    title = "Learning Social Etiquette: Human Trajectory Understanding in Crowded Scenes",
    booktitle = "ECCV",
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
<details close>
<summary><strong><em>Vasquez, "Novel Planning-Based Algorithms For Human Motion Prediction", ICRA, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/7487505>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#virat">VIRAT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#run_time">Run Time</a></li>
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
<details close>
<summary><strong><em>Zhou et al., "Learning Time Series Models For Pedestrian Motion Prediction", ICRA, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7487506>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhou_2016_ICRA,
    author = "Zhou, Chenghui and Balle, B. and Pineau, J.",
    booktitle = "ICRA",
    title = "Learning Time Series Models For Pedestrian Motion Prediction",
    year = "2016"
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

</ul><ul><a name=aede></a>
<details close>
<summary><em><l style="font-size:20px"><strong>AEDE</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Sun et al., "3Dof Pedestrian Trajectory Prediction Learned From Long-Term Autonomous Mobile Robot Deployment Data", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8461228>paper</a> <a href=https://arxiv.org/pdf/1710.00126.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#strands">STRANDS</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#l-cas">L-CAS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#aede">AEDE</a></li>
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
</ul>
</details>

</ul><ul><a name=aer></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Avergae Error Rate (AER)</strong><small> [21]</small></l>
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

</ul><ul><a name=aiou></a>
<details close>
<summary><em><l style="font-size:20px"><strong>AIoU</strong><small> [21]</small></l>
</em></summary>
<ul>
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
</ul>
</details>

</ul><ul><a name=al></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Average Likelihood (AL)</strong><small> [21]</small></l>
</em></summary>
<ul>
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
</ul>
</details>

</ul><ul><a name=amd></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Average Mahalanobis Distance (AMD)</strong><small> [20]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Wakulicz et al., "Topological Trajectory Prediction with Homotopy Classes", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10160250>paper</a> <a href=https://arxiv.org/pdf/2301.09821.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#atc">ATC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#kld">KLD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#amd">AMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wakulicz_2023_ICRA,
    author = "Wakulicz, Jennifer and Brian Lee, Ki Myung and Vidal-Calleja, Teresa and Fitch, Robert",
    title = "Topological Trajectory Prediction with Homotopy Classes",
    booktitle = "ICRA",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Mohamed et al., "Social-Implicit: Rethinking Trajectory Prediction Evaluation and the Effectiveness of Implicit Maximum Likelihood Estimation", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820451.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.03057.pdf>arxiv</a> <a href=https://github.com/abduallahmohamed/Social-Implicit/>code</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#kde">KDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#amv">AMV</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#amd">AMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mohamed_2022_ECCV,
    author = "Mohamed, Abduallah and Zhu, Deyao and Vu, Warren and Elhoseiny, Mohamed and Claudel, Christian",
    title = "{Social-Implicit}: Rethinking Trajectory Prediction Evaluation and the Effectiveness of Implicit Maximum Likelihood Estimation",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=amv></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Average Magnitude Variation (AMV)</strong><small> [20]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Chen et al., "CRITERIA: a New Benchmarking Paradigm for Evaluating Trajectory Prediction Models for Autonomous Driving", ICRA, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10610911>paper</a> <a href=https://arxiv.org/pdf/2310.07794>arxiv</a> <a href=https://github.com/huawei-noah/SMARTS/tree/CRITERIA-latest/papers/CRITERIA>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#dac">DAC</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#dao">DAO</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#amv">AMV</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minasd">minASD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfsd">minFSD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rf">RF</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#att">ATT</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#aae">AAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Chen_CRITERIA_2024_ICRA,
    author = "Chen, Changhe and Pourkeshavarz, Mozhgan and Rasouli, Amir",
    booktitle = "ICRA",
    title = "CRITERIA: a New Benchmarking Paradigm for Evaluating Trajectory Prediction Models for Autonomous Driving",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Mohamed et al., "Social-Implicit: Rethinking Trajectory Prediction Evaluation and the Effectiveness of Implicit Maximum Likelihood Estimation", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820451.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.03057.pdf>arxiv</a> <a href=https://github.com/abduallahmohamed/Social-Implicit/>code</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#kde">KDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#amv">AMV</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#amd">AMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mohamed_2022_ECCV,
    author = "Mohamed, Abduallah and Zhu, Deyao and Vu, Warren and Elhoseiny, Mohamed and Claudel, Christian",
    title = "{Social-Implicit}: Rethinking Trajectory Prediction Evaluation and the Effectiveness of Implicit Maximum Likelihood Estimation",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=ande></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Average Nonlinear Displacement Error (ANDE)</strong><small> [20]</small></l>
</em></summary>
<ul>
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
</ul>
</details>

</ul><ul><a name=ap></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Average Precision (AP)</strong><small> [20]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Peri et al., "Forecasting From LiDAR via Future Object Detection", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Peri_Forecasting_From_LiDAR_via_Future_Object_Detection_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.16297.pdf>arxiv</a> <a href=https://github.com/neeharperi/FutureDet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ap">AP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Peri_2022_CVPR,
    author = "Peri, Neehar and Luiten, Jonathon and Li, Mengtian and O\v{s}ep, Aljo\v{s}a and Leal-Taix\'e, Laura and Ramanan, Deva",
    title = "Forecasting From {LiDAR} via Future Object Detection",
    booktitle = "CVPR",
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
</ul>
</details>

</ul><ul><a name=apad></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Average Path Deviation (APaD)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Oh et al., "Impact of Traffic Lights on Trajectory Forecasting of Human-driven Vehicles near Signalized Intersections", IROS, 2020.</em></strong> <a href=http://ras.papercept.net/images/temp/IROS/files/3159.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.00486.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#spmd">SPMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#apad">APaD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#twae">TWAE</a></li>
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
</ul>
</details>

</ul><ul><a name=app></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Average Prediction Probability (APP)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Rehder et al., "Pedestrian Prediction By Planning Using Deep Neural Networks", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8460203>paper</a> <a href=https://arxiv.org/pdf/1706.05904.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#app">APP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rehder_2018_ICRA,
    author = "Rehder, E. and Wirth, F. and Lauer, M. and Stiller, C.",
    booktitle = "ICRA",
    title = "Pedestrian Prediction By Planning Using Deep Neural Networks",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=arb></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Average RMSE of Bounding box (ARB)</strong><small> [20]</small></l>
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

</ul><ul><a name=asd></a>
<details close>
<summary><em><l style="font-size:20px"><strong>ASD</strong><small> [21]</small></l>
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

</ul><ul><a name=ate></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Along Track Error (ATE)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Cui et al., "GoRela: Go Relative for Viewpoint-Invariant Motion Forecasting", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10160984>paper</a> <a href=https://arxiv.org/pdf/2211.02545.pdf>arxiv</a> <a href=https://waabi.ai/research/go-relative-for-viewpoint-invariant-motion-forecasting>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#highwaysim">HighwaySim</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#cte">CTE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ate">ATE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cui_2023_ICRA,
    author = "Cui, Alexander and Casas, Sergio and Wong, Kelvin and Suo, Simon and Urtasun, Raquel",
    title = "GoRela: Go Relative for Viewpoint-Invariant Motion Forecasting",
    booktitle = "ICRA",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=att></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Admissibility Triad Test (ATT)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Chen et al., "CRITERIA: a New Benchmarking Paradigm for Evaluating Trajectory Prediction Models for Autonomous Driving", ICRA, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10610911>paper</a> <a href=https://arxiv.org/pdf/2310.07794>arxiv</a> <a href=https://github.com/huawei-noah/SMARTS/tree/CRITERIA-latest/papers/CRITERIA>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#dac">DAC</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#dao">DAO</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#amv">AMV</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minasd">minASD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfsd">minFSD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rf">RF</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#att">ATT</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#aae">AAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Chen_CRITERIA_2024_ICRA,
    author = "Chen, Changhe and Pourkeshavarz, Mozhgan and Rasouli, Amir",
    booktitle = "ICRA",
    title = "CRITERIA: a New Benchmarking Paradigm for Evaluating Trajectory Prediction Models for Autonomous Driving",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=auc></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Area Under the Curve (AUC)</strong><small> [21]</small></l>
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
</ul>
</details>

</ul><ul><a name=b-ade></a>
<details close>
<summary><em><l style="font-size:20px"><strong>b-ADE</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Acharya et al., "Learning to Forecast Aleatoric and Epistemic Uncertainties over Long Horizon Trajectories", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10160766>paper</a> <a href=https://arxiv.org/pdf/2302.08669.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mmd">MMD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-ade">b-ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Acharya_2023_ICRA,
    author = "Acharya, Aastha and Russell, Rebecca and Ahmed, Nisar R.",
    title = "Learning to Forecast Aleatoric and Epistemic Uncertainties over Long Horizon Trajectories",
    booktitle = "ICRA",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=b-minade></a>
<details close>
<summary><em><l style="font-size:20px"><strong>b-minADE</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Shi et al., "Trajectory Unified Transformer for Pedestrian Trajectory Prediction", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Shi_Trajectory_Unified_Transformer_for_Pedestrian_Trajectory_Prediction_ICCV_2023_paper.pdf>paper</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minade">b-minADE</a></li>
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
</ul>
</details>

</ul><ul><a name=b-minfde></a>
<details close>
<summary><em><l style="font-size:20px"><strong>brier-minFDE (b-minFDE)</strong><small> [10]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Tang et al., "HPNet: Dynamic Trajectory Forecasting with Historical Prediction Attention", CVPR, 2024.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Tang_HPNet_Dynamic_Trajectory_Forecasting_with_Historical_Prediction_Attention_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2404.06351>arxiv</a> <a href=https://github.com/XiaolongTang23/HPNet>code</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minjointfde">minJointFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minjointade">minJointADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tang_HPNet_2024_CVPR,
    author = "Tang, Xiaolong and Kan, Meina and Shan, Shiguang and Ji, Zhilong and Bai, Jinfeng and Chen, Xilin",
    title = "HPNet: Dynamic Trajectory Forecasting with Historical Prediction Attention",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Lan et al., "SEPT: Towards Efficient Scene Representation Learning for Motion Prediction", ICLR, 2024.</em></strong> <a href=https://openreview.net/pdf?id=efeBC1sQj9>paper</a> <a href=https://arxiv.org/pdf/2309.15289>arxiv</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Lan_SEPT_2024_ICLR,
    author = "Lan, Zhiqian and Jiang, Yuxuan and Mu, Yao and Chen, Chen and Li, Shengbo Eben",
    title = "{SEPT}: Towards Efficient Scene Representation Learning for Motion Prediction",
    booktitle = "ICLR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wang et al., "Improving Autonomous Driving Safety with POP: A Framework for Accurate Partially Observed Trajectory Predictions", ICRA, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10610154>paper</a> <a href=https://arxiv.org/pdf/2309.15685>arxiv</a> <a href=https://github.com/chantsss/POP-CODE>code</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Wang_Improving_2024_ICRA,
    author = "Wang, Sheng and Chen, Yingbing and Cheng, Jie and Mei, Xiaodong and Xin, Ren and Song, Yongkang and Liu, Ming",
    booktitle = "ICRA",
    title = "Improving Autonomous Driving Safety with POP: A Framework for Accurate Partially Observed Trajectory Predictions",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhang et al., "SIMPL: A Simple and Efficient Multi-Agent Motion Prediction Baseline for Autonomous Driving", RAL, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10449378>paper</a> <a href=https://arxiv.org/pdf/2402.02519>arxiv</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfye">minFYE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Zhang_SIMPL_2024_RAL,
    author = "Zhang, Lu and Li, Peiliang and Liu, Sikang and Shen, Shaojie",
    journal = "RAL",
    title = "SIMPL: A Simple and Efficient Multi-Agent Motion Prediction Baseline for Autonomous Driving",
    year = "2024",
    volume = "9",
    number = "4",
    pages = "3767-3774"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhou et al., "Query-Centric Trajectory Prediction", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Zhou_Query-Centric_Trajectory_Prediction_CVPR_2023_paper.pdf>paper</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhou_2023_CVPR,
    author = "Zhou, Zikang and Wang, Jianping and Li, Yung-Hui and Huang, Yu-Kai",
    title = "Query-Centric Trajectory Prediction",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wang et al., "ProphNet: Efficient Agent-Centric Motion Forecasting With Anchor-Informed Proposals", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_ProphNet_Efficient_Agent-Centric_Motion_Forecasting_With_Anchor-Informed_Proposals_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.12071.pdf>arxiv</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2023_CVPR_1,
    author = "Wang, Xishun and Su, Tong and Da, Fang and Yang, Xiaodong",
    title = "ProphNet: Efficient Agent-Centric Motion Forecasting With Anchor-Informed Proposals",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Aydemir et al., "ADAPT: Efficient Multi-Agent Trajectory Prediction with Adaptation", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Aydemir_ADAPT_Efficient_Multi-Agent_Trajectory_Prediction_with_Adaptation_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2307.14187.pdf>arxiv</a> <a href=https://kuis-ai.github.io/adapt/>code</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Aydemir_2023_ICCV,
    author = "Aydemir, Gorkay and Akan, Adil Kaan and Guney, Fatma",
    title = "ADAPT: Efficient Multi-Agent Trajectory Prediction with Adaptation",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Cheng et al., "Forecast-MAE: Self-supervised Pre-training for Motion Forecasting with Masked Autoencoders", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Cheng_Forecast-MAE_Self-supervised_Pre-training_for_Motion_Forecasting_with_Masked_Autoencoders_ICCV_2023_paper.pdf>paper</a> <a href=https://github.com/jchengai/forecast-mae>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cheng_2023_ICCV,
    author = "Cheng, Jie and Mei, Xiaodong and Liu, Ming",
    title = "Forecast-MAE: Self-supervised Pre-training for Motion Forecasting with Masked Autoencoders",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Shi et al., "Trajectory Unified Transformer for Pedestrian Trajectory Prediction", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Shi_Trajectory_Unified_Transformer_for_Pedestrian_Trajectory_Prediction_ICCV_2023_paper.pdf>paper</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minade">b-minADE</a></li>
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
<summary><strong><em>Ye et al., "Bootstrap Motion Forecasting With Self-Consistent Constraints", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Ye_Bootstrap_Motion_Forecasting_With_Self-Consistent_Constraints_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.05859.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#map">mAP</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ye_2023_ICCV,
    author = "Ye, Maosheng and Xu, Jiamiao and Xu, Xunnong and Wang, Tengfei and Cao, Tongyi and Chen, Qifeng",
    title = "Bootstrap Motion Forecasting With Self-Consistent Constraints",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Cui et al., "GoRela: Go Relative for Viewpoint-Invariant Motion Forecasting", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10160984>paper</a> <a href=https://arxiv.org/pdf/2211.02545.pdf>arxiv</a> <a href=https://waabi.ai/research/go-relative-for-viewpoint-invariant-motion-forecasting>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#highwaysim">HighwaySim</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#cte">CTE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ate">ATE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cui_2023_ICRA,
    author = "Cui, Alexander and Casas, Sergio and Wong, Kelvin and Suo, Simon and Urtasun, Raquel",
    title = "GoRela: Go Relative for Viewpoint-Invariant Motion Forecasting",
    booktitle = "ICRA",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Gao et al., "Dynamic Scenario Representation Learning for Motion Forecasting With Heterogeneous Graph Convolutional Recurrent Networks", RAL, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10081482>paper</a> <a href=https://arxiv.org/pdf/2303.04364>arxiv</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Gao_Dynamic_2023_RAL,
    author = "Gao, Xing and Jia, Xiaogang and Li, Yikang and Xiong, Hongkai",
    journal = "RAL",
    title = "Dynamic Scenario Representation Learning for Motion Forecasting With Heterogeneous Graph Convolutional Recurrent Networks",
    year = "2023",
    volume = "8",
    number = "5",
    pages = "2946-2953"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wang et al., "GANet: Goal Area Network for Motion Forecasting", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10160468>paper</a> <a href=https://arxiv.org/pdf/2209.09723.pdf>arxiv</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2023_ICRA_1,
    author = "Wang, Mingkun and Zhu, Xinge and Yu, Changqian and Li, Wei and Ma, Yuexin and Jin, Ruochun and Ren, Xiaoguang and Ren, Dongchun and Wang, Mingxu and Yang, Wenjing",
    title = "GANet: Goal Area Network for Motion Forecasting",
    booktitle = "ICRA",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Fan et al., "Look Before You Drive: Boosting Trajectory Forecasting via Imagining Future", IROS, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10341509>paper</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@INPROCEEDINGS{Fan_2023_IROS,
    author = "Fan, Yixuan and Liu, Xin and Li, Yali and Wang, Shengjin",
    booktitle = "IROS",
    title = "Look Before You Drive: Boosting Trajectory Forecasting via Imagining Future",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Huang et al., "Multi-modal Motion Prediction with Transformer-based Neural Network for Autonomous Driving", ICRA, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/document/9812060>paper</a> <a href=https://arxiv.org/pdf/2109.06446.pdf>arxiv</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Huang_2022_ICRA,
    author = "Huang, Zhiyu and Mo, Xiaoyu and Lv, Chen",
    booktitle = "ICRA",
    title = "Multi-modal Motion Prediction with Transformer-based Neural Network for Autonomous Driving",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Strohbeck et al., "Deep Kernel Learning for Uncertainty Estimation in Multiple Trajectory Prediction Networks", IROS, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9982167>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Strohbeck_2022_IROS,
    author = "Strohbeck, Jan and Muller, Johannes and Herrmann, Martin and Buchholz, Michael",
    booktitle = "IROS",
    title = "Deep Kernel Learning for Uncertainty Estimation in Multiple Trajectory Prediction Networks",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhang et al., "Trajectory Prediction with Graph-based Dual-scale Context Fusion", IROS, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9981923>paper</a> <a href=https://arxiv.org/pdf/2111.01592.pdf>arxiv</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2022_IROS,
    author = "Zhang, Lu and Li, Peiliang and Chen, Jing and Shen, Shaojie",
    booktitle = "IROS",
    title = "Trajectory Prediction with Graph-based Dual-scale Context Fusion",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=bev_ap></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Bird's Eye View Average Precision (BEV AP)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Zhang et al., "STINet: Spatio-Temporal-Interactive Network for Pedestrian Detection and Trajectory Prediction", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_STINet_Spatio-Temporal-Interactive_Network_for_Pedestrian_Detection_and_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.04255.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#bev_ap">BEV AP</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#de">DE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2020_CVPR,
    author = "Zhang, Zhishuai and Gao, Jiyang and Mao, Junhua and Liu, Yukai and Anguelov, Dragomir and Li, Congcong",
    title = "{STINet}: Spatio-Temporal-Interactive Network for Pedestrian Detection and Trajectory Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=bnace></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Box Normalized Average Centroid Error (BNACE)</strong><small> [21]</small></l>
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

</ul><ul><a name=boxorfp></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Box Off-Road False Positive (BoxORFP)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Cui et al., "Ellipse Loss for Scene-Compliant Motion Prediction", ICRA, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9561536>paper</a> <a href=https://arxiv.org/pdf/2011.03139.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#boxorfp">BoxORFP</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ctrorfp">CtrORFP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cui_2021_ICRA,
    author = "Cui, Henggang and Shajari, Hoda and Yalamanchi, Sai and Djuric, Nemanja",
    booktitle = "ICRA",
    title = "Ellipse Loss for Scene-Compliant Motion Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=cd></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Chamfer Distance (CD)</strong><small> [20]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Weng et al., "Joint Metrics Matter: A Better Standard for Trajectory Forecasting", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Weng_Joint_Metrics_Matter_A_Better_Standard_for_Trajectory_Forecasting_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2305.06292.pdf>arxiv</a> <a href=https://github.com/ericaweng/joint-metrics-matter>code</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minjointfde">minJointFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minjointade">minJointADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#cd">CD</a></li>
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
<summary><strong><em>Cui et al., "LookOut: Diverse Multi-Future Prediction and Planning for Self-Driving", ICCV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Cui_LookOut_Diverse_Multi-Future_Prediction_and_Planning_for_Self-Driving_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2101.06547.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#cd">CD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#progress">Progress</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cui_2021_ICCV,
    author = "Cui, Alexander and Casas, Sergio and Sadat, Abbas and Liao, Renjie and Urtasun, Raquel",
    title = "{LookOut}: Diverse Multi-Future Prediction and Planning for Self-Driving",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=ce></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Cross Entropy (CE)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Rhinehart et al., "R2P2: A Reparameterized Pushforward Policy For Diverse, Precise Generative Path Forecasting", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Nicholas_Rhinehart_R2P2_A_ReparameteRized_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minmsd">minMSD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#meanmsd">meanMSD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ce">CE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rhinehart_2018_ECCV,
    author = "Rhinehart, Nicholas and Kitani, Kris M. and Vernaza, Paul",
    title = "{R2P2}: A Reparameterized Pushforward Policy For Diverse, Precise Generative Path Forecasting",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=cll></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Conditional Log-Likelihood (CLL)</strong><small> [21]</small></l>
</em></summary>
<ul>
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
</ul>
</details>

</ul><ul><a name=cmr></a>
<details close>
<summary><em><l style="font-size:20px"><strong>CMR</strong><small> [21]</small></l>
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

</ul><ul><a name=comfort></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Comfort</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Shridhar et al., "Beelines: Motion Prediction Metrics for Self-Driving Safety and Comfort", ICRA, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/document/9560950>paper</a> <a href=https://arxiv.org/pdf/2011.00393.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#l2">L2</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#comfort">Comfort</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#safety">Safety</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shridhar_2021_ICRA,
    author = "Shridhar, Skanda and Ma, Yuhang and Stentz, Tara and Shen, Zhengdi and Haynes, Galen Clark and Traft, Neil",
    booktitle = "ICRA",
    title = "Beelines: Motion Prediction Metrics for Self-Driving Safety and Comfort",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=cr></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Collision Rate (CR)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Mozaffari et al., "Multimodal Manoeuvre and Trajectory Prediction for Automated Driving on Highways Using Transformer Networks", RAL, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10207845>paper</a> <a href=https://arxiv.org/pdf/2303.16109>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#ind">inD</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#exid">exiD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#orr">ORR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#cr">CR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Mozaffari_Multimodal_2023_RAL,
    author = "Mozaffari, Sajjad and Sormoli, Mreza Alipour and Koufos, Konstantinos and Dianati, Mehrdad",
    journal = "RAL",
    title = "Multimodal Manoeuvre and Trajectory Prediction for Automated Driving on Highways Using Transformer Networks",
    year = "2023",
    volume = "8",
    number = "10",
    pages = "6123-6130"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=crm></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Collision Rate per Mill (CRM)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Zhou et al., "Dynamic Attention-Based CVAE-GAN for Pedestrian Trajectory Prediction", RAL, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9996571>paper</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#crm">CRM</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Zhou_Dynamic_2023_RAL,
    author = "Zhou, Zhou and Huang, Gang and Su, Zhaoxin and Li, Yongfu and Hua, Wei",
    journal = "RAL",
    title = "Dynamic Attention-Based CVAE-GAN for Pedestrian Trajectory Prediction",
    year = "2023",
    volume = "8",
    number = "2",
    pages = "704-711"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=cross-col></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Cross-Col</strong><small> [21]</small></l>
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

</ul><ul><a name=ct></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Completion Time (CT)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Fisac et al., "Probabilistically Safe Robot Planning with Confidence-based Human Predictions", RSS, 2018.</em></strong> <a href=http://www.roboticsproceedings.org/rss14/p69.pdf>paper</a> <a href=https://arxiv.org/pdf/1806.00109.pdf%3E>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ct">CT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Fisac_2018_RSS,
    author = "Fisac, Jaime F and Bajcsy, Andrea and Herbert, Sylvia L and Fridovich-Keil, David and Wang, Steven and Tomlin, Claire J and Dragan, Anca D",
    title = "Probabilistically Safe Robot Planning with Confidence-based Human Predictions",
    booktitle = "RSS",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=cte></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Cross Track Error (CTE)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Cui et al., "GoRela: Go Relative for Viewpoint-Invariant Motion Forecasting", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10160984>paper</a> <a href=https://arxiv.org/pdf/2211.02545.pdf>arxiv</a> <a href=https://waabi.ai/research/go-relative-for-viewpoint-invariant-motion-forecasting>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#highwaysim">HighwaySim</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#b-minfde">b-minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#cte">CTE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ate">ATE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cui_2023_ICRA,
    author = "Cui, Alexander and Casas, Sergio and Wong, Kelvin and Suo, Simon and Urtasun, Raquel",
    title = "GoRela: Go Relative for Viewpoint-Invariant Motion Forecasting",
    booktitle = "ICRA",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=ctrorfp></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Center Off-Road False Positive (CtrORFP)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Cui et al., "Ellipse Loss for Scene-Compliant Motion Prediction", ICRA, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9561536>paper</a> <a href=https://arxiv.org/pdf/2011.03139.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#boxorfp">BoxORFP</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ctrorfp">CtrORFP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cui_2021_ICRA,
    author = "Cui, Henggang and Shajari, Hoda and Yalamanchi, Sai and Djuric, Nemanja",
    booktitle = "ICRA",
    title = "Ellipse Loss for Scene-Compliant Motion Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=dac></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Drivable Area Compliance (DAC)</strong><small> [16]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Chen et al., "CRITERIA: a New Benchmarking Paradigm for Evaluating Trajectory Prediction Models for Autonomous Driving", ICRA, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10610911>paper</a> <a href=https://arxiv.org/pdf/2310.07794>arxiv</a> <a href=https://github.com/huawei-noah/SMARTS/tree/CRITERIA-latest/papers/CRITERIA>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#dac">DAC</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#dao">DAO</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#amv">AMV</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minasd">minASD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfsd">minFSD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rf">RF</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#att">ATT</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#aae">AAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Chen_CRITERIA_2024_ICRA,
    author = "Chen, Changhe and Pourkeshavarz, Mozhgan and Rasouli, Amir",
    booktitle = "ICRA",
    title = "CRITERIA: a New Benchmarking Paradigm for Evaluating Trajectory Prediction Models for Autonomous Driving",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Afshar et al., "PBP: Path-based Trajectory Prediction for Autonomous Driving", ICRA, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10610610>paper</a> <a href=https://arxiv.org/pdf/2309.03750>arxiv</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#orr">ORR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#dac">DAC</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#ld">LD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Afshar_PBP_2024_ICRA,
    author = "Afshar, Sepideh and Deo, Nachiket and Bhagat, Akshay and Chakraborty, Titas and Shao, Yunming and Buddharaju, Balarama Raju and Deshpande, Adwait and Motional, Henggang Cui",
    booktitle = "ICRA",
    title = "PBP: Path-based Trajectory Prediction for Autonomous Driving",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Girgis et al., "Latent Variable Sequential Set Transformers for Joint Multi-Agent Motion Prediction", ICLR, 2022.</em></strong> <a href=https://openreview.net/pdf?id=Dup_dDqkZC5>paper</a> <a href=https://arxiv.org/pdf/2104.00563.pdf>arxiv</a> <a href=https://fgolemo.github.io/autobots/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#trajnet++">Trajnet++</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#orr">ORR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#dac">DAC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Girgis_2022_ICLR,
    author = "Girgis, Roger and Golemo, Florian and Codevilla, Felipe and Weiss, Martin and D'Souza, Jim Aldon and Kahou, Samira Ebrahimi and Heide, Felix and Pal, Christopher",
    title = "Latent Variable Sequential Set Transformers for Joint Multi-Agent Motion Prediction",
    booktitle = "ICLR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Rella et al., "Decoder Fusion RNN: Context and Interaction Aware Decoders for Trajectory Prediction", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636577>paper</a> <a href=https://arxiv.org/pdf/2108.05814.pdf>arxiv</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#dac">DAC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rella_2021_IROS,
    author = "Rella, Edoardo Mello and Zaech, Jan-Nico and Liniger, Alexander and Van Gool, Luc",
    booktitle = "IROS",
    title = "Decoder {Fusion RNN}: Context and Interaction Aware Decoders for Trajectory Prediction",
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
<summary><strong><em>Strohbeck et al., "Multiple Trajectory Prediction with Deep Temporal and Spatial Convolutional Neural Networks", IROS, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9341327>paper</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#dac">DAC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Strohbeck_2020_IROS,
    author = "Strohbeck, J. and Belagiannis, V. and Müller, J. and Schreiber, M. and Herrmann, M. and Wolf, D. and Buchholz, M.",
    booktitle = "IROS",
    title = "Multiple Trajectory Prediction with Deep Temporal and Spatial Convolutional Neural Networks",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=dao></a>
<details close>
<summary><em><l style="font-size:20px"><strong>DAO</strong><small> [20]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Chen et al., "CRITERIA: a New Benchmarking Paradigm for Evaluating Trajectory Prediction Models for Autonomous Driving", ICRA, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10610911>paper</a> <a href=https://arxiv.org/pdf/2310.07794>arxiv</a> <a href=https://github.com/huawei-noah/SMARTS/tree/CRITERIA-latest/papers/CRITERIA>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#dac">DAC</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#dao">DAO</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#amv">AMV</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minasd">minASD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfsd">minFSD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rf">RF</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#att">ATT</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#aae">AAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Chen_CRITERIA_2024_ICRA,
    author = "Chen, Changhe and Pourkeshavarz, Mozhgan and Rasouli, Amir",
    booktitle = "ICRA",
    title = "CRITERIA: a New Benchmarking Paradigm for Evaluating Trajectory Prediction Models for Autonomous Driving",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Pourkeshavarz et al., "Learn TAROT with MENTOR: A Meta-Learned Self-Supervised Approach for Trajectory Prediction", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Pourkeshavarz_Learn_TAROT_with_MENTOR_A_Meta-Learned_Self-Supervised_Approach_for_Trajectory_ICCV_2023_paper.pdf>paper</a></summary>
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
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mr">MR</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#rf">RF</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#dao">DAO</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Pourkeshavarz_2023_ICCV,
    author = "Pourkeshavarz, Mozhgan and Chen, Changhe and Rasouli, Amir",
    title = "Learn TAROT with MENTOR: A Meta-Learned Self-Supervised Approach for Trajectory Prediction",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=de></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Displacement Error (DE)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Zhang et al., "STINet: Spatio-Temporal-Interactive Network for Pedestrian Detection and Trajectory Prediction", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_STINet_Spatio-Temporal-Interactive_Network_for_Pedestrian_Detection_and_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.04255.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#bev_ap">BEV AP</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#de">DE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2020_CVPR,
    author = "Zhang, Zhishuai and Gao, Jiyang and Mao, Junhua and Liu, Yukai and Anguelov, Dragomir and Li, Congcong",
    title = "{STINet}: Spatio-Temporal-Interactive Network for Pedestrian Detection and Trajectory Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=deltaesv></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Delta Empirical Sigma Value (DeltaESV)</strong><small> [21]</small></l>
</em></summary>
<ul>
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
</ul>
</details>

</ul><ul><a name=dtg></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Distance to Goal (DtG)</strong><small> [21]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Lee et al., "Predicting Wide Receiver Trajectories In American Football", WACV, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7477732>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#osu">OSU</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#kld">KLD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#mhd">MHD</a></li>
<li><a href="../../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#dtg">DtG</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lee_2016_WACV,
    author = "Lee, N. and Kitani, K. M.",
    booktitle = "WACV",
    title = "Predicting Wide Receiver Trajectories In {A}merican Football",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul>