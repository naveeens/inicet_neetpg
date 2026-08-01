# Biostatistics Measures Tests of Significance

## Types of Data
| Type | Subtype | Example | Central Tendency |
|---|---|---|---|
| Qualitative (categorical) | Nominal | Blood group, sex | Mode |
| Qualitative (categorical) | Ordinal | Mild/moderate/severe | Median |
| Quantitative (numerical) | Discrete | No. of children | Mean/Median |
| Quantitative (numerical) | Continuous | Height, BP, Hb | Mean |

## Measures of Central Tendency
- **Mean** — arithmetic average; affected by outliers/skew; used for symmetric (normal) data
- **Median** — middle value of ranked data; preferred for **skewed** data (e.g., income, hospital stay); not affected by extreme values
- **Mode** — most frequent value; only measure usable for nominal data

*High-yield: For skewed distributions, Mean ≠ Median ≠ Mode. Positively (right) skewed → Mean > Median > Mode.*

## Measures of Dispersion
| Measure | Formula/Notes |
|---|---|
| Range | Max − Min |
| Standard Deviation (SD) | √[Σ(x − x̄)²/n] — spread of **individual observations** around mean |
| Variance | SD² |
| Standard Error of Mean (SEM) | SD/√n — spread of **sample means** around true population mean; used for CI of mean |
| Coefficient of Variation | (SD/Mean) × 100 — compares variability between datasets with different units/means |

*High-yield distinction: SD describes the data; SEM describes the precision of the estimate (mean) and shrinks as sample size increases.*

## Normal Distribution
- Mean = Median = Mode; symmetric bell curve
- Mean ± 1 SD → ~68% of observations
- Mean ± 2 SD → ~95% of observations
- Mean ± 3 SD → ~99.7% of observations
- 95% Confidence Interval of mean = Mean ± 1.96 × SEM

## Correlation and Regression
- **Correlation coefficient (r)**: ranges −1 to +1; strength/direction of linear association between two continuous variables; does NOT imply causation
- r = 0 → no linear correlation; r closer to ±1 → stronger association
- **Regression**: predicts value of one variable (dependent) from another (independent); used for prediction, not just association

## Tests of Significance — Choosing the Right Test
| Test | Used For | Data Type |
|---|---|---|
| Student's **t-test** (unpaired) | Comparing means of 2 independent groups | Quantitative, normal distribution |
| Paired t-test | Comparing means of same group before/after | Quantitative, normal distribution |
| **Chi-square (χ²) test** | Association between 2 categorical variables | Qualitative/categorical |
| **ANOVA** (F-test) | Comparing means of ≥3 groups | Quantitative, normal distribution |
| **Z-test** | Comparing means/proportions with large samples (n>30), known population SD | Quantitative or proportions |
| Fisher's exact test | Association in 2×2 table when expected cell frequency <5 | Categorical, small samples |
| Wilcoxon/Mann-Whitney U | Non-parametric alternative to t-test | Non-normal/ordinal data |
| Kruskal-Wallis | Non-parametric alternative to ANOVA | Non-normal, ≥3 groups |

*High-yield: Chi-square requires expected frequency ≥5 in each cell; if not met, use Fisher's exact test.*

## p-value and Hypothesis Testing
- **Null hypothesis (H0)**: no difference/association exists between groups/variables
- **p-value** = probability of observing the result (or one more extreme) if H0 is true
- **p < 0.05** conventionally taken as statistically significant → reject H0
- p-value does NOT quantify effect size or clinical importance — only statistical significance

## Type I and Type II Errors
| Error | Definition | Related to |
|---|---|---|
| Type I (α error) | Rejecting a true H0 (false positive) | Level of significance (usually 0.05) |
| Type II (β error) | Accepting a false H0 (false negative) | Power of study (1 − β) |

- **Power of study** = 1 − β; probability of correctly detecting a true effect when it exists; conventionally set ≥80%
- Increasing sample size → decreases Type II error → increases power

## Confidence Interval (CI)
- 95% CI = Estimate ± (1.96 × SE) — range within which the true population value lies with 95% confidence
- Narrower CI = more precise estimate (usually from larger sample size)
- If the CI for a difference/ratio (e.g., RR, OR) includes the null value (1 for ratios, 0 for differences) → result is not statistically significant

## Sample Size Determination
Depends on: expected effect size, desired power, level of significance (α), expected variability (SD) or prevalence.
- Smaller effect size to detect → larger sample size needed
- Higher precision (narrower CI) required → larger sample size needed
- Higher desired power → larger sample size needed

## High-Yield One-Liners
- Median is the best measure of central tendency for skewed data
- SD measures individual variability; SEM measures precision of the mean estimate
- Chi-square test needs expected cell frequency ≥5; use Fisher's exact test otherwise
- p<0.05 = statistically significant by convention; does not equal clinical significance
- Type I error (α) = false positive; Type II error (β) = false negative; Power = 1−β
- Paired t-test for before-after comparisons in the same subjects; unpaired t-test for two independent groups
- Chi-square test compares proportions/categorical data across groups
- ANOVA compares means across three or more groups
- Correlation shows association, not causation
