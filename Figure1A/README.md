# Duckweed Surface Coverage Analysis

This repository contains the R code and dataset used to generate **Figure 1A** in the manuscript:

> **Sara Nouere**  
> _"Duckweed surface coverage under herbivory and control treatments"_  
> Submitted to **PNAS**, 2025

---

## Contents

- `duckweed_coverage.Rmd` — R Markdown file for data analysis and plot generation  
- `duckweedcoverage.txt` — Tab-separated file with duckweed surface coverage data

---

##  What This Code Does

The R Markdown script:

- Loads experimental data on duckweed surface coverage
- Summarizes coverage by treatment and timepoint
- Generates a time-series plot with treatment comparisons (Figure 1A)
- Performs linear mixed-effects models to assess treatment effects across early and late timepoints

---

## How to Reproduce Figure 1A

To run the analysis and generate the figure:

1. Open `duckweed_coverage.Rmd` in **RStudio**
2. Install required packages (if not already installed):

   ```r
   install.packages(c("dplyr", "ggplot2", "car", "plotrix"))
   install.packages("lme4")
