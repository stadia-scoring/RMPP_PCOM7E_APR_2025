# Unit 8 – Inference: Exercise 8.4 – Paired Samples t-Test

**Dataset Used:** Data Set G – `Filtration.xlsx` (from 7 Data Annexe)

---

## Problem Context:
This study tests the effectiveness of two filtration agents (Agent1 and Agent2) in reducing impurities. Each of **12 batches** of material was split and treated with both agents. Since each batch is tested under both conditions, the data is **paired**.

---

## Step 1: State the Hypotheses

- **Null Hypothesis (H₀):** There is no difference in mean impurity levels between Agent1 and Agent2.  
  \( H_0: \mu_D = 0 \)

- **Alternative Hypothesis (H₁):** There is a difference in mean impurity levels between Agent1 and Agent2.  
  \( H_1: \mu_D \ne 0 \)

---

## Step 2: Summary Statistics

| Metric                          | Value         |
|---------------------------------|---------------|
| Sample Size (n)                | 12            |
| Mean Difference (Agent1 - Agent2) | -0.433        |
| Standard Deviation of Differences | 0.460        |

---

## Step 3: t-Test Results

| Test Statistic  | Value   |
|------------------|---------|
| t-statistic      | -3.264  |
| p-value          | 0.0075  |
| Significance Level (α) | 0.05 |

---

## Step 4: Decision

Since the **p-value (0.0075)** is **less than 0.05**, we **reject the null hypothesis**.

---

## Interpretation

There is strong evidence that **Agent1 and Agent2 differ** in their ability to reduce impurities. The **negative mean difference** suggests that **Agent2 is more effective**, as impurity levels were lower compared to Agent1 for most batches.

---

**Conclusion:**  
> This paired t-test confirms that the choice of filtration agent has a statistically significant effect. Further testing may be warranted to explore consistency across larger sample sizes.
