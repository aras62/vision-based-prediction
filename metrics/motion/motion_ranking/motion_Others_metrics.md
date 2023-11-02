<a name=top></a>
<a name=top></a>
---
<a href=../../../README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../datasets/datasets.md#top><l style="font-size:30px">Datasets</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Metrics</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
[Home](../../metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Video](../../video/video_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Action](../../action/action_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Trajectory](../../trajectory/trajectory_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Motion&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Other](../../other/other_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[Home](../motion_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Alphabetical](../motion_alphabetical/motion_alphabetical_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Ranking&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[Top5](motion_Top5_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Top6-10](motion_Top6-10_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Others&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
<h2>Others</h2> 
<ul><a name=mse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Square Error (MSE)</strong></l>
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
<summary><strong><em>Ahn et al., "Can We Use Diffusion Probabilistic Models for 3D Motion Prediction?", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10160722>paper</a> <a href=https://arxiv.org/pdf/2302.14503.pdf>arxiv</a></summary>
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
<summary><strong><em>Mascaro et al., "Robust Human Motion Forecasting using Transformer-based Model", IROS, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9981877>paper</a> <a href=https://arxiv.org/pdf/2302.08274.pdf>arxiv</a></summary>
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
<summary><strong><em>Adeli et al., "Socially and Contextually Aware Human Motion and Pose Forecasting", RAL, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9145701>paper</a> <a href=https://arxiv.org/pdf/2007.06843.pdf>arxiv</a></summary>
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
</ul>
</details>

<a name=ed></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Euclidean Distance (ED)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Mitjans et al., "Koopman Pose Predictions for Temporally Consistent Human Walking Estimations", IROS, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9981204>paper</a> <a href=https://arxiv.org/pdf/2205.02737.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#ed">ED</a></li>
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
<summary><strong><em>Zhang et al., "IMNet: Physics-Infused Neural Network for Human Motion Prediction", RAL, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9816127>paper</a></summary>
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
<summary><strong><em>Conte et al., "Autonomous Robotic Escort Incorporating Motion Prediction and Human Intention", ICRA, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9561469>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Conte_2021_ICRA,
    author = "Conte, Dean and Furukawa, Tomonari",
    booktitle = "ICRA",
    title = "Autonomous Robotic Escort Incorporating Motion Prediction and Human Intention",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Kratzer et al., "Prediction of Human Full-Body Movements with Motion Optimization and Recurrent Neural Networks", ICRA, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9197290>paper</a> <a href=https://arxiv.org/pdf/1910.01843.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kratzer_2020_ICRA,
    author = "Kratzer, P. and Toussaint, M. and Mainprice, J.",
    booktitle = "ICRA",
    title = "Prediction of Human Full-Body Movements with Motion Optimization and Recurrent Neural Networks",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

<a name=fid></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Frechet Instance Distance (FID)</strong></l>
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
<summary><strong><em>Mao et al., "Weakly-Supervised Action Transition Learning for Stochastic Human Motion Prediction", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Mao_Weakly-Supervised_Action_Transition_Learning_for_Stochastic_Human_Motion_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://github.com/wei-mao-2019/WAT>code</a></summary>
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
<summary><strong><em>Nawhal et al., "Rethinking Learning Approaches for Long-Term Action Anticipation", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136660409.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.10542.pdf>arxiv</a> <a href=https://europe.naverlabs.com/research/computer-vision/posegpt/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#grab">GRAB</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#babel">BABEL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fid">FID</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#dt">DT</a></li>
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
</ul>
</details>

<a name=rmse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Root Mean Square Error (RMSE)</strong></l>
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
<summary><strong><em>Du et al., "Bio-LSTM: A Biomechanically Inspired Recurrent Neural Network for 3-D Pedestrian Pose and Gait Prediction", RAL, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8626436>paper</a> <a href=https://arxiv.org/pdf/1809.03705.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pedx">PedX</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#rmse">RMSE</a></li>
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
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#rmse">RMSE</a></li>
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

<a name=minade></a>
<details close>
<summary><em><l style="font-size:20px"><strong>minADE</strong></l>
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
<summary><strong><em>Xu et al., "Diverse Human Motion Prediction Guided by Multi-level Spatial-Temporal Anchors", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820244.pdf>paper</a> <a href=https://github.com/Sirui-Xu/STARS>code</a></summary>
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
</ul>
</details>

<a name=minfde></a>
<details close>
<summary><em><l style="font-size:20px"><strong>minFDE</strong></l>
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
<summary><strong><em>Xu et al., "Diverse Human Motion Prediction Guided by Multi-level Spatial-Temporal Anchors", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820244.pdf>paper</a> <a href=https://github.com/Sirui-Xu/STARS>code</a></summary>
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
</ul>
</details>

<a name=accuracy></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Accuracy</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Luo et al., "Human Intention Inference And On-Line Human Hand Motion Prediction For Human-Robot Collaboration", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8968192>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Luo_2019_IROS,
    author = "Luo, Ren C. and Mai, Lincong",
    booktitle = "IROS",
    title = "Human Intention Inference And On-Line Human Hand Motion Prediction For Human-Robot Collaboration",
    year = "2019"
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
</ul>
</details>

<a name=human></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Human Judgement (Human)</strong></l>
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
<summary><strong><em>Gui et al., "Adversarial Geometry-Aware Human Motion Prediction", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Liangyan_Gui_Adversarial_Geometry-Aware_Human_ECCV_2018_paper.pdf>paper</a></summary>
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
</ul>
</details>

<a name=run_time></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Run Time</strong></l>
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
<summary><strong><em>Wu et al., "Futurepose - Mixed Reality Martial Arts Training Using Real-Time 3D Human Pose Forecasting With A RGB Camera", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8658594>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#pck">PCK</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#run_time">Run Time</a></li>
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

<a name=kld></a>
<details close>
<summary><em><l style="font-size:20px"><strong>KullbackLeibler Divergence (KLD)</strong></l>
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
<summary><strong><em>Aliakbarian et al., "A Stochastic Conditioning Scheme for Diverse Human Motion Prediction", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Aliakbarian_A_Stochastic_Conditioning_Scheme_for_Diverse_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://github.com/mix-and-match/mix-and-match-tutorial>code</a></summary>
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
</ul>
</details>

<a name=l2></a>
<details close>
<summary><em><l style="font-size:20px"><strong>L2</strong></l>
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
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#l2">L2</a></li>
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

<a name=si></a>
<details close>
<summary><em><l style="font-size:20px"><strong>SI</strong></l>
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
</ul>
</details>

<a name=mape></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Absolute Percentage Error (MAPE)</strong></l>
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
</ul>
</details>

<a name=pskl></a>
<details close>
<summary><em><l style="font-size:20px"><strong>PoSe KL (PSKL)</strong></l>
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
</ul>
</details>

<a name=psent></a>
<details close>
<summary><em><l style="font-size:20px"><strong>PoSe Entropy (PSEnt)</strong></l>
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
</ul>
</details>

<a name=lo></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Limb Orientation (LO)</strong></l>
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
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mje">MJE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#lo">LO</a></li>
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

<a name=npss></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Normalized Power Spectrum Similarity (NPSS)</strong></l>
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
</ul>
</details>

<a name=cmd></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Cumulative Motion Distribution (CMD)</strong></l>
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
</ul>
</details>

<a name=pcp3d></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Percentage of Correct Parts (PCP3D)</strong></l>
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
</ul>
</details>

<a name=cma></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Cumulative Matching Accuracy (CMA)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Yuan et al., "3DMotion-Net: Learning Continuous Flow Function for 3D Motion Prediction", IROS, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9341671>paper</a> <a href=https://arxiv.org/pdf/2006.13906.pdf>arxiv</a></summary>
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
</ul>
</details>

<a name=p-mpjpe></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Procrustes aligned MPJPE (P-MPJPE)</strong></l>
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
</ul>
</details>

<a name=mpble></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Per-Bone Length Error (MPBLE)</strong></l>
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
</ul>
</details>

<a name=vim></a>
<details close>
<summary><em><l style="font-size:20px"><strong>VIM</strong></l>
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
</ul>
</details>

<a name=dt></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Diversity Test (DT)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Nawhal et al., "Rethinking Learning Approaches for Long-Term Action Anticipation", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136660409.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.10542.pdf>arxiv</a> <a href=https://europe.naverlabs.com/research/computer-vision/posegpt/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#grab">GRAB</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#babel">BABEL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fid">FID</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#dt">DT</a></li>
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
</ul>
</details>

<a name=kl></a>
<details close>
<summary><em><l style="font-size:20px"><strong>KL</strong></l>
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
</ul>
</details>

<a name=s-mse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Sampling loss MSE (S-MSE)</strong></l>
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
</ul>
</details>

<a name=sde></a>
<details close>
<summary><em><l style="font-size:20px"><strong>standard Deviation of displacement Error (sDE)</strong></l>
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
</ul>
</details>

<a name=ame></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Aligned Mean Error (AME)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Guo et al., "Multi-Person Extreme Motion Prediction", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_Multi-Person_Extreme_Motion_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2105.08825.pdf>arxiv</a> <a href=https://github.com/GUO-W/MultiMotion>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#expi">ExPI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ame">AME</a></li>
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
</ul>
</details>

<a name=is></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Inception Scores (IS)</strong></l>
</em></summary>
<ul>
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
</ul>
</details>

<a name=r2></a>
<details close>
<summary><em><l style="font-size:20px"><strong>R2</strong></l>
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
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#r2">R2</a></li>
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

<a name=div></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Div</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Mao et al., "Weakly-Supervised Action Transition Learning for Stochastic Human Motion Prediction", CVPR, 2022.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Mao_Weakly-Supervised_Action_Transition_Learning_for_Stochastic_Human_Motion_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://github.com/wei-mao-2019/WAT>code</a></summary>
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
</ul>
</details>

<a name=re></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Reconstruction Error (RE)</strong></l>
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
</ul>
</details>

<a name=nll></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Negative Log-Likelihood (NLL)</strong></l>
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
</ul>
</details>

<a name=ssim></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Structural SIMilarity (SSIM)</strong></l>
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
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#auc">AUC</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#nss">NSS</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#ssim">SSIM</a></li>
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

<a name=nss></a>
<details close>
<summary><em><l style="font-size:20px"><strong>NSS</strong></l>
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
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#auc">AUC</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#nss">NSS</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#ssim">SSIM</a></li>
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

<a name=auc></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Area Under the Curve (AUC)</strong></l>
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
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#auc">AUC</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#nss">NSS</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#ssim">SSIM</a></li>
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

<a name=kde></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Keypoint Displacement Error (KDE)</strong></l>
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
</ul>
</details>

</ul>