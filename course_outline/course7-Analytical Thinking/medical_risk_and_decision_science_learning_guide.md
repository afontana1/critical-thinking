# Learning Guide: Medical Risk, Clinical Epidemiology, and Decision Science

**A structured, quantitative curriculum for a reader with a background in finance, economics, project management, and systems engineering**  
**Suggested pace:** 12 weeks, roughly 3–5 hours per week (or use as a self-paced syllabus)  
**Prerequisites:** Comfort with probabilities, ratios, decision trees, and basic statistical inference. No clinical training assumed.

> **Purpose:** Learn how medical professionals estimate and communicate risk, evaluate evidence, and make decisions under uncertainty. This is an educational guide, not a framework for self-diagnosing or independently making treatment decisions. All numerical cases below are hypothetical unless explicitly identified as research findings.

## Contents

1. [How to use this guide](#1-how-to-use-this-guide)
2. [The conceptual map: from risk estimate to medical decision](#2-the-conceptual-map-from-risk-estimate-to-medical-decision)
3. [Twelve-week learning plan](#3-twelve-week-learning-plan)
4. [The integrated practice case](#4-the-integrated-practice-case)
5. [Medical risk formula sheet](#5-medical-risk-formula-sheet)
6. [A practical framework for interrogating medical risk claims](#6-a-practical-framework-for-interrogating-medical-risk-claims)
7. [Resource library with links](#7-resource-library-with-links)
8. [Capstone assignment and reusable template](#8-capstone-assignment-and-reusable-template)
9. [Answer key and self-assessment](#9-answer-key-and-self-assessment)

---

## 1. How to use this guide

### The main path

The recommended sequence is deliberate:

1. **BMJ and Oxford Centre for Evidence-Based Medicine (CEBM):** Learn the language of medical risk and diagnostic reasoning.
2. **Clinical epidemiology:** Understand the populations, study designs, and data-generating processes behind the estimates.
3. **Critical appraisal and evidence synthesis:** Judge how much confidence to place in published estimates.
4. **Medical decision analysis:** Combine probabilities with benefits, harms, utilities, and timing.
5. **Health economics and causal inference:** Evaluate resource tradeoffs and distinguish predictive associations from treatment effects.

Read **selectively**, not cover-to-cover. Book assignments identify topics or verified chapter titles; use the relevant sections of your edition. The free resources are enough to complete the foundational exercises. The paid textbooks support a much deeper treatment.

### Keep four running artifacts

- **Risk glossary:** One sentence, formula, appropriate use case, and common misinterpretation for each measure.
- **Evidence ledger:** For every study, capture population, comparator, outcome, horizon, effect measure, uncertainty, and biases.
- **Decision model:** A spreadsheet or small Python notebook containing a two-arm comparison, Bayes calculations, and eventually a decision tree.
- **Decision memo:** A one-page explanation of an actual *published* clinical result, translated into absolute risks and decision-relevant terms. Use no identifiable personal health information.

### Weekly study pattern

- **Read (60–120 min):** Follow the core links and selective textbook assignments.
- **Model (45–90 min):** Reproduce a calculation or build an example.
- **Explain (20–30 min):** Write a plain-language interpretation as though you were speaking to a non-technical patient.
- **Audit (15–30 min):** Identify unspoken assumptions, missing denominators, time horizons, and limitations.

### Milestones

| After | You should be able to… | Deliverable |
|---|---|---|
| Week 3 | Decode RR, OR, HR, absolute risk, NNT, test accuracy, and timing | Risk glossary + numerical worksheet |
| Week 6 | Critically appraise a study and a systematic review | One-page evidence appraisal |
| Week 9 | Structure treatment options with probabilities and outcome utilities | Decision tree + sensitivity table |
| Week 12 | Explain a medical decision using evidence, causal reasoning, and uncertainty | Final decision memo |

---

## 2. The conceptual map: from risk estimate to medical decision

Medical risk analysis comprises related but distinguishable questions:

| Question | Main discipline | Closest analogy from your background |
|---|---|---|
| How often does an event occur? | Epidemiology / biostatistics | Failure probability, event frequency |
| What changes the event probability? | Clinical epidemiology | Comparative scenario analysis |
| Can this study support a causal claim? | Causal inference | Econometric identification |
| How trustworthy and portable is the estimate? | Evidence-based medicine | Model validation, external validity, evidence quality |
| What will new diagnostic evidence tell us? | Diagnostic decision analysis | Bayesian updating |
| What should we do given benefits, harms, and preferences? | Medical decision analysis | Expected utility and decision theory |
| What is the impact over many years? | Survival analysis / state-transition modeling | Hazard models, Markov processes |
| Are benefits worth additional resources? | Health economics | Cost-effectiveness and constrained optimization |

**Crucial distinction:** In epidemiology, *risk* commonly denotes the probability of a specified event over a specified period. In finance, risk may denote volatility, tail loss, or dispersion. In medical decision analysis, consequences and preferences enter separately through utility or outcome-value models. Do not assume that a higher event probability always implies a worse overall decision: the severity of the event, the treatment benefits, and the alternatives also matter.

---

## 3. Twelve-week learning plan

### Week 1 — Master the vocabulary of medical risk

**Read (free):**

- [BMJ Best Practice — Understanding statistics: risk](https://bestpractice.bmj.com/info/toolkit/learn-ebm/how-to-calculate-risk/).
- [BMJ — Understanding risk](https://bestpractice.bmj.com/info/us/evidence/practise-ebm/understanding-risk/).
- [Oxford CEBM — Number Needed to Treat](https://www.cebm.ox.ac.uk/resources/ebm-tools/number-needed-to-treat-nnt/).
- [NICE — Shared decision making, section 1.4](https://www.nice.org.uk/guidance/NG197/chapter/recommendations) (especially communication of absolute risks and natural frequencies).

**Master:** Baseline and absolute risk; absolute risk difference; risk ratio/relative risk; relative risk reduction/increase; odds and odds ratio; NNT and NNH; percentage *versus* percentage points; the role of a comparator and a time horizon.

**Do:** Use Practice Case A in Section 4 to calculate CER, EER, ARR, RR, RRR, NNT, and OR by hand. Describe the same data in both natural-frequency and relative terms.

**Checkpoint:** Explain why “30% risk reduction” may mean something very different from “30 percentage points of risk reduction.”

### Week 2 — Bayesian diagnosis: prior probabilities, sensitivity, specificity, and likelihood ratios

**Read (free):**

- [Oxford CEBM — Likelihood Ratios](https://www.cebm.ox.ac.uk/resources/ebm-tools/likelihood-ratios).
- [Oxford CEBM — EBM tools index](https://www.cebm.ox.ac.uk/resources/ebm-tools) (find diagnostic appraisal and pretest-probability resources).

**Read (textbook, selective):**

- *Medical Decision Making*, 3rd ed., **Chapter 3: “Probability: quantifying uncertainty,” Chapter 4: “Interpreting new information: Bayes’ theorem,” and Chapter 5: “Measuring the accuracy of clinical findings.”** [Publisher / table of contents](https://onlinelibrary.wiley.com/doi/book/10.1002/9781119627876).

**Master:** Pretest and post-test probability; base-rate sensitivity; false positives; sensitivity and specificity; positive and negative predictive values; likelihood ratios (`LR+`, `LR−`); threshold-based testing.

**Do:** Work Practice Case B in Section 4. Recompute the positive predictive value at disease prevalences of 2%, 10%, and 30% while holding sensitivity and specificity fixed.

**Checkpoint:** Explain why the same positive test can be much more informative in a high-prevalence population than in a low-prevalence population.

### Week 3 — Rates, incidence, prognosis, and survival over time

**Read (textbook, selective):**

- *Clinical Epidemiology: The Essentials*, 6th ed.: sections on **frequency, prevalence and incidence, cumulative incidence, incidence density/person-time, and prognosis**. [Publisher](https://shop.lww.com/Clinical-Epidemiology/p/9781975109585).
- *Medical Decision Making*, 3rd ed., **Chapter 11: “Survival models: representing uncertainty about the length of life.”** [Publisher](https://onlinelibrary.wiley.com/doi/book/10.1002/9781119627876).

**Master:** Incidence proportion versus incidence rate; person-years; hazards versus cumulative risk; survival functions; survival curves; censoring; proportional hazards; why an HR is *not* an RR; competing risks as an advanced caveat.

**Do:** Given a hypothetical constant annual hazard of 0.02, calculate five-year event probability as `1 − exp(−0.02 × 5)`. Compare it with the naive `5 × 2%` approximation. Explain when the approximation is misleading.

**Checkpoint:** Distinguish a statement like “5 events per 1,000 person-years” from “a 0.5% five-year risk.”

### Week 4 — Study designs, biases, and where risk estimates come from

**Read (free):**

- [Oxford CEBM — Study designs](https://www.cebm.ox.ac.uk/resources/ebm-tools/study-designs).
- [Oxford CEBM — Critical appraisal tools](https://www.cebm.ox.ac.uk/resources/ebm-tools/critical-appraisal-tools).
- [BMJ — Appraise the evidence](https://bestpractice.bmj.com/info/us/evidence/learn-ebm/appraise-the-evidence/).

**Read (textbook, selective):**

- *Clinical Epidemiology: The Essentials*: sections on **bias, chance, study populations, cohort studies, case-control studies, trials, and external validity**.

**Master:** Randomization; selection bias; information bias; confounding; confounding by indication; observational versus randomized comparisons; selection of a control group; representativeness and generalizability.

**Do:** Construct a table comparing RCT, cohort, case-control, and cross-sectional designs, indicating their typical use, strengths, threats to validity, and whether risks can be directly calculated from the sampling design.

**Checkpoint:** Explain why a case-control study usually reports an odds ratio and generally cannot directly estimate population risk without additional information.

### Week 5 — Learn to read an individual medical paper

**Read (free):**

- [Oxford CEBM — Critical appraisal tools](https://www.cebm.ox.ac.uk/resources/ebm-tools/critical-appraisal-tools) (use the RCT and prognosis worksheets).
- [BMJ — How to clarify a clinical question](https://bestpractice.bmj.com/info/us/evidence/learn-ebm/how-to-clarify-a-clinical-question/).

**Read (textbook, selective):**

- *How to Read a Paper*, 7th ed., by Trisha Greenhalgh and Paul Dijkstra: sections on **study design, statistical appraisal, trials, and observational evidence**. [Publisher](https://onlinelibrary.wiley.com/doi/book/10.1002/9781394206933).
- Optional deeper reference: *Users' Guides to the Medical Literature*, 3rd ed., edited by Gordon Guyatt: sections addressing **therapy, harm, prognosis, and applicability**. [Publisher](https://www.mheducation.com/highered/mhp/product/users-guides-medical-literature-manual-evidence-based-clinical-practice-3e.html).

**Master:** PICO (population, intervention, comparator, outcomes); study registration; primary versus secondary outcomes; intention-to-treat; absolute and relative results; confidence intervals; statistical versus clinical importance; missing data.

**Do:** Choose a published trial or the hypothetical example in Section 4. Fill out an Oxford critical-appraisal worksheet, including a paragraph explaining who the results may not apply to.

**Checkpoint:** Identify a study result that is statistically precise but potentially trivial in clinical terms.

### Week 6 — Systematic reviews, certainty of evidence, and translating results

**Read (free):**

- [Cochrane Handbook — Chapter 14: Summary of findings and GRADE](https://www.cochrane.org/authors/handbooks-and-manuals/handbook/current/chapter-14).
- [Cochrane Handbook — Chapter 15: Interpreting results and drawing conclusions](https://www.cochrane.org/authors/handbooks-and-manuals/handbook/current/chapter-15).
- [BMJ — What is GRADE?](https://bestpractice.bmj.com/info/us/evidence/learn-ebm/what-is-grade/).

**Master:** Systematic reviews and meta-analysis; pooled effects; heterogeneity; differences between absolute effects and relative pooled measures; confidence intervals; GRADE domains (risk of bias, inconsistency, indirectness, imprecision, publication bias); certainty of evidence versus strength of recommendation.

**Do:** Find a Cochrane review with a Summary of Findings table. For one binary outcome, record the baseline risk, relative effect, implied or reported absolute effect, time horizon, and evidence certainty. Write two sentences describing what the result does and does not establish.

**Checkpoint:** Explain why “low certainty” is not the same as “no effect,” and why a recommendation can depend on patient preferences even when the evidence is high-certainty.

### Week 7 — Apply population results to an individual patient

**Read (free):**

- [NICE — Shared decision making recommendations](https://www.nice.org.uk/guidance/NG197/chapter/recommendations).
- [BMJ — What is EBM?](https://bestpractice.bmj.com/info/us/evidence/learn-ebm/what-is-ebm/).
- [BMJ — Understanding risk](https://bestpractice.bmj.com/info/us/evidence/practise-ebm/understanding-risk/).

**Optional (accessible):**

- *Risk Savvy: How to Make Good Decisions*, Gerd Gigerenzer, for natural frequencies, screening, risk literacy, and communication. [Publisher](https://www.penguinrandomhouse.com/books/309675/risk-savvy-by-gerd-gigerenzer/).

**Master:** Baseline-risk variation; average treatment effect versus conditional effects; calibration of prediction models; shared decision-making; personal versus population-level estimates; absolute frequencies and risk framing.

**Do:** Keep a treatment RR fixed at 0.70. Compute treated risks, ARRs, and NNTs for patients with baseline event risks of 1%, 8%, and 20%. Explain what assumptions are required to apply the same RR across risk strata.

**Checkpoint:** Ask: “Compared with whom, for what event, over how long, and how was this number estimated?”

### Week 8 — Decision trees and expected value/expected utility

**Read (textbook):**

- *Medical Decision Making*, 3rd ed., **Chapter 6: “Decision trees – representing the structure of a decision problem” and Chapter 7: “Decision tree analysis.”** [Publisher](https://onlinelibrary.wiley.com/doi/book/10.1002/9781119627876).
- *Decision Making in Health and Medicine: Integrating Evidence and Values*, 2nd ed., Hunink et al.: select sections on **decision trees and expected-value decision analysis**. [Publisher](https://www.cambridge.org/hm/titles/decision-making-health-and-medicine-integrating-evidence-and-values-2nd-edition).

**Master:** Decision nodes versus chance nodes; mutually exclusive branches; conditional probabilities; rollback; expected loss; dominance; treatment and test thresholds; one-way sensitivity analysis.

**Do:** Create a decision tree for Treatment A versus no treatment using the two outcomes in Practice Case A (severe event prevented, mild adverse event caused). Draw separate benefit and harm branches or use an additive expected-disutility model with clearly stated assumptions.

**Checkpoint:** Explain why choosing the option with the lower risk of *one* outcome need not maximize overall expected utility.

### Week 9 — Utilities, quality of life, patient preferences, and risk attitudes

**Read (textbook):**

- *Medical Decision Making*, 3rd ed., **Chapter 8: “Outcome utility – representing risk attitudes,” Chapter 9: “Outcome utilities – clinical applications,” and Chapter 10: “Outcome utilities – adjusting for the quality of life.”** [Publisher](https://onlinelibrary.wiley.com/doi/book/10.1002/9781119627876).
- *Decision Making in Health and Medicine*, 2nd ed.: select sections on **utilities, preferences, and outcomes**.

**Master:** Outcome value versus event probability; expected utility; different patients' preferences; health-state utilities; quality-adjusted life years (QALYs); quality-of-life and duration tradeoffs; elicitation limitations.

**Do:** Assign separate disutilities to severe and mild adverse outcomes in Practice Case A. Vary their ratio and find the point where the preferred option switches. Explicitly avoid treating arbitrary numbers as validated patient utilities.

**Checkpoint:** Explain why the term “high-risk procedure” is not a complete decision analysis.

### Week 10 — Longer-term models, sensitivity analysis, and cost-effectiveness

**Read (textbook):**

- *Medical Decision Making*, 3rd ed., **Chapter 12: “Markov models” and Chapter 15: “Cost-effectiveness analysis.”** Review Chapter 11 on survival models as needed. [Publisher](https://onlinelibrary.wiley.com/doi/book/10.1002/9781119627876).
- *Decision Making in Health and Medicine*, 2nd ed.: select sections on **state-transition models, uncertainty, and cost-effectiveness**. [Publisher](https://www.cambridge.org/hm/titles/decision-making-health-and-medicine-integrating-evidence-and-values-2nd-edition).

**Master:** Transition probabilities; time cycles; absorbing states; horizon selection; sensitivity analysis; probabilistic sensitivity analysis; cost-effectiveness; incremental cost-effectiveness ratio (ICER); when value of information matters.

**Do:** Sketch a three-state Markov model (`Healthy`, `Complication`, `Dead`). Identify possible transitions and which states can be absorbing. Then calculate a simple ICER from two fictional strategies, using a consistent perspective and time horizon.

**Checkpoint:** Distinguish a health-economic ICER (incremental cost / incremental health gain) from a clinical RR or from a financial return-on-investment ratio.

### Week 11 — Causal inference: from association to treatment effect

**Read (free):**

- [Hernán and Robins — *Causal Inference: What If*](https://miguelhernan.org/whatifbook), **Part I: causal inference without models**. Use Part II as an optional quantitative extension; the official site also provides code and data.

**Read (review):**

- *Clinical Epidemiology: The Essentials*: review **confounding, bias, cohort studies, and intervention comparisons**.

**Master:** Counterfactual outcomes; exchangeability; treatment assignment mechanisms; confounding by indication; selection bias; positivity and consistency at a conceptual level; target trial thinking; association versus causal effect.

**Do:** Consider outcomes of surgery versus no surgery in observational data. Draw a simple causal diagram showing that disease severity may influence both the treatment choice and subsequent outcome. Explain why comparing raw outcome proportions can give a misleading estimate of surgery's causal effect.

**Checkpoint:** Explain the difference between a model that accurately *predicts* complications and an analysis that estimates what would happen if treatment were changed.

### Week 12 — Integration, critique, and communication

**Read / revisit:**

- [Cochrane Chapter 15](https://www.cochrane.org/authors/handbooks-and-manuals/handbook/current/chapter-15).
- [NICE shared decision-making recommendations](https://www.nice.org.uk/guidance/NG197/chapter/recommendations).
- *Medical Decision Making*: revisit chapters 6–10, 13–15 based on what your capstone requires.

**Build:** Complete the [capstone](#8-capstone-assignment-and-reusable-template): an evidence-to-decision memo (2–4 pages), an accompanying calculations sheet, and a one-minute plain-language explanation.

**Checkpoint:** Can another reader identify the event, population, comparator, probabilities, time horizon, uncertainty, patient-relevant consequences, and assumptions from your memo *without* consulting the source paper?

---

## 4. The integrated practice case

All figures below are **fictional and used only for learning**. They do not represent the effect of any real intervention.

### Case A: A treatment with both a potential benefit and harm

Suppose 2,000 similar people are followed for **one year**, with 1,000 randomly assigned to each group.

| Outcome over 1 year | No treatment (1,000) | Treatment (1,000) |
|---|---:|---:|
| Severe event | 80 | 56 |
| Mild adverse event | 20 | 35 |

For simplicity, treat these as distinct marginal outcomes. Individuals could experience both. Do **not** obtain “the risk of any event” by summing their probabilities. For the expected-disutility exercise, assume outcome burdens are additive; this assumption can be relaxed in a more detailed model.

**Tasks:**

1. Compute the severe-event risk in each group, absolute risk reduction, RR, RRR, OR, and NNT.
2. Compute the increase in mild adverse-event risk and NNH.
3. Describe the severe-event result as (a) natural frequencies, (b) percentage-point difference, and (c) relative reduction.
4. Recalculate the absolute benefit if baseline severe-event risk is 1% or 20%, **assuming** the treatment RR of 0.70 transfers to those populations.
5. Assign disutility 10 units to a severe event and 1 unit to a mild event. Calculate the expected net reduction in disutility per 1,000 patients, assuming these are the only relevant differences.
6. Repeat task 5 if a mild event is assigned disutility 20 units. Discuss how the decision changes.
7. List at least five reasons the observed trial results might not map exactly to an individual's situation.

### Case B: Diagnostic test and base-rate effects

A hypothetical test has sensitivity **90%** and specificity **95%**. Assume disease prevalence is **2%** in 10,000 tested people.

**Tasks:**

1. Compute the expected numbers of true positives, false positives, false negatives, and true negatives.
2. Compute positive predictive value (`PPV = TP / (TP + FP)`).
3. Compute the positive likelihood ratio (`LR+ = sensitivity / (1 − specificity)`).
4. Repeat PPV calculations at 10% and 30% prevalence.
5. Explain why a “90% accurate” description (if someone used it) would be ambiguous and potentially misleading.

### Case C: Causal inference

A hospital registry shows **higher 30-day mortality after surgery** among patients who underwent an operation than among those who received non-operative treatment. Patients selected for surgery, however, had more severe disease.

**Tasks:**

1. Identify one plausible common cause of treatment selection and outcome.
2. Explain why the observed association is not automatically the treatment's causal effect.
3. Describe one feasible research design or analysis that would help address confounding.
4. Separate the questions “Who is likely to do poorly?” and “Would surgery improve outcomes for otherwise comparable patients?”

---

## 5. Medical risk formula sheet

Take `p0` as the probability of the event in the reference/control group and `p1` as the probability in the exposed/treatment group, for **the same outcome and time horizon**.

| Quantity | Formula | Interpretation / caution |
|---|---|---|
| Absolute risk | Events / people at risk | Cumulative event probability for a specified period |
| Risk difference (RD) | `p1 − p0` | Change in **percentage points** when multiplied by 100 |
| Absolute risk reduction (ARR) | `p0 − p1` | Positive if treatment prevents an undesirable event |
| Relative risk (RR) | `p1 / p0` | Ratio of cumulative risks; `RR=0.7` = 30% lower relative risk |
| Relative risk reduction (RRR) | `1 − RR` | Proportional reduction relative to baseline |
| Odds | `p / (1 − p)` | Probability is `odds / (1 + odds)` |
| Odds ratio (OR) | `[p1/(1−p1)] / [p0/(1−p0)]` | Not generally equal to RR; approximation improves for rare events |
| NNT | `1 / ARR` | Use ARR as a decimal, with meaningful causal interpretation and defined horizon; conventionally round up |
| NNH | `1 / (p1−p0)` | For an excess harmful event; same timing and causal caveats |
| Incidence rate | New events / person-time | A rate, not directly a cumulative probability |
| Positive likelihood ratio | `Se / (1−Sp)` | `Se` = sensitivity, `Sp` = specificity |
| Negative likelihood ratio | `(1−Se) / Sp` | Updates odds after a negative test |
| Post-test odds | Pretest odds × LR | Convert odds back to probability to interpret clinically |
| Hazard ratio (HR) | `h1(t) / h0(t)` | Ratio of instantaneous hazards; not necessarily RR over the full follow-up |
| Constant-hazard event risk | `1 − exp(−h × t)` | A simplified survival-model relationship, under a constant hazard assumption |
| ICER | `(Cost_A − Cost_B)/(Effect_A − Effect_B)` | Commonly dollars per QALY gained; interpretation needs context |

**Important:** NNT/NNH become misleading if they are read as intrinsic, timeless treatment properties. They change with underlying baseline risk, time horizon, assumptions about treatment effect, and outcome definition. HRs should not be casually translated into relative risk reductions without modeling cumulative incidence and relevant assumptions.

---

## 6. A practical framework for interrogating medical risk claims

Use this checklist whenever you read “increased risk,” “high risk,” “doubles risk,” or “reduces mortality by 30%.”

### The eight-question audit

- [ ] **Event:** Precisely what outcome is counted? Mild complication, major complication, readmission, reoperation, disease-specific death, all-cause death, or a composite?
- [ ] **Denominator:** Who is in the population at risk, and how was the cohort selected?
- [ ] **Comparator:** Relative to no treatment, a different treatment, average patients, a low-risk subgroup, or the patient's own prior baseline?
- [ ] **Measure:** Absolute risk, difference, RR, OR, HR, incidence rate, or model-predicted probability?
- [ ] **Time:** During the procedure, 30 days, one year, five years, or lifetime?
- [ ] **Uncertainty:** What is the confidence interval or other uncertainty description? Is the data robust enough for the claimed precision?
- [ ] **Validity:** Is the result causal or observational, adjusted or unadjusted, and applicable to the patient in question?
- [ ] **Decision relevance:** What are the benefits, harms, severity, duration, reversibility, and consequences of alternatives including no intervention?

**Useful clinical phrasing:** “When you say my risk is higher, what is the estimated absolute probability for someone like me, what is the comparator, and what time period does it cover? What changes if I don't undergo the procedure?”

### Evidence ledger template

| Item | Notes |
|---|---|
| Source / date / study design | |
| Population and exclusions | |
| Interventions and comparators | |
| Outcome and exact definition | |
| Time horizon | |
| Numerators and denominators | |
| Absolute risks | |
| Effect measure (RR / OR / HR / RD) | |
| 95% CI or credible interval | |
| Confounders / study limitations | |
| Baseline risk applicability | |
| Seriousness and reversibility | |
| Bottom-line interpretation | |

---

## 7. Resource library with links

### A. Free core references — start here

| Reference | Focus | Access |
|---|---|---|
| [BMJ: Understanding statistics — risk](https://bestpractice.bmj.com/info/toolkit/learn-ebm/how-to-calculate-risk/) | AR, ARR, RR, RRR, OR, HR, NNT/NNH | Free reference page |
| [BMJ: Understanding risk](https://bestpractice.bmj.com/info/us/evidence/practise-ebm/understanding-risk/) | Patient-facing framing and risk communication | Free reference page |
| [BMJ: What is EBM?](https://bestpractice.bmj.com/info/us/evidence/learn-ebm/what-is-ebm/) | Evidence, expertise, and patient preferences | Free reference page |
| [BMJ: Appraise the evidence](https://bestpractice.bmj.com/info/us/evidence/learn-ebm/appraise-the-evidence/) | Validity and bias | Free reference page |
| [BMJ: What is GRADE?](https://bestpractice.bmj.com/info/us/evidence/learn-ebm/what-is-grade/) | Evidence certainty and recommendations | Free reference page |
| [Oxford CEBM: EBM tools](https://www.cebm.ox.ac.uk/resources/ebm-tools) | Hub for appraisals, NNT, LR, study designs | Free resources |
| [Oxford CEBM: Number Needed to Treat](https://www.cebm.ox.ac.uk/resources/ebm-tools/number-needed-to-treat-nnt/) | NNT formula and limitations | Free resource |
| [Oxford CEBM: Likelihood Ratios](https://www.cebm.ox.ac.uk/resources/ebm-tools/likelihood-ratios) | Bayesian diagnostic updating | Free resource |
| [Oxford CEBM: Critical Appraisal Tools](https://www.cebm.ox.ac.uk/resources/ebm-tools/critical-appraisal-tools) | Worksheets for trials, prognosis, reviews, diagnosis | Free resources |
| [Oxford CEBM: Study Designs](https://www.cebm.ox.ac.uk/resources/ebm-tools/study-designs) | Designs and tradeoffs | Free resource |
| [Cochrane Handbook, Chapter 14](https://www.cochrane.org/authors/handbooks-and-manuals/handbook/current/chapter-14) | Summary of findings and certainty | Free online handbook |
| [Cochrane Handbook, Chapter 15](https://www.cochrane.org/authors/handbooks-and-manuals/handbook/current/chapter-15) | Relative/absolute effects and communication | Free online handbook |
| [NICE: Shared Decision Making (NG197)](https://www.nice.org.uk/guidance/NG197/chapter/recommendations) | Practical risk presentation and patient choices | Free guideline |
| [Hernán & Robins: *Causal Inference: What If*](https://miguelhernan.org/whatifbook) | Counterfactual reasoning and causal estimation | Free full book, data, and code |

### B. Primary textbooks — read selectively in this order

1. **Grant S. Fletcher, *Clinical Epidemiology: The Essentials*, 6th ed. (2020).** [Wolters Kluwer / LWW](https://shop.lww.com/Clinical-Epidemiology/p/9781975109585). Start with sections on frequency, incidence, bias, diagnosis, prognosis, and research design. **Role:** explains what risk estimates mean and where they come from. Generally paid.
2. **Harold C. Sox, Michael C. Higgins, Douglas K. Owens, and Gillian Sanders Schmidler, *Medical Decision Making*, 3rd ed. (2024).** [Wiley; full table of contents](https://onlinelibrary.wiley.com/doi/book/10.1002/9781119627876). Read chapters 3–8 and 11–15 as the main quantitative spine. **Role:** probabilities → Bayes → decision trees → utilities → survival and state-transition models → cost-effectiveness. Generally paid; some chapter previews may be accessible.
3. **M. G. Myriam Hunink et al., *Decision Making in Health and Medicine: Integrating Evidence and Values*, 2nd ed. (2014).** [Cambridge University Press](https://www.cambridge.org/hm/titles/decision-making-health-and-medicine-integrating-evidence-and-values-2nd-edition). Read relevant sections on formal decision analysis, utilities, uncertainty, health-state modeling, and cost-effectiveness. **Role:** deeper treatment for readers with operations-research and economic modeling experience. Generally paid.

### C. Supplementary books — useful rather than mandatory

4. **Trisha Greenhalgh and Paul Dijkstra, *How to Read a Paper: The Basics of Evidence-Based Healthcare*, 7th ed. (2025).** [Wiley](https://onlinelibrary.wiley.com/doi/book/10.1002/9781394206933). Highly practical bridge to reading trial reports and systematic reviews. Generally paid.
5. **Gerd Gigerenzer, *Risk Savvy: How to Make Good Decisions* (2014; later paperback 2015).** [Penguin Random House](https://www.penguinrandomhouse.com/books/309675/risk-savvy-by-gerd-gigerenzer/). Read for communication, risk literacy, frequency framing, and common cognitive mistakes. Generally paid; publisher sample available.
6. **Gordon Guyatt (ed.), *Users' Guides to the Medical Literature: A Manual for Evidence-Based Clinical Practice*, 3rd ed. (2015).** [McGraw Hill](https://www.mheducation.com/highered/mhp/product/users-guides-medical-literature-manual-evidence-based-clinical-practice-3e.html). Use as a reference for appraisal of diagnosis, therapy, harms, prognosis, and evidence applicability. Generally paid.

### Access notes

- The linked pages above were verified as discoverable publisher, organizational, or author pages when this syllabus was compiled. Website paths and institutional access rules can change.
- Free online reference pages are usually sufficient for Weeks 1–2, 4, and 6–7. Access to the full textbook chapters may require purchase, a library, or institutional credentials.
- The *What If* author's page explicitly provides its book, code, and data for free; use that page for the latest version of the text.

---

## 8. Capstone assignment and reusable template

### Capstone: Evidence-to-decision brief

Choose a **published RCT or systematic review** that compares a medical treatment with another treatment or no treatment and reports at least one important binary patient outcome. A clear clinical question and enough data to recover absolute risks are more valuable than a complicated paper.

**Deliverables:**

1. **Study identification** — citation, study type, population, eligibility criteria, comparator, follow-up period.
2. **Quantitative reconstruction** — original event counts (when available), absolute risks, RD, RR or other reported effect measure, NNT/NNH when valid, and uncertainty.
3. **Evidence appraisal** — biases, confounding concerns if observational, sample size, precision, applicability, and certainty.
4. **Decision model** — a treatment-choice diagram or decision table considering meaningful benefits and harms, with explicit assumptions about severity and preferences.
5. **Sensitivity analysis** — show how the conclusion changes with baseline risk, utility assumptions, and plausible effect estimates.
6. **Communication draft** — a paragraph that uses natural frequencies and a clear time horizon, without presenting uncertainty as individual destiny.

#### Copyable memo template

```markdown
# Evidence-to-Decision Memo: [Question]

## Decision and alternatives
- Population / intended patient profile:
- Option A:
- Option B:
- Time horizon:

## Evidence
- Source and study design:
- Eligibility / applicability:
- Event definition and severity:
- Absolute risks (with counts):
- Risk difference / relative effect:
- Uncertainty (CI and/or range):
- Evidence certainty and limitations:

## Decision analysis
- Benefits and harms of each option:
- Assumptions and outcome utilities:
- Sensitivity to baseline risk:
- Sensitivity to uncertain treatment effects:
- Important missing data:

## Explanation for a nontechnical reader
[Use a common denominator and time horizon.]

## Decision-relevant follow-up questions
1.
2.
3.
```

**Evaluation rubric (20 points):** Correctness of measures (4); well-specified comparator/time/outcome (4); critical appraisal (4); explicit preferences and sensitivity analysis (4); transparent, understandable communication (4).

---

## 9. Answer key and self-assessment

**Case A answers:**

- Severe-event risk: `80/1000 = 8%` untreated; `56/1000 = 5.6%` treated.
- Severe-event ARR: `8% − 5.6% = 2.4 percentage points` (24 fewer severe events per 1,000 treated over one year).
- RR: `0.056 / 0.08 = 0.70`; RRR: `30%`.
- OR: `(56/944) / (80/920) ≈ 0.682`; this differs from RR = 0.70.
- NNT: `1 / 0.024 = 41.67`; round up to **42** for the specified one-year endpoint, if interpreted causally.
- Mild-event risk: `2%` untreated, `3.5%` treated. Absolute increase: `1.5 percentage points`; NNH: `1 / 0.015 = 66.67`, round up to **67**.
- With constant RR = 0.70: 1% untreated → 0.7% treated; ARR 0.3 percentage points; NNT = **334**. At 20% untreated → 14% treated; ARR 6 percentage points; NNT = **17**.
- Additive expected-disutility model per 1,000 patients: `(24 fewer severe events × 10) − (15 additional mild events × 1) = +225` disutility units avoided with treatment. If mild-event disutility becomes 20: `(24 × 10) − (15 × 20) = −60` units avoided; under this deliberately simplified value model, no treatment becomes preferred. This is an illustration of preference sensitivity, not a medical recommendation.

**Case B answers:**

- 2% of 10,000 = 200 people have disease, 9,800 do not.
- TP = 180; FN = 20; TN = 9,310; FP = 490.
- PPV = `180 / (180 + 490) ≈ 26.9%` despite 90% sensitivity and 95% specificity.
- `LR+ = 0.90 / (1−0.95) = 18`.
- At 10% prevalence, PPV = `0.09 / (0.09 + 0.045) ≈ 66.7%`; at 30%, PPV = `0.27 / (0.27 + 0.035) ≈ 88.5%`.

**Case C key observation:** Disease severity is a plausible confounder if it affects both the likelihood of surgery and the probability of the outcome. A raw observational risk difference may therefore reflect treatment effects, pre-existing patient differences, or both. Randomization when ethical and feasible, or carefully designed observational methods emulating an explicit target trial, may help address the question; neither automatically eliminates every source of bias.

### Final mastery questions

1. Can you translate “50% lower risk” into absolute numbers for more than one baseline risk?
2. Can you tell whether a paper measured incidence proportion, person-time incidence rate, odds, or hazard?
3. Can you explain why OR = 2 does not generally imply RR = 2?
4. Can you apply likelihood ratios to update a pretest probability?
5. Can you identify likely confounders and distinguish prediction from causal effect?
6. Can you interpret an absolute-effect estimate together with its confidence interval and GRADE certainty?
7. Can you build a two-option decision tree and check sensitivity to patient values?
8. Can you articulate what is still unknown before an individual makes a decision?

**Completion criterion:** You have achieved the core objective when you can reconstruct a published medical risk claim from its numerator, denominator, comparator, outcome definition, time horizon, and uncertainty—and then explain how (and whether) that evidence should inform a real decision.
