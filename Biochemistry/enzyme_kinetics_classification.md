# Enzyme Kinetics Classification

## Overview
Enzymes are biological catalysts that lower activation energy without altering reaction equilibrium. Enzyme kinetics (Michaelis-Menten model) describes the relationship between substrate concentration and reaction velocity, and underlies how inhibitors and regulatory mechanisms are understood — a frequent source of graph-based MCQs.

## Enzyme Classification (IUBMB — 6 major classes, EC numbers)
| Class | Function | Example |
|---|---|---|
| Oxidoreductases | Catalyze oxidation-reduction | Lactate dehydrogenase, Alcohol dehydrogenase |
| Transferases | Transfer functional groups | Aminotransferases (ALT/AST), Hexokinase |
| Hydrolases | Hydrolysis reactions | Lipase, Amylase, Peptidases |
| Lyases | Add/remove groups without hydrolysis (form double bonds) | Aldolase, Decarboxylases |
| Isomerases | Intramolecular rearrangement | Phosphohexose isomerase, Mutases |
| Ligases | Join two molecules using ATP | Pyruvate carboxylase, DNA ligase |
*(A 7th class, Translocases, was added later for transport across membranes — less commonly tested)*

## Michaelis-Menten Kinetics
- Equation: V = (Vmax × [S]) / (Km + [S])
- **Km** = substrate concentration at which velocity is half of Vmax; inversely related to enzyme's affinity for substrate (low Km = high affinity)
- **Vmax** = maximum velocity, achieved at saturating substrate; directly proportional to enzyme concentration
- At low [S]: reaction is first-order (velocity ∝ [S]); at high [S]: reaction is zero-order (velocity ≈ Vmax, independent of [S])
- **Lineweaver-Burk plot** (double reciprocal, 1/V vs 1/[S]): straight line; y-intercept = 1/Vmax; x-intercept = -1/Km — used to distinguish inhibitor types

## Enzyme Inhibition — Comparison Table
| Feature | Competitive | Non-Competitive | Uncompetitive |
|---|---|---|---|
| Binds | Active site (resembles substrate) | Different site (allosteric), binds E or ES | Binds ES complex only |
| Effect on Km | ↑ (apparent) | Unchanged | ↓ |
| Effect on Vmax | Unchanged | ↓ | ↓ |
| Reversibility | Overcome by ↑[S] | NOT overcome by ↑[S] | NOT overcome by ↑[S] |
| Lineweaver-Burk pattern | Lines converge on y-axis (same y-intercept) | Lines converge on x-axis (same x-intercept) | Parallel lines |
| Classic example | Statins on HMG-CoA reductase; Malonate on succinate dehydrogenase | Heavy metals on sulfhydryl enzymes | Rare; lithium on some enzymes |

- **Irreversible inhibition**: covalent modification of enzyme (e.g., organophosphates on acetylcholinesterase, aspirin on COX) — permanently inactivates enzyme

## Allosteric Enzymes
- Do NOT follow Michaelis-Menten kinetics — sigmoidal (S-shaped) velocity curve instead of hyperbolic
- Regulated by allosteric effectors binding at sites other than active site (positive or negative)
- Often multi-subunit, exhibit cooperativity (like hemoglobin-O2 binding analogy, though Hb is not strictly an enzyme)
- Examples: PFK-1 (glycolysis), Aspartate transcarbamoylase (pyrimidine synthesis)

## Factors Affecting Enzyme Activity
| Factor | Effect |
|---|---|
| Temperature | Activity increases with temperature until denaturation (optimum ~37°C for human enzymes) |
| pH | Each enzyme has optimum pH (e.g., pepsin ~1.5-2, trypsin ~7.5-8.5, alkaline phosphatase ~9-10, acid phosphatase ~5) |
| Enzyme concentration | Velocity directly proportional (at constant substrate) |
| Cofactors/Coenzymes | Many enzymes require metal ions (cofactors, e.g., Zn2+, Mg2+) or organic molecules (coenzymes, often vitamin-derived, e.g., NAD+, FAD, TPP, CoA, PLP, biotin) |
| Zymogens | Inactive enzyme precursors requiring proteolytic cleavage for activation (e.g., pepsinogen → pepsin, trypsinogen → trypsin) |

## Isoenzymes — Clinically Important
| Enzyme | Isoenzyme | Clinical Use |
|---|---|---|
| LDH | LDH1-5 | LDH1 (heart, RBC) elevated in MI; LDH5 (liver, skeletal muscle) elevated in liver disease |
| CK (Creatine Kinase) | CK-MM (skeletal muscle), CK-MB (cardiac), CK-BB (brain) | CK-MB used in MI diagnosis (with troponin) |
| Alkaline phosphatase | Bone, liver, placental isoforms | Differentiates source of elevated ALP |
| Amylase | Salivary, Pancreatic | Elevated pancreatic amylase/lipase in acute pancreatitis |

## Regulation of Enzyme Activity — Mechanisms
1. **Allosteric regulation** — fast, reversible, by small molecules (e.g., ATP, AMP, citrate)
2. **Covalent modification** — phosphorylation/dephosphorylation (e.g., glycogen phosphorylase, PDH, HMG-CoA reductase), fast and reversible
3. **Zymogen activation** — irreversible proteolytic cleavage (digestive enzymes, clotting factors)
4. **Induction/repression of enzyme synthesis** — slow, transcriptional level (e.g., glucokinase induced by insulin)
5. **Availability of substrate/cofactor**

## High-Yield One-Liners
- Low Km = high enzyme-substrate affinity; Vmax depends on enzyme concentration
- Competitive inhibitor: ↑Km, same Vmax, overcome by excess substrate
- Non-competitive inhibitor: same Km, ↓Vmax, not overcome by substrate
- Lineweaver-Burk: competitive inhibitors share the same y-intercept; non-competitive share the same x-intercept
- Allosteric enzymes give sigmoidal curves, not classic Michaelis-Menten hyperbolic curves
- Zymogen activation (e.g., trypsinogen→trypsin by enteropeptidase) is irreversible
- Organophosphates = irreversible inhibitors of acetylcholinesterase — basis of nerve agent/pesticide toxicity
- CK-MB and Troponin remain the gold-standard enzyme/protein markers for myocardial infarction
