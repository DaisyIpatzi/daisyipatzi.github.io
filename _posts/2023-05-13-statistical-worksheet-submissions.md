---
title: 'Statistical Worksheet Submissions'
date: 2023-05-13 00:00:00
description: 'Exploring the ethical challenges faced by a statistical programmer analyzing the nutritional data of a new cereal, "Whizzz".'
featured_image: '/images/demo/nutrition.jpeg'
---

# Statistical Worksheet Submissions

This chapter consolidates the Statistical Worksheet Submissions from Units 6, 7, 8 and 9. Each section presents the results, analyses, and links to download the relevant Excel files.

##  Quantitative Methods - Descriptive and Inferential Statistics

**Exercise 6.1.** See the below results, where the sample standard deviation of the weight loss for Diet A is s = 2.536 kg. Since the mean weight loss is a little larger than 2s, then a high proportion of those individuals on Diet A had a positive weight loss, again emphasising the effectiveness of the diet. Briefly interpret your findings. What do these results tell you about the relative effectiveness of the two weight-reducing diets?

| Metric | Diet A  | Diet B  |
|--------|---------|---------|
| n      | 50      | 50      |
| Mean   | 5.341   | 3.710   |
| SD     | 2.536   | 2.769   |

**Analysis**

**Mean Weight Loss**: Diet A has a higher mean weight loss (5.341 kg) compared to Diet B (3.710 kg), indicating that, on average, individuals on Diet A lost more weight than those on Diet B.

**Standard Deviation**: The standard deviations are somewhat close, with Diet A at 2.536 kg and Diet B at 2.769 kg. This indicates that the weight loss results for both diets are spread around the mean in a similar manner, although Diet B's results are slightly more variable.

**Effectiveness of the Diets**: Given the higher average weight loss in Diet A, it can be considered more effective for weight loss compared to Diet B based on this sample. The consistency (as measured by the standard deviation) is similar for both diets, suggesting that the primary difference lies in the average effectiveness rather than in the variability of the results.

**Conclusion**

Diet A appears to be more effective than Diet B in terms of average weight loss achieved by the participants. The analysis suggests that individuals looking to lose more weight might prefer Diet A over Diet B, based on the data provided.

[Exa 8.1B](https://github.com/DaisyIpatzi/daisyipatzi.github.io/raw/main/assets/RM_Artifacts/Exa%208.1B.xlsx)

**Exercise 6.2.** Obtain the sample median, first and third quartiles and the sample interquartile range of the weight loss for Diet B. Place these results in the block of cells F26 to F29, using the same format as that employed for the Diet A results in the above example. Briefly interpret your findings. What do these results tell you about the relative effectiveness of the two weight-reducing diets?

| Metric  | Diet A  | Diet B  |
|---------|---------|---------|
| n       | 50      | 50      |
| Mean    | 5.341   | 3.71    |
| SD      | 2.536   | 2.769   |
| Median  | 5.642   | 3.745   |
| Q1      | 3.748   | 2.695   |
| Q3      | 7.033   | 5.404   |
| IQR     | 3.285   | 2.708   |

**Analysis**

**Central Tendency and Dispersion**:
* Diet A has both a higher mean and median weight loss compared to Diet B, suggesting it is more effective on average and at the median level. The median being higher than the mean also hints at a slightly skewed distribution, possibly with a few lower outliers pulling the mean down.
* The standard deviations are similar, indicating a similar spread around the mean for both diets.

**Quartile Analysis**:
* The first quartile for Diet A is higher than that of Diet B, which means that even the lower 25% of participants on Diet A lost more weight compared to the lower 25% on Diet B.
* The third quartile for Diet A is significantly higher than that for Diet B, indicating that the top 25% of participants on Diet A lost substantially more weight.

**Interquartile Range (IQR)**:
* Diet A’s IQR is wider than that of Diet B, suggesting more variability in the middle 50% of the data. This could mean that while Diet A works very well for some, it may not be as effective for others, compared to the more consistent results seen with Diet B.

**Conclusion**

Diet A seems to be more effective overall in terms of median and mean weight loss, and the top 25% of individuals on this diet experienced significantly better outcomes. However, the broader IQR indicates that the effectiveness of Diet A might vary more among its users compared to Diet B, which shows a smaller IQR suggesting a tighter grouping of results around the median.
Overall, Diet A might be the preferable choice for those aiming for higher weight loss, whereas Diet B could be considered by those seeking more consistent, albeit slightly lower, results.

[Exa 8.2B](https://github.com/DaisyIpatzi/daisyipatzi.github.io/raw/main/assets/RM_Artifacts/Exa%208.2B.xlsx)

**Exercise 6.3.** Obtain the frequencies and percentage frequencies of the variable Brand, but this time for the Area 2 respondents, using the same format as that employed for the Area1 results in the above example. Briefly interpret your findings. What do these results tell you about the patterns of brand preferences for each of the two demographic areas?

**Frequencies**

| Category | Area 1 | Area 2 |
|----------|--------|--------|
| A        | 11     | 19     |
| B        | 17     | 30     |
| Other    | 42     | 41     |
| Total    | 70     | 90     |

**Percentages**

| Category | Area 1 | Area 2 |
|----------|--------|--------|
| A        | 15.7   | 21.1   |
| B        | 24.3   | 33.3   |
| Other    | 60.0   | 45.6   |
| Total    | 100.0  | 100.0  |

**Analysis**

**Brand A**: More popular in Area 1 in relative terms (60.0%) compared to Area 2 (21.1%). This suggests that Brand A has a significantly stronger market presence or preference in Area 1.
**Brand B**: More popular in Area 2, capturing a higher share of the total (33.3%) compared to Area 1 (24.3%). This indicates that Brand B is more favored in Area 2.
Other Brands: In Area 1, 'Other' brands dominate the preferences with 60.0% of respondents choosing brands outside of A and B. This suggests a diverse market with no single brand dominating. In Area 2, while still significant, the preference for 'Other' brands is slightly less (45.6%) compared to Area 1.

**Conclusion**

The patterns in brand preference between Area 1 and Area 2 are distinctly different. Area 1 shows a high inclination towards 'Other' brands, indicating a diverse or fragmented market. Brand A, despite a smaller overall frequency, enjoys a relatively higher preference among those who chose among A, B, and Other. In contrast, Area 2 shows a more evenly distributed preference between the major brands and 'Other' brands, with a stronger presence of Brand B.

This indicates that marketing strategies and brand positioning might need to be tailored differently for each area, taking into account the local consumer preferences and competitive landscape.

[Exa 8.3D](https://github.com/DaisyIpatzi/daisyipatzi.github.io/raw/main/assets/RM_Artifacts/Exa%208.3D.xlsx)

##  Hypothesis Testing

### The Related Samples t-test

**Example 7.1.** Consider the container design data in Data Set F. Notice that the two variables Con1 and Con 2 indeed measure the same characteristic (the number of items sold), but under two different “conditions” (the two different container designs). We conduct a two-tailed related samples t test of whether the underlying (population) mean number of items sold differs between the two container designs. 

The resulting output is presented below.
Not all this output is relevant, so it need not all be discussed. 
The obtained related samples t = 2.875 with 9 degrees of freedom.
The associated two-tailed p-value is p = 0.018, so the observed t is significant at the 5% level (two-tailed).

|                         | Con1    | Con2    |
|-------------------------|---------|---------|
| Mean                    | 172.6   | 159.4   |
| Variance                | 750.2666667 | 789.3777778 |
| Observations            | 10      | 10      |
| Pearson Correlation     | 0.863335004 |         |
| Hypothesized Mean Difference | 0 |         |
| df                      | 9       |         |
| t Stat                  | 2.874702125 |         |
| P(T<=t) one-tail        | 0.009167817 |         |
| t Critical one-tail     | 1.833112933 |         |
| P(T<=t) two-tail        | 0.018335635 |         |
| t Critical two-tail     | 2.262157163 |         |
| **Difference in Means** | **13.2** |         |

The data therefore constitute strong evidence (on a one-tailed test) that the underlying mean number of containers sold was greater for Design 1, by an estimated 172.6 - 159.4 = 13.2 items per store. The results continue to suggest that Design 1 should be preferred. Although broadly similar conclusions were reached as before, a higher level of significance was obtained with the one-tailed test. 
Notice that if we had sought to test the alternative pair of one-tailed hypotheses **H₀: μ₁ ≥ μ₂ against H₁: μ₁ < μ₂** we would have found the difference in sample means to be consistent with the null hypothesis that the population mean sales for Design 2 was no greater than that for Design 1. We would thus have declared the result to be not significant without even bothering to inspect the p-value.

**Exercise 7.1.** Recall that in the previous unit exercises, a two-tailed test was undertaken whether the population
mean impurity differed between the two filtration agents in Data Set G. Suppose instead a one-tailed test had been conducted to determine whether Filter Agent 1 was the more effective. What would your conclusions have been?

