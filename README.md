# MAPS Dataset

Malware Analysis and Profiling on Smartphones (MAPS) Dataset

# What is MAPS?

MAPS dataset is for the research community that provides a very in-depth and detailed deep analysis of Android applications for 
extracting an enhanced set of features. The MAPS dataset relies on a diverse dataset collected from different repositories, 
containing more than 153000 applications (>2TB in size), and outputs more than 40000 features for analysis and training of deep neural network models.

# Dataset

The dataset (header included) is divided into multiple 20 MiB files (i.e., benign and malware), which require to be combined via the following command.

```bash
cat Benign_wheader.?? > Benign_wheader.tar.gz
```

# Acknowledgment

If you use MAPS dataset, you must cite the following paper [MAPS's paper](https://dl.acm.org/doi/10.1145/3556548.3559629).

```bash

Pasdar A, Lee YC, Hong SH, Liu T. MAPS: a dataset for semantic profiling and analysis of Android applications. InProceedings of the 17th ACM Workshop on Mobility in the Evolving Internet Architecture 2022 Oct 21 (pp. 13-18).

