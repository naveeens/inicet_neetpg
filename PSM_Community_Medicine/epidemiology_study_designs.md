# Epidemiology Study Designs

## Overview of Study Types
| Category | Design | Direction | Key Feature |
|---|---|---|---|
| Descriptive | Case report/series, cross-sectional, ecological | — | Generates hypothesis; no comparison group (except cross-sectional) |
| Analytical Observational | Case-control | Retrospective | Starts with outcome (disease), looks back at exposure |
| Analytical Observational | Cohort | Prospective/Retrospective | Starts with exposure, follows forward for outcome |
| Experimental | RCT, community trial, field trial | Forward | Investigator assigns exposure/intervention |

## Cross-Sectional Study
- Measures exposure and outcome **at a single point in time** ("snapshot")
- Gives **prevalence**, not incidence
- Cannot establish temporal sequence (cause-effect) — good for hypothesis generation only
- Cheap, quick; used widely for planning health services

## Case-Control Study
- Starts with **cases** (disease present) and **controls** (disease absent) → looks backward for exposure history
- Measure of association: **Odds Ratio (OR)** = (a×d)/(b×c) [from 2×2 table: a=exposed cases, b=exposed controls, c=unexposed cases, d=unexposed controls]
- Best for **rare diseases** and diseases with **long latency**
- Efficient, quick, inexpensive; can study multiple exposures for one disease
- Prone to: **recall bias** (cases recall exposure more readily), **selection bias** in choosing controls
- Cannot calculate incidence or relative risk directly (can only estimate OR, which approximates RR when disease is rare)

## Cohort Study
- Starts with **exposed and unexposed** groups (disease-free at baseline) → followed forward for outcome
- **Prospective cohort**: exposure and follow-up both in the future from start of study
- **Retrospective (historical) cohort**: exposure already occurred; records used to reconstruct follow-up
- Measure of association: **Relative Risk (RR)** = Incidence in exposed / Incidence in unexposed
- Best for **rare exposures** and studying **multiple outcomes** from one exposure
- Can directly calculate incidence
- Disadvantages: time-consuming, expensive, loss to follow-up (attrition bias), not suited for rare diseases
- Prone to less recall bias than case-control (exposure recorded before outcome occurs)

## Case-Control vs Cohort — Quick Comparison
| Feature | Case-Control | Cohort |
|---|---|---|
| Direction | Backward (effect→cause) | Forward (cause→effect) |
| Starts with | Disease status | Exposure status |
| Measure | Odds Ratio | Relative Risk |
| Best for | Rare disease, long latency | Rare exposure, multiple outcomes |
| Time/Cost | Less, faster | More, expensive |
| Bias | Recall bias, selection bias | Loss to follow-up |
| Can calculate incidence? | No | Yes |

## Randomized Controlled Trial (RCT)
- Gold standard for establishing **causation**; participants randomly allocated to intervention vs control (placebo/standard care)
- **Randomization** eliminates selection bias and balances known/unknown confounders
- **Blinding**: single (participant unaware), double (participant + investigator unaware), triple (+ data analyst unaware) — minimizes observer/ascertainment bias
- **Intention-to-treat analysis** — analyze participants per original group assignment regardless of adherence/crossover (preserves randomization benefit, preferred over "per protocol" for real-world estimate of effect)
- Phases of drug trials: Phase I (safety, healthy volunteers), Phase II (efficacy/dose, small patient group), Phase III (large-scale efficacy/safety vs standard, pre-marketing), Phase IV (post-marketing surveillance)

## Ecological Study
- Unit of analysis = **population/group**, not individual (e.g., comparing salt intake and stroke rates across countries)
- Cheap, uses existing data; hypothesis-generating
- Major limitation: **Ecological fallacy** — assuming group-level association applies to individuals

## Bias in Epidemiological Studies
| Bias | Description | Most Associated With |
|---|---|---|
| Selection bias | Non-random/non-representative selection of study/control groups | Case-control |
| Recall bias | Differential accuracy of memory between cases and controls | Case-control |
| Observer/Ascertainment bias | Investigator's knowledge of exposure/outcome influences assessment | Any (esp. unblinded) |
| Confounding | Third variable associated with both exposure and outcome, distorts true association | Any observational study |
| Loss to follow-up (attrition) | Differential dropout related to exposure/outcome | Cohort, RCT |
| Berkson's bias | Hospital-based controls not representative of general population | Hospital-based case-control |

## Levels of Evidence (Hierarchy)
Systematic review/meta-analysis of RCTs > RCT > Cohort study > Case-control study > Cross-sectional study > Case series/report > Expert opinion

## High-Yield One-Liners
- Case-control study: OR; starts with disease; retrospective; best for rare disease
- Cohort study: RR; starts with exposure; best for rare exposure and studying multiple outcomes
- Cross-sectional study gives prevalence, not incidence
- RCT is the strongest design for causation due to randomization controlling confounding
- Ecological fallacy = incorrectly applying group-level associations to individuals
- Intention-to-treat analysis preserves the value of randomization
- Recall bias is the classic weakness of case-control studies; loss to follow-up is the classic weakness of cohort studies
- Meta-analysis of RCTs sits at the top of the evidence pyramid
