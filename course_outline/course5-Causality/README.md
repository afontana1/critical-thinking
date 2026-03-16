# Course Overview: Causality and Causal Reasoning – From Difference-Making to Causal Inference Across Disciplines

**Big question:**
How do we tell when one thing actually *causes* another, what kinds of evidence justify causal claims, and how do different disciplines—from epidemiology and economics to law and AI—reason about causation under uncertainty?

**By the end, students should be able to:**

* Distinguish **causal claims** from descriptive, predictive, and merely correlational claims.
* Explain major ways of thinking about causation, including **difference-making, counterfactual, interventionist, mechanistic, and capacity-based** approaches.
* Use a shared causal vocabulary, including **necessary, sufficient, contributory, proximate, general, and specific** causation.
* Understand why **study design** is central to causal inference, and distinguish **identification** from **estimation**.
* Recognize the logic of **experiments, quasi-experiments, and observational designs**, including their assumptions and limits.
* Use simple **causal diagrams** to reason about confounders, mediators, colliders, and sources of bias.
* Explain why **more controls** do not automatically improve a causal analysis, and why adjustment depends on causal structure.
* Understand the importance of **mechanisms, capacities, and process evidence** in judging whether causal claims are plausible and whether they will travel across contexts.
* Compare how different fields—especially **epidemiology, economics, law, and AI/ML**—operationalize and justify causal claims.
* Evaluate causal arguments using ideas such as **Bradford Hill considerations, triangulation, process tracing, and robustness checks**.
* Detect common mistakes in causal reasoning, including **post hoc reasoning, reverse causation, selection bias, regression to the mean, base-rate neglect, and overclaiming from weak designs**.
* Communicate causal claims responsibly by stating the **question, design, assumptions, magnitude, uncertainty, and limits of generalization**.
* Be prepared for later work in **risk analysis, systems thinking, model thinking, and policy reasoning**, where causal claims must be interpreted and used rather than merely identified.

---

## Unit 1 – What Is a Causal Claim?

**Guiding questions**

* What makes a claim genuinely causal rather than merely descriptive or correlational?
* What does it mean to say that one event, factor, or intervention made a difference?
* Why have philosophers and scientists developed multiple theories of causation rather than one universally accepted definition?

**Sub-units**

1. **Scene-setting: Why causal claims matter**

   * Causal claims structure everyday reasoning in health, policy, law, business, journalism, and ordinary life.
   * People constantly move from “X and Y are associated” to “X caused Y,” often too quickly.
   * The course begins by slowing that move down and asking what has to be true for a causal claim to be justified.

2. **Causation as difference-making**

   * Introduce the intuitive idea that causes make a difference to what happens.
   * Basic formulation: if X had not occurred, Y would have been different.
   * This captures why causation matters for explanation, prediction, blame, and intervention.

3. **Counterfactuals and possible alternatives**

   * Counterfactual thinking asks what would happen in relevant alternative scenarios.
   * This gives students an intuitive entry point into causal reasoning before formal methods.
   * It also raises difficulties: which alternative worlds are relevant, and how close must they be?

4. **Kinds of causes**

   * Necessary, sufficient, and contributory causes.
   * Single-cause stories versus **multiple causation** and interacting causal factors.
   * Distinguish triggering conditions from background conditions.

5. **Mechanisms, regularities, and capacities**

   * Some causal reasoning focuses on regular patterns; some on underlying mechanisms.
   * Cartwright’s emphasis on **capacities** helps students see that causes may have powers that manifest differently in different contexts.
   * This introduces an early contrast between abstract causal claims and context-sensitive causal production.

6. **Mill’s Methods as early causal heuristics**

   * Agreement, difference, residues, and concomitant variation.
   * Treat these not as magical rules but as historically important heuristics for comparing cases.
   * Show both their enduring value and their limitations in complex causal systems.

7. **How causal language appears in public discourse**

   * Causal verbs and constructions in headlines, policy briefs, product claims, and health advice.
   * Students learn to hear when writers are implying causation without explicitly defending it.
   * Practice distinguishing “is associated with,” “predicts,” “increases the risk of,” and “causes.”

8. **First-pass tests for identifying a causal claim**

   * “Is it causal?” checklist:

     * verb test
     * counterfactual test
     * ruled-out-alternatives test
   * Short paragraph rewrites from causal to correlational language and back again.
   * Begin building a habit of cautious interpretation.

**Core readings**

* John Stuart Mill, *A System of Logic*, Book III.
* James Woodward, *Making Things Happen: A Theory of Causal Explanation*.
* Judea Pearl and Dana Mackenzie, *The Book of Why*.
* Nancy Cartwright, *Nature’s Capacities and Their Measurement*.
* *The Oxford Handbook of Causation* (selected chapters).
* Stanford Encyclopedia of Philosophy, “Causation” and “Counterfactual Theories of Causation.”

---

## Unit 2 – Counterfactuals, Interventions, and Competing Theories of Causation

**Guiding questions**

* What are the main philosophical frameworks for understanding causation?
* How are counterfactual and interventionist accounts related?
* Why do mechanisms and capacities matter even when we have statistical evidence?

**Sub-units**

1. **Counterfactual theories of causation**

   * A cause is linked to an effect by what would happen under relevant alternatives.
   * Counterfactual theories help explain why causes matter for explanation and policy.
   * They also face puzzles involving overdetermination, preemption, and causal chains.

2. **Interventionism and manipulation**

   * Woodward’s interventionist account: X is causally relevant to Y if intervening on X would change Y.
   * This clarifies why experimentation is so powerful in causal inquiry.
   * It also links causal explanation to practical questions: what could we change?

3. **The ladder from seeing to doing to imagining**

   * Draw from *The Book of Why* to distinguish association, intervention, and counterfactual reasoning.
   * This gives students a memorable hierarchy:

     * seeing patterns
     * acting on systems
     * imagining alternatives
   * It helps explain why causal reasoning goes beyond prediction.

4. **Capacities and context sensitivity**

   * Cartwright’s view that causes have capacities, but capacities operate within specific arrangements.
   * This helps students understand why causal claims may fail to generalize across settings.
   * It also complicates any simple “one-size-fits-all” theory of causal inference.

5. **Mechanistic theories and causal production**

   * Mechanistic views ask how causes bring effects about.
   * These views are especially important in biology, medicine, social explanation, and engineering.
   * Distinguish evidence that something makes a difference from evidence showing how it works.

6. **Pluralism about causation**

   * Different domains may require different emphases: counterfactuals, interventions, mechanisms, capacities, or legal standards.
   * Students should see that causal reasoning is not reducible to one formula.
   * This prepares them to compare disciplinary approaches later in the course.

7. **Causal explanation versus causal discovery**

   * Discovering a plausible cause is not the same as fully explaining an outcome.
   * Explanation often requires mechanism, context, and comparison to rivals.
   * This distinction will recur in policy, case studies, and AI applications.

**Core readings**

* David Lewis and related selections on counterfactual causation.
* James Woodward, *Making Things Happen*.
* Nancy Cartwright, *Nature’s Capacities and Their Measurement*.
* Stephen L. Morgan and Christopher Winship, *Counterfactuals and Causal Inference* (conceptual chapters).
* *The Oxford Handbook of Causal Reasoning* (selected chapters).
* *The Oxford Handbook of Causation* (selected chapters).

---

## Unit 3 – How Do We Learn About Causes? Designs, Identification, and Validity

**Guiding questions**

* Why is causal inference primarily a matter of design rather than statistical ritual?
* What makes an experiment or quasi-experiment credible?
* How do we distinguish whether a design identifies a causal effect from how precisely we estimate it?

**Sub-units**

1. **From causal question to research design**

   * Causal inquiry starts with a question about what would happen under different conditions.
   * A design is a strategy for approximating the relevant comparison.
   * Students learn that causal inference begins before any model is fitted.

2. **Experiments and randomization**

   * Random assignment, control groups, and blinding.
   * Why randomization helps break confounding by balancing background factors on average.
   * The experiment as the benchmark for causal identification.

3. **Why experiments are not always possible**

   * Ethical, logistical, political, and financial constraints.
   * Many important causal questions cannot be studied by direct randomization.
   * This motivates quasi-experimental and observational strategies.

4. **Quasi-experiments and natural experiments**

   * Policy changes, lotteries, discontinuities, administrative rules, and unexpected shocks.
   * What makes these designs credible is not novelty but plausibly exogenous variation.
   * Students should learn to ask what exactly is doing the identifying work.

5. **Identification versus estimation**

   * Identification asks whether the design supports a causal claim at all.
   * Estimation asks how large the effect appears to be.
   * This distinction is foundational: a precise estimate from a bad design is still weak evidence.

6. **Threats to internal validity**

   * Confounding, selection bias, reverse causation, attrition, measurement error, spillovers, and noncompliance.
   * Students learn a compact “threats to validity” audit.
   * Internal validity is about whether the estimated contrast tracks the causal contrast of interest.

7. **External validity and transportability**

   * Even a well-identified effect may not travel to another population, institution, or historical context.
   * Mechanisms, background conditions, and implementation details matter.
   * This is where causal inference meets explanation and policy judgment.

8. **Design-spotting in public claims**

   * Practice classifying study summaries as RCT, natural experiment, before/after, cohort, case-control, cross-sectional, or weak observational study.
   * Students learn to infer what a design can and cannot support.
   * This turns abstract design knowledge into reading habits.

**Core readings**

* William R. Shadish, Thomas D. Cook, and Donald T. Campbell, *Experimental and Quasi-Experimental Designs for Generalized Causal Inference*.
* Donald T. Campbell and Julian C. Stanley, *Experimental and Quasi-Experimental Designs for Research*.
* Miguel A. Hernán and James M. Robins, *Causal Inference: What If*, Chapters 1–3.
* Joshua D. Angrist and Jörn-Steffen Pischke, *Mastering ’Metrics*.
* Scott Cunningham, *Causal Inference: The Mixtape*.
* Angus Deaton and Nancy Cartwright, “Understanding and Misunderstanding Randomized Controlled Trials.”

---

## Unit 4 – Causal Diagrams, Confounding, and the Logic of Adjustment

**Guiding questions**

* How can simple causal diagrams clarify causal arguments?
* What are confounders, mediators, and colliders, and why do they matter?
* Why can controlling for the wrong variable make an analysis worse rather than better?

**Sub-units**

1. **Why draw causal diagrams?**

   * Causal diagrams make assumptions visible.
   * They help students represent rival causal stories clearly and compare them.
   * The goal is conceptual clarity, not mathematical formalism.

2. **Nodes, arrows, and causal pathways**

   * Variables as nodes, causal influence as directed arrows.
   * Directed acyclic graphs as simplified representations of causal structure.
   * Students learn that every diagram encodes assumptions, not facts beyond dispute.

3. **Confounders**

   * Common causes of both treatment and outcome.
   * Why confounding creates misleading associations.
   * Show how blocking confounding paths supports better causal comparison.

4. **Mediators**

   * Variables on the pathway between cause and effect.
   * Why adjusting for mediators can erase the very effect one is trying to understand.
   * Distinguish total effects from direct and indirect effects in a light-touch way.

5. **Colliders**

   * Common effects of two causes.
   * Why conditioning on a collider can introduce spurious association.
   * This is often counterintuitive and therefore especially important for critical thinking.

6. **Why more controls are not always better**

   * Students often assume all background variables should be added automatically.
   * This unit teaches that adjustment depends on causal role, not just availability.
   * Good control requires theory, not mere data abundance.

7. **Simpson’s paradox and stratification**

   * Association reversals when aggregated versus disaggregated.
   * Explain why the paradox is not just statistical weirdness but a sign of causal structure.
   * Connect to the need for careful conditioning and interpretation.

8. **Triangulation and converging evidence**

   * No single study or model settles most important causal questions.
   * Triangulation combines multiple designs, data sources, and theoretical perspectives.
   * Students learn to look for convergence rather than isolated proof.

9. **Micro-DAGs for public reasoning**

   * Rapid diagramming of headlines and policy claims.
   * “Adjust or don’t adjust?” flashcards for confounders, mediators, and colliders.
   * This is the course’s main visual reasoning practice.

**Core readings**

* Judea Pearl, Madelyn Glymour, and Nicholas P. Jewell, *Causal Inference in Statistics: A Primer*.
* Stephen L. Morgan and Christopher Winship, *Counterfactuals and Causal Inference*.
* Felix Elwert, “Graphical Causal Models.”
* Julia M. Rohrer, “Thinking Clearly About Correlations and Causation.”
* Selections from *The Book of Why*.
* George E. P. Box, “Science and Statistics” for the spirit of triangulation.

---

## Unit 5 – Causal Inference in Epidemiology and Public Health

**Guiding questions**

* How do epidemiology and public health reason from association to causation?
* What is the difference between population-level causal evidence and causal judgment in an individual case?
* How should causal claims about risk and harm be communicated?

**Sub-units**

1. **Association versus causation in epidemiology**

   * Epidemiology often begins with patterned associations in populations.
   * The challenge is to determine when those patterns support causal interpretation.
   * This connects directly to confounding, bias, and study design.

2. **Bradford Hill considerations**

   * Strength, consistency, temporality, dose-response, plausibility, coherence, experiment, analogy, and specificity.
   * Present these as considerations, not mechanical criteria.
   * Emphasize their role in disciplined judgment rather than checklist formalism.

3. **Confounding and exchangeability**

   * Public-health inference depends on whether exposed and unexposed groups are meaningfully comparable.
   * Introduce exchangeability conceptually through Hernán and Robins.
   * Show why comparability is often more important than sample size.

4. **General versus specific causation**

   * General causation: can exposure X cause outcome Y in a population?
   * Specific causation: did X cause this person’s outcome in this case?
   * This distinction is especially important for medicine, toxic torts, and regulation.

5. **Absolute versus relative risk**

   * Relative changes may sound dramatic while absolute changes remain modest.
   * Students learn to interpret effect magnitude in ways relevant to decision-making.
   * This is a key bridge to risk analysis and public communication.

6. **Causal reasoning under imperfect evidence**

   * Many public-health decisions must be made before certainty is possible.
   * Students examine how action, precaution, and uncertainty interact.
   * This unit helps them resist both naïve certainty and paralyzing skepticism.

7. **Population evidence, policy, and implementation**

   * Public-health interventions depend on institutions, uptake, compliance, and context.
   * Even when a cause is real, intervention effects may vary with implementation.
   * This connects causal inference to policy realism.

**Core readings**

* A. Bradford Hill, “The Environment and Disease: Association or Causation?”
* Kenneth J. Rothman, Sander Greenland, and Timothy L. Lash, *Modern Epidemiology* (selected conceptual sections).
* Miguel A. Hernán and James M. Robins, *Causal Inference: What If* (selected chapters on confounding and exchangeability).
* M. Susser, *Causal Thinking in the Health Sciences*.
* Nancy Cartwright and Jeremy Hardie, *Evidence-Based Policy* (selected sections on application and context).

---

## Unit 6 – Causal Inference in Economics and the Social Sciences

**Guiding questions**

* How do economists and social scientists infer causal effects when randomization is unavailable?
* What makes designs like IV, DiD, and RD persuasive?
* Why do assumptions and falsification tests matter as much as the estimated effect itself?

**Sub-units**

1. **The credibility revolution**

   * Economics increasingly emphasizes design-based inference.
   * The focus shifts from pure model specification to credible variation and transparent assumptions.
   * This is a major intellectual transformation in the social sciences.

2. **Natural experiments as opportunities for causal inference**

   * Institutions and policies sometimes create quasi-random variation.
   * Students learn to ask whether the variation is plausibly unrelated to the outcome except through the treatment.
   * Credibility depends on argument, not rhetorical labeling.

3. **Instrumental variables**

   * Instruments as encouragement devices or sources of indirect variation.
   * Basic idea: use variation in X that is plausibly independent of the confounders affecting Y.
   * Emphasize assumptions rather than formulas.

4. **Difference-in-differences**

   * Compare changes over time across treated and comparison groups.
   * Explain the logic of parallel trends in plain language.
   * Students learn why pre-trends and placebos matter.

5. **Regression discontinuity**

   * Threshold-based assignment rules.
   * Why units near a cutoff may be especially comparable.
   * Emphasize local causal effects and their limits.

6. **Falsification tests and credibility checks**

   * Balance checks, placebo outcomes, placebo treatments, and sensitivity to specification.
   * These are not decorations but part of the causal argument.
   * Students learn to look for evidence that would have counted against the claim.

7. **Causal inference and explanation in social science**

   * Social outcomes often arise through multiple interacting pathways.
   * This makes mechanisms and contextual knowledge especially important.
   * Connect to *Hunting Causes and Using Them* and to later work on mechanisms and cases.

**Core readings**

* Joshua D. Angrist and Jörn-Steffen Pischke, *Mastering ’Metrics*.
* Scott Cunningham, *Causal Inference: The Mixtape*.
* Stephen L. Morgan and Christopher Winship, *Counterfactuals and Causal Inference*.
* Nancy Cartwright and collaborators, *Hunting Causes and Using Them*.
* Selected chapters from *The Oxford Handbook of Causal Reasoning*.

---

## Unit 7 – Law, Responsibility, and Causation

**Guiding questions**

* How does legal causation differ from scientific causation?
* What is the difference between factual cause and proximate cause?
* How do standards of proof and expert evidence shape causal judgment in legal settings?

**Sub-units**

1. **Why law needs its own causal concepts**

   * Legal systems care not only about what caused what, but about responsibility, foreseeability, and institutional fairness.
   * This gives legal causation a partly normative structure.
   * Students learn that “cause” in law is not merely copied from science.

2. **Factual cause and the but-for test**

   * Basic test: but for the defendant’s action, would the harm have occurred?
   * This connects legal reasoning to ordinary counterfactual thinking.
   * Show its usefulness and its limitations.

3. **Multiple sufficient causes and material contribution**

   * Some harms have more than one sufficient cause.
   * In such cases, simple but-for reasoning can fail.
   * Introduce material contribution and related doctrines as legal responses to overdetermination problems.

4. **Proximate cause and scope of liability**

   * Foreseeability, scope of risk, remoteness, and policy limits.
   * Use the Palsgraf intuition to show that legal causation includes normative boundary-setting.
   * Distinguish causing harm from being legally answerable for it.

5. **Standards of proof**

   * Preponderance of the evidence in civil law.
   * Contrast with higher criminal thresholds where relevant.
   * Emphasize that standards of proof govern action under uncertainty, not certainty itself.

6. **Scientific and epidemiological evidence in court**

   * Expert testimony, epidemiological evidence, toxic torts, and probabilistic proof.
   * Introduce Daubert reliability factors and the judicial problem of evaluating science.
   * This is a crucial bridge between causal inference and institutional decision-making.

7. **Law as a special case of causal reasoning under uncertainty**

   * Legal institutions must make decisions even when evidence is incomplete.
   * This highlights the practical stakes of causal reasoning.
   * It also shows why causal standards may vary by domain and purpose.

**Core readings**

* H. L. A. Hart and Tony Honoré, *Causation in the Law*.
* Richard W. Wright, “Causation in Tort Law.”
* *Restatement (Third) of Torts* (selected sections on factual cause and proximate cause).
* *Reference Manual on Scientific Evidence* (selected chapters on epidemiology and statistics).
* *Palsgraf v. Long Island Railroad Co.*
* *Daubert v. Merrell Dow Pharmaceuticals, Inc.*
* *McGhee v. National Coal Board*.

---

## Unit 8 – AI, Machine Learning, and the Limits of Prediction

**Guiding questions**

* Why does accurate prediction not automatically yield causal understanding?
* What can causal reasoning contribute to AI and machine learning?
* How do fairness and counterfactual reasoning intersect?

**Sub-units**

1. **Prediction versus intervention**

   * A model may predict Y from X without X being a cause of Y.
   * This is the central limit of purely predictive systems.
   * Students learn why policy and explanation require more than predictive success.

2. **The ladder of causation in AI**

   * Pearl’s distinction between association, intervention, and counterfactual reasoning.
   * Use this to explain why much machine learning excels at association but struggles with intervention.
   * This gives students a conceptual map of AI’s causal limits.

3. **Causal discovery as hypothesis generation**

   * Data-driven discovery methods can suggest causal structures.
   * But discovery outputs do not eliminate the need for theory, design, and domain knowledge.
   * Emphasize caveats and responsible use.

4. **Counterfactual fairness**

   * Fairness can be framed in causal terms by asking whether a decision would differ under a counterfactual change in protected attributes or their downstream pathways.
   * This shows one concrete way causal reasoning enters contemporary algorithmic ethics.
   * It also reveals how fairness debates depend on causal assumptions.

5. **Feedback loops and adaptive systems**

   * Predictions can shape behavior, and behavior can alter future data.
   * This introduces a bridge from DAG-based reasoning to systems thinking and dynamic feedback.
   * Students see where simple acyclic models become strained.

6. **AI, explanation, and intervention**

   * The most socially important questions about AI are often causal:

     * What drove this decision?
     * What would change the outcome?
     * What intervention would improve performance or reduce harm?
   * This helps integrate the course’s philosophical and practical strands.

**Core readings**

* Jonas Peters, Dominik Janzing, and Bernhard Schölkopf, *Elements of Causal Inference*.
* Judea Pearl and Dana Mackenzie, *The Book of Why*.
* Matt J. Kusner, Joshua Loftus, Chris Russell, and Ricardo Silva, “Counterfactual Fairness.”
* Solon Barocas, Moritz Hardt, and Arvind Narayanan, *Fairness and Machine Learning* (conceptual chapters).
* Selected chapters from *The Oxford Handbook of Causal Reasoning*.

---

## Unit 9 – Mechanisms, Cases, and Causal Explanation

**Guiding questions**

* When is statistical evidence not enough?
* How do mechanism-based and case-based approaches strengthen causal reasoning?
* How can multiple weak forms of evidence combine into a strong explanatory case?

**Sub-units**

1. **Mechanisms and causal production**

   * Mechanisms specify how X brings about Y.
   * They are crucial for explanation, transfer, and intervention design.
   * This deepens the earlier distinction between difference-making and production.

2. **Mechanism maps and weak links**

   * Students practice narrating a causal chain and identifying where it might break.
   * This helps them evaluate claims that are statistically suggestive but explanatorily thin.
   * It also supports external-validity reasoning.

3. **Process tracing within cases**

   * Use within-case evidence to test competing causal stories.
   * Students learn “hoop tests” and “smoking gun” tests as structured ways of evaluating case evidence.
   * This introduces a disciplined form of qualitative causal inference.

4. **Case studies and theory development**

   * Cases can generate hypotheses, refine concepts, and test mechanisms.
   * They are not merely anecdotal when used systematically.
   * This is especially important in history, political science, and organizational analysis.

5. **Qualitative Comparative Analysis**

   * Conjunctive causation, equifinality, and causal recipes.
   * Some outcomes arise through multiple sufficient combinations rather than one dominant cause.
   * QCA helps students think beyond single-variable models.

6. **Consilience and triangulation**

   * A strong causal case may emerge from multiple imperfect strands of evidence.
   * Students learn to appreciate rope-like evidence rather than demanding a single decisive proof.
   * This reinforces the course-wide theme of triangulation.

7. **Mechanisms and transportability**

   * Mechanism knowledge helps us judge whether a causal relation will travel across settings.
   * This reconnects explanation, policy, and generalization.
   * It also shows why abstract effect estimates are not enough.

**Core readings**

* Peter Hedström and Petri Ylikoski, “Causal Mechanisms in the Social Sciences.”
* Alexander L. George and Andrew Bennett, *Case Studies and Theory Development in the Social Sciences*.
* Derek Beach and Rasmus Brun Pedersen, *Process-Tracing Methods*.
* Charles C. Ragin, *The Comparative Method* and *Redesigning Social Inquiry*.
* Nancy Cartwright and Jeremy Hardie, *Evidence-Based Policy*.
* James Woodward, *Making Things Happen* (selected chapters on explanation).

---

## Unit 10 – Judging, Communicating, and Using Causal Claims

**Guiding questions**

* How should non-specialists read causal claims responsibly?
* What should a good public-facing causal summary include?
* How do we use causal evidence without exaggerating certainty?

**Sub-units**

1. **Effect size, importance, and heterogeneity**

   * A statistically detectable effect may still be practically minor.
   * Average effects can conceal important subgroup differences.
   * Students learn to distinguish magnitude from significance and average from variation.

2. **Uncertainty in plain language**

   * Intervals as ranges of reasonable values.
   * Robustness checks and sensitivity analyses as more informative than ritual thresholding.
   * This section emphasizes honest uncertainty communication.

3. **Common mistakes in causal interpretation**

   * Post hoc reasoning.
   * Base-rate neglect.
   * Regression to the mean.
   * Selection bias.
   * p-hacking and garden-of-forking-paths.
   * Reverse causation and overcontrol.

4. **How to write an honest causal summary**

   * What is the question?
   * What design identifies it?
   * What assumptions matter?
   * How large is the effect?
   * How uncertain is it?
   * Will it generalize?

5. **The Causal Claim Skeptic’s Checklist**

   * A compact final framework for reading and evaluating claims.
   * This turns the course into a reusable critical-thinking habit.
   * It serves as a synthesis of vocabulary, design, diagrams, mechanisms, and communication.

6. **Using causal claims in decision-making**

   * Policy, medicine, law, and personal decision-making often require action before certainty.
   * Students learn to ask whether the evidence is good enough for the decision at hand.
   * This is the practical endpoint of the course.

7. **Bridges to later courses**

   * Risk analysis: translating causal effects into expected harms and benefits.
   * Cognitive bias: why humans distort causal evidence.
   * Model thinking: when to use DAGs, narratives, case evidence, or formal models.
   * Systems thinking: when feedback and nonlinearity challenge simple causal claims.

**Core readings**

* David Spiegelhalter, *The Art of Statistics* (communication chapters).
* American Statistical Association, statement on p-values and plain-language commentary.
* Gerd Gigerenzer, *Calculated Risks*.
* John P. A. Ioannidis, “Why Most Published Research Findings Are False.”
* Steven Sloman, *Causal Models*.
* Daniel Kahneman, *Thinking, Fast and Slow* (selected chapters on causal stories and judgment).

---

## Teaching moves

* **One-page design cards** for RCT, natural experiment, DiD, IV, RD, Bradford Hill considerations, and law’s distinction between factual and proximate cause.
* **Micro-DAGs in the margin** whenever a claim appears, with a one-line note about what would need to be blocked or clarified.
* **Two plausible stories boxes** showing rival causal diagrams and the evidence needed to distinguish them.
* **Case vignettes across domains** such as vaccine trials, minimum-wage studies, toxic tort litigation, and fairness audits in machine learning.
* **Mechanism maps** paired with effect claims so students learn to ask not only whether an effect exists, but how it is supposed to arise.
* **Triangulation prompts** asking what second line of evidence would strengthen or weaken confidence in a claim.

---

## Possible capstone activities

* **Headline Autopsy: Reading Causal Claims in the Wild**

  Students collect several public claims from journalism, policy, health communication, or advertising and:

  * classify each as causal, predictive, descriptive, or ambiguous
  * identify the implied causal question
  * infer what research design would be needed to justify the claim
  * sketch a micro-DAG showing at least one rival explanation
  * rewrite the claim in more responsible language

* **Design Choice Memo**

  Students are given several real-world constraints—ethical, financial, institutional, and temporal—and must:

  * choose among an RCT, natural experiment, DiD design, RD design, case study, or process-tracing approach
  * justify the choice in terms of identification and feasibility
  * identify the main threats to validity
  * explain what would count as a useful falsification or robustness check

* **Law and Causation Case Lab**

  Students analyze a short tort-style case and:

  * distinguish factual from proximate cause
  * identify whether but-for reasoning is sufficient
  * explain whether epidemiological or mechanistic evidence would help
  * state what standard of proof is relevant
  * write a short judgment-style explanation

* **Mechanism and Triangulation Portfolio**

  Students choose a policy or scientific claim and:

  * state the main causal hypothesis
  * map one plausible mechanism
  * identify one design-based source of evidence and one case-based source of evidence
  * explain how the two sources complement each other
  * assess how well the causal claim would travel to another context

---

## Glossary

**Counterfactual**; **Difference-making**; **Confounder**; **Mediator**; **Collider**; **Identification**; **Estimation**; **Internal validity**; **External validity**; **Transportability**; **Natural experiment**; **Instrument**; **Difference-in-differences**; **Regression discontinuity**; **Mechanism**; **Capacity**; **Process tracing**; **QCA**; **Triangulation**; **General causation**; **Specific causation**; **Factual cause**; **Proximate cause**; **Material contribution**.

---