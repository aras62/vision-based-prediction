<a name=top></a>
<a name=top></a>
---
<a href=../../README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Datasets</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../metrics/metrics.md#top><l style="font-size:30px">Metrics</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
[Home](../datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Alphabetical](../alphabetical/alphabetical_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Year](../year/year_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Application&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Task](../task/task_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Annotation](../annotation_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[Video](video_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Action](action_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Trajectory](trajectory_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Motion](motion_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Other&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
<h2>Other Datasets</h2> 
<ul><a name=kitti></a>
<details close>
<summary><l style="font-size:20px"><strong>KITTI</strong></l> <a href=http://www.cvlibs.net/datasets/kitti/>link</a> <a href=https://ieeexplore.ieee.org/document/6248074>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale driving dataset recorded with different modalities including stereo, LIDAR, GPS, etc. recorded at 10hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a>, <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, LIDAR, bounding box, optical flow, vehicle sensors, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Dong et al., "MemFlow: Optical Flow Estimation and Prediction with Memory", CVPR, 2024.</em> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Dong_MemFlow_Optical_Flow_Estimation_and_Prediction_with_Memory_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2404.04808>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
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
<summary><em>Zhong et al., "Motion Graph Unleashed: A Novel Approach to Video Prediction", NeurIPS, 2024.</em> <a href=https://openreview.net/pdf?id=4ztP4PujOG>paper</a> <a href=https://arxiv.org/pdf/2410.22288>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf_sports">UCF Sports</a></li>
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
@inproceedings{Zhong_Motion_2024_NeurIPS,
    author = "Zhong, Yiqi and Liang, Luming and Tang, Bohan and Zharkov, Ilya and Neumann, Ulrich",
    title = "Motion Graph Unleashed: A Novel Approach to Video Prediction",
    booktitle = "NeurIPS",
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
<summary><em>Sun et al., "MOSO: Decomposing MOtion, Scene and Object for Video Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Sun_MOSO_Decomposing_MOtion_Scene_and_Object_for_Video_Prediction_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.03684.pdf>arxiv</a> <a href=https://github.com/iva-mzsun/MOSO>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#robonet">RoboNet</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#fid">FID</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2023_CVPR_1,
    author = "Sun, Mingzhen and Wang, Weining and Zhu, Xinxin and Liu, Jing",
    title = "MOSO: Decomposing MOtion, Scene and Object for Video Prediction",
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
<summary><em>Lange et al., "Attention Augmented ConvLSTM for Environment Prediction", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636386>paper</a> <a href=https://arxiv.org/pdf/2010.09662.pdf>arxiv</a> <a href=https://github.com/sisl/AttentionAugmentedConvLSTM>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/video/video_alphabetical/video_e-i_metrics.md#is">IS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lange_2021_IROS,
    author = "Lange, Bernard and Itkina, Masha and Kochenderfer, Mykel J.",
    booktitle = "IROS",
    title = "Attention Augmented {ConvLSTM} for Environment Prediction",
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
<summary><em>Kwon et al., "Predicting Future Frames Using Retrospective Cycle GAN", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Kwon_Predicting_Future_Frames_Using_Retrospective_Cycle_GAN_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cuhk_avenue">CUHK Avenue</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#shanghaitech_campus">ShanghaiTech Campus</a></li>
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
@InProceedings{Kwon_2019_CVPR,
    author = "Kwon, Yong-Hoon and Park, Min-Gyu",
    title = "Predicting Future Frames Using Retrospective Cycle {GAN}",
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#yuv">YUV</a></li>
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
<summary><em>Liu et al., "Dyan: A Dynamical Atoms-Based Network For Video Prediction", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Wenqian_Liu_DYAN_A_Dynamical_ECCV_2018_paper.pdf>paper</a> <a href=https://github.com/liuem607/DYAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
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
<summary><em>Bhattacharjee et al., "Predicting Video Frames Using Feature Based Locally Guided Objectives", ACCV, 2018.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20870-7_42>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
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
@InProceedings{Bhattacharjee_2018_ACCV,
    author = "Bhattacharjee, Prateep and Das, Sukhendu",
    editor = "Jawahar, C.V. and Li, Hongdong and Mori, Greg and Schindler, Konrad",
    title = "Predicting Video Frames Using Feature Based Locally Guided Objectives",
    booktitle = "ACCV",
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
<summary><em>Jin et al., "VarNet: Exploring Variations For Unsupervised Video Prediction", IROS, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8594264>paper</a> <a href=https://github.com/jinbeibei/VarNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
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
@InProceedings{Jin_2018_IROS,
    author = "Jin, B. and Hu, Y. and Zeng, Y. and Tang, Q. and Liu, S. and Ye, J.",
    booktitle = "IROS",
    title = "{VarNet}: Exploring Variations For Unsupervised Video Prediction",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
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
<summary><em>Filatov et al., "Any Motion Detector: Learning Class-agnostic Scene Dynamics from a Sequence of LiDAR Point Clouds", ICRA, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9196716>paper</a> <a href=https://arxiv.org/pdf/2004.11647.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/action_alphabetical/action_a-d_metrics.md#ap">AP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Filatov_2020_ICRA,
    author = "Filatov, A. and Rykov, A. and Murashkin, V.",
    booktitle = "ICRA",
    title = "Any Motion Detector: Learning Class-agnostic Scene Dynamics from a Sequence of {LiDAR} Point Clouds",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Weng et al., "Whose Track Is It Anyway? Improving Robustness to Tracking Errors With Affinity-Based Trajectory Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Weng_Whose_Track_Is_It_Anyway_Improving_Robustness_to_Tracking_Errors_CVPR_2022_paper.pdf>paper</a> <a href=https://www.xinshuoweng.com/projects/Affinipred/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Weng_2022_CVPR,
    author = "Weng, Xinshuo and Ivanovic, Boris and Kitani, Kris and Pavone, Marco",
    title = "Whose Track Is It Anyway? Improving Robustness to Tracking Errors With Affinity-Based Trajectory Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Choi et al., "Shared Cross-Modal Trajectory Prediction for Autonomous Driving", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Choi_Shared_Cross-Modal_Trajectory_Prediction_for_Autonomous_Driving_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2011.08436.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
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
@InProceedings{Choi_2021_CVPR,
    author = "Choi, Chiho and Choi, Joon Hee and Li, Jiachen and Malla, Srikanth",
    title = "Shared Cross-Modal Trajectory Prediction for Autonomous Driving",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Weng et al., "PTP: Parallelized Tracking and Prediction With Graph Neural Networks and Diversity Sampling", RAL, 2021.</em> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9387598&tag=1>paper</a> <a href=https://arxiv.org/pdf/2003.07847>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fsd">FSD</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#asd">ASD</a></li>
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
<summary><em>Weng et al., "Inverting the Pose Forecasting Pipeline with SPF2: Sequential Pointcloud Forecasting for Sequential Pose Forecasting", CoRL, 2021.</em> <a href=https://proceedings.mlr.press/v155/weng21a/weng21a.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.08376.pdf>arxiv</a> <a href=https://github.com/xinshuoweng/SPF2>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Sun et al., "See the Future: A Semantic Segmentation Network Predicting Ego-Vehicle Trajectory With a Single Monocular Camera", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9004469>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#accuracy">Accuracy</a></li>
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
<summary><em>Rhinehart et al., "R2P2: A Reparameterized Pushforward Policy For Diverse, Precise Generative Path Forecasting", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Nicholas_Rhinehart_R2P2_A_ReparameteRized_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minmsd">minMSD</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#meanmsd">meanMSD</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ce">CE</a></li>
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
<summary><em>Agro et al., "UnO: Unsupervised Occupancy Fields for Perception and Forecasting", CVPR, 2024.</em> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Agro_UnO_Unsupervised_Occupancy_Fields_for_Perception_and_Forecasting_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/abs/2406.08691>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#cd">CD</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#l1">L1</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#nfcd">NFCD</a></li>
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
<summary><em>Khurana et al., "Point Cloud Forecasting as a Proxy for 4D Occupancy Forecasting", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Khurana_Point_Cloud_Forecasting_as_a_Proxy_for_4D_Occupancy_Forecasting_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2302.13130.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#l1">L1</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#absrel">AbsRel</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#nfe">NFE</a></li>
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
<details close>
<summary><em>Li et al., "TTC4MCP: Monocular Collision Prediction Based on Self-Supervised TTC Estimation", IROS, 2023.</em> <a href=https://ieeexplore.ieee.org/document/10341966>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#time">time</a></li>
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
<summary><em>Luo et al., "PCPNet: An Efficient and Semantic-Enhanced Transformer Network for Point Cloud Prediction", RAL, 2023.</em> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10141631>paper</a> <a href=https://arxiv.org/pdf/2304.07773>arxiv</a> <a href=https://github.com/Blurryface0814/PCPNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#cd">CD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@ARTICLE{Luo_PCPNet_2023_RAL,
    author = "Luo, Zhen and Ma, Junyi and Zhou, Zijie and Xiong, Guangming",
    journal = "RAL",
    title = "PCPNet: An Efficient and Semantic-Enhanced Transformer Network for Point Cloud Prediction",
    year = "2023",
    volume = "8",
    number = "7",
    pages = "4267-4274"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Weng et al., "S2Net: Stochastic Sequential Pointcloud Forecasting", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136870541.pdf>paper</a> <a href=https://www.xinshuoweng.com/projects/S2Net>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#cd">CD</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#emd">EMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Weng_2022_ECCV,
    author = "Weng, Xinshuo and Nan, Junyu and Lee, Kuan-Hui and McAllister, Rowan and Gaidon, Adrien and Rhinehart, Nicholas and Kitani, Kris M.",
    title = "{S2Net}: Stochastic Sequential Pointcloud Forecasting",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Mersch et al., "Self-supervised Point Cloud Prediction Using 3D Spatio-temporal Convolutional Networks", CoRL, 2021.</em> <a href=https://openreview.net/pdf?id=JvXqtLtAtMY>paper</a> <a href=https://download.arxiv.org/pdf/2110.04076v2>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#cd">CD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mersch_2021_CoRL,
    author = "Mersch, Benedikt and Chen, Xieyuanli and Behley, Jens and Stachniss, Cyrill",
    title = "Self-supervised Point Cloud Prediction Using {3D} Spatio-temporal Convolutional Networks",
    booktitle = "CoRL",
    year = "2021"
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#run_time">Run Time</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#tp">TP</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#tn">TN</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
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
    title = "Are We Ready For Autonomous Driving? The {KITTI} Vision Benchmark Suite",
    booktitle = "CVPR",
    year = "2012"
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
<a name=sd></a>
<details close>
<summary><l style="font-size:20px"><strong>Solar Dynamics Observatory (SDO)</strong></l> <a href=https://sdo.gsfc.nasa.gov/data/>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of solar activity recordings
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Solar Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Almeida et al., "Trajectory Prediction for Heterogeneous Agents: A Performance Analysis on Small and Imbalanced Datasets", RAL, 2024.</em> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10545544>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#thor-magni">THOR-MAGNI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<summary><em>Lee et al., "MUSE-VAE: Multi-Scale VAE for Environment-Aware Long Term Trajectory Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Lee_MUSE-VAE_Multi-Scale_VAE_for_Environment-Aware_Long_Term_Trajectory_Prediction_CVPR_2022_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#nll">NLL</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#kde">KDE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#ecfl">ECFL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lee_2022_CVPR,
    author = "Lee, Mihee and Sohn, Samuel S. and Moon, Seonghyeon and Yoon, Sejong and Kapadia, Mubbasir and Pavlovic, Vladimir",
    title = "{MUSE-VAE}: Multi-Scale {VAE} for Environment-Aware Long Term Trajectory Prediction",
    booktitle = "CVPR",
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
<summary><em>Cao et al., "Spectral Temporal Graph Neural Network for Trajectory Prediction", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561461>paper</a> <a href=https://arxiv.org/pdf/2106.02930.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cao_2021_ICRA,
    author = "Cao, Defu and Li, Jiachen and Ma, Hengbo and Tomizuka, Masayoshi",
    booktitle = "ICRA",
    title = "Spectral Temporal Graph Neural Network for Trajectory Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Mangalam et al., "It Is Not the Journey but the Destination: Endpoint Conditioned Trajectory Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470749.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.02025.pdf>arxiv</a> <a href=https://github.com/HarshayuGirase/PECNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mangalam_2020_ECCV,
    author = "Mangalam, Karttikeya and Girase, Harshayu and Agarwal, Shreyas and Lee, Kuan-Hui and Adeli, Ehsan and Malik, Jitendra and Gaidon, Adrien",
    title = "It Is Not the Journey but the Destination: Endpoint Conditioned Trajectory Prediction",
    booktitle = "ECCV",
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_e-i_metrics.md#fde">FDE</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_j-z_metrics.md#minfde">minFDE</a></li>
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
<summary><em>Robicquet et al., "Learning Social Etiquette: Human Trajectory Understanding in Crowded Scenes", ECCV, 2016.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46484-8_33>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/trajectory_alphabetical/trajectory_a-d_metrics.md#ade">ADE</a></li>
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
<summary><em>Kaneda et al., "Flare Transformer: Solar Flare Prediction using Magnetograms and Sunspot Physical Features", ACCV, 2022.</em> <a href=https://openaccess.thecvf.com/content/ACCV2022/papers/Kaneda_Flare_Transformer_Solar_Flare_Prediction_using_Magnetograms_and_Sunspot_Physical_ACCV_2022_paper.pdf>paper</a> <a href=https://github.com/keio-smilab21/flare_transformer>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sdo">SDO</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#bss">BSS</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#tss">TSS</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#gmgs">GMGS</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Misc{SDO_2020,
    author = "Observatory, Solar Dynamics",
    Title = "The Sun Now",
    HowPublished = "Online",
    accessed = "2022-12-16",
    year = "2020"
}
</pre>
</details>

</ul></details>
<a name=mogaze></a>
<details close>
<summary><l style="font-size:20px"><strong>MoGaze</strong></l> <a href=https://humans-to-robots-motion.github.io/mogaze/>link</a> <a href=https://arxiv.org/pdf/2011.11552.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 180 minutes of motion and gaze of humans performing 1627 pick and place actions.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Pose, Gaze, Activity</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hu et al., "GazeMotion: Gaze-guided Human Motion Forecasting", IROS, 2024.</em> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10802548>paper</a> <a href=https://arxiv.org/pdf/2403.09885>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#gimo">GIMO</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mogaze">MoGaze</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#adt">ADT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_j-z_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@inproceedings{Hu_GazeMotion_2024_IROS,
    author = "Hu, Zhiming and Schmitt, Syn and Häufle, Daniel and Bulling, Andreas",
    booktitle = "IROS",
    title = "GazeMotion: Gaze-guided Human Motion Forecasting",
    year = "2024"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Razali et al., "Using Eye Gaze to Forecast Human Pose in Everyday Pick and Place Actions", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9812079>paper</a> <a href=https://github.com/HaziqRazali/Using-Eye-Gaze-to-Forecast-Human-Pose-in-Everyday-Pick-and-Place-Actions>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mogaze">MoGaze</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#l2">L2</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@article{Kratzer_2020_RAL,
    author = "Kratzer, Philipp and Bihlmaier, Simon and Balachandra Midlagajni, Niteesh and Prakash, Rohit and Toussaint, Marc and Mainprice, Jim",
    title = "{MoGaze}: A Dataset of Full-Body Motions that Includes Workspace Geometry and Eye-Gaze",
    journal = "RAL",
    year = "2020"
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
<a name=egopat3d></a>
<details close>
<summary><l style="font-size:20px"><strong>EgoPAT3D</strong></l> <a href=https://ai4ce.github.io/EgoPAT3D/>link</a> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Egocentric_Prediction_of_Action_Target_in_3D_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.13116.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 15 household scenes with 150 recordings with different object configurations.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, IR, IMU, Point Cloud, Action, Pose</li>
<li><em><strong>Task:</strong></em> Action</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Bao et al., "Uncertainty-aware State Space Transformer for Egocentric 3D Hand Trajectory Forecasting", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Bao_Uncertainty-aware_State_Space_Transformer_for_Egocentric_3D_Hand_Trajectory_Forecasting_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2307.08243.pdf>arxiv</a> <a href=https://actionlab-cv.github.io/EgoHandTrajPred/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egopat3d">EgoPAT3D</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#h2o">H2O</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bao_2023_ICCV,
    author = "Bao, Wentao and Chen, Lele and Zeng, Libing and Li, Zhong and Xu, Yi and Yuan, Junsong and Kong, Yu",
    title = "Uncertainty-aware State Space Transformer for Egocentric 3D Hand Trajectory Forecasting",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Li et al., "Egocentric Prediction of Action Target in 3D", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Egocentric_Prediction_of_Action_Target_in_3D_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.13116.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egopat3d">EgoPAT3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2022_CVPR_2,
    author = "Li, Yiming and Cao, Ziang and Liang, Andrew and Liang, Benjamin and Chen, Luoyao and Zhao, Hang and Feng, Chen",
    title = "Egocentric Prediction of Action Target in {3D}",
    booktitle = "CVPR",
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
@InProceedings{Li_2022_CVPR,
    author = "Li, Lihuan and Pagnucco, Maurice and Song, Yang",
    title = "Graph-Based Spatial Transformer With Memory Replay for Multi-Future Pedestrian Trajectory Prediction",
    booktitle = "CVPR",
    year = "2022"
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
<a name=facescape></a>
<details close>
<summary><l style="font-size:20px"><strong>FaceScape</strong></l> <a href=https://github.com/zhuhao-nju/facescape>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_FaceScape_A_Large-Scale_High_Quality_3D_Face_Dataset_and_Detailed_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.13989.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 900+ faces and corresponding multi-view 3D meshes
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, 3D Model, Landmarks</li>
<li><em><strong>Task:</strong></em> Face</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yang et al., "FaceScape: A Large-Scale High Quality 3D Face Dataset and Detailed Riggable 3D Face Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_FaceScape_A_Large-Scale_High_Quality_3D_Face_Dataset_and_Detailed_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.13989.pdf>arxiv</a> <a href=https://github.com/zhuhao-nju/facescape>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#facescape">FaceScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#me">ME</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Yang_2020_CVPR,
    author = "Yang, Haotian and Zhu, Hao and Wang, Yanru and Huang, Mingkai and Shen, Qiu and Yang, Ruigang and Cao, Xun",
    title = "{FaceScape}: A Large-Scale High Quality 3D Face Dataset and Detailed Riggable {3D} Face Prediction",
    booktitle = "CVPR",
    year = "2020"
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
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Weather</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Siddiqui et al., "A Deep Learning Approach To Solar-Irradiance Forecasting In Sky-Videos", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8659184>paper</a> <a href=https://arxiv.org/pdf/1901.04881.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#arizona">Arizona</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tuscan">Tuscan</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#golden_colorado">Golden Colorado</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#nmape">nMAPE</a></li>
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
    title = "{NREl} Solar Radiation Research Laboratory ({SRRL}): Baseline Measurement System ({BMS}); Golden, Colorado (Data)",
    year = "1981",
    institution = "National Renewable Energy Lab.(NREL)"
}
</pre>
</details>

</ul></details>
<a name=habitat></a>
<details close>
<summary><l style="font-size:20px"><strong>Habitat</strong></l> <a href=https://aihabitat.org/>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Savva_Habitat_A_Platform_for_Embodied_AI_Research_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.01201.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of photo realistic 3D indoor environments
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/motion/motion_papers.md#top>Motion prediction<application></a>, <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
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
@InProceedings{Savva_2019_ICCV,
    author = "Savva, Manolis and Kadian, Abhishek and Maksymets, Oleksandr and Zhao, Yili and Wijmans, Erik and Jain, Bhavana and Straub, Julian and Liu, Jia and Koltun, Vladlen and Malik, Jitendra and Parikh, Devi and Batra, Dhruv",
    title = "Habitat: A Platform for Embodied {AI} Research",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=drip></a>
<details close>
<summary><l style="font-size:20px"><strong>Deformable Rigid Interaction Prediction (DRIP)</strong></l> <a href=https://github.com/wengzehang/deformable_rigid_interaction_prediction>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/9636660>paper</a> <a href=https://arxiv.org/pdf/2103.02932.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of simulated deformable and rigid objects with associated graph representation.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Graph</li>
<li><em><strong>Task:</strong></em> Object (simulation)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Weng et al., "Graph-based Task-specific Prediction Models for Interactions between Deformable and Rigid Objects", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636660>paper</a> <a href=https://arxiv.org/pdf/2103.02932.pdf>arxiv</a> <a href=https://github.com/wengzehang/deformable_rigid_interaction_prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#drip">DRIP</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#mpe">MPE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Weng_2021_IROS,
    author = "Weng, Zehang and Paus, Fabian and Varava, Anastasiia and Yin, Hang and Asfour, Tamim and Kragic, Danica",
    booktitle = "IROS",
    title = "Graph-based Task-specific Prediction Models for Interactions between Deformable and Rigid Objects",
    year = "2021"
}
</pre>
</details>

</ul></details>
<a name=once></a>
<details close>
<summary><l style="font-size:20px"><strong>ONCE</strong></l> <a href=https://once-for-auto-driving.github.io/>link</a> <a href=https://arxiv.org/pdf/2106.11037.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of over 140 hours of driving with corresponding camera and LIDAR frames and 15K fully annotated scenes.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> LIDAR, 3D Bounding Box, Object Class</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Khurana et al., "Differentiable Raycasting for Self-Supervised Occupancy Forecasting", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136980349.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.01917.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#once">ONCE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#cross-entropy">Cross-entropy</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Mao_2021_NIPS,
    author = "Mao, Jiageng and Minzhe, Niu and Jiang, ChenHan and liang, hanxue and Chen, Jingheng and Liang, Xiaodan and Li, Yamin and Ye, Chaoqiang and Zhang, Wei and Li, Zhenguo and Yu, Jie and XU, Chunjing and Xu, Hang",
    title = "One Million Scenes for Autonomous Driving: {ONCE} Dataset",
    booktitle = "NeurIPS",
    year = "2021"
}
</pre>
</details>

</ul></details>
<a name=coax></a>
<details close>
<summary><l style="font-size:20px"><strong>Collaborative Action (CoAx)</strong></l> <a href=https://dlgmtzs.github.io/dataset-coax/>link</a> <a href=https://www.scitepress.org/Papers/2022/107756/107756.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of human robot collaboration using a robot arm.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Depth, Activity label</li>
<li><em><strong>Task:</strong></em> Human Robot Collaboration</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Lagamtzis et al., "Exploiting Spatio-Temporal Human-Object Relations Using Graph Neural Networks for Human Action Recognition and 3D Motion Forecasting", IROS, 2023.</em> <a href=https://ieeexplore.ieee.org/document/10342491>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bimanual_actions">Bimanual Actions</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#coax">CoAx</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/motion_alphabetical/motion_e-i_metrics.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/motion_alphabetical/motion_a-d_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@INPROCEEDINGS{Lagamtzis_2023_IROS,
    author = "Lagamtzis, Dimitrios and Schmidt, Fabian and Seyler, Jan and Dang, Thao and Schober, Steffen",
    booktitle = "IROS",
    title = "Exploiting Spatio-Temporal Human-Object Relations Using Graph Neural Networks for Human Action Recognition and 3D Motion Forecasting",
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
@inproceedings{lagamtzis2022coax,
    author = "Lagamtzis, Dimitrios and Schmidt, Fabian and Seyler, Jan R and Dang, Thao",
    title = "CoAx: Collaborative Action Dataset for Human Motion Forecasting in an Industrial Workspace.",
    booktitle = "ICAART",
    year = "2022"
}
</pre>
</details>

</ul></details>
<a name=copilot></a>
<details close>
<summary><l style="font-size:20px"><strong>COPILOT</strong></l> <a href=https://sites.google.com/stanford.edu/copilot>link</a> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Pan_COPILOT_Human-Environment_Collision_Prediction_and_Localization_from_Egocentric_Videos_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.01781.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 8.6M egocentric RGBD synthetic data with collision labels and heat maps.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, Collision region</li>
<li><em><strong>Task:</strong></em> Simulation (Ego)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Pan et al., "COPILOT: Human-Environment Collision Prediction and Localization from Egocentric Videos", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Pan_COPILOT_Human-Environment_Collision_Prediction_and_Localization_from_Egocentric_Videos_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.01781.pdf>arxiv</a> <a href=https://sites.google.com/stanford.edu/copilot>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#copilot">COPILOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#f1">F1</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#kld">KLD</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Pan_2023_ICCV,
    author = "Pan, Boxiao and Shen, Bokui and Rempe, Davis and Paschalidou, Despoina and Mo, Kaichun and Yang, Yanchao and Guibas, Leonidas J.",
    title = "COPILOT: Human-Environment Collision Prediction and Localization from Egocentric Videos",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul></details>
<a name=solarcube></a>
<details close>
<summary><l style="font-size:20px"><strong>SolarCube</strong></l> <a href=https://github.com/Ruohan-Li/SolarCube>link</a> <a href=https://openreview.net/pdf?id=WffhOhYvZ0>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of temporally and spatially aligned image-based satellite data and point-based insitu data for solar energy forecasting recorded from 19 study areas each size of 600x600 km^2
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Radiation</li>
<li><em><strong>Task:</strong></em> Solar radiation</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Li et al., "SolarCube: An Integrative Benchmark Dataset Harnessing Satellite and In-situ Observations for Large-scale Solar Energy Forecasting", NeurIPS, 2024.</em> <a href=https://openreview.net/pdf?id=WffhOhYvZ0>paper</a> <a href=https://github.com/Ruohan-Li/SolarCube>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#solarcube">SolarCube</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#rmse">RMSE</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#r-squared">R-squared</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_e-i_metrics.md#fs">FS</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#mbd">MBD</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@inproceedings{Li_Solarcube_2024_NeurIPS,
    author = "Li, Ruohan and Xie, Yiqun and Jia, Xiaowei and Wang, Dongdong and Li, Yanhua and Zhang, Yingxue and Wang, Zhihao and Li, Zhili",
    title = "SolarCube: An Integrative Benchmark Dataset Harnessing Satellite and In-situ Observations for Large-scale Solar Energy Forecasting",
    booktitle = "NeurIPS",
    year = "2024"
}
</pre>
</details>

</ul></details>
<a name=ltcf></a>
<details close>
<summary><l style="font-size:20px"><strong>Long-Term Crowd Flow (LTCF)</strong></l> <a href=https://github.com/SSSohn/LTCF>link</a> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123740698.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of simulated crow flow with 87K+ samples
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Grayscale, Trajectory</li>
<li><em><strong>Task:</strong></em> Crowd (Simulation)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sohn et al., "Laying the Foundations of Deep Long-Term Crowd Flow Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123740698.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ltcf">LTCF</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Sohn_2020_ECCV,
    author = "Sohn, Samuel S and Zhou, Honglu and Moon, Seonghyeon and Yoon, Sejong and Pavlovic, Vladimir and Kapadia, Mubbasir",
    title = "Laying the Foundations of Deep Long-Term Crowd Flow Prediction",
    booktitle = "ECCV",
    year = "2020"
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
<a name=gibson_env></a>
<details close>
<summary><l style="font-size:20px"><strong>Gibson Env</strong></l> <a href=http://gibsonenv.stanford.edu/database/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Xia_Gibson_Env_Real-World_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1808.10654.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of photo realistic 1.4K+ 3D indoor environments
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
@InProceedings{Xia_2018_CVPR,
    author = "Xia, Fei and R. Zamir, Amir and He, Zhi-Yang and Sax, Alexander and Malik, Jitendra and Savarese, Silvio",
    title = "{Gibson Env}: Real-world Perception for Embodied Agents",
    booktitle = "CVPR",
    year = "2018"
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
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Weather</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Siddiqui et al., "A Deep Learning Approach To Solar-Irradiance Forecasting In Sky-Videos", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8659184>paper</a> <a href=https://arxiv.org/pdf/1901.04881.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#arizona">Arizona</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tuscan">Tuscan</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#golden_colorado">Golden Colorado</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#nmape">nMAPE</a></li>
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
<a name=3d_movie></a>
<details close>
<summary><l style="font-size:20px"><strong>3D Movie</strong></l> <a href=https://www.di.ens.fr/willow/research/stereoseg/README.php>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of annotated poses and stereo pairs.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, 3D Pose, Stereo</li>
<li><em><strong>Task:</strong></em> Pose</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@inproceedings{Alahari_2013_ICCV,
    author = "Alahari, Karteek and Seguin, Guillaume and Sivic, Josef and Laptev, Ivan",
    title = "Pose Estimation and Segmentation of People in {3D} Movies",
    booktitle = "ICCV",
    year = "2013"
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
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, LIDAR, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Choi et al., "Robust Modeling And Prediction In Dynamic Environments Using Recurrent Flow Networks", IROS, 2016.</em> <a href=https://ieeexplore.ieee.org/abstract/document/7759278>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#fcvl">FCVL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#recall">Recall</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#precision">Precision</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_a-d_metrics.md#auc">AUC</a></li>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#run_time">Run Time</a></li>
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
    journal = "IJRR",
    volume = "30",
    number = "13",
    pages = "1543--1552",
    year = "2011"
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
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>He et al., "Aggregated Sparse Attention For Steering Angle Prediction", ICPR, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8546051>paper</a> <a href=https://arxiv.org/pdf/1803.05785.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#diplecs">DIPLECS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#mae">MAE</a></li>
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
<a name=amos></a>
<details close>
<summary><l style="font-size:20px"><strong>AMOS</strong></l> <a href=http://amos.cse.wustl.edu/>link</a> <a href=https://ieeexplore.ieee.org/document/4270283>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 17M+ images captured every half hour during a period of 6 months from 538 outdoor webcams across the US
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, time, camera coordinate</li>
<li><em><strong>Task:</strong></em> Weather</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chu et al., "Visual Weather Temperature Prediction", WACV, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8354136>paper</a> <a href=https://arxiv.org/pdf/1801.08267.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amos">AMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/other_alphabetical/other_j-z_metrics.md#rmse">RMSE</a></li>
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
<a name=pnw-typhoon></a>
<details close>
<summary><l style="font-size:20px"><strong>PNW-Typhoon</strong></l> <a href=https://github.com/DongGeun-Yoon/DGDM>link</a> <a href=https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04326.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of typhoon recording over 4 years in East Asia
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Grayscale</li>
<li><em><strong>Task:</strong></em> Weather</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@inproceedings{Yoon_Probabilistic_2024_ECCV,
    author = "Yoon, Donggeun and Seo, Minseok and Kim, Doyi and Choi, Yeji and Cho, Donghyeon",
    title = "Probabilistic Weather Forecasting with Deterministic Guidance-Based Diffusion Model",
    booktitle = "ECCV",
    year = "2024"
}
</pre>
</details>

</ul></details>
</ul>