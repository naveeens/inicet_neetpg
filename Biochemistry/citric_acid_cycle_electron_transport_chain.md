# Citric Acid Cycle Electron Transport Chain

## Overview
The citric acid cycle (Krebs/TCA cycle) is the final common oxidative pathway for carbohydrates, fats, and proteins — occurs entirely in the mitochondrial matrix (except succinate dehydrogenase, embedded in inner membrane). Each turn oxidizes 1 acetyl-CoA completely to 2 CO2, generating reducing equivalents that feed the electron transport chain (ETC) for oxidative phosphorylation.

## TCA Cycle — Key Steps and Regulation
| Step | Enzyme | Product | Regulation |
|---|---|---|---|
| Acetyl-CoA + Oxaloacetate → Citrate | Citrate synthase | Citrate | Inhibited by ATP, NADH, citrate, succinyl-CoA; first committed step |
| Citrate → Isocitrate | Aconitase | Isocitrate | — |
| Isocitrate → α-Ketoglutarate | **Isocitrate dehydrogenase** — rate-limiting enzyme of TCA cycle | α-KG + CO2 + NADH | Activated by ADP, Ca2+; Inhibited by ATP, NADH |
| α-Ketoglutarate → Succinyl-CoA | α-Ketoglutarate dehydrogenase complex | Succinyl-CoA + CO2 + NADH | Requires TPP, lipoic acid, CoA, FAD, NAD+ (same cofactors as PDH); inhibited by NADH, succinyl-CoA, ATP |
| Succinyl-CoA → Succinate | Succinyl-CoA synthetase | Succinate + **GTP** | Only step producing high-energy phosphate directly (substrate-level phosphorylation) |
| Succinate → Fumarate | Succinate dehydrogenase (Complex II of ETC) | Fumarate + FADH2 | Only membrane-bound TCA enzyme; directly feeds electrons to ETC |
| Fumarate → Malate | Fumarase | Malate | — |
| Malate → Oxaloacetate | Malate dehydrogenase | OAA + NADH | Regenerates OAA to continue cycle |

- Per acetyl-CoA: 3 NADH + 1 FADH2 + 1 GTP + 2 CO2
- Total ATP yield per acetyl-CoA (via ETC): ~10 ATP (3 NADH × 2.5 + 1 FADH2 × 1.5 + 1 GTP)
- Total ATP per glucose (complete aerobic oxidation): ~30-32 ATP
- Amphibolic pathway: also supplies intermediates for biosynthesis (OAA → gluconeogenesis/aspartate; α-KG → glutamate; succinyl-CoA → heme synthesis; citrate → fatty acid synthesis)
- Anaplerosis: replenishing reactions (e.g., pyruvate carboxylase making OAA) keep the cycle running

## Electron Transport Chain (Inner Mitochondrial Membrane)
| Complex | Name | Electron Donor | Inhibitors |
|---|---|---|---|
| Complex I | NADH-CoQ reductase | NADH | Rotenone, amytal |
| Complex II | Succinate-CoQ reductase | FADH2 (succinate, also ETF from fatty acid oxidation) | Malonate (competitive with succinate) |
| Complex III | CoQ-cytochrome c reductase | Coenzyme Q (ubiquinone) | Antimycin A |
| Complex IV | Cytochrome c oxidase | Cytochrome c | **Cyanide, azide, CO, H2S** |
| Complex V | ATP synthase | Proton gradient | Oligomycin |

- Electron flow: NADH → Complex I → CoQ → Complex III → Cyt c → Complex IV → O2 (final electron acceptor, reduced to H2O)
- FADH2 enters at Complex II/CoQ level, bypassing Complex I → lower ATP yield than NADH
- Proton-motive force across inner membrane drives ATP synthase (chemiosmotic hypothesis — Peter Mitchell)
- **Uncouplers** (e.g., 2,4-dinitrophenol, thermogenin/UCP1 in brown fat): dissipate proton gradient as heat without ATP synthesis → ↑O2 consumption, ↓ATP, ↑heat
- Oligomycin: inhibits ATP synthase directly, blocking both ATP synthesis and (secondarily) electron transport (since proton gradient cannot dissipate)

## Cofactor/Shuttle High-Yield Points
- Cytosolic NADH cannot cross inner mitochondrial membrane directly — requires shuttles:
  - **Malate-aspartate shuttle** (liver, heart, kidney): yields 2.5 ATP/NADH (full yield)
  - **Glycerol-3-phosphate shuttle** (muscle, brain): yields 1.5 ATP/NADH (electrons enter as FADH2 equivalent at Complex II level)

## Clinically Relevant Points
| Condition | Mechanism |
|---|---|
| Cyanide poisoning | Blocks Complex IV → cells cannot use O2 → histotoxic hypoxia despite normal PaO2; treat with amyl nitrite/sodium nitrite/thiosulfate or hydroxocobalamin |
| Arsenic poisoning | Inhibits lipoic acid-dependent enzymes (PDH, α-KGDH) → blocks TCA cycle entry and α-KG step |
| Thiamine deficiency | Impairs PDH and α-KGDH (both TPP-dependent) → lactic acidosis, Wernicke-Korsakoff |
| Fluoroacetate poisoning | Converted to fluorocitrate → inhibits aconitase → blocks TCA cycle |
| MELAS/mitochondrial myopathies | Mutations in mtDNA affecting ETC complexes → maternal inheritance, ragged red fibers |

## High-Yield One-Liners
- Rate-limiting enzyme of TCA cycle: **isocitrate dehydrogenase**
- Only substrate-level phosphorylation step in TCA cycle: succinyl-CoA synthetase (produces GTP)
- Succinate dehydrogenase = only TCA enzyme embedded in inner mitochondrial membrane = also Complex II of ETC
- α-KG dehydrogenase shares identical cofactor requirement with PDH: TPP, lipoic acid, CoA, FAD, NAD+
- Cyanide blocks Complex IV; CO also blocks Complex IV (competes with O2 at cytochrome a3)
- 2,4-DNP and thermogenin = classic uncouplers → heat production without ATP (used historically as weight-loss drug, now banned for toxicity)
- Final electron acceptor of ETC: molecular oxygen → reduced to water
- Malate-aspartate shuttle (2.5 ATP/NADH) > glycerol-3-phosphate shuttle (1.5 ATP/NADH) in efficiency
