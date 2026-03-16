# Course Overview: Model Thinking – From System Stories to Explicit Models

This unit sits **after Systems Thinking** and **builds on it**.

* Analytical Thinking → you learned to decompose problems, analyze decisions, and evaluate policies.
* Systems Thinking → you learned to see **feedback, structure, and dynamics**.
* **Model Thinking** → now you learn to **build, combine, critique, and use models** as *explicit tools* for understanding and acting in the world.

The unit is **not math-heavy**. Equations are treated as *examples* rather than prerequisites.

**Big question:**
How can we build, combine, critique, and use models as explicit tools for understanding, exploring, and acting in the world without mistaking those models for reality itself?

**By the end, students should be able to:**

* Define a **model** as a deliberately simplified representation built to answer particular questions.
* Distinguish between **mental models** and **formal models**.
* Explain the main purposes of models: **explanation, prediction, exploration, design, and communication**.
* Recognize the limits of models, including the difference between **“Model Land”** and the messy real world.
* Identify major **types of models** and explain why **multi-model thinking** is often better than relying on a single model.
* Translate **system stories and diagrams** into more explicit model structures.
* Explain, conceptually, how models connect to **data, calibration, and validation**.
* Reason about **uncertainty, sensitivity, and robustness** in model-based analysis.
* Understand when **simulation and agent-based modeling** are useful.
* Explain how **optimization and decision models** represent objectives, constraints, and trade-offs.
* Critically evaluate how models are used in **policy, ethics, and power**.
* Use a practical **model-thinking checklist** to interrogate or build a model responsibly.

---

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
   * Key idea (from Epstein): “If you have a thought about how something works, you already have a model; it’s just implicit and untested.” ([JASSS][1])

3. **Why model?**

   * Explanation: Why did this pattern happen?
   * Prediction/forecasting: What might happen if trends continue?
   * Exploration: “What-if?” experiments in silico (policy options, scenarios).
   * Design: Trying out structural changes (new rules, incentives) in a model before reality.
   * Communication: Shared object for interdisciplinary teams.

**Core readings**

* Joshua Epstein, “Why Model?” (*Journal of Artificial Societies and Social Simulation*, 2008). ([JASSS][1])
* Scott E. Page, *The Model Thinker*, Introduction (what models are, many-model idea). ([Amazon][2])
* Roman Frigg & Stephan Hartmann, “Models in Science,” *Stanford Encyclopedia of Philosophy* (overview of types, roles of models in science). ([Stanford Encyclopedia of Philosophy][3])

---

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

**Core readings**

* Erica Thompson, *Escape from Model Land*, chapters on how models go wrong and how to “escape” (especially early chapters). ([LSE Blogs][4])
* Naomi Oreskes et al., “Verification, Validation, and Confirmation of Numerical Models in the Earth Sciences,” *Science* (1994) – why full “verification” is impossible and what partial confirmation means. ([Science][5])

---

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
   * Benefits of many models:

     * Reduce overfitting to one story.
     * Triangulate truth.
     * Stress-test conclusions.

3. **Model ensembles in practice**

   * Climate science: multi-model ensembles to represent structural uncertainty. ([ScienceDirect][7])
   * Integrated assessment models for climate policy: multiple models, multiple futures. ([NBER][8])
   * Lesson: **diversity of models** is a feature, not a bug.

4. **Choosing a model family**

   * Based on:

     * Question type (explain, predict, explore, design).
     * Available data.
     * Level of detail needed.
     * Complexity of system (complicated vs. complex).

**Core readings**

* Scott E. Page, *The Model Thinker*, chapters surveying different model classes (e.g., linear models, networks, diffusion, Markov models, learning models). ([Amazon][2])
* Eric Winsberg, “Computer Simulations in Science,” *Stanford Encyclopedia of Philosophy* (for a conceptual overview of computational/simulation models). ([Stanford Encyclopedia of Philosophy][9])

---

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
   * Emphasize *logic*: if stock increases when inflow > outflow, how do we express that?

4. **Toy models**

   * Use very simple, deliberately unrealistic models to:

     * Clarify mechanisms,
     * Separate structural effects from parameter details.
   * Examples:

     * Simple SIR epidemic model,
     * Schelling segregation model,
     * Logistic growth with carrying capacity.

**Core readings**

* Hiroki Sayama, *Introduction to the Modeling and Analysis of Complex Systems* (conceptual parts of early chapters showing how to build simple dynamical & network models). ([Real World Data Science][10])
* Stephen Downes, *Models and Modeling in the Sciences* (or similar introductory text) for conceptual treatment of models as representations across disciplines. ([PhilPapers][11])

---

## Unit 5 – Data, Calibration, and Validation (Conceptual)

**Guiding questions**

* How do models connect to data?
* What do calibration, fitting, and validation mean conceptually?
* Why should models be treated as arguments rather than oracles?

**Sub-units**

1. **Models of data vs. models of systems**

   * Models of data: statistical models that summarize patterns (regression, time-series).
   * Models of systems: mechanistic models with explicit structure.
   * Both rely on **data reduction and curve fitting**, but for different purposes. ([Stanford Encyclopedia of Philosophy][12])

2. **Calibration / fitting**

   * Adjust model parameters so that outputs align with observed data.
   * Distinguish:

     * **Parameter choice by theory** vs. **parameter estimation from data**.
   * Overfitting vs. underfitting, conceptually:

     * Too many knobs → model fits noise.
     * Too few knobs → model cannot capture key patterns.

3. **Validation and confirmation (conceptual only)**

   * There is no final “proof” that a model is true (Oreskes et al.). ([Science][5])
   * Instead:

     * Compare model outputs to new data not used in calibration.
     * Test predictive skill across contexts.
     * Ask: “Where does it work? Where does it fail?”

4. **Models as arguments, not oracles**

   * Treat running a model like making a **structured argument**:

     * Premises = assumptions & inputs,
     * Reasoning = model structure,
     * Conclusion = outputs.
   * Critical thinking = interrogating all three.

**Core readings**

* Naomi Oreskes et al. (1994), “Verification, Validation, and Confirmation of Numerical Models in the Earth Sciences,” *Science*. ([Science][5])
* Roman Frigg, “Models of Data” section in *Models in Science* (SEP). ([Stanford Encyclopedia of Philosophy][3])

---

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
   * Global sensitivity analysis as a field (Saltelli et al.). ([andreasaltelli.eu][13])

3. **Robustness and model-based decision-making**

   * Instead of one “optimal” plan:

     * Seek strategies that perform **acceptably well** across many plausible futures.
   * Connect to earlier **decision analysis** and **complex systems**:

     * Stress testing and scenario planning.

4. **Multi-model and multi-scenario ensembles**

   * Use ensembles to:

     * Capture both parameter and model-form uncertainty.
     * Quantify ranges rather than point estimates (e.g., climate projections, IAMs). ([ScienceDirect][7])

**Core readings**

* Andrea Saltelli et al., *Global Sensitivity Analysis: The Primer* (introductory chapter, concept-focused). ([andreasaltelli.eu][13])
* Selected sections from *Escape from Model Land* on uncertainty and model dependence. ([LSE Blogs][4])

---

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
   * Implement simulation (NetLogo, Python libraries – mentioned, not taught).
   * Run experiments across parameter ranges.
   * Analyze emergent patterns, compare to data.

4. **Examples and case studies**

   * Schelling segregation model.
   * Opinion dynamics or contagion on networks.
   * A simple urban health or social behavior ABM. ([PMC][14])

**Core readings**

* Paul Smaldino, *Modeling Social Behavior: Mathematical and Agent-Based Models of Social Dynamics and Cultural Evolution* (intro + early chapters on ABM and social dynamics). ([JASSS][1])
* Auchincloss & Diez Roux, “A New Tool for Epidemiology: Agent-Based Models,” or similar introductory guide to ABM for public health / social science. ([PMC][14])
* Introductory ABM tutorial from Winter Simulation Conference (e.g., Macal & North). ([informs-sim.org][15])

---

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

     * No single “best” solution; Pareto front / compromise solutions.

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

**Core readings**

* Michael W. Carter & Camille C. Price, *Operations Research: A Practical Introduction* (non-technical chapters on problem formulation and modeling process).
* Brian Christian & Tom Griffiths, *Algorithms to Live By* (chapters on optimal stopping, explore–exploit, scheduling, etc., as everyday models).
* Matteo Fischetti, *Introduction to Mathematical Optimization* (selected sections on linear/integer programming formulation). ([JASSS][16])

---

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
     * Consider distributional impacts (who gains/loses).

**Core readings**

* Erica Thompson, *Escape from Model Land*, chapters on models and power, subjectivity, and value judgments. ([LSE Blogs][4])
* Mary S. Morgan, *The World in the Model: How Economists Work and Think* (selected chapters on models as tools in economics).

---

## Unit 10 – Integrating the Model Lens

**Guiding questions**

* What practical habits should learners use when they encounter or build a model?
* How does model thinking connect back to analytical and systems thinking?
* How can a capstone project bring the whole unit together?

**Sub-units**

1. **Model Thinking checklist**

   When you meet a model (or build one), ask:

   * **Purpose & question**

     * What is this model for? What questions is it built to answer?
   * **Representation**

     * What is being modeled? What is left out?
     * What kind of model is it (statistical, mechanistic, ABM, optimization, etc.)?
   * **Assumptions & structure**

     * What are the key assumptions about agents, environment, and feedback?
   * **Evidence & calibration**

     * How was it checked against data? What data were *not* used?
   * **Uncertainty & sensitivity**

     * How sensitive are results to parameter and structural choices?
   * **Use & ethics**

     * Who uses this model, for what decisions, with what consequences?

2. **Capstone project**

   Learners pick a real-world issue (personal, organizational, societal). Building on their **systems capstone**, they now:

   1. Restate the problem and system view (from previous unit).
   2. Choose a suitable **model family** (e.g., simple dynamical model, ABM sketch, optimization model, or statistical conceptual model).
   3. Explicitly write:

      * Purpose of the model,
      * Key variables and parameters,
      * Assumptions (in bullet form).
   4. Outline (conceptually) how they would:

      * Calibrate it with data,
      * Explore uncertainty (scenarios, parameter sweeps),
      * Use model outputs to inform a decision or policy.
   5. Reflect on:

      * Ethical issues,
      * Limits of the model,
      * How multiple models might give complementary insights.

3. **Connecting back to the whole course**

   * **Analytical Thinking**:

     * Gave you tools to frame problems, reason with evidence, and evaluate decisions.
   * **Systems Thinking**:

     * Gave you a lens for structure, feedback, and emergence.
   * **Model Thinking**:

     * Gave you tools to *build explicit representations* that you can test, combine, and critique.
   * Big meta-message:

     > “All models are wrong, some are useful, and **your job is to decide when and how** they are useful.”

**Core readings**

* Revisit key sections of:

  * Scott Page, *The Model Thinker* (multi-model thinking & application chapters). ([Amazon][2])
  * Erica Thompson, *Escape from Model Land* (summative chapters on working responsibly with models). ([LSE Blogs][4])
* Selected SEP entries (*Models in Science*, *Computer Simulations in Science*) for learners who want deeper philosophical context. ([Stanford Encyclopedia of Philosophy][3])

---

[1]: https://www.jasss.org/11/4/12.html "Why Model?"
[2]: https://www.amazon.com/Model-Thinker-What-Need-Know/dp/0465094627 "The Model Thinker: What You Need to Know to Make Data ..."
[3]: https://plato.stanford.edu/entries/models-science/ "Models in Science - Stanford Encyclopedia of Philosophy"
[4]: https://blogs.lse.ac.uk/lsereviewofbooks/2023/11/30/book-review-escape-from-model-land-how-mathematical-models-can-lead-us-astray-and-what-we-can-do-about-it-erica-thompson/ "Escape from Model Land: How Mathematical Models Can ..."
[5]: https://www.science.org/doi/10.1126/science.263.5147.641 "Verification, Validation, and Confirmation of Numerical ..."
[6]: https://mande.co.uk/2019/media-3/books/the-model-thinker-what-you-need-to-know-to-make-data-work-for-you/ "THE MODEL THINKER What You Need to Know to Make ..."
[7]: https://www.sciencedirect.com/science/article/pii/S2212094724000495 "A novel approach to a multi-model ensemble for climate ..."
[8]: https://www.nber.org/system/files/working_papers/w21637/w21637.pdf "Modeling Uncertainty in Climate Change"
[9]: https://plato.stanford.edu/entries/simulations-science/ "Computer Simulations in Science"
[10]: https://realworlddatascience.net/foundation-frontiers/interviews/posts/2023/01/25/erica-thompson.html "How to 'Escape from Model Land': an interview with Erica ..."
[11]: https://philpapers.org/rec/FRIMIS "Roman Frigg & Stephan Hartmann, Models in Science"
[12]: https://plato.stanford.edu/archives/sum2018/entries/models-science/ "Models in Science - Stanford Encyclopedia of Philosophy"
[13]: https://www.andreasaltelli.eu/file/repository/A_Saltelli_Marco_Ratto_Terry_Andres_Francesca_Campolongo_Jessica_Cariboni_Debora_Gatelli_Michaela_Saisana_Stefano_Tarantola_Global_Sensitivity_Analysis_The_Primer_Wiley_Interscience_2008_.pdf "Global Sensitivity Analysis. The Primer"
[14]: https://pmc.ncbi.nlm.nih.gov/articles/PMC5391997/ "Brief introductory guide to agent-based modeling and an ..."
[15]: https://informs-sim.org/wsc14papers/includes/files/004.pdf "INTRODUCTORY TUTORIAL: AGENT-BASED MODELING ..."
[16]: https://www.jasss.org/27/2/4.html "Reliable and Efficient Agent-Based Modeling and Simulation"
