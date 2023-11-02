<a name=top></a>
<a name=top></a>
---
<a href=../../../README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../datasets/datasets.md#top><l style="font-size:30px">Datasets</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Metrics</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
[Home](../../metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Video](../../video/video_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Action](../../action/action_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Trajectory](../../trajectory/trajectory_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Motion&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Other](../../other/other_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[Home](../motion_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Alphabetical&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Ranking](../motion_ranking/motion_ranking_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[A-D](motion_a-d_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[E-I](motion_e-i_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;J-Z&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
<h2>J-Z <small>[rank]</small></h2> 
<ul><a name=kde></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Keypoint Displacement Error (KDE)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Salzmann et al., "Motron: Multimodal Probabilistic Human Motion Forecasting", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Salzmann_Motron_Multimodal_Probabilistic_Human_Motion_Forecasting_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.04132.pdf>arxiv</a> <a href=https://github.com/TUM-AAS/motron-cvpr22>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#kde">KDE</a></li>
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
</ul>
</details>

</ul><ul><a name=kl></a>
<details close>
<summary><em><l style="font-size:20px"><strong>KL</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Aliakbarian et al., "A Stochastic Conditioning Scheme for Diverse Human Motion Prediction", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Aliakbarian_A_Stochastic_Conditioning_Scheme_for_Diverse_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://github.com/mix-and-match/mix-and-match-tutorial>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#kld">KLD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#si">SI</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#kl">KL</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#s-mse">S-MSE</a></li>
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
</ul>
</details>

</ul><ul><a name=kld></a>
<details close>
<summary><em><l style="font-size:20px"><strong>KullbackLeibler Divergence (KLD)</strong><small> [12]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Aliakbarian et al., "Contextually Plausible and Diverse 3D Human Motion Prediction", ICCV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Aliakbarian_Contextually_Plausible_and_Diverse_3D_Human_Motion_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.08521.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#kld">KLD</a></li>
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
<summary><strong><em>Aliakbarian et al., "A Stochastic Conditioning Scheme for Diverse Human Motion Prediction", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Aliakbarian_A_Stochastic_Conditioning_Scheme_for_Diverse_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://github.com/mix-and-match/mix-and-match-tutorial>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#kld">KLD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#si">SI</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#kl">KL</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#s-mse">S-MSE</a></li>
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
</ul>
</details>

</ul><ul><a name=l2></a>
<details close>
<summary><em><l style="font-size:20px"><strong>L2</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Lei et al., "An Intention Prediction Based Shared Control System for Point-to-point Navigation of a Robotic Wheelchair", RAL, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9817650>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#l2">L2</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Lei_2022_RAL,
    author = "Lei, Zhen and Tan, Bang Yi and Garg, Neha P and Li, Lei and Sidarta, Ananda and Ang, Wei Tech",
    journal = "RAL",
    title = "An Intention Prediction Based Shared Control System for Point-to-point Navigation of a Robotic Wheelchair",
    volume = "7",
    number = "4",
    pages = "8893--8900",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=lo></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Limb Orientation (LO)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Joo et al., "Towards Social Artificial Intelligence: Nonverbal Social Signal Prediction In A Triadic Interaction", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Joo_Towards_Social_Artificial_Intelligence_Nonverbal_Social_Signal_Prediction_in_a_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.04158.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#lo">LO</a></li>
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
</ul>
</details>

</ul><ul><a name=mae></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Absolute Error (MAE)</strong><small> [6]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Ma et al., "Progressively Generating Better Initial Guesses Towards Next Stages for High-Quality Human Motion Prediction", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Ma_Progressively_Generating_Better_Initial_Guesses_Towards_Next_Stages_for_High-Quality_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.16051.pdf>arxiv</a> <a href=https://github.com/705062791/PGBIG>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
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
<summary><strong><em>Zhong et al., "Spatio-Temporal Gating-Adjacency GCN for Human Motion Prediction", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Zhong_Spatio-Temporal_Gating-Adjacency_GCN_for_Human_Motion_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.01474.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
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
<summary><strong><em>Li et al., "Skeleton-Parted Graph Scattering Networks for 3D Human Motion Prediction", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136660018.pdf>paper</a> <a href=https://arxiv.org/pdf/2208.00368.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/SPGSN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
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
<summary><strong><em>Sun et al., "Overlooked Poses Actually Make Sense: Distilling Privileged Knowledge for Human Motion Prediction", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136650668.pdf>paper</a> <a href=https://arxiv.org/pdf/2208.01302.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
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
<summary><strong><em>Wang et al., "Prediction of Whole-Body Velocity and Direction From Local Leg Joint Movements in Insect Walking via LSTM Neural Networks", RAL, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9832735>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#r2">R2</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Wang_2022_RAL,
    author = "Wang, Yuchen and Hayashibe, Mitsuhiro and Owaki, Dai",
    journal = "RAL",
    title = "Prediction of Whole-Body Velocity and Direction From Local Leg Joint Movements in Insect Walking via {LSTM} Neural Networks",
    volume = "7",
    number = "4",
    pages = "9389--9396",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Li et al., "RAIN: Reinforced Hybrid Attention Inference Network for Motion Forecasting", ICCV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Li_RAIN_Reinforced_Hybrid_Attention_Inference_Network_for_Motion_Forecasting_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2108.01316.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
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
<summary><strong><em>Sofianos et al., "Space-Time-Separable Graph Convolutional Network for Pose Forecasting", ICCV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Sofianos_Space-Time-Separable_Graph_Convolutional_Network_for_Pose_Forecasting_ICCV_2021_paper.pdf>paper</a> <a href=https://github.com/FraLuca/STSGCN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
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
<summary><strong><em>Li et al., "Directed Acyclic Graph Neural Network for Human Motion Prediction", ICRA, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9561540>paper</a> <a href=https://github.com/Qinli-zz/DA-GNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
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
<summary><strong><em>Zhang et al., "Non-local Graph Convolutional Network for Joint Activity Recognition and Motion Prediction", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636107>paper</a> <a href=https://arxiv.org/pdf/2108.01518.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
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
<summary><strong><em>Chao et al., "Adversarial Refinement Network for Human Motion Prediction", ACCV, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content/ACCV2020/papers/Chao_Adversarial_Refinement_Network_for_Human_Motion_Prediction_ACCV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2011.11221.pdf>arxiv</a> <a href=https://github.com/Xianjin111/ARNet-for-human-motion-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
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
</ul>
</details>

</ul><ul><a name=mane></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean angular error (MAnE)</strong><small> [2]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Walters et al., "EVReflex: Dense Time-to-Impact Prediction for Event-based Obstacle Avoidance", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636327>paper</a> <a href=https://arxiv.org/pdf/2109.00405.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Walters_2021_IROS,
    author = "Walters, Celyn and Hadfield, Simon",
    booktitle = "IROS",
    title = "{EVReflex}: Dense Time-to-Impact Prediction for Event-based Obstacle Avoidance",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Corona et al., "Context-Aware Human Motion Prediction", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Corona_Context-Aware_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.03419.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wbhm">WBHM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
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
<details close>
<summary><strong><em>Cui et al., "Learning Dynamic Relationships for 3D Human Motion Prediction", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Cui_Learning_Dynamic_Relationships_for_3D_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://github.com/cuiqiongjie/LDRGCN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
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
<summary><strong><em>Li et al., "Dynamic Multiscale Graph Neural Networks for 3D Skeleton Based Human Motion Prediction", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Dynamic_Multiscale_Graph_Neural_Networks_for_3D_Skeleton_Based_Human_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.08802.pdf>arxiv</a> <a href=https://github.com/limaosen0/DMGNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
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
<summary><strong><em>Cai et al., "Learning Progressive Joint Propagation for Human Motion Prediction", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520222.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
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
<summary><strong><em>Mao et al., "History Repeats Itself: Human Motion Prediction via Motion Attention", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590460.pdf>paper</a> <a href=https://arxiv.org/pdf/2007.11755.pdf>arxiv</a> <a href=https://github.com/wei-mao-2019/HisRepItself>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
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
<summary><strong><em>Piergiovanni et al., "Adversarial Generative Grammars for Human Activity Prediction", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470494.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.04888.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
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
<summary><strong><em>Gopalakrishnan et al., "A Neural Temporal Model For Human Motion Prediction", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Gopalakrishnan_A_Neural_Temporal_Model_for_Human_Motion_Prediction_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1809.03036.pdf>arxiv</a> <a href=https://github.com/cr7anand/neural_temporal_models>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#npss">NPSS</a></li>
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
<summary><strong><em>Hernandez et al., "Human Motion Prediction Via Spatio-Temporal Inpainting", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Hernandez_Human_Motion_Prediction_via_Spatio-Temporal_Inpainting_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.05478.pdf>arxiv</a> <a href=https://github.com/magnux/MotionGAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#human">Human</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pskl">PSKL</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#psent">PSEnt</a></li>
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
<summary><strong><em>Mao et al., "Learning Trajectory Dependencies For Human Motion Prediction", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Mao_Learning_Trajectory_Dependencies_for_Human_Motion_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.05436.pdf>arxiv</a> <a href=https://github.com/wei-mao-2019/LearnTrajDep>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
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
<summary><strong><em>Wang et al., "Imitation Learning For Human Pose Prediction", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Imitation_Learning_for_Human_Pose_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1909.03449.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
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
<summary><strong><em>Gui et al., "Few-Shot Human Motion Prediction Via Meta-Learning", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Liangyan_Gui_Few-Shot_Human_Motion_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
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
<summary><strong><em>Gui et al., "Adversarial Geometry-Aware Human Motion Prediction", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Liangyan_Gui_Adversarial_Geometry-Aware_Human_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#human">Human</a></li>
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
<summary><strong><em>Gui et al., "Teaching Robots To Predict Human Motion", IROS, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8594452>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
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
<summary><strong><em>Martinez et al., "On Human Motion Prediction Using Recurrent Neural Networks", CVPR, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Martinez_On_Human_Motion_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.02445.pdf>arxiv</a> <a href=https://github.com/una-dinosauria/human-motion-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
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
<summary><strong><em>Jain et al., "Structural-RNN: Deep Learning On Spatio-Temporal Graphs", CVPR, 2016.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.05298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
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
<summary><strong><em>Fragkiadaki et al., "Recurrent Network Models For Human Dynamics", ICCV, 2015.</em></strong> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Fragkiadaki_Recurrent_Network_Models_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1508.00271.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#accuracy">Accuracy</a></li>
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
</ul>
</details>

</ul><ul><a name=mape></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Absolute Percentage Error (MAPE)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Peng et al., "Trajectory-Aware Body Interaction Transformer for Multi-Person Pose Forecasting", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Peng_Trajectory-Aware_Body_Interaction_Transformer_for_Multi-Person_Pose_Forecasting_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.05095.pdf>arxiv</a> <a href=https://github.com/xiaogangpeng/TBIFormer>code</a></summary>
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
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mape">MAPE</a></li>
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
</ul>
</details>

</ul><ul><a name=minade></a>
<details close>
<summary><em><l style="font-size:20px"><strong>minADE</strong><small> [12]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Ahn et al., "Can We Use Diffusion Probabilistic Models for 3D Motion Prediction?", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10160722>paper</a> <a href=https://arxiv.org/pdf/2302.14503.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#sde">sDE</a></li>
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
<summary><strong><em>Xu et al., "Diverse Human Motion Prediction Guided by Multi-level Spatial-Temporal Anchors", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820244.pdf>paper</a> <a href=https://github.com/Sirui-Xu/STARS>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#minade">minADE</a></li>
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
</ul>
</details>

</ul><ul><a name=minfde></a>
<details close>
<summary><em><l style="font-size:20px"><strong>minFDE</strong><small> [12]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Ahn et al., "Can We Use Diffusion Probabilistic Models for 3D Motion Prediction?", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10160722>paper</a> <a href=https://arxiv.org/pdf/2302.14503.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#sde">sDE</a></li>
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
<summary><strong><em>Xu et al., "Diverse Human Motion Prediction Guided by Multi-level Spatial-Temporal Anchors", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820244.pdf>paper</a> <a href=https://github.com/Sirui-Xu/STARS>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#minade">minADE</a></li>
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
</ul>
</details>

</ul><ul><a name=mje></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Joint Error (MJE)</strong><small> [4]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Maeda et al., "MotionAug: Augmentation With Physical Correction for Human Motion Prediction", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Maeda_MotionAug_Augmentation_With_Physical_Correction_for_Human_Motion_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.09116.pdf>arxiv</a> <a href=https://github.com/meaten/MotionAug>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#hdm05">HDM05</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Maeda_2022_CVPR,
    author = "Maeda, Takahiro and Ukita, Norimichi",
    title = "{MotionAug}: Augmentation With Physical Correction for Human Motion Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Park et al., "HMPO: Human Motion Prediction in Occluded Environments for Safe Motion Planning", RSS, 2020.</em></strong> <a href=http://www.roboticsproceedings.org/rss16/p051.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.00424.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wnp">WnP</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#utka">UTKA</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#occlusion_mocap">Occlusion MoCap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
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
<details close>
<summary><strong><em>Callens et al., "A Framework for Recognition and Prediction of Human Motions in Human-Robot Collaboration Using Probabilistic Motion Models", RAL, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9130153>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Callens_2020_RAL,
    author = "Callens, T. and van der Have, T. and Rossom, S. V. and Schutter, J. De and Aertbeliën, E.",
    journal = "RAL",
    title = "A Framework for Recognition and Prediction of Human Motions in Human-Robot Collaboration Using Probabilistic Motion Models",
    year = "2020",
    volume = "5",
    number = "4",
    pages = "5151-5158"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Joo et al., "Towards Social Artificial Intelligence: Nonverbal Social Signal Prediction In A Triadic Interaction", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Joo_Towards_Social_Artificial_Intelligence_Nonverbal_Social_Signal_Prediction_in_a_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.04158.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#lo">LO</a></li>
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
<summary><strong><em>Liu et al., "Towards Natural And Accurate Future Motion Prediction Of Humans And Animals", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Liu_Towards_Natural_and_Accurate_Future_Motion_Prediction_of_Humans_and_CVPR_2019_paper.pdf>paper</a> <a href=https://github.com/BII-wushuang/Lie-Group-Motion-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mouse_fish">Mouse Fish</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#run_time">Run Time</a></li>
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
<summary><strong><em>Yuan et al., "Ego-Pose Estimation And Forecasting As Real-Time Pd Control", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Yuan_Ego-Pose_Estimation_and_Forecasting_As_Real-Time_PD_Control_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.03173.pdf>arxiv</a> <a href=https://github.com/Khrylx/EgoPose>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egopose">EgoPose</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
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
<details close>
<summary><strong><em>Talignani et al., "Prediction Of Human Arm Target For Robot Reaching Movements", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8968559>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Talignani_2019_IROS,
    author = "Talignani Landi, Chiara and Cheng, Yujiao and Ferraguti, Federica and Bonfe, Marcello and Secchi, Cristian and Tomizuka, Masayoshi",
    booktitle = "IROS",
    title = "Prediction Of Human Arm Target For Robot Reaching Movements",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Chiu et al., "Action-Agnostic Human Pose Forecasting", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8658717>paper</a> <a href=https://arxiv.org/pdf/1810.09676.pdf>arxiv</a> <a href=https://github.com/eddyhkchiu/pose_forecast_wacv/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
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
<summary><strong><em>Wu et al., "Futurepose - Mixed Reality Martial Arts Training Using Real-Time 3D Human Pose Forecasting With A RGB Camera", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8658594>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#run_time">Run Time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wu_2019_WACV,
    author = "Wu, E. and Koike, H.",
    booktitle = "WACV",
    title = "Futurepose - Mixed Reality Martial Arts Training Using Real-Time 3D Human Pose Forecasting With A {RGB} Camera",
    year = "2019"
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
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#ca">CA</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sbuki">SBUKI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
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
<summary><strong><em>Bütepage et al., "Anticipating Many Futures: Online Human Motion Prediction And Generation For Human-Robot Interaction", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8460651>paper</a> <a href=https://arxiv.org/pdf/1702.08212.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Butepage_2018_ICRA,
    author = "Bütepage, J. and Kjellström, H. and Kragic, D.",
    booktitle = "ICRA",
    title = "Anticipating Many Futures: Online Human Motion Prediction And Generation For Human-Robot Interaction",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Butepage et al., "Deep Representation Learning For Human Motion Prediction And Classification", CVPR, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Butepage_Deep_Representation_Learning_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1702.07486.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
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
<summary><strong><em>Walker et al., "The Pose Knows: Video Forecasting By Generating Pose Futures", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Walker_The_Pose_Knows_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.00053.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
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
<summary><strong><em>Cao et al., "Forecasting Human Pose And Motion With Multibody Dynamic Model", WACV, 2015.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/7045887>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cao_2015_WACV,
    author = "Cao, S. and Nevatia, R.",
    booktitle = "WACV",
    title = "Forecasting Human Pose And Motion With Multibody Dynamic Model",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=mmade></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Multi-Modal ADE (MMADE)</strong><small> [8]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Barquero et al., "BeLFusion: Latent Diffusion for Behavior-Driven Human Motion Prediction", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Barquero_BeLFusion_Latent_Diffusion_for_Behavior-Driven_Human_Motion_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2211.14304.pdf>arxiv</a> <a href=https://barquerogerman.github.io/BeLFusion/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmade">MMADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmfde">MMFDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fid">FID</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#cmd">CMD</a></li>
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
<summary><strong><em>Chen et al., "HumanMAC: Masked Motion Completion for Human Motion Prediction", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_HumanMAC_Masked_Motion_Completion_for_Human_Motion_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2302.03665.pdf>arxiv</a> <a href=https://lhchen.top/Human-MAC/>code</a></summary>
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
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmade">MMADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmfde">MMFDE</a></li>
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
<summary><strong><em>Nikdel et al., "DMMGAN: Diverse Multi Motion Prediction of 3D Human Joints using Attention-Based Generative Adversarial Network", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10160401>paper</a> <a href=https://arxiv.org/pdf/2209.09124.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmade">MMADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmfde">MMFDE</a></li>
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
<summary><strong><em>Saadatnejad et al., "A generic diffusion-based approach for 3D human pose prediction in the wild", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10160399>paper</a> <a href=https://arxiv.org/pdf/2210.05669.pdf>arxiv</a></summary>
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
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmade">MMADE</a></li>
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
<summary><strong><em>Zhang et al., "We Are More Than Our Joints: Predicting How 3D Bodies Move", CVPR, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_We_Are_More_Than_Our_Joints_Predicting_How_3D_Bodies_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2012.00619.pdf>arxiv</a> <a href=https://yz-cnsdqz.github.io/MOJO/MOJO.html>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmade">MMADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmfde">MMFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2021_CVPR,
    author = "Zhang, Yan and Black, Michael J. and Tang, Siyu",
    title = "We Are More Than Our Joints: Predicting How {3D} Bodies Move",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Yuan et al., "DLow: Diversifying Latent Flows for Diverse Human Motion Prediction", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123540324.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.08386.pdf>arxiv</a> <a href=https://github.com/Khrylx/DLow>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmade">MMADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmfde">MMFDE</a></li>
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
</ul>
</details>

</ul><ul><a name=mmfde></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Multi-Modal FDE (MMFDE)</strong><small> [9]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Barquero et al., "BeLFusion: Latent Diffusion for Behavior-Driven Human Motion Prediction", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Barquero_BeLFusion_Latent_Diffusion_for_Behavior-Driven_Human_Motion_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2211.14304.pdf>arxiv</a> <a href=https://barquerogerman.github.io/BeLFusion/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmade">MMADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmfde">MMFDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fid">FID</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#cmd">CMD</a></li>
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
<summary><strong><em>Chen et al., "HumanMAC: Masked Motion Completion for Human Motion Prediction", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_HumanMAC_Masked_Motion_Completion_for_Human_Motion_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2302.03665.pdf>arxiv</a> <a href=https://lhchen.top/Human-MAC/>code</a></summary>
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
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmade">MMADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmfde">MMFDE</a></li>
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
<summary><strong><em>Nikdel et al., "DMMGAN: Diverse Multi Motion Prediction of 3D Human Joints using Attention-Based Generative Adversarial Network", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10160401>paper</a> <a href=https://arxiv.org/pdf/2209.09124.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmade">MMADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmfde">MMFDE</a></li>
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
<summary><strong><em>Zhang et al., "We Are More Than Our Joints: Predicting How 3D Bodies Move", CVPR, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_We_Are_More_Than_Our_Joints_Predicting_How_3D_Bodies_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2012.00619.pdf>arxiv</a> <a href=https://yz-cnsdqz.github.io/MOJO/MOJO.html>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmade">MMADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmfde">MMFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2021_CVPR,
    author = "Zhang, Yan and Black, Michael J. and Tang, Siyu",
    title = "We Are More Than Our Joints: Predicting How {3D} Bodies Move",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Yuan et al., "DLow: Diversifying Latent Flows for Diverse Human Motion Prediction", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123540324.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.08386.pdf>arxiv</a> <a href=https://github.com/Khrylx/DLow>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmade">MMADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mmfde">MMFDE</a></li>
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
</ul>
</details>

</ul><ul><a name=mpble></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Per-Bone Length Error (MPBLE)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Cui et al., "Test-time Personalizable Forecasting of 3D Human Poses", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Cui_Test-time_Personalizable_Forecasting_of_3D_Human_Poses_ICCV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#grab">GRAB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpble">MPBLE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#p-mpjpe">P-MPJPE</a></li>
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
</ul>
</details>

</ul><ul><a name=mpjpe></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Per Joint Prediction Error (MPJPE)</strong><small> [1]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Gao et al., "Decompose More and Aggregate Better: Two Closer Looks at Frequency Representation Learning for Human Motion Prediction", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Gao_Decompose_More_and_Aggregate_Better_Two_Closer_Looks_at_Frequency_CVPR_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
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
<summary><strong><em>Peng et al., "Trajectory-Aware Body Interaction Transformer for Multi-Person Pose Forecasting", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Peng_Trajectory-Aware_Body_Interaction_Transformer_for_Multi-Person_Pose_Forecasting_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.05095.pdf>arxiv</a> <a href=https://github.com/xiaogangpeng/TBIFormer>code</a></summary>
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
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mape">MAPE</a></li>
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
<summary><strong><em>Sun et al., "DeFeeNet: Consecutive 3D Human Motion Prediction With Deviation Feedback", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Sun_DeFeeNet_Consecutive_3D_Human_Motion_Prediction_With_Deviation_Feedback_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2304.04496.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#babel">BABEL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
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
<summary><strong><em>Xu et al., "Uncovering the Missing Pattern: Unified Framework Towards Trajectory Imputation and Prediction", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Xu_EqMotion_Equivariant_Multi-Agent_Motion_Prediction_With_Invariant_Interaction_Reasoning_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.10876.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/EqMotion>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
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
<summary><strong><em>Choudhury et al., "TEMPO: Efficient Multi-View Pose Estimation, Tracking, and Forecasting", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Choudhury_TEMPO_Efficient_Multi-View_Pose_Estimation_Tracking_and_Forecasting_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2309.07910.pdf>arxiv</a> <a href=https://rccchoudhury.github.io/tempo2023/>code</a></summary>
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
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pcp3d">PCP3D</a></li>
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
<summary><strong><em>Cui et al., "Test-time Personalizable Forecasting of 3D Human Poses", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Cui_Test-time_Personalizable_Forecasting_of_3D_Human_Poses_ICCV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#grab">GRAB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpble">MPBLE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#p-mpjpe">P-MPJPE</a></li>
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
<summary><strong><em>Tanke et al., "Social Diffusion: Long-term Multiple Human Motion Anticipation", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Tanke_Social_Diffusion_Long-term_Multiple_Human_Motion_Anticipation_ICCV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mupots-3d">MuPoTS-3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
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
<summary><strong><em>Xing et al., "HDG-ODE: A Hierarchical Continuous-Time Model for Human Pose Forecasting", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Xing_HDG-ODE_A_Hierarchical_Continuous-Time_Model_for_Human_Pose_Forecasting_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.05859.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mupots-3d">MuPoTS-3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
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
<summary><strong><em>Xu et al., "Joint-Relation Transformer for Multi-Person Motion Prediction", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Xu_Joint-Relation_Transformer_for_Multi-Person_Motion_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.04808.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/JRTransformer>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mupots-3d">MuPoTS-3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#vim">VIM</a></li>
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
<summary><strong><em>Xu et al., "Auxiliary Tasks Benefit 3D Skeleton-based Human Motion Prediction", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Xu_Auxiliary_Tasks_Benefit_3D_Skeleton-based_Human_Motion_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.08942.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/AuxFormer>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
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
<summary><strong><em>Guo et al., "Back to MLP: A Simple Baseline for Human Motion Prediction", WACV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/WACV2023/papers/Guo_Back_to_MLP_A_Simple_Baseline_for_Human_Motion_Prediction_WACV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.01567.pdf>arxiv</a> <a href=https://github.com/dulucas/siMLPe>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
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
<summary><strong><em>Guo et al., "Multi-Person Extreme Motion Prediction", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_Multi-Person_Extreme_Motion_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2105.08825.pdf>arxiv</a> <a href=https://github.com/GUO-W/MultiMotion>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#expi">ExPI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ame">AME</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Guo_2022_CVPR_2,
    author = "Guo, Wen and Bie, Xiaoyu and Alameda-Pineda, Xavier and Moreno-Noguer, Francesc",
    title = "Multi-Person Extreme Motion Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Diller et al., "Forecasting Characteristic 3D Poses of Human Actions", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Diller_Forecasting_Characteristic_3D_Poses_of_Human_Actions_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2011.15079.pdf>arxiv</a> <a href=https://github.com/chrdiller/characteristic3dposes>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#grab">GRAB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#is">IS</a></li>
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
<summary><strong><em>Ma et al., "Progressively Generating Better Initial Guesses Towards Next Stages for High-Quality Human Motion Prediction", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Ma_Progressively_Generating_Better_Initial_Guesses_Towards_Next_Stages_for_High-Quality_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.16051.pdf>arxiv</a> <a href=https://github.com/705062791/PGBIG>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
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
<summary><strong><em>Zhong et al., "Spatio-Temporal Gating-Adjacency GCN for Human Motion Prediction", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Zhong_Spatio-Temporal_Gating-Adjacency_GCN_for_Human_Motion_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.01474.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
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
<summary><strong><em>Li et al., "Skeleton-Parted Graph Scattering Networks for 3D Human Motion Prediction", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136660018.pdf>paper</a> <a href=https://arxiv.org/pdf/2208.00368.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/SPGSN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
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
<summary><strong><em>Sampieri et al., "Pose Forecasting in Industrial Human-Robot Collaboration", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136980051.pdf>paper</a> <a href=https://arxiv.org/pdf/2208.07308.pdf>arxiv</a> <a href=https://github.com/federicocunico/human-robot-collaboration>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#chico">CHICO</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
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
<summary><strong><em>Sun et al., "Overlooked Poses Actually Make Sense: Distilling Privileged Knowledge for Human Motion Prediction", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136650668.pdf>paper</a> <a href=https://arxiv.org/pdf/2208.01302.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
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
<summary><strong><em>Zheng et al., "GIMO: Gaze-Informed Human Motion Prediction in Context", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136730675.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.09443.pdf>arxiv</a> <a href=https://github.com/y-zheng18/GIMO>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#gimo">GIMO</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2022_ECCV_2,
    author = "Zheng, Yang and Yang, Yanchao and Mo, Kaichun and Li, Jiaman and Yu, Tao and Liu, Yebin and Liu, Karen and Guibas, Leonidas J.",
    title = "{GIMO}: Gaze-Informed Human Motion Prediction in Context",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Mao et al., "Contact-aware Human Motion Forecasting", NeurIPS, 2022.</em></strong> <a href=https://openreview.net/pdf?id=LIKlL1Br9AT>paper</a> <a href=https://arxiv.org/pdf/2210.03954.pdf>arxiv</a> <a href=https://github.com/wei-mao-2019/ContAwareMotionPred>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#gta-im">GTA-IM</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#prox">PROX</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mao_2022_NeurIPS,
    author = "Mao, Wei and miaomiao Liu and Hartley, Richard and Salzmann, Mathieu",
    title = "Contact-aware Human Motion Forecasting",
    booktitle = "NeurIPS",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Sun et al., "Action-guided 3D Human Motion Prediction", NeurIPS, 2021.</em></strong> <a href=https://papers.nips.cc/paper/2021/file/fd9dd764a6f1d73f4340d570804eacc4-Paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
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
<summary><strong><em>Wang et al., "Multi-Person 3D Motion Prediction with Multi-Range Transformers", NeurIPS, 2021.</em></strong> <a href=https://papers.nips.cc/paper/2021/file/2fd5d41ec6cfab47e32164d5624269b1-Paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2111.12073.pdf>arxiv</a> <a href=https://github.com/jiashunwang/MRT>code</a></summary>
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
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
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
<summary><strong><em>Cui et al., "Towards Accurate 3D Human Motion Prediction From Incomplete Observations", CVPR, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Cui_Towards_Accurate_3D_Human_Motion_Prediction_From_Incomplete_Observations_CVPR_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
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
<summary><strong><em>Dang et al., "MSR-GCN: Multi-Scale Residual Graph Convolution Networks for Human Motion Prediction", ICCV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Dang_MSR-GCN_Multi-Scale_Residual_Graph_Convolution_Networks_for_Human_Motion_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://github.com/Droliven/MSRGCN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
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
<summary><strong><em>Liu et al., "Motion Prediction Using Trajectory Cues", ICCV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Liu_Motion_Prediction_Using_Trajectory_Cues_ICCV_2021_paper.pdf>paper</a> <a href=https://github.com/Pose-Group/MPT>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mouse_fish">Mouse Fish</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
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
<summary><strong><em>Sofianos et al., "Space-Time-Separable Graph Convolutional Network for Pose Forecasting", ICCV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Sofianos_Space-Time-Separable_Graph_Convolutional_Network_for_Pose_Forecasting_ICCV_2021_paper.pdf>paper</a> <a href=https://github.com/FraLuca/STSGCN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
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
<summary><strong><em>Xu et al., "Probabilistic Human Motion Prediction via A Bayesian Neural Network", ICRA, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9561665>paper</a> <a href=https://arxiv.org/pdf/2107.06564.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
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
<summary><strong><em>Cui et al., "Learning Dynamic Relationships for 3D Human Motion Prediction", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Cui_Learning_Dynamic_Relationships_for_3D_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://github.com/cuiqiongjie/LDRGCN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
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
<summary><strong><em>Cai et al., "Learning Progressive Joint Propagation for Human Motion Prediction", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520222.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
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
<summary><strong><em>Cao et al., "Long-term Human Motion Prediction with Scene Context", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460375.pdf>paper</a> <a href=https://arxiv.org/pdf/2007.03672.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#prox">PROX</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#gta-im">GTA-IM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cao_2020_ECCV,
    author = "Cao, Zhe and Gao, Hang and Mangalam, Karttikeya and Cai, Qi-Zhi and Vo, Minh and Malik, Jitendra",
    title = "Long-term Human Motion Prediction with Scene Context",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Mao et al., "History Repeats Itself: Human Motion Prediction via Motion Attention", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590460.pdf>paper</a> <a href=https://arxiv.org/pdf/2007.11755.pdf>arxiv</a> <a href=https://github.com/wei-mao-2019/HisRepItself>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
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
<summary><strong><em>Lebailly et al., "Motion Prediction Using Temporal Inception Module", ACCV, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content/ACCV2020/papers/Lebailly_Motion_Prediction_Using_Temporal_Inception_Module_ACCV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2010.03006.pdf>arxiv</a> <a href=https://github.com/tileb1/motion-prediction-tim>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
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
<summary><strong><em>Mao et al., "Learning Trajectory Dependencies For Human Motion Prediction", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Mao_Learning_Trajectory_Dependencies_for_Human_Motion_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.05436.pdf>arxiv</a> <a href=https://github.com/wei-mao-2019/LearnTrajDep>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
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
<summary><strong><em>Zhang et al., "Predicting 3D Human Dynamics From Video", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Predicting_3D_Human_Dynamics_From_Video_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.04781.pdf>arxiv</a> <a href=https://github.com/jasonyzhang/phd>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#instavariety">InstaVariety</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#re">RE</a></li>
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
<summary><strong><em>Du et al., "Bio-LSTM: A Biomechanically Inspired Recurrent Neural Network for 3-D Pedestrian Pose and Gait Prediction", RAL, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8626436>paper</a> <a href=https://arxiv.org/pdf/1809.03705.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pedx">PedX</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Du_2019_RAL,
    author = "Du, X. and Vasudevan, R. and Johnson-Roberson, M.",
    journal = "RAL",
    title = "{Bio-LSTM}: A Biomechanically Inspired Recurrent Neural Network for 3-D Pedestrian Pose and Gait Prediction",
    year = "2019",
    volume = "4",
    number = "2",
    pages = "1501-1508"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=mse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Square Error (MSE)</strong><small> [9]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Mao et al., "Masked Motion Predictors are Strong 3D Action Representation Learners", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Mao_Masked_Motion_Predictors_are_Strong_3D_Action_Representation_Learners_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.07092.pdf>arxiv</a> <a href=https://github.com/maoyunyao/MAMP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pku-mmd">PKU-MMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Ahn et al., "Can We Use Diffusion Probabilistic Models for 3D Motion Prediction?", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10160722>paper</a> <a href=https://arxiv.org/pdf/2302.14503.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#sde">sDE</a></li>
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
<summary><strong><em>Mascaro et al., "Robust Human Motion Forecasting using Transformer-based Model", IROS, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9981877>paper</a> <a href=https://arxiv.org/pdf/2302.08274.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Yasar et al., "A Scalable Approach to Predict Multi-Agent Motion for Human-Robot Collaboration", RAL, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9353218>paper</a></summary>
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
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Adeli et al., "Socially and Contextually Aware Human Motion and Pose Forecasting", RAL, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9145701>paper</a> <a href=https://arxiv.org/pdf/2007.06843.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#posetrack">PoseTrack</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
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
</ul>
</details>

</ul><ul><a name=nll></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Negative Log-Likelihood (NLL)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Salzmann et al., "Motron: Multimodal Probabilistic Human Motion Forecasting", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Salzmann_Motron_Multimodal_Probabilistic_Human_Motion_Forecasting_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.04132.pdf>arxiv</a> <a href=https://github.com/TUM-AAS/motron-cvpr22>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#kde">KDE</a></li>
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
</ul>
</details>

</ul><ul><a name=npss></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Normalized Power Spectrum Similarity (NPSS)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Gopalakrishnan et al., "A Neural Temporal Model For Human Motion Prediction", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Gopalakrishnan_A_Neural_Temporal_Model_for_Human_Motion_Prediction_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1809.03036.pdf>arxiv</a> <a href=https://github.com/cr7anand/neural_temporal_models>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#npss">NPSS</a></li>
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
</ul>
</details>

</ul><ul><a name=nss></a>
<details close>
<summary><em><l style="font-size:20px"><strong>NSS</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Liu et al., "Joint Hand Motion and Interaction Hotspots Prediction From Egocentric Videos", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Joint_Hand_Motion_and_Interaction_Hotspots_Prediction_From_Egocentric_Videos_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.01696.pdf>arxiv</a> <a href=https://stevenlsw.github.io/hoi-forecast/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#auc">AUC</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#nss">NSS</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#ssim">SSIM</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2022_CVPR_3,
    author = "Liu, Shaowei and Tripathi, Subarna and Majumdar, Somdeb and Wang, Xiaolong",
    title = "Joint Hand Motion and Interaction Hotspots Prediction From Egocentric Videos",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=p-mpjpe></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Procrustes aligned MPJPE (P-MPJPE)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Cui et al., "Test-time Personalizable Forecasting of 3D Human Poses", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Cui_Test-time_Personalizable_Forecasting_of_3D_Human_Poses_ICCV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#grab">GRAB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpble">MPBLE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#p-mpjpe">P-MPJPE</a></li>
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
</ul>
</details>

</ul><ul><a name=pck></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Percentage of Correct Keypoints (PCK)</strong><small> [7]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Cui et al., "Test-time Personalizable Forecasting of 3D Human Poses", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Cui_Test-time_Personalizable_Forecasting_of_3D_Human_Poses_ICCV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#grab">GRAB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpble">MPBLE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#p-mpjpe">P-MPJPE</a></li>
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
<summary><strong><em>Xing et al., "HDG-ODE: A Hierarchical Continuous-Time Model for Human Pose Forecasting", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Xing_HDG-ODE_A_Hierarchical_Continuous-Time_Model_for_Human_Pose_Forecasting_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.05859.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mupots-3d">MuPoTS-3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
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
<summary><strong><em>Sun et al., "Action-guided 3D Human Motion Prediction", NeurIPS, 2021.</em></strong> <a href=https://papers.nips.cc/paper/2021/file/fd9dd764a6f1d73f4340d570804eacc4-Paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
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
<summary><strong><em>Honda et al., "RNN-based Motion Prediction in Competitive Fencing Considering Interaction between Players", BMVC, 2020.</em></strong> <a href=https://www.bmvc2020-conference.com/assets/papers/0618.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Honda_2020_BMVC,
    author = "Honda, Yutaro and Kawakami, Rei and Naemura, Takeshi",
    title = "{RNN}-based Motion Prediction in Competitive Fencing Considering Interaction between Players",
    booktitle = "BMVC",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhang et al., "Predicting 3D Human Dynamics From Video", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Predicting_3D_Human_Dynamics_From_Video_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.04781.pdf>arxiv</a> <a href=https://github.com/jasonyzhang/phd>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#instavariety">InstaVariety</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#re">RE</a></li>
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
<summary><strong><em>Chiu et al., "Action-Agnostic Human Pose Forecasting", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8658717>paper</a> <a href=https://arxiv.org/pdf/1810.09676.pdf>arxiv</a> <a href=https://github.com/eddyhkchiu/pose_forecast_wacv/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
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
<summary><strong><em>Wu et al., "Futurepose - Mixed Reality Martial Arts Training Using Real-Time 3D Human Pose Forecasting With A RGB Camera", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8658594>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#run_time">Run Time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wu_2019_WACV,
    author = "Wu, E. and Koike, H.",
    booktitle = "WACV",
    title = "Futurepose - Mixed Reality Martial Arts Training Using Real-Time 3D Human Pose Forecasting With A {RGB} Camera",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Chao et al., "Forecasting Human Dynamics From Static Images", CVPR, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Chao_Forecasting_Human_Dynamics_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1704.03432.pdf>arxiv</a> <a href=https://github.com/ywchao/image-play>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mpii_human_pose">MPII Human Pose</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
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
</ul>
</details>

</ul><ul><a name=pcp3d></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Percentage of Correct Parts (PCP3D)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Choudhury et al., "TEMPO: Efficient Multi-View Pose Estimation, Tracking, and Forecasting", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Choudhury_TEMPO_Efficient_Multi-View_Pose_Estimation_Tracking_and_Forecasting_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2309.07910.pdf>arxiv</a> <a href=https://rccchoudhury.github.io/tempo2023/>code</a></summary>
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
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pcp3d">PCP3D</a></li>
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
</ul>
</details>

</ul><ul><a name=psent></a>
<details close>
<summary><em><l style="font-size:20px"><strong>PoSe Entropy (PSEnt)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Hernandez et al., "Human Motion Prediction Via Spatio-Temporal Inpainting", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Hernandez_Human_Motion_Prediction_via_Spatio-Temporal_Inpainting_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.05478.pdf>arxiv</a> <a href=https://github.com/magnux/MotionGAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#human">Human</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pskl">PSKL</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#psent">PSEnt</a></li>
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
</ul>
</details>

</ul><ul><a name=pskl></a>
<details close>
<summary><em><l style="font-size:20px"><strong>PoSe KL (PSKL)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Hernandez et al., "Human Motion Prediction Via Spatio-Temporal Inpainting", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Hernandez_Human_Motion_Prediction_via_Spatio-Temporal_Inpainting_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.05478.pdf>arxiv</a> <a href=https://github.com/magnux/MotionGAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mane">MAnE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#human">Human</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pskl">PSKL</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#psent">PSEnt</a></li>
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
</ul>
</details>

</ul><ul><a name=r2></a>
<details close>
<summary><em><l style="font-size:20px"><strong>R2</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Wang et al., "Prediction of Whole-Body Velocity and Direction From Local Leg Joint Movements in Insect Walking via LSTM Neural Networks", RAL, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9832735>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#r2">R2</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Wang_2022_RAL,
    author = "Wang, Yuchen and Hayashibe, Mitsuhiro and Owaki, Dai",
    journal = "RAL",
    title = "Prediction of Whole-Body Velocity and Direction From Local Leg Joint Movements in Insect Walking via {LSTM} Neural Networks",
    volume = "7",
    number = "4",
    pages = "9389--9396",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=re></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Reconstruction Error (RE)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Zhang et al., "Predicting 3D Human Dynamics From Video", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Predicting_3D_Human_Dynamics_From_Video_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.04781.pdf>arxiv</a> <a href=https://github.com/jasonyzhang/phd>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#instavariety">InstaVariety</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#re">RE</a></li>
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
</ul>
</details>

</ul><ul><a name=rmse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Root Mean Square Error (RMSE)</strong><small> [11]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Du et al., "Unsupervised Pedestrian Pose Prediction: A Deep Predictive Coding Network-Based Approach for Autonomous Vehicle Perception", RAL, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9042808>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pedx">PedX</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#rmse">RMSE</a></li>
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
<summary><strong><em>Du et al., "Bio-LSTM: A Biomechanically Inspired Recurrent Neural Network for 3-D Pedestrian Pose and Gait Prediction", RAL, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8626436>paper</a> <a href=https://arxiv.org/pdf/1809.03705.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pedx">PedX</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Du_2019_RAL,
    author = "Du, X. and Vasudevan, R. and Johnson-Roberson, M.",
    journal = "RAL",
    title = "{Bio-LSTM}: A Biomechanically Inspired Recurrent Neural Network for 3-D Pedestrian Pose and Gait Prediction",
    year = "2019",
    volume = "4",
    number = "2",
    pages = "1501-1508"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Aykut et al., "Delay Compensation for a Telepresence System With 3D 360 Degree Vision Based on Deep Head Motion Prediction and Dynamic FoV Adaptation", RAL, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8429079>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Aykut_2018_RAL,
    author = "Aykut, T. and Karimi, M. and Burgmair, C. and Finkenzeller, A. and Bachhuber, C. and Steinbach, E.",
    journal = "RAL",
    title = "Delay Compensation for a Telepresence System With {3D} 360 Degree Vision Based on Deep Head Motion Prediction and Dynamic {FoV} Adaptation",
    year = "2018",
    volume = "3",
    number = "4",
    pages = "4343-4350"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=run_time></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Run Time</strong><small> [12]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Liu et al., "Towards Natural And Accurate Future Motion Prediction Of Humans And Animals", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Liu_Towards_Natural_and_Accurate_Future_Motion_Prediction_of_Humans_and_CVPR_2019_paper.pdf>paper</a> <a href=https://github.com/BII-wushuang/Lie-Group-Motion-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mouse_fish">Mouse Fish</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#run_time">Run Time</a></li>
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
<summary><strong><em>Wu et al., "Futurepose - Mixed Reality Martial Arts Training Using Real-Time 3D Human Pose Forecasting With A RGB Camera", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8658594>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#run_time">Run Time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wu_2019_WACV,
    author = "Wu, E. and Koike, H.",
    booktitle = "WACV",
    title = "Futurepose - Mixed Reality Martial Arts Training Using Real-Time 3D Human Pose Forecasting With A {RGB} Camera",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=s-mse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Sampling loss MSE (S-MSE)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Aliakbarian et al., "A Stochastic Conditioning Scheme for Diverse Human Motion Prediction", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Aliakbarian_A_Stochastic_Conditioning_Scheme_for_Diverse_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://github.com/mix-and-match/mix-and-match-tutorial>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#kld">KLD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#si">SI</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#kl">KL</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#s-mse">S-MSE</a></li>
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
</ul>
</details>

</ul><ul><a name=sde></a>
<details close>
<summary><em><l style="font-size:20px"><strong>standard Deviation of displacement Error (sDE)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Ahn et al., "Can We Use Diffusion Probabilistic Models for 3D Motion Prediction?", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10160722>paper</a> <a href=https://arxiv.org/pdf/2302.14503.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#apd">APD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#sde">sDE</a></li>
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
</ul>
</details>

</ul><ul><a name=si></a>
<details close>
<summary><em><l style="font-size:20px"><strong>SI</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Aliakbarian et al., "A Stochastic Conditioning Scheme for Diverse Human Motion Prediction", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Aliakbarian_A_Stochastic_Conditioning_Scheme_for_Diverse_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://github.com/mix-and-match/mix-and-match-tutorial>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#kld">KLD</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#si">SI</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#kl">KL</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#s-mse">S-MSE</a></li>
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
</ul>
</details>

</ul><ul><a name=ssim></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Structural SIMilarity (SSIM)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Liu et al., "Joint Hand Motion and Interaction Hotspots Prediction From Egocentric Videos", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Joint_Hand_Motion_and_Interaction_Hotspots_Prediction_From_Egocentric_Videos_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.01696.pdf>arxiv</a> <a href=https://stevenlsw.github.io/hoi-forecast/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#auc">AUC</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#nss">NSS</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#ssim">SSIM</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2022_CVPR_3,
    author = "Liu, Shaowei and Tripathi, Subarna and Majumdar, Somdeb and Wang, Xiaolong",
    title = "Joint Hand Motion and Interaction Hotspots Prediction From Egocentric Videos",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=vim></a>
<details close>
<summary><em><l style="font-size:20px"><strong>VIM</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Xu et al., "Joint-Relation Transformer for Multi-Person Motion Prediction", ICCV, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Xu_Joint-Relation_Transformer_for_Multi-Person_Motion_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.04808.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/JRTransformer>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mupots-3d">MuPoTS-3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#vim">VIM</a></li>
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
</ul>
</details>

</ul>