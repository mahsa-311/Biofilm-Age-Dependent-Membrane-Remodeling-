# Biofilm-Age-Dependent-Membrane-Remodeling
<div align="justify">
Biofilm-associated infections represent enduring challenges in antimicrobial therapy owing to the structural and physiological robustness of bacterial biofilms. As Pseudomonas aeruginosa biofilms mature, the composition and biomechanical properties of their membranes undergo progressive remodeling, thereby modulating susceptibility to antimicrobial agents. In this study, all-atom molecular dynamics (MD) simulations were employed to elucidate the molecular mechanism of action of the cationic peptide LF11-215; a lactoferrin-derived fragment with experimentally confirmed antibiofilm efficacy against P. aeruginosa native-like model membranes that recapitulate four developmental stages: planktonic, 1-day (BF1), 2-day (BF2), and 6-day (BF6) biofilms. A quorum-sensing peptide (QSP) family member was used as a negative control to delineate the physicochemical determinants of peptide activity. Each membrane system was simulated for 500 ns both in the absence of peptides and in the presence of LF11-215 or the QSP control. The simulations revealed stage-dependent changes in membrane organization, including lipid packing density, bilayer thickness, acyl-chain order, and microscopic fluidity. LF11-215 exhibited strong electrostatic and hydrophobic interactions with anionic phosphatidylglycerol (PG) lipids, resulting in extensive hydrogen-bond formation and membrane destabilization. Peptide binding reduced acyl-chain order and increased interleaflet interdigitation, consistent with experimental observations. Notably, the most potent peptide–membrane interactions were observed in the mature 6-day biofilm model, where the electrostatic interaction energy reached −1199.5 kJ/mol and area-per-lipid (APL) increased by approximately 10–12%, indicating that biofilm age critically modulates peptide efficacy. Collectively, these findings provide atomistic insight into how biofilm maturation and membrane lipid composition govern the mechanisms of action of antimicrobial peptides and offer a molecular basis for the rational design of antibiofilm therapeutics.
</div>
<img width="1536" height="844" alt="Biofilm Membrane Remodeling and Peptide Activity" src="https://github.com/user-attachments/assets/7ddc2044-477b-4fa4-bc09-6c5d42fd288e" />




## Simulation system parameters

| System | Lipids per leaflet | Water molecules | Na⁺ | Cl⁻ | Pressure (bar) | Temperature (K) | Total atoms |
|:-------|-------------------:|----------------:|----:|----:|---------------:|----------------:|------------:|
| Plankt bilayer | 50 | 4216 | 62 | 10 | 1 | 310.15 | 25074 |
| BF1 bilayer     | 50 | 4192 | 58 | 10 | 1 | 310.15 | 25070 |
| BF2 bilayer     | 50 | 4176 | 57 | 9  | 1 | 310.15 | 25065 |
| BF6 bilayer     | 50 | 4211 | 56 | 10 | 1 | 310.15 | 24988 |
