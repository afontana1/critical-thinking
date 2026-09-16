# Course Overview: Model Thinking – From System Stories to Explicit Models

This course sits **after Systems Thinking** and **builds on it**.

* Analytical Thinking → you learned to decompose problems, analyze decisions, and evaluate policies.
* Systems Thinking → you learned to see **feedback, structure, and dynamics**.
* **Model Thinking** → now you learn to **build, combine, critique, and use models** as *explicit tools* for understanding and acting in the world.

The course is **not math-heavy**. Equations are optional compact expressions of rules, not prerequisites; students can work with diagrams, tables, and hand-worked examples.

**Running case — a service backlog:** Revisit a service team whose unfinished requests accumulate when arrivals exceed completed work. Carry forward the Systems Thinking view, then make one model explicit, check it, vary it, compare alternatives, and document its limits. Students may instead carry forward their own Systems Thinking capstone; no programming or full optimization is required.

**A recurring model-use test:** For every model, specify the question and intended use (explain, explore, predict, or support a decision); its target and boundaries; its assumptions and outputs; and what evidence would be needed to justify that *particular* use. Showing that a mechanism is possible inside a model does not establish that it occurs, is frequent, or will respond to an intervention the same way in the world.

## Table of Contents

<!-- UNIT_TOC_START -->
- [Unit 1 – What Is a Model? Why Model?](#unit-1)
- [Unit 2 – Purposes and Limits of Models (“Model Land”)](#unit-2)
- [Unit 3 – Types of Models and Multi-Model Thinking](#unit-3)
- [Unit 4 – From System Stories to Formal Models](#unit-4)
- [Unit 5 – Data, Calibration, and Validation (Conceptual)](#unit-5)
- [Unit 6 – Uncertainty, Sensitivity, and Robustness](#unit-6)
- [Unit 7 – Simulation and Agent-Based Modeling](#unit-7)
- [Unit 8 – Optimization and Decision Models (Light OR)](#unit-8)
- [Unit 9 – Models in Policy, Ethics, and Power](#unit-9)
- [Unit 10 – Integrating the Model Lens](#unit-10)
<!-- UNIT_TOC_END -->

**Big question:**
How can we build, combine, critique, and use models as explicit tools for understanding, exploring, and acting in the world without mistaking those models for reality itself?

**By the end, students should be able to:**

* Define a **model** as a deliberately simplified representation built to answer particular questions.
* Distinguish between **mental models** and **formal models**.
* Explain the main purposes of models: **explanation, prediction, exploration, design, and communication**.
* Recognize the limits of models, including the difference between **“Model Land”** and the messy real world.
* Identify major **types of models** and assess when complementary models add insight, disagree, or share blind spots.
* Translate **system stories and diagrams** into explicit rules or model structures, stating units, time steps, and omissions.
* Explain, conceptually, how models connect to **data, calibration, and validation**.
* Reason about **uncertainty, sensitivity, and robustness** in model-based analysis.
* Understand when **simulation and agent-based modeling** are useful.
* Explain how **optimization and decision models** represent objectives, constraints, and trade-offs.
* Critically evaluate how models are used in **policy, ethics, and power**.
* Produce a concise **model dossier** that states intended and unsupported uses, checks, sensitivity, alternatives, and decision caveats.

---

<a id="unit-1"></a>
## Unit 1 – What Is a Model? Why Model?

**Guiding questions**

* What is a model?
* Why are models central to science, policy, and everyday reasoning?
* How does model thinking build on systems thinking?

**Sub-units**

1. **Models as representations**

   * Working definition:

     > A **model** is a deliberately simplified representation of some aspect of the world, built to answer particular questions.
   * Types of representation:

     * Verbal narratives.
     * Diagrams (system maps, CLDs, stock–flow diagrams).
     * Mathematical models (equations).
     * Computational models (simulation, agent-based).
     * Physical models (scale models, prototypes).
   * Emphasize: *every* model involves **choices**: what to include, what to ignore, what to hold constant.

2. **Mental models vs. formal models**

   * Mental models: tacit “movies in your head” about how things work.
   * Formal models: explicit artifacts (equations, diagrams, code) that can be:

     * Shared,
     * Critiqued,
     * Tested,
     * Modified.
   * Key idea: even an informal explanation contains assumptions; making them explicit allows others to question them. Epstein’s “Why Model?” introduces the value of explicit modeling. ([JASSS][1])

3. **Why model?**

   * Explanation: Why did this pattern happen?
   * Prediction/forecasting: What might happen if trends continue?
   * Exploration: “What-if?” experiments in silico (policy options, scenarios).
   * Design: Trying out structural changes (new rules, incentives) in a model before reality.
   * Communication: Shared object for interdisciplinary teams.

**Practice — a model description card:** Compare a verbal backlog story, its Systems Thinking diagram, and a simple rule-based account. For each, record **purpose, target, representation, assumptions, outputs, and intended use**; note what becomes clearer or remains hidden.

**Local core readings (selected):** Epstein, “Why Model?” (repository file `1. What is a model/epstein - why model.pdf`); Scott E. Page, *The Model Thinker*, introductory selection (`books/Scott E. Page - The Model Thinker.pdf`). The repository metadata for the short “Why Model?” files is inconsistent on authorship; use the PDF title page for a formal citation.

**Optional local / external:** Page, *Model Thinking Course Notes* (selected opening material); Frigg & Hartmann, “Models in Science,” *Stanford Encyclopedia of Philosophy* (external conceptual overview). ([Stanford Encyclopedia of Philosophy][3])

---

<a id="unit-2"></a>
## Unit 2 – Purposes and Limits of Models (“Model Land”)

**Guiding questions**

* Why should students become suspicious of models in a healthy way?
* What is “Model Land”?
* When do models clarify, and when do they mislead?

**Sub-units**

1. **Model Land vs. real world**

   * From Erica Thompson: “Model Land” = the clean, idealized universe in which the model’s assumptions are exactly true. ([LSE Blogs][4])
   * Real world = open systems, noisy data, changing behavior, incomplete knowledge.
   * Core tension: models are powerful *because* they ignore things, and dangerous *because* they ignore things.

2. **Idealization and abstraction**

   * Helpful idealizations:

     * Spherical cow, frictionless plane, rational agents, homogeneous populations.
   * Risks:

     * Leaving out critical mechanisms (e.g., feedbacks, heterogeneity) that dominate behavior in reality.
   * Link back to **Systems Thinking**: omission of feedback or delays can fundamentally change system behavior.

3. **Explanation vs. prediction vs. control**

   * Many models are **explanatory or exploratory**, not predictive:

     * They clarify mechanisms, not produce exact forecasts.
   * Distinguish:

     * Using models for **scenario exploration** vs. **numerical prediction**.
     * Using models to **understand** vs. to **justify** decisions.

4. **Model scope and domain of applicability**

   * Every model has:

     * A target system (what it’s about),
     * A scale (micro/macro),
     * A time horizon,
     * A regime where it works reasonably well.
   * “All models are wrong, but some are useful”: translate into *“All models are limited; clarify the limits.”*
   * **Fitness for purpose is not the same as realism:** a stripped-down model can illuminate a possible mechanism without estimating how common it is or reliably forecasting an intervention.

**Practice — permitted and unsupported uses:** Given the backlog model, distinguish “this rule can produce a growing backlog” from “this is the true cause of this team’s backlog” and “this staffing change will reduce it.” List the additional evidence each stronger claim would need.

**Local core readings (selected):** Erica Thompson, *Escape from Model Land* (opening discussion of model assumptions and use); Edmonds et al., “Different Modelling Purposes” (`2. Purpose and Limits of Models/different modeling purposes.pdf`).

**Optional external:** Oreskes et al. (1994), “Verification, Validation, and Confirmation of Numerical Models in the Earth Sciences” (on limits of confirmation; distinguish this from checking whether code implements its specification). ([Science][5])

---

<a id="unit-3"></a>
## Unit 3 – Types of Models and Multi-Model Thinking

**Guiding questions**

* What kinds of models are there?
* Why is model pluralism important?
* How do we choose among model families?

**Sub-units**

1. **A taxonomy of models (light-touch)**

   * Categories (with intuitive examples, not derivations):

     * **Statistical models**: regression, classification, time-series models.
     * **Mechanistic models**: differential equations (epidemics, population growth).
     * **Network models**: contagion, influence, infrastructure.
     * **Optimization/decision models**: choosing best options under constraints.
     * **Agent-based models**: interacting, heterogeneous agents.
     * **Game-theoretic models**: strategic interaction.
     * **System dynamics models**: stocks, flows, feedback structures turned numeric.

2. **The many-model idea**

   * From Page: each model captures a **different slice** of reality (spatial, temporal, structural, behavioral). ([Mande][6])
   * Potential benefits of multiple models:

     * Reveal different mechanisms and assumptions.
     * Expose sensitivity to how a problem is represented.
     * Stress-test conclusions when the models offer meaningfully different perspectives.
   * **Plurality is not automatic validation:** models may share data, assumptions, and omissions; their outputs may measure different things. Disagreement may be more informative than averaging.

3. **Model ensembles in practice**

   * Climate science: multi-model ensembles to represent structural uncertainty. ([ScienceDirect][7])
   * Integrated assessment models for climate policy: multiple models, multiple futures. ([NBER][8])
   * Lesson: ask whether a set of models meaningfully spans relevant uncertainties before treating agreement or a range of outputs as informative.

4. **Choosing a model family**

   * Based on:

     * Question type (explain, predict, explore, design).
     * Available data.
     * Level of detail needed.
     * Complexity of system (complicated vs. complex).

**Practice — two models, one phenomenon:** Compare the local Granovetter threshold model with the Miller–Page standing-ovation model. Identify what each represents, leaves out, and measures; determine which questions their outputs can and cannot answer. Do not combine unlike outputs into a single score.

**Local core readings (selected):** Page, *The Model Thinker* or *Model Thinking Course Notes* (an instructor-selected model comparison); Granovetter, “Threshold Models of Collective Behavior” (`3. Types of Models and Multi-Model Thinking/modelthinking_01.06_Granovetter_Model.pdf`); Miller & Page, “The Standing Ovation Problem” (same folder, `modelthinking_01.06_Miller_Page_Model.pdf`).

**Optional external:** Winsberg, “Computer Simulations in Science,” *Stanford Encyclopedia of Philosophy*. ([Stanford Encyclopedia of Philosophy][9])

---

<a id="unit-4"></a>
## Unit 4 – From System Stories to Formal Models

**Guiding questions**

* How do we move from system narratives and diagrams to simple formal models?
* What choices are involved in that translation?
* Why are toy models useful?

**Sub-units**

1. **From problem to model purpose**

   * Start from a clarified question:

     * “What are we trying to understand, predict, or decide?”
   * Define:

     * Inputs (parameters, assumptions),
     * Outputs (what we’ll examine),
     * Key mechanisms (feedbacks, interactions).

2. **Variable selection and aggregation**

   * Decide what to treat as:

     * State variables (stocks),
     * Control variables (decisions),
     * Exogenous drivers (scenarios).
   * Aggregation tradeoffs:

     * Aggregate individuals into groups vs. model them as agents.
     * Aggregate time into steps (daily, yearly).

3. **Translating diagrams to equations or rules**

   * You did CLDs and BOTGs in Systems Thinking; now:

     * A **stock–flow** diagram becomes a difference or differential equation.
     * A **network** diagram becomes rules for how influence or contagion spreads.
     * An **interaction diagram** becomes agent rules in an ABM.
   * Emphasize *logic*: if a stock increases when inflow exceeds outflow, how do we express that?
   * **Worked backlog rule:** next backlog = current backlog + arriving requests − completed requests (assuming no cancellations or reclassification). State the time step (such as one week), unit (requests), and nonnegative-capacity constraints; an equation is optional shorthand for a verbal or tabular rule.

4. **Toy models**

   * Use very simple, deliberately unrealistic models to:

     * Clarify mechanisms,
     * Separate structural effects from parameter details.
   * Examples:

     * Simple SIR epidemic model,
     * Schelling segregation model,
     * Logistic growth with carrying capacity.

**Practice — make the running case explicit:** Specify the backlog model’s inputs, output, parameters, state variable, controllable decision, assumptions, and chosen time step. Work through two periods by hand; identify a situation (such as variable request complexity) where the toy rule becomes inadequate. Keep the richer epidemic, segregation, and growth examples optional.

**Local core reading:** Paul E. Smaldino, “How to Translate a Verbal Theory Into a Formal Model” (`1. What is a model/How to translate a verbal theory into a formal model.pdf`; selected accessible sections).

**Optional local examples:** Lamberson & Page, “Tipping Points” (`4. From System Stories to Formal Models/tippingpoints.pdf`); Page’s *Model Thinking Course Notes* (instructor-selected toy-model example).

---

<a id="unit-5"></a>
## Unit 5 – Data, Calibration, and Validation (Conceptual)

**Guiding questions**

* How do models connect to data?
* What do calibration, fitting, and validation mean conceptually?
* Why should models be treated as arguments rather than oracles?

**Sub-units**

1. **Models of data vs. models of systems**

   * Models of data: statistical models that summarize patterns (regression, time-series).
   * Models of systems: mechanistic models with explicit structure.
   * Some models are estimated from data; others deliberately stipulate mechanisms to explore their implications. **Not every model is fitted to observations.**

2. **Calibration / fitting**

   * Where relevant, adjust or estimate parameters using observed data and document which observations were used. Some exploratory models instead use clearly stipulated values.
   * Distinguish:

     * **Parameter choice by theory** vs. **parameter estimation from data**.
   * Overfitting vs. underfitting, conceptually:

     * Too many knobs → model fits noise.
     * Too few knobs → model cannot capture key patterns.

3. **Implementation checks, validation, and confirmation (conceptual only)**

   * **Implementation / verification:** does the rule, spreadsheet, or program do what its specification says? This differs from whether the specification fits reality.
   * **Calibration:** which values were chosen from theory, stipulated for exploration, or estimated using data?
   * **Validation for an intended use:** compare relevant outputs or patterns with appropriate evidence; when assessing prediction, use genuinely held-out data where possible. An exploratory model may instead be checked for internal coherence and whether its mechanism is plausible.
   * No single test proves a model true or validates every possible use. Ask: “Where does it work, for what purpose, and where does it fail?”

4. **Models as arguments, not oracles**

   * Treat running a model like making a **structured argument**:

     * Premises = assumptions & inputs,
     * Reasoning = model structure,
     * Conclusion = outputs.
   * Critical thinking = interrogating all three.

**Practice — an evidence plan:** For the backlog rule, document what administrative records could inform arrivals and completions, what was used to choose any parameters, one implementation check, and a separate test of its intended use. Do not call matching the data used for fitting independent validation.

**Local core reading:** Collins, Koehler & Lynch, “Methods That Support the Validation of Agent-Based Models: An Overview and Discussion” (`5. Data Calibration and Validation/Methods that Support Validation of Agent Based Models.pdf`; selected conceptual sections, with its ABM scope stated).

**Optional external:** Oreskes et al. (1994), “Verification, Validation, and Confirmation of Numerical Models in the Earth Sciences.” ([Science][5])

---

<a id="unit-6"></a>
## Unit 6 – Uncertainty, Sensitivity, and Robustness

**Guiding questions**

* What kinds of uncertainty matter in models?
* What does sensitivity analysis do?
* How should modelers think about robustness?

**Sub-units**

1. **Types of uncertainty**

   * Parameter uncertainty (we don’t know exact values).
   * Structural uncertainty (we’re not sure we have the right mechanisms).
   * Scenario uncertainty (we don’t know future policies, technologies, behavior).

2. **Sensitivity analysis (conceptual view)**

   * Idea: systematically vary assumptions and see how outputs change.
   * Questions:

     * Which parameters really matter for the conclusions?
     * Where are we “fragile” to assumption changes?
   * Global sensitivity analysis is a deeper extension, not a required technique in this course. ([andreasaltelli.eu][13])

3. **Robustness and model-based decision-making**

   * Instead of one “optimal” plan:

     * Seek strategies that perform **acceptably well** across many plausible futures.
   * Connect to earlier **decision analysis** and **complex systems**:

     * Stress testing and scenario planning.

4. **Multi-model and multi-scenario ensembles**

   * Ensembles can display variation across included parameters, scenarios, or model structures, **not the full space of possibilities**.
   * Agreement among models with shared assumptions or data is not independent confirmation; report excluded scenarios as well as the range shown.

**Practice — two sensitivity checks:** Change the assumed arrivals or processing rate in a two-period backlog table and record the outcome. Then alter the *structure* (for example, processing capacity falls when staff are overloaded). State which conclusion persists and which depends on the chosen rule; neither exercise estimates real-world likelihoods by itself.

**Local core reading:** Thompson, *Escape from Model Land* (selected passages on uncertainty and model dependence).

**Optional external / acquisition gap:** Saltelli et al., *Global Sensitivity Analysis: The Primer* (introductory conceptual selection). ([andreasaltelli.eu][13]) A short nontechnical parameter-versus-structure sensitivity handout would fill a focused repository gap; full global sensitivity methods are not required.

---

<a id="unit-7"></a>
## Unit 7 – Simulation and Agent-Based Modeling

**Guiding questions**

* What is an agent-based model?
* When should we use simulation and ABM?
* How does simulation turn qualitative complexity ideas into explicit experiments?

**Sub-units**

1. **What is an agent-based model?**

   * Agents with:

     * States,
     * Rules for behavior,
     * Rules for interaction.
   * Environment:

     * Spatial (grid, network) or abstract (e.g., market).
   * Emergent behavior from repeated interactions.

2. **When to use ABM**

   * Heterogeneous agents matter (different types/roles).
   * Local interactions produce global patterns (segregation, cascades, norms).
   * Adaptation and learning (changing rules over time).

3. **ABM workflow (conceptual)**

   * Define purpose and questions.
   * Specify agent types and rules.
   * Optionally implement a simulation (NetLogo or Python may be mentioned, but **coding is not required**).
   * Run experiments across parameter ranges.
   * Analyze emergent patterns, compare to data.

4. **Examples and case studies**

   * Schelling segregation model.
   * Opinion dynamics or contagion on networks.
   * A simple urban health or social behavior ABM as an optional application. ([PMC][14])

**Practice — one conceptual simulation experiment:** Sketch agents, states, behavioral and interaction rules, an outcome measure, and one rule to vary. Run a few rounds by hand or explain how a simulation would run. Distinguish a pattern demonstrated *inside the stipulated model* from a claim that the real population behaves that way.

**Local core reading:** Nigel Gilbert, “Agent Based Modeling and Simulation” (`7. Simulation & Agent Based Models/Agent Based Modeling and Simulation - An Informatics Perspective.pdf`; introductory selection).

**Optional local:** Elsenbroich, “Explanation in Agent-Based Modelling: Functions, Causality or Mechanisms?”; Waldherr & Wijermans, “Communicating Social Simulation Models to Sceptical Minds” (both in the Unit 7 folder). Further specialist ABM studies are references, not a required reading sequence.

**Optional external:** Introductory ABM guide for public health or social science. ([PMC][14])

---

<a id="unit-8"></a>
## Unit 8 – Optimization and Decision Models (Light OR)

**Guiding questions**

* How can models be built explicitly for choosing actions?
* How do objectives, constraints, and trade-offs enter a model?
* What can optimization clarify even in a light, non-technical treatment?

**Sub-units**

1. **Optimization as a modeling activity**

   * General template:

     * Decide on **decision variables** (what can we choose?),
     * Define **objective function** (what are we trying to maximize/minimize?),
     * Specify **constraints** (resources, capacities, rules).
   * Examples:

     * Allocating limited budget across programs.
     * Choosing staffing levels or schedules.
     * Portfolio-like trade-offs (risk vs. return).

2. **Objectives, metrics, and value choices**

   * Objectives encode **value judgments**:

     * Efficiency vs. equity,
     * Short-term vs. long-term.
   * Multi-objective trade-offs:

     * Different objectives can lead to different admissible trade-offs; a model optimum is conditional on its stated objective and constraints.

3. **From real problem to optimization model**

   * Step-by-step formulation practice:

     * Start with a narrative description.
     * Identify decisions, constraints, and outcomes.
     * Translate into a simple mathematical or tabular model.
   * Emphasize: even a rough spreadsheet model can clarify trade-offs.

4. **Algorithmic ideas in everyday decisions**

   * Connect to algorithmic thinking from Analytical unit:

     * Optimal stopping (when to stop searching),
     * Explore–exploit (trying new vs. known options),
     * Scheduling and queuing (waiting times).
   * Use these as **conceptual models** for personal and organizational choices.

**Practice — a constrained choice table:** Using the backlog case, list possible staffing or scheduling changes, a fixed capacity or budget constraint, and two distinct objectives (for example, waiting time and staff workload). Compare alternatives transparently. Explain why a solution preferred by the model may not be acceptable to all affected people; no solver is needed.

**Local core readings (selected):** Craig W. Kirkwood, introductory decision-theory chapter (`8. Optimization and Decision Models/Decision_Theory.pdf`); *Multi_Criteria_Decisionmaking.pdf* (same folder; verify its full bibliographic title and attribution before citing formally).

**Optional local:** `Linear_Models.pdf` (same folder; PDF metadata title is unreliable). Keep programming, game theory, and full operations research outside the required scope.

---

<a id="unit-9"></a>
## Unit 9 – Models in Policy, Ethics, and Power

**Guiding questions**

* How are models used in public decision-making?
* What political, ethical, and institutional issues arise around models?
* How should model critique be part of model thinking?

**Sub-units**

1. **Models as decision support, not decision makers**

   * Models inform:

     * Policy options,
     * Impact assessments,
     * Risk evaluations.
   * Danger of “model worship”: hiding value judgments behind technical language.

2. **Whose model? For whom? With what data?**

   * Questions to ask:

     * Who built the model, funded it, and controls it?
     * What interests or values are embedded in:

       * Choice of objective,
       * Constraints,
       * Scenarios considered?
   * Transparency and participatory modeling:

     * Involving stakeholders in problem framing and assumption checking.

3. **Case studies**

   * Climate policy:

     * Integrated assessment models and ethical assumptions about discounting & equity. ([NBER][8])
   * Pandemic modeling:

     * Trade-offs between health and economic objectives (at a conceptual level).
   * Risk of models reinforcing existing power structures if used uncritically.

4. **Critique as part of model thinking**

   * Connect back to Analytical & Systems units:

     * Assumption audits,
     * System boundaries,
     * Framing effects.
   * Encourage learners to:

     * Ask for model documentation,
     * Question the fit between model purpose and use,
     * Consider distributional impacts (who gains/loses),
     * Distinguish evidence about performance from judgments about values, authority, and legitimate use.

**Practice — model-governance audit:** Using the backlog model or an instructor-provided example, identify who frames its question, whose circumstances it represents, who can inspect or challenge its assumptions, and how different groups might experience a decision based on its outputs. Do not infer decision-makers’ private motives from the model alone.

**Local core reading:** Thompson, *Escape from Model Land* (selected chapters on subjectivity, value judgments, and power).

**Optional external:** Morgan, *The World in the Model* (selected chapters). The Unit 9 repository folder contains specific model examples, not a general replacement for this ethics discussion.

---

<a id="unit-10"></a>
## Unit 10 – Integrating the Model Lens

**Guiding questions**

* What practical habits should learners use when they encounter or build a model?
* How does model thinking connect back to analytical and systems thinking?
* How can a capstone project bring the whole unit together?

**Sub-units**

1. **Model-thinking checklist / dossier rubric**

   When you meet a model (or build one), document:

   * **Purpose and scope:** What question, target, time horizon, and intended use does it address? What uses are unsupported?
   * **Representation:** What form does it take, and what important features are omitted?
   * **Assumptions and structure:** What rules, variables, units, parameters, and boundaries matter?
   * **Evidence and checks:** What informed inputs? What implementation check and use-specific test are possible? Which data, if any, were held out?
   * **Alternatives and uncertainty:** What different representation might reveal something else? What happens if a parameter or structural assumption changes?
   * **Use and ethics:** Who may rely on the result, who is affected, and which value judgments are not supplied by the model?

2. **Capstone — concise model dossier**

   Extend the **Systems Thinking capstone** (or use the running service-backlog case); do not start an unrelated project merely to satisfy this course. Submit a compact dossier containing:

   1. A purpose statement identifying the intended question and at least one **unsupported use**.
   2. A model sketch, rule table, or simple hand-worked example with explicit variables, time steps, and assumptions; no programming is required.
   3. One alternative representation or model family, identifying what differs and whether the outputs can be compared.
   4. An evidence plan separating parameter choice, implementation checks, and evidence appropriate to the intended use.
   5. At least one **parameter** and one **structural** sensitivity check, with a brief account of what changed.
   6. A decision-use caveat addressing limitations, affected people, and observations that would prompt revision.

   A model that has been explored but not tested against real observations must be labeled **exploratory**, not presented as an empirically validated forecast or intervention estimate.

3. **Connecting back to the whole course**

   * **Analytical Thinking**:

     * Gave you tools to frame problems, reason with evidence, and evaluate decisions.
   * **Systems Thinking**:

     * Gave you a lens for structure, feedback, and emergence.
   * **Model Thinking**:

     * Gave you tools to *build explicit representations* that you can test, combine, and critique.
   * Big meta-message: **Models are limited tools; assess whether the representation and supporting evidence justify the particular use.**

**Local synthesis readings:** Revisit selected sections of Page, *The Model Thinker* / *Model Thinking Course Notes*, and Thompson, *Escape from Model Land*. No new full book is required.

**Optional external:** SEP entries “Models in Science” and “Computer Simulations in Science” for philosophical context. ([Stanford Encyclopedia of Philosophy][3]) ([Stanford Encyclopedia of Philosophy][9])

---

[1]: https://www.jasss.org/11/4/12.html "Why Model?"

[3]: https://plato.stanford.edu/entries/models-science/ "Models in Science - Stanford Encyclopedia of Philosophy"
[4]: https://blogs.lse.ac.uk/lsereviewofbooks/2023/11/30/book-review-escape-from-model-land-how-mathematical-models-can-lead-us-astray-and-what-we-can-do-about-it-erica-thompson/ "Escape from Model Land: How Mathematical Models Can ..."
[5]: https://www.science.org/doi/10.1126/science.263.5147.641 "Verification, Validation, and Confirmation of Numerical ..."
[6]: https://mande.co.uk/2019/media-3/books/the-model-thinker-what-you-need-to-know-to-make-data-work-for-you/ "THE MODEL THINKER What You Need to Know to Make ..."
[7]: https://www.sciencedirect.com/science/article/pii/S2212094724000495 "A novel approach to a multi-model ensemble for climate ..."
[8]: https://www.nber.org/system/files/working_papers/w21637/w21637.pdf "Modeling Uncertainty in Climate Change"
[9]: https://plato.stanford.edu/entries/simulations-science/ "Computer Simulations in Science"

[13]: https://www.andreasaltelli.eu/file/repository/A_Saltelli_Marco_Ratto_Terry_Andres_Francesca_Campolongo_Jessica_Cariboni_Debora_Gatelli_Michaela_Saisana_Stefano_Tarantola_Global_Sensitivity_Analysis_The_Primer_Wiley_Interscience_2008_.pdf "Global Sensitivity Analysis. The Primer"
[14]: https://pmc.ncbi.nlm.nih.gov/articles/PMC5391997/ "Brief introductory guide to agent-based modeling and an ..."
