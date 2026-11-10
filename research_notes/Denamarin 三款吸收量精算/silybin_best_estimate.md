# Silybin from Denamarin's SPC in a 9.1 kg dog: best-estimate absorption and the numbers behind it

This is round 2. It builds on `research_notes/Denamarin 三款成分与吸收对比/silybin_absorption.md` and does not repeat it, except where a number needed re-checking.

Evidence tags (each number also carries a species label):
- **[PR]**: peer-reviewed paper.
- **[PR-ind]**: peer-reviewed, written or funded by Nutramax.
- **[Abstract]**: conference abstract.
- **[Diss]**: PhD dissertation, not itself peer-reviewed.
- **[Review]**: secondary source.
- **[Mfr]**: manufacturer material or a retailer copy of the label.
- **[Extrap]**: my own calculation or cross-species extrapolation.

Abbreviations:
- SPC: silybin–phosphatidylcholine complex. Silipide, IdB 1016 and Siliphos are Indena's SPC; Marin is Nutramax's SPC product.
- F: absolute oral bioavailability of intact (free, unconjugated) silybin.
- Fa: fraction of the dose absorbed in any form (free plus conjugated).
- Silibinin and silybin are the same substance (silybin A+B). Molar mass 482.44 g/mol, used for µM → ng/mL conversions.

---

## Q1. Recommended estimates for the three products (the deliverable)

### Takeaway
**Nobody has measured how much silybin a dog absorbs from SPC.** There is no canine IV study and no canine bile or urine recovery study. Both numbers below are therefore cross-species extrapolations.

| Measure (SPC, fasted 9.1 kg dog) | Best estimate | Plausible range |
|---|---|---|
| (1) Intact (free) silybin reaching systemic blood | **≈4%** | 2–9% |
| (2) Silybin absorbed in any form (free + conjugated; what passes through the liver) | **≈20%** | 10–35% |

The floor for measure (2) is about 13–14%, the value actually measured in humans.

| Product (dose) | Intact silybin reaching blood | Silybin absorbed in any form |
|---|---|---|
| A or B (24 mg) | ≈1.0 mg | ≈4.8 mg |
| C, ½ tablet (17.5 mg) | ≈0.7 mg | ≈3.5 mg |
| C, 1 tablet (35 mg) | ≈1.4 mg | ≈7.0 mg |

The three products differ only in dose. No product-specific absorption data exist.

### Cited Findings
**Anchor data for measure (1), absolute F of intact silybin:**
- **(cat) [PR; academic authors; Winn Feline Foundation grant; Marin SPC supplied by Nutramax]** Webb, Gustafson & Twedt 2012. Five cats fasted 12 h were given SPC orally in capsule form (each capsule 131 mg SPC = 40 mg silibinin), with an IV silibinin reference; the assay measured parent silibinin.
  - "Based on this data, the oral bioavailability (F) was calculated to be approximately 0.07 (7%)."
  - "the bioavailability of SPC administered on an empty stomach in a capsule form to cats is between 6-7%."

  Details and my dose-corrected re-derivation (6.6–8.8%) are in Q2. — [Webb et al. 2012, Intern J Appl Res Vet Med 10:107–112](https://jarvm.com/articles/Vol10Iss2/Vol10%20Iss2Webb.pdf)
- **(cat) [Review, same group]** "Oral bioavailability is enhanced to approximately 7% in cats due in part to limited glucuronidation capacity in this species." — [Hackett, Twedt & Gustafson 2013, JVIM 27:10](https://academic.oup.com/jvim/article/27/1/10/8451910)
- **(horse) [PR]** SPC (Siliphos), IV reference, parent silibinin assay: "Bioavailability of orally administered silibinin phospholipid was 0.6% PO in feed and 2.9% via nasogastric tube. During the multidose phase, silibinin had nonlinear pharmacokinetics." — [Hackett et al. 2013, Am J Vet Res, PMID 24066917](https://pubmed.ncbi.nlm.nih.gov/24066917/)
- **(horse) [Diss]** The same experiment in the author's dissertation (2011 draft), which used AUC0–8h for every route, gives about twice the published values: "Bioavailability for the oral fed silibyn phospholipids was 1.4% and nasogastric bioavailability was 5.0%." — [Hackett, CSU dissertation, "Silibinin pharmacology and opportunities for therapy in horses"](https://api.mountainscholar.org/server/api/core/bitstreams/9fb1847a-1008-412b-a925-9b308619899b/content)
- **(rat) [PR]** Plain silibinin, not SPC: "The oral bioavailability of silibinin in rats was estimated to be 0.73%." — [Wu et al. 2007, PMID 17692492](https://pubmed.ncbi.nlm.nih.gov/17692492/)

**Anchor data for measure (2), silybin absorbed in any form:**
- **(human) [PR]** Nine cholecystectomy patients with T-tube drainage were given a single oral dose of silipide (SPC) or silymarin, each 120 mg as silybin equivalents. "The amount of silybin recovered in bile in free and conjugated form within 48 h accounted for 11% of the dose after silipide and for 3% of the dose after silymarin." — [Schandalik, Gatti & Perucca 1992, Arzneimittelforschung 42:964, PMID 1329780](https://pubmed.ncbi.nlm.nih.gov/1329780/)
- **(human) [PR]** For SPC (IdB 1016): "Less than 3% of the administered dose was accounted for by urinary recovery of free plus conjugated silybin." — [Barzaghi et al. 1990, PMID 2088770](https://pubmed.ncbi.nlm.nih.gov/2088770/)
- **(human) [PR]** T-tube collection is incomplete: "Considering that through the T-tube only one to two thirds of the bile output can be collected and consequently analysed, the total amount of silybin eliminated via the bile must be estimated higher." — [Lorenz et al. 1981, PMID 7321653](https://pubmed.ncbi.nlm.nih.gov/7321653/)
- **(rat) [PR; Indena authors]** Silipide at 200 mg/kg:
  - Bile: "the biliary recovery after 24 h accounted for about 13% of the administered amount" (silymarin: "about 2%"). — [Morazzoni et al. 1993, PMID 8149949](https://pubmed.ncbi.nlm.nih.gov/8149949/)
  - Bile and urine in a second study: "Cumulative biliary (0-24 h) and urinary (0-72 h) excretion values after administration of IdB 1016 accounted for 3.73% and 3.26% of the administered dose." — [Morazzoni et al. 1992, PMID 1499596](https://pubmed.ncbi.nlm.nih.gov/1499596/)

**Relative data in dogs:**
- **(dog) [PR-ind]** SPC (Marin), about 16 mg/kg silybin, fed, total silybin: AUC0–24 was 11,200 ng·h/mL, against 3,720 and 2,520 ng·h/mL for silymarin extract. That is a 3.0–4.4-fold advantage. — [Filburn et al. 2007, PMID 17348898](https://pubmed.ncbi.nlm.nih.gov/17348898/)

**Doses from the labels [Mfr, retailer copies; verified in round 1]:**
- Coated medium tablet: 82 mg SPC = 24 mg silybin A+B. — [PetSmart](https://www.petsmart.com/dog/health-and-wellness/vitamins-and-supplements/nutramax-laboratories-veterinary-sciences-denamarin-dog-liver-health-supplement-medium-dogs-30ct-84087.html)
- Chewable: 82 mg SPC = 24 mg. — [1800PetMeds](https://www.1800petmeds.com/dog/otc-vitamins-and-supplements/product/nutramax-denamarin-liver-health-supplement-same-silybin/prod13991.html)
- Advanced Chewable, small–medium: 118 mg SPC = 35 mg; label for 15–25 lb is "Give 1/2". — [Banfield](https://shop.banfield.com/27063130BO.html)

### Inferences
**Ranking of candidate data for measure (1), intact systemic F [Extrap]:**

| Rank | Species, form | Fed or fasted | Assay | Value | Quality | Why this rank |
|---|---|---|---|---|---|---|
| 1 | Cat, Marin SPC capsule | Fasted 12 h | Free (parent) silibinin, LC-MS/MS, IV reference | 7% as reported; 6.6–8.8% dose-corrected | n=5; fixed order (oral, then IV); non-MEDLINE journal; IV curve above the assay's upper limit (Q2) | Same SPC, same fasted capsule condition, true absolute F. But cats glucuronidate poorly and the dose (~8–10 mg/kg) was 2–5 times the Denamarin label dose, so it probably **overstates** a dog's value. |
| 2 | Horse, Siliphos SPC by nasogastric tube | Feeding not stated | Free silibinin | 2.9% (5.0% in the dissertation) | n=9, MEDLINE journal | SPC in a species that glucuronidates well, but a herbivore gut. Analysis choice alone changed F about 2-fold. |
| 3 | Horse, SPC in feed | Fed | Free silibinin | 0.6% (1.4%) | Same study | Feed matrix plus herbivore; least like a fasted dog. |
| 4 | Dog, Marin SPC vs silymarin | Fed | Total silybin | Relative only, ×3.0–4.4 | n=8, industry | Right species, no absolute value. Used only as a cross-check (Q3). |
| 5 | Rat, plain silibinin | Not stated | — | 0.73% | — | Wrong form (not SPC). |
| — | Human | — | — | No IV-referenced oral F found | — | — |

**Recommended value for measure (1): ≈4%, plausible range 2–9%.** Three lines of reasoning point to the low single digits:
1. **Species bracket.**
   - Upper: the dose-corrected cat value, about 8–9%.
   - Lower: the horse nasogastric value, 2.9%.
   - Geometric midpoint: √(8.0 × 2.9) = 4.8%.

   A dog should sit below the cat for two reasons. It glucuronidates silybin efficiently, so less of the absorbed silybin stays intact. And at the label dose, saturable conjugation (the explanation offered for the horse nonlinearity) should be less saturated than at the cat's dose.
2. **Cross-study calculation from the dog's own total-silybin AUC** (Q3): central about 4.5%, extreme range 0.6–32%.
3. **Mechanistic check.** About 20% absorbed in any form (measure 2) × 4–25% of circulating silybin present as free drug (rat 4%, human 25%) gives roughly 1–5%.

The 2–9% range has a geometric centre of √(2 × 9) = **4.2%**, so I recommend **4%**.

**Ranking of candidate data for measure (2), absorbed in any form [Extrap]:**

| Rank | Data | Value | Strength | Weakness |
|---|---|---|---|---|
| 1 | Human SPC, bile collected by T-tube | 11% of dose in 48 h, free + conjugated; urine adds <3% | Same formulation class; dose of 120 mg ≈ 1.7 mg/kg, close to the dog label doses of 1.9–3.8 mg/kg; cholecystectomised patients, like this dog | T-tube drainage collects only part of the bile |
| 2 | Rat SPC | 7.0% (bile + urine) in one study; ≥13% (bile alone) in another | Complete bile collection | Dose of 200 mg/kg is about 100 times the dog's; rat |
| 3 | Human silymarin (Legalon), T-tube | 7–15% in 24 h | — | Not SPC |
| 4 | Cat | Implies at least the free F of 7–9% | — | Glucuronides were monitored but not reported |

**Recommended value for measure (2): ≈20%, plausible range 10–35%.**
- Floor: 11% (bile) + 2–3% (urine) = 13–14%.
- Allowing for incomplete T-tube collection (one-third to two-thirds of bile collected), 11% becomes 16.5–33% in bile. Adding about 2% urine gives roughly 19–35%.
- Lower plausible bound: about 10%, because the rat SPC figure of 7% shows lower values occur.
- Geometric centre of 10–35% is 18.7%, so I recommend **≈20%**.

**The final table (all [Extrap]; evidence grade: low for measure 1, low-to-moderate for measure 2):**

| Measure for SPC in a fasted dog | Best estimate (range) | Evidence grade | A: coated tablet, 24 mg | B: Chewable, 24 mg | C: Advanced Chewable ½ tablet, 17.5 mg | C: 1 tablet, 35 mg |
|---|---|---|---|---|---|---|
| (1) Intact (free) silybin reaching systemic blood | **4% (2–9%)** | Extrap from cat [PR] + horse [PR]; dog cross-check [PR-ind] | **0.96 mg** (0.48–2.16) | **0.96 mg** (0.48–2.16) | **0.70 mg** (0.35–1.58) | **1.40 mg** (0.70–3.15) |
| (2) Absorbed in any form (free + conjugated; bile + urine) | **20% (10–35%)** | Extrap from human SPC bile/urine [PR] + rat [PR] | **4.8 mg** (2.4–8.4) | **4.8 mg** (2.4–8.4) | **3.5 mg** (1.75–6.13) | **7.0 mg** (3.5–12.25) |
| (2a) Measured human floor: 11% bile + 2–3% urine | 13–14% | [PR] human | 3.1–3.4 mg | 3.1–3.4 mg | 2.3–2.5 mg | 4.6–4.9 mg |
| Sensitivity: cat F taken at face value | 7% | [PR] cat | 1.68 mg | 1.68 mg | 1.23 mg | 2.45 mg |

**Arithmetic** (absorbed mg = silybin dose × fraction):
- Measure (1):
  - 24 × 0.04 = 0.96; 24 × 0.02 = 0.48; 24 × 0.09 = 2.16.
  - 17.5 × 0.04 = 0.70; 17.5 × 0.02 = 0.35; 17.5 × 0.09 = 1.575.
  - 35 × 0.04 = 1.40; 35 × 0.02 = 0.70; 35 × 0.09 = 3.15.
- Measure (2):
  - 24 × 0.20 = 4.8; 24 × 0.10 = 2.4; 24 × 0.35 = 8.4.
  - 17.5 × 0.20 = 3.5; 17.5 × 0.10 = 1.75; 17.5 × 0.35 = 6.125.
  - 35 × 0.20 = 7.0; 35 × 0.10 = 3.5; 35 × 0.35 = 12.25.
- Floor (2a): 24 × 0.13–0.14 = 3.12–3.36; 17.5 × 0.13–0.14 = 2.28–2.45; 35 × 0.13–0.14 = 4.55–4.90.

**Per kg:** the doses are 2.64 mg/kg (24 mg), 1.92 mg/kg (17.5 mg) and 3.85 mg/kg (35 mg). At 4% and 20%, that is about 0.11 and 0.53 mg/kg absorbed for 24 mg.

**Why measure (2) matters more here.** The target organ is the liver. Silybin absorbed in any form travels through the portal vein to the liver before it reaches the systemic circulation, and bile is where most of it is excreted, so measure (2) is the closer proxy for "silybin delivered to the liver." Measure (1) is what a blood test of free silybin would see.

**Cross-check of measure (2) against the SPC advantage:**
- Human bile ratio, SPC vs silymarin: 11/3 = 3.7.
- Dog plasma AUC ratio: 3.0–4.4.

These agree, which supports transferring the human SPC recovery figures to the dog.

**Same-size caveat for all three products.** A, B and C use what appears to be the same SPC (about 29% silybin; round-1 notes). I have no data showing that the coating (A) or the chewable matrices (B, C) change silybin absorption, so the same percentages are applied to each. **The products differ only in dose**: C at ½ tablet gives 0.73 times, and C at 1 tablet 1.46 times, the exposure of A or B.

### Gaps
- No canine absolute F, no canine bile or urine recovery, and no canine dose-proportionality data. Every number above is an extrapolation; they are not measurements in dogs.
- The fasted versus fed direction for SPC is unknown in every species (Q7), so no food correction was applied.
- These estimates assume a healthy liver. Cholestasis or hepatocellular disease can raise plasma silybin several-fold. The JVIM 2013 review reports that "Drug exposure is increased 3- to 5-fold in people with hepatic disease." — [Hackett 2013](https://academic.oup.com/jvim/article/27/1/10/8451910)

---

## Q2. The cat study (Webb, Gustafson & Twedt 2012): what was dosed and measured, and is "7%" right?

### Takeaway
**7% is approximately right. The 24% reading is not supported.**
- Each cat received SPC from capsules that each held about 131 mg SPC, or 40 mg silibinin. The IV reference was 50 mg of silibinin per cat, at 90.5% purity.
- The cats were fasted for 12 h, and the assay measured **free (parent) silibinin** by LC-MS/MS, with no deconjugation step.
- The paper's 7% equals the raw ratio of oral to IV AUC (6.1/86.6 = 0.070), with no correction for dose.
- Correcting for the actual silibinin doses gives **6.6–8.8%**.
- Reading "10 mg/kg of SPC" literally (about 15 mg silibinin) would give 21–24%. That reading conflicts with the capsule contents and with the paper's own CL/F value.

### Cited Findings
All quotations are from the [Webb et al. 2012 PDF](https://jarvm.com/articles/Vol10Iss2/Vol10%20Iss2Webb.pdf) [PR] (cat).

**Design and doses:**
- Abstract: "Five adult cats were given a single oral dose (10 mg/kg) of SPC... Following a 2-week washout period, a single intravenous dose of SPC (50 mg/cat) was given." The abstract calls the IV dose "SPC"; the methods say it was silibinin.
- Methods, IV dose: "A single IV dose of silibinin (90.5% pure; 50 mg/cat dissolved in absolute ethanol) was administered to each cat via this catheter."
- Cats: "Their mean body weight was 4.8 ± 0.9 kg (range 3.8 to 5.6 kg)."
- Capsules: "The capsules were hand filled by using a Feton Capsule Filler and loader. Each capsule contained approximately 131 mg of SPC material... Each capsule delivered 40 mg of silibinin A+B by analytical analysis."
- Oral dose: "all five cats were administered 10 mg/kg of SPC as a powder combined with cornstarch (31% silibinin) in a capsule (Nutramax Laboratories, Inc....). Capsule administration was followed by 3 ml of water."

**Feeding and sedation:**
- "Prior to both the oral and intravenous portions of the study cats were held off food for 12 hours, and central IV catheters were placed under ketamine sedation."
- Order was fixed, oral first: "Following a 14-day washout period, central IV catheters were again placed in the same five cats."

**Assay (free silibinin):**
- Plasma "extracted with 1 ml of acidified ethyl acetate (0.1 % formic acid)". No β-glucuronidase or sulfatase step is described.
- Quantification was "by monitoring the transition m/z 481 to m/z 125 for the analyte silibinin".
- "The glucoronide conjugates of silibinin were monitored at m/z 657 to 481", but no glucuronide results are reported.
- "Lower and upper limits of detection were 2.5 and 5000 ng/ml."

**Results (Table 1):**

| Parameter | IV | Oral |
|---|---|---|
| Cmax (µM) | 87.1 ± 44.2 | 5.8 ± 3.1 |
| AUC0–∞ (µM·h) | 86.6 ± 81.4 | 6.1 ± 3.5 |
| t½ (h) | 2.51 ± 1.63 | 3.16 ± 1.74 |
| Vz/F (L) | 5.65 ± 3.66 | 309 ± 165 |
| CL/F (L/h) | 1.88 ± 0.99 | 74.7 ± 47.1 |

**Conclusions:**
- "Based on this data, the oral bioavailability (F) was calculated to be approximately 0.07 (7%)."
- "the bioavailability of SPC administered on an empty stomach in a capsule form to cats is between 6-7%."

**Funding and product:**
- "This study was supported through a grant from the Winn Feline Foundation."
- Footnote: "Found in Marin®, Nutramax Laboratories, Inc."

**Earlier version [Diss, citing an Abstract]:** The data were first presented at the ACVIM Forum in 2008 and cited as "6-7% in cats". Reference 73 reads "Webb CB, Samber BJ, Gustafson DL, et al. ... Proceedings of the ACVIM Forum 2008; San Antonio, TX:361". — [Hackett dissertation](https://api.mountainscholar.org/server/api/core/bitstreams/9fb1847a-1008-412b-a925-9b308619899b/content)

### Inferences
**Re-deriving F under each reading of the oral dose [Extrap].** Raw AUC ratio = 6.1 / 86.6 = 0.0704. F = 0.0704 × (IV silibinin dose ÷ oral silibinin dose). The IV dose is either 45.25 mg (purity-adjusted, 50 × 0.905) or 50 mg (nominal).

| Reading of the oral dose | Oral silibinin per cat | F (IV 45.25 mg) | F (IV 50 mg) | Consistent with the methods? |
|---|---|---|---|---|
| Paper's implicit assumption: oral dose = IV dose | — | 7.0% | 7.0% | — |
| "10 mg/kg" meaning silibinin (4.8 kg × 10) | 48 mg | 6.6% | 7.3% | Yes; reproduces "6–7%" |
| One capsule | 40 mg (8.3 mg/kg; 7.1–10.5 mg/kg across body weights) | 8.0% | 8.8% | Yes; best fit to "each capsule delivered 40 mg" |
| "10 mg/kg of SPC" read literally | 48 mg SPC × 31% = 14.9 mg | 21.4% | 23.7% | **No**: one 131 mg capsule cannot deliver 48 mg SPC; it would need about ⅓ of a capsule |
| Ratio of reported clearances, 1.88 / 74.7 | — | 2.5% | 2.5% | **No**: see the check below |

**Internal-consistency check of the CL/F values [Extrap]:**
- With between-cat variability, the mean of individual Dose/AUC values is about Dose / mean(AUC) × (1 + CV²).
  - Oral: CV = 3.5/6.1 = 0.57, so the factor is 1.33.
  - IV: CV = 81.4/86.6 = 0.94, so the factor is 1.88.
- **IV:** 1.88 L/h = D / 86.6 × 1.88, so D ≈ 86.6 µmol ≈ 41.7 mg. This matches the 45.25 mg of pure silibinin actually given, so the IV clearance was computed with the real dose.
- **Oral:** 74.7 L/h = D / 6.1 × 1.33, so D ≈ 343 µmol ≈ **165 mg**.
  - An input of 40 mg silibinin would have produced CL/F ≈ 18 L/h.
  - An input of 48 mg would have produced about 22 L/h.
  - An input of 131 mg (the SPC mass of one capsule) produces about 59 L/h, which is within the sampling noise of n = 5.

  So the reported oral CL/F and Vz/F look as if they were computed with the **SPC mass (about 130–165 mg)** as the dose, not the silibinin content.
- **Conclusion:**
  - The oral dose was at least one full capsule, which rules out the literal "10 mg/kg SPC" (24%) reading.
  - The headline F was taken as the plain AUC ratio, effectively treating the oral and IV silibinin doses as equal.
  - Best dose-corrected cat F: **about 7–9%** (6.6–8.8%).
  - The CL/F-based 2.5% is an artefact of the dose units.

**Quality caveats that widen the cat number's uncertainty [Extrap from cited facts]:**
1. The IV Cmax of 87.1 µM is about 42,000 ng/mL. That is roughly 8 times the stated 5,000 ng/mL upper limit of the assay, and the paper does not say whether samples were diluted.
2. IV AUC varied enormously (CV 94%), which is unusual for an IV dose. With n = 5 the mean is imprecise: the t-based 95% CI is about ±101 µM·h around 86.6.
3. The order was fixed (oral, then IV), with ketamine sedation for catheter placement and an ethanol IV vehicle.
4. **Only free silibinin was measured.** In cats ("limited glucuronidation capacity"), free silibinin is a larger share of what is absorbed than in dogs. The cat F therefore probably overstates a dog's free-silybin F.

### Gaps
- The ACVIM 2008 abstract (VIN) needed a login, so I could not check whether it states the dose differently.
- The paper gives no individual-cat data, so per-cat F and its spread cannot be recomputed.
- The silibinin glucuronide data that were "monitored" are not reported. Fa in cats therefore cannot be computed.

---

## Q3. Is there an IV silybin study in dogs? A cross-study estimate of absolute F in dogs

### Takeaway
**No canine IV silybin pharmacokinetic study with usable numbers was found** in English, Chinese or German searches.
- One Chinese beagle study (Wang 2010, Nanotechnology) gave silybin nanosuspensions both orally and IV. Its abstract gives no numbers and the full text is paywalled.
- Combining Filburn's fed, total-silybin dog AUC with cat and horse IV clearances and human or rat free-to-total ratios gives a **central F of about 4.5%, with an extreme range of 0.6–32%**. That is too uncertain to stand alone, but it is consistent with the recommended 2–9%.

### Cited Findings
- **(dog) [PR]** Oral plus IV nanosuspension study in beagles. The abstract reports only that oral nanosuspensions "significantly increase its bioavailability compared to the coarse powder" and that, "for intravenous infusion the lower pressure produced silybin nanosuspensions appeared to maintain a more sustained drug release profile." It gives no AUC, dose or F. — [Wang et al. 2010, Nanotechnology 21:155104, PMID 20332565](https://pubmed.ncbi.nlm.nih.gov/20332565/); the [IOPscience full text](https://iopscience.iop.org/article/10.1088/0957-4484/21/15/155104) is paywalled.
- **(dog) [PR]** A Chinese beagle study of silymarin phospholipid-complex controlled-release tablets against a commercial silymarin capsule (Legalon) at 30 mg/kg reports relative bioavailability only, according to its abstract snippet: "AUC_0→24分别为（2.996 8±0.583 3）、（2.268 9±0.432 8） h·μg/ml" and "相对生物利用度为（162.21±30.82）%". It has no IV arm. — [曾棋平 et al. 2023, 药学实践杂志](https://yxsj.smmu.edu.cn/article/id/e09da4c8-ee52-4150-8eb6-5f25ef788b3d)
- **(cat) [PR]** IV silibinin, about 9.4 mg/kg pure (45.25 mg per 4.8 kg cat): AUC 86.6 µM·h, i.e. 41,780 ng·h/mL; CL 1.88 L/h. — [Webb 2012](https://jarvm.com/articles/Vol10Iss2/Vol10%20Iss2Webb.pdf)
- **(horse) [Diss]** IV silibinin 6.5 mg/kg: Cmax 19.3 ± 3.58 µM; AUC0–8h 7.45 ± 1.18 µM·h. The assay used the same ethyl acetate extraction and m/z 481→125 parent-silibinin transition as the cat study. — [Hackett dissertation](https://api.mountainscholar.org/server/api/core/bitstreams/9fb1847a-1008-412b-a925-9b308619899b/content)
- **(human) [PR]** After 80 mg silybin as silipide: "AUC values for conjugated sylibin were about three-fold greater than those of free drug." — [Gatti & Perucca 1994, PMID 7874377](https://pubmed.ncbi.nlm.nih.gov/7874377/)
- **(rat) [PR]** After IdB 1016: "Mean AUC (0-6 h) values were 9.78 and 232.15 h.micrograms.ml-1 indicating that about 94% of the plasma silybin is present in a conjugated form." — [Morazzoni 1992, PMID 1499596](https://pubmed.ncbi.nlm.nih.gov/1499596/)
- **(dog) [PR-ind]** SPC at about 16 mg/kg, fed: total-silybin AUC0–24 11,200 ng·h/mL. — [Filburn 2007](https://pubmed.ncbi.nlm.nih.gov/17348898/)
- **Search coverage:**
  - English: PubMed and Europe PMC via round 1, plus web searches for silybin or silibinin with intravenous, beagle and absolute bioavailability.
  - Chinese: 水飞蓟宾 Beagle犬 静脉 药动学 / 绝对生物利用度 / 纳米混悬剂.
  - German: Silibinin Hund Pharmakokinetik intravenös.
  - Patents: a Chinese silybin-injection patent ([US10314923](https://patents.google.com/patent/US10314923B2/en)) contains formulation data only, no dog pharmacokinetics.

### Inferences
**Cross-study calculation [Extrap; shown so it can be checked, not as a measurement]:**
- F_dog = CL_dog × AUC_free,dog ÷ Dose.
- Filburn's total-silybin AUC per mg/kg = 11,200 ÷ 16 = 700 ng·h/mL per mg/kg, i.e. 0.70 mg·h/L. (Using 14.25 or 17.55 mg/kg instead gives 786 or 638.)
- AUC_free = f_free × 0.70, where f_free is the free share of total plasma silybin. It is unknown in dogs:
  - human silipide: 1/(1+3) = 0.25;
  - rat: 9.78/232.15 = 0.042.
- CL_dog for free silibinin is unknown:
  - cat: 9.43 mg/kg ÷ 41.78 mg·h/L = 0.23 L/h/kg (0.39 using the paper's mean CL ÷ 4.8 kg); a poor glucuronidator, so likely a low value;
  - horse: 6.5 ÷ (7.45 × 0.48244) = 1.81 L/h/kg; good glucuronidation.
- Therefore **F_dog = 0.70 × f_free × CL**:

| Assumptions | F_dog |
|---|---|
| Low: f_free 0.04, CL 0.23 | 0.70 × 0.04 × 0.23 = **0.6%** |
| High: f_free 0.25, CL 1.81 | 0.70 × 0.25 × 1.81 = **32%** |
| Central (geometric means): f_free 0.10, CL 0.64 | 0.70 × 0.10 × 0.64 = **4.5%** |

- **Caveats:**
  - Filburn's assay was "total" silybin with background subtraction and an unverified hydrolysis method. The cat and horse assays measured free silibinin.
  - Filburn's dogs were fed; the cats were fasted.
  - The dose (16 mg/kg) was about 6 times the label dose, and horses showed nonlinearity.
  - Neither CL nor f_free has been measured in dogs.

  Treat this only as a consistency check: it lands in the same low-single-digit zone as the species bracket.
- **Dose-normalised exposure comparison [Extrap]:**
  - Cat free-silibinin AUC: 2,943 ng·h/mL ÷ 8.33 mg/kg = 353 per mg/kg.
  - Dog total-silybin AUC: 700 per mg/kg.

  Even counting conjugates, the dog's exposure per mg/kg is only 2 times the cat's exposure to free drug. If 4–25% of the dog's total is free, the dog's free exposure per mg/kg is about 0.1–0.5 times the cat's. That supports placing dog F at or below the cat value unless dog clearance is much higher.

### Gaps
- Wang 2010 (beagle, oral + IV nanosuspension) may contain the only canine IV silybin AUC. The full text was paywalled (IOPscience), and a Chinese thesis version was not found. If obtained, it would give an absolute F for silybin coarse powder in beagles, which could be scaled by the SPC advantage (3–4.4 times).
- No canine study measured both free and conjugated silybin, so f_free for dogs is unknown.

---

## Q4. Filburn 2006 and 2007: assay, feeding, dose, and what they allow

### Takeaway
- **Dose per dog:** 178 mg silybin A+B as SPC (Marin), in 10.14–12.49 kg beagles, i.e. 14.3–17.6 mg/kg (the manufacturer says 16 mg/kg).
- **Feeding:** the dose was given **on a full stomach**, after a first attempt in fasted dogs caused vomiting.
- **Assay:** "total silybin" by an outside lab (B.T. Biotecnica, Varese, Italy), with background subtraction. The hydrolysis step is not described in any accessible text.
- **What the data allow:** no IV arm and no bile or urine collection, so neither F nor Fa can be computed. Only relative bioavailability (3.0–4.4 times silymarin by AUC) and an apparent oral clearance of total silybin are available.

### Cited Findings
All [PR-ind] (dog).

**Dose (2006):** "On Day 1 of dosing, dogs received 178 mg silybin (A+B) equivalents complexed with phosphatidylcholine (SPC), 616 IU dα-tocopheryl acetate, and 118 mg elemental zinc as zinc gluconate (Marin®...), along with 10 mL of water to assure timely entry into the stomach." The dogs weighed "10.14-12.49 kg". — [Filburn 2006 PDF](https://jarvm.com/articles/Vol4Iss4/Griffin.pdf)

**Feeding (2006):**
- "Initial dosing at 118 mg of elemental zinc after a 23-hour fast resulted in vomiting. All dogs consumed this same level when administered on a full stomach with no vomiting."
- "Dosing following food intake was necessary at these higher levels for full acceptance of the supplement and avoidance of inappetence or emesis."

— [Filburn 2006](https://jarvm.com/articles/Vol4Iss4/Griffin.pdf)

**Diet (2006):** the dogs ate "a standard colony diet (Joy Special Meal...) that contained not less than 26% protein and 12% fat." — [Filburn 2006](https://jarvm.com/articles/Vol4Iss4/Griffin.pdf)

**Sampling and assay (2006):**
- Samples were taken "24 hours and immediately prior to dosing, then at 0.5, 1, 2, 4, 6, 8, and 24 hours."
- "Plasma or serum samples were analyzed for silybin (A+B) (B.T. Biotecnica, Varese, Italy)." No method details are given.

— [Filburn 2006](https://jarvm.com/articles/Vol4Iss4/Griffin.pdf)

**Assay wording and background subtraction (2007 and 2013):**
- The 2007 abstract reports values "for total silybin". — [PubMed 17348898](https://pubmed.ncbi.nlm.nih.gov/17348898/)
- The 2013 Nutramax letter's figure legend says values are "after subtraction of background peaks averaged for days 1 and 0". — [JVIM 2013 letter](https://academic.oup.com/jvim/article/27/4/755/8451857)

**Comparisons drawn by the authors (2006):**
- Marin exposure "and bioavailability assessed as area-under-the-curve over 24 hours were comparable to those observed in humans and twice that shown in beagle dogs after adjusting for dose."
- Reference 82 is the silymarin-proliposome beagle study: "Yan-Yu X ... Preparation of silymarin proliposome: A new way to increase oral bioavailability of silymarin in beagle dogs. Int J Pharmaceut 2006;319:162-168."
- The authors also cite their reference 80 for "dogs with ... a different type of silybin:phosphatidylcholine mixture", but reference 80 is a rat study (Yanyu 2006, Int J Pharm 307:77–82). This is an apparent citation error.

— [Filburn 2006](https://jarvm.com/articles/Vol4Iss4/Griffin.pdf)

**Course:** levels showed "an increase to a maximum of 1.31 ± 0.31 μg/mL at 3 hrs, followed by a return to background levels at 24 hrs." — [Filburn 2006](https://jarvm.com/articles/Vol4Iss4/Griffin.pdf)

**Full text of the 2007 paper not reachable:** Wiley `/doi/pdf/` and `/doi/full/` both returned HTTP 403 in this round; Semantic Scholar returned 403; the Unpaywall API required a personal email, which I did not send.

### Inferences
**Apparent oral clearance of total silybin [Extrap]:** CL/F = Dose ÷ AUC.
- SPC: 16 mg/kg ÷ 11.2 mg·h/L = 1.43 L/h/kg.
- Silymarin arms: 16 ÷ 3.72 = 4.3 L/h/kg and 16 ÷ 2.52 = 6.3 L/h/kg.

These describe exposure only. Without IV data they cannot be split into absorption and elimination.

**"Total" probably means free plus conjugated silybin after enzymatic deconjugation.** That is how the Indena-linked literature of the period uses the term (for example, Morazzoni 1993 refers to "total (free + unconjugated drug)" [sic]). It is unverified for B.T. Biotecnica's method. If "total" were actually parent-only, Filburn's dog exposure would be even closer to the cat's. [Extrap]

**The dog data are fed-state, high-dose data.** They support "SPC is about 3 times better than silymarin in dogs," not an absolute absorption percentage at label dose on an empty stomach.

### Gaps
Unverified because the 2007 full text was blocked:
- the hydrolysis or deconjugation method;
- whether the silymarin comparison was a crossover, with what washout;
- the feeding state of the silymarin arms;
- half-life;
- individual-dog data.

---

## Q5. Biliary and urinary recovery in humans and rats: how much silybin is absorbed in any form?

### Takeaway
- **Humans, SPC:** about 11% of an oral SPC dose (120 mg silybin) was recovered in bile as free plus conjugated silybin within 48 h, against 3% for silymarin. Urine adds under 3%.
- **T-tube drainage collects only one-third to two-thirds of bile output**, so these are minimum values. Correcting gives roughly 19–35% for SPC in any form.
- **Rats, SPC:** 7% (bile + urine) and 13% (bile alone) in two studies.
- These are the best available measures of silybin "absorbed in any form." The patients had no gallbladder, as this dog has none. However, their bile was diverted externally, so their absorption may have been, if anything, lower than in the dog.

### Cited Findings
**Schandalik 1992 (human) [PR]. Design:** "The biliary excretion of silybin... was evaluated by using a specific HPLC method in 9 cholecystectomy patients with T-tube drainage following single oral doses of silipide... and of silymarin (120 mg, expressed as silybin equivalents)."

**Schandalik 1992 results:**
- "After intake of silipide, the concentration of silybin in bile reached a peak within 4 h and declined thereafter with a mean time of about 10 h."
- "The amount of silybin recovered in bile in free and conjugated form within 48 h accounted for 11% of the dose after silipide and for 3% of the dose after silymarin."
- "Plasma silybin concentrations, determined in 3 subjects, were several-fold lower than those in bile after intake of silipide and mostly undetectable after intake of silymarin."
- "This results in increased delivery of the compound to the liver, which represents the target organ for pharmacological action."

The abstract does not state fasting status. — [PubMed 1329780](https://pubmed.ncbi.nlm.nih.gov/1329780/)

**Barzaghi 1990 (human) [PR], SPC:** "Most of the silybin present in the systemic circulation was in conjugated form. Less than 3% of the administered dose was accounted for by urinary recovery of free plus conjugated silybin, a significant proportion of the dose probably being excreted in the bile." — [PubMed 2088770](https://pubmed.ncbi.nlm.nih.gov/2088770/)

**Gatti & Perucca 1994 (human) [PR], 80 mg silybin as silipide:**
- "Free silybin concentrations reached a peak of 141 +/- 31 ng/ml (mean +/- SEM) at 2.4 hours."
- "AUC values for conjugated sylibin were about three-fold greater than those of free drug."

— [PubMed 7874377](https://pubmed.ncbi.nlm.nih.gov/7874377/)

**Lorenz 1981 (human) [PR], silymarin (Legalon), T-tube:**
- "approx. 7-15% of its main component silybin was determined in the 24 h-bile of 10 cholecystectomized patients with T-drainage. In one case the value was 25%."
- "through the T-tube only one to two thirds of the bile output can be collected."

— [PubMed 7321653](https://pubmed.ncbi.nlm.nih.gov/7321653/)

**Lorenz 1984 (human) [PR], silymarin:**
- After 560 mg silymarin (240 mg silibinin), "renal excretion... amounted to only 1-2% of the silibinin dose over 24 hours."
- In T-tube bile after 140 mg silymarin, concentrations were "approximately 100 times higher than in the serum".
- "complete collection of bile from these patients was impossible."

— [PubMed 6513680](https://pubmed.ncbi.nlm.nih.gov/6513680/)

**Morazzoni 1993 (rat) [PR; Indena], silipide 200 mg/kg:**
- Biliary recovery after 24 h was "about 13% of the administered amount", against about 2% for silymarin.
- "The relative bioavailability of silipide (calculated in the target organ as the ratio between AUCs of cumulative biliary excretion curves) was 10-fold higher than that of silymarin."

— [PubMed 8149949](https://pubmed.ncbi.nlm.nih.gov/8149949/)

**Morazzoni 1992 (rat) [PR; Indena]:**
- IdB 1016: bile 0–24 h 3.73%, urine 0–72 h 3.26%.
- Plain silybin: "only 0.001% and 0.032% of the dose respectively".

— [PubMed 1499596](https://pubmed.ncbi.nlm.nih.gov/1499596/)

**Review [Review]:** "Only about 1%-5% of the administered dose is eliminated by the kidneys." — [Tvrdý et al. 2021, PMID 33587317](https://pubmed.ncbi.nlm.nih.gov/33587317/) (from round 1)

### Inferences
**Fa for SPC in humans [Extrap].**
- Measured floor: 11% (bile, 48 h) + about 2–3% (urine, from a different study, Barzaghi) ≈ **13–14%**.
- Correcting for incomplete T-tube collection: 11% ÷ ⅔ = 16.5%; ÷ ½ = 22%; ÷ ⅓ = 33%. Adding about 2% urine gives **≈19–35%**.
- I took **20% as the central value** and **10–35% as the range**. The lower end allows for the rat SPC figure of 7%.

**The human study fits the case well.**
- Its 120 mg dose (about 1.7 mg/kg in a 70 kg adult) is close to the dog doses of 1.9–3.8 mg/kg.
- It is the only SPC study in **cholecystectomised** subjects, and this dog has no gallbladder.

**How its conditions differ from the dog's.** The T-tube diverted bile out of the body. That interrupts enterohepatic recycling and lowers intestinal bile, which could reduce absorption of a phospholipid complex. A cholecystectomised dog with normal bile flow into the duodenum may therefore absorb as much or more. [Extrap]

**Silymarin data from the same patients.** Silymarin gave 3% in the same patients, so SPC delivered 3.7 times more silybin to bile. This matches the dog plasma AUC advantage of 3.0–4.4. [Extrap]

**What bile plus urine recovery leaves out.** It is a lower bound for Fa. It misses:
- conjugates formed in the gut wall and pumped back into the gut lumen (not "absorbed" in the sense relevant to the liver anyway);
- metabolites the assay did not measure;
- tissue retention.

### Gaps
- The Schandalik 1992 full text (Arzneimittelforschung) was not accessed. Not verified:
  - fasting status;
  - per-subject bile volumes;
  - whether completeness of the T-tube collection was measured;
  - free vs conjugated split in bile;
  - whether the 11% applies to the silipide arm in all 9 patients.
- No canine bile or urine recovery data exist for silybin in any form.

---

## Q6. Where does "ordinary silymarin is only 30–50% absorbed" (普通水飞蓟素口服只吸收 30–50%) come from?

### Takeaway
**I found no primary measurement behind "30–50%".** The published versions are "20–50%" (a 2011 review citing a 2009 review) and "23–47%" (repeated in many 2021–2024 formulation papers, which cite secondary sources and even an unrelated griseofulvin paper). The attribution to Flora 1998 could not be checked because the paper is paywalled.

These figures describe **gastrointestinal absorption in any form for silymarin in humans**, not intact systemic bioavailability. They are well above the measured human recovery for plain silymarin (3% in bile in Schandalik; 7–15% in T-tube bile and 1–2% in urine in Lorenz). **They should not be used for Denamarin.** If plain silymarin really absorbed 30–50%, SPC's 3–4.4-fold advantage would imply more than 100%, which is impossible.

### Cited Findings
- **"20–50%" [Review]:** "Only 20-50 percent of oral silymarin is absorbed from the gastrointestinal tract where it undergoes extensive enterohepatic circulation. Therefore, absorption of silymarin from the gastrointestinal tract is low, making [its] bioavailability poor.13" Reference 13 is "Wu JW, Lin LC, Tsai TH. Drug-drug interactions of silymarin on the perspective of pharmacokinetics. J Ethnopharmacol 2009;121:185-193", itself a review. — [Javed, Kohli & Ali 2011, Altern Med Rev 16:239](https://www.e-lactancia.org/media/papers/CardoMarianoSilimarina-AltMedRev2011.pdf)
- **"23–47%" [Review/secondary], with circular citations:**
  - "poor water-solubility... results in low oral bioavailability (23–47%) and large variability in the absorption [13,14,15]". The references are Kumar 2014 (silymarin liposomes), Sahibzada 2017 (silibinin nanoparticles) and Fujioka 2007, which is about griseofulvin. — [PMC11359960 (2024)](https://pmc.ncbi.nlm.nih.gov/articles/PMC11359960/)
  - "low bioavailability (23–47%)... [9,10,11]". The references are Javed 2011, Schulz 1995 and Morazzoni 1993 (rats). — [Song et al. 2021, PMC8146637](https://pmc.ncbi.nlm.nih.gov/articles/PMC8146637/)
  - "systemic absorption is about 23–47%. 1, 2". The references are Wu 2007 (rat F 0.73%) and Ghosh 2010. — [PMC10536084 (2023)](https://pmc.ncbi.nlm.nih.gov/articles/PMC10536084/)
- **Flora 1998:** the abstract has no absorption figure. — [Flora et al. 1998, PMID 9468229](https://pubmed.ncbi.nlm.nih.gov/9468229/). The full text redirected to Ovid, which returned HTTP 402, so the "23–47%" attribution remains unverified.
- **Primary human silymarin recovery data [PR]:**
  - 3% of the silybin dose in bile in 48 h. — [Schandalik 1992](https://pubmed.ncbi.nlm.nih.gov/1329780/)
  - 7–15% (one patient 25%) in 24 h T-tube bile, with T-tube collection of "one to two thirds" of bile. — [Lorenz 1981](https://pubmed.ncbi.nlm.nih.gov/7321653/)
  - 1–2% in urine over 24 h. — [Lorenz 1984](https://pubmed.ncbi.nlm.nih.gov/6513680/)
  - An earlier German T-tube study exists, but PubMed has no abstract for it, so its numbers are unverified. — [Flory et al. 1980, Planta Med, PMID 7367491](https://pubmed.ncbi.nlm.nih.gov/7367491/)

### Inferences
- **A possible origin, which I could not verify:** a 20–50% range is what you get if you correct Lorenz's 7–15% T-tube recovery for one-third to two-thirds collection (7 ÷ ⅔ ≈ 10%; 15 ÷ ⅓ = 45%). Lorenz used Legalon, a pharmaceutical silymarin. Schandalik's silymarin gave only 3%, which suggests silymarin products differ widely. [Extrap]
- **Whatever its origin**, the user's "30–50%" is at most a fraction absorbed in any form for some silymarin products in humans. It is not the amount of intact silybin reaching the blood, and it is not about SPC or dogs. It should be dropped or relabelled in the comparison table.

### Gaps
- Flora 1998 (Ovid paywall), Wu 2009 (J Ethnopharmacol) and Saller 2001 (Drugs) were not read in full, so the earliest source of "20–50%" or "23–47%" remains unidentified.
- An archive.org Scholar search was rate-limited. A SciSpace copy of a review returned an empty page.

---

## Q7. Fed vs fasted, and a dog without a gallbladder

### Takeaway
**No fed-versus-fasted study of silybin or SPC was found in any species**, in English or Chinese searches. The indirect evidence points both ways:
- Feed lowered SPC bioavailability about 4–5-fold in horses.
- An oily softgel tripled human Cmax.
- The only dog SPC data were obtained fed.

I therefore applied no food correction. In a dog without a gallbladder, bile enters the duodenum continuously, so the fed–fasted difference in intestinal bile is probably smaller than in an intact dog. This is an inference, not data.

### Cited Findings
- **(horse) [PR]:** "0.6% PO in feed and 2.9% via nasogastric tube." — [Hackett 2013 AJVR](https://pubmed.ncbi.nlm.nih.gov/24066917/)
- **(horse) [Diss]:** "Relative oral bioavailability of silybin phospholipid compared to nasogastric administration was 28%." The carrier meal is described only for the phase-II dose-escalation part ("400 g pelleted feed..., 50 g wheat bran, and 150 mL water"). The feeding status of the phase-I nasogastric and IV arms is not stated. — [Hackett dissertation](https://api.mountainscholar.org/server/api/core/bitstreams/9fb1847a-1008-412b-a925-9b308619899b/content)
- **(dog) [PR-ind]:** the dose was given on a full stomach after fasted dosing caused vomiting (quotes in Q4). — [Filburn 2006](https://jarvm.com/articles/Vol4Iss4/Griffin.pdf)
- **(cat) [PR]:** fasted 12 h; the result was described as "bioavailability of SPC administered on an empty stomach". — [Webb 2012](https://jarvm.com/articles/Vol10Iss2/Vol10%20Iss2Webb.pdf)
- **(human) [Review; Thorne Research, a Siliphos seller]:** in 12 subjects given 80 mg silybin as phytosome, "The maximum plasma concentration attained from the softgel was three times greater than from the hardgel." — [Kidd & Head 2005, PMID 16164374](https://pubmed.ncbi.nlm.nih.gov/16164374/) (round 1)
- **(human) [PR]:** a modern SPC study dosed after a 10-hour fast. — [Méndez-Sánchez 2019, PMC6330464](https://pmc.ncbi.nlm.nih.gov/articles/PMC6330464/) (round 1)
- **Searches that found no food-effect study:**
  - Chinese: 水飞蓟宾胶囊 空腹 餐后 生物等效性. Results were consumer pages and labels only.
  - English: "silybin phosphatidylcholine complex food effect fed fasted". Results were comparisons against silymarin only.

### Inferences
- **The label's empty-stomach instruction is a SAMe rule** (round 1). For silybin, there is no evidence that fasting helps or hurts. The recommended 4% and 20% are anchored on fasted cat data and, probably, fasted human data, so they apply to the labelled fasted use, though with large uncertainty. [Extrap]
- **Dog without a gallbladder:**
  - Continuous bile flow means some bile is in the duodenum even when fasted, which could help disperse the phospholipid complex.
  - Bile also reaches the gut more often, so biliary silybin conjugates are recycled (enterohepatic circulation) more often.
  - Both effects would push the true Fa towards or above the central estimate rather than below it. This is unquantified. [Extrap]

### Gaps
- No silybin or SPC food-effect pharmacokinetic study in dogs, cats, humans or rats was found.
- No study of silybin pharmacokinetics in cholecystectomised dogs exists.
