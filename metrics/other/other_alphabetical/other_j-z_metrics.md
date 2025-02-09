<a name=top></a>
<a name=top></a>
---
<a href=../../../README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../datasets/datasets.md#top><l style="font-size:30px">Datasets</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Metrics</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
[Home](../../metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Video](../../video/video_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Action](../../action/action_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Trajectory](../../trajectory/trajectory_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Motion](../../motion/motion_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Other&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[Home](../other_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Alphabetical&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Ranking](../other_ranking/other_ranking_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[A-D](other_a-d_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[E-I](other_e-i_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;J-Z&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
<h2>J-Z <small>[rank]</small></h2> 
<ul><a name=kld></a>
<details close>
<summary><em><l style="font-size:20px"><strong>KullbackLeibler Divergence (KLD)</strong><small> [12]</small></l>
</em></summary>
<ul>
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
<summary><strong><em>Doellinger et al., "Predicting Occupancy Distributions of Walking Humans With Convolutional Neural Networks", RAL, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8278198>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#rt">RT</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#kld">KLD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Doellinger_2018_RAL,
    author = "Doellinger, J. and Spies, M. and Burgard, W.",
    journal = "RAL",
    title = "Predicting Occupancy Distributions of Walking Humans With Convolutional Neural Networks",
    year = "2018",
    volume = "3",
    number = "3",
    pages = "1522-1528"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=l1></a>
<details close>
<summary><em><l style="font-size:20px"><strong>L1</strong><small> [11]</small></l>
</em></summary>
<ul>
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

</ul><ul><a name=l2></a>
<details close>
<summary><em><l style="font-size:20px"><strong>L2</strong><small> [12]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Li et al., "Weakly Supervised Class-Agnostic Motion Prediction for Autonomous Driving", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Weakly_Supervised_Class-Agnostic_Motion_Prediction_for_Autonomous_Driving_CVPR_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#l2">L2</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2023_CVPR,
    author = "Li, Ruibo and Shi, Hanyu and Fu, Ziang and Wang, Zhe and Lin, Guosheng",
    title = "Weakly Supervised Class-Agnostic Motion Prediction for Autonomous Driving",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Razali et al., "Using Eye Gaze to Forecast Human Pose in Everyday Pick and Place Actions", ICRA, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/document/9812079>paper</a> <a href=https://github.com/HaziqRazali/Using-Eye-Gaze-to-Forecast-Human-Pose-in-Everyday-Pick-and-Place-Actions>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#mogaze">MoGaze</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#l2">L2</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Razali_2022_ICRA,
    author = "Razali, Haziq and Demiris, Yiannis",
    booktitle = "ICRA",
    title = "Using Eye Gaze to Forecast Human Pose in Everyday Pick and Place Actions",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=mae></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Absolute Error (MAE)</strong><small> [7]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Kalble et al., "Accurate Training Data for Occupancy Map Prediction in Automated Driving Using Evidence Theory", CVPR, 2024.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Kalble_Accurate_Training_Data_for_Occupancy_Map_Prediction_in_Automated_Driving_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2405.10575>arxiv</a> <a href=https://github.com/boschresearch/evidential-occupancy>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kalble_Accurate_2024_CVPR,
    author = "Kalble, Jonas and Wirges, Sascha and Tatarchenko, Maxim and Ilg, Eddy",
    title = "Accurate Training Data for Occupancy Map Prediction in Automated Driving Using Evidence Theory",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Yoon et al., "Probabilistic Weather Forecasting with Deterministic Guidance-Based Diffusion Model", ECCV, 2024.</em></strong> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04326.pdf>paper</a> <a href=https://github.com/DongGeun-Yoon/DGDM>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#weatherbench">WeatherBench</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pnw-typhoon">PNW-Typhoon</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#fvd">FVD</a></li>
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
<summary><strong><em>Oota et al., "HealTech - A System for Predicting Patient Hospitalization Risk and Wound Progression in Old Patients", WACV, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Oota_HealTech_-_A_System_for_Predicting_Patient_Hospitalization_Risk_and_WACV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Oota_2021_WACV,
    author = "Oota, Subba Reddy and Rowtula, Vijay and Mohammed, Shahid and Galitz, Jeffrey and Liu, Minghsun and Gupta, Manish",
    title = "{HealTech} - A System for Predicting Patient Hospitalization Risk and Wound Progression in Old Patients",
    booktitle = "WACV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Sohn et al., "Laying the Foundations of Deep Long-Term Crowd Flow Prediction", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123740698.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ltcf">LTCF</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sohn_2020_ECCV,
    author = "Sohn, Samuel S and Zhou, Honglu and Moon, Seonghyeon and Yoon, Sejong and Pavlovic, Vladimir and Kapadia, Mubbasir",
    title = "Laying the Foundations of Deep Long-Term Crowd Flow Prediction",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>He et al., "Aggregated Sparse Attention For Steering Angle Prediction", ICPR, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8546051>paper</a> <a href=https://arxiv.org/pdf/1803.05785.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#diplecs">DIPLECS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
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
<details close>
<summary><strong><em>Al-Halah et al., "Fashion Forward: Forecasting Visual Style In Fashion", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Al-Halah_Fashion_Forward_Forecasting_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.06394.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#amazon">Amazon</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mape">MAPE</a></li>
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
<details close>
<summary><strong><em>Cai et al., "Asking for Help with the Right Question by Predicting Human Visual Performance", RSS, 2016.</em></strong> <a href=http://www.roboticsproceedings.org/rss12/p38.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#nmse">NMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cai_2016_RSS,
    author = "Cai, Hong and Mostofi, Yasamin",
    title = "Asking for Help with the Right Question by Predicting Human Visual Performance",
    booktitle = "RSS",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wilson et al., "Vehicle State Prediction For Outdoor Autonomous High-Speed Off-Road UGVs", ICRA, 2015.</em></strong> <a href=https://ieeexplore.ieee.org/document/7139221>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wilson_2015_ICRA,
    author = "Wilson, G. N. and Ramirez-Serrano, A. and Sun, Q.",
    booktitle = "ICRA",
    title = "Vehicle State Prediction For Outdoor Autonomous High-Speed Off-Road {UGVs}",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=map></a>
<details close>
<summary><em><l style="font-size:20px"><strong>mean Average Precision (mAP)</strong><small> [10]</small></l>
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
<summary><strong><em>Liu et al., "LiDAR-based 4D Occupancy Completion and Forecasting", IROS, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10801302>paper</a> <a href=https://arxiv.org/pdf/2310.11239>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#map">mAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Liu_LiDAR_2024_IROS,
    author = "Liu, Xinhao and Gong, Moonjun and Fang, Qi and Xie, Haoyu and Li, Yiming and Zhao, Hang and Feng, Chen",
    booktitle = "IROS",
    title = "LiDAR-based 4D Occupancy Completion and Forecasting",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Agro et al., "Implicit Occupancy Flow Fields for Perception and Prediction in Self-Driving", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Agro_Implicit_Occupancy_Flow_Fields_for_Perception_and_Prediction_in_Self-Driving_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.01471.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#epe">EPE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#map">mAP</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#rt">RT</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#soft-iou">Soft-IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#ece">ECE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Agro_2023_CVPR,
    author = "Agro, Ben and Sykora, Quinlan and Casas, Sergio and Urtasun, Raquel",
    title = "Implicit Occupancy Flow Fields for Perception and Prediction in Self-Driving",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
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

</ul><ul><a name=mape></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Absolute Percentage Error (MAPE)</strong><small> [12]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Wang et al., "Retweet Wars: Tweet Popularity Prediction Via Dynamic Multimodal Regression", WACV, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8354308>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#mbi-1m">MBI-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mape">MAPE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#src">SRC</a></li>
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
<details close>
<summary><strong><em>Al-Halah et al., "Fashion Forward: Forecasting Visual Style In Fashion", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Al-Halah_Fashion_Forward_Forecasting_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.06394.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#amazon">Amazon</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mape">MAPE</a></li>
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
</ul>
</details>

</ul><ul><a name=mbd></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Bias Deviation (MBD)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Li et al., "SolarCube: An Integrative Benchmark Dataset Harnessing Satellite and In-situ Observations for Large-scale Solar Energy Forecasting", NeurIPS, 2024.</em></strong> <a href=https://openreview.net/pdf?id=WffhOhYvZ0>paper</a> <a href=https://github.com/Ruohan-Li/SolarCube>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#solarcube">SolarCube</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#rmse">RMSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#r-squared">R-squared</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#fs">FS</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mbd">MBD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Li_Solarcube_2024_NeurIPS,
    author = "Li, Ruohan and Xie, Yiqun and Jia, Xiaowei and Wang, Dongdong and Li, Yanhua and Zhang, Yingxue and Wang, Zhihao and Li, Zhili",
    title = "SolarCube: An Integrative Benchmark Dataset Harnessing Satellite and In-situ Observations for Large-scale Solar Energy Forecasting",
    booktitle = "NeurIPS",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=mcc></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Matthews Correlation Coefficient (MCC)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Sur et al., "Robots That Anticipate Pain: Anticipating Physical Perturbations From Visual Cues Through Deep Predictive Models", IROS, 2017.</em></strong> <a href=https://ieeexplore.ieee.org/document/8206442>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mcc">MCC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sur_2017_IROS,
    author = "Sur, I. and Ben Amor, H.",
    booktitle = "IROS",
    title = "Robots That Anticipate Pain: Anticipating Physical Perturbations From Visual Cues Through Deep Predictive Models",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=mce></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Maximum Calibration Error (MCE)</strong><small> [13]</small></l>
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

</ul><ul><a name=me></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Error (ME)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Yang et al., "FaceScape: A Large-Scale High Quality 3D Face Dataset and Detailed Riggable 3D Face Prediction", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_FaceScape_A_Large-Scale_High_Quality_3D_Face_Dataset_and_Detailed_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.13989.pdf>arxiv</a> <a href=https://github.com/zhuhao-nju/facescape>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#facescape">FaceScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#me">ME</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yang_2020_CVPR,
    author = "Yang, Haotian and Zhu, Hao and Wang, Yanru and Huang, Mingkai and Shen, Qiu and Yang, Ruigang and Cao, Xun",
    title = "{FaceScape}: A Large-Scale High Quality 3D Face Dataset and Detailed Riggable {3D} Face Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=meteor></a>
<details close>
<summary><em><l style="font-size:20px"><strong>METEOR</strong><small> [13]</small></l>
</em></summary>
<ul>
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

</ul><ul><a name=miou></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean IoU (MIoU)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Jin et al., "Predicting Scene Parsing And Motion Dynamics In The Future", NeurIPS, 2017.</em></strong> <a href=https://papers.nips.cc/paper/7267-predicting-scene-parsing-and-motion-dynamics-in-the-future.pdf>paper</a> <a href=https://arxiv.org/pdf/1711.03270.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#epe">EPE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#miou">MIoU</a></li>
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
</ul>
</details>

</ul><ul><a name=mpe></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Position Error (MPE)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Weng et al., "Graph-based Task-specific Prediction Models for Interactions between Deformable and Rigid Objects", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636660>paper</a> <a href=https://arxiv.org/pdf/2103.02932.pdf>arxiv</a> <a href=https://github.com/wengzehang/deformable_rigid_interaction_prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#drip">DRIP</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mpe">MPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Weng_2021_IROS,
    author = "Weng, Zehang and Paus, Fabian and Varava, Anastasiia and Yin, Hang and Asfour, Tamim and Kragic, Danica",
    booktitle = "IROS",
    title = "Graph-based Task-specific Prediction Models for Interactions between Deformable and Rigid Objects",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=mre></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Relative Error (MRE)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Xie et al., "Automated Type-Aware Traffic Speed Prediction based on Sparse Intelligent Camera System", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636559>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mre">MRE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xie_2021_IROS,
    author = "Xie, Xiaoyang and Shao, Kangjia and Wang, Yang and Miao, Fei and Zhang, Desheng",
    booktitle = "IROS",
    title = "Automated Type-Aware Traffic Speed Prediction based on Sparse Intelligent Camera System",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=mse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Square Error (MSE)</strong><small> [7]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Yoon et al., "Probabilistic Weather Forecasting with Deterministic Guidance-Based Diffusion Model", ECCV, 2024.</em></strong> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04326.pdf>paper</a> <a href=https://github.com/DongGeun-Yoon/DGDM>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#weatherbench">WeatherBench</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pnw-typhoon">PNW-Typhoon</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#fvd">FVD</a></li>
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
<summary><strong><em>Toyungyernsub et al., "Dynamics-Aware Spatiotemporal Occupancy Prediction in Urban Environments", IROS, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9981323>paper</a> <a href=https://arxiv.org/pdf/2209.13172.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#is">IS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Toyungyernsub_2022_IROS,
    author = "Toyungyernsub, Maneekwan and Yel, Esen and Li, Jiachen and Kochenderfer, Mykel J",
    booktitle = "IROS",
    title = "Dynamics-Aware Spatiotemporal Occupancy Prediction in Urban Environments",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
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
<details close>
<summary><strong><em>Qi et al., "Imitative Non-Autoregressive Modeling for Trajectory Forecasting and Imputation", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Qi_Imitative_Non-Autoregressive_Modeling_for_Trajectory_Forecasting_and_Imputation_CVPR_2020_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#btd">BTD</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pems-sf">PEMS-SF</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Qi_2020_CVPR,
    author = "Qi, Mengshi and Qin, Jie and Wu, Yu and Yang, Yi",
    title = "Imitative Non-Autoregressive Modeling for Trajectory Forecasting and Imputation",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Sohn et al., "Laying the Foundations of Deep Long-Term Crowd Flow Prediction", ECCV, 2020.</em></strong> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123740698.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ltcf">LTCF</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sohn_2020_ECCV,
    author = "Sohn, Samuel S and Zhou, Honglu and Moon, Seonghyeon and Yoon, Sejong and Pavlovic, Vladimir and Kapadia, Mubbasir",
    title = "Laying the Foundations of Deep Long-Term Crowd Flow Prediction",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Jin et al., "Predicting Scene Parsing And Motion Dynamics In The Future", NeurIPS, 2017.</em></strong> <a href=https://papers.nips.cc/paper/7267-predicting-scene-parsing-and-motion-dynamics-in-the-future.pdf>paper</a> <a href=https://arxiv.org/pdf/1711.03270.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#epe">EPE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#miou">MIoU</a></li>
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
<details close>
<summary><strong><em>Cai et al., "Asking for Help with the Right Question by Predicting Human Visual Performance", RSS, 2016.</em></strong> <a href=http://www.roboticsproceedings.org/rss12/p38.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#nmse">NMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cai_2016_RSS,
    author = "Cai, Hong and Mostofi, Yasamin",
    title = "Asking for Help with the Right Question by Predicting Human Visual Performance",
    booktitle = "RSS",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=nfcd></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Near-Field Chamfer Distance (NFCD)</strong><small> [13]</small></l>
</em></summary>
<ul>
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
</ul>
</details>

</ul><ul><a name=nfe></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Near-Field Error (NFE)</strong><small> [13]</small></l>
</em></summary>
<ul>
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

</ul><ul><a name=nll></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Negative Log-Likelihood (NLL)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Oh et al., "HCNAF: Hyper-Conditioned Neural Autoregressive Flow and its Application for Probabilistic Occupancy Map Forecasting", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Oh_HCNAF_Hyper-Conditioned_Neural_Autoregressive_Flow_and_its_Application_for_Probabilistic_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.08111.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#mnist">MNIST</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#nll">NLL</a></li>
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
</ul>
</details>

</ul><ul><a name=nmape></a>
<details close>
<summary><em><l style="font-size:20px"><strong>normalized Mean Absolute Percentage Error (nMAPE)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Siddiqui et al., "A Deep Learning Approach To Solar-Irradiance Forecasting In Sky-Videos", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8659184>paper</a> <a href=https://arxiv.org/pdf/1901.04881.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#arizona">Arizona</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#tuscan">Tuscan</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#golden_colorado">Golden Colorado</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#nmape">nMAPE</a></li>
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
</ul>
</details>

</ul><ul><a name=nmse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Normalized MSE (NMSE)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Cai et al., "Asking for Help with the Right Question by Predicting Human Visual Performance", RSS, 2016.</em></strong> <a href=http://www.roboticsproceedings.org/rss12/p38.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#nmse">NMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cai_2016_RSS,
    author = "Cai, Hong and Mostofi, Yasamin",
    title = "Asking for Help with the Right Question by Predicting Human Visual Performance",
    booktitle = "RSS",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=nse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Nash-Sutcliffe Efficiency (NSE)</strong><small> [13]</small></l>
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
</ul>
</details>

</ul><ul><a name=nss></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Normalized Scanpath Salience (NSS)</strong><small> [13]</small></l>
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
</ul>
</details>

</ul><ul><a name=p-value></a>
<details close>
<summary><em><l style="font-size:20px"><strong>p-value</strong><small> [13]</small></l>
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
</ul>
</details>

</ul><ul><a name=pcp></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Percentage of Correct Predictions (PCP)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Mottaghi et al., "What Happens If... Learning To Predict The Effect Of Forces In Images", ECCV, 2016.</em></strong> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46493-0_17>paper</a> <a href=https://arxiv.org/pdf/1603.05600.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#sun_rgb-d">SUN RGB-D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#pcp">PCP</a></li>
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
</ul>
</details>

</ul><ul><a name=ppfe></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Per-point Flow Error (PPFE)</strong><small> [13]</small></l>
</em></summary>
<ul>
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

</ul><ul><a name=pq></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Panoptic Quality (PQ)</strong><small> [12]</small></l>
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
</ul>
</details>

</ul><ul><a name=precision></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Precision</strong><small> [4]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Lai et al., "Listen to look into the future: Audio-visual egocentric gaze anticipation", ECCV, 2024.</em></strong> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/01396.pdf>paper</a> <a href=https://arxiv.org/pdf/2305.03907>arxiv</a> <a href=https://bolinlai.github.io/CSTS-EgoGazeAnticipation/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#ego4d">Ego4D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Lai_Listen_2024_ECCV,
    author = "Lai, Bolin and Ryan, Fiona and Jia, Wenqi and Liu, Miao and Rehg, James M",
    title = "Listen to look into the future: Audio-visual egocentric gaze anticipation",
    booktitle = "ECCV",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Liu et al., "LiDAR-based 4D Occupancy Completion and Forecasting", IROS, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10801302>paper</a> <a href=https://arxiv.org/pdf/2310.11239>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#map">mAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Liu_LiDAR_2024_IROS,
    author = "Liu, Xinhao and Gong, Moonjun and Fang, Qi and Xie, Haoyu and Li, Yiming and Zhao, Hang and Feng, Chen",
    booktitle = "IROS",
    title = "LiDAR-based 4D Occupancy Completion and Forecasting",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
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
<summary><strong><em>Li et al., "TTC4MCP: Monocular Collision Prediction Based on Self-Supervised TTC Estimation", IROS, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10341966>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#time">time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@INPROCEEDINGS{Li_2023_IROS,
    author = "Li, Changlin and Qian, Yeqiang and Sun, Cong and Yan, Weihao and Wang, Chunxiang and Yang, Ming",
    booktitle = "IROS",
    title = "TTC4MCP: Monocular Collision Prediction Based on Self-Supervised TTC Estimation",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Sharma et al., "ProxMaP: Proximal Occupancy Map Prediction for Efficient Indoor Robot Navigation", IROS, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10341435>paper</a> <a href=https://arxiv.org/pdf/2203.04177.pdf>arxiv</a> <a href=https://raaslab.org/projects/ProxMaP/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#hm3d">HM3D</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@INPROCEEDINGS{Sharma_2023_IROS,
    author = "Sharma, Vishnu D. and Chen, Jingxi and Tokekar, Pratap",
    booktitle = "IROS",
    title = "ProxMaP: Proximal Occupancy Map Prediction for Efficient Indoor Robot Navigation",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Jia et al., "Generative Adversarial Network for Future Hand Segmentation from Egocentric Video", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136730638.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.11305.pdf>arxiv</a> <a href=https://vjwq.github.io/EgoGAN/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jia_2022_ECCV,
    author = "Jia, Wenqi and Liu, Miao and Rehg, James M.",
    title = "Generative Adversarial Network for Future Hand Segmentation from Egocentric Video",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
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
<details close>
<summary><strong><em>Walters et al., "EVReflex: Dense Time-to-Impact Prediction for Event-based Obstacle Avoidance", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636327>paper</a> <a href=https://arxiv.org/pdf/2109.00405.pdf>arxiv</a></summary>
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
<summary><strong><em>Wang et al., "Learning-based 3D Occupancy Prediction for Autonomous Navigation in Occluded Environments", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636333>paper</a> <a href=https://arxiv.org/pdf/2011.03981.pdf>arxiv</a> <a href=https://github.com/ZJU-FAST-Lab/OPNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2021_IROS,
    author = "Wang, Lizi and Ye, Hongkai and Wang, Qianhao and Gao, Yuman and Xu, Chao and Gao, Fei",
    booktitle = "IROS",
    title = "Learning-based {3D} Occupancy Prediction for Autonomous Navigation in Occluded Environments",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wirthmüller et al., "Predicting the Time Until a Vehicle Changes the Lane Using LSTM-Based Recurrent Neural Networks", RAL, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9353203>paper</a> <a href=https://arxiv.org/pdf/2102.01431.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Wirthmuller_2021_RAL,
    author = "Wirthmüller, Florian and Klimke, Marvin and Schlechtriemen, Julian and Hipp, Jochen and Reichert, Manfred",
    journal = "RAL",
    title = "Predicting the Time Until a Vehicle Changes the Lane Using {LSTM-Based} Recurrent Neural Networks",
    year = "2021",
    volume = "6",
    number = "2",
    pages = "2357-2364"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Kataoka et al., "Joint Pedestrian Detection and Risk-level Prediction with Motion-Representation-by-Detection", ICRA, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9197399>paper</a></summary>
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
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kataoka_2020_ICRA,
    author = "Kataoka, H. and Suzuki, T. and Nakashima, K. and Satoh, Y. and Aoki, Y.",
    booktitle = "ICRA",
    title = "Joint Pedestrian Detection and Risk-level Prediction with Motion-Representation-by-Detection",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wang et al., "Group Split and Merge Prediction With 3D Convolutional Networks", RAL, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/8972421>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Wang_2020_RAL,
    author = "Wang, A. and Steinfeld, A.",
    journal = "RAL",
    title = "Group Split and Merge Prediction With 3D Convolutional Networks",
    year = "2020",
    volume = "5",
    number = "2",
    pages = "1923-1930"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Kim et al., "Deep-Hurricane-Tracker: Tracking And Forecasting Extreme Climate Events", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8658402>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kim_2019_WACV,
    author = "Kim, S. and Kim, H. and Lee, J. and Yoon, S. and Kahou, S. E. and Kashinath, K. and Prabhat, M.",
    booktitle = "WACV",
    title = "Deep-Hurricane-Tracker: Tracking And Forecasting Extreme Climate Events",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Sur et al., "Robots That Anticipate Pain: Anticipating Physical Perturbations From Visual Cues Through Deep Predictive Models", IROS, 2017.</em></strong> <a href=https://ieeexplore.ieee.org/document/8206442>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mcc">MCC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sur_2017_IROS,
    author = "Sur, I. and Ben Amor, H.",
    booktitle = "IROS",
    title = "Robots That Anticipate Pain: Anticipating Physical Perturbations From Visual Cues Through Deep Predictive Models",
    year = "2017"
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

</ul><ul><a name=psi></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Psi</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Afolabi et al., "People As Sensors: Imputing Maps From Human Actions", IROS, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8594511>paper</a> <a href=https://arxiv.org/pdf/1711.01022.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#psi">Psi</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#ism">ISM</a></li>
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
</ul>
</details>

</ul><ul><a name=psnr></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Peak Signal-to-Noise Ratio (PSNR)</strong><small> [10]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Yang et al., "Carff: Conditional auto-encoded radiance field for 3d scene forecasting", ECCV, 2024.</em></strong> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/12520.pdf>paper</a> <a href=https://www.carff.website/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Yang_Carff_2024_ECCV,
    author = "Yang, Jiezhi and Desai, Khushi and Packer, Charles and Bhatia, Harshil and Rhinehart, Nicholas and McAllister, Rowan and Gonzalez, Joseph E",
    title = "Carff: Conditional auto-encoded radiance field for 3d scene forecasting",
    booktitle = "ECCV",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Yoon et al., "Probabilistic Weather Forecasting with Deterministic Guidance-Based Diffusion Model", ECCV, 2024.</em></strong> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04326.pdf>paper</a> <a href=https://github.com/DongGeun-Yoon/DGDM>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#weatherbench">WeatherBench</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pnw-typhoon">PNW-Typhoon</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#fvd">FVD</a></li>
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
<summary><strong><em>Katyal et al., "Uncertainty-Aware Occupancy Map Prediction Using Generative Networks For Robot Navigation", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8793500>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#run_time">Run Time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Katyal_2019_ICRA,
    author = "Katyal, K. and Popek, K. and Paxton, C. and Burlina, P. and Hager, G. D.",
    booktitle = "ICRA",
    title = "Uncertainty-Aware Occupancy Map Prediction Using Generative Networks For Robot Navigation",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Luc et al., "Predicting Deeper Into The Future Of Semantic Segmentation", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Luc_Predicting_Deeper_Into_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1703.07684.pdf>arxiv</a> <a href=https://github.com/facebookresearch/SegmPred>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#psnr">PSNR</a></li>
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
</ul>
</details>

</ul><ul><a name=r-squared></a>
<details close>
<summary><em><l style="font-size:20px"><strong>R-squared</strong><small> [12]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Li et al., "SolarCube: An Integrative Benchmark Dataset Harnessing Satellite and In-situ Observations for Large-scale Solar Energy Forecasting", NeurIPS, 2024.</em></strong> <a href=https://openreview.net/pdf?id=WffhOhYvZ0>paper</a> <a href=https://github.com/Ruohan-Li/SolarCube>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#solarcube">SolarCube</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#rmse">RMSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#r-squared">R-squared</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#fs">FS</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mbd">MBD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Li_Solarcube_2024_NeurIPS,
    author = "Li, Ruohan and Xie, Yiqun and Jia, Xiaowei and Wang, Dongdong and Li, Yanhua and Zhang, Yingxue and Wang, Zhihao and Li, Zhili",
    title = "SolarCube: An Integrative Benchmark Dataset Harnessing Satellite and In-situ Observations for Large-scale Solar Energy Forecasting",
    booktitle = "NeurIPS",
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

</ul><ul><a name=recall></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Recall</strong><small> [3]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Lai et al., "Listen to look into the future: Audio-visual egocentric gaze anticipation", ECCV, 2024.</em></strong> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/01396.pdf>paper</a> <a href=https://arxiv.org/pdf/2305.03907>arxiv</a> <a href=https://bolinlai.github.io/CSTS-EgoGazeAnticipation/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#ego4d">Ego4D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Lai_Listen_2024_ECCV,
    author = "Lai, Bolin and Ryan, Fiona and Jia, Wenqi and Liu, Miao and Rehg, James M",
    title = "Listen to look into the future: Audio-visual egocentric gaze anticipation",
    booktitle = "ECCV",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Peddi et al., "Towards scene graph anticipation", ECCV, 2024.</em></strong> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/12130.pdf>paper</a> <a href=https://arxiv.org/pdf/2403.04899>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#action_genome">Action Genome</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Peddi_Towards_2024_ECCV,
    author = "Peddi, Rohith and Singh, Saksham and Saurabh and Singla, Parag and Gogate, Vibhav",
    title = "Towards scene graph anticipation",
    booktitle = "ECCV",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Liu et al., "LiDAR-based 4D Occupancy Completion and Forecasting", IROS, 2024.</em></strong> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10801302>paper</a> <a href=https://arxiv.org/pdf/2310.11239>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#map">mAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Liu_LiDAR_2024_IROS,
    author = "Liu, Xinhao and Gong, Moonjun and Fang, Qi and Xie, Haoyu and Li, Yiming and Zhao, Hang and Feng, Chen",
    booktitle = "IROS",
    title = "LiDAR-based 4D Occupancy Completion and Forecasting",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
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
<details close>
<summary><strong><em>Li et al., "TTC4MCP: Monocular Collision Prediction Based on Self-Supervised TTC Estimation", IROS, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10341966>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#time">time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@INPROCEEDINGS{Li_2023_IROS,
    author = "Li, Changlin and Qian, Yeqiang and Sun, Cong and Yan, Weihao and Wang, Chunxiang and Yang, Ming",
    booktitle = "IROS",
    title = "TTC4MCP: Monocular Collision Prediction Based on Self-Supervised TTC Estimation",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Sharma et al., "ProxMaP: Proximal Occupancy Map Prediction for Efficient Indoor Robot Navigation", IROS, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10341435>paper</a> <a href=https://arxiv.org/pdf/2203.04177.pdf>arxiv</a> <a href=https://raaslab.org/projects/ProxMaP/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#hm3d">HM3D</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@INPROCEEDINGS{Sharma_2023_IROS,
    author = "Sharma, Vishnu D. and Chen, Jingxi and Tokekar, Pratap",
    booktitle = "IROS",
    title = "ProxMaP: Proximal Occupancy Map Prediction for Efficient Indoor Robot Navigation",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Jia et al., "Generative Adversarial Network for Future Hand Segmentation from Egocentric Video", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136730638.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.11305.pdf>arxiv</a> <a href=https://vjwq.github.io/EgoGAN/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jia_2022_ECCV,
    author = "Jia, Wenqi and Liu, Miao and Rehg, James M.",
    title = "Generative Adversarial Network for Future Hand Segmentation from Egocentric Video",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Walters et al., "EVReflex: Dense Time-to-Impact Prediction for Event-based Obstacle Avoidance", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636327>paper</a> <a href=https://arxiv.org/pdf/2109.00405.pdf>arxiv</a></summary>
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
<summary><strong><em>Wang et al., "Learning-based 3D Occupancy Prediction for Autonomous Navigation in Occluded Environments", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636333>paper</a> <a href=https://arxiv.org/pdf/2011.03981.pdf>arxiv</a> <a href=https://github.com/ZJU-FAST-Lab/OPNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2021_IROS,
    author = "Wang, Lizi and Ye, Hongkai and Wang, Qianhao and Gao, Yuman and Xu, Chao and Gao, Fei",
    booktitle = "IROS",
    title = "Learning-based {3D} Occupancy Prediction for Autonomous Navigation in Occluded Environments",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wirthmüller et al., "Predicting the Time Until a Vehicle Changes the Lane Using LSTM-Based Recurrent Neural Networks", RAL, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9353203>paper</a> <a href=https://arxiv.org/pdf/2102.01431.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Wirthmuller_2021_RAL,
    author = "Wirthmüller, Florian and Klimke, Marvin and Schlechtriemen, Julian and Hipp, Jochen and Reichert, Manfred",
    journal = "RAL",
    title = "Predicting the Time Until a Vehicle Changes the Lane Using {LSTM-Based} Recurrent Neural Networks",
    year = "2021",
    volume = "6",
    number = "2",
    pages = "2357-2364"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Kataoka et al., "Joint Pedestrian Detection and Risk-level Prediction with Motion-Representation-by-Detection", ICRA, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/9197399>paper</a></summary>
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
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kataoka_2020_ICRA,
    author = "Kataoka, H. and Suzuki, T. and Nakashima, K. and Satoh, Y. and Aoki, Y.",
    booktitle = "ICRA",
    title = "Joint Pedestrian Detection and Risk-level Prediction with Motion-Representation-by-Detection",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Wang et al., "Group Split and Merge Prediction With 3D Convolutional Networks", RAL, 2020.</em></strong> <a href=https://ieeexplore.ieee.org/document/8972421>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Wang_2020_RAL,
    author = "Wang, A. and Steinfeld, A.",
    journal = "RAL",
    title = "Group Split and Merge Prediction With 3D Convolutional Networks",
    year = "2020",
    volume = "5",
    number = "2",
    pages = "1923-1930"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Kim et al., "Deep-Hurricane-Tracker: Tracking And Forecasting Extreme Climate Events", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8658402>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kim_2019_WACV,
    author = "Kim, S. and Kim, H. and Lee, J. and Yoon, S. and Kahou, S. E. and Kashinath, K. and Prabhat, M.",
    booktitle = "WACV",
    title = "Deep-Hurricane-Tracker: Tracking And Forecasting Extreme Climate Events",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Sur et al., "Robots That Anticipate Pain: Anticipating Physical Perturbations From Visual Cues Through Deep Predictive Models", IROS, 2017.</em></strong> <a href=https://ieeexplore.ieee.org/document/8206442>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mcc">MCC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sur_2017_IROS,
    author = "Sur, I. and Ben Amor, H.",
    booktitle = "IROS",
    title = "Robots That Anticipate Pain: Anticipating Physical Perturbations From Visual Cues Through Deep Predictive Models",
    year = "2017"
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

</ul><ul><a name=refclipscore></a>
<details close>
<summary><em><l style="font-size:20px"><strong>RefCLIPScore</strong><small> [13]</small></l>
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

</ul><ul><a name=ri></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Rand Index (RI)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Luc et al., "Predicting Future Instance Segmentation By Forecasting Convolutional Features", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Pauline_Luc_Predicting_Future_Instance_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1803.11496.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#voi">VoI</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#gce">GCE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#ri">RI</a></li>
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
</ul>
</details>

</ul><ul><a name=rmse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Root Mean Square Error (RMSE)</strong><small> [7]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Kalble et al., "Accurate Training Data for Occupancy Map Prediction in Automated Driving Using Evidence Theory", CVPR, 2024.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Kalble_Accurate_Training_Data_for_Occupancy_Map_Prediction_in_Automated_Driving_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2405.10575>arxiv</a> <a href=https://github.com/boschresearch/evidential-occupancy>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#womd">WOMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kalble_Accurate_2024_CVPR,
    author = "Kalble, Jonas and Wirges, Sascha and Tatarchenko, Maxim and Ilg, Eddy",
    title = "Accurate Training Data for Occupancy Map Prediction in Automated Driving Using Evidence Theory",
    booktitle = "CVPR",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
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
<summary><strong><em>Li et al., "SolarCube: An Integrative Benchmark Dataset Harnessing Satellite and In-situ Observations for Large-scale Solar Energy Forecasting", NeurIPS, 2024.</em></strong> <a href=https://openreview.net/pdf?id=WffhOhYvZ0>paper</a> <a href=https://github.com/Ruohan-Li/SolarCube>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#solarcube">SolarCube</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#rmse">RMSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#r-squared">R-squared</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#fs">FS</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mbd">MBD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Li_Solarcube_2024_NeurIPS,
    author = "Li, Ruohan and Xie, Yiqun and Jia, Xiaowei and Wang, Dongdong and Li, Yanhua and Zhang, Yingxue and Wang, Zhihao and Li, Zhili",
    title = "SolarCube: An Integrative Benchmark Dataset Harnessing Satellite and In-situ Observations for Large-scale Solar Energy Forecasting",
    booktitle = "NeurIPS",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
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
<details close>
<summary><strong><em>Yu et al., "Congestion Prediction for Large Fleets of Mobile Robots", ICRA, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10161554>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yu_2023_ICRA,
    author = "Yu, Ge and Wolf, Michael T",
    title = "Congestion Prediction for Large Fleets of Mobile Robots",
    booktitle = "ICRA",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Chu et al., "Visual Weather Temperature Prediction", WACV, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8354136>paper</a> <a href=https://arxiv.org/pdf/1801.08267.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#amos">AMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#rmse">RMSE</a></li>
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
<details close>
<summary><strong><em>Cunningham et al., "Improving Slip Prediction on Mars using Thermal Inertia Measurements", RSS, 2017.</em></strong> <a href=http://www.roboticsproceedings.org/rss13/p38.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cunningham_2017_RSS,
    author = "Cunningham, Christopher and Nesnas, Issa A and Whittaker, William L",
    title = "Improving Slip Prediction on Mars using Thermal Inertia Measurements",
    booktitle = "RSS",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=roc></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Receiver Operator Characteristic (ROC)</strong><small> [12]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Schreiber et al., "Long-Term Occupancy Grid Prediction Using Recurrent Neural Networks", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8793582>paper</a> <a href=https://arxiv.org/pdf/1809.03782.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#roc">ROC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Schreiber_2019_ICRA,
    author = "Schreiber, M. and Hoermann, S. and Dietmayer, K.",
    booktitle = "ICRA",
    title = "Long-Term Occupancy Grid Prediction Using Recurrent Neural Networks",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Hoermann et al., "Dynamic Occupancy Grid Prediction For Urban Autonomous Driving: A Deep Learning Approach With Fully Automatic Labeling", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8460874>paper</a> <a href=https://arxiv.org/pdf/1705.08781.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#roc">ROC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hoermann_2018_ICRA,
    author = "Hoermann, S. and Bach, M. and Dietmayer, K.",
    booktitle = "ICRA",
    title = "Dynamic Occupancy Grid Prediction For Urban Autonomous Driving: A Deep Learning Approach With Fully Automatic Labeling",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=rov></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Retention of Vehicles (RoV)</strong><small> [13]</small></l>
</em></summary>
<ul>
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
</ul>
</details>

</ul><ul><a name=rq></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Recognition Quality (RQ)</strong><small> [13]</small></l>
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
</ul>
</details>

</ul><ul><a name=rs></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Repetition Score (RS)</strong><small> [13]</small></l>
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
</ul>
</details>

</ul><ul><a name=rt></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Run Time (RT)</strong><small> [12]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Agro et al., "Implicit Occupancy Flow Fields for Perception and Prediction in Self-Driving", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Agro_Implicit_Occupancy_Flow_Fields_for_Perception_and_Prediction_in_Self-Driving_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.01471.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#epe">EPE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#map">mAP</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#rt">RT</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#soft-iou">Soft-IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#ece">ECE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Agro_2023_CVPR,
    author = "Agro, Ben and Sykora, Quinlan and Casas, Sergio and Urtasun, Raquel",
    title = "Implicit Occupancy Flow Fields for Perception and Prediction in Self-Driving",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Doellinger et al., "Predicting Occupancy Distributions of Walking Humans With Convolutional Neural Networks", RAL, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8278198>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#rt">RT</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#kld">KLD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Doellinger_2018_RAL,
    author = "Doellinger, J. and Spies, M. and Burgard, W.",
    journal = "RAL",
    title = "Predicting Occupancy Distributions of Walking Humans With Convolutional Neural Networks",
    year = "2018",
    volume = "3",
    number = "3",
    pages = "1522-1528"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=run_time></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Run Time</strong><small> [11]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Mohajerin et al., "Multi-Step Prediction Of Occupancy Grid Maps With Recurrent Neural Networks", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Mohajerin_Multi-Step_Prediction_of_Occupancy_Grid_Maps_With_Recurrent_Neural_Networks_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.09395.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#run_time">Run Time</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#tp">TP</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#tn">TN</a></li>
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
<summary><strong><em>Katyal et al., "Uncertainty-Aware Occupancy Map Prediction Using Generative Networks For Robot Navigation", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8793500>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#run_time">Run Time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Katyal_2019_ICRA,
    author = "Katyal, K. and Popek, K. and Paxton, C. and Burlina, P. and Hager, G. D.",
    booktitle = "ICRA",
    title = "Uncertainty-Aware Occupancy Map Prediction Using Generative Networks For Robot Navigation",
    year = "2019"
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

</ul><ul><a name=sile></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Scale-Invariant Logarithmic Error (SILE)</strong><small> [13]</small></l>
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

</ul><ul><a name=similarity></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Similarity</strong><small> [13]</small></l>
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
</ul>
</details>

</ul><ul><a name=soft-iou></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Soft-IoU</strong><small> [12]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Agro et al., "Implicit Occupancy Flow Fields for Perception and Prediction in Self-Driving", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Agro_Implicit_Occupancy_Flow_Fields_for_Perception_and_Prediction_in_Self-Driving_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.01471.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#epe">EPE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#map">mAP</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#rt">RT</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#soft-iou">Soft-IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#ece">ECE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Agro_2023_CVPR,
    author = "Agro, Ben and Sykora, Quinlan and Casas, Sergio and Urtasun, Raquel",
    title = "Implicit Occupancy Flow Fields for Perception and Prediction in Self-Driving",
    booktitle = "CVPR",
    year = "2023"
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
</ul>
</details>

</ul><ul><a name=spice></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Semantic Propositional Image Caption Evaluation (SPICE)</strong><small> [13]</small></l>
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

</ul><ul><a name=sq></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Segmentation Quality (SQ)</strong><small> [12]</small></l>
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
</ul>
</details>

</ul><ul><a name=src></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Spearman’s Ranking Correlation (SRC)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Wang et al., "Retweet Wars: Tweet Popularity Prediction Via Dynamic Multimodal Regression", WACV, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8354308>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#mbi-1m">MBI-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mape">MAPE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#src">SRC</a></li>
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
</ul>
</details>

</ul><ul><a name=ssim></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Structural SIMilarity (SSIM)</strong><small> [10]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Yoon et al., "Probabilistic Weather Forecasting with Deterministic Guidance-Based Diffusion Model", ECCV, 2024.</em></strong> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04326.pdf>paper</a> <a href=https://github.com/DongGeun-Yoon/DGDM>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#weatherbench">WeatherBench</a></li>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#pnw-typhoon">PNW-Typhoon</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#fvd">FVD</a></li>
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
<summary><strong><em>Mohajerin et al., "Multi-Step Prediction Of Occupancy Grid Maps With Recurrent Neural Networks", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Mohajerin_Multi-Step_Prediction_of_Occupancy_Grid_Maps_With_Recurrent_Neural_Networks_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.09395.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#run_time">Run Time</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#tp">TP</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#tn">TN</a></li>
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
<summary><strong><em>Katyal et al., "Uncertainty-Aware Occupancy Map Prediction Using Generative Networks For Robot Navigation", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8793500>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#run_time">Run Time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Katyal_2019_ICRA,
    author = "Katyal, K. and Popek, K. and Paxton, C. and Burlina, P. and Hager, G. D.",
    booktitle = "ICRA",
    title = "Uncertainty-Aware Occupancy Map Prediction Using Generative Networks For Robot Navigation",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Luc et al., "Predicting Deeper Into The Future Of Semantic Segmentation", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Luc_Predicting_Deeper_Into_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1703.07684.pdf>arxiv</a> <a href=https://github.com/facebookresearch/SegmPred>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#psnr">PSNR</a></li>
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
</ul>
</details>

</ul><ul><a name=time></a>
<details close>
<summary><em><l style="font-size:20px"><strong>time</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Li et al., "TTC4MCP: Monocular Collision Prediction Based on Self-Supervised TTC Estimation", IROS, 2023.</em></strong> <a href=https://ieeexplore.ieee.org/document/10341966>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#time">time</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@INPROCEEDINGS{Li_2023_IROS,
    author = "Li, Changlin and Qian, Yeqiang and Sun, Cong and Yan, Weihao and Wang, Chunxiang and Yang, Ming",
    booktitle = "IROS",
    title = "TTC4MCP: Monocular Collision Prediction Based on Self-Supervised TTC Estimation",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul><ul><a name=tn></a>
<details close>
<summary><em><l style="font-size:20px"><strong>True Negative (TN)</strong><small> [12]</small></l>
</em></summary>
<ul>
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
<summary><strong><em>Mohajerin et al., "Multi-Step Prediction Of Occupancy Grid Maps With Recurrent Neural Networks", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Mohajerin_Multi-Step_Prediction_of_Occupancy_Grid_Maps_With_Recurrent_Neural_Networks_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.09395.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#run_time">Run Time</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#tp">TP</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#tn">TN</a></li>
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
</ul>
</details>

</ul><ul><a name=tp></a>
<details close>
<summary><em><l style="font-size:20px"><strong>True Positive (TP)</strong><small> [12]</small></l>
</em></summary>
<ul>
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
<summary><strong><em>Mohajerin et al., "Multi-Step Prediction Of Occupancy Grid Maps With Recurrent Neural Networks", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Mohajerin_Multi-Step_Prediction_of_Occupancy_Grid_Maps_With_Recurrent_Neural_Networks_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.09395.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#run_time">Run Time</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#tp">TP</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#tn">TN</a></li>
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
</ul>
</details>

</ul><ul><a name=tpr></a>
<details close>
<summary><em><l style="font-size:20px"><strong>True Positive Rate (TPR)</strong><small> [13]</small></l>
</em></summary>
<ul>
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
</ul>
</details>

</ul><ul><a name=tss></a>
<details close>
<summary><em><l style="font-size:20px"><strong>True Skill Statistics (TSS)</strong><small> [13]</small></l>
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

</ul><ul><a name=ttc></a>
<details close>
<summary><em><l style="font-size:20px"><strong>TTC</strong><small> [13]</small></l>
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
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#ttc">TTC</a></li>
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
</ul>
</details>

</ul><ul><a name=voi></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Variation of Information (VoI)</strong><small> [13]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Luc et al., "Predicting Future Instance Segmentation By Forecasting Convolutional Features", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Pauline_Luc_Predicting_Future_Instance_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1803.11496.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#voi">VoI</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#gce">GCE</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#ri">RI</a></li>
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
</ul>
</details>

</ul><ul><a name=vpq></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Video Panoptic Quality (VPQ)</strong><small> [9]</small></l>
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
<summary><strong><em>Wang et al., "Drones Help Drones: A Collaborative Framework for Multi-Drone Object Trajectory Prediction and Beyond", NeurIPS, 2024.</em></strong> <a href=https://openreview.net/pdf?id=20QgErW5zH>paper</a> <a href=https://arxiv.org/pdf/2405.14674>arxiv</a> <a href=https://github.com/WangzcBruce/DHD>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#vpq">VPQ</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Wang_Drones_2024_NeurIPS,
    author = "Wang, Zhechao and Cheng, Peirui and Chen, Minxing and Tian, Pengju and Wang, Zhirui and Li, Xinming and Yang, Xue and Sun, Xian",
    title = "Drones Help Drones: A Collaborative Framework for Multi-Drone Object Trajectory Prediction and Beyond",
    booktitle = "NeurIPS",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Akan et al., "StretchBEV: Stretching Future Instance Prediction Spatially and Temporally", ECCV, 2022.</em></strong> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136980436.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.13641.pdf>arxiv</a> <a href=https://kuis-ai.github.io/stretchbev/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/other/other_alphabetical/other_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/other/other_alphabetical/other_j-z_metrics.md#vpq">VPQ</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Akan_2022_ECCV,
    author = "Akan, Adil Kaan and Guney, Fatma",
    title = "{StretchBEV}: Stretching Future Instance Prediction Spatially and Temporally",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

</ul>