# SCEBIOS Library (scebios_lib)
This is the software library with code developed in the SCEBIOS project

This repository contains the software library with all the code developed during the [SCEBIOS project](http://www.etti.legacy.tuiasi.ro/ncleju/scebios/),
including the code which supports all the papers and manuscripts written during the project's implementation period.

## Organization
The library consists of 6 submodules. For convenience, each has its own repository, such that it is possible to clone only
one particular repository that you are interested in.

|    Submodule  |  Description  |
| ------------- | ------------- |
| (Python) [code_paper_FusionOMPLSP](https://github.com/scebios-project/code_paper_FusionOMPLSP) | Accompanying code for the paper "Fusion of Orthogonal Matching Pursuit and Least Squares Pursuit for Robust Sparse Recovery".|
| (Python) [code_paper_code_paper_IterativeAffineProjections](https://github.com/scebios-project/code_paper_code_paper_IterativeAffineProjections) | Accompanying code for the paper "Spectrum Insensitive Sparse Recovery with Iterative Affine Projections".|
| (Matlab) [code_paper_PrecKSVD](https://github.com/scebios-project/code_paper_PrecKSVD) | Accompanying code for the manuscript "Preconditioned K-SVD for ECG Anomaly Detection".  This also contains the code for sparse coding on multichannel signals.|
| (Python) [code_paper_NSTPrec](https://github.com/scebios-project/code_paper_NSTPrec) | Accompanying code for the manuscript "Null Space Tuning and Preconditioning for Ill-Conditioned Sparse Recovery".|
| (Matlab) [code_ECG_BoW_Pat](https://github.com/scebios-project/code_ECG_BoW_Pat) | Code for the project results on pathology detection from ECG signals based on Sparse COding and Bag-of-Words".|
| (Matlab) [code_ECG_BoW_Identif](https://github.com/scebios-project/code_ECG_BoW_Identif) | Code for the project results on person identification based on ECG signals based on Sparse Coding and Bag-of-Words".|




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
