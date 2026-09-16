# Course Overview: Heuristics and Cognitive Biases – From Fast Judgments to Better Decision-Making

## Table of Contents

<!-- UNIT_TOC_START -->
- [Unit 1 – Heuristics as Adaptive Tools](#unit-1)
- [Unit 2 – Representativeness, Availability, and Anchoring](#unit-2)
- [Unit 3 – Risk, Uncertainty, and Reference Points](#unit-3)
- [Unit 4 – Bayesian Reasoning and the Format of Evidence](#unit-4)
- [Unit 5 – Overconfidence, Calibration, and Forecasting](#unit-5)
- [Unit 6 – Motivated Reasoning, Identity, and Confirmation](#unit-6)
- [Unit 7 – Memory, Attention, and Retrospective Bias](#unit-7)
- [Unit 8 – Social Biases: Conformity, Groupthink, and Echoes](#unit-8)
- [Unit 9 – Causal Illusions and Evidence Pitfalls](#unit-9)
- [Unit 10 – Choice Architecture and Decision Design](#unit-10)
- [Unit 11 – Debiasing and Decision Hygiene](#unit-11)
- [Unit 12 – Biases in Models and Systems](#unit-12)
<!-- UNIT_TOC_END -->


**Big question:**
Why do human beings rely on cognitive shortcuts, when do those shortcuts work well, when do they systematically mislead us, and how can individuals and institutions design better judgment under uncertainty?

**By the end, students should be able to:**

* Explain why people use **heuristics** under conditions of bounded rationality, limited time, and incomplete information.
* Distinguish between heuristics as **adaptive tools** and biases as systematic patterns of error.
* Understand the idea of **ecological rationality**: that good reasoning depends on fit between a strategy and its environment.
* Recognize major families of heuristics and biases, including **representativeness, availability, anchoring, framing, overconfidence, hindsight bias, motivated reasoning, and conformity effects**.
* Use basic ideas from **Bayesian reasoning** to interpret evidence, especially base rates, likelihoods, and natural frequencies.
* Explain how **reference points, loss aversion, and framing** shape judgment under risk and uncertainty.
* Diagnose how **memory, attention, salience, and narrative** distort retrospective and prospective reasoning.
* Analyze how **social environments** amplify bias through conformity, cascades, echo chambers, and reputational pressures.
* Identify common **causal illusions and evidence pitfalls**, including illusory correlation, spurious pattern detection, regression to the mean, and post hoc reasoning.
* Evaluate how **choice architecture** and decision environments shape behavior, for better or worse.
* Apply practical **debiasing and decision-hygiene techniques**, including outside-view thinking, premortems, calibration, red teaming, and structured judgment.
* Understand how biases can become embedded in **models, institutions, and systems**, not just in individual minds.
* Communicate about uncertainty, evidence, and judgment more responsibly in everyday, professional, and civic contexts.
* Apply skills from the preceding **argumentation, evidence, data literacy, and causality** courses, while preparing for later work in **risk analysis, model reasoning, and systems thinking**.

**A course-wide diagnostic rule:** Before describing a judgment as biased, specify its benchmark (for example, probabilistic accuracy, consistency, a stated goal, or performance in the relevant environment). Separate a *plausible heuristic or source of bias* from an error actually demonstrated by evidence. A useful shortcut in one setting may mislead in another.

**Reading approach:** “Core” denotes assigned **selections**, not entire books or anthologies. Readings explicitly marked *repository book* or *repository article* appear in the supplied metadata; other cited texts are external readings or possible acquisitions, not confirmed local files. Decision-analysis, risk-analysis, modeling, and systems texts are optional bridges rather than additional core curricula.

---

<a id="unit-1"></a>
## Unit 1 – Heuristics as Adaptive Tools

**Guiding questions**

* Why does the mind rely on shortcuts rather than exhaustive calculation?
* When are heuristics signs of limitation, and when are they signs of intelligence adapted to real environments?
* What does it mean to say that a reasoning strategy “fits” a context?
* What benchmark and comparison would justify calling a heuristic successful—or biased?

**Sub-units**

1. **Bounded rationality and the need for shortcuts**

   * Human beings reason under constraints of time, attention, memory, and computation.
   * Full optimization is often impossible, so heuristics function as workable strategies under real conditions.
   * This unit introduces the contrast between idealized rationality and practical reasoning.

2. **Heuristics as adaptive strategies**

   * Heuristics are not merely flaws or lazy habits.
   * In many settings they are efficient, robust, and surprisingly successful.
   * Students should learn to ask when a shortcut is well adapted rather than assuming all shortcuts are irrational.

3. **Benchmarks for evaluating judgment**

   * Ask what task is being solved, what outcome matters, which alternative strategies are available, and what time, information, and error costs apply.
   * Distinguish a descriptive claim (“people use this shortcut”) from a normative or empirical claim (“it yields worse judgments than an appropriate alternative”).
   * Do not diagnose bias from a label alone: specify the benchmark and the evidence of a systematic deviation.

4. **Ecological rationality**

   * A strategy can be rational relative to an environment even if it is not globally optimal.
   * Good reasoning depends on the structure of the task, the information available, and the costs of delay or error.
   * This idea is foundational for understanding why some heuristics work well in one context and poorly in another.

5. **Fast-and-frugal reasoning**

   * Introduce the “fast and frugal” tradition as an alternative to precision-heavy models of judgment.
   * Compare simple heuristics with more computationally demanding approaches.
   * Emphasize that complexity is not always superior.

6. **Evidence formats as a preview**

   * The way information is represented can dramatically affect reasoning quality.
   * Preview natural frequencies and transparent comparisons as examples of how representation can affect reasoning; detailed translation and evidence-format experiments belong in Unit 4.([Cognitive Science at UCSD][1])
   * Connect back to data literacy and evidence communication without repeating the probability curriculum.

7. **Heuristics and model fit**

   * Every reasoning strategy carries assumptions about the world.
   * Students begin to ask not just “is this shortcut biased?” but “what assumptions make it useful or misleading here?”
   * This creates an early bridge to model reasoning and context-sensitive evaluation.

**Core readings**

* Gerd Gigerenzer, Peter M. Todd & the ABC Research Group, *Simple Heuristics That Make Us Smart* (repository book; selected chapters on fast-and-frugal heuristics and ecological rationality).
* Thomas Gilovich, Dale Griffin & Daniel Kahneman (eds.), *Heuristics and Biases: The Psychology of Intuitive Judgment* (repository book; selected overview or contrasting chapters).
* Gigerenzer & Hoffrage (1995), “How to Improve Bayesian Reasoning Without Instruction” (optional preview; assigned in Unit 4).([Cognitive Science at UCSD][1])

---

<a id="unit-2"></a>
## Unit 2 – Representativeness, Availability, and Anchoring

**Guiding questions**

* How do people judge probability, frequency, and typicality without formal calculation?
* Why do vivid, salient, or emotionally charged cases dominate judgment?
* Why do initial numbers or frames continue to shape later estimates?

**Sub-units**

1. **Representativeness**

   * People often judge likelihood by similarity to a prototype or stereotype.
   * This can be useful for quick classification, but it often leads to neglect of background rates.
   * Students learn why resemblance is not the same thing as probability.

2. **Base-rate neglect**

   * General prevalence information is often ignored when individuating details are vivid.
   * This helps explain errors in medicine, law, hiring, and everyday inference.
   * It also prepares students for later work in Bayesian reasoning.

3. **Availability**

   * Judgments of frequency and risk are strongly influenced by how easily examples come to mind.([familyvest.com][4])
   * Recent, dramatic, and emotionally intense cases feel more common than they are.
   * This explains why public risk perception can drift away from statistical reality.

4. **Salience and perceived prevalence**

   * Repetition, recency, and vivid presentation can affect which examples are available for a frequency judgment.
   * Contrast readily recalled events with relevant denominator data; do not assume every memorable example is unrepresentative.
   * Detailed analysis of media ecosystems and persuasion belongs in the later media-focused course.

5. **Anchoring and insufficient adjustment**

   * Initial values—even arbitrary ones—pull later judgments toward them.
   * Adjustment away from an anchor is often too small.
   * Students learn to see how first numbers set cognitive reference points.

6. **Heuristic or bias? Compare against evidence**

   * A vivid case can feel more convincing than a stable pattern, but vividness, familiarity, and anchors sometimes convey useful information.
   * For each example specify the judgment task, the relevant base rate or other benchmark, and the conditions under which the shortcut helps or misleads.
   * Use one worked problem each for representativeness, availability, and anchoring; distinguish actual error from a plausible but untested diagnosis.

**Core readings**

* Daniel Kahneman, Paul Slovic & Amos Tversky (eds.), *Judgment under Uncertainty: Heuristics and Biases* (repository book; selected original studies on representativeness, availability, and anchoring).
* Thomas Gilovich, Dale Griffin & Daniel Kahneman (eds.), *Heuristics and Biases: The Psychology of Intuitive Judgment* (repository book; selected chapters on benchmarks and boundary conditions).
* Tversky & Kahneman (1973), “Availability: A Heuristic for Judging Frequency and Probability.”([familyvest.com][4])

---

<a id="unit-3"></a>
## Unit 3 – Risk, Uncertainty, and Reference Points

**Guiding questions**

* What is the difference between measurable risk and deeper uncertainty?
* Why do gains and losses feel psychologically asymmetric?
* How do framing and reference points shape what counts as a good or bad outcome?

**Sub-units**

1. **Risk versus uncertainty**

   * Some situations allow stable probabilistic reasoning; others do not.
   * Students learn why this distinction matters for decision-making and inference.
   * This helps them see why the same heuristic may perform differently across environments.

2. **Reference dependence**

   * Outcomes are often evaluated relative to a baseline, expectation, or status quo.
   * This means value is not assessed in absolute terms alone.
   * Students begin to see why “the same” outcome can feel different under different descriptions.

3. **Loss aversion**

   * Losses often loom larger than equivalent gains.([Massachusetts Institute of Technology][5])
   * This helps explain caution, status quo bias, and reluctance to give up possessions or commitments.
   * It also helps explain distortions in policy and personal decision-making.

4. **Diminishing sensitivity**

   * The subjective impact of changes often depends on where one starts.
   * A shift from 0 to 10 can feel more important than a shift from 100 to 110.
   * This shapes how people perceive trade-offs and incentives.

5. **Framing effects and a paired-choice exercise**

   * Equivalent options can be judged differently depending on whether they are presented as gains or losses.
   * Give students one decision twice, with numerically equivalent gain and loss frames; compare judgments and ask what actually changed.
   * Distinguish inconsistent responses to equivalent information from cases where the descriptions supply genuinely different information or alter the relevant decision context.
   * Connect the exercise back to argumentation and data-literacy work on representation.

6. **Reference points in public argument and policy**

   * Framing influences not only individual choices but social debates.
   * Policy claims often smuggle in assumptions about what counts as the default or the loss to be avoided.
   * This helps students analyze persuasive language more critically.

**Core readings**

* Daniel Kahneman & Amos Tversky (eds.), *Choices, Values, and Frames* (repository book; selected chapters on framing, reference dependence, and risk—not the complete anthology).
* Kahneman & Tversky (1979), “Prospect Theory: An Analysis of Decision under Risk.”([Massachusetts Institute of Technology][5])
* Tversky & Kahneman (1992), “Advances in Prospect Theory” (optional extension).([CSUF Psychology Department][3])

---

<a id="unit-4"></a>
## Unit 4 – Bayesian Reasoning and the Format of Evidence

**Guiding questions**

* Why do people struggle with conditional probability and base rates?
* Why do natural frequencies often improve reasoning more than percentages do?
* How can evidence be reformatted to support better judgment?

**Sub-units**

1. **Base rates, likelihoods, and posterior judgment**

   * Apply the Bayesian concepts introduced in the preceding Evidence and Data Literacy courses rather than reteaching their full statistical foundations.
   * Distinguish prior prevalence, P(evidence | hypothesis), and P(hypothesis | evidence); the last cannot be read directly from a test's sensitivity.
   * Focus on what format changes make those distinctions easier or harder for a reader to recognize.

2. **The mammography problem and diagnostic reasoning**

   * Use classic examples to show how easily people misjudge low-base-rate events.([Cambridge University Press & Assessment][6])
   * Emphasize why intuitive responses often confuse test accuracy with the probability of a condition.
   * This is a practical bridge to medicine, law, and everyday risk interpretation.

3. **Why natural frequencies help**

   * Many learners reason better when information is expressed as counts rather than abstract percentages.([Cognitive Science at UCSD][1])
   * Treat improved performance as an empirical, task-dependent finding, not a guarantee for every person or probabilistic judgment.
   * Students evaluate how representation interacts with comprehension, numeracy, and the specific question.([Frontiers][2])

4. **Evidence-format comparison lab**

   * Solve the same diagnostic problem first in percentages, then in a natural-frequency table, and finally with a simple frequency tree; keep the underlying prevalence and test properties identical.
   * Record the answer and explanation in each format, identify where conditional probabilities were confused, and compare the representations rather than assuming one works for everyone.
   * Extend to one non-medical example so students transfer the interpretation skill rather than memorize one puzzle.

5. **Bayesian reasoning beyond medicine**

   * Applications in legal evidence, screening, everyday decisions, and policy contexts.
   * Students learn to generalize the pattern rather than memorize one puzzle.
   * This turns Bayesian reasoning into a reusable interpretive tool.

6. **When Bayesian reasoning still does not settle the question**

   * Good probabilistic reasoning depends on good inputs and good models.
   * Students learn that Bayesian tools can clarify inference without eliminating ambiguity.
   * This sets up later units on overconfidence, motivation, and model risk.

**Core readings**

* Gigerenzer & Hoffrage (1995), *How to Improve Bayesian Reasoning Without Instruction*.([Cognitive Science at UCSD][1])
* Eddy (1982), *Probabilistic Reasoning in Clinical Medicine*.([Cambridge University Press & Assessment][6])
* Hoffrage (2015), “Natural frequencies improve Bayesian reasoning…”([Frontiers][2])
* Kahneman, Slovic & Tversky (eds.), *Judgment under Uncertainty* (repository book; optional related selections).

---

<a id="unit-5"></a>
## Unit 5 – Overconfidence, Calibration, and Forecasting

**Guiding questions**

* Why are people often more certain than they should be?
* What is the difference between being knowledgeable and being well-calibrated?
* How can judgment be improved through forecasting discipline?

**Sub-units**

1. **Three forms of overconfidence**

   * Overestimation, overplacement, and overprecision.([Europe PMC][7])
   * Students learn that “overconfidence” is not one single phenomenon.
   * This helps them diagnose different failures in self-assessment and comparison.

2. **Confidence, calibration, and forecast quality**

   * Distinguish a subjective feeling of certainty from an explicitly stated probability that can be checked against outcomes.
   * Calibration asks whether events assigned a given probability occur at roughly that rate; it is not the whole of forecast quality.
   * Sharpness/resolution and comparison with a simple baseline also matter: assigning 50% to everything can look calibrated while providing little discrimination.

3. **Forecasting and probabilistic judgment**

   * Good forecasting requires explicit probabilities, feedback, and revision.
   * Students learn why vague certainty language often masks poor reasoning.
   * This also connects to intellectual humility as a practical virtue.

4. **The Brier score and its limits**

   * Introduce the Brier score as a proper scoring rule for binary probabilistic forecasts.([American Meteorological Society Journals][8])
   * Compare each student's score with a stated simple baseline and examine a small confidence-versus-outcome table or plot.
   * Do not interpret a single Brier score as a direct measurement of calibration: it reflects more than calibration, and short exercises produce noisy estimates.

5. **Calibration drills and reflective practice**

   * Collect timestamped probabilities for a set of resolvable questions and record outcomes before reviewing judgments.
   * Examine bins of forecasts alongside observed frequencies and compare with a simple baseline; explicitly note small-sample limitations.
   * Use repeated feedback to investigate—not presume—overprecision, poorly chosen reference classes, or other possible weaknesses.

6. **On-ramps to superforecasting**

   * Update beliefs incrementally.
   * Distinguish signal from noise.
   * Break large questions into smaller ones.
   * Seek disconfirming evidence and compare outside views.([Barnes & Noble][9])

**Core readings**

* Moore & Healy (2008), *The Trouble with Overconfidence*.([Europe PMC][7])
* Brier (1950), *Verification of Forecasts Expressed in Terms of Probability*.([American Meteorological Society Journals][8])
* Tetlock & Gardner (2015), *Superforecasting: The Art & Science of Prediction* (external reading; selected chapters).([Barnes & Noble][9])
* Jonathan Baron, *Thinking and Deciding* (repository book; optional selected sections on judgment and probability).

---

<a id="unit-6"></a>
## Unit 6 – Motivated Reasoning, Identity, and Confirmation

**Guiding questions**

* Why do people often use reasoning to defend prior commitments rather than discover the truth?
* How do goals, identities, and group loyalties shape evidence evaluation?
* What helps people reason more accurately in contested domains?

**Sub-units**

1. **What is motivated reasoning?**

   * Reasoning is often guided by desires, goals, or identity commitments.([Frank Baumgartner][10])
   * People are not always asking “what is true?” but “what can I defend?” or “what fits who I am?”
   * This reframes bias as partly motivational, not purely computational.

2. **Confirmation and selective exposure**

   * People preferentially seek, remember, and endorse information that supports existing beliefs.
   * Contrary evidence is often discounted or avoided.
   * Students learn to see confirmation bias as a process, not just a slogan.

3. **Disconfirmation asymmetry**

   * Opposing evidence often receives harsher scrutiny than supporting evidence.([Semantic Scholar][11])
   * This can make intelligent people more polarized rather than more accurate.
   * It helps explain why conflict over evidence often intensifies with argument.

4. **Identity-protective cognition**

   * Examine research on how social belonging or identity can be associated with selective handling of evidence, including limits and competing interpretations of particular studies.([Network Dynamics Group][12])
   * Avoid diagnosing an individual or group from a political or social label alone; first look for observable asymmetries in the task and evaluation criteria.
   * Compare how the same evidence is treated across differently framed claims without assuming a particular identity uniquely displays the effect.

5. **Standards, prompts, and accountability**

   * Accuracy prompts, shared criteria, and structured evaluation can reduce some motivated distortions.
   * Students learn that better reasoning often depends on institutional supports, not just willpower.
   * This connects debiasing to design.

6. **Motivated reasoning in argumentation and public life**

   * Return to Course 2's argument reconstruction: compare how participants select, scrutinize, or dismiss substantively similar evidence.
   * Separate observations about selective evaluation from speculative attributions of private motives or fixed traits.
   * Treat civic controversies as possible case material without making political agreement or disagreement itself a measure of reasoning quality.

**Core readings**

* Kunda (1990), *The Case for Motivated Reasoning*.([Frank Baumgartner][10])
* Lord, Ross & Lepper (1979), *Biased assimilation and attitude polarization*.([Semantic Scholar][11])
* Kahan (2013), “Ideology, Motivated Reasoning, and Cognitive Reflection” (one case-specific research contribution).([Network Dynamics Group][12])
* Jost, Glaser, Kruglanski & Sulloway, “Political Conservatism as Motivated Social Cognition” (repository article; optional, contextualized case study rather than a stand-in for motivated reasoning across all groups).

---

<a id="unit-7"></a>
## Unit 7 – Memory, Attention, and Retrospective Bias

**Guiding questions**

* How do memory and attention reshape what we think we knew, saw, or expected?
* Why do hindsight and salience distort judgment after events occur?
* How do narratives and visual presentations influence what is later remembered as obvious?

**Sub-units**

1. **Hindsight bias**

   * After outcomes are known, they often seem more predictable than they were.([ResearchGate][13])
   * Students learn why “I knew it all along” is often a reconstruction rather than a memory.
   * This matters for blame, evaluation, and overconfidence.

2. **Salience and attentional capture**

   * What stands out in perception and communication often dominates later recall.
   * Attention is selective, and what is selected shapes later judgment.
   * This helps explain why certain risks and stories become cognitively oversized.

3. **Recency and memory weighting**

   * Recent events often feel more important or diagnostic than older but more representative information.
   * Students learn how temporal proximity distorts perceived relevance.
   * This links memory bias to availability effects.

4. **Availability cascades (brief bridge)**

   * Repeated discussion can amplify perceived importance independently of the underlying prevalence.([SSRN][14])
   * Use one example to link retrieval and social reinforcement; leave sustained analysis of media ecosystems to the later media course.

5. **Narratives, visualizations, and after-the-fact explanation**

   * Stories and visual patterns help memory but can also create false coherence.
   * Students examine how explanation after the fact can exceed what was justified beforehand.
   * This is a key safeguard for reasoning from outcomes backward.

6. **Before-and-after hindsight lab**

   * Before an outcome is disclosed, record a prediction, confidence, reasons, and plausible alternatives; afterward compare the record with a fresh recollection of the earlier judgment.
   * Check for changes in remembered confidence, perceived inevitability, and recalled alternatives.
   * A classroom demonstration prompts reflection; it does not alone establish the prevalence, mechanism, or universality of hindsight bias.
   * Keep timestamped logs as a practical safeguard and connect to Unit 5's calibration work.

**Core readings**

* Fischhoff (1975), *The Knew-It-All-Along Effect*.([ResearchGate][13])
* Tversky & Kahneman (1973), *Availability*.([familyvest.com][4])
* Kuran & Sunstein (1999), “Availability Cascades and Risk Regulation” (optional bridge).([SSRN][14])
* Rüdiger F. Pohl (ed.), *Cognitive Illusions: Intriguing Phenomena in Judgement, Thinking and Memory* (repository book; selected chapters on memory, attention, and hindsight).

---

<a id="unit-8"></a>
## Unit 8 – Social Biases: Conformity, Groupthink, and Echoes

**Guiding questions**

* How do other people reshape what individuals perceive, say, and believe?
* Why do groups sometimes become less accurate rather than more intelligent?
* What organizational conditions make collective judgment better or worse?

**Sub-units**

1. **Conformity, learning from others, and social pressure**

   * Distinguish publicly expressed agreement, privately held belief, and rational updating from other people's genuine information.
   * Use classic conformity tasks to ask what evidence supports each interpretation; agreement alone does not demonstrate bias.([nwkpsych.rutgers.edu][15])
   * Explore how task ambiguity, incentives, and the quality of others' information affect collective judgment.

2. **Reputational pressure and signaling**

   * People do not only seek truth; they also manage impressions.
   * Fear of isolation, career costs, or reputational penalties can distort public judgment.
   * This helps explain silence, exaggeration, and performative agreement.

3. **Groupthink**

   * Highly cohesive groups can suppress dissent, ignore warning signs, and overestimate their certainty.([Internet Archive][16])
   * Students learn the symptoms of groupthink and how they appear in committees, institutions, and policy teams.
   * This connects cognitive bias to organizational failure.

4. **Information cascades and social amplification**

   * Once a judgment seems widely accepted, others may adopt it without independent evaluation.
   * Cascades can emerge from limited information plus social imitation.
   * This links social reasoning to broader systems effects.

5. **Echo chambers and feedback environments (scope note)**

   * Repeated exposure and homogeneous groups may shape which evidence is encountered and which sources are trusted.
   * Connect briefly to Course 1's social epistemology; defer platform architecture and media-persuasion analysis to the later media course.

6. **Independent-versus-group judgment lab and safeguards**

   * Collect initial independent estimates and their reasons; then compare estimates after group discussion, noting new evidence, conformity pressure, and whether dissent was voiced.
   * Compare a second round with anonymous input or structured dissent; distinguish observed changes from proof that one procedure is generally superior.
   * Discuss red teams, independent estimates, and role rotation as candidate safeguards to be evaluated rather than assumed effective.

**Core readings**

* Asch (1951), *Effects of Group Pressure upon the Modification and Distortion of Judgments*.([nwkpsych.rutgers.edu][15])
* Janis (1972/1982), *Victims of Groupthink* / *Groupthink* (external reading; selected chapters).([Internet Archive][16])
* Gilovich, Griffin & Kahneman (eds.), *Heuristics and Biases* (repository book; optional relevant social-judgment selections).

---

<a id="unit-9"></a>
## Unit 9 – Causal Illusions and Evidence Pitfalls

**Guiding questions**

* Why do people so readily see patterns, causes, and signals that are not really there?
* What makes pseudoscientific and superstitious explanations so cognitively attractive?
* How do causal misconceptions persist even when students know appropriate evidence and causal-design standards?

**Sub-units**

1. **Illusory correlation**

   * People often perceive associations that fit expectations even when the evidence is weak or absent.([PubMed][17])
   * This shows how prior beliefs can structure pattern detection.
   * Students learn why confident pattern recognition is not self-validating.

2. **Illusions of causality**

   * Repeated co-occurrence can be mistaken for genuine causation.([PMC][18])
   * Students examine why interventions, rituals, or false remedies can feel effective.
   * This is especially important for understanding pseudoscience and magical thinking.

3. **Spurious patterns and noisy environments**

   * Random variation often produces apparent structure.
   * Students learn to distinguish meaningful regularity from chance clustering.
   * This supports both critical thinking and quantitative literacy.

4. **Regression to the mean**

   * Extreme outcomes are often followed by more typical ones even without intervention.
   * This creates powerful illusions of improvement or decline.
   * It is one of the most important neglected biases in everyday causal judgment.

5. **Why earlier causal and statistical pitfalls feel persuasive**

   * Revisit one previously learned example of base-rate neglect, a misleading aggregation, or regression to the mean from Courses 4–5.
   * Diagnose *why* the intuitive story attracts belief: salient co-occurrence, omitted alternatives, selective attention, or a compelling narrative.
   * Do not re-teach formal stratification, DAG adjustment, or study-design methods here.

6. **Causal-illusion diagnosis and repair**

   * First capture the intuitive causal account; then use already learned evidence and causal-design tools to identify an alternative explanation or test.
   * Contrast psychological appeal with evidential support, rather than labeling a causal claim false solely because a familiar bias could explain it.
   * This is an *application of* Course 5's causality methods, not preparation for a later causality course.

**Core readings**

* Chapman & Chapman (1969), *Illusory correlation as an obstacle to the use of valid psychodiagnostic signs*.([PubMed][17])
* Matute et al. (2015), *Illusions of causality: how they bias our everyday thinking*.([PMC][18])

---

<a id="unit-10"></a>
## Unit 10 – Choice Architecture and Decision Design

**Guiding questions**

* How do environments shape choice independently of explicit reasoning?
* When can small design changes produce large behavioral effects?
* What makes a nudge helpful, manipulative, or ethically questionable?

**Sub-units**

1. **Choice architecture as an applied psychology of decision**

   * Decisions are shaped by order, defaults, visibility, and effort.
   * This unit shows that judgment is always situated in an environment.
   * It shifts attention from internal bias to external design.

2. **Defaults**

   * Default options powerfully influence behavior because changing them requires attention, effort, or confidence.([Dan Goldstein][20])
   * Students learn why default design matters in health, finance, administration, and digital systems.
   * This is one of the clearest demonstrations of environment-sensitive choice.

3. **Salience and option ordering**

   * What is easiest to notice or first to appear often receives disproportionate weight.
   * Students examine how menus, forms, interfaces, and sequences influence decision-making.
   * This ties back to availability and attention effects.

4. **Present bias and limited attention**

   * Immediate costs and rewards often dominate long-term considerations.
   * Choice environments can either exacerbate or mitigate this tendency.
   * This helps explain procrastination, under-saving, and policy design challenges.

5. **Choice overload and boundary conditions**

   * More options can be useful or burdensome depending on the task, option similarity, decision-maker knowledge, and available support.
   * Treat choice overload as a context-dependent empirical question, not a universal effect.
   * Ask what the added options contribute and whether the presentation makes meaningful comparison possible.

6. **Auditing a choice environment and the ethics of nudging**

   * Audit a real form or workflow: identify the default, order, salience, friction, and accessible alternatives.
   * Ask whose objectives the design serves, whether its mechanism is visible, and whether users can meaningfully decline or reverse the default.
   * Discuss autonomy, transparency, consent, and the conditions under which a design choice is helpful, ineffective, or manipulative; do not assume a nudge works uniformly across contexts.

7. **Choice design as a systems lever**

   * Small local changes can scale into large aggregate effects.
   * This makes choice architecture a bridge from psychology to institutions and systems thinking.
   * Students begin to see individual judgment as embedded in larger design structures.

**Core readings**

* Thaler & Sunstein (2008/2021), *Nudge*.([PenguinRandomhouse.com][19])
* Johnson & Goldstein (2003/2004), “Do Defaults Save Lives?” / “Defaults and Donation Decisions” (external reading; selected study).([Dan Goldstein][20])
* Martin Peterson, *An Introduction to Decision Theory* (repository book; optional conceptual bridge, not a full decision-analysis module).

---

<a id="unit-11"></a>
## Unit 11 – Debiasing and Decision Hygiene

**Guiding questions**

* Can biases actually be reduced, or only managed?
* What kinds of interventions improve judgment across tasks and settings?
* How do habits, procedures, and institutions support better reasoning?

**Sub-units**

1. **What counts as evidence of successful debiasing?**

   * Distinguish feeling more thoughtful from measurably improved accuracy, calibration, consistency, or decision outcomes.
   * Ask whether benefits persist over time and transfer to unfamiliar tasks, and which benchmark the intervention is supposed to improve.
   * The goal is often mitigation and management rather than permanent cognitive repair; effectiveness varies by task and setting.

2. **Cognitive debiasing strategies**

   * Consider-the-opposite, outside-view reasoning, explicit base-rate checks, and reframing.([Wiley Online Library][21])
   * These strategies help individuals interrupt default patterns of thought.
   * The emphasis is on practical use rather than abstract endorsement.

3. **Motivational debiasing**

   * Accuracy prompts, accountability, and incentive structures can reduce some distortions.
   * Students learn that wanting to be right is not always enough, but it matters.
   * This revisits the course’s earlier unit on motivated reasoning in a practical register.

4. **Premortems, red teams, and structured dissent**

   * Premortems ask what might cause failure before it occurs.([Harvard Business Review][22])
   * Red teams institutionalize critique rather than leaving it to personality.
   * These tools reduce blind spots in teams and organizations.

5. **Noise versus bias**

   * Not all poor judgment is systematic in one direction.
   * Some failures come from inconsistency, variability, or idiosyncratic standards.([Hachette Book Group][23])
   * This helps students distinguish patterned distortion from random judgment scatter.

6. **Checklists, rails, and a small comparison exercise**

   * Compare an unstructured judgment round with a round using independent initial estimates, base-rate prompts, or structured criteria, while holding the question and evaluation benchmark explicit.
   * Note practice effects, small samples, and task differences: a classroom comparison cannot establish general debiasing effectiveness.
   * Discuss how standardized forms and staged evaluation might reduce avoidable error, subject to testing and monitoring.

7. **Decision hygiene and intellectual virtue**

   * Humility, revision, transparency, and error-correction become practical habits.
   * Students connect judgment improvement to character as well as technique.
   * This provides a culminating ethical dimension to the course.

**Core readings**

* Larrick (2004), *Debiasing*.([Wiley Online Library][21])
* Klein (2007), *Performing a Project Premortem*.([Harvard Business Review][22])
* Kahneman, Sibony & Sunstein (2021), *Noise: A Flaw in Human Judgment*.([Hachette Book Group][23])
* Soll (2015), “A User’s Guide to Debiasing” (external reading; evidence and boundary conditions).([Katy Milkman][24])
* Jonathan Baron, *Thinking and Deciding* (repository book; selected sections on judgment and decision strategies).

---

<a id="unit-12"></a>
## Unit 12 – Biases in Models and Systems

**Guiding questions**

* How do biases move from individual minds into models, metrics, and institutions?
* What does it mean to say that a model is useful even when it is wrong?
* How do incentives, abstractions, and feedback loops amplify judgment failures?

**Sub-units**

1. **Distinguishing cognitive, model, and incentive problems**

   * **Cognitive bias:** an identified pattern of judgment error relative to a benchmark.
   * **Model misspecification:** a representation or set of assumptions that fits its task poorly; it need not be traceable to an individual's cognitive bias.
   * **Metric distortion:** incentives or feedback change behavior in response to a target; this is related to but not identical with either of the above.
   * Examine how these distinct problems can interact without collapsing them into one label.

2. **Model risk and uncertainty**

   * Every model excludes some factors and represents others imperfectly.
   * Students learn to ask what was left out, idealized, or stabilized.
   * This is a bridge from cognitive bias to analytical model thinking.

3. **“All models are wrong, some are useful”**

   * Box’s famous line is interpreted as a principle of disciplined humility.([www-sop.inria.fr][25])
   * The issue is not whether a model is literally true, but whether it is useful for a purpose under stated assumptions.
   * This helps students evaluate models without either worship or cynicism.

4. **Goodhart’s Law and target distortion**

   * When a measure becomes a target, it can stop functioning as a good measure.([SpringerLink][27])
   * Incentives reshape behavior around the metric.
   * This shows how measurement systems can generate perverse outcomes.

5. **Feedback loops and a single traceable case**

   * Trace one example from an initial judgment through an imperfect measurement proxy, an institutional performance target, and feedback from subsequent behavior.
   * At each step identify the distinct cognitive, modeling, measurement, or incentive-based mechanism instead of assuming they are interchangeable.
   * Keep feedback analysis introductory; dynamic systems modeling belongs in the later systems course.

6. **Mental models and internal representations**

   * People reason using simplified internal pictures of how systems work.([Internet Archive][28])
   * These mental models can guide action effectively or mislead badly.
   * Students learn to inspect their own implicit representations of systems.

7. **Biases in organizations and infrastructures**

   * Screening systems, dashboards, algorithmic tools, and institutional routines can stabilize particular errors or create new ones.
   * Ask who is affected, what feedback would reveal an error, and which decision or measurement process could be revised.
   * End with a handoff to deeper model and systems courses rather than a second comprehensive modeling unit.

**Core readings**

* Box (1976), *Science and Statistics*.([www-sop.inria.fr][25])
* Sterman (2000), *Business Dynamics: Systems Thinking and Modeling for a Complex World* (optional forward reference for the later systems course).([McGraw Hill][26])
* Goodhart (1975), *Problems of Monetary Management: The U.K. Experience*.([SpringerLink][27])
* Johnson-Laird (1983), *Mental Models* (optional bridge to model thinking).([Internet Archive][28])

---

## Practical activities, capstones, and reflection

* **Bias Journal and Decision Audit**

  Students keep a one-week journal in which they:

  * identify a daily decision or judgment and the benchmark for evaluating it
  * name the **plausible** heuristic or bias involved without assuming it has been demonstrated
  * record the evidence format, alternatives, and time/information constraints
  * consider when the shortcut might be adaptive or misleading and what evidence would distinguish the cases
  * propose and, where feasible, test an improvement such as checking base rates, translating to frequencies, or using an outside view
  * finish with the question: **What model did you implicitly use?**

* **Calibration Clinic**

  * Students answer about 20 resolvable prediction items using timestamped probabilities, then record outcomes.
  * They compute the Brier score, compare it with a simple baseline, and examine a confidence-versus-outcome table.
  * They discuss whether the sample is large enough to support a conclusion about calibration and how feedback might improve future forecasts.

* **Premortem and Red-Team Exercise**

  * Small groups conduct a 20-minute premortem on an upcoming assignment, project, or organizational plan.
  * A separate group acts as a red team and challenges the assumptions.
  * Students compare the results with unstructured group discussion, noting what was surfaced without assuming the exercise proves general effectiveness.

* **Choice Architecture Audit**

  * Students analyze a campus form, digital workflow, public-facing website, or institutional process.
  * They identify defaults, salience cues, friction points, and possible overload.
  * They document whose goals are served, whether choices are transparent and reversible, and who may be disadvantaged.
  * They propose a redesign and specify how its effectiveness and autonomy effects could be evaluated.

* **Causal Illusion Case Study**

  * Students choose a public claim, pseudoscientific practice, or apparently striking correlation.
  * They explain why a proposed causal story is cognitively attractive while distinguishing suspicion from a demonstrated mistake.
  * They apply causal-design tools from Course 5 and propose a stronger evidential test.

* **Model and Metric Critique**

  * Students select a ranking system, performance metric, dashboard, or simple predictive model.
  * They identify separately any cognitive judgment error, model misspecification, measurement proxy, incentive, and feedback mechanism.
  * They trace one plausible interaction and explain what additional evidence would be needed to substantiate it.

---

**Activity safeguards:** Treat classroom results as illustrations, not estimates of population-wide bias or proof of debiasing effectiveness. Reuse selected readings from Tetlock & Gardner (forecasting), Klein (premortems), and Larrick (debiasing) as needed.([Barnes & Noble][9]; [Harvard Business Review][22]; [Wiley Online Library][21])

---

## Teaching moves

* **Natural-frequency rewrites** that convert abstract probabilities into concrete counts.
* **Prediction logs** that preserve uncertainty before outcomes are known.
* **Micro-case contrasts** comparing a heuristic that works well in one environment and badly in another.
* **Argument repair exercises** in which students revise claims distorted by framing, anchoring, or salience.
* **Group decision labs** that make conformity, dissent, and groupthink visible in real time.
* **Bias-to-design bridges** that ask not only “what went wrong in the mind?” but also “what in the environment encouraged it?”
* **Model reflection prompts** asking students what assumptions or simplifications they implicitly used.

---

## Glossary

**Benchmark for bias**; **Bounded rationality**; **Heuristic**; **Ecological rationality**; **Representativeness**; **Availability**; **Anchoring**; **Base-rate neglect**; **Reference dependence**; **Loss aversion**; **Framing effect**; **Natural frequency**; **Calibration**; **Overconfidence**; **Brier score**; **Motivated reasoning**; **Identity-protective cognition**; **Hindsight bias**; **Availability cascade**; **Groupthink**; **Echo chamber**; **Illusory correlation**; **Regression to the mean**; **Choice architecture**; **Default effect**; **Premortem**; **Noise**; **Goodhart’s Law**; **Mental model**.

---

[1]: https://cogsci.ucsd.edu/~coulson/203/GG_How_1995.pdf "How to Improve Bayesian Reasoning Without Instruction"
[2]: https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2015.01473/full "Natural frequencies improve Bayesian reasoning in simple ..."
[3]: https://psych.fullerton.edu/mbirnbaum/psych466/articles/Tversky_Kahneman_JRU_92.pdf "Advances in prospect theory: Cumulative representation of ..."
[4]: https://familyvest.com/wp-content/uploads/2019/02/TverskyKahneman73.pdf "Availability: A Heuristic for Judging Frequency and ..."
[5]: https://web.mit.edu/curhan/www/docs/Articles/15341_Readings/Behavioral_Decision_Theory/Kahneman_Tversky_1979_Prospect_theory.pdf "Prospect Theory: An Analysis of Decision under Risk"
[6]: https://www.cambridge.org/core/books/judgment-under-uncertainty/probabilistic-reasoning-in-clinical-medicine-problems-and-opportunities/661E12D1ECD669EDB5B410407A4BB570 "Probabilistic reasoning in clinical medicine: Problems and ..."
[7]: https://europepmc.org/article/med/18426301 "The trouble with overconfidence. - Abstract"
[8]: https://journals.ametsoc.org/view/journals/mwre/78/1/1520-0493_1950_078_0001_vofeit_2_0_co_2.xml "VERIFICATION OF FORECASTS EXPRESSED IN TERMS OF ..."
[9]: https://www.barnesandnoble.com/w/superforecasting-philip-e-tetlock/1120956116 "Superforecasting: The Art and Science of Prediction"
[10]: https://fbaum.unc.edu/teaching/articles/Psych-Bulletin-1990-Kunda.pdf "The Case for Motivated Reasoning"
[11]: https://www.semanticscholar.org/paper/Biased-Assimilation-and-Attitude-Polarization%3A-The-Lord-Ross/16ae4cf82e87451492d0eb12190acfb63294e305 "Biased Assimilation and Attitude Polarization: The Effects ..."
[12]: https://ndg.asc.upenn.edu/wp-content/uploads/2017/08/Ideology-motivated-reasoning.pdf "Ideology, motivated reasoning, and cognitive reflection"
[13]: https://www.researchgate.net/publication/232494530_The_Knew-It-All-Along_Effect "The knew-it-all-along effect"
[14]: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=138144&utm_source=chatgpt.com "Availability Cascades and Risk Regulation"
[15]: https://nwkpsych.rutgers.edu/~kharber/selectedtopicsinsocialpsychology/READINGS/Asch%201951%20Group%20pressure%20and%20judgment.pdf "Asch 1951 Group pressure and judgment.pdf"
[16]: https://archive.org/details/janis_groupthink "Victims of Groupthink: A Psychological Study of Foreign-Policy ..."
[17]: https://pubmed.ncbi.nlm.nih.gov/4896551/ "Illusory correlation as an obstacle to the use of valid ..."
[18]: https://pmc.ncbi.nlm.nih.gov/articles/PMC4488611/ "Illusions of causality: how they bias our everyday thinking ..."
[19]: https://www.penguinrandomhouse.com/books/690485/nudge-by-richard-h-thaler-and-cass-r-sunstein/ "Nudge by Richard H. Thaler, Cass R. Sunstein"
[20]: https://www.dangoldstein.com/papers/DefaultsScience.pdf "POLICY FORUM"
[21]: https://onlinelibrary.wiley.com/doi/10.1002/9780470752937.ch16 "Debiasing - Blackwell Handbook of Judgment and ..."
[22]: https://hbr.org/product/performing-a-project-premortem/F0709A-PDF-ENG "Performing a Project Premortem"
[23]: https://www.hachettebookgroup.com/titles/daniel-kahneman/noise/9780316451383/ "Noise by Daniel Kahneman | Hachette ..."
[24]: https://www.katymilkman.com/s/39-2016_Handbook_of_JDM-bht6.pdf "A User's Guide to Debiasing"
[25]: https://www-sop.inria.fr/members/Ian.Jermyn/philosophy/writings/Boxonmaths.pdf "Science and Statistics George E. P. Box Journal of the ..."
[26]: https://www.mheducation.com/highered/product/business-dynamics-sterman.html "Business Dynamics: Systems Thinking and Modeling for a ..."
[27]: https://link.springer.com/chapter/10.1007/978-1-349-17295-5_4 "Problems of Monetary Management: The UK Experience"
[28]: https://archive.org/details/mentalmodelstowa0000john "Mental models : towards a cognitive science of language ..."
