# Superlearner-Hepatology-2024

This repository contains code to reproduce the results presented in the paper 

> **Charu V, Liang JW, Mannalithara A, Kwong A, Tian, Lu, and Kim, RW. Benchmarking clinical risk prediction algorithms with ensemble machine learning: An illustration of the superlearner algorithm for the non-invasive diagnosis of liver fibrosis in non-alcoholic fatty liver disease. 2024.**

Original repo with commit history can be found [here](https://github.com/janewliang/NAFLD_superlearner). 

## R package dependencies
- Data wrangling and visualization: [`tidyverse`](https://cran.r-project.org/web/packages/tidyverse/index.html), [`gridExtra`](https://cran.r-project.org/web/packages/gridExtra/index.html), [`gtable`](https://cran.r-project.org/web/packages/gtable/index.html), [`reshape2`](https://cran.r-project.org/web/packages/reshape2/index.html), [`forcats`](https://cran.r-project.org/web/packages/forcats/index.html), and [`cowplot`](https://cran.r-project.org/web/packages/cowplot/index.html)
- Superlearners: [`Superlearner`](https://cran.r-project.org/web/packages/SuperLearner/index.html)
- Performance metrics and survey weighting: [`cvAUC`](https://cran.r-project.org/web/packages/cvAUC/index.html), [`pROC`](https://cran.r-project.org/web/packages/pROC/index.html), [`survey`](https://cran.r-project.org/web/packages/survey/index.html), [`DescTools`](https://cran.r-project.org/web/packages/DescTools/index.html), and [`WeightedROC`](https://cran.r-project.org/web/packages/WeightedROC/index.html)

## Data
- Nonalcoholic Steatohepatitis Clinical Research Network Cohort<sup>[1](#myfootnote1)</sup> (**NASH-CRN**; training set)
- Farnesoid X Receptor (FXR) Ligand Obeticholic Acid in NASH Treatment trial<sup>[2](#myfootnote2)</sup> (**FLINT**; testing set 1)
- National Health and Nutrition Examination Survey NAFLD Cohort<sup>[3](#myfootnote3)</sup> (**NHANES-NAFLD**; testing set 2)

---

<a name="myfootnote1">1</a>. Harrison SA, Oliver D, Arnold HL, Gogia S, Neuschwander-Tetri BA. Development and validation of a simple NAFLD clinical scoring system for identifying patients without advanced disease. Gut. 2008;57(10):1441-1447. doi:10.1136/gut.2007.146019

<a name="myfootnote2">2</a>. Neuschwander-Tetri BA, Loomba R, Sanyal AJ, et al. Farnesoid X nuclear receptor ligand obeticholic acid for non-cirrhotic, non-alcoholic steatohepatitis (FLINT): a multicentre, randomised, placebo-controlled trial. Lancet. 2015;385(9972):956-965. 

<a name="myfootnote3">3</a>. National Center for Health Statistics. About the National Health and Nutrition Examination Survey. Accessed October 17, 2021. [https://www.cdc.gov/nchs/nhanes/about\_nhanes.htm](https://www.cdc.gov/nchs/nhanes/about\_nhanes.htm)
