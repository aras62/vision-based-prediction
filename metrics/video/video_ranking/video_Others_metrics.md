<a name=top></a>
<a name=top></a>
---
<a href=../../../README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../datasets/datasets.md#top><l style="font-size:30px">Datasets</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Metrics</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
[Home](../../metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Video&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Action](../../action/action_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Trajectory](../../trajectory/trajectory_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Motion](../../motion/motion_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Other](../../other/other_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[Home](../video_metrics.md"#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Alphabetical](../video_alphabetical/video_alphabetical_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Ranking&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[Top5](video_Top5_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Top6-10](video_Top6-10_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Others&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
<h2>Others</h2> 
<ul><a name=is></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Inception Scores (IS)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Lange et al., "Attention Augmented ConvLSTM for Environment Prediction", IROS, 2021.</em></strong> <a href=https://ieeexplore.ieee.org/abstract/document/9636386>paper</a> <a href=https://arxiv.org/pdf/2010.09662.pdf>arxiv</a> <a href=https://github.com/sisl/AttentionAugmentedConvLSTM>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="video_j-z_datasets.md#mse">MSE</a></li>
<li><a href="video_e-i_datasets.md#is">IS</a></li>
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
<summary><strong><em>Walker et al., "The Pose Knows: Video Forecasting By Generating Pose Futures", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Walker_The_Pose_Knows_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.00053.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="video_e-i_datasets.md#is">IS</a></li>
<li><a href="video_j-z_datasets.md#mmd">MMD</a></li>
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

<a name=fid></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Frechet Instance Distance (FID)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Sun et al., "MOSO: Decomposing MOtion, Scene and Object for Video Prediction", CVPR, 2023.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Sun_MOSO_Decomposing_MOtion_Scene_and_Object_for_Video_Prediction_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.03684.pdf>arxiv</a> <a href=https://github.com/iva-mzsun/MOSO>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#robonet">RoboNet</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="video_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="video_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="video_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="video_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="video_e-i_datasets.md#fid">FID</a></li>
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
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="video_e-i_datasets.md#is">IS</a></li>
<li><a href="video_j-z_datasets.md#mmd">MMD</a></li>
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

<a name=absrel></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Absolute Relative error (AbsRel)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Nematollahi et al., "T3VIP: Transformation-based $3\mathrmD$ Video Prediction", IROS, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/document/9981187>paper</a> <a href=https://arxiv.org/pdf/2209.11693.pdf>arxiv</a> <a href=https://github.com/nematoli/t3vip>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#omnipush">Omnipush</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#calvin">CALVIN</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="video_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="video_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="video_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="video_j-z_datasets.md#rmse">RMSE</a></li>
<li><a href="video_a-d_datasets.md#absrel">AbsRel</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Nematollahi_2022_IROS,
    author = "Nematollahi, Iman and Rosete-Beas, Erick and Azad, Seyed Mahdi B. and Rajan, Raghu and Hutter, Frank and Burgard, Wolfram",
    booktitle = "IROS",
    title = "{T3VIP}: Transformation-based $3\mathrm{D}$ Video Prediction",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
</ul>
</details>

<a name=sharpness></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Sharpness</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Rupprecht et al., "Learning in an Uncertain World: Representing Ambiguity Through Multiple Hypotheses", ICCV, 2017.</em></strong> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Rupprecht_Learning_in_an_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1612.00197.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="video_j-z_datasets.md#mse">MSE</a></li>
<li><a href="video_j-z_datasets.md#sharpness">Sharpness</a></li>
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
</ul>
</details>

<a name=iou></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Intersection over Union (IoU)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Lee et al., "Revisiting Hierarchical Approach for Persistent Long-Term Video Prediction", ICLR, 2021.</em></strong> <a href=https://openreview.net/pdf?id=3RLN4EPMdYd>paper</a> <a href=https://arxiv.org/pdf/2104.06697.pdf>arxiv</a> <a href=https://github.com/1Konny/HVP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#dancing">Dancing</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="video_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="video_e-i_datasets.md#iou">IoU</a></li>
<li><a href="video_a-d_datasets.md#csim">CSIM</a></li>
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
</ul>
</details>

<a name=gdl></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Gradient Difference Loss (GDL)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Wu et al., "MotionRNN: A Flexible Model for Video Prediction With Spacetime-Varying Motions", CVPR, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Wu_MotionRNN_A_Flexible_Model_for_Video_Prediction_With_Spacetime-Varying_Motions_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2103.02243.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="video_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="video_j-z_datasets.md#mse">MSE</a></li>
<li><a href="video_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="video_j-z_datasets.md#mae">MAE</a></li>
<li><a href="video_a-d_datasets.md#csi">CSI</a></li>
<li><a href="video_e-i_datasets.md#gdl">GDL</a></li>
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
</ul>
</details>

<a name=csi></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Critical Success Index (CSI)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Wu et al., "MotionRNN: A Flexible Model for Video Prediction With Spacetime-Varying Motions", CVPR, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Wu_MotionRNN_A_Flexible_Model_for_Video_Prediction_With_Spacetime-Varying_Motions_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2103.02243.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="video_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="video_j-z_datasets.md#mse">MSE</a></li>
<li><a href="video_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="video_j-z_datasets.md#mae">MAE</a></li>
<li><a href="video_a-d_datasets.md#csi">CSI</a></li>
<li><a href="video_e-i_datasets.md#gdl">GDL</a></li>
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
</ul>
</details>

<a name=ms-ssim></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Multi-Scale SSIM (MS-SSIM)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Wu et al., "Future Video Synthesis With Object Motion Prediction", CVPR, 2020.</em></strong> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Wu_Future_Video_Synthesis_With_Object_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.00542.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="video_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="video_j-z_datasets.md#ms-ssim">MS-SSIM</a></li>
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
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#bouncing_ball">Bouncing Ball</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="video_j-z_datasets.md#mse">MSE</a></li>
<li><a href="video_a-d_datasets.md#bce">BCE</a></li>
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

<a name=csim></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Cosine Similarity (CSIM)</strong></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Lee et al., "Revisiting Hierarchical Approach for Persistent Long-Term Video Prediction", ICLR, 2021.</em></strong> <a href=https://openreview.net/pdf?id=3RLN4EPMdYd>paper</a> <a href=https://arxiv.org/pdf/2104.06697.pdf>arxiv</a> <a href=https://github.com/1Konny/HVP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="datasets/alphabetical/a-d_alphabetical_datasets.md#dancing">Dancing</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="video_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="video_e-i_datasets.md#iou">IoU</a></li>
<li><a href="video_a-d_datasets.md#csim">CSIM</a></li>
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
</ul>
</details>

</ul>