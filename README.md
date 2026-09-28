# PISA 2006: Gender Differences in Reading, Mathematics, and Science in Japan and Korea

## General Information

### Project Title

PISA 2006: Gender Differences in Reading, Mathematics, and Science in Japan and Korea

### Researcher

Donger Chen

### ORCID

https://orcid.org/0009-0006-8215-5576

### Project Description

This project uses data from the OECD Programme for International Student Assessment (PISA) 2006 to compare the academic performance of 15-year-old students in Japan and Korea.

The analysis focuses on three subject areas: reading, mathematics, and science. For each subject, the project examines the overall average score as well as the average scores for female and male students.

The purpose of the project is to document a small educational dataset in a transparent and reproducible way and to examine how gender differences vary across subjects and between the two countries.

### Research Questions

1. How do average PISA 2006 scores in reading, mathematics, and science differ between Japan and Korea?

2. How do female and male students perform in each subject in Japan and Korea?

3. How does the gender gap differ across reading, mathematics, and science?

---

## Data Source

The data were obtained from the OECD PISA International Data Explorer.

Data source:

OECD Programme for International Student Assessment (PISA)

Assessment year:

2006

Population:

15-year-old students

Countries:

Japan and Korea

Subjects:

- Reading
- Mathematics
- Science

Grouping variable:

Student gender

Statistics:

- Average score
- Standard error

---

## Data Collection Procedure

The data were retrieved using the OECD PISA International Data Explorer.

The following procedure was used:

1. Open the PISA International Data Explorer.
2. Select the 2006 PISA assessment.
3. Select 15-year-old students.
4. Select Japan and Korea as the jurisdictions.
5. Select reading, mathematics, and science.
6. Create one report for all students.
7. Create a second report using Student (Standardized) Gender as the grouping variable.
8. Select average score as the statistic.
9. Generate the reports.
10. Record the average score and standard error for each country, subject, and gender group.

This procedure was applied consistently across the three subjects.

---

## Dataset Overview

The dataset contains summary statistics from PISA 2006.

Each observation represents a combination of:

- assessment year
- country
- subject
- student group

The dataset includes the mean PISA score and its corresponding standard error.

---

## File Overview

This repository contains the following files:

- `README.md` — Provides the project metadata, research context, methodology, data dictionary, access information, and documentation.
- `pisa_2006_japan_korea.csv` — Contains the summary dataset used in this project, including mean scores and standard errors for Japan and Korea across reading, mathematics, and science.
- `pisa_2006_source_report.pdf` — Contains the original reports exported from the OECD PISA International Data Explorer, including overall and gender-grouped results for all three subject areas.

---

## Data

| Subject | Country | Group | Mean Score | Standard Error |
|---|---|---|---:|---:|
| Science | Japan | Overall | 531 | 3.4 |
| Science | Japan | Female | 530 | 5.1 |
| Science | Japan | Male | 533 | 4.9 |
| Science | Korea | Overall | 522 | 3.4 |
| Science | Korea | Female | 523 | 3.9 |
| Science | Korea | Male | 521 | 4.8 |
| Reading | Japan | Overall | 498 | 3.6 |
| Reading | Japan | Female | 513 | 5.2 |
| Reading | Japan | Male | 483 | 5.4 |
| Reading | Korea | Overall | 556 | 3.8 |
| Reading | Korea | Female | 574 | 4.5 |
| Reading | Korea | Male | 539 | 4.6 |
| Mathematics | Japan | Overall | 523 | 3.3 |
| Mathematics | Japan | Female | 513 | 4.9 |
| Mathematics | Japan | Male | 533 | 4.8 |
| Mathematics | Korea | Overall | 547 | 3.8 |
| Mathematics | Korea | Female | 543 | 4.5 |
| Mathematics | Korea | Male | 552 | 5.3 |

---

## Data Dictionary

| Variable | Type | Description | Example |
|---|---|---|---|
| year | Integer | PISA assessment year | 2006 |
| country | Categorical | Country or jurisdiction included in the analysis | Japan |
| subject | Categorical | PISA assessment domain | Reading |
| group | Categorical | Student group represented by the estimate | Female |
| mean_score | Numeric | Estimated average PISA score | 513 |
| standard_error | Numeric | Standard error associated with the estimated mean score | 5.2 |

### Standard Error

Standard error represents the uncertainty associated with an estimated mean.

A smaller standard error generally indicates a more precise estimate of the population mean.

The standard error should not be interpreted as the variation in individual students' scores.

---

## Derived Variables

A gender gap was calculated for each subject and country.

Gender gap was defined as:

Male mean score - Female mean score

A positive value indicates a higher male average score.

A negative value indicates a higher female average score.

| Subject | Japan Gender Gap | Korea Gender Gap |
|---|---:|---:|
| Science | 3 | -2 |
| Reading | -30 | -35 |
| Mathematics | 20 | 9 |

Country differences were also calculated as:

Korea mean score - Japan mean score

| Subject | Overall Difference | Female Difference | Male Difference |
|---|---:|---:|---:|
| Science | -9 | -7 | -12 |
| Reading | 58 | 61 | 56 |
| Mathematics | 24 | 30 | 19 |

---

## Methodological Information

This project uses descriptive analysis of aggregated PISA estimates.

No individual-level student records were analyzed.

The analysis compares estimated mean scores across countries, subjects, and gender groups.

The results describe patterns in the PISA 2006 data and should not be interpreted as evidence of causal relationships.

The OECD PISA Data Explorer also notes that apparent differences between estimates may not necessarily be statistically significant.

---

## Main Observations

Reading showed the largest gender differences in both countries. Female students had higher average reading scores than male students in both Japan and Korea.

In mathematics, male students had higher average scores in both countries.

Science showed relatively small gender differences compared with reading and mathematics.

The descriptive results also show differences between Japan and Korea across the three subject areas. These comparisons describe the observed estimates and do not by themselves establish statistical significance.

---

## Metadata Standard

### Selected Standard: Data Documentation Initiative (DDI)

The Data Documentation Initiative (DDI) was selected as the metadata standard for this project.

DDI is particularly relevant to social science and educational research data because it supports structured documentation of datasets, variables, methodology, data sources, and access information.

This README is informed by DDI principles but does not implement a complete DDI XML record.

---

## Sharing and Access Information

The source data are publicly available through the OECD PISA International Data Explorer.

PISA International Data Explorer:

https://pisadataexplorer.oecd.org/ide/idepisa/

This repository contains only aggregated results used for this educational analysis and does not contain personally identifiable student information.

---

## Software and Tools

The following tools were used:

- OECD PISA International Data Explorer
- GitHub
- Markdown
- Microsoft Excel or spreadsheet software for organizing and checking calculations
- Make a README as a reference for README structure

---

## Challenges and Reflection

The most challenging part of creating the README was documenting a small dataset that was derived from a much larger international educational database.

It was important to distinguish between the original OECD PISA data and the smaller subset of aggregated results used in this project.

Another challenge was documenting the meaning of standard error and distinguishing the original variables from derived measures such as the gender gap.

These challenges were addressed by recording the exact assessment year, countries, subjects, grouping variables, statistics, and calculation rules used in the PISA Data Explorer.

---

## Reproducibility

Another researcher can reproduce this dataset by:

1. Opening the OECD PISA International Data Explorer.
2. Selecting PISA 2006.
3. Selecting 15-year-old students.
4. Selecting Japan and Korea.
5. Selecting reading, mathematics, and science.
6. Selecting average scores.
7. Generating one report for all students.
8. Generating another report grouped by standardized student gender.
9. Recording the means and standard errors.
10. Calculating gender gaps as male mean minus female mean.

---

## DOI

DOI: https://doi.org/10.5281/zenodo.23021847

---

## Citation

Chen, D. (2026). PISA 2006: Gender Differences in Reading, Mathematics, and Science in Japan and Korea. Zenodo. https://doi.org/10.5281/zenodo.23021847
