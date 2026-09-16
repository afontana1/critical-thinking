# Course Overview: Analytical Thinking – From Problem Framing to Judgment Under Uncertainty

## Table of Contents

<!-- UNIT_TOC_START -->
- [Unit 1 — Foundations of Analytical Thinking](#unit-1)
- [Unit 2 — Problem Decomposition and Representation](#unit-2)
- [Unit 3 — Computational and Algorithmic Thinking](#unit-3)
- [Unit 4 — Decision Analysis](#unit-4)
- [Unit 5 — Process and Systems Orientation](#unit-5)
- [Unit 6 — Meta-Analytical Habits](#unit-6)
- [Unit 7 — Program Evaluation and Policy Analysis](#unit-7)
- [Unit 8 — Intelligence Analysis and Structured Analytic Techniques](#unit-8)
- [Unit 9 — Data Analysis, Visualization, and Evidentiary Displays](#unit-9)
- [Unit 10 — Risk Analysis and Uncertainty Communication](#unit-10)
- [Unit 11 — Structured Problem Solving and Root Cause Analysis](#unit-11)
- [Unit 12 — Forecasting, Scenario Analysis, and Red Teaming](#unit-12)
<!-- UNIT_TOC_END -->


**Big question:**
How do we analyze messy problems well—by framing questions clearly, structuring complexity, evaluating evidence, comparing alternatives, and making reasoned judgments under uncertainty?

**By the end, students should be able to:**

* Explain what **analytical thinking** is and distinguish it from critical, creative, and purely intuitive thinking.
* Frame problems clearly by defining scope, clarifying terms, identifying assumptions, and asking operational questions.
* Break complex issues into parts, relationships, processes, and systems using appropriate forms of representation.
* Use **computational and algorithmic habits of thought** to structure procedures, constraints, and tradeoffs without requiring advanced mathematics.
* Analyze choices under uncertainty using basic ideas from **decision analysis**, including tradeoffs, thresholds, expected value, and sensitivity to assumptions.
* Recognize how **systems and processes** shape outcomes through interactions, feedback, boundaries, and unintended consequences.
* Develop **meta-analytical habits** such as self-questioning, robustness checks, alternative analysis, and reflective critique of one’s own methods.
* Evaluate programs, interventions, and policies using structured reasoning about goals, mechanisms, outcomes, evidence, and constraints.
* Apply key methods from **intelligence analysis**, including competing hypotheses, indicators, confidence judgments, and structured challenge.
* Use basic **data analysis and visualization** to inspect patterns, compare trends, identify anomalies, and communicate evidence responsibly.
* Reason about **risk** in ways that distinguish hazard, likelihood, consequence, uncertainty, and decision thresholds.
* Use practical **problem-solving methods** such as root-cause analysis, bottleneck identification, and criteria-based option evaluation.
* Practice **forecasting and scenario analysis** by identifying drivers, alternative futures, signposts, and revisable judgments.
* Produce concise analytic products that distinguish **evidence, inference, interpretation, recommendation, and confidence**.
* Build habits that prepare students for later work in **policy analysis, systems thinking, model reasoning, intelligence studies, and decision-making**.

**Course through-line: one analytic workflow**

Frame the question → decompose and represent the problem → identify evidence and assumptions → compare explanations or options → test sensitivity and alternatives → communicate a qualified conclusion. Earlier courses supplied the foundations in argumentation, evidence, data literacy, causality, and heuristics; this course integrates those skills into an **analytic product**. Specialist methods in policy analysis, systems thinking, model reasoning, risk analysis, and intelligence studies are introduced only as needed for that product.

**Running case (illustrative, not a real dataset): persistent service delays.** Students act as analysts asked why a service is regularly late and what might improve it. Each unit revisits the *same question* through a different tool; no diagnosis is presumed in advance. In the absence of real data, use explicitly hypothetical records and do not present their conclusions as empirical findings.

---

<a id="unit-1"></a>
## Unit 1 — Foundations of Analytical Thinking

**Guiding questions**

* What is analytical thinking, and how does it differ from other forms of thought?
* What makes a problem well framed rather than vague or ill-posed?
* How do analysts separate evidence, inference, and interpretation?

**Sub-units**

1. **What analytical thinking is**

   * Define analytical thinking as disciplined reasoning aimed at clarifying questions, structuring problems, and drawing justified conclusions.
   * Distinguish it from critical thinking, creative thinking, and intuitive judgment.
   * Emphasize that analytical thinking is not the rejection of intuition, but the disciplined examination of it.

2. **Problem framing and scoping**

   * Show how analysts define the boundaries of a problem.
   * Clarify what is in scope, what is out of scope, and what practical question is being asked.
   * Stress that poor framing often produces poor analysis even when later reasoning is careful.

3. **Clarifying terms, categories, and assumptions**

   * Many disputes are partly conceptual: people use the same words differently.
   * Teach students to define key terms, separate categories, and identify hidden assumptions.
   * Connect conceptual clarity to stronger downstream analysis.

4. **Asking precise and operational questions**

   * Move from vague concerns to tractable questions.
   * Distinguish broad topic areas from specific analytical questions.
   * Introduce the idea that a question becomes analytically useful when it guides evidence-gathering and comparison.

5. **Evidence, inference, and interpretation**

   * Distinguish raw information from interpreted evidence.
   * Explain the difference between what the evidence shows, what is inferred from it, and how it is interpreted in a broader context.
   * This distinction becomes a recurring habit across the whole course.

6. **The analytic workflow and a first-pass brief**

   * Frame the running case as a question that could guide evidence collection: what is delayed, compared with which service standard, for whom, and over what period?
   * Record scope, provisional assumptions, information gaps, and at least two possible explanations; avoid treating an early hypothesis as an established cause.
   * Start a one-page analytic brief that will be revised through the remaining units, keeping observation, inference, interpretation, recommendation, and confidence separate.

**Assigned readings — local Course 7 repository (selected sections, not entire books)**

* Richard Paul & Linda Elder, *The Thinker’s Guide to Analytic Thinking* (the 83-page repository guide; choose foundational selections).
* George Pólya, *How to Solve It: A New Aspect of Mathematical Method* (selected problem-framing and checking strategies).

**Cross-course or external references (not listed in the Course 7 inventory)**

* Herbert Simon, “The Structure of Ill-Structured Problems” (external; optional context).
* Daniel Kahneman, *Thinking, Fast and Slow*, and Edward de Bono, *Six Thinking Hats* (external/previous-course background; not required core here).

---

<a id="unit-2"></a>
## Unit 2 — Problem Decomposition and Representation

**Guiding questions**

* How can a messy problem be broken into manageable parts?
* What kinds of representations make hidden relationships easier to see?
* How do diagrams and structures shape the quality of analysis?

**Sub-units**

1. **Top-down and bottom-up decomposition**

   * Introduce two broad decomposition strategies:

     * top-down from the whole to the parts
     * bottom-up from observed pieces to larger patterns
   * Show when each is useful.
   * Emphasize that decomposition is never neutral; it reflects an analytic choice.

2. **Concept mapping and relationship mapping**

   * Use maps to represent entities, categories, and relationships.
   * Teach students to distinguish hierarchical, causal, and associative links.
   * Show how maps can reveal ambiguity and missing connections.

3. **Process mapping and workflow visualization**

   * Represent problems as sequences of actions, stages, or decision points.
   * Use flowcharts and process diagrams to clarify where breakdowns or delays occur.
   * Connect process representation to operational analysis.

4. **Boundary identification and variable classification**

   * Teach students to identify what belongs inside the analysis and what belongs outside it.
   * Distinguish actors, variables, constraints, inputs, outputs, and background conditions.
   * Show how bad boundary choices distort conclusions.

5. **Translating qualitative descriptions into structured forms**

   * Convert narratives into tables, maps, matrices, timelines, or diagrams.
   * Emphasize that representation is a form of analysis, not just presentation.
   * This unit prepares students for later work in systems, data, and decision analysis.

6. **Compare representations of the same problem**

   * For the service-delay case, make a problem hierarchy, workflow map, evidence table, and tentative causal sketch.
   * Mark causal arrows as **hypotheses**, not conclusions, and distinguish them from temporal or merely associative links.
   * For each representation, state one useful insight, one omission, and one question it cannot answer. Select the representation that fits the immediate analytic task.

**Assigned readings — local Course 7 repository (selected sections, not entire books)**

* Richard Paul, Linda Elder & Robert Niewoehner, *The Thinker’s Guide to Engineering Reasoning* (repository guide; verify title-page contributor details before formal citation).
* George Pólya, *How to Solve It* (repository book; selected material on representing a problem).
* David A. Schum, *Intelligence Analysis as Discovery of Evidence, Hypotheses, and Arguments: Connecting the Dots* (repository book; selected passages on evidence and hypothesis structure).

**Cross-course or external references (not listed in the Course 7 inventory)**

* Joseph Novak, *Learning How to Learn*; Dan Roam, *The Back of the Napkin*; introductory BPMN/flowchart guides (outside this repository; optional representation references).

---

<a id="unit-3"></a>
## Unit 3 — Computational and Algorithmic Thinking

**Guiding questions**

* What does it mean to think algorithmically without formal programming?
* How do sequences, loops, conditions, and constraints help structure reasoning?
* When should we optimize, and when is satisficing enough?

**Sub-units**

1. **Problems as procedures**

   * Introduce the idea that some problems can be analyzed as ordered procedures.
   * Break tasks into steps, branches, and recurring operations.
   * Show how procedural clarity can improve both understanding and execution.

2. **Sequences, conditions, and loops**

   * Teach core algorithmic patterns in plain language.
   * Show how conditions structure choices and how loops model repeated checking or adjustment.
   * Use everyday examples rather than technical programming notation.

3. **Algorithmic decomposition**

   * Move from general problem decomposition to more rule-based procedural decomposition.
   * Ask what a person or system would have to do first, next, and under what conditions.
   * This helps students structure operational and administrative problems.

4. **Optimization, satisficing, and constraints**

   * Explain the difference between finding the best possible answer and finding a good-enough answer under real constraints.
   * Introduce tradeoffs involving time, cost, accuracy, and complexity.
   * Link back to Simon’s bounded rationality.

5. **Computational models as conceptual tools**

   * Show that computational thinking is not only for coding.
   * Use it as a framework for understanding procedures, decision rules, and system behavior.
   * This creates a bridge between human problem solving and formal modeling.

6. **A plain-language procedure with failure checks**

   * Write pseudocode for the service-delay investigation: ordered steps, one if/then branch, a stopping rule, and an error or missing-data check. No programming is required.
   * Test the procedure on a contrary example. Consistent execution makes the process reproducible but does **not** make its assumptions, data, or conclusions valid.

**Assigned readings — local Course 7 repository (selected sections, not entire books)**

* George Pólya, *How to Solve It* (repository book; heuristics for executing and checking a plan).
* Daniel J. Velleman, *How to Prove It: A Structured Approach* (repository book; **optional comparison** on explicit logical structure, not a computational-thinking substitute).

**Cross-course or external references (not listed in the Course 7 inventory)**

* Brian Christian & Tom Griffiths, *Algorithms to Live By*; Jeannette Wing, “Computational Thinking”; Melanie Mitchell, *Complexity*; Charles Petzold, *Code* (listed in the original outline but not held in this course inventory).

**Short resource to obtain or prepare**

* A short introductory computational-thinking or pseudocode handout with a worked branching/stopping example; use Wing’s essay if accessible.

---

<a id="unit-4"></a>
## Unit 4 — Decision Analysis

**Guiding questions**

* How should we compare options under uncertainty?
* What role do tradeoffs, thresholds, and assumptions play in decisions?
* How can decision tools clarify choices without pretending to eliminate uncertainty?

**Sub-units**

1. **Decisions under uncertainty**

   * Introduce decision analysis as structured reasoning about uncertain outcomes.
   * Distinguish choosing under certainty from choosing under ambiguity and risk.
   * Show why explicit tradeoff reasoning often improves judgment.

2. **Probability intuitions and bias**

   * Review how intuitive judgments about probability can mislead.
   * Connect to later material in risk and forecasting.
   * Emphasize that decision quality depends partly on how uncertainty is represented.

3. **Decision trees and option structure**

   * Use decision trees to clarify options, branches, outcomes, and contingencies.
   * Teach them as visual reasoning tools rather than formal mathematical devices.
   * Show how decision trees force analysts to state what depends on what.

4. **Expected value, utility, and action thresholds**

   * Introduce these as conceptual tools for comparing options.
   * Avoid mathematical heaviness while preserving the core idea of weighing outcomes by likelihood and importance.
   * Show that reasonable people may differ because they value outcomes differently.

5. **Sensitivity to assumptions**

   * Decisions often hinge on assumptions about consequences, likelihoods, or constraints.
   * Teach students to vary assumptions and ask whether the recommendation changes.
   * This is one of the most important habits in practical analysis.

6. **A compact decision memo**

   * For the running case, identify feasible actions, objectives, constraints, uncertain consequences, and whose values enter the comparison.
   * Separate empirical claims about likely outcomes from value judgments about their importance; evidence alone does not select the preferred trade-off.
   * Vary one pivotal assumption and note whether the comparative assessment changes; reserve advanced utility elicitation for a later decision-analysis course.

**Assigned readings — local Course 7 repository (selected sections, not entire books)**

* Jordan Ellenberg, *How Not to Be Wrong: The Power of Mathematical Thinking* (repository book; optional short selections on quantitative comparisons).

**Cross-course or external references (not listed in the Course 7 inventory)**

* Martin Peterson, *An Introduction to Decision Theory*, or Robert T. Clemen, *Making Hard Decisions* (held in the Course 6 inventory; **cross-course selections**, not Course 7 files).
* Howard Raiffa, *Decision Analysis*; Annie Duke, *Thinking in Bets*; Kahneman, Slovic & Tversky, *Judgment under Uncertainty*; Nassim Nicholas Taleb, *The Black Swan* (external to Course 7; optional).

---

<a id="unit-5"></a>
## Unit 5 — Process and Systems Orientation

**Guiding questions**

* How do processes and systems differ from simple linear chains?
* What happens when parts interact through feedback, delay, and interdependence?
* How do boundaries and simplifications shape what an analysis can see?

**Sub-units**

1. **Processes as analyzable structures**

   * Introduce process thinking as the study of stages, flows, dependencies, and handoffs.
   * Show how many failures arise not from bad parts alone but from bad coordination among parts.
   * Connect process mapping to diagnosis and redesign.

2. **Systems as interacting wholes**

   * Define systems in terms of interacting components within boundaries.
   * Emphasize interdependence, not mere aggregation.
   * This broadens analysis from isolated parts to patterned interactions.

3. **Feedback loops, stocks, and flows**

   * Introduce core systems concepts in nontechnical language.
   * Explain how accumulation, delay, and feedback create behavior that linear reasoning misses.
   * This prepares students for later work in model and systems thinking.

4. **Leverage points and unintended consequences**

   * Not every intervention matters equally.
   * Show how small changes at the right place can matter more than large changes at the wrong place.
   * Also show how interventions can create second-order effects.

5. **Boundary-setting, scope, and simplification**

   * Every system representation excludes something.
   * Teach students to ask what the model or system map leaves out.
   * This unit reinforces the importance of humility in analytic modeling.

6. **Map a handoff and test the boundary**

   * Map a service request through successive handoffs; identify a candidate bottleneck, a dependency, and a possible unintended consequence of a proposed change.
   * Redraw the boundary to include an overlooked actor or stage. Explain what changes, while treating feedback, stocks, and flows as an introduction rather than a full systems model.

**Assigned readings — local Course 7 repository (selected sections, not entire books)**

* Richard Paul, Linda Elder & Robert Niewoehner, *The Thinker’s Guide to Engineering Reasoning* (repository guide; selected reasoning and boundary-setting material).

**Cross-course or external references (not listed in the Course 7 inventory)**

* Donella Meadows, *Thinking in Systems*; Peter Checkland, *Soft Systems Methodology in Action*; Charles Perrow, *Normal Accidents* (later systems-course references; not held in Course 7).
* A basic causal-loop or system-mapping guide (external; optional, not necessary for the handoff map).

---

<a id="unit-6"></a>
## Unit 6 — Meta-Analytical Habits

**Guiding questions**

* How do we notice weaknesses in our own analysis?
* What habits make analysis more robust, self-correcting, and open-minded?
* How can alternative analysis improve judgment?

**Sub-units**

1. **Reflective diagnostics**

   * Teach students to step back from their own reasoning.
   * Ask what assumptions they are making and what evidence would disconfirm their view.
   * Build the habit of analyzing one’s own analysis.

2. **Intellectual humility and open-mindedness**

   * Show why strong analysis requires more than technical skill.
   * Introduce humility not as indecision, but as disciplined awareness of fallibility.
   * Connect this to better revision and error-correction.

3. **Assumption audits and robustness checks**

   * Identify central assumptions and test how much conclusions depend on them.
   * Ask what happens if a key assumption is false or weakened.
   * This habit is useful across all later units.

4. **Counterfactual and alternative analysis**

   * Ask what else could be true.
   * Compare rival explanations, not just favored ones.
   * Show how counterfactuals and alternatives improve both diagnosis and decision.

5. **Framing effects and methodological limitations**

   * Analysts can be trapped by the way a problem is initially posed.
   * Teach students to ask how a different frame or method might alter what they see.
   * This creates a bridge to intelligence analysis and decision hygiene.

6. **Revise an analysis after structured challenge**

   * Name the assumption on which the draft service-delay explanation most depends. Construct one serious rival explanation and specify an observation that would favor it.
   * Reframe the question once, check whether the conclusion survives, and record a justified revision—or explain why no revision is warranted.
   * Apply, rather than repeat, the earlier course’s cognitive-bias and debiasing material.

**Assigned readings — local Course 7 repository (selected sections, not entire books)**

* Katherine Hibbs Pherson & Randolph H. Pherson, *Critical Thinking for Intelligence Analysis* (repository book; selected structured-questioning material).
* David A. Schum, *Intelligence Analysis as Discovery of Evidence, Hypotheses, and Arguments* (repository book; selected treatment of competing interpretations).

**Cross-course or external references (not listed in the Course 7 inventory)**

* Gary Klein, *Sources of Power*; Richard Rumelt, *Good Strategy/Bad Strategy*; Nassim Taleb, *Antifragile*; RAND crisis-thinking guide (originally listed but not in the Course 7 inventory; optional).

---

<a id="unit-7"></a>
## Unit 7 — Program Evaluation and Policy Analysis

**Guiding questions**

* How do we evaluate whether a program or policy works?
* What counts as a good evaluation question?
* How do analysts move from evidence to recommendations under real institutional constraints?

**Sub-units**

1. **Framing evaluation questions**

   * Introduce evaluation as structured reasoning about whether an intervention achieves its aims.
   * Ask what works, for whom, under what conditions, and by what mechanism.
   * Emphasize that the question structure shapes the evaluation design.

2. **Logic models and theories of change**

   * Teach students to represent interventions as chains linking inputs, activities, outputs, outcomes, and impacts.
   * Show how theory-of-change models make assumptions explicit.
   * This provides a scaffold for evaluating success or failure.

3. **Outputs, outcomes, and impacts**

   * Distinguish what was produced from what changed and from what mattered.
   * This is essential for avoiding shallow program assessment.
   * It also helps students separate activity from effect.

4. **Evaluation types and validity**

   * Introduce formative, summative, process, and impact evaluation.
   * Explain validity threats conceptually, especially where causal claims are involved.
   * Connect to the logic of causal inference without making the unit overly technical.

5. **Policy analysis and recommendation**

   * Move from description to option comparison.
   * Teach students to evaluate policies using effectiveness, efficiency, equity, feasibility, and institutional fit.
   * Emphasize that good analysis must survive the real world of politics and implementation.

6. **From evidence to use**

   * Ask how evaluation results actually shape decisions.
   * Recognize that recommendations are filtered through institutions, incentives, and competing values.
   * This unit bridges analysis and practice.

7. **Interpret an evaluation for a decision**

   * Build a miniature logic model for a proposed service improvement: inputs → activities → outputs → outcomes → intended impact.
   * Ask whether an observed change is **attributable** to the intervention, or whether timing, selection, or another cause could explain it.
   * Separate the empirical finding from the criteria and stakeholder values used to compare policy or program options; defer full evaluation design and policy-analysis methods to later courses.

**Assigned readings — local Course 7 repository (selected sections, not entire books)**

* Richard Paul, Linda Elder & Robert Niewoehner, *The Thinker’s Guide to Engineering Reasoning* (repository guide; brief selection on defining goals and evaluating outcomes).

**Cross-course or external references (not listed in the Course 7 inventory)**

* CDC, *Framework for Program Evaluation in Public Health* (external introductory guide; suggested **single** methodological anchor).
* Carol Weiss; Rossi, Lipsey & Freeman; Michael Quinn Patton; Eugene Bardach; Deborah Stone; Herbert Simon; Howard Raiffa; Pearl & Mackenzie (original extended references, not local Course 7 readings; use selectively in later courses).

**Short resource to obtain or prepare**

* Obtain or link one concise, accessible evaluation-guide excerpt covering logic models, outputs versus outcomes, and attribution; do not assign the original nine-book list as core.

---

<a id="unit-8"></a>
## Unit 8 — Intelligence Analysis and Structured Analytic Techniques

**Guiding questions**

* How do analysts reason when information is incomplete, contested, or deceptive?
* What helps prevent premature closure around a favored explanation?
* How should analytic confidence and uncertainty be communicated?

**Sub-units**

1. **Inference under ambiguity**

   * Intelligence analysis provides a model of reasoning under incomplete and adversarial conditions.
   * Students learn to distinguish uncertainty caused by lack of information from uncertainty caused by deception or ambiguity.
   * This makes intelligence analysis a powerful case study in analytical discipline.

2. **Signals, noise, and missing information**

   * Not all information is equally informative.
   * Teach students to ask what is signal, what is noise, and what crucial information may be absent.
   * This helps resist overconfident interpretation.

3. **Competing hypotheses**

   * Introduce the idea that strong analysis compares rival explanations explicitly.
   * Show the danger of locking onto a preferred explanation too early.
   * This connects to structured intelligence-analysis tradecraft; build first from the Pherson and Schum books held locally.

4. **Structured analytic techniques**

   * Introduce ACH, indicators, signposts, key assumptions checks, and devil’s advocacy.
   * Teach these as ways of organizing judgment rather than bureaucratic rituals.
   * Emphasize that structure helps reduce predictable analytic failure.

5. **Confidence, caveats, and analytic writing**

   * Distinguish judgment from certainty.
   * Teach students to write concise assessments that include assumptions, uncertainty, and confidence levels.
   * This is a practical analytic communication skill.

6. **Competing-hypotheses case lab**

   * Compare at least two explanations for service delays using an evidence-by-hypothesis table; record each source, uncertainty, potential dependence, and the **diagnostic value** of each item.
   * Note missing information and any item that would materially change the assessment. Do not equate evidence quantity with evidential strength.
   * Treat analysis of competing hypotheses (ACH) as an aid to exposing assumptions and contradictions, **not** as a mechanical proof or automatic scoring rule.
   * Produce a short paragraph that separates the lead judgment, alternatives, confidence, and signposts for revision.

**Assigned readings — local Course 7 repository (selected sections, not entire books)**

* Katherine Hibbs Pherson & Randolph H. Pherson, *Critical Thinking for Intelligence Analysis* (exact title of the local book; **do not silently equate** it with *Critical Thinking for Strategic Intelligence*).
* David A. Schum, *Intelligence Analysis as Discovery of Evidence, Hypotheses, and Arguments: Connecting the Dots* (repository book; selected evidence/hypothesis mapping).

**Cross-course or external references (not listed in the Course 7 inventory)**

* Richards J. Heuer Jr., *Psychology of Intelligence Analysis*; Heuer & Pherson, *Structured Analytic Techniques for Intelligence Analysis*; CIA tradecraft primers; Sherman Kent (not in this course inventory; optional advanced references).

---

<a id="unit-9"></a>
## Unit 9 — Data Analysis, Visualization, and Evidentiary Displays

**Guiding questions**

* What questions should analysts ask of a dataset before drawing conclusions?
* How do summaries and graphics clarify patterns—or mislead?
* How can data displays support better evidence-based reasoning?

**Sub-units**

1. **What analysts ask of data**

   * Introduce practical questions:

     * What is being counted?
     * Compared to what?
     * Over what period?
     * Using what categories?
   * This teaches students to approach data critically before interpreting it.

2. **Descriptive analysis without heavy statistics**

   * Focus on trends, differences, rates, outliers, anomalies, and patterns.
   * Show how much can be learned from careful descriptive reasoning.
   * Emphasize disciplined comparison over formal technique.

3. **Visual reasoning with common chart forms**

   * Teach bar charts, line charts, scatterplots, tables, and heat maps as analytic tools.
   * Explain what each is good for and where it can mislead.
   * Connect display choice to the question being asked.

4. **Misleading graphics and false visual certainty**

   * Show how scale manipulation, omitted baselines, visual clutter, and selective framing distort interpretation.
   * Train students to critique public charts and dashboards.
   * This creates a bridge to evidence literacy.

5. **Data provenance, missingness, and context**

   * Data always come from somewhere.
   * Teach students to ask about source, quality, omissions, and coding choices.
   * This reinforces the distinction between data and warranted inference.

6. **A one-page analytic display**

   * Prepare an evidence table or annotated chart for the running case, stating the comparison, unit of analysis, time window, source, missingness, and one material limitation.
   * Label what was observed separately from explanatory hypotheses; choose a display that advances the question rather than decorating the brief.
   * Reuse the graphic-critique skills from Data Literacy instead of reteaching every chart type.

**Assigned readings — local Course 7 repository (selected sections, not entire books)**

* Jordan Ellenberg, *How Not to Be Wrong: The Power of Mathematical Thinking* (repository book; selected quantitative-reasoning examples).
* David A. Schum, *Intelligence Analysis as Discovery of Evidence, Hypotheses, and Arguments* (repository book; selected evidentiary-display material).

**Cross-course or external references (not listed in the Course 7 inventory)**

* Edward Tufte, *The Visual Display of Quantitative Information* / *Visual Explanations*, and Darrell Huff, *How to Lie with Statistics* (held in the Course 4 Data Literacy inventory; cross-course selections).
* Cole Nussbaumer Knaflic, *Storytelling with Data*; Alberto Cairo, *How Charts Lie* (not in Course 7 inventory; optional).

---

<a id="unit-10"></a>
## Unit 10 — Risk Analysis and Uncertainty Communication

**Guiding questions**

* What is risk, and how is it different from uncertainty or ignorance?
* How should low-probability, high-consequence possibilities be handled?
* How can analysts communicate risk clearly without exaggeration or false certainty?

**Sub-units**

1. **Core concepts in risk analysis**

   * Introduce hazard, likelihood, consequence, exposure, and vulnerability.
   * Show that risk is not just probability but a structured combination of factors.
   * Emphasize practical rather than technical understanding.

2. **Uncertainty, ambiguity, and ignorance**

   * Distinguish known uncertainty from deeper ambiguity and unknown unknowns.
   * Show why analysts must not collapse these into one category.
   * This prepares students for difficult public and organizational decisions.

3. **Qualitative and semi-quantitative risk tools**

   * Introduce matrices, scenario comparisons, and threshold-based judgments.
   * Explain both their usefulness and their limitations.
   * This encourages disciplined use without false confidence.

4. **High-impact and low-probability events**

   * Explore why rare events can be especially difficult to reason about.
   * Discuss precaution, resilience, and the problem of surprise.
   * Connect to Taleb and the broader literature on uncertainty.

5. **Communicating risk to others**

   * Different audiences need different kinds of clarity.
   * Teach students to distinguish risk communication from persuasion or alarm.
   * This unit emphasizes honesty about uncertainty and stakes.

6. **Characterize risk without false precision**

   * Add a risk box to the running-case brief: possible harm/event, exposure or vulnerability, likelihood (if supportable), consequences, and what remains unknown.
   * Explain that a qualitative risk matrix organizes judgments but does not confer precise probabilities or make unlike categories automatically comparable.
   * Keep action thresholds distinct from the strength of the evidence; detailed risk quantification belongs in the later risk-analysis course.

**Assigned readings — local Course 7 repository (selected sections, not entire books)**

* Jordan Ellenberg, *How Not to Be Wrong* (repository book; optional selected cautionary quantitative examples).

**Cross-course or external references (not listed in the Course 7 inventory)**

* National Research Council, *Understanding Risk*; David Spiegelhalter, *The Art of Statistics*; Gerd Gigerenzer, *Calculated Risks*; Cass Sunstein, *Risk and Reason*; Nassim Taleb, *The Black Swan* (not in Course 7 inventory; optional risk-course references).

**Short resource to obtain or prepare**

* If this unit needs a stand-alone assigned text, use one short introductory risk-characterization/communication guide rather than several full books.

---

<a id="unit-11"></a>
## Unit 11 — Structured Problem Solving and Root Cause Analysis

**Guiding questions**

* How do we distinguish symptoms from causes?
* What problem-solving methods help with diagnosis, options, and action?
* How do analysts move from explanation to recommendation?

**Sub-units**

1. **Defining the problem well**

   * Start with the question: what exactly is wrong, relative to what expected condition?
   * Show that vague complaints rarely produce useful diagnosis.
   * This unit returns to framing, now in a practical troubleshooting setting.

2. **Symptoms, causes, and causal chains**

   * Distinguish surface manifestations from underlying drivers.
   * Explain proximate causes versus systemic causes.
   * This helps students avoid stopping at the first plausible explanation.

3. **Root cause methods**

   * Introduce 5 Whys, fishbone diagrams, fault trees, and causal chains.
   * Use them as structured aids rather than mechanical solutions.
   * Emphasize that different tools reveal different aspects of a problem.

4. **Constraints and bottlenecks**

   * Many problems are shaped by the most limiting factor in the system.
   * Teach students to identify bottlenecks, dependencies, and high-friction points.
   * This creates a bridge to operational and process thinking.

5. **Option evaluation and recommendation**

   * After diagnosis comes choice.
   * Compare interventions using explicit criteria and tradeoffs.
   * End by moving from explanation to action.

6. **Root-cause hypotheses are not findings**

   * Use a 5 Whys chain or fishbone diagram to generate **at least two** rival explanations for the service delays; do not assume there is one unique root cause.
   * Identify the observation or test that would distinguish the rivals, and record any unresolved mechanism or missing information.
   * Compare interventions against explicit constraints, likely consequences, and what would be monitored after implementation.

**Assigned readings — local Course 7 repository (selected sections, not entire books)**

* George Pólya, *How to Solve It* (repository book; problem-solving, verification, and checking).
* Richard Paul, Linda Elder & Robert Niewoehner, *The Thinker’s Guide to Engineering Reasoning* (repository guide; selected troubleshooting context).

**Cross-course or external references (not listed in the Course 7 inventory)**

* Charles Kepner & Benjamin Tregoe, *The New Rational Manager*; Eliyahu Goldratt, *The Goal*; Russell Ackoff, *The Art of Problem Solving* (not in Course 7 inventory; optional advanced references).

**Short resource to obtain or prepare**

* A short practical 5 Whys/fishbone or fault-tree handout explicitly distinguishing a proposed causal chain from a verified explanation.

---

<a id="unit-12"></a>
## Unit 12 — Forecasting, Scenario Analysis, and Red Teaming

**Guiding questions**

* How should analysts think about the future without pretending to predict it exactly?
* What is the difference between forecasting and scenario analysis?
* How do red teaming and challenge analysis improve forward-looking judgment?

**Sub-units**

1. **Forecasting as disciplined judgment**

   * Introduce forecasting as structured estimation under uncertainty.
   * Show why forecasting is not prophecy but revisable judgment.
   * Emphasize explicit probabilities, revision, and accountability.

2. **Base rates, trends, and reference classes**

   * Teach students to begin with prior patterns rather than pure speculation.
   * Show how reference-class thinking improves estimates.
   * Connect to broader themes of calibrated judgment.

3. **Scenarios and alternative futures**

   * Distinguish predicting one future from exploring several plausible futures.
   * Use scenarios to think through drivers, branching paths, and contingencies.
   * This helps students think strategically rather than linearly.

4. **Indicators, signposts, and early warning**

   * Good analysts do not only make judgments; they specify what would update them.
   * Teach signposts and indicators as mechanisms for revising expectations.
   * This creates a more dynamic model of analysis.

5. **Red teaming and premortems**

   * Introduce organized challenge as a way of testing fragile assumptions.
   * Use premortems and alternative analysis to identify failure paths.
   * End with the lesson that better forecasting depends on better self-critique.

6. **Three distinct forward-looking outputs**

   * **Forecast:** a time-bounded, revisable judgment about an outcome, with uncertainty stated.
   * **Scenario:** an internally coherent possible development used to explore drivers and contingencies, not a disguised probability forecast.
   * **Red-team challenge:** an organized test of the assumptions, blind spots, and failure modes underlying the first two.
   * For the running case, specify two signposts and what evidence would cause the brief’s assessment to change; reuse rather than reteach Course 6’s calibration methods.

**Assigned readings — local Course 7 repository (selected sections, not entire books)**

* Katherine Hibbs Pherson & Randolph H. Pherson, *Critical Thinking for Intelligence Analysis* (repository book; selected structured challenge and indicators).
* David A. Schum, *Intelligence Analysis as Discovery of Evidence, Hypotheses, and Arguments* (repository book; selected updating of evidential assessments).

**Cross-course or external references (not listed in the Course 7 inventory)**

* Philip Tetlock & Dan Gardner, *Superforecasting*; Gary Klein, “Performing a Project Premortem” (identified in the Course 6 outline; cross-course if available).
* Kees van der Heijden, *Scenarios*; Heuer & Pherson, *Structured Analytic Techniques for Intelligence Analysis*; Heuer, *Psychology of Intelligence Analysis* (not in Course 7 inventory; optional).

---

## Possible capstone activities

* **Integrated Analytic Brief (recommended course through-line)**

  Students develop a **two-page brief** on the recurring service-delay case (using verified data where available and clearly labeled hypothetical data otherwise), or on a comparable chosen issue. The brief must:

  * frame the question, scope, comparator, and relevant stakeholders
  * distinguish observations, evidence, inferences, interpretations, recommendations, and confidence
  * compare at least two plausible explanations or options and identify their source evidence
  * identify a pivotal assumption and show one sensitivity or alternative-framing check
  * provide a qualified conclusion, implementation constraint, and signposts for revision
  * include a compact appendix with a problem map, evidence table, and one alternate explanation or decision comparison; avoid treating an illustrative case as an empirical finding

* **Competing Hypotheses Exercise**

  * Students analyze a disputed event or policy problem using:

    * alternative hypotheses
    * key evidence for and against each
    * confidence judgments
    * indicators that would change the conclusion

* **Data Display Critique**

  * Students select a public chart, dashboard, or infographic and:

    * identify what the display gets right or wrong
    * explain what contextual information is missing
    * redesign the display for better analysis

* **Risk Memo**

  * Students choose a technological, policy, or organizational risk and:

    * define the risk
    * identify likely consequences and uncertainties
    * compare response options
    * recommend an action threshold or monitoring strategy

* **Root Cause Analysis Lab**

  * Students diagnose a failure case using:

    * symptom/cause distinction
    * a causal chain or fishbone diagram
    * alternative explanations
    * a prioritized intervention plan

* **Scenario and Forecast Portfolio**

  * Students build a small scenario set around a live issue, identify signposts, and assign probabilistic judgments that they later revisit and revise.

---

## Teaching moves

* **Assumption audits** attached to every major analytic task.
* **Competing-explanations boxes** that require at least one serious alternative interpretation.
* **Analyst’s confidence labels** so students practice calibrated judgment rather than false certainty.
* **Evidence ladders** distinguishing raw information, interpreted evidence, inference, and recommendation.
* **Diagram-first reasoning** using concept maps, process maps, fault trees, and causal chains.
* **Forecast logs** to preserve uncertainty and enable later calibration.
* **Red-team rotations** where another student or group must challenge the leading view.
* **Decision memos** that require criteria, tradeoffs, and implementation considerations.
* **One running-case brief** revised through the units; each tool must add information or expose a limitation rather than become a stand-alone specialist module.

---

## Glossary

**Problem framing**; **Decomposition**; **Representation**; **Abstraction**; **Constraint**; **Assumption**; **Inference**; **Interpretation**; **Tradeoff**; **Expected value**; **Sensitivity analysis**; **Feedback loop**; **Boundary**; **Robustness check**; **Alternative hypothesis**; **Indicator**; **Signpost**; **Root cause**; **Scenario**; **Calibration**; **Confidence judgment**; **Data provenance**; **Outlier**; **Risk characterization**; **Decision threshold**.

---

## Reading access, scope, and extended reference list

The **nine entries in the Course 7 metadata are book records**, including two apparent copies of *The Thinker’s Guide to Analytic Thinking*. The unit lists above mark readings held in this Course 7 inventory separately from cross-course or external references; an item named in this extended list is **not automatically held locally or assigned in full**. Select short passages for teaching and verify chapter/page references against the actual editions before making a student reading schedule. The two apparent copies have matching title, page count, and file size in the metadata; compare their actual hashes before treating them as identical or deleting either. Leave the physical folders and `metadata.json` unchanged.

**Extended bibliography (original suggestions retained for optional reference; availability varies)**

* Richard Paul & Linda Elder, *The Thinker’s Guide to Analytical Thinking.*
* George Pólya, *How to Solve It.*
* Herbert Simon, “The Structure of Ill-Structured Problems.”
* Daniel Kahneman, *Thinking, Fast and Slow.*
* Edward de Bono, *Six Thinking Hats.*
* Joseph Novak, *Learning How to Learn.*
* Dan Roam, *The Back of the Napkin.*
* Brian Christian & Tom Griffiths, *Algorithms to Live By.*
* Jeannette Wing, “Computational Thinking.”
* Melanie Mitchell, *Complexity: A Guided Tour.*
* Howard Raiffa, *Decision Analysis: Introductory Lectures on Choices under Uncertainty.*
* Annie Duke, *Thinking in Bets.*
* Daniel Kahneman, Paul Slovic, and Amos Tversky, *Judgment under Uncertainty.*
* Donella Meadows, *Thinking in Systems.*
* Peter Checkland, *Soft Systems Methodology in Action.*
* Gary Klein, *Sources of Power.*
* Carol Weiss, *Evaluation: Methods for Studying Programs and Policies.*
* Rossi, Lipsey & Freeman, *Evaluation: A Systematic Approach.*
* Michael Quinn Patton, *Utilization-Focused Evaluation.*
* CDC, *Framework for Program Evaluation in Public Health.*
* Judea Pearl & Dana Mackenzie, *The Book of Why.*
* Eugene Bardach, *A Practical Guide for Policy Analysis: The Eightfold Path.*
* Deborah Stone, *Policy Paradox.*
* Herbert Simon, *Administrative Behavior.*
* Richards J. Heuer Jr., *Psychology of Intelligence Analysis.*
* Richards J. Heuer Jr. & Randolph H. Pherson, *Structured Analytic Techniques for Intelligence Analysis.*
* Randolph H. Pherson & Katherine Hibbs Pherson, *Critical Thinking for Strategic Intelligence.*
* Sherman Kent, *Strategic Intelligence for American World Policy.*
* Edward Tufte, *The Visual Display of Quantitative Information.*
* Edward Tufte, *Visual Explanations.*
* Cole Nussbaumer Knaflic, *Storytelling with Data.*
* Alberto Cairo, *How Charts Lie.*
* Darrell Huff, *How to Lie with Statistics.*
* National Research Council, *Understanding Risk: Informing Decisions in a Democratic Society.*
* David Spiegelhalter, *The Art of Statistics.*
* Gerd Gigerenzer, *Calculated Risks.*
* Cass Sunstein, *Risk and Reason.*
* Charles Kepner & Benjamin Tregoe, *The New Rational Manager.*
* Eliyahu Goldratt, *The Goal.*
* Russell Ackoff, *The Art of Problem Solving.*
* Philip Tetlock & Dan Gardner, *Superforecasting.*
* Gary Klein, “Performing a Project Premortem.”
* Kees van der Heijden, *Scenarios: The Art of Strategic Conversation.*
