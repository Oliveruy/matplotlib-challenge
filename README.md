# matplotlib-challenge

## Overview

This repository contains an analysis of pharmaceutical data using matplotlib in a Jupyter notebook. The analysis explores drug regimens, gender distribution, and specific details about the Capomulin treatment.

## Contents

- **data:** This folder contains the two data files used in the analysis.
  - `study_results.csv`: Clinical trial data.
  - `mouse_metadata.csv`: Mouse drug data.

- **matplotlib_challenge.ipynb:** Jupyter notebook containing the code for the analysis.

- **README.md:** Documentation providing an overview of the project, analysis results, and additional information.

## Drug Regimen Analysis

Capomulin and Ramicane have the most number of mouse data per timepoint, suggesting a consistent and complete dataset for these regimens. Capomulin and Ramicane also show promising results in terms of tumor volume reduction.

## Gender Distribution

The gender distribution among the mice is relatively balanced, with 51% male and 49% female.

## Capomulin Specific Analysis

Capomulin demonstrates effectiveness in reducing tumor volume over time. The decline in tumor volume becomes noticeable around the 20th day and continues to decrease between the 30th and 40th day of treatment.

## Correlation Analysis

There is a strong positive correlation (0.84) between mouse weight and the average tumor volume. This indicates that as the weight of mice increases, the average tumor volume tends to increase as well.

### **High-Level Analysis**

- **Capomulin and Ramicane:** These regimens stand out in terms of both the completeness of data and effectiveness in reducing tumor volume. They may be considered as preferred treatment options.
- **Gender Distribution:** The study has a relatively equal distribution of male and female mice, enhancing the generalizability of findings.
- **Capomulin Effectiveness:** The observed decline in tumor volume with Capomulin treatment aligns with its reputation as an effective treatment.
- **Correlation between Weight and Tumor Volume:** The strong positive correlation between mouse weight and average tumor volume suggests that weight may influence tumor development. Further investigation into this relationship could provide insights into potential factors affecting treatment outcomes.

#### **References**

#### Finding rows that have duplicate values:
https://stackoverflow.com/questions/70018198/find-rows-in-dataframe-that-have-duplicates-in-two-columns#:~:text=Use%20pd.DataFrame.duplicated%20%28%29%20df_new%20%3D,df%20%5Bdf.duplicated%20%28subset%3D%20%5B%22col1%22%2C%20%22col2%22%5D%2C%20keep%3DFalse%29%5D

#### Filtering using .isin()
https://www.geeksforgeeks.org/python-pandas-dataframe-isin/

#### Changing the marker color using fliers
https://stackoverflow.com/questions/43342564/flier-colors-in-boxplot-with-matplotlib

#### Using scipy pearsonr
https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.pearsonr.html

#### Linear regression
Followed Data Visualisation Day 3 activity 8 as guide on how to plot linear regression
