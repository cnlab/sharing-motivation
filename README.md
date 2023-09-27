# sharing-motivation
This repository contains code for the analyses reported in the following manuscript:

**Neural and behavioral evidence that message self and social relevance motivate content sharing**


## Compiled analysis files

The main analyses from fMRI study 1 are reported [here](https://cnlab.github.io/sharing-motivation/analysis/study1_analyses) and the supplementary analyses are reported [here](https://cnlab.github.io/sharing-motivation/analysis/study1_supplementary_analyses).

The main analyses from follow-up behavioral study 2 are reported [here](https://cnlab.github.io/sharing-motivation/analysis/study2_analyses) and the supplementary analyses are reported [here](https://cnlab.github.io/sharing-motivation/analysis/study2_supplementary_analyses).

The main analyses from field study 3 are reported [here](https://cnlab.github.io/sharing-motivation/analysis/study3_analyses) and the supplementary analyses are reported [here](https://cnlab.github.io/sharing-motivation/analysis/study3_supplementary_analyses).

## Analysis reproduction
To reproduce the analyses in the manuscript, first execute the study cleaning scripts, then the study prep scripts, and finally the analysis scripts (`study1_analysis.Rmd`, `study2_analysis.Rmd`, `study3_analysis.Rmd`, `study1_supplementary_analyses.Rmd`, `study2_supplementary_analyses.Rmd`, `study3_supplementary_analyses.Rmd`). Given that raw data is required to run the cleaning and prep scripts, folks outside the research team will only be able to reproduce the analysis scripts.

## Directory structure

* `analysis` = R code for the analyses reported in the manuscript and supplementary material
* `cleaning` = R code and supporting files for cleaning the data
* `data` = text files containing the data
* `stimuli` = text files containing the newspaper article stimuli

```
├── analysis
│	├── analysis.Rproj
│	├── indirectMLM.R
│	├── models
│	│	├── model_mediation_other.RDS
│	│	├── model_mediation_other_alternative.RDS
│	│	├── model_mediation_self.RDS
│	│	└── model_mediation_self_alternative.RDS
│   ├── study1_analyses.Rmd
│   ├── study1_analyses.html
│   ├── study1_supplementary_analyses.Rmd
│   ├── study1_supplementary_analyses.html
│   ├── study2_analyses.Rmd
│   ├── study2_analyses.html
│   ├── study2_demographics.Rmd
│   ├── study2_demographics.html
│   ├── study2_supplementary_analyses.Rmd
│   ├── study2_supplementary_analyses.html
│   ├── study3_analyses.Rmd
│   ├── study3_analyses.html
│   ├── study3_supplementary_analyses.Rmd
│   └── study3_supplementary_analyses.html
├── cleaning
│   ├── state_codes.csv
│   ├── study1_analysis_prep.Rmd
│   ├── study2_analysis_prep.Rmd
│   ├── study2_cleaning.Rmd
│   └── study3_analysis_prep.Rmd
├── data
│   ├── study1_data.csv
│   ├── study2_data.csv
│   ├── study2_demo.csv
│   └── study3_data.csv
└── stimuli
    └── articles.csv
```
