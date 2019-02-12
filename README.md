# SNAP2_Org_Survey

This repository contains code used in the analysis and to produce the manuscript for **1. Wong DJN, Popham S, Wilson AM, Barneto LM, Lindsay HA, Farmer L, et al.** [Postoperative critical care and high-acuity care provision in the United Kingdom, Australia, and New Zealand](http://www.sciencedirect.com/science/article/pii/S000709121930011X). *British Journal of Anaesthesia.* 2019 Feb 8 (in press).

## Explanation

The manuscript was written in [R Markdown](https://rmarkdown.rstudio.com/articles_intro.html)<sup>[1](#myfootnote1)</sup> and is contained within the file `Org_Survey_Manuscript.Rmd`. You may fork this repository and reproduce the entire manuscript on your own computer, provided you have the correct `R` packages installed<sup>[1](#myfootnote2)</sup>. Data for the analyses are included in the `data/` subdirectory. References are included as a `.bib` file along with a citation style file for the BJA in the `references/` subdirectory. 

The `.html` version of the rendered manuscript is included here (`Org_Survey_Manuscript.html`). To view the rendered manuscript in `.html`, you may need to download the raw file onto your computer and open it in your browser as GitHub may not display it automatically.

---

<a name="myfootnote1"><sup>1</sup></a>: Other examples of manuscripts produced using R Markdown can be found [here](http://dannyjnwong.github.io/Producing-a-manuscript-for-journal-publication-in-R-Markdown/), [here](http://dannyjnwong.github.io/Predicting-Postop-Morbidity-Elective-Surgical-Patients-using-SORT/), and [here](https://github.com/dannyjnwong/SNAP2_Cancellations).

<a name="myfootnote2"><sup>1</sup></a>: The following packages were used: `sjlabelled_1.0.13`, `bindrcpp_0.2.2`, `sjPlot_2.6.0`, `pander_0.6.2`, `labelled_1.1.0`, `tableone_0.9.3`, `forcats_0.3.0`, `stringr_1.3.1`, `dplyr_0.7.6`, `purrr_0.2.5`, `readr_1.1.1`, `tidyr_0.8.1`, `tibble_1.4.2`, `ggplot2_3.0.0`, `tidyverse_1.2.1`, in addition to base R.
