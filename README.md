# HierCDF



#### Description
This is the official code of the KDD'22 research track paper *HierCDF: A Bayesian Network-based Hierarchical Cognitive Diagnosis Framework*.

If you want to cite this paper, please use citations below.

- BibTeX
```bibtex
@inproceedings{10.1145/3534678.3539486,
author = {Li, Jiatong and Wang, Fei and Liu, Qi and Zhu, Mengxiao and Huang, Wei and Huang, Zhenya and Chen, Enhong and Su, Yu and Wang, Shijin},
title = {HierCDF: A Bayesian Network-Based Hierarchical Cognitive Diagnosis Framework},
year = {2022},
isbn = {9781450393850},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3534678.3539486},
doi = {10.1145/3534678.3539486},
booktitle = {Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining},
pages = {904–913},
numpages = {10},
keywords = {bayesian network, attribute hierarchy, cognitive diagnosis},
location = {Washington DC, USA},
series = {KDD '22}
}
```

- ACM Ref
```
Jiatong Li, Fei Wang, Qi Liu, Mengxiao Zhu, Wei Huang, Zhenya Huang, Enhong Chen, Yu Su, and Shijin Wang. 2022. HierCDF: A Bayesian Network-based Hierarchical Cognitive Diagnosis Framework. In Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD '22). Association for Computing Machinery, New York, NY, USA, 904–913. https://doi.org/10.1145/3534678.3539486
```

#### File Structure
- config.py: the configuration of the HierCDF model
- dataloader.py: the data loader of the HierCDF model
- itf.py: basic interaction functions of HierCDF (IRT, MIRT, MF)
- model.py: the definition of the HierCDF model
- README.md: It's me. :-)
- requirements.txt: necessary python packages for HierCDF.
- tools.py: some tools, e.g., logger, data divider, etc.
- train.py: the training script. (If you want to train HierCDF, please use this!)
- data/: data files
  - train*.csv: the train set
  - test*.csv: the test set
  - hier.csv: the attribute hierarchy
  - Q_matrix.txt: the exercise-attribute Q matrix.

#### Installation
- You'd better run the HierCDF on a Linux platform.
- install & run:
```
pip3 install -r requirements.txt
python3 train.py
```

#### P.S.
- There are several interaction functions for HierCDF: 
  - `irt`,`mirt`,`mf`,`sigmoid-mf`,`ncd` (the `ncd` is defined in model.py)



