# SCEBIOS Library (scebios_lib)
This is the software library with code developed in the SCEBIOS project

This repository contains the software library with all the code developed during the [SCEBIOS project](http://www.etti.legacy.tuiasi.ro/ncleju/scebios/),
including the code which supports all the papers and manuscripts written during the project's implementation period.

## Organization
The library consists of 6 submodules. For convenience, each has its own repository, such that it is possible to clone only
one particular repository that you are interested in.

Due to the nature of research, 3 submodules are developed in Python, and the other 3 in Matlab.

A short description of the submodules is given here. More details about each one are provided below.

|    Submodule  |  Language  | Description  |
| ------------- | ---------- | ------------- |
|[code_paper_FusionOMPLSP](https://github.com/scebios-project/code_paper_FusionOMPLSP) | Python | Accompanying code for the paper "Fusion of Orthogonal Matching Pursuit and Least Squares Pursuit for Robust Sparse Recovery".|
|[code_paper_code_paper_IterativeAffineProjections](https://github.com/scebios-project/code_paper_code_paper_IterativeAffineProjections) | Python | Accompanying code for the paper "Spectrum Insensitive Sparse Recovery with Iterative Affine Projections".|
|[code_paper_PrecKSVD](https://github.com/scebios-project/code_paper_PrecKSVD) | Matlab | Accompanying code for the manuscript "Preconditioned K-SVD for ECG Anomaly Detection".  This also contains the code for sparse coding on multichannel signals.|
|[code_paper_NSTPrec](https://github.com/scebios-project/code_paper_NSTPrec) | Python | Accompanying code for the manuscript "Null Space Tuning and Preconditioning for Ill-Conditioned Sparse Recovery".|
|[code_ECG_BoW_Pat](https://github.com/scebios-project/code_ECG_BoW_Pat) | Matlab | Code for the project results on pathology detection from ECG signals based on Sparse COding and Bag-of-Words".|
|[code_ECG_BoW_Identif](https://github.com/scebios-project/code_ECG_BoW_Identif) | Matlab | Code for the project results on person identification based on ECG signals based on Sparse Coding and Bag-of-Words".|




## Installation

### Full install
To install the complete library please run:

```git clone --recursive https://github.com/scebios-project/scebios_lib```

### Install specific submodules
To install only a specific submodule, run one of the following lines:

```git clone --recursive https://github.com/scebios-project/code_ECG_BoW_Identif```

```git clone --recursive https://github.com/scebios-project/code_ECG_BoW_Pat```

```git clone --recursive https://github.com/scebios-project/code_paper_FusionOMPLSP```

```git clone --recursive https://github.com/scebios-project/code_paper_IterativeAffineProjections```

```git clone --recursive https://github.com/scebios-project/code_paper_NSTPrec```

```git clone --recursive https://github.com/scebios-project/code_paper_PrecKSVD```

## Content
