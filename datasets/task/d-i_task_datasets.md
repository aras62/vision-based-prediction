<a name=top></a>
<a name=top></a>
---
<a href=../../README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Datasets</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../metrics/metrics.md#top><l style="font-size:30px">Metrics</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
[Home](../datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Alphabetical](../alphabetical/alphabetical_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Year](../year/year_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Application](../application/application_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Task&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Annotation](../annotation_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[A-C](a-c_task_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;D-I&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[J-Z](j-z_task_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
<h2>D-I</h2> 
Within each group, the datasets are **sorted** based on their **popularity**, (i.e how often they are used in prediction papers).

 Each dataset in the list has an associated link to the publication page and/or arxiv preprint if available. By **clicking on the dataset** you can get the following information:

* **Summary** of the dataset's characteristics, e.g. quantity, number of objects or classes, etc.
* **Applications** that use the dataset
* **Data type and annotations** available in the dataset
* **Task** of the dataset, e.g. driving, activity, etc
* **Papers** that used the dataset in chronological order
* **Bibtext** of the dataset

<h2>Digit</h2>
<ul><a name=mmnist></a>
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
<summary><em>Gao et al., "SimVP: Simpler Yet Better Video Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Gao_SimVP_Simpler_Yet_Better_Video_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2206.05099.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#taxi_bj">Taxi BJ</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/video_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2022_CVPR,
    author = "Gao, Zhangyang and Tan, Cheng and Wu, Lirong and Li, Stan Z.",
    title = "SimVP: Simpler Yet Better Video Prediction",
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#town_center">Town Center</a></li>
<li><a href="../datasets/year_datasets.md#smtsmt">SmtSmt</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics/video_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chang_2021_NeurIPS,
    author = "Chang, Zheng and Zhang, Xinfeng and Wang, Shanshe and Ma, Siwei and Ye, Yan and Xinguang, Xiang and Gao, Wen",
    booktitle = "NeurIPS",
    title = "MAU: A Motion-Aware Unit for Video Prediction and Beyond",
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
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
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="../datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#taxi_bj">Taxi BJ</a></li>
<li><a href="../datasets/year_datasets.md#sst">SST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/video_metrics.md#mae">MAE</a></li>
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
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
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
<summary><em>Franceschi et al., "Stochastic latent residual video prediction", ICML, 2020.</em> <a href=http://proceedings.mlr.press/v119/franceschi20a/franceschi20a.pdf>paper</a> <a href=https://arxiv.org/pdf/2002.09219.pdf>arxiv</a> <a href=https://github.com/edouardelasalles/srvp>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="../datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics/video_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Franceschi_2020_ICML,
    author = Franceschi, Jean-Yves and Delasalles, Edouard and Chen, Micka{\"e}l and Lamprier, Sylvain and Gallinari, Patrick,
    title = "Stochastic latent residual video prediction",
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
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#penn_action">Penn Action</a></li>
<li><a href="../datasets/year_datasets.md#bair_push">BAIR Push</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#fvd">FVD</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="../datasets/year_datasets.md#weizmann">Weizmann</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
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
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics/video_metrics.md#fvd">FVD</a></li>
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
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
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
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
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
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
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
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/video_metrics.md#bce">BCE</a></li>
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
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
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
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
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
<li><a href="../metrics/video_metrics.md#human">Human</a></li>
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
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
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
<li><a href="../metrics/other_metrics.md#nll">NLL</a></li>
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
</ul><h2>Diving</h2>
<ul><a name=vdd-c></a>
<details close>
<summary><l style="font-size:20px"><strong>VDD-C</strong></l> <a href=https://conservancy.umn.edu/handle/11299/219383>link</a> <a href=https://arxiv.org/pdf/2012.05701.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 100k images of under water diving recorded in Caribbean coasts
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, 2D Bounding Box</li>
<li><em><strong>Task:</strong></em> Diving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Agarwal et al., "Predicting the Future Motion of Divers for Enhanced Underwater Human-Robot Collaboration", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636374>paper</a> <a href=https://github.com/IRVLab/diver-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#vdd-c">VDD-C</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#iou">IoU</a></li>
<li><a href="../metrics/trajectory_metrics.md#bnace">BNACE</a></li>
<li><a href="../metrics/trajectory_metrics.md#inace">INACE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Agarwal_2021_IROS,
    author = "Agarwal, Tanmay and Fulton, Michael and Sattar, Junaed",
    booktitle = "IROS",
    title = "Predicting the Future Motion of Divers for Enhanced Underwater Human-Robot Collaboration",
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
@Article{Langis_2021_arxiv,
    author = "de Langis, Karin and Fulton, Michael and Sattar, Junaed",
    journal = "arxiv",
    title = "An Analysis of Deep Object Detectors For Diver Detection",
    year = "2021"
}
</pre>
</details>

</ul></details>
</ul><h2>Driving</h2>
<ul><a name=nuscenes></a>
<details close>
<summary><l style="font-size:20px"><strong>nuScenes</strong></l> <a href=https://www.nuscenes.org/>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Caesar_nuScenes_A_Multimodal_Dataset_for_Autonomous_Driving_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1903.11027.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset with 1K driving sequences and 1M+ 3D bounding boxes annotated at 2hz
</li>
<li>
<em><strong>Applications:</strong></em> </li>
<li><em><strong>Data type and annotations:</strong></em> RGB, LIDAR, 3D Bounding Box, Object Class, Attribute, Map, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Schmeckpeper et al., "Learning Predictive Models From Observation and Interaction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650698.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.12773.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#htud">HTUD</a></li>
<li><a href="../datasets/year_datasets.md#bdd100k">BDD100K</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
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
<summary><em>Chen et al., "ScePT: Scene-Consistent, Policy-Based Trajectory Predictions for Planning", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Chen_ScePT_Scene-Consistent_Policy-Based_Trajectory_Predictions_for_Planning_CVPR_2022_paper.pdf>paper</a> <a href=https://github.com/nvr-avg/ScePT>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2022_CVPR,
    author = "Chen, Yuxiao and Ivanovic, Boris and Pavone, Marco",
    title = "ScePT: Scene-Consistent, Policy-Based Trajectory Predictions for Planning",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#kde">KDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#ecfl">ECFL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lee_2022_CVPR,
    author = "Lee, Mihee and Sohn, Samuel S. and Moon, Seonghyeon and Yoon, Sejong and Kapadia, Mubbasir and Pavlovic, Vladimir",
    title = "MUSE-VAE: Multi-Scale VAE for Environment-Aware Long Term Trajectory Prediction",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#ap">AP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Peri_2022_CVPR,
    author = "Peri, Neehar and Luiten, Jonathon and Li, Mengtian and O\v{s}ep, Aljo\v{s}a and Leal-Taix\'e, Laura and Ramanan, Deva",
    title = "Forecasting From LiDAR via Future Object Detection",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2022_CVPR_2,
    author = "Wang, Yunlong and Pan, Hongyu and Zhu, Jun and Wu, Yu-Huan and Zhan, Xin and Jiang, Kun and Yang, Diange",
    title = "BE-STI: Spatial-Temporal Integrated Network for Class-Agnostic Motion Prediction With Bidirectional Enhancement",
    booktitle = "CVPR",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#ed">ED</a></li>
<li><a href="../metrics/trajectory_metrics.md#kld">KLD</a></li>
<li><a href="../metrics/trajectory_metrics.md#l1">L1</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Deyao_2021_ICLR,
    author = "Zhu, Deyao and Zahran, Mohamed and Li, Li Erran and Elhoseiny, Mohamed",
    booktitle = "ICLR",
    title = "HalentNet: Multimodal Trajectory Forecasting with Hallucinative Intents",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#euro-pvi">Euro-PVI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bhattacharyya_2021_CVPR,
    author = "Bhattacharyya, Apratim and Reino, Daniel Olmeda and Fritz, Mario and Schiele, Bernt",
    title = "Euro-PVI: Pedestrian Vehicle Interactions in Dense Urban Centers",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kim_2021_CVPR,
    author = "Kim, ByeoungDo and Park, Seong Hyeon and Lee, Seokhwan and Khoshimjonov, Elbek and Kum, Dongsuk and Kim, Junsoo and Kim, Jeong Soo and Choi, Jun Won",
    title = "LaPred: Lane-Aware Prediction of Multi-Modal Future Trajectories of Dynamic Agents",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#cpi">CPI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#emd">EMD</a></li>
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
<summary><em>Hu et al., "FIERY: Future Instance Prediction in Bird's-Eye View From Surround Monocular Cameras", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Hu_FIERY_Future_Instance_Prediction_in_Birds-Eye_View_From_Surround_Monocular_ICCV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#iou">IoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2021_ICCV,
    author = "Hu, Anthony and Murez, Zak and Mohan, Nikhil and Dudas, Sofia and Hawke, Jeffrey and Badrinarayanan, Vijay and Cipolla, Roberto and Kendall, Alex",
    title = "FIERY: Future Instance Prediction in Bird's-Eye View From Surround Monocular Cameras",
    booktitle = "ICCV",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfsd">minFSD</a></li>
<li><a href="../metrics/trajectory_metrics.md#minasd">minASD</a></li>
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
<summary><em>Ren et al., "Safety-Aware Motion Prediction With Unseen Vehicles for Autonomous Driving", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Ren_Safety-Aware_Motion_Prediction_With_Unseen_Vehicles_for_Autonomous_Driving_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2109.01510.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/trajectory_metrics.md#ur">UR</a></li>
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
<summary><em>Zheng et al., "Unlimited Neighborhood Interaction for Heterogeneous Trajectory Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Zheng_Unlimited_Neighborhood_Interaction_for_Heterogeneous_Trajectory_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2108.00238.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2021_ICCV_2,
    author = "Li, Jiachen and Yang, Fan and Ma, Hengbo and Malla, Srikanth and Tomizuka, Masayoshi and Choi, Chiho",
    title = "RAIN: Reinforced Hybrid Attention Inference Network for Motion Forecasting",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#orr">ORR</a></li>
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
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
<summary><em>Dulian et al., "Exploiting latent representation of sparse semantic layers for improved short-term motion prediction with Capsule Networks", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561467>paper</a> <a href=https://arxiv.org/pdf/2103.01644.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Dulian_2021_ICRA,
    author = "Dulian, Albert and Murray, John C.",
    booktitle = "ICRA",
    title = "Exploiting latent representation of sparse semantic layers for improved short-term motion prediction with Capsule Networks",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#maxd">MaxD</a></li>
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
<summary><em>Meyer et al., "LaserFlow: Efficient and Probabilistic Object Detection and Motion Forecasting", RAL, 2017.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9310205>paper</a> <a href=https://arxiv.org/pdf/2003.05982.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#l2">L2</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Meyer_2021_RAL,
    author = "Meyer, Gregory P. and Charland, Jake and Pandey, Shreyash and Laddha, Ankit and Gautam, Shivam and Vallespi-Gonzalez, Carlos and Wellington, Carl K.",
    journal = "RAL",
    title = "LaserFlow: Efficient and Probabilistic Object Detection and Motion Forecasting",
    year = "2017",
    volume = "6",
    number = "2",
    pages = "526-533"
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#tcr">TCR</a></li>
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Laddha_2021_IROS,
    author = "Laddha, Ankit and Gautam, Shivam and Meyer, Gregory P. and Vallespi-Gonzalez, Carlos and Wellington, Carl K.",
    booktitle = "IROS",
    title = "RV-FuseNet: Range View Based Fusion of Time-Series LiDAR Data for Joint 3D Object Detection and Motion Forecasting",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ed">ED</a></li>
<li><a href="../metrics/trajectory_metrics.md#mane">MAnE</a></li>
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
<summary><em>Kawasaki et al., "Multimodal Trajectory Predictions for Autonomous Driving Without a Detailed Prior Map", WACV, 2021.</em> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Kawasaki_Multimodal_Trajectory_Predictions_for_Autonomous_Driving_Without_a_Detailed_Prior_WACV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
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
<summary><em>Hu et al., "Collaborative Motion Prediction via Neural Motion Message Passing", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Hu_Collaborative_Motion_Prediction_via_Neural_Motion_Message_Passing_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.06594.pdf>arxiv</a> <a href=https://github.com/PhyllisH/NMMP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liang_2020_CVPR,
    author = "Liang, Ming and Yang, Bin and Zeng, Wenyuan and Chen, Yun and Hu, Rui and Casas, Sergio and Urtasun, Raquel",
    title = "PnPNet: End-to-End Perception and Prediction With Tracking in the Loop",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/year_datasets.md#fit">FIT</a></li>
<li><a href="../datasets/year_datasets.md#mapillary_vistas">Mapillary Vistas</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#iou">IoU</a></li>
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Phan-Minh_2020_CVPR,
    author = "Phan-Minh, Tung and Grigore, Elena Corina and Boulton, Freddy A. and Beijbom, Oscar and Wolff, Eric M.",
    title = "CoverNet: Multimodal Behavior Prediction Using Trajectory Sets",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wu_2020_CVPR_2,
    author = "Wu, Pengxiang and Chen, Siheng and Metaxas, Dimitris N.",
    title = "MotionNet: Joint Perception and Motion Prediction for Autonomous Driving Based on Bird's Eye View Maps",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Casas et al., "Implicit latent variable model for scene-consistent motion forecasting", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123680613.pdf>paper</a> <a href=https://arxiv.org/pdf/2007.12036.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#scr">SCR</a></li>
<li><a href="../metrics/trajectory_metrics.md#meansfde">meanSFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#meansade">meanSADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minsfde">minSFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minsade">minSADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Casas_2020_ECCV,
    author = "Casas, Sergio and Gulino, Cole and Suo, Simon and Luo, Katie and Liao, Renjie and Urtasun, Raquel",
    title = "Implicit latent variable model for scene-consistent motion forecasting",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#meanfde">meanFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#meanade">meanADE</a></li>
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
<summary><em>Salzmann et al., "Trajectron++: Multi-agent generative trajectory forecasting with heterogeneous data for control", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123630664.pdf>paper</a> <a href=https://arxiv.org/pdf/2001.03093.pdf>arxiv</a> <a href=https://github.com/StanfordASL/Trajectron-plus-plus>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Salzmann_2020_ECCV,
    author = "Salzmann, Tim and Ivanovic, Boris and Chakravarty, Punarjay and Pavone, Marco",
    title = "Trajectron++: Multi-agent generative trajectory forecasting with heterogeneous data for control",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Casas_2020_ICRA,
    author = "Casas, S. and Gulino, C. and Liao, R. and Urtasun, R.",
    booktitle = "ICRA",
    title = "SpAGNN: Spatially-Aware Graph Neural Networks for Relational Behavior Forecasting from Sensor Data",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fle">FLE</a></li>
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#tcr">TCR</a></li>
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
<summary><em>Buhet et al., "PLOP: Probabilistic poLynomial Objects trajectory Planning for autonomous driving", CoRL, 2020.</em> <a href=https://drive.google.com/file/d/1--QAL2sR7KMk9R4DwxyfJAT5iGCheFrn/view>paper</a> <a href=https://arxiv.org/pdf/2003.08744.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#a2d2">A2D2</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minmsd">minMSD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Buhet_2020_CORL,
    author = "Buhet, Thibault and Wirbel, Emilie and Bursuc, Andrei and Perrotton, Xavier",
    title = "PLOP: Probabilistic poLynomial Objects trajectory Planning for autonomous driving",
    booktitle = "CoRL",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ivanovic et al., "MATS: An Interpretable Trajectory Forecasting Representation for Planning and Control", CoRL, 2020.</em> <a href=https://drive.google.com/file/d/1kQ3I2AYhC01Pc-BNBu7I_J54m85H82a-/view>paper</a> <a href=https://arxiv.org/pdf/2009.07517.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ivanovic_2020_CORL,
    author = "Ivanovic, Boris and Elhafsi, Amine and Rosman, Guy and Gaidon, Adrien and Pavone, Marco",
    title = "MATS: An Interpretable Trajectory Forecasting Representation for Planning and Control",
    booktitle = "CoRL",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Li et al., "Differentiable logic layer for rule guided trajectory prediction", CoRL, 2020.</em> <a href=https://drive.google.com/file/d/1XxYxO_doBjFy70ruodwikpCJB9htrdIV/view>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#maxd">MaxD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2020_CORL,
    author = "Li, Xiao and Rosman, Guy and Gilitschenski, Igor and DeCastro, Jonathan and Vasile, Cristian-Ioan and Rus, Sertac Karaman Daniela",
    title = "Differentiable logic layer for rule guided trajectory prediction",
    year = "2020",
    booktitle = "CoRL"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Shah et al., "LiRaNet: End-to-End Trajectory Prediction using Spatio-Temporal Radar Fusion", CoRL, 2020.</em> <a href=https://drive.google.com/file/d/1DHcWIcLQpJAozpHQT1XRzkNP2MR3Ilja/view>paper</a> <a href=https://arxiv.org/pdf/2010.00731.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shah_2020_CORL,
    author = "Shah, Meet and Huang, Zhiling and Laddha, Ankit and Langford, Matthew and Barber, Blake and Zhang, Sidney and Vallespi-Gonzalez, Carlos and Urtasun, Raquel",
    title = "LiRaNet: End-to-End Trajectory Prediction using Spatio-Temporal Radar Fusion",
    booktitle = "CoRL",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Weng et al., "Inverting the Pose Forecasting Pipeline with SPF2: Sequential Pointcloud Forecasting for Sequential Pose Forecasting", CoRL, 2020.</em> <a href=https://drive.google.com/file/d/1G-9Pjp4K_RVDKL7OdoX7_fCphGGHapB2/view>paper</a> <a href=https://arxiv.org/pdf/2003.08376.pdf>arxiv</a> <a href=https://github.com/xinshuoweng/SPF2>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Weng_2020_CORL,
    author = "Weng, Xinshuo and Wang, Jianren and Levine, Sergey and Kitani, Kris and Rhinehart, Nick",
    title = "Inverting the Pose Forecasting Pipeline with SPF2: Sequential Pointcloud Forecasting for Sequential Pose Forecasting",
    booktitle = "CoRL",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhang et al., "Map-Adaptive Goal-Based Trajectory Prediction", CoRL, 2020.</em> <a href=https://drive.google.com/file/d/1Gwd2P1div60UHxHa3eq373ZDrwbzkQzG/view>paper</a> <a href=https://arxiv.org/pdf/2009.04450.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minmsd">minMSD</a></li>
<li><a href="../metrics/trajectory_metrics.md#meanmsd">meanMSD</a></li>
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
<summary><em>Hu et al., "Safe Local Motion Planning With Self-Supervised Freespace Forecasting", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Hu_Safe_Local_Motion_Planning_With_Self-Supervised_Freespace_Forecasting_CVPR_2021_paper.pdf>paper</a> <a href=https://github.com/peiyunh/ff>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/other_metrics.md#f1">F1</a></li>
<li><a href="../metrics/other_metrics.md#ap">AP</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Caesar_2020_CVPR,
    author = "Caesar, Holger and Bankiti, Varun and Lang, Alex H. and Vora, Sourabh and Liong, Venice Erin and Xu, Qiang and Krishnan, Anush and Pan, Yu and Baldan, Giancarlo and Beijbom, Oscar",
    title = "nuScenes: A Multimodal Dataset for Autonomous Driving",
    booktitle = "Proceedings of the CVPR",
    year = "2020"
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
<summary><em>Zaech et al., "Action Sequence Predictions of Vehicles in Urban Environments using Map and Social Context", IROS, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9340643>paper</a> <a href=https://arxiv.org/pdf/2004.14251.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#ap">AP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zaech_2020_IROS,
    author = "Zaech, J. -N. and Dai, D. and Liniger, A. and Gool, L. V.",
    booktitle = "IROS",
    title = "Action Sequence Predictions of Vehicles in Urban Environments using Map and Social Context",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Bahari et al., "Vehicle Trajectory Prediction Works, but Not Everywhere", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Bahari_Vehicle_Trajectory_Prediction_Works_but_Not_Everywhere_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2112.03909.pdf>arxiv</a> <a href=https://s-attack.github.io/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#sor">SOR</a></li>
<li><a href="../metrics/trajectory_metrics.md#hor">HOR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bahari_2022_CVPR,
    author = "Bahari, Mohammadhossein and Saadatnejad, Saeed and Rahimi, Ahmad and Shaverdikondori, Mohammad and Shahidzadeh, Amir Hossein and Moosavi-Dezfooli, Seyed-Mohsen and Alahi, Alexandre",
    title = "Vehicle Trajectory Prediction Works, but Not Everywhere",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhou et al., "HiVT: Hierarchical Vector Transformer for Multi-Agent Motion Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Zhou_HiVT_Hierarchical_Vector_Transformer_for_Multi-Agent_Motion_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://github.com/ZikangZhou/HiVT>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhou_2022_CVPR,
    author = "Zhou, Zikang and Ye, Luyao and Wang, Jianping and Wu, Kui and Lu, Kejie",
    title = "HiVT: Hierarchical Vector Transformer for Multi-Agent Motion Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "LTP: Lane-Based Trajectory Prediction for Autonomous Driving", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_LTP_Lane-Based_Trajectory_Prediction_for_Autonomous_Driving_CVPR_2022_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2022_CVPR_3,
    author = "Wang, Jingke and Ye, Tengju and Gu, Ziqing and Chen, Junbo",
    title = "LTP: Lane-Based Trajectory Prediction for Autonomous Driving",
    booktitle = "CVPR",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#ed">ED</a></li>
<li><a href="../metrics/trajectory_metrics.md#kld">KLD</a></li>
<li><a href="../metrics/trajectory_metrics.md#l1">L1</a></li>
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
<summary><em>Walters et al., "Trajectory Prediction using Equivariant Continuous Convolution", ICLR, 2021.</em> <a href=https://openreview.net/pdf?id=J8_GttYLFgr>paper</a> <a href=https://arxiv.org/pdf/2010.11344.pdf>arxiv</a> <a href=https://github.com/Rose-STL-Lab/ECCO>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#trajnet++">Trajnet++</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#ed">ED</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Robin_2021_ICLR,
    author = "Walters, Robin and Li, Jinxi and Yu, Rose",
    booktitle = "ICLR",
    title = "Trajectory Prediction using Equivariant Continuous Convolution",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Amirloo et al., "Self-Supervised Simultaneous Multi-Step Prediction of Road Dynamics and Cost Map", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Amirloo_Self-Supervised_Simultaneous_Multi-Step_Prediction_of_Road_Dynamics_and_Cost_Map_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2103.01039.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#tcr">TCR</a></li>
<li><a href="../metrics/trajectory_metrics.md#rv">RV</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Amirloo_2021_CVPR,
    author = "Amirloo, Elmira and Rohani, Mohsen and Banijamali, Ershad and Luo, Jun and Poupart, Pascal",
    title = "Self-Supervised Simultaneous Multi-Step Prediction of Road Dynamics and Cost Map",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kim_2021_CVPR,
    author = "Kim, ByeoungDo and Park, Seong Hyeon and Lee, Seokhwan and Khoshimjonov, Elbek and Kum, Dongsuk and Kim, Junsoo and Kim, Jeong Soo and Choi, Jun Won",
    title = "LaPred: Lane-Aware Prediction of Multi-Modal Future Trajectories of Dynamic Agents",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liu et al., "Multimodal Motion Prediction With Stacked Transformers", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Liu_Multimodal_Motion_Prediction_With_Stacked_Transformers_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2103.11624.pdf>arxiv</a> <a href=https://github.com/decisionforce/mmTransformer>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2021_CVPR,
    author = "Liu, Yicheng and Zhang, Jinghuai and Fang, Liangji and Jiang, Qinhong and Zhou, Bolei",
    title = "Multimodal Motion Prediction With Stacked Transformers",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ye et al., "TPCN: Temporal Point Cloud Networks for Motion Forecasting", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Ye_TPCN_Temporal_Point_Cloud_Networks_for_Motion_Forecasting_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2103.03067.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ye_2021_CVPR,
    author = "Ye, Maosheng and Cao, Tongyi and Chen, Qifeng",
    title = "TPCN: Temporal Point Cloud Networks for Motion Forecasting",
    booktitle = "CVPR",
    year = "2021"
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
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/trajectory_metrics.md#tn">TN</a></li>
<li><a href="../metrics/trajectory_metrics.md#tp">TP</a></li>
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
<summary><em>Gu et al., "DenseTNT: End-to-End Trajectory Prediction From Dense Goal Sets", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Gu_DenseTNT_End-to-End_Trajectory_Prediction_From_Dense_Goal_Sets_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2108.09640.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#waymo">Waymo</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gu_2021_ICCV,
    author = "Gu, Junru and Sun, Chen and Zhao, Hang",
    title = "DenseTNT: End-to-End Trajectory Prediction From Dense Goal Sets",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Tolstaya et al., "Identifying Driver Interactions via Conditional Behavior Prediction", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561967>paper</a> <a href=https://arxiv.org/pdf/2104.09959.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#wade">wADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tolstaya_2021_ICRA,
    author = "Tolstaya, Ekaterina and Mahjourian, Reza and Downey, Carlton and Vadarajan, Balakrishnan and Sapp, Benjamin and Anguelov, Dragomir",
    booktitle = "ICRA",
    title = "Identifying Driver Interactions via Conditional Behavior Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "Multiple Contextual Cues Integrated Trajectory Prediction for Autonomous Driving", RAL, 2021.</em> <a href=https://ieeexplore.ieee.org/document/9476975>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#wade">wADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#wfde">wFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Wang_2021_RAL,
    author = "Wang, Li and Wu, Tao and Fu, Hao and Xiao, Liang and Wang, Zhiyu and Dai, Bin",
    journal = "RAL",
    title = "Multiple Contextual Cues Integrated Trajectory Prediction for Autonomous Driving",
    year = "2021",
    volume = "6",
    number = "4",
    pages = "6844-6851"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Rella et al., "Decoder Fusion RNN: Context and Interaction Aware Decoders for Trajectory Prediction", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636577>paper</a> <a href=https://arxiv.org/pdf/2108.05814.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#dac">DAC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Rella_2021_IROS,
    author = "Rella, Edoardo Mello and Zaech, Jan-Nico and Liniger, Alexander and Van Gool, Luc",
    booktitle = "IROS",
    title = "Decoder Fusion RNN: Context and Interaction Aware Decoders for Trajectory Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zeng et al., "LaneRCNN: Distributed Representations for Graph-Centric Motion Forecasting", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636035>paper</a> <a href=https://arxiv.org/pdf/2101.06653.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zeng_2021_IROS,
    author = "Zeng, Wenyuan and Liang, Ming and Liao, Renjie and Urtasun, Raquel",
    booktitle = "IROS",
    title = "LaneRCNN: Distributed Representations for Graph-Centric Motion Forecasting",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
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
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#dac">DAC</a></li>
<li><a href="../metrics/trajectory_metrics.md#wsfde">WSFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#wsade">WSADE</a></li>
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
<summary><em>Liang et al., "Learning lane graph representations for motion forecasting", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470528.pdf>paper</a> <a href=https://arxiv.org/pdf/2007.13732.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liang_2020_ECCV_2,
    author = "Liang, Ming and Yang, Bin and Hu, Rui and Chen, Yun and Liao, Renjie and Feng, Song and Urtasun, Raquel",
    title = "Learning lane graph representations for motion forecasting",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liu et al., "SMART: Simultaneous Multi-Agent Recurrent Trajectory Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123720460.pdf>paper</a> <a href=https://arxiv.org/pdf/2007.13078.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2020_ECCV_2,
    author = "Liu, Buyu and Pittaluga, Francesco and Chandraker, Manmohan and others",
    title = "SMART: Simultaneous Multi-Agent Recurrent Trajectory Prediction",
    booktitle = "ECCV",
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
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
<li><a href="../datasets/year_datasets.md#virat/actev">VIRAT/ActEV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liang_2020_ECCV,
    author = "Liang, Junwei and Jiang, Lu and Hauptmann, Alexander",
    title = "SimAug: Learning Robust Representations from Simulation for Trajectory Prediction",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#meanfde">meanFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#meanade">meanADE</a></li>
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
<summary><em>Biktairov et al., "PRANK: motion Prediction based on RANKing", NeurIPS, 2020.</em> <a href=https://papers.nips.cc/paper/2020/file/1b0251ccb8bd5f9ccf444e4bda7713e3-Paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2010.12007.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#ll">LL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Biktairov_2020_NeurIPS,
    author = "Biktairov, Yuriy and Stebelev, Maxim and Rudenko, Irina and Shliazhko, Oleh and Yangel, Boris",
    editor = "Larochelle, H. and Ranzato, M. and Hadsell, R. and Balcan, M. F. and Lin, H.",
    booktitle = "NeurIPS",
    title = "PRANK: motion Prediction based on RANKing",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Kawasaki et al., "Multimodal Trajectory Predictions for Urban Environments Using Geometric Relationships between a Vehicle and Lanes", ICRA, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9196738>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kawasaki_2020_ICRA,
    author = "Kawasaki, A. and Seki, A.",
    booktitle = "ICRA",
    title = "Multimodal Trajectory Predictions for Urban Environments Using Geometric Relationships between a Vehicle and Lanes",
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
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
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
<summary><em>Luo et al., "Probabilistic Multi-modal Trajectory Prediction with Lane Attention for Autonomous Vehicles", IROS, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9341034>paper</a> <a href=https://arxiv.org/pdf/2007.02574.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Luo_2020_IROS,
    author = "Luo, C. and Sun, L. and Dabiri, D. and Yuille, A.",
    booktitle = "IROS",
    title = "Probabilistic Multi-modal Trajectory Prediction with Lane Attention for Autonomous Vehicles",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Strohbeck et al., "Multiple Trajectory Prediction with Deep Temporal and Spatial Convolutional Neural Networks", IROS, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9341327>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#dac">DAC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Strohbeck_2020_IROS,
    author = "Strohbeck, J. and Belagiannis, V. and Müller, J. and Schreiber, M. and Herrmann, M. and Wolf, D. and Buchholz, M.",
    booktitle = "IROS",
    title = "Multiple Trajectory Prediction with Deep Temporal and Spatial Convolutional Neural Networks",
    year = "2020"
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
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#apolloscape">ApolloScape</a></li>
<li><a href="../datasets/year_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Chandra_2020_RAL,
    author = "Chandra, R. and Guan, T. and Panuganti, S. and Mittal, T. and Bhattacharya, U. and Bera, A. and Manocha, D.",
    journal = "RAL",
    title = "Forecasting Trajectory and Behavior of Road-Agents Using Spectral Clustering in Graph-LSTMs",
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
<summary><em>Huang et al., "DiversityGAN: Diversity-Aware Vehicle Motion Prediction via Latent Semantic Sampling", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9127831>paper</a> <a href=https://arxiv.org/pdf/1911.12736.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Huang_2020_RAL,
    author = "Huang, X. and McGill, S. G. and DeCastro, J. A. and Fletcher, L. and Leonard, J. J. and Williams, B. C. and Rosman, G.",
    journal = "RAL",
    title = "DiversityGAN: Diversity-Aware Vehicle Motion Prediction via Latent Semantic Sampling",
    year = "2020",
    volume = "5",
    number = "4",
    pages = "5089-5096"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhao et al., "Tnt: Target-driven trajectory prediction", CoRL, 2020.</em> <a href=https://drive.google.com/file/d/1Ol40GkiELqcechS9eWINoacMb5ebDUkD/view>paper</a> <a href=https://arxiv.org/pdf/2008.08294.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
<li><a href="../datasets/year_datasets.md#interaction">INTERACTION</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#miss_rate">Miss rate</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhao_2020_CORL,
    author = "Zhao, Hang and Gao, Jiyang and Lan, Tian and Sun, Chen and Sapp, Benjamin and Varadarajan, Balakrishnan and Shen, Yue and Shen, Yi and Chai, Yuning and Schmid, Cordelia and others",
    title = "Tnt: Target-driven trajectory prediction",
    booktitle = "CoRL",
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
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
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
<summary><em>Geng et al., "Comparing Correspondences: Video Prediction With Correspondence-Wise Losses", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Geng_Comparing_Correspondences_Video_Prediction_With_Correspondence-Wise_Losses_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2104.09498.pdf>arxiv</a> <a href=https://github.com/dangeng/CorrWiseLosses>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#town_center">Town Center</a></li>
<li><a href="../datasets/year_datasets.md#smtsmt">SmtSmt</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics/video_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chang_2021_NeurIPS,
    author = "Chang, Zheng and Zhang, Xinfeng and Wang, Shanshe and Ma, Siwei and Ye, Yan and Xinguang, Xiang and Gao, Wen",
    booktitle = "NeurIPS",
    title = "MAU: A Motion-Aware Unit for Video Prediction and Beyond",
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#dancing">Dancing</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#fvd">FVD</a></li>
<li><a href="../metrics/video_metrics.md#iou">IoU</a></li>
<li><a href="../metrics/video_metrics.md#csim">CSIM</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#robonet">RoboNet</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics/video_metrics.md#fvd">FVD</a></li>
<li><a href="../metrics/video_metrics.md#human">Human</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/video_metrics.md#is">IS</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lange_2021_IROS,
    author = "Lange, Bernard and Itkina, Masha and Kochenderfer, Mykel J.",
    booktitle = "IROS",
    title = "Attention Augmented ConvLSTM for Environment Prediction",
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#bair">BAIR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics/video_metrics.md#fvd">FVD</a></li>
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
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics/video_metrics.md#ms-ssim">MS-SSIM</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#chuk_avenue">CHUK Avenue</a></li>
<li><a href="../datasets/year_datasets.md#shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
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
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
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
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
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
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#sports-1m">Sports-1M</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#ap">AP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Filatov_2020_ICRA,
    author = "Filatov, A. and Rykov, A. and Murashkin, V.",
    booktitle = "ICRA",
    title = "Any Motion Detector: Learning Class-agnostic Scene Dynamics from a Sequence of LiDAR Point Clouds",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#h3d">H3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Marchetti et al., "MANTRA: Memory Augmented Networks for Multiple Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Marchetti_MANTRA_Memory_Augmented_Networks_for_Multiple_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.03340.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#orc">ORC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Weng et al., "Inverting the Pose Forecasting Pipeline with SPF2: Sequential Pointcloud Forecasting for Sequential Pose Forecasting", CoRL, 2020.</em> <a href=https://drive.google.com/file/d/1G-9Pjp4K_RVDKL7OdoX7_fCphGGHapB2/view>paper</a> <a href=https://arxiv.org/pdf/2003.08376.pdf>arxiv</a> <a href=https://github.com/xinshuoweng/SPF2>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Weng_2020_CORL,
    author = "Weng, Xinshuo and Wang, Jianren and Levine, Sergey and Kitani, Kris and Rhinehart, Nick",
    title = "Inverting the Pose Forecasting Pipeline with SPF2: Sequential Pointcloud Forecasting for Sequential Pose Forecasting",
    booktitle = "CoRL",
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
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
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
<li><a href="../metrics/trajectory_metrics.md#minmsd">minMSD</a></li>
<li><a href="../metrics/trajectory_metrics.md#meanmsd">meanMSD</a></li>
<li><a href="../metrics/trajectory_metrics.md#ce">CE</a></li>
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
<li><a href="../metrics/trajectory_metrics.md#ed">ED</a></li>
<li><a href="../metrics/trajectory_metrics.md#miss_rate">Miss rate</a></li>
<li><a href="../metrics/trajectory_metrics.md#mined">minED</a></li>
<li><a href="../metrics/trajectory_metrics.md#maxd">maxD</a></li>
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
<li><a href="../metrics/other_metrics.md#run_time">Run Time</a></li>
<li><a href="../metrics/other_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/other_metrics.md#tp">TP</a></li>
<li><a href="../metrics/other_metrics.md#tn">TN</a></li>
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
<li><a href="../metrics/other_metrics.md#f1">F1</a></li>
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
<summary><l style="font-size:20px"><strong>Next Generation Simulation (NGSIM)</strong></l> <a href=https://catalog.data.gov/dataset/next-generation-simulation-ngsim-vehicle-trajectories>link</a></summary> 
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
<summary><em>Berlati et al., "Ambiguity in Sequential Data: Predicting Uncertain Futures With Recurrent Models", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9001185>paper</a> <a href=https://arxiv.org/pdf/2003.10381.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#recall">Recall</a></li>
<li><a href="../metrics/action_metrics.md#precision">Precision</a></li>
<li><a href="../metrics/action_metrics.md#f1">F1</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#recall">Recall</a></li>
<li><a href="../metrics/action_metrics.md#precision">Precision</a></li>
<li><a href="../metrics/action_metrics.md#f1">F1</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics/action_metrics.md#recall">Recall</a></li>
<li><a href="../metrics/action_metrics.md#precision">Precision</a></li>
<li><a href="../metrics/action_metrics.md#ttm">TTM</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Banijamali et al., "Prediction by Anticipation: An Action-Conditional Prediction Method Based on Interaction Learning", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Banijamali_Prediction_by_Anticipation_An_Action-Conditional_Prediction_Method_Based_on_Interaction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2012.13478.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/trajectory_metrics.md#tn">TN</a></li>
<li><a href="../metrics/trajectory_metrics.md#tp">TP</a></li>
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
<summary><em>Xie et al., "Congestion-aware Multi-agent Trajectory Prediction for Collision Avoidance", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9560994>paper</a> <a href=https://github.com/xuxie1031/CollisionFreeMultiAgentTrajectoryPrediciton>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
<li><a href="../metrics/trajectory_metrics.md#tcr">TCR</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#highd">HighD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
<li><a href="../metrics/trajectory_metrics.md#qde">QDE</a></li>
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
<summary><em>Mersch et al., "Maneuver-based Trajectory Prediction for Self-driving Cars Using Spatio-temporal Convolutional Networks", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636875>paper</a> <a href=https://arxiv.org/pdf/2109.07365.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#highd">HighD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#highd">HighD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Song_2020_ECCV,
    author = "Song, Haoran and Ding, Wenchao and Chen, Yuxuan and Shen, Shaojie and Wang, Michael Yu and Chen, Qifeng",
    title = "PiP: Planning-informed Trajectory Prediction for Autonomous Driving",
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#nba">NBA</a></li>
<li><a href="../datasets/year_datasets.md#charges">Charges</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mercat_2020_ICRA,
    author = "Mercat, J. and Gilles, T. and El Zoghby, N. and Sandou, G. and Beauvois, D. and Gil, G. P.",
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#highd">HighD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jeon_2020_IROS,
    author = "Jeon, H. and Choi, J. and Kum, D.",
    booktitle = "IROS",
    title = "SCALE-Net: Scalable Vehicle Trajectory Prediction Network under Random Number of Interacting Vehicles via Edge-enhanced Graph Convolutional Neural Network",
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#apolloscape">ApolloScape</a></li>
<li><a href="../datasets/year_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Chandra_2020_RAL,
    author = "Chandra, R. and Guan, T. and Panuganti, S. and Mittal, T. and Bhattacharya, U. and Bera, A. and Manocha, D.",
    journal = "RAL",
    title = "Forecasting Trajectory and Behavior of Road-Agents Using Spectral Clustering in Graph-LSTMs",
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2020_ICIP,
    author = "Chen, Guangxi and Hu, Ling and Zhang, Qieshi and Ren, Ziliang and Gao, Xiangyang and Cheng, Jun",
    booktitle = "ICIP",
    title = "ST-LSTM: Spatio-Temporal Graph Based Long Short-Term Memory Network For Vehicle Trajectory Prediction",
    year = "2020"
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
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
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
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../metrics/trajectory_metrics.md#ll">LL</a></li>
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
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
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
<li><a href="../metrics/trajectory_metrics.md#ll">LL</a></li>
<li><a href="../metrics/trajectory_metrics.md#kld">KLD</a></li>
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
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
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
<summary><em>Geng et al., "Comparing Correspondences: Video Prediction With Correspondence-Wise Losses", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Geng_Comparing_Correspondences_Video_Prediction_With_Correspondence-Wise_Losses_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2104.09498.pdf>arxiv</a> <a href=https://github.com/dangeng/CorrWiseLosses>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#dancing">Dancing</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#fvd">FVD</a></li>
<li><a href="../metrics/video_metrics.md#iou">IoU</a></li>
<li><a href="../metrics/video_metrics.md#csim">CSIM</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics/video_metrics.md#ms-ssim">MS-SSIM</a></li>
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
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics/video_metrics.md#fvd">FVD</a></li>
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
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#orc">ORC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
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
<summary><em>Graber et al., "Joint Forecasting of Panoptic Segmentations With Difference Attention", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Graber_Joint_Forecasting_of_Panoptic_Segmentations_With_Difference_Attention_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.07157.pdf>arxiv</a> <a href=https://github.com/cgraber/psf-diffattn>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/other_metrics.md#f1">F1</a></li>
<li><a href="../metrics/other_metrics.md#iou">IoU</a></li>
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
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/other_metrics.md#iou">IoU</a></li>
<li><a href="../metrics/other_metrics.md#ap">AP</a></li>
<li><a href="../metrics/other_metrics.md#rq">RQ</a></li>
<li><a href="../metrics/other_metrics.md#sq">SQ</a></li>
<li><a href="../metrics/other_metrics.md#pq">PQ</a></li>
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
<li><a href="../datasets/year_datasets.md#cityscape">Cityscape</a></li>
<li><a href="../datasets/year_datasets.md#3d_movie">3D Movie</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/other_metrics.md#ap">AP</a></li>
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
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/other_metrics.md#iou">IoU</a></li>
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
<summary><em>Hu et al., "Probabilistic future prediction for video scene understanding", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123610749.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.06409.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/other_metrics.md#iou">IoU</a></li>
<li><a href="../metrics/other_metrics.md#ddm">DDM</a></li>
<li><a href="../metrics/other_metrics.md#aepe">AEPE</a></li>
<li><a href="../metrics/other_metrics.md#sile">SILE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2020_ECCV,
    author = "Hu, Anthony and Cotter, Fergal and Mohan, Nikhil and Gurau, Corina and Kendall, Alex",
    title = "Probabilistic future prediction for video scene understanding",
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
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/other_metrics.md#iou">IoU</a></li>
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
<li><a href="../metrics/other_metrics.md#iou">IoU</a></li>
<li><a href="../metrics/other_metrics.md#voi">VoI</a></li>
<li><a href="../metrics/other_metrics.md#gce">GCE</a></li>
<li><a href="../metrics/other_metrics.md#ri">RI</a></li>
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
<li><a href="../metrics/other_metrics.md#iou">IoU</a></li>
<li><a href="../metrics/other_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/other_metrics.md#psnr">PSNR</a></li>
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
<li><a href="../metrics/other_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/other_metrics.md#miou">MIoU</a></li>
<li><a href="../metrics/other_metrics.md#epe">EPE</a></li>
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
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#l1">L1</a></li>
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
<li><a href="../metrics/video_metrics.md#l1">L1</a></li>
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
<summary><em>Rasouli et al., "Bifold and Semantic Reasoning for Pedestrian Behavior Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Rasouli_Bifold_and_Semantic_Reasoning_for_Pedestrian_Behavior_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2012.03298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics/action_metrics.md#precision">Precision</a></li>
<li><a href="../metrics/action_metrics.md#f1">F1</a></li>
<li><a href="../metrics/action_metrics.md#auc">AUC</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics/action_metrics.md#ap">AP</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics/action_metrics.md#f1">F1</a></li>
<li><a href="../metrics/action_metrics.md#auc">AUC</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#stip">STIP</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<summary><em>Saleh et al., "Real-Time Intent Prediction Of Pedestrians For Autonomous Ground Vehicles Via Spatio-Temporal Densenet", ICRA, 2019.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8793991>paper</a> <a href=https://arxiv.org/pdf/1904.09862.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#ap">AP</a></li>
<li><a href="../metrics/action_metrics.md#run_time">Run Time</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../metrics/action_metrics.md#map">mAP</a></li>
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
<summary><em>Neumann et al., "Pedestrian and Ego-Vehicle Trajectory Prediction From Monocular Camera", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Neumann_Pedestrian_and_Ego-Vehicle_Trajectory_Prediction_From_Monocular_Camera_CVPR_2021_paper.pdf>paper</a> <a href=https://gitlab.com/lukeN86/pedFutureTracking>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Yao_2021_RAL,
    author = "Yao, Yu and Atkins, Ella and Johnson-Roberson, Matthew and Vasudevan, Ram and Du, Xiaoxiao",
    journal = "RAL",
    title = "BiTraP: Bi-Directional Pedestrian Trajectory Prediction With Multi-Modal Goal Estimation",
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#kde">KDE</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#fpl">FPL</a></li>
<li><a href="../datasets/year_datasets.md#citywalks">CityWalks</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ansari_2020_IROS,
    author = "Ansari, J. A. and Bhowmick, B.",
    booktitle = "IROS",
    title = "Simple means Faster: Real-Time Human Motion Forecasting in Monocular First Person Videos on CPU",
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
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Du et al., "Unsupervised Pedestrian Pose Prediction: A Deep Predictive Coding Network-Based Approach for Autonomous Vehicle Perception", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9042808>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#pedx">PedX</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/motion_metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/other_metrics.md#psi">Psi</a></li>
<li><a href="../metrics/other_metrics.md#ism">ISM</a></li>
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
<summary><em>Gao et al., "SimVP: Simpler Yet Better Video Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Gao_SimVP_Simpler_Yet_Better_Video_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2206.05099.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#taxi_bj">Taxi BJ</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/video_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2022_CVPR,
    author = "Gao, Zhangyang and Tan, Cheng and Wu, Lirong and Li, Stan Z.",
    title = "SimVP: Simpler Yet Better Video Prediction",
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#town_center">Town Center</a></li>
<li><a href="../datasets/year_datasets.md#smtsmt">SmtSmt</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics/video_metrics.md#fvd">FVD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chang_2021_NeurIPS,
    author = "Chang, Zheng and Zhang, Xinfeng and Wang, Shanshe and Ma, Siwei and Ye, Yan and Xinguang, Xiang and Gao, Wen",
    booktitle = "NeurIPS",
    title = "MAU: A Motion-Aware Unit for Video Prediction and Beyond",
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#bair">BAIR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
<li><a href="../metrics/video_metrics.md#fvd">FVD</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#chuk_avenue">CHUK Avenue</a></li>
<li><a href="../datasets/year_datasets.md#shanghaitech_campus">ShanghaiTech Campus</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
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
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
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
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
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
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
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
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/video_metrics.md#l1">L1</a></li>
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
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#thumos">THUMOS</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics/action_metrics.md#auc">AUC</a></li>
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
<summary><em>Rasouli et al., "Bifold and Semantic Reasoning for Pedestrian Behavior Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Rasouli_Bifold_and_Semantic_Reasoning_for_Pedestrian_Behavior_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2012.03298.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics/action_metrics.md#precision">Precision</a></li>
<li><a href="../metrics/action_metrics.md#f1">F1</a></li>
<li><a href="../metrics/action_metrics.md#auc">AUC</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics/action_metrics.md#ap">AP</a></li>
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
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics/action_metrics.md#f1">F1</a></li>
<li><a href="../metrics/action_metrics.md#auc">AUC</a></li>
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
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics/action_metrics.md#recall">Recall</a></li>
<li><a href="../metrics/action_metrics.md#precision">Precision</a></li>
<li><a href="../metrics/action_metrics.md#f1">F1</a></li>
<li><a href="../metrics/action_metrics.md#auc">AUC</a></li>
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
<summary><em>Neumann et al., "Pedestrian and Ego-Vehicle Trajectory Prediction From Monocular Camera", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Neumann_Pedestrian_and_Ego-Vehicle_Trajectory_Prediction_From_Monocular_Camera_CVPR_2021_paper.pdf>paper</a> <a href=https://gitlab.com/lukeN86/pedFutureTracking>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#mse">MSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Yao_2021_RAL,
    author = "Yao, Yu and Atkins, Ella and Johnson-Roberson, Matthew and Vasudevan, Ram and Du, Xiaoxiao",
    journal = "RAL",
    title = "BiTraP: Bi-Directional Pedestrian Trajectory Prediction With Multi-Modal Goal Estimation",
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
<summary><em>Kim et al., "Pedestrian Intention Prediction for Autonomous Driving Using a Multiple Stakeholder Perspective Model", IROS, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9341083>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#mse">MSE</a></li>
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
<summary><em>Rasouli et al., "Pie: A Large-Scale Dataset And Models For Pedestrian Intention Estimation And Trajectory Prediction", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.pdf>paper</a> <a href=https://github.com/aras62/PIEPredict>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<a name=waymo></a>
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
<summary><em>Sun et al., "M2I: From Factored Marginal Trajectory Prediction to Interactive Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Sun_M2I_From_Factored_Marginal_Trajectory_Prediction_to_Interactive_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2202.11884.pdf>arxiv</a> <a href=https://github.com/Tsinghua-MARS-Lab/M2I>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#waymo">Waymo</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2022_CVPR,
    author = "Sun, Qiao and Huang, Xin and Gu, Junru and Williams, Brian C. and Zhao, Hang",
    title = "M2I: From Factored Marginal Trajectory Prediction to Interactive Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ettinger et al., "Large Scale Interactive Motion Forecasting for Autonomous Driving: The Waymo Open Motion Dataset", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Ettinger_Large_Scale_Interactive_Motion_Forecasting_for_Autonomous_Driving_The_Waymo_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2104.10133.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#waymo">Waymo</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#map">mAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ettinger_2021_ICCV,
    author = "Ettinger, Scott and Cheng, Shuyang and Caine, Benjamin and Liu, Chenxi and Zhao, Hang and Pradhan, Sabeek and Chai, Yuning and Sapp, Ben and Qi, Charles R. and Zhou, Yin and Yang, Zoey and Chouard, Aurelien and Sun, Pei and Ngiam, Jiquan and Vasudevan, Vijay and McCauley, Alexander and Shlens, Jonathon and Anguelov, Dragomir",
    title = "Large Scale Interactive Motion Forecasting for Autonomous Driving: The Waymo Open Motion Dataset",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Gu et al., "DenseTNT: End-to-End Trajectory Prediction From Dense Goal Sets", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Gu_DenseTNT_End-to-End_Trajectory_Prediction_From_Dense_Goal_Sets_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2108.09640.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#waymo">Waymo</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gu_2021_ICCV,
    author = "Gu, Junru and Sun, Chen and Zhao, Hang",
    title = "DenseTNT: End-to-End Trajectory Prediction From Dense Goal Sets",
    booktitle = "ICCV",
    year = "2021"
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/year_datasets.md#fit">FIT</a></li>
<li><a href="../datasets/year_datasets.md#mapillary_vistas">Mapillary Vistas</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#iou">IoU</a></li>
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
<summary><em>Zhang et al., "STINet: Spatio-Temporal-Interactive Network for Pedestrian Detection and Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_STINet_Spatio-Temporal-Interactive_Network_for_Pedestrian_Detection_and_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.04255.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/year_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#bev_ap">BEV AP</a></li>
<li><a href="../metrics/trajectory_metrics.md#de">DE</a></li>
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
<details close>
<summary><em>Toyungyernsub et al., "Double-Prong ConvLSTM for Spatiotemporal Occupancy Prediction in Dynamic Environments", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561940>paper</a> <a href=https://arxiv.org/pdf/2011.09045.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#way">Way</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/other_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/other_metrics.md#ims">ImS</a></li>
<li><a href="../metrics/other_metrics.md#dmse">DMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Toyungyernsub_2021_ICRA,
    author = "Toyungyernsub, Maneekwan and Itkina, Masha and Senanayake, Ransalu and Kochenderfer, Mykel J.",
    booktitle = "ICRA",
    title = "Double-Prong ConvLSTM for Spatiotemporal Occupancy Prediction in Dynamic Environments",
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
@InProceedings{Sun_2020_CVPR_3,
    author = "Sun, Pei and Kretzschmar, Henrik and Dotiwalla, Xerxes and Chouard, Aurelien and Patnaik, Vijaysai and Tsui, Paul and Guo, James and Zhou, Yin and Chai, Yuning and Caine, Benjamin and Vasudevan, Vijay and Han, Wei and Ngiam, Jiquan and Zhao, Hang and Timofeev, Aleksei and Ettinger, Scott and Krivokon, Maxim and Gao, Amy and Joshi, Aditya and Zhang, Yu and Shlens, Jonathon and Chen, Zhifeng and Anguelov, Dragomir",
    title = "Scalability in Perception for Autonomous Driving: Waymo Open Dataset",
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
<summary><em>Zhang et al., "On Adversarial Robustness of Trajectory Prediction for Autonomous Vehicles", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_On_Adversarial_Robustness_of_Trajectory_Prediction_for_Autonomous_Vehicles_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2201.05057.pdf>arxiv</a> <a href=https://github.com/zqzqz/AdvTrajectoryPrediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Zheng et al., "Unlimited Neighborhood Interaction for Heterogeneous Trajectory Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Zheng_Unlimited_Neighborhood_Interaction_for_Heterogeneous_Trajectory_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2108.00238.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Wang et al., "Multiple Contextual Cues Integrated Trajectory Prediction for Autonomous Driving", RAL, 2021.</em> <a href=https://ieeexplore.ieee.org/document/9476975>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#wade">wADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#wfde">wFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Wang_2021_RAL,
    author = "Wang, Li and Wu, Tao and Fu, Hao and Xiao, Liang and Wang, Zhiyu and Dai, Bin",
    journal = "RAL",
    title = "Multiple Contextual Cues Integrated Trajectory Prediction for Autonomous Driving",
    year = "2021",
    volume = "6",
    number = "4",
    pages = "6844-6851"
}
</pre>
</details>

</ul>
</details>
<details close>
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
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#dac">DAC</a></li>
<li><a href="../metrics/trajectory_metrics.md#wsfde">WSFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#wsade">WSADE</a></li>
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
<summary><em>He et al., "UST: Unifying Spatio-Temporal Context for Trajectory Prediction in Autonomous Driving", IROS, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9340943>paper</a> <a href=https://arxiv.org/pdf/2005.02790.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#apolloscape">ApolloScape</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
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
<summary><em>Chandra et al., "Forecasting Trajectory and Behavior of Road-Agents Using Spectral Clustering in Graph-LSTMs", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9126166>paper</a> <a href=https://arxiv.org/pdf/1912.01118.pdf>arxiv</a> <a href=https://github.com/rohanchandra30/Spectral-Trajectory-and-Behavior-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#apolloscape">ApolloScape</a></li>
<li><a href="../datasets/year_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Chandra_2020_RAL,
    author = "Chandra, R. and Guan, T. and Panuganti, S. and Mittal, T. and Bhattacharya, U. and Bera, A. and Manocha, D.",
    journal = "RAL",
    title = "Forecasting Trajectory and Behavior of Road-Agents Using Spectral Clustering in Graph-LSTMs",
    year = "2020",
    volume = "5",
    number = "3",
    pages = "4882-4890"
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
<summary><em>Monti et al., "How Many Observations Are Enough? Knowledge Distillation for Trajectory Forecasting", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Monti_How_Many_Observations_Are_Enough_Knowledge_Distillation_for_Trajectory_Forecasting_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.04781.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
<li><a href="../datasets/year_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Monti_2022_CVPR,
    author = "Monti, Alessio and Porrello, Angelo and Calderara, Simone and Coscia, Pasquale and Ballan, Lamberto and Cucchiara, Rita",
    title = "How Many Observations Are Enough? Knowledge Distillation for Trajectory Forecasting",
    booktitle = "CVPR",
    year = "2022"
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#iou">IoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2021_ICCV,
    author = "Hu, Anthony and Murez, Zak and Mohan, Nikhil and Dudas, Sofia and Hawke, Jeffrey and Badrinarayanan, Vijay and Cipolla, Roberto and Kendall, Alex",
    title = "FIERY: Future Instance Prediction in Bird's-Eye View From Surround Monocular Cameras",
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/trajectory_metrics.md#ur">UR</a></li>
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
<summary><em>Zhang et al., "STINet: Spatio-Temporal-Interactive Network for Pedestrian Detection and Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_STINet_Spatio-Temporal-Interactive_Network_for_Pedestrian_Detection_and_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.04255.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/year_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#bev_ap">BEV AP</a></li>
<li><a href="../metrics/trajectory_metrics.md#de">DE</a></li>
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
<details close>
<summary><em>Chandra et al., "Forecasting Trajectory and Behavior of Road-Agents Using Spectral Clustering in Graph-LSTMs", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9126166>paper</a> <a href=https://arxiv.org/pdf/1912.01118.pdf>arxiv</a> <a href=https://github.com/rohanchandra30/Spectral-Trajectory-and-Behavior-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#apolloscape">ApolloScape</a></li>
<li><a href="../datasets/year_datasets.md#lyft">Lyft</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Chandra_2020_RAL,
    author = "Chandra, R. and Guan, T. and Panuganti, S. and Mittal, T. and Bhattacharya, U. and Bera, A. and Manocha, D.",
    journal = "RAL",
    title = "Forecasting Trajectory and Behavior of Road-Agents Using Spectral Clustering in Graph-LSTMs",
    year = "2020",
    volume = "5",
    number = "3",
    pages = "4882-4890"
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
<a name=highd></a>
<details close>
<summary><l style="font-size:20px"><strong>HighD</strong></l> <a href=https://www.highd-dataset.com/>link</a> <a href=https://arxiv.org/pdf/1810.05642.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 147 hours of 110K+ cars driving on German highways recorded from top-down view using a drone
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Trajectory, Vehicle Type, Vehicle Size</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Anderson et al., "A Kinematic Model for Trajectory Prediction in General Highway Scenarios", RAL, 2021.</em> <a href=https://ieeexplore.ieee.org/document/9472993>paper</a> <a href=https://arxiv.org/pdf/2103.16673.pdf>arxiv</a> <a href=https://github.com/umautobots/kinematic_highway>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#highd">HighD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
<li><a href="../metrics/trajectory_metrics.md#qde">QDE</a></li>
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
<summary><em>Mersch et al., "Maneuver-based Trajectory Prediction for Self-driving Cars Using Spatio-temporal Convolutional Networks", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636875>paper</a> <a href=https://arxiv.org/pdf/2109.07365.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#highd">HighD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#highd">HighD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Song_2020_ECCV,
    author = "Song, Haoran and Ding, Wenchao and Chen, Yuxuan and Shen, Shaojie and Wang, Michael Yu and Chen, Qifeng",
    title = "PiP: Planning-informed Trajectory Prediction for Autonomous Driving",
    booktitle = "ECCV",
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
<li><a href="../datasets/year_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/year_datasets.md#highd">HighD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
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
<summary><em>Wirthmüller et al., "Predicting the Time Until a Vehicle Changes the Lane Using LSTM-Based Recurrent Neural Networks", RAL, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9353203>paper</a> <a href=https://arxiv.org/pdf/2102.01431.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#highd">HighD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/other_metrics.md#f1">F1</a></li>
<li><a href="../metrics/other_metrics.md#precision">Precision</a></li>
<li><a href="../metrics/other_metrics.md#recall">Recall</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Wirthmuller_2021_RAL,
    author = "Wirthmüller, Florian and Klimke, Marvin and Schlechtriemen, Julian and Hipp, Jochen and Reichert, Manfred",
    journal = "RAL",
    title = "Predicting the Time Until a Vehicle Changes the Lane Using LSTM-Based Recurrent Neural Networks",
    year = "2021",
    volume = "6",
    number = "2",
    pages = "2357-2364"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Krajewski_2018_ITSC,
    author = "Krajewski, Robert and Bock, Julian and Kloeker, Laurent and Eckstein, Lutz",
    title = "The highD Dataset: A Drone Dataset of Naturalistic Vehicle Trajectories on German Highways for Validation of Highly Automated Driving Systems",
    booktitle = "ITSC",
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
<summary><em>Bao et al., "DRIVE: Deep Reinforced Accident Anticipation With Visual Explanation", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Bao_DRIVE_Deep_Reinforced_Accident_Anticipation_With_Visual_Explanation_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2107.10189.pdf>arxiv</a> <a href=https://github.com/Cogito2012/DRIVE>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#dad">DAD</a></li>
<li><a href="../datasets/year_datasets.md#dada-2000">DADA-2000</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#auc">AUC</a></li>
<li><a href="../metrics/action_metrics.md#tta">TTA</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bao_2021_ICCV,
    author = "Bao, Wentao and Yu, Qi and Kong, Yu",
    title = "DRIVE: Deep Reinforced Accident Anticipation With Visual Explanation",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Suzuki et al., "Anticipating Traffic Accidents With Adaptive Loss And Large-Scale Incident Db", The CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0494.pdf>paper</a> <a href=https://arxiv.org/pdf/1804.02675.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#dad">DAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics/action_metrics.md#recall">Recall</a></li>
<li><a href="../metrics/action_metrics.md#precision">Precision</a></li>
<li><a href="../metrics/action_metrics.md#f1">F1</a></li>
<li><a href="../metrics/action_metrics.md#map">mAP</a></li>
<li><a href="../metrics/action_metrics.md#attc">ATTC</a></li>
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
<li><a href="../metrics/action_metrics.md#map">mAP</a></li>
<li><a href="../metrics/action_metrics.md#tta">TTA</a></li>
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
<li><a href="../datasets/year_datasets.md#dad">DAD</a></li>
<li><a href="../datasets/year_datasets.md#hev-i">HEV-I</a></li>
<li><a href="../datasets/year_datasets.md#a3d">A3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fiou">FioU</a></li>
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
<li><a href="../metrics/action_metrics.md#recall">Recall</a></li>
<li><a href="../metrics/action_metrics.md#precision">Precision</a></li>
<li><a href="../metrics/action_metrics.md#f1">F1</a></li>
<li><a href="../metrics/action_metrics.md#ttm">TTM</a></li>
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
<li><a href="../metrics/action_metrics.md#recall">Recall</a></li>
<li><a href="../metrics/action_metrics.md#precision">Precision</a></li>
<li><a href="../metrics/action_metrics.md#ttm">TTM</a></li>
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
<li><a href="../metrics/action_metrics.md#recall">Recall</a></li>
<li><a href="../metrics/action_metrics.md#precision">Precision</a></li>
<li><a href="../metrics/action_metrics.md#ttm">TTM</a></li>
<li><a href="../metrics/action_metrics.md#fp">FP</a></li>
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
<a name=h3d></a>
<details close>
<summary><l style="font-size:20px"><strong>Honda 3D (H3D)</strong></l> <a href=https://usa.honda-ri.com/H3D>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/8793925>paper</a> <a href=https://arxiv.org/pdf/1903.01568.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 8 traffic objects annotated with 3D bounding boxes at 2Hz on 10Hz recorded data
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, LIDAR, 3D Bounding box, Object class</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Choi et al., "Shared Cross-Modal Trajectory Prediction for Autonomous Driving", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Choi_Shared_Cross-Modal_Trajectory_Prediction_for_Autonomous_Driving_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2011.08436.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#h3d">H3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Li et al., "EvolveGraph: Multi-Agent Trajectory Prediction with Dynamic Relational Reasoning", NeurIPS, 2020.</em> <a href=https://papers.nips.cc/paper/2020/file/e4d8163c7a068b65a64c89bd745ec360-Paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.13924.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
<li><a href="../datasets/year_datasets.md#nba">NBA</a></li>
<li><a href="../datasets/year_datasets.md#h3d">H3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2020_NeurIPS,
    author = "Li, Jiachen and Yang, Fan and Tomizuka, Masayoshi and Choi, Chiho",
    editor = "Larochelle, H. and Ranzato, M. and Hadsell, R. and Balcan, M. F. and Lin, H.",
    booktitle = "NeurIPS",
    title = "EvolveGraph: Multi-Agent Trajectory Prediction with Dynamic Relational Reasoning",
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
@InProceedings{Patil_2019_ICRA,
    author = "Patil, Abhishek and Malla, Srikanth and Gang, Haiming and Chen, Yi-Ting",
    title = "The H3D Dataset for Full-Surround 3D Multi-Object Detection and Tracking in Crowded Urban Scenes",
    booktitle = "ICRA",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=usyd></a>
<details close>
<summary><l style="font-size:20px"><strong>USyd Campus Dataset (Usyd)</strong></l> <a href=http://its.acfr.usyd.edu.au/datasets/usyd-campus-dataset/>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of driving in university of Sydney campus collected under different conditions
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, LIDAR, vehicle sensors, GPS</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Li et al., "Attentional-GCNN: Adaptive Pedestrian Trajectory Prediction towards Generic Autonomous Vehicle Use Cases", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561480>paper</a> <a href=https://arxiv.org/pdf/2011.11190.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#usyd">USyd</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2021_ICRA_2,
    author = "Li, Kunming and Eiffert, Stuart and Shan, Mao and Gomez-Donoso, Francisco and Worrall, Stewart and Nebot, Eduardo",
    booktitle = "ICRA",
    title = "Attentional-GCNN: Adaptive Pedestrian Trajectory Prediction towards Generic Autonomous Vehicle Use Cases",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Eiffert et al., "Probabilistic Crowd GAN: Multimodal Pedestrian Trajectory Prediction Using a Graph Vehicle-Pedestrian Attention Network", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9123560>paper</a> <a href=https://arxiv.org/pdf/2006.12906.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#usyd">USyd</a></li>
<li><a href="../datasets/year_datasets.md#vci">VCI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mhd">MHD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Eiffert_2020_RAL,
    author = "Eiffert, S. and Li, K. and Shan, M. and Worrall, S. and Sukkarieh, S. and Nebot, E.",
    journal = "RAL",
    title = "Probabilistic Crowd GAN: Multimodal Pedestrian Trajectory Prediction Using a Graph Vehicle-Pedestrian Attention Network",
    year = "2020",
    volume = "5",
    number = "4",
    pages = "5026-5033"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Misc{Zhou_2019_data,
    author = "Zhou, Wei and Perez, Julie Stephany Berrio and Alvis, Charika De and Shan, Mao and Worrall, Stewart and Ward, James and Nebot, Eduardo",
    title = "The USyd Campus Dataset",
    year = "2019"
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
<summary><em>Zhao et al., "Tnt: Target-driven trajectory prediction", CoRL, 2020.</em> <a href=https://drive.google.com/file/d/1Ol40GkiELqcechS9eWINoacMb5ebDUkD/view>paper</a> <a href=https://arxiv.org/pdf/2008.08294.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
<li><a href="../datasets/year_datasets.md#interaction">INTERACTION</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#miss_rate">Miss rate</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhao_2020_CORL,
    author = "Zhao, Hang and Gao, Jiyang and Lan, Tian and Sun, Chen and Sapp, Benjamin and Varadarajan, Balakrishnan and Shen, Yue and Shen, Yi and Chai, Yuning and Schmid, Cordelia and others",
    title = "Tnt: Target-driven trajectory prediction",
    booktitle = "CoRL",
    year = "2020"
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
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<a name=hev-i></a>
<details close>
<summary><l style="font-size:20px"><strong>Honda Egocentric View-Intersection (HEV-I)</strong></l> <a href=https://usa.honda-ri.com/hevi0>link</a> <a href=https://ieeexplore.ieee.org/document/8794474>paper</a> <a href=https://arxiv.org/pdf/1809.07408.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 230 video clips of driving at different intersections in San Francisco annotated at 10Hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Object Class, Bounding Box, Tracking ID, activity label, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yao et al., "Egocentric Vision-based Future Vehicle Localization for Intelligent Driving Assistance Systems", ICRA, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8794474>paper</a> <a href=https://arxiv.org/pdf/1809.07408.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#hev-i">HEV-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fiou">FioU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yao_2019_ICRA,
    author = "Yao, Y. and Xu, M. and Choi, C. and Crandall, D. J. and Atkins, E. M. and Dariush, B.",
    booktitle = "ICRA",
    title = "Egocentric Vision-based Future Vehicle Localization for Intelligent Driving Assistance Systems",
    year = "2019"
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
<li><a href="../datasets/year_datasets.md#dad">DAD</a></li>
<li><a href="../datasets/year_datasets.md#hev-i">HEV-I</a></li>
<li><a href="../datasets/year_datasets.md#a3d">A3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fiou">FioU</a></li>
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
@InProceedings{Yao_2019_ICRA,
    author = "Yao, Y. and Xu, M. and Choi, C. and Crandall, D. J. and Atkins, E. M. and Dariush, B.",
    booktitle = "ICRA",
    title = "Egocentric Vision-based Future Vehicle Localization for Intelligent Driving Assistance Systems",
    year = "2019"
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
<summary><em>Zhi et al., "Probabilistic Trajectory Prediction with Structural Constraints", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636003>paper</a> <a href=https://arxiv.org/pdf/2107.04193.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#lankershim_boulevard">Lankershim Boulevard</a></li>
<li><a href="../datasets/year_datasets.md#thor">THOR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#al">AL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhi_2021_IROS,
    author = "Zhi, Weiming and Ott, Lionel and Ramos, Fabio",
    booktitle = "IROS",
    title = "Probabilistic Trajectory Prediction with Structural Constraints",
    year = "2021"
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
<li><a href="../datasets/year_datasets.md#lankershim_boulevard">Lankershim Boulevard</a></li>
<li><a href="../datasets/year_datasets.md#eifp">EIFP</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
    author = "Department of Transportation, U.S.",
    title = "Lankershim Boulevard Dataset",
    url = "https://www.fhwa.dot.gov/publications/research/operations/07029/index.cfm",
    year = "2007"
}
</pre>
</details>

</ul></details>
<a name=pedx></a>
<details close>
<summary><l style="font-size:20px"><strong>PedX</strong></l> <a href=http://pedx.io/>link</a> <a href=https://ieeexplore.ieee.org/document/8630473>paper</a> <a href=https://arxiv.org/pdf/1809.03605.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 10K images of pedestrians at traffic intersections with 2D and 3D poses
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB (Image), LIDAR, 2D/3D Pose</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Du et al., "Unsupervised Pedestrian Pose Prediction: A Deep Predictive Coding Network-Based Approach for Autonomous Vehicle Perception", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9042808>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#pedx">PedX</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/motion_metrics.md#rmse">RMSE</a></li>
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
<summary><em>Du et al., "Bio-LSTM: A Biomechanically Inspired Recurrent Neural Network for 3-D Pedestrian Pose and Gait Prediction", RAL, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8626436>paper</a> <a href=https://arxiv.org/pdf/1809.03705.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#pedx">PedX</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/motion_metrics.md#mpjpe">MPJPE</a></li>
<li><a href="../metrics/motion_metrics.md#rmse">RMSE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Du_2019_RAL,
    author = "Du, X. and Vasudevan, R. and Johnson-Roberson, M.",
    journal = "RAL",
    title = "Bio-LSTM: A Biomechanically Inspired Recurrent Neural Network for 3-D Pedestrian Pose and Gait Prediction",
    year = "2019",
    volume = "4",
    number = "2",
    pages = "1501-1508"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Kim_2019_RAL,
    author = "Kim, W. and Ramanagopal, M. S. and Barto, C. and Yu, M. and Rosaen, K. and Goumas, N. and Vasudevan, R. and Johnson-Roberson, M.",
    journal = "RAL",
    title = "PedX: Benchmark Dataset for Metric 3-D Pose Estimation of Pedestrians in Complex Urban Intersections",
    year = "2019",
    volume = "4",
    number = "2",
    pages = "1940-1947"
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
<li><a href="../datasets/year_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/year_datasets.md#orc">ORC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#ed">ED</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics/action_metrics.md#auc">AUC</a></li>
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
<summary><em>Huynh et al., "Aol: Adaptive online learning for human trajectory prediction in dynamic video scenes", BMVC, 2020.</em> <a href=https://www.bmvc2020-conference.com/assets/papers/0493.pdf>paper</a> <a href=https://arxiv.org/pdf/2002.06666.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#eth_pedestrian">ETH Pedestrian</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Huynh_2020_BMVC,
    author = "Huynh, Manh and Alaghband, Gita",
    title = "Aol: Adaptive online learning for human trajectory prediction in dynamic video scenes",
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
<summary><em>Gao et al., "SimVP: Simpler Yet Better Video Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Gao_SimVP_Simpler_Yet_Better_Video_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2206.05099.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#kth">KTH</a></li>
<li><a href="../datasets/year_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/year_datasets.md#taxi_bj">Taxi BJ</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/video_metrics.md#mae">MAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gao_2022_CVPR,
    author = "Gao, Zhangyang and Tan, Cheng and Wu, Lirong and Li, Stan Z.",
    title = "SimVP: Simpler Yet Better Video Prediction",
    booktitle = "CVPR",
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
<li><a href="../datasets/year_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/year_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/year_datasets.md#taxi_bj">Taxi BJ</a></li>
<li><a href="../datasets/year_datasets.md#sst">SST</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/video_metrics.md#mae">MAE</a></li>
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
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#iou">IoU</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics/action_metrics.md#auc">AUC</a></li>
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
<a name=euro-pvi></a>
<details close>
<summary><l style="font-size:20px"><strong>Euro-PVI</strong></l> <a href=www.europvi.mpi-inf.mpg.de>link</a> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Bhattacharyya_Euro-PVI_Pedestrian_Vehicle_Interactions_in_Dense_Urban_Centers_CVPR_2021_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of driving fousing on traffic interactions.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, LIDAR, Activity Label, Bounding box</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Bhattacharyya et al., "Euro-PVI: Pedestrian Vehicle Interactions in Dense Urban Centers", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Bhattacharyya_Euro-PVI_Pedestrian_Vehicle_Interactions_in_Dense_Urban_Centers_CVPR_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#euro-pvi">Euro-PVI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bhattacharyya_2021_CVPR,
    author = "Bhattacharyya, Apratim and Reino, Daniel Olmeda and Fritz, Mario and Schiele, Bernt",
    title = "Euro-PVI: Pedestrian Vehicle Interactions in Dense Urban Centers",
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
@InProceedings{Bhattacharyya_2021_CVPR,
    author = "Bhattacharyya, Apratim and Reino, Daniel Olmeda and Fritz, Mario and Schiele, Bernt",
    title = "Euro-PVI: Pedestrian Vehicle Interactions in Dense Urban Centers",
    booktitle = "CVPR",
    year = "2021"
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
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Gaze</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Bao et al., "DRIVE: Deep Reinforced Accident Anticipation With Visual Explanation", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Bao_DRIVE_Deep_Reinforced_Accident_Anticipation_With_Visual_Explanation_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2107.10189.pdf>arxiv</a> <a href=https://github.com/Cogito2012/DRIVE>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#dad">DAD</a></li>
<li><a href="../datasets/year_datasets.md#dada-2000">DADA-2000</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#auc">AUC</a></li>
<li><a href="../metrics/action_metrics.md#tta">TTA</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bao_2021_ICCV,
    author = "Bao, Wentao and Yu, Qi and Kong, Yu",
    title = "DRIVE: Deep Reinforced Accident Anticipation With Visual Explanation",
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
    title = "DADA: Driver Attention Prediction in Driving Accident Scenarios",
    year = "2021"
}
</pre>
</details>

</ul></details>
<a name=ind></a>
<details close>
<summary><l style="font-size:20px"><strong>inD</strong></l> <a href=https://www.ind-dataset.com/>link</a> <a href=https://ieeexplore.ieee.org/document/9304839>paper</a> <a href=https://arxiv.org/pdf/1911.07602.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of road users’ trajectories recorded from BEV at German intersections.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Trajectory, Vehicle Type, Vehicle Size</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Guo et al., "End-to-End Trajectory Distribution Prediction Based on Occupancy Grid Maps", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_End-to-End_Trajectory_Distribution_Prediction_Based_on_Occupancy_Grid_Maps_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.16910.pdf>arxiv</a> <a href=https://github.com/Kguo-cs/TDOR>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#sd">SD</a></li>
<li><a href="../datasets/year_datasets.md#ind">inD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#offroad_rate">Offroad Rate</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Guo_2022_CVPR,
    author = "Guo, Ke and Liu, Wenxi and Pan, Jia",
    title = "End-to-End Trajectory Distribution Prediction Based on Occupancy Grid Maps",
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
@InProceedings{Bock_2020_IV,
    author = "Bock, Julian and Krajewski, Robert and Moers, Tobias and Runde, Steffen and Vater, Lennart and Eckstein, Lutz",
    title = "The inD Dataset: A Drone Dataset of Naturalistic Road User Trajectories at German Intersections",
    booktitle = "IV",
    year = "2020"
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
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Activity Label, 3D Bounding Box</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yau et al., "Graph-SIM: A Graph-based Spatiotemporal Interaction Modelling for Pedestrian Action Prediction", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561107>paper</a> <a href=https://arxiv.org/pdf/2012.02148.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#pepscenes">PepScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics/action_metrics.md#precision">Precision</a></li>
<li><a href="../metrics/action_metrics.md#f1">F1</a></li>
<li><a href="../metrics/action_metrics.md#auc">AUC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yau_2021_ICRA,
    author = "Yau, Tiffany and Malekmohammadi, Saber and Rasouli, Amir and Lakner, Peter and Rohani, Mohsen and Luo, Jun",
    booktitle = "ICRA",
    title = "Graph-SIM: A Graph-based Spatiotemporal Interaction Modelling for Pedestrian Action Prediction",
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
    title = "Pepscenes: A novel dataset and baseline for pedestrian action prediction in 3d",
    year = "2020"
}
</pre>
</details>

</ul></details>
<a name=otoh></a>
<details close>
<summary><l style="font-size:20px"><strong>One Thousand and One Hours (OTOH)</strong></l> <a href=https://self-driving.lyft.com/level5/prediction/>link</a> <a href=https://drive.google.com/file/d/1aABQsyBkxr-TlgjwKRdeeJy6YjShUAmj/view>paper</a> <a href=https://arxiv.org/pdf/2006.14480.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of over 1000 hours of driving with associated trajectories and map
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Trajectory, vehicle sensors, map</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Houston et al., "One thousand and one hours: Self-driving motion prediction dataset", CoRL, 2020.</em> <a href=https://drive.google.com/file/d/1aABQsyBkxr-TlgjwKRdeeJy6YjShUAmj/view>paper</a> <a href=https://arxiv.org/pdf/2006.14480.pdf>arxiv</a> <a href=https://github.com/lyft/l5kit>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#otoh">OTOH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Houston_2020_CORL,
    author = "Houston, John and Zuidhof, Guido and Bergamini, Luca and Ye, Yawei and Chen, Long and Jain, Ashesh and Omari, Sammy and Iglovikov, Vladimir and Ondruska, Peter",
    title = "One thousand and one hours: Self-driving motion prediction dataset",
    booktitle = "CoRL",
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
@InProceedings{Houston_2020_CORL,
    author = "Houston, John and Zuidhof, Guido and Bergamini, Luca and Ye, Yawei and Chen, Long and Jain, Ashesh and Omari, Sammy and Iglovikov, Vladimir and Ondruska, Peter",
    title = "One thousand and one hours: Self-driving motion prediction dataset",
    booktitle = "CoRL",
    year = "2020"
}
</pre>
</details>

</ul></details>
<a name=a2d2></a>
<details close>
<summary><l style="font-size:20px"><strong>Audi Autonomous Driving Dataset (A2D2)</strong></l> <a href=https://www.a2d2.audi/a2d2/en/dataset.html>link</a> <a href=https://arxiv.org/pdf/2004.06320.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 40k frames of driving with semantic segmentation, 12k frames with 3D bounding boxes and 390k unlabelled footage collected in 3 cities.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, LIDAR, 3D Bounding Box, Semantic Segment</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Buhet et al., "PLOP: Probabilistic poLynomial Objects trajectory Planning for autonomous driving", CoRL, 2020.</em> <a href=https://drive.google.com/file/d/1--QAL2sR7KMk9R4DwxyfJAT5iGCheFrn/view>paper</a> <a href=https://arxiv.org/pdf/2003.08744.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#a2d2">A2D2</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minmsd">minMSD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Buhet_2020_CORL,
    author = "Buhet, Thibault and Wirbel, Emilie and Bursuc, Andrei and Perrotton, Xavier",
    title = "PLOP: Probabilistic poLynomial Objects trajectory Planning for autonomous driving",
    booktitle = "CoRL",
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
@Article{Geyer_2020_arxiv,
    author = Geyer, Jakob and Kassahun, Yohannes and Mahmudi, Mentar and Ricou, Xavier and Durgesh, Rupesh and Chung, Andrew S and Hauswald, Lorenz and Pham, Viet Hoang and M{\"u}hlegg, Maximilian and Dorn, Sebastian and others,
    title = "A2d2: Audi autonomous driving dataset",
    journal = "arXiv:2004.06320",
    year = "2020"
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
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#iou">IoU</a></li>
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
<a name=titan></a>
<details close>
<summary><l style="font-size:20px"><strong>TITAN</strong></l> <a href=https://usa.honda-ri.com/titan>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Malla_TITAN_Future_Forecast_Using_Action_Priors_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.13886.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 700 front-view video clips of driving for pedestrian action and trajectory prediction annotated at 10hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Bounding Box, Attribute, Object Class, Tracking ID</li>
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
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fiou">FIoU</a></li>
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
<a name=stip></a>
<details close>
<summary><l style="font-size:20px"><strong>Stanford-TRI Intent Prediction (STIP)</strong></l> <a href=https://stip.stanford.edu/dataset.html>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/9013045>paper</a> <a href=https://arxiv.org/pdf/2002.08945.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of over 900 hours of driving in 5 US cities annotated at 2Hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, activity label, temporal segment, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Liu et al., "Spatiotemporal Relationship Reasoning for Pedestrian Intent Prediction", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9013045>paper</a> <a href=https://arxiv.org/pdf/2002.08945.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/year_datasets.md#stip">STIP</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#precision">Precision</a></li>
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
<a name=vci></a>
<details close>
<summary><l style="font-size:20px"><strong>VCI</strong></l> <a href=https://github.com/dongfang-steven-yang/vci-dataset-dut>link</a> <a href=https://ieeexplore.ieee.org/document/8814092>paper</a> <a href=https://arxiv.org/pdf/1902.00487.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 1793 pedestrian trajectories collected from top-down view using a drone
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Trajectory</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Eiffert et al., "Probabilistic Crowd GAN: Multimodal Pedestrian Trajectory Prediction Using a Graph Vehicle-Pedestrian Attention Network", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9123560>paper</a> <a href=https://arxiv.org/pdf/2006.12906.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/year_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/year_datasets.md#usyd">USyd</a></li>
<li><a href="../datasets/year_datasets.md#vci">VCI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mhd">MHD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Eiffert_2020_RAL,
    author = "Eiffert, S. and Li, K. and Shan, M. and Worrall, S. and Sukkarieh, S. and Nebot, E.",
    journal = "RAL",
    title = "Probabilistic Crowd GAN: Multimodal Pedestrian Trajectory Prediction Using a Graph Vehicle-Pedestrian Attention Network",
    year = "2020",
    volume = "5",
    number = "4",
    pages = "5026-5033"
}
</pre>
</details>

</ul>
</details>
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Yang_2019_IV,
    author = "Yang, D. and Li, L. and Redmill, K. and Özgüner, Ü.",
    booktitle = "IV",
    title = "Top-view Trajectories: A Pedestrian Dataset of Vehicle-Crowd Interaction from Controlled Experiments and Crowded Campus",
    year = "2019"
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
<em><strong>Applications:</strong></em> <a href=../papers/video_papers.md#top>Video prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Bounding Box, Semantic Segment, Lane Marking, Drivable Areas</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Schmeckpeper et al., "Learning Predictive Models From Observation and Interaction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650698.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.12773.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#htud">HTUD</a></li>
<li><a href="../datasets/year_datasets.md#bdd100k">BDD100K</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/video_metrics.md#ssim">SSIM</a></li>
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#lpips">LPIPS</a></li>
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
<li><a href="../metrics/other_metrics.md#mae">MAE</a></li>
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
<li><a href="../metrics/other_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/other_metrics.md#ed">ED</a></li>
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
<li><a href="../metrics/other_metrics.md#precision">Precision</a></li>
<li><a href="../metrics/other_metrics.md#recall">Recall</a></li>
<li><a href="../metrics/other_metrics.md#run_time">Run Time</a></li>
<li><a href="../metrics/other_metrics.md#auc">AUC</a></li>
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
<a name=spmd></a>
<details close>
<summary><l style="font-size:20px"><strong>Safety Pilot Model Deployment (SPMD)</strong></l> <a href=https://catalog.data.gov/dataset/safety-pilot-model-deployment-data>link</a> <a href=https://www.nhtsa.gov/sites/nhtsa.dot.gov/files/812171-safetypilotmodeldeploydeltestcondrtmrep.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of vehicle data collected in Ann Arbor at 10Hz with associated GPS and vehicle data
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> GPS, Vehicle sensor</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Oh et al., "Impact of traffic lights on trajectory forecasting of human-driven vehicles near signalized intersections", IROS, 2020.</em> <a href=http://ras.papercept.net/images/temp/IROS/files/3159.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.00486.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#spmd">SPMD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#mae">MAE</a></li>
<li><a href="../metrics/trajectory_metrics.md#apad">APaD</a></li>
<li><a href="../metrics/trajectory_metrics.md#twae">TWAE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Oh_2020_IROS,
    author = "Oh, Geunseob and Peng, Huei",
    title = "Impact of traffic lights on trajectory forecasting of human-driven vehicles near signalized intersections",
    booktitle = "IROS",
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
@Techreport{Bezzina_2014_tech,
    author = "Bezzina, Debby and Sayer, James",
    title = "Safety pilot model deployment: Test conductor team report",
    institution = "NHTSA",
    year = "2014"
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
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#aede">AEDE</a></li>
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
<a name=a3d></a>
<details close>
<summary><l style="font-size:20px"><strong>AnAn Accident Detection (A3D)</strong></l> <a href=https://github.com/MoonBlvd/tad-IROS2019>link</a> <a href=https://ieeexplore.ieee.org/document/8967556>paper</a> <a href=https://arxiv.org/pdf/1903.00618.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 1500 video clips of traffic accidents with start and end annotations of events
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, temporal segment</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yao et al., "Unsupervised Traffic Accident Detection in First-Person Videos", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8967556>paper</a> <a href=https://arxiv.org/pdf/1903.00618.pdf>arxiv</a> <a href=https://github.com/MoonBlvd/tad-IROS2019>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#dad">DAD</a></li>
<li><a href="../datasets/year_datasets.md#hev-i">HEV-I</a></li>
<li><a href="../datasets/year_datasets.md#a3d">A3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fiou">FioU</a></li>
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
@InProceedings{Yao_2019_IROS,
    author = "Yao, Y. and Xu, M. and Wang, Y. and Crandall, D. J. and Atkins, E. M.",
    booktitle = "IROS",
    title = "Unsupervised Traffic Accident Detection in First-Person Videos",
    year = "2019"
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
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#aede">AEDE</a></li>
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
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
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
<a name=loki></a>
<details close>
<summary><l style="font-size:20px"><strong>Long Term and Key Intentions (LOKI)</strong></l> <a href=https://usa.honda-ri.com/loki>link</a> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Girase_LOKI_Long_Term_and_Key_Intentions_for_Trajectory_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2108.08236.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 644 driving scenarios annotated at 5Hz for 8 traffic objects.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Intention, temporal segment, Attributes, Bounding box</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Girase et al., "LOKI: Long Term and Key Intentions for Trajectory Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Girase_LOKI_Long_Term_and_Key_Intentions_for_Trajectory_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2108.08236.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#loki">LOKI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Girase_2021_ICCV,
    author = "Girase, Harshayu and Gang, Haiming and Malla, Srikanth and Li, Jiachen and Kanehara, Akira and Mangalam, Karttikeya and Choi, Chiho",
    title = "LOKI: Long Term and Key Intentions for Trajectory Prediction",
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
@InProceedings{Girase_2021_ICCV,
    author = "Girase, Harshayu and Gang, Haiming and Malla, Srikanth and Li, Jiachen and Kanehara, Akira and Mangalam, Karttikeya and Choi, Chiho",
    title = "LOKI: Long Term and Key Intentions for Trajectory Prediction",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul></details>
</ul><h2>Driving (simulation)</h2>
<ul><a name=carla></a>
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
<summary><em>Filatov et al., "Any Motion Detector: Learning Class-agnostic Scene Dynamics from a Sequence of LiDAR Point Clouds", ICRA, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9196716>paper</a> <a href=https://arxiv.org/pdf/2004.11647.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/year_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#ap">AP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Filatov_2020_ICRA,
    author = "Filatov, A. and Rykov, A. and Murashkin, V.",
    booktitle = "ICRA",
    title = "Any Motion Detector: Learning Class-agnostic Scene Dynamics from a Sequence of LiDAR Point Clouds",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Roh et al., "Multimodal Trajectory Prediction via Topological Invariance for Navigation at Uncontrolled Intersections", CoRL, 2020.</em> <a href=https://drive.google.com/file/d/1mzKW09aNW683bCveX8bKjUYRo5sVq3fH/view>paper</a> <a href=https://arxiv.org/pdf/2011.03894.pdf>arxiv</a> <a href=https://github.com/rohjunha/multiple-topologies-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minmsd">minMSD</a></li>
<li><a href="../metrics/trajectory_metrics.md#meanmsd">meanMSD</a></li>
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
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
<li><a href="../metrics/trajectory_metrics.md#run_time">Run Time</a></li>
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
<li><a href="../datasets/year_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/year_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/other_metrics.md#f1">F1</a></li>
<li><a href="../metrics/other_metrics.md#ap">AP</a></li>
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
<li><a href="../datasets/year_datasets.md#mnist">MNIST</a></li>
<li><a href="../datasets/year_datasets.md#carla">CARLA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/other_metrics.md#nll">NLL</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
</ul><h2>Face</h2>
<ul><a name=facescape></a>
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
<li><a href="../metrics/other_metrics.md#me">ME</a></li>
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
</ul><h2>Face (expression)</h2>
<ul><a name=mug></a>
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
<li><a href="../metrics/video_metrics.md#psnr">PSNR</a></li>
<li><a href="../metrics/video_metrics.md#mse">MSE</a></li>
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
</ul><h2>Face (smile)</h2>
<ul><a name=uva-nemo></a>
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
<li><a href="../metrics/video_metrics.md#fvd">FVD</a></li>
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
</ul><h2>Fashion</h2>
<ul><a name=amazon></a>
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
<li><a href="../metrics/other_metrics.md#mae">MAE</a></li>
<li><a href="../metrics/other_metrics.md#mape">MAPE</a></li>
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
</ul><h2>Interaction</h2>
<ul><a name=uti></a>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics/action_metrics.md#mrr">MRR</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../metrics/action_metrics.md#map">mAP</a></li>
<li><a href="../metrics/action_metrics.md#cap">cAP</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<summary><em>Wang et al., "Multi-Person 3D Motion Prediction with Multi-Range Transformers", NeurIPS, 2021.</em> <a href=https://papers.nips.cc/paper/2021/file/2fd5d41ec6cfab47e32164d5624269b1-Paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2111.12073.pdf>arxiv</a> <a href=https://github.com/jiashunwang/MRT>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#cmu_mocap">CMU Mocap</a></li>
<li><a href="../datasets/year_datasets.md#3dpw">3DPW</a></li>
<li><a href="../datasets/year_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
<li><a href="../datasets/year_datasets.md#mupots-3d">MuPoTS-3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/motion_metrics.md#mpjpe">MPJPE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2021_NeurIPS,
    author = "Wang, Jiashun and Xu, Huazhe and Narasimhan, Medhini and Wang, Xiaolong",
    booktitle = "NeurIPS",
    title = "Multi-Person 3D Motion Prediction with Multi-Range Transformers",
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
<li><a href="../datasets/year_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../datasets/year_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
<li><a href="../datasets/year_datasets.md#kth-hrc">KTH-HRC</a></li>
<li><a href="../datasets/year_datasets.md#utd-mhad">UTD-MHAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/motion_metrics.md#mse">MSE</a></li>
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
<summary><em>Chen et al., "Group Activity Prediction with Sequential Relational Anticipation Model", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660579.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.02441.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ca">CA</a></li>
<li><a href="../datasets/year_datasets.md#volleyball">Volleyball</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ca">CA</a></li>
<li><a href="../datasets/year_datasets.md#sbuki">SBUKI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/year_datasets.md#ca">CA</a></li>
<li><a href="../datasets/year_datasets.md#sbuki">SBUKI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics/action_metrics.md#f1">F1</a></li>
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
<a name=kth-hrc></a>
<details close>
<summary><l style="font-size:20px"><strong>KTH-HRC</strong></l> <a href=https://github.com/jbutepage/human_robot_interaction_data/tree/master/hh>link</a> <a href=https://www.frontiersin.org/articles/10.3389/frobt.2020.00047/full>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of human-human and human-robot collaboration involving 4 basic actions.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/motion_papers.md#top>Motion prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> 3D pose</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Yasar et al., "A Scalable Approach to Predict Multi-Agent Motion for Human-Robot Collaboration", RAL, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9353218>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#ntu_rgb-d">NTU RGB-D</a></li>
<li><a href="../datasets/year_datasets.md#cmu_panoptic">CMU Panoptic</a></li>
<li><a href="../datasets/year_datasets.md#kth-hrc">KTH-HRC</a></li>
<li><a href="../datasets/year_datasets.md#utd-mhad">UTD-MHAD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/motion_metrics.md#mse">MSE</a></li>
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
@Article{Butepage_2020_FRAI,
    author = "Bütepage, Judith and Ghadirzadeh, Ali and Öztimur Karadaǧ, Özge and Björkman, Mårten and Kragic, Danica",
    journal = "Frontiers in Robotics and AI",
    title = "Imitating by Generating: Deep Generative Models for Imitation of Interactive Tasks",
    year = "2020",
    volume = "7",
    number = "2"
}
</pre>
</details>

</ul></details>
<a name=thor></a>
<details close>
<summary><l style="font-size:20px"><strong>THOR</strong></l> <a href=http://thor.oru.se/>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/8954833>paper</a> <a href=https://arxiv.org/pdf/1909.04403.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of interactions between humans and robots in indoor environment with 60+ minutes to racking and 600+ trajectories.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> LIDAR, 3D pose, Gaze, Map</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhi et al., "Probabilistic Trajectory Prediction with Structural Constraints", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636003>paper</a> <a href=https://arxiv.org/pdf/2107.04193.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/year_datasets.md#lankershim_boulevard">Lankershim Boulevard</a></li>
<li><a href="../datasets/year_datasets.md#thor">THOR</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#al">AL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhi_2021_IROS,
    author = "Zhi, Weiming and Ott, Lionel and Ramos, Fabio",
    booktitle = "IROS",
    title = "Probabilistic Trajectory Prediction with Structural Constraints",
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
@Article{Rudenko_2020_RAL,
    author = "Rudenko, Andrey and Kucner, Tomasz P. and Swaminathan, Chittaranjan S. and Chadalavada, Ravi T. and Arras, Kai O. and Lilienthal, Achim J.",
    journal = "RAL",
    title = "THÖR: Human-Robot Navigation Data Collection and Accurate Motion Trajectories Dataset",
    year = "2020",
    volume = "5",
    number = "2",
    pages = "676-682"
}
</pre>
</details>

</ul></details>
</ul>