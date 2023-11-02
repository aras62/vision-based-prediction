<a name=top></a>
<a name=top></a>
---
<a href=../../README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Datasets</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../metrics.md#top><l style="font-size:30px">Metrics</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
[Home](../datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Alphabetical](../alphabetical/alphabetical_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Year](../year/year_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Application&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Task](../task/task_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Annotation](../annotation_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
Video&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Action](action_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Trajectory](trajectory_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Motion](motion_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Other](other_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
<h2>Video Datasets</h2> 
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#human">Human</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_a-d_datasets.md#csi">CSI</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#gdl">GDL</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#human">Human</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#human">Human</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_e-i_datasets.md#eid">EiD</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_a-d_datasets.md#apd">APD</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mmade">MMADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mmfde">MMFDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_e-i_datasets.md#fid">FID</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_a-d_datasets.md#cmd">CMD</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#pcp3d">PCP3D</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#pck">PCK</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpble">MPBLE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#p-mpjpe">P-MPJPE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#pck">PCK</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_a-d_datasets.md#apd">APD</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mmade">MMADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mmfde">MMFDE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_a-d_datasets.md#apd">APD</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#sde">sDE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mmade">MMADE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_a-d_datasets.md#apd">APD</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_e-i_datasets.md#is">IS</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_a-d_datasets.md#apd">APD</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#nll">NLL</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#kde">KDE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_a-d_datasets.md#apd">APD</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#minade">minADE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_e-i_datasets.md#ed">ED</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#pck">PCK</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#kld">KLD</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_a-d_datasets.md#apd">APD</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#kld">KLD</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#si">SI</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#kl">KL</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#s-mse">S-MSE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_a-d_datasets.md#apd">APD</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mmade">MMADE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mmfde">MMFDE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mae">MAE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#npss">NPSS</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mje">MJE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#run_time">Run Time</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_e-i_datasets.md#human">Human</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#pskl">PSKL</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#psent">PSEnt</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#pck">PCK</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#re">RE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mje">MJE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#pck">PCK</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_e-i_datasets.md#human">Human</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#pck">PCK</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mane">MAnE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<a name=kitti></a>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#rt">RT</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fid">FID</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#iou">IoU</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_a-d_datasets.md#csim">CSIM</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#human">Human</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#is">IS</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ms-ssim">MS-SSIM</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#ap">AP</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
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
<summary><em>Weng et al., "Inverting the Pose Forecasting Pipeline with SPF2: Sequential Pointcloud Forecasting for Sequential Pose Forecasting", CoRL, 2021.</em> <a href=https://proceedings.mlr.press/v155/weng21a/weng21a.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.08376.pdf>arxiv</a> <a href=https://github.com/xinshuoweng/SPF2>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#minmsd">minMSD</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#meanmsd">meanMSD</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_a-d_datasets.md#ce">CE</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#mr">MR</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_e-i_datasets.md#ed">ED</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#mined">minED</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#maxd">maxD</a></li>
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
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_a-d_datasets.md#absrel">AbsRel</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_j-z_datasets.md#l1">L1</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_j-z_datasets.md#nfe">NFE</a></li>
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
<summary><em>Weng et al., "S2Net: Stochastic Sequential Pointcloud Forecasting", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136870541.pdf>paper</a> <a href=https://www.xinshuoweng.com/projects/S2Net>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_a-d_datasets.md#cd">CD</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_e-i_datasets.md#emd">EMD</a></li>
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
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_a-d_datasets.md#cd">CD</a></li>
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
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_j-z_datasets.md#run_time">Run Time</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_j-z_datasets.md#tp">TP</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_j-z_datasets.md#tn">TN</a></li>
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
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_e-i_datasets.md#f1">F1</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#rt">RT</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fid">FID</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#is">IS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mmd">MMD</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<a name=mmnist></a>
<details close>
<summary><l style="font-size:20px"><strong>Moving MNIST (MMNIST)</strong></l> <a href=http://www.cs.toronto.edu/~nitish/unsupervised_video/>link</a> <a href=http://proceedings.mlr.press/v37/srivastava15.pdf>paper</a> <a href=https://arxiv.org/pdf/1502.04681.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of moving digits on a simple uniform background
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Grayscale</li>
<li><em><strong>Task:</strong></em> Digit</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhong et al., "MMVP: Motion-Matrix-Based Video Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Zhong_MMVP_Motion-Matrix-Based_Video_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.16154.pdf>arxiv</a> <a href=https://github.com/Kay1794/MMVP-motion-matrix-based-video-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf_sports">UCF Sports</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhong_2023_ICCV,
    author = "Zhong, Yiqi and Liang, Luming and Zharkov, Ilya and Neumann, Ulrich",
    title = "MMVP: Motion-Matrix-Based Video Prediction",
    booktitle = "ICCV",
    year = "2023"
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
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
<summary><em>Villar-Corrales et al., "MSPred: Video Prediction at Multiple Spatio-Temporal Scales with Hierarchical Recurrent Networks", BMVC, 2022.</em> <a href=https://bmvc2022.mpi-inf.mpg.de/0034.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.09303.pdf>arxiv</a> <a href=https://github.com/AIS-Bonn/MSPred>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Villar-Corrales_2022_BMVC,
    author = "Villar-Corrales, Angel and Karapetyan, Ani and Boltres, Andreas and Behnke, Sven",
    title = "{MSPred}: Video Prediction at Multiple Spatio-Temporal Scales with Hierarchical Recurrent Networks",
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<summary><em>Ben et al., "PhyLoNet: Physically-Constrained Long Term Video Prediction", ACCV, 2022.</em> <a href=https://openaccess.thecvf.com/content/ACCV2022/papers/Zikri_PhyLoNet_Physically-Constrained_Long_Term_Video_Prediction_ACCV_2022_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ben_Zikri_2022_ACCV,
    author = "Ben Zikri, Nir and Sharf, Andrei",
    title = "{PhyLoNet}: Physically-Constrained Long Term Video Prediction",
    booktitle = "ACCV",
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
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
<summary><em>Chatterjee et al., "A Hierarchical Variational Neural Uncertainty Model for Stochastic Video Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Chatterjee_A_Hierarchical_Variational_Neural_Uncertainty_Model_for_Stochastic_Video_Prediction_ICCV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chatterjee_2021_ICCV,
    author = "Chatterjee, Moitreya and Ahuja, Narendra and Cherian, Anoop",
    title = "A Hierarchical Variational Neural Uncertainty Model for Stochastic Video Prediction",
    booktitle = "ICCV",
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<summary><em>Xu et al., "Video Prediction via Example Guidance", ICML, 2020.</em> <a href=http://proceedings.mlr.press/v119/xu20j/xu20j.pdf>paper</a> <a href=https://arxiv.org/pdf/2007.01738.pdf>arxiv</a> <a href=https://github.com/xjwxjw/VPEG>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2020_ICML,
    author = "Xu, Jingwei and Xu, Huazhe and Ni, Bingbing and Yang, Xiaokang and Darrell, Trevor",
    title = "Video Prediction via Example Guidance",
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<summary><em>Lee et al., "Mutual Suppression Network For Video Prediction Using Disentangled Features", BMVC, 2019.</em> <a href=https://bmvc2019.org/wp-content/uploads/papers/0336-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.04810.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#msr">MSR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bouncing_ball">Bouncing Ball</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_a-d_datasets.md#bce">BCE</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#sports-1m">Sports-1M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#visor">ViSOR</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#prost">PROST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#human">Human</a></li>
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
<summary><em>Wang et al., "PredRNN: Recurrent Neural Networks For Predictive Learning Using Spatiotemporal LSTMs", NeurIPS, 2017.</em> <a href=https://papers.nips.cc/paper/6689-predrnn-recurrent-neural-networks-for-predictive-learning-using-spatiotemporal-lstms.pdf>paper</a> <a href=https://github.com/ujjax/pred-rnn>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2017_NeurIPS,
    author = "Wang, Yunbo and Long, Mingsheng and Wang, Jianmin and Gao, Zhifeng and Yu, Philip S",
    title = "{PredRNN}: Recurrent Neural Networks For Predictive Learning Using Spatiotemporal {LSTMs}",
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mnist">MNIST</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_j-z_datasets.md#nll">NLL</a></li>
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
@InProceedings{Srivastava_2015_ICML,
    author = "Srivastava, Nitish and Mansimov, Elman and Salakhudinov, Ruslan",
    title = "Unsupervised Learning Of Video Representations Using {LSTMs}",
    booktitle = "ICML",
    year = "2015"
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#l1">L1</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#l1">L1</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_j-z_datasets.md#recall">Recall</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_j-z_datasets.md#precision">Precision</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#ap">AP</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#ap">AP</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_j-z_datasets.md#run_time">Run Time</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_e-i_datasets.md#fiou">FIoU</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_e-i_datasets.md#frb">FRB</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_a-d_datasets.md#arb">ARB</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_e-i_datasets.md#fiou">FIoU</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#kde">KDE</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#rmse">RMSE</a></li>
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
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_j-z_datasets.md#psi">Psi</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_e-i_datasets.md#ism">ISM</a></li>
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
<a name=kth></a>
<details close>
<summary><l style="font-size:20px"><strong>KTH</strong></l> <a href=http://www.nada.kth.se/cvap/actions/>link</a> <a href=https://ieeexplore.ieee.org/document/1334462>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 6 basic actions, e.g. walking, jogging, running, recorded from 25 subjects at 25fps for a total of 2391 sequences
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Grayscale, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fid">FID</a></li>
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
<summary><em>Davtyan et al., "Efficient Video Prediction via Sparsely Conditioned Flow Matching", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Davtyan_Efficient_Video_Prediction_via_Sparsely_Conditioned_Flow_Matching_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2211.14575.pdf>arxiv</a> <a href=https://araachie.github.io/river/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair">BAIR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Davtyan_2023_ICCV,
    author = "Davtyan, Aram and Sameni, Sepehr and Favaro, Paolo",
    title = "Efficient Video Prediction via Sparsely Conditioned Flow Matching",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhong et al., "MMVP: Motion-Matrix-Based Video Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Zhong_MMVP_Motion-Matrix-Based_Video_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.16154.pdf>arxiv</a> <a href=https://github.com/Kay1794/MMVP-motion-matrix-based-video-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf_sports">UCF Sports</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhong_2023_ICCV,
    author = "Zhong, Yiqi and Liang, Luming and Zharkov, Ilya and Neumann, Ulrich",
    title = "MMVP: Motion-Matrix-Based Video Prediction",
    booktitle = "ICCV",
    year = "2023"
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
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
<summary><em>Villar-Corrales et al., "MSPred: Video Prediction at Multiple Spatio-Temporal Scales with Hierarchical Recurrent Networks", BMVC, 2022.</em> <a href=https://bmvc2022.mpi-inf.mpg.de/0034.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.09303.pdf>arxiv</a> <a href=https://github.com/AIS-Bonn/MSPred>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Villar-Corrales_2022_BMVC,
    author = "Villar-Corrales, Angel and Karapetyan, Ani and Boltres, Andreas and Behnke, Sven",
    title = "{MSPred}: Video Prediction at Multiple Spatio-Temporal Scales with Hierarchical Recurrent Networks",
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
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
<summary><em>Chatterjee et al., "A Hierarchical Variational Neural Uncertainty Model for Stochastic Video Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Chatterjee_A_Hierarchical_Variational_Neural_Uncertainty_Model_for_Stochastic_Video_Prediction_ICCV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chatterjee_2021_ICCV,
    author = "Chatterjee, Moitreya and Ahuja, Narendra and Cherian, Anoop",
    title = "A Hierarchical Variational Neural Uncertainty Model for Stochastic Video Prediction",
    booktitle = "ICCV",
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<summary><em>Lee et al., "Mutual Suppression Network For Video Prediction Using Disentangled Features", BMVC, 2019.</em> <a href=https://bmvc2019.org/wp-content/uploads/papers/0336-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.04810.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#msr">MSR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#human">Human</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#rmse">RMSE</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<summary><em>Jin et al., "VarNet: Exploring Variations For Unsupervised Video Prediction", IROS, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8594264>paper</a> <a href=https://github.com/jinbeibei/VarNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<summary><em>Wang et al., "PredRNN: Recurrent Neural Networks For Predictive Learning Using Spatiotemporal LSTMs", NeurIPS, 2017.</em> <a href=https://papers.nips.cc/paper/6689-predrnn-recurrent-neural-networks-for-predictive-learning-using-spatiotemporal-lstms.pdf>paper</a> <a href=https://github.com/ujjax/pred-rnn>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2017_NeurIPS,
    author = "Wang, Yunbo and Long, Mingsheng and Wang, Jianmin and Gao, Zhifeng and Yu, Philip S",
    title = "{PredRNN}: Recurrent Neural Networks For Predictive Learning Using Spatiotemporal {LSTMs}",
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
    title = "Recognizing Human Actions: A Local {SVM} Approach",
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
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a>, <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a>, <a href=../../papers/other/other_papers.md#top>Other prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, bounding box, semantic segment, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#rt">RT</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#iou">IoU</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_a-d_datasets.md#csim">CSIM</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ms-ssim">MS-SSIM</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#minade">minADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_j-z_datasets.md#minfde">minFDE</a></li>
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
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
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
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_e-i_datasets.md#f1">F1</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_e-i_datasets.md#iou">IoU</a></li>
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
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_e-i_datasets.md#iou">IoU</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_a-d_datasets.md#ap">AP</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_j-z_datasets.md#rq">RQ</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_j-z_datasets.md#sq">SQ</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_j-z_datasets.md#pq">PQ</a></li>
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
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_a-d_datasets.md#ap">AP</a></li>
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
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_e-i_datasets.md#iou">IoU</a></li>
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
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_e-i_datasets.md#iou">IoU</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_a-d_datasets.md#ddm">DDM</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_a-d_datasets.md#aepe">AEPE</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_j-z_datasets.md#sile">SILE</a></li>
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
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_e-i_datasets.md#iou">IoU</a></li>
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
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_e-i_datasets.md#iou">IoU</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_j-z_datasets.md#voi">VoI</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_e-i_datasets.md#gce">GCE</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_j-z_datasets.md#ri">RI</a></li>
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
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_e-i_datasets.md#iou">IoU</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_e-i_datasets.md#epe">EPE</a></li>
<li><a href="../../metrics/other/<built-in method lower of str object at 0x11005fcf0>_alphabeticalother_j-z_datasets.md#miou">MIoU</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#l1">L1</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<a name=penn_action></a>
<details close>
<summary><l style="font-size:20px"><strong>Penn Action</strong></l> <a href=http://dreamdragon.github.io/PennAction/>link</a> <a href=https://www.cv-foundation.org/openaccess/content_iccv_2013/papers/Zhang_From_Actemes_to_2013_ICCV_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 2.3K+ video clips of 15 actions with the corresponding human joint annotations
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a>, <a href=../../papers/motion/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, pose, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Xu et al., "Video Prediction via Example Guidance", ICML, 2020.</em> <a href=http://proceedings.mlr.press/v119/xu20j/xu20j.pdf>paper</a> <a href=https://arxiv.org/pdf/2007.01738.pdf>arxiv</a> <a href=https://github.com/xjwxjw/VPEG>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2020_ICML,
    author = "Xu, Jingwei and Xu, Huazhe and Ni, Bingbing and Yang, Xiaokang and Darrell, Trevor",
    title = "Video Prediction via Example Guidance",
    booktitle = "ICML",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ye et al., "Compositional Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ye_Compositional_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.08522.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#shapestack">ShapeStack</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uva-nemo">UvA-NEMO</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mgif">MGIF</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#jhmdb">JHMDB</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mug">MUG</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#is">IS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mmd">MMD</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#human">Human</a></li>
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
<summary><em>Sun et al., "Action-guided 3D Human Motion Prediction", NeurIPS, 2021.</em> <a href=https://papers.nips.cc/paper/2021/file/fd9dd764a6f1d73f4340d570804eacc4-Paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#pck">PCK</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#kld">KLD</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mpjpe">MPJPE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#pck">PCK</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#re">RE</a></li>
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
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#mje">MJE</a></li>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#pck">PCK</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mpii_human_pose">MPII Human Pose</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/motion/<built-in method lower of str object at 0x1100477f0>_alphabeticalmotion_j-z_datasets.md#pck">PCK</a></li>
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
<a name=bair></a>
<details close>
<summary><l style="font-size:20px"><strong>BAIR Push</strong></l> <a href=https://sites.google.com/site/brainrobotdata/home/push-dataset>link</a> <a href=https://papers.nips.cc/paper/6161-unsupervised-learning-for-physical-interaction-through-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1605.07157.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of object manipulation using a robot arm with 59k object pushing motion samples
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Robot object manipulation</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Davtyan et al., "Efficient Video Prediction via Sparsely Conditioned Flow Matching", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Davtyan_Efficient_Video_Prediction_via_Sparsely_Conditioned_Flow_Matching_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2211.14575.pdf>arxiv</a> <a href=https://araachie.github.io/river/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair">BAIR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#rt">RT</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Davtyan_2023_ICCV,
    author = "Davtyan, Aram and Sameni, Sepehr and Favaro, Paolo",
    title = "Efficient Video Prediction via Sparsely Conditioned Flow Matching",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chatterjee et al., "A Hierarchical Variational Neural Uncertainty Model for Stochastic Video Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Chatterjee_A_Hierarchical_Variational_Neural_Uncertainty_Model_for_Stochastic_Video_Prediction_ICCV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chatterjee_2021_ICCV,
    author = "Chatterjee, Moitreya and Ahuja, Narendra and Cherian, Anoop",
    title = "A Hierarchical Variational Neural Uncertainty Model for Stochastic Video Prediction",
    booktitle = "ICCV",
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<summary><em>Xu et al., "Video Prediction via Example Guidance", ICML, 2020.</em> <a href=http://proceedings.mlr.press/v119/xu20j/xu20j.pdf>paper</a> <a href=https://arxiv.org/pdf/2007.01738.pdf>arxiv</a> <a href=https://github.com/xjwxjw/VPEG>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2020_ICML,
    author = "Xu, Jingwei and Xu, Huazhe and Ni, Bingbing and Yang, Xiaokang and Darrell, Trevor",
    title = "Video Prediction via Example Guidance",
    booktitle = "ICML",
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#ap">AP</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_j-z_datasets.md#map">mAP</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#cap">cAP</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<a name=taxi_bj></a>
<details close>
<summary><l style="font-size:20px"><strong>Taxi BJ</strong></l> <a href=https://github.com/roryhr/taxi-trajectories>link</a> <a href=https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/viewFile/14501/13964>paper</a> <a href=https://arxiv.org/pdf/1610.00081.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of GPS data collected from 10K+ taxis in Beijing with a sampling rate of every 117 seconds
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> GPS</li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
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
    title = "{T-Drive}: Driving Directions Based on Taxi Trajectories",
    booktitle = "International Conference on Advances in Geographic Information Systems",
    pages = "99--108",
    year = "2010"
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
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Map, Temperature</li>
<li><em><strong>Task:</strong></em> Simulation</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mae">MAE</a></li>
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
<a name=cuhk_avenue></a>
<details close>
<summary><l style="font-size:20px"><strong>CUHK Avenue</strong></l> <a href=http://www.cse.cuhk.edu.hk/leojia/projects/detectabnormal/dataset.html>link</a> <a href=https://openaccess.thecvf.com/content_iccv_2013/papers/Lu_Abnormal_Event_Detection_2013_ICCV_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 37 video clips with 30K+ frames showing abnormal events
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a>, <a href=../../papers/trajectory/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, anomaly, temporal segment</li>
<li><em><strong>Task:</strong></em> Surveillance, Anomaly</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
<details close>
<summary><em>Xu et al., "Encoding Crowd Interaction With Deep Neural Network For Pedestrian Trajectory Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/2136.pdf>paper</a> <a href=https://github.com/svip-lab/CIDNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#cuhk_avenue">CUHK Avenue</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_a-d_datasets.md#ade">ADE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_e-i_datasets.md#fde">FDE</a></li>
<li><a href="../../metrics/trajectory/<built-in method lower of str object at 0x106fbad30>_alphabeticaltrajectory_a-d_datasets.md#ande">ANDE</a></li>
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
    title = "Abnormal Event Detection At 150 Fps In {M}atlab",
    booktitle = "ICCV",
    year = "2013"
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
<a name=yuv></a>
<details close>
<summary><l style="font-size:20px"><strong>YUV Videos</strong></l> <a href=http://trace.kom.aau.dk/yuv/index.html>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A collection of color video clips with different subjects and resolutions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Mix videos</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ho et al., "Deep Video Prediction Through Sparse Motion Regularization", ICIP, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9191154>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#yuv">YUV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
    title = "{YUV} Video Sequences",
    year = "2009",
    howpublished = "http://trace.kom.aau.dk/yuv/index.html"
}
</pre>
</details>

</ul></details>
<a name=ucf_sports></a>
<details close>
<summary><l style="font-size:20px"><strong>UCF Sports</strong></l> <a href=https://www.crcv.ucf.edu/data/UCF_Sports_Action.php>link</a> <a href=https://ieeexplore.ieee.org/document/4587727>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset 150 sequences with the resolution of 720 x 480 depicting 10 sport actions.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity Label</li>
<li><em><strong>Task:</strong></em> Action</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhong et al., "MMVP: Motion-Matrix-Based Video Prediction", ICCV, 2023.</em> <a href=https://openaccess.thecvf.com/content/ICCV2023/papers/Zhong_MMVP_Motion-Matrix-Based_Video_Prediction_ICCV_2023_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2308.16154.pdf>arxiv</a> <a href=https://github.com/Kay1794/MMVP-motion-matrix-based-video-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf_sports">UCF Sports</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhong_2023_ICCV,
    author = "Zhong, Yiqi and Liang, Luming and Zharkov, Ilya and Neumann, Ulrich",
    title = "MMVP: Motion-Matrix-Based Video Prediction",
    booktitle = "ICCV",
    year = "2023"
}
</pre>
</details>

</ul>
</details>
<details close>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Rodriguez_2008_CVPR,
    author = "Rodriguez, Mikel D. and Ahmed, Javed and Shah, Mubarak",
    title = "Action {MACH} a Spatio-temporal Maximum Average Correlation Height Filter for Action Recognition",
    booktitle = "CVPR",
    year = "2008"
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
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, mask, stability</li>
<li><em><strong>Task:</strong></em> Object (simulation)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Schmeckpeper et al., "Object-centric Video Prediction without Annotation", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561541>paper</a> <a href=https://arxiv.org/pdf/2105.02799.pdf>arxiv</a> <a href=https://github.com/kschmeckpeper/opa>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#shapestack">ShapeStack</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Schmeckpeper_2021_ICRA,
    author = "Schmeckpeper, Karl and Georgakis, Georgios and Daniilidis, Kostas",
    booktitle = "ICRA",
    title = "Object-centric Video Prediction without Annotation",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ye et al., "Compositional Video Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Ye_Compositional_Video_Prediction_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1908.08522.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#shapestack">ShapeStack</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
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
    title = "{ShapeStacks}: Learning Vision-Based Physical Intuition For Generalised Object Stacking",
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
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, anomaly</li>
<li><em><strong>Task:</strong></em> Surveillance, Anomaly</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#auc">AUC</a></li>
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
@InProceedings{Liu_2018_CVPR,
    author = "Liu, Wen and Luo, Weixin and Lian, Dongze and Gao, Shenghua",
    title = "Future Frame Prediction For Anomaly Detection – A New Baseline",
    booktitle = "CVPR",
    year = "2018"
}
</pre>
</details>

</ul></details>
<a name=robonet></a>
<details close>
<summary><l style="font-size:20px"><strong>RoboNet</strong></l> <a href=https://bair.berkeley.edu/blog/2019/11/26/robo-net/>link</a> <a href=http://proceedings.mlr.press/v100/dasari20a/dasari20a.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.11215.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale dataset of video of robot arms moving various objects
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Robot object manipulation</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fid">FID</a></li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#human">Human</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Dasari_2019_CORL,
    author = "Dasari, Sudeep and Ebert, Frederik and Tian, Stephen and Nair, Suraj and Bucher, Bernadette and Schmeckpeper, Karl and Singh, Siddharth and Levine, Sergey and Finn, Chelsea",
    title = "{RoboNet}: Large-scale Multi-robot Learning",
    booktitle = "CoRL",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=smtsmt></a>
<details close>
<summary><l style="font-size:20px"><strong>Something Something (SmtSmt)</strong></l> <a href=https://developer.qualcomm.com/software/ai-datasets/something-something>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Goyal_The_Something_Something_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1706.04261.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 220+ K videos of different actors interacting with various objects
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity Label</li>
<li><em><strong>Task:</strong></em> Object interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#accuracy">Accuracy</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Goya_2017_CVPR,
    author = "Goyal, Raghav and Ebrahimi Kahou, Samira and Michalski, Vincent and Materzynska, Joanna and Westphal, Susanne and Kim, Heuna and Haenel, Valentin and Fruend, Ingo and Yianilos, Peter and Mueller-Freitag, Moritz and others",
    title = "The {Something Something} Video Database for Learning and Evaluating Visual Common Sense",
    booktitle = "CVPR",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=activitynet></a>
<details close>
<summary><l style="font-size:20px"><strong>ActivityNet</strong></l> <a href=http://activity-net.org/>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Heilbron_ActivityNet_A_Large-Scale_2015_CVPR_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 648 hours of video with 100 videos per 200 different activity classes
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity Label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Rothfuss et al., "Deep Episodic Memory: Encoding, Recalling, and Predicting Episodic Experiences for Robot Action Execution", RAL, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8421022>paper</a> <a href=https://arxiv.org/pdf/1801.04134.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#activitynet">ActivityNet</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#20bn">20BN</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Rothfuss_2018_RAL,
    author = "Rothfuss, J. and Ferreira, F. and Aksoy, E. E. and Zhou, Y. and Asfour, T.",
    journal = "RAL",
    title = "Deep Episodic Memory: Encoding, Recalling, and Predicting Episodic Experiences for Robot Action Execution",
    year = "2018",
    volume = "3",
    number = "4",
    pages = "4007-4014"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Hosseinzadeh et al., "Video Captioning of Future Frames", WACV, 2021.</em> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Hosseinzadeh_Video_Captioning_of_Future_Frames_WACV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#activitynet">ActivityNet</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#swag">SWAG</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#cider">CIDEr</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_j-z_datasets.md#rouge-l">ROUGE-L</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_j-z_datasets.md#meteor">METEOR</a></li>
<li><a href="../../metrics/action/<built-in method lower of str object at 0x106fba730>_alphabeticalaction_a-d_datasets.md#bleu@n">BLEU@N</a></li>
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
@InProceedings{Caba_2015_CVPR,
    author = "Fabian Caba Heilbron, Victor Escorcia, Bernard Ghanem and Niebles, Juan Carlos",
    title = "{ActivityNet}: A Large-Scale Video Benchmark for Human Activity Understanding",
    booktitle = "CVPR",
    year = "2015"
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
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kim et al., "Unsupervised Keypoint Learning For Guiding Class-Conditional Video Prediction", NeurIPS, 2019.</em> <a href=https://papers.nips.cc/paper/8637-unsupervised-keypoint-learning-for-guiding-class-conditional-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.02027.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uva-nemo">UvA-NEMO</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mgif">MGIF</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<a name=dancing></a>
<details close>
<summary><l style="font-size:20px"><strong>Dancing</strong></l> <a href=https://github.com/NVIDIA/vid2vid>link</a> <a href=https://papers.nips.cc/paper/2018/file/d86ea612dec96096c5e0fcc8dd42ab6d-Paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1808.06601.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of body poses of single dancers
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#iou">IoU</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_a-d_datasets.md#csim">CSIM</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Ting_2018_NeurIPS,
    author = "Wang, Ting-Chun and Liu, Ming-Yu and Zhu, Jun-Yan and Liu, Guilin and Tao, Andrew and Kautz, Jan and Catanzaro, Bryan",
    booktitle = "NeurIPS",
    title = "Video-to-Video Synthesis",
    year = "2018"
}
</pre>
</details>

</ul></details>
<a name=omnipush></a>
<details close>
<summary><l style="font-size:20px"><strong>Omnipush</strong></l> <a href=https://web.mit.edu/mcube/omnipush-dataset/>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/8967920>paper</a> <a href=https://arxiv.org/pdf/1910.00618.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 250 pushes for 250 different objects recorded with RGB-D cameras.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB-D</li>
<li><em><strong>Task:</strong></em> Robot object manipulation</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Nematollahi et al., "T3VIP: Transformation-based $3\mathrmD$ Video Prediction", IROS, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9981187>paper</a> <a href=https://arxiv.org/pdf/2209.11693.pdf>arxiv</a> <a href=https://github.com/nematoli/t3vip>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#omnipush">Omnipush</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#calvin">CALVIN</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#rmse">RMSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_a-d_datasets.md#absrel">AbsRel</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Bauza_2022_IROS,
    author = "Bauza, Maria and Alet, Ferran and Lin, Yen-Chen and Lozano-Pérez, Tomás and Kaelbling, Leslie P. and Isola, Phillip and Rodriguez, Alberto",
    booktitle = "IROS",
    title = "Omnipush: Accurate, Diverse, Real-world Dataset of Pushing Dynamics with {RGB-D} Video",
    year = "2022"
}
</pre>
</details>

</ul></details>
<a name=htud></a>
<details close>
<summary><l style="font-size:20px"><strong>Human Tool Use Dataset (HTUD)</strong></l> <a href=https://sites.google.com/view/lpmfoai>link</a> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650698.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.12773.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 1000 videos of a human using different tools to push objects
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Object interaction</li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Schmeckpeper_2020_ECCV,
    author = "Schmeckpeper, Karl and Xie, Annie and Rybkin, Oleh and Tian, Stephen and Daniilidis, Kostas and Levine, Sergey and Finn, Chelsea",
    title = "Learning Predictive Models From Observation and Interaction",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul></details>
<a name=bimanual_actions></a>
<details close>
<summary><l style="font-size:20px"><strong>Bimanual Actions</strong></l> <a href=https://bimanual-actions.humanoids.kit.edu/>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/8880484>paper</a> <a href=https://arxiv.org/pdf/1908.08391.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 540 recordings of 6 subjects performing 9 basic tasks
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity Label, Bounding Box</li>
<li><em><strong>Task:</strong></em> Object interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Bodla et al., "Hierarchical Video Prediction Using Relational Layouts for Human-Object Interactions", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Bodla_Hierarchical_Video_Prediction_Using_Relational_Layouts_for_Human-Object_Interactions_CVPR_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bimanual_actions">Bimanual Actions</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bodla_2021_CVPR,
    author = "Bodla, Navaneeth and Shrivastava, Gaurav and Chellappa, Rama and Shrivastava, Abhinav",
    title = "Hierarchical Video Prediction Using Relational Layouts for Human-Object Interactions",
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
@Article{Dreher_2020_RAL,
    author = "Dreher, C. R. G. and Wächter, Mirko and Asfour, Tamim",
    journal = "RAL",
    title = "Learning Object-Action Relations from Bimanual Human Demonstration Using Graph Networks",
    year = "2020",
    volume = "5",
    number = "1",
    pages = "187-194"
}
</pre>
</details>

</ul></details>
<a name=davis17></a>
<details close>
<summary><l style="font-size:20px"><strong>DAVIS17</strong></l> <a href=https://davischallenge.org/davis2017/code.html>link</a> <a href=https://arxiv.org/pdf/1704.00675.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset consisting of 150 video sequences with over 10K frames and 376 objects with associated segmentation masks.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Segmentation</li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#rt">RT</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@article{Pont_2017_Arxiv,
    author = "Pont-Tuset, Jordi and Perazzi, Federico and Caelles, Sergi and Arbelaez, Pablo and Sorkine-Hornung, Alex and Van Gool, Luc",
    title = "The 2017 davis challenge on video object segmentation",
    journal = "arXiv:1704.00675",
    year = "2017"
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
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Face (smile)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Kim et al., "Unsupervised Keypoint Learning For Guiding Class-Conditional Video Prediction", NeurIPS, 2019.</em> <a href=https://papers.nips.cc/paper/8637-unsupervised-keypoint-learning-for-guiding-class-conditional-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1910.02027.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#uva-nemo">UvA-NEMO</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mgif">MGIF</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_e-i_datasets.md#fvd">FVD</a></li>
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
<a name=20bn></a>
<details close>
<summary><l style="font-size:20px"><strong>20BN</strong></l> <a href=https://20bn.com/datasets/something-something/v2>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Goyal_The_Something_Something_ICCV_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1706.04261.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 220K+ videos of 174 different activities
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity Label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Rothfuss et al., "Deep Episodic Memory: Encoding, Recalling, and Predicting Episodic Experiences for Robot Action Execution", RAL, 2018.</em> <a href=https://ieeexplore.ieee.org/document/8421022>paper</a> <a href=https://arxiv.org/pdf/1801.04134.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#activitynet">ActivityNet</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#20bn">20BN</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Rothfuss_2018_RAL,
    author = "Rothfuss, J. and Ferreira, F. and Aksoy, E. E. and Zhou, Y. and Asfour, T.",
    journal = "RAL",
    title = "Deep Episodic Memory: Encoding, Recalling, and Predicting Episodic Experiences for Robot Action Execution",
    year = "2018",
    volume = "3",
    number = "4",
    pages = "4007-4014"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Goyal_2017_ICCV,
    author = "Goyal, Raghav and Kahou, Samira Ebrahimi and Michalski, Vincent and Materzynska, Joanna and Westphal, Susanne and Kim, Heuna and Haenel, Valentin and Fruend, Ingo and Yianilos, Peter and Mueller-Freitag, Moritz and others",
    title = "The Something Something Video Database for Learning and Evaluating Visual Common Sense.",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=bdd100k></a>
<details close>
<summary><l style="font-size:20px"><strong>Berkeley DeepDrive (BDD100K)</strong></l> <a href=https://bair.berkeley.edu/blog/2018/05/30/bdd/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Xu_End-To-End_Learning_of_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1612.01079.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 100K driving sequences with annotations fo 10 traffic objects annotated at 10Hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Bounding Box, Semantic Segment, Lane Marking, Drivable Areas</li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Xu_2017_CVPR,
    author = "Xu, Huazhe and Gao, Yang and Yu, Fisher and Darrell, Trevor",
    title = "End-To-End Learning of Driving Models From Large-Scale Video Datasets",
    booktitle = "CVPR",
    year = "2017"
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
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Object (simulation)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hsieh et al., "Learning To Decompose And Disentangle Representations For Video Prediction", NeurIPS, 2018.</em> <a href=https://papers.nips.cc/paper/7333-learning-to-decompose-and-disentangle-representations-for-video-prediction.pdf>paper</a> <a href=https://arxiv.org/pdf/1806.04166.pdf>arxiv</a> <a href=https://github.com/jthsieh/DDPAE-video-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#bouncing_ball">Bouncing Ball</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_a-d_datasets.md#bce">BCE</a></li>
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
<a name=visor></a>
<details close>
<summary><l style="font-size:20px"><strong>ViSOR</strong></l> <a href=https://imagelab.ing.unimore.it/visor/>link</a> <a href=https://link.springer.com/article/10.1007/s11042-009-0402-9>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A repository of various surveillance footage of pedestrians in indoor and outdoor environments with 162 video clips and 1M+ frames
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, pose, attribute</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
    title = "Video Surveillance Online Repository ({VISOR}): An Integrated Framework",
    journal = "Multimedia Tools and Applications",
    volume = "50",
    number = "2",
    pages = "359--380",
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
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Reda et al., "SDC-Net: Video Prediction Using Spatially-Displaced Convolution", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Fitsum_Reda_SDC-Net_Video_prediction_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1811.00684.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#youtube-8m">Youtube-8M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#l1">L1</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Abu_2016_arxiv,
    author = "Abu-El-Haija, Sami and Kothari, Nisarg and Lee, Joonseok and Natsev, Paul and Toderici, George and Varadarajan, Balakrishnan and Vijayanarasimhan, Sudheendra",
    title = "{YouTube-8M}: A Large-Scale Video Classification Benchmark",
    journal = "arXiv:1609.08675",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=prost></a>
<details close>
<summary><l style="font-size:20px"><strong>PROST</strong></l> <a href=https://www.gpu4vision.com>link</a> <a href=https://ieeexplore.ieee.org/document/5540145>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 4K+ frames for tracking objects in the presences of camera motion
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Object</li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
    title = "{PROST}: Parallel Robust Online Simple Tracking",
    booktitle = "CVPR",
    year = "2010"
}
</pre>
</details>

</ul></details>
<a name=weizmann></a>
<details close>
<summary><l style="font-size:20px"><strong>Weizmann</strong></l> <a href=http://www.wisdom.weizmann.ac.il/~vision/SpaceTimeActions.html>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/1544882>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of actions in RGB video sequence with corresponding binary masks and activity labels
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity label, Mask</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Blank_2005_ICCV,
    author = "Blank, Moshe and Gorelick, Lena and Shechtman, Eli and Irani, Michal and Basri, Ronen",
    title = "Actions as Space-Time Shapes",
    booktitle = "ICCV",
    year = "2005"
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
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, keypoints, motion label</li>
<li><em><strong>Task:</strong></em> Face (expression)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhao et al., "Learning To Forecast And Refine Residual Motion For Image-To-Video Generation", ECCV, 2018.</em> <a href=https://openaccess.thecvf.com/content_ECCV_2018/papers/Long_Zhao_Learning_to_Forecast_ECCV_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1807.09951.pdf>arxiv</a> <a href=https://github.com/garyzhao/FRGAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mug">MUG</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#mse">MSE</a></li>
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
<a name=sjtu4k></a>
<details close>
<summary><l style="font-size:20px"><strong>SJTU4K</strong></l> <a href=https://qualinet.github.io/databases/video/sjtu_4k_video_sequence_dataset/>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset containing 15 new 4K resolution ultra-high definition (UHD) video sequences.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB</li>
<li><em><strong>Task:</strong></em> Action</li>
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
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Song_2013_QoMEX,
    author = "Song, Li and Tang, Xun and Zhang, Wei and Yang, Xiaokang and Xia, Pingjian",
    title = "The {SJTU 4K} Video Sequence Dataset",
    booktitle = "QoMEX",
    year = "2013"
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
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Depth, activity label</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Wang et al., "Order Matters: Shuffling Sequence Generation For Video Prediction", BMVC, 2019.</em> <a href=https://bmvc2019.org/wp-content/uploads/papers/1023-paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1907.08845.pdf>arxiv</a> <a href=https://github.com/andrewjywang/SEENet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#msr">MSR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
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
    title = "Action Recognition Based On A Bag Of {3D} Points",
    booktitle = "CVPRW",
    year = "2010"
}
</pre>
</details>

</ul></details>
<a name=calvin></a>
<details close>
<summary><l style="font-size:20px"><strong>Composing Actions from Language and Vision (CALVIN)</strong></l> <a href=https://github.com/mees/calvin>link</a> <a href=https://ieeexplore.ieee.org/document/9788026>paper</a> <a href=https://arxiv.org/pdf/2112.03227.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of a simulated robotic arm manipulating basic objects.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../../papers/video/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Depth, State</li>
<li><em><strong>Task:</strong></em> Simulation</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Nematollahi et al., "T3VIP: Transformation-based $3\mathrmD$ Video Prediction", IROS, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9981187>paper</a> <a href=https://arxiv.org/pdf/2209.11693.pdf>arxiv</a> <a href=https://github.com/nematoli/t3vip>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../../datasets/alphabetical/j-z_alphabetical_datasets.md#omnipush">Omnipush</a></li>
<li><a href="../../datasets/alphabetical/a-d_alphabetical_datasets.md#calvin">CALVIN</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#ssim">SSIM</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#psnr">PSNR</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#lpips">LPIPS</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_j-z_datasets.md#rmse">RMSE</a></li>
<li><a href="../../metrics/video/<built-in method lower of str object at 0x105371ef0>_alphabeticalvideo_a-d_datasets.md#absrel">AbsRel</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Mees_2022_RAL,
    author = "Mees, Oier and Hermann, Lukas and Rosete-Beas, Erick and Burgard, Wolfram",
    journal = "RAL",
    title = "{CALVIN}: A Benchmark for Language-Conditioned Policy Learning for Long-Horizon Robot Manipulation Tasks",
    volume = "7",
    number = "3",
    pages = "7327-7334",
    year = "2022"
}
</pre>
</details>

</ul></details>
</ul>