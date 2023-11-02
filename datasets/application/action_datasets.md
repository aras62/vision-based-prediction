<a name=top></a>
<a name=top></a>
---
<a href=../../README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Datasets</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../metrics.md#top><l style="font-size:30px">Metrics</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
[Home](../datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Alphabetical](../alphabetical/alphabetical_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Year](../year/year_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Application&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Task](../task/task_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Annotation](../annotation_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[Video](video_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Action&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Trajectory](trajectory_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Motion](motion_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Other](other_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
<h2>Action Datasets</h2> 
<ul><a name=human3.6m></a>
<details close>
<summary><l style="font-size:20px"><strong>Human3.6M</strong></l> <a href=http://vision.imar.ro/human3.6m/description.php>link</a> <a href=https://ieeexplore.ieee.org/document/6682899>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale dataset of 3D human poses with 3M+ images captured using 11 professional actors in 17 scenarios, such as discussion, smoking, taking photo, etc.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a>, <a href=../../papers/action/action_papers.md#top>Action prediction<application></a>, <a href=../../papers/motion/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chang et al., "STRPM: A Spatiotemporal Residual Predictive Model for High-Resolution Video Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Chang_STRPM_A_Spatiotemporal_Residual_Predictive_Model_for_High-Resolution_Video_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.16084.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf_sports">UCF Sports</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sjtu4k">SJTU4K</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chang_2022_CVPR,
    author = "Chang, Zheng and Zhang, Xinfeng and Wang, Shanshe and Ma, Siwei and Gao, Wen",
    title = "{STRPM}: A Spatiotemporal Residual Predictive Model for High-Resolution Video Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Gao et al., "SimVP: Simpler Yet Better Video Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Gao_SimVP_Simpler_Yet_Better_Video_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2206.05099.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#taxi_bj">Taxi BJ</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2022_CVPR,
    author = "Gao, Zhangyang and Tan, Cheng and Wu, Lirong and Li, Stan Z.",
    title = "{SimVP}: Simpler Yet Better Video Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Pourheydari et al., "TaylorSwiftNet: Taylor Driven Temporal Modeling for Swift Future Frame Prediction", BMVC, 2022.</em> <a href=https://bmvc2022.mpi-inf.mpg.de/0389.pdf>paper</a> <a href=https://arxiv.org/pdf/2110.14392.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#taxi_bj">Taxi BJ</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sst">SST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Pourheydari_2022_BMVC,
    author = "Pourheydari, Mohammad Saber and Bahrami, Emad and Fayyaz, Mohsen and Francesca, Gianpiero and Noroozi, Mehdi and Gall, Jürgen",
    title = "{TaylorSwiftNet}: Taylor Driven Temporal Modeling for Swift Future Frame Prediction",
    booktitle = "BMVC",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "Towards Unified Multi-Excitation for Unsupervised Video Prediction", BMVC, 2022.</em> <a href=https://bmvc2022.mpi-inf.mpg.de/0587.pdf>paper</a> <a href=https://github.com/captaincj/UMENet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#taxi_bj">Taxi BJ</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sst">SST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2022_BMVC,
    author = "Wang, Junyan and Likun, Qin and Zhang, Peng and Long, Yang and Hu, Bingzhang and Pagnucco, Maurice and Wang, Shizheng and Song, Yang",
    title = "Towards Unified Multi-Excitation for Unsupervised Video Prediction",
    booktitle = "BMVC",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Lee et al., "Video Prediction Recalling Long-Term Motion Context via Memory Alignment Learning", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Lee_Video_Prediction_Recalling_Long-Term_Motion_Context_via_Memory_Alignment_Learning_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2104.00924.pdf>arxiv</a> <a href=https://github.com/sangmin-git/LMC-Memory>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lee_2021_CVPR,
    author = "Lee, Sangmin and Kim, Hak Gu and Choi, Dae Hwi and Kim, Hyung-Il and Ro, Yong Man",
    title = "Video Prediction Recalling Long-Term Motion Context via Memory Alignment Learning",
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_e-i_datasets.md#human">Human</a></li>
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
<summary><em>Wu et al., "MotionRNN: A Flexible Model for Video Prediction With Spacetime-Varying Motions", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Wu_MotionRNN_A_Flexible_Model_for_Video_Prediction_With_Spacetime-Varying_Motions_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2103.02243.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_a-d_datasets.md#csi">CSI</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_e-i_datasets.md#gdl">GDL</a></li>
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
<details close>
<summary><em>Gao et al., "Accurate Grid Keypoint Learning for Efficient Video Prediction", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636874>paper</a> <a href=https://arxiv.org/pdf/2107.13170.pdf>arxiv</a> <a href=https://github.com/xjgaocs/Grid-Keypoint-Learning>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jigsaws">JIGSAWS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2021_IROS,
    author = "Gao, Xiaojie and Jin, Yueming and Dou, Qi and Fu, Chi-Wing and Heng, Pheng-Ann",
    booktitle = "IROS",
    title = "Accurate Grid Keypoint Learning for Efficient Video Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Le et al., "Disentangling Physical Dynamics From Unknown Factors for Unsupervised Video Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Le_Guen_Disentangling_Physical_Dynamics_From_Unknown_Factors_for_Unsupervised_Video_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.01460.pdf>arxiv</a> <a href=https://github.com/vincent-leguen/PhyDNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#taxi_bj">Taxi BJ</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sst">SST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
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
<summary><em>Franceschi et al., "Stochastic Latent Residual Video Prediction", ICML, 2020.</em> <a href=http://proceedings.mlr.press/v119/franceschi20a/franceschi20a.pdf>paper</a> <a href=https://arxiv.org/pdf/2002.09219.pdf>arxiv</a> <a href=https://github.com/edouardelasalles/srvp>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Franceschi_2020_ICML,
    author = {Franceschi, Jean-Yves and Delasalles, Edouard and Chen, Micka{\"e}l and Lamprier, Sylvain and Gallinari, Patrick},
    title = "Stochastic Latent Residual Video Prediction",
    booktitle = "ICML",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yao et al., "Unsupervised Transfer Learning for Spatiotemporal Predictive Networks", ICML, 2020.</em> <a href=http://proceedings.mlr.press/v119/yao20a/yao20a.pdf>paper</a> <a href=https://arxiv.org/pdf/2009.11763.pdf>arxiv</a> <a href=https://github.com/thuml/transferable-memory>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#weizmann">Weizmann</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yao_2020_ICML,
    author = "Yao, Zhiyu and Wang, Yunbo and Long, Mingsheng and Wang, Jianmin",
    title = "Unsupervised Transfer Learning for Spatiotemporal Predictive Networks",
    booktitle = "ICML",
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_e-i_datasets.md#human">Human</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_e-i_datasets.md#human">Human</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<summary><em>Mascaro et al., "Intention-Conditioned Long-Term Human Egocentric Action Anticipation", WACV, 2023.</em> <a href=https://openaccess.thecvf.com/content/WACV2023/papers/Mascaro_Intention-Conditioned_Long-Term_Human_Egocentric_Action_Anticipation_WACV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#ego4d">Ego4D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#eid">EiD</a></li>
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
<details close>
<summary><em>Butepage et al., "Deep Representation Learning For Human Motion Prediction And Classification", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Butepage_Deep_Representation_Learning_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1702.07486.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<summary><em>Mahdavian et al., "STPOTR: Simultaneous Human Trajectory and Pose Prediction Using a Non-Autoregressive Transformer for Robot Follow-Ahead", ICRA, 2023.</em> <a href=https://ieeexplore.ieee.org/document/10160538>paper</a> <a href=https://arxiv.org/pdf/2209.07600.pdf>arxiv</a> <a href=https://github.com/mmahdavian/STPOTR>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<summary><em>Nikdel et al., "DMMGAN: Diverse Multi Motion Prediction of 3D Human Joints using Attention-Based Generative Adversarial Network", ICRA, 2023.</em> <a href=https://ieeexplore.ieee.org/document/10160401>paper</a> <a href=https://arxiv.org/pdf/2209.09124.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<summary><em>Gao et al., "Decompose More and Aggregate Better: Two Closer Looks at Frequency Representation Learning for Human Motion Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Gao_Decompose_More_and_Aggregate_Better_Two_Closer_Looks_at_Frequency_CVPR_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Sun et al., "DeFeeNet: Consecutive 3D Human Motion Prediction With Deviation Feedback", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Sun_DeFeeNet_Consecutive_3D_Human_Motion_Prediction_With_Deviation_Feedback_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2304.04496.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#babel">BABEL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Xu et al., "Uncovering the Missing Pattern: Unified Framework Towards Trajectory Imputation and Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Xu_EqMotion_Equivariant_Multi-Agent_Motion_Prediction_With_Invariant_Interaction_Reasoning_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.10876.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/EqMotion>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Barquero et al., "BeLFusion: Latent Diffusion for Behavior-Driven Human Motion Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Barquero_BeLFusion_Latent_Diffusion_for_Behavior-Driven_Human_Motion_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2211.14304.pdf>arxiv</a> <a href=https://barquerogerman.github.io/BeLFusion/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#apd">APD</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mmade">MMADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mmfde">MMFDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_e-i_datasets.md#fid">FID</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#cmd">CMD</a></li>
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
<summary><em>Choudhury et al., "TEMPO: Efficient Multi-View Pose Estimation, Tracking, and Forecasting", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Choudhury_TEMPO_Efficient_Multi-View_Pose_Estimation_Tracking_and_Forecasting_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2309.07910.pdf>arxiv</a> <a href=https://rccchoudhury.github.io/tempo2023/>code</a></summary>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#pcp3d">PCP3D</a></li>
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
<summary><em>Cui et al., "Test-time Personalizable Forecasting of 3D Human Poses", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Cui_Test-time_Personalizable_Forecasting_of_3D_Human_Poses_ICCV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#grab">GRAB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#pck">PCK</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpble">MPBLE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#p-mpjpe">P-MPJPE</a></li>
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
<summary><em>Xing et al., "HDG-ODE: A Hierarchical Continuous-Time Model for Human Pose Forecasting", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Xing_HDG-ODE_A_Hierarchical_Continuous-Time_Model_for_Human_Pose_Forecasting_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.05859.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mupots-3d">MuPoTS-3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#pck">PCK</a></li>
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
<summary><em>Chen et al., "HumanMAC: Masked Motion Completion for Human Motion Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_HumanMAC_Masked_Motion_Completion_for_Human_Motion_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2302.03665.pdf>arxiv</a> <a href=https://lhchen.top/Human-MAC/>code</a></summary>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#apd">APD</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mmade">MMADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mmfde">MMFDE</a></li>
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
<summary><em>Xu et al., "Auxiliary Tasks Benefit 3D Skeleton-based Human Motion Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Xu_Auxiliary_Tasks_Benefit_3D_Skeleton-based_Human_Motion_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.08942.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/AuxFormer>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Ahn et al., "Can We Use Diffusion Probabilistic Models for 3D Motion Prediction?", ICRA, 2023.</em> <a href=https://ieeexplore.ieee.org/document/10160722>paper</a> <a href=https://arxiv.org/pdf/2302.14503.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#apd">APD</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#sde">sDE</a></li>
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
<summary><em>Saadatnejad et al., "A generic diffusion-based approach for 3D human pose prediction in the wild", ICRA, 2023.</em> <a href=https://ieeexplore.ieee.org/document/10160399>paper</a> <a href=https://arxiv.org/pdf/2210.05669.pdf>arxiv</a></summary>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mmade">MMADE</a></li>
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
<summary><em>Guo et al., "Back to MLP: A Simple Baseline for Human Motion Prediction", WACV, 2023.</em> <a href=https://openaccess.thecvf.com/content/WACV2023/papers/Guo_Back_to_MLP_A_Simple_Baseline_for_Human_Motion_Prediction_WACV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.01567.pdf>arxiv</a> <a href=https://github.com/dulucas/siMLPe>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Ma et al., "Multi-Objective Diverse Human Motion Prediction With Knowledge Distillation", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Ma_Multi-Objective_Diverse_Human_Motion_Prediction_With_Knowledge_Distillation_CVPR_2022_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#apd">APD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ma_2022_CVPR_2,
    author = "Ma, Hengbo and Li, Jiachen and Hosseini, Ramtin and Tomizuka, Masayoshi and Choi, Chiho",
    title = "Multi-Objective Diverse Human Motion Prediction With Knowledge Distillation",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Diller et al., "Forecasting Characteristic 3D Poses of Human Actions", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Diller_Forecasting_Characteristic_3D_Poses_of_Human_Actions_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2011.15079.pdf>arxiv</a> <a href=https://github.com/chrdiller/characteristic3dposes>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#grab">GRAB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_e-i_datasets.md#is">IS</a></li>
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
<summary><em>Ma et al., "Progressively Generating Better Initial Guesses Towards Next Stages for High-Quality Human Motion Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Ma_Progressively_Generating_Better_Initial_Guesses_Towards_Next_Stages_for_High-Quality_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.16051.pdf>arxiv</a> <a href=https://github.com/705062791/PGBIG>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<summary><em>Salzmann et al., "Motron: Multimodal Probabilistic Human Motion Forecasting", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Salzmann_Motron_Multimodal_Probabilistic_Human_Motion_Forecasting_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.04132.pdf>arxiv</a> <a href=https://github.com/TUM-AAS/motron-cvpr22>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#apd">APD</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#nll">NLL</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#kde">KDE</a></li>
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
<details close>
<summary><em>Zhong et al., "Spatio-Temporal Gating-Adjacency GCN for Human Motion Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Zhong_Spatio-Temporal_Gating-Adjacency_GCN_for_Human_Motion_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.01474.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<summary><em>Li et al., "Skeleton-Parted Graph Scattering Networks for 3D Human Motion Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136660018.pdf>paper</a> <a href=https://arxiv.org/pdf/2208.00368.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/SPGSN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<summary><em>Sampieri et al., "Pose Forecasting in Industrial Human-Robot Collaboration", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136980051.pdf>paper</a> <a href=https://arxiv.org/pdf/2208.07308.pdf>arxiv</a> <a href=https://github.com/federicocunico/human-robot-collaboration>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#chico">CHICO</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Sun et al., "Overlooked Poses Actually Make Sense: Distilling Privileged Knowledge for Human Motion Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136650668.pdf>paper</a> <a href=https://arxiv.org/pdf/2208.01302.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<summary><em>Xu et al., "Diverse Human Motion Prediction Guided by Multi-level Spatial-Temporal Anchors", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820244.pdf>paper</a> <a href=https://github.com/Sirui-Xu/STARS>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#apd">APD</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#minade">minADE</a></li>
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
<details close>
<summary><em>Mascaro et al., "Robust Human Motion Forecasting using Transformer-based Model", IROS, 2022.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9981877>paper</a> <a href=https://arxiv.org/pdf/2302.08274.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mse">MSE</a></li>
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
<summary><em>Zhang et al., "IMNet: Physics-Infused Neural Network for Human Motion Prediction", RAL, 2022.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9816127>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_e-i_datasets.md#ed">ED</a></li>
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
<summary><em>Sun et al., "Action-guided 3D Human Motion Prediction", NeurIPS, 2021.</em> <a href=https://papers.nips.cc/paper/2021/file/fd9dd764a6f1d73f4340d570804eacc4-Paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#pck">PCK</a></li>
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
<summary><em>Cui et al., "Towards Accurate 3D Human Motion Prediction From Incomplete Observations", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Cui_Towards_Accurate_3D_Human_Motion_Prediction_From_Incomplete_Observations_CVPR_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Li et al., "RAIN: Reinforced Hybrid Attention Inference Network for Motion Forecasting", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Li_RAIN_Reinforced_Hybrid_Attention_Inference_Network_for_Motion_Forecasting_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2108.01316.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<summary><em>Aliakbarian et al., "Contextually Plausible and Diverse 3D Human Motion Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Aliakbarian_Contextually_Plausible_and_Diverse_3D_Human_Motion_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.08521.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#kld">KLD</a></li>
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
<summary><em>Dang et al., "MSR-GCN: Multi-Scale Residual Graph Convolution Networks for Human Motion Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Dang_MSR-GCN_Multi-Scale_Residual_Graph_Convolution_Networks_for_Human_Motion_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://github.com/Droliven/MSRGCN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Liu et al., "Motion Prediction Using Trajectory Cues", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Liu_Motion_Prediction_Using_Trajectory_Cues_ICCV_2021_paper.pdf>paper</a> <a href=https://github.com/Pose-Group/MPT>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mouse_fish">Mouse Fish</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Mao et al., "Generating Smooth Pose Sequences for Diverse Human Motion Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Mao_Generating_Smooth_Pose_Sequences_for_Diverse_Human_Motion_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2108.08422.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#apd">APD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mao_2021_ICCV,
    author = "Mao, Wei and Liu, Miaomiao and Salzmann, Mathieu",
    title = "Generating Smooth Pose Sequences for Diverse Human Motion Prediction",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sofianos et al., "Space-Time-Separable Graph Convolutional Network for Pose Forecasting", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Sofianos_Space-Time-Separable_Graph_Convolutional_Network_for_Pose_Forecasting_ICCV_2021_paper.pdf>paper</a> <a href=https://github.com/FraLuca/STSGCN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<summary><em>Li et al., "Directed Acyclic Graph Neural Network for Human Motion Prediction", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561540>paper</a> <a href=https://github.com/Qinli-zz/DA-GNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<summary><em>Xu et al., "Probabilistic Human Motion Prediction via A Bayesian Neural Network", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561665>paper</a> <a href=https://arxiv.org/pdf/2107.06564.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Zhang et al., "Non-local Graph Convolutional Network for Joint Activity Recognition and Motion Prediction", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636107>paper</a> <a href=https://arxiv.org/pdf/2108.01518.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<summary><em>Aliakbarian et al., "A Stochastic Conditioning Scheme for Diverse Human Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Aliakbarian_A_Stochastic_Conditioning_Scheme_for_Diverse_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://github.com/mix-and-match/mix-and-match-tutorial>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#kld">KLD</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#si">SI</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#kl">KL</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#s-mse">S-MSE</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<summary><em>Cai et al., "Learning Progressive Joint Propagation for Human Motion Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520222.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<summary><em>Mao et al., "History Repeats Itself: Human Motion Prediction via Motion Attention", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590460.pdf>paper</a> <a href=https://arxiv.org/pdf/2007.11755.pdf>arxiv</a> <a href=https://github.com/wei-mao-2019/HisRepItself>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#amass">AMASS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<summary><em>Piergiovanni et al., "Adversarial Generative Grammars for Human Activity Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470494.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.04888.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<summary><em>Yuan et al., "DLow: Diversifying Latent Flows for Diverse Human Motion Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123540324.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.08386.pdf>arxiv</a> <a href=https://github.com/Khrylx/DLow>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#humaneva-i">HumanEva-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#apd">APD</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mmade">MMADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mmfde">MMFDE</a></li>
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
<details close>
<summary><em>Chao et al., "Adversarial Refinement Network for Human Motion Prediction", ACCV, 2020.</em> <a href=https://openaccess.thecvf.com/content/ACCV2020/papers/Chao_Adversarial_Refinement_Network_for_Human_Motion_Prediction_ACCV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2011.11221.pdf>arxiv</a> <a href=https://github.com/Xianjin111/ARNet-for-human-motion-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<details close>
<summary><em>Lebailly et al., "Motion Prediction Using Temporal Inception Module", ACCV, 2020.</em> <a href=https://openaccess.thecvf.com/content/ACCV2020/papers/Lebailly_Motion_Prediction_Using_Temporal_Inception_Module_ACCV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2010.03006.pdf>arxiv</a> <a href=https://github.com/tileb1/motion-prediction-tim>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Gopalakrishnan et al., "A Neural Temporal Model For Human Motion Prediction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Gopalakrishnan_A_Neural_Temporal_Model_for_Human_Motion_Prediction_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1809.03036.pdf>arxiv</a> <a href=https://github.com/cr7anand/neural_temporal_models>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#npss">NPSS</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mouse_fish">Mouse Fish</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mje">MJE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#run_time">Run Time</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_e-i_datasets.md#human">Human</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#pskl">PSKL</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#psent">PSEnt</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#instavariety">InstaVariety</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#pck">PCK</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#re">RE</a></li>
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
<summary><em>Chiu et al., "Action-Agnostic Human Pose Forecasting", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8658717>paper</a> <a href=https://arxiv.org/pdf/1810.09676.pdf>arxiv</a> <a href=https://github.com/eddyhkchiu/pose_forecast_wacv/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mje">MJE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#pck">PCK</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_e-i_datasets.md#human">Human</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mpii_human_pose">MPII Human Pose</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#pck">PCK</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<summary><em>Jain et al., "Structural-RNN: Deep Learning On Spatio-Temporal Graphs", CVPR, 2016.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.05298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<summary><em>Fragkiadaki et al., "Recurrent Network Models For Human Dynamics", ICCV, 2015.</em> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Fragkiadaki_Recurrent_Network_Models_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1508.00271.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#accuracy">Accuracy</a></li>
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
    title = "{Human3.6M}: Large Scale Datasets And Predictive Methods For {3D} Human Sensing In Natural Environments",
    journal = "PAMI",
    volume = "36",
    number = "7",
    pages = "1325-1339",
    year = "2014"
}
</pre>
</details>

</ul></details>
<a name=nuscenes></a>
<details close>
<summary><l style="font-size:20px"><strong>nuScenes</strong></l> <a href=https://www.nuscenes.org/>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Caesar_nuScenes_A_Multimodal_Dataset_for_Autonomous_Driving_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1903.11027.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset with 1K driving sequences and 1M+ 3D bounding boxes annotated at 2hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a>, <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, LIDAR, 3D Bounding Box, Object Class, Attribute, Map, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Schmeckpeper et al., "Learning Predictive Models From Observation and Interaction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650698.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.12773.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#htud">HTUD</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bdd100k">BDD100K</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Schmeckpeper_2020_ECCV,
    author = "Schmeckpeper, Karl and Xie, Annie and Rybkin, Oleh and Tian, Stephen and Daniilidis, Kostas and Levine, Sergey and Finn, Chelsea",
    title = "Learning Predictive Models From Observation and Interaction",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ivanovic et al., "Expanding the Deployment Envelope of Behavior Prediction via Adaptive Meta-Learning", ICRA, 2023.</em> <a href=https://ieeexplore.ieee.org/document/10161155>paper</a> <a href=https://arxiv.org/pdf/2209.11820.pdf>arxiv</a> <a href=https://github.com/ NVlabs/adaptive-prediction.>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#nll">NLL</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#ece">ECE</a></li>
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
<summary><em>Fang et al., "TBP-Former: Learning Temporal Bird's-Eye-View Pyramid for Joint Perception and Prediction in Vision-Centric Autonomous Driving", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Fang_TBP-Former_Learning_Temporal_Birds-Eye-View_Pyramid_for_Joint_Perception_and_Prediction_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.09998.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/TBP-Former>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#iou">IoU</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#vpq">VPQ</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Fang_2023_CVPR,
    author = "Fang, Shaoheng and Wang, Zi and Zhong, Yiqi and Ge, Junhao and Chen, Siheng",
    title = "TBP-Former: Learning Temporal Bird's-Eye-View Pyramid for Joint Perception and Prediction in Vision-Centric Autonomous Driving",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Gu et al., "ViP3D: End-to-End Visual Trajectory Prediction via 3D Agent Queries", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Gu_ViP3D_End-to-End_Visual_Trajectory_Prediction_via_3D_Agent_Queries_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2208.01582.pdf>arxiv</a> <a href=https://tsinghua-mars-lab.github.io/ViP3D/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mr">MR</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#epa">EPA</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gu_2023_CVPR,
    author = "Gu, Junru and Hu, Chenxu and Zhang, Tianyuan and Chen, Xuanyao and Wang, Yilun and Wang, Yue and Zhao, Hang",
    title = "ViP3D: End-to-End Visual Trajectory Prediction via 3D Agent Queries",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "FEND: A Future Enhanced Distribution-Aware Contrastive Learning Framework for Long-Tail Trajectory Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_FEND_A_Future_Enhanced_Distribution-Aware_Contrastive_Learning_Framework_for_Long-Tail_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.16574.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<summary><em>Zhu et al., "IPCC-TP: Utilizing Incremental Pearson Correlation Coefficient for Joint Multi-Agent Trajectory Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Zhu_IPCC-TP_Utilizing_Incremental_Pearson_Correlation_Coefficient_for_Joint_Multi-Agent_Trajectory_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.00575.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minjointfde">minJointFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minjointade">minJointADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhu_2023_CVPR,
    author = "Zhu, Dekai and Zhai, Guangyao and Di, Yan and Manhardt, Fabian and Berkemeyer, Hendrik and Tran, Tuan and Navab, Nassir and Tombari, Federico and Busam, Benjamin",
    title = "IPCC-TP: Utilizing Incremental Pearson Correlation Coefficient for Joint Multi-Agent Trajectory Prediction",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Choi et al., "R-Pred: Two-Stage Motion Prediction Via Tube-Query Attention-Based Trajectory Refinement", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Choi_R-Pred_Two-Stage_Motion_Prediction_Via_Tube-Query_Attention-Based_Trajectory_Refinement_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2211.08609.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mr">MR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Choi_2023_ICCV,
    author = "Choi, Sehwan and Kim, Jungho and Yun, Junyong and Choi, Jun Won",
    title = "R-Pred: Two-Stage Motion Prediction Via Tube-Query Attention-Based Trajectory Refinement",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Pourkeshavarz et al., "Learn TAROT with MENTOR: A Meta-Learned Self-Supervised Approach for Trajectory Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Pourkeshavarz_Learn_TAROT_with_MENTOR_A_Meta-Learned_Self-Supervised_Approach_for_Trajectory_ICCV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mr">MR</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#rf">RF</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#dao">DAO</a></li>
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
<details close>
<summary><em>Veer et al., "Multi-Predictor Fusion: Combining Learning-based and Rule-based Trajectory Predictors", CoRL, 2023.</em> <a href=https://openreview.net/pdf?id=MF_cS7TCYk>paper</a> <a href=https://arxiv.org/pdf/2307.01408.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Veer_2023_CoRL,
    author = "Veer, Sushant and Sharma, Apoorva and Pavone, Marco",
    title = "Multi-Predictor Fusion: Combining Learning-based and Rule-based Trajectory Predictors",
    booktitle = "CoRL",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zheng et al., "Robustness of Trajectory Prediction Models Under Map-Based Attacks", WACV, 2023.</em> <a href=https://openaccess.thecvf.com/content/WACV2023/papers/Zheng_Robustness_of_Trajectory_Prediction_Models_Under_Map-Based_Attacks_WACV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zheng_2023_WACV,
    author = "Zheng, Zhihao and Ying, Xiaowen and Yao, Zhen and Chuah, Mooi Choo",
    title = "Robustness of Trajectory Prediction Models Under Map-Based Attacks",
    booktitle = "WACV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chen et al., "ScePT: Scene-Consistent, Policy-Based Trajectory Predictions for Planning", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Chen_ScePT_Scene-Consistent_Policy-Based_Trajectory_Predictions_for_Planning_CVPR_2022_paper.pdf>paper</a> <a href=https://github.com/nvr-avg/ScePT>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2022_CVPR,
    author = "Chen, Yuxiao and Ivanovic, Boris and Pavone, Marco",
    title = "{ScePT}: Scene-Consistent, Policy-Based Trajectory Predictions for Planning",
    booktitle = "CVPR",
    year = "2022"
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#nll">NLL</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#kde">KDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#ecfl">ECFL</a></li>
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
<summary><em>Peri et al., "Forecasting From LiDAR via Future Object Detection", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Peri_Forecasting_From_LiDAR_via_Future_Object_Detection_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.16297.pdf>arxiv</a> <a href=https://github.com/neeharperi/FutureDet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ap">AP</a></li>
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
<summary><em>Weng et al., "Whose Track Is It Anyway? Improving Robustness to Tracking Errors With Affinity-Based Trajectory Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Weng_Whose_Track_Is_It_Anyway_Improving_Robustness_to_Tracking_Errors_CVPR_2022_paper.pdf>paper</a> <a href=https://www.xinshuoweng.com/projects/Affinipred/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
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
<summary><em>Zhang et al., "On Adversarial Robustness of Trajectory Prediction for Autonomous Vehicles", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_On_Adversarial_Robustness_of_Trajectory_Prediction_for_Autonomous_Vehicles_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2201.05057.pdf>arxiv</a> <a href=https://github.com/zqzqz/AdvTrajectoryPrediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2022_CVPR,
    author = "Zhang, Qingzhao and Hu, Shengtuo and Sun, Jiachen and Chen, Qi Alfred and Mao, Z. Morley",
    title = "On Adversarial Robustness of Trajectory Prediction for Autonomous Vehicles",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "BE-STI: Spatial-Temporal Integrated Network for Class-Agnostic Motion Prediction With Bidirectional Enhancement", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_BE-STI_Spatial-Temporal_Integrated_Network_for_Class-Agnostic_Motion_Prediction_With_Bidirectional_CVPR_2022_paper.pdf>paper</a> <a href=https://github.com/be-sti/be-sti>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<summary><em>Xu et al., "PreTraM: Self-Supervised Pre-training via Connecting Trajectory and Map", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136990034.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.10435.pdf>arxiv</a> <a href=https://github.com/chenfengxu714/PreTraM>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2022_ECCV_3,
    author = "Xu, Chenfeng and Li, Tian and Tang, Chen and Sun, Lingfeng and Keutzer, Kurt and Tomizuka, Masayoshi and Fathi, Alireza and Zhan, Wei",
    title = "{PreTraM}: Self-Supervised Pre-training via Connecting Trajectory and Map",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Cao et al., "AdvDO: Realistic Adversarial Attacks for Trajectory Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136650036.pdf>paper</a> <a href=https://arxiv.org/pdf/2209.08744.pdf>arxiv</a> <a href=https://robustav.github.io/RobustPred/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mr">MR</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#orr">ORR</a></li>
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
<summary><em>Choi et al., "Hierarchical Latent Structure for Multi-modal Vehicle Trajectory Forecasting", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820125.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.04624.pdf>arxiv</a> <a href=https://github.com/d1024choi/HLSTrajForecast>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Choi_2022_ECCV,
    author = "Choi, Dooseop and Min, KyoungWook",
    title = "Hierarchical Latent Structure for Multi-modal Vehicle Trajectory Forecasting",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhong et al., "Aware of the History: Trajectory Forecasting with the Local Behavior Data", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820383.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.09646.pdf>arxiv</a> <a href=https://github.com/Kay1794/LocalBehavior-based-trajectory-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mr">MR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhong_2022_ECCV,
    author = "Zhong, Yiqi and Ni, Zhenyang and Chen, Siheng and Neumann, Ulrich",
    title = "Aware of the History: Trajectory Forecasting with the Local Behavior Data",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Cao et al., "Robust Trajectory Prediction against Adversarial Attacks", CoRL, 2022.</em> <a href=https://openreview.net/pdf?id=uhhA2OryTjj>paper</a> <a href=https://arxiv.org/pdf/2208.00094.pdf>arxiv</a> <a href=https://github.com/kikacaty/RobustTraj>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cao_2022_CoRL,
    author = "Cao, Yulong and Xu, Danfei and Weng, Xinshuo and Mao, Zhuoqing and Anandkumar, Anima and Xiao, Chaowei and Pavone, Marco",
    title = "Robust Trajectory Prediction against Adversarial Attacks",
    booktitle = "CoRL",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Itkina et al., "Interpretable Self-Aware Neural Networks for Robust Trajectory Prediction", CoRL, 2022.</em> <a href=https://openreview.net/pdf?id=fnaMlJbRc4t>paper</a> <a href=https://download.arxiv.org/pdf/2211.08701v1>arxiv</a> <a href=https://github.com/sisl/InterpretableSelfAwarePrediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Itkina_2022_CoRL,
    author = "Itkina, Masha and Kochenderfer, Mykel",
    title = "Interpretable Self-Aware Neural Networks for Robust Trajectory Prediction",
    booktitle = "CoRL",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Girgis et al., "Latent Variable Sequential Set Transformers for Joint Multi-Agent Motion Prediction", ICLR, 2022.</em> <a href=https://openreview.net/pdf?id=Dup_dDqkZC5>paper</a> <a href=https://arxiv.org/pdf/2104.00563.pdf>arxiv</a> <a href=https://fgolemo.github.io/autobots/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#trajnet++">Trajnet++</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mr">MR</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#orr">ORR</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#dac">DAC</a></li>
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
<summary><em>Makansi et al., "You Mostly Walk Alone: Analyzing Feature Attribution in Trajectory Prediction", ICLR, 2022.</em> <a href=https://openreview.net/pdf?id=POxF-LEqnF>paper</a> <a href=https://arxiv.org/pdf/2110.05304.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Makansi_2022_ICLR,
    author = "Makansi, Osama and Kugelgen, Julius Von and Locatello, Francesco and Gehler, Peter Vincent and Janzing, Dominik and Brox, Thomas and Scholkopf, Bernhard",
    title = "You Mostly Walk Alone: Analyzing Feature Attribution in Trajectory Prediction",
    booktitle = "ICLR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ivanovic et al., "Propagating State Uncertainty Through Trajectory Forecasting", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9811776>paper</a> <a href=https://arxiv.org/pdf/2110.03267.pdf>arxiv</a> <a href=https://github.com/StanfordASL/PSU-TF>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#nll">NLL</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#deltaesv">DeltaESV</a></li>
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
<details close>
<summary><em>Fadadu et al., "Multi-View Fusion of Sensor Data for Improved Perception and Prediction in Autonomous Driving", WACV, 2022.</em> <a href=https://openaccess.thecvf.com/content/WACV2022/papers/Fadadu_Multi-View_Fusion_of_Sensor_Data_for_Improved_Perception_and_Prediction_WACV_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.11901.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Fadadu_2022_WACV,
    author = "Fadadu, Sudeep and Pandey, Shreyash and Hegde, Darshan and Shi, Yi and Chou, Fang-Chieh and Djuric, Nemanja and Vallespi-Gonzalez, Carlos",
    title = "Multi-View Fusion of Sensor Data for Improved Perception and Prediction in Autonomous Driving",
    booktitle = "WACV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Tang et al., "Interventional Behavior Prediction: Avoiding Overly Confident Anticipation in Interactive Prediction", IROS, 2022.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9981524>paper</a> <a href=https://arxiv.org/pdf/2204.08665.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
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
<summary><em>Tang et al., "Collaborative Uncertainty in Multi-Agent Trajectory Forecasting", NeurIPS, 2021.</em> <a href=https://papers.nips.cc/paper/2021/file/31ca0ca71184bbdb3de7b20a51e88e90-Paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2110.13947.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#ed">ED</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#kld">KLD</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#l1">L1</a></li>
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
<summary><em>Zhu et al., "HalentNet: Multimodal Trajectory Forecasting with Hallucinative Intents", ICLR, 2021.</em> <a href=https://openreview.net/pdf?id=9GBZBPn0Jx>paper</a> <a href=https://github.com/Vision-CAIR/HalentNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Deyao_2021_ICLR,
    author = "Zhu, Deyao and Zahran, Mohamed and Li, Li Erran and Elhoseiny, Mohamed",
    booktitle = "ICLR",
    title = "{HalentNet}: Multimodal Trajectory Forecasting with Hallucinative Intents",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Bhattacharyya et al., "Euro-PVI: Pedestrian Vehicle Interactions in Dense Urban Centers", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Bhattacharyya_Euro-PVI_Pedestrian_Vehicle_Interactions_in_Dense_Urban_Centers_CVPR_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#euro-pvi">Euro-PVI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bhattacharyya_2021_CVPR,
    author = "Bhattacharyya, Apratim and Reino, Daniel Olmeda and Fritz, Mario and Schiele, Bernt",
    title = "{Euro-PVI}: Pedestrian Vehicle Interactions in Dense Urban Centers",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Kim et al., "LaPred: Lane-Aware Prediction of Multi-Modal Future Trajectories of Dynamic Agents", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Kim_LaPred_Lane-Aware_Prediction_of_Multi-Modal_Future_Trajectories_of_Dynamic_Agents_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2104.00249.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kim_2021_CVPR,
    author = "Kim, ByeoungDo and Park, Seong Hyeon and Lee, Seokhwan and Khoshimjonov, Elbek and Kum, Dongsuk and Kim, Junsoo and Kim, Jeong Soo and Choi, Jun Won",
    title = "{LaPred}: Lane-Aware Prediction of Multi-Modal Future Trajectories of Dynamic Agents",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Narayanan et al., "Divide-and-Conquer for Lane-Aware Diverse Trajectory Prediction", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Narayanan_Divide-and-Conquer_for_Lane-Aware_Diverse_Trajectory_Prediction_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2104.08277.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cpi">CPI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mr">MR</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#orr">ORR</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#emd">EMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Narayanan_2021_CVPR,
    author = "Narayanan, Sriram and Moslemi, Ramin and Pittaluga, Francesco and Liu, Buyu and Chandraker, Manmohan",
    title = "Divide-and-Conquer for Lane-Aware Diverse Trajectory Prediction",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ma et al., "Likelihood-Based Diverse Sampling for Trajectory Forecasting", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Jason_Likelihood-Based_Diverse_Sampling_for_Trajectory_Forecasting_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2011.15084.pdf>arxiv</a> <a href=https://github.com/JasonMa2016/LDS>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfsd">minFSD</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minasd">minASD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ma_2021_ICCV,
    author = "Ma, Yecheng Jason and Inala, Jeevana Priya and Jayaraman, Dinesh and Bastani, Osbert",
    title = "Likelihood-Based Diverse Sampling for Trajectory Forecasting",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Makansi et al., "On Exposing the Challenging Long Tail in Future Prediction of Traffic Actors", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Makansi_On_Exposing_the_Challenging_Long_Tail_in_Future_Prediction_of_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2103.12474.pdf>arxiv</a> <a href=https://github.com/lmb-freiburg/Contrastive-Future-Trajectory-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Makansi_2021_ICCV,
    author = "Makansi, Osama and Cicek, Ozgun and Marrakchi, Yassine and Brox, Thomas",
    title = "On Exposing the Challenging Long Tail in Future Prediction of Traffic Actors",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ren et al., "Safety-Aware Motion Prediction With Unseen Vehicles for Autonomous Driving", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Ren_Safety-Aware_Motion_Prediction_With_Unseen_Vehicles_for_Autonomous_Driving_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2109.01510.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mr">MR</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#ur">UR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ren_2021_ICCV,
    author = "Ren, Xuanchi and Yang, Tao and Li, Li Erran and Alahi, Alexandre and Chen, Qifeng",
    title = "Safety-Aware Motion Prediction With Unseen Vehicles for Autonomous Driving",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yuan et al., "AgentFormer: Agent-Aware Transformers for Socio-Temporal Multi-Agent Forecasting", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Yuan_AgentFormer_Agent-Aware_Transformers_for_Socio-Temporal_Multi-Agent_Forecasting_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2103.14023.pdf>arxiv</a> <a href=https://github.com/Khrylx/AgentFormer>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yuan_2021_ICCV,
    author = "Yuan, Ye and Weng, Xinshuo and Ou, Yanglan and Kitani, Kris M.",
    title = "{AgentFormer}: Agent-Aware Transformers for Socio-Temporal Multi-Agent Forecasting",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zheng et al., "Unlimited Neighborhood Interaction for Heterogeneous Trajectory Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Zheng_Unlimited_Neighborhood_Interaction_for_Heterogeneous_Trajectory_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2108.00238.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<summary><em>Li et al., "RAIN: Reinforced Hybrid Attention Inference Network for Motion Forecasting", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Li_RAIN_Reinforced_Hybrid_Attention_Inference_Network_for_Motion_Forecasting_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2108.01316.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mr">MR</a></li>
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
<summary><em>Berkemeyer et al., "Feasible and Adaptive Multimodal Trajectory Prediction with Semantic Maneuver Fusion", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561380>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mr">MR</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#orr">ORR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Berkemeyer_2021_ICRA,
    author = "Berkemeyer, Hendrik and Franceschini, Riccardo and Tran, Tuan and Che, Lin and Pipa, Gordon",
    booktitle = "ICRA",
    title = "Feasible and Adaptive Multimodal Trajectory Prediction with Semantic Maneuver Fusion",
    year = "2021"
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
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
<summary><em>Dulian et al., "Exploiting Latent Representation of Sparse Semantic Layers for Improved Short-term Motion Prediction with Capsule Networks", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561467>paper</a> <a href=https://arxiv.org/pdf/2103.01644.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<summary><em>Li et al., "A Scalable Approach to Predict Multi-Agent Motion for Human-Robot Collaboration", RAL, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9366373>paper</a> <a href=https://dspace.mit.edu/bitstream/handle/1721.1/135520/ICRA_2021_final_version2-1.pdf?sequence=2&isAllowed=y>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#maxd">MaxD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Li_2021_RAL,
    author = "Li, Xiao and Rosman, Guy and Gilitschenski, Igor and Vasile, Cristian-Ioan and DeCastro, Jonathan A. and Karaman, Sertac and Rus, Daniela",
    journal = "RAL",
    title = "A Scalable Approach to Predict Multi-Agent Motion for Human-Robot Collaboration",
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
<summary><em>Kumar et al., "Interaction-Based Trajectory Prediction Over a Hybrid Traffic Graph", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636143>paper</a> <a href=https://arxiv.org/pdf/2009.12916.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#tcr">TCR</a></li>
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
<summary><em>Laddha et al., "RV-FuseNet: Range View Based Fusion of Time-Series LiDAR Data for Joint 3D Object Detection and Motion Forecasting", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636083>paper</a> <a href=https://arxiv.org/pdf/2005.10863.pdf?ref=https://githubhelp.com>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Laddha_2021_IROS,
    author = "Laddha, Ankit and Gautam, Shivam and Meyer, Gregory P. and Vallespi-Gonzalez, Carlos and Wellington, Carl K.",
    booktitle = "IROS",
    title = "{RV-FuseNet}: Range View Based Fusion of Time-Series {LiDAR} Data for Joint {3D} Object Detection and Motion Forecasting",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Su et al., "Temporally-Continuous Probabilistic Prediction using Polynomial Trajectory Parameterization", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636751>paper</a> <a href=https://arxiv.org/pdf/2011.00399.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#ed">ED</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mane">MAnE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Su_2021_IROS_2,
    author = "Su, Zhaoen and Wang, Chao and Cui, Henggang and Djuric, Nemanja and Vallespi-Gonzalez, Carlos and Bradley, David",
    booktitle = "IROS",
    title = "Temporally-Continuous Probabilistic Prediction using Polynomial Trajectory Parameterization",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Deo et al., "Multimodal Trajectory Prediction Conditioned on Lane-Graph Traversals", CoRL, 2021.</em> <a href=https://openreview.net/pdf?id=hu7b7MPCqiC>paper</a> <a href=https://arxiv.org/pdf/2106.15004.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mr">MR</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#orr">ORR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Deo_2021_CoRL,
    author = "Deo, Nachiket and Wolff, Eric and Beijbom, Oscar",
    title = "Multimodal Trajectory Prediction Conditioned on Lane-Graph Traversals",
    booktitle = "CoRL",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhu et al., "Motion Forecasting with Unlikelihood Training in Continuous Space", CoRL, 2021.</em> <a href=https://openreview.net/pdf?id=4u25M570Iji>paper</a> <a href=https://github.com/Vision-CAIR/UnlikelihoodMotionForecasting>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#orr">ORR</a></li>
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
<summary><em>Kawasaki et al., "Multimodal Trajectory Predictions for Autonomous Driving Without a Detailed Prior Map", WACV, 2021.</em> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Kawasaki_Multimodal_Trajectory_Predictions_for_Autonomous_Driving_Without_a_Detailed_Prior_WACV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kawasaki_2021_WACV,
    author = "Kawasaki, Atsushi and Seki, Akihito",
    title = "Multimodal Trajectory Predictions for Autonomous Driving Without a Detailed Prior Map",
    booktitle = "WACV",
    year = "2021"
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<summary><em>Hu et al., "Collaborative Motion Prediction via Neural Motion Message Passing", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Hu_Collaborative_Motion_Prediction_via_Neural_Motion_Message_Passing_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.06594.pdf>arxiv</a> <a href=https://github.com/PhyllisH/NMMP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<summary><em>Liang et al., "PnPNet: End-to-End Perception and Prediction With Tracking in the Loop", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Liang_PnPNet_End-to-End_Perception_and_Prediction_With_Tracking_in_the_Loop_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.14711.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<summary><em>Makansi et al., "Multimodal Future Localization and Emergence Prediction for Objects in Egocentric View With a Reachability Prior", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Makansi_Multimodal_Future_Localization_and_Emergence_Prediction_for_Objects_in_Egocentric_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.04700.pdf>arxiv</a> <a href=https://github.com/lmb-freiburg/FLN-EPN-RPN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#fit">FIT</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mapillary_vistas">Mapillary Vistas</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#nll">NLL</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#iou">IoU</a></li>
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
<summary><em>Phan-Minh et al., "CoverNet: Multimodal Behavior Prediction Using Trajectory Sets", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Phan-Minh_CoverNet_Multimodal_Behavior_Prediction_Using_Trajectory_Sets_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.10298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Phan-Minh_2020_CVPR,
    author = "Phan-Minh, Tung and Grigore, Elena Corina and Boulton, Freddy A. and Beijbom, Oscar and Wolff, Eric M.",
    title = "{CoverNet}: Multimodal Behavior Prediction Using Trajectory Sets",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wu et al., "MotionNet: Joint Perception and Motion Prediction for Autonomous Driving Based on Bird's Eye View Maps", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Wu_MotionNet_Joint_Perception_and_Motion_Prediction_for_Autonomous_Driving_Based_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.06754.pdf>arxiv</a> <a href=https://www.merl.com/research/license#MotionNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<summary><em>Casas et al., "Implicit Latent Variable Model for Scene-consistent Motion Forecasting", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123680613.pdf>paper</a> <a href=https://arxiv.org/pdf/2007.12036.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minsfde">minSFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minsade">minSADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#scr">SCR</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#meansfde">meanSFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#meansade">meanSADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Casas_2020_ECCV,
    author = "Casas, Sergio and Gulino, Cole and Suo, Simon and Luo, Katie and Liao, Renjie and Urtasun, Raquel",
    title = "Implicit Latent Variable Model for Scene-consistent Motion Forecasting",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Park et al., "Diverse and Admissible Trajectory Forecasting through Multimodal Context Understanding", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123560273.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.03212.pdf>arxiv</a> <a href=https://github.com/kami93/CMU-DATF>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#meanfde">meanFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#meanade">meanADE</a></li>
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
<summary><em>Salzmann et al., "Trajectron++: Multi-agent Generative Trajectory Forecasting with Heterogeneous Data for Control", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123630664.pdf>paper</a> <a href=https://arxiv.org/pdf/2001.03093.pdf>arxiv</a> <a href=https://github.com/StanfordASL/Trajectron-plus-plus>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#nll">NLL</a></li>
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
<summary><em>Wong et al., "Testing the Safety of Self-driving Vehicles by Simulating Perception and Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123710307.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.06020.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<summary><em>Casas et al., "SpAGNN: Spatially-Aware Graph Neural Networks for Relational Behavior Forecasting from Sensor Data", ICRA, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9196697>paper</a> <a href=https://arxiv.org/pdf/1910.08233.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Casas_2020_ICRA,
    author = "Casas, S. and Gulino, C. and Liao, R. and Urtasun, R.",
    booktitle = "ICRA",
    title = "{SpAGNN}: Spatially-Aware Graph Neural Networks for Relational Behavior Forecasting from Sensor Data",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Casas et al., "The Importance of Prior Knowledge in Precise Multimodal Prediction", IROS, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9341199>paper</a> <a href=https://arxiv.org/pdf/2006.02636.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fle">FLE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Casas_2020_IROS,
    author = "Casas, S. and Gulino, C. and Suo, S. and Urtasun, R.",
    booktitle = "IROS",
    title = "The Importance of Prior Knowledge in Precise Multimodal Prediction",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Li et al., "End-to-end Contextual Perception and Prediction with Interaction Transformer", IROS, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9341392>paper</a> <a href=https://arxiv.org/pdf/2008.05927.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#tcr">TCR</a></li>
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
<summary><em>Meyer et al., "LaserFlow: Efficient and Probabilistic Object Detection and Motion Forecasting", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9310205>paper</a> <a href=https://arxiv.org/pdf/2003.05982.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#l2">L2</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Meyer_2020_RAL,
    author = "Meyer, Gregory P. and Charland, Jake and Pandey, Shreyash and Laddha, Ankit and Gautam, Shivam and Vallespi-Gonzalez, Carlos and Wellington, Carl K.",
    journal = "RAL",
    title = "{LaserFlow}: Efficient and Probabilistic Object Detection and Motion Forecasting",
    year = "2020",
    volume = "6",
    number = "2",
    pages = "526-533"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Buhet et al., "PLOP: Probabilistic PoLynomial Objects Trajectory Planning for Autonomous Driving", CoRL, 2020.</em> <a href=https://proceedings.mlr.press/v155/buhet21a/buhet21a.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.08744.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#a2d2">A2D2</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minmsd">minMSD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Buhet_2020_CORL,
    author = "Buhet, Thibault and Wirbel, Emilie and Bursuc, Andrei and Perrotton, Xavier",
    title = "{PLOP}: Probabilistic PoLynomial Objects Trajectory Planning for Autonomous Driving",
    booktitle = "CoRL",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ivanovic et al., "MATS: An Interpretable Trajectory Forecasting Representation for Planning and Control", CoRL, 2020.</em> <a href=https://proceedings.mlr.press/v155/ivanovic21a/ivanovic21a.pdf>paper</a> <a href=https://arxiv.org/pdf/2009.07517.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ivanovic_2020_CORL,
    author = "Ivanovic, Boris and Elhafsi, Amine and Rosman, Guy and Gaidon, Adrien and Pavone, Marco",
    title = "{MATS}: An Interpretable Trajectory Forecasting Representation for Planning and Control",
    booktitle = "CoRL",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Li et al., "Differentiable Logic Layer for Rule Guided Trajectory Prediction", CoRL, 2020.</em> <a href=https://proceedings.mlr.press/v155/li21b/li21b.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#maxd">MaxD</a></li>
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
<summary><em>Shah et al., "LiRaNet: End-to-End Trajectory Prediction using Spatio-Temporal Radar Fusion", CoRL, 2020.</em> <a href=https://proceedings.mlr.press/v155/shah21a/shah21a.pdf>paper</a> <a href=https://arxiv.org/pdf/2010.00731.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<summary><em>Zhang et al., "Map-Adaptive Goal-Based Trajectory Prediction", CoRL, 2020.</em> <a href=https://proceedings.mlr.press/v155/zhang21a/zhang21a.pdf>paper</a> <a href=https://arxiv.org/pdf/2009.04450.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2020_CORL,
    author = "Zhang, Lingyao and Su, Po-Hsun and Hoang, Jerrick and Haynes, Galen Clark and Marchetti-Bowick, Micol",
    title = "Map-Adaptive Goal-Based Trajectory Prediction",
    booktitle = "CoRL",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Rhinehart et al., "Precog: Prediction Conditioned On Goals In Visual Multi-Agent Settings", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rhinehart_PRECOG_PREdiction_Conditioned_on_Goals_in_Visual_Multi-Agent_Settings_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.01296.pdf>arxiv</a> <a href=https://sites.google.com/view/precog>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minmsd">minMSD</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#meanmsd">meanMSD</a></li>
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
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_a-d_datasets.md#absrel">AbsRel</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_j-z_datasets.md#l1">L1</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_j-z_datasets.md#nfe">NFE</a></li>
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
<summary><em>Li et al., "Weakly Supervised Class-Agnostic Motion Prediction for Autonomous Driving", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Weakly_Supervised_Class-Agnostic_Motion_Prediction_for_Autonomous_Driving_CVPR_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_j-z_datasets.md#l2">L2</a></li>
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
<summary><em>Akan et al., "StretchBEV: Stretching Future Instance Prediction Spatially and Temporally", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136980436.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.13641.pdf>arxiv</a> <a href=https://kuis-ai.github.io/stretchbev/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_e-i_datasets.md#iou">IoU</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_j-z_datasets.md#vpq">VPQ</a></li>
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
<details close>
<summary><em>Khurana et al., "Differentiable Raycasting for Self-Supervised Occupancy Forecasting", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136980349.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.01917.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#once">ONCE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_a-d_datasets.md#cross-entropy">Cross-entropy</a></li>
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
<summary><em>Weng et al., "S2Net: Stochastic Sequential Pointcloud Forecasting", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136870541.pdf>paper</a> <a href=https://www.xinshuoweng.com/projects/S2Net>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_a-d_datasets.md#cd">CD</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_e-i_datasets.md#emd">EMD</a></li>
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
<summary><em>Hu et al., "Safe Local Motion Planning With Self-Supervised Freespace Forecasting", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Hu_Safe_Local_Motion_Planning_With_Self-Supervised_Freespace_Forecasting_CVPR_2021_paper.pdf>paper</a> <a href=https://github.com/peiyunh/ff>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_a-d_datasets.md#ap">AP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2021_CVPR,
    author = "Hu, Peiyun and Huang, Aaron and Dolan, John and Held, David and Ramanan, Deva",
    title = "Safe Local Motion Planning With Self-Supervised Freespace Forecasting",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Hu et al., "FIERY: Future Instance Prediction in Bird's-Eye View From Surround Monocular Cameras", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Hu_FIERY_Future_Instance_Prediction_in_Birds-Eye_View_From_Surround_Monocular_ICCV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_e-i_datasets.md#iou">IoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2021_ICCV,
    author = "Hu, Anthony and Murez, Zak and Mohan, Nikhil and Dudas, Sofia and Hawke, Jeffrey and Badrinarayanan, Vijay and Cipolla, Roberto and Kendall, Alex",
    title = "{FIERY}: Future Instance Prediction in Bird's-Eye View From Surround Monocular Cameras",
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
@InProceedings{Caesar_2020_CVPR,
    author = "Caesar, Holger and Bankiti, Varun and Lang, Alex H. and Vora, Sourabh and Liong, Venice Erin and Xu, Qiang and Krishnan, Anush and Pan, Yu and Baldan, Giancarlo and Beijbom, Oscar",
    title = "{nuScenes}: A Multimodal Dataset for Autonomous Driving",
    booktitle = "CVPR",
    year = "2020"
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
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a>, <a href=../../papers/action/action_papers.md#top>Action prediction<application></a>, <a href=../../papers/motion/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#rt">RT</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_e-i_datasets.md#fid">FID</a></li>
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
<summary><em>Ho et al., "Deep Video Prediction Through Sparse Motion Regularization", ICIP, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9191154>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#yuv">YUV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ho_2020_ICIP,
    author = "Ho, Yung-Han and Chan, Chih-Chun and Peng, Wen-Hsiao",
    booktitle = "ICIP",
    title = "Deep Video Prediction Through Sparse Motion Regularization",
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<summary><em>Ho et al., "SME-Net: Sparse Motion Estimation For Parametric Video Prediction Through Reinforcement Learning", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ho_SME-Net_Sparse_Motion_Estimation_for_Parametric_Video_Prediction_Through_Reinforcement_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#yuv">YUV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ho_2019_ICCV,
    author = "Ho, Yung-Han and Cho, Chuan-Yuan and Peng, Wen-Hsiao and Jin, Guo-Lun",
    title = "{SME-Net}: Sparse Motion Estimation For Parametric Video Prediction Through Reinforcement Learning",
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sports-1m">Sports-1M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#visor">ViSOR</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#prost">PROST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<summary><em>Walker et al., "The Pose Knows: Video Forecasting By Generating Pose Futures", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Walker_The_Pose_Knows_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.00053.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_e-i_datasets.md#is">IS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mmd">MMD</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<summary><em>Stergiou et al., "The Wisdom of Crowds: Temporal Progressive Attention for Early Action Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Stergiou_The_Wisdom_of_Crowds_Temporal_Progressive_Attention_for_Early_Action_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.13340.pdf>arxiv</a> <a href=https://alexandrosstergiou.github.io/project_pages/TemPr/index.html>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#smtsmt">SmtSmt</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Stergiou_2023_CVPR,
    author = "Stergiou, Alexandros and Damen, Dima",
    title = "The Wisdom of Crowds: Temporal Progressive Attention for Early Action Prediction",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Foo et al., "ERA: Expert Retrieval and Assembly for Early Action Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940657.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.09675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Foo_2022_ECCV,
    author = "Foo, Lin Geng and Li, Tianjiao and Rahmani, Hossein and Ke, Qiuhong and Liu, Jun",
    title = "{ERA}: Expert Retrieval and Assembly for Early Action Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Fernando et al., "Anticipating Human Actions by Correlating Past With the Future With Jaccard Similarity Measures", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Fernando_Anticipating_Human_Actions_by_Correlating_Past_With_the_Future_With_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2105.12414.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Fernando_2021_CVPR,
    author = "Fernando, Basura and Herath, Samitha",
    title = "Anticipating Human Actions by Correlating Past With the Future With Jaccard Similarity Measures",
    booktitle = "CVPR",
    year = "2021"
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uti">UTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jhmdb">JHMDB</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#willow_action">Willow Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wider">WIDER</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#stanford-40">Stanford-40</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bu_action">BU Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uti">UTI</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<summary><em>Shi et al., "Action Anticipation With RBF Kernelized Feature Mapping RNN", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yuge_Shi_Action_Anticipation_with_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.07806.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uti">UTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shi_2018_ECCV,
    author = "Shi, Yuge and Fernando, Basura and Hartley, Richard",
    title = "Action Anticipation With {RBF} Kernelized Feature Mapping {RNN}",
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#hmdb">HMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bit">BIT</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<summary><em>Sadegh et al., "Encouraging LSTMs To Anticipate Actions Very Early", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Aliakbarian_Encouraging_LSTMs_to_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uti">UTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Aliakbarian_2017_ICCV,
    author = "Sadegh Aliakbarian, Mohammad and Sadat Saleh, Fatemeh and Salzmann, Mathieu and Fernando, Basura and Petersson, Lars and Andersson, Lars",
    title = "Encouraging {LSTM}s To Anticipate Actions Very Early",
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uti">UTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_a-d_datasets.md#accuracy">Accuracy</a></li>
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
@Article{Soomro_2012_arxiv,
    author = "Soomro, Khurram and Zamir, Amir Roshan and Shah, Mubarak",
    title = "{UCF101}: A Dataset Of 101 Human Actions Classes From Videos In The Wild",
    journal = "arXiv:1212.0402",
    year = "2012"
}
</pre>
</details>

</ul></details>
<a name=ngsim></a>
<details close>
<summary><l style="font-size:20px"><strong>Next Generation Simulation (NGSIM)</strong></l> <a href=https://catalog.data.gov/dataset/next-generation-simulation-ngsim-vehicle-trajectories>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of vehicle trajectories containing 10K+ frames of recording
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a>, <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Map, trajectory</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Berlati et al., "Ambiguity in Sequential Data: Predicting Uncertain Futures With Recurrent Models", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9001185>paper</a> <a href=https://arxiv.org/pdf/2003.10381.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
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
<summary><em>Ding et al., "Predicting Vehicle Behaviors Over An Extended Horizon Using Behavior Interaction Network", ICRA, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8794146>paper</a> <a href=https://arxiv.org/pdf/1903.00848.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#ttm">TTM</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<summary><em>Zhang et al., "On Adversarial Robustness of Trajectory Prediction for Autonomous Vehicles", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_On_Adversarial_Robustness_of_Trajectory_Prediction_for_Autonomous_Vehicles_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2201.05057.pdf>arxiv</a> <a href=https://github.com/zqzqz/AdvTrajectoryPrediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2022_CVPR,
    author = "Zhang, Qingzhao and Hu, Shengtuo and Sun, Jiachen and Chen, Qi Alfred and Mao, Z. Morley",
    title = "On Adversarial Robustness of Trajectory Prediction for Autonomous Vehicles",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Antonello et al., "Flash: Fast and Light Motion Prediction for Autonomous Driving with Bayesian Inverse Planning and Learned Motion Profiles", IROS, 2022.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9981347>paper</a> <a href=https://arxiv.org/pdf/2203.08251.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Antonello_2022_IROS,
    author = "Antonello, Morris and Dobre, Mihai and Albrecht, Stefano V and Redford, John and Ramamoorthy, Subramanian",
    booktitle = "IROS",
    title = "Flash: Fast and Light Motion Prediction for Autonomous Driving with Bayesian Inverse Planning and Learned Motion Profiles",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Banijamali et al., "Prediction by Anticipation: An Action-Conditional Prediction Method Based on Interaction Learning", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Banijamali_Prediction_by_Anticipation_An_Action-Conditional_Prediction_Method_Based_on_Interaction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2012.13478.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#tn">TN</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#tp">TP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Banijamali_2021_ICCV,
    author = "Banijamali, Ershad and Rohani, Mohsen and Amirloo, Elmira and Luo, Jun and Poupart, Pascal",
    title = "Prediction by Anticipation: An Action-Conditional Prediction Method Based on Interaction Learning",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xie et al., "Congestion-aware Multi-agent Trajectory Prediction for Collision Avoidance", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9560994>paper</a> <a href=https://arxiv.org/pdf/2103.14231.pdf>arxiv</a> <a href=https://github.com/xuxie1031/CollisionFreeMultiAgentTrajectoryPrediciton>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#rmse">RMSE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#tcr">TCR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xie_2021_ICRA,
    author = "Xie, Xu and Zhang, Chi and Zhu, Yixin and Wu, Ying Nian and Zhu, Song-Chun",
    booktitle = "ICRA",
    title = "Congestion-aware Multi-agent Trajectory Prediction for Collision Avoidance",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Anderson et al., "A Kinematic Model for Trajectory Prediction in General Highway Scenarios", RAL, 2021.</em> <a href=https://ieeexplore.ieee.org/document/9472993>paper</a> <a href=https://arxiv.org/pdf/2103.16673.pdf>arxiv</a> <a href=https://github.com/umautobots/kinematic_highway>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#rmse">RMSE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#qde">QDE</a></li>
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
<summary><em>Xu et al., "Tra2Tra: Trajectory-to-Trajectory Prediction With a Global Social Spatial-Temporal Attentive Neural Network", RAL, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9347678>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#charges">Charges</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#rmse">RMSE</a></li>
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
<summary><em>Mersch et al., "Maneuver-based Trajectory Prediction for Self-driving Cars Using Spatio-temporal Convolutional Networks", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636875>paper</a> <a href=https://arxiv.org/pdf/2109.07365.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mersch_2021_IROS,
    author = "Mersch, Benedikt and Höllen, Thomas and Zhao, Kun and Stachniss, Cyrill and Roscher, Ribana",
    booktitle = "IROS",
    title = "Maneuver-based Trajectory Prediction for Self-driving Cars Using Spatio-temporal Convolutional Networks",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Song et al., "PiP: Planning-informed Trajectory Prediction for Autonomous Driving", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660596.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.11476.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#nll">NLL</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Song_2020_ECCV,
    author = "Song, Haoran and Ding, Wenchao and Chen, Yuxuan and Shen, Shaojie and Wang, Michael Yu and Chen, Qifeng",
    title = "{PiP}: Planning-informed Trajectory Prediction for Autonomous Driving",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Kamra et al., "Multi-agent Trajectory Prediction with Fuzzy Query Attention", NeurIPS, 2020.</em> <a href=https://papers.nips.cc/paper/2020/file/fe87435d12ef7642af67d9bc82a8b3cd-Paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2010.15891.pdf>arxiv</a> <a href=https://github.com/nitinkamra1992/FQA>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#charges">Charges</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kamra_2020_NeurIPS,
    author = "Kamra, Nitin and Zhu, Hao and Trivedi, Dweep Kumarbhai and Zhang, Ming and Liu, Yan",
    editor = "Larochelle, H. and Ranzato, M. and Hadsell, R. and Balcan, M. F. and Lin, H.",
    booktitle = "NeurIPS",
    title = "Multi-agent Trajectory Prediction with Fuzzy Query Attention",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Mercat et al., "Multi-Head Attention for Multi-Modal Joint Vehicle Motion Forecasting", ICRA, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9197340>paper</a> <a href=https://arxiv.org/pdf/1910.03650.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mr">MR</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#nll">NLL</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mercat_2020_ICRA,
    author = "Mercat, J. and Gilles, T. and Zoghby, N. El and Sandou, G. and Beauvois, D. and Gil, G. P.",
    booktitle = "ICRA",
    title = "Multi-Head Attention for Multi-Modal Joint Vehicle Motion Forecasting",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Mukherjee et al., "Interacting Vehicle Trajectory Prediction with Convolutional Recurrent Neural Networks", ICRA, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9196807>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mukherjee_2020_ICRA,
    author = "Mukherjee, S. and Wang, S. and Wallace, A.",
    booktitle = "ICRA",
    title = "Interacting Vehicle Trajectory Prediction with Convolutional Recurrent Neural Networks",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>He et al., "UST: Unifying Spatio-Temporal Context for Trajectory Prediction in Autonomous Driving", IROS, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9340943>paper</a> <a href=https://arxiv.org/pdf/2005.02790.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{He_2020_IROS,
    author = "He, H. and Dai, H. and Wang, N.",
    booktitle = "IROS",
    title = "UST: Unifying Spatio-Temporal Context for Trajectory Prediction in Autonomous Driving",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Jeon et al., "SCALE-Net: Scalable Vehicle Trajectory Prediction Network under Random Number of Interacting Vehicles via Edge-enhanced Graph Convolutional Neural Network", IROS, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9341288>paper</a> <a href=https://arxiv.org/pdf/2002.12609.pdf>arxiv</a> <a href=https://github.com/coolsunxu/Scale_Net>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jeon_2020_IROS,
    author = "Jeon, H. and Choi, J. and Kum, D.",
    booktitle = "IROS",
    title = "{SCALE-Net}: Scalable Vehicle Trajectory Prediction Network under Random Number of Interacting Vehicles via Edge-enhanced Graph Convolutional Neural Network",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Anderson et al., "Low Latency Trajectory Predictions for Interaction Aware Highway Driving", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9140336>paper</a> <a href=https://arxiv.org/pdf/1909.05227.pdf>arxiv</a> <a href=https://github.com/umautobots/low_latency_predictions>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Anderson_2020_RAL,
    author = "Anderson, C. and Vasudevan, R. and Johnson-Roberson, M.",
    journal = "RAL",
    title = "Low Latency Trajectory Predictions for Interaction Aware Highway Driving",
    year = "2020",
    volume = "5",
    number = "4",
    pages = "5456-5463"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chandra et al., "Forecasting Trajectory and Behavior of Road-Agents Using Spectral Clustering in Graph-LSTMs", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9126166>paper</a> <a href=https://arxiv.org/pdf/1912.01118.pdf>arxiv</a> <a href=https://github.com/rohanchandra30/Spectral-Trajectory-and-Behavior-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<summary><em>Chen et al., "ST-LSTM: Spatio-Temporal Graph Based Long Short-Term Memory Network For Vehicle Trajectory Prediction", ICIP, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9191332>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#nll">NLL</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2020_ICIP,
    author = "Chen, Guangxi and Hu, Ling and Zhang, Qieshi and Ren, Ziliang and Gao, Xiangyang and Cheng, Jun",
    booktitle = "ICIP",
    title = "{ST-LSTM}: Spatio-Temporal Graph Based Long Short-Term Memory Network For Vehicle Trajectory Prediction",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chandra et al., "TraPHic: Trajectory Prediction In Dense And Heterogeneous Traffic Using Weighted Interactions", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Chandra_TraPHic_Trajectory_Prediction_in_Dense_and_Heterogeneous_Traffic_Using_Weighted_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.04767.pdf>arxiv</a> <a href=https://go.umd.edu/TraPHic>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#traf">TRAF</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<summary><em>Zhao et al., "Multi-Agent Tensor Fusion For Contextual Trajectory Prediction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhao_Multi-Agent_Tensor_Fusion_for_Contextual_Trajectory_Prediction_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.04776.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#rmse">RMSE</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#ll">LL</a></li>
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
<summary><em>Tang et al., "Multiple futures prediction", NeurIPS, 2019.</em> <a href=https://proceedings.neurips.cc/paper/2019/file/86a1fa88adb5c33bd7a68ac2f9f3f96b-Paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#nll">NLL</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#rmse">RMSE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minmde">minMDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tang_2019_NeurIPS,
    author = "Tang, Charlie and Salakhutdinov, Russ R",
    title = "Multiple futures prediction",
    booktitle = "NeurIPS",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Henaff et al., "Model-Predictive Policy Learning with Uncertainty Regularization for Driving in Dense Traffic", ICLR, 2019.</em> <a href=https://openreview.net/pdf?id=HygQBn0cYm>paper</a> <a href=https://openreview.net/pdf?id=HygQBn0cYm>arxiv</a> <a href=https://github.com/atcold/pytorch-PPUU>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
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
<summary><em>Li et al., "Interaction-Aware Multi-Agent Tracking And Probabilistic Behavior Prediction Via Adversarial Learning", ICRA, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8793661>paper</a> <a href=https://arxiv.org/pdf/1904.02390.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#ll">LL</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#kld">KLD</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
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
<summary><em>Bhattacharyya et al., "Multi-Agent Imitation Learning for Driving Simulation", IROS, 2018.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8593758>paper</a> <a href=https://arxiv.org/pdf/1803.01044.pdf>arxiv</a> <a href=https://github.com/sisl/ngsim_env>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bhattacharyya_2018_IROS,
    author = "Bhattacharyya, Raunak P. and Phillips, Derek J. and Wulfe, Blake and Morton, Jeremy and Kuefler, Alex and Kochenderfer, Mykel J.",
    booktitle = "IROS",
    title = "Multi-Agent Imitation Learning for Driving Simulation",
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
@Misc{NGSIM_2007,
    author = "of Transporation, U.S. Department",
    Title = "Next Generation Simulation ({NGSIM})",
    HowPublished = "Online",
    accessed = "2019-11-29",
    year = "2007"
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a>, <a href=../../papers/motion/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Butepage et al., "Deep Representation Learning For Human Motion Prediction And Classification", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Butepage_Deep_Representation_Learning_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1702.07486.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<summary><em>Gao et al., "Decompose More and Aggregate Better: Two Closer Looks at Frequency Representation Learning for Human Motion Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Gao_Decompose_More_and_Aggregate_Better_Two_Closer_Looks_at_Frequency_CVPR_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Peng et al., "Trajectory-Aware Body Interaction Transformer for Multi-Person Pose Forecasting", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Peng_Trajectory-Aware_Body_Interaction_Transformer_for_Multi-Person_Pose_Forecasting_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2303.05095.pdf>arxiv</a> <a href=https://github.com/xiaogangpeng/TBIFormer>code</a></summary>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mape">MAPE</a></li>
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
<summary><em>Tanke et al., "Social Diffusion: Long-term Multiple Human Motion Anticipation", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Tanke_Social_Diffusion_Long-term_Multiple_Human_Motion_Anticipation_ICCV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mupots-3d">MuPoTS-3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Xu et al., "Joint-Relation Transformer for Multi-Person Motion Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Xu_Joint-Relation_Transformer_for_Multi-Person_Motion_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.04808.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/JRTransformer>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mupots-3d">MuPoTS-3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#vim">VIM</a></li>
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
<summary><em>Chen et al., "HumanMAC: Masked Motion Completion for Human Motion Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_HumanMAC_Masked_Motion_Completion_for_Human_Motion_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2302.03665.pdf>arxiv</a> <a href=https://lhchen.top/Human-MAC/>code</a></summary>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#apd">APD</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mmade">MMADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mmfde">MMFDE</a></li>
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
<summary><em>Xu et al., "Auxiliary Tasks Benefit 3D Skeleton-based Human Motion Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Xu_Auxiliary_Tasks_Benefit_3D_Skeleton-based_Human_Motion_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.08942.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/AuxFormer>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Ma et al., "Progressively Generating Better Initial Guesses Towards Next Stages for High-Quality Human Motion Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Ma_Progressively_Generating_Better_Initial_Guesses_Towards_Next_Stages_for_High-Quality_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.16051.pdf>arxiv</a> <a href=https://github.com/705062791/PGBIG>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<summary><em>Li et al., "Skeleton-Parted Graph Scattering Networks for 3D Human Motion Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136660018.pdf>paper</a> <a href=https://arxiv.org/pdf/2208.00368.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/SPGSN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<summary><em>Sun et al., "Overlooked Poses Actually Make Sense: Distilling Privileged Knowledge for Human Motion Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136650668.pdf>paper</a> <a href=https://arxiv.org/pdf/2208.01302.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<summary><em>Wang et al., "Multi-Person 3D Motion Prediction with Multi-Range Transformers", NeurIPS, 2021.</em> <a href=https://papers.nips.cc/paper/2021/file/2fd5d41ec6cfab47e32164d5624269b1-Paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2111.12073.pdf>arxiv</a> <a href=https://github.com/jiashunwang/MRT>code</a></summary>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Cui et al., "Towards Accurate 3D Human Motion Prediction From Incomplete Observations", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Cui_Towards_Accurate_3D_Human_Motion_Prediction_From_Incomplete_Observations_CVPR_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Aliakbarian et al., "Contextually Plausible and Diverse 3D Human Motion Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Aliakbarian_Contextually_Plausible_and_Diverse_3D_Human_Motion_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.08521.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#kld">KLD</a></li>
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
<summary><em>Dang et al., "MSR-GCN: Multi-Scale Residual Graph Convolution Networks for Human Motion Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Dang_MSR-GCN_Multi-Scale_Residual_Graph_Convolution_Networks_for_Human_Motion_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://github.com/Droliven/MSRGCN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Liu et al., "Motion Prediction Using Trajectory Cues", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Liu_Motion_Prediction_Using_Trajectory_Cues_ICCV_2021_paper.pdf>paper</a> <a href=https://github.com/Pose-Group/MPT>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mouse_fish">Mouse Fish</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Li et al., "Directed Acyclic Graph Neural Network for Human Motion Prediction", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561540>paper</a> <a href=https://github.com/Qinli-zz/DA-GNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<summary><em>Zhang et al., "Non-local Graph Convolutional Network for Joint Activity Recognition and Motion Prediction", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636107>paper</a> <a href=https://arxiv.org/pdf/2108.01518.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<summary><em>Aliakbarian et al., "A Stochastic Conditioning Scheme for Diverse Human Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Aliakbarian_A_Stochastic_Conditioning_Scheme_for_Diverse_Human_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://github.com/mix-and-match/mix-and-match-tutorial>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#kld">KLD</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#si">SI</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#kl">KL</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#s-mse">S-MSE</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<summary><em>Cai et al., "Learning Progressive Joint Propagation for Human Motion Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520222.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<summary><em>Chao et al., "Adversarial Refinement Network for Human Motion Prediction", ACCV, 2020.</em> <a href=https://openaccess.thecvf.com/content/ACCV2020/papers/Chao_Adversarial_Refinement_Network_for_Human_Motion_Prediction_ACCV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2011.11221.pdf>arxiv</a> <a href=https://github.com/Xianjin111/ARNet-for-human-motion-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<details close>
<summary><em>Lebailly et al., "Motion Prediction Using Temporal Inception Module", ACCV, 2020.</em> <a href=https://openaccess.thecvf.com/content/ACCV2020/papers/Lebailly_Motion_Prediction_Using_Temporal_Inception_Module_ACCV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2010.03006.pdf>arxiv</a> <a href=https://github.com/tileb1/motion-prediction-tim>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Mao et al., "Learning Trajectory Dependencies For Human Motion Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Mao_Learning_Trajectory_Dependencies_for_Human_Motion_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.05436.pdf>arxiv</a> <a href=https://github.com/wei-mao-2019/LearnTrajDep>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#3dpw">3DPW</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
    title = "{CMU} Graphics Lab Motion Capture Database",
    howpublished = "http://mocap.cs.cmu.edu/",
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#l1">L1</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#l1">L1</a></li>
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
<summary><em>Song et al., "Pedestrian Intention Prediction Based on Traffic-Aware Scene Graph Model", IROS, 2022.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9981690>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#ap">AP</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#ap">AP</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#run_time">Run Time</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
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
<summary><em>Rasouli et al., "PedFormer: Pedestrian Behavior Prediction via Cross-Modal Attention Modulation and Gated Multitask Learning", ICRA, 2023.</em> <a href=https://ieeexplore.ieee.org/document/10161318>paper</a> <a href=https://arxiv.org/pdf/2210.07886.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fiou">FIoU</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#frb">FRB</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#arb">ARB</a></li>
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
<summary><em>Huynh et al., "Online Adaptive Temporal Memory With Certainty Estimation for Human Trajectory Prediction", WACV, 2023.</em> <a href=https://openaccess.thecvf.com/content/WACV2023/papers/Huynh_Online_Adaptive_Temporal_Memory_With_Certainty_Estimation_for_Human_Trajectory_WACV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<summary><em>Neumann et al., "Pedestrian and Ego-Vehicle Trajectory Prediction From Monocular Camera", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Neumann_Pedestrian_and_Ego-Vehicle_Trajectory_Prediction_From_Monocular_Camera_CVPR_2021_paper.pdf>paper</a> <a href=https://gitlab.com/lukeN86/pedFutureTracking>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<summary><em>Wang et al., "Stepwise Goal-Driven Networks for Trajectory Prediction", RAL, 2021.</em> <a href=https://ieeexplore.ieee.org/document/9691856>paper</a> <a href=https://arxiv.org/pdf/2103.14107.pdf>arxiv</a> <a href=https://github.com/ChuhuaW/SGNet.pytorch>code</a></summary>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fiou">FIoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Wang_2021_RAL_2,
    author = "Wang, Chuhua and Wang, Yuchen and Xu, Mingze and Crandall, David J.",
    journal = "RAL",
    title = "Stepwise Goal-Driven Networks for Trajectory Prediction",
    year = "2021",
    volume = "7",
    number = "2",
    pages = "2716-2723"
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#kde">KDE</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#rmse">RMSE</a></li>
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
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_j-z_datasets.md#psi">Psi</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_e-i_datasets.md#ism">ISM</a></li>
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
<a name=pie></a>
<details close>
<summary><l style="font-size:20px"><strong>Pedestrian Intention Estimation (PIE)</strong></l> <a href=http://data.nvision2.eecs.yorku.ca/PIE_dataset/>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of driving sequences with more than 6 hours of footage with 1.8K+ pedestrian tracks and 2.3M+ relevant traffic object bounding boxes annotated at 30fps
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a>, <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, object class, attribute, temporal segment, vehicle sensors, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Song et al., "Pedestrian Intention Prediction Based on Traffic-Aware Scene Graph Model", IROS, 2022.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9981690>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#ap">AP</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<summary><em>Rasouli et al., "Pedestrian Action Anticipation Using Contextual Feature Fusion In Stacked Rnns", BMVC, 2019.</em> <a href=https://bmvc2019.org/wp-content/uploads/papers/0283-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.06582.pdf>arxiv</a> <a href=https://github.com/aras62/SF-GRU>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<summary><em>Rasouli et al., "PedFormer: Pedestrian Behavior Prediction via Cross-Modal Attention Modulation and Gated Multitask Learning", ICRA, 2023.</em> <a href=https://ieeexplore.ieee.org/document/10161318>paper</a> <a href=https://arxiv.org/pdf/2210.07886.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fiou">FIoU</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#frb">FRB</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#arb">ARB</a></li>
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
<summary><em>Huynh et al., "Online Adaptive Temporal Memory With Certainty Estimation for Human Trajectory Prediction", WACV, 2023.</em> <a href=https://openaccess.thecvf.com/content/WACV2023/papers/Huynh_Online_Adaptive_Temporal_Memory_With_Certainty_Estimation_for_Human_Trajectory_WACV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<summary><em>Neumann et al., "Pedestrian and Ego-Vehicle Trajectory Prediction From Monocular Camera", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Neumann_Pedestrian_and_Ego-Vehicle_Trajectory_Prediction_From_Monocular_Camera_CVPR_2021_paper.pdf>paper</a> <a href=https://gitlab.com/lukeN86/pedFutureTracking>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<summary><em>Wang et al., "Stepwise Goal-Driven Networks for Trajectory Prediction", RAL, 2021.</em> <a href=https://ieeexplore.ieee.org/document/9691856>paper</a> <a href=https://arxiv.org/pdf/2103.14107.pdf>arxiv</a> <a href=https://github.com/ChuhuaW/SGNet.pytorch>code</a></summary>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fiou">FIoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Wang_2021_RAL_2,
    author = "Wang, Chuhua and Wang, Yuchen and Xu, Mingze and Crandall, David J.",
    journal = "RAL",
    title = "Stepwise Goal-Driven Networks for Trajectory Prediction",
    year = "2021",
    volume = "7",
    number = "2",
    pages = "2716-2723"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Kim et al., "Pedestrian Intention Prediction for Autonomous Driving Using a Multiple Stakeholder Perspective Model", IROS, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9341083>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kim_2020_IROS,
    author = "Kim, K. and Lee, Y. K. and Ahn, H. and Hahn, S. and Oh, S.",
    booktitle = "IROS",
    title = "Pedestrian Intention Prediction for Autonomous Driving Using a Multiple Stakeholder Perspective Model",
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Rasouli_2019_ICCV,
    author = "Rasouli, Amir and Kotseruba, Iuliia and Kunic, Toni and Tsotsos, John K.",
    title = "{PIE}: A Large-Scale Dataset And Models For Pedestrian Intention Estimation And Trajectory Prediction",
    booktitle = "ICCV",
    year = "2019"
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, audio, bounding box, object class, text, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Girase et al., "Latency Matters: Real-Time Action Forecasting Transformer", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Girase_Latency_Matters_Real-Time_Action_Forecasting_Transformer_CVPR_2023_paper.pdf>paper</a> <a href=https://karttikeya.github.io/publication/RAFTformer/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Girase_2023_CVPR,
    author = "Girase, Harshayu and Agarwal, Nakul and Choi, Chiho and Mangalam, Karttikeya",
    title = "Latency Matters: Real-Time Action Forecasting Transformer",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Stergiou et al., "The Wisdom of Crowds: Temporal Progressive Attention for Early Action Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Stergiou_The_Wisdom_of_Crowds_Temporal_Progressive_Attention_for_Early_Action_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.13340.pdf>arxiv</a> <a href=https://alexandrosstergiou.github.io/project_pages/TemPr/index.html>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#smtsmt">SmtSmt</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Stergiou_2023_CVPR,
    author = "Stergiou, Alexandros and Damen, Dima",
    title = "The Wisdom of Crowds: Temporal Progressive Attention for Early Action Prediction",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhong et al., "Anticipative Feature Fusion Transformer for Multi-Modal Action Anticipation", WACV, 2023.</em> <a href=https://openaccess.thecvf.com/content/WACV2023/papers/Zhong_Anticipative_Feature_Fusion_Transformer_for_Multi-Modal_Action_Anticipation_WACV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.12649.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhong_2023_WACV,
    author = "Zhong, Zeyun and Schneider, David and Voit, Michael and Stiefelhagen, Rainer and Beyerer, Jurgen",
    title = "Anticipative Feature Fusion Transformer for Multi-Modal Action Anticipation",
    booktitle = "WACV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liu et al., "A Hybrid Egocentric Activity Anticipation Framework via Memory-Augmented Recurrent and One-Shot Representation Forecasting", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_A_Hybrid_Egocentric_Activity_Anticipation_Framework_via_Memory-Augmented_Recurrent_and_CVPR_2022_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2022_CVPR_2,
    author = "Liu, Tianshan and Lam, Kin-Man",
    title = "A Hybrid Egocentric Activity Anticipation Framework via Memory-Augmented Recurrent and One-Shot Representation Forecasting",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Nawhal et al., "Rethinking Learning Approaches for Long-Term Action Anticipation", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940547.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.11566.pdf>arxiv</a> <a href=https://github.com/Nmegha2601/anticipatr>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
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
<details close>
<summary><em>Roy et al., "Action Anticipation Using Latent Goal Learning", WACV, 2022.</em> <a href=https://openaccess.thecvf.com/content/WACV2022/papers/Roy_Action_Anticipation_Using_Latent_Goal_Learning_WACV_2022_paper.pdf>paper</a> <a href=https://github.com/debadityaroy/LatentGoal>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Roy_2022_WACV,
    author = "Roy, Debaditya and Fernando, Basura",
    title = "Action Anticipation Using Latent Goal Learning",
    booktitle = "WACV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ke et al., "Future Moment Assessment for Action Query", WACV, 2021.</em> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Ke_Future_Moment_Assessment_for_Action_Query_WACV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#rmse">RMSE</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ke_2021_WACV,
    author = "Ke, Qiuhong and Fritz, Mario and Schiele, Bernt",
    title = "Future Moment Assessment for Action Query",
    booktitle = "WACV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liu et al., "Forecasting Human Object Interaction: Joint Prediction of Motor Attention and Actions in First Person Video", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460681.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.10967.pdf>arxiv</a> <a href=https://github.com/2020aptx4869lm/Forecasting-Human-Object-Interaction-in-FPV>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#kld">KLD</a></li>
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
<summary><em>Zhao et al., "On Diverse Asynchronous Activity Anticipation", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123740766.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhao_2020_ECCV,
    author = "Zhao, He and Wildes, Richard P.",
    title = "On Diverse Asynchronous Activity Anticipation",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ke et al., "Time-Conditioned Action Anticipation In One Shot", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Ke_Time-Conditioned_Action_Anticipation_in_One_Shot_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
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
<summary><em>Furnari et al., "What Would You Expect? Anticipating Egocentric Actions With Rolling-Unrolling LSTMs And Modality Attention", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Furnari_What_Would_You_Expect_Anticipating_Egocentric_Actions_With_Rolling-Unrolling_LSTMs_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.09035.pdf>arxiv</a> <a href=https://github.com/fpv-iplab/rulstm>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Furnari_2019_ICCV,
    author = "Furnari, Antonino and Farinella, Giovanni Maria",
    title = "What Would You Expect? Anticipating Egocentric Actions With Rolling-Unrolling {LSTMs} And Modality Attention",
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
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
<summary><em>Liu et al., "Joint Hand Motion and Interaction Hotspots Prediction From Egocentric Videos", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Joint_Hand_Motion_and_Interaction_Hotspots_Prediction_From_Egocentric_Videos_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.01696.pdf>arxiv</a> <a href=https://stevenlsw.github.io/hoi-forecast/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#auc">AUC</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#nss">NSS</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#ssim">SSIM</a></li>
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
<details close>
<summary><em>Jia et al., "Generative Adversarial Network for Future Hand Segmentation from Egocentric Video", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136730638.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.11305.pdf>arxiv</a> <a href=https://vjwq.github.io/EgoGAN/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_j-z_datasets.md#precision">Precision</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Damen_2018_ECCV,
    author = "Damen, Dima and Doughty, Hazel and Farinella, Giovanni Maria and Fidler, Sanja and Furnari, Antonino and Kazakos, Evangelos and Moltisanti, Davide and Munro, Jonathan and Perrett, Toby and Price, Will and Wray, Michael",
    title = "Scaling Egocentric Vision: The {EPIC-KITCHENS} Dataset",
    booktitle = "ECCV",
    year = "2018"
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
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a>, <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Gao et al., "SimVP: Simpler Yet Better Video Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Gao_SimVP_Simpler_Yet_Better_Video_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2206.05099.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#taxi_bj">Taxi BJ</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2022_CVPR,
    author = "Gao, Zhangyang and Tan, Cheng and Wu, Lirong and Li, Stan Z.",
    title = "{SimVP}: Simpler Yet Better Video Prediction",
    booktitle = "CVPR",
    year = "2022"
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<summary><em>Ho et al., "SME-Net: Sparse Motion Estimation For Parametric Video Prediction Through Reinforcement Learning", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ho_SME-Net_Sparse_Motion_Estimation_for_Parametric_Video_Prediction_Through_Reinforcement_ICCV_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#yuv">YUV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ho_2019_ICCV,
    author = "Ho, Yung-Han and Cho, Chuan-Yuan and Peng, Wen-Hsiao and Jin, Guo-Lun",
    title = "{SME-Net}: Sparse Motion Estimation For Parametric Video Prediction Through Reinforcement Learning",
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<summary><em>Reda et al., "SDC-Net: Video Prediction Using Spatially-Displaced Convolution", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Fitsum_Reda_SDC-Net_Video_prediction_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1811.00684.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#youtube-8m">Youtube-8M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#l1">L1</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Reda_2018_ECCV,
    author = "Reda, Fitsum A. and Liu, Guilin and Shih, Kevin J. and Kirby, Robert and Barker, Jon and Tarjan, David and Tao, Andrew and Catanzaro, Bryan",
    title = "{SDC-Net}: Video Prediction Using Spatially-Displaced Convolution",
    booktitle = "ECCV",
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<summary><em>Hariyono et al., "Estimation Of Collision Risk For Improving Driver's Safety", IECON, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7793743>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth_pedestrian">ETH Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#daimler">Daimler</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hariyono_2016_IES,
    author = "Hariyono, Joko and Shahbaz, Ajmal and Kurnianggoro, Laksono and Jo, Kang-Hyun",
    title = "Estimation Of Collision Risk For Improving Driver's Safety",
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
<a name=ntu_rgb-d></a>
<details close>
<summary><l style="font-size:20px"><strong>NTU RGB-D</strong></l> <a href=http://rose1.ntu.edu.sg/Datasets/actionRecognition.asp>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Shahroudy_NTU_RGBD_A_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1604.02808.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An action dataset of 60 daily activities in 56K+ video samples
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, IR, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Rupprecht et al., "Learning in an Uncertain World: Representing Ambiguity Through Multiple Hypotheses", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Rupprecht_Learning_in_an_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1612.00197.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#sharpness">Sharpness</a></li>
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
<details close>
<summary><em>Stergiou et al., "The Wisdom of Crowds: Temporal Progressive Attention for Early Action Prediction", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Stergiou_The_Wisdom_of_Crowds_Temporal_Progressive_Attention_for_Early_Action_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.13340.pdf>arxiv</a> <a href=https://alexandrosstergiou.github.io/project_pages/TemPr/index.html>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#smtsmt">SmtSmt</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Stergiou_2023_CVPR,
    author = "Stergiou, Alexandros and Damen, Dima",
    title = "The Wisdom of Crowds: Temporal Progressive Attention for Early Action Prediction",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Foo et al., "ERA: Expert Retrieval and Assembly for Early Action Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940657.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.09675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Foo_2022_ECCV,
    author = "Foo, Lin Geng and Li, Tianjiao and Rahmani, Hossein and Ke, Qiuhong and Liu, Jun",
    title = "{ERA}: Expert Retrieval and Assembly for Early Action Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Li et al., "HARD-Net: Hardness-AwaRe Discrimination Network for 3D Early Activity Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123560409.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#fpha">FPHA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2020_ECCV,
    author = "Li, Tianjiao and Liu, Jun and Zhang, Wei and Duan, Lingyu",
    title = "{HARD-Net}: Hardness-AwaRe Discrimination Network for {3D} Early Activity Prediction",
    booktitle = "ECCV",
    year = "2020"
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<summary><em>Mao et al., "Masked Motion Predictors are Strong 3D Action Representation Learners", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Mao_Masked_Motion_Predictors_are_Strong_3D_Action_Representation_Learners_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.07092.pdf>arxiv</a> <a href=https://github.com/maoyunyao/MAMP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pku-mmd">PKU-MMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mse">MSE</a></li>
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
<summary><em>Mao et al., "Weakly-Supervised Action Transition Learning for Stochastic Human Motion Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Mao_Weakly-Supervised_Action_Transition_Learning_for_Stochastic_Human_Motion_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://github.com/wei-mao-2019/WAT>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#grab">GRAB</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#babel">BABEL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_e-i_datasets.md#fid">FID</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#div">Div</a></li>
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
<summary><em>Zhang et al., "Non-local Graph Convolutional Network for Joint Activity Recognition and Motion Prediction", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636107>paper</a> <a href=https://arxiv.org/pdf/2108.01518.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<summary><em>Yasar et al., "A Scalable Approach to Predict Multi-Agent Motion for Human-Robot Collaboration", RAL, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9353218>paper</a></summary>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mse">MSE</a></li>
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
<summary><em>Adeli et al., "Socially and Contextually Aware Human Motion and Pose Forecasting", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9145701>paper</a> <a href=https://arxiv.org/pdf/2007.06843.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#posetrack">PoseTrack</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mse">MSE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Shahroudy_2016_CVPR,
    author = "Shahroudy, Amir and Liu, Jun and Ng, Tian-Tsong and Wang, Gang",
    title = "{NTU RGB+D}: A Large Scale Dataset For 3D Human Activity Analysis",
    booktitle = "CVPR",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=50salads></a>
<details close>
<summary><l style="font-size:20px"><strong>50Salads</strong></l> <a href=https://cvip.computing.dundee.ac.uk/datasets/foodpreparation/50salads/>link</a> <a href=https://dl.acm.org/doi/abs/10.1145/2493432.2493482>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 25 human subjects preparing 2 mixed salads each with 4h+ of annotated accelerometer and RGB-D video data recorded 50hz and 30hz respectively
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, activity label, temporal segment, accelerometer</li>
<li><em><strong>Task:</strong></em> Cooking (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Girase et al., "Latency Matters: Real-Time Action Forecasting Transformer", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Girase_Latency_Matters_Real-Time_Action_Forecasting_Transformer_CVPR_2023_paper.pdf>paper</a> <a href=https://karttikeya.github.io/publication/RAFTformer/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Girase_2023_CVPR,
    author = "Girase, Harshayu and Agarwal, Nakul and Choi, Chiho and Mangalam, Karttikeya",
    title = "Latency Matters: Real-Time Action Forecasting Transformer",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Nawhal et al., "Rethinking Learning Approaches for Long-Term Action Anticipation", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940547.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.11566.pdf>arxiv</a> <a href=https://github.com/Nmegha2601/anticipatr>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
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
<details close>
<summary><em>Roy et al., "Action Anticipation Using Latent Goal Learning", WACV, 2022.</em> <a href=https://openaccess.thecvf.com/content/WACV2022/papers/Roy_Action_Anticipation_Using_Latent_Goal_Learning_WACV_2022_paper.pdf>paper</a> <a href=https://github.com/debadityaroy/LatentGoal>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Roy_2022_WACV,
    author = "Roy, Debaditya and Fernando, Basura",
    title = "Action Anticipation Using Latent Goal Learning",
    booktitle = "WACV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ke et al., "Future Moment Assessment for Action Query", WACV, 2021.</em> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Ke_Future_Moment_Assessment_for_Action_Query_WACV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#rmse">RMSE</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ke_2021_WACV,
    author = "Ke, Qiuhong and Fritz, Mario and Schiele, Bernt",
    title = "Future Moment Assessment for Action Query",
    booktitle = "WACV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Piergiovanni et al., "Adversarial Generative Grammars for Human Activity Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470494.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.04888.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#charades">Charades</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
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
<summary><em>Zhao et al., "On Diverse Asynchronous Activity Anticipation", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123740766.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhao_2020_ECCV,
    author = "Zhao, He and Wildes, Richard P.",
    title = "On Diverse Asynchronous Activity Anticipation",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ke et al., "Time-Conditioned Action Anticipation In One Shot", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Ke_Time-Conditioned_Action_Anticipation_in_One_Shot_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
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
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<a name=carla></a>
<details close>
<summary><l style="font-size:20px"><strong>CARLA</strong></l> <a href=https://sites.google.com/view/precog>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rhinehart_PRECOG_PREdiction_Conditioned_on_Goals_in_Visual_Multi-Agent_Settings_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.01296.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 900 simulated driving segments for multi-agent trajectory forecasting and planning
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Driving (simulation)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Filatov et al., "Any Motion Detector: Learning Class-agnostic Scene Dynamics from a Sequence of LiDAR Point Clouds", ICRA, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9196716>paper</a> <a href=https://arxiv.org/pdf/2004.11647.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#ap">AP</a></li>
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
<summary><em>Diehl et al., "Energy-based Potential Games for Joint Motion Forecasting and Control", CoRL, 2023.</em> <a href=https://openreview.net/pdf?id=Eyb4e3GBuuR>paper</a> <a href=https://github.com/rst-tu-dortmund/diff_epo_planner>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#exid">exiD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minsfde">minSFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minsade">minSADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#or">OR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Diehl_2023_CoRL,
    author = "Diehl, Christopher and Klosek, Tobias and Krueger, Martin and Murzyn, Nils and Osterburg, Timo and Bertram, Torsten",
    title = "Energy-based Potential Games for Joint Motion Forecasting and Control",
    booktitle = "CoRL",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Roh et al., "Multimodal Trajectory Prediction via Topological Invariance for Navigation at Uncontrolled Intersections", CoRL, 2020.</em> <a href=https://proceedings.mlr.press/v155/roh21a/roh21a.pdf>paper</a> <a href=https://arxiv.org/pdf/2011.03894.pdf>arxiv</a> <a href=https://github.com/rohjunha/multiple-topologies-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Roh_2020_CORL,
    author = "Roh, Junha and Mavrogiannis, Christoforos and Madan, Rishabh and Fox, Dieter and Srinivasa, Siddhartha S",
    title = "Multimodal Trajectory Prediction via Topological Invariance for Navigation at Uncontrolled Intersections",
    booktitle = "CoRL",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Rhinehart et al., "Precog: Prediction Conditioned On Goals In Visual Multi-Agent Settings", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rhinehart_PRECOG_PREdiction_Conditioned_on_Goals_in_Visual_Multi-Agent_Settings_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.01296.pdf>arxiv</a> <a href=https://sites.google.com/view/precog>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minmsd">minMSD</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#meanmsd">meanMSD</a></li>
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
<summary><em>Tang et al., "Multiple futures prediction", NeurIPS, 2019.</em> <a href=https://proceedings.neurips.cc/paper/2019/file/86a1fa88adb5c33bd7a68ac2f9f3f96b-Paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#nll">NLL</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#rmse">RMSE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minmde">minMDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tang_2019_NeurIPS,
    author = "Tang, Charlie and Salakhutdinov, Russ R",
    title = "Multiple futures prediction",
    booktitle = "NeurIPS",
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
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#rmse">RMSE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#run_time">Run Time</a></li>
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
<summary><em>Hu et al., "Safe Local Motion Planning With Self-Supervised Freespace Forecasting", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Hu_Safe_Local_Motion_Planning_With_Self-Supervised_Freespace_Forecasting_CVPR_2021_paper.pdf>paper</a> <a href=https://github.com/peiyunh/ff>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_a-d_datasets.md#ap">AP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2021_CVPR,
    author = "Hu, Peiyun and Huang, Aaron and Dolan, John and Held, David and Ramanan, Deva",
    title = "Safe Local Motion Planning With Self-Supervised Freespace Forecasting",
    booktitle = "CVPR",
    year = "2021"
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mnist">MNIST</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_j-z_datasets.md#nll">NLL</a></li>
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
<a name=egtea_gaze+></a>
<details close>
<summary><l style="font-size:20px"><strong>Extended Georgia Tech Egocentric Activity Gaze+ (EGTEA Gaze+)</strong></l> <a href=http://www.cbi.gatech.edu/fpv/>link</a> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yin_Li_In_the_Eye_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.00626.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An egocentric cooking action dataset with 28 hours of recording with 86 unique sessions of 32 subjects with framerate of 30hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, gaze, mask, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Girase et al., "Latency Matters: Real-Time Action Forecasting Transformer", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Girase_Latency_Matters_Real-Time_Action_Forecasting_Transformer_CVPR_2023_paper.pdf>paper</a> <a href=https://karttikeya.github.io/publication/RAFTformer/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Girase_2023_CVPR,
    author = "Girase, Harshayu and Agarwal, Nakul and Choi, Chiho and Mangalam, Karttikeya",
    title = "Latency Matters: Real-Time Action Forecasting Transformer",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhong et al., "Anticipative Feature Fusion Transformer for Multi-Modal Action Anticipation", WACV, 2023.</em> <a href=https://openaccess.thecvf.com/content/WACV2023/papers/Zhong_Anticipative_Feature_Fusion_Transformer_for_Multi-Modal_Action_Anticipation_WACV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.12649.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhong_2023_WACV,
    author = "Zhong, Zeyun and Schneider, David and Voit, Michael and Stiefelhagen, Rainer and Beyerer, Jurgen",
    title = "Anticipative Feature Fusion Transformer for Multi-Modal Action Anticipation",
    booktitle = "WACV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liu et al., "A Hybrid Egocentric Activity Anticipation Framework via Memory-Augmented Recurrent and One-Shot Representation Forecasting", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_A_Hybrid_Egocentric_Activity_Anticipation_Framework_via_Memory-Augmented_Recurrent_and_CVPR_2022_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2022_CVPR_2,
    author = "Liu, Tianshan and Lam, Kin-Man",
    title = "A Hybrid Egocentric Activity Anticipation Framework via Memory-Augmented Recurrent and One-Shot Representation Forecasting",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Nawhal et al., "Rethinking Learning Approaches for Long-Term Action Anticipation", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940547.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.11566.pdf>arxiv</a> <a href=https://github.com/Nmegha2601/anticipatr>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
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
<details close>
<summary><em>Liu et al., "Forecasting Human Object Interaction: Joint Prediction of Motor Attention and Actions in First Person Video", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460681.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.10967.pdf>arxiv</a> <a href=https://github.com/2020aptx4869lm/Forecasting-Human-Object-Interaction-in-FPV>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#kld">KLD</a></li>
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
<summary><em>Furnari et al., "What Would You Expect? Anticipating Egocentric Actions With Rolling-Unrolling LSTMs And Modality Attention", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Furnari_What_Would_You_Expect_Anticipating_Egocentric_Actions_With_Rolling-Unrolling_LSTMs_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.09035.pdf>arxiv</a> <a href=https://github.com/fpv-iplab/rulstm>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Furnari_2019_ICCV,
    author = "Furnari, Antonino and Farinella, Giovanni Maria",
    title = "What Would You Expect? Anticipating Egocentric Actions With Rolling-Unrolling {LSTMs} And Modality Attention",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liu et al., "Joint Hand Motion and Interaction Hotspots Prediction From Egocentric Videos", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Joint_Hand_Motion_and_Interaction_Hotspots_Prediction_From_Egocentric_Videos_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.01696.pdf>arxiv</a> <a href=https://stevenlsw.github.io/hoi-forecast/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_a-d_datasets.md#auc">AUC</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#nss">NSS</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#ssim">SSIM</a></li>
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
<details close>
<summary><em>Jia et al., "Generative Adversarial Network for Future Hand Segmentation from Egocentric Video", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136730638.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.11305.pdf>arxiv</a> <a href=https://vjwq.github.io/EgoGAN/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_j-z_datasets.md#precision">Precision</a></li>
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
<a name=breakfast></a>
<details close>
<summary><l style="font-size:20px"><strong>Breakfast</strong></l> <a href=http://serre-lab.clps.brown.edu/resource/breakfast-actions-dataset/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2014/papers/Kuehne_The_Language_of_2014_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 77 hours of a video recording showing 10 breakfast preparation actions performed by 52 subjects in 18 different locations
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Girase et al., "Latency Matters: Real-Time Action Forecasting Transformer", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Girase_Latency_Matters_Real-Time_Action_Forecasting_Transformer_CVPR_2023_paper.pdf>paper</a> <a href=https://karttikeya.github.io/publication/RAFTformer/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Girase_2023_CVPR,
    author = "Girase, Harshayu and Agarwal, Nakul and Choi, Chiho and Mangalam, Karttikeya",
    title = "Latency Matters: Real-Time Action Forecasting Transformer",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Nawhal et al., "Rethinking Learning Approaches for Long-Term Action Anticipation", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940547.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.11566.pdf>arxiv</a> <a href=https://github.com/Nmegha2601/anticipatr>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#egtea_gaze+">EGTEA Gaze+</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
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
<details close>
<summary><em>Roy et al., "Action Anticipation Using Latent Goal Learning", WACV, 2022.</em> <a href=https://openaccess.thecvf.com/content/WACV2022/papers/Roy_Action_Anticipation_Using_Latent_Goal_Learning_WACV_2022_paper.pdf>paper</a> <a href=https://github.com/debadityaroy/LatentGoal>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Roy_2022_WACV,
    author = "Roy, Debaditya and Fernando, Basura",
    title = "Action Anticipation Using Latent Goal Learning",
    booktitle = "WACV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhao et al., "On Diverse Asynchronous Activity Anticipation", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123740766.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-kitchens">Epic-Kitchens</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhao_2020_ECCV,
    author = "Zhao, He and Wildes, Richard P.",
    title = "On Diverse Asynchronous Activity Anticipation",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Morais et al., "Learning to Abstract and Predict Human Actions", BMVC, 2020.</em> <a href=https://www.bmvc2020-conference.com/assets/papers/0979.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.09234.pdf>arxiv</a> <a href=https://github.com/RomeroBarata/hierarchical_action_prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#mof">MoF</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#moc">MoC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Morais_2020_BMVC,
    author = "Morais, Romero and Le, Vuong and Tran, Truyen and Venkatesh, Svetha",
    title = "Learning to Abstract and Predict Human Actions",
    booktitle = "BMVC",
    year = "2020"
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
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mpii_cooking">MPII Cooking</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
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
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<a name=uti></a>
<details close>
<summary><l style="font-size:20px"><strong>UT Interaction (UTI)</strong></l> <a href=http://cvrc.ece.utexas.edu/SDHA2010/Human_Interaction.html>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 6 human-human interactions, such as shaking hands, hugging, with 20 video clips of subjects with different clothing items recorded at 30fps
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Gammulle et al., "Predicting The Future: A Jointly Learnt Model For Action Anticipation", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Gammulle_Predicting_the_Future_A_Jointly_Learnt_Model_for_Action_Anticipation_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.07148.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uti">UTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uti">UTI</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<summary><em>Shi et al., "Action Anticipation With RBF Kernelized Feature Mapping RNN", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yuge_Shi_Action_Anticipation_with_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.07806.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uti">UTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shi_2018_ECCV,
    author = "Shi, Yuge and Fernando, Basura and Hartley, Richard",
    title = "Action Anticipation With {RBF} Kernelized Feature Mapping {RNN}",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sadegh et al., "Encouraging LSTMs To Anticipate Actions Very Early", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Aliakbarian_Encouraging_LSTMs_to_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uti">UTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Aliakbarian_2017_ICCV,
    author = "Sadegh Aliakbarian, Mohammad and Sadat Saleh, Fatemeh and Salzmann, Mathieu and Fernando, Basura and Petersson, Lars and Andersson, Lars",
    title = "Encouraging {LSTM}s To Anticipate Actions Very Early",
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uti">UTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uti">UTI</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uti">UTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#mrr">MRR</a></li>
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
    title = "{Ut-INteraction Dataset}, {ICPR} Contest On Semantic Description Of HUman ACtivities (SDHA)",
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
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a>, <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, mask, activity label, pose, optical flow</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Tang et al., "Pose Guided Global And Local Gan For Appearance Preserving Human Video Prediction", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8803792>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<summary><em>Fernando et al., "Anticipating Human Actions by Correlating Past With the Future With Jaccard Similarity Measures", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Fernando_Anticipating_Human_Actions_by_Correlating_Past_With_the_Future_With_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2105.12414.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Fernando_2021_CVPR,
    author = "Fernando, Basura and Herath, Samitha",
    title = "Anticipating Human Actions by Correlating Past With the Future With Jaccard Similarity Measures",
    booktitle = "CVPR",
    year = "2021"
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jhmdb">JHMDB</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#ava">AVA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#ap">AP</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jhmdb">JHMDB</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<summary><em>Shi et al., "Action Anticipation With RBF Kernelized Feature Mapping RNN", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yuge_Shi_Action_Anticipation_with_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.07806.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uti">UTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shi_2018_ECCV,
    author = "Shi, Yuge and Fernando, Basura and Hartley, Richard",
    title = "Action Anticipation With {RBF} Kernelized Feature Mapping {RNN}",
    booktitle = "ECCV",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sadegh et al., "Encouraging LSTMs To Anticipate Actions Very Early", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Aliakbarian_Encouraging_LSTMs_to_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uti">UTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Aliakbarian_2017_ICCV,
    author = "Sadegh Aliakbarian, Mohammad and Sadat Saleh, Fatemeh and Salzmann, Mathieu and Fernando, Basura and Petersson, Lars and Andersson, Lars",
    title = "Encouraging {LSTM}s To Anticipate Actions Very Early",
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<a name=thumos></a>
<details close>
<summary><l style="font-size:20px"><strong>THUMOS</strong></l> <a href=http://www.thumos.info/home.html>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 20K+ videos of 101 diverse action classes
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a>, <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<summary><em>Piergiovanni et al., "Adversarial Generative Grammars for Human Activity Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470494.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.04888.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#charades">Charades</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
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
<summary><em>Zhong et al., "Unsupervised Learning For Forecasting Action Representations", ICIP, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8451428>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<summary><em>Gao et al., "RED: Reinforced Encoder-Decoder Networks For Action Anticipation", BMVC, 2017.</em> <a href=http://www.bmva.org/bmvc/2017/papers/paper092/paper092.pdf>paper</a> <a href=https://arxiv.org/pdf/1707.04818.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_series">TV Series</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#cap">cAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2017_BMVC,
    author = "Gao, Jiyang and Yang, Zhenheng and Nevatia, Ram",
    title = "{RED}: Reinforced Encoder-Decoder Networks For Action Anticipation",
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<a name=tv_human_interaction></a>
<details close>
<summary><l style="font-size:20px"><strong>TV Human Interaction (THI)</strong></l> <a href=http://www.robots.ox.ac.uk/~alonso/tv_human_interactions.html>link</a> <a href=http://www.bmva.org/bmvc/2010/conference/paper50/abstract50.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 300 video clips collected from 20+ different TV shows containing 4 interactions: handshakes, high fives, hugs, and kisses
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, head pose, activity label</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Gammulle et al., "Predicting The Future: A Jointly Learnt Model For Action Anticipation", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Gammulle_Predicting_the_Future_A_Jointly_Learnt_Model_for_Action_Anticipation_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.07148.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uti">UTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<summary><em>Gao et al., "RED: Reinforced Encoder-Decoder Networks For Action Anticipation", BMVC, 2017.</em> <a href=http://www.bmva.org/bmvc/2017/papers/paper092/paper092.pdf>paper</a> <a href=https://arxiv.org/pdf/1707.04818.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_series">TV Series</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#cap">cAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2017_BMVC,
    author = "Gao, Jiyang and Yang, Zhenheng and Nevatia, Ram",
    title = "{RED}: Reinforced Encoder-Decoder Networks For Action Anticipation",
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
    title = "{High Five}: Recognising Human Interactions In {TV} Shows",
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D pose, activity label, affordance label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Alati et al., "Help By Predicting What To Do", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8803155>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mpii_cooking">MPII Cooking</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
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
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#acticipate">ACTICIPATE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
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
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
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
<summary><em>Jain et al., "Structural-RNN: Deep Learning On Spatio-Temporal Graphs", CVPR, 2016.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.05298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#ttm">TTM</a></li>
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
<summary><em>Hu et al., "Human Intent Forecasting Using Intrinsic Kinematic Constraints", IROS, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7759141>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
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
    title = "Learning Human Activities And Object Affordances From {RGB-D} Videos",
    journal = "IJRR",
    volume = "32",
    number = "8",
    pages = "951--970",
    year = "2013"
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, object class, temporal segment, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Bao et al., "DRIVE: Deep Reinforced Accident Anticipation With Visual Explanation", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Bao_DRIVE_Deep_Reinforced_Accident_Anticipation_With_Visual_Explanation_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2107.10189.pdf>arxiv</a> <a href=https://github.com/Cogito2012/DRIVE>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#dada-2000">DADA-2000</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#tta">TTA</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bao_2021_ICCV,
    author = "Bao, Wentao and Yu, Qi and Kong, Yu",
    title = "{DRIVE}: Deep Reinforced Accident Anticipation With Visual Explanation",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Suzuki et al., "Anticipating Traffic Accidents With Adaptive Loss And Large-Scale Incident Db", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0494.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.02675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#attc">ATTC</a></li>
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
<summary><em>Zeng et al., "Agent-Centric Risk Assessment: Accident Anticipation And Risky Region Localization", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Zeng_Agent-Centric_Risk_Assessment_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.06560.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-fail">Epic-Fail</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#tta">TTA</a></li>
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
<summary><em>Yao et al., "Unsupervised Traffic Accident Detection in First-Person Videos", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8967556>paper</a> <a href=https://arxiv.org/pdf/1903.00618.pdf>arxiv</a> <a href=https://github.com/MoonBlvd/tad-IROS2019>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#hev-i">HEV-I</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#a3d">A3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fiou">FIoU</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Chan_2017_ACCV,
    author = "Chan, Fu-Hsiang and Chen, Yu-Ting and Xiang, Yu and Sun, Min",
    editor = "Lai, Shang-Hong and Lepetit, Vincent and Nishino, Ko and Sato, Yoichi",
    title = "Anticipating Accidents In Dashcam Videos",
    booktitle = "ACCV",
    year = "2017"
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a>, <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chen et al., "Simultaneous Prediction of Pedestrian Trajectory and Actions based on Context Information Iterative Reasoning", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636252>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#virat/actev">VIRAT/ActEV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
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
<summary><em>Liang et al., "Peeking Into The Future: Predicting Future Person Activities And Locations In Videos", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Liang_Peeking_Into_the_Future_Predicting_Future_Person_Activities_and_Locations_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1902.03748.pdf>arxiv</a> <a href=https://github.com/google/next-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#virat/actev">VIRAT/ActEV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#virat/actev">VIRAT/ActEV</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#forking_paths">Forking Paths</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<summary><em>Liang et al., "SimAug: Learning Robust Representations from Simulation for Trajectory Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580273.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.02022.pdf>arxiv</a> <a href=https://github.com/JunweiLiang/Multiverse/tree/master/SimAug>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#virat/actev">VIRAT/ActEV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liang_2020_ECCV,
    author = "Liang, Junwei and Jiang, Lu and Hauptmann, Alexander",
    title = "{SimAug}: Learning Robust Representations from Simulation for Trajectory Prediction",
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
@InProceedings{Awad_2018_Trecvid,
    author = "Awad, George and Butt, Asad and Curtis, Keith and Lee, Yooyoung and Fiscus, Jonathan and Godil, Afzad and Joy, David and Delgado, Andrew and Smeaton, Alan and Graham, Yvette and others",
    title = "Benchmarking Video Activity Detection, Video Captioning And Matching, Video Storytelling Linking And Video Search",
    booktitle = "TRECVID",
    year = "2018"
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhao et al., "Spatiotemporal Feature Residual Propagation For Action Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhao_Spatiotemporal_Feature_Residual_Propagation_for_Action_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://github.com/JoeHEZHAO/Spatiotemporal-Residual-Propagation>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jhmdb">JHMDB</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uti">UTI</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bit">BIT</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uti">UTI</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bit">BIT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<a name=cmu_panoptic></a>
<details close>
<summary><l style="font-size:20px"><strong>CMU Panoptic</strong></l> <a href=http://domedb.perception.cs.cmu.edu/index.html>link</a> <a href=https://openaccess.thecvf.com/content_iccv_2015/papers/Joo_Panoptic_Studio_A_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1612.03153.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A multiview group activity dataset recorded with 10 RGB-D sensors and 30+ HD views with the corresponding 3D annotations
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a>, <a href=../../papers/motion/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, multiview, 3D pose, 3D facial landmark, Transcripts</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Joo et al., "Towards Social Artificial Intelligence: Nonverbal Social Signal Prediction In A Triadic Interaction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Joo_Towards_Social_Artificial_Intelligence_Nonverbal_Social_Signal_Prediction_in_a_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.04158.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<summary><em>Choudhury et al., "TEMPO: Efficient Multi-View Pose Estimation, Tracking, and Forecasting", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Choudhury_TEMPO_Efficient_Multi-View_Pose_Estimation_Tracking_and_Forecasting_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2309.07910.pdf>arxiv</a> <a href=https://rccchoudhury.github.io/tempo2023/>code</a></summary>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#pcp3d">PCP3D</a></li>
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
<summary><em>Wang et al., "Multi-Person 3D Motion Prediction with Multi-Range Transformers", NeurIPS, 2021.</em> <a href=https://papers.nips.cc/paper/2021/file/2fd5d41ec6cfab47e32164d5624269b1-Paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2111.12073.pdf>arxiv</a> <a href=https://github.com/jiashunwang/MRT>code</a></summary>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<summary><em>Yasar et al., "A Scalable Approach to Predict Multi-Agent Motion for Human-Robot Collaboration", RAL, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9353218>paper</a></summary>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mse">MSE</a></li>
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
<a name=brain4cars></a>
<details close>
<summary><l style="font-size:20px"><strong>Brain4Cars</strong></l> <a href=https://github.com/asheshjain399/ICCV2015_Brain4Cars>link</a> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Jain_Car_That_Knows_ICCV_2015_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1504.02789.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 700 driving events using inside and outside looking cameras with annotated actions for various driving maneuvers
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, attribute, temporal segment, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Jain et al., "Structural-RNN: Deep Learning On Spatio-Temporal Graphs", CVPR, 2016.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.05298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#ttm">TTM</a></li>
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
<summary><em>Jain et al., "Recurrent Neural Networks For Driver Activity Anticipation Via Sensory-Fusion Architecture", ICRA, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7487478>paper</a> <a href=https://arxiv.org/pdf/1509.05016.pdf>arxiv</a> <a href=https://github.com/asheshjain399/RNNexp>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#ttm">TTM</a></li>
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
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#brain4cars">Brain4Cars</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#ttm">TTM</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#fp">FP</a></li>
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
<a name=sysu_3dhoi></a>
<details close>
<summary><l style="font-size:20px"><strong>SYSU 3DHOI</strong></l> <a href=http://www.isee-ai.cn/~hujianfang/ProjectJOULE.html>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Hu_Jointly_Learning_Heterogeneous_2015_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 12 simple activities in 480 video clips with depth maps
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Object interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Foo et al., "ERA: Expert Retrieval and Assembly for Early Action Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940657.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.09675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Foo_2022_ECCV,
    author = "Foo, Lin Geng and Li, Tianjiao and Rahmani, Hossein and Ke, Qiuhong and Liu, Jun",
    title = "{ERA}: Expert Retrieval and Assembly for Early Action Prediction",
    booktitle = "ECCV",
    year = "2022"
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<summary><em>Hu et al., "Real-Time RGB-D Activity Prediction By Soft Regression", ECCV, 2016.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46448-0_17>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#orgbd">ORGBD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2016_ECCV,
    author = "Hu, Jian-Fang and Zheng, Wei-Shi and Ma, Lianyang and Wang, Gang and Lai, Jianhuang",
    editor = "Leibe, Bastian and Matas, Jiri and Sebe, Nicu and Welling, Max",
    title = "Real-Time {RGB-D} Activity Prediction By Soft Regression",
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
    title = "Jointly Learning Heterogeneous Features For {RGB-D} Activity Recognition",
    booktitle = "CVPR",
    year = "2015"
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
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a>, <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Sport</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Lu et al., "Flexible Spatio-Temporal Networks For Video Prediction", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Lu_Flexible_Spatio-Temporal_Networks_CVPR_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sports-1m">Sports-1M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#visor">ViSOR</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#prost">PROST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bit">BIT</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<a name=mpii_cooking></a>
<details close>
<summary><l style="font-size:20px"><strong>MPII Cooking</strong></l> <a href=https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/human-activity-recognition/mpii-cooking-activities-dataset/>link</a> <a href=https://ieeexplore.ieee.org/document/6247801>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 65 cooking activities with 5.5K+ video clips recorded from 12 subjects
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, 3D pose, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Alati et al., "Help By Predicting What To Do", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8803155>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#breakfast">Breakfast</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mpii_cooking">MPII Cooking</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mpii_cooking">MPII Cooking</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#virat">VIRAT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#rmse">RMSE</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mpii_cooking">MPII Cooking</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#rmse">RMSE</a></li>
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
<a name=recipe1m></a>
<details close>
<summary><l style="font-size:20px"><strong>Recipe1M</strong></l> <a href=http://pic2recipe.csail.mit.edu/>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Learning_Cross-Modal_Embeddings_With_Adversarial_Networks_for_Cooking_Recipes_and_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.01273.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 1M+ cooking recipes with 13M food images
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB (image), text</li>
<li><em><strong>Task:</strong></em> Cooking</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sener et al., "Zero-Shot Anticipation For Instructional Activities", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Sener_Zero-Shot_Anticipation_for_Instructional_Activities_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.02501.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#youcook2">YouCook2</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#recipe1m">Recipe1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
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
<summary><em>Abdelsalam et al., "GePSAn: Generative Procedure Step Anticipation in Cooking Videos", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Abdelsalam_GePSAn_Generative_Procedure_Step_Anticipation_in_Cooking_Videos_ICCV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#youcook2">YouCook2</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#recipe1m">Recipe1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_a-d_datasets.md#bleu">BLEU</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_j-z_datasets.md#meteor">METEOR</a></li>
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
<a name=pku-mmd></a>
<details close>
<summary><l style="font-size:20px"><strong>PKU-MMD</strong></l> <a href=http://www.icst.pku.edu.cn/struct/Projects/PKUMMD.html>link</a> <a href=https://arxiv.org/pdf/1703.07475.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A multimodal dataset of 41 daily activities and 10 interaction actions recorded from 3 camera views using 60 subjects
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, IR, 3D pose, multiview, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity, Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liu et al., "SSNet: Scale Selection Network For Online 3D Action Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_SSNet_Scale_Selection_CVPR_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pku-mmd">PKU-MMD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#oad">OAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2018_CVPR_ssnet,
    author = "Liu, Jun and Shahroudy, Amir and Wang, Gang and Duan, Ling-Yu and Kot, Alex C.",
    title = "{SSNet}: Scale Selection Network For Online {3D} Action Prediction",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Mao et al., "Masked Motion Predictors are Strong 3D Action Representation Learners", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Mao_Masked_Motion_Predictors_are_Strong_3D_Action_Representation_Learners_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.07092.pdf>arxiv</a> <a href=https://github.com/maoyunyao/MAMP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pku-mmd">PKU-MMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mse">MSE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Liu_2017_arxiv,
    author = "Chunhui, Liu and Yueyu, Hu and Yanghao, Li and Sijie, Song and Jiaying, Liu",
    title = "{PKU-MMD}: A Large Scale Benchmark For Continuous Multi-Modal Human Action Understanding",
    journal = "arXiv:1703.07475",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=jigsaws></a>
<details close>
<summary><l style="font-size:20px"><strong>JIGSAWS</strong></l> <a href=https://cirl.lcsr.jhu.edu/research/hmm/datasets/jigsaws_release/>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/7805258>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 3 surgical operation actions performed by 8 subjects using robotic arms
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, Activity Label, Temporal Segment</li>
<li><em><strong>Task:</strong></em> Robot</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Gao et al., "Accurate Grid Keypoint Learning for Efficient Video Prediction", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636874>paper</a> <a href=https://arxiv.org/pdf/2107.13170.pdf>arxiv</a> <a href=https://github.com/xjgaocs/Grid-Keypoint-Learning>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jigsaws">JIGSAWS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x1165d1ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2021_IROS,
    author = "Gao, Xiaojie and Jin, Yueming and Dou, Qi and Fu, Chi-Wing and Heng, Pheng-Ann",
    booktitle = "IROS",
    title = "Accurate Grid Keypoint Learning for Efficient Video Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Park et al., "Recognition and Prediction of Surgical Actions Based on Online Robotic Tool Detection", RAL, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9357894>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jigsaws">JIGSAWS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Park_2021_RAL,
    author = "Park, Juyoun and Park, Chung Hyuk",
    journal = "RAL",
    title = "Recognition and Prediction of Surgical Actions Based on Online Robotic Tool Detection",
    year = "2021",
    volume = "6",
    number = "2",
    pages = "2365-2372"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Ahmidi_2017_BE,
    author = "Ahmidi, Narges and Tao, Lingling and Sefati, Shahin and Gao, Yixin and Lea, Colin and Haro, Benjamín Béjar and Zappella, Luca and Khudanpur, Sanjeev and Vidal, René and Hager, Gregory D.",
    journal = "IEEE Transactions on Biomedical Engineering",
    title = "A Dataset and Benchmarks for Segmentation and Recognition of Gestures in Robotic Surgery",
    year = "2017",
    volume = "64",
    number = "9",
    pages = "2025-2041"
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hariyono et al., "Estimation Of Collision Risk For Improving Driver's Safety", IECON, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7793743>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth_pedestrian">ETH Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#daimler">Daimler</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hariyono_2016_IES,
    author = "Hariyono, Joko and Shahbaz, Ajmal and Kurnianggoro, Laksono and Jo, Kang-Hyun",
    title = "Estimation Of Collision Risk For Improving Driver's Safety",
    booktitle = "IECON",
    year = "2016"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Huynh et al., "AOL: Adaptive Online Learning for Human Trajectory Prediction in Dynamic Video Scenes", BMVC, 2020.</em> <a href=https://www.bmvc2020-conference.com/assets/papers/0493.pdf>paper</a> <a href=https://arxiv.org/pdf/2002.06666.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth_pedestrian">ETH Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<a name=youcook2></a>
<details close>
<summary><l style="font-size:20px"><strong>YouCook2</strong></l> <a href=http://youcook2.eecs.umich.edu/>link</a> <a href=https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/17344/16367>paper</a> <a href=https://arxiv.org/pdf/1703.09788.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset consists of 2K videos of cooking 89 recipes with corresponding English descriptions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, audio, text, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sener et al., "Zero-Shot Anticipation For Instructional Activities", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Sener_Zero-Shot_Anticipation_for_Instructional_Activities_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.02501.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#youcook2">YouCook2</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#recipe1m">Recipe1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
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
<summary><em>Abdelsalam et al., "GePSAn: Generative Procedure Step Anticipation in Cooking Videos", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Abdelsalam_GePSAn_Generative_Procedure_Step_Anticipation_in_Cooking_Videos_ICCV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#youcook2">YouCook2</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#recipe1m">Recipe1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_a-d_datasets.md#bleu">BLEU</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_j-z_datasets.md#meteor">METEOR</a></li>
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
<a name=ca></a>
<details close>
<summary><l style="font-size:20px"><strong>Collective Activity (CA)</strong></l> <a href=http://www-personal.umich.edu/~wgchoi/eccv12/wongun_eccv12.html>link</a> <a href=https://ieeexplore.ieee.org/document/5457461>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 40+ video clips showing collective activities including  crossing, waiting, queueing, walking and talking
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a>, <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../../papers/motion/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, attribute, activity label, temporal segment, pose</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chen et al., "Group Activity Prediction with Sequential Relational Anticipation Model", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660579.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.02441.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#ca">CA</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#volleyball">Volleyball</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<summary><em>Yao et al., "Multiple Granularity Group Interaction Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0721.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#ca">CA</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sbuki">SBUKI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
    title = "What Are They Doing?: Collective Activity Classification Using Spatio-Temporal Relationship Among People",
    booktitle = "ICCVW",
    year = "2009"
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a>, <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Surveillance, Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Mahmud et al., "Joint Prediction Of Activity Labels And Starting Times In Untrimmed Videos", ICCV, 2017.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Mahmud_Joint_Prediction_of_ICCV_2017_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mpii_cooking">MPII Cooking</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#virat">VIRAT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#rmse">RMSE</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#virat">VIRAT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#nll">NLL</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_j-z_datasets.md#run_time">Run Time</a></li>
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
<a name=hmdb></a>
<details close>
<summary><l style="font-size:20px"><strong>Human Motion Database (HMDB)</strong></l> <a href=http://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database/>link</a> <a href=https://ieeexplore.ieee.org/document/6126543>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 6.8K+ video clips of 51 actions corresponding to general facial actions (laughing), facial actions with object manipulation (smoking), general body movements (clapping hands), body movements with object interaction (catching), and body movements for human interaction (fencing)
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, mask, activity label, attribute</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Cho et al., "A Temporal Sequence Learning For Action Recognition And Prediction", WACV, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8354149>paper</a> <a href=https://arxiv.org/pdf/1906.06813.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#hmdb">HMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/other/<built-in method lower of str object at 0x117d9fc30>_alphabeticalother_a-d_datasets.md#accuracy">Accuracy</a></li>
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
@InProceedings{Kuehne_2011_ICCV,
    author = "Kuehne, H. and Jhuang, H. and Garrote, E. and Poggio, T. and Serre, T.",
    title = "{HMDB}: A Large Video Database For Human Motion Recognition",
    booktitle = "ICCV",
    year = "2011"
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D pose, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kataoka et al., "Recognition Of Transitional Action For Short-Term Action Prediction Using Discriminative Temporal CNN Feature", BMVC, 2016.</em> <a href=http://www.bmva.org/bmvc/2016/papers/paper012/paper012.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wnp">WnP</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#utka">UTKA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kataoka_2016_BMVC,
    author = "Kataoka, Hirokatsu and Miyashita, Yudai and Hayashi, Masaki and Iwata, Kenji and Satoh, Yutaka",
    title = "Recognition Of Transitional Action For Short-Term Action Prediction Using Discriminative Temporal {CNN} Feature",
    year = "2016",
    booktitle = "BMVC"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Park et al., "HMPO: Human Motion Prediction in Occluded Environments for Safe Motion Planning", RSS, 2020.</em> <a href=http://www.roboticsproceedings.org/rss16/p051.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.00424.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wnp">WnP</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#utka">UTKA</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#occlusion_mocap">Occlusion MoCap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mje">MJE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Wu_2015_CVPR,
    author = "Wu, Chenxia and Zhang, Jiemi and Savarese, Silvio and Saxena, Ashutosh",
    title = "{Watch-N-Patch}: Unsupervised Understanding Of Actions And Relations",
    booktitle = "CVPR",
    year = "2015"
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D pose, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kataoka et al., "Recognition Of Transitional Action For Short-Term Action Prediction Using Discriminative Temporal CNN Feature", BMVC, 2016.</em> <a href=http://www.bmva.org/bmvc/2016/papers/paper012/paper012.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wnp">WnP</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#utka">UTKA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kataoka_2016_BMVC,
    author = "Kataoka, Hirokatsu and Miyashita, Yudai and Hayashi, Masaki and Iwata, Kenji and Satoh, Yutaka",
    title = "Recognition Of Transitional Action For Short-Term Action Prediction Using Discriminative Temporal {CNN} Feature",
    year = "2016",
    booktitle = "BMVC"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Park et al., "HMPO: Human Motion Prediction in Occluded Environments for Safe Motion Planning", RSS, 2020.</em> <a href=http://www.roboticsproceedings.org/rss16/p051.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.00424.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wnp">WnP</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#utka">UTKA</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#occlusion_mocap">Occlusion MoCap</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x117d87730>_alphabeticalmotion_j-z_datasets.md#mje">MJE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Xia_2012_CVPRW,
    author = "Xia, L. and Chen, C.C. and Aggarwal, JK",
    title = "View Invariant Human Action Recognition Using Histograms Of {3D} Joints",
    booktitle = "CVPRW",
    year = "2012"
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Stereo grayscale, bounding box, temporal segment, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Schulz et al., "Pedestrian Intention Recognition Using Latent-Dynamic Conditional Random Fields", IV, 2015.</em> <a href=https://ieeexplore.ieee.org/document/7225754>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#daimler_path">Daimler Path</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#daimler_path">Daimler Path</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x117cfac70>_alphabeticaltrajectory_e-i_datasets.md#ed">ED</a></li>
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
<a name=vidhoi></a>
<details close>
<summary><l style="font-size:20px"><strong>VidHOI</strong></l> <a href=https://github.com/coldmanck/VidHOI>link</a> <a href=https://dl.acm.org/doi/10.1145/3463944.3469097>paper</a> <a href=https://arxiv.org/pdf/2105.11731.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of human-object interactions with over 70 hours of video recording, 7.3M annotations and 557 interactions.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Bounding Box, RGB</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Mascaro et al., "HOI4ABOT: Human-Object Interaction Anticipation for Human Intention Reading Collaborative roBOTs", CoRL, 2023.</em> <a href=https://openreview.net/pdf?id=rYZBdBytxBx>paper</a> <a href=https://arxiv.org/pdf/2309.16524.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#vidhoi">VidHOI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Chiou_2021_ICAR,
    author = "Chiou, Meng-Jiun and Liao, Chun-Yu and Wang, Li-Wei and Zimmermann, Roger and Feng, Jiashi",
    title = "ST-HOI: A Spatial-Temporal Baseline for Human-Object Interaction Detection in Videos",
    booktitle = "Workshop on Intelligent Cross-Data Analysis and Retrieval",
    year = "2021"
}
</pre>
</details>

</ul></details>
<a name=iitb-corridor></a>
<details close>
<summary><l style="font-size:20px"><strong>IITB-Corridor</strong></l> <a href=https://rodrigues-royston.github.io/Multi-timescale_Trajectory_Prediction/>link</a> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Rodrigues_Multi-timescale_Trajectory_Prediction_for_Abnormal_Human_Activity_Detection_WACV_2020_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 480K video frames for anomaly detection consisting of 10 different types of actions.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity Label</li>
<li><em><strong>Task:</strong></em> Anomaly</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Cao et al., "A New Comprehensive Benchmark for Semi-Supervised Video Anomaly Detection and Anticipation", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Cao_A_New_Comprehensive_Benchmark_for_Semi-Supervised_Video_Anomaly_Detection_and_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2305.13611.pdf>arxiv</a> <a href=https://github.com/zugexiaodui/campus_vad_code>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cuhk_avenue">CUHK Avenue</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#stc">STC</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nwpu_campus">NWPU Campus</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#iitb-corridor">IITB-Corridor</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cao_2023_CVPR,
    author = "Cao, Congqi and Lu, Yue and Wang, Peng and Zhang, Yanning",
    title = "A New Comprehensive Benchmark for Semi-Supervised Video Anomaly Detection and Anticipation",
    booktitle = "CVPR",
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
@InProceedings{Rodrigues_2020_WACV,
    author = "Rodrigues, Royston and Bhargava, Neha and Velmurugan, Rajbabu and Chaudhuri, Subhasis",
    title = "Multi-timescale Trajectory Prediction for Abnormal Human Activity Detection",
    booktitle = "WACV",
    year = "2020"
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sun et al., "Relational Action Forecasting", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Sun_Relational_Action_Forecasting_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1904.04231.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jhmdb">JHMDB</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#ava">AVA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#ap">AP</a></li>
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
    title = "{AVA}: A Video Dataset Of Spatio-Temporally Localized Atomic Visual Actions",
    booktitle = "CVPR",
    year = "2018"
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, gaze, pose</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Schydlo et al., "Anticipation In Human-Robot Cooperation: A Recurrent Neural Network Approach For Multiple Action Sequences Prediction", ICRA, 2018.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8460924>paper</a> <a href=https://arxiv.org/pdf/1802.10503.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cad-120">CAD-120</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#acticipate">ACTICIPATE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
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
<a name=trans></a>
<details close>
<summary><l style="font-size:20px"><strong>TRANS</strong></l> <a href=https://github.com/vita-epfl/pedestrian-transition-dataset>link</a> <a href=https://ieeexplore.ieee.org/document/9811664>paper</a> <a href=https://arxiv.org/pdf/2203.02489.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of pedestrian action derived from existing PIE, JAAD, and TITAN datasets with additional stop and go lables.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Trajectory, Activity Label, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Guo et al., "Pedestrian Stop and Go Forecasting with Hybrid Feature Fusion", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9811664>paper</a> <a href=https://arxiv.org/pdf/2203.02489.pdf>arxiv</a> <a href=https://github.com/vita-epfl/hybrid-feature-fusion>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#trans">TRANS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#ap">AP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Guo_2022_ICRA,
    author = "Guo, Dongxu and Mordan, Taylor and Alahi, Alexandre",
    booktitle = "ICRA",
    title = "Pedestrian Stop and Go Forecasting with Hybrid Feature Fusion",
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
@InProceedings{Guo_2022_ICRA,
    author = "Guo, Dongxu and Mordan, Taylor and Alahi, Alexandre",
    booktitle = "ICRA",
    title = "Pedestrian Stop and Go Forecasting with Hybrid Feature Fusion",
    year = "2022"
}
</pre>
</details>

</ul></details>
<a name=dada-2000></a>
<details close>
<summary><l style="font-size:20px"><strong>DADA-2000</strong></l> <a href=https://github.com/JWFangit/LOTVS-DADA>link</a> <a href=https://ieeexplore.ieee.org/document/9312486>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of driving scenarios with collected driver's gaze.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Gaze</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Bao et al., "DRIVE: Deep Reinforced Accident Anticipation With Visual Explanation", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Bao_DRIVE_Deep_Reinforced_Accident_Anticipation_With_Visual_Explanation_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2107.10189.pdf>arxiv</a> <a href=https://github.com/Cogito2012/DRIVE>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#dada-2000">DADA-2000</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#tta">TTA</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bao_2021_ICCV,
    author = "Bao, Wentao and Yu, Qi and Kong, Yu",
    title = "{DRIVE}: Deep Reinforced Accident Anticipation With Visual Explanation",
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
@ARTICLE{FANG_2021_TITS,
    author = "Fang, J. and Yan, D. and Qiao, J. and Xue, J. and Yu, H.",
    journal = "Trans-ITS",
    title = "{DADA}: Driver Attention Prediction in Driving Accident Scenarios",
    year = "2021"
}
</pre>
</details>

</ul></details>
<a name=pepscenes></a>
<details close>
<summary><l style="font-size:20px"><strong>PepScenes</strong></l> <a href=https://github.com/huawei-noah/PePScenes>link</a> <a href=https://ml4ad.github.io/files/papers2020/PePScenes:%20A%20Novel%20Dataset%20and%20Baseline%20for%20Pedestrian%20Action%20Prediction%20in%203D.pdf>paper</a> <a href=https://arxiv.org/pdf/2012.07773.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of pedestrian trajectories and crossing actions that provide extended annotations on an existing nuScenes dataset.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Activity Label, 3D Bounding Box</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yau et al., "Graph-SIM: A Graph-based Spatiotemporal Interaction Modelling for Pedestrian Action Prediction", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561107>paper</a> <a href=https://arxiv.org/pdf/2012.02148.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pepscenes">PepScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Rasouli_2020_NeurIPSW,
    author = "Rasouli, Amir and Yau, Tiffany and Lakner, Peter and Malekmohammadi, Saber and Rohani, Mohsen and Luo, Jun",
    booktitle = "NeurIPSW",
    title = "{PePScenes}: A Novel Dataset and Baseline for Pedestrian Action Prediction in {3D}",
    year = "2020"
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Robot</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Manglik et al., "Forecasting Time-To-Collision From Monocular Video: Feasibility, Dataset, And Challenges", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8967730>paper</a> <a href=https://arxiv.org/pdf/1903.09102.pdf>arxiv</a> <a href=https://github.com/aashi7/NearCollision>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#luggage">Luggage</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#mae">MAE</a></li>
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
<a name=finegym></a>
<details close>
<summary><l style="font-size:20px"><strong>FineGym</strong></l> <a href=https://sdolivia.github.io/FineGym/>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Shao_FineGym_A_Hierarchical_Video_Dataset_for_Fine-Grained_Action_Understanding_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.06704.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of sport events, containing 10 different events and over 700 hrs of recordings
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Temporal Segment, Activity Label</li>
<li><em><strong>Task:</strong></em> Sport</li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Shao_2020_CVPR,
    author = "Shao, Dian and Zhao, Yue and Dai, Bo and Lin, Dahua",
    title = "{FineGym}: A Hierarchical Video Dataset for Fine-grained Action Understanding",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul></details>
<a name=fpha></a>
<details close>
<summary><l style="font-size:20px"><strong>First Person Hand Action (FPHA)</strong></l> <a href=https://guiggh.github.io/publications/first-person-hands/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Garcia-Hernando_First-Person_Hand_Action_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1704.02463.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 100K frames of 45 dailt activities involving 26 different objects with 21 joint locations
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D Model, 3D pose, 6D object pose</li>
<li><em><strong>Task:</strong></em> Activity (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Li et al., "HARD-Net: Hardness-AwaRe Discrimination Network for 3D Early Activity Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123560409.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#fpha">FPHA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2020_ECCV,
    author = "Li, Tianjiao and Liu, Jun and Zhang, Wei and Duan, Lingyu",
    title = "{HARD-Net}: Hardness-AwaRe Discrimination Network for {3D} Early Activity Prediction",
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
@InProceedings{Garcia_2018_CVPR,
    author = "Garcia-Hernando, Guillermo and Yuan, Shanxin and Baek, Seungryul and Kim, Tae-Kyun",
    title = "First-Person Hand Action Benchmark with {RGB-D} Videos and {3D} Hand Pose Annotations",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul></details>
<a name=swag></a>
<details close>
<summary><l style="font-size:20px"><strong>Situations With Adversarial Generations (SWAG)</strong></l> <a href=https://rowanzellers.com/swag/>link</a> <a href=https://www.aclweb.org/anthology/D18-1009.pdf>paper</a> <a href=https://arxiv.org/pdf/1808.05326.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
The dataset consists of 113k multiple choice video questions about grounded situations with four answer choices about what might happen next in the scene.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Text</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hosseinzadeh et al., "Video Captioning of Future Frames", WACV, 2021.</em> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Hosseinzadeh_Video_Captioning_of_Future_Frames_WACV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#activitynet">ActivityNet</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#swag">SWAG</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#cider">CIDEr</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#rouge-l">ROUGE-L</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#meteor">METEOR</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#bleu@n">BLEU@N</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hosseinzadeh_2021_WACV,
    author = "Hosseinzadeh, Mehrdad and Wang, Yang",
    title = "Video Captioning of Future Frames",
    booktitle = "WACV",
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
@InProceedings{Zellers_2018_EMNLP,
    author = "Zellers, Rowan and Bisk, Yonatan and Schwartz, Roy and Choi, Yejin",
    title = "{SWAG}: A Large-Scale Adversarial Dataset for Grounded Commonsense Inference",
    booktitle = "EMNLP",
    year = "2018"
}
</pre>
</details>

</ul></details>
<a name=stip></a>
<details close>
<summary><l style="font-size:20px"><strong>Stanford-TRI Intent Prediction (STIP)</strong></l> <a href=https://stip.stanford.edu/dataset.html>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/9013045>paper</a> <a href=https://arxiv.org/pdf/2002.08945.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of over 900 hours of driving in 5 US cities annotated at 2Hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, activity label, temporal segment, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liu et al., "Spatiotemporal Relationship Reasoning for Pedestrian Intent Prediction", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9013045>paper</a> <a href=https://arxiv.org/pdf/2002.08945.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#stip">STIP</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
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

</ul></details>
<a name=ego4d></a>
<details close>
<summary><l style="font-size:20px"><strong>Ego4D</strong></l> <a href=https://ego4d-data.org/>link</a> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Grauman_Ego4D_Around_the_World_in_3000_Hours_of_Egocentric_Video_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2110.07058.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 3.7K  hours of daily-life activity video with various activities captured by 931 unique camera in 74 worldwide locations and 9 different countries.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Audio, Q&A, Activity Label, Temporal Segment</li>
<li><em><strong>Task:</strong></em> Activity (Ego)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Mascaro et al., "Intention-Conditioned Long-Term Human Egocentric Action Anticipation", WACV, 2023.</em> <a href=https://openaccess.thecvf.com/content/WACV2023/papers/Mascaro_Intention-Conditioned_Long-Term_Human_Egocentric_Action_Anticipation_WACV_2023_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#ego4d">Ego4D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#eid">EiD</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@inproceedings{Grauman_2022_CVPR,
    author = "Grauman, Kristen and Westbury, Andrew and Byrne, Eugene and Chavis, Zachary and Furnari, Antonino and Girdhar, Rohit and Hamburger, Jackson and Jiang, Hao and Liu, Miao and Liu, Xingyu and others",
    title = "Ego4d: Around the world in 3,000 hours of egocentric video",
    booktitle = "CVPR",
    year = "2022"
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity Label, Temporal Segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Epstein et al., "Oops! Predicting Unintentional Action in Video", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Epstein_Oops_Predicting_Unintentional_Action_in_Video_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.11206.pdf>arxiv</a> <a href=https://github.com/cvlab-columbia/oops>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#oops!">Oops!</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<a name=oad></a>
<details close>
<summary><l style="font-size:20px"><strong>Online Action Detection (OAD)</strong></l> <a href=http://www.icst.pku.edu.cn/struct/Projects/OAD.html>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46478-7_13>paper</a> <a href=https://arxiv.org/pdf/1604.05633.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 10 indoor activities in 59 sequences collected using a Kinect V2 sensor
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D pose, activity label, temporal segment, Tracking ID</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liu et al., "SSNet: Scale Selection Network For Online 3D Action Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_SSNet_Scale_Selection_CVPR_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#pku-mmd">PKU-MMD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#oad">OAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2018_CVPR_ssnet,
    author = "Liu, Jun and Shahroudy, Amir and Wang, Gang and Duan, Ling-Yu and Kot, Alex C.",
    title = "{SSNet}: Scale Selection Network For Online {3D} Action Prediction",
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
<a name=viena></a>
<details close>
<summary><l style="font-size:20px"><strong>VIENA</strong></l> <a href=https://sites.google.com/view/viena2-project/home>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20887-5_28>paper</a> <a href=https://arxiv.org/pdf/1810.09044.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A virtual driving dataset for action anticipation containing 5 different driving scenarios and 25 action classes
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving (simulation)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Aliakbarian et al., "VIENA2: A Driving Anticipation Dataset", ACCV, 2018.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-030-20887-5_28>paper</a> <a href=https://arxiv.org/pdf/1810.09044.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#viena">VIENA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
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

</ul></details>
<a name=bu_action></a>
<details close>
<summary><l style="font-size:20px"><strong>BU Action (BUA)</strong></l> <a href=http://cs-people.bu.edu/sbargal/BU-action/>link</a> <a href=https://www.sciencedirect.com/science/article/abs/pii/S0031320317300353>paper</a> <a href=https://arxiv.org/pdf/1512.07155.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of action images with 23K+ images and 101 activity classes collected from existing action video datasets
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB (image), activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Safaei et al., "Still Image Action Recognition By Predicting Spatial-Temporal Pixel Evolution", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8658386>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#willow_action">Willow Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wider">WIDER</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#stanford-40">Stanford-40</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bu_action">BU Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
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
<a name=daimler></a>
<details close>
<summary><l style="font-size:20px"><strong>Daimler</strong></l> <a href=http://www.gavrila.net/Datasets/Daimler_Pedestrian_Benchmark_D/Daimler_Mono_Ped__Detection_Be/daimler_mono_ped__detection_be.html>link</a> <a href=https://ieeexplore.ieee.org/document/4657363>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A grayscale dataset of 70K+ pedestrian samples recorded during the course of 27 minutes of driving
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Grayscale, bounding box</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hariyono et al., "Estimation Of Collision Risk For Improving Driver's Safety", IECON, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7793743>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth_pedestrian">ETH Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#daimler">Daimler</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hariyono_2016_IES,
    author = "Hariyono, Joko and Shahbaz, Ajmal and Kurnianggoro, Laksono and Jo, Kang-Hyun",
    title = "Estimation Of Collision Risk For Improving Driver's Safety",
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
<a name=willow_action></a>
<details close>
<summary><l style="font-size:20px"><strong>Willow Action</strong></l> <a href=https://www.di.ens.fr/willow/research/stillactions/>link</a> <a href=http://www.bmva.org/bmvc/2010/conference/paper97/paper97.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 7 actions, e.g. riding a bike, riding a horse, running, depicted in 968 RGB and grayscale images
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB (image), Grayscale (image), activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Safaei et al., "Still Image Action Recognition By Predicting Spatial-Temporal Pixel Evolution", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8658386>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#willow_action">Willow Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wider">WIDER</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#stanford-40">Stanford-40</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bu_action">BU Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB (image), bounding box, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Safaei et al., "Still Image Action Recognition By Predicting Spatial-Temporal Pixel Evolution", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8658386>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#willow_action">Willow Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wider">WIDER</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#stanford-40">Stanford-40</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bu_action">BU Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
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
<a name=sbuki></a>
<details close>
<summary><l style="font-size:20px"><strong>SBU Kinetic Interction (SBUKI)</strong></l> <a href=https://www3.cs.stonybrook.edu/~kyun/research/kinect_interaction/index.html>link</a> <a href=https://ieeexplore.ieee.org/document/6239234>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 8 dyadic human interactions, e.g. approaching, departing, pushing, kicking, recorded from 7 participants using a Kinect sensor comprising a total of approx. 300 interactions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a>, <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../../papers/motion/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yao et al., "Multiple Granularity Group Interaction Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0721.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#ca">CA</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sbuki">SBUKI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<a name=msrda></a>
<details close>
<summary><l style="font-size:20px"><strong>MSR Daily Activity (MSRDA)</strong></l> <a href=https://documents.uow.edu.au/~wanqing/MSRActionRecognitionDatasetsCodes%20-%20Zicheng.htm>link</a> <a href=https://ieeexplore.ieee.org/document/6247813>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 16 activities, such as writing on a paper, using a laptop, using a vacuum cleaner, cheering up, etc., performed by 10 subjects, recording using a Kinect sensor
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhang et al., "Bio-Inspired Predictive Orientation Decomposition Of Skeleton Trajectories For Real-Time Human Activity Prediction", ICRA, 2015.</em> <a href=https://ieeexplore.ieee.org/document/7139618>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#msrda">MSRDA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<a name=maniac></a>
<details close>
<summary><l style="font-size:20px"><strong>MANIAC</strong></l> <a href=https://alexandria.physik3.uni-goettingen.de/cns-group/datasets/maniac/>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/6163000>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An object manipulation action dataset with 8 different manipulation actions performed by 5 different subjects recorded using a Kinect sensor
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, semantic segment, activity label</li>
<li><em><strong>Task:</strong></em> Object interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ziaeetabar et al., "Prediction Of Manipulation Action Classes Using Semantic Spatial Reasoning", IROS, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8593717>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#maniac">MANIAC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#pp">PP</a></li>
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
<a name=gtea_gaze></a>
<details close>
<summary><l style="font-size:20px"><strong>Georgia Tech Egocentric Activity Gaze (GTEA Gaze)</strong></l> <a href=http://www.cbi.gatech.edu/fpv/>link</a> <a href=https://link.springer.com/content/pdf/10.1007%2F978-3-642-33718-5_23.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An egocentric dataset of 17 cooking activity videos performed by 14 subjects
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, gaze, mask, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Shen et al., "Egocentric Activity Prediction Via Event Modulated Attention", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Shen_Egocentric_Activity_Prediction_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#gtea_gaze+">GTEA Gaze+</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#gtea_gaze">GTEA Gaze</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, bounding box, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hu et al., "Real-Time RGB-D Activity Prediction By Soft Regression", ECCV, 2016.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46448-0_17>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sysu_3dhoi">SYSU 3DHOI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#orgbd">ORGBD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2016_ECCV,
    author = "Hu, Jian-Fang and Zheng, Wei-Shi and Ma, Lianyang and Wang, Gang and Lai, Jianhuang",
    editor = "Leibe, Bastian and Matas, Jiri and Sebe, Nicu and Welling, Max",
    title = "Real-Time {RGB-D} Activity Prediction By Soft Regression",
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
@InProceedings{Yu_2015_ACCV,
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB (image), activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Safaei et al., "Still Image Action Recognition By Predicting Spatial-Temporal Pixel Evolution", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8658386>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#willow_action">Willow Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#wider">WIDER</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#stanford-40">Stanford-40</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bu_action">BU Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
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
<a name=gtea_gaze+></a>
<details close>
<summary><l style="font-size:20px"><strong>Georgia Tech Egocentric Activity Gaze+ (GTEA Gaze+)</strong></l> <a href=http://www.cbi.gatech.edu/fpv/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2015/papers/Li_Delving_Into_Egocentric_2015_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An egocentric dataset of 37 videos of 7 cooking activities recorded from 26 subjects with the corresponding gaze tracking information
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, gaze, mask, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Cooking (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Shen et al., "Egocentric Activity Prediction Via Event Modulated Attention", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Shen_Egocentric_Activity_Prediction_ECCV_2018_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#gtea_gaze+">GTEA Gaze+</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#gtea_gaze">GTEA Gaze</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity (egocentric)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhou et al., "Temporal Perception And Prediction In Ego-Centric Video", ICCV, 2015.</em> <a href=https://openaccess.thecvf.com/content_iccv_2015/papers/Zhou_Temporal_Perception_and_ICCV_2015_paper.pdf>paper</a> <a href=https://github.com/aditya7874/Activity-Prediction-in-EgoCentric-Videos>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#fppa">FPPA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<a name=tv_series></a>
<details close>
<summary><l style="font-size:20px"><strong>TV Series</strong></l> <a href=https://github.com/zhenyangli/online_action>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46454-1_17>paper</a> <a href=https://arxiv.org/pdf/1604.06506.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A collection of sequences collected from TV series for the purpose of action detection
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Gao et al., "RED: Reinforced Encoder-Decoder Networks For Action Anticipation", BMVC, 2017.</em> <a href=http://www.bmva.org/bmvc/2017/papers/paper092/paper092.pdf>paper</a> <a href=https://arxiv.org/pdf/1707.04818.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_human_interaction">TV Human Interaction</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#tv_series">TV Series</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#cap">cAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2017_BMVC,
    author = "Gao, Jiyang and Yang, Zhenheng and Nevatia, Ram",
    title = "{RED}: Reinforced Encoder-Decoder Networks For Action Anticipation",
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
<a name=oa></a>
<details close>
<summary><l style="font-size:20px"><strong>Ongoing Activity (OA)</strong></l> <a href=http://www.mpii.de/ongoing-activity>link</a> <a href=https://ieeexplore.ieee.org/document/7477586>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 450+ activities, such as cooking, house chores, etc.,  videos collected from public video sharing websites
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Li et al., "Recognition Of Ongoing Complex Activities By Sequence Prediction Over A Hierarchical Label Space", WACV, 2016.</em> <a href=https://ieeexplore.ieee.org/document/7477586>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#oa">OA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<a name=charades></a>
<details close>
<summary><l style="font-size:20px"><strong>Charades</strong></l> <a href=https://prior.allenai.org/projects/charades>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46448-0_31>paper</a> <a href=https://arxiv.org/pdf/1604.01753.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of ~10K indoor videos with 157 action  and 46 object classes
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity label, Object Class, Temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Piergiovanni et al., "Adversarial Generative Grammars for Human Activity Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470494.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.04888.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#50salads">50Salads</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#charades">Charades</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Sigurdsson_2016_ECCV,
    author = {Sigurdsson, Gunnar A and Varol, G{\"u}l and Wang, Xiaolong and Farhadi, Ali and Laptev, Ivan and Gupta, Abhinav},
    title = "Hollywood in Homes: Crowdsourcing Data Collection for Activity Understanding",
    booktitle = "ECCV",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=volleyball></a>
<details close>
<summary><l style="font-size:20px"><strong>Volleyball</strong></l> <a href=https://github.com/mostafa-saad/deep-activity-rec#dataset>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Ibrahim_A_Hierarchical_Deep_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.06040.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 4830 frames from 55 videos with 9 player action labels and 8 team activity labels
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a>, <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity label, Bounding box</li>
<li><em><strong>Task:</strong></em> Sport</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chen et al., "Group Activity Prediction with Sequential Relational Anticipation Model", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660579.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.02441.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#ca">CA</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#volleyball">Volleyball</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Ibrahim_2016_CVPR,
    author = "Ibrahim, Mostafa S and Muralidharan, Srikanth and Deng, Zhiwei and Vahdat, Arash and Mori, Greg",
    title = "A Hierarchical Deep Temporal Model for Group Activity Recognition",
    booktitle = "CVPR",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=ceilidh_dance></a>
<details close>
<summary><l style="font-size:20px"><strong>Ceilidh Dance</strong></l> <a href=https://homepages.inf.ed.ac.uk/rbf/CEILIDHDATA/>link</a> <a href=https://homepages.inf.ed.ac.uk/rbf/CEILIDHDATA/msc_20161996.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of Ceilidh Scottish dance sequences performed by 16 dancers in two styles recorded from bird’s eye view.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a>, <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity Label, Trajectory</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hu et al., "Entry-Flipped Transformer for Inference and Prediction of Participant Behavior", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136640433.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.06235.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#ceilidh_dance">Ceilidh Dance</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@mastersthesis{Aizeboje_2016_masc,
    author = "Aizeboje, Jeremiah",
    title = "Ceilidh Dance Recognition from an Overhead Camera",
    year = "2016",
    school = "University of Edinburgh"
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
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, trajectory, temporal segment</li>
<li><em><strong>Task:</strong></em> Risk assessment</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zeng et al., "Agent-Centric Risk Assessment: Accident Anticipation And Risky Region Localization", CVPR, 2017.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Zeng_Agent-Centric_Risk_Assessment_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1705.06560.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#epic-fail">Epic-Fail</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_j-z_datasets.md#tta">TTA</a></li>
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
<a name=nwpu_campus></a>
<details close>
<summary><l style="font-size:20px"><strong>NWPU Campus</strong></l> <a href=https://campusvad.github.io/>link</a> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Cao_A_New_Comprehensive_Benchmark_for_Semi-Supervised_Video_Anomaly_Detection_and_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2305.13611.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 1.4M video frames with 28 classes for anomaly detection.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/action/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity Label</li>
<li><em><strong>Task:</strong></em> Anomaly</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Cao et al., "A New Comprehensive Benchmark for Semi-Supervised Video Anomaly Detection and Anticipation", CVPR, 2023.</em> <a href=https://openaccess.thecvf.com/content/CVPR2023/papers/Cao_A_New_Comprehensive_Benchmark_for_Semi-Supervised_Video_Anomaly_Detection_and_CVPR_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2305.13611.pdf>arxiv</a> <a href=https://github.com/zugexiaodui/campus_vad_code>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cuhk_avenue">CUHK Avenue</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#stc">STC</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nwpu_campus">NWPU Campus</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#iitb-corridor">IITB-Corridor</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x117cfa670>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cao_2023_CVPR,
    author = "Cao, Congqi and Lu, Yue and Wang, Peng and Zhang, Yanning",
    title = "A New Comprehensive Benchmark for Semi-Supervised Video Anomaly Detection and Anticipation",
    booktitle = "CVPR",
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
@InProceedings{Cao_2023_CVPR,
    author = "Cao, Congqi and Lu, Yue and Wang, Peng and Zhang, Yanning",
    title = "A New Comprehensive Benchmark for Semi-Supervised Video Anomaly Detection and Anticipation",
    booktitle = "CVPR",
    year = "2023"
}
</pre>
</details>

</ul></details>
</ul>