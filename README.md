# Social Media Use and Student Well-Being

**An accessible data story exploring social media use, problematic use, and well-being among first-year university students.**

## Project Summary

How is social media use related to student well-being?

Using data from 158 first-year university students, this project explores the relationship between reported social media use frequency, problematic social media use, and three aspects of well-being: depression, anxiety, and loneliness.

The findings tell a more nuanced story than the idea that spending more time on social media is always worse. Students in higher-frequency use groups generally reported higher problematic-use scores, although the pattern was not perfectly consistent across all groups. Problematic social media use was modestly associated with depression and anxiety scores, while no evidence of a linear association with loneliness was found.

These findings highlight the importance of distinguishing time spent on social media from problematic patterns of use and considering different aspects of well-being separately.

## Key Findings

* **Social media use:** Students reported a range of daily social media use frequencies.
* **Frequency and problematic use:** Problematic-use scores differed across the five reported frequency groups (Kruskal–Wallis test: χ²(4) = 11.97, *p* = .018).
* **Depression:** Problematic-use scores showed a modest positive association with depression scores (*r* = .233, *p* = .003).
* **Anxiety:** A modest positive association was also observed with anxiety scores (*r* = .208, *p* = .009).
* **Loneliness:** No evidence of a linear association was found (*r* = .035, *p* = .671).

These are observational associations, not evidence that social media use causes changes in mental health.

## Visualizations

The story includes six figures across the two versions:

1. Distribution of reported social media use frequency.
2. Problematic-use scores across frequency groups.
3. Associations between problematic use and depression, anxiety, and loneliness.
4. An accessible view of social media use frequency.
5. A reader-friendly comparison of problematic-use scores.
6. An accessible visualization of well-being associations.

The visualizations use counts, boxplots, individual observations, and fitted linear trends with 95% confidence bands.

## Data Source

The analysis uses the dataset *Social Media use on 1st-year Students' Experiences and Well-being*, attributed to the University of Liverpool.

* **Dataset:** [View the dataset on Zenodo](https://doi.org/10.5281/zenodo.13759037)
* **Sample size:** 158 first-year university students
* **Variables of interest:** Reported social media use frequency, problematic social media use, depression, anxiety, and loneliness

## Methods

* Descriptive statistics to summarize reported social media use.
* Kruskal–Wallis test to examine differences in problematic-use scores across five frequency groups.
* Pearson correlations to assess linear associations between problematic-use scores and each well-being measure.
* Data visualizations to communicate patterns and uncertainty.

## Limitations

The data are observational and self-reported. The findings do not establish causal relationships and may not generalize to all university students. Four observations were missing from the loneliness analysis, which therefore included 154 students; depression and anxiety analyses included 158 students.

The reported frequency categories are treated as ordered groups rather than exact, equally spaced measures of time.

## Technologies

* R
* Quarto
* ggplot2
* haven
* HTML

## Author

**Marjan Nikbakhtzadeh**
