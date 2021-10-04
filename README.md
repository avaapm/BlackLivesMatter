# What Happened in Social Media during the 2020 BLM Movement? An Analysis of Deleted and Suspended Users in Twitter

This repository contains the utilized components and results from the paper [What Happened in Social Media during the 2020 BLM Movement? An Analysis of Deletedand Suspended Users in Twitter](https://arxiv.org/abs/2110.00070). This study mainly focuses on the user behaviors in Twitter after the emergence of the 2020 BLM Movement.

## Dataset

The dataset used in this study is composed of two main parts: Users that involving BLM movement [`blm_user_and_tweet_ids.7z`](https://github.com/avaapm/BlackLivesMatter/raw/master/blm_user_and_tweet_ids.7z) and control group users [`control_user_and_tweet_ids.7z`](https://github.com/avaapm/BlackLivesMatter/raw/master/control_user_and_tweet_ids.7z). Columns of the dataset are the same and defined as follows:

| Column Name  | Description |
| ------------- | ------------- |
| Tweet ID  | Twitter ID number of the tweet |
| User ID  | Twitter ID number of the user |
| Old/New  | Old: User account is created before 2020/05/25, New: User account is created after 2020/05/25 |
| Label<sup>1</sup> | 0: Active user, 50: Deleted User, 63: Suspended User |

<sup>1</sup> Status (labels) of users may change depending on the date you downloaded the dataset.

## Supplementary Material

BLM related keywords, hashtags used in experiments, statistical significance tests and other substantial statistics of the dataset can be found in [`stat_test_and_other_details.7z`](https://github.com/avaapm/BlackLivesMatter/raw/master/stat_test_and_other_details.7z) and [`supplementary_material.pdf`](https://github.com/avaapm/BlackLivesMatter/raw/master/supplementary_material.pdf)

If you make use of this repository, please cite the following paper:

```bibtex
@article{toraman2021blm,
      title={What Happened in Social Media during the 2020 BLM Movement? An Analysis of Deleted and Suspended Users in Twitter}, 
      author={Cagri Toraman and Furkan \c{S}ahinu\c{c} and Eyup Halit Yilmaz},
      year={2021},
      eprint={2110.00070},
}
```
