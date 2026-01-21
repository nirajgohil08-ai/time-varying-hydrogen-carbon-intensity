# Results Summary – Time-Varying Hydrogen Carbon Intensity Modeling

## What this repository demonstrates

This repository documents a time-resolved life-cycle modeling framework that quantifies **hourly carbon intensity of electrolytic hydrogen** under real-world electricity grid variability. The central finding is that **annual-average emissions accounting can materially misrepresent hydrogen lifecycle emissions**, which directly affects qualification outcomes under the **IRA Section 45V Clean Hydrogen Production Tax Credit**.

---

## Key Results

### Result 1 – External validation under real-world grid conditions
**Figure 4 (Validation):** `figures/validation/Hourly_Carbon_Intensity_Validation_vs_Electricity_Maps.png`  
The modeled hourly carbon intensity values closely track independently reported Electricity Maps data for a representative operating period. This supports the accuracy and robustness of the proposed framework and confirms the methodology produces credible time-resolved outputs.

### Result 2 – Full-year evidence that emissions vary materially hour-to-hour
**Figure 5 (8760-hour variability):** `figures/results/Hourly_Grid_Carbon_Intensity_8760h.png`  
Across a full calendar year, electricity carbon intensity varies significantly across hours and seasons. This variability is large enough that static or annual-average methods can mask periods of high emissions and distort emissions attribution for hydrogen production.

---

## Why this matters for U.S. national interest (policy and investment integrity)

Clean hydrogen is a strategic pillar of U.S. decarbonization policy and receives substantial federal support through Section 45V and hydrogen hub programs. Because Section 45V eligibility depends on lifecycle emissions thresholds, **accurate time-resolved emissions attribution is necessary** to:

- prevent misclassification of hydrogen carbon intensity  
- reduce incentives being awarded to non-qualifying production pathways  
- improve transparency and enforceability of federal guidance  
- protect taxpayers and improve environmental integrity of clean hydrogen deployment  

---

## Practical implication

Time-resolved modeling enables decision-makers to evaluate how operational choices (when hydrogen is produced and which electricity pathways supply it) change lifecycle emissions outcomes. This supports more credible qualification analysis and reduces the risk of emissions arbitrage that can occur when annual-average methods are applied to time-varying grids.

---

## References within this repository

- `EXHIBIT_MAP.md`  
- `policy/45V_alignment.md`  
- `dhanasar/prong1_national_importance.md`  
- `dhanasar/prong2_well_positioned.md`  
- `dhanasar/prong3_balance_of_benefits.md`  

