# EGT Literature Synthesis — Snyder Call Prep

Quick-reference guide grouped by domain. All papers are in either
~/workspace/EGTRelated/Academic_Research/SitePapers/ or
~/Documents/StanfordKingCellEGTRCT/literature/

## EPIDEMIOLOGY — Human EGT Levels Predict Outcomes

### Smith et al. 2020 — Malmö Diet and Cancer Study (PRIMARY MOTIVATION)
- Heart. PMID 31672783. PDF: literature/egt_mortality_malmo_20yr.pdf
- N=3,236, median 21.4 yr follow-up, 843 deaths
- EGT was the strongest dietary biomarker associated with a health-conscious food pattern
- Per 1 SD higher plasma EGT: all-cause mortality HR 0.86 (p=4e-5), CV mortality HR 0.79 (p=0.002), CHD HR 0.85 (p=0.01)
- Independent of established risk factors

### Paul BD 2022 — "Ergothioneine: A Stress Vitamin with Antiaging, Vascular, and Neuroprotective Roles"
- Antioxid Redox Signal, 2022. PMID ? PDF: SitePapers/EGT_General.pdf
- Comprehensive review: EGT depletion accelerates aging phenotypes; EGT crosses BBB; neuroprotective in AD/PD models
- Proposes EGT as a "stress vitamin" essential for healthspan maintenance
- Covers the longitudinal study linking low EGT to higher mortality

## MOLECULAR MECHANISMS — How EGT Works

### D'Onofrio et al. 2016 — EGT + SIRT1/SIRT6 + High Glucose (GLYCEMIC LINK)
- Free Radic Biol Med. PMID 27101740. PDF: literature/donofrio_2016_egt_sirt6_highglucose.pdf
- EGT (0.5 mM) upregulates SIRT1 and SIRT6 under high-glucose conditions
- Blocks endothelial senescence: reduces ROS, downregulates p66Shc and NF-κB
- **SIRT6 silencing by siRNA abolishes the protective effect entirely** — this is the causal evidence
- SIRT6 functions at the intersection of glucose metabolism and chromatin regulation (deacetylates H3K9, H3K56)
- **Key for Snyder**: This is the mechanistic bridge between metabolic health and epigenetic aging

### Sprenger et al. 2025 — EGT Directly Activates MPST (FIRST DIRECT TARGET)
- Cell Metabolism. PDF: literature/egt_mpst_mitochondria_cellmetab_2025.pdf (also SitePapers/EGT_Exercise_Study.pdf)
- EGT accumulates in muscle mitochondria during exercise
- **First identified direct molecular target of EGT**: MPST (3-mercaptopyruvate sulfurtransferase)
- EGT directly binds and activates MPST → boosts mitochondrial respiration → improves exercise performance
- This is a separate mechanism from SIRT6 — EGT hits multiple targets
- **Key for Snyder**: Clean, direct mechanism story. EGT has a defined molecular target.

### Zhao & Qi 2026 — EGT as Geroprotector (HALLMARK-SPANNING)
- Ageing Res Rev. PMID 42107722. PDF: literature/zhao_qi_2026_egt_geroprotector_review.pdf
- Systematic review mapping EGT onto all 12+ Lopez-Otin hallmarks of aging
- Covers: telomere maintenance, mitochondrial integrity, NRF2 pathway, SIRT1/SIRT6, neurodegeneration, metabolic dysfunction
- Proposes EGT as a biomarker of biological aging
- Network pharmacology shows EGT hits multiple aging pathways simultaneously
- **Key for Snyder**: Comprehensive map showing EGT is not a single-pathway compound

### Servillo, D'Onofrio & Balestrieri — EGT Cardiovascular
- SitePapers/EGT_Cardiovascular.pdf
- EGT chemistry to cardiovascular therapeutic potential
- OCTN1 transporter, tissue accumulation, antioxidant mechanisms
- Links EGT to endothelial protection and cardiovascular disease prevention

### Ishimoto & Kato — EGT in the Brain
- SitePapers/EGT_Cognition.pdf (review)
- EGT crosses BBB via OCTN1
- Neuroprotective: reduces oxidative damage, inflammation in brain
- Relevant to cognitive endpoints in our RCT

## CLINICAL TRIALS — EGT in Humans

### Yau, Cheah et al. 2024 — EGT-MCI Pilot (COGNITION)
- J Alzheimers Dis. PMID 39544014. PDF: literature/yau_2024_egt_mci_pilot.pdf
- 25 mg EGT 3x/week (~10.7 mg/day) vs placebo, 1 year, MCI patients (mean age ~70)
- Safe and well-tolerated with no toxicity
- Improved Rey Auditory Verbal Learning Test (AVLT) learning
- Stabilized neurofilament light (NfL) levels
- Primary dose justification for our 30 mg/day — this is the longest human EGT trial to date

### Tian et al. 2021 — ErgMS Protocol (DOSE FINDING)
- Pilot Feasibility Stud. PMID 34715934.
- 5 mg/day and 30 mg/day EGT for 12 weeks in metabolic syndrome
- Both doses safe and well-tolerated
- 30 mg/day is our selected dose — provides margin above estimated dietary intake (~1-5 mg/day)

### Katsube et al. 2022 — EGT Sleep Trial (SLEEP)
- J Functional Foods. PDF: SitePapers/EGT_Sleep.pdf
- RCT: 20 mg EGT/day for 4 weeks in adults with sleep complaints
- EGT significantly improved sleep difficulties (survey + EEG)
- Increased N2 stage, decreased N1 stage and waking after sleep onset
- Mechanisms: inhibits histamine N-methyltransferase, aldehyde dehydrogenase; binds α3β4 nicotinic receptor
- Serum metabolome: reduced glutamate, enhanced lipid metabolism
- **Key for Snyder**: Direct human RCT data in a non-EGT-specific population

### Hseu et al. 2020 — EGT Skin Anti-Aging (SKIN)
- Oxid Med Cell Longev. PMID ? PDF: SitePapers/EGT_Skin.pdf
- EGT protects human dermal fibroblasts from UVA-induced photoaging
- Inhibits AP-1 pathway, activates Nrf2-mediated antioxidant genes
- Supports our skin aging functional endpoint

## PRECEDENT — Metabolic Interventions Shift Epigenetic Clocks

### Corley et al. 2025 (now Nat Commun 2026) — Semaglutide Slows Clocks
- medRxiv → Nature Communications. PMID 40791720 / 42156721
- Full text XML: literature/Corley2025_Semaglutide_Epigenetic_Aging_HIV.xml
- 32 weeks, double-blind, N=84 (45 semaglutide, 39 placebo)
- HIV+ adults with lipohypertrophy, non-diabetic (median HbA1c 5.5%, mean age 49)
- **Effect sizes (adjusted mean differences):**
  - GrimAge2: -2.3 yr (p=0.009)
  - PhenoAge: -4.9 yr (p=0.004)
  - DunedinPACE: -0.09 units (p=0.01, ~9% slower)
  - PCGrimAge: -3.1 yr (p=0.007)
- 11 organ-system clocks showed concordant decreased aging
- **Key for Snyder**: A purely metabolic intervention (GLP-1 agonist) slowed all major clocks. Establishes that the metabolic → epigenetic aging axis is real and intervention-responsive.

## CLOCK METHODOLOGY

### Belsky et al. 2022 — DunedinPACE Validation
- eLife. PMID 35029144. PDF: literature/belsky_2022.pdf
- ICC 0.96 [0.93-0.98] — excellent test-retest reliability
- Correlates with 20-year Pace of Aging: r = 0.78
- Measures rate (yr/yr), not state — ideal for intervention studies
- **Key for Snyder**: Clock reliability justifies our N=160 (Corley found significant effects with N=84)

### Anderson et al. 2026 — FTC/TAF Reduces Bio Age
- medRxiv. PMID 41929344. N=36, 12 weeks
- DunedinPACE -0.061 (p=0.019), PhenoAge -6.33 (p=0.008)
- Confirms clocks respond to interventions in short timeframes

## ANIMAL / PRECLINICAL — Additional EGT Biology

### EGT + Hepatic Steatosis via PCYT2 (2026)
- Phytomedicine. PMID 42275877. PDF: literature/egthepatic_steatosis_2026_phytomedicine.pdf
- EGT alleviates NAFLD via phosphatidylethanolamine homeostasis restoration

### EGT + Metformin + T2D Rats (2021)
- PMID 34582252. EGT + metformin reduced oxidative stress, inflammation, hypertriglyceridemia in T2D rat liver

### Wang et al. 2023 — EGT + SIRT6 + Osteoarthritis
- PMID 37156032. EGT acts through SIRT6/NF-κB axis in vivo in OA model
- Confirms EGT-SIRT6 axis in a disease context

### Yoshida et al. — EGT + Immune System
- SitePapers/EGT_Immune_System.pdf. EGT augments immunomodulatory function of TLR agonists on macrophages

### Mao et al. — EGT + Liver Fibrosis
- SitePapers/EGT_Liver_Health.pdf. EGT ameliorates liver fibrosis via glycerophospholipids metabolism and TGF-β/Smads pathway

### EGT + Eye Research (2024)
- SitePapers/EGT_Eye_Research.pdf. Screening antioxidants for retinal pigment epithelial cell protection

### Ricceri et al. 2014 — Seasonal Methylation Drift
- PLoS ONE. PMID 25210735. PDF: literature/ricceri_2014_seasonal_methylation.pdf
- LINE-1 methylation ~0.8% difference spring/summer vs autumn/winter (p=0.04)
- Supports 12-month study duration (controls for seasonal cycle)
