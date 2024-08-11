<a name=top></a>
<a name=top></a>
---
<a href=../../../README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../../datasets/datasets.md#top><l style="font-size:30px">Datasets</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Metrics</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
[Home](../../metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Video&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Action](../../action/action_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Trajectory](../../trajectory/trajectory_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Motion](../../motion/motion_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Other](../../other/other_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[Home](../video_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Alphabetical&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Ranking](../video_ranking/video_ranking_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
A-D&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[E-I](video_e-i_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[J-Z](video_j-z_metrics.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
<h2>A-D <small>[rank]</small></h2> 
<ul><a name=absrel></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Absolute Relative error (AbsRel)</strong><small> [9]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Nematollahi et al., "T3VIP: Transformation-based $3\mathrmD$ Video Prediction", IROS, 2022.</em></strong> <a href=https://ieeexplore.ieee.org/document/9981187>paper</a> <a href=https://arxiv.org/pdf/2209.11693.pdf>arxiv</a> <a href=https://github.com/nematoli/t3vip>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#omnipush">Omnipush</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#calvin">CALVIN</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../../metrics/video/video_alphabetical/video_j-z_metrics.md#psnr">PSNR</a></li>
<li><a href="../../../metrics/video/video_alphabetical/video_j-z_metrics.md#lpips">LPIPS</a></li>
<li><a href="../../../metrics/video/video_alphabetical/video_j-z_metrics.md#rmse">RMSE</a></li>
<li><a href="../../../metrics/video/video_alphabetical/video_a-d_metrics.md#absrel">AbsRel</a></li>
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

</ul><ul><a name=bce></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Binary Cross Entropy (BCE)</strong><small> [9]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Hsieh et al., "Learning To Decompose And Disentangle Representations For Video Prediction", NeurIPS, 2018.</em></strong> <a href=https://papers.nips.cc/paper/7333-learning-to-decompose-and-disentangle-representations-for-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1806.04166.pdf>arxiv</a> <a href=https://github.com/jthsieh/DDPAE-video-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#bouncing_ball">Bouncing Ball</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/video/video_alphabetical/video_a-d_metrics.md#bce">BCE</a></li>
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

</ul><ul><a name=clipsim></a>
<details close>
<summary><em><l style="font-size:20px"><strong>CLIPSIM</strong><small> [9]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Yang et al., "Generalized Predictive Model for Autonomous Driving", CVPR, 2024.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2024/papers/Yang_Generalized_Predictive_Model_for_Autonomous_Driving_CVPR_2024_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2403.09630>arxiv</a> <a href=https://github.com/OpenDriveLab/DriveAGI>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#opendv-2k">OpenDV-2K</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
<li><a href="../../../metrics/video/video_alphabetical/video_e-i_metrics.md#fid">FID</a></li>
<li><a href="../../../metrics/video/video_alphabetical/video_a-d_metrics.md#clipsim">CLIPSIM</a></li>
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
</ul>
</details>

</ul><ul><a name=csi></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Critical Success Index (CSI)</strong><small> [9]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Wu et al., "MotionRNN: A Flexible Model for Video Prediction With Spacetime-Varying Motions", CVPR, 2021.</em></strong> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Wu_MotionRNN_A_Flexible_Model_for_Video_Prediction_With_Spacetime-Varying_Motions_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2103.02243.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/video/video_alphabetical/video_j-z_metrics.md#ssim">SSIM</a></li>
<li><a href="../../../metrics/video/video_alphabetical/video_j-z_metrics.md#mse">MSE</a></li>
<li><a href="../../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
<li><a href="../../../metrics/video/video_alphabetical/video_j-z_metrics.md#mae">MAE</a></li>
<li><a href="../../../metrics/video/video_alphabetical/video_a-d_metrics.md#csi">CSI</a></li>
<li><a href="../../../metrics/video/video_alphabetical/video_e-i_metrics.md#gdl">GDL</a></li>
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

</ul><ul><a name=csim></a>
<details close>
<summary><em><l style="font-size:20px"><strong>Cosine Similarity (CSIM)</strong><small> [9]</small></l>
</em></summary>
<ul>
<details close>
<summary><strong><em>Lee et al., "Revisiting Hierarchical Approach for Persistent Long-Term Video Prediction", ICLR, 2021.</em></strong> <a href=https://openreview.net/pdf?id=3RLN4EPMdYd>paper</a> <a href=https://arxiv.org/pdf/2104.06697.pdf>arxiv</a> <a href=https://github.com/1Konny/HVP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../../../datasets/alphabetical/a-d_alphabetical_datasets.md#dancing">Dancing</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../../metrics/video/video_alphabetical/video_e-i_metrics.md#fvd">FVD</a></li>
<li><a href="../../../metrics/video/video_alphabetical/video_e-i_metrics.md#iou">IoU</a></li>
<li><a href="../../../metrics/video/video_alphabetical/video_a-d_metrics.md#csim">CSIM</a></li>
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