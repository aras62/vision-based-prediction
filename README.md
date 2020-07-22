<a name=top></a>
# Deep Learning for Vision-based Prediction
This repository serves as a reference database for the paper [Deep Learning for Vision-based Prediction: A Survey](https://arxiv.org/pdf/2007.00095.pdf). Here you can find the list of **vison-based prediction** papers that use **deep learning** and are published since *five years ago (ending 2019)*. The goal is to maintain this repository by adding papers published after 2019 and upward.

All the papers contain the following information: **datasets** and **metrics** they use as well as corresponding **bibtex** and **links** to all published papers.

Similar to the survey paper, the papers are categorized into 5 groups: **Video**, **Action**, **Trajectory**, **Motion** and **Other** which may include applications such as visual weather forecasting, fashion trends prediction, etc.

The repository also contains information about the datasets used in the papers. Here, for each dataset, in addition to the **links** to the dataset and corresponding **papers**,  you can find information regarding  **applications**, **type or annotations**, **task**, **list of papers** used the dataset and **bibtex** of the publication.

To search for papers, you can use one of the following options:

* [Papers](papers/papers.md#top)
  * [Video prediction](papers/video_papers.md#top)
  * [Action prediction](papers/action_papers.md#top)
  * [Trajectory prediction](papers/rajectory_papers.md#top)
  * [Motion prediction](papers/motion_papers.md#top)
  * [Other prediction](papers/other_papers.md#top)
  * [Papers with code](papers/papers_with_code.md#top)
* [Datasets](datasets/datasets.md#top)
  * [Year](datasets/year_datasets.md#top)
  * [Application](datasets/application_datasets.md#top)
  * [Task](datasets/task_datasets.md#top)
  * [Annotation](datasets/annotation_datasets.md#top)
* [Metrics](metrics.md#top)


### Contribute to this project
Please feel free to submit an issue if you found missing information, incorrect links, etc.

I intend to maintain this database by including papers for this and upcoming years. However, if you found papers missing from the list that should be included, please provide the following information and I'll do my best to include them:

* *Paper name*
* *Venue (journal, conference, etc.) it was published in*
* *Metric(s) used in the paper*
* *Dataset(s) used in the paper*
* *Links to the paper, and arxiv and code (if any). **Note**: the links for the paper should be to the original webpages of the journal or conference proceedings and/or authors' published code.

Please make sure the paper has the following characteristics:
* **Vision-based** The paper has to have a computer vision component, i.e. it should present algorithms that use vision data. The data can be either in the form of RGB, LIDAR, etc. or can be extracted from visual data such as trajectory, pose, etc.

* **Published in recognized venues** Attempts have been made to maintain a list of high quality papers that are published in recognized venues. So please do not send works that are only published as pre-print, tech reports, etc. or published in low ranking journals or conferences.

### Cite
If you found this database and the paper useful for your research, please consider citing the paper as:
```
@Article{Rasouli_2020_arxiv,
  title={Deep Learning for Vision-based Prediction: A Survey},
  author={Rasouli, Amir},
  journal={arXiv:2007.00095},
  year={2020}
}
```
