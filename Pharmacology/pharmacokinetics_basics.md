# Pharmacokinetics Basics

## Overview
Pharmacokinetics (PK) = what the body does to the drug: Absorption, Distribution, Metabolism, Excretion (ADME). Foundation for dosing, dose adjustment in organ failure, and drug interactions — one of the highest-yield conceptual areas in exams.

## Absorption & Bioavailability
- **Bioavailability (F)** = fraction of administered dose reaching systemic circulation unchanged
  - IV = 100% (F = 1) by definition
  - Oral F reduced by first-pass metabolism (gut wall + liver)
- **First-pass metabolism**: high for drugs like propranolol, lidocaine, GTN, morphine, verapamil — hence low oral bioavailability; some given sublingual/IV/transdermal to bypass it (e.g., GTN sublingual/patch, lidocaine IV only)
- Drugs with negligible first pass but still poor oral F due to gut destruction: insulin, aminoglycosides (peptide/large polar molecules)
- **Bioequivalence**: two formulations with similar F and similar rate (Cmax, Tmax) — required for generic substitution

## Volume of Distribution (Vd)
Vd = Total dose administered / plasma concentration at time 0
- **Low Vd (≈ plasma volume, ~4–5 L)**: large, highly plasma-protein-bound, polar drugs (e.g., warfarin) — stay in blood
- **High Vd (> total body water, can exceed 100s of L)**: lipophilic drugs sequestered in tissue (e.g., digoxin ~500 L, chloroquine — very high Vd)
- Vd used to calculate **loading dose** = Vd × target concentration / F

## Clearance & Half-Life
- **Clearance (Cl)** = volume of plasma cleared of drug per unit time = rate of elimination / plasma concentration
- **Half-life (t½)** = 0.693 × Vd / Cl
- Steady state reached in **~4–5 half-lives** (97% of steady state at 5 t½) — high-yield for predicting when to check drug levels (e.g., digoxin, phenytoin, lithium)
- **Maintenance dose** = Cl × target steady-state concentration / F (independent of Vd)
- Time to steady state depends only on t½, NOT on dose or dosing frequency

## Order of Kinetics
| Feature | First-order (linear) | Zero-order (saturation) |
|---|---|---|
| Amount eliminated | Constant **fraction** per unit time | Constant **amount** per unit time |
| Half-life | Constant | Variable, increases with dose |
| Plasma conc. vs dose | Proportional | Disproportionate (small dose ↑ → large conc. ↑) |
| Classic drugs | Most drugs | **Phenytoin, Ethanol, Aspirin (high dose), Warfarin (high dose)** — mnemonic "PEA(W)" |

*High-yield: Phenytoin follows first-order kinetics at low/therapeutic doses but switches to zero-order (saturation of hepatic metabolism) at higher doses — small increments near therapeutic range can cause disproportionate toxic rise. This is why phenytoin dose increments must be small once near target level.*

## Drug Metabolism
### Phase I (Oxidation/Reduction/Hydrolysis)
- Mainly via **Cytochrome P450 (CYP450)** system in liver (smooth ER)
- Usually inactivates drug, but some produce active metabolites (**prodrugs**): codeine → morphine (CYP2D6), enalapril → enalaprilat, clopidogrel → active thiol metabolite (CYP2C19)

### Phase II (Conjugation)
- Glucuronidation, sulfation, acetylation, methylation, glutathione conjugation → usually inactive, water-soluble, excretable products
- **Neonates** have immature glucuronidation → risk of chloramphenicol (gray baby syndrome) and morphine toxicity

### Key CYP Enzyme Interactions (exam favorites)
| Enzyme | Inducers | Inhibitors |
|---|---|---|
| CYP3A4 (most drugs metabolized here) | Rifampicin, Phenytoin, Phenobarbitone, Carbamazepine, St. John's Wort | Ketoconazole, Ritonavir, Erythromycin/Clarithromycin, Grapefruit juice, Cimetidine |
| CYP2D6 | — | Fluoxetine, Quinidine (poor metabolizer phenotype relevant to codeine failure) |

*Mnemonic for enzyme inducers: "CRAP GPS" — Carbamazepine, Rifampicin, Alcohol (chronic), Phenytoin, Griseofulvin, Phenobarbitone, Sulfonylureas... classically remembered as Rifampicin, Phenytoin, Phenobarbitone, Carbamazepine, Griseofulvin, Chronic alcohol.*

- **Enzyme induction** = onset over days-weeks (needs new protein synthesis); **enzyme inhibition** = onset rapid (hours), often first dose

## Excretion
- Kidney = major route; also biliary/fecal, lungs (volatile anesthetics), sweat, milk
- **Renal clearance** depends on: glomerular filtration + active tubular secretion − tubular reabsorption
- Weak acids (e.g., aspirin) eliminated faster in **alkaline urine** (ion trapping) — basis of urinary alkalinization in aspirin/phenobarbitone poisoning
- Weak bases (e.g., amphetamine) eliminated faster in **acidic urine**
- **Enterohepatic circulation**: drug excreted in bile, reabsorbed in intestine — prolongs action (e.g., oral contraceptives affected by antibiotics disrupting gut flora — classic but debated concept)

## Drug Interactions — Pharmacokinetic
| Level | Example |
|---|---|
| Absorption | Tetracyclines + antacids/milk (Ca²⁺/Mg²⁺ chelation) → ↓ absorption |
| Distribution | Aspirin displaces warfarin from albumin → ↑ free warfarin → bleeding |
| Metabolism | Enzyme induction/inhibition (see above) |
| Excretion | Probenecid ↓ tubular secretion of penicillin → ↑ penicillin levels (used therapeutically) |

## High-Yield One-Liners
- Time to reach steady state depends only on half-life (~4–5 t½), not on dose/rate
- Loading dose depends on Vd; maintenance dose depends on clearance
- Phenytoin, ethanol, aspirin (toxic dose) follow zero-order kinetics
- Enzyme induction = slow onset (days); enzyme inhibition = fast onset (hours)
- Digoxin has a very high Vd due to extensive tissue (skeletal muscle) binding
- Weak acid drug poisoning (e.g., salicylates) → alkalinize urine to enhance excretion
- Neonates are prone to drug toxicity due to immature Phase II (glucuronidation) pathways
