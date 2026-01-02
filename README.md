![University Logo](logo_university.png)

# Applied Statistics: Cybersecurity Attacks Analysis

This repository contains an applied statistics project focused on a descriptive statistical analysis of a cybersecurity attacks dataset.

> **Note:** The analytical report and statistical analysis are written in **Albanian**, while this repository documentation is provided in **English**.

## Contents

The repository includes the following key files:

- **Projekt-Final.pdf** — Final compiled report (PDF)
- **Projekt Final.Rmd** — R Markdown source file used to generate the analysis
- **cybersecurity_attacks.csv** — Dataset used for the statistical analysis
- **logo_university.png** — University logo used on the report cover page

## Main Output

- 📄 **PDF Report:** `Projekt-Final.pdf`

This document contains the full descriptive statistical analysis, visualizations, and interpretations.

## Reproducing the Analysis

### Requirements
- R (version 4.0 or newer)
- RStudio (optional, but recommended)
- LaTeX distribution for PDF generation (TinyTeX recommended)

### Required R packages
```r
install.packages(c("rmarkdown", "knitr", "ggplot2", "dplyr", "janitor"))
```

### Render the report
From the repository root directory, run:

```r
rmarkdown::render("Projekt Final.Rmd")
```

This will regenerate the PDF report locally.

## Author

**Orgito Leka**
