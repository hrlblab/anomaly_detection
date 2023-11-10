# Feasibility of Universal Anomaly Detection without Knowing the Abnormality in Medical Images

This is the official implementation of Feasibility of Universal Anomaly Detection without Knowing the Abnormality in Medical Images. <br />

**MILLanD2023 Paper** <br />
> [Feasibility of Universal Anomaly Detection without Knowing the Abnormality in Medical Images](https://arxiv.org/pdf/2307.00750.pdf) <br />
> Can Cui, Yaohong Wang, Shunxing Bao, Yucheng Tang, Ruining Deng, Lucas W. Remedios, Zuhayr Asad, Joseph T. Roland, Ken S. Lau, Qi Liu, Lori A. Coburn, Keith T. Wilson, Bennett A. Landman, Yuankai Huo  <br />
> *MICCAI MILLanD2023 Workshop* <br />

## Abstract
Many anomaly detection approaches, especially deep learning methods, have been recently developed to identify abnormal image morphology by only employing normal images during training. Unfortunately, many prior anomaly detection methods were optimized for a specific “known” abnormality (e.g., brain tumor, bone fraction, cell types). Moreover, even though only the normal images were used in the training process, the abnormal images were often employed during the validation process (e.g., epoch selection, hyper-parameter tuning), which might leak the supposed “unknown” abnormality unintentionally. <br /> 

In this study, we investigated these two essential aspects regarding universal anomaly detection in medical images by: <br />
(1) comparing various anomaly detection methods across four medical datasets; <br />
(2) investigating the inevitable but often neglected issues on how to unbiasedly select the optimal anomaly detection model during the validation phase using only normal images;<br />
(3) proposing a simple decision-level ensemble method to leverage the advantage of different kinds of anomaly detection without knowing the abnormality. 

## Quick Start
#### Get our docker image
Todo

#### Run code
Todo


## Citation
```
@inproceedings{cui2023feasibility,
  title={Feasibility of Universal Anomaly Detection Without Knowing the Abnormality in Medical Images},
  author={Cui, Can and Wang, Yaohong and Bao, Shunxing and Tang, Yucheng and Deng, Ruining and Remedios, Lucas W and Asad, Zuhayr and Roland, Joseph T and Lau, Ken S and Liu, Qi and others},
  booktitle={Workshop on Medical Image Learning with Limited and Noisy Data},
  pages={82--92},
  year={2023},
  organization={Springer}
}

```
