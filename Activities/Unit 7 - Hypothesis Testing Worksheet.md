## Exercise 7.1 – Paired t-Test on Container Designs

Hypotheses:

- H₀: μ₁ = μ₂ (no difference in mean items sold)
- H₁: μ₁ ≠ μ₂ (difference in mean items sold)

Results:

| Metric                     | Value      |
|-||
| Mean (Con1)                | 172.6      |
| Mean (Con2)                | 159.4      |
| Mean Difference            | 13.2       |
| Paired t-statistic         | 2.875      |
| Two-tailed p-value         | 0.018      |

Interpretation:

There is statistically significant evidence that Design 1 results in more items sold than Design 2.



## Exercise 7.2 – Independent Samples t-Test on Weight Loss

Hypotheses:

- H₀: μ₁ = μ₂ (no difference in mean weight loss)
- H₁: μ₁ ≠ μ₂ (difference in mean weight loss)

Results:

| Metric                     | Value        |
|-|--|
| Mean (Diet A)              | 5.341 kg     |
| Mean (Diet B)              | 3.710 kg     |
| Mean Difference            | 1.631 kg     |
| Variance Test p-value (F)  | 0.540        |
| t-statistic                | 3.072        |
| Two-tailed p-value         | 0.003        |

Interpretation:

There is statistically significant evidence that Diet A leads to greater weight loss than Diet B.



## Exercise 7.3 – Chi-Square Test of Independence

Hypotheses:

- H₀: Brand preference is independent of area
- H₁: Brand preference is associated with area

Observed Frequencies:

| Area | A   | B   | Other |
||--|--|--|
| 1    | 11  | 17  | 42     |
| 2    | 19  | 30  | 41     |

Results:

| Statistic              | Value    |
||-|
| Chi-square statistic   | 3.293    |
| Degrees of freedom     | 2        |
| p-value                | 0.193    |

Interpretation:

There is no significant evidence that brand preference is associated with area.



## Exercise 7.4 – One-Sample t-Test for Diet A

Hypotheses:

- H₀: μ = 4.0 (mean weight loss is 4.0 kg)
- H₁: μ > 4.0 (mean weight loss exceeds 4.0 kg)

Results:

| Metric                  | Value      |
|--||
| Sample Mean              | 5.341 kg   |
| t-statistic              | 3.740      |
| One-tailed p-value       | < 0.001    |

Interpretation:

There is strong evidence that the mean weight loss for Diet A exceeds 4.0 kg.



## Exercise 7.6 – Two-Proportion z-Test (Weight Loss > 4 kg)

Hypotheses:

- H₀: Proportion of success is the same for both diets
- H₁: Proportion of success differs between diets

Results:

| Metric                                 | Diet A     | Diet B     |
|-|||
| Number of Individuals                  | 50         | 50         |
| Number who lost > 4 kg                 | 36         | 22         |
| Proportion who lost > 4 kg             | 0.72       | 0.44       |

| Test Result              | Value    |
|--|-|
| z-statistic              | 2.837    |
| p-value (two-tailed)     | 0.005    |

Interpretation:

There is significant evidence that a greater proportion of Diet A participants lost more than 4 kg compared to Diet B.

