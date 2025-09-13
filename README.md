# Soapbox Science in Kamloops 2024  
Inspiring Curiosity and Connection Through Inclusive STEM Engagement

[![R](https://img.shields.io/badge/R-4.x-276DC3)](https://www.r-project.org/)
[![R Markdown](https://img.shields.io/badge/R%20Markdown-📄-brightgreen)](https://rmarkdown.rstudio.com/)
[![License: MIT (code)](https://img.shields.io/badge/License-MIT-blue.svg)](#license)
[![ggplot2](https://img.shields.io/badge/ggplot2-✓-orange)](https://ggplot2.tidyverse.org/)

---

## Overview

This repository contains the analysis, figures, and reproducible R code for **Soapbox Science Kamloops 2024**, a public-outreach event designed to increase the visibility of women and non-binary scientists and their work. Using survey responses collected at the event, the analysis:

- **Cleans & merges** survey exports.
- **Engineers features** from multi-select items (who “looks like a scientist”) into interpretable binary indicators (age group, ethnicity, gender, dress, expression).
- **Builds respondent-level ethnicity flags** across repeated columns.
- **Summarizes & visualizes** outcomes (bar charts with counts/%, attribute distributions, proportional stacks, alluvial plots).
- **Exports** clean datasets and publication-ready figures.

**Primary questions**
- How do participants perceive *who looks like a scientist* across demographic characteristics?
- Does representation and visibility at a Soapbox event relate to **interest in science** and **STEM career consideration**?

---

## Abstract

This study explores the impact of role models showcased during the Soapbox Science event, a novel public-outreach platform designed to promote women and non-binary scientists and their work. The event aims to challenge traditional gender stereotypes in STEM by bringing science directly into public spaces and increasing the visibility of diverse scientists. Using survey data, the study investigates how participants perceive scientists based on demographic characteristics such as gender and ethnicity and examines the role of representation in shaping these perceptions.

The findings reveal that while participants often identified scientists based on their own demographic characteristics, this trend was influenced by the overrepresentation of white and female respondents in the sample. In particular, white respondents predominantly identified scientists as white, but also recognized other ethnic groups- such as Black and Asian scientists -to a lesser extent. Similarly, women in the survey universally identified both male and female scientists, suggesting inclusivity rather than bias.

Furthermore, the study highlights the positive impact of the event in inspiring participants, with most reporting increased interest in science and research after interacting with visible and relatable role models. These results underscore the value of platforms like Soapbox Science in fostering public engagement, challenging stereotypes, and promoting diversity in STEM. The insights contribute to the growing understanding of the importance of representation in enhancing accessibility and inclusivity within the scientific community.

---

## Key Findings (Descriptive)

- **Science improves lives:** ~**93.3%** agreement.
- **Confidence with the scientific method:** ~**63.3%** agree (with variability across levels).
- **Considering a STEM career:** ~**43.3%** strong motivation; others mixed.
- **Inspired by women & non-binary scientists:** ~**93.3%**.
- **Interest increased by event:** ~**70%** reported increased interest.
- **Demographics:** Majority aged **21–50**, gender split **~60% women**, **~33% men**, small non-binary/prefer-not-to-say groups; education varied (largest: undergrad/grad).

> ⚠️ Small sample (≈30). Results are descriptive and should be interpreted cautiously.

---

## Repository Structure

```text
soapbox-kamloops-2024/
├── README.md
├── analysis/
│   └── Soapbox_2024_Kamloops.Rmd   # main reproducible document (title: "Soapbox event Kamloops 2024")
├── data/
│   ├── raw/
│   │   └── Soapbox Science Community Outreach Impact_34observations.xlsx
│   └── processed/
│       ├── final_data_cleaned.xlsx
│       ├── soapbox_data_categorised.xlsx
│       └── Categorical_Variables_Summary.csv
├── figures/
│   ├── Improves_Lives_plot.png
│   ├── Gender_plot.png
│   ├── Educational_Background_plot.png
│   ├── Scientist_Attributes_Distribution_Horizontal.png
│   ├── Ethnicity_Distribution_Horizontal.jpg
│   ├── proportional_distribution_by_ethnicity.png
│   └── enhanced_alluvial_plot.png
└── .gitignore

