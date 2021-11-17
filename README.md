# ARGH-Rumor-Generation

[![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1uh9iZ4IFM3YQJTMIKrfmXb8hTxNEyUIx?usp=sharing)

## Disclaimer:
The ARGH software was developed for academic purposes to augment rumor datasets and improve rumor detection models. ARGH is not for generating rumors for the   purpose of spreading misinformation. ARGH is not for any illicit, unethical, or questionable purposes. It exists in an educational and academic capacity, intended  to further the study of rumor detection methods. A demonstration of the framework has been made available, however the codebase and datasets used to produce the generative model will not be released.

## Description:
This repository contains the demo and datasets for [ARGH!: Automated Rumor Generation Hub](https://dl.acm.org/doi/abs/10.1145/3459637.3481894)
<br>
Larry Huynh, Thai Nguyen, Joshua Goh, Hyoungshick Kim, Jin B. Hong

# Datasets:

    The datasets can be found in : ./datasets
    - PHEME5 generated rumors dataset
        - CSV with the generated rumors used
        - Files containing all the generations created for each rumor
    - Twitter16 generated rumors dataset
        - CSV with the generated rumors used
        - Files containing all the generations created for each rumor
            - First line of each .txt file is the original rumor

# Demo:
The demo can be accessed on Google Colab through this url: https://colab.research.google.com/drive/1uh9iZ4IFM3YQJTMIKrfmXb8hTxNEyUIx?usp=sharing

# Citation:
Please cite [our paper](https://dl.acm.org/doi/abs/10.1145/3459637.3481894) if you use code from this repo:

    @inproceedings{huynh2021argh,
      title={ARGH! Automated Rumor Generation Hub},
      author={Huynh, Larry and Nguyen, Thai and Goh, Joshua and Kim, Hyoungshick and Hong, Jin B},
      booktitle={Proceedings of the 30th ACM International Conference on Information \& Knowledge Management},
      pages={3847--3856},
      year={2021}
    }
