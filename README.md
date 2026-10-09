# Social Media Use and Student Well-Being

**An accessible data story exploring social media use, problematic social media use, and well-being among first-year university students.**

## Project Overview

How is social media use related to student well-being?

This project explores data from 158 first-year university students to examine reported social media use frequency, problematic social media use, and three aspects of well-being: depression, anxiety, and loneliness.

The findings suggest that the relationship between social media use and well-being is more nuanced than the idea that spending more time on social media is always worse. Problematic social media use was modestly associated with depression and anxiety, while no statistically significant linear association was found with loneliness.

These are observational findings and do not establish cause-and-effect relationships.

## Story Summary

Social media is an important part of university students’ daily lives, but its relationship with well-being is complex. This project explores social media use among students, focusing on how usage frequency relates to problematic social media use and different aspects of psychological well-being.

The visualizations highlight three key questions: How frequently do students use social media? Does problematic social media use differ across usage-frequency groups? And how is social media use associated with well-being measures such as depression, anxiety, and loneliness?

The findings suggest that more frequent social media use is associated with differences in problematic use, while its relationships with well-being vary across measures. These patterns highlight why social media use and student well-being should be considered from multiple perspectives.

## Key Findings

* **Frequency and problematic use:** Problematic-use scores differed across the five reported frequency groups (Kruskal–Wallis test: χ²(4) = 11.97, *p* = .018).
* **Depression:** A modest positive association was found between problematic-use and depression scores (*r* = .233, *p* = .003).
* **Anxiety:** A modest positive association was found between problematic-use and anxiety scores (*r* = .208, *p* = .009).
* **Loneliness:** No statistically significant linear association was found (*r* = .035, *p* = .671).

## Visualizations

### 1. Social Media Use Frequency

![Social media use frequency](figures/social_media_frequency_accessible.png)

Students reported a range of social media use frequencies. The chart shows the number of students in each reported category.

### 2. Problematic Social Media Use

![Problematic social media use](figures/problematic_use_accessible.png)

Students in higher reported-use categories generally had higher problematic-use scores, although the pattern was not identical across every group.

### 3. Social Media Use and Well-Being

![Social media use and well-being](figures/wellbeing_accessible.png)

Problematic social media use was modestly associated with depression and anxiety scores. No statistically significant linear association was found with loneliness. These associations do not establish causation.

## Data Source

University of Liverpool, *Social Media use on 1st-year Students' Experiences and Well-being*.

[View the dataset on Zenodo](https://doi.org/10.5281/zenodo.13759037)

* **Sample size:** 158 first-year university students.
* **Variables:** Reported social media use frequency, problematic social media use, depression, anxiety, and loneliness.

## Methods

* Descriptive statistics to summarize reported social media use.
* Kruskal–Wallis test to examine differences in problematic-use scores across five frequency groups.
* Pearson correlations to examine linear associations between problematic-use scores and well-being measures.
* Data visualization using R, ggplot2, and Quarto.

## Limitations

The data are observational and self-reported. The findings do not establish causal relationships and may not generalize to all university students.

Four observations were missing from the loneliness analysis, which included 154 students; depression and anxiety analyses included 158 students.

The reported frequency categories were treated as ordered groups rather than exact, equally spaced measures of time.

## Technologies

* R
* Quarto
* ggplot2
* haven
* Git and GitHub
* HTML

## Author

**Marjan Nikbakhtzadeh**
