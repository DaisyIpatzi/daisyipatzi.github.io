---
title: 'Jaccard Coefficient Calculations'
date: 2023-12-27 13:00:00
description: 'Activity: Jaccard Coefficients | Machine Learning Module'
featured_image: '/images/demo/Jaccard.png'
---

## Jaccard Coefficient Calculations

**Activity**: The table shows the pathological test results for three individuals.

|   Name  | Gender | Fever | Cough | Test-1 | Test-2 | Test-3 | Test-4 |
| ------- | ------ | ----- | ----- | ------ | ------ | ------ | ------ |
|   Jack  |   M    |   Y   |   N   |   P    |   N    |   N    |   A    |
|   Mary  |   F    |   Y   |   N   |   P    |   A    |   P    |   N    |
|   Jim   |   M    |   Y   |   P   |   N    |   N    |   N    |   A    |

Calculate Jaccard coefficient for the following pairs:

- (Jack, Mary)
- (Jack, Jim)
- (Jim, Mary)

**Solution**: The Jaccard coefficient, also known as the Jaccard index or Jaccard similarity coefficient, is a statistic used in clustering and other forms of data analysis to measure the similarity and diversity of sample sets and it is given by:

Jaccard = (f01 + f10) / (f01 + f10 + f11)

-To calculate the Jaccard coefficient, we first convert the asymmetric variables to binary values and re-write the table. Since Gender is a symmetric variable (that is, male, female have the same weight), it is not converted.

-So, let **Y** & **P** = 1; **N** & **A** = 0 Let's recalculate it using the binary values:

-Now, we'll rewrite the table with these binary values:

  |   Name  | Gender | Fever | Cough | Test-1 | Test-2 | Test-3 | Test-4 |
  | ------- | ------ | ----- | ----- | ------ | ------ | ------ | ------ |
  |   Jack  |   M    |   1   |   0   |   1    |   0    |   0    |   0    |
  |   Mary  |   F    |   1   |   0   |   1    |   0    |   1    |   0    |
  |   Jim   |   M    |   1   |   1   |   0    |   0    |   0    |   0    |

**-For (Jack, Mary)**
  
  Jack: (1, 0, 1, 0, 0, 0)
  
  Mary: (1, 0, 1, 0, 1, 0)
  
  **Jaccar**d = (1+0)/(1+0+2)= **0.33**

**-For (Jack, Jim)**
  
  Jack: (1, 0, 1, 0, 0, 0)
  
  Jim:  (1, 1, 0, 0, 0, 0)
  
  **Jaccard** = (1+1)/(1+1+1)= **0.67**

  **-For (Jim, Mary)**
  
  Jim:  (1, 1, 0, 0, 0, 0)
  
  Mary: (1, 0, 1, 0, 1, 0)
  
  **Jaccard** = (2+1)/(2+1+1)= **0.75**


**Conclusions**

-Jack and Mary have a Jaccard coefficient of 0.33, which means that they have a relatively low degree of similarity in their test results. Only 33% of the binary attributes are the same between them.

-Jack and Jim have a Jaccard coefficient of 0.67, indicating a higher degree of similarity compared to Jack and Mary. 67% of their binary attributes match, suggesting a moderate level of similarity.

-Jim and Mary have the highest Jaccard coefficient among the pairs, with a value of 0.75. This suggests a relatively high degree of similarity in their test results, with 75% of their binary attributes being the same.

Note that, in practical applications, a Jaccard coefficient of 1 is often used to represent complete similarity or a perfect match between two sets.
