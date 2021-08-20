# Fact-check-experiment

This repository contains replication materials for the paper _"Perceiving Fact-Checks as Biased but Nevertheless Persuaded? Effects of Fact-Checking News Delivered by Partisan Media"_ (working paper). 

For any questions or inquries, please contact the corresponding author, Hyunjin (Jin) Song (hyunjinsong@yonsei.ac.kr) or the first author [Je Hoon Chae][https://jehoonchae.github.io/] (chaejehoon@yonsei.ac.kr). Questions concerning R codes should be directed to the first author.



## Structure of the Repository

Replication codes for reproducing the results reported in the paper are located within each Study folder (e.g., ```Study 1``` directory), where we place all analyses and statistics reported in the paper. In addition, ```Preregistration and analysis plan``` directory contains the pre-registered hypotheses and analytic plans (Study 2: registered at [https://osf.io/jtbz5/](https://osf.io/jtbz5), 2021-06-18). To control relative file paths, using `FC-experiment.Rproj` can be an option.

#### Data

[`./Study 1/main-analysis/data/`](./Study 1/main-analysis/data/)

- `raw-data_study-1.xlsx`: Raw data which was initally collected for Study 1 with South Korean sample on September 2019.
- `processed-data_study-1.csv`: Pre-processed data which recoding and leaving only relevant varilbles from `processed-data_study-1.csv`.

[`./Study 2/03_main-analysis/data/`](./Study 2/03_main-analysis/data/)

- `raw-data_study-2.csv`: Raw data which was collected for Study 2 with U.S. sample (Amazon MTurk) on June 2021.
- `processed-data_study-2.csv`: Pre-processed data recoding and leaving only relevant variables from `raw-data_study-2.csv`

#### Code

[`./Study 1/main-analysis/code/`](./Study 1/main-analysis/code/)

- `01_data-clean.R`: Data wrangling R script code of Study 1
- `02_table-1.R`:  Prints Table 1 in the paper
- `03_table-2.R`:  Prints Table 2 in the paper
- `04_table-3.R`:  Prints Table 3 in the paper
- `05_figure-1.R`:  Generate Figure 1 in the paper
- `06_figure-2.R`:  Generate Figure 2 in the paper

[`./Study 2/03_main-analysis/code/`](./Study 2/03_main-analysis/code/)

- `01_data-clean.R`: Data wrangling R script code of Study 2
- `02_table-4.R`:  Prints Table 4 in the paper
- `03_table-5.R`:  Prints Table 5 in the paper
- `04_table-6.R`:  Prints Table 6 in the paper
- `05_table-7.R`:  Prints Table 7 in the paper
- `06_figure-3.R`:  Generate Figure 3 in the paper
- `07_figure-4.R`:  Generate Figure 4 in the paper

#### Results

Following folders are containing the figures (files of `.png` and `.pdf` extensions) of study 1 and 2 generated by the R code

- [`./Study 1/main-analysis/results/`](./Study 1/main-analysis/results/)

- [`./Study 2/03_main-analysis/results/`](./Study 2/03_main-analysis/results/)


