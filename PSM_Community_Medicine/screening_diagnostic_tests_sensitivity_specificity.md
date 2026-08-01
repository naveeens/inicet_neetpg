# Screening Diagnostic Tests Sensitivity Specificity

## The 2×2 Table
| | Disease Present | Disease Absent |
|---|---|---|
| **Test Positive** | a (True Positive) | b (False Positive) |
| **Test Negative** | c (False Negative) | d (True Negative) |

## Key Formulas
| Measure | Formula | Meaning |
|---|---|---|
| **Sensitivity** | a/(a+c) | Ability of test to correctly identify those **with** disease; % of true positives among all diseased |
| **Specificity** | d/(b+d) | Ability of test to correctly identify those **without** disease; % of true negatives among all non-diseased |
| **Positive Predictive Value (PPV)** | a/(a+b) | Probability that a person testing positive actually has the disease |
| **Negative Predictive Value (NPV)** | d/(c+d) | Probability that a person testing negative is actually disease-free |
| **Accuracy** | (a+d)/(a+b+c+d) | Overall proportion correctly classified |
| **False Positive Rate** | b/(b+d) = 1 − Specificity | |
| **False Negative Rate** | c/(a+c) = 1 − Sensitivity | |

*High-yield: Sensitivity & specificity are intrinsic properties of the test — do NOT change with disease prevalence. PPV & NPV DO change with prevalence.*

## Effect of Prevalence on Predictive Values
- ↑ Prevalence → ↑ PPV, ↓ NPV (in a high-prevalence population, a positive test is more likely to be a true positive)
- ↓ Prevalence → ↓ PPV, ↑ NPV (in screening low-prevalence populations, most positives are false positives — a key reason for confirmatory/second-tier testing)

## Choosing Tests — Screening vs Confirmatory
| Purpose | Test Property Needed | Rationale |
|---|---|---|
| **Screening test** | High **Sensitivity** | Must not miss true cases (minimize false negatives); acceptable to have some false positives, confirmed later |
| **Confirmatory/diagnostic test** | High **Specificity** | Must correctly rule out disease-free (minimize false positives) before committing to treatment/label |

*Mnemonic: SP-IN — a highly SPecific test, when positive, rules IN disease. SN-OUT — a highly SeNsitive test, when negative, rules OUT disease.*

## Likelihood Ratios
| Measure | Formula | Interpretation |
|---|---|---|
| Positive LR (LR+) | Sensitivity/(1−Specificity) | LR+ >10 → strong evidence to rule in disease if positive |
| Negative LR (LR−) | (1−Sensitivity)/Specificity | LR− <0.1 → strong evidence to rule out disease if negative |

- LR is independent of prevalence (advantage over PPV/NPV) and combines with pre-test odds → post-test odds (Bayes' theorem)

## Criteria for a Good Screening Test/Program (WHO — Wilson & Jungner principles, adapted)
- Disease should be an important health problem
- Recognizable latent/early symptomatic stage
- Natural history of disease should be understood
- Effective, acceptable treatment available for disease detected early
- Suitable test — simple, safe, acceptable to population, high sensitivity & specificity
- Facilities for diagnosis and treatment available
- Agreed policy on whom to treat
- Cost of screening should be economically balanced against benefit
- Screening should be a continuing process, not a one-time project

## Validity vs Reliability
- **Validity**: how well a test measures what it intends to measure (sensitivity, specificity, accuracy)
- **Reliability (precision)**: reproducibility/consistency of results on repeat testing (intra-observer, inter-observer, test-retest)
- A test can be reliable but not valid (consistently wrong); validity requires reliability but not vice versa

## Bias Specific to Screening Programs
| Bias | Description |
|---|---|
| Lead-time bias | Early detection appears to prolong survival, but only shifts diagnosis earlier without changing actual disease course/mortality |
| Length-time bias | Screening preferentially detects slow-growing (less aggressive) disease that has a longer detectable pre-clinical phase, inflating apparent survival benefit |
| Selection/volunteer bias | Health-conscious individuals more likely to volunteer for screening, biasing outcomes favorably |

## Types of Screening
| Type | Description | Example |
|---|---|---|
| Mass screening | Entire population offered screening | Universal newborn screening |
| High-risk (selective) screening | Only high-risk group screened | Screening smokers for lung cancer |
| Multiphasic screening | Several tests applied simultaneously | Health camps with multiple tests |

## High-Yield One-Liners
- Sensitivity and specificity are inherent to the test and do not change with prevalence; PPV/NPV do
- SnOUT: high sensitivity test, if negative, rules OUT disease. SpIN: high specificity test, if positive, rules IN disease
- Screening tests should have high sensitivity; confirmatory tests should have high specificity
- Lead-time bias and length-time bias artificially inflate apparent benefit of screening — must be adjusted for in evaluating screening programs
- LR+ and LR− are prevalence-independent and more clinically useful than PPV/NPV for individual patient decision-making
- A good screening test needs an understood natural history and available effective treatment for the disease it screens for (Wilson-Jungner criteria)
