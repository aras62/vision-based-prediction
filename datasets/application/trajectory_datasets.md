<a name=top></a>
<a name=top></a>
---
<a href=../../README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Datasets</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../../metrics/metrics.md#top><l style="font-size:30px">Metrics</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
[Home](../datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Alphabetical](../alphabetical/alphabetical_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Year](../year/year_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Application&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Task](../task/task_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Annotation](../annotation_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
[Video](video_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Action](action_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Trajectory&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Motion](motion_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[Other](other_datasets.md#top)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
___
<h2>Trajectory</h2> 

Within each group, the datasets are **sorted** based on their **popularity**, (i.e how often they are used in prediction papers).

 Each dataset in the list has an associated link to the publication page and/or arxiv preprint if available. By **clicking on the dataset** you can get the following information:

* **Summary** of the dataset's characteristics, e.g. quantity, number of objects or classes, etc.
* **Applications** that use the dataset
* **Data type and annotations** available in the dataset
* **Task** of the dataset, e.g. driving, activity, etc
* **Papers** that used the dataset in chronological order
* **Bibtext** of the dataset

<h2>Datasets</h2>
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
<summary><em>Bae et al., "Non-Probability Sampling Network for Stochastic Human Trajectory Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Bae_Non-Probability_Sampling_Network_for_Stochastic_Human_Trajectory_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.13471.pdf>arxiv</a> <a href=https://github.com/inhwanbae/NPSN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#tcc">TCC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bae_2022_CVPR,
    author = "Bae, Inhwan and Park, Jin-Hwi and Jeon, Hae-Gon",
    title = "Non-Probability Sampling Network for Stochastic Human Trajectory Prediction",
    booktitle = "CVPR",
    year = "2022"
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<summary><em>Gu et al., "Stochastic Trajectory Prediction via Motion Indeterminacy Diffusion", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Gu_Stochastic_Trajectory_Prediction_via_Motion_Indeterminacy_Diffusion_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.13777.pdf>arxiv</a> <a href=https://github.com/gutianpei/MID>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gu_2022_CVPR,
    author = "Gu, Tianpei and Chen, Guangyi and Li, Junlong and Lin, Chunze and Rao, Yongming and Zhou, Jie and Lu, Jiwen",
    title = "Stochastic Trajectory Prediction via Motion Indeterminacy Diffusion",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liu et al., "Towards Robust and Adaptive Motion Forecasting: A Causal Representation Perspective", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Towards_Robust_and_Adaptive_Motion_Forecasting_A_Causal_Representation_Perspective_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2111.14820.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2022_CVPR,
    author = "Liu, Yuejiang and Cadei, Riccardo and Schweizer, Jonas and Bahmani, Sherwin and Alahi, Alexandre",
    title = "Towards Robust and Adaptive Motion Forecasting: A Causal Representation Perspective",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Monti et al., "How Many Observations Are Enough? Knowledge Distillation for Trajectory Forecasting", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Monti_How_Many_Observations_Are_Enough_Knowledge_Distillation_for_Trajectory_Forecasting_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.04781.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
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
<summary><em>Xu et al., "Remember Intentions: Retrospective-Memory-Based Trajectory Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_Remember_Intentions_Retrospective-Memory-Based_Trajectory_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.11474.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/MemoNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2022_CVPR,
    author = "Xu, Chenxin and Mao, Weibo and Zhang, Wenjun and Chen, Siheng",
    title = "Remember Intentions: Retrospective-Memory-Based Trajectory Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sun et al., "Human Trajectory Prediction With Momentary Observation", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Sun_Human_Trajectory_Prediction_With_Momentary_Observation_CVPR_2022_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2022_CVPR_2,
    author = "Sun, Jianhua and Li, Yuxuan and Chai, Liang and Fang, Hao-Shu and Li, Yong-Lu and Lu, Cewu",
    title = "Human Trajectory Prediction With Momentary Observation",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "GroupNet: Multiscale Hypergraph Neural Networks for Trajectory Prediction With Relational Reasoning", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_GroupNet_Multiscale_Hypergraph_Neural_Networks_for_Trajectory_Prediction_With_Relational_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.08770.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/GroupNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2022_CVPR_2,
    author = "Xu, Chenxin and Li, Maosen and Ni, Zhenyang and Zhang, Ya and Chen, Siheng",
    title = "GroupNet: Multiscale Hypergraph Neural Networks for Trajectory Prediction With Relational Reasoning",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Adaptive Trajectory Prediction via Transferable GNN", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_Adaptive_Trajectory_Prediction_via_Transferable_GNN_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.05046.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2022_CVPR_3,
    author = "Xu, Yi and Wang, Lichen and Wang, Yizhou and Fu, Yun",
    title = "Adaptive Trajectory Prediction via Transferable GNN",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Bae et al., "Learning Pedestrian Group Representations for Multi-modal Trajectory Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820263.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.09953.pdf>arxiv</a> <a href=https://github.com/inhwanbae/GPGraph>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#tcr">TCR</a></li>
<li><a href="../metrics/trajectory_metrics.md#tcc">TCC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bae_2022_ECCV,
    author = "Bae, Inhwan and Park, Jin-Hwi and Jeon, Hae-Gon",
    title = "Learning Pedestrian Group Representations for Multi-modal Trajectory Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Hu et al., "Entry-Flipped Transformer for Inference and Prediction of Participant Behavior", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136640433.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.06235.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#ceilidh_dance">Ceilidh Dance</a></li>
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
<details close>
<summary><em>Mohamed et al., "Social-Implicit: Rethinking Trajectory Prediction Evaluation and the Effectiveness of Implicit Maximum Likelihood Estimation", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820451.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.03057.pdf>arxiv</a> <a href=https://github.com/abduallahmohamed/Social-Implicit/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#kde">KDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#amv">AMV</a></li>
<li><a href="../metrics/trajectory_metrics.md#amd">AMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mohamed_2022_ECCV,
    author = "Mohamed, Abduallah and Zhu, Deyao and Vu, Warren and Elhoseiny, Mohamed and Claudel, Christian",
    title = "Social-Implicit: Rethinking Trajectory Prediction Evaluation and the Effectiveness of Implicit Maximum Likelihood Estimation",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Tsao et al., "Social-SSL: Self-Supervised Cross-Sequence Representation Learning Based on Transformers for Multi-agent Trajectory Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820227.pdf>paper</a> <a href=https://github.com/Sigta678/Social-SSL>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tsao_2022_ECCV,
    author = "Tsao, Li-Wu and Wang, Yan-Kai and Lin, Hao-Siang and Shuai, Hong-Han and Wong, Lai-Kuan and Cheng, Wen-Huang",
    title = "Social-SSL: Self-Supervised Cross-Sequence Representation Learning Based on Transformers for Multi-agent Trajectory Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wong et al., "View Vertically: A Hierarchical Network for Trajectory Prediction via Fourier Spectrums", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820661.pdf>paper</a> <a href=https://arxiv.org/pdf/2110.07288.pdf>arxiv</a> <a href=https://github.com/cocoon2wong/Vertical>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wong_2022_ECCV,
    author = "Wong, Conghao and Xia, Beihao and Hong, Ziming and Peng, Qinmu and Yuan, Wei and Cao, Qiong and Yang, Yibo and You, Xinge",
    title = "View Vertically: A Hierarchical Network for Trajectory Prediction via Fourier Spectrums",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "SocialVAE: Human Trajectory Prediction Using Timewise Latents", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136640504.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.08207.pdf>arxiv</a> <a href=https://motion-lab.github.io/SocialVAE/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
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
@InProceedings{Xu_2022_ECCV,
    author = "Xu, Pei and Hayet, Jean-Bernard and Karamouzas, Ioannis",
    title = "SocialVAE: Human Trajectory Prediction Using Timewise Latents",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yue et al., "Human Trajectory Prediction via Neural Social Physics", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940368.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.10435.pdf>arxiv</a> <a href=https://github.com/realcrane/Human-Trajectory-Prediction-via-Neural-Social-Physics>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yue_2022_ECCV,
    author = "Yue, Jiangbei and Manocha, Dinesh and Wang, He",
    title = "Human Trajectory Prediction via Neural Social Physics",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Meng et al., "Forecasting Human Trajectory from Scene History", NeurIPS, 2022.</em> <a href=https://openreview.net/pdf?id=RW-OOBU11xl>paper</a> <a href=https://arxiv.org/pdf/2210.08732.pdf>arxiv</a> <a href=https://github.com/MaKaRuiNah/SHENet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#mot">MOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Meng_2022_NeurIPS,
    author = "Meng, Mancheng and Wu, Ziyan and Chen, Terrence and Cai, Xiran and Zhou, Xiang Sean and Yang, Fan and Shen, Dinggang",
    title = "Forecasting Human Trajectory from Scene History",
    booktitle = "NeurIPS",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
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
<summary><em>Hasan et al., "Meta-path Analysis on Spatio-Temporal Graphs for Pedestrian Trajectory Prediction", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9811632>paper</a> <a href=https://arxiv.org/pdf/2202.13427.pdf>arxiv</a> <a href=https://gitlab.engr.illinois.edu/hubris/mesrnn>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hasan_2022_ICRA,
    author = "Hasan, Aamir and Sriram, Pranav and Driggs-Campbell, Katherine",
    booktitle = "ICRA",
    title = "Meta-path Analysis on Spatio-Temporal Graphs for Pedestrian Trajectory Prediction",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#deltaesv">DeltaESV</a></li>
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
<summary><em>Zhou et al., "Grouptron: Dynamic Multi-Scale Graph Convolutional Networks for Group-Aware Dense Crowd Trajectory Forecasting", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9811585>paper</a> <a href=https://arxiv.org/pdf/2109.14128.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhou_2022_ICRA,
    author = "Zhou, Rui and Zhou, Hongyu and Gao, Huidong and Tomizuka, Masayoshi and Li, Jiachen and Xu, Zhuo",
    booktitle = "ICRA",
    title = "Grouptron: Dynamic Multi-Scale Graph Convolutional Networks for Group-Aware Dense Crowd Trajectory Forecasting",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xie et al., "Synchronous Bi-Directional Pedestrian Trajectory Prediction with Error Compensation", ACCV, 2022.</em> <a href=https://openaccess.thecvf.com/content/ACCV2022/papers/Xie_Synchronous_Bi-Directional_Pedestrian_Trajectory_Prediction_with_Error_Compensation_ACCV_2022_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xie_2022_ACCV,
    author = "Xie, Ce and Li, Yuanman and Liang, Rongqin and Dong, Li and Li, Xia",
    title = "Synchronous Bi-Directional Pedestrian Trajectory Prediction with Error Compensation",
    booktitle = "ACCV",
    year = "2022"
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<summary><em>Pang et al., "Trajectory Prediction With Latent Belief Energy-Based Model", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Pang_Trajectory_Prediction_With_Latent_Belief_Energy-Based_Model_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2104.03086.pdf>arxiv</a> <a href=https://github.com/bpucla/lbebm>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Pang_2021_CVPR,
    author = "Pang, Bo and Zhao, Tianyang and Xie, Xu and Wu, Ying Nian",
    title = "Trajectory Prediction With Latent Belief Energy-Based Model",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Shafiee et al., "Introvert: Human Trajectory Prediction via Conditional 3D Attention", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Shafiee_Introvert_Human_Trajectory_Prediction_via_Conditional_3D_Attention_CVPR_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shafiee_2021_CVPR,
    author = "Shafiee, Nasim and Padir, Taskin and Elhamifar, Ehsan",
    title = "Introvert: Human Trajectory Prediction via Conditional 3D Attention",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Shi et al., "SGCN: Sparse Graph Convolution Network for Pedestrian Trajectory Prediction", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Shi_SGCN_Sparse_Graph_Convolution_Network_for_Pedestrian_Trajectory_Prediction_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2104.01528.pdf>arxiv</a> <a href=https://github.com/shuaishiliu/SGCN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shi_2021_CVPR,
    author = "Shi, Liushuai and Wang, Le and Long, Chengjiang and Zhou, Sanping and Zhou, Mo and Niu, Zhenxing and Hua, Gang",
    title = "SGCN: Sparse Graph Convolution Network for Pedestrian Trajectory Prediction",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chen et al., "Personalized Trajectory Prediction via Distribution Discrimination", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Chen_Personalized_Trajectory_Prediction_via_Distribution_Discrimination_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2107.14204.pdf>arxiv</a> <a href=https://github.com/ CHENGY12/DisDis>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2021_ICCV,
    author = "Chen, Guangyi and Li, Junlong and Zhou, Nuoxing and Ren, Liangliang and Lu, Jiwen",
    title = "Personalized Trajectory Prediction via Distribution Discrimination",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Dendorfer et al., "MG-GAN: A Multi-Generator Model Preventing Out-of-Distribution Samples in Pedestrian Trajectory Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Dendorfer_MG-GAN_A_Multi-Generator_Model_Preventing_Out-of-Distribution_Samples_in_Pedestrian_Trajectory_ICCV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Dendorfer_2021_ICCV,
    author = "Dendorfer, Patrick and Elflein, Sven and Leal-Taixe, Laura",
    title = "MG-GAN: A Multi-Generator Model Preventing Out-of-Distribution Samples in Pedestrian Trajectory Prediction",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Li et al., "Spatial-Temporal Consistency Network for Low-Latency Trajectory Forecasting", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Li_Spatial-Temporal_Consistency_Network_for_Low-Latency_Trajectory_Forecasting_ICCV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2021_ICCV,
    author = "Li, Shijie and Zhou, Yanying and Yi, Jinhui and Gall, Juergen",
    title = "Spatial-Temporal Consistency Network for Low-Latency Trajectory Forecasting",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
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
<summary><em>Mangalam et al., "From Goals, Waypoints & Paths to Long Term Human Trajectory Forecasting", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Mangalam_From_Goals_Waypoints__Paths_to_Long_Term_Human_Trajectory_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2012.01526.pdf>arxiv</a> <a href=https://github.com/HarshayuGirase/Human-Path-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mangalam_2021_ICCV,
    author = "Mangalam, Karttikeya and An, Yang and Girase, Harshayu and Malik, Jitendra",
    title = "From Goals, Waypoints \& Paths to Long Term Human Trajectory Forecasting",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sun et al., "Three Steps to Multimodal Trajectory Prediction: Modality Clustering, Classification and Synthesis", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Sun_Three_Steps_to_Multimodal_Trajectory_Prediction_Modality_Clustering_Classification_and_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2103.07854.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2021_ICCV,
    author = "Sun, Jianhua and Li, Yuxuan and Fang, Hao-Shu and Lu, Cewu",
    title = "Three Steps to Multimodal Trajectory Prediction: Modality Clustering, Classification and Synthesis",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yuan_2021_ICCV,
    author = "Yuan, Ye and Weng, Xinshuo and Ou, Yanglan and Kitani, Kris M.",
    title = "AgentFormer: Agent-Aware Transformers for Socio-Temporal Multi-Agent Forecasting",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhao et al., "Where Are You Heading? Dynamic Trajectory Prediction With Expert Goal Examples", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Zhao_Where_Are_You_Heading_Dynamic_Trajectory_Prediction_With_Expert_Goal_ICCV_2021_paper.pdf>paper</a> <a href=https://github.com/JoeHEZHAO/expert_traj>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhao_2021_ICCV,
    author = "Zhao, He and Wildes, Richard P.",
    title = "Where Are You Heading? Dynamic Trajectory Prediction With Expert Goal Examples",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chen et al., "Human Trajectory Prediction via Counterfactual Analysis", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Chen_Human_Trajectory_Prediction_via_Counterfactual_Analysis_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2107.14202.pdf>arxiv</a> <a href=https://github.com/CHENGY12/CausalHTP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2021_ICCV_2,
    author = "Chen, Guangyi and Li, Junlong and Lu, Jiwen and Zhou, Jie",
    title = "Human Trajectory Prediction via Counterfactual Analysis",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liu et al., "AVGCN: Trajectory Prediction using Graph Convolutional Networks Guided by Human Attention", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9560908>paper</a> <a href=https://arxiv.org/pdf/2101.05682.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2021_ICRA,
    author = "Liu, Congcong and Chen, Yuying and Liu, Ming and Shi, Bertram E.",
    booktitle = "ICRA",
    title = "AVGCN: Trajectory Prediction using Graph Convolutional Networks Guided by Human Attention",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Malla et al., "Social-STAGE: Spatio-Temporal Multi-Modal Future Trajectory Forecast", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561582>paper</a> <a href=https://arxiv.org/pdf/2011.04853.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
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
@InProceedings{Malla_2021_ICRA,
    author = "Malla, Srikanth and Choi, Chiho and Dariush, Behzad",
    booktitle = "ICRA",
    title = "Social-STAGE: Spatio-Temporal Multi-Modal Future Trajectory Forecast",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhu et al., "Star Topology based Interaction for Robust Trajectory Forecasting in Dynamic Scene", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561067>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhu_2021_ICRA,
    author = "Zhu, Yanliang and Ren, Dongchun and Qian, Deheng and Fan, Mingyu and Li, Xin and Xia, Huaxia",
    booktitle = "ICRA",
    title = "Star Topology based Interaction for Robust Trajectory Forecasting in Dynamic Scene",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
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
<summary><em>Li et al., "Attentional-GCNN: Adaptive Pedestrian Trajectory Prediction towards Generic Autonomous Vehicle Use Cases", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561480>paper</a> <a href=https://arxiv.org/pdf/2011.11190.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#usyd">USyd</a></li>
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
<summary><em>Bhujel et al., "Self-critical Learning of Influencing Factors for Trajectory Prediction using Gated Graph Convolutional Network", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636641>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bhujel_2021_IROS,
    author = "Bhujel, Niraj and Yun, Yau Wei and Wang, Han and Dwivedi, Vijay Prakash",
    booktitle = "IROS",
    title = "Self-critical Learning of Influencing Factors for Trajectory Prediction using Gated Graph Convolutional Network",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chen et al., "Simultaneous Prediction of Pedestrian Trajectory and Actions based on Context Information Iterative Reasoning", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636252>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Schöller et al., "FloMo: Tractable Motion Prediction with Normalizing Flows", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636445>paper</a> <a href=https://arxiv.org/pdf/2103.03614.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Scholler_2021_IROS,
    author = "Schöller, Christoph and Knoll, Alois",
    booktitle = "IROS",
    title = "FloMo: Tractable Motion Prediction with Normalizing Flows",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Su et al., "CR-LSTM: Collision-prior Guided Social Refinement for Pedestrian Trajectory Prediction", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636722>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Su_2021_IROS,
    author = "Su, Zhaoxin and Zhang, Sanyuan and Hua, Wei",
    booktitle = "IROS",
    title = "CR-LSTM: Collision-prior Guided Social Refinement for Pedestrian Trajectory Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "Group-based Motion Prediction for Navigation in Crowded Environments", CoRL, 2021.</em> <a href=https://openreview.net/pdf?id=knObbYqSowX>paper</a> <a href=https://arxiv.org/pdf/2107.11637.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#fiou">FIoU</a></li>
<li><a href="../metrics/trajectory_metrics.md#miou">MIoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2021_CoRL,
    author = "Wang, Allan and Mavrogiannis, Christoforos and Steinfeld, Aaron",
    title = "Group-based Motion Prediction for Navigation in Crowded Environments",
    booktitle = "CoRL",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Tran et al., "Goal-Driven Long-Term Trajectory Prediction", WACV, 2021.</em> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Tran_Goal-Driven_Long-Term_Trajectory_Prediction_WACV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/abs/2011.02751>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tran_2021_WACV,
    author = "Tran, Hung and Le, Vuong and Tran, Truyen",
    title = "Goal-Driven Long-Term Trajectory Prediction",
    booktitle = "WACV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "GraphTCN: Spatio-Temporal Interaction Modeling for Human Trajectory Prediction", WACV, 2021.</em> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Wang_GraphTCN_Spatio-Temporal_Interaction_Modeling_for_Human_Trajectory_Prediction_WACV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.07167.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2021_WACV,
    author = "Wang, Chengxin and Cai, Shaofeng and Tan, Gary",
    title = "GraphTCN: Spatio-Temporal Interaction Modeling for Human Trajectory Prediction",
    booktitle = "WACV",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
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
<summary><em>Hu et al., "Collaborative Motion Prediction via Neural Motion Message Passing", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Hu_Collaborative_Motion_Prediction_via_Neural_Motion_Message_Passing_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.06594.pdf>arxiv</a> <a href=https://github.com/PhyllisH/NMMP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<summary><em>Mohamed et al., "Social-STGCNN: A Social Spatio-Temporal Graph Convolutional Neural Network for Human Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Mohamed_Social-STGCNN_A_Social_Spatio-Temporal_Graph_Convolutional_Neural_Network_for_Human_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2002.11927.pdf>arxiv</a> <a href=https://github.com/abduallahmohamed/Social-STGCNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Sun et al., "Recursive Social Behavior Graph for Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Sun_Recursive_Social_Behavior_Graph_for_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.10402.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Bi et al., "How Can I See My Future? FvTraj: Using First-person View for Pedestrian Trajectory Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520562.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bi_2020_ECCV,
    author = "Bi, Huikun and Zhang, Ruisi and Mao, Tianlu and Deng, Zhigang and Wang, Zhaoqi",
    title = "How Can I See My Future? FvTraj: Using First-person View for Pedestrian Trajectory Prediction",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ma et al., "AutoTrajectory: Label-free Trajectory Extraction and Prediction from Videos using Dynamic Points", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580630.pdf>paper</a> <a href=https://arxiv.org/pdf/2007.05719.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ma_2020_ECCV,
    author = "Ma, Yuexin and Zhu, Xinge and Cheng, Xinjing and Yang, Ruigang and Liu, Jiming and Manocha, Dinesh",
    title = "AutoTrajectory: Label-free Trajectory Extraction and Prediction from Videos using Dynamic Points",
    booktitle = "ECCV",
    year = "2020"
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Salzmann et al., "Trajectron++: Multi-agent generative trajectory forecasting with heterogeneous data for control", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123630664.pdf>paper</a> <a href=https://arxiv.org/pdf/2001.03093.pdf>arxiv</a> <a href=https://github.com/StanfordASL/Trajectron-plus-plus>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<summary><em>Tao et al., "Dynamic and Static Context-aware LSTM for Multi-agent Motion Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660545.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.00777.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#tcc">TCC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tao_2020_ECCV,
    author = "Tao, Chaofan and Jiang, Qinhong and Duan, Lixin and Luo, Ping",
    title = "Dynamic and Static Context-aware LSTM for Multi-agent Motion Prediction",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yu et al., "Spatio-Temporal Graph Transformer Networks for Pedestrian Trajectory Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123570494.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.08514.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yu_2020_ECCV,
    author = "Yu, Cunjun and Ma, Xiao and Ren, Jiawei and Zhao, Haiyu and Yi, Shuai",
    title = "Spatio-Temporal Graph Transformer Networks for Pedestrian Trajectory Prediction",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#charges">Charges</a></li>
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
<summary><em>Chen et al., "CoMoGCN: Coherent motion aware trajectory prediction with graph representation", BMVC, 2020.</em> <a href=https://www.bmvc2020-conference.com/assets/papers/0238.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.00754.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2020_BMVC,
    author = "Chen, Yuying and Liu, Congcong and Shi, Bertram and Liu, Ming",
    title = "CoMoGCN: Coherent motion aware trajectory prediction with graph representation",
    booktitle = "BMVC",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Dendorfer et al., "Goal-GAN: Multimodal Trajectory Prediction Based on Goal Position Estimation", ACCV, 2020.</em> <a href=https://openaccess.thecvf.com/content/ACCV2020/papers/Dendorfer_Goal-GAN_Multimodal_Trajectory_Prediction_Based_on_Goal_Position_Estimation_ACCV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2010.01114.pdf>arxiv</a> <a href=https://github.com/dendorferpatrick/GoalGAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#mc">MC</a></li>
<li><a href="../metrics/trajectory_metrics.md#f">F</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Dendorfer_2020_ACCV,
    author = "Dendorfer, Patrick and Osep, Aljosa and Leal-Taixe, Laura",
    title = "Goal-GAN: Multimodal Trajectory Prediction Based on Goal Position Estimation",
    booktitle = "ACCV",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Katyal et al., "Intent-Aware Pedestrian Prediction for Adaptive Crowd Navigation", ICRA, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9197434>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Katyal_2020_ICRA,
    author = "Katyal, K. D. and Hager, G. D. and Huang, C. -M.",
    booktitle = "ICRA",
    title = "Intent-Aware Pedestrian Prediction for Adaptive Crowd Navigation",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Dwivedi et al., "SSP: Single Shot Future Trajectory Prediction", IROS, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9340754>paper</a> <a href=https://arxiv.org/pdf/2004.05846.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Dwivedi_2020_IROS,
    author = "Dwivedi, I. and Malla, S. and Dariush, B. and Choi, C.",
    booktitle = "IROS",
    title = "SSP: Single Shot Future Trajectory Prediction",
    year = "2020"
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#usyd">USyd</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#vci">VCI</a></li>
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
<details close>
<summary><em>Gilitschenski et al., "Deep Context Maps: Agent Trajectory Prediction Using Location-Specific Latent Maps", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9126143>paper</a> <a href=https://arxiv.org/pdf/1912.06785.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Gilitschenski_2020_RAL,
    author = "Gilitschenski, I. and Rosman, G. and Gupta, A. and Karaman, S. and Rus, D.",
    journal = "RAL",
    title = "Deep Context Maps: Agent Trajectory Prediction Using Location-Specific Latent Maps",
    year = "2020",
    volume = "5",
    number = "4",
    pages = "5097-5104"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Schöller et al., "What the Constant Velocity Model Can Teach Us About Pedestrian Motion Prediction", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/8972605>paper</a> <a href=https://arxiv.org/pdf/1903.07933.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Scholler_2020_RAL,
    author = "Schöller, C. and Aravantinos, V. and Lay, F. and Knoll, A.",
    journal = "RAL",
    title = "What the Constant Velocity Model Can Teach Us About Pedestrian Motion Prediction",
    year = "2020",
    volume = "5",
    number = "2",
    pages = "1696-1703"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Brito et al., "Social-VRNN: One-Shot Multi-modal Trajectory Prediction for Interacting Pedestrians", CoRL, 2020.</em> <a href=https://drive.google.com/file/d/1EKg07pBCdlMUQD4oAx75lDr6hAYTzXuW/view>paper</a> <a href=https://arxiv.org/pdf/2010.09056.pdf>arxiv</a> <a href=https://github.com/tud-amr/social_vrnn>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Brito_2020_CORL,
    author = "Brito, Bruno and Zhu, Hai and Pan, Wei and Alonso-Mora, Javier",
    title = "Social-VRNN: One-Shot Multi-modal Trajectory Prediction for Interacting Pedestrians",
    booktitle = "CoRL",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#virat/actev">VIRAT/ActEV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
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
<summary><em>Choi et al., "Looking To Relations For Future Trajectory Forecast", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Choi_Looking_to_Relations_for_Future_Trajectory_Forecast_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.08855.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
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
<summary><em>Kosaraju et al., "Social-Bigat: Multimodal Trajectory Forecasting Using Bicycle-Gan And Graph Attention Networks", NeurIPS, 2019.</em> <a href=http://papers.nips.cc/paper/8308-social-bigat-multimodal-trajectory-forecasting-using-bicycle-gan-and-graph-attention-networks.pdf>paper</a> <a href=https://arxiv.org/pdf/1907.03395.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
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
<details close>
<summary><em>Zhu et al., "Starnet: Pedestrian Trajectory Prediction Using Deep Neural Network In Star Topology", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8967811>paper</a> <a href=https://arxiv.org/pdf/1906.01797.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pets2009">PETS2009</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#town_center">Town Center</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#chuk">CHUK</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#ande">ANDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#town_center">Town Center</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mane">MAnE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#town_center">Town Center</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#scr">SCR</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#ande">ANDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
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
<summary><em>Wang et al., "Group Split and Merge Prediction With 3D Convolutional Networks", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/8972421>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
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
<summary><em>Bae et al., "Non-Probability Sampling Network for Stochastic Human Trajectory Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Bae_Non-Probability_Sampling_Network_for_Stochastic_Human_Trajectory_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.13471.pdf>arxiv</a> <a href=https://github.com/inhwanbae/NPSN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#tcc">TCC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bae_2022_CVPR,
    author = "Bae, Inhwan and Park, Jin-Hwi and Jeon, Hae-Gon",
    title = "Non-Probability Sampling Network for Stochastic Human Trajectory Prediction",
    booktitle = "CVPR",
    year = "2022"
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<summary><em>Gu et al., "Stochastic Trajectory Prediction via Motion Indeterminacy Diffusion", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Gu_Stochastic_Trajectory_Prediction_via_Motion_Indeterminacy_Diffusion_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.13777.pdf>arxiv</a> <a href=https://github.com/gutianpei/MID>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gu_2022_CVPR,
    author = "Gu, Tianpei and Chen, Guangyi and Li, Junlong and Lin, Chunze and Rao, Yongming and Zhou, Jie and Lu, Jiwen",
    title = "Stochastic Trajectory Prediction via Motion Indeterminacy Diffusion",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liu et al., "Towards Robust and Adaptive Motion Forecasting: A Causal Representation Perspective", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Towards_Robust_and_Adaptive_Motion_Forecasting_A_Causal_Representation_Perspective_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2111.14820.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2022_CVPR,
    author = "Liu, Yuejiang and Cadei, Riccardo and Schweizer, Jonas and Bahmani, Sherwin and Alahi, Alexandre",
    title = "Towards Robust and Adaptive Motion Forecasting: A Causal Representation Perspective",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Monti et al., "How Many Observations Are Enough? Knowledge Distillation for Trajectory Forecasting", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Monti_How_Many_Observations_Are_Enough_Knowledge_Distillation_for_Trajectory_Forecasting_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.04781.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
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
<summary><em>Xu et al., "Remember Intentions: Retrospective-Memory-Based Trajectory Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_Remember_Intentions_Retrospective-Memory-Based_Trajectory_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.11474.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/MemoNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2022_CVPR,
    author = "Xu, Chenxin and Mao, Weibo and Zhang, Wenjun and Chen, Siheng",
    title = "Remember Intentions: Retrospective-Memory-Based Trajectory Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sun et al., "Human Trajectory Prediction With Momentary Observation", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Sun_Human_Trajectory_Prediction_With_Momentary_Observation_CVPR_2022_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2022_CVPR_2,
    author = "Sun, Jianhua and Li, Yuxuan and Chai, Liang and Fang, Hao-Shu and Li, Yong-Lu and Lu, Cewu",
    title = "Human Trajectory Prediction With Momentary Observation",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "GroupNet: Multiscale Hypergraph Neural Networks for Trajectory Prediction With Relational Reasoning", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_GroupNet_Multiscale_Hypergraph_Neural_Networks_for_Trajectory_Prediction_With_Relational_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.08770.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/GroupNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2022_CVPR_2,
    author = "Xu, Chenxin and Li, Maosen and Ni, Zhenyang and Zhang, Ya and Chen, Siheng",
    title = "GroupNet: Multiscale Hypergraph Neural Networks for Trajectory Prediction With Relational Reasoning",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "Adaptive Trajectory Prediction via Transferable GNN", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_Adaptive_Trajectory_Prediction_via_Transferable_GNN_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.05046.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2022_CVPR_3,
    author = "Xu, Yi and Wang, Lichen and Wang, Yizhou and Fu, Yun",
    title = "Adaptive Trajectory Prediction via Transferable GNN",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Bae et al., "Learning Pedestrian Group Representations for Multi-modal Trajectory Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820263.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.09953.pdf>arxiv</a> <a href=https://github.com/inhwanbae/GPGraph>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#tcr">TCR</a></li>
<li><a href="../metrics/trajectory_metrics.md#tcc">TCC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bae_2022_ECCV,
    author = "Bae, Inhwan and Park, Jin-Hwi and Jeon, Hae-Gon",
    title = "Learning Pedestrian Group Representations for Multi-modal Trajectory Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Hu et al., "Entry-Flipped Transformer for Inference and Prediction of Participant Behavior", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136640433.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.06235.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#ceilidh_dance">Ceilidh Dance</a></li>
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
<details close>
<summary><em>Mohamed et al., "Social-Implicit: Rethinking Trajectory Prediction Evaluation and the Effectiveness of Implicit Maximum Likelihood Estimation", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820451.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.03057.pdf>arxiv</a> <a href=https://github.com/abduallahmohamed/Social-Implicit/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#kde">KDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#amv">AMV</a></li>
<li><a href="../metrics/trajectory_metrics.md#amd">AMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mohamed_2022_ECCV,
    author = "Mohamed, Abduallah and Zhu, Deyao and Vu, Warren and Elhoseiny, Mohamed and Claudel, Christian",
    title = "Social-Implicit: Rethinking Trajectory Prediction Evaluation and the Effectiveness of Implicit Maximum Likelihood Estimation",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Tsao et al., "Social-SSL: Self-Supervised Cross-Sequence Representation Learning Based on Transformers for Multi-agent Trajectory Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820227.pdf>paper</a> <a href=https://github.com/Sigta678/Social-SSL>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tsao_2022_ECCV,
    author = "Tsao, Li-Wu and Wang, Yan-Kai and Lin, Hao-Siang and Shuai, Hong-Han and Wong, Lai-Kuan and Cheng, Wen-Huang",
    title = "Social-SSL: Self-Supervised Cross-Sequence Representation Learning Based on Transformers for Multi-agent Trajectory Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wong et al., "View Vertically: A Hierarchical Network for Trajectory Prediction via Fourier Spectrums", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820661.pdf>paper</a> <a href=https://arxiv.org/pdf/2110.07288.pdf>arxiv</a> <a href=https://github.com/cocoon2wong/Vertical>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wong_2022_ECCV,
    author = "Wong, Conghao and Xia, Beihao and Hong, Ziming and Peng, Qinmu and Yuan, Wei and Cao, Qiong and Yang, Yibo and You, Xinge",
    title = "View Vertically: A Hierarchical Network for Trajectory Prediction via Fourier Spectrums",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "SocialVAE: Human Trajectory Prediction Using Timewise Latents", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136640504.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.08207.pdf>arxiv</a> <a href=https://motion-lab.github.io/SocialVAE/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
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
@InProceedings{Xu_2022_ECCV,
    author = "Xu, Pei and Hayet, Jean-Bernard and Karamouzas, Ioannis",
    title = "SocialVAE: Human Trajectory Prediction Using Timewise Latents",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yue et al., "Human Trajectory Prediction via Neural Social Physics", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940368.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.10435.pdf>arxiv</a> <a href=https://github.com/realcrane/Human-Trajectory-Prediction-via-Neural-Social-Physics>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yue_2022_ECCV,
    author = "Yue, Jiangbei and Manocha, Dinesh and Wang, He",
    title = "Human Trajectory Prediction via Neural Social Physics",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Meng et al., "Forecasting Human Trajectory from Scene History", NeurIPS, 2022.</em> <a href=https://openreview.net/pdf?id=RW-OOBU11xl>paper</a> <a href=https://arxiv.org/pdf/2210.08732.pdf>arxiv</a> <a href=https://github.com/MaKaRuiNah/SHENet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#mot">MOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Meng_2022_NeurIPS,
    author = "Meng, Mancheng and Wu, Ziyan and Chen, Terrence and Cai, Xiran and Zhou, Xiang Sean and Yang, Fan and Shen, Dinggang",
    title = "Forecasting Human Trajectory from Scene History",
    booktitle = "NeurIPS",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
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
<summary><em>Hasan et al., "Meta-path Analysis on Spatio-Temporal Graphs for Pedestrian Trajectory Prediction", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9811632>paper</a> <a href=https://arxiv.org/pdf/2202.13427.pdf>arxiv</a> <a href=https://gitlab.engr.illinois.edu/hubris/mesrnn>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hasan_2022_ICRA,
    author = "Hasan, Aamir and Sriram, Pranav and Driggs-Campbell, Katherine",
    booktitle = "ICRA",
    title = "Meta-path Analysis on Spatio-Temporal Graphs for Pedestrian Trajectory Prediction",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#deltaesv">DeltaESV</a></li>
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
<summary><em>Zhou et al., "Grouptron: Dynamic Multi-Scale Graph Convolutional Networks for Group-Aware Dense Crowd Trajectory Forecasting", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9811585>paper</a> <a href=https://arxiv.org/pdf/2109.14128.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhou_2022_ICRA,
    author = "Zhou, Rui and Zhou, Hongyu and Gao, Huidong and Tomizuka, Masayoshi and Li, Jiachen and Xu, Zhuo",
    booktitle = "ICRA",
    title = "Grouptron: Dynamic Multi-Scale Graph Convolutional Networks for Group-Aware Dense Crowd Trajectory Forecasting",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xie et al., "Synchronous Bi-Directional Pedestrian Trajectory Prediction with Error Compensation", ACCV, 2022.</em> <a href=https://openaccess.thecvf.com/content/ACCV2022/papers/Xie_Synchronous_Bi-Directional_Pedestrian_Trajectory_Prediction_with_Error_Compensation_ACCV_2022_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xie_2022_ACCV,
    author = "Xie, Ce and Li, Yuanman and Liang, Rongqin and Dong, Li and Li, Xia",
    title = "Synchronous Bi-Directional Pedestrian Trajectory Prediction with Error Compensation",
    booktitle = "ACCV",
    year = "2022"
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<summary><em>Pang et al., "Trajectory Prediction With Latent Belief Energy-Based Model", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Pang_Trajectory_Prediction_With_Latent_Belief_Energy-Based_Model_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2104.03086.pdf>arxiv</a> <a href=https://github.com/bpucla/lbebm>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Pang_2021_CVPR,
    author = "Pang, Bo and Zhao, Tianyang and Xie, Xu and Wu, Ying Nian",
    title = "Trajectory Prediction With Latent Belief Energy-Based Model",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Shafiee et al., "Introvert: Human Trajectory Prediction via Conditional 3D Attention", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Shafiee_Introvert_Human_Trajectory_Prediction_via_Conditional_3D_Attention_CVPR_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shafiee_2021_CVPR,
    author = "Shafiee, Nasim and Padir, Taskin and Elhamifar, Ehsan",
    title = "Introvert: Human Trajectory Prediction via Conditional 3D Attention",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Shi et al., "SGCN: Sparse Graph Convolution Network for Pedestrian Trajectory Prediction", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Shi_SGCN_Sparse_Graph_Convolution_Network_for_Pedestrian_Trajectory_Prediction_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2104.01528.pdf>arxiv</a> <a href=https://github.com/shuaishiliu/SGCN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Shi_2021_CVPR,
    author = "Shi, Liushuai and Wang, Le and Long, Chengjiang and Zhou, Sanping and Zhou, Mo and Niu, Zhenxing and Hua, Gang",
    title = "SGCN: Sparse Graph Convolution Network for Pedestrian Trajectory Prediction",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chen et al., "Personalized Trajectory Prediction via Distribution Discrimination", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Chen_Personalized_Trajectory_Prediction_via_Distribution_Discrimination_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2107.14204.pdf>arxiv</a> <a href=https://github.com/ CHENGY12/DisDis>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2021_ICCV,
    author = "Chen, Guangyi and Li, Junlong and Zhou, Nuoxing and Ren, Liangliang and Lu, Jiwen",
    title = "Personalized Trajectory Prediction via Distribution Discrimination",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Dendorfer et al., "MG-GAN: A Multi-Generator Model Preventing Out-of-Distribution Samples in Pedestrian Trajectory Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Dendorfer_MG-GAN_A_Multi-Generator_Model_Preventing_Out-of-Distribution_Samples_in_Pedestrian_Trajectory_ICCV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Dendorfer_2021_ICCV,
    author = "Dendorfer, Patrick and Elflein, Sven and Leal-Taixe, Laura",
    title = "MG-GAN: A Multi-Generator Model Preventing Out-of-Distribution Samples in Pedestrian Trajectory Prediction",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Li et al., "Spatial-Temporal Consistency Network for Low-Latency Trajectory Forecasting", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Li_Spatial-Temporal_Consistency_Network_for_Low-Latency_Trajectory_Forecasting_ICCV_2021_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2021_ICCV,
    author = "Li, Shijie and Zhou, Yanying and Yi, Jinhui and Gall, Juergen",
    title = "Spatial-Temporal Consistency Network for Low-Latency Trajectory Forecasting",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
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
<summary><em>Mangalam et al., "From Goals, Waypoints & Paths to Long Term Human Trajectory Forecasting", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Mangalam_From_Goals_Waypoints__Paths_to_Long_Term_Human_Trajectory_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2012.01526.pdf>arxiv</a> <a href=https://github.com/HarshayuGirase/Human-Path-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mangalam_2021_ICCV,
    author = "Mangalam, Karttikeya and An, Yang and Girase, Harshayu and Malik, Jitendra",
    title = "From Goals, Waypoints \& Paths to Long Term Human Trajectory Forecasting",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sun et al., "Three Steps to Multimodal Trajectory Prediction: Modality Clustering, Classification and Synthesis", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Sun_Three_Steps_to_Multimodal_Trajectory_Prediction_Modality_Clustering_Classification_and_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2103.07854.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2021_ICCV,
    author = "Sun, Jianhua and Li, Yuxuan and Fang, Hao-Shu and Lu, Cewu",
    title = "Three Steps to Multimodal Trajectory Prediction: Modality Clustering, Classification and Synthesis",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yuan_2021_ICCV,
    author = "Yuan, Ye and Weng, Xinshuo and Ou, Yanglan and Kitani, Kris M.",
    title = "AgentFormer: Agent-Aware Transformers for Socio-Temporal Multi-Agent Forecasting",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhao et al., "Where Are You Heading? Dynamic Trajectory Prediction With Expert Goal Examples", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Zhao_Where_Are_You_Heading_Dynamic_Trajectory_Prediction_With_Expert_Goal_ICCV_2021_paper.pdf>paper</a> <a href=https://github.com/JoeHEZHAO/expert_traj>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhao_2021_ICCV,
    author = "Zhao, He and Wildes, Richard P.",
    title = "Where Are You Heading? Dynamic Trajectory Prediction With Expert Goal Examples",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chen et al., "Human Trajectory Prediction via Counterfactual Analysis", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Chen_Human_Trajectory_Prediction_via_Counterfactual_Analysis_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2107.14202.pdf>arxiv</a> <a href=https://github.com/CHENGY12/CausalHTP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2021_ICCV_2,
    author = "Chen, Guangyi and Li, Junlong and Lu, Jiwen and Zhou, Jie",
    title = "Human Trajectory Prediction via Counterfactual Analysis",
    booktitle = "ICCV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Liu et al., "AVGCN: Trajectory Prediction using Graph Convolutional Networks Guided by Human Attention", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9560908>paper</a> <a href=https://arxiv.org/pdf/2101.05682.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Liu_2021_ICRA,
    author = "Liu, Congcong and Chen, Yuying and Liu, Ming and Shi, Bertram E.",
    booktitle = "ICRA",
    title = "AVGCN: Trajectory Prediction using Graph Convolutional Networks Guided by Human Attention",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Malla et al., "Social-STAGE: Spatio-Temporal Multi-Modal Future Trajectory Forecast", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561582>paper</a> <a href=https://arxiv.org/pdf/2011.04853.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
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
@InProceedings{Malla_2021_ICRA,
    author = "Malla, Srikanth and Choi, Chiho and Dariush, Behzad",
    booktitle = "ICRA",
    title = "Social-STAGE: Spatio-Temporal Multi-Modal Future Trajectory Forecast",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhu et al., "Star Topology based Interaction for Robust Trajectory Forecasting in Dynamic Scene", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561067>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhu_2021_ICRA,
    author = "Zhu, Yanliang and Ren, Dongchun and Qian, Deheng and Fan, Mingyu and Li, Xin and Xia, Huaxia",
    booktitle = "ICRA",
    title = "Star Topology based Interaction for Robust Trajectory Forecasting in Dynamic Scene",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
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
<summary><em>Li et al., "Attentional-GCNN: Adaptive Pedestrian Trajectory Prediction towards Generic Autonomous Vehicle Use Cases", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9561480>paper</a> <a href=https://arxiv.org/pdf/2011.11190.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#usyd">USyd</a></li>
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
<summary><em>Bhujel et al., "Self-critical Learning of Influencing Factors for Trajectory Prediction using Gated Graph Convolutional Network", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636641>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bhujel_2021_IROS,
    author = "Bhujel, Niraj and Yun, Yau Wei and Wang, Han and Dwivedi, Vijay Prakash",
    booktitle = "IROS",
    title = "Self-critical Learning of Influencing Factors for Trajectory Prediction using Gated Graph Convolutional Network",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Chen et al., "Simultaneous Prediction of Pedestrian Trajectory and Actions based on Context Information Iterative Reasoning", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636252>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Postnikov et al., "CovarianceNet: Conditional Generative Model for Correct Covariance Prediction in Human Motion Prediction", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9635968>paper</a> <a href=https://arxiv.org/pdf/2109.02965.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#ppei">PPEI</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Postnikov_2021_IROS,
    author = "Postnikov, Aleksey and Gamayunov, Aleksander and Ferrer, Gonzalo",
    booktitle = "IROS",
    title = "CovarianceNet: Conditional Generative Model for Correct Covariance Prediction in Human Motion Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Schöller et al., "FloMo: Tractable Motion Prediction with Normalizing Flows", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636445>paper</a> <a href=https://arxiv.org/pdf/2103.03614.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Scholler_2021_IROS,
    author = "Schöller, Christoph and Knoll, Alois",
    booktitle = "IROS",
    title = "FloMo: Tractable Motion Prediction with Normalizing Flows",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Su et al., "CR-LSTM: Collision-prior Guided Social Refinement for Pedestrian Trajectory Prediction", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636722>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Su_2021_IROS,
    author = "Su, Zhaoxin and Zhang, Sanyuan and Hua, Wei",
    booktitle = "IROS",
    title = "CR-LSTM: Collision-prior Guided Social Refinement for Pedestrian Trajectory Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "Group-based Motion Prediction for Navigation in Crowded Environments", CoRL, 2021.</em> <a href=https://openreview.net/pdf?id=knObbYqSowX>paper</a> <a href=https://arxiv.org/pdf/2107.11637.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#fiou">FIoU</a></li>
<li><a href="../metrics/trajectory_metrics.md#miou">MIoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2021_CoRL,
    author = "Wang, Allan and Mavrogiannis, Christoforos and Steinfeld, Aaron",
    title = "Group-based Motion Prediction for Navigation in Crowded Environments",
    booktitle = "CoRL",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Tran et al., "Goal-Driven Long-Term Trajectory Prediction", WACV, 2021.</em> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Tran_Goal-Driven_Long-Term_Trajectory_Prediction_WACV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/abs/2011.02751>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tran_2021_WACV,
    author = "Tran, Hung and Le, Vuong and Tran, Truyen",
    title = "Goal-Driven Long-Term Trajectory Prediction",
    booktitle = "WACV",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wang et al., "GraphTCN: Spatio-Temporal Interaction Modeling for Human Trajectory Prediction", WACV, 2021.</em> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Wang_GraphTCN_Spatio-Temporal_Interaction_Modeling_for_Human_Trajectory_Prediction_WACV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.07167.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wang_2021_WACV,
    author = "Wang, Chengxin and Cai, Shaofeng and Tan, Gary",
    title = "GraphTCN: Spatio-Temporal Interaction Modeling for Human Trajectory Prediction",
    booktitle = "WACV",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
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
<summary><em>Hu et al., "Collaborative Motion Prediction via Neural Motion Message Passing", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Hu_Collaborative_Motion_Prediction_via_Neural_Motion_Message_Passing_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.06594.pdf>arxiv</a> <a href=https://github.com/PhyllisH/NMMP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<summary><em>Mohamed et al., "Social-STGCNN: A Social Spatio-Temporal Graph Convolutional Neural Network for Human Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Mohamed_Social-STGCNN_A_Social_Spatio-Temporal_Graph_Convolutional_Neural_Network_for_Human_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2002.11927.pdf>arxiv</a> <a href=https://github.com/abduallahmohamed/Social-STGCNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Sun et al., "Recursive Social Behavior Graph for Trajectory Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Sun_Recursive_Social_Behavior_Graph_for_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.10402.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Bi et al., "How Can I See My Future? FvTraj: Using First-person View for Pedestrian Trajectory Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520562.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bi_2020_ECCV,
    author = "Bi, Huikun and Zhang, Ruisi and Mao, Tianlu and Deng, Zhigang and Wang, Zhaoqi",
    title = "How Can I See My Future? FvTraj: Using First-person View for Pedestrian Trajectory Prediction",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ma et al., "AutoTrajectory: Label-free Trajectory Extraction and Prediction from Videos using Dynamic Points", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580630.pdf>paper</a> <a href=https://arxiv.org/pdf/2007.05719.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ma_2020_ECCV,
    author = "Ma, Yuexin and Zhu, Xinge and Cheng, Xinjing and Yang, Ruigang and Liu, Jiming and Manocha, Dinesh",
    title = "AutoTrajectory: Label-free Trajectory Extraction and Prediction from Videos using Dynamic Points",
    booktitle = "ECCV",
    year = "2020"
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Salzmann et al., "Trajectron++: Multi-agent generative trajectory forecasting with heterogeneous data for control", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123630664.pdf>paper</a> <a href=https://arxiv.org/pdf/2001.03093.pdf>arxiv</a> <a href=https://github.com/StanfordASL/Trajectron-plus-plus>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<summary><em>Tao et al., "Dynamic and Static Context-aware LSTM for Multi-agent Motion Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660545.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.00777.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#tcc">TCC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tao_2020_ECCV,
    author = "Tao, Chaofan and Jiang, Qinhong and Duan, Lixin and Luo, Ping",
    title = "Dynamic and Static Context-aware LSTM for Multi-agent Motion Prediction",
    booktitle = "ECCV",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yu et al., "Spatio-Temporal Graph Transformer Networks for Pedestrian Trajectory Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123570494.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.08514.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yu_2020_ECCV,
    author = "Yu, Cunjun and Ma, Xiao and Ren, Jiawei and Zhao, Haiyu and Yi, Shuai",
    title = "Spatio-Temporal Graph Transformer Networks for Pedestrian Trajectory Prediction",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#charges">Charges</a></li>
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
<summary><em>Chen et al., "CoMoGCN: Coherent motion aware trajectory prediction with graph representation", BMVC, 2020.</em> <a href=https://www.bmvc2020-conference.com/assets/papers/0238.pdf>paper</a> <a href=https://arxiv.org/pdf/2005.00754.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2020_BMVC,
    author = "Chen, Yuying and Liu, Congcong and Shi, Bertram and Liu, Ming",
    title = "CoMoGCN: Coherent motion aware trajectory prediction with graph representation",
    booktitle = "BMVC",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Dendorfer et al., "Goal-GAN: Multimodal Trajectory Prediction Based on Goal Position Estimation", ACCV, 2020.</em> <a href=https://openaccess.thecvf.com/content/ACCV2020/papers/Dendorfer_Goal-GAN_Multimodal_Trajectory_Prediction_Based_on_Goal_Position_Estimation_ACCV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2010.01114.pdf>arxiv</a> <a href=https://github.com/dendorferpatrick/GoalGAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#mc">MC</a></li>
<li><a href="../metrics/trajectory_metrics.md#f">F</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Dendorfer_2020_ACCV,
    author = "Dendorfer, Patrick and Osep, Aljosa and Leal-Taixe, Laura",
    title = "Goal-GAN: Multimodal Trajectory Prediction Based on Goal Position Estimation",
    booktitle = "ACCV",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Katyal et al., "Intent-Aware Pedestrian Prediction for Adaptive Crowd Navigation", ICRA, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9197434>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Katyal_2020_ICRA,
    author = "Katyal, K. D. and Hager, G. D. and Huang, C. -M.",
    booktitle = "ICRA",
    title = "Intent-Aware Pedestrian Prediction for Adaptive Crowd Navigation",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Dwivedi et al., "SSP: Single Shot Future Trajectory Prediction", IROS, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9340754>paper</a> <a href=https://arxiv.org/pdf/2004.05846.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Dwivedi_2020_IROS,
    author = "Dwivedi, I. and Malla, S. and Dariush, B. and Choi, C.",
    booktitle = "IROS",
    title = "SSP: Single Shot Future Trajectory Prediction",
    year = "2020"
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#usyd">USyd</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#vci">VCI</a></li>
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
<details close>
<summary><em>Gilitschenski et al., "Deep Context Maps: Agent Trajectory Prediction Using Location-Specific Latent Maps", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9126143>paper</a> <a href=https://arxiv.org/pdf/1912.06785.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Gilitschenski_2020_RAL,
    author = "Gilitschenski, I. and Rosman, G. and Gupta, A. and Karaman, S. and Rus, D.",
    journal = "RAL",
    title = "Deep Context Maps: Agent Trajectory Prediction Using Location-Specific Latent Maps",
    year = "2020",
    volume = "5",
    number = "4",
    pages = "5097-5104"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Schöller et al., "What the Constant Velocity Model Can Teach Us About Pedestrian Motion Prediction", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/8972605>paper</a> <a href=https://arxiv.org/pdf/1903.07933.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Scholler_2020_RAL,
    author = "Schöller, C. and Aravantinos, V. and Lay, F. and Knoll, A.",
    journal = "RAL",
    title = "What the Constant Velocity Model Can Teach Us About Pedestrian Motion Prediction",
    year = "2020",
    volume = "5",
    number = "2",
    pages = "1696-1703"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Brito et al., "Social-VRNN: One-Shot Multi-modal Trajectory Prediction for Interacting Pedestrians", CoRL, 2020.</em> <a href=https://drive.google.com/file/d/1EKg07pBCdlMUQD4oAx75lDr6hAYTzXuW/view>paper</a> <a href=https://arxiv.org/pdf/2010.09056.pdf>arxiv</a> <a href=https://github.com/tud-amr/social_vrnn>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Brito_2020_CORL,
    author = "Brito, Bruno and Zhu, Hai and Pan, Wei and Alonso-Mora, Javier",
    title = "Social-VRNN: One-Shot Multi-modal Trajectory Prediction for Interacting Pedestrians",
    booktitle = "CoRL",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#virat/actev">VIRAT/ActEV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
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
<summary><em>Choi et al., "Looking To Relations For Future Trajectory Forecast", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Choi_Looking_to_Relations_for_Future_Trajectory_Forecast_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.08855.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
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
<details close>
<summary><em>Zhu et al., "Starnet: Pedestrian Trajectory Prediction Using Deep Neural Network In Star Topology", IROS, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8967811>paper</a> <a href=https://arxiv.org/pdf/1906.01797.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pets2009">PETS2009</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#chuk">CHUK</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#ande">ANDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ed">ED</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#ande">ANDE</a></li>
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
<summary><em>Wang et al., "Group Split and Merge Prediction With 3D Convolutional Networks", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/8972421>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
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
<a name=nuscenes></a>
<details close>
<summary><l style="font-size:20px"><strong>nuScenes</strong></l> <a href=https://www.nuscenes.org/>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Caesar_nuScenes_A_Multimodal_Dataset_for_Autonomous_Driving_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1903.11027.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset with 1K driving sequences and 1M+ 3D bounding boxes annotated at 2hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, LIDAR, 3D Bounding Box, Object Class, Attribute, Map, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Schmeckpeper et al., "Learning Predictive Models From Observation and Interaction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650698.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.12773.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#htud">HTUD</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#bdd100k">BDD100K</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<summary><em>Akan et al., "StretchBEV: Stretching Future Instance Prediction Spatially and Temporally", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136980436.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.13641.pdf>arxiv</a> <a href=https://kuis-ai.github.io/stretchbev/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#iou">IoU</a></li>
<li><a href="../metrics/trajectory_metrics.md#vpq">VPQ</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Akan_2022_ECCV,
    author = "Akan, Adil Kaan and Guney, Fatma",
    title = "StretchBEV: Stretching Future Instance Prediction Spatially and Temporally",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#orr">ORR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cao_2022_ECCV,
    author = "Cao, Yulong and Xiao, Chaowei and Anandkumar, Anima and Xu, Danfei and Pavone, Marco",
    title = "AdvDO: Realistic Adversarial Attacks for Trajectory Prediction",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#trajnet++">Trajnet++</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#dac">DAC</a></li>
<li><a href="../metrics/trajectory_metrics.md#orr">ORR</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#deltaesv">DeltaESV</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Tang et al., "Collaborative Uncertainty in Multi-Agent Trajectory Forecasting", NeurIPS, 2021.</em> <a href=https://papers.nips.cc/paper/2021/file/31ca0ca71184bbdb3de7b20a51e88e90-Paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2110.13947.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#euro-pvi">Euro-PVI</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cpi">CPI</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
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
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<summary><em>Deo et al., "Multimodal Trajectory Prediction Conditioned on Lane-Graph Traversals", CoRL, 2021.</em> <a href=https://openreview.net/pdf?id=hu7b7MPCqiC>paper</a> <a href=https://arxiv.org/pdf/2106.15004.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#offroad_rate">Offroad Rate</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#fit">FIT</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#mapillary_vistas">Mapillary Vistas</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#scr">SCR</a></li>
<li><a href="../metrics/trajectory_metrics.md#minsfde">minSFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minsade">minSADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#meansfde">meanSFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#meansade">meanSADE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#a2d2">A2D2</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
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
<summary><em>Khurana et al., "Differentiable Raycasting for Self-Supervised Occupancy Forecasting", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136980349.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.01917.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#once">ONCE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/other_metrics.md#f1">F1</a></li>
<li><a href="../metrics/other_metrics.md#precision">Precision</a></li>
<li><a href="../metrics/other_metrics.md#cross-entropy">Cross-entropy</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/other_metrics.md#cr">CR</a></li>
<li><a href="../metrics/other_metrics.md#emd">EMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Weng_2022_ECCV,
    author = "Weng, Xinshuo and Nan, Junyu and Lee, Kuan-Hui and McAllister, Rowan and Gaidon, Adrien and Rhinehart, Nicholas and Kitani, Kris M.",
    title = "S2Net: Stochastic Sequential Pointcloud Forecasting",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
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
<li><em><strong>Data type and annotations:</strong></em> RGB, LIDAR, 3D bounding box, Map, Trajectory</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zaech et al., "Action Sequence Predictions of Vehicles in Urban Environments using Map and Social Context", IROS, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9340643>paper</a> <a href=https://arxiv.org/pdf/2004.14251.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<summary><em>Choi et al., "Hierarchical Latent Structure for Multi-modal Vehicle Trajectory Forecasting", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820125.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.04624.pdf>arxiv</a> <a href=https://github.com/d1024choi/HLSTrajForecast>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<summary><em>Bhattacharyya et al., "SSL-Lanes: Self-Supervised Learning for Motion Forecasting in Autonomous Driving", CoRL, 2022.</em> <a href=https://openreview.net/pdf?id=fXMV2CEwNVo>paper</a> <a href=https://arxiv.org/pdf/2206.14116.pdf>arxiv</a> <a href=https://github.com/AutoVision-cloud/SSL-Lanes>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
@InProceedings{Bhattacharyya_2022_CoRL,
    author = "Bhattacharyya, Prarthana and Huang, Chengjie and Czarnecki, Krzysztof",
    title = "SSL}-Lanes: Self-Supervised Learning for Motion Forecasting in Autonomous Driving",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#trajnet++">Trajnet++</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#dac">DAC</a></li>
<li><a href="../metrics/trajectory_metrics.md#orr">ORR</a></li>
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
<summary><em>Ngiam et al., "Scene Transformer: A unified architecture for predicting future trajectories of multiple agents", ICLR, 2022.</em> <a href=https://openreview.net/pdf?id=Wm3EA5OlHsG>paper</a> <a href=https://arxiv.org/pdf/2106.08417.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#map">mAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ngiam_2022_ICLR,
    author = "Ngiam, Jiquan and Vasudevan, Vijay and Caine, Benjamin and Zhang, Zhengdong and Chiang, Hao-Tien Lewis and Ling, Jeffrey and Roelofs, Rebecca and Bewley, Alex and Liu, Chenxi and Venugopal, Ashish and Weiss, David J and Sapp, Ben and Chen, Zhifeng and Shlens, Jonathon",
    title = "Scene Transformer: A unified architecture for predicting future trajectories of multiple agents",
    booktitle = "ICLR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Da et al., "Path-Aware Graph Attention for HD Maps in Motion Prediction", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9812100>paper</a> <a href=https://arxiv.org/pdf/2202.13772.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
@InProceedings{Da_2022_ICRA,
    author = "Da, Fang and Zhang, Yu",
    booktitle = "ICRA",
    title = "Path-Aware Graph Attention for HD Maps in Motion Prediction",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Gilles et al., "GOHOME: Graph-Oriented Heatmap Output for future Motion Estimation", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9812253>paper</a> <a href=https://arxiv.org/pdf/2109.01827.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
@InProceedings{Gilles_2022_ICRA,
    author = "Gilles, Thomas and Sabatini, Stefano and Tsishkou, Dzmitry and Stanciulescu, Bogdan and Moutarde, Fabien",
    booktitle = "ICRA",
    title = "GOHOME: Graph-Oriented Heatmap Output for future Motion Estimation",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Huang et al., "Multi-modal Motion Prediction with Transformer-based Neural Network for Autonomous Driving", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9812060>paper</a> <a href=https://arxiv.org/pdf/2109.06446.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#bminfde">bminFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Huang_2022_ICRA,
    author = "Huang, Zhiyu and Mo, Xiaoyu and Lv, Chen",
    booktitle = "ICRA",
    title = "Multi-modal Motion Prediction with Transformer-based Neural Network for Autonomous Driving",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Kim et al., "StopNet: Scalable Trajectory and Occupancy Prediction for Urban Autonomous Driving", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9811830>paper</a> <a href=https://arxiv.org/pdf/2206.00991.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
<li>Custom</li>

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
@InProceedings{Kim_2022_ICRA,
    author = "Kim, Jinkyu and Mahjourian, Reza and Ettinger, Scott and Bansal, Mayank and White, Brandyn and Sapp, Ben and Anguelov, Dragomir",
    booktitle = "ICRA",
    title = "StopNet: Scalable Trajectory and Occupancy Prediction for Urban Autonomous Driving",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Kuo et al., "Trajectory Prediction with Linguistic Representations", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9811928>paper</a> <a href=https://arxiv.org/pdf/2110.09741.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#entropy">Entropy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kuo_2022_ICRA,
    author = "Kuo, Yen-Ling and Huang, Xin and Barbu, Andrei and McGill, Stephen G. and Katz, Boris and Leonard, John J. and Rosman, Guy",
    booktitle = "ICRA",
    title = "Trajectory Prediction with Linguistic Representations",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Schmidt et al., "CRAT-Pred: Vehicle Trajectory Prediction with Crystal Graph Convolutional Neural Networks and Multi-Head Self-Attention", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9811637>paper</a> <a href=https://arxiv.org/pdf/2202.04488.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
@InProceedings{Schmidt_2022_ICRA,
    author = "Schmidt, Julian and Jordan, Julian and Gritschneder, Franz and Dietmayer, Klaus",
    booktitle = "ICRA",
    title = "CRAT-Pred: Vehicle Trajectory Prediction with Crystal Graph Convolutional Neural Networks and Multi-Head Self-Attention",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Su et al., "Narrowing the coordinate-frame gap in behavior prediction models: Distillation for efficient and accurate scene-centric motion forecasting", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9812368>paper</a> <a href=https://arxiv.org/pdf/2206.03970.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#wade">wADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Su_2022_ICRA,
    author = "Su, DiJia Andy and Douillard, Bertrand and Al-Rfou, Rami and Park, Cheol and Sapp, Benjamin",
    booktitle = "ICRA",
    title = "Narrowing the coordinate-frame gap in behavior prediction models: Distillation for efficient and accurate scene-centric motion forecasting",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#trajnet++">Trajnet++</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#waymo">Waymo</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<summary><em>Song et al., "Learning to Predict Vehicle Trajectories with Model-based Planning", CoRL, 2021.</em> <a href=https://openreview.net/pdf?id=GhMZNcr54zt>paper</a> <a href=https://arxiv.org/pdf/2103.04027.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
@InProceedings{Song_2021_CoRL,
    author = "Song, Haoran and Luan, Di and Ding, Wenchao and Wang, Michael Y and Chen, Qifeng",
    title = "Learning to Predict Vehicle Trajectories with Model-based Planning",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
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
<summary><em>Fang et al., "TPNet: Trajectory Proposal Network for Motion Prediction", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Fang_TPNet_Trajectory_Proposal_Network_for_Motion_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.12255.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#virat/actev">VIRAT/ActEV</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
<li>Custom</li>

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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
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
<summary><em>Bae et al., "Non-Probability Sampling Network for Stochastic Human Trajectory Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Bae_Non-Probability_Sampling_Network_for_Stochastic_Human_Trajectory_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.13471.pdf>arxiv</a> <a href=https://github.com/inhwanbae/NPSN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#tcc">TCC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bae_2022_CVPR,
    author = "Bae, Inhwan and Park, Jin-Hwi and Jeon, Hae-Gon",
    title = "Non-Probability Sampling Network for Stochastic Human Trajectory Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Gu et al., "Stochastic Trajectory Prediction via Motion Indeterminacy Diffusion", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Gu_Stochastic_Trajectory_Prediction_via_Motion_Indeterminacy_Diffusion_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.13777.pdf>arxiv</a> <a href=https://github.com/gutianpei/MID>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Gu_2022_CVPR,
    author = "Gu, Tianpei and Chen, Guangyi and Li, Junlong and Lin, Chunze and Rao, Yongming and Zhou, Jie and Lu, Jiwen",
    title = "Stochastic Trajectory Prediction via Motion Indeterminacy Diffusion",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Guo et al., "End-to-End Trajectory Distribution Prediction Based on Occupancy Grid Maps", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_End-to-End_Trajectory_Distribution_Prediction_Based_on_Occupancy_Grid_Maps_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.16910.pdf>arxiv</a> <a href=https://github.com/Kguo-cs/TDOR>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#ind">inD</a></li>
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
<details close>
<summary><em>Lee et al., "MUSE-VAE: Multi-Scale VAE for Environment-Aware Long Term Trajectory Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Lee_MUSE-VAE_Multi-Scale_VAE_for_Environment-Aware_Long_Term_Trajectory_Prediction_CVPR_2022_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
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
<summary><em>Monti et al., "How Many Observations Are Enough? Knowledge Distillation for Trajectory Forecasting", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Monti_How_Many_Observations_Are_Enough_Knowledge_Distillation_for_Trajectory_Forecasting_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.04781.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
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
<summary><em>Xu et al., "Remember Intentions: Retrospective-Memory-Based Trajectory Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_Remember_Intentions_Retrospective-Memory-Based_Trajectory_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.11474.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/MemoNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2022_CVPR,
    author = "Xu, Chenxin and Mao, Weibo and Zhang, Wenjun and Chen, Siheng",
    title = "Remember Intentions: Retrospective-Memory-Based Trajectory Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sun et al., "Human Trajectory Prediction With Momentary Observation", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Sun_Human_Trajectory_Prediction_With_Momentary_Observation_CVPR_2022_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Sun_2022_CVPR_2,
    author = "Sun, Jianhua and Li, Yuxuan and Chai, Liang and Fang, Hao-Shu and Li, Yong-Lu and Lu, Cewu",
    title = "Human Trajectory Prediction With Momentary Observation",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Bae et al., "Learning Pedestrian Group Representations for Multi-modal Trajectory Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820263.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.09953.pdf>arxiv</a> <a href=https://github.com/inhwanbae/GPGraph>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#tcr">TCR</a></li>
<li><a href="../metrics/trajectory_metrics.md#tcc">TCC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Bae_2022_ECCV,
    author = "Bae, Inhwan and Park, Jin-Hwi and Jeon, Hae-Gon",
    title = "Learning Pedestrian Group Representations for Multi-modal Trajectory Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Tsao et al., "Social-SSL: Self-Supervised Cross-Sequence Representation Learning Based on Transformers for Multi-agent Trajectory Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820227.pdf>paper</a> <a href=https://github.com/Sigta678/Social-SSL>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tsao_2022_ECCV,
    author = "Tsao, Li-Wu and Wang, Yan-Kai and Lin, Hao-Siang and Shuai, Hong-Han and Wong, Lai-Kuan and Cheng, Wen-Huang",
    title = "Social-SSL: Self-Supervised Cross-Sequence Representation Learning Based on Transformers for Multi-agent Trajectory Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Wong et al., "View Vertically: A Hierarchical Network for Trajectory Prediction via Fourier Spectrums", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820661.pdf>paper</a> <a href=https://arxiv.org/pdf/2110.07288.pdf>arxiv</a> <a href=https://github.com/cocoon2wong/Vertical>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wong_2022_ECCV,
    author = "Wong, Conghao and Xia, Beihao and Hong, Ziming and Peng, Qinmu and Yuan, Wei and Cao, Qiong and Yang, Yibo and You, Xinge",
    title = "View Vertically: A Hierarchical Network for Trajectory Prediction via Fourier Spectrums",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "SocialVAE: Human Trajectory Prediction Using Timewise Latents", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136640504.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.08207.pdf>arxiv</a> <a href=https://motion-lab.github.io/SocialVAE/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
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
@InProceedings{Xu_2022_ECCV,
    author = "Xu, Pei and Hayet, Jean-Bernard and Karamouzas, Ioannis",
    title = "SocialVAE: Human Trajectory Prediction Using Timewise Latents",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Yue et al., "Human Trajectory Prediction via Neural Social Physics", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940368.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.10435.pdf>arxiv</a> <a href=https://github.com/realcrane/Human-Trajectory-Prediction-via-Neural-Social-Physics>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yue_2022_ECCV,
    author = "Yue, Jiangbei and Manocha, Dinesh and Wang, He",
    title = "Human Trajectory Prediction via Neural Social Physics",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhang et al., "D2-TPred: Discontinuous Dependency for Trajectory Prediction under Traffic Lights", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136680512.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.10398.pdf>arxiv</a> <a href=https://github.com/VTP-TL/D2-TPred>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#vtp-tl">VTP-TL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2022_ECCV,
    author = "Zhang, Yuzhen and Wang, Wentong and Guo, Weizhi and Lv, Pei and Xu, Mingliang and Chen, Wei and Manocha, Dinesh",
    title = "D2-TPred: Discontinuous Dependency for Trajectory Prediction under Traffic Lights",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Kothari et al., "Motion Style Transfer: Modular Low-Rank Adaptation for Deep Motion Forecasting", CoRL, 2022.</em> <a href=https://openreview.net/pdf?id=tVgD4METs6o>paper</a> <a href=https://arxiv.org/pdf/2211.03165.pdf>arxiv</a> <a href=https://github.com/vita-epfl/motion-style-transfer>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#ind">inD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kothari_2022_CoRL,
    author = "Kothari, Parth and Li, Danya and Liu, Yuejiang and Alahi, Alexandre",
    title = "Motion Style Transfer: Modular Low-Rank Adaptation for Deep Motion Forecasting",
    booktitle = "CoRL",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Meng et al., "Forecasting Human Trajectory from Scene History", NeurIPS, 2022.</em> <a href=https://openreview.net/pdf?id=RW-OOBU11xl>paper</a> <a href=https://arxiv.org/pdf/2210.08732.pdf>arxiv</a> <a href=https://github.com/MaKaRuiNah/SHENet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#mot">MOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Meng_2022_NeurIPS,
    author = "Meng, Mancheng and Wu, Ziyan and Chen, Terrence and Cai, Xiran and Zhou, Xiang Sean and Yang, Fan and Shen, Dinggang",
    title = "Forecasting Human Trajectory from Scene History",
    booktitle = "NeurIPS",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xie et al., "Synchronous Bi-Directional Pedestrian Trajectory Prediction with Error Compensation", ACCV, 2022.</em> <a href=https://openaccess.thecvf.com/content/ACCV2022/papers/Xie_Synchronous_Bi-Directional_Pedestrian_Trajectory_Prediction_with_Error_Compensation_ACCV_2022_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xie_2022_ACCV,
    author = "Xie, Ce and Li, Yuanman and Liang, Rongqin and Dong, Li and Li, Xia",
    title = "Synchronous Bi-Directional Pedestrian Trajectory Prediction with Error Compensation",
    booktitle = "ACCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhao et al., "Where Are You Heading? Dynamic Trajectory Prediction With Expert Goal Examples", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Zhao_Where_Are_You_Heading_Dynamic_Trajectory_Prediction_With_Expert_Goal_ICCV_2021_paper.pdf>paper</a> <a href=https://github.com/JoeHEZHAO/expert_traj>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhao_2021_ICCV,
    author = "Zhao, He and Wildes, Richard P.",
    title = "Where Are You Heading? Dynamic Trajectory Prediction With Expert Goal Examples",
    booktitle = "ICCV",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
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
<summary><em>Yu et al., "Towards Robust Human Trajectory Prediction in Raw Videos", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636831>paper</a> <a href=https://arxiv.org/pdf/2108.08259.pdf>arxiv</a> <a href=https://github.com/rui-yu-public/Retracking-by-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mota">MOTA</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yu_2021_IROS_2,
    author = "Yu, Rui and Zhou, Zihan",
    booktitle = "IROS",
    title = "Towards Robust Human Trajectory Prediction in Raw Videos",
    year = "2021"
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#virat/actev">VIRAT/ActEV</a></li>
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
<summary><em>Mangalam et al., "It Is Not the Journey but the Destination: Endpoint Conditioned Trajectory Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470749.pdf>paper</a> <a href=https://arxiv.org/pdf/2004.02025.pdf>arxiv</a> <a href=https://github.com/HarshayuGirase/PECNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Tao et al., "Dynamic and Static Context-aware LSTM for Multi-agent Motion Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660545.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.00777.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#tcc">TCC</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Tao_2020_ECCV,
    author = "Tao, Chaofan and Jiang, Qinhong and Duan, Lixin and Luo, Ping",
    title = "Dynamic and Static Context-aware LSTM for Multi-agent Motion Prediction",
    booktitle = "ECCV",
    year = "2020"
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#h3d">H3D</a></li>
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
<details close>
<summary><em>Dendorfer et al., "Goal-GAN: Multimodal Trajectory Prediction Based on Goal Position Estimation", ACCV, 2020.</em> <a href=https://openaccess.thecvf.com/content/ACCV2020/papers/Dendorfer_Goal-GAN_Multimodal_Trajectory_Prediction_Based_on_Goal_Position_Estimation_ACCV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2010.01114.pdf>arxiv</a> <a href=https://github.com/dendorferpatrick/GoalGAN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#mc">MC</a></li>
<li><a href="../metrics/trajectory_metrics.md#f">F</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Dendorfer_2020_ACCV,
    author = "Dendorfer, Patrick and Osep, Aljosa and Leal-Taixe, Laura",
    title = "Goal-GAN: Multimodal Trajectory Prediction Based on Goal Position Estimation",
    booktitle = "ACCV",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Dwivedi et al., "SSP: Single Shot Future Trajectory Prediction", IROS, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9340754>paper</a> <a href=https://arxiv.org/pdf/2004.05846.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Dwivedi_2020_IROS,
    author = "Dwivedi, I. and Malla, S. and Dariush, B. and Choi, C.",
    booktitle = "IROS",
    title = "SSP: Single Shot Future Trajectory Prediction",
    year = "2020"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Berlati et al., "Ambiguity in Sequential Data: Predicting Uncertain Futures With Recurrent Models", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9001185>paper</a> <a href=https://arxiv.org/pdf/2003.10381.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
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
<summary><em>Ridel et al., "Scene Compliant Trajectory Forecast With Agent-Centric Spatio-Temporal Grids", RAL, 2020.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9000540>paper</a> <a href=https://arxiv.org/pdf/1909.03895.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@Article{Ridel_2020_RAL,
    author = "Ridel, D. and Deo, N. and Wolf, D. and Trivedi, M.",
    journal = "RAL",
    title = "Scene Compliant Trajectory Forecast With Agent-Centric Spatio-Temporal Grids",
    year = "2020",
    volume = "5",
    number = "2",
    pages = "2816-2823"
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
<li>Custom</li>

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
<summary><em>Li, "Which Way Are You Going? Imitative Decision Learning For Path Forecasting In Dynamic Scenes", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Which_Way_Are_You_Going_Imitative_Decision_Learning_for_Path_CVPR_2019_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
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
<summary><em>Makansi et al., "Overcoming Limitations of Mixture Density Networks: A Sampling and Fitting Framework for Multimodal Future Prediction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Makansi_Overcoming_Limitations_of_Mixture_Density_Networks_A_Sampling_and_Fitting_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.03631.pdf>arxiv</a> <a href=https://github.com/lmb-freiburg/Multimodal-Future-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cpi">CPI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#emd">EMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Makansi_2019_CVPR,
    author = "Makansi, Osama and Ilg, Eddy and Cicek, Ozgun and Brox, Thomas",
    title = "Overcoming Limitations of Mixture Density Networks: A Sampling and Fitting Framework for Multimodal Future Prediction",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
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
<summary><em>Choi et al., "Looking To Relations For Future Trajectory Forecast", ICCV, 2019.</em> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Choi_Looking_to_Relations_for_Future_Trajectory_Forecast_ICCV_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1905.08855.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
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
<details close>
<summary><em>Xue et al., "Location-Velocity Attention For Pedestrian Trajectory Prediction", WACV, 2019.</em> <a href=https://ieeexplore.ieee.org/document/8659060>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pets2009">PETS2009</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#ed">ED</a></li>
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
<summary><em>Ballan et al., "Knowledge Transfer For Scene-Specific Motion Prediction", ECCV, 2016.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46448-0_42>paper</a> <a href=https://arxiv.org/pdf/1603.06987.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#town_center">Town Center</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#smtsmt">SmtSmt</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#dancing">Dancing</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
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
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#robonet">RoboNet</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#bair">BAIR</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#chuk_avenue">CHUK Avenue</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#shanghaitech_campus">ShanghaiTech Campus</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#yuv">YUV</a></li>
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
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
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
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kth">KTH</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#thumos">THUMOS</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sports-1m">Sports-1M</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#carla">CARLA</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#h3d">H3D</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#orc">ORC</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#oxford">Oxford</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#ed">ED</a></li>
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
<summary><em>Weng et al., "S2Net: Stochastic Sequential Pointcloud Forecasting", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136870541.pdf>paper</a> <a href=https://www.xinshuoweng.com/projects/S2Net>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/other_metrics.md#cr">CR</a></li>
<li><a href="../metrics/other_metrics.md#emd">EMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Weng_2022_ECCV,
    author = "Weng, Xinshuo and Nan, Junyu and Lee, Kuan-Hui and McAllister, Rowan and Gaidon, Adrien and Rhinehart, Nicholas and Kitani, Kris M.",
    title = "S2Net: Stochastic Sequential Pointcloud Forecasting",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/other_metrics.md#cr">CR</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Mersch_2021_CoRL,
    author = "Mersch, Benedikt and Chen, Xieyuanli and Behley, Jens and Stachniss, Cyrill",
    title = "Self-supervised Point Cloud Prediction Using 3D Spatio-temporal Convolutional Networks",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#charges">Charges</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#traf">TRAF</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
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
<summary><em>Guo et al., "Pedestrian Stop and Go Forecasting with Hybrid Feature Fusion", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9811664>paper</a> <a href=https://arxiv.org/pdf/2203.02489.pdf>arxiv</a> <a href=https://github.com/vita-epfl/hybrid-feature-fusion>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#titan">TITAN</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#ap">AP</a></li>
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
<details close>
<summary><em>Zhai et al., "Social Aware Multi-Modal Pedestrian Crossing Behavior Prediction", ACCV, 2022.</em> <a href=https://openaccess.thecvf.com/content/ACCV2022/papers/Zhai_Social_Aware_Multi-Modal_Pedestrian_Crossing_Behavior_Prediction_ACCV_2022_paper.pdf>paper</a> <a href=https://github.com/zxll0106/Pedestrian_Crossing_Behavior_Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics/action_metrics.md#precision">Precision</a></li>
<li><a href="../metrics/action_metrics.md#f1">F1</a></li>
<li><a href="../metrics/action_metrics.md#map">mAP</a></li>
<li><a href="../metrics/action_metrics.md#auc">AUC</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#stip">STIP</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#viena">VIENA</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
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
<summary><em>Halawa et al., "Action-Based Contrastive Learning for Trajectory Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136990140.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.08664.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#titan">TITAN</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#fpl">FPL</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#citywalks">CityWalks</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pedx">PedX</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#dancing">Dancing</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#bair_push">BAIR Push</a></li>
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
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#human3.6m">Human3.6M</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#orc">ORC</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#oxford">Oxford</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscape">Cityscape</a></li>

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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
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
<a name=waymo></a>
<details close>
<summary><l style="font-size:20px"><strong>Waymo Open Dataset (WOD)</strong></l> <a href=https://waymo.com/open/>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Sun_Scalability_in_Perception_for_Autonomous_Driving_Waymo_Open_Dataset_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.04838.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset with approx. 2K driving segments and 20M+ 2D/3D bounding boxes annotated at 10hz
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, LIDAR, Bounding Box, 3D Bounding Box, Object Class, Tracking ID, Trajectory</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Sun et al., "M2I: From Factored Marginal Trajectory Prediction to Interactive Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Sun_M2I_From_Factored_Marginal_Trajectory_Prediction_to_Interactive_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2202.11884.pdf>arxiv</a> <a href=https://github.com/Tsinghua-MARS-Lab/M2I>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#waymo">Waymo</a></li>
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
<summary><em>Najibi et al., "Motion Inspired Unsupervised Perception and Prediction in Autonomous Driving", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136980416.pdf>paper</a> <a href=https://arxiv.org/pdf/2210.08061.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#epe3d">EPE3D</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Najibi_2022_ECCV,
    author = "Najibi, Mahyar and Ji, Jingwei and Zhou, Yin and Qi, Charles R. and Yan, Xinchen and Ettinger, Scott and Anguelov, Dragomir",
    title = "Motion Inspired Unsupervised Perception and Prediction in Autonomous Driving",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhang et al., "D2-TPred: Discontinuous Dependency for Trajectory Prediction under Traffic Lights", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136680512.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.10398.pdf>arxiv</a> <a href=https://github.com/VTP-TL/D2-TPred>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#vtp-tl">VTP-TL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2022_ECCV,
    author = "Zhang, Yuzhen and Wang, Wentong and Guo, Weizhi and Lv, Pei and Xu, Mingliang and Chen, Wei and Manocha, Dinesh",
    title = "D2-TPred: Discontinuous Dependency for Trajectory Prediction under Traffic Lights",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Jia et al., "Towards Capturing the Temporal Dynamics for Trajectory Prediction: a Coarse-to-Fine Approach", CoRL, 2022.</em> <a href=https://openreview.net/pdf?id=PZiKO7mjC43>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#ur">UR</a></li>
<li><a href="../metrics/trajectory_metrics.md#tri">TRI</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jia_2022_CoRL,
    author = "Jia, Xiaosong and Chen, Li and Wu, Penghao and Zeng, Jia and Yan, Junchi and Li, Hongyang and Qiao, Yu",
    title = "Towards Capturing the Temporal Dynamics for Trajectory Prediction: a Coarse-to-Fine Approach",
    booktitle = "CoRL",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Luo et al., "JFP: Joint Future Prediction with Interactive Multi-Agent Modeling for Autonomous Driving", CoRL, 2022.</em> <a href=https://openreview.net/pdf?id=Y42uoIekm5b>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#map">mAP</a></li>
<li><a href="../metrics/trajectory_metrics.md#minsfde">minSFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minsade">minSADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Luo_2022_CoRL,
    author = "Luo, Wenjie and Park, Cheol and Cornman, Andre and Sapp, Benjamin and Anguelov, Dragomir",
    title = "JFP}: Joint Future Prediction with Interactive Multi-Agent Modeling for Autonomous Driving",
    booktitle = "CoRL",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Nishimura et al., "RAP: Risk-Aware Prediction for Robust Planning", CoRL, 2022.</em> <a href=https://openreview.net/pdf?id=z_hPo2Fu9A3>paper</a> <a href=https://arxiv.org/pdf/2210.01368.pdf>arxiv</a> <a href=https://github.com/TRI-ML/RAP>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#risk">Risk</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Nishimura_2022_CoRL,
    author = "Nishimura, Haruki and Mercat, Jean and Wulfe, Blake and McAllister, Rowan Thomas and Gaidon, Adrien",
    title = "RAP}: Risk-Aware Prediction for Robust Planning",
    booktitle = "CoRL",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Ngiam et al., "Scene Transformer: A unified architecture for predicting future trajectories of multiple agents", ICLR, 2022.</em> <a href=https://openreview.net/pdf?id=Wm3EA5OlHsG>paper</a> <a href=https://arxiv.org/pdf/2106.08417.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#map">mAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ngiam_2022_ICLR,
    author = "Ngiam, Jiquan and Vasudevan, Vijay and Caine, Benjamin and Zhang, Zhengdong and Chiang, Hao-Tien Lewis and Ling, Jeffrey and Roelofs, Rebecca and Bewley, Alex and Liu, Chenxi and Venugopal, Ashish and Weiss, David J and Sapp, Ben and Chen, Zhifeng and Shlens, Jonathon",
    title = "Scene Transformer: A unified architecture for predicting future trajectories of multiple agents",
    booktitle = "ICLR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Lu et al., "KEMP: Keyframe-Based Hierarchical End-to-End Deep Model for Long- Term Trajectory Prediction", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9812337>paper</a> <a href=https://arxiv.org/pdf/2205.04624.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#map">mAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Lu_2022_ICRA,
    author = "Lu, Qiujing and Han, Weiqiao and Ling, Jeffrey and Wang, Minfa and Chen, Haoyu and Varadarajan, Balakrishnan and Covington, Paul",
    booktitle = "ICRA",
    title = "KEMP: Keyframe-Based Hierarchical End-to-End Deep Model for Long- Term Trajectory Prediction",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Su et al., "Narrowing the coordinate-frame gap in behavior prediction models: Distillation for efficient and accurate scene-centric motion forecasting", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9812368>paper</a> <a href=https://arxiv.org/pdf/2206.03970.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#wade">wADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Su_2022_ICRA,
    author = "Su, DiJia Andy and Douillard, Bertrand and Al-Rfou, Rami and Park, Cheol and Sapp, Benjamin",
    booktitle = "ICRA",
    title = "Narrowing the coordinate-frame gap in behavior prediction models: Distillation for efficient and accurate scene-centric motion forecasting",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Varadarajan et al., "MultiPath++: Efficient Information Fusion and Trajectory Aggregation for Behavior Prediction", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9812107>paper</a> <a href=https://arxiv.org/pdf/2111.14973.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#map">mAP</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Varadarajan_2022_ICRA,
    author = "Varadarajan, Balakrishnan and Hefny, Ahmed and Srivastava, Avikalp and Refaat, Khaled S. and Nayakanti, Nigamaa and Cornman, Andre and Chen, Kan and Douillard, Bertrand and Lam, Chi Pang and Anguelov, Dragomir and Sapp, Benjamin",
    booktitle = "ICRA",
    title = "MultiPath++: Efficient Information Fusion and Trajectory Aggregation for Behavior Prediction",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#waymo">Waymo</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#waymo">Waymo</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#fit">FIT</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#mapillary_vistas">Mapillary Vistas</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#way">Way</a></li>
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
<summary><em>Guo et al., "Pedestrian Stop and Go Forecasting with Hybrid Feature Fusion", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9811664>paper</a> <a href=https://arxiv.org/pdf/2203.02489.pdf>arxiv</a> <a href=https://github.com/vita-epfl/hybrid-feature-fusion>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#titan">TITAN</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#ap">AP</a></li>
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
<details close>
<summary><em>Zhai et al., "Social Aware Multi-Modal Pedestrian Crossing Behavior Prediction", ACCV, 2022.</em> <a href=https://openaccess.thecvf.com/content/ACCV2022/papers/Zhai_Social_Aware_Multi-Modal_Pedestrian_Crossing_Behavior_Prediction_ACCV_2022_paper.pdf>paper</a> <a href=https://github.com/zxll0106/Pedestrian_Crossing_Behavior_Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics/action_metrics.md#precision">Precision</a></li>
<li><a href="../metrics/action_metrics.md#f1">F1</a></li>
<li><a href="../metrics/action_metrics.md#map">mAP</a></li>
<li><a href="../metrics/action_metrics.md#auc">AUC</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
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
<summary><em>Halawa et al., "Action-Based Contrastive Learning for Trajectory Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136990140.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.08664.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#titan">TITAN</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
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
<a name=nba></a>
<details close>
<summary><l style="font-size:20px"><strong>NBA</strong></l> <a href=https://github.com/linouk23/NBA-Player-Movements>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 

</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Trajectory</li>
<li><em><strong>Task:</strong></em> Sport</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Xu et al., "Remember Intentions: Retrospective-Memory-Based Trajectory Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_Remember_Intentions_Retrospective-Memory-Based_Trajectory_Prediction_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.11474.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/MemoNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2022_CVPR,
    author = "Xu, Chenxin and Mao, Weibo and Zhang, Wenjun and Chen, Siheng",
    title = "Remember Intentions: Retrospective-Memory-Based Trajectory Prediction",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Xu et al., "GroupNet: Multiscale Hypergraph Neural Networks for Trajectory Prediction With Relational Reasoning", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_GroupNet_Multiscale_Hypergraph_Neural_Networks_for_Trajectory_Prediction_With_Relational_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2204.08770.pdf>arxiv</a> <a href=https://github.com/MediaBrain-SJTU/GroupNet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Xu_2022_CVPR_2,
    author = "Xu, Chenxin and Li, Maosen and Ni, Zhenyang and Zhang, Ya and Chen, Siheng",
    title = "GroupNet: Multiscale Hypergraph Neural Networks for Trajectory Prediction With Relational Reasoning",
    booktitle = "CVPR",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Hu et al., "Entry-Flipped Transformer for Inference and Prediction of Participant Behavior", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136640433.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.06235.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#ceilidh_dance">Ceilidh Dance</a></li>
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
<details close>
<summary><em>Xu et al., "SocialVAE: Human Trajectory Prediction Using Timewise Latents", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136640504.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.08207.pdf>arxiv</a> <a href=https://motion-lab.github.io/SocialVAE/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
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
@InProceedings{Xu_2022_ECCV,
    author = "Xu, Pei and Hayet, Jean-Bernard and Karamouzas, Ioannis",
    title = "SocialVAE: Human Trajectory Prediction Using Timewise Latents",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Fassmeyer et al., "Semi-Supervised Generative Models for Multiagent Trajectories", NeurIPS, 2022.</em> <a href=https://openreview.net/pdf?id=KpuObEWvvOX>paper</a> <a href=https://github.com/fassmeyer/MAT_NeurIPS22>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
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
@InProceedings{Fassmeyer_2022_NeurIPS,
    author = "Fassmeyer, Dennis and Fassmeyer, Pascal and Brefeld, Ulf",
    title = "Semi-Supervised Generative Models for Multiagent Trajectories",
    booktitle = "NeurIPS",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
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
<summary><em>Li et al., "GRIN: Generative Relation and Intention Network for Multi-agent Trajectory Prediction", NeurIPS, 2021.</em> <a href=https://papers.nips.cc/paper/2021/file/e3670ce0c315396e4836d7024abcf3dd-Paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#charges">Charges</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#mmd">MMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2021_NeurIPS,
    author = "Li, Longyuan and Yao, Jian and Wenliang, Li and He, Tong and Xiao, Tianjun and Yan, Junchi and Wipf, David and Zhang, Zheng",
    booktitle = "NeurIPS",
    title = "GRIN: Generative Relation and Intention Network for Multi-agent Trajectory Prediction",
    year = "2021"
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#charges">Charges</a></li>
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
<summary><em>Li et al., "EvolveGraph: Multi-Agent Trajectory Prediction with Dynamic Relational Reasoning", NeurIPS, 2020.</em> <a href=https://papers.nips.cc/paper/2020/file/e4d8163c7a068b65a64c89bd745ec360-Paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.13924.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#h3d">H3D</a></li>
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
<details close>
<summary><em>Ivanovic et al., "Generative modeling of multimodal multi-human behavior", IROS, 2018.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8594393>paper</a> <a href=https://arxiv.org/pdf/1803.02015.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Ivanovic_2018_IROS,
    author = "Ivanovic, Boris and Schmerling, Edward and Leung, Karen and Pavone, Marco",
    title = "Generative modeling of multimodal multi-human behavior",
    booktitle = "IROS",
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
@Misc{Linou_2016,
    author = "Luo, K",
    Title = "NBA-Player-Movements",
    HowPublished = "Online",
    year = "2016",
    url = "https://github.com/linouk23/NBA-Player-Movements"
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
<summary><em>Hu et al., "Causal-based Time Series Domain Generalization for Vehicle Intention Prediction", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9812188>paper</a> <a href=https://arxiv.org/pdf/2112.02093.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hu_2022_ICRA,
    author = "Hu, Yeping and Jia, Xiaogang and Tomizuka, Masayoshi and Zhan, Wei",
    booktitle = "ICRA",
    title = "Causal-based Time Series Domain Generalization for Vehicle Intention Prediction",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Zhang et al., "D2-TPred: Discontinuous Dependency for Trajectory Prediction under Traffic Lights", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136680512.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.10398.pdf>arxiv</a> <a href=https://github.com/VTP-TL/D2-TPred>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#vtp-tl">VTP-TL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2022_ECCV,
    author = "Zhang, Yuzhen and Wang, Wentong and Guo, Weizhi and Lv, Pei and Xu, Mingliang and Chen, Wei and Manocha, Dinesh",
    title = "D2-TPred: Discontinuous Dependency for Trajectory Prediction under Traffic Lights",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Cao et al., "Leveraging Smooth Attention Prior for Multi-Agent Trajectory Prediction", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9811718>paper</a> <a href=https://arxiv.org/pdf/2203.04421.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cao_2022_ICRA,
    author = "Cao, Zhangjie and Biyik, Erdem and Rosman, Guy and Sadigh, Dorsa",
    booktitle = "ICRA",
    title = "Leveraging Smooth Attention Prior for Multi-Agent Trajectory Prediction",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Kamenev et al., "PredictionNet: Real-Time Joint Probabilistic Traffic Prediction for Planning, Control, and Simulation", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9812223>paper</a> <a href=https://arxiv.org/pdf/2109.11094.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
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
@InProceedings{Kamenev_2022_ICRA,
    author = "Kamenev, Alexey and Wang, Lirui and Bohan, Ollin Boer and Kulkarni, Ishwar and Kartal, Bilal and Molchanov, Artem and Birchfield, Stan and Nistér, David and Smolyanskiy, Nikolai",
    booktitle = "ICRA",
    title = "PredictionNet: Real-Time Joint Probabilistic Traffic Prediction for Planning, Control, and Simulation",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Kim et al., "StopNet: Scalable Trajectory and Occupancy Prediction for Urban Autonomous Driving", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9811830>paper</a> <a href=https://arxiv.org/pdf/2206.00991.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
<li>Custom</li>

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
@InProceedings{Kim_2022_ICRA,
    author = "Kim, Jinkyu and Mahjourian, Reza and Ettinger, Scott and Bansal, Mayank and White, Brandyn and Sapp, Ben and Anguelov, Dragomir",
    booktitle = "ICRA",
    title = "StopNet: Scalable Trajectory and Occupancy Prediction for Urban Autonomous Driving",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Jia et al., "Multi-Agent Trajectory Prediction by Combining Egocentric and Allocentric Views", CoRL, 2021.</em> <a href=https://openreview.net/pdf?id=lAtePxetBNb>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#trajnet++">Trajnet++</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jia_2021_CoRL,
    author = "Jia, Xiaosong and Sun, Liting and Zhao, Hang and Tomizuka, Masayoshi and Zhan, Wei",
    title = "Multi-Agent Trajectory Prediction by Combining Egocentric and Allocentric Views",
    booktitle = "CoRL",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sun et al., "On complementing end-to-end human behavior predictors with planning", RSS, 2021.</em> <a href=http://www.roboticsproceedings.org/rss17/p037.pdf>paper</a> <a href=https://arxiv.org/pdf/2103.05661.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{SunL_2021_RSS,
    AUTHOR = "Sun, Liting and Jia, Xiaogang and Dragan, Anca",
    TITLE = "On complementing end-to-end human behavior predictors with planning}",
    BOOKTITLE = "RSS",
    YEAR = "2021"
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
<li>Custom</li>

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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
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
<summary><em>Zhang et al., "D2-TPred: Discontinuous Dependency for Trajectory Prediction under Traffic Lights", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136680512.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.10398.pdf>arxiv</a> <a href=https://github.com/VTP-TL/D2-TPred>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#vtp-tl">VTP-TL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2022_ECCV,
    author = "Zhang, Yuzhen and Wang, Wentong and Guo, Weizhi and Lv, Pei and Xu, Mingliang and Chen, Wei and Manocha, Dinesh",
    title = "D2-TPred: Discontinuous Dependency for Trajectory Prediction under Traffic Lights",
    booktitle = "ECCV",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
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
<a name=highd></a>
<details close>
<summary><l style="font-size:20px"><strong>highD</strong></l> <a href=https://www.highd-dataset.com/>link</a> <a href=https://arxiv.org/pdf/1810.05642.pdf>arxiv</a></summary> 
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
<summary><em>Wen et al., "Social ODE: Multi-agent Trajectory Forecasting with Neural Ordinary Differential Equations", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820211.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#ind">inD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#round">rounD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wen_2022_ECCV,
    author = "Wen, Song and Wang, Hao and Metaxas, Dimitris N.",
    title = "Social ODE: Multi-agent Trajectory Forecasting with Neural Ordinary Differential Equations",
    booktitle = "ECCV",
    year = "2022"
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
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
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#chuk">CHUK</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#ande">ANDE</a></li>
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
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#qmul">QMUL</a></li>
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
<details close>
<summary><em>Yi et al., "Pedestrian Behavior Understanding And Prediction With Deep Neural Networks", ECCV, 2016.</em> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46448-0_16>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#mitt">MITT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ed">ED</a></li>
<li><a href="../metrics/trajectory_metrics.md#run_time">Run Time</a></li>
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
<summary><em>Sohn et al., "Laying the Foundations of Deep Long-Term Crowd Flow Prediction", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123740698.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ltcf">LTCF</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/other_metrics.md#mae">MAE</a></li>
<li><a href="../metrics/other_metrics.md#mse">MSE</a></li>
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
@InProceedings{Zhou_2012_CVPR,
    author = "Zhou, Bolei and Wang, Xiaogang and Tang, Xiaoou",
    title = "Understanding Collective Crowd Behaviors: Learning A Mixture Model Of Dynamic Pedestrian-Agents",
    booktitle = "CVPR",
    year = "2012"
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
<li><em><strong>Data type and annotations:</strong></em> RGB, LIDAR, 3D Bounding Box, Object Class, Attribute, Map, Tracking ID, Trajectory</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Monti et al., "How Many Observations Are Enough? Knowledge Distillation for Trajectory Forecasting", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Monti_How_Many_Observations_Are_Enough_Knowledge_Distillation_for_Trajectory_Forecasting_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2203.04781.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#lyft">Lyft</a></li>
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
<a name=trajnet++></a>
<details close>
<summary><l style="font-size:20px"><strong>Trajnet++</strong></l> <a href=https://www.aicrowd.com/challenges/trajnet-a-trajectory-forecasting-challenge#data>link</a> <a href=https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9408398>paper</a> <a href=https://arxiv.org/pdf/2007.03639.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of simulated pedestrian trajectories with focus on interactions.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Trajectory, Tracking Id</li>
<li><em><strong>Task:</strong></em> Trajectory</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Girgis et al., "Latent Variable Sequential Set Transformers for Joint Multi-Agent Motion Prediction", ICLR, 2022.</em> <a href=https://openreview.net/pdf?id=Dup_dDqkZC5>paper</a> <a href=https://arxiv.org/pdf/2104.00563.pdf>arxiv</a> <a href=https://fgolemo.github.io/autobots/>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#trajnet++">Trajnet++</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#dac">DAC</a></li>
<li><a href="../metrics/trajectory_metrics.md#orr">ORR</a></li>
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
<summary><em>Walters et al., "Trajectory Prediction using Equivariant Continuous Convolution", ICLR, 2021.</em> <a href=https://openreview.net/pdf?id=J8_GttYLFgr>paper</a> <a href=https://arxiv.org/pdf/2010.11344.pdf>arxiv</a> <a href=https://github.com/Rose-STL-Lab/ECCO>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#trajnet++">Trajnet++</a></li>
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
<summary><em>Kothari et al., "Interpretable Social Anchors for Human Trajectory Forecasting in Crowds", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Kothari_Interpretable_Social_Anchors_for_Human_Trajectory_Forecasting_in_Crowds_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2105.03136.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#trajnet++">Trajnet++</a></li>
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
@InProceedings{Kothari_2021_CVPR,
    author = "Kothari, Parth and Sifringer, Brian and Alahi, Alexandre",
    title = "Interpretable Social Anchors for Human Trajectory Forecasting in Crowds",
    booktitle = "CVPR",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Cheng et al., "Exploring Dynamic Context for Multi-path Trajectory Prediction", ICRA, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9562034>paper</a> <a href=https://github.com/wtliao/DCENet>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#trajnet++">Trajnet++</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Cheng_2021_ICRA,
    author = "Cheng, Hao and Liao, Wentong and Tang, Xuejiao and Yang, Michael Ying and Sester, Monika and Rosenhahn, Bodo",
    booktitle = "ICRA",
    title = "Exploring Dynamic Context for Multi-path Trajectory Prediction",
    year = "2021"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Jia et al., "Multi-Agent Trajectory Prediction by Combining Egocentric and Allocentric Views", CoRL, 2021.</em> <a href=https://openreview.net/pdf?id=lAtePxetBNb>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#trajnet++">Trajnet++</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Jia_2021_CoRL,
    author = "Jia, Xiaosong and Sun, Liting and Zhao, Hang and Tomizuka, Masayoshi and Zhan, Wei",
    title = "Multi-Agent Trajectory Prediction by Combining Egocentric and Allocentric Views",
    booktitle = "CoRL",
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
@Article{Kothari_2021_TITS,
    author = "Kothari, Parth and Kreiss, Sven and Alahi, Alexandre",
    title = "Human trajectory forecasting in crowds: A deep learning perspective",
    journal = "T-ITS",
    year = "2021"
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
<summary><em>Chang et al., "MAU: A Motion-Aware Unit for Video Prediction and Beyond", NeurIPS, 2021.</em> <a href=https://papers.nips.cc/paper/2021/file/e25cfa90f04351958216f97e3efdabe9-Paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#mmnist">MMNIST</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#town_center">Town Center</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#smtsmt">SmtSmt</a></li>
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
<summary><em>Hasan et al., "Mx-Lstm: Mixing Tracklets And Vislets To Jointly Forecast Trajectories And Head Poses", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Hasan_MX-LSTM_Mixing_Tracklets_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1805.00652.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#town_center">Town Center</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#town_center">Town Center</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mane">MAnE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#town_center">Town Center</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#scr">SCR</a></li>
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
<summary><em>Chen et al., "Simultaneous Prediction of Pedestrian Trajectory and Actions based on Context Information Iterative Reasoning", IROS, 2021.</em> <a href=https://ieeexplore.ieee.org/abstract/document/9636252>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#virat/actev">VIRAT/ActEV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#map">mAP</a></li>
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
<summary><em>Liang et al., "Peeking Into The Future: Predicting Future Person Activities And Locations In Videos", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPRW_2019/papers/Precognition/Liang_Peeking_Into_the_Future_Predicting_Future_Person_Activities_and_Locations_CVPRW_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1902.03748.pdf>arxiv</a> <a href=https://github.com/google/next-prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#virat/actev">VIRAT/ActEV</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#map">mAP</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#virat/actev">VIRAT/ActEV</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#forking_paths">Forking Paths</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#argoverse">Argoverse</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#virat/actev">VIRAT/ActEV</a></li>
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
<summary><em>Chen et al., "S2F2: Single-Stage Flow Forecasting for Future Multiple Trajectories Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820593.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#mot">MOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#iou">IoU</a></li>
<li><a href="../metrics/trajectory_metrics.md#fiou">FIoU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Chen_2022_ECCV,
    author = "Chen, Yu-Wen and Yang, Hsuan-Kung and Chiu, Chu-Chi and Lee, Chun-Yi",
    title = "S2F2: Single-Stage Flow Forecasting for Future Multiple Trajectories Prediction",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Dendorfer et al., "Quo Vadis: Is Trajectory Forecasting the Key Towards Long-Term Multi-Object Tracking?", NeurIPS, 2022.</em> <a href=https://openreview.net/pdf?id=3r0yLLCo4fF>paper</a> <a href=https://arxiv.org/pdf/2210.07681.pdf>arxiv</a> <a href=https://github.com/dendorferpatrick/QuoVadis>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#mot">MOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Dendorfer_2022_NeurIPS,
    author = "Dendorfer, Patrick and Yugay, Vladimir and Osep, Aljosa and Leal-Taix{\'e, Laura",
    title = "Quo Vadis: Is Trajectory Forecasting the Key Towards Long-Term Multi-Object Tracking?",
    booktitle = "NeurIPS",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Meng et al., "Forecasting Human Trajectory from Scene History", NeurIPS, 2022.</em> <a href=https://openreview.net/pdf?id=RW-OOBU11xl>paper</a> <a href=https://arxiv.org/pdf/2210.08732.pdf>arxiv</a> <a href=https://github.com/MaKaRuiNah/SHENet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#mot">MOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Meng_2022_NeurIPS,
    author = "Meng, Mancheng and Wu, Ziyan and Chen, Terrence and Cai, Xiran and Zhou, Xiang Sean and Yang, Fan and Shen, Dinggang",
    title = "Forecasting Human Trajectory from Scene History",
    booktitle = "NeurIPS",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Sanchez-Matilla et al., "A Predictor Of Moving Objects For First-Person Vision", ICIP, 2019.</em> <a href=https://ieeexplore.ieee.org/abstract/document/8803140>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#mot">MOT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
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
<summary><em>Guo et al., "Pedestrian Stop and Go Forecasting with Hybrid Feature Fusion", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9811664>paper</a> <a href=https://arxiv.org/pdf/2203.02489.pdf>arxiv</a> <a href=https://github.com/vita-epfl/hybrid-feature-fusion>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#titan">TITAN</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#ap">AP</a></li>
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
<details close>
<summary><em>Halawa et al., "Action-Based Contrastive Learning for Trajectory Prediction", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136990140.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.08664.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pie">PIE</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#titan">TITAN</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<summary><em>Malla et al., "TITAN: Future Forecast Using Action Priors", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Malla_TITAN_Future_Forecast_Using_Action_Priors_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.13886.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#titan">TITAN</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#ind">inD</a></li>
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
<details close>
<summary><em>Wen et al., "Social ODE: Multi-agent Trajectory Forecasting with Neural Ordinary Differential Equations", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820211.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#ind">inD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#round">rounD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wen_2022_ECCV,
    author = "Wen, Song and Wang, Hao and Metaxas, Dimitris N.",
    title = "Social ODE: Multi-agent Trajectory Forecasting with Neural Ordinary Differential Equations",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul>
</details>
<details close>
<summary><em>Kothari et al., "Motion Style Transfer: Modular Low-Rank Adaptation for Deep Motion Forecasting", CoRL, 2022.</em> <a href=https://openreview.net/pdf?id=tVgD4METs6o>paper</a> <a href=https://arxiv.org/pdf/2211.03165.pdf>arxiv</a> <a href=https://github.com/vita-epfl/motion-style-transfer>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#ind">inD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Kothari_2022_CoRL,
    author = "Kothari, Parth and Li, Danya and Liu, Yuejiang and Alahi, Alexandre",
    title = "Motion Style Transfer: Modular Low-Rank Adaptation for Deep Motion Forecasting",
    booktitle = "CoRL",
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
<a name=basketball></a>
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
<summary><em>Hauri et al., "Multi-Modal Trajectory Prediction of NBA Players", WACV, 2021.</em> <a href=https://openaccess.thecvf.com/content/WACV2021/papers/Hauri_Multi-Modal_Trajectory_Prediction_of_NBA_Players_WACV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.07870.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#basketball">Basketball</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Hauri_2021_WACV,
    author = "Hauri, Sandro and Djuric, Nemanja and Radosavljevic, Vladan and Vucetic, Slobodan",
    title = "Multi-Modal Trajectory Prediction of NBA Players",
    booktitle = "WACV",
    year = "2021"
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#btd">BTD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mr">MR</a></li>
<li><a href="../metrics/trajectory_metrics.md#maxd">maxD</a></li>
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
<summary><em>Qi et al., "Imitative Non-Autoregressive Modeling for Trajectory Forecasting and Imputation", CVPR, 2020.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Qi_Imitative_Non-Autoregressive_Modeling_for_Trajectory_Forecasting_and_Imputation_CVPR_2020_paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#btd">BTD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pems-sf">PEMS-SF</a></li>
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
@InProceedings{Felsen_2018_ECCV,
    author = "Felsen, Panna and Lucey, Patrick and Ganguly, Sujoy",
    title = "Where Will They Go? Predicting Fine-Grained Adversarial Multi-Agent Motion Using Conditional Variational Autoencoders",
    booktitle = "ECCV",
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#mpii_cooking">MPII Cooking</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#virat">VIRAT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#accuracy">Accuracy</a></li>
<li><a href="../metrics/action_metrics.md#recall">Recall</a></li>
<li><a href="../metrics/action_metrics.md#precision">Precision</a></li>
<li><a href="../metrics/action_metrics.md#rmse">RMSE</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#virat">VIRAT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#run_time">Run Time</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#lankershim_boulevard">Lankershim Boulevard</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#thor">THOR</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#lankershim_boulevard">Lankershim Boulevard</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eifp">EIFP</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#usyd">USyd</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#usyd">USyd</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#vci">VCI</a></li>
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
<a name=cpi></a>
<details close>
<summary><l style="font-size:20px"><strong>Car Pedestrian Interaction (CPI)</strong></l> <a href=https://github.com/lmb-freiburg/Multimodal-Future-Prediction>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Makansi_Overcoming_Limitations_of_Mixture_Density_Networks_A_Sampling_and_Fitting_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.03631.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of simulated cars and pedestrians interacting
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Trajectory, Tracking Id</li>
<li><em><strong>Task:</strong></em> Trajectory</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Narayanan et al., "Divide-and-Conquer for Lane-Aware Diverse Trajectory Prediction", CVPR, 2021.</em> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Narayanan_Divide-and-Conquer_for_Lane-Aware_Diverse_Trajectory_Prediction_CVPR_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2104.08277.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cpi">CPI</a></li>
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
<summary><em>Makansi et al., "Overcoming Limitations of Mixture Density Networks: A Sampling and Fitting Framework for Multimodal Future Prediction", CVPR, 2019.</em> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Makansi_Overcoming_Limitations_of_Mixture_Density_Networks_A_Sampling_and_Fitting_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1906.03631.pdf>arxiv</a> <a href=https://github.com/lmb-freiburg/Multimodal-Future-Prediction>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cpi">CPI</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#emd">EMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Makansi_2019_CVPR,
    author = "Makansi, Osama and Ilg, Eddy and Cicek, Ozgun and Brox, Thomas",
    title = "Overcoming Limitations of Mixture Density Networks: A Sampling and Fitting Framework for Multimodal Future Prediction",
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
@InProceedings{Makansi_2019_CVPR,
    author = "Makansi, Osama and Ilg, Eddy and Cicek, Ozgun and Brox, Thomas",
    title = "Overcoming Limitations of Mixture Density Networks: A Sampling and Fitting Framework for Multimodal Future Prediction",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=forking_paths></a>
<details close>
<summary><l style="font-size:20px"><strong>Forking Paths</strong></l> <a href=https://github.com/JunweiLiang/Multiverse>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Liang_The_Garden_of_Forking_Paths_Towards_Multi-Future_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.06445.pdf>arxiv</a></summary> 
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
<summary><em>Li et al., "Graph-Based Spatial Transformer With Memory Replay for Multi-Future Pedestrian Trajectory Prediction", CVPR, 2022.</em> <a href=https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Graph-Based_Spatial_Transformer_With_Memory_Replay_for_Multi-Future_Pedestrian_Trajectory_CVPR_2022_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2206.05712.pdf>arxiv</a> <a href=https://github.com/Jacobieee/ST-MR>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#forking_paths">Forking Paths</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#ptu">PTU</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2022_CVPR,
    author = "Li, Lihuan and Pagnucco, Maurice and Song, Yang",
    title = "Graph-Based Spatial Transformer With Memory Replay for Multi-Future Pedestrian Trajectory Prediction",
    booktitle = "CVPR",
    year = "2022"
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#virat/actev">VIRAT/ActEV</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#forking_paths">Forking Paths</a></li>
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
<summary><l style="font-size:20px"><strong>CityWalks</strong></l> <a href=https://github.com/olly-styles/Multiple-Object-Forecasting>link</a> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Styles_Multiple_Object_Forecasting_Predicting_Future_Object_Locations_in_Diverse_Environments_WACV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1909.11944.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 500+ front-view sequences of pedestrian trajectories annotated at 30fps
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, attribute, Tracking ID</li>
<li><em><strong>Task:</strong></em> Walking</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Styles et al., "Multiple Object Forecasting: Predicting Future Object Locations in Diverse Environments", WACV, 2020.</em> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Styles_Multiple_Object_Forecasting_Predicting_Future_Object_Locations_in_Diverse_Environments_WACV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1909.11944.pdf>arxiv</a> <a href=https://github.com/olly-styles/Multiple-Object-Forecasting>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#citywalks">CityWalks</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<details close>
<summary><em>Ansari et al., "Simple means Faster: Real-Time Human Motion Forecasting in Monocular First Person Videos on CPU", IROS, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9340999>paper</a> <a href=https://arxiv.org/pdf/2011.04943.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#fpl">FPL</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#citywalks">CityWalks</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucf-101">UCF-101</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#caltech_pedestrian">Caltech Pedestrian</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#chuk_avenue">CHUK Avenue</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#shanghaitech_campus">ShanghaiTech Campus</a></li>
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
<summary><em>Xu et al., "Encoding Crowd Interaction With Deep Neural Network For Pedestrian Trajectory Prediction", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/2136.pdf>paper</a> <a href=https://github.com/svip-lab/CIDNN>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#chuk">CHUK</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#ande">ANDE</a></li>
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
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#hev-i">HEV-I</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fiou">FIoU</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#hev-i">HEV-I</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#a3d">A3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fiou">FIoU</a></li>
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
<a name=charges></a>
<details close>
<summary><l style="font-size:20px"><strong>Charges</strong></l> <a href=https://github.com/ethanfetaya/nri>link</a> <a href=http://proceedings.mlr.press/v80/kipf18a/kipf18a.pdf>paper</a> <a href=https://arxiv.org/pdf/1802.04687.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A physics-based simulation of particles.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Trajectory</li>
<li><em><strong>Task:</strong></em> Simulation</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Li et al., "GRIN: Generative Relation and Intention Network for Multi-agent Trajectory Prediction", NeurIPS, 2021.</em> <a href=https://papers.nips.cc/paper/2021/file/e3670ce0c315396e4836d7024abcf3dd-Paper.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#charges">Charges</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#mmd">MMD</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Li_2021_NeurIPS,
    author = "Li, Longyuan and Yao, Jian and Wenliang, Li and He, Tong and Xiao, Tianjun and Yan, Junchi and Wipf, David and Zhang, Zheng",
    booktitle = "NeurIPS",
    title = "GRIN: Generative Relation and Intention Network for Multi-agent Trajectory Prediction",
    year = "2021"
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#charges">Charges</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Kipf_ICML_2018,
    author = "Kipf, Thomas and Fetaya, Ethan and Wang, Kuan-Chieh and Welling, Max and Zemel, Richard",
    title = "Neural relational inference for interacting systems",
    booktitle = "ICML",
    year = "2018"
}
</pre>
</details>

</ul></details>
<a name=fpl></a>
<details close>
<summary><l style="font-size:20px"><strong>First Person Localization (FPL)</strong></l> <a href=https://github.com/takumayagi/fpl>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Yagi_Future_Person_Localization_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1711.11217.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of pedestrian trajectories recorded recorded from ego-perspective
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Trajectory, ego-motion, pose</li>
<li><em><strong>Task:</strong></em> Pedestrian</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Ansari et al., "Simple means Faster: Real-Time Human Motion Forecasting in Monocular First Person Videos on CPU", IROS, 2020.</em> <a href=https://ieeexplore.ieee.org/document/9340999>paper</a> <a href=https://arxiv.org/pdf/2011.04943.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#jaad">JAAD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#fpl">FPL</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#citywalks">CityWalks</a></li>
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
<summary><em>Yagi et al., "Future Person Localization in First-Person Videos", CVPR, 2018.</em> <a href=https://openaccess.thecvf.com/content_cvpr_2018/papers/Yagi_Future_Person_Localization_CVPR_2018_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1711.11217.pdf>arxiv</a> <a href=https://github.com/takumayagi/fpl>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#fpl">FPL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Yagi_2018_CVPR,
    author = "Yagi, Takuma and Mangalam, Karttikeya and Yonetani, Ryo and Sato, Yoichi",
    title = "Future Person Localization in First-Person Videos",
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
@InProceedings{Yagi_2018_CVPR,
    author = "Yagi, Takuma and Mangalam, Karttikeya and Yonetani, Ryo and Sato, Yoichi",
    title = "Future Person Localization in First-Person Videos",
    booktitle = "CVPR",
    year = "2018"
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#h3d">H3D</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nba">NBA</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#h3d">H3D</a></li>
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
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eifp">EIFP</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ed">ED</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#lankershim_boulevard">Lankershim Boulevard</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eifp">EIFP</a></li>
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
@mastersthesis{Majecka_2009,
    author = "Majecka, Barbara",
    title = "Statistical Models Of Pedestrian Behaviour In The Forum",
    school = "School of Informatics, University of Edinburgh",
    year = "2009"
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#orc">ORC</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#kitti">KITTI</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityscapes">Cityscapes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#oxford">Oxford</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#ca">CA</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#volleyball">Volleyball</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#ca">CA</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sbuki">SBUKI</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#otoh">OTOH</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#usyd">USyd</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#vci">VCI</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#a2d2">A2D2</a></li>
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
<a name=loki></a>
<details close>
<summary><l style="font-size:20px"><strong>Long Term and Key Intentions (LOKI)</strong></l> <a href=https://usa.honda-ri.com/loki>link</a> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Girase_LOKI_Long_Term_and_Key_Intentions_for_Trajectory_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2108.08236.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 644 driving scenarios annotated at 5Hz for 8 traffic objects.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Intention, Temporal segment, Attributes, Bounding box</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Girase et al., "LOKI: Long Term and Key Intentions for Trajectory Prediction", ICCV, 2021.</em> <a href=https://openaccess.thecvf.com/content/ICCV2021/papers/Girase_LOKI_Long_Term_and_Key_Intentions_for_Trajectory_Prediction_ICCV_2021_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2108.08236.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#loki">LOKI</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#lankershim_boulevard">Lankershim Boulevard</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#thor">THOR</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#fit">FIT</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#mapillary_vistas">Mapillary Vistas</a></li>
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
<a name=round></a>
<details close>
<summary><l style="font-size:20px"><strong>rounD</strong></l> <a href=https://www.round-dataset.com/>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/9294728>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of road users recorded using drones at German roundabouts.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Trajectory</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Wen et al., "Social ODE: Multi-agent Trajectory Forecasting with Neural Ordinary Differential Equations", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136820211.pdf>paper</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#highd">highD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#ind">inD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#round">rounD</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Wen_2022_ECCV,
    author = "Wen, Song and Wang, Hao and Metaxas, Dimitris N.",
    title = "Social ODE: Multi-agent Trajectory Forecasting with Neural Ordinary Differential Equations",
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
@InProceedings{Krajewski_2020_ITSC,
    author = "Krajewski, Robert and Moers, Tobias and Bock, Julian and Vater, Lennart and Eckstein, Lutz",
    title = "The rounD Dataset: A Drone Dataset of Road User Trajectories at Roundabouts in Germany",
    booktitle = "ITSC",
    year = "2020"
}
</pre>
</details>

</ul></details>
<a name=vdd-c></a>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#vdd-c">VDD-C</a></li>
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
<a name=euro-pvi></a>
<details close>
<summary><l style="font-size:20px"><strong>Euro-PVI</strong></l> <a href=https://www.europvi.mpi-inf.mpg.de>link</a> <a href=https://openaccess.thecvf.com/content/CVPR2021/papers/Bhattacharyya_Euro-PVI_Pedestrian_Vehicle_Interactions_in_Dense_Urban_Centers_CVPR_2021_paper.pdf>paper</a></summary> 
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#euro-pvi">Euro-PVI</a></li>
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
<a name=trajair></a>
<details close>
<summary><l style="font-size:20px"><strong>TrajAir</strong></l> <a href=https://theairlab.org/trajair/>link</a> <a href=https://ieeexplore.ieee.org/document/9811972>paper</a> <a href=https://arxiv.org/pdf/2109.15158.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of airplanes’ trajectories collected in a span of several month with recorded weather conditions in a single runway.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> Trajectory, Date, Weather</li>
<li><em><strong>Task:</strong></em> Airplane</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Patrikar et al., "Predicting Like A Pilot: Dataset and Method to Predict Socially-Aware Aircraft Trajectories in Non-Towered Terminal Airspace", ICRA, 2022.</em> <a href=https://ieeexplore.ieee.org/document/9811972>paper</a> <a href=https://arxiv.org/pdf/2109.15158.pdf>arxiv</a> <a href=https://github.com/castacks/trajairnet>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#trajair">TrajAir</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#minade">minADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#minfde">minFDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Patrikar_2022_ICRA,
    author = "Patrikar, Jay and Moon, Brady and Oh, Jean and Scherer, Sebastian",
    booktitle = "ICRA",
    title = "Predicting Like A Pilot: Dataset and Method to Predict Socially-Aware Aircraft Trajectories in Non-Towered Terminal Airspace",
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
@InProceedings{Patrikar_2022_ICRA,
    author = "Patrikar, Jay and Moon, Brady and Oh, Jean and Scherer, Sebastian",
    booktitle = "ICRA",
    title = "Predicting Like A Pilot: Dataset and Method to Predict Socially-Aware Aircraft Trajectories in Non-Towered Terminal Airspace",
    year = "2022"
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ucy">UCY</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#eth">ETH</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pets2009">PETS2009</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
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
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#mitt">MITT</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ed">ED</a></li>
<li><a href="../metrics/trajectory_metrics.md#run_time">Run Time</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#btd">BTD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#pems-sf">PEMS-SF</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#atc">ATC</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#run_time">Run Time</a></li>
<li><a href="../metrics/trajectory_metrics.md#mhd">MHD</a></li>
<li><a href="../metrics/trajectory_metrics.md#nlp">NLP</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#spmd">SPMD</a></li>
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
<a name=volleyball></a>
<details close>
<summary><l style="font-size:20px"><strong>Volleyball</strong></l> <a href=https://github.com/mostafa-saad/deep-activity-rec#dataset>link</a> <a href=https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Ibrahim_A_Hierarchical_Deep_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1511.06040.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 4830 frames from 55 videos with 9 player action labels and 8 team activity labels
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity label, Bounding box</li>
<li><em><strong>Task:</strong></em> Sport</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Chen et al., "Group Activity Prediction with Sequential Relational Anticipation Model", ECCV, 2020.</em> <a href=https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660579.pdf>paper</a> <a href=https://arxiv.org/pdf/2008.02441.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#ca">CA</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#volleyball">Volleyball</a></li>
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
</ul></details>
<details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Ibrahim_2016_CVPR,
    author = "Ibrahim, Mostafa S and Muralidharan, Srikanth and Deng, Zhiwei and Vahdat, Arash and Mori, Greg",
    title = "A hierarchical deep temporal model for group activity recognition",
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
<em><strong>Applications:</strong></em> <a href=../papers/action_papers.md#top>Action prediction<application></a>, <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Activity Label, Trajectory</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Hu et al., "Entry-Flipped Transformer for Inference and Prediction of Participant Behavior", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136640433.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.06235.pdf>arxiv</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#ceilidh_dance">Ceilidh Dance</a></li>
<li>Custom</li>

</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/action_metrics.md#f1">F1</a></li>
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
    title = "Ceilidh dance recognition from an overhead camera",
    year = "2016",
    school = "University of Edinburgh"
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#strands">STRANDS</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#l-cas">L-CAS</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#strands">STRANDS</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#l-cas">L-CAS</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#cityperson">CityPerson</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#nuscenes">nuScenes</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#fit">FIT</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#mapillary_vistas">Mapillary Vistas</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#osu">OSU</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#nll">NLL</a></li>
<li><a href="../metrics/trajectory_metrics.md#mse">MSE</a></li>
<li><a href="../metrics/trajectory_metrics.md#mhd">MHD</a></li>
<li><a href="../metrics/trajectory_metrics.md#kld">KLD</a></li>
<li><a href="../metrics/trajectory_metrics.md#dtg">DtG</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#dad">DAD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#hev-i">HEV-I</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#a3d">A3D</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fiou">FIoU</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#ngsim">NGSIM</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#traf">TRAF</a></li>
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
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#ca">CA</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sbuki">SBUKI</a></li>
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
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#gc">GC</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#qmul">QMUL</a></li>
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
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#fm">FM</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#accuracy">Accuracy</a></li>
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
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#tum_kitchen">TUM Kitchen</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ed">ED</a></li>
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
<a name=vtp-tl></a>
<details close>
<summary><l style="font-size:20px"><strong>VTP-TL</strong></l> <a href=https://github.com/VTP-TL/D2-TPred>link</a> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136680512.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.10398.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of various types of road intersections recorded using a drone.
</li>
<li>
<em><strong>Applications:</strong></em> <a href=../papers/trajectory_papers.md#top>Trajectory prediction<application></a></li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Trajectory, map, Activity Label, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong><em>Used in papers</em></strong></summary>
<ul><details close>
<summary><em>Zhang et al., "D2-TPred: Discontinuous Dependency for Trajectory Prediction under Traffic Lights", ECCV, 2022.</em> <a href=https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136680512.pdf>paper</a> <a href=https://arxiv.org/pdf/2207.10398.pdf>arxiv</a> <a href=https://github.com/VTP-TL/D2-TPred>code</a></summary>
<ul>
<em>Datasets</em>
<ul>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#sd">SD</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#wod">WOD</a></li>
<li><a href="../datasets/alphabetical/e-i_alphabetical_datasets.md#interaction">INTERACTION</a></li>
<li><a href="../datasets/alphabetical/a-d_alphabetical_datasets.md#apolloscape">ApolloScape</a></li>
<li><a href="../datasets/alphabetical/j-z_alphabetical_datasets.md#vtp-tl">VTP-TL</a></li>
</ul>
<em>Metrics</em>
<ul>
<li><a href="../metrics/trajectory_metrics.md#ade">ADE</a></li>
<li><a href="../metrics/trajectory_metrics.md#fde">FDE</a></li>
</ul>
<details close>
<summary><em>Bibtex</em></summary>
<pre>
@InProceedings{Zhang_2022_ECCV,
    author = "Zhang, Yuzhen and Wang, Wentong and Guo, Weizhi and Lv, Pei and Xu, Mingliang and Chen, Wei and Manocha, Dinesh",
    title = "D2-TPred: Discontinuous Dependency for Trajectory Prediction under Traffic Lights",
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
@InProceedings{Zhang_2022_ECCV,
    author = "Zhang, Yuzhen and Wang, Wentong and Guo, Weizhi and Lv, Pei and Xu, Mingliang and Chen, Wei and Manocha, Dinesh",
    title = "D2-TPred: Discontinuous Dependency for Trajectory Prediction under Traffic Lights",
    booktitle = "ECCV",
    year = "2022"
}
</pre>
</details>

</ul></details>
</ul>
