# Snyder Call — Tricky Questions Prep

## Q1: "Why 30mg? That is a low dose."

**The truth:** It's the highest dose tested in a controlled human trial with full safety data when we designed the protocol. But there's now newer data.

**Your answer (honest and tactical):**

*"30mg was conservative — it's the top dose from Tian 2021 (ErgMS protocol), 6-30x normal dietary intake (~1-5mg/day), safe and well-tolerated. Yau 2024 showed cognitive effects at ~10.7mg/day equivalent, so 30mg gives us headroom.*

*That said, a 2026 study just published 120mg/day for 3 months in 40 women — no safety issues, ovarian reserve improved. So the safety margin is wider than we assumed. If your study infrastructure supports it, I'd happily revisit the dose. 60-120mg would be defensible and might improve the signal-to-noise ratio."*

**Key facts to have ready:**
- Tian 2021: tested 5 and 30mg, 12 weeks, metabolic syndrome. 30mg was the top dose. Safe.
- Yau 2024: ~10.7mg/day equivalent, 1 year, MCI. Cognitive stabilization seen at this low dose.
- **PMID 42310611** (2026): 120mg/day for 3 months, 40 women, safe. AMH improved. PSQI sleep improved.
- No human dose-response data exists for clock endpoints. We're in uncharted territory.
- EGT has long tissue half-life (OCTN1 retention in RBCs ~30 days) — accumulation over time means steady-state is higher than acute dose suggests.

---

## Q2: "Can the study be shortened or lengthened to mesh with your existing arm(s)? What are the tradeoffs?"

**Shorter (<12 months):**

| Duration | Clocks work? | Function works? | Seasonality? | Practice effects? |
|----------|-------------|----------------|--------------|-------------------|
| 6 months | Probably — Corley saw signals at 32wk | Unlikely — decline too small in healthy 50-70 | Confounded — half a seasonal cycle | Risky — insufficient familiarization |
| 8 months | Likely — same as Corley timeline | Marginal — some cognitive domains might show | Partial — still missing half the cycle | Moderate |
| 12 months | Yes | Yes — Salthouse 2009 rates detectable | Controlled — full annual cycle | Mitigated with 1-2 familiarization sessions |

**Best answer:** *"We designed for 12 months because it controls seasonal methylation drift (Ricceri 2014 showed ~0.8% LINE-1 oscillation), gives functional endpoints time to diverge, and lets us do one annual cycle. But clocks don't need 12 months — Corley's semaglutide trial hit all major clocks at 32 weeks. If your trial timeline demands shorter, we could move the primary clock analysis to 6-8 months and keep 12 months as a follow-up for durability and functional endpoints."*

**Longer (>12 months):**
- Already have an optional 18-month extension in the protocol
- Tradeoffs: attrition (~5-10% per 6 months), budget (+$100K per 6mo), sustained adherence
- Benefit: more power for functional endpoints, durability data
- **Best if his study is already 18-24 months** — then our 12-month is just an interim analysis

**If his study is e.g. 6 months:** *"We could run clocks at 0 and 6 months as primary analysis, with a 12-month extension funded separately for functional endpoints. The clock data is publishable at 6 months — Corley proved that."*

---

## Q3: "How orthogonal are EGT's benefits? Can it be co-administered?"

**The honest answer:**

*"EGT is not orthogonal in the drug sense — it doesn't have one on-off target. It's a cytoprotective agent that hits multiple aging hallmarks: SIRT6 chromatin regulation, MPST mitochondrial activation, NRF2 antioxidant response, telomere maintenance. That's its strength and its weakness.*

*Strength: it protects against stress broadly, so you'd expect to see effects across multiple domains. Weakness: if you co-administer it with another compound, you can't cleanly separate which effect came from which. The signals would be additive or synergistic, and you'd need a 2x2 factorial design to disentangle them — which doubles the N to ~320.*

*A better design for your question: share the placebo group and run EGT vs Compound X vs placebo — three arms, same N as two 2-arm trials would need separately. You get a direct head-to-head comparison of effect sizes across the same endpoints. We both win: your compound compares against an active reference, we both share the control group cost, and the clock panel is the common readout that lets us say 'Compound X moved clocks more than EGT on this domain, EGT moved more on that domain.'*

*On augmentation (exercise, diet): we should monitor, not prescribe. If we prescribe exercise to everyone, we can't separate EGT from exercise effects. If we randomize by exercise, we need more arms and more N. Better to use actigraphy/wearables as covariates and measure natural variation."*

**Three-arm logic (for emphasis):**

| Arm | N | Cost |
|-----|---|------|
| Placebo | 80 | Shared infrastructure |
| EGT 30-60mg | 80 | Capsules + assays |
| Compound X | 80 | Your marginal cost |
| **Total** | **240** | **~1.5x a 2-arm trial** |

*"Three arms for the price of 1.5. The shared placebo and common clock panel maximize information per dollar."*

---

## Q4: "How do I get 'juice' from this? How do we confidently correlate observed effects?"

**Key insight:** The study produces publishable data regardless of which arm wins, because:
- The clock panel is a validated, independent readout — if EGT moves clocks but Compound X doesn't, that's a publication. If the reverse, that's also a publication.
- The optional iPOP sub-study multi-omics data is valuable as a reference dataset regardless of group differences
- Wearable data (actigraphy, glucose monitoring) produces longitudinal trajectories that are publishable as method development even without significant group differences

**For correlation specifically:**
- The three clocks provide **mechanism discrimination**: if PhenoAge moves but GrimAge2 doesn't, the effect is metabolic (PhenoAge includes glucose). If all three move uniformly, the effect is global aging slowing.
- Spearman correlation matrices between clock changes, biomarker changes, and functional changes (pre-specified in the SAP)
- Individual CpG site analysis (limma, DMRcate) identifies differentially methylated regions — pathway enrichment tells us mechanism
- Principal component analysis of multi-omics profiles groups participants by response type
