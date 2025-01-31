# sharing-motivation
This repository contains code for the analyses reported in the following manuscript:

**[Perceived self and social relevance of content motivates news sharing across cultures and topics]([https://osf.io/preprints/psyarxiv/z8946](https://doi.org/10.1093/pnasnexus/pgaf019))**


## Compiled analysis files

* [Combined analyses](https://cnlab.github.io/sharing-motivation/analysis/combined_analyses)
* [Study 1](https://cnlab.github.io/sharing-motivation/analysis/study1_analyses)
* [Study 1 exploratory analyses](https://cnlab.github.io/sharing-motivation/analysis/study1_analyses_exploratory)
* [Study 2](https://cnlab.github.io/sharing-motivation/analysis/study2_analyses)
* [Study 3](https://cnlab.github.io/sharing-motivation/analysis/study3_analyses)
* [Study 3 alternatively defined ROIs](https://cnlab.github.io/sharing-motivation/analysis/study3_alt_roi_analyses)
* [Study 3 exploratory individual difference analyses](https://cnlab.github.io/sharing-motivation/analysis/study3_analyses_exploratory)
* [Study 3 sensitivity analyses](https://cnlab.github.io/sharing-motivation/analysis/study3_analyses_sensitivity)
* [Study 4](https://cnlab.github.io/sharing-motivation/analysis/study4_analyses)

## Analysis reproduction

To reproduce the analyses in the manuscript, first execute the study cleaning scripts, then the study prep scripts, and finally the analysis scripts. Given that raw data is required to run the cleaning and prep scripts, folks outside the research team will only be able to reproduce the analysis scripts.

## Directory structure

* `analysis` = R code for the analyses reported in the manuscript and supplementary material
* `cleaning` = R code and supporting files for cleaning the data
* `data` = text files containing the data
* `stimuli` = text files containing the newspaper article stimuli

```
├── analysis
│	├── analysis.Rproj
│	├── combined_analyses.Rmd
│	├── combined_analyses.html
│	├── study1_analyses.Rmd
│	├── study1_analyses.html
│	├── study1_analyses_exploratory.Rmd
│	├── study1_analyses_exploratory.html
│	├── study1_demographics.Rmd
│	├── study1_demographics.html
│	├── study2_analyses.Rmd
│	├── study2_analyses.html
│	├── study3_alt_roi_analyses.Rmd
│	├── study3_alt_roi_analyses.html
│	├── study3_analyses.Rmd
│	├── study3_analyses.html
│	├── study3_analyses_exploratory.Rmd
│	├── study3_analyses_exploratory.html
│	├── study3_analyses_sensitivity.Rmd
│	├── study3_analyses_sensitivity.html
│	├── study4_analyses.Rmd
│	├── study4_analyses.html
│	├── study4_demographics.Rmd
│	└── study4_demographics.html
├── cleaning
│	├── state_codes.csv
│	├── study1_analysis_prep.Rmd
│	├── study2_analysis_prep.Rmd
│	├── study3_analysis_prep.Rmd
│	├── study3_analysis_prep_sensitivity.Rmd
│	├── study4_analysis_prep.Rmd
│	└── study4_cleaning.Rmd
├── data
│	├── study1_climate_cause.csv
│	├── study1_data.csv
│	├── study1_exploratory_dvs.csv
│	├── study2_data.csv
│	├── study3_data.csv
│	├── study3_data_sensitivity.csv
│	├── study4_data.csv
│	└── study4_demo.csv
└── stimuli
    └── articles.csv
```
