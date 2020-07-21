---
<a href=README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=datasets/datasets.md#top><l style="font-size:30px">Datasets</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Metrics</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
<a name=top></a>
# Metrics for vision-based prediction
 <img src="./images/video_metrics.png" alt="video metrics" width="250"/><img src="./images/action_metrics.png" alt="action metrics" width="250"/><img src="./images/trajectory_metrics.png" alt="trajectory metrics" width="280"/><img src="./images/motion_metrics.png" alt="motion metrics" width="210"/><br/>
In this page you can find the *metrics* used in vision-based prediction applications.The metrics are **sorted** based on **popularity**, (i.e how often used in prediction papers) and categorized into 5 groups:
* [Video](#metrics_video)
* [Action](#metrics_action)
* [Trajectory](#metrics_trajectory)
* [Motion](#metrics_motion)
* [Other](#metrics_other)<br/>

By clicking on each metric you can see the list of papers that used that metric. Each paper also can be expanded to display its information.
<a name=metrics_video></a>
<h2 style="color:#d52b0f">  Video Prediction </h2><a href=#top>&uarr; top</a>
<ul><a name=psnr></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Peak Signal-to-Noise Ratio (PSNR)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle Gan", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#chuk_avenue">CHUK Avenue</a></li>
<li><a href="datasets/year_datasets.md#shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Gao et al., "Disentangling Propagation And Generation For Video Prediction", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Gao_Disentangling_Propagation_and_Generation_for_Video_Prediction_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Ho et al., "Sme-Net: Sparse Motion Estimation For Parametric Video Prediction Through Reinforcement Learning", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ho_SME-Net_Sparse_Motion_Estimation_for_Parametric_Video_Prediction_Through_Reinforcement_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#yuv">YUV</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Lee et al., "Mutual Suppression Network For Video Prediction Using Disentangled Features", BMVC, 2019.</em></strong> <a href=https://bmvc2019.org/wp-content/uploads/papers/0336-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.04810.pdf>arxiv</a> <a href=https://github.com/aras62/SF-GRU>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="datasets/year_datasets.md#kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Wang et al., "Order Matters: Shuffling Sequence Generation For Video Prediction", BMVC, 2019.</em></strong> <a href=https://bmvc2019.org/wp-content/uploads/papers/1023-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1907.08845.pdf>arxiv</a> <a href=https://github.com/andrewjywang/SEENet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="datasets/year_datasets.md#msr">MSR</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Ho et al., "Deep Reinforcement Learning For Video Prediction", ICIP, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8803825>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#yuv">YUV</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Tang et al., "Pose Guided Global And Local Gan For Appearance Preserving Human Video Prediction", ICIP, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8803792>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Zhang et al., "Looking-Ahead: Neural Future Video Frame Prediction", ICIP, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8803151>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Xu et al., "Structure Preserving Video Prediction", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers_backup/Xu_Structure_Preserving_Video_CVPR_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Byeon et al., "Contextvp: Fully Context-Aware Video Prediction", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Wonmin_Byeon_ContextVP_Fully_Context-Aware_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Cai et al., "Deep Video Generation, Prediction And Completion Of Human Action Sequences", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Chunyan_Bai_Deep_Video_Generation_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1711.08682.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Liu et al., "Dyan: A Dynamical Atoms-Based Network For Video Prediction", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Wenqian_Liu_DYAN_A_Dynamical_ECCV_2018_paper.pdf)>paper</a> <a href=https://github.com/liuem607/DYAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Oliu et al., "Folded Recurrent Neural Networks For Future Video Prediction", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Marc_Oliu_Folded_Recurrent_Neural_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1712.00311.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="datasets/year_datasets.md#kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Reda et al., "Sdc-Net: Video Prediction Using Spatially-Displaced Convolution", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Fitsum_Reda_SDC-Net_Video_prediction_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1811.00684.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#youtube-8m">Youtube-8M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
<li><a href="metrics.md#l1">L1</a></li>
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
<summary><strong><em>Zhao et al., "Learning To Forecast And Refine Residual Motion For Image-To-Video Generation", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Long_Zhao_Learning_to_Forecast_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1807.09951.pdf>arxiv</a> <a href=https://github.com/garyzhao/FRGAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="datasets/year_datasets.md#mug">MUG</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Xu et al., "Video Prediction Via Selective Sampling", NeurIPS, 2018.</em></strong> <a href=https://papers.nips.cc/paper/7442-video-prediction-via-selective-sampling.pdf>paper</a> <a href=https://github.com/xjwxjw/VPSS>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Bhattacharjee et al., "Predicting Video Frames Using Feature Based Locally Guided Objectives", ACCV, 2019.</em></strong> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20870-7_42>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Ying et al., "Better Guider Predicts Future Better: Difference Guided Generative Adversarial Networks", ACCV, 2018.</em></strong> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20876-9_18>paper</a> <a href=https://arxiv.org/pdf/1901.01649.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Jin et al., "Varnet: Exploring Variations For Unsupervised Video Prediction", IROS, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8594264>paper</a> <a href=https://github.com/jinbeibei/VarNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Lu et al., "Flexible Spatio-Temporal Networks For Video Prediction", CVPR, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lu_Flexible_Spatio-Temporal_Networks_CVPR_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
<li><a href="datasets/year_datasets.md#visor">ViSOR</a></li>
<li><a href="datasets/year_datasets.md#prost">PROST</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
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
<summary><strong><em>Liang et al., "Dual Motion Gan For Future-Flow Embedded Video Prediction", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Liang_Dual_Motion_GAN_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00284.pdf>arxiv</a> <a href=https://github.com/gurkirt/realtime-action-detection>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Bhattacharjee et al., "Temporal Coherency Based Criteria For Predicting Video Frames Using Deep Multi-Stage Generative Adversarial Networks", NeurIPS, 2017.</em></strong> <a href=https://papers.nips.cc/paper/7014-temporal-coherency-based-criteria-for-predicting-video-frames-using-deep-multi-stage-generative-adversarial-networks.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Wang et al., "Predrnn: Recurrent Neural Networks For Predictive Learning Using Spatiotemporal Lstms", NeurIPS, 2017.</em></strong> <a href=https://papers.nips.cc/paper/6689-predrnn-recurrent-neural-networks-for-predictive-learning-using-spatiotemporal-lstms.pdf>paper</a> <a href=https://github.com/ujjax/pred-rnn>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="datasets/year_datasets.md#kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<details close>
<summary><strong><em>Villegas et al., "Learning To Generate Long-Term Future Via Hierarchical Prediction", ICML, 2017.</em></strong> <a href=http://proceedings.mlr.press/v70/villegas17a.html>paper</a> <a href=https://arxiv.org/pdf/1704.05831.pdf>arxiv</a> <a href=https://github.com/rubenvillegas/icml2017hierchvid>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#human">Human</a></li>
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
<summary><strong><em>Finn et al., "Unsupervised Learning For Physical Interaction Through Video Prediction", NeurIPS, 2016.</em></strong> <a href=https://papers.nips.cc/paper/6161-unsupervised-learning-for-physical-interaction-through-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1605.07157.pdf>arxiv</a> <a href=https://github.com/tensorflow/models/tree/master/research/video_prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
</ul>
</details>

<a name=ssim></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Structural SIMilarity (SSIM)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle Gan", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#chuk_avenue">CHUK Avenue</a></li>
<li><a href="datasets/year_datasets.md#shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Castrejon et al., "Improved Conditional Vrnns For Video Prediction", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Castrejon_Improved_Conditional_VRNNs_for_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.12165.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#lpips">LPIPS</a></li>
<li><a href="metrics.md#fvd">FVD</a></li>
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
<summary><strong><em>Gao et al., "Disentangling Propagation And Generation For Video Prediction", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Gao_Disentangling_Propagation_and_Generation_for_Video_Prediction_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Ho et al., "Sme-Net: Sparse Motion Estimation For Parametric Video Prediction Through Reinforcement Learning", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ho_SME-Net_Sparse_Motion_Estimation_for_Parametric_Video_Prediction_Through_Reinforcement_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#yuv">YUV</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Lee et al., "Mutual Suppression Network For Video Prediction Using Disentangled Features", BMVC, 2019.</em></strong> <a href=https://bmvc2019.org/wp-content/uploads/papers/0336-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.04810.pdf>arxiv</a> <a href=https://github.com/aras62/SF-GRU>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="datasets/year_datasets.md#kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Wang et al., "Order Matters: Shuffling Sequence Generation For Video Prediction", BMVC, 2019.</em></strong> <a href=https://bmvc2019.org/wp-content/uploads/papers/1023-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1907.08845.pdf>arxiv</a> <a href=https://github.com/andrewjywang/SEENet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="datasets/year_datasets.md#msr">MSR</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Ho et al., "Deep Reinforcement Learning For Video Prediction", ICIP, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8803825>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#yuv">YUV</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Tang et al., "Pose Guided Global And Local Gan For Appearance Preserving Human Video Prediction", ICIP, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8803792>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Zhang et al., "Looking-Ahead: Neural Future Video Frame Prediction", ICIP, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8803151>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Xu et al., "Structure Preserving Video Prediction", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers_backup/Xu_Structure_Preserving_Video_CVPR_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Byeon et al., "Contextvp: Fully Context-Aware Video Prediction", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Wonmin_Byeon_ContextVP_Fully_Context-Aware_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Cai et al., "Deep Video Generation, Prediction And Completion Of Human Action Sequences", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Chunyan_Bai_Deep_Video_Generation_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1711.08682.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Liu et al., "Dyan: A Dynamical Atoms-Based Network For Video Prediction", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Wenqian_Liu_DYAN_A_Dynamical_ECCV_2018_paper.pdf)>paper</a> <a href=https://github.com/liuem607/DYAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Oliu et al., "Folded Recurrent Neural Networks For Future Video Prediction", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Marc_Oliu_Folded_Recurrent_Neural_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1712.00311.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="datasets/year_datasets.md#kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Reda et al., "Sdc-Net: Video Prediction Using Spatially-Displaced Convolution", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Fitsum_Reda_SDC-Net_Video_prediction_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1811.00684.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#youtube-8m">Youtube-8M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
<li><a href="metrics.md#l1">L1</a></li>
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
<summary><strong><em>Xu et al., "Video Prediction Via Selective Sampling", NeurIPS, 2018.</em></strong> <a href=https://papers.nips.cc/paper/7442-video-prediction-via-selective-sampling.pdf>paper</a> <a href=https://github.com/xjwxjw/VPSS>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Bhattacharjee et al., "Predicting Video Frames Using Feature Based Locally Guided Objectives", ACCV, 2019.</em></strong> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20870-7_42>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Ying et al., "Better Guider Predicts Future Better: Difference Guided Generative Adversarial Networks", ACCV, 2018.</em></strong> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20876-9_18>paper</a> <a href=https://arxiv.org/pdf/1901.01649.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Jin et al., "Varnet: Exploring Variations For Unsupervised Video Prediction", IROS, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8594264>paper</a> <a href=https://github.com/jinbeibei/VarNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Liang et al., "Dual Motion Gan For Future-Flow Embedded Video Prediction", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Liang_Dual_Motion_GAN_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00284.pdf>arxiv</a> <a href=https://github.com/gurkirt/realtime-action-detection>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Bhattacharjee et al., "Temporal Coherency Based Criteria For Predicting Video Frames Using Deep Multi-Stage Generative Adversarial Networks", NeurIPS, 2017.</em></strong> <a href=https://papers.nips.cc/paper/7014-temporal-coherency-based-criteria-for-predicting-video-frames-using-deep-multi-stage-generative-adversarial-networks.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
<summary><strong><em>Wang et al., "Predrnn: Recurrent Neural Networks For Predictive Learning Using Spatiotemporal Lstms", NeurIPS, 2017.</em></strong> <a href=https://papers.nips.cc/paper/6689-predrnn-recurrent-neural-networks-for-predictive-learning-using-spatiotemporal-lstms.pdf>paper</a> <a href=https://github.com/ujjax/pred-rnn>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="datasets/year_datasets.md#kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<details close>
<summary><strong><em>Finn et al., "Unsupervised Learning For Physical Interaction Through Video Prediction", NeurIPS, 2016.</em></strong> <a href=https://papers.nips.cc/paper/6161-unsupervised-learning-for-physical-interaction-through-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1605.07157.pdf>arxiv</a> <a href=https://github.com/tensorflow/models/tree/master/research/video_prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
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
</ul>
</details>

<a name=mse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Square Error (MSE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle Gan", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#chuk_avenue">CHUK Avenue</a></li>
<li><a href="datasets/year_datasets.md#shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Ho et al., "Sme-Net: Sparse Motion Estimation For Parametric Video Prediction Through Reinforcement Learning", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ho_SME-Net_Sparse_Motion_Estimation_for_Parametric_Video_Prediction_Through_Reinforcement_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#yuv">YUV</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Ho et al., "Deep Reinforcement Learning For Video Prediction", ICIP, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8803825>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#yuv">YUV</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Liu et al., "Dyan: A Dynamical Atoms-Based Network For Video Prediction", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Wenqian_Liu_DYAN_A_Dynamical_ECCV_2018_paper.pdf)>paper</a> <a href=https://github.com/liuem607/DYAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Oliu et al., "Folded Recurrent Neural Networks For Future Video Prediction", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Marc_Oliu_Folded_Recurrent_Neural_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1712.00311.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="datasets/year_datasets.md#kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Reda et al., "Sdc-Net: Video Prediction Using Spatially-Displaced Convolution", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Fitsum_Reda_SDC-Net_Video_prediction_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1811.00684.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#youtube-8m">Youtube-8M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
<li><a href="metrics.md#l1">L1</a></li>
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
<summary><strong><em>Zhao et al., "Learning To Forecast And Refine Residual Motion For Image-To-Video Generation", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Long_Zhao_Learning_to_Forecast_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1807.09951.pdf>arxiv</a> <a href=https://github.com/garyzhao/FRGAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="datasets/year_datasets.md#mug">MUG</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Hsieh et al., "Learning To Decompose And Disentangle Representations For Video Prediction", NeurIPS, 2018.</em></strong> <a href=https://papers.nips.cc/paper/7333-learning-to-decompose-and-disentangle-representations-for-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1806.04166.pdf>arxiv</a> <a href=https://github.com/jthsieh/DDPAE-video-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="datasets/year_datasets.md#bouncing_ball">Bouncing Ball</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mse">MSE</a></li>
<li><a href="metrics.md#bce">BCE</a></li>
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
<summary><strong><em>Ying et al., "Better Guider Predicts Future Better: Difference Guided Generative Adversarial Networks", ACCV, 2018.</em></strong> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20876-9_18>paper</a> <a href=https://arxiv.org/pdf/1901.01649.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Ji et al., "Dynamic Visual Sequence Prediction With Motion Flow Networks", WACV, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8354223>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Liang et al., "Dual Motion Gan For Future-Flow Embedded Video Prediction", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Liang_Dual_Motion_GAN_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00284.pdf>arxiv</a> <a href=https://github.com/gurkirt/realtime-action-detection>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<summary><strong><em>Wang et al., "Predrnn: Recurrent Neural Networks For Predictive Learning Using Spatiotemporal Lstms", NeurIPS, 2017.</em></strong> <a href=https://papers.nips.cc/paper/6689-predrnn-recurrent-neural-networks-for-predictive-learning-using-spatiotemporal-lstms.pdf>paper</a> <a href=https://github.com/ujjax/pred-rnn>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="datasets/year_datasets.md#kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
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
<details close>
<summary><strong><em>Oh et al., "Action-Conditional Video Prediction Using Deep Networks In Atari Games", NeurIPS, 2015.</em></strong> <a href=https://papers.nips.cc/paper/5859-action-conditional-video-prediction-using-deep-networks-in-atari-games.pdf>paper</a> <a href=https://arxiv.org/pdf/1507.08750.pdf>arxiv</a> <a href=https://github.com/junhyukoh/nips2015-action-conditional-video-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#atari">Atari</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mse">MSE</a></li>
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
</ul>
</details>

<a name=lpips></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Learned Perceptual Image Patch Similarity (LPIPS)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Castrejon et al., "Improved Conditional Vrnns For Video Prediction", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Castrejon_Improved_Conditional_VRNNs_for_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.12165.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#lpips">LPIPS</a></li>
<li><a href="metrics.md#fvd">FVD</a></li>
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
<summary><strong><em>Ye et al., "Compositional Video Prediction", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ye_Compositional_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.08522.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="datasets/year_datasets.md#shapestack">ShapeStack</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#lpips">LPIPS</a></li>
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
<summary><strong><em>Jung et al., "Goal-Directed Behavior Under Variational Predictive Coding: Dynamic Organization Of Visual Attention And Working Memory", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8968597>paper</a> <a href=https://arxiv.org/pdf/1903.04932.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#lpips">LPIPS</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jung_2019_IROS,
    author = "Jung, Minju and Matsumoto, Takazumi and Tani, Jun",
    booktitle = "IROS",
    title = "Goal-Directed Behavior Under Variational Predictive Coding: Dynamic Organization Of Visual Attention And Working Memory",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Li et al., "Flow-Grounded Spatial-Temporal Video Prediction From Still Images", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yin_Li_In_the_Eye_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.00626.pdf>arxiv</a> <a href=https://github.com/Yijunmaverick/FlowGrounded-VideoPrediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#human">Human</a></li>
<li><a href="metrics.md#lpips">LPIPS</a></li>
<li><a href="metrics.md#rmse">RMSE</a></li>
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
</ul>
</details>

<a name=human></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Human Judgement (Human)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Li et al., "Flow-Grounded Spatial-Temporal Video Prediction From Still Images", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yin_Li_In_the_Eye_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.00626.pdf>arxiv</a> <a href=https://github.com/Yijunmaverick/FlowGrounded-VideoPrediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#human">Human</a></li>
<li><a href="metrics.md#lpips">LPIPS</a></li>
<li><a href="metrics.md#rmse">RMSE</a></li>
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
<summary><strong><em>Wichers et al., "Hierarchical Long-Term Video Prediction Without Supervision", ICML, 2018.</em></strong> <a href=http://proceedings.mlr.press/v80/wichers18a.html>paper</a> <a href=https://arxiv.org/pdf/1806.04768.pdf>arxiv</a> <a href=https://bit.ly/2HqiHqx>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#human">Human</a></li>
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
<summary><strong><em>Zeng et al., "Visual Forecasting By Imitating Dynamics In Natural Sequences", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/supplemental/Zeng_Visual_Forecasting_by_ICCV_2017_supplemental.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.05827.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#mmnist">MMNIST</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#human">Human</a></li>
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
<summary><strong><em>Villegas et al., "Learning To Generate Long-Term Future Via Hierarchical Prediction", ICML, 2017.</em></strong> <a href=http://proceedings.mlr.press/v70/villegas17a.html>paper</a> <a href=https://arxiv.org/pdf/1704.05831.pdf>arxiv</a> <a href=https://github.com/rubenvillegas/icml2017hierchvid>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#human">Human</a></li>
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
</ul>
</details>

<a name=fvd></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Frechet Video Distanc (FVD)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Castrejon et al., "Improved Conditional Vrnns For Video Prediction", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Castrejon_Improved_Conditional_VRNNs_for_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.12165.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#lpips">LPIPS</a></li>
<li><a href="metrics.md#fvd">FVD</a></li>
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
<summary><strong><em>Kim et al., "Unsupervised Keypoint Learning For Guiding Class-Conditional Video Prediction", NeurIPS, 2019.</em></strong> <a href=https://papers.nips.cc/paper/8637-unsupervised-keypoint-learning-for-guiding-class-conditional-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.02027.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="datasets/year_datasets.md#uva-nemo">UvA-NEMO</a></li>
<li><a href="datasets/year_datasets.md#mgif">MGIF</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#fvd">FVD</a></li>
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
</ul>
</details>

<a name=l1></a>
<details close>
<summary><em><l style="font-size:20px"><strong>L1</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Gujjar et al., "Classifying Pedestrian Actions In Advance Using Predicted Video Of Urban Driving Scenes", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8794278>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#l1">L1</a></li>
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
<summary><strong><em>Reda et al., "Sdc-Net: Video Prediction Using Spatially-Displaced Convolution", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Fitsum_Reda_SDC-Net_Video_prediction_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1811.00684.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#youtube-8m">Youtube-8M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psnr">PSNR</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
<li><a href="metrics.md#l1">L1</a></li>
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
</ul>
</details>

<a name=bce></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Binary Cross Entropy (BCE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Hsieh et al., "Learning To Decompose And Disentangle Representations For Video Prediction", NeurIPS, 2018.</em></strong> <a href=https://papers.nips.cc/paper/7333-learning-to-decompose-and-disentangle-representations-for-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1806.04166.pdf>arxiv</a> <a href=https://github.com/jthsieh/DDPAE-video-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="datasets/year_datasets.md#bouncing_ball">Bouncing Ball</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mse">MSE</a></li>
<li><a href="metrics.md#bce">BCE</a></li>
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
</ul>
</details>

<a name=is></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Inception Scores (IS)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Walker et al., "The Pose Knows: Video Forecasting By Generating Pose Futures", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Walker_The_Pose_Knows_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.00053.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#is">IS</a></li>
<li><a href="metrics.md#mmd">MMD</a></li>
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
</ul>
</details>

<a name=mmd></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Maximum Mean Discrepancy (MMD)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Walker et al., "The Pose Knows: Video Forecasting By Generating Pose Futures", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Walker_The_Pose_Knows_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.00053.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#is">IS</a></li>
<li><a href="metrics.md#mmd">MMD</a></li>
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
</ul>
</details>

<a name=rmse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Root Mean Square Error (RMSE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Li et al., "Flow-Grounded Spatial-Temporal Video Prediction From Still Images", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yin_Li_In_the_Eye_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.00626.pdf>arxiv</a> <a href=https://github.com/Yijunmaverick/FlowGrounded-VideoPrediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kth">KTH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#human">Human</a></li>
<li><a href="metrics.md#lpips">LPIPS</a></li>
<li><a href="metrics.md#rmse">RMSE</a></li>
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
</ul>
</details>

</ul><a name=metrics_action></a>
<h2 style="color:#2f38e8">  Action Prediction </h2><a href=#top>&uarr; top</a>
<ul><a name=accuracy></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Accuracy</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Joo et al., "Towards Social Artificial Intelligence: Nonverbal Social Signal Prediction In A Triadic Interaction", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Joo_Towards_Social_Artificial_Intelligence_Nonverbal_Social_Signal_Prediction_in_a_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.04158.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Ke et al., "Time-Conditioned Action Anticipation In One Shot", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Ke_Time-Conditioned_Action_Anticipation_in_One_Shot_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets/year_datasets.md#50salad">50Salad</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
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
<summary><strong><em>Wang et al., "Progressive Teacher-Student Learning For Early Action Prediction", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Progressive_Teacher-Student_Learning_for_Early_Action_Prediction_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
<li><a href="datasets/year_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Furnari et al., "What Would You Expect? Anticipating Egocentric Actions With Rolling-Unrolling Lstms And Modality Attention", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Furnari_What_Would_You_Expect_Anticipating_Egocentric_Actions_With_Rolling-Unrolling_LSTMs_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.09035.pdf>arxiv</a> <a href=https://github.com/fpv-iplab/rulstm>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets/year_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
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
<summary><strong><em>Gammulle et al., "Predicting The Future: A Jointly Learnt Model For Action Anticipation", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Gammulle_Predicting_the_Future_A_Jointly_Learnt_Model_for_Action_Anticipation_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.07148.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Zhao et al., "Spatiotemporal Feature Residual Propagation For Action Prediction", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhao_Spatiotemporal_Feature_Residual_Propagation_for_Action_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://github.com/JoeHEZHAO/Spatiotemporal-Residual-Propagation>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#jhmdb">JHMDB</a></li>
<li><a href="datasets/year_datasets.md#bit">BIT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Gammulle et al., "Forecasting Future Action Sequences With Neural Memory Networks", BMVC, 2019.</em></strong> <a href=https://bmvc2019.org/wp-content/uploads/papers/0585-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1909.09278.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#breakfast">Breakfast</a></li>
<li><a href="datasets/year_datasets.md#50salad">50Salad</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Rasouli et al., "Pedestrian Action Anticipation Using Contextual Feature Fusion In Stacked Rnns", BMVC, 2019.</em></strong> <a href=https://bmvc2019.org/wp-content/uploads/papers/0283-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.06582.pdf>arxiv</a> <a href=https://github.com/aras62/SF-GRU>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#pie">PIE</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#auc">AUC</a></li>
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
<summary><strong><em>Gujjar et al., "Classifying Pedestrian Actions In Advance Using Predicted Video Of Urban Driving Scenes", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8794278>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#ap">AP</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
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
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#ttm">TTM</a></li>
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
<summary><strong><em>Luo et al., "Human Intention Inference And On-Line Human Hand Motion Prediction For Human-Robot Collaboration", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8968192>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Wu et al., "Gaze-Based Intention Anticipation Over Driving Manoeuvres In Semi-Autonomous Vehicles", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8967779>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#ttm">TTM</a></li>
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
<summary><strong><em>Safaei et al., "Still Image Action Recognition By Predicting Spatial-Temporal Pixel Evolution", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8658386>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#willow_action">Willow Action</a></li>
<li><a href="datasets/year_datasets.md#wider">WIDER</a></li>
<li><a href="datasets/year_datasets.md#stanford-40">Stanford-40</a></li>
<li><a href="datasets/year_datasets.md#bu_action">BU Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#map">mAP</a></li>
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
<summary><strong><em>Alati et al., "Help By Predicting What To Do", ICIP, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8803155>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cad-120">CAD-120</a></li>
<li><a href="datasets/year_datasets.md#mpii_cooking">MPII Cooking</a></li>
<li><a href="datasets/year_datasets.md#breakfast">Breakfast</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
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
<li><a href="datasets/year_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
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
<summary><strong><em>Abu et al., "When Will You Do What? - Anticipating Temporal Occurrences Of Activities", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Abu_Farha_When_Will_You_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.00892.pdf>arxiv</a> <a href=https://github.com/yabufarha/anticipating-activities>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#breakfast">Breakfast</a></li>
<li><a href="datasets/year_datasets.md#50salad">50Salad</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<details close>
<summary><strong><em>Suzuki et al., "Anticipating Traffic Accidents With Adaptive Loss And Large-Scale Incident Db", The CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0494.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.02675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#dad">DAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#map">mAP</a></li>
<li><a href="metrics.md#attc">ATTC</a></li>
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
<summary><strong><em>Yao et al., "Multiple Granularity Group Interaction Prediction", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0721.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#sbuki">SBUKI</a></li>
<li><a href="datasets/year_datasets.md#ca">CA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Liu et al., "Ssnet: Scale Selection Network For Online 3D Action Prediction", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_SSNet_Scale_Selection_CVPR_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#pku-mmd">PKU-MMD</a></li>
<li><a href="datasets/year_datasets.md#oad">OAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<details close>
<summary><strong><em>Chen et al., "Part-Activated Deep Reinforcement Learning For Action Prediction", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Lei_Chen_Part-Activated_Deep_Reinforcement_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="datasets/year_datasets.md#bit">BIT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Shen et al., "Egocentric Activity Prediction Via Event Modulated Attention", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Shen_Egocentric_Activity_Prediction_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#gtea_gaze+">GTEA Gaze+</a></li>
<li><a href="datasets/year_datasets.md#gtea_gaze">GTEA Gaze</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<details close>
<summary><strong><em>Shi et al., "Action Anticipation With Rbf Kernelized Feature Mapping Rnn", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yuge_Shi_Action_Anticipation_with_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.07806.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Aliakbarian et al., "Viena: A Driving Anticipation Dataset", ACCV, 2019.</em></strong> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20887-5_28>paper</a> <a href=https://arxiv.org/pdf/1810.09044.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="datasets/year_datasets.md#viena">VIENA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Bütepage et al., "Anticipating Many Futures: Online Human Motion Prediction And Generation For Human-Robot Interaction", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8460651>paper</a> <a href=https://arxiv.org/pdf/1702.08212.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Scheel et al., "Situation Assessment For Planning Lane Changes: Combining Recurrent Models And Prediction", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8462838/>paper</a> <a href=https://arxiv.org/pdf/1805.06776.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Strickland et al., "Deep Predictive Models For Collision Risk Assessment In Autonomous Driving", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8461160>paper</a> <a href=https://arxiv.org/pdf/1711.10453.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#mcc">MCC</a></li>
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
<details close>
<summary><strong><em>Schydlo et al., "Anticipation In Human-Robot Cooperation: A Recurrent Neural Network Approach For Multiple Action Sequences Prediction", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8460924>paper</a> <a href=https://arxiv.org/pdf/1802.10503.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cad-120">CAD-120</a></li>
<li><a href="datasets/year_datasets.md#acticipate">ACTICIPATE</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#f1">F1</a></li>
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
<summary><strong><em>Cho et al., "A Temporal Sequence Learning For Action Recognition And Prediction", WACV, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8354149>paper</a> <a href=https://arxiv.org/pdf/1906.06813.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#hmdb">HMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Zhong et al., "Unsupervised Learning For Forecasting Action Representations", ICIP, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8451428>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Butepage et al., "Deep Representation Learning For Human Motion Prediction And Classification", CVPR, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Butepage_Deep_Representation_Learning_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1702.07486.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Kong et al., "Deep Sequential Context Networks For Action Prediction", CVPR, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Kong_Deep_Sequential_Context_CVPR_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#bit">BIT</a></li>
<li><a href="datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Su et al., "Predicting Behaviors Of Basketball Players From First Person Videos", CVPR, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Su_Predicting_Behaviors_of_CVPR_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Su_2017_CVPR,
    author = "Su, Shan and Pyo Hong, Jung and Shi, Jianbo and Soo Park, Hyun",
    title = "Predicting Behaviors Of Basketball Players From First Person Videos",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Sadegh et al., "Encouraging Lstms To Anticipate Actions Very Early", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Aliakbarian_Encouraging_LSTMs_to_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Felsen et al., "What Will Happen Next? Forecasting Player Moves In Sports Videos", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Felsen_What_Will_Happen_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Felsen_2017_ICCV,
    author = "Felsen, Panna and Agrawal, Pulkit and Malik, Jitendra",
    title = "What Will Happen Next? Forecasting Player Moves In Sports Videos",
    booktitle = "ICCV",
    year = "2017"
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
<li><a href="datasets/year_datasets.md#mpii_cooking">MPII Cooking</a></li>
<li><a href="datasets/year_datasets.md#virat">VIRAT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#rmse">RMSE</a></li>
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
<summary><strong><em>Rhinehart et al., "First-Person Activity Forecasting With Online Inverse Reinforcement Learning", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Rhinehart_First-Person_Activity_Forecasting_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1612.07796.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rhinehart_2017_ICCV,
    author = "Rhinehart, Nicholas and Kitani, Kris M.",
    title = "First-Person Activity Forecasting With Online Inverse Reinforcement Learning",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Singh et al., "Online Real-Time Multiple Spatiotemporal Action Localisation And Prediction", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Singh_Online_Real-Time_Multiple_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1611.08563.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#map">mAP</a></li>
<li><a href="metrics.md#auc">AUC</a></li>
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
<summary><strong><em>Zeng et al., "Visual Forecasting By Imitating Dynamics In Natural Sequences", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Zeng_Visual_Forecasting_by_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.05827.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Vondrick et al., "Anticipating Visual Representations From Unlabeled Video", CVPR, 2016.</em></strong> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Vondrick_Anticipating_Visual_Representations_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1504.08023.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<details close>
<summary><strong><em>Hu et al., "Real-Time Rgb-D Activity Prediction By Soft Regression", ECCV, 2016.</em></strong> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46448-0_17>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
<li><a href="datasets/year_datasets.md#orgbd">ORGBD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<details close>
<summary><strong><em>Kataoka et al., "Recognition Of Transitional Action For Short-Term Action Prediction Using Discriminative Temporal Cnn Feature", BMVC, 2016.</em></strong> <a href=http://www.bmva.org/bmvc/2016/papers/paper012/paper012.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#wnp">WnP</a></li>
<li><a href="datasets/year_datasets.md#utka">UTKA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<details close>
<summary><strong><em>Hu et al., "Human Intent Forecasting Using Intrinsic Kinematic Constraints", IROS, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7759141>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cad-120">CAD-120</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
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
<summary><strong><em>Park et al., "Hi Robot: Human Intention-Aware Robot Planning For Safe And Efficient Navigation In Crowds", IROS, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7759511>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Park_2016_IROS,
    author = "Park, C. and Ondřej, J. and Gilbert, M. and Freeman, K. and O'Sullivan, C.",
    booktitle = "IROS",
    title = "Hi Robot: Human Intention-Aware Robot Planning For Safe And Efficient Navigation In Crowds",
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
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
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
<summary><strong><em>Li et al., "Recognition Of Ongoing Complex Activities By Sequence Prediction Over A Hierarchical Label Space", WACV, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7477586>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#oa">OA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<details close>
<summary><strong><em>Xu et al., "Human Activities Prediction By Learning Combinatorial Sparse Representations", ICIP, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7532452>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#uti">UTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Lee et al., "Human Activity Prediction Based On Sub-Volume Relationship Descriptor", ICPR, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7899939>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="datasets/year_datasets.md#bit">BIT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Hariyono et al., "Estimation Of Collision Risk For Improving Driver'S Safety", IECON, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7793743>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#eth_pedestrian">ETH Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#daimler">Daimler</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#auc">AUC</a></li>
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
<details close>
<summary><strong><em>Volz et al., "A Data-Driven Approach For Pedestrian Intention Estimation", ITSC, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7795975>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#rmse">RMSE</a></li>
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
<details close>
<summary><strong><em>Xu et al., "Activity Auto-Completion: Predicting Human Activities From Partial Videos", ICCV, 2015.</em></strong> <a href=https://openaccess.thecvf.com/content_iccv_2015/papers/Xu_Activity_Auto-Completion_Predicting_ICCV_2015_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#uti">UTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#mrr">MRR</a></li>
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
<details close>
<summary><strong><em>Zhou et al., "Temporal Perception And Prediction In Ego-Centric Video", ICCV, 2015.</em></strong> <a href=https://openaccess.thecvf.com/content_iccv_2015/papers/Zhou_Temporal_Perception_and_ICCV_2015_paper.pdf>paper</a> <a href=https://github.com/aditya7874/Activity-Prediction-in-EgoCentric-Videos>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#fppa">FPPA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<details close>
<summary><strong><em>Pérez-D'Arpino et al., "Fast Target Prediction Of Human Reaching Motion For Cooperative Human-Robot Manipulation Tasks Using Time Series Classification", ICRA, 2015.</em></strong> <a href=https://ieeexplore.ieee.org/document/7140066>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Arpino_2015_ICRA,
    author = "Pérez-D'Arpino, C. and Shah, J. A.",
    booktitle = "ICRA",
    title = "Fast Target Prediction Of Human Reaching Motion For Cooperative Human-Robot Manipulation Tasks Using Time Series Classification",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zhang et al., "Bio-Inspired Predictive Orientation Decomposition Of Skeleton Trajectories For Real-Time Human Activity Prediction", ICRA, 2015.</em></strong> <a href=https://ieeexplore.ieee.org/document/7139618>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#msrda">MSRDA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<details close>
<summary><strong><em>Hashimoto et al., "Probability Estimation For Pedestrian Crossing Intention At Signalized Crosswalks", ICVES, 2015.</em></strong> <a href=https://ieeexplore.ieee.org/document/7396904>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hashimoto_2015_ICVES,
    author = "Hashimoto, Yoriyoshi and Gu, Yanlei and Hsu, Li-Ta and Kamijo, Shunsuke",
    title = "Probability Estimation For Pedestrian Crossing Intention At Signalized Crosswalks",
    booktitle = "ICVES",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Kohler et al., "Stereo-Vision-Based Pedestrian'S Intention Detection In A Moving Vehicle", ITSC, 2015.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/7313466>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kohler_2015_ITSC,
    author = "Kohler, Sebastian and Goldhammer, Michael and Zindler, Klaus and Doll, Konrad and Dietmeyer, Klaus",
    title = "Stereo-Vision-Based Pedestrian'S Intention Detection In A Moving Vehicle",
    booktitle = "ITSC",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Volz et al., "Feature Relevance Estimation For Learning Pedestrian Behavior At Crosswalks", ITSC, 2015.</em></strong> <a href=https://ieeexplore.ieee.org/document/7313236>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#tnr">TNR</a></li>
<li><a href="metrics.md#tpr">TPR</a></li>
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
<details close>
<summary><strong><em>Schulz et al., "Pedestrian Intention Recognition Using Latent-Dynamic Conditional Random Fields", IV, 2015.</em></strong> <a href=https://ieeexplore.ieee.org/document/7225754>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#daimler_path">Daimler Path</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
</ul>
</details>

<a name=recall></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Recall</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Ke et al., "Time-Conditioned Action Anticipation In One Shot", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Ke_Time-Conditioned_Action_Anticipation_in_One_Shot_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets/year_datasets.md#50salad">50Salad</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
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
<summary><strong><em>Furnari et al., "What Would You Expect? Anticipating Egocentric Actions With Rolling-Unrolling Lstms And Modality Attention", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Furnari_What_Would_You_Expect_Anticipating_Egocentric_Actions_With_Rolling-Unrolling_LSTMs_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.09035.pdf>arxiv</a> <a href=https://github.com/fpv-iplab/rulstm>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets/year_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
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
<summary><strong><em>Sener et al., "Zero-Shot Anticipation For Instructional Activities", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Sener_Zero-Shot_Anticipation_for_Instructional_Activities_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.02501.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#youcook2">YouCook2</a></li>
<li><a href="datasets/year_datasets.md#recipe1m">Recipe1M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
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
<li><a href="datasets/year_datasets.md#pie">PIE</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#auc">AUC</a></li>
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
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
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
<li><a href="datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#ap">AP</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
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
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#ttm">TTM</a></li>
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
<li><a href="datasets/year_datasets.md#cad-120">CAD-120</a></li>
<li><a href="datasets/year_datasets.md#mpii_cooking">MPII Cooking</a></li>
<li><a href="datasets/year_datasets.md#breakfast">Breakfast</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
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
<li><a href="datasets/year_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
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
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#ap">AP</a></li>
<li><a href="metrics.md#tta">TTA</a></li>
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
<summary><strong><em>Suzuki et al., "Anticipating Traffic Accidents With Adaptive Loss And Large-Scale Incident Db", The CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0494.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.02675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#dad">DAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#map">mAP</a></li>
<li><a href="metrics.md#attc">ATTC</a></li>
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
<summary><strong><em>Casas et al., "Intentnet: Learning To Predict Intention From Raw Sensor Data", CORL, 2018.</em></strong> <a href=http://proceedings.mlr.press/v87/casas18a/casas18a.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#map">mAP</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Casas_2018_CORL,
    author = "Casas, Sergio and Luo, Wenjie and Urtasun, Raquel",
    title = "Intentnet: Learning To Predict Intention From Raw Sensor Data",
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
<li><a href="datasets/year_datasets.md#mpii_cooking">MPII Cooking</a></li>
<li><a href="datasets/year_datasets.md#virat">VIRAT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#rmse">RMSE</a></li>
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
<li><a href="datasets/year_datasets.md#cad-120">CAD-120</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
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
<summary><strong><em>Kwak et al., "Pedestrian Intention Prediction Based On Dynamic Fuzzy Automata For Vehicle Driving At Nighttime", Infrared Physics \\& Technology, 2017.</em></strong> <a href=https://www.sciencedirect.com/science/article/abs/pii/S1350449516304935>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Kwak_2017_IPT,
    author = "Kwak, Joon-Young and Ko, Byoung Chul and Nam, Jae-Yeal",
    title = "Pedestrian Intention Prediction Based On Dynamic Fuzzy Automata For Vehicle Driving At Nighttime",
    journal = "Infrared Physics \\\& Technology",
    volume = "81",
    pages = "41--51",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Jain et al., "Structural-Rnn: Deep Learning On Spatio-Temporal Graphs", CVPR, 2016.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.05298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cad-120">CAD-120</a></li>
<li><a href="datasets/year_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#ttm">TTM</a></li>
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
<summary><strong><em>Jain et al., "Recurrent Neural Networks For Driver Activity Anticipation Via Sensory-Fusion Architecture", ICRA, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7487478>paper</a> <a href=https://arxiv.org/pdf/1509.05016.pdf>arxiv</a> <a href=https://github.com/asheshjain399/RNNexp>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#ttm">TTM</a></li>
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
<li><a href="datasets/year_datasets.md#cad-120">CAD-120</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
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
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
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
<li><a href="datasets/year_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#ttm">TTM</a></li>
<li><a href="metrics.md#fp">FP</a></li>
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

<a name=precision></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Precision</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Ke et al., "Time-Conditioned Action Anticipation In One Shot", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Ke_Time-Conditioned_Action_Anticipation_in_One_Shot_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="datasets/year_datasets.md#50salad">50Salad</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
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
<li><a href="datasets/year_datasets.md#pie">PIE</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#auc">AUC</a></li>
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
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
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
<li><a href="datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#ap">AP</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
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
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#ttm">TTM</a></li>
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
<li><a href="datasets/year_datasets.md#cad-120">CAD-120</a></li>
<li><a href="datasets/year_datasets.md#mpii_cooking">MPII Cooking</a></li>
<li><a href="datasets/year_datasets.md#breakfast">Breakfast</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
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
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#ap">AP</a></li>
<li><a href="metrics.md#tta">TTA</a></li>
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
<summary><strong><em>Suzuki et al., "Anticipating Traffic Accidents With Adaptive Loss And Large-Scale Incident Db", The CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0494.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.02675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#dad">DAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#map">mAP</a></li>
<li><a href="metrics.md#attc">ATTC</a></li>
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
<summary><strong><em>Mahmud et al., "Joint Prediction Of Activity Labels And Starting Times In Untrimmed Videos", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Mahmud_Joint_Prediction_of_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#mpii_cooking">MPII Cooking</a></li>
<li><a href="datasets/year_datasets.md#virat">VIRAT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#rmse">RMSE</a></li>
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
<li><a href="datasets/year_datasets.md#cad-120">CAD-120</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
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
<summary><strong><em>Kwak et al., "Pedestrian Intention Prediction Based On Dynamic Fuzzy Automata For Vehicle Driving At Nighttime", Infrared Physics \\& Technology, 2017.</em></strong> <a href=https://www.sciencedirect.com/science/article/abs/pii/S1350449516304935>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Kwak_2017_IPT,
    author = "Kwak, Joon-Young and Ko, Byoung Chul and Nam, Jae-Yeal",
    title = "Pedestrian Intention Prediction Based On Dynamic Fuzzy Automata For Vehicle Driving At Nighttime",
    journal = "Infrared Physics \\\& Technology",
    volume = "81",
    pages = "41--51",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Jain et al., "Structural-Rnn: Deep Learning On Spatio-Temporal Graphs", CVPR, 2016.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.05298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cad-120">CAD-120</a></li>
<li><a href="datasets/year_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#ttm">TTM</a></li>
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
<summary><strong><em>Jain et al., "Recurrent Neural Networks For Driver Activity Anticipation Via Sensory-Fusion Architecture", ICRA, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7487478>paper</a> <a href=https://arxiv.org/pdf/1509.05016.pdf>arxiv</a> <a href=https://github.com/asheshjain399/RNNexp>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#ttm">TTM</a></li>
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
<li><a href="datasets/year_datasets.md#cad-120">CAD-120</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
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
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
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
<li><a href="datasets/year_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#ttm">TTM</a></li>
<li><a href="metrics.md#fp">FP</a></li>
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

<a name=f1></a>
<details close>
<summary><em><l style="font-size:20px"><strong>F1</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Rasouli et al., "Pedestrian Action Anticipation Using Contextual Feature Fusion In Stacked Rnns", BMVC, 2019.</em></strong> <a href=https://bmvc2019.org/wp-content/uploads/papers/0283-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.06582.pdf>arxiv</a> <a href=https://github.com/aras62/SF-GRU>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#pie">PIE</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#auc">AUC</a></li>
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
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
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
<li><a href="datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#ap">AP</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
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
<summary><strong><em>Suzuki et al., "Anticipating Traffic Accidents With Adaptive Loss And Large-Scale Incident Db", The CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0494.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.02675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#dad">DAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#map">mAP</a></li>
<li><a href="metrics.md#attc">ATTC</a></li>
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
<summary><strong><em>Schydlo et al., "Anticipation In Human-Robot Cooperation: A Recurrent Neural Network Approach For Multiple Action Sequences Prediction", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8460924>paper</a> <a href=https://arxiv.org/pdf/1802.10503.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cad-120">CAD-120</a></li>
<li><a href="datasets/year_datasets.md#acticipate">ACTICIPATE</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#f1">F1</a></li>
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
<li><a href="datasets/year_datasets.md#cad-120">CAD-120</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
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
<summary><strong><em>Jain et al., "Structural-Rnn: Deep Learning On Spatio-Temporal Graphs", CVPR, 2016.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.05298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cad-120">CAD-120</a></li>
<li><a href="datasets/year_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#ttm">TTM</a></li>
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
<summary><strong><em>Hu et al., "Human Intent Forecasting Using Intrinsic Kinematic Constraints", IROS, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7759141>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cad-120">CAD-120</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
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
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
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

<a name=map></a>
<details close>
<summary><em><l style="font-size:20px"><strong>mean Average Precision (mAP)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Liang et al., "Peeking Into The Future: Predicting Future Person Activities And Locations In Videos", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPRW_2019/papers/Precognition/Liang_Peeking_Into_the_Future_Predicting_Future_Person_Activities_and_Locations_CVPRW_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1902.03748.pdf>arxiv</a> <a href=https://github.com/google/next-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#actev/virat">ActEV/VIRAT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#map">mAP</a></li>
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
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#willow_action">Willow Action</a></li>
<li><a href="datasets/year_datasets.md#wider">WIDER</a></li>
<li><a href="datasets/year_datasets.md#stanford-40">Stanford-40</a></li>
<li><a href="datasets/year_datasets.md#bu_action">BU Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#map">mAP</a></li>
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
<summary><strong><em>Suzuki et al., "Anticipating Traffic Accidents With Adaptive Loss And Large-Scale Incident Db", The CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0494.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.02675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#dad">DAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#map">mAP</a></li>
<li><a href="metrics.md#attc">ATTC</a></li>
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
<summary><strong><em>Casas et al., "Intentnet: Learning To Predict Intention From Raw Sensor Data", CORL, 2018.</em></strong> <a href=http://proceedings.mlr.press/v87/casas18a/casas18a.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#map">mAP</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Casas_2018_CORL,
    author = "Casas, Sergio and Luo, Wenjie and Urtasun, Raquel",
    title = "Intentnet: Learning To Predict Intention From Raw Sensor Data",
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
<li><a href="datasets/year_datasets.md#dad">DAD</a></li>
<li><a href="datasets/year_datasets.md#epic-fail">Epic-Fail</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#map">mAP</a></li>
<li><a href="metrics.md#tta">TTA</a></li>
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
<summary><strong><em>Singh et al., "Online Real-Time Multiple Spatiotemporal Action Localisation And Prediction", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Singh_Online_Real-Time_Multiple_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1611.08563.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#map">mAP</a></li>
<li><a href="metrics.md#auc">AUC</a></li>
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
<li><a href="datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#map">mAP</a></li>
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
<summary><strong><em>Gao et al., "Red: Reinforced Encoder-Decoder Networks For Action Anticipation", BMVC, 2017.</em></strong> <a href=http://www.bmva.org/bmvc/2017/papers/paper092/paper092.pdf>paper</a> <a href=https://arxiv.org/pdf/1707.04818.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="datasets/year_datasets.md#thumos">THUMOS</a></li>
<li><a href="datasets/year_datasets.md#tv_series">TV Series</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#map">mAP</a></li>
<li><a href="metrics.md#cap">cAP</a></li>
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
</ul>
</details>

<a name=ap></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Average Precision (AP)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Sun et al., "Relational Action Forecasting", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Sun_Relational_Action_Forecasting_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.04231.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#jhmdb">JHMDB</a></li>
<li><a href="datasets/year_datasets.md#ava">AVA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ap">AP</a></li>
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
<summary><strong><em>Gujjar et al., "Classifying Pedestrian Actions In Advance Using Predicted Video Of Urban Driving Scenes", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8794278>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#ap">AP</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
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
<summary><strong><em>Saleh et al., "Real-Time Intent Prediction Of Pedestrians For Autonomous Ground Vehicles Via Spatio-Temporal Densenet", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8793991>paper</a> <a href=https://arxiv.org/pdf/1904.09862.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ap">AP</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
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
<summary><strong><em>Wang et al., "A Learning-Based Prediction Model For Baby Accidents", ICIP, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8803820>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#ap">AP</a></li>
<li><a href="metrics.md#tta">TTA</a></li>
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
<summary><strong><em>Chan et al., "Anticipating Accidents In Dashcam Videos", ACCV, 2017.</em></strong> <a href=https://link.springer.com/chapter/10.1007/978-3-319-54190-7_9>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ap">AP</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
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

</ul>
</details>
</ul>
</details>

<a name=ttm></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Time To Maneuver (TTM)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Scheel et al., "Attention-Based Lane Change Prediction", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8793648>paper</a> <a href=https://arxiv.org/pdf/1903.01246.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#ttm">TTM</a></li>
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
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#ttm">TTM</a></li>
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
<summary><strong><em>Jain et al., "Structural-Rnn: Deep Learning On Spatio-Temporal Graphs", CVPR, 2016.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.05298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cad-120">CAD-120</a></li>
<li><a href="datasets/year_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#ttm">TTM</a></li>
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
<summary><strong><em>Jain et al., "Recurrent Neural Networks For Driver Activity Anticipation Via Sensory-Fusion Architecture", ICRA, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7487478>paper</a> <a href=https://arxiv.org/pdf/1509.05016.pdf>arxiv</a> <a href=https://github.com/asheshjain399/RNNexp>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#ttm">TTM</a></li>
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
<li><a href="datasets/year_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#ttm">TTM</a></li>
<li><a href="metrics.md#fp">FP</a></li>
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

<a name=auc></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Area Under the Curve (AUC)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Rasouli et al., "Pedestrian Action Anticipation Using Contextual Feature Fusion In Stacked Rnns", BMVC, 2019.</em></strong> <a href=https://bmvc2019.org/wp-content/uploads/papers/0283-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.06582.pdf>arxiv</a> <a href=https://github.com/aras62/SF-GRU>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#pie">PIE</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#auc">AUC</a></li>
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
<summary><strong><em>Singh et al., "Online Real-Time Multiple Spatiotemporal Action Localisation And Prediction", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Singh_Online_Real-Time_Multiple_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1611.08563.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#map">mAP</a></li>
<li><a href="metrics.md#auc">AUC</a></li>
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
<summary><strong><em>Hariyono et al., "Estimation Of Collision Risk For Improving Driver'S Safety", IECON, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7793743>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#eth_pedestrian">ETH Pedestrian</a></li>
<li><a href="datasets/year_datasets.md#daimler">Daimler</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#auc">AUC</a></li>
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
</ul>
</details>

<a name=rmse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Root Mean Square Error (RMSE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Mahmud et al., "Joint Prediction Of Activity Labels And Starting Times In Untrimmed Videos", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Mahmud_Joint_Prediction_of_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#mpii_cooking">MPII Cooking</a></li>
<li><a href="datasets/year_datasets.md#virat">VIRAT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#rmse">RMSE</a></li>
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
<li><a href="datasets/year_datasets.md#mpii_cooking">MPII Cooking</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#rmse">RMSE</a></li>
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
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#rmse">RMSE</a></li>
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

<a name=tta></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Time To Accident (TTA)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Wang et al., "A Learning-Based Prediction Model For Baby Accidents", ICIP, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8803820>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#ap">AP</a></li>
<li><a href="metrics.md#tta">TTA</a></li>
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
<li><a href="datasets/year_datasets.md#dad">DAD</a></li>
<li><a href="datasets/year_datasets.md#epic-fail">Epic-Fail</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#map">mAP</a></li>
<li><a href="metrics.md#tta">TTA</a></li>
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

<a name=run_time></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Run Time</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Gujjar et al., "Classifying Pedestrian Actions In Advance Using Predicted Video Of Urban Driving Scenes", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8794278>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#ap">AP</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
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
<summary><strong><em>Saleh et al., "Real-Time Intent Prediction Of Pedestrians For Autonomous Ground Vehicles Via Spatio-Temporal Densenet", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8793991>paper</a> <a href=https://arxiv.org/pdf/1904.09862.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ap">AP</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
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
</ul>
</details>

<a name=fp></a>
<details close>
<summary><em><l style="font-size:20px"><strong>False positive (FP)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Jain et al., "Car That Knows Before You Do: Anticipating Maneuvers Via Learning Temporal Driving Models", ICCV, 2015.</em></strong> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Jain_Car_That_Knows_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1504.02789.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#ttm">TTM</a></li>
<li><a href="metrics.md#fp">FP</a></li>
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

<a name=mcc></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Matthews Correlation Coefficient (MCC)</strong></l>
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
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#mcc">MCC</a></li>
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

<a name=tpr></a>
<details close>
<summary><em><l style="font-size:20px"><strong>True Positive Rate (TPR)</strong></l>
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
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#tnr">TNR</a></li>
<li><a href="metrics.md#tpr">TPR</a></li>
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

<a name=attc></a>
<details close>
<summary><em><l style="font-size:20px"><strong>ATTC</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Suzuki et al., "Anticipating Traffic Accidents With Adaptive Loss And Large-Scale Incident Db", The CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0494.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.02675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#dad">DAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#f1">F1</a></li>
<li><a href="metrics.md#map">mAP</a></li>
<li><a href="metrics.md#attc">ATTC</a></li>
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
</ul>
</details>

<a name=tnr></a>
<details close>
<summary><em><l style="font-size:20px"><strong>TNR</strong></l>
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
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#tnr">TNR</a></li>
<li><a href="metrics.md#tpr">TPR</a></li>
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

<a name=mae></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Absolute Error (MAE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Manglik et al., "Forecasting Time-To-Collision From Monocular Video: Feasibility, Dataset, And Challenges", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8967730>paper</a> <a href=https://arxiv.org/pdf/1903.09102.pdf>arxiv</a> <a href=https://github.com/aashi7/NearCollision>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#luggage">Luggage</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mae">MAE</a></li>
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

<a name=pp></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Prediction Power (PP)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Ziaeetabar et al., "Prediction Of Manipulation Action Classes Using Semantic Spatial Reasoning", IROS, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8593717>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#maniac">MANIAC</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#pp">PP</a></li>
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

<a name=mrr></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Miss Rate (MRR)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Xu et al., "Activity Auto-Completion: Predicting Human Activities From Partial Videos", ICCV, 2015.</em></strong> <a href=https://openaccess.thecvf.com/content_iccv_2015/papers/Xu_Activity_Auto-Completion_Predicting_ICCV_2015_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#uti">UTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
<li><a href="metrics.md#mrr">MRR</a></li>
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

<a name=cap></a>
<details close>
<summary><em><l style="font-size:20px"><strong>calibrated Average Precision (cAP)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Gao et al., "Red: Reinforced Encoder-Decoder Networks For Action Anticipation", BMVC, 2017.</em></strong> <a href=http://www.bmva.org/bmvc/2017/papers/paper092/paper092.pdf>paper</a> <a href=https://arxiv.org/pdf/1707.04818.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="datasets/year_datasets.md#thumos">THUMOS</a></li>
<li><a href="datasets/year_datasets.md#tv_series">TV Series</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#map">mAP</a></li>
<li><a href="metrics.md#cap">cAP</a></li>
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
</ul>
</details>

</ul><a name=metrics_trajectory></a>
<h2 style="color:#30bd19">  Trajectory Prediction </h2><a href=#top>&uarr; top</a>
<ul><a name=ade></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Average Displacement Error (ADE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Chandra et al., "Traphic: Trajectory Prediction In Dense And Heterogeneous Traffic Using Weighted Interactions", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Chandra_TraPHic_Trajectory_Prediction_in_Dense_and_Heterogeneous_Traffic_Using_Weighted_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.04767.pdf>arxiv</a> <a href=https://go.umd.edu/TraPHic>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="datasets/year_datasets.md#traf">TRAF</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Hong et al., "Rules Of The Road: Predicting Driving Behavior With A Convolutional Model Of Semantic Interactions", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Hong_Rules_of_the_Road_Predicting_Driving_Behavior_With_a_Convolutional_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.08945.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#hit_rate">Hit Rate</a></li>
<li><a href="metrics.md#mined">minED</a></li>
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
<summary><strong><em>Liang et al., "Peeking Into The Future: Predicting Future Person Activities And Locations In Videos", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPRW_2019/papers/Precognition/Liang_Peeking_Into_the_Future_Predicting_Future_Person_Activities_and_Locations_CVPRW_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1902.03748.pdf>arxiv</a> <a href=https://github.com/google/next-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="datasets/year_datasets.md#actev/virat">ActEV/VIRAT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Sadeghian et al., "Sophie: An Attentive Gan For Predicting Paths Compliant To Social And Physical Constraints", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Sadeghian_SoPhie_An_Attentive_GAN_for_Predicting_Paths_Compliant_to_Social_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1806.01482.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Zhang et al., "Sr-Lstm: State Refinement For Lstm Towards Pedestrian Trajectory Prediction", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_SR-LSTM_State_Refinement_for_LSTM_Towards_Pedestrian_Trajectory_Prediction_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1903.02793.pdf>arxiv</a> <a href=https://github.com/zhangpur/SR-LSTM>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Zhao et al., "Multi-Agent Tensor Fusion For Contextual Trajectory Prediction", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhao_Multi-Agent_Tensor_Fusion_for_Contextual_Trajectory_Prediction_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.04776.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="datasets/year_datasets.md#sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#rmse">RMSE</a></li>
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
<summary><strong><em>Bi et al., "Joint Prediction For Kinematic Trajectories In Vehicle-Pedestrian-Mixed Scenes", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Bi_Joint_Prediction_for_Kinematic_Trajectories_in_Vehicle-Pedestrian-Mixed_Scenes_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="datasets/year_datasets.md#vpm">VPM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="datasets/year_datasets.md#sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Huang et al., "Stgat: Modeling Spatial-Temporal Interactions For Human Trajectory Prediction", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Huang_STGAT_Modeling_Spatial-Temporal_Interactions_for_Human_Trajectory_Prediction_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Rasouli et al., "Pie: A Large-Scale Dataset And Models For Pedestrian Intention Estimation And Trajectory Prediction", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.pdf>paper</a> <a href=https://github.com/aras62/PIEPredict>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="datasets/year_datasets.md#pie">PIE</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Kosaraju et al., "Social-Bigat: Multimodal Trajectory Forecasting Using Bicycle-Gan And Graph Attention Networks", NeurIPS, 2019.</em></strong> <a href=http://papers.nips.cc/paper/8308-social-bigat-multimodal-trajectory-forecasting-using-bicycle-gan-and-graph-attention-networks.pdf>paper</a> <a href=https://arxiv.org/pdf/1907.03395.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Cui et al., "Multimodal Trajectory Predictions For Autonomous Driving Using Deep Convolutional Networks", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8793868>paper</a> <a href=https://arxiv.org/pdf/1809.10732.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cui_2019_ICRA,
    author = "Cui, H. and Radosavljevic, V. and Chou, F. and Lin, T. and Nguyen, T. and Huang, T. and Schneider, J. and Djuric, N.",
    booktitle = "ICRA",
    title = "Multimodal Trajectory Predictions For Autonomous Driving Using Deep Convolutional Networks",
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
<li><a href="metrics.md#ade">ADE</a></li>
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
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
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
<summary><strong><em>Anderson et al., "Stochastic Sampling Simulation For Pedestrian Trajectory Prediction", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8967857>paper</a> <a href=https://arxiv.org/pdf/1903.01860.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#minade">minADE</a></li>
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
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
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
<summary><strong><em>Li et al., "Conditional Generative Neural System For Probabilistic Trajectory Prediction", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8967822>paper</a> <a href=https://arxiv.org/pdf/1905.01631.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="datasets/year_datasets.md#sd">SD</a></li>
<li><a href="datasets/year_datasets.md#interaction">INTERACTION</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Srikanth et al., "Infer: Intermediate Representations For Future Prediction", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8968553>paper</a> <a href=https://arxiv.org/pdf/1903.10641.pdf>arxiv</a> <a href=https://rebrand.ly/INFER-results>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="datasets/year_datasets.md#oxford">Oxford</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
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
<summary><strong><em>Zhou et al., "Clone Swarms: Learning To Predict And Control Multi-Robot Systems By Imitation", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8967824>paper</a> <a href=https://arxiv.org/pdf/1912.02811.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
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
<summary><strong><em>Zhu et al., "Starnet: Pedestrian Trajectory Prediction Using Deep Neural Network In Star Topology", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8967811>paper</a> <a href=https://arxiv.org/pdf/1906.01797.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Chai et al., "Multipath: Multiple Probabilistic Anchor Trajectory Hypotheses For Behavior Prediction", CoRL, 2019.</em></strong> <a href=http://proceedings.mlr.press/v100/chai20a/chai20a.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.05449.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#minade">minADE</a></li>
<li><a href="metrics.md#ll">LL</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chai_2019_CORL,
    author = "Chai, Yuning and Sapp, Benjamin and Bansal, Mayank and Anguelov, Dragomir",
    title = "Multipath: Multiple Probabilistic Anchor Trajectory Hypotheses For Behavior Prediction",
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
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#nll">NLL</a></li>
<li><a href="metrics.md#ece">ECE</a></li>
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
<li><a href="datasets/year_datasets.md#eifp">EIFP</a></li>
<li><a href="datasets/year_datasets.md#lankershim_boulevard">Lankershim Boulevard</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="datasets/year_datasets.md#sd">SD</a></li>
<li><a href="datasets/year_datasets.md#pets2009">PETS2009</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<li><a href="datasets/year_datasets.md#mot">MOT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
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
<li><a href="datasets/year_datasets.md#cityperson">CityPerson</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#nll">NLL</a></li>
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
<summary><strong><em>Gupta et al., "Social Gan: Socially Acceptable Trajectories With Generative Adversarial Networks", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Gupta_Social_GAN_Socially_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1803.10892.pdf>arxiv</a> <a href=https://github.com/agrimgupta92/sgan>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Hasan et al., "Mx-Lstm: Mixing Tracklets And Vislets To Jointly Forecast Trajectories And Head Poses", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Hasan_MX-LSTM_Mixing_Tracklets_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1805.00652.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#town_center">Town Center</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Yao et al., "Multiple Granularity Group Interaction Prediction", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0721.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#sbuki">SBUKI</a></li>
<li><a href="datasets/year_datasets.md#ca">CA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
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
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="datasets/year_datasets.md#gc">GC</a></li>
<li><a href="datasets/year_datasets.md#chuk">CHUK</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#ande">ANDE</a></li>
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
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#miss_rate">Miss rate</a></li>
<li><a href="metrics.md#maxd">maxD</a></li>
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
<summary><strong><em>Fernando et al., "Gd-Gan: Generative Adversarial Networks For Trajectory Prediction And Group Detection In Crowds", ACCV, 2019.</em></strong> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20887-5_20>paper</a> <a href=https://arxiv.org/pdf/1812.07667.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Sun et al., "3Dof Pedestrian Trajectory Prediction Learned From Long-Term Autonomous Mobile Robot Deployment Data", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8461228>paper</a> <a href=https://arxiv.org/pdf/1710.00126.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#strands">STRANDS</a></li>
<li><a href="datasets/year_datasets.md#l-cas">L-CAS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#aede">AEDE</a></li>
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
<details close>
<summary><strong><em>Vemula et al., "Social Attention: Modeling Attention In Human Crowds", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8460504>paper</a> <a href=https://arxiv.org/pdf/1710.04689.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
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
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#nll">NLL</a></li>
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
<summary><strong><em>Hasan et al., ""Seeing Is Believing": Pedestrian Trajectory Forecasting Using Visual Frustum Of Attention", WACV, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8354238>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#town_center">Town Center</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#mane">MAnE</a></li>
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
<summary><strong><em>Xue et al., "Ss-Lstm: A Hierarchical Lstm Model For Pedestrian Trajectory Prediction", WACV, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8354239>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Bartoli et al., "Context-Aware Trajectory Prediction", ICPR, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8545447>paper</a> <a href=https://arxiv.org/pdf/1705.02503.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
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
<summary><strong><em>Solaimanpour et al., "A Layered Hmm For Predicting Motion Of A Leader In Multi-Robot Settings", ICRA, 2017.</em></strong> <a href=https://ieeexplore.ieee.org/document/7989097>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#kld">KLD</a></li>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Solaimanpour_2017_ICRA,
    author = "Solaimanpour, S. and Doshi, P.",
    booktitle = "ICRA",
    title = "A Layered Hmm For Predicting Motion Of A Leader In Multi-Robot Settings",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Alahi et al., "Social Lstm: Human Trajectory Prediction In Crowded Spaces", CVPR, 2016.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Alahi_Social_LSTM_Human_CVPR_2016_paper.pdf>paper</a> <a href=https://github.com/quancore/social-lstm>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#ande">ANDE</a></li>
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
<summary><strong><em>Yoo et al., "Visual Path Prediction In Complex Scenes With Crowded Moving Objects", CVPR, 2016.</em></strong> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Yoo_Visual_Path_Prediction_CVPR_2016_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#gc">GC</a></li>
<li><a href="datasets/year_datasets.md#qmul">QMUL</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
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
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
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
<summary><strong><em>Yi et al., "Pedestrian Behavior Understanding And Prediction With Deep Neural Networks", ECCV, 2016.</em></strong> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46448-0_16>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#gc">GC</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<li><a href="datasets/year_datasets.md#virat">VIRAT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#nll">NLL</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
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
<li><a href="metrics.md#ade">ADE</a></li>
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
<li><a href="datasets/year_datasets.md#daimler_path">Daimler Path</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#ed">ED</a></li>
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

<a name=fde></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Final Displacement Error (FDE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Chandra et al., "Traphic: Trajectory Prediction In Dense And Heterogeneous Traffic Using Weighted Interactions", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Chandra_TraPHic_Trajectory_Prediction_in_Dense_and_Heterogeneous_Traffic_Using_Weighted_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.04767.pdf>arxiv</a> <a href=https://go.umd.edu/TraPHic>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="datasets/year_datasets.md#traf">TRAF</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Liang et al., "Peeking Into The Future: Predicting Future Person Activities And Locations In Videos", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPRW_2019/papers/Precognition/Liang_Peeking_Into_the_Future_Predicting_Future_Person_Activities_and_Locations_CVPRW_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1902.03748.pdf>arxiv</a> <a href=https://github.com/google/next-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="datasets/year_datasets.md#actev/virat">ActEV/VIRAT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Sadeghian et al., "Sophie: An Attentive Gan For Predicting Paths Compliant To Social And Physical Constraints", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Sadeghian_SoPhie_An_Attentive_GAN_for_Predicting_Paths_Compliant_to_Social_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1806.01482.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Zhang et al., "Sr-Lstm: State Refinement For Lstm Towards Pedestrian Trajectory Prediction", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_SR-LSTM_State_Refinement_for_LSTM_Towards_Pedestrian_Trajectory_Prediction_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1903.02793.pdf>arxiv</a> <a href=https://github.com/zhangpur/SR-LSTM>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Zhao et al., "Multi-Agent Tensor Fusion For Contextual Trajectory Prediction", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhao_Multi-Agent_Tensor_Fusion_for_Contextual_Trajectory_Prediction_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.04776.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="datasets/year_datasets.md#sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#rmse">RMSE</a></li>
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
<summary><strong><em>Bi et al., "Joint Prediction For Kinematic Trajectories In Vehicle-Pedestrian-Mixed Scenes", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Bi_Joint_Prediction_for_Kinematic_Trajectories_in_Vehicle-Pedestrian-Mixed_Scenes_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="datasets/year_datasets.md#vpm">VPM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="datasets/year_datasets.md#sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Huang et al., "Stgat: Modeling Spatial-Temporal Interactions For Human Trajectory Prediction", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Huang_STGAT_Modeling_Spatial-Temporal_Interactions_for_Human_Trajectory_Prediction_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Rasouli et al., "Pie: A Large-Scale Dataset And Models For Pedestrian Intention Estimation And Trajectory Prediction", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.pdf>paper</a> <a href=https://github.com/aras62/PIEPredict>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="datasets/year_datasets.md#pie">PIE</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Kosaraju et al., "Social-Bigat: Multimodal Trajectory Forecasting Using Bicycle-Gan And Graph Attention Networks", NeurIPS, 2019.</em></strong> <a href=http://papers.nips.cc/paper/8308-social-bigat-multimodal-trajectory-forecasting-using-bicycle-gan-and-graph-attention-networks.pdf>paper</a> <a href=https://arxiv.org/pdf/1907.03395.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Cui et al., "Multimodal Trajectory Predictions For Autonomous Driving Using Deep Convolutional Networks", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8793868>paper</a> <a href=https://arxiv.org/pdf/1809.10732.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cui_2019_ICRA,
    author = "Cui, H. and Radosavljevic, V. and Chou, F. and Lin, T. and Nguyen, T. and Huang, T. and Schneider, J. and Djuric, N.",
    booktitle = "ICRA",
    title = "Multimodal Trajectory Predictions For Autonomous Driving Using Deep Convolutional Networks",
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
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#minade">minADE</a></li>
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
<summary><strong><em>Li et al., "Conditional Generative Neural System For Probabilistic Trajectory Prediction", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8967822>paper</a> <a href=https://arxiv.org/pdf/1905.01631.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="datasets/year_datasets.md#sd">SD</a></li>
<li><a href="datasets/year_datasets.md#interaction">INTERACTION</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Zhu et al., "Starnet: Pedestrian Trajectory Prediction Using Deep Neural Network In Star Topology", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8967811>paper</a> <a href=https://arxiv.org/pdf/1906.01797.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Chai et al., "Multipath: Multiple Probabilistic Anchor Trajectory Hypotheses For Behavior Prediction", CoRL, 2019.</em></strong> <a href=http://proceedings.mlr.press/v100/chai20a/chai20a.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.05449.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#minade">minADE</a></li>
<li><a href="metrics.md#ll">LL</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chai_2019_CORL,
    author = "Chai, Yuning and Sapp, Benjamin and Bansal, Mayank and Anguelov, Dragomir",
    title = "Multipath: Multiple Probabilistic Anchor Trajectory Hypotheses For Behavior Prediction",
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
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#nll">NLL</a></li>
<li><a href="metrics.md#ece">ECE</a></li>
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
<li><a href="datasets/year_datasets.md#eifp">EIFP</a></li>
<li><a href="datasets/year_datasets.md#lankershim_boulevard">Lankershim Boulevard</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="datasets/year_datasets.md#sd">SD</a></li>
<li><a href="datasets/year_datasets.md#pets2009">PETS2009</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Gupta et al., "Social Gan: Socially Acceptable Trajectories With Generative Adversarial Networks", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Gupta_Social_GAN_Socially_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1803.10892.pdf>arxiv</a> <a href=https://github.com/agrimgupta92/sgan>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Hasan et al., "Mx-Lstm: Mixing Tracklets And Vislets To Jointly Forecast Trajectories And Head Poses", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Hasan_MX-LSTM_Mixing_Tracklets_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1805.00652.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#town_center">Town Center</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Xu et al., "Encoding Crowd Interaction With Deep Neural Network For Pedestrian Trajectory Prediction", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/2136.pdf>paper</a> <a href=https://github.com/svip-lab/CIDNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="datasets/year_datasets.md#gc">GC</a></li>
<li><a href="datasets/year_datasets.md#chuk">CHUK</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#ande">ANDE</a></li>
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
<summary><strong><em>Fernando et al., "Gd-Gan: Generative Adversarial Networks For Trajectory Prediction And Group Detection In Crowds", ACCV, 2019.</em></strong> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20887-5_20>paper</a> <a href=https://arxiv.org/pdf/1812.07667.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Vemula et al., "Social Attention: Modeling Attention In Human Crowds", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8460504>paper</a> <a href=https://arxiv.org/pdf/1710.04689.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Hasan et al., ""Seeing Is Believing": Pedestrian Trajectory Forecasting Using Visual Frustum Of Attention", WACV, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8354238>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#town_center">Town Center</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#mane">MAnE</a></li>
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
<summary><strong><em>Xue et al., "Ss-Lstm: A Hierarchical Lstm Model For Pedestrian Trajectory Prediction", WACV, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8354239>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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
<summary><strong><em>Alahi et al., "Social Lstm: Human Trajectory Prediction In Crowded Spaces", CVPR, 2016.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Alahi_Social_LSTM_Human_CVPR_2016_paper.pdf>paper</a> <a href=https://github.com/quancore/social-lstm>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#ande">ANDE</a></li>
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
<summary><strong><em>Yi et al., "Pedestrian Behavior Understanding And Prediction With Deep Neural Networks", ECCV, 2016.</em></strong> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46448-0_16>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#gc">GC</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
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

<a name=ed></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Euclidean Distance (ED)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Carvalho et al., "Long-Term Prediction Of Motion Trajectories Using Path Homology Clusters", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8968125>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#eifp">EIFP</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ed">ED</a></li>
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
<summary><strong><em>Baumann et al., "Predicting Ego-Vehicle Paths From Environmental Observations With A Deep Neural Network", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8460704>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ed">ED</a></li>
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
<li><a href="metrics.md#ed">ED</a></li>
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
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ed">ED</a></li>
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
<summary><strong><em>Lee et al., "Desire: Distant Future Prediction In Dynamic Scenes With Interacting Agents", CVPR, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lee_DESIRE_Distant_Future_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1704.04394.pdf>arxiv</a> <a href=https://github.com/yadrimz/DESIRE>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ed">ED</a></li>
<li><a href="metrics.md#mined">minED</a></li>
<li><a href="metrics.md#maxd">maxD</a></li>
<li><a href="metrics.md#miss_rate">Miss rate</a></li>
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
<summary><strong><em>Karasev et al., "Intent-Aware Long-Term Prediction Of Pedestrian Motion", ICRA, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7487409>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ed">ED</a></li>
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
<li><a href="metrics.md#ed">ED</a></li>
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
<li><a href="datasets/year_datasets.md#tum_kitchen">TUM Kitchen</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ed">ED</a></li>
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
<li><a href="datasets/year_datasets.md#gc">GC</a></li>
<li><a href="datasets/year_datasets.md#mitt">MITT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ed">ED</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
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
<li><a href="datasets/year_datasets.md#daimler_path">Daimler Path</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#ed">ED</a></li>
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

<a name=nll></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Negative Log-Likelihood (NLL)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Jain et al., "Discrete Residual Flow For Probabilistic Pedestrian Behavior Prediction", CoRL, 2019.</em></strong> <a href=http://proceedings.mlr.press/v100/jain20a/jain20a.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.08041.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#nll">NLL</a></li>
<li><a href="metrics.md#ece">ECE</a></li>
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
<summary><strong><em>Bhattacharyya et al., "Long-Term On-Board Prediction Of People In Traffic Scenes Under Uncertainty", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Bhattacharyya_Long-Term_On-Board_Prediction_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1711.09026.pdf>arxiv</a> <a href=https://github.com/apratimbhattacharyya18/onboard_long_term_prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cityperson">CityPerson</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#nll">NLL</a></li>
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
<summary><strong><em>Zhang et al., "Integrating Kinematics And Environment Context Into Deep Inverse Reinforcement Learning For Predicting Off-Road Vehicle Trajectories", CoRL, 2018.</em></strong> <a href=http://proceedings.mlr.press/v87/zhang18a/zhang18a.pdf>paper</a> <a href=https://arxiv.org/pdf/1810.07225.pdf>arxiv</a> <a href=https://github.com/yfzhang/vehicle-motion-forecasting>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#nll">NLL</a></li>
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
<summary><strong><em>Ma et al., "Forecasting Interactive Dynamics Of Pedestrians With Fictitious Play", CVPR, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Ma_Forecasting_Interactive_Dynamics_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1604.01431.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#town_center">Town Center</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#nll">NLL</a></li>
<li><a href="metrics.md#scr">SCR</a></li>
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
<summary><strong><em>Vasquez, "Novel Planning-Based Algorithms For Human Motion Prediction", ICRA, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/7487505>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#virat">VIRAT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#nll">NLL</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
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
<summary><strong><em>Lee et al., "Predicting Wide Receiver Trajectories In American Football", WACV, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7477732>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#osu">OSU</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#nll">NLL</a></li>
<li><a href="metrics.md#kld">KLD</a></li>
<li><a href="metrics.md#mhd">MHD</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
<li><a href="metrics.md#dtg">DtG</a></li>
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
</ul>
</details>

<a name=run_time></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Run Time</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Ding et al., "Online Vehicle Trajectory Prediction Using Policy Anticipation Network And Optimization-Based Context Reasoning", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8793568>paper</a> <a href=https://arxiv.org/pdf/1903.00847.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#carla">CARLA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#run_time">Run Time</a></li>
<li><a href="metrics.md#rmse">RMSE</a></li>
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
<details close>
<summary><strong><em>Rudenko et al., "Joint Long-Term Prediction Of Human Motion Using A Planning-Based Social Force Approach", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8460527>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#atc">ATC</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#run_time">Run Time</a></li>
<li><a href="metrics.md#mhd">MHD</a></li>
<li><a href="metrics.md#nlp">NLP</a></li>
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
<details close>
<summary><strong><em>Shen et al., "Transferable Pedestrian Motion Prediction Models At Intersections", IROS, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8593783>paper</a> <a href=https://arxiv.org/pdf/1804.00495.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
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
<summary><strong><em>Vasquez, "Novel Planning-Based Algorithms For Human Motion Prediction", ICRA, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/7487505>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#virat">VIRAT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#nll">NLL</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
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
<summary><strong><em>Akbarzadeh et al., "Kernel Density Estimation For Target Trajectory Prediction", IROS, 2015.</em></strong> <a href=https://ieeexplore.ieee.org/document/7353858>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#gc">GC</a></li>
<li><a href="datasets/year_datasets.md#mitt">MITT</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ed">ED</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
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
</ul>
</details>

<a name=ll></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Log-Likelihood (LL)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Thiede et al., "Analyzing The Variety Loss In The Context Of Probabilistic Trajectory Prediction", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Thiede_Analyzing_the_Variety_Loss_in_the_Context_of_Probabilistic_Trajectory_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1907.10178.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ll">LL</a></li>
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
<summary><strong><em>Tang et al., "Adaptive Probabilistic Vehicle Trajectory Prediction Through Physically Feasible Bayesian Recurrent Neural Network", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8794130>paper</a> <a href=https://arxiv.org/pdf/1911.04597.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ll">LL</a></li>
<li><a href="metrics.md#kld">KLD</a></li>
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
<summary><strong><em>Chai et al., "Multipath: Multiple Probabilistic Anchor Trajectory Hypotheses For Behavior Prediction", CoRL, 2019.</em></strong> <a href=http://proceedings.mlr.press/v100/chai20a/chai20a.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.05449.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#minade">minADE</a></li>
<li><a href="metrics.md#ll">LL</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chai_2019_CORL,
    author = "Chai, Yuning and Sapp, Benjamin and Bansal, Mayank and Anguelov, Dragomir",
    title = "Multipath: Multiple Probabilistic Anchor Trajectory Hypotheses For Behavior Prediction",
    booktitle = "CoRL",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Schulz et al., "Interaction-Aware Probabilistic Behavior Prediction In Urban Environments", IROS, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8594095>paper</a> <a href=https://arxiv.org/pdf/1804.10467.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ll">LL</a></li>
<li><a href="metrics.md#wrmse">WRMSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Schulz_2018_IROS,
    author = "Schulz, J. and Hubmann, C. and Löchner, J. and Burschka, D.",
    booktitle = "IROS",
    title = "Interaction-Aware Probabilistic Behavior Prediction In Urban Environments",
    year = "2018"
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
<summary><strong><em>Chang et al., "Argoverse: 3D Tracking And Forecasting With Rich Maps", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_Argoverse_3D_Tracking_and_Forecasting_With_Rich_Maps_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.02620.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#argoverse">ARGOVerse</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#minade">minADE</a></li>
<li><a href="metrics.md#minfde">minFDE</a></li>
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
<details close>
<summary><strong><em>Li, "Which Way Are You Going? Imitative Decision Learning For Path Forecasting In Dynamic Scenes", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Which_Way_Are_You_Going_Imitative_Decision_Learning_for_Path_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="datasets/year_datasets.md#sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#minade">minADE</a></li>
<li><a href="metrics.md#minfde">minFDE</a></li>
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
<summary><strong><em>Anderson et al., "Stochastic Sampling Simulation For Pedestrian Trajectory Prediction", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8967857>paper</a> <a href=https://arxiv.org/pdf/1903.01860.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#minade">minADE</a></li>
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
<summary><strong><em>Chai et al., "Multipath: Multiple Probabilistic Anchor Trajectory Hypotheses For Behavior Prediction", CoRL, 2019.</em></strong> <a href=http://proceedings.mlr.press/v100/chai20a/chai20a.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.05449.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#minade">minADE</a></li>
<li><a href="metrics.md#ll">LL</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chai_2019_CORL,
    author = "Chai, Yuning and Sapp, Benjamin and Bansal, Mayank and Anguelov, Dragomir",
    title = "Multipath: Multiple Probabilistic Anchor Trajectory Hypotheses For Behavior Prediction",
    booktitle = "CoRL",
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
<summary><strong><em>Tang et al., "Adaptive Probabilistic Vehicle Trajectory Prediction Through Physically Feasible Bayesian Recurrent Neural Network", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8794130>paper</a> <a href=https://arxiv.org/pdf/1911.04597.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ll">LL</a></li>
<li><a href="metrics.md#kld">KLD</a></li>
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
<summary><strong><em>Solaimanpour et al., "A Layered Hmm For Predicting Motion Of A Leader In Multi-Robot Settings", ICRA, 2017.</em></strong> <a href=https://ieeexplore.ieee.org/document/7989097>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#kld">KLD</a></li>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Solaimanpour_2017_ICRA,
    author = "Solaimanpour, S. and Doshi, P.",
    booktitle = "ICRA",
    title = "A Layered Hmm For Predicting Motion Of A Leader In Multi-Robot Settings",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Lee et al., "Predicting Wide Receiver Trajectories In American Football", WACV, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7477732>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#osu">OSU</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#nll">NLL</a></li>
<li><a href="metrics.md#kld">KLD</a></li>
<li><a href="metrics.md#mhd">MHD</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
<li><a href="metrics.md#dtg">DtG</a></li>
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
</ul>
</details>

<a name=mhd></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Modified Hausdorff Distance (MHD)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Rudenko et al., "Joint Long-Term Prediction Of Human Motion Using A Planning-Based Social Force Approach", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8460527>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#atc">ATC</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#run_time">Run Time</a></li>
<li><a href="metrics.md#mhd">MHD</a></li>
<li><a href="metrics.md#nlp">NLP</a></li>
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
<details close>
<summary><strong><em>Rudenko et al., "Human Motion Prediction Under Social Grouping Constraints", IROS, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8594258>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mhd">MHD</a></li>
<li><a href="metrics.md#nlp">NLP</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rudenko_2018_IROS,
    author = "Rudenko, A. and Palmieri, L. and Lilienthal, A. J. and Arras, K. O.",
    booktitle = "IROS",
    title = "Human Motion Prediction Under Social Grouping Constraints",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Lee et al., "Predicting Wide Receiver Trajectories In American Football", WACV, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7477732>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#osu">OSU</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#nll">NLL</a></li>
<li><a href="metrics.md#kld">KLD</a></li>
<li><a href="metrics.md#mhd">MHD</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
<li><a href="metrics.md#dtg">DtG</a></li>
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
</ul>
</details>

<a name=rmse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Root Mean Square Error (RMSE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Zhao et al., "Multi-Agent Tensor Fusion For Contextual Trajectory Prediction", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhao_Multi-Agent_Tensor_Fusion_for_Contextual_Trajectory_Prediction_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.04776.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="datasets/year_datasets.md#sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#rmse">RMSE</a></li>
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
<summary><strong><em>Ding et al., "Online Vehicle Trajectory Prediction Using Policy Anticipation Network And Optimization-Based Context Reasoning", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8793568>paper</a> <a href=https://arxiv.org/pdf/1903.00847.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#carla">CARLA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#run_time">Run Time</a></li>
<li><a href="metrics.md#rmse">RMSE</a></li>
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
</ul>
</details>

<a name=hit_rate></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Hit Rate</strong></l>
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
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#hit_rate">Hit Rate</a></li>
<li><a href="metrics.md#mined">minED</a></li>
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
<li><a href="metrics.md#hit_rate">Hit Rate</a></li>
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

<a name=nlp></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Negative Log-Probability (NLP)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Rudenko et al., "Joint Long-Term Prediction Of Human Motion Using A Planning-Based Social Force Approach", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8460527>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#atc">ATC</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#run_time">Run Time</a></li>
<li><a href="metrics.md#mhd">MHD</a></li>
<li><a href="metrics.md#nlp">NLP</a></li>
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
<details close>
<summary><strong><em>Rudenko et al., "Human Motion Prediction Under Social Grouping Constraints", IROS, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8594258>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mhd">MHD</a></li>
<li><a href="metrics.md#nlp">NLP</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rudenko_2018_IROS,
    author = "Rudenko, A. and Palmieri, L. and Lilienthal, A. J. and Arras, K. O.",
    booktitle = "IROS",
    title = "Human Motion Prediction Under Social Grouping Constraints",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

<a name=meanmsd></a>
<details close>
<summary><em><l style="font-size:20px"><strong>mean Mean Square Displacemen (meanMSD)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Rhinehart et al., "Precog: Prediction Conditioned On Goals In Visual Multi-Agent Settings", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rhinehart_PRECOG_PREdiction_Conditioned_on_Goals_in_Visual_Multi-Agent_Settings_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.01296.pdf>arxiv</a> <a href=https://sites.google.com/view/precog>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#carla">CARLA</a></li>
<li><a href="datasets/year_datasets.md#nuscenes">nuScenes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#meanmsd">meanMSD</a></li>
<li><a href="metrics.md#minmsd">minMSD</a></li>
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
<summary><strong><em>Rhinehart et al., "R2P2: A Reparameterized Pushforward Policy For Diverse, Precise Generative Path Forecasting", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Nicholas_Rhinehart_R2P2_A_ReparameteRized_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#meanmsd">meanMSD</a></li>
<li><a href="metrics.md#minmsd">minMSD</a></li>
<li><a href="metrics.md#ce">CE</a></li>
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
</ul>
</details>

<a name=ande></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Average Nonlinear Displacement Error (ANDE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Xu et al., "Encoding Crowd Interaction With Deep Neural Network For Pedestrian Trajectory Prediction", CVPR, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/2136.pdf>paper</a> <a href=https://github.com/svip-lab/CIDNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="datasets/year_datasets.md#gc">GC</a></li>
<li><a href="datasets/year_datasets.md#chuk">CHUK</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#ande">ANDE</a></li>
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
<summary><strong><em>Alahi et al., "Social Lstm: Human Trajectory Prediction In Crowded Spaces", CVPR, 2016.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Alahi_Social_LSTM_Human_CVPR_2016_paper.pdf>paper</a> <a href=https://github.com/quancore/social-lstm>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#ande">ANDE</a></li>
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
</ul>
</details>

<a name=miss_rate></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Miss rate</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Felsen et al., "Where Will They Go? Predicting Fine-Grained Adversarial Multi-Agent Motion Using Conditional Variational Autoencoders", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Panna_Felsen_Where_Will_They_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#miss_rate">Miss rate</a></li>
<li><a href="metrics.md#maxd">maxD</a></li>
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
<summary><strong><em>Lee et al., "Desire: Distant Future Prediction In Dynamic Scenes With Interacting Agents", CVPR, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lee_DESIRE_Distant_Future_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1704.04394.pdf>arxiv</a> <a href=https://github.com/yadrimz/DESIRE>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ed">ED</a></li>
<li><a href="metrics.md#mined">minED</a></li>
<li><a href="metrics.md#maxd">maxD</a></li>
<li><a href="metrics.md#miss_rate">Miss rate</a></li>
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
</ul>
</details>

<a name=accuracy></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Accuracy</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Kim et al., "Instance-Level Future Motion Estimation In A Single Image Based On Ordinal Regression", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Kim_Instance-Level_Future_Motion_Estimation_in_a_Single_Image_Based_on_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#fm">FM</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Solaimanpour et al., "A Layered Hmm For Predicting Motion Of A Leader In Multi-Robot Settings", ICRA, 2017.</em></strong> <a href=https://ieeexplore.ieee.org/document/7989097>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#kld">KLD</a></li>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Solaimanpour_2017_ICRA,
    author = "Solaimanpour, S. and Doshi, P.",
    booktitle = "ICRA",
    title = "A Layered Hmm For Predicting Motion Of A Leader In Multi-Robot Settings",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

<a name=mined></a>
<details close>
<summary><em><l style="font-size:20px"><strong>minED</strong></l>
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
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#hit_rate">Hit Rate</a></li>
<li><a href="metrics.md#mined">minED</a></li>
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
<summary><strong><em>Lee et al., "Desire: Distant Future Prediction In Dynamic Scenes With Interacting Agents", CVPR, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lee_DESIRE_Distant_Future_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1704.04394.pdf>arxiv</a> <a href=https://github.com/yadrimz/DESIRE>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ed">ED</a></li>
<li><a href="metrics.md#mined">minED</a></li>
<li><a href="metrics.md#maxd">maxD</a></li>
<li><a href="metrics.md#miss_rate">Miss rate</a></li>
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
</ul>
</details>

<a name=minfde></a>
<details close>
<summary><em><l style="font-size:20px"><strong>minFDE</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Chang et al., "Argoverse: 3D Tracking And Forecasting With Rich Maps", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_Argoverse_3D_Tracking_and_Forecasting_With_Rich_Maps_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.02620.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#argoverse">ARGOVerse</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#minade">minADE</a></li>
<li><a href="metrics.md#minfde">minFDE</a></li>
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
<details close>
<summary><strong><em>Li, "Which Way Are You Going? Imitative Decision Learning For Path Forecasting In Dynamic Scenes", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Which_Way_Are_You_Going_Imitative_Decision_Learning_for_Path_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="datasets/year_datasets.md#sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#minade">minADE</a></li>
<li><a href="metrics.md#minfde">minFDE</a></li>
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
</ul>
</details>

<a name=minmsd></a>
<details close>
<summary><em><l style="font-size:20px"><strong>minMSD</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Rhinehart et al., "Precog: Prediction Conditioned On Goals In Visual Multi-Agent Settings", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rhinehart_PRECOG_PREdiction_Conditioned_on_Goals_in_Visual_Multi-Agent_Settings_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.01296.pdf>arxiv</a> <a href=https://sites.google.com/view/precog>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#carla">CARLA</a></li>
<li><a href="datasets/year_datasets.md#nuscenes">nuScenes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#meanmsd">meanMSD</a></li>
<li><a href="metrics.md#minmsd">minMSD</a></li>
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
<summary><strong><em>Rhinehart et al., "R2P2: A Reparameterized Pushforward Policy For Diverse, Precise Generative Path Forecasting", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Nicholas_Rhinehart_R2P2_A_ReparameteRized_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#meanmsd">meanMSD</a></li>
<li><a href="metrics.md#minmsd">minMSD</a></li>
<li><a href="metrics.md#ce">CE</a></li>
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
</ul>
</details>

<a name=mse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Square Error (MSE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Casas et al., "Intentnet: Learning To Predict Intention From Raw Sensor Data", CORL, 2018.</em></strong> <a href=http://proceedings.mlr.press/v87/casas18a/casas18a.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mse">MSE</a></li>
<li><a href="metrics.md#l1">L1</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Casas_2018_CORL,
    author = "Casas, Sergio and Luo, Wenjie and Urtasun, Raquel",
    title = "Intentnet: Learning To Predict Intention From Raw Sensor Data",
    booktitle = "CORL",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Lee et al., "Predicting Wide Receiver Trajectories In American Football", WACV, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7477732>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#osu">OSU</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#nll">NLL</a></li>
<li><a href="metrics.md#kld">KLD</a></li>
<li><a href="metrics.md#mhd">MHD</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
<li><a href="metrics.md#dtg">DtG</a></li>
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
</ul>
</details>

<a name=maxd></a>
<details close>
<summary><em><l style="font-size:20px"><strong>maxD</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Felsen et al., "Where Will They Go? Predicting Fine-Grained Adversarial Multi-Agent Motion Using Conditional Variational Autoencoders", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Panna_Felsen_Where_Will_They_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#miss_rate">Miss rate</a></li>
<li><a href="metrics.md#maxd">maxD</a></li>
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
<summary><strong><em>Lee et al., "Desire: Distant Future Prediction In Dynamic Scenes With Interacting Agents", CVPR, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lee_DESIRE_Distant_Future_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1704.04394.pdf>arxiv</a> <a href=https://github.com/yadrimz/DESIRE>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/year_datasets.md#sd">SD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ed">ED</a></li>
<li><a href="metrics.md#mined">minED</a></li>
<li><a href="metrics.md#maxd">maxD</a></li>
<li><a href="metrics.md#miss_rate">Miss rate</a></li>
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
</ul>
</details>

<a name=scr></a>
<details close>
<summary><em><l style="font-size:20px"><strong>State Collision Rate (SCR)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Ma et al., "Forecasting Interactive Dynamics Of Pedestrians With Fictitious Play", CVPR, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Ma_Forecasting_Interactive_Dynamics_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1604.01431.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#town_center">Town Center</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#nll">NLL</a></li>
<li><a href="metrics.md#scr">SCR</a></li>
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
</ul>
</details>

<a name=wrmse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>WRMSE</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Schulz et al., "Interaction-Aware Probabilistic Behavior Prediction In Urban Environments", IROS, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8594095>paper</a> <a href=https://arxiv.org/pdf/1804.10467.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ll">LL</a></li>
<li><a href="metrics.md#wrmse">WRMSE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Schulz_2018_IROS,
    author = "Schulz, J. and Hubmann, C. and Löchner, J. and Burschka, D.",
    booktitle = "IROS",
    title = "Interaction-Aware Probabilistic Behavior Prediction In Urban Environments",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

<a name=app></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Average Prediction Probability (APP)</strong></l>
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
<li><a href="metrics.md#app">APP</a></li>
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

<a name=l1></a>
<details close>
<summary><em><l style="font-size:20px"><strong>L1</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Casas et al., "Intentnet: Learning To Predict Intention From Raw Sensor Data", CORL, 2018.</em></strong> <a href=http://proceedings.mlr.press/v87/casas18a/casas18a.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mse">MSE</a></li>
<li><a href="metrics.md#l1">L1</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Casas_2018_CORL,
    author = "Casas, Sergio and Luo, Wenjie and Urtasun, Raquel",
    title = "Intentnet: Learning To Predict Intention From Raw Sensor Data",
    booktitle = "CORL",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

<a name=mane></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean angular error (MAnE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Hasan et al., ""Seeing Is Believing": Pedestrian Trajectory Forecasting Using Visual Frustum Of Attention", WACV, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8354238>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="datasets/year_datasets.md#town_center">Town Center</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#mane">MAnE</a></li>
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
</ul>
</details>

<a name=aede></a>
<details close>
<summary><em><l style="font-size:20px"><strong>AEDE</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Sun et al., "3Dof Pedestrian Trajectory Prediction Learned From Long-Term Autonomous Mobile Robot Deployment Data", ICRA, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8461228>paper</a> <a href=https://arxiv.org/pdf/1710.00126.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#strands">STRANDS</a></li>
<li><a href="datasets/year_datasets.md#l-cas">L-CAS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#aede">AEDE</a></li>
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
</ul>
</details>

<a name=pd></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Percentage Deviated (PD)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Shkurti et al., "Topologically Distinct Trajectory Predictions For Probabilistic Pursuit", IROS, 2017.</em></strong> <a href=https://ieeexplore.ieee.org/document/8206454>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#pd">PD</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shkurti_2017_IROS,
    author = "Shkurti, F. and Dudek, G.",
    booktitle = "IROS",
    title = "Topologically Distinct Trajectory Predictions For Probabilistic Pursuit",
    year = "2017"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

<a name=ce></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Cross Entropy (CE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Rhinehart et al., "R2P2: A Reparameterized Pushforward Policy For Diverse, Precise Generative Path Forecasting", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Nicholas_Rhinehart_R2P2_A_ReparameteRized_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#meanmsd">meanMSD</a></li>
<li><a href="metrics.md#minmsd">minMSD</a></li>
<li><a href="metrics.md#ce">CE</a></li>
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
</ul>
</details>

<a name=dtg></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Distance to Goal (DtG)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Lee et al., "Predicting Wide Receiver Trajectories In American Football", WACV, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/document/7477732>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#osu">OSU</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#nll">NLL</a></li>
<li><a href="metrics.md#kld">KLD</a></li>
<li><a href="metrics.md#mhd">MHD</a></li>
<li><a href="metrics.md#mse">MSE</a></li>
<li><a href="metrics.md#dtg">DtG</a></li>
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
</ul>
</details>

<a name=none></a>
<details close>
<summary><em><l style="font-size:20px"><strong>None</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>M\ogelmose et al., "Trajectory Analysis And Prediction For Improved Pedestrian Safety: Integrated Framework And Evaluations", IV, 2015.</em></strong> <a href=https://ieeexplore.ieee.org/document/7225707>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#none">None</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mogelmose_2015_IV,
    author = "M\ogelmose, Andreas and Trivedi, Mohan M and Moeslund, Thomas B",
    title = "Trajectory Analysis And Prediction For Improved Pedestrian Safety: Integrated Framework And Evaluations",
    booktitle = "IV",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

<a name=precision></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Precision</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Yoo et al., "Visual Path Prediction In Complex Scenes With Crowded Moving Objects", CVPR, 2016.</em></strong> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Yoo_Visual_Path_Prediction_CVPR_2016_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#gc">GC</a></li>
<li><a href="datasets/year_datasets.md#qmul">QMUL</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
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
</ul>
</details>

<a name=fnm></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Fraction of Near Misses (FNM)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Bai et al., "Intention-Aware Online Pomdp Planning For Autonomous Driving In A Crowd", ICRA, 2015.</em></strong> <a href=https://ieeexplore.ieee.org/document/7139219>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#fnm">FNM</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bai_2015_ICRA,
    author = "Bai, Haoyu and Cai, Shaojun and Ye, Nan and Hsu, David and Lee, Wee Sun",
    title = "Intention-Aware Online Pomdp Planning For Autonomous Driving In A Crowd",
    booktitle = "ICRA",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

<a name=ece></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Expected Calibration Error (ECE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Jain et al., "Discrete Residual Flow For Probabilistic Pedestrian Behavior Prediction", CoRL, 2019.</em></strong> <a href=http://proceedings.mlr.press/v100/jain20a/jain20a.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.08041.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ade">ADE</a></li>
<li><a href="metrics.md#fde">FDE</a></li>
<li><a href="metrics.md#nll">NLL</a></li>
<li><a href="metrics.md#ece">ECE</a></li>
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

</ul><a name=metrics_motion></a>
<h2 style="color:#c12fdc">  Motion Prediction </h2><a href=#top>&uarr; top</a>
<ul><a name=mje></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Joint Error (MJE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Joo et al., "Towards Social Artificial Intelligence: Nonverbal Social Signal Prediction In A Triadic Interaction", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Joo_Towards_Social_Artificial_Intelligence_Nonverbal_Social_Signal_Prediction_in_a_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.04158.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mje">MJE</a></li>
<li><a href="metrics.md#lo">LO</a></li>
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
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#mouse_fish">Mouse Fish</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mje">MJE</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
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
<li><a href="datasets/year_datasets.md#egopose">EgoPose</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mje">MJE</a></li>
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
<li><a href="metrics.md#mje">MJE</a></li>
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
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mje">MJE</a></li>
<li><a href="metrics.md#pck">PCK</a></li>
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
<summary><strong><em>Wu et al., "Futurepose - Mixed Reality Martial Arts Training Using Real-Time 3D Human Pose Forecasting With A Rgb Camera", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8658594>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mje">MJE</a></li>
<li><a href="metrics.md#pck">PCK</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wu_2019_WACV,
    author = "Wu, E. and Koike, H.",
    booktitle = "WACV",
    title = "Futurepose - Mixed Reality Martial Arts Training Using Real-Time 3D Human Pose Forecasting With A Rgb Camera",
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
<li><a href="datasets/year_datasets.md#sbuki">SBUKI</a></li>
<li><a href="datasets/year_datasets.md#ca">CA</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mje">MJE</a></li>
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
<li><a href="metrics.md#mje">MJE</a></li>
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
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mje">MJE</a></li>
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
<li><a href="datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mje">MJE</a></li>
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
<li><a href="metrics.md#mje">MJE</a></li>
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

<a name=mane></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean angular error (MAnE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Gopalakrishnan et al., "A Neural Temporal Model For Human Motion Prediction", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Gopalakrishnan_A_Neural_Temporal_Model_for_Human_Motion_Prediction_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1809.03036.pdf>arxiv</a> <a href=https://github.com/cr7anand/neural_temporal_models>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mane">MAnE</a></li>
<li><a href="metrics.md#npss">NPSS</a></li>
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
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mane">MAnE</a></li>
<li><a href="metrics.md#human">Human</a></li>
<li><a href="metrics.md#pskl">PSKL</a></li>
<li><a href="metrics.md#psent">PSEnt</a></li>
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
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="datasets/year_datasets.md#3dpw">3DPW</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mane">MAnE</a></li>
<li><a href="metrics.md#mpjpe">MPJPE</a></li>
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
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mane">MAnE</a></li>
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
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mane">MAnE</a></li>
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
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mane">MAnE</a></li>
<li><a href="metrics.md#human">Human</a></li>
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
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mane">MAnE</a></li>
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
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mane">MAnE</a></li>
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
<summary><strong><em>Jain et al., "Structural-Rnn: Deep Learning On Spatio-Temporal Graphs", CVPR, 2016.</em></strong> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.05298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mane">MAnE</a></li>
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
<summary><strong><em>Fragkiadaki et al., "Recurrent Network Models For Human Dynamics", ICCV, 2015.</em></strong> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Fragkiadaki_Recurrent_Network_Models_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1508.00271.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mane">MAnE</a></li>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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

<a name=pck></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Percentage of Correct Keypoints (PCK)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Zhang et al., "Predicting 3D Human Dynamics From Video", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Predicting_3D_Human_Dynamics_From_Video_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.04781.pdf>arxiv</a> <a href={https://jasonyzhang.com/phd/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="datasets/year_datasets.md#instavariety">InstaVariety</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#pck">PCK</a></li>
<li><a href="metrics.md#mpjpe">MPJPE</a></li>
<li><a href="metrics.md#re">RE</a></li>
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
<summary><strong><em>Chiu et al., "Action-Agnostic Human Pose Forecasting", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8658717>paper</a> <a href=https://arxiv.org/pdf/1810.09676.pdf>arxiv</a> <a href=https://github.com/eddyhkchiu/pose_forecast_wacv/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mje">MJE</a></li>
<li><a href="metrics.md#pck">PCK</a></li>
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
<summary><strong><em>Wu et al., "Futurepose - Mixed Reality Martial Arts Training Using Real-Time 3D Human Pose Forecasting With A Rgb Camera", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8658594>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mje">MJE</a></li>
<li><a href="metrics.md#pck">PCK</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wu_2019_WACV,
    author = "Wu, E. and Koike, H.",
    booktitle = "WACV",
    title = "Futurepose - Mixed Reality Martial Arts Training Using Real-Time 3D Human Pose Forecasting With A Rgb Camera",
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
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="datasets/year_datasets.md#mpii_human_pose">MPII Human Pose</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#pck">PCK</a></li>
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
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#mouse_fish">Mouse Fish</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mje">MJE</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
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
<summary><strong><em>Wu et al., "Futurepose - Mixed Reality Martial Arts Training Using Real-Time 3D Human Pose Forecasting With A Rgb Camera", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8658594>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mje">MJE</a></li>
<li><a href="metrics.md#pck">PCK</a></li>
<li><a href="metrics.md#run_time">Run Time</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wu_2019_WACV,
    author = "Wu, E. and Koike, H.",
    booktitle = "WACV",
    title = "Futurepose - Mixed Reality Martial Arts Training Using Real-Time 3D Human Pose Forecasting With A Rgb Camera",
    year = "2019"
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
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mane">MAnE</a></li>
<li><a href="metrics.md#human">Human</a></li>
<li><a href="metrics.md#pskl">PSKL</a></li>
<li><a href="metrics.md#psent">PSEnt</a></li>
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
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mane">MAnE</a></li>
<li><a href="metrics.md#human">Human</a></li>
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
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mane">MAnE</a></li>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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

<a name=mpjpe></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Per Joint Prediction Error (MPJPE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Mao et al., "Learning Trajectory Dependencies For Human Motion Prediction", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Mao_Learning_Trajectory_Dependencies_for_Human_Motion_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.05436.pdf>arxiv</a> <a href=https://github.com/wei-mao-2019/LearnTrajDep>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="datasets/year_datasets.md#3dpw">3DPW</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mane">MAnE</a></li>
<li><a href="metrics.md#mpjpe">MPJPE</a></li>
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
<summary><strong><em>Zhang et al., "Predicting 3D Human Dynamics From Video", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Predicting_3D_Human_Dynamics_From_Video_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.04781.pdf>arxiv</a> <a href={https://jasonyzhang.com/phd/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="datasets/year_datasets.md#instavariety">InstaVariety</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#pck">PCK</a></li>
<li><a href="metrics.md#mpjpe">MPJPE</a></li>
<li><a href="metrics.md#re">RE</a></li>
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
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mane">MAnE</a></li>
<li><a href="metrics.md#human">Human</a></li>
<li><a href="metrics.md#pskl">PSKL</a></li>
<li><a href="metrics.md#psent">PSEnt</a></li>
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
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mane">MAnE</a></li>
<li><a href="metrics.md#human">Human</a></li>
<li><a href="metrics.md#pskl">PSKL</a></li>
<li><a href="metrics.md#psent">PSEnt</a></li>
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

<a name=re></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Reconstruction Error (RE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Zhang et al., "Predicting 3D Human Dynamics From Video", ICCV, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Predicting_3D_Human_Dynamics_From_Video_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.04781.pdf>arxiv</a> <a href={https://jasonyzhang.com/phd/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="datasets/year_datasets.md#instavariety">InstaVariety</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#pck">PCK</a></li>
<li><a href="metrics.md#mpjpe">MPJPE</a></li>
<li><a href="metrics.md#re">RE</a></li>
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
<li><a href="datasets/year_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mje">MJE</a></li>
<li><a href="metrics.md#lo">LO</a></li>
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
<li><a href="datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mane">MAnE</a></li>
<li><a href="metrics.md#npss">NPSS</a></li>
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

</ul><a name=metrics_other></a>
<h2 style="color:#bd831f">  Other Prediction </h2><a href=#top>&uarr; top</a>
<ul><a name=accuracy></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Accuracy</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Zeng et al., "Visual Forecasting By Imitating Dynamics In Natural Sequences", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Zeng_Visual_Forecasting_by_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.05827.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#vist">VIST</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="datasets/year_datasets.md#mu">MU</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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
<summary><strong><em>Joo et al., "Automated Facial Trait Judgment And Election Outcome Prediction: Social Dimensions Of Face", ICCV, 2015.</em></strong> <a href=https://openaccess.thecvf.com/content_iccv_2015/papers/Joo_Panoptic_Studio_A_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1612.03153.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#accuracy">Accuracy</a></li>
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

<a name=iou></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Intersection over Union (IoU)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Terwilliger et al., "Recurrent Flow-Guided Semantic Forecasting", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8658639>paper</a> <a href=https://arxiv.org/pdf/1809.08318.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#iou">IoU</a></li>
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
<summary><strong><em>Luc et al., "Predicting Future Instance Segmentation By Forecasting Convolutional Features", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Pauline_Luc_Predicting_Future_Instance_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1803.11496.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#iou">IoU</a></li>
<li><a href="metrics.md#voi">VoI</a></li>
<li><a href="metrics.md#gce">GCE</a></li>
<li><a href="metrics.md#ri">RI</a></li>
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
<summary><strong><em>Luc et al., "Predicting Deeper Into The Future Of Semantic Segmentation", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Luc_Predicting_Deeper_Into_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1703.07684.pdf>arxiv</a> <a href=https://github.com/facebookresearch/SegmPred>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#iou">IoU</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#psnr">PSNR</a></li>
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

<a name=mae></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Absolute Error (MAE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>He et al., "Aggregated Sparse Attention For Steering Angle Prediction", ICPR, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8546051>paper</a> <a href=https://arxiv.org/pdf/1803.05785.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#diplecs">DIPLECS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mae">MAE</a></li>
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
<li><a href="datasets/year_datasets.md#amazon">Amazon</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mae">MAE</a></li>
<li><a href="metrics.md#mape">MAPE</a></li>
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
<summary><strong><em>Wilson et al., "Vehicle State Prediction For Outdoor Autonomous High-Speed Off-Road Ugvs", ICRA, 2015.</em></strong> <a href=https://ieeexplore.ieee.org/document/7139221>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mae">MAE</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wilson_2015_ICRA,
    author = "Wilson, G. N. and Ramirez-Serrano, A. and Sun, Q.",
    booktitle = "ICRA",
    title = "Vehicle State Prediction For Outdoor Autonomous High-Speed Off-Road Ugvs",
    year = "2015"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

<a name=recall></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Recall</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Choi et al., "Robust Modeling And Prediction In Dynamic Environments Using Recurrent Flow Networks", IROS, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/7759278>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#fcvl">FCVL</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#run_time">Run Time</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#auc">AUC</a></li>
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
<details close>
<summary><strong><em>Kim et al., "Deep-Hurricane-Tracker: Tracking And Forecasting Extreme Climate Events", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8658402>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
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
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#mcc">MCC</a></li>
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

<a name=run_time></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Run Time</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Mohajerin et al., "Multi-Step Prediction Of Occupancy Grid Maps With Recurrent Neural Networks", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Mohajerin_Multi-Step_Prediction_of_Occupancy_Grid_Maps_With_Recurrent_Neural_Networks_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.09395.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#run_time">Run Time</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#tp">TP</a></li>
<li><a href="metrics.md#tn">TN</a></li>
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
<li><a href="metrics.md#run_time">Run Time</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#psnr">PSNR</a></li>
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
<li><a href="datasets/year_datasets.md#fcvl">FCVL</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#run_time">Run Time</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#auc">AUC</a></li>
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

<a name=precision></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Precision</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Choi et al., "Robust Modeling And Prediction In Dynamic Environments Using Recurrent Flow Networks", IROS, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/7759278>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#fcvl">FCVL</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#run_time">Run Time</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#auc">AUC</a></li>
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
<details close>
<summary><strong><em>Kim et al., "Deep-Hurricane-Tracker: Tracking And Forecasting Extreme Climate Events", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8658402>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
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
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#mcc">MCC</a></li>
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

<a name=ssim></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Structural SIMilarity (SSIM)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Mohajerin et al., "Multi-Step Prediction Of Occupancy Grid Maps With Recurrent Neural Networks", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Mohajerin_Multi-Step_Prediction_of_Occupancy_Grid_Maps_With_Recurrent_Neural_Networks_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.09395.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#run_time">Run Time</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#tp">TP</a></li>
<li><a href="metrics.md#tn">TN</a></li>
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
<li><a href="metrics.md#run_time">Run Time</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#psnr">PSNR</a></li>
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
<li><a href="datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#iou">IoU</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#psnr">PSNR</a></li>
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

<a name=ed></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Euclidean Distance (ED)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Graves et al., "Perception As Prediction Using General Value Functions In Autonomous Driving Applications", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8968293>paper</a> <a href=https://arxiv.org/pdf/2001.09113.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ed">ED</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Graves_2019_IROS,
    author = "Graves, Daniel and Rezaee, Kasra and Scheideman, Sean",
    booktitle = "IROS",
    title = "Perception As Prediction Using General Value Functions In Autonomous Driving Applications",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><strong><em>Zapf et al., "Pedestrian Density Prediction For Efficient Mobile Robot Exploration", IROS, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8967763>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#ed">ED</a></li>
</ul>

<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zapf_2019_IROS,
    author = "Zapf, Marc Patrick and Kawanabe, Motoaki and Morales Saiki, Luis Yoichi",
    booktitle = "IROS",
    title = "Pedestrian Density Prediction For Efficient Mobile Robot Exploration",
    year = "2019"
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
<summary><strong><em>Wang et al., "Retweet Wars: Tweet Popularity Prediction Via Dynamic Multimodal Regression", WACV, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8354308>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#mbi-1m">MBI-1M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mape">MAPE</a></li>
<li><a href="metrics.md#src">SRC</a></li>
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
<li><a href="datasets/year_datasets.md#amazon">Amazon</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mae">MAE</a></li>
<li><a href="metrics.md#mape">MAPE</a></li>
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

<a name=psnr></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Peak Signal-to-Noise Ratio (PSNR)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Katyal et al., "Uncertainty-Aware Occupancy Map Prediction Using Generative Networks For Robot Navigation", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8793500>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#run_time">Run Time</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#psnr">PSNR</a></li>
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
<li><a href="datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#iou">IoU</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#psnr">PSNR</a></li>
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

<a name=roc></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Receiver Operator Characteristic (ROC)</strong></l>
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
<li><a href="metrics.md#roc">ROC</a></li>
<li><a href="metrics.md#f1">F1</a></li>
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
<li><a href="metrics.md#roc">ROC</a></li>
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

<a name=f1></a>
<details close>
<summary><em><l style="font-size:20px"><strong>F1</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Guizilini et al., "Dynamic Hilbert Maps: Real-Time Occupancy Predictions In Changing Environments", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/document/8793914>paper</a> <a href=https://arxiv.org/pdf/1912.02149.pdf>arxiv</a> <a href=https://bitbucket.org/vguizilini/cvpp/src>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#f1">F1</a></li>
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
<details close>
<summary><strong><em>Schreiber et al., "Long-Term Occupancy Grid Prediction Using Recurrent Neural Networks", ICRA, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8793582>paper</a> <a href=https://arxiv.org/pdf/1809.03782.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li>Custom</li>

</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#roc">ROC</a></li>
<li><a href="metrics.md#f1">F1</a></li>
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
</ul>
</details>

<a name=psi></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Psi</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Afolabi et al., "People As Sensors: Imputing Maps From Human Actions", IROS, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8594511>paper</a> <a href=https://arxiv.org/pdf/1711.01022.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psi">Psi</a></li>
<li><a href="metrics.md#ism">ISM</a></li>
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

<a name=miou></a>
<details close>
<summary><em><l style="font-size:20px"><strong>MIoU</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Jin et al., "Predicting Scene Parsing And Motion Dynamics In The Future", NeurIPS, 2017.</em></strong> <a href=https://papers.nips.cc/paper/7267-predicting-scene-parsing-and-motion-dynamics-in-the-future.pdf>paper</a> <a href=https://arxiv.org/pdf/1711.03270.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mse">MSE</a></li>
<li><a href="metrics.md#miou">MIoU</a></li>
<li><a href="metrics.md#epe">EPE</a></li>
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

<a name=pcp></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Percentage of Correct Predictions (PCP)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Mottaghi et al., "What Happens If... Learning To Predict The Effect Of Forces In Images", ECCV, 2016.</em></strong> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46493-0_17>paper</a> <a href=https://arxiv.org/pdf/1603.05600.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#sun_rgb-d">SUN RGB-D</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#pcp">PCP</a></li>
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

<a name=voi></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Variation of Information (VoI)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Luc et al., "Predicting Future Instance Segmentation By Forecasting Convolutional Features", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Pauline_Luc_Predicting_Future_Instance_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1803.11496.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#iou">IoU</a></li>
<li><a href="metrics.md#voi">VoI</a></li>
<li><a href="metrics.md#gce">GCE</a></li>
<li><a href="metrics.md#ri">RI</a></li>
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

<a name=src></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Spearman’s Ranking Correlation (SRC)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Wang et al., "Retweet Wars: Tweet Popularity Prediction Via Dynamic Multimodal Regression", WACV, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8354308>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#mbi-1m">MBI-1M</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mape">MAPE</a></li>
<li><a href="metrics.md#src">SRC</a></li>
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

<a name=gce></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Global Consistency Error (GCE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Luc et al., "Predicting Future Instance Segmentation By Forecasting Convolutional Features", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Pauline_Luc_Predicting_Future_Instance_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1803.11496.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#iou">IoU</a></li>
<li><a href="metrics.md#voi">VoI</a></li>
<li><a href="metrics.md#gce">GCE</a></li>
<li><a href="metrics.md#ri">RI</a></li>
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

<a name=mcc></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Matthews Correlation Coefficient (MCC)</strong></l>
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
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#mcc">MCC</a></li>
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

<a name=nmape></a>
<details close>
<summary><em><l style="font-size:20px"><strong>normalized Mean Absolute Percentage Error (nMAPE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Siddiqui et al., "A Deep Learning Approach To Solar-Irradiance Forecasting In Sky-Videos", WACV, 2019.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/8659184>paper</a> <a href=https://arxiv.org/pdf/1901.04881.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#arizona">Arizona</a></li>
<li><a href="datasets/year_datasets.md#tuscan">Tuscan</a></li>
<li><a href="datasets/year_datasets.md#golden_colorado">Golden Colorado</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#nmape">nMAPE</a></li>
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

<a name=auc></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Area Under the Curve (AUC)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Choi et al., "Robust Modeling And Prediction In Dynamic Environments Using Recurrent Flow Networks", IROS, 2016.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/7759278>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#fcvl">FCVL</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#run_time">Run Time</a></li>
<li><a href="metrics.md#recall">Recall</a></li>
<li><a href="metrics.md#precision">Precision</a></li>
<li><a href="metrics.md#auc">AUC</a></li>
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

<a name=mse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Mean Square Error (MSE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Jin et al., "Predicting Scene Parsing And Motion Dynamics In The Future", NeurIPS, 2017.</em></strong> <a href=https://papers.nips.cc/paper/7267-predicting-scene-parsing-and-motion-dynamics-in-the-future.pdf>paper</a> <a href=https://arxiv.org/pdf/1711.03270.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mse">MSE</a></li>
<li><a href="metrics.md#miou">MIoU</a></li>
<li><a href="metrics.md#epe">EPE</a></li>
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

<a name=ism></a>
<details close>
<summary><em><l style="font-size:20px"><strong>ISM</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Afolabi et al., "People As Sensors: Imputing Maps From Human Actions", IROS, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8594511>paper</a> <a href=https://arxiv.org/pdf/1711.01022.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#psi">Psi</a></li>
<li><a href="metrics.md#ism">ISM</a></li>
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

<a name=ri></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Rand Index (RI)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Luc et al., "Predicting Future Instance Segmentation By Forecasting Convolutional Features", ECCV, 2018.</em></strong> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Pauline_Luc_Predicting_Future_Instance_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1803.11496.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#iou">IoU</a></li>
<li><a href="metrics.md#voi">VoI</a></li>
<li><a href="metrics.md#gce">GCE</a></li>
<li><a href="metrics.md#ri">RI</a></li>
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

<a name=rmse></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Root Mean Square Error (RMSE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Chu et al., "Visual Weather Temperature Prediction", WACV, 2018.</em></strong> <a href=https://ieeexplore.ieee.org/document/8354136>paper</a> <a href=https://arxiv.org/pdf/1801.08267.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#amos">AMOS</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#rmse">RMSE</a></li>
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
</ul>
</details>

<a name=epe></a>
<details close>
<summary><em><l style="font-size:20px"><strong>End-Point Error (EPE)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Jin et al., "Predicting Scene Parsing And Motion Dynamics In The Future", NeurIPS, 2017.</em></strong> <a href=https://papers.nips.cc/paper/7267-predicting-scene-parsing-and-motion-dynamics-in-the-future.pdf>paper</a> <a href=https://arxiv.org/pdf/1711.03270.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#mse">MSE</a></li>
<li><a href="metrics.md#miou">MIoU</a></li>
<li><a href="metrics.md#epe">EPE</a></li>
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

<a name=tn></a>
<details close>
<summary><em><l style="font-size:20px"><strong>True Negative (TN)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Mohajerin et al., "Multi-Step Prediction Of Occupancy Grid Maps With Recurrent Neural Networks", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Mohajerin_Multi-Step_Prediction_of_Occupancy_Grid_Maps_With_Recurrent_Neural_Networks_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.09395.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#run_time">Run Time</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#tp">TP</a></li>
<li><a href="metrics.md#tn">TN</a></li>
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

<a name=tp></a>
<details close>
<summary><em><l style="font-size:20px"><strong>True Positive (TP)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Mohajerin et al., "Multi-Step Prediction Of Occupancy Grid Maps With Recurrent Neural Networks", CVPR, 2019.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Mohajerin_Multi-Step_Prediction_of_Occupancy_Grid_Maps_With_Recurrent_Neural_Networks_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.09395.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>

<em>Metrics</em>
<ul>
<li><a href="metrics.md#run_time">Run Time</a></li>
<li><a href="metrics.md#ssim">SSIM</a></li>
<li><a href="metrics.md#tp">TP</a></li>
<li><a href="metrics.md#tn">TN</a></li>
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

</ul>