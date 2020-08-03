<a name=top></a>
<a name=top></a>
---
<a href=../README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Datasets</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../metrics.md#top><l style="font-size:30px">Metrics</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
[Home](datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Year](year_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Application&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Task](task_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Annotation](annotation_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
<h2>Datasets by Application</h2> 
Below is the list of datasets grouped according to their applications.Within each group, the datasets are **sorted** based on their **popularity**, (i.e how often they are used in prediction papers).

 Each dataset in the list has an associated link to the publication page and/or arxiv preprint if available. By **clicking on the dataset** you can get the following information:

* **Summary** of the dataset's characteristics, e.g. quantity, number of objects or classes, etc.
* **Applications** that use the dataset
* **Data type and annotations** available in the dataset
* **Task** of the dataset, e.g. driving, activity, etc
* **Papers** that used the dataset in chronological order
* **Bibtext** of the dataset

<a name=datasets_Video></a>
<h2>Video</h2> <a href=#top>&uarr; top</a>
<ul><a name=human3.6m></a>
<details close>
<summary><l style="font-size:20px"><strong>Human3.6M</strong></l> <a href=http://vision.imar.ro/human3.6m/description.php>link</a> <a href=https://ieeexplore.ieee.org/document/6682899>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale dataset of 3D human poses with 3M+ images captured using 11 professional actors in 17 scenarios, such as discussion, smoking, taking photo, etc.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Le et al., "Disentangling Physical Dynamics From Unknown Factors for Unsupervised Video Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Le_Guen_Disentangling_Physical_Dynamics_From_Unknown_Factors_for_Unsupervised_Video_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.01460.pdf>arxiv</a> <a href=https://github.com/vincent-leguen/PhyDNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#sst">SST</a></li>
<li><a href="../datasets/year_datasets.md#taxi_bj">Taxi BJ</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
<li><a href="../metrics.md#mae">MAE</a></li>
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
<summary><em>Xu et al., "Structure Preserving Video Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers_backup/Xu_Structure_Preserving_Video_CVPR_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#human">Human</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#human">Human</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<summary><em>Aliakbarian et al., "A Stochastic Conditioning Scheme for Diverse Human Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Aliakbarian_A_Stochastic_Conditioning_Scheme_for_Diverse_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://github.com/mix-and-match/mix-and-match-tutorial>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#kld">KLD</a></li>
<li><a href="../metrics.md#si">SI</a></li>
<li><a href="../metrics.md#kl">KL</a></li>
<li><a href="../metrics.md#s-mse">S-MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../datasets/year_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#mpjpe">MPJPE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2020_CVPR,
    author = "Li, Maosen and Chen, Siheng and Zhao, Yangheng and Zhang, Ya and Wang, Yanfeng and Tian, Qi",
    title = "Dynamic Multiscale Graph Neural Networks for 3D Skeleton Based Human Motion Prediction",
    booktitle = "CVPR",
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#npss">NPSS</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mouse_fish">Mouse Fish</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mje">MJE</a></li>
<li><a href="../metrics.md#run_time">Run Time</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#human">Human</a></li>
<li><a href="../metrics.md#pskl">PSKL</a></li>
<li><a href="../metrics.md#psent">PSEnt</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../datasets/year_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#mpjpe">MPJPE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#instavariety">InstaVariety</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#pck">PCK</a></li>
<li><a href="../metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../metrics.md#re">RE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mje">MJE</a></li>
<li><a href="../metrics.md#pck">PCK</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#human">Human</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#mpii_human_pose">MPII Human Pose</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#pck">PCK</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=ucf-101></a>
<details close>
<summary><l style="font-size:20px"><strong>UCF-101</strong></l> <a href=https://www.crcv.ucf.edu/data/UCF101.php>link</a> <a href=https://arxiv.org/pdf/1212.0402.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale dataset of 101 actions with 13K+ video clips divided into 5 groups of human-object interaction, body-motion only, human-human interaction, playing musical instruments, and sports
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle Gan", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#chuk_avenue">CHUK Avenue</a></li>
<li><a href="../datasets/year_datasets.md#shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#yuv">YUV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Liu et al., "Dyan: A Dynamical Atoms-Based Network For Video Prediction", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Wenqian_Liu_DYAN_A_Dynamical_ECCV_2018_paper.pdf>paper</a> <a href=https://github.com/liuem607/DYAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
<li><a href="../datasets/year_datasets.md#visor">ViSOR</a></li>
<li><a href="../datasets/year_datasets.md#prost">PROST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Liang et al., "Dual Motion Gan For Future-Flow Embedded Video Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Liang_Dual_Motion_GAN_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00284.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#is">IS</a></li>
<li><a href="../metrics.md#mmd">MMD</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
<li><a href="../datasets/year_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
<li><a href="../datasets/year_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#willow_action">Willow Action</a></li>
<li><a href="../datasets/year_datasets.md#wider">WIDER</a></li>
<li><a href="../datasets/year_datasets.md#stanford-40">Stanford-40</a></li>
<li><a href="../datasets/year_datasets.md#bu_action">BU Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#map">mAP</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#hmdb">HMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#bit">BIT</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<summary><em>Singh et al., "Online Real-Time Multiple Spatiotemporal Action Localisation And Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Singh_Online_Real-Time_Multiple_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1611.08563.pdf>arxiv</a> <a href=https://github.com/gurkirt/realtime-action-detection>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#map">mAP</a></li>
<li><a href="../metrics.md#auc">AUC</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=kitti></a>
<details close>
<summary><l style="font-size:20px"><strong>KITTI</strong></l> <a href=http://www.cvlibs.net/datasets/kitti/>link</a> <a href=https://ieeexplore.ieee.org/document/6248074>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale driving dataset recorded with different modalities including stereo, LIDAR, GPS, etc. recorded at 10hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, LIDAR, bounding box, optical flow, vehicle sensors, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Jin et al., "Exploring Spatial-Temporal Multi-Frequency Analysis for High-Fidelity and Temporal-Consistency Video Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Jin_Exploring_Spatial-Temporal_Multi-Frequency_Analysis_for_High-Fidelity_and_Temporal-Consistency_Video_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2002.09905.pdf>arxiv</a> <a href=https://github.com/Bei-Jin/STMFANet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="../datasets/year_datasets.md#bair">BAIR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics.md#fvd">FVD</a></li>
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
<summary><em>Wu et al., "Future Video Synthesis With Object Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Wu_Future_Video_Synthesis_With_Object_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.00542.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics.md#ms-ssim">MS-SSIM</a></li>
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
<summary><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle Gan", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#chuk_avenue">CHUK Avenue</a></li>
<li><a href="../datasets/year_datasets.md#shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#yuv">YUV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Liu et al., "Dyan: A Dynamical Atoms-Based Network For Video Prediction", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Wenqian_Liu_DYAN_A_Dynamical_ECCV_2018_paper.pdf>paper</a> <a href=https://github.com/liuem607/DYAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Liang et al., "Dual Motion Gan For Future-Flow Embedded Video Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Liang_Dual_Motion_GAN_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00284.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Marchetti et al., "MANTRA: Memory Augmented Networks for Multiple Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Marchetti_MANTRA_Memory_Augmented_Networks_for_Multiple_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.03340.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#orc">ORC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Marchetti_2020_CVPR,
    author = "Marchetti, Francesco and Becattini, Federico and Seidenari, Lorenzo and Del Bimbo, Alberto",
    title = "MANTRA: Memory Augmented Networks for Multiple Trajectory Prediction",
    booktitle = "CVPR",
    year = "2020"
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#oxford">Oxford</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#meanmsd">meanMSD</a></li>
<li><a href="../metrics.md#minmsd">minMSD</a></li>
<li><a href="../metrics.md#ce">CE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ed">ED</a></li>
<li><a href="../metrics.md#mined">minED</a></li>
<li><a href="../metrics.md#maxd">maxD</a></li>
<li><a href="../metrics.md#miss_rate">Miss rate</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#run_time">Run Time</a></li>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#tp">TP</a></li>
<li><a href="../metrics.md#tn">TN</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#f1">F1</a></li>
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
<a name=mmnist></a>
<details close>
<summary><l style="font-size:20px"><strong>Moving MNIST (MMNIST)</strong></l> <a href=http://www.cs.toronto.edu/~nitish/unsupervised_video/>link</a> <a href=http://proceedings.mlr.press/v37/srivastava15.pdf>paper</a> <a href=https://arxiv.org/pdf/1502.04681.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of moving digits on a simple uniform background
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Grayscale</li>
<li><em><strong>Task:</strong></em> Digit</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Le et al., "Disentangling Physical Dynamics From Unknown Factors for Unsupervised Video Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Le_Guen_Disentangling_Physical_Dynamics_From_Unknown_Factors_for_Unsupervised_Video_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.01460.pdf>arxiv</a> <a href=https://github.com/vincent-leguen/PhyDNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#sst">SST</a></li>
<li><a href="../datasets/year_datasets.md#taxi_bj">Taxi BJ</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
<li><a href="../metrics.md#mae">MAE</a></li>
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
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<summary><em>Castrejon et al., "Improved Conditional Vrnns For Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Castrejon_Improved_Conditional_VRNNs_for_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.12165.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics.md#fvd">FVD</a></li>
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
<summary><em>Lee et al., "Mutual Suppression Network For Video Prediction Using Disentangled Features", BMVC, 2019.</em> <a href=https://bmvc2019.org/wp-content/uploads/papers/0336-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.04810.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="../datasets/year_datasets.md#msr">MSR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#bouncing_ball">Bouncing Ball</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mse">MSE</a></li>
<li><a href="../metrics.md#bce">BCE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
<li><a href="../datasets/year_datasets.md#visor">ViSOR</a></li>
<li><a href="../datasets/year_datasets.md#prost">PROST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#human">Human</a></li>
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
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<summary><em>Oh et al., "HCNAF: Hyper-Conditioned Neural Autoregressive Flow and its Application for Probabilistic Occupancy Map Forecasting", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Oh_HCNAF_Hyper-Conditioned_Neural_Autoregressive_Flow_and_its_Application_for_Probabilistic_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.08111.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#mnist">MNIST</a></li>
<li><a href="../datasets/year_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Oh_2020_CVPR,
    author = "Oh, Geunseob and Valois, Jean-Sebastien",
    title = "HCNAF: Hyper-Conditioned Neural Autoregressive Flow and its Application for Probabilistic Occupancy Map Forecasting",
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
    title = "Unsupervised Learning Of Video Representations Using Lstms",
    booktitle = "ICML",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=caltech_pedestrian></a>
<details close>
<summary><l style="font-size:20px"><strong>Caltech Pedestrian</strong></l> <a href=http://www.vision.caltech.edu/Image_Datasets/CaltechPedestrians/>link</a> <a href=https://ieeexplore.ieee.org/document/5206631>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A pedestrian detection dataset with 2.3K unique samples with approx. 10 hours of video footage recorded and annotated at 30hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Jin et al., "Exploring Spatial-Temporal Multi-Frequency Analysis for High-Fidelity and Temporal-Consistency Video Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Jin_Exploring_Spatial-Temporal_Multi-Frequency_Analysis_for_High-Fidelity_and_Temporal-Consistency_Video_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2002.09905.pdf>arxiv</a> <a href=https://github.com/Bei-Jin/STMFANet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="../datasets/year_datasets.md#bair">BAIR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics.md#fvd">FVD</a></li>
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
<summary><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle Gan", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#chuk_avenue">CHUK Avenue</a></li>
<li><a href="../datasets/year_datasets.md#shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#yuv">YUV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#yuv">YUV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Liu et al., "Dyan: A Dynamical Atoms-Based Network For Video Prediction", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Wenqian_Liu_DYAN_A_Dynamical_ECCV_2018_paper.pdf>paper</a> <a href=https://github.com/liuem607/DYAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#youtube-8m">Youtube-8M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
<li><a href="../metrics.md#l1">L1</a></li>
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
<summary><em>Liang et al., "Dual Motion Gan For Future-Flow Embedded Video Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Liang_Dual_Motion_GAN_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00284.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#eth_pedestrian">ETH Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#daimler">Daimler</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#auc">AUC</a></li>
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
<a name=kth></a>
<details close>
<summary><l style="font-size:20px"><strong>KTH</strong></l> <a href=http://www.nada.kth.se/cvap/actions/>link</a> <a href=https://ieeexplore.ieee.org/document/1334462>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 6 basic actions, e.g. walking, jogging, running, recorded from 25 subjects at 25fps for a total of 2391 sequences
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Grayscale, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Jin et al., "Exploring Spatial-Temporal Multi-Frequency Analysis for High-Fidelity and Temporal-Consistency Video Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Jin_Exploring_Spatial-Temporal_Multi-Frequency_Analysis_for_High-Fidelity_and_Temporal-Consistency_Video_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2002.09905.pdf>arxiv</a> <a href=https://github.com/Bei-Jin/STMFANet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="../datasets/year_datasets.md#bair">BAIR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics.md#fvd">FVD</a></li>
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
<summary><em>Wang et al., "Probabilistic Video Prediction From Noisy Data With a Posterior Confidence", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_Probabilistic_Video_Prediction_From_Noisy_Data_With_a_Posterior_Confidence_CVPR_2020_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<summary><em>Lee et al., "Mutual Suppression Network For Video Prediction Using Disentangled Features", BMVC, 2019.</em> <a href=https://bmvc2019.org/wp-content/uploads/papers/0336-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.04810.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="../datasets/year_datasets.md#msr">MSR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Li et al., "Flow-Grounded Spatial-Temporal Video Prediction From Still Images", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yijun_Li_Flow-Grounded_Spatial-Temporal_Video_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1807.09755.pdf>arxiv</a> <a href=https://github.com/Yijunmaverick/FlowGrounded-VideoPrediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics.md#human">Human</a></li>
<li><a href="../metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<a name=cityscapes></a>
<details close>
<summary><l style="font-size:20px"><strong>Cityscapes</strong></l> <a href=https://www.cityscapes-dataset.com/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Cordts_The_Cityscapes_Dataset_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1604.01685.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A driving dataset of street images with annotations for 30 traffic objects in 5k frames and weak annotations in 20k frames
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, bounding box, semantic segment, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Wu et al., "Future Video Synthesis With Object Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Wu_Future_Video_Synthesis_With_Object_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.00542.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics.md#ms-ssim">MS-SSIM</a></li>
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
<summary><em>Castrejon et al., "Improved Conditional Vrnns For Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Castrejon_Improved_Conditional_VRNNs_for_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.12165.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics.md#fvd">FVD</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Saric et al., "Warp to the Future: Joint Forecasting of Features and Feature Motion", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Saric_Warp_to_the_Future_Joint_Forecasting_of_Features_and_Feature_CVPR_2020_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#iou">IoU</a></li>
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
<summary><em>Srikanth et al., "Infer: Intermediate Representations For Future Prediction", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8968553>paper</a> <a href=https://arxiv.org/pdf/1903.10641.pdf>arxiv</a> <a href=https://rebrand.ly/INFER-results>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#oxford">Oxford</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
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
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#iou">IoU</a></li>
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
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#iou">IoU</a></li>
<li><a href="../metrics.md#voi">VoI</a></li>
<li><a href="../metrics.md#gce">GCE</a></li>
<li><a href="../metrics.md#ri">RI</a></li>
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
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#iou">IoU</a></li>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mse">MSE</a></li>
<li><a href="../metrics.md#miou">MIoU</a></li>
<li><a href="../metrics.md#epe">EPE</a></li>
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
<a name=penn_action></a>
<details close>
<summary><l style="font-size:20px"><strong>Penn Action</strong></l> <a href=http://dreamdragon.github.io/PennAction/>link</a> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2013/papers/Zhang_From_Actemes_to_2013_ICCV_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 2.3K+ video clips of 15 actions with the corresponding human joint annotations
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ye et al., "Compositional Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ye_Compositional_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.08522.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#shapestack">ShapeStack</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
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
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#uva-nemo">UvA-NEMO</a></li>
<li><a href="../datasets/year_datasets.md#mgif">MGIF</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#fvd">FVD</a></li>
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
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#mug">MUG</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#is">IS</a></li>
<li><a href="../metrics.md#mmd">MMD</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#human">Human</a></li>
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
<summary><em>Zhang et al., "Predicting 3D Human Dynamics From Video", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Predicting_3D_Human_Dynamics_From_Video_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.04781.pdf>arxiv</a> <a href=https://github.com/jasonyzhang/phd>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#instavariety">InstaVariety</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#pck">PCK</a></li>
<li><a href="../metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../metrics.md#re">RE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mje">MJE</a></li>
<li><a href="../metrics.md#pck">PCK</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#mpii_human_pose">MPII Human Pose</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#pck">PCK</a></li>
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
<a name=jaad></a>
<details close>
<summary><l style="font-size:20px"><strong>Joint Attention in Autonomous Driving (JAAD)</strong></l> <a href=http://data.nvision2.eecs.yorku.ca/JAAD_dataset/>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w3/Rasouli_Are_They_Going_ICCV_2017_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of pedestrians with 346 video sequences showing pedestrians at the time of crossing in different geographical locations and under different weather conditions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, attribute, temporal segment, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chaabane et al., "Looking Ahead: Anticipating Pedestrians Crossing with Future Frames Prediction", WACV, 2020.</em> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Chaabane_Looking_Ahead_Anticipating_Pedestrians_Crossing_with_Future_Frames_Prediction_WACV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.09077.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#l1">L1</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#l1">L1</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ap">AP</a></li>
<li><a href="../metrics.md#run_time">Run Time</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#viena">VIENA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#map">mAP</a></li>
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
<summary><em>Mangalam et al., "Disentangling Human Dynamics for Pedestrian Locomotion Forecasting with Noisy Supervision", WACV, 2020.</em> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Mangalam_Disentangling_Human_Dynamics_for_Pedestrian_Locomotion_Forecasting_with_Noisy_Supervision_WACV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.01138.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#kde">KDE</a></li>
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
<summary><em>Rasouli et al., "Pie: A Large-Scale Dataset And Models For Pedestrian Intention Estimation And Trajectory Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.pdf>paper</a> <a href=https://github.com/aras62/PIEPredict>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psi">Psi</a></li>
<li><a href="../metrics.md#ism">ISM</a></li>
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
<a name=jhmdb></a>
<details close>
<summary><l style="font-size:20px"><strong>Joint-Annotated Human Motion Data Base (JHMDB)</strong></l> <a href=http://jhmdb.is.tue.mpg.de/>link</a> <a href=https://openaccess.thecvf.com/content_iccv_2013/papers/Jhuang_Towards_Understanding_Action_2013_ICCV_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 928 video clips of 21 actions with corresponding flow maps and poses
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, mask, activity label, pose, optical flow</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Tang et al., "Pose Guided Global And Local Gan For Appearance Preserving Human Video Prediction", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8803792>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
<li><a href="../datasets/year_datasets.md#ava">AVA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ap">AP</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
<li><a href="../datasets/year_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<summary><em>Singh et al., "Online Real-Time Multiple Spatiotemporal Action Localisation And Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Singh_Online_Real-Time_Multiple_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1611.08563.pdf>arxiv</a> <a href=https://github.com/gurkirt/realtime-action-detection>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#map">mAP</a></li>
<li><a href="../metrics.md#auc">AUC</a></li>
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
<a name=bair></a>
<details close>
<summary><l style="font-size:20px"><strong>BAIR Push</strong></l> <a href=https://sites.google.com/site/brainrobotdata/home/push-dataset>link</a> <a href=https://papers.nips.cc/paper/6161-unsupervised-learning-for-physical-interaction-through-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1605.07157.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of object manipulation using a robot arm with 59k object pushing motion samples
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Robot object manipulation</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Jin et al., "Exploring Spatial-Temporal Multi-Frequency Analysis for High-Fidelity and Temporal-Consistency Video Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Jin_Exploring_Spatial-Temporal_Multi-Frequency_Analysis_for_High-Fidelity_and_Temporal-Consistency_Video_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2002.09905.pdf>arxiv</a> <a href=https://github.com/Bei-Jin/STMFANet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="../datasets/year_datasets.md#bair">BAIR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics.md#fvd">FVD</a></li>
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
<summary><em>Castrejon et al., "Improved Conditional Vrnns For Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Castrejon_Improved_Conditional_VRNNs_for_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.12165.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics.md#fvd">FVD</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<a name=thumos></a>
<details close>
<summary><l style="font-size:20px"><strong>THUMOS</strong></l> <a href=http://www.thumos.info/home.html>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 20K+ videos of 101 diverse action classes
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liang et al., "Dual Motion Gan For Future-Flow Embedded Video Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Liang_Dual_Motion_GAN_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00284.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
<li><a href="../datasets/year_datasets.md#tv_series">TV Series</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#map">mAP</a></li>
<li><a href="../metrics.md#cap">cAP</a></li>
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
<li><a href="../datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=sports-1m></a>
<details close>
<summary><l style="font-size:20px"><strong>Sports-1M</strong></l> <a href=https://cs.stanford.edu/people/karpathy/deepvideo/>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Karpathy_Large-scale_Video_Classification_2014_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale dataset of 1M sports videos with 487 classes
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Sport</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Lu et al., "Flexible Spatio-Temporal Networks For Video Prediction", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lu_Flexible_Spatio-Temporal_Networks_CVPR_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
<li><a href="../datasets/year_datasets.md#visor">ViSOR</a></li>
<li><a href="../datasets/year_datasets.md#prost">PROST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#bit">BIT</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=chuk_avenue></a>
<details close>
<summary><l style="font-size:20px"><strong>CHUK Avenue</strong></l> <a href=http://www.cse.cuhk.edu.hk/leojia/projects/detectabnormal/dataset.html>link</a> <a href=https://openaccess.thecvf.com/content_iccv_2013/papers/Lu_Abnormal_Event_Detection_2013_ICCV_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 37 video clips with 30K+ frames showing abnormal events
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, anomaly, temporal segment</li>
<li><em><strong>Task:</strong></em> Surveillance, Anomaly</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle Gan", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#chuk_avenue">CHUK Avenue</a></li>
<li><a href="../datasets/year_datasets.md#shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#gc">GC</a></li>
<li><a href="../datasets/year_datasets.md#chuk">CHUK</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#ande">ANDE</a></li>
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
<a name=yuv></a>
<details close>
<summary><l style="font-size:20px"><strong>YUV Videos</strong></l> <a href=http://trace.kom.aau.dk/yuv/index.html>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A collection of color video clips with different subjects and resolutions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Mix videos</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ho et al., "Sme-Net: Sparse Motion Estimation For Parametric Video Prediction Through Reinforcement Learning", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ho_SME-Net_Sparse_Motion_Estimation_for_Parametric_Video_Prediction_Through_Reinforcement_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#yuv">YUV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#yuv">YUV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<a name=uva-nemo></a>
<details close>
<summary><l style="font-size:20px"><strong>UvA-NEMO</strong></l> <a href=https://www.uva-nemo.org/>link</a> <a href=https://link.springer.com/content/pdf/10.1007%2F978-3-642-33712-3_38.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale dataset of smiles with 1240 video clips with both spontaneous and posed actions recorded at 50fps from 400 subjects with ages between 8 to 76 years
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Face (smile)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kim et al., "Unsupervised Keypoint Learning For Guiding Class-Conditional Video Prediction", NeurIPS, 2019.</em> <a href=https://papers.nips.cc/paper/8637-unsupervised-keypoint-learning-for-guiding-class-conditional-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.02027.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#uva-nemo">UvA-NEMO</a></li>
<li><a href="../datasets/year_datasets.md#mgif">MGIF</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#fvd">FVD</a></li>
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
<a name=taxi_bj></a>
<details close>
<summary><l style="font-size:20px"><strong>Taxi BJ</strong></l> <a href=https://github.com/roryhr/taxi-trajectories>link</a> <a href=https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/viewFile/14501/13964>paper</a> <a href=https://arxiv.org/pdf/1610.00081.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of GPS data collected from 10K+ taxis in Beijing with a sampling rate of every 117 seconds
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> GPS</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Le et al., "Disentangling Physical Dynamics From Unknown Factors for Unsupervised Video Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Le_Guen_Disentangling_Physical_Dynamics_From_Unknown_Factors_for_Unsupervised_Video_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.01460.pdf>arxiv</a> <a href=https://github.com/vincent-leguen/PhyDNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#sst">SST</a></li>
<li><a href="../datasets/year_datasets.md#taxi_bj">Taxi BJ</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
<li><a href="../metrics.md#mae">MAE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@inproceedings{Yuan_2010_ICAGIS,
    author = "Yuan, Jing and Zheng, Yu and Zhang, Chengyang and Xie, Wenlei and Xie, Xing and Sun, Guangzhong and Huang, Yan",
    title = "T-Drive: Driving Directions Based on Taxi Trajectories",
    booktitle = "International Conference on Advances in Geographic Information Systems",
    pages = "99--108",
    year = "2010"
}
</pre>
</details>

</ul></details>
<a name=msr></a>
<details close>
<summary><l style="font-size:20px"><strong>MSR</strong></l> <a href=https://www.microsoft.com/en-us/download/details.aspx?id=52315>link</a> <a href=https://ieeexplore.ieee.org/document/5543273>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset 20 actions, such as high arm wave, horizontal arm wave, hammer, forward punch, recorded using a depth camera at 15fps for a total of 23K+ frames
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Depth, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Wang et al., "Order Matters: Shuffling Sequence Generation For Video Prediction", BMVC, 2019.</em> <a href=https://bmvc2019.org/wp-content/uploads/papers/1023-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1907.08845.pdf>arxiv</a> <a href=https://github.com/andrewjywang/SEENet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="../datasets/year_datasets.md#msr">MSR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<a name=youtube-8m></a>
<details close>
<summary><l style="font-size:20px"><strong>Youtube-8M</strong></l> <a href=https://research.google.com/youtube8m/>link</a> <a href=https://arxiv.org/pdf/1609.08675.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale dataset of videos collected from YouTube with corresponding machine-generated annotations from a vocabulary of 3.8K+ visual entities
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Reda et al., "Sdc-Net: Video Prediction Using Spatially-Displaced Convolution", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Fitsum_Reda_SDC-Net_Video_prediction_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1811.00684.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#youtube-8m">Youtube-8M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
<li><a href="../metrics.md#l1">L1</a></li>
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
<a name=mug></a>
<details close>
<summary><l style="font-size:20px"><strong>MUG</strong></l> <a href=https://mug.ee.auth.gr/fed/>link</a> <a href=https://ieeexplore.ieee.org/document/5617662>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 86 human subjects performing 6 types of basic expressions including anger, disgust, fear, happiness, sadness, and surprise recorded at 19fps for a total of 1462 sequences
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, keypoints, motion label</li>
<li><em><strong>Task:</strong></em> Face (expression)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhao et al., "Learning To Forecast And Refine Residual Motion For Image-To-Video Generation", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Long_Zhao_Learning_to_Forecast_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1807.09951.pdf>arxiv</a> <a href=https://github.com/garyzhao/FRGAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#mug">MUG</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<a name=bouncing_ball></a>
<details close>
<summary><l style="font-size:20px"><strong>Bouncing Ball (BB)</strong></l> <a href=https://github.com/mbchang/dynamics>link</a> <a href=https://openreview.net/pdf?id=Bkab5dqxe>paper</a> <a href=https://arxiv.org/pdf/1612.00341.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A simulated dataset of bounding balls generated using Neural Physics Engine
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Object (simulation)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hsieh et al., "Learning To Decompose And Disentangle Representations For Video Prediction", NeurIPS, 2018.</em> <a href=https://papers.nips.cc/paper/7333-learning-to-decompose-and-disentangle-representations-for-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1806.04166.pdf>arxiv</a> <a href=https://github.com/jthsieh/DDPAE-video-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#bouncing_ball">Bouncing Ball</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mse">MSE</a></li>
<li><a href="../metrics.md#bce">BCE</a></li>
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
<a name=prost></a>
<details close>
<summary><l style="font-size:20px"><strong>PROST</strong></l> <a href=www.gpu4vision.com>link</a> <a href=https://ieeexplore.ieee.org/document/5540145>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 4K+ frames for tracking objects in the presences of camera motion
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Object</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Lu et al., "Flexible Spatio-Temporal Networks For Video Prediction", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lu_Flexible_Spatio-Temporal_Networks_CVPR_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
<li><a href="../datasets/year_datasets.md#visor">ViSOR</a></li>
<li><a href="../datasets/year_datasets.md#prost">PROST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<a name=visor></a>
<details close>
<summary><l style="font-size:20px"><strong>ViSOR</strong></l> <a href=imagelab.ing.unimore.it/visor>link</a> <a href=https://link.springer.com/article/10.1007/s11042-009-0402-9>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A repository of various surveillance footage of pedestrians in indoor and outdoor environments with 162 video clips and 1M+ frames
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, pose, attribute</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Lu et al., "Flexible Spatio-Temporal Networks For Video Prediction", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lu_Flexible_Spatio-Temporal_Networks_CVPR_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
<li><a href="../datasets/year_datasets.md#visor">ViSOR</a></li>
<li><a href="../datasets/year_datasets.md#prost">PROST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<a name=shapestack></a>
<details close>
<summary><l style="font-size:20px"><strong>ShapeStack</strong></l> <a href=https://shapestacks.robots.ox.ac.uk/>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ye_Compositional_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.08522.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A simulated dataset of 20K stack configurations composed of a variety of elementary geometric primitives annotated with semantics and structural stability
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, mask, stability</li>
<li><em><strong>Task:</strong></em> Object (simulation)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ye et al., "Compositional Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ye_Compositional_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.08522.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#shapestack">ShapeStack</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
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
<a name=shanghaitech_campus></a>
<details close>
<summary><l style="font-size:20px"><strong>ShanghaiTech Campus (STC)</strong></l> <a href=https://svip-lab.github.io/dataset/campus_dataset.html>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_Future_Frame_Prediction_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1712.09867.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An anomaly detection dataset with 300K+ frames surveillance footage with 130 abnormal events in 13 scenes
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, anomaly</li>
<li><em><strong>Task:</strong></em> Surveillance, Anomaly</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle Gan", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#chuk_avenue">CHUK Avenue</a></li>
<li><a href="../datasets/year_datasets.md#shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<a name=sst></a>
<details close>
<summary><l style="font-size:20px"><strong>Sea Surface Temperature (SST)</strong></l> <a href=https://resources.marine.copernicus.eu/?option=com_csw&view=details&product_id=GLOBAL_ANALYSIS_FORECAST_PHY_001_024>link</a> <a href=https://openreview.net/pdf?id=By4HsfWAZ>paper</a> <a href=https://arxiv.org/pdf/1711.07970.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset containing monthly report of ocean forecast information including  temperature, salinity, currents, sea level, etc.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Map, Temperature</li>
<li><em><strong>Task:</strong></em> Simulation</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Le et al., "Disentangling Physical Dynamics From Unknown Factors for Unsupervised Video Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Le_Guen_Disentangling_Physical_Dynamics_From_Unknown_Factors_for_Unsupervised_Video_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.01460.pdf>arxiv</a> <a href=https://github.com/vincent-leguen/PhyDNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#sst">SST</a></li>
<li><a href="../datasets/year_datasets.md#taxi_bj">Taxi BJ</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
<li><a href="../metrics.md#mae">MAE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@inproceedings{Bezenac_2018_ICLR,
    author = "de Bezenac, Emmanuel and Pajot, Arthur and Gallinari, Patrick",
    title = "Deep Learning for Physical Processes: Incorporating Prior Scientific Knowledge",
    booktitle = "ICLR",
    year = "2018"
}
</pre>
</details>

</ul></details>
<a name=mgif></a>
<details close>
<summary><l style="font-size:20px"><strong>MGIF</strong></l> <a href=https://github.com/AliaksandrSiarohin/monkey-net>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Siarohin_Animating_Arbitrary_Objects_via_Deep_Motion_Transfer_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.08861.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of cartoon animal animations for future video prediction
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kim et al., "Unsupervised Keypoint Learning For Guiding Class-Conditional Video Prediction", NeurIPS, 2019.</em> <a href=https://papers.nips.cc/paper/8637-unsupervised-keypoint-learning-for-guiding-class-conditional-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.02027.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#uva-nemo">UvA-NEMO</a></li>
<li><a href="../datasets/year_datasets.md#mgif">MGIF</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#fvd">FVD</a></li>
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
</ul><a name=datasets_Action></a>
<h2>Action</h2> <a href=#top>&uarr; top</a>
<ul><a name=human3.6m></a>
<details close>
<summary><l style="font-size:20px"><strong>Human3.6M</strong></l> <a href=http://vision.imar.ro/human3.6m/description.php>link</a> <a href=https://ieeexplore.ieee.org/document/6682899>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale dataset of 3D human poses with 3M+ images captured using 11 professional actors in 17 scenarios, such as discussion, smoking, taking photo, etc.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Le et al., "Disentangling Physical Dynamics From Unknown Factors for Unsupervised Video Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Le_Guen_Disentangling_Physical_Dynamics_From_Unknown_Factors_for_Unsupervised_Video_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.01460.pdf>arxiv</a> <a href=https://github.com/vincent-leguen/PhyDNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#sst">SST</a></li>
<li><a href="../datasets/year_datasets.md#taxi_bj">Taxi BJ</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
<li><a href="../metrics.md#mae">MAE</a></li>
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
<summary><em>Xu et al., "Structure Preserving Video Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers_backup/Xu_Structure_Preserving_Video_CVPR_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#human">Human</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#human">Human</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<summary><em>Aliakbarian et al., "A Stochastic Conditioning Scheme for Diverse Human Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Aliakbarian_A_Stochastic_Conditioning_Scheme_for_Diverse_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://github.com/mix-and-match/mix-and-match-tutorial>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#kld">KLD</a></li>
<li><a href="../metrics.md#si">SI</a></li>
<li><a href="../metrics.md#kl">KL</a></li>
<li><a href="../metrics.md#s-mse">S-MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../datasets/year_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#mpjpe">MPJPE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2020_CVPR,
    author = "Li, Maosen and Chen, Siheng and Zhao, Yangheng and Zhang, Ya and Wang, Yanfeng and Tian, Qi",
    title = "Dynamic Multiscale Graph Neural Networks for 3D Skeleton Based Human Motion Prediction",
    booktitle = "CVPR",
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#npss">NPSS</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mouse_fish">Mouse Fish</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mje">MJE</a></li>
<li><a href="../metrics.md#run_time">Run Time</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#human">Human</a></li>
<li><a href="../metrics.md#pskl">PSKL</a></li>
<li><a href="../metrics.md#psent">PSEnt</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../datasets/year_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#mpjpe">MPJPE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#instavariety">InstaVariety</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#pck">PCK</a></li>
<li><a href="../metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../metrics.md#re">RE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mje">MJE</a></li>
<li><a href="../metrics.md#pck">PCK</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#human">Human</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#mpii_human_pose">MPII Human Pose</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#pck">PCK</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=ucf-101></a>
<details close>
<summary><l style="font-size:20px"><strong>UCF-101</strong></l> <a href=https://www.crcv.ucf.edu/data/UCF101.php>link</a> <a href=https://arxiv.org/pdf/1212.0402.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale dataset of 101 actions with 13K+ video clips divided into 5 groups of human-object interaction, body-motion only, human-human interaction, playing musical instruments, and sports
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle Gan", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#chuk_avenue">CHUK Avenue</a></li>
<li><a href="../datasets/year_datasets.md#shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#yuv">YUV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Liu et al., "Dyan: A Dynamical Atoms-Based Network For Video Prediction", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Wenqian_Liu_DYAN_A_Dynamical_ECCV_2018_paper.pdf>paper</a> <a href=https://github.com/liuem607/DYAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
<li><a href="../datasets/year_datasets.md#visor">ViSOR</a></li>
<li><a href="../datasets/year_datasets.md#prost">PROST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Liang et al., "Dual Motion Gan For Future-Flow Embedded Video Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Liang_Dual_Motion_GAN_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00284.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#is">IS</a></li>
<li><a href="../metrics.md#mmd">MMD</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
<li><a href="../datasets/year_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
<li><a href="../datasets/year_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#willow_action">Willow Action</a></li>
<li><a href="../datasets/year_datasets.md#wider">WIDER</a></li>
<li><a href="../datasets/year_datasets.md#stanford-40">Stanford-40</a></li>
<li><a href="../datasets/year_datasets.md#bu_action">BU Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#map">mAP</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#hmdb">HMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#bit">BIT</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<summary><em>Singh et al., "Online Real-Time Multiple Spatiotemporal Action Localisation And Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Singh_Online_Real-Time_Multiple_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1611.08563.pdf>arxiv</a> <a href=https://github.com/gurkirt/realtime-action-detection>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#map">mAP</a></li>
<li><a href="../metrics.md#auc">AUC</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=ngsim></a>
<details close>
<summary><l style="font-size:20px"><strong>Next Generation simulationulation (NGSIM)</strong></l> <a href=https://catalog.data.gov/dataset/next-generation-simulation-ngsim-vehicle-trajectories>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of vehicle trajectories containing 10K+ frames of recording
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Map, trajectory</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ding et al., "Predicting Vehicle Behaviors Over An Extended Horizon Using Behavior Interaction Network", ICRA, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8794146>paper</a> <a href=https://arxiv.org/pdf/1903.00848.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
<li><a href="../metrics.md#f1">F1</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
<li><a href="../metrics.md#ttm">TTM</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#traf">TRAF</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ll">LL</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ll">LL</a></li>
<li><a href="../metrics.md#kld">KLD</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
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
<a name=caltech_pedestrian></a>
<details close>
<summary><l style="font-size:20px"><strong>Caltech Pedestrian</strong></l> <a href=http://www.vision.caltech.edu/Image_Datasets/CaltechPedestrians/>link</a> <a href=https://ieeexplore.ieee.org/document/5206631>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A pedestrian detection dataset with 2.3K unique samples with approx. 10 hours of video footage recorded and annotated at 30hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Jin et al., "Exploring Spatial-Temporal Multi-Frequency Analysis for High-Fidelity and Temporal-Consistency Video Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Jin_Exploring_Spatial-Temporal_Multi-Frequency_Analysis_for_High-Fidelity_and_Temporal-Consistency_Video_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2002.09905.pdf>arxiv</a> <a href=https://github.com/Bei-Jin/STMFANet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="../datasets/year_datasets.md#bair">BAIR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics.md#fvd">FVD</a></li>
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
<summary><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle Gan", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#chuk_avenue">CHUK Avenue</a></li>
<li><a href="../datasets/year_datasets.md#shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#yuv">YUV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#yuv">YUV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Liu et al., "Dyan: A Dynamical Atoms-Based Network For Video Prediction", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Wenqian_Liu_DYAN_A_Dynamical_ECCV_2018_paper.pdf>paper</a> <a href=https://github.com/liuem607/DYAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#youtube-8m">Youtube-8M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
<li><a href="../metrics.md#l1">L1</a></li>
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
<summary><em>Liang et al., "Dual Motion Gan For Future-Flow Embedded Video Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Liang_Dual_Motion_GAN_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00284.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#eth_pedestrian">ETH Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#daimler">Daimler</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#auc">AUC</a></li>
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
<a name=jaad></a>
<details close>
<summary><l style="font-size:20px"><strong>Joint Attention in Autonomous Driving (JAAD)</strong></l> <a href=http://data.nvision2.eecs.yorku.ca/JAAD_dataset/>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w3/Rasouli_Are_They_Going_ICCV_2017_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of pedestrians with 346 video sequences showing pedestrians at the time of crossing in different geographical locations and under different weather conditions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, attribute, temporal segment, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chaabane et al., "Looking Ahead: Anticipating Pedestrians Crossing with Future Frames Prediction", WACV, 2020.</em> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Chaabane_Looking_Ahead_Anticipating_Pedestrians_Crossing_with_Future_Frames_Prediction_WACV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.09077.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#l1">L1</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#l1">L1</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ap">AP</a></li>
<li><a href="../metrics.md#run_time">Run Time</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#viena">VIENA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#map">mAP</a></li>
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
<summary><em>Mangalam et al., "Disentangling Human Dynamics for Pedestrian Locomotion Forecasting with Noisy Supervision", WACV, 2020.</em> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Mangalam_Disentangling_Human_Dynamics_for_Pedestrian_Locomotion_Forecasting_with_Noisy_Supervision_WACV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.01138.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#kde">KDE</a></li>
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
<summary><em>Rasouli et al., "Pie: A Large-Scale Dataset And Models For Pedestrian Intention Estimation And Trajectory Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.pdf>paper</a> <a href=https://github.com/aras62/PIEPredict>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psi">Psi</a></li>
<li><a href="../metrics.md#ism">ISM</a></li>
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
<a name=uti></a>
<details close>
<summary><l style="font-size:20px"><strong>UT Interaction (UTI)</strong></l> <a href=http://cvrc.ece.utexas.edu/SDHA2010/Human_Interaction.html>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 6 human-human interactions, such as shaking hands, hugging, with 20 video clips of subjects with different clothing items recorded at 30fps
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Gammulle et al., "Predicting The Future: A Jointly Learnt Model For Action Anticipation", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Gammulle_Predicting_the_Future_A_Jointly_Learnt_Model_for_Action_Anticipation_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.07148.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#mrr">MRR</a></li>
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
<a name=jhmdb></a>
<details close>
<summary><l style="font-size:20px"><strong>Joint-Annotated Human Motion Data Base (JHMDB)</strong></l> <a href=http://jhmdb.is.tue.mpg.de/>link</a> <a href=https://openaccess.thecvf.com/content_iccv_2013/papers/Jhuang_Towards_Understanding_Action_2013_ICCV_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 928 video clips of 21 actions with corresponding flow maps and poses
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, mask, activity label, pose, optical flow</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Tang et al., "Pose Guided Global And Local Gan For Appearance Preserving Human Video Prediction", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8803792>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
<li><a href="../datasets/year_datasets.md#ava">AVA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ap">AP</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
<li><a href="../datasets/year_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<summary><em>Singh et al., "Online Real-Time Multiple Spatiotemporal Action Localisation And Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Singh_Online_Real-Time_Multiple_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1611.08563.pdf>arxiv</a> <a href=https://github.com/gurkirt/realtime-action-detection>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#map">mAP</a></li>
<li><a href="../metrics.md#auc">AUC</a></li>
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
<a name=cmu_mocap></a>
<details close>
<summary><l style="font-size:20px"><strong>CMU Mocap</strong></l> <a href=http://mocap.cs.cmu.edu/>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A motion dataset consists of various activities including human interaction, interaction with the environment, locomotion, sports, etc.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Butepage et al., "Deep Representation Learning For Human Motion Prediction And Classification", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Butepage_Deep_Representation_Learning_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1702.07486.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<summary><em>Aliakbarian et al., "A Stochastic Conditioning Scheme for Diverse Human Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Aliakbarian_A_Stochastic_Conditioning_Scheme_for_Diverse_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://github.com/mix-and-match/mix-and-match-tutorial>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#kld">KLD</a></li>
<li><a href="../metrics.md#si">SI</a></li>
<li><a href="../metrics.md#kl">KL</a></li>
<li><a href="../metrics.md#s-mse">S-MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../datasets/year_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#mpjpe">MPJPE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2020_CVPR,
    author = "Li, Maosen and Chen, Siheng and Zhao, Yangheng and Zhang, Ya and Wang, Yanfeng and Tian, Qi",
    title = "Dynamic Multiscale Graph Neural Networks for 3D Skeleton Based Human Motion Prediction",
    booktitle = "CVPR",
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../datasets/year_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#mpjpe">MPJPE</a></li>
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
<a name=tv_human_interaction></a>
<details close>
<summary><l style="font-size:20px"><strong>TV Human Interaction (THI)</strong></l> <a href=http://www.robots.ox.ac.uk/~alonso/tv_human_interactions.html>link</a> <a href=http://www.bmva.org/bmvc/2010/conference/paper50/abstract50.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 300 video clips collected from 20+ different TV shows containing 4 interactions: handshakes, high fives, hugs, and kisses
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, head pose, activity label</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Gammulle et al., "Predicting The Future: A Jointly Learnt Model For Action Anticipation", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Gammulle_Predicting_the_Future_A_Jointly_Learnt_Model_for_Action_Anticipation_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.07148.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
<li><a href="../datasets/year_datasets.md#tv_series">TV Series</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#map">mAP</a></li>
<li><a href="../metrics.md#cap">cAP</a></li>
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
<li><a href="../datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=cad-120></a>
<details close>
<summary><l style="font-size:20px"><strong>CAD-120</strong></l> <a href=http://pr.cs.cornell.edu/humanactivities/data.php>link</a> <a href=https://journals.sagepub.com/doi/abs/10.1177/0278364913478446>paper</a> <a href=https://arxiv.org/pdf/1210.1207.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 120 RGBD videos of 10 daily activities performed by 4 subjects
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D pose, activity label, affordance label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Alati et al., "Help By Predicting What To Do", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8803155>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#cad-120">CAD-120</a></li>
<li><a href="../datasets/year_datasets.md#mpii_cooking">MPII Cooking</a></li>
<li><a href="../datasets/year_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
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
<li><a href="../datasets/year_datasets.md#cad-120">CAD-120</a></li>
<li><a href="../datasets/year_datasets.md#acticipate">ACTICIPATE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#f1">F1</a></li>
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
<li><a href="../datasets/year_datasets.md#cad-120">CAD-120</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
<li><a href="../metrics.md#f1">F1</a></li>
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
<li><a href="../datasets/year_datasets.md#cad-120">CAD-120</a></li>
<li><a href="../datasets/year_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
<li><a href="../metrics.md#f1">F1</a></li>
<li><a href="../metrics.md#ttm">TTM</a></li>
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
<li><a href="../datasets/year_datasets.md#cad-120">CAD-120</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
<li><a href="../metrics.md#f1">F1</a></li>
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
<a name=thumos></a>
<details close>
<summary><l style="font-size:20px"><strong>THUMOS</strong></l> <a href=http://www.thumos.info/home.html>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 20K+ videos of 101 diverse action classes
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liang et al., "Dual Motion Gan For Future-Flow Embedded Video Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Liang_Dual_Motion_GAN_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00284.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
<li><a href="../datasets/year_datasets.md#tv_series">TV Series</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#map">mAP</a></li>
<li><a href="../metrics.md#cap">cAP</a></li>
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
<li><a href="../datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=bit></a>
<details close>
<summary><l style="font-size:20px"><strong>BIT</strong></l> <a href=https://sites.google.com/site/alexkongy/software>link</a> <a href=https://link.springer.com/content/pdf/10.1007%2F978-3-642-33718-5_22.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of human interactions with 400 video clips capturing 8 different interaction classes
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhao et al., "Spatiotemporal Feature Residual Propagation For Action Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhao_Spatiotemporal_Feature_Residual_Propagation_for_Action_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://github.com/JoeHEZHAO/Spatiotemporal-Residual-Propagation>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
<li><a href="../datasets/year_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#bit">BIT</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=50salad></a>
<details close>
<summary><l style="font-size:20px"><strong>50Salads</strong></l> <a href=https://cvip.computing.dundee.ac.uk/datasets/foodpreparation/50salads/>link</a> <a href=https://dl.acm.org/doi/abs/10.1145/2493432.2493482>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 25 human subjects preparing 2 mixed salads each with 4h+ of annotated accelerometer and RGB-D video data recorded 50hz and 30hz respectively
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, activity label, temporal segment, accelerometer</li>
<li><em><strong>Task:</strong></em> Cooking (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ke et al., "Time-Conditioned Action Anticipation In One Shot", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Ke_Time-Conditioned_Action_Anticipation_in_One_Shot_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../datasets/year_datasets.md#50salad">50Salad</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
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
<li><a href="../datasets/year_datasets.md#breakfast">Breakfast</a></li>
<li><a href="../datasets/year_datasets.md#50salad">50Salad</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#breakfast">Breakfast</a></li>
<li><a href="../datasets/year_datasets.md#50salad">50Salad</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=mpii_cooking></a>
<details close>
<summary><l style="font-size:20px"><strong>MPII Cooking</strong></l> <a href=https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/human-activity-recognition/mpii-cooking-activities-dataset/>link</a> <a href=https://ieeexplore.ieee.org/document/6247801>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 65 cooking activities with 5.5K+ video clips recorded from 12 subjects
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, 3D pose, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Alati et al., "Help By Predicting What To Do", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8803155>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#cad-120">CAD-120</a></li>
<li><a href="../datasets/year_datasets.md#mpii_cooking">MPII Cooking</a></li>
<li><a href="../datasets/year_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
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
<li><a href="../datasets/year_datasets.md#mpii_cooking">MPII Cooking</a></li>
<li><a href="../datasets/year_datasets.md#virat">VIRAT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
<li><a href="../metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/year_datasets.md#mpii_cooking">MPII Cooking</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#rmse">RMSE</a></li>
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
<a name=brain4cars></a>
<details close>
<summary><l style="font-size:20px"><strong>Brain4Cars</strong></l> <a href=https://github.com/asheshjain399/ICCV2015_Brain4Cars>link</a> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Jain_Car_That_Knows_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1504.02789.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 700 driving events using inside and outside looking cameras with annotated actions for various driving maneuvers
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, attribute, temporal segment, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Jain et al., "Structural-Rnn: Deep Learning On Spatio-Temporal Graphs", CVPR, 2016.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.05298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#cad-120">CAD-120</a></li>
<li><a href="../datasets/year_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
<li><a href="../metrics.md#f1">F1</a></li>
<li><a href="../metrics.md#ttm">TTM</a></li>
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
<li><a href="../datasets/year_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
<li><a href="../metrics.md#ttm">TTM</a></li>
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
<li><a href="../datasets/year_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
<li><a href="../metrics.md#ttm">TTM</a></li>
<li><a href="../metrics.md#fp">FP</a></li>
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
<a name=carla></a>
<details close>
<summary><l style="font-size:20px"><strong>CARLA</strong></l> <a href=https://sites.google.com/view/precog>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rhinehart_PRECOG_PREdiction_Conditioned_on_Goals_in_Visual_Multi-Agent_Settings_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.01296.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 900 simulated driving segments for multi-agent trajectory forecasting and planning
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Driving (simulation)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Rhinehart et al., "Precog: Prediction Conditioned On Goals In Visual Multi-Agent Settings", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rhinehart_PRECOG_PREdiction_Conditioned_on_Goals_in_Visual_Multi-Agent_Settings_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.01296.pdf>arxiv</a> <a href=https://sites.google.com/view/precog>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#meanmsd">meanMSD</a></li>
<li><a href="../metrics.md#minmsd">minMSD</a></li>
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
<li><a href="../datasets/year_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#run_time">Run Time</a></li>
<li><a href="../metrics.md#rmse">RMSE</a></li>
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
<summary><em>Oh et al., "HCNAF: Hyper-Conditioned Neural Autoregressive Flow and its Application for Probabilistic Occupancy Map Forecasting", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Oh_HCNAF_Hyper-Conditioned_Neural_Autoregressive_Flow_and_its_Application_for_Probabilistic_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.08111.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#mnist">MNIST</a></li>
<li><a href="../datasets/year_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Oh_2020_CVPR,
    author = "Oh, Geunseob and Valois, Jean-Sebastien",
    title = "HCNAF: Hyper-Conditioned Neural Autoregressive Flow and its Application for Probabilistic Occupancy Map Forecasting",
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
@InProceedings{Rhinehart_2019_ICCV,
    author = "Rhinehart, Nicholas and McAllister, Rowan and Kitani, Kris and Levine, Sergey",
    title = "Precog: Prediction Conditioned On Goals In Visual Multi-Agent Settings",
    booktitle = "ICCV",
    year = "2019"
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
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Gammulle et al., "Forecasting Future Action Sequences With Neural Memory Networks", BMVC, 2019.</em> <a href=https://bmvc2019.org/wp-content/uploads/papers/0585-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1909.09278.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#breakfast">Breakfast</a></li>
<li><a href="../datasets/year_datasets.md#50salad">50Salad</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#cad-120">CAD-120</a></li>
<li><a href="../datasets/year_datasets.md#mpii_cooking">MPII Cooking</a></li>
<li><a href="../datasets/year_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
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
<li><a href="../datasets/year_datasets.md#breakfast">Breakfast</a></li>
<li><a href="../datasets/year_datasets.md#50salad">50Salad</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=epic-kitchens></a>
<details close>
<summary><l style="font-size:20px"><strong>Epic-Kitchens</strong></l> <a href=https://epic-kitchens.github.io/2019>link</a> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Dima_Damen_Scaling_Egocentric_Vision_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.02748.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An egocentric cooking action dataset with 55 hours of recording at 60fps with corresponding audio recording and 40K action segments
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, audio, bounding box, object class, text, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ke et al., "Time-Conditioned Action Anticipation In One Shot", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Ke_Time-Conditioned_Action_Anticipation_in_One_Shot_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../datasets/year_datasets.md#50salad">50Salad</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
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
<li><a href="../datasets/year_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../datasets/year_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#recall">Recall</a></li>
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
<li><a href="../datasets/year_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#recall">Recall</a></li>
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
<a name=sports-1m></a>
<details close>
<summary><l style="font-size:20px"><strong>Sports-1M</strong></l> <a href=https://cs.stanford.edu/people/karpathy/deepvideo/>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Karpathy_Large-scale_Video_Classification_2014_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale dataset of 1M sports videos with 487 classes
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Sport</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Lu et al., "Flexible Spatio-Temporal Networks For Video Prediction", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lu_Flexible_Spatio-Temporal_Networks_CVPR_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
<li><a href="../datasets/year_datasets.md#visor">ViSOR</a></li>
<li><a href="../datasets/year_datasets.md#prost">PROST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#bit">BIT</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=daimler_path></a>
<details close>
<summary><l style="font-size:20px"><strong>Daimler Path</strong></l> <a href=http://www.gavrila.net/Datasets/Daimler_Pedestrian_Benchmark_D/Pedestrian_Path_Predict_GCPR_1/pedestrian_path_predict_gcpr_1.html>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-642-40602-7_18>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 68 pedestrian sequences recorded using a dashboard camera inside a vehicle during stationary and mobile states
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Stereo grayscale, bounding box, temporal segment, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Schulz et al., "Pedestrian Intention Recognition Using Latent-Dynamic Conditional Random Fields", IV, 2015.</em> <a href=https://ieeexplore.ieee.org/document/7225754>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#daimler_path">Daimler Path</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#daimler_path">Daimler Path</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#ed">ED</a></li>
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
<a name=sysu_3dhoi></a>
<details close>
<summary><l style="font-size:20px"><strong>SYSU 3DHOI</strong></l> <a href=http://www.isee-ai.cn/~hujianfang/ProjectJOULE.html>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Hu_Jointly_Learning_Heterogeneous_2015_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 12 simple activities in 480 video clips with depth maps
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Object interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Wang et al., "Progressive Teacher-Student Learning For Early Action Prediction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Progressive_Teacher-Student_Learning_for_Early_Action_Prediction_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
<li><a href="../datasets/year_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
<li><a href="../datasets/year_datasets.md#orgbd">ORGBD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=virat></a>
<details close>
<summary><l style="font-size:20px"><strong>VIRAT</strong></l> <a href=http://viratdata.org/>link</a> <a href=https://ieeexplore.ieee.org/document/5995586>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A multiview dataset of 12 events, such as a person loading an object to a vehicle, a person opening a vehicle trunk, recorded in 11 scenes for a total of approx. 8.5 hours of video footage
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Surveillance, Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Mahmud et al., "Joint Prediction Of Activity Labels And Starting Times In Untrimmed Videos", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Mahmud_Joint_Prediction_of_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#mpii_cooking">MPII Cooking</a></li>
<li><a href="../datasets/year_datasets.md#virat">VIRAT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
<li><a href="../metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/year_datasets.md#virat">VIRAT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#nll">NLL</a></li>
<li><a href="../metrics.md#run_time">Run Time</a></li>
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
<a name=pie></a>
<details close>
<summary><l style="font-size:20px"><strong>Pedestrian Intention Estimation (PIE)</strong></l> <a href=http://data.nvision2.eecs.yorku.ca/PIE_dataset/>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of driving sequences with more than 6 hours of footage with 1.8K+ pedestrian tracks and 2.3M+ relevant traffic object bounding boxes annotated at 30fps
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, object class, attribute, temporal segment, vehicle sensors, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Rasouli et al., "Pedestrian Action Anticipation Using Contextual Feature Fusion In Stacked Rnns", BMVC, 2019.</em> <a href=https://bmvc2019.org/wp-content/uploads/papers/0283-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.06582.pdf>arxiv</a> <a href=https://github.com/aras62/SF-GRU>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
<li><a href="../metrics.md#f1">F1</a></li>
<li><a href="../metrics.md#auc">AUC</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<a name=virat/actev></a>
<details close>
<summary><l style="font-size:20px"><strong>VIRAT/ActEV</strong></l> <a href=https://actev.nist.gov/trecvid19>link</a> <a href=https://www-nlpir.nist.gov/projects/tvpubs/tv18.papers/tv18overview.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of multiview surveillance sequences for trajectory  prediction and activity detection of 38 outdoor common activities
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liang et al., "Peeking Into The Future: Predicting Future Person Activities And Locations In Videos", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPRW_2019/papers/Precognition/Liang_Peeking_Into_the_Future_Predicting_Future_Person_Activities_and_Locations_CVPRW_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1902.03748.pdf>arxiv</a> <a href=https://github.com/google/next-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#virat/actev">VIRAT/ActEV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#map">mAP</a></li>
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
<summary><em>Liang et al., "The Garden of Forking Paths: Towards Multi-Future Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Liang_The_Garden_of_Forking_Paths_Towards_Multi-Future_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.06445.pdf>arxiv</a> <a href=https://github.com/JunweiLiang/Multiverse>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#virat/actev">VIRAT/ActEV</a></li>
<li><a href="../datasets/year_datasets.md#multiverse">Multiverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#minade">minADE</a></li>
<li><a href="../metrics.md#minfde">minFDE</a></li>
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
<a name=dad></a>
<details close>
<summary><l style="font-size:20px"><strong>Dashcam Accident Dataset (DAD)</strong></l> <a href=https://aliensunmin.github.io/project/dashcam/>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-54190-7_9>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 620 video sequences of traffic accidents recorded in six cities
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, object class, temporal segment, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Suzuki et al., "Anticipating Traffic Accidents With Adaptive Loss And Large-Scale Incident Db", The CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0494.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.02675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#dad">DAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
<li><a href="../metrics.md#f1">F1</a></li>
<li><a href="../metrics.md#map">mAP</a></li>
<li><a href="../metrics.md#attc">ATTC</a></li>
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
<li><a href="../datasets/year_datasets.md#dad">DAD</a></li>
<li><a href="../datasets/year_datasets.md#epic-fail">Epic-Fail</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#map">mAP</a></li>
<li><a href="../metrics.md#tta">TTA</a></li>
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
<a name=luggage></a>
<details close>
<summary><l style="font-size:20px"><strong>Luggage</strong></l> <a href=https://aashi7.github.io/NearCollision.html>link</a> <a href=https://ieeexplore.ieee.org/document/8967730>paper</a> <a href=https://arxiv.org/pdf/1903.09102.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 13K indoor video clips each showing trajectories of persons ending in close proximity (near collision) with the camera mounted on a mobile suitcase-shaped platform
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Robot</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Manglik et al., "Forecasting Time-To-Collision From Monocular Video: Feasibility, Dataset, And Challenges", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8967730>paper</a> <a href=https://arxiv.org/pdf/1903.09102.pdf>arxiv</a> <a href=https://github.com/aashi7/NearCollision>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#luggage">Luggage</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mae">MAE</a></li>
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
<a name=pku-mmd></a>
<details close>
<summary><l style="font-size:20px"><strong>PKU-MMD</strong></l> <a href=http://www.icst.pku.edu.cn/struct/Projects/PKUMMD.html>link</a> <a href=https://arxiv.org/pdf/1703.07475.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A multimodal dataset of 41 daily activities and 10 interaction actions recorded from 3 camera views using 60 subjects
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, IR, 3D pose, multiview, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity, Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liu et al., "Ssnet: Scale Selection Network For Online 3D Action Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_SSNet_Scale_Selection_CVPR_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#pku-mmd">PKU-MMD</a></li>
<li><a href="../datasets/year_datasets.md#oad">OAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=recipe1m></a>
<details close>
<summary><l style="font-size:20px"><strong>Recipe1M</strong></l> <a href=http://pic2recipe.csail.mit.edu/>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Learning_Cross-Modal_Embeddings_With_Adversarial_Networks_for_Cooking_Recipes_and_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.01273.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 1M+ cooking recipes with 13M food images
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB (image), text</li>
<li><em><strong>Task:</strong></em> Cooking</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sener et al., "Zero-Shot Anticipation For Instructional Activities", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Sener_Zero-Shot_Anticipation_for_Instructional_Activities_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.02501.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#youcook2">YouCook2</a></li>
<li><a href="../datasets/year_datasets.md#recipe1m">Recipe1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#recall">Recall</a></li>
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
<a name=ava></a>
<details close>
<summary><l style="font-size:20px"><strong>Atomic Visual Actions (AVA)</strong></l> <a href=https://research.google.com/ava/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Gu_AVA_A_Video_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.08421.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An action dataset of 80 atomic visual actions in 430 videos with 1.62M corresponding labels localized in space and time
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sun et al., "Relational Action Forecasting", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Sun_Relational_Action_Forecasting_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.04231.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
<li><a href="../datasets/year_datasets.md#ava">AVA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ap">AP</a></li>
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
<a name=bu_action></a>
<details close>
<summary><l style="font-size:20px"><strong>BU Action (BUA)</strong></l> <a href=http://cs-people.bu.edu/sbargal/BU-action/>link</a> <a href=https://www.sciencedirect.com/science/article/abs/pii/S0031320317300353>paper</a> <a href=https://arxiv.org/pdf/1512.07155.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of action images with 23K+ images and 101 activity classes collected from existing action video datasets
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB (image), activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Safaei et al., "Still Image Action Recognition By Predicting Spatial-Temporal Pixel Evolution", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8658386>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#willow_action">Willow Action</a></li>
<li><a href="../datasets/year_datasets.md#wider">WIDER</a></li>
<li><a href="../datasets/year_datasets.md#stanford-40">Stanford-40</a></li>
<li><a href="../datasets/year_datasets.md#bu_action">BU Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#map">mAP</a></li>
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
<a name=epic-fail></a>
<details close>
<summary><l style="font-size:20px"><strong>Epic-Fail</strong></l> <a href=http://aliensunmin.github.io/project/video-Forecasting/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Zeng_Agent-Centric_Risk_Assessment_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.06560.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A risk-assessment dataset of failed activity videos with 3K samples annotated at every 15 frames with bounding boxes around risky regions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, trajectory, temporal segment</li>
<li><em><strong>Task:</strong></em> Risk assessment</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zeng et al., "Agent-Centric Risk Assessment: Accident Anticipation And Risky Region Localization", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Zeng_Agent-Centric_Risk_Assessment_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.06560.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#dad">DAD</a></li>
<li><a href="../datasets/year_datasets.md#epic-fail">Epic-Fail</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#map">mAP</a></li>
<li><a href="../metrics.md#tta">TTA</a></li>
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
<a name=acticipate></a>
<details close>
<summary><l style="font-size:20px"><strong>ACTICIPATE</strong></l> <a href=http://vislab.isr.tecnico.ulisboa.pt/datasets/>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/8460924/>paper</a> <a href=https://arxiv.org/pdf/1802.10503.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A collection of datasets for human-robot interaction involving object handover between humans and human-robots
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, gaze, pose</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Schydlo et al., "Anticipation In Human-Robot Cooperation: A Recurrent Neural Network Approach For Multiple Action Sequences Prediction", ICRA, 2018.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8460924>paper</a> <a href=https://arxiv.org/pdf/1802.10503.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#cad-120">CAD-120</a></li>
<li><a href="../datasets/year_datasets.md#acticipate">ACTICIPATE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#f1">F1</a></li>
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
<a name=oa></a>
<details close>
<summary><l style="font-size:20px"><strong>Ongoing Activity (OA)</strong></l> <a href=http://www.mpii.de/ongoing-activity>link</a> <a href=https://ieeexplore.ieee.org/document/7477586>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 450+ activities, such as cooking, house chores, etc.,  videos collected from public video sharing websites
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Li et al., "Recognition Of Ongoing Complex Activities By Sequence Prediction Over A Hierarchical Label Space", WACV, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7477586>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#oa">OA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=youcook2></a>
<details close>
<summary><l style="font-size:20px"><strong>YouCook2</strong></l> <a href=http://youcook2.eecs.umich.edu/>link</a> <a href=https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/17344/16367>paper</a> <a href=https://arxiv.org/pdf/1703.09788.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset consists of 2K videos of cooking 89 recipes with corresponding English descriptions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, audio, text, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sener et al., "Zero-Shot Anticipation For Instructional Activities", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Sener_Zero-Shot_Anticipation_for_Instructional_Activities_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.02501.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#youcook2">YouCook2</a></li>
<li><a href="../datasets/year_datasets.md#recipe1m">Recipe1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#recall">Recall</a></li>
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
<a name=viena></a>
<details close>
<summary><l style="font-size:20px"><strong>VIENA</strong></l> <a href=https://sites.google.com/view/viena2-project/home>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20887-5_28>paper</a> <a href=https://arxiv.org/pdf/1810.09044.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A virtual driving dataset for action anticipation containing 5 different driving scenarios and 25 action classes
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving (simulation)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Aliakbarian et al., "Viena: A Driving Anticipation Dataset", ACCV, 2019.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20887-5_28>paper</a> <a href=https://arxiv.org/pdf/1810.09044.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#viena">VIENA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=egtea_gaze+></a>
<details close>
<summary><l style="font-size:20px"><strong>Extended Georgia Tech Egocentric Activity Gaze+ (EGTEA Gaze+)</strong></l> <a href=http://www.cbi.gatech.edu/fpv/>link</a> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yin_Li_In_the_Eye_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.00626.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An egocentric cooking action dataset with 28 hours of recording with 86 unique sessions of 32 subjects with framerate of 30hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, gaze, mask, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Furnari et al., "What Would You Expect? Anticipating Egocentric Actions With Rolling-Unrolling Lstms And Modality Attention", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Furnari_What_Would_You_Expect_Anticipating_Egocentric_Actions_With_Rolling-Unrolling_LSTMs_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.09035.pdf>arxiv</a> <a href=https://github.com/fpv-iplab/rulstm>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../datasets/year_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#recall">Recall</a></li>
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
<a name=ntu_rgb-d></a>
<details close>
<summary><l style="font-size:20px"><strong>NTU RGB-D</strong></l> <a href=http://rose1.ntu.edu.sg/Datasets/actionRecognition.asp>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Shahroudy_NTU_RGBD_A_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1604.02808.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An action dataset of 60 daily activities in 56K+ video samples
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, IR, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Wang et al., "Progressive Teacher-Student Learning For Early Action Prediction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Progressive_Teacher-Student_Learning_for_Early_Action_Prediction_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
<li><a href="../datasets/year_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=wnp></a>
<details close>
<summary><l style="font-size:20px"><strong>Watch-n-Push (WnP)</strong></l> <a href=http://watchnpatch.cs.cornell.edu/>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Wu_Watch-n-Patch_Unsupervised_Understanding_2015_CVPR_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1603.03541.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 458 videos of 21 daily actions in office and kitchen environments recorded using a Kinect V2 sensor
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D pose, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kataoka et al., "Recognition Of Transitional Action For Short-Term Action Prediction Using Discriminative Temporal Cnn Feature", BMVC, 2016.</em> <a href=http://www.bmva.org/bmvc/2016/papers/paper012/paper012.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#wnp">WnP</a></li>
<li><a href="../datasets/year_datasets.md#utka">UTKA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=oad></a>
<details close>
<summary><l style="font-size:20px"><strong>Online Action Detection (OAD)</strong></l> <a href=http://www.icst.pku.edu.cn/struct/Projects/OAD.html>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46478-7_13>paper</a> <a href=https://arxiv.org/pdf/1604.05633.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 10 indoor activities in 59 sequences collected using a Kinect V2 sensor
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D pose, activity label, temporal segment, Tracking ID</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liu et al., "Ssnet: Scale Selection Network For Online 3D Action Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_SSNet_Scale_Selection_CVPR_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#pku-mmd">PKU-MMD</a></li>
<li><a href="../datasets/year_datasets.md#oad">OAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=msrda></a>
<details close>
<summary><l style="font-size:20px"><strong>MSR Daily Activity (MSRDA)</strong></l> <a href=https://documents.uow.edu.au/~wanqing/MSRActionRecognitionDatasetsCodes%20-%20Zicheng.htm>link</a> <a href=https://ieeexplore.ieee.org/document/6247813>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 16 activities, such as writing on a paper, using a laptop, using a vacuum cleaner, cheering up, etc., performed by 10 subjects, recording using a Kinect sensor
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhang et al., "Bio-Inspired Predictive Orientation Decomposition Of Skeleton Trajectories For Real-Time Human Activity Prediction", ICRA, 2015.</em> <a href=https://ieeexplore.ieee.org/document/7139618>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#msrda">MSRDA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=daimler></a>
<details close>
<summary><l style="font-size:20px"><strong>Daimler</strong></l> <a href=http://www.gavrila.net/Datasets/Daimler_Pedestrian_Benchmark_D/Daimler_Mono_Ped__Detection_Be/daimler_mono_ped__detection_be.html>link</a> <a href=https://ieeexplore.ieee.org/document/4657363>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A grayscale dataset of 70K+ pedestrian samples recorded during the course of 27 minutes of driving
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Grayscale, bounding box</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hariyono et al., "Estimation Of Collision Risk For Improving Driver'S Safety", IECON, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7793743>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#eth_pedestrian">ETH Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#daimler">Daimler</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#auc">AUC</a></li>
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
    journal = "PAMI",
    volume = "31",
    number = "12",
    pages = "2179--2195",
    year = "2008"
}
</pre>
</details>

</ul></details>
<a name=ca></a>
<details close>
<summary><l style="font-size:20px"><strong>Collective Activity (CA)</strong></l> <a href=http://www-personal.umich.edu/~wgchoi/eccv12/wongun_eccv12.html>link</a> <a href=https://ieeexplore.ieee.org/document/5457461>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 40+ video clips showing collective activities including  crossing, waiting, queueing, walking and talking
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, attribute, activity label, temporal segment, pose</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yao et al., "Multiple Granularity Group Interaction Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0721.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#sbuki">SBUKI</a></li>
<li><a href="../datasets/year_datasets.md#ca">CA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=willow_action></a>
<details close>
<summary><l style="font-size:20px"><strong>Willow Action</strong></l> <a href=https://www.di.ens.fr/willow/research/stillactions/>link</a> <a href=http://www.bmva.org/bmvc/2010/conference/paper97/paper97.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 7 actions, e.g. riding a bike, riding a horse, running, depicted in 968 RGB and grayscale images
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB (image), Grayscale (image) activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Safaei et al., "Still Image Action Recognition By Predicting Spatial-Temporal Pixel Evolution", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8658386>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#willow_action">Willow Action</a></li>
<li><a href="../datasets/year_datasets.md#wider">WIDER</a></li>
<li><a href="../datasets/year_datasets.md#stanford-40">Stanford-40</a></li>
<li><a href="../datasets/year_datasets.md#bu_action">BU Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#map">mAP</a></li>
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
<a name=stanford-40></a>
<details close>
<summary><l style="font-size:20px"><strong>Stanford-40</strong></l> <a href=http://vision.stanford.edu/Datasets/40actions.html>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/6126386>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 40 actions with 9.5K+ RGB images and the corresponding bounding boxes around actors
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB (image), bounding box, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Safaei et al., "Still Image Action Recognition By Predicting Spatial-Temporal Pixel Evolution", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8658386>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#willow_action">Willow Action</a></li>
<li><a href="../datasets/year_datasets.md#wider">WIDER</a></li>
<li><a href="../datasets/year_datasets.md#stanford-40">Stanford-40</a></li>
<li><a href="../datasets/year_datasets.md#bu_action">BU Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#map">mAP</a></li>
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
<a name=hmdb></a>
<details close>
<summary><l style="font-size:20px"><strong>Human Motion Database (HMDB)</strong></l> <a href=http://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database/>link</a> <a href=https://ieeexplore.ieee.org/document/6126543>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 6.8K+ video clips of 51 actions corresponding to general facial actions (laughing), facial actions with object manipulation (smoking), general body movements (clapping hands), body movements with object interaction (catching), and body movements for human interaction (fencing)
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, mask, activity label, attribute</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Cho et al., "A Temporal Sequence Learning For Action Recognition And Prediction", WACV, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8354149>paper</a> <a href=https://arxiv.org/pdf/1906.06813.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#hmdb">HMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=utka></a>
<details close>
<summary><l style="font-size:20px"><strong>UTKinect-Action (UTKA)</strong></l> <a href=http://cvrc.ece.utexas.edu/KinectDatasets/HOJ3D.html>link</a> <a href=https://ieeexplore.ieee.org/document/6239233>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 10 basic actions, e.g. throwing, pushing, pulling, each performed by 10 subjects using a Kinect sensor recorded at 15fps
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D pose, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kataoka et al., "Recognition Of Transitional Action For Short-Term Action Prediction Using Discriminative Temporal Cnn Feature", BMVC, 2016.</em> <a href=http://www.bmva.org/bmvc/2016/papers/paper012/paper012.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#wnp">WnP</a></li>
<li><a href="../datasets/year_datasets.md#utka">UTKA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=sbuki></a>
<details close>
<summary><l style="font-size:20px"><strong>SBU Kinetic Interction (SBUKI)</strong></l> <a href=https://www3.cs.stonybrook.edu/~kyun/research/kinect_interaction/index.html>link</a> <a href=https://ieeexplore.ieee.org/document/6239234>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 8 dyadic human interactions, e.g. approaching, departing, pushing, kicking, recorded from 7 participants using a Kinect sensor comprising a total of approx. 300 interactions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yao et al., "Multiple Granularity Group Interaction Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0721.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#sbuki">SBUKI</a></li>
<li><a href="../datasets/year_datasets.md#ca">CA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=maniac></a>
<details close>
<summary><l style="font-size:20px"><strong>MANIAC</strong></l> <a href=https://alexandria.physik3.uni-goettingen.de/cns-group/datasets/maniac/>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/6163000>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An object manipulation action dataset with 8 different manipulation actions performed by 5 different subjects recorded using a Kinect sensor
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, semantic segment, activity label</li>
<li><em><strong>Task:</strong></em> Object interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ziaeetabar et al., "Prediction Of Manipulation Action Classes Using Semantic Spatial Reasoning", IROS, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8593717>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#maniac">MANIAC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#pp">PP</a></li>
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
<a name=tv_series></a>
<details close>
<summary><l style="font-size:20px"><strong>TV Series</strong></l> <a href=https://github.com/zhenyangli/online_action>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46454-1_17>paper</a> <a href=https://arxiv.org/pdf/1604.06506.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A collection of sequences collected from TV series for the purpose of action detection
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Gao et al., "Red: Reinforced Encoder-Decoder Networks For Action Anticipation", BMVC, 2017.</em> <a href=http://www.bmva.org/bmvc/2017/papers/paper092/paper092.pdf>paper</a> <a href=https://arxiv.org/pdf/1707.04818.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
<li><a href="../datasets/year_datasets.md#tv_series">TV Series</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#map">mAP</a></li>
<li><a href="../metrics.md#cap">cAP</a></li>
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
<a name=gtea_gaze></a>
<details close>
<summary><l style="font-size:20px"><strong>Georgia Tech Egocentric Activity Gaze (GTEA Gaze)</strong></l> <a href=http://www.cbi.gatech.edu/fpv/>link</a> <a href=https://link.springer.com/content/pdf/10.1007%2F978-3-642-33718-5_23.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An egocentric dataset of 17 cooking activity videos performed by 14 subjects
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, gaze, mask, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Shen et al., "Egocentric Activity Prediction Via Event Modulated Attention", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Shen_Egocentric_Activity_Prediction_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#gtea_gaze+">GTEA Gaze+</a></li>
<li><a href="../datasets/year_datasets.md#gtea_gaze">GTEA Gaze</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=orgbd></a>
<details close>
<summary><l style="font-size:20px"><strong>Online RGBD Action Dataset (ORGBD)</strong></l> <a href=https://sites.google.com/site/skicyyu/orgbd>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-16814-2_4>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of RGBD sequences capturing 7  human-object interaction activities including drinking, eating, using a laptop, reading on a cellphone, etc.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, bounding box, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hu et al., "Real-Time Rgb-D Activity Prediction By Soft Regression", ECCV, 2016.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46448-0_17>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
<li><a href="../datasets/year_datasets.md#orgbd">ORGBD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=wider></a>
<details close>
<summary><l style="font-size:20px"><strong>WIDER</strong></l> <a href=http://yjxiong.me/event_recog/WIDER/>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Xiong_Recognize_Complex_Events_2015_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A complex event dataset of 61 event categories in 50K+ images
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB (image), activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Safaei et al., "Still Image Action Recognition By Predicting Spatial-Temporal Pixel Evolution", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8658386>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#willow_action">Willow Action</a></li>
<li><a href="../datasets/year_datasets.md#wider">WIDER</a></li>
<li><a href="../datasets/year_datasets.md#stanford-40">Stanford-40</a></li>
<li><a href="../datasets/year_datasets.md#bu_action">BU Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#map">mAP</a></li>
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
<a name=eth_pedestrian></a>
<details close>
<summary><l style="font-size:20px"><strong>ETH Pedestrian</strong></l> <a href=https://data.vision.ee.ethz.ch/cvl/aess/>link</a> <a href=https://ieeexplore.ieee.org/document/4409092>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of pedestrians recorded using a mobile platform with 5K+ frames span over 6 minutes
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hariyono et al., "Estimation Of Collision Risk For Improving Driver'S Safety", IECON, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7793743>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#eth_pedestrian">ETH Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#daimler">Daimler</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#auc">AUC</a></li>
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
<a name=gtea_gaze+></a>
<details close>
<summary><l style="font-size:20px"><strong>Georgia Tech Egocentric Activity Gaze+ (GTEA Gaze+)</strong></l> <a href=http://www.cbi.gatech.edu/fpv/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2015/papers/Li_Delving_Into_Egocentric_2015_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An egocentric dataset of 37 videos of 7 cooking activities recorded from 26 subjects with the corresponding gaze tracking information
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, gaze, mask, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Shen et al., "Egocentric Activity Prediction Via Event Modulated Attention", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Shen_Egocentric_Activity_Prediction_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#gtea_gaze+">GTEA Gaze+</a></li>
<li><a href="../datasets/year_datasets.md#gtea_gaze">GTEA Gaze</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhou et al., "Temporal Perception And Prediction In Ego-Centric Video", ICCV, 2015.</em> <a href=https://openaccess.thecvf.com/content_iccv_2015/papers/Zhou_Temporal_Perception_and_ICCV_2015_paper.pdf>paper</a> <a href=https://github.com/aditya7874/Activity-Prediction-in-EgoCentric-Videos>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#fppa">FPPA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=cmu_panoptic></a>
<details close>
<summary><l style="font-size:20px"><strong>CMU Panoptic</strong></l> <a href=http://domedb.perception.cs.cmu.edu/index.html>link</a> <a href=https://openaccess.thecvf.com/content_iccv_2015/papers/Joo_Panoptic_Studio_A_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1612.03153.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A multiview group activity dataset recorded with 10 RGB-D sensors and 30+ HD views with the corresponding 3D annotations
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, multiview, 3D pose, 3D facial landmark, Transcripts</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Joo et al., "Towards Social Artificial Intelligence: Nonverbal Social Signal Prediction In A Triadic Interaction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Joo_Towards_Social_Artificial_Intelligence_Nonverbal_Social_Signal_Prediction_in_a_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.04158.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=oops!></a>
<details close>
<summary><l style="font-size:20px"><strong>Oops!</strong></l> <a href=https://oops.cs.columbia.edu/data/>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Epstein_Oops_Predicting_Unintentional_Action_in_Video_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.11206.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 20K+ video clips of failed actions including physical and social errors, errors in planning and execution, etc
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity Label, Temporal Segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Epstein et al., "Oops! Predicting Unintentional Action in Video", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Epstein_Oops_Predicting_Unintentional_Action_in_Video_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.11206.pdf>arxiv</a> <a href=https://github.com/cvlab-columbia/oops>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#oops!">Oops!</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Epstein_2020_CVPR,
    author = "Epstein, Dave and Chen, Boyuan and Vondrick, Carl",
    title = "Oops! Predicting Unintentional Action in Video",
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
@InProceedings{Epstein_2020_CVPR,
    author = "Epstein, Dave and Chen, Boyuan and Vondrick, Carl",
    title = "Oops! Predicting Unintentional Action in Video",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul></details>
</ul><a name=datasets_Trajectory></a>
<h2>Trajectory</h2> <a href=#top>&uarr; top</a>
<ul><a name=ucy></a>
<details close>
<summary><l style="font-size:20px"><strong>UCY</strong></l> <a href=https://graphics.cs.ucy.ac.cy/research/downloads/crowd-data>link</a> <a href=https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1467-8659.2007.01089.x>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of surveillance videos capturing 900+ pedestrian trajectories in outdoor environments containing 4 videos
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, trajectory, gaze</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Fang et al., "TPNet: Trajectory Proposal Network for Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Fang_TPNet_Trajectory_Proposal_Network_for_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.12255.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#minade">minADE</a></li>
<li><a href="../metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics.md#dac">DAC</a></li>
<li><a href="../metrics.md#wsfde">WSFDE</a></li>
<li><a href="../metrics.md#wsade">WSADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Fang_2020_CVPR,
    author = "Fang, Liangji and Jiang, Qinhong and Shi, Jianping and Zhou, Bolei",
    title = "TPNet: Trajectory Proposal Network for Motion Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Hu et al., "Collaborative Motion Prediction via Neural Motion Message Passing", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Hu_Collaborative_Motion_Prediction_via_Neural_Motion_Message_Passing_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.06594.pdf>arxiv</a> <a href=https://github.com/PhyllisH/NMMP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<summary><em>Sun et al., "Recursive Social Behavior Graph for Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Sun_Recursive_Social_Behavior_Graph_for_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.10402.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<summary><em>Sun et al., "Reciprocal Learning Networks for Human Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Sun_Reciprocal_Learning_Networks_for_Human_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.04340.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2020_CVPR_2,
    author = "Sun, Hao and Zhao, Zhiqun and He, Zhihai",
    title = "Reciprocal Learning Networks for Human Trajectory Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Haddad et al., "Self-Growing Spatial Graph Networks for Pedestrian Trajectory Prediction", WACV, 2020.</em> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Haddad_Self-Growing_Spatial_Graph_Networks_for_Pedestrian_Trajectory_Prediction_WACV_2020_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<summary><em>Li, "Which Way Are You Going? Imitative Decision Learning For Path Forecasting In Dynamic Scenes", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Which_Way_Are_You_Going_Imitative_Decision_Learning_for_Path_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#minade">minADE</a></li>
<li><a href="../metrics.md#minfde">minFDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#virat/actev">VIRAT/ActEV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ll">LL</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#minade">minADE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
<li><a href="../datasets/year_datasets.md#interaction">INTERACTION</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
<li><a href="../datasets/year_datasets.md#pets2009">PETS2009</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#town_center">Town Center</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#gc">GC</a></li>
<li><a href="../datasets/year_datasets.md#chuk">CHUK</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#ande">ANDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#town_center">Town Center</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#mane">MAnE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#town_center">Town Center</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#nll">NLL</a></li>
<li><a href="../metrics.md#scr">SCR</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#ande">ANDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
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
<a name=eth></a>
<details close>
<summary><l style="font-size:20px"><strong>ETH</strong></l> <a href=https://icu.ee.ethz.ch/research/datsets.html>link</a> <a href=https://ieeexplore.ieee.org/document/5459260>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of pedestrian trajectory with 650 tracks in 25+ minutes of video footage
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, trajectory</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Fang et al., "TPNet: Trajectory Proposal Network for Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Fang_TPNet_Trajectory_Proposal_Network_for_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.12255.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#minade">minADE</a></li>
<li><a href="../metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics.md#dac">DAC</a></li>
<li><a href="../metrics.md#wsfde">WSFDE</a></li>
<li><a href="../metrics.md#wsade">WSADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Fang_2020_CVPR,
    author = "Fang, Liangji and Jiang, Qinhong and Shi, Jianping and Zhou, Bolei",
    title = "TPNet: Trajectory Proposal Network for Motion Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Hu et al., "Collaborative Motion Prediction via Neural Motion Message Passing", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Hu_Collaborative_Motion_Prediction_via_Neural_Motion_Message_Passing_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.06594.pdf>arxiv</a> <a href=https://github.com/PhyllisH/NMMP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<summary><em>Sun et al., "Recursive Social Behavior Graph for Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Sun_Recursive_Social_Behavior_Graph_for_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.10402.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<summary><em>Sun et al., "Reciprocal Learning Networks for Human Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Sun_Reciprocal_Learning_Networks_for_Human_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.04340.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2020_CVPR_2,
    author = "Sun, Hao and Zhao, Zhiqun and He, Zhihai",
    title = "Reciprocal Learning Networks for Human Trajectory Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Haddad et al., "Self-Growing Spatial Graph Networks for Pedestrian Trajectory Prediction", WACV, 2020.</em> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Haddad_Self-Growing_Spatial_Graph_Networks_for_Pedestrian_Trajectory_Prediction_WACV_2020_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<summary><em>Li, "Which Way Are You Going? Imitative Decision Learning For Path Forecasting In Dynamic Scenes", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Which_Way_Are_You_Going_Imitative_Decision_Learning_for_Path_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#minade">minADE</a></li>
<li><a href="../metrics.md#minfde">minFDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#virat/actev">VIRAT/ActEV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#minade">minADE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
<li><a href="../datasets/year_datasets.md#interaction">INTERACTION</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
<li><a href="../datasets/year_datasets.md#pets2009">PETS2009</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#gc">GC</a></li>
<li><a href="../datasets/year_datasets.md#chuk">CHUK</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#ande">ANDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ed">ED</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#ande">ANDE</a></li>
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
<a name=kitti></a>
<details close>
<summary><l style="font-size:20px"><strong>KITTI</strong></l> <a href=http://www.cvlibs.net/datasets/kitti/>link</a> <a href=https://ieeexplore.ieee.org/document/6248074>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale driving dataset recorded with different modalities including stereo, LIDAR, GPS, etc. recorded at 10hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, LIDAR, bounding box, optical flow, vehicle sensors, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Jin et al., "Exploring Spatial-Temporal Multi-Frequency Analysis for High-Fidelity and Temporal-Consistency Video Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Jin_Exploring_Spatial-Temporal_Multi-Frequency_Analysis_for_High-Fidelity_and_Temporal-Consistency_Video_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2002.09905.pdf>arxiv</a> <a href=https://github.com/Bei-Jin/STMFANet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="../datasets/year_datasets.md#bair">BAIR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics.md#fvd">FVD</a></li>
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
<summary><em>Wu et al., "Future Video Synthesis With Object Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Wu_Future_Video_Synthesis_With_Object_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.00542.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics.md#ms-ssim">MS-SSIM</a></li>
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
<summary><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle Gan", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#chuk_avenue">CHUK Avenue</a></li>
<li><a href="../datasets/year_datasets.md#shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#yuv">YUV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Liu et al., "Dyan: A Dynamical Atoms-Based Network For Video Prediction", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Wenqian_Liu_DYAN_A_Dynamical_ECCV_2018_paper.pdf>paper</a> <a href=https://github.com/liuem607/DYAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Liang et al., "Dual Motion Gan For Future-Flow Embedded Video Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Liang_Dual_Motion_GAN_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00284.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Marchetti et al., "MANTRA: Memory Augmented Networks for Multiple Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Marchetti_MANTRA_Memory_Augmented_Networks_for_Multiple_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.03340.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#orc">ORC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Marchetti_2020_CVPR,
    author = "Marchetti, Francesco and Becattini, Federico and Seidenari, Lorenzo and Del Bimbo, Alberto",
    title = "MANTRA: Memory Augmented Networks for Multiple Trajectory Prediction",
    booktitle = "CVPR",
    year = "2020"
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#oxford">Oxford</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#meanmsd">meanMSD</a></li>
<li><a href="../metrics.md#minmsd">minMSD</a></li>
<li><a href="../metrics.md#ce">CE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ed">ED</a></li>
<li><a href="../metrics.md#mined">minED</a></li>
<li><a href="../metrics.md#maxd">maxD</a></li>
<li><a href="../metrics.md#miss_rate">Miss rate</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#run_time">Run Time</a></li>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#tp">TP</a></li>
<li><a href="../metrics.md#tn">TN</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#f1">F1</a></li>
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
<a name=ngsim></a>
<details close>
<summary><l style="font-size:20px"><strong>Next Generation simulationulation (NGSIM)</strong></l> <a href=https://catalog.data.gov/dataset/next-generation-simulation-ngsim-vehicle-trajectories>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of vehicle trajectories containing 10K+ frames of recording
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Map, trajectory</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ding et al., "Predicting Vehicle Behaviors Over An Extended Horizon Using Behavior Interaction Network", ICRA, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8794146>paper</a> <a href=https://arxiv.org/pdf/1903.00848.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
<li><a href="../metrics.md#f1">F1</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
<li><a href="../metrics.md#ttm">TTM</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#traf">TRAF</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ll">LL</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ll">LL</a></li>
<li><a href="../metrics.md#kld">KLD</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
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
<a name=cityscapes></a>
<details close>
<summary><l style="font-size:20px"><strong>Cityscapes</strong></l> <a href=https://www.cityscapes-dataset.com/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Cordts_The_Cityscapes_Dataset_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1604.01685.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A driving dataset of street images with annotations for 30 traffic objects in 5k frames and weak annotations in 20k frames
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, bounding box, semantic segment, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Wu et al., "Future Video Synthesis With Object Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Wu_Future_Video_Synthesis_With_Object_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.00542.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics.md#ms-ssim">MS-SSIM</a></li>
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
<summary><em>Castrejon et al., "Improved Conditional Vrnns For Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Castrejon_Improved_Conditional_VRNNs_for_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.12165.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics.md#fvd">FVD</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Saric et al., "Warp to the Future: Joint Forecasting of Features and Feature Motion", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Saric_Warp_to_the_Future_Joint_Forecasting_of_Features_and_Feature_CVPR_2020_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#iou">IoU</a></li>
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
<summary><em>Srikanth et al., "Infer: Intermediate Representations For Future Prediction", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8968553>paper</a> <a href=https://arxiv.org/pdf/1903.10641.pdf>arxiv</a> <a href=https://rebrand.ly/INFER-results>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#oxford">Oxford</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
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
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#iou">IoU</a></li>
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
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#iou">IoU</a></li>
<li><a href="../metrics.md#voi">VoI</a></li>
<li><a href="../metrics.md#gce">GCE</a></li>
<li><a href="../metrics.md#ri">RI</a></li>
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
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#iou">IoU</a></li>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mse">MSE</a></li>
<li><a href="../metrics.md#miou">MIoU</a></li>
<li><a href="../metrics.md#epe">EPE</a></li>
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
<a name=jaad></a>
<details close>
<summary><l style="font-size:20px"><strong>Joint Attention in Autonomous Driving (JAAD)</strong></l> <a href=http://data.nvision2.eecs.yorku.ca/JAAD_dataset/>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w3/Rasouli_Are_They_Going_ICCV_2017_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of pedestrians with 346 video sequences showing pedestrians at the time of crossing in different geographical locations and under different weather conditions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, attribute, temporal segment, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chaabane et al., "Looking Ahead: Anticipating Pedestrians Crossing with Future Frames Prediction", WACV, 2020.</em> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Chaabane_Looking_Ahead_Anticipating_Pedestrians_Crossing_with_Future_Frames_Prediction_WACV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.09077.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#l1">L1</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#l1">L1</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ap">AP</a></li>
<li><a href="../metrics.md#run_time">Run Time</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#viena">VIENA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#map">mAP</a></li>
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
<summary><em>Mangalam et al., "Disentangling Human Dynamics for Pedestrian Locomotion Forecasting with Noisy Supervision", WACV, 2020.</em> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Mangalam_Disentangling_Human_Dynamics_for_Pedestrian_Locomotion_Forecasting_with_Noisy_Supervision_WACV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.01138.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#kde">KDE</a></li>
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
<summary><em>Rasouli et al., "Pie: A Large-Scale Dataset And Models For Pedestrian Intention Estimation And Trajectory Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.pdf>paper</a> <a href=https://github.com/aras62/PIEPredict>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psi">Psi</a></li>
<li><a href="../metrics.md#ism">ISM</a></li>
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
<a name=sd></a>
<details close>
<summary><l style="font-size:20px"><strong>Stanford Drone (SD)</strong></l> <a href=http://cvgl.stanford.edu/projects/uav_data/>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46484-8_33>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of pedestrians and cyclists movements recorded using an aerial drone with 3K+ tracks
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, object class, Tracking ID</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Haddad et al., "Self-Growing Spatial Graph Networks for Pedestrian Trajectory Prediction", WACV, 2020.</em> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Haddad_Self-Growing_Spatial_Graph_Networks_for_Pedestrian_Trajectory_Prediction_WACV_2020_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<summary><em>Li, "Which Way Are You Going? Imitative Decision Learning For Path Forecasting In Dynamic Scenes", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Which_Way_Are_You_Going_Imitative_Decision_Learning_for_Path_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#minade">minADE</a></li>
<li><a href="../metrics.md#minfde">minFDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
<li><a href="../datasets/year_datasets.md#interaction">INTERACTION</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
<li><a href="../datasets/year_datasets.md#pets2009">PETS2009</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ed">ED</a></li>
<li><a href="../metrics.md#mined">minED</a></li>
<li><a href="../metrics.md#maxd">maxD</a></li>
<li><a href="../metrics.md#miss_rate">Miss rate</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
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
<a name=gc></a>
<details close>
<summary><l style="font-size:20px"><strong>New York Grand Central (GC)</strong></l> <a href=http://www.ee.cuhk.edu.hk/~xgwang/grandcentral.html>link</a> <a href=https://ieeexplore.ieee.org/document/6248013>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A trajectory dataset of pedestrians walking in the train station with 50K+ samples annotated at 25fps
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, trajectory</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Xu et al., "Encoding Crowd Interaction With Deep Neural Network For Pedestrian Trajectory Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/2136.pdf>paper</a> <a href=https://github.com/svip-lab/CIDNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#gc">GC</a></li>
<li><a href="../datasets/year_datasets.md#chuk">CHUK</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#ande">ANDE</a></li>
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
<li><a href="../datasets/year_datasets.md#gc">GC</a></li>
<li><a href="../datasets/year_datasets.md#qmul">QMUL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
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
<li><a href="../datasets/year_datasets.md#gc">GC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#gc">GC</a></li>
<li><a href="../datasets/year_datasets.md#mitt">MITT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ed">ED</a></li>
<li><a href="../metrics.md#run_time">Run Time</a></li>
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
<a name=wod></a>
<details close>
<summary><l style="font-size:20px"><strong>Waymo Open Dataset (WOD)</strong></l> <a href=https://waymo.com/open/>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Sun_Scalability_in_Perception_for_Autonomous_Driving_Waymo_Open_Dataset_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.04838.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset with approx. 2K driving segments and 20M+ 2D/3D bounding boxes annotated at 10hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, LIDAR, Bounding Box, 3D Bounding Box, Object Class, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Makansi et al., "Multimodal Future Localization and Emergence Prediction for Objects in Egocentric View With a Reachability Prior", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Makansi_Multimodal_Future_Localization_and_Emergence_Prediction_for_Objects_in_Egocentric_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.04700.pdf>arxiv</a> <a href=https://github.com/lmb-freiburg/FLN-EPN-RPN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/year_datasets.md#fit">FIT</a></li>
<li><a href="../datasets/year_datasets.md#mapillary_vistas">Mapillary Vistas</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#nll">NLL</a></li>
<li><a href="../metrics.md#iou">IoU</a></li>
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
<details close>
<summary><em>Mohamed et al., "Social-STGCNN: A Social Spatio-Temporal Graph Convolutional Neural Network for Human Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Mohamed_Social-STGCNN_A_Social_Spatio-Temporal_Graph_Convolutional_Neural_Network_for_Human_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2002.11927.pdf>arxiv</a> <a href=https://github.com/abduallahmohamed/Social-STGCNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#waymo">Waymo</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mohamed_2020_CVPR,
    author = "Mohamed, Abduallah and Qian, Kun and Elhoseiny, Mohamed and Claudel, Christian",
    title = "Social-STGCNN: A Social Spatio-Temporal Graph Convolutional Neural Network for Human Trajectory Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhang et al., "STINet: Spatio-Temporal-Interactive Network for Pedestrian Detection and Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_STINet_Spatio-Temporal-Interactive_Network_for_Pedestrian_Detection_and_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.04255.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/year_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#bev_ap">BEV AP</a></li>
<li><a href="../metrics.md#de">DE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2020_CVPR,
    author = "Zhang, Zhishuai and Gao, Jiyang and Mao, Junhua and Liu, Yukai and Anguelov, Dragomir and Li, Congcong",
    title = "STINet: Spatio-Temporal-Interactive Network for Pedestrian Detection and Trajectory Prediction",
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
@InProceedings{Sun_2020_CVPR_3,
    author = "Sun, Pei and Kretzschmar, Henrik and Dotiwalla, Xerxes and Chouard, Aurelien and Patnaik, Vijaysai and Tsui, Paul and Guo, James and Zhou, Yin and Chai, Yuning and Caine, Benjamin and Vasudevan, Vijay and Han, Wei and Ngiam, Jiquan and Zhao, Hang and Timofeev, Aleksei and Ettinger, Scott and Krivokon, Maxim and Gao, Amy and Joshi, Aditya and Zhang, Yu and Shlens, Jonathon and Chen, Zhifeng and Anguelov, Dragomir",
    title = "Scalability in Perception for Autonomous Driving: Waymo Open Dataset",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul></details>
<a name=town_center></a>
<details close>
<summary><l style="font-size:20px"><strong>Town Center</strong></l> <a href=http://www.robots.ox.ac.uk/ActiveVision/Research/Projects/2009bbenfold_headpose/project.html#datasets>link</a> <a href=https://ieeexplore.ieee.org/document/5995667>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of surveillance recording of 2.2K pedestrians walking at the Oxford Town Center
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hasan et al., "Mx-Lstm: Mixing Tracklets And Vislets To Jointly Forecast Trajectories And Head Poses", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Hasan_MX-LSTM_Mixing_Tracklets_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1805.00652.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#town_center">Town Center</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#town_center">Town Center</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#mane">MAnE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#town_center">Town Center</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#nll">NLL</a></li>
<li><a href="../metrics.md#scr">SCR</a></li>
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
<a name=orc></a>
<details close>
<summary><l style="font-size:20px"><strong>Oxford Robot Car (ORC)</strong></l> <a href=https://robotcar-dataset.robots.ox.ac.uk/>link</a> <a href=https://journals.sagepub.com/doi/abs/10.1177/0278364916679498>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset containing 100 repetitions of a consistent route through Oxford driving by a vehicle under different weather and traffic conditions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, LIDAR, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Marchetti et al., "MANTRA: Memory Augmented Networks for Multiple Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Marchetti_MANTRA_Memory_Augmented_Networks_for_Multiple_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.03340.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#orc">ORC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Marchetti_2020_CVPR,
    author = "Marchetti, Francesco and Becattini, Federico and Seidenari, Lorenzo and Del Bimbo, Alberto",
    title = "MANTRA: Memory Augmented Networks for Multiple Trajectory Prediction",
    booktitle = "CVPR",
    year = "2020"
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#oxford">Oxford</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
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
<a name=pie></a>
<details close>
<summary><l style="font-size:20px"><strong>Pedestrian Intention Estimation (PIE)</strong></l> <a href=http://data.nvision2.eecs.yorku.ca/PIE_dataset/>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of driving sequences with more than 6 hours of footage with 1.8K+ pedestrian tracks and 2.3M+ relevant traffic object bounding boxes annotated at 30fps
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, object class, attribute, temporal segment, vehicle sensors, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Rasouli et al., "Pedestrian Action Anticipation Using Contextual Feature Fusion In Stacked Rnns", BMVC, 2019.</em> <a href=https://bmvc2019.org/wp-content/uploads/papers/0283-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.06582.pdf>arxiv</a> <a href=https://github.com/aras62/SF-GRU>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
<li><a href="../metrics.md#f1">F1</a></li>
<li><a href="../metrics.md#auc">AUC</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<a name=chuk_avenue></a>
<details close>
<summary><l style="font-size:20px"><strong>CHUK Avenue</strong></l> <a href=http://www.cse.cuhk.edu.hk/leojia/projects/detectabnormal/dataset.html>link</a> <a href=https://openaccess.thecvf.com/content_iccv_2013/papers/Lu_Abnormal_Event_Detection_2013_ICCV_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 37 video clips with 30K+ frames showing abnormal events
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, anomaly, temporal segment</li>
<li><em><strong>Task:</strong></em> Surveillance, Anomaly</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle Gan", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#chuk_avenue">CHUK Avenue</a></li>
<li><a href="../datasets/year_datasets.md#shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#gc">GC</a></li>
<li><a href="../datasets/year_datasets.md#chuk">CHUK</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#ande">ANDE</a></li>
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
<a name=btd></a>
<details close>
<summary><l style="font-size:20px"><strong>Basketball Tracking Dataset (BTD)</strong></l> <a href=https://github.com/sealneaward/nba-movement-data>link</a> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Panna_Felsen_Where_Will_They_ECCV_2018_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of basketball players’ trajectories for 2015-16 NBA games
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Trajectory</li>
<li><em><strong>Task:</strong></em> Sport</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Qi et al., "Imitative Non-Autoregressive Modeling for Trajectory Forecasting and Imputation", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Qi_Imitative_Non-Autoregressive_Modeling_for_Trajectory_Forecasting_and_Imputation_CVPR_2020_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#btd">BTD</a></li>
<li><a href="../datasets/year_datasets.md#pems-sf">PEMS-SF</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ed">ED</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<summary><em>Felsen et al., "Where Will They Go? Predicting Fine-Grained Adversarial Multi-Agent Motion Using Conditional Variational Autoencoders", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Panna_Felsen_Where_Will_They_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#btd">BTD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#miss_rate">Miss rate</a></li>
<li><a href="../metrics.md#maxd">maxD</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Felsen_2018_ECCV,
    author = "Felsen, Panna and Lucey, Patrick and Ganguly, Sujoy",
    title = "Where Will They Go? Predicting Fine-Grained Adversarial Multi-Agent Motion Using Conditional Variational Autoencoders",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul></details>
<a name=virat/actev></a>
<details close>
<summary><l style="font-size:20px"><strong>VIRAT/ActEV</strong></l> <a href=https://actev.nist.gov/trecvid19>link</a> <a href=https://www-nlpir.nist.gov/projects/tvpubs/tv18.papers/tv18overview.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of multiview surveillance sequences for trajectory  prediction and activity detection of 38 outdoor common activities
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liang et al., "Peeking Into The Future: Predicting Future Person Activities And Locations In Videos", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPRW_2019/papers/Precognition/Liang_Peeking_Into_the_Future_Predicting_Future_Person_Activities_and_Locations_CVPRW_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1902.03748.pdf>arxiv</a> <a href=https://github.com/google/next-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#virat/actev">VIRAT/ActEV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#map">mAP</a></li>
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
<summary><em>Liang et al., "The Garden of Forking Paths: Towards Multi-Future Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Liang_The_Garden_of_Forking_Paths_Towards_Multi-Future_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.06445.pdf>arxiv</a> <a href=https://github.com/JunweiLiang/Multiverse>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#virat/actev">VIRAT/ActEV</a></li>
<li><a href="../datasets/year_datasets.md#multiverse">Multiverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#minade">minADE</a></li>
<li><a href="../metrics.md#minfde">minFDE</a></li>
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
<a name=virat></a>
<details close>
<summary><l style="font-size:20px"><strong>VIRAT</strong></l> <a href=http://viratdata.org/>link</a> <a href=https://ieeexplore.ieee.org/document/5995586>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A multiview dataset of 12 events, such as a person loading an object to a vehicle, a person opening a vehicle trunk, recorded in 11 scenes for a total of approx. 8.5 hours of video footage
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Surveillance, Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Mahmud et al., "Joint Prediction Of Activity Labels And Starting Times In Untrimmed Videos", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Mahmud_Joint_Prediction_of_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#mpii_cooking">MPII Cooking</a></li>
<li><a href="../datasets/year_datasets.md#virat">VIRAT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
<li><a href="../metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/year_datasets.md#virat">VIRAT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#nll">NLL</a></li>
<li><a href="../metrics.md#run_time">Run Time</a></li>
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
<a name=argoverse></a>
<details close>
<summary><l style="font-size:20px"><strong>Argoverse</strong></l> <a href=https://www.argoverse.org/data.html>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_Argoverse_3D_Tracking_and_Forecasting_With_Rich_Maps_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.02620.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset with 100+ driving segments and 10K+ 3D bounding boxes for tracking and 300K+ segments for forecasting annotated at 10hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, LIDAR, 3D bounding box, Map</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Fang et al., "TPNet: Trajectory Proposal Network for Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Fang_TPNet_Trajectory_Proposal_Network_for_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.12255.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#minade">minADE</a></li>
<li><a href="../metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics.md#dac">DAC</a></li>
<li><a href="../metrics.md#wsfde">WSFDE</a></li>
<li><a href="../metrics.md#wsade">WSADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Fang_2020_CVPR,
    author = "Fang, Liangji and Jiang, Qinhong and Shi, Jianping and Zhou, Bolei",
    title = "TPNet: Trajectory Proposal Network for Motion Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chang et al., "Argoverse: 3D Tracking And Forecasting With Rich Maps", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_Argoverse_3D_Tracking_and_Forecasting_With_Rich_Maps_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.02620.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#minade">minADE</a></li>
<li><a href="../metrics.md#minfde">minFDE</a></li>
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
<a name=eifp></a>
<details close>
<summary><l style="font-size:20px"><strong>Edinburgh Informatics Forum Pedestrian (EIFP)</strong></l> <a href=http://homepages.inf.ed.ac.uk/rbf/FORUMTRACKING/>link</a> <a href=https://homepages.inf.ed.ac.uk/rbf/FORUMTRACKING/IM090734.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 92K+ trajectories recorded with a top-down view camera capturing people walking inside a campus area for a period of several month
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, Tracking ID</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Carvalho et al., "Long-Term Prediction Of Motion Trajectories Using Path Homology Clusters", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8968125>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#eifp">EIFP</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ed">ED</a></li>
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
<li><a href="../datasets/year_datasets.md#eifp">EIFP</a></li>
<li><a href="../datasets/year_datasets.md#lankershim_boulevard">Lankershim Boulevard</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<a name=interaction></a>
<details close>
<summary><l style="font-size:20px"><strong>INTERACTION</strong></l> <a href=https://interaction-dataset.com>link</a> <a href=https://arxiv.org/pdf/1910.03088.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A naturalistic dataset of motions of various traffic road users in a variety of interactive driving scenarios for behavior modeling and prediction
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Map, trajectory</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Li et al., "Conditional Generative Neural System For Probabilistic Trajectory Prediction", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8967822>paper</a> <a href=https://arxiv.org/pdf/1905.01631.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
<li><a href="../datasets/year_datasets.md#interaction">INTERACTION</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<a name=pems-sf></a>
<details close>
<summary><l style="font-size:20px"><strong>PEMS-SF</strong></l> <a href=https://archive.ics.uci.edu/ml/datasets/PEMS-SF#:~:text=UCI%20Machine%20Learning%20Repository%3A%20PEMS%2DSF%20Data%20Set&text=Abstract%3A%2015%20months%20worth%20of,bay%20area%20freeways%20across%20time.>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset with over 15 months of lane occupancy rate (0 to 1) information for select freeways in California
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Lane Occupancy Rate</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Qi et al., "Imitative Non-Autoregressive Modeling for Trajectory Forecasting and Imputation", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Qi_Imitative_Non-Autoregressive_Modeling_for_Trajectory_Forecasting_and_Imputation_CVPR_2020_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#btd">BTD</a></li>
<li><a href="../datasets/year_datasets.md#pems-sf">PEMS-SF</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ed">ED</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Misc{Dua_2019,
    author = "Dua, Dheeru and Graff, Casey",
    year = "2017",
    title = "UCI Machine Learning Repository",
    url = "http://archive.ics.uci.edu/ml",
    institution = "University of California, Irvine, School of Information and Computer Sciences"
}
</pre>
</details>

</ul></details>
<a name=titan></a>
<details close>
<summary><l style="font-size:20px"><strong>TITAN</strong></l> <a href=https://usa.honda-ri.com/titan>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Malla_TITAN_Future_Forecast_Using_Action_Priors_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.13886.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 700 front-view video clips of driving for pedestrian action and trajectory prediction annotated at 10hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Bounding Box, Attibute, Object Class, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Malla et al., "TITAN: Future Forecast Using Action Priors", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Malla_TITAN_Future_Forecast_Using_Action_Priors_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.13886.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#titan">TITAN</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#rmse">RMSE</a></li>
<li><a href="../metrics.md#fiou">FIoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Malla_2020_CVPR,
    author = "Malla, Srikanth and Dariush, Behzad and Choi, Chiho",
    title = "TITAN: Future Forecast Using Action Priors",
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
@InProceedings{Malla_2020_CVPR,
    author = "Malla, Srikanth and Dariush, Behzad and Choi, Chiho",
    title = "TITAN: Future Forecast Using Action Priors",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul></details>
<a name=multiverse></a>
<details close>
<summary><l style="font-size:20px"><strong>Multiverse</strong></l> <a href=https://github.com/JunweiLiang/Multiverse>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Liang_The_Garden_of_Forking_Paths_Towards_Multi-Future_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.06445.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 3K simulated videos of pedestrian trajectory samples from 4 different camera views. Each sample comes with multiple human-annotated possible trajectories.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Bounding Box, Semantic Segment, Tracking ID</li>
<li><em><strong>Task:</strong></em> Surveillance (simulation)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liang et al., "The Garden of Forking Paths: Towards Multi-Future Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Liang_The_Garden_of_Forking_Paths_Towards_Multi-Future_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.06445.pdf>arxiv</a> <a href=https://github.com/JunweiLiang/Multiverse>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#virat/actev">VIRAT/ActEV</a></li>
<li><a href="../datasets/year_datasets.md#multiverse">Multiverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#minade">minADE</a></li>
<li><a href="../metrics.md#minfde">minFDE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Liang_2020_CVPR_2,
    author = "Liang, Junwei and Jiang, Lu and Murphy, Kevin and Yu, Ting and Hauptmann, Alexander",
    title = "The Garden of Forking Paths: Towards Multi-Future Trajectory Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul></details>
<a name=citywalks></a>
<details close>
<summary><l style="font-size:20px"><strong>Citywalks</strong></l> <a href=https://github.com/olly-styles/Multiple-Object-Forecasting>link</a> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Styles_Multiple_Object_Forecasting_Predicting_Future_Object_Locations_in_Diverse_Environments_WACV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1909.11944.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 500+ front-view sequences of pedestrian trajectories annotated at 30fps
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Bounding Box, Attribute, Tracking ID</li>
<li><em><strong>Task:</strong></em> Walking</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Styles et al., "Multiple Object Forecasting: Predicting Future Object Locations in Diverse Environments", WACV, 2020.</em> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Styles_Multiple_Object_Forecasting_Predicting_Future_Object_Locations_in_Diverse_Environments_WACV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1909.11944.pdf>arxiv</a> <a href=https://github.com/olly-styles/Multiple-Object-Forecasting>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#citywalks">Citywalks</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Styles_2020_WACV,
    author = "Styles, Oliver and Sanchez, Victor and Guha, Tanaya",
    title = "Multiple Object Forecasting: Predicting Future Object Locations in Diverse Environments",
    booktitle = "WACV",
    year = "2020"
}
</pre>
</details>

</ul></details>
<a name=traf></a>
<details close>
<summary><l style="font-size:20px"><strong>TRAF</strong></l> <a href=https://drive.google.com/drive/folders/1LqzJuRkx5yhOcjWFORO5WZ97v6jg8RHN>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Chandra_TraPHic_Trajectory_Prediction_in_Dense_and_Heterogeneous_Traffic_Using_Weighted_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.04767.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 50 driving sequences with mix front and top-down view clips annotated at 30fps
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, object class, time-of-day, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chandra et al., "Traphic: Trajectory Prediction In Dense And Heterogeneous Traffic Using Weighted Interactions", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Chandra_TraPHic_Trajectory_Prediction_in_Dense_and_Heterogeneous_Traffic_Using_Weighted_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.04767.pdf>arxiv</a> <a href=https://go.umd.edu/TraPHic>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#traf">TRAF</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<a name=fit></a>
<details close>
<summary><l style="font-size:20px"><strong>Freiburg Imra Testing (FIT)</strong></l> <a href=https://lmb.informatik.uni-freiburg.de/resources/software.php>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Makansi_Multimodal_Future_Localization_and_Emergence_Prediction_for_Objects_in_Egocentric_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.04700.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A small-scale driving dataset with automatically generated bounding box track annotations
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Bounding Box, Object Class, Semantic Segment</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Makansi et al., "Multimodal Future Localization and Emergence Prediction for Objects in Egocentric View With a Reachability Prior", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Makansi_Multimodal_Future_Localization_and_Emergence_Prediction_for_Objects_in_Egocentric_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.04700.pdf>arxiv</a> <a href=https://github.com/lmb-freiburg/FLN-EPN-RPN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/year_datasets.md#fit">FIT</a></li>
<li><a href="../datasets/year_datasets.md#mapillary_vistas">Mapillary Vistas</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#nll">NLL</a></li>
<li><a href="../metrics.md#iou">IoU</a></li>
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
@InProceedings{Makansi_2020_CVPR,
    author = "Makansi, Osama and Cicek, Ozgun and Buchicchio, Kevin and Brox, Thomas",
    title = "Multimodal Future Localization and Emergence Prediction for Objects in Egocentric View With a Reachability Prior",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul></details>
<a name=apolloscape></a>
<details close>
<summary><l style="font-size:20px"><strong>ApolloScape</strong></l> <a href=http://apolloscape.auto/>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/8753527>paper</a> <a href=https://arxiv.org/pdf/1803.06184.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A driving dataset of 5K vehicle instances, 110K lane segments and 100 mins of sequences for trajectory prediction and tracking annotated at 2hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, LIDAR, 3D Bounding Box, Object Class, Semantic Segment, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Fang et al., "TPNet: Trajectory Proposal Network for Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Fang_TPNet_Trajectory_Proposal_Network_for_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.12255.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#minade">minADE</a></li>
<li><a href="../metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics.md#dac">DAC</a></li>
<li><a href="../metrics.md#wsfde">WSFDE</a></li>
<li><a href="../metrics.md#wsade">WSADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Fang_2020_CVPR,
    author = "Fang, Liangji and Jiang, Qinhong and Shi, Jianping and Zhou, Bolei",
    title = "TPNet: Trajectory Proposal Network for Motion Prediction",
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
@article{Wang_2019_PAMI,
    author = "Wang, Peng and Huang, Xinyu and Cheng, Xinjing and Zhou, Dingfu and Geng, Qichuan and Yang, Ruigang",
    title = "The Apolloscape Open Dataset for Autonomous Driving and its Application",
    journal = "PAMI",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=fm></a>
<details close>
<summary><l style="font-size:20px"><strong>Future Motion (FM)</strong></l> <a href=https://mcl.korea.ac.kr/~krkim/iccv2019/index.html>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Kim_Instance-Level_Future_Motion_Estimation_in_a_Single_Image_Based_on_ICCV_2019_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of instance-level motions in still images containing 11K+ pedestrian instances along with quantized motion directions and auto-generated bounding boxes
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB (image), bounding box, activity label, motion direction, speed</li>
<li><em><strong>Task:</strong></em> Mix</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kim et al., "Instance-Level Future Motion Estimation In A Single Image Based On Ordinal Regression", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Kim_Instance-Level_Future_Motion_Estimation_in_a_Single_Image_Based_on_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#fm">FM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=strands></a>
<details close>
<summary><l style="font-size:20px"><strong>STRANDS</strong></l> <a href=https://strands.readthedocs.io/en/latest/datasets/>link</a> <a href=https://ieeexplore.ieee.org/document/7948740>paper</a> <a href=https://arxiv.org/pdf/1604.04384.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An RGBD dataset of objects with corresponding 3D bounding boxes collected using a mobile robot
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D bounding box</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sun et al., "3Dof Pedestrian Trajectory Prediction Learned From Long-Term Autonomous Mobile Robot Deployment Data", ICRA, 2018.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8461228>paper</a> <a href=https://arxiv.org/pdf/1710.00126.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#strands">STRANDS</a></li>
<li><a href="../datasets/year_datasets.md#l-cas">L-CAS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#aede">AEDE</a></li>
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
<a name=mapillary_vistas></a>
<details close>
<summary><l style="font-size:20px"><strong>Mapillary Vistas</strong></l> <a href=https://www.mapillary.com/dataset/vistas?lat=-12.95419285181812&lng=-39.89899730092117&z=0.6853800234619407&pKey=H1P0sKnFsYu1MkfcjGUZTg>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Neuhold_The_Mapillary_Vistas_ICCV_2017_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of street-level images with the corresponding instance and semantic segmentation
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Bounding Box, Semantic Segment</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Makansi et al., "Multimodal Future Localization and Emergence Prediction for Objects in Egocentric View With a Reachability Prior", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Makansi_Multimodal_Future_Localization_and_Emergence_Prediction_for_Objects_in_Egocentric_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.04700.pdf>arxiv</a> <a href=https://github.com/lmb-freiburg/FLN-EPN-RPN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/year_datasets.md#fit">FIT</a></li>
<li><a href="../datasets/year_datasets.md#mapillary_vistas">Mapillary Vistas</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#fde">FDE</a></li>
<li><a href="../metrics.md#nll">NLL</a></li>
<li><a href="../metrics.md#iou">IoU</a></li>
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
<a name=cityperson></a>
<details close>
<summary><l style="font-size:20px"><strong>CityPersons</strong></l> <a href=https://bitbucket.org/shanshanzhang/citypersons/src/default/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_CityPersons_A_Diverse_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1702.05693.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A subset of Cityscapes dataset with fine-grained annotations for pedestrians and vehicles in additional 20K images with a total of 35K+ bounding boxes for pedestrians
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, bounding box, semantic segment</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Bhattacharyya et al., "Long-Term On-Board Prediction Of People In Traffic Scenes Under Uncertainty", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Bhattacharyya_Long-Term_On-Board_Prediction_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1711.09026.pdf>arxiv</a> <a href=https://github.com/apratimbhattacharyya18/onboard_long_term_prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#cityperson">CityPerson</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#nll">NLL</a></li>
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
<a name=l-cas></a>
<details close>
<summary><l style="font-size:20px"><strong>L-CAS</strong></l> <a href=https://lcas.lincoln.ac.uk/wp/research/data-sets-software/l-cas-3d-point-cloud-people-dataset/>link</a> <a href=https://ieeexplore.ieee.org/document/8202247>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 28K indoor LIDAR scans showing the surroundings of a mobile robot in stationary or moving states
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> LIDAR, 3D bounding box, attribute</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sun et al., "3Dof Pedestrian Trajectory Prediction Learned From Long-Term Autonomous Mobile Robot Deployment Data", ICRA, 2018.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8461228>paper</a> <a href=https://arxiv.org/pdf/1710.00126.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#strands">STRANDS</a></li>
<li><a href="../datasets/year_datasets.md#l-cas">L-CAS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#aede">AEDE</a></li>
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
<a name=mot></a>
<details close>
<summary><l style="font-size:20px"><strong>MOT</strong></l> <a href=https://motchallenge.net/>link</a> <a href=https://arxiv.org/pdf/1504.01942.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A collection of videos from existing datasets for the purpose of object tracking
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sanchez-Matilla et al., "A Predictor Of Moving Objects For First-Person Vision", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8803140>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#mot">MOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
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
<a name=atc></a>
<details close>
<summary><l style="font-size:20px"><strong>ATC</strong></l> <a href=https://irc.atr.jp/crest2010_HRI/ATC_dataset/>link</a> <a href=https://ieeexplore.ieee.org/document/6636027>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of human tracks recorded in a shopping mall for a period of 92 days using 3D range sensors
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, trajectory, attribute, depth</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Rudenko et al., "Joint Long-Term Prediction Of Human Motion Using A Planning-Based Social Force Approach", ICRA, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8460527>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#atc">ATC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#run_time">Run Time</a></li>
<li><a href="../metrics.md#mhd">MHD</a></li>
<li><a href="../metrics.md#nlp">NLP</a></li>
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
<a name=sbuki></a>
<details close>
<summary><l style="font-size:20px"><strong>SBU Kinetic Interction (SBUKI)</strong></l> <a href=https://www3.cs.stonybrook.edu/~kyun/research/kinect_interaction/index.html>link</a> <a href=https://ieeexplore.ieee.org/document/6239234>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 8 dyadic human interactions, e.g. approaching, departing, pushing, kicking, recorded from 7 participants using a Kinect sensor comprising a total of approx. 300 interactions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yao et al., "Multiple Granularity Group Interaction Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0721.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#sbuki">SBUKI</a></li>
<li><a href="../datasets/year_datasets.md#ca">CA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=ca></a>
<details close>
<summary><l style="font-size:20px"><strong>Collective Activity (CA)</strong></l> <a href=http://www-personal.umich.edu/~wgchoi/eccv12/wongun_eccv12.html>link</a> <a href=https://ieeexplore.ieee.org/document/5457461>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 40+ video clips showing collective activities including  crossing, waiting, queueing, walking and talking
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, attribute, activity label, temporal segment, pose</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yao et al., "Multiple Granularity Group Interaction Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0721.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#sbuki">SBUKI</a></li>
<li><a href="../datasets/year_datasets.md#ca">CA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=osu></a>
<details close>
<summary><l style="font-size:20px"><strong>OSU</strong></l> <a href=http://eecs.oregonstate.edu/football/tracking/dataset>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/5206801>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 20 videos, each with approx. 400 frames, of different football matches
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, attribute, Tracking ID</li>
<li><em><strong>Task:</strong></em> Sport</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Lee et al., "Predicting Wide Receiver Trajectories In American Football", WACV, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7477732>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#osu">OSU</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#nll">NLL</a></li>
<li><a href="../metrics.md#kld">KLD</a></li>
<li><a href="../metrics.md#mhd">MHD</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
<li><a href="../metrics.md#dtg">DtG</a></li>
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
<a name=pets2009></a>
<details close>
<summary><l style="font-size:20px"><strong>PETS2009</strong></l> <a href=http://www.cvg.reading.ac.uk/PETS2009/a.html>link</a> <a href=https://ieeexplore.ieee.org/document/5399556>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of crowd activities, e.g. walking, running, evacuation (rapid dispersion), local dispersion, recorded from multiple views (up to 8) with different crows densities
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Xue et al., "Location-Velocity Attention For Pedestrian Trajectory Prediction", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8659060>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
<li><a href="../datasets/year_datasets.md#pets2009">PETS2009</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<a name=qmul></a>
<details close>
<summary><l style="font-size:20px"><strong>QMUL</strong></l> <a href=http://personal.ie.cuhk.edu.hk/~ccloy/downloads_qmul_junction.html>link</a> <a href=http://www.bmva.org/bmvc/2009/Papers/Paper077/Paper077.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of surveillance footage of road traffic  with 90K+ frames recorded at 25hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, trajectory</li>
<li><em><strong>Task:</strong></em> Driving, Anomaly</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yoo et al., "Visual Path Prediction In Complex Scenes With Crowded Moving Objects", CVPR, 2016.</em> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Yoo_Visual_Path_Prediction_CVPR_2016_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#gc">GC</a></li>
<li><a href="../datasets/year_datasets.md#qmul">QMUL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
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
<a name=tum_kitchen></a>
<details close>
<summary><l style="font-size:20px"><strong>TUM Kitchen</strong></l> <a href=https://ias.in.tum.de/dokuwiki/software/kitchen-activity-data>link</a> <a href=https://ieeexplore.ieee.org/document/5457583>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of multiview video and multimodal sensor recordings of common activities in a kitchen environment containing 20 sequences
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, RFID, 3D pose, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Vo et al., "Augmenting Physical State Prediction Through Structured Activity Inference", ICRA, 2015.</em> <a href=https://ieeexplore.ieee.org/document/7139262>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#tum_kitchen">TUM Kitchen</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ed">ED</a></li>
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
<a name=mitt></a>
<details close>
<summary><l style="font-size:20px"><strong>MIT Trajectory (MITT)</strong></l> <a href=http://www.ee.cuhk.edu.hk/~xgwang/MITtrajsingle.html>link</a> <a href=https://ieeexplore.ieee.org/document/4587718>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 40K+ trajectories recorded from a parking lot for five days
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, trajectory</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Akbarzadeh et al., "Kernel Density Estimation For Target Trajectory Prediction", IROS, 2015.</em> <a href=https://ieeexplore.ieee.org/document/7353858>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#gc">GC</a></li>
<li><a href="../datasets/year_datasets.md#mitt">MITT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ed">ED</a></li>
<li><a href="../metrics.md#run_time">Run Time</a></li>
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
<a name=lankershim_boulevard></a>
<details close>
<summary><l style="font-size:20px"><strong>Lankershim Boulevard</strong></l> <a href=https://www.fhwa.dot.gov/publications/research/operations/07029/index.cfm>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of vehicle trajectories containing 30 minutes of data recorded at Lankershim Boulevard
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, trajectory</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhi et al., "Kernel Trajectory Maps For Multi-Modal Probabilistic Motion Prediction", CoRL, 2019.</em> <a href=http://proceedings.mlr.press/v100/zhi20a/zhi20a.pdf>paper</a> <a href=https://arxiv.org/pdf/1907.05127.pdf>arxiv</a> <a href=https://github.com/wzhi/KernelTrajectoryMaps>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#eifp">EIFP</a></li>
<li><a href="../datasets/year_datasets.md#lankershim_boulevard">Lankershim Boulevard</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<a name=lyft></a>
<details close>
<summary><l style="font-size:20px"><strong>Lyft</strong></l> <a href=https://self-driving.lyft.com/level5/data/>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A driving dataset with 1M+ 3D annotations for perception and 1K+ driving sequences for prediction annotated at 2hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, LIDAR, 3D Bounding Box, Object Class, Attribute, Map, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhang et al., "STINet: Spatio-Temporal-Interactive Network for Pedestrian Detection and Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_STINet_Spatio-Temporal-Interactive_Network_for_Pedestrian_Detection_and_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.04255.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/year_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#bev_ap">BEV AP</a></li>
<li><a href="../metrics.md#de">DE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2020_CVPR,
    author = "Zhang, Zhishuai and Gao, Jiyang and Mao, Junhua and Liu, Yukai and Anguelov, Dragomir and Li, Congcong",
    title = "STINet: Spatio-Temporal-Interactive Network for Pedestrian Detection and Trajectory Prediction",
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
@Misc{Lyft_2020,
    author = "Lyft",
    title = "Lyft Level 5 AV Dataset",
    howpublished = "https://self-driving.lyft.com/level5/data/",
    year = "2020"
}
</pre>
</details>

</ul></details>
</ul><a name=datasets_Motion></a>
<h2>Motion</h2> <a href=#top>&uarr; top</a>
<ul><a name=human3.6m></a>
<details close>
<summary><l style="font-size:20px"><strong>Human3.6M</strong></l> <a href=http://vision.imar.ro/human3.6m/description.php>link</a> <a href=https://ieeexplore.ieee.org/document/6682899>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale dataset of 3D human poses with 3M+ images captured using 11 professional actors in 17 scenarios, such as discussion, smoking, taking photo, etc.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Le et al., "Disentangling Physical Dynamics From Unknown Factors for Unsupervised Video Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Le_Guen_Disentangling_Physical_Dynamics_From_Unknown_Factors_for_Unsupervised_Video_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.01460.pdf>arxiv</a> <a href=https://github.com/vincent-leguen/PhyDNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#sst">SST</a></li>
<li><a href="../datasets/year_datasets.md#taxi_bj">Taxi BJ</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
<li><a href="../metrics.md#mae">MAE</a></li>
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
<summary><em>Xu et al., "Structure Preserving Video Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers_backup/Xu_Structure_Preserving_Video_CVPR_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#human">Human</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#human">Human</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<summary><em>Aliakbarian et al., "A Stochastic Conditioning Scheme for Diverse Human Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Aliakbarian_A_Stochastic_Conditioning_Scheme_for_Diverse_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://github.com/mix-and-match/mix-and-match-tutorial>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#kld">KLD</a></li>
<li><a href="../metrics.md#si">SI</a></li>
<li><a href="../metrics.md#kl">KL</a></li>
<li><a href="../metrics.md#s-mse">S-MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../datasets/year_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#mpjpe">MPJPE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2020_CVPR,
    author = "Li, Maosen and Chen, Siheng and Zhao, Yangheng and Zhang, Ya and Wang, Yanfeng and Tian, Qi",
    title = "Dynamic Multiscale Graph Neural Networks for 3D Skeleton Based Human Motion Prediction",
    booktitle = "CVPR",
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#npss">NPSS</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mouse_fish">Mouse Fish</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mje">MJE</a></li>
<li><a href="../metrics.md#run_time">Run Time</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#human">Human</a></li>
<li><a href="../metrics.md#pskl">PSKL</a></li>
<li><a href="../metrics.md#psent">PSEnt</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../datasets/year_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#mpjpe">MPJPE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#instavariety">InstaVariety</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#pck">PCK</a></li>
<li><a href="../metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../metrics.md#re">RE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mje">MJE</a></li>
<li><a href="../metrics.md#pck">PCK</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#human">Human</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#mpii_human_pose">MPII Human Pose</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#pck">PCK</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=ucf-101></a>
<details close>
<summary><l style="font-size:20px"><strong>UCF-101</strong></l> <a href=https://www.crcv.ucf.edu/data/UCF101.php>link</a> <a href=https://arxiv.org/pdf/1212.0402.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale dataset of 101 actions with 13K+ video clips divided into 5 groups of human-object interaction, body-motion only, human-human interaction, playing musical instruments, and sports
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle Gan", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#chuk_avenue">CHUK Avenue</a></li>
<li><a href="../datasets/year_datasets.md#shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#yuv">YUV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Liu et al., "Dyan: A Dynamical Atoms-Based Network For Video Prediction", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Wenqian_Liu_DYAN_A_Dynamical_ECCV_2018_paper.pdf>paper</a> <a href=https://github.com/liuem607/DYAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
<li><a href="../datasets/year_datasets.md#visor">ViSOR</a></li>
<li><a href="../datasets/year_datasets.md#prost">PROST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Liang et al., "Dual Motion Gan For Future-Flow Embedded Video Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Liang_Dual_Motion_GAN_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00284.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#is">IS</a></li>
<li><a href="../metrics.md#mmd">MMD</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
<li><a href="../datasets/year_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
<li><a href="../datasets/year_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#willow_action">Willow Action</a></li>
<li><a href="../datasets/year_datasets.md#wider">WIDER</a></li>
<li><a href="../datasets/year_datasets.md#stanford-40">Stanford-40</a></li>
<li><a href="../datasets/year_datasets.md#bu_action">BU Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#map">mAP</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#hmdb">HMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#bit">BIT</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<summary><em>Singh et al., "Online Real-Time Multiple Spatiotemporal Action Localisation And Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Singh_Online_Real-Time_Multiple_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1611.08563.pdf>arxiv</a> <a href=https://github.com/gurkirt/realtime-action-detection>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics.md#map">mAP</a></li>
<li><a href="../metrics.md#auc">AUC</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#uti">UTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=penn_action></a>
<details close>
<summary><l style="font-size:20px"><strong>Penn Action</strong></l> <a href=http://dreamdragon.github.io/PennAction/>link</a> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2013/papers/Zhang_From_Actemes_to_2013_ICCV_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 2.3K+ video clips of 15 actions with the corresponding human joint annotations
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ye et al., "Compositional Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ye_Compositional_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.08522.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#shapestack">ShapeStack</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
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
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#uva-nemo">UvA-NEMO</a></li>
<li><a href="../datasets/year_datasets.md#mgif">MGIF</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#fvd">FVD</a></li>
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
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#mug">MUG</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#is">IS</a></li>
<li><a href="../metrics.md#mmd">MMD</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#human">Human</a></li>
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
<summary><em>Zhang et al., "Predicting 3D Human Dynamics From Video", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Predicting_3D_Human_Dynamics_From_Video_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.04781.pdf>arxiv</a> <a href=https://github.com/jasonyzhang/phd>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#instavariety">InstaVariety</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#pck">PCK</a></li>
<li><a href="../metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../metrics.md#re">RE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mje">MJE</a></li>
<li><a href="../metrics.md#pck">PCK</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#mpii_human_pose">MPII Human Pose</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#pck">PCK</a></li>
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
<a name=cmu_mocap></a>
<details close>
<summary><l style="font-size:20px"><strong>CMU Mocap</strong></l> <a href=http://mocap.cs.cmu.edu/>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A motion dataset consists of various activities including human interaction, interaction with the environment, locomotion, sports, etc.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Butepage et al., "Deep Representation Learning For Human Motion Prediction And Classification", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Butepage_Deep_Representation_Learning_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1702.07486.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<summary><em>Aliakbarian et al., "A Stochastic Conditioning Scheme for Diverse Human Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Aliakbarian_A_Stochastic_Conditioning_Scheme_for_Diverse_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://github.com/mix-and-match/mix-and-match-tutorial>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#kld">KLD</a></li>
<li><a href="../metrics.md#si">SI</a></li>
<li><a href="../metrics.md#kl">KL</a></li>
<li><a href="../metrics.md#s-mse">S-MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../datasets/year_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#mpjpe">MPJPE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2020_CVPR,
    author = "Li, Maosen and Chen, Siheng and Zhao, Yangheng and Zhang, Ya and Wang, Yanfeng and Tian, Qi",
    title = "Dynamic Multiscale Graph Neural Networks for 3D Skeleton Based Human Motion Prediction",
    booktitle = "CVPR",
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../datasets/year_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#mpjpe">MPJPE</a></li>
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
<a name=3dpw></a>
<details close>
<summary><l style="font-size:20px"><strong>3D POSES IN THE WILD (3DPW)</strong></l> <a href=https://virtualhumans.mpi-inf.mpg.de/3DPW/>link</a> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Timo_von_Marcard_Recovering_Accurate_3D_ECCV_2018_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 60 video sequences with 2D poses and 3D body models
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, 2D/3D pose, models</li>
<li><em><strong>Task:</strong></em> Outdoor</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Cui et al., "Learning Dynamic Relationships for 3D Human Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Cui_Learning_Dynamic_Relationships_for_3D_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://github.com/cuiqiongjie/LDRGCN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../datasets/year_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#mpjpe">MPJPE</a></li>
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
<summary><em>Mao et al., "Learning Trajectory Dependencies For Human Motion Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Mao_Learning_Trajectory_Dependencies_for_Human_Motion_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.05436.pdf>arxiv</a> <a href=https://github.com/wei-mao-2019/LearnTrajDep>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../datasets/year_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
<li><a href="../metrics.md#mpjpe">MPJPE</a></li>
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
<a name=ca></a>
<details close>
<summary><l style="font-size:20px"><strong>Collective Activity (CA)</strong></l> <a href=http://www-personal.umich.edu/~wgchoi/eccv12/wongun_eccv12.html>link</a> <a href=https://ieeexplore.ieee.org/document/5457461>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 40+ video clips showing collective activities including  crossing, waiting, queueing, walking and talking
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, attribute, activity label, temporal segment, pose</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yao et al., "Multiple Granularity Group Interaction Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0721.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#sbuki">SBUKI</a></li>
<li><a href="../datasets/year_datasets.md#ca">CA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=sbuki></a>
<details close>
<summary><l style="font-size:20px"><strong>SBU Kinetic Interction (SBUKI)</strong></l> <a href=https://www3.cs.stonybrook.edu/~kyun/research/kinect_interaction/index.html>link</a> <a href=https://ieeexplore.ieee.org/document/6239234>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 8 dyadic human interactions, e.g. approaching, departing, pushing, kicking, recorded from 7 participants using a Kinect sensor comprising a total of approx. 300 interactions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yao et al., "Multiple Granularity Group Interaction Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0721.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#sbuki">SBUKI</a></li>
<li><a href="../datasets/year_datasets.md#ca">CA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=mpii_human_pose></a>
<details close>
<summary><l style="font-size:20px"><strong>MPII Human Pose</strong></l> <a href=http://human-pose.mpi-inf.mpg.de/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2014/papers/Andriluka_2D_Human_Pose_2014_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A pose detection dataset with 25K images containing 40K subjects performing 410 different activities
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chao et al., "Forecasting Human Dynamics From Static Images", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Chao_Forecasting_Human_Dynamics_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1704.03432.pdf>arxiv</a> <a href=https://github.com/ywchao/image-play>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#mpii_human_pose">MPII Human Pose</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#pck">PCK</a></li>
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
<a name=cmu_panoptic></a>
<details close>
<summary><l style="font-size:20px"><strong>CMU Panoptic</strong></l> <a href=http://domedb.perception.cs.cmu.edu/index.html>link</a> <a href=https://openaccess.thecvf.com/content_iccv_2015/papers/Joo_Panoptic_Studio_A_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1612.03153.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A multiview group activity dataset recorded with 10 RGB-D sensors and 30+ HD views with the corresponding 3D annotations
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, multiview, 3D pose, 3D facial landmark, Transcripts</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Joo et al., "Towards Social Artificial Intelligence: Nonverbal Social Signal Prediction In A Triadic Interaction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Joo_Towards_Social_Artificial_Intelligence_Nonverbal_Social_Signal_Prediction_in_a_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.04158.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=wbhm></a>
<details close>
<summary><l style="font-size:20px"><strong>Whole-Body Human Motion (WBHM)</strong></l> <a href=https://motion-database.humanoids.kit.edu/>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/7251476>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A human motion dataset consists of 2.4K+ experiments using 224 subjects and 135 objects
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, 3D Pose</li>
<li><em><strong>Task:</strong></em> Pose</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Corona et al., "Context-Aware Human Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Corona_Context-Aware_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.03419.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#wbhm">WBHM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mane">MAnE</a></li>
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
    title = "The KIT whole-body human motion database",
    booktitle = "ICAR",
    year = "2015"
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
<em><strong>Applications:</strong></em> <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Depth, 3D pose</li>
<li><em><strong>Task:</strong></em> Animal</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liu et al., "Towards Natural And Accurate Future Motion Prediction Of Humans And Animals", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Liu_Towards_Natural_and_Accurate_Future_Motion_Prediction_of_Humans_and_CVPR_2019_paper.pdf>paper</a> <a href=https://github.com/BII-wushuang/Lie-Group-Motion-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mouse_fish">Mouse Fish</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mje">MJE</a></li>
<li><a href="../metrics.md#run_time">Run Time</a></li>
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
<a name=instavariety></a>
<details close>
<summary><l style="font-size:20px"><strong>InstaVariety</strong></l> <a href=https://github.com/akanazawa/human_dynamics>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kanazawa_Learning_3D_Human_Dynamics_From_Video_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.01601.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset with 28 hours of video footage and corresponding auto-generated 2D poses
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Bounding Box, Pose</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhang et al., "Predicting 3D Human Dynamics From Video", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Predicting_3D_Human_Dynamics_From_Video_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.04781.pdf>arxiv</a> <a href=https://github.com/jasonyzhang/phd>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#instavariety">InstaVariety</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#pck">PCK</a></li>
<li><a href="../metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../metrics.md#re">RE</a></li>
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
<a name=egopose></a>
<details close>
<summary><l style="font-size:20px"><strong>EgoPose</strong></l> <a href=https://github.com/Khrylx/EgoPose>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Yuan_Ego-Pose_Estimation_and_Forecasting_As_Real-Time_PD_Control_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.03173.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of walking human video clips from the front and egocentric views with the corresponding 3D poses
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, 3D pose</li>
<li><em><strong>Task:</strong></em> Pose (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yuan et al., "Ego-Pose Estimation And Forecasting As Real-Time Pd Control", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Yuan_Ego-Pose_Estimation_and_Forecasting_As_Real-Time_PD_Control_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.03173.pdf>arxiv</a> <a href=https://github.com/Khrylx/EgoPose>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#egopose">EgoPose</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mje">MJE</a></li>
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
</ul><a name=datasets_Other></a>
<h2>Other</h2> <a href=#top>&uarr; top</a>
<ul><a name=kitti></a>
<details close>
<summary><l style="font-size:20px"><strong>KITTI</strong></l> <a href=http://www.cvlibs.net/datasets/kitti/>link</a> <a href=https://ieeexplore.ieee.org/document/6248074>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale driving dataset recorded with different modalities including stereo, LIDAR, GPS, etc. recorded at 10hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, LIDAR, bounding box, optical flow, vehicle sensors, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Jin et al., "Exploring Spatial-Temporal Multi-Frequency Analysis for High-Fidelity and Temporal-Consistency Video Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Jin_Exploring_Spatial-Temporal_Multi-Frequency_Analysis_for_High-Fidelity_and_Temporal-Consistency_Video_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2002.09905.pdf>arxiv</a> <a href=https://github.com/Bei-Jin/STMFANet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="../datasets/year_datasets.md#bair">BAIR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics.md#fvd">FVD</a></li>
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
<summary><em>Wu et al., "Future Video Synthesis With Object Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Wu_Future_Video_Synthesis_With_Object_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.00542.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics.md#ms-ssim">MS-SSIM</a></li>
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
<summary><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle Gan", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#chuk_avenue">CHUK Avenue</a></li>
<li><a href="../datasets/year_datasets.md#shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#yuv">YUV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Liu et al., "Dyan: A Dynamical Atoms-Based Network For Video Prediction", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Wenqian_Liu_DYAN_A_Dynamical_ECCV_2018_paper.pdf>paper</a> <a href=https://github.com/liuem607/DYAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Liang et al., "Dual Motion Gan For Future-Flow Embedded Video Prediction", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Liang_Dual_Motion_GAN_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.00284.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Marchetti et al., "MANTRA: Memory Augmented Networks for Multiple Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Marchetti_MANTRA_Memory_Augmented_Networks_for_Multiple_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.03340.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#orc">ORC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Marchetti_2020_CVPR,
    author = "Marchetti, Francesco and Becattini, Federico and Seidenari, Lorenzo and Del Bimbo, Alberto",
    title = "MANTRA: Memory Augmented Networks for Multiple Trajectory Prediction",
    booktitle = "CVPR",
    year = "2020"
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#oxford">Oxford</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#meanmsd">meanMSD</a></li>
<li><a href="../metrics.md#minmsd">minMSD</a></li>
<li><a href="../metrics.md#ce">CE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ed">ED</a></li>
<li><a href="../metrics.md#mined">minED</a></li>
<li><a href="../metrics.md#maxd">maxD</a></li>
<li><a href="../metrics.md#miss_rate">Miss rate</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#run_time">Run Time</a></li>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#tp">TP</a></li>
<li><a href="../metrics.md#tn">TN</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#f1">F1</a></li>
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
<a name=cityscapes></a>
<details close>
<summary><l style="font-size:20px"><strong>Cityscapes</strong></l> <a href=https://www.cityscapes-dataset.com/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Cordts_The_Cityscapes_Dataset_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1604.01685.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A driving dataset of street images with annotations for 30 traffic objects in 5k frames and weak annotations in 20k frames
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, bounding box, semantic segment, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Wu et al., "Future Video Synthesis With Object Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Wu_Future_Video_Synthesis_With_Object_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.00542.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics.md#ms-ssim">MS-SSIM</a></li>
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
<summary><em>Castrejon et al., "Improved Conditional Vrnns For Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Castrejon_Improved_Conditional_VRNNs_for_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.12165.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics.md#fvd">FVD</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<summary><em>Saric et al., "Warp to the Future: Joint Forecasting of Features and Feature Motion", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Saric_Warp_to_the_Future_Joint_Forecasting_of_Features_and_Feature_CVPR_2020_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#iou">IoU</a></li>
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
<summary><em>Srikanth et al., "Infer: Intermediate Representations For Future Prediction", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8968553>paper</a> <a href=https://arxiv.org/pdf/1903.10641.pdf>arxiv</a> <a href=https://rebrand.ly/INFER-results>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#oxford">Oxford</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
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
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#iou">IoU</a></li>
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
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#iou">IoU</a></li>
<li><a href="../metrics.md#voi">VoI</a></li>
<li><a href="../metrics.md#gce">GCE</a></li>
<li><a href="../metrics.md#ri">RI</a></li>
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
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#iou">IoU</a></li>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mse">MSE</a></li>
<li><a href="../metrics.md#miou">MIoU</a></li>
<li><a href="../metrics.md#epe">EPE</a></li>
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
<a name=jaad></a>
<details close>
<summary><l style="font-size:20px"><strong>Joint Attention in Autonomous Driving (JAAD)</strong></l> <a href=http://data.nvision2.eecs.yorku.ca/JAAD_dataset/>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w3/Rasouli_Are_They_Going_ICCV_2017_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of pedestrians with 346 video sequences showing pedestrians at the time of crossing in different geographical locations and under different weather conditions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a>, <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, attribute, temporal segment, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chaabane et al., "Looking Ahead: Anticipating Pedestrians Crossing with Future Frames Prediction", WACV, 2020.</em> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Chaabane_Looking_Ahead_Anticipating_Pedestrians_Crossing_with_Future_Frames_Prediction_WACV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.09077.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics.md#l1">L1</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#l1">L1</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ap">AP</a></li>
<li><a href="../metrics.md#run_time">Run Time</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#viena">VIENA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#map">mAP</a></li>
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
<summary><em>Mangalam et al., "Disentangling Human Dynamics for Pedestrian Locomotion Forecasting with Noisy Supervision", WACV, 2020.</em> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Mangalam_Disentangling_Human_Dynamics_for_Pedestrian_Locomotion_Forecasting_with_Noisy_Supervision_WACV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.01138.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#kde">KDE</a></li>
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
<summary><em>Rasouli et al., "Pie: A Large-Scale Dataset And Models For Pedestrian Intention Estimation And Trajectory Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.pdf>paper</a> <a href=https://github.com/aras62/PIEPredict>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#ade">ADE</a></li>
<li><a href="../metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#psi">Psi</a></li>
<li><a href="../metrics.md#ism">ISM</a></li>
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
<a name=golden_colorado></a>
<details close>
<summary><l style="font-size:20px"><strong>Golden Colorado</strong></l> <a href=https://www.osti.gov/dataexplorer/biblio/dataset/1052221>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of wide-angle images of the sky with the corresponding temperature recorded for 12 years at 1 frame every 10 minutes 300K+ images
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Weather</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Siddiqui et al., "A Deep Learning Approach To Solar-Irradiance Forecasting In Sky-Videos", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8659184>paper</a> <a href=https://arxiv.org/pdf/1901.04881.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#arizona">Arizona</a></li>
<li><a href="../datasets/year_datasets.md#tuscan">Tuscan</a></li>
<li><a href="../datasets/year_datasets.md#golden_colorado">Golden Colorado</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#nmape">nMAPE</a></li>
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
<a name=tuscan></a>
<details close>
<summary><l style="font-size:20px"><strong>Tuscan, Arizona</strong></l> <a href=http://www.mmto.org/>link</a> <a href=https://www.spiedigitallibrary.org/conference-proceedings-of-spie/6267/62671A/The-MMT-all-sky-camera/10.1117/12.672508.short?SSO=1>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of wide-angle images of the sky with the corresponding temperature recorded for 7 months at 10 frames per minute rate with a total of approx. 1M images
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Weather</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Siddiqui et al., "A Deep Learning Approach To Solar-Irradiance Forecasting In Sky-Videos", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8659184>paper</a> <a href=https://arxiv.org/pdf/1901.04881.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#arizona">Arizona</a></li>
<li><a href="../datasets/year_datasets.md#tuscan">Tuscan</a></li>
<li><a href="../datasets/year_datasets.md#golden_colorado">Golden Colorado</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#nmape">nMAPE</a></li>
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
<a name=amos></a>
<details close>
<summary><l style="font-size:20px"><strong>AMOS</strong></l> <a href=http://amos.cse.wustl.edu/>link</a> <a href=https://ieeexplore.ieee.org/document/4270283>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 17M+ images captured every half hour during a period of 6 months from 538 outdoor webcams across the US
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, time, camera coordinate</li>
<li><em><strong>Task:</strong></em> Weather</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chu et al., "Visual Weather Temperature Prediction", WACV, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8354136>paper</a> <a href=https://arxiv.org/pdf/1801.08267.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#amos">AMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#rmse">RMSE</a></li>
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
<a name=diplecs></a>
<details close>
<summary><l style="font-size:20px"><strong>DIPLECS</strong></l> <a href=https://cvssp.org/data/diplecs/>link</a> <a href=https://link.springer.com/content/pdf/10.1007%2F978-3-642-15567-3_12.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 3.5 hours of driving with the corresponding steering angle computed based on a marker on the steering wheel
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>He et al., "Aggregated Sparse Attention For Steering Angle Prediction", ICPR, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8546051>paper</a> <a href=https://arxiv.org/pdf/1803.05785.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#diplecs">DIPLECS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mae">MAE</a></li>
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
<a name=fcvl></a>
<details close>
<summary><l style="font-size:20px"><strong>Ford Campus Vision LiDAR (FCVL)</strong></l> <a href=http://robots.engin.umich.edu/SoftwareData/Ford>link</a> <a href=https://journals.sagepub.com/doi/pdf/10.1177/0278364911400640>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of LIDAR scans and IMU readings with the corresponding images collected using a Ford F-250 autonomous pickup truck with approx. 200 GB of data
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, LIDAR, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Choi et al., "Robust Modeling And Prediction In Dynamic Environments Using Recurrent Flow Networks", IROS, 2016.</em> <a href=https://ieeexplore.ieee.org/abstract/document/7759278>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#fcvl">FCVL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#run_time">Run Time</a></li>
<li><a href="../metrics.md#recall">Recall</a></li>
<li><a href="../metrics.md#precision">Precision</a></li>
<li><a href="../metrics.md#auc">AUC</a></li>
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
<a name=sun_rgb-d></a>
<details close>
<summary><l style="font-size:20px"><strong>SUN RGB-D</strong></l> <a href=http://rgbd.cs.princeton.edu/>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Song_SUN_RGB-D_A_2015_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 10K RGB-D images of indoor environments with the corresponding 2D and 3D annotations
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D bounding box, object class</li>
<li><em><strong>Task:</strong></em> Place</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Mottaghi et al., "What Happens If... Learning To Predict The Effect Of Forces In Images", ECCV, 2016.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46493-0_17>paper</a> <a href=https://arxiv.org/pdf/1603.05600.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#sun_rgb-d">SUN RGB-D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#pcp">PCP</a></li>
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
<a name=mbi-1m></a>
<details close>
<summary><l style="font-size:20px"><strong>MicroBlog-Images (MBI-1M)</strong></l> <a href=http://academic.mywebsiteontheinternet.com/data/>link</a> <a href=https://dl.acm.org/doi/abs/10.1145/2671188.2749405>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An activity dataset of 1M images and the content of the corresponding tweets collected in years 2013-14
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB (image), attribute, text</li>
<li><em><strong>Task:</strong></em> Tweet</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Wang et al., "Retweet Wars: Tweet Popularity Prediction Via Dynamic Multimodal Regression", WACV, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8354308>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#mbi-1m">MBI-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mape">MAPE</a></li>
<li><a href="../metrics.md#src">SRC</a></li>
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
<a name=amazon></a>
<details close>
<summary><l style="font-size:20px"><strong>Amazon</strong></l> <a href=http://jmcauley.ucsd.edu/data/amazon/index_2014.html>link</a> <a href=https://dl.acm.org/doi/abs/10.1145/2766462.2767755>paper</a> <a href=https://arxiv.org/pdf/1506.04757.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 142M+ product reviews from Amazon with corresponding metadata including price, brand, descriptions, category information, etc.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Features, attribute, text</li>
<li><em><strong>Task:</strong></em> Fashion</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Al-Halah et al., "Fashion Forward: Forecasting Visual Style In Fashion", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Al-Halah_Fashion_Forward_Forecasting_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.06394.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#amazon">Amazon</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#mae">MAE</a></li>
<li><a href="../metrics.md#mape">MAPE</a></li>
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
<a name=vist></a>
<details close>
<summary><l style="font-size:20px"><strong>Visual Storytelling (VIST)</strong></l> <a href=http://visionandlanguage.net/VIST/>link</a> <a href=https://www.aclweb.org/anthology/N16-1147.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 80K+ images collected from 21K+ sequences with corresponding text captions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, text</li>
<li><em><strong>Task:</strong></em> Visual story</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zeng et al., "Visual Forecasting By Imitating Dynamics In Natural Sequences", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Zeng_Visual_Forecasting_by_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1708.05827.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#vist">VIST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=mu></a>
<details close>
<summary><l style="font-size:20px"><strong>Miss Universe (MU)</strong></l> <a href=http://staff.itee.uq.edu.au/lovell/MissUniverse/>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/7899781>paper</a> <a href=https://arxiv.org/pdf/1604.07547.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of catwalks by Miss Universe contestants during the evening gown competition from 1996 to 2010
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, scores</li>
<li><em><strong>Task:</strong></em> Miss universe</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Carvajal et al., "Towards Miss Universe Automatic Prediction: The Evening Gown Competition", ICPR, 2016.</em> <a href=https://ieeexplore.ieee.org/abstract/document/7899781>paper</a> <a href=https://arxiv.org/pdf/1604.07547.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#mu">MU</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#accuracy">Accuracy</a></li>
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
<a name=facescape></a>
<details close>
<summary><l style="font-size:20px"><strong>FaceScape</strong></l> <a href=https://github.com/zhuhao-nju/facescape>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_FaceScape_A_Large-Scale_High_Quality_3D_Face_Dataset_and_Detailed_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.13989.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 900+ faces and corresponding multi-view 3D meshes
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, 3D Model, Landmarks</li>
<li><em><strong>Task:</strong></em> Face</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yang et al., "FaceScape: A Large-Scale High Quality 3D Face Dataset and Detailed Riggable 3D Face Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_FaceScape_A_Large-Scale_High_Quality_3D_Face_Dataset_and_Detailed_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.13989.pdf>arxiv</a> <a href=https://github.com/zhuhao-nju/facescape>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#facescape">FaceScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics.md#me">ME</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yang_2020_CVPR,
    author = "Yang, Haotian and Zhu, Hao and Wang, Yanru and Huang, Mingkai and Shen, Qiu and Yang, Ruigang and Cao, Xun",
    title = "FaceScape: A Large-Scale High Quality 3D Face Dataset and Detailed Riggable 3D Face Prediction",
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
@InProceedings{Yang_2020_CVPR,
    author = "Yang, Haotian and Zhu, Hao and Wang, Yanru and Huang, Mingkai and Shen, Qiu and Yang, Ruigang and Cao, Xun",
    title = "FaceScape: A Large-Scale High Quality 3D Face Dataset and Detailed Riggable 3D Face Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul></details>
</ul>