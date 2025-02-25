<a name=top></a>
# Deep Learning for Vision-based Prediction
This repository serves as a reference database for the paper [Deep Learning for Vision-based Prediction: A Survey](https://arxiv.org/pdf/2007.00095.pdf). Here you can find the list of **vison-based prediction** papers that use **deep learning** and are published since **2015**. The goal is to maintain this repository by adding papers published as they become available online.

All the papers contain the following information: **datasets** and **metrics** they use as well as corresponding **bibtex** and **links** to all published papers. The bibtex of all papers can also be found in `prediction_refs.bib`.

Similar to the survey paper, the papers are categorized into 5 groups: **Video**, **Action**, **Trajectory**, **Motion** and **Other** which may include applications such as visual weather forecasting, fashion trends prediction, etc.

The repository also contains information about the datasets used in the papers. Here, for each dataset, in addition to the **links** to the dataset and corresponding **papers**,  you can find information regarding  **applications**, **type or annotations**, **task**, **list of papers** used the dataset and **bibtex** of the publication.

To search for papers, you can use one of the following options:

* [Papers](papers/papers.md#top)
  * [Video prediction](papers/video/video_papers.md#top)
  * [Action prediction](papers/action/action_papers.md#top)
  * [Trajectory prediction](papers/trajectory/trajectory_papers.md#top)
  * [Motion prediction](papers/motion/motion_papers.md#top)
  * [Other prediction](papers/other/other_papers.md#top)
  * [Papers with code](papers/papers_with_code/papers_with_code.md#top)
* [Datasets](datasets/datasets.md#top)
  * [Alphabetical](datasets/alphabetical/alphabetical_datasets.md#top)
  * [Year](datasets/year/year_datasets.md#top)
  * [Application](datasets/application/application_datasets.md#top)
  * [Task](datasets/task/task_datasets.md#top)
  * [Annotation](datasets/annotation_datasets.md#top)
* [Metrics](metrics/metrics.md#top)


### Contribute to this project
Please feel free to submit an issue if you found missing information, incorrect links, etc. If you consider contributing please see [contribution](contribution.md)

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

### Updates
### As of now I don't have any plan to continue adding works to this repo beyond 2024. The repository, however, stays up, hoping it will be beneficial to the community
* 9/02/2025: Added 2024 CoRL, IROS, ECCV, and NeurIPS (68 papers, 17 datasets and 12 metrics)
* 18/08/2024: Minor updates and change to dataset abbreviations (WOD->WOMD, SD->SDD)
* 18/08/2024: Added ICRA and RAL 2024 (46 papers) and missing RAL 2020-2023 (31 papers) (in total: 77 papers, 10 datasets, 16 metrics) 
* 17/08/2024: Added ICLR and ICML 2024 papers (12 papers, 9 datasets, 4 metrics)
* 11/08/2024: Added CVPR 2024 papers (48 papers, 10 datasets, 13 metrics)
* 11/08/2024: Note that this is the last year covering ACCV and BMVC papers due to the volume of papers in other conferences 
* 25/02/2024: Added IROS 2023 papers (16 papers, 4 datasets, 1 metric)
* 2/11/2023: Updated metrics. They are divided based on ranking and alphabetical order
* 2/11/2023: Updated some papers and 1 dataset is added
* 19/10/2023: Note that this is the last year covering WACV papers due to the volume of papers in other conferences 
* 19/10/2023: Added 2023 papers for ICCV, CVPR, ICML, CoRL, ICRA, WACV (100 papers, 26 datasets, 23 metrics)
* 16/03/2023: Added IROS2022 and 2 additional (30 papers, 4 datasets, 2 metrics)
* 16/02/2023: Updated metric information for a number of trajectory prediction models
* 27/1/2023: Added 1 paper ECCV2022
* 18/1/2023: Added 10 papers from previous years
* 15/1/2023: Added 7 papers and 1 metric from previous years
* 12/1/2023: Updated the paper links for CoRL 2020
* 11/1/2023: Split pages by year
* 9/1/2023: Improved styling of bibtex
* 9/1/2023: Minor bug fixes and readability improvement
* 9/1/2023: Added ICRA 22 (21 papers, 2 metrics, 2 datasets)
* 23/12/2022: Added CoRL 21-22,RSS 20-21 (15 papers, 4 metrics)
* 16/12/2022: Added NeurIPS, ICLR, BMVC, WACV, ACCV 2022 (17 papers, 1 dataset, 3 metrics)
* 11/11/2022: Fixed some bugs with reference links
* 11/11/2022: Added ECCV 2022 (28 papers, 86 datasets, 6 metrics)
* 21/06/2022: Added CVPR 2022 (38 papers, 8 datasets, 6 metrics)
* 10/05/2022: Added ICRA,IROS, NeurIPS, ICLR 2021 (74 papers, 8 datasets, 17 metrics)
* 12/10/2021: Added a CVPR2021 paper + 1 dataset
* 12/10/2021: ICCV 2021 added(31 papers, 4 datasets, 9 metrics)
* 31/07/2021: CVPR 2021 added(25 papers, 5 datasets, 7 metrics)
* 02/05/2021: Note: Starting 2021, ICIP and ICPR papers  no longer will be added
* 02/05/2021: CoRL, BMVC, and ICIP 2020 (18 papers, 2 datasets, 3 metrics)
* 17/02/2021: ICML 2020 (3 papers, 1 dataset)
* 16/02/2021: NeurIPS 2020, IROS 2020, RAL 2020 (25 papers, 10 datasets, 3 metrics)
* 24/01/2021: WACV 2021 added (8 papers, 1 dataset, 4 metrics)
* 24/01/2021: Fixed some bugs and added 1 paper and 1 dataset
* 12/12/2020: ACCV 2020 added (3 papers, 2 metrics)
* 18/11/2020: RAL 2015-2019 added (8 papers, 3 datasets, 2 metrics)
* 17/11/2020: ICRA and RAL 2020 papers are added (25 papers, 1 dataset)
* 17/11/2020: 3 new papers and 2 datasets added (CVPR18, ICRA19, IROS19)
* 03/09/2020: RSS 2015-2020 papers added (7 papers, 1 dataset)
* 27/08/2020: ECCV2020 papers added (30 papers, 15 datasets)
* 03/08/2020: Added summary information to datasets
* 03/08/2020: Updated the information for some of the datasets
* 27/07/2020: Added CVPR and WACV 2020 papers
* 27/07/2020: 16 new datasets are added
