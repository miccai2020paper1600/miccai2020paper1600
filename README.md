# Universal Loss Reweighting to Balance Lesion Size Inequality in 3D Medical Image Segmentation
Anonymous code release for paper id 1600
## Table of Contents
* [Typos](#typos)
* [Requirements](#requirements)
* [Repository Structure](#repository-structure)
* [Results](#results)
* [Experiment Reproduction](#experiment-reproduction)
## Typos
1. Introduction. Paragraph 3.  In some cases, large lesions could be up to 50 times bigger than the small one (see Supplementary Materials Fig. 3). Should be: <...than the small one (Fig. 1)>
2. Introduction. Paragraph 4.  The shortcoming of this approach is that it pays attention to lesion type, but not lesion size (Fig. ??). Should be: <...but not lesion size(Supplementary Materials Fig. 3)>
3. [TODO] last caption
## Requirements
- [Python](https://www.python.org) (v3.6 or later)
- [Deep pipe](https://github.com/neuro-ml/deep_pipe) (commit: [4383211ea312c098d710fbeacc05151e10a27e80](https://github.com/neuro-ml/deep_pipe/tree/4383211ea312c098d710fbeacc05151e10a27e80))
- [NiBabel](https://pypi.org/project/nibabel/) (v3.0.2)
- [NumPy](http://numpy.org/) (v1.17.0 or later)
- [OpenCV python](https://pypi.org/project/opencv-python/) (v4.2.0.32)
- [Pandas](https://pandas.pydata.org/) (v1.0.1 or later)
- [SciPy library](https://www.scipy.org/scipylib/index.html) (v0.19.0 or later)
- [scikit-image](https://scikit-image.org) (v0.15.0 or later)
- [Simple ITK](http://www.simpleitk.org/) (v1.2.4)
- [torch](https://pypi.org/project/torch/) (v1.1.0 or later)
- [tqdm](https://tqdm.github.io) (v4.32.0 or later)
## Repository Structure
[TODO] Brief explanation of each part purpose..
```
├── config
│   ├── assets
│   └── exp_holdout
│       ├── lits
│       │   └── *.config
│       └── luna
│           └── *.config
├── iw
├── notebook
│   ├── data_preprocessing
│   └── results
│       └── placeholder
├── plots
│   └── placeholder
└── README.md
```
## Results
[TODO] Description of the notebook/plots with the results..
## Experiment Reproduction
[TODO] Step-by-step guide to run an experiment..
