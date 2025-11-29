# Course Overview: Data Literacy – From Measurement to Data Ecosystems

**Big question:**
How do measurements become *data*, how do we reason from data under uncertainty, and how do institutions and infrastructures shape what “the numbers” seem to say?

**By the end, students should be able to:**

* Explain what *data* are (units, variables, metadata) and distinguish data from information and knowledge.
* Trace the **data lifecycle**: question → population → sampling frame → measurement → dataset → analysis → reporting.
* Distinguish **populations vs samples**, understand basic sampling designs, and diagnose common sampling biases (selection bias, survivorship bias, Berkson’s paradox, etc.).([Amazon][1])
* Recognize how **measurement decisions** and metrology (including social/psychological measurement) constrain what datasets can legitimately say.([OAPEN Library][2])
* Use basic **probability and statistical ideas** (conditional probability, base rates, Type I/II errors, sensitivity/specificity, confidence intervals) to interpret everyday quantitative claims.
* See statistical analysis as **principled argument from data**, not just as a bag of formulas.([Routledge][3])
* Detect common **misuses of statistics** and dodgy data graphics, drawing on “Calling Bullshit,” Huff, Campbell, and Tufte.([Amazon][4])
* Understand the role of **research practice and reporting guidelines** (CONSORT, STROBE, PRISMA, GRADE, Cochrane) in making data interpretable and trustworthy.([SpringerLink][5])
* Appreciate how **big data, platforms, and infrastructures** (EHRs, administrative data, platform logs) change sampling, bias, governance, and the politics of quantification.([Wikipedia][6])
* Be ready for the next course on **causality**, having seen Simpson’s paradox, base-rate neglect, ecological fallacies, and “correlation ≠ causation” in a properly serious way.([Stanford Encyclopedia of Philosophy][7])

---

## Unit 1 – From Measurement to Data: Units, Variables, and Information

**Guiding questions**

* What *is* data, conceptually?
* How do we get from raw measurements to “a dataset”?
* What’s the difference between data, information, and knowledge?

**Sub-units**

1. **Scene-setting: From measurements to recorded values**

   * Recap from Evidence course:

     * Measurement as assigning values to attributes of objects/events according to rules.
     * Reliability, validity, error (already introduced in “Evidence”).
   * Bring in *Measurement Across the Sciences* as a unifying view of measurement across physics, engineering, psychometrics, etc.([OAPEN Library][2])
   * Transition: those measurements become **recorded values** (numbers, categories, scores) in some information system; now we care about how they are *assembled* and used.

2. **What is data? Data vs information vs knowledge**

   * Data as *structured records* of measurements or observations on units.
   * Information as data *interpreted* relative to questions and background models.
   * Knowledge as more stable, justified patterns distilled from many datasets + theory.
   * Use examples from *Calling Bullshit* (e.g., “data-free” stories vs data-saturated but misleading dashboards).([Amazon][4])

3. **Units of analysis: “What are the things?”**

   * Define units of analysis (individuals, cells, households, firms, time points, countries, etc.).
   * Show how mis-chosen units distort inference (e.g., country-level averages as if each country were a person → ecological fallacies).([Amazon][4])
   * Link back to Evidence course: the “facts” we talk about are often aggregates over units—this matters.

4. **Scope and target populations: “What world are we talking about?”**

   * Target population vs “the universe of discourse”:

     * All adults in the US? Patients at this hospital in 2024? All trials on a drug?
   * Emphasize that population choice is a **scientific and ethical** decision, not automatic.
   * Connect to evidence hierarchies and EBM (whose population is “this guideline” about?).([Cochrane][8])

5. **Variables and data types**

   * Variables as attributes measured across units.
   * Distinguish:

     * Categorical (nominal, ordinal)
     * Quantitative (continuous, discrete, counts)
   * Light link to modeling: these will later determine what probability models are reasonable.

6. **Metadata and codebooks**

   * Introduce metadata and codebooks as the *narrative* of the dataset: variable definitions, units, coding schemes, missing-value codes, provenance.
   * Show an example of a good vs terrible codebook; tie to information literacy.([Amazon][4])

**Core readings**

* Luca Mari, Mark Wilson & Andrew Maul, *Measurement Across the Sciences: Developing a Shared Concept System for Measurement* (intro + conceptual chapters).([OAPEN Library][2])
* Theodore Porter, *Trust in Numbers: The Pursuit of Objectivity in Science and Public Life* (Introduction + “How Social Numbers Are Made Valid”).([Wikipedia][6])
* Carl Bergstrom & Jevin West, *Calling Bullshit: The Art of Skepticism in a Data-Driven World* (chapters on data, bullshit, and contexts of use).([Amazon][4])

---

## Unit 2 – Populations, Sampling, and Study Designs

**Guiding questions**

* How do we get from a conceptual population to the actual data we see?
* What is a sampling frame, and why does it matter more than “N”?
* How do different study designs (RCT, cohort, case-control, cross-sectional) structure data?

**Sub-units**

1. **Population vs sample: the core statistical move**

   * Population = conceptual set we care about.
   * Sample = units we *actually* observe.
   * Explain why most statistical reasoning is about using a sample to say something about a population.
   * Use *Seven Pillars of Statistical Wisdom* to highlight “aggregation” and “design” as central pillars.([Amazon][9])

2. **Sampling frames and real-world messiness**

   * Sampling frame = the operational list/mechanism (voter files, clinic rosters, websites, EHRs).
   * Talk about frame–population mismatch (e.g., phone surveys, online convenience panels).
   * Connect to selection bias, coverage error, nonresponse.([Amazon][4])

3. **Probability sampling designs (conceptual)**

   * Simple random sampling (SRS) as a benchmark.
   * Stratified sampling: ensuring coverage of key subgroups.
   * Cluster and multistage sampling: classrooms, villages, hospitals, etc.; design effects and intra-cluster correlation (conceptual, not formulaic).
   * Show how these designs appear in national surveys and epidemiological studies.([Amazon][4])

4. **Non-probability sampling and “found” data**

   * Convenience samples, snowball sampling, self-selected online surveys, platform logs and administrative data.
   * Emphasize: *large N does not cure bias* – a million self-selected users can be worse than 1,000 sampled carefully.
   * Bring examples from *Calling Bullshit* on “big data hubris”.([callingbullshit.org][10])

5. **Study designs: experiments vs observational studies**

   * Randomized controlled trials (RCTs), including CONSORT as a reporting standard.([SpringerLink][5])
   * Observational designs: cohort, case-control, cross-sectional; STROBE as a reporting standard.([Amazon][4])
   * Diagnostic/prognostic designs and STARD, briefly.([Amazon][4])
   * Use simple data diagrams (2×2 tables, timelines) to show what is observed in each design.

6. **From study design to evidence hierarchies**

   * Introduce hierarchies of evidence (systematic reviews/meta-analyses, RCTs, well-designed observational studies, case series, anecdotes).([Amazon][4])
   * Link to EBM and your previous Evidence unit: this is *why* people care about design.

**Core readings**

* Stephen K. Campbell, *Flaws and Fallacies in Statistical Thinking* (chapters on sampling and bias).([Amazon][11])
* Foster Provost & Tom Fawcett, *Data Science for Business* (chapters on data-analytic thinking and data provenance).([Amazon][12])
* CONSORT 2010/2025 statement; STROBE statement checklists.([Legacy File Share][13])
* Stanford Encyclopedia of Philosophy, “Simpson’s Paradox” (as a teaser for later causal issues).([Stanford Encyclopedia of Philosophy][7])

---

## Unit 3 – Errors, Biases, and the Texture of Uncertainty

**Guiding questions**

* What kinds of errors creep into data even before we run any model?
* How do sampling error and sampling bias differ?
* How do missing data, survivorship, and paradoxes (Simpson’s, ecological) distort our inferences?

**Sub-units**

1. **Sampling error vs sampling bias**

   * Sampling error: randomness from seeing only part of the population; shrinks with larger N.
   * Sampling bias: systematic distortion from who gets in the sample; does *not* shrink with N.
   * Precision vs accuracy: how tight vs how right.

2. **Measurement error and misclassification**

   * Random vs systematic measurement error (instrument drift, miscalibrated surveys).
   * Misclassification of outcomes or exposures (false positives/negatives, sensitivity/specificity).([Amazon][4])
   * Link back to metrology and *Measurement Across the Sciences*; forward to diagnostic testing in Unit 5.([OAPEN Library][2])

3. **Missing data and nonresponse**

   * Types of missingness (conceptually): missing completely at random, at random, not at random.
   * Nonresponse bias in surveys; missing lab values in clinical studies; attrition in longitudinal data.
   * Emphasize that missingness often hides a *secondary sampling process* (“who is invisible?”).

4. **Iconic statistical pathologies**

   * Simpson’s paradox: association reversals when conditioning on a lurking variable; highlight its causal reading and why “correlation ≠ causation” is not enough.([Stanford Encyclopedia of Philosophy][7])
   * Ecological fallacy (group-level vs individual-level associations).([Amazon][1])
   * Base-rate neglect / prosecutor’s fallacy in legal and forensic contexts.([Amazon][4])
   * Regression toward the mean and why many “treatments” appear to work just by timing.([Amazon][4])

5. **Information overload, filter bubbles, and selection into data streams**

   * Information overload and filter bubbles as *selection mechanisms* on what data we ever see.([Amazon][4])
   * Connect to Course 1’s social epistemology + echo chambers; connect to “Calling Bullshit” chapters on information streams.

**Core readings**

* Stephen K. Campbell, *Flaws and Fallacies in Statistical Thinking* (selection of chapters on sampling, selection, and misinterpretation).([Internet Archive][14])
* Darrell Huff, *How to Lie with Statistics* (with an instructor note on its historical context and limitations).([Amazon][15])
* Bergstrom & West, *Calling Bullshit* (chapters on selection bias, visual bullshit, and model errors).([callingbullshit.org][10])
* SEP “Simpson’s Paradox” and related overviews of ecological fallacy and survivorship bias.([Stanford Encyclopedia of Philosophy][7])

---

## Unit 4 – Describing and Visualizing Data: EDA and Graphics

**Guiding questions**

* How do we *look at* data before we model?
* What are summary statistics actually summarizing?
* How can graphics clarify—or distort—the story?

**Sub-units**

1. **Exploratory data analysis (EDA) as disciplined curiosity**

   * Tukey-style idea of EDA; looking at distributions, outliers, time trends, simple cross-tabs.
   * Data as “snapshot of the world” filtered through measurement and sampling.
   * Bridge to Abelson: descriptive statistics as part of a **principled argument** about the world, not just ritual reporting.([Routledge][3])

2. **Descriptive statistics: summaries, not truths**

   * Means, medians, proportions, quantiles, standard deviations, IQR, etc.
   * Emphasize:

     * They are summaries of the sample, *not* the population.
     * They are shaped by design decisions (who is in the sample, how variables are measured).

3. **Visualizing distributions, relationships, and uncertainty**

   * Histograms, density plots, boxplots, scatterplots, time-series plots.
   * Basic visual tools for uncertainty: error bars, confidence bands, fan charts (conceptual).
   * Introduce “uncertainty visualization” as a craft: how do we show what we *don’t* know?

4. **Tufte and the ethics of graphics**

   * Tufte’s principles: graphical integrity, data-ink ratio, small multiples, lie factor, etc.([Amazon][15])
   * Examples of deceptive graphics (truncated axes, cherry-picked time windows, junk charts).
   * Connect to Huff’s classic examples, and to Bergstrom & West on “visual bullshit”.([Horace][16])

5. **EDA as prelude to modeling, not fishing expedition**

   * Distinguish honest EDA from data dredging (p-hacking).
   * Connect forward to Unit 5 (inference and testing) and to the replication crisis.

**Core readings**

* Edward Tufte, *The Visual Display of Quantitative Information*, *Envisioning Information*, and *Beautiful Evidence* (selected chapters).([Amazon][15])
* Darrell Huff, *How to Lie with Statistics* (graphics-related chapters).([Amazon][15])
* Bergstrom & West, *Calling Bullshit* (chapters on visualization and misleading dashboards).([callingbullshit.org][10])

---

## Unit 5 – Probability, Inference, and Diagnostic Reasoning

**Guiding questions**

* What does it mean to say something is “likely” or “significant”?
* How do we reason with conditional probabilities and base rates?
* What can we legitimately infer from p-values, intervals, and diagnostic tests?

**Sub-units**

1. **Interpretations of probability**

   * Frequentist vs Bayesian vs propensity vs subjective interpretations (light touch).([Amazon][4])
   * How these interpretations show up in practice (weather forecasts, betting odds, clinical risk).

2. **Conditional probability, Bayes’ rule, and base rates**

   * Intuitive explanation of conditional probability and Bayes’ rule (e.g., frequency trees).
   * Base-rate neglect and the prosecutor’s fallacy in law and forensic evidence.([Amazon][4])
   * Use *The Signal and the Noise* to show real-world Bayesian-ish forecasting (weather, elections).([Amazon][17])

3. **Sensitivity, specificity, and predictive values**

   * Diagnostic testing:

     * Sensitivity, specificity, positive/negative predictive value, ROC curves (conceptually).([Amazon][4])
   * Confusion matrices and contingency tables as core representational tools.([Amazon][4])
   * Show how base rates radically affect PPV/NPV.

4. **Hypothesis testing and common misinterpretations**

   * Null hypothesis significance testing (NHST) in plain language; p-values as *compatibility* measures, not “the probability the null is true.”
   * Type I vs Type II errors; power as long-run behavior.([Amazon][4])
   * ASA statement on p-values and why over-reliance on “p<0.05” is problematic.([Default][18])

5. **Inference as argument, not ritual**

   * Abelson’s “Statistics as Principled Argument”: MAGIC criteria (magnitude, articulation, generality, interestingness, credibility).([Routledge][3])
   * Ioannidis, “Why Most Published Research Findings Are False,” and the replication crisis as institutional consequences of misused inference.([PMC][19])
   * Stigler’s *Seven Pillars* as a conceptual unification of statistical insight (likelihood, residuals, etc.).([Amazon][9])

6. **Judgment, heuristics, and decision making under uncertainty**

   * Draw from Jonathan Baron’s *Thinking and Deciding*: normative standards (probability, utility) vs descriptive heuristics and biases.([Amazon][20])
   * Connect back to Course 1 on cognitive biases; connect forward to Causality course (deciding when evidence is “good enough” to act).

**Core readings**

* Robert Abelson, *Statistics as Principled Argument*.([Routledge][3])
* Stephen M. Stigler, *The Seven Pillars of Statistical Wisdom* (overview chapters).([Amazon][9])
* Nate Silver, *The Signal and the Noise: Why So Many Predictions Fail—but Some Don’t*.([Amazon][17])
* American Statistical Association statements on p-values and selected essays on the replication crisis.([Default][18])
* Jonathan Baron, *Thinking and Deciding* (sections on probability judgment and decisions).([Cambridge University Press & Assessment][21])

---

## Unit 6 – Research Practice, Reporting, and Evidence Synthesis

**Guiding questions**

* How do good research practices make data interpretable?
* What do reporting guidelines (CONSORT, STROBE, PRISMA, GRADE) actually do?
* How do systematic reviews, meta-analyses, and replication fit into the data ecosystem?

**Sub-units**

1. **From research questions to protocols (PICO and beyond)**

   * PICO (Population, Intervention, Comparator, Outcome) and similar frameworks for structuring clinical and policy questions.([Amazon][4])
   * Study protocols (SPIRIT) and preregistration as ways of specifying the data plan in advance.([Amazon][4])

2. **Reporting guidelines as “structured metadata”**

   * CONSORT (trials), STROBE (observational), PRISMA (systematic reviews), STARD (diagnostic accuracy), CARE (case reports), AGREE (guidelines), etc.([SpringerLink][5])
   * EQUATOR network as a hub.
   * Treat checklists as **institutionalized expectations** about what data and analyses need to be made visible.

3. **Systematic reviews and meta-analysis**

   * Cochrane Handbook; PRISMA 2020 statement and flow diagrams.([Amazon][4])
   * Steps: searching, screening, risk-of-bias assessment, pooling, heterogeneity, sensitivity analyses (conceptual).
   * Discuss the *GRADE* approach to rating certainty of evidence and strength of recommendations.([gradeworkinggroup.org][22])

4. **Replication and reproducibility**

   * Conceptual difference:

     * Reproducibility (same data, same code).
     * Replicability (new data).
   * Use high-profile replication crisis examples (psychology, biomedicine) to show how data/analysis decisions propagate.
   * Discuss registration, open data/code, and reporting practices as infrastructure for data trust.

5. **Evidence-based practice and policy**

   * Evidence-based medicine and public health; BMJ EBM, Cochrane, and related initiatives.([Amazon][4])
   * Brownson et al., “Understanding Evidence-Based Public Health Policy” as a bridge between data, politics, and implementation.([American Journal of Public Health][23])
   * Illustrate “research translation” from data → systematic review → guideline → policy.

**Core readings**

* Cochrane Handbook for Systematic Reviews of Interventions (selected methods chapters).([Amazon][4])
* PRISMA 2020 statement and checklist.([BMJ][24])
* CONSORT 2010/2025 and STROBE statements.([Legacy File Share][13])
* GRADE Handbook / GRADE Book (introductory chapters).([Cochrane][8])
* Ross Brownson et al., “Understanding Evidence-Based Public Health Policy.”([American Journal of Public Health][23])

---

## Unit 7 – Data, Institutions, and Big-Data Ecosystems

**Guiding questions**

* What changes when we move from individual datasets to *data infrastructures*?
* How do institutions, incentives, and governance shape what gets measured and how?
* Why can big data *amplify* bias and uncertainty rather than eliminating them?

**Sub-units**

1. **From datasets to data ecosystems**

   * Contrast the “single study” perspective with:

     * Long-lived databases (EHRs, registries).
     * Platform data (social media, search logs, mobile tracking).
     * Multi-institution consortia and data commons.
   * Introduce Porter’s thesis in *Trust in Numbers*: quantification as a tool for bureaucratic legitimacy and “objective” decision-making.([Wikipedia][6])

2. **Provenance, governance, and accountability**

   * Provenance across pipelines:

     * Data collection institutions, transformations, linkages, and curation.
   * Governance: access, consent, regulation, ethical review, data protection.
   * Connect to evidence law and your Evidence course (e.g., chain of custody, admissibility, forensic databases).

3. **Metadata, ontologies, and interoperability**

   * Large-scale projects depend on shared vocabularies and ontologies (e.g., gene ontologies, clinical vocabularies) to make data interoperable.
   * Show how ontologies *encode assumptions* about the world (what counts as a disease, an event, a “case”).
   * Connect back to conceptual engineering from Course 1 and to Measurement/Mari–Wilson–Maul: categories as measurement decisions.([OAPEN Library][2])

4. **Big data vs designed data**

   * Hypothesis-driven experiments vs data-driven discovery, machine learning on large observational corpora.
   * “N = All?” fallacy: big but biased data can be worse than small, carefully designed samples.
   * Draw examples from *Data Science for Business* and *Calling Bullshit* on predictive systems, recommendation engines, and platform metrics.([Google Books][25])

5. **Uncertainty at scale: new risks, new tools**

   * Algorithmic bias, covariate shift, data leakage, feedback loops.
   * Documentation and monitoring practices (e.g., model/data cards) as analogues of CONSORT/PRISMA for models.
   * Connect to forthcoming Causality course: big data does not automatically yield causal knowledge; in fact, it can obscure causal structure without careful design.

6. **Sociology and history of quantification**

   * Use *Trust in Numbers* for a historical view of how different fields came to rely on numbers for legitimacy.([Wikipedia][6])
   * Connect to your earlier work on epistemic injustice: whose experiences are captured in datasets, whose are rendered invisible?

**Core readings**

* Theodore Porter, *Trust in Numbers: The Pursuit of Objectivity in Science and Public Life*.([Wikipedia][6])
* Mari, Wilson & Maul, *Measurement Across the Sciences* (chapters on modeling, quality, and public trust in measurement).([OAPEN Library][2])
* Bergstrom & West, *Calling Bullshit* (chapters on big data, algorithmic decision-making, and institutional bullshit).([callingbullshit.org][10])
* Selected papers or essays on data governance, ontologies, and research infrastructures (you could plug in domain-specific readings here).

---

## Possible capstone activities

* **Data Lifecycle Case Study**

  Students choose a real dataset or published study (e.g., a clinical trial, a policy report, or a big-platform dataset) and:

  * Reconstruct the **data lifecycle**:

    * Question → population → sampling frame → sampling design → measurement → dataset → analysis → reporting.
  * Identify sources of **uncertainty and bias** at each step (sampling, measurement, missingness, analysis).
  * Map **EDA and visualization** practices used, and critique them with Tufte/Huff/Bergstrom’s tools.
  * Reinterpret the statistical analysis as a **principled argument** (Abelson’s MAGIC criteria).
  * Connect to **evidence synthesis** (How would this feed into a systematic review? What would PRISMA/CONSORT/STROBE demand?) and to **big-data ecosystems** if relevant (e.g., how the data might be reused).

* **Mini-capstone: Debunking a Quantitative Claim**

  * Each group selects one public quantitative claim (news graphic, op-ed, policy brief, viral statistic, or dashboard).
  * They:

    * Trace the likely **data generating and sampling process**.
    * Identify at least two plausible **sources of bias or uncertainty**.
    * Build an alternative **visualization or summary** that better represents the uncertainty.
    * Write a short, public-facing memo explaining the issue, drawing explicitly on *Calling Bullshit*, Huff, and Campbell.

---

[1]: https://www.amazon.com/Beautiful-Evidence-Edward-R-Tufte/dp/1930824165 "Beautiful Evidence: Edward R. Tufte: 9781930824164"
[2]: https://library.oapen.org/bitstream/id/a3b419e3-c022-4a84-b07e-bac400ed28db/978-3-031-22448-5.pdf "Measurement Across the Sciences"
[3]: https://www.routledge.com/Statistics-As-Principled-Argument/Abelson/p/book/9780805805284 "Statistics As Principled Argument - 1st Edition"
[4]: https://www.amazon.com/Calling-Bullshit-Skepticism-Data-Driven-World/dp/0525509186 "Calling Bullshit: The Art of Skepticism in a Data-Driven World"
[5]: https://bmcmedicine.biomedcentral.com/articles/10.1186/1741-7015-8-18 "CONSORT 2010 Statement: updated guidelines for reporting ..."
[6]: https://en.wikipedia.org/wiki/Trust_in_Numbers "Trust in Numbers"
[7]: https://plato.stanford.edu/entries/paradox-simpson/ "Simpson's Paradox - Stanford Encyclopedia of Philosophy"
[8]: https://www.cochrane.org/learn/courses-and-resources/cochrane-methodology/grade-approach/grade-handbook "GRADE Handbook"
[9]: https://www.amazon.com/Seven-Pillars-Statistical-Wisdom/dp/0674088913 "The Seven Pillars of Statistical Wisdom"
[10]: https://callingbullshit.org/ "Calling Bullshit."
[11]: https://www.amazon.com/Flaws-Fallacies-Statistical-Thinking-Mathematics/dp/0486435989 "Flaws and Fallacies in Statistical Thinking (Dover Books on ..."
[12]: https://www.amazon.com/Data-Science-Business-Data-Analytic-Thinking/dp/1449361323 "Data Science for Business: What You Need to Know about ..."
[13]: https://legacyfileshare.elsevier.com/promis_misc/CONSORT-2010-Checklist.pdf "CONSORT 2010 Checklist"
[14]: https://archive.org/details/flawsfallaciesin0000camp "Flaws and fallacies in statistical thinking"
[15]: https://www.amazon.com/How-Lie-Statistics-Darrell-Huff/dp/0393310728 "How to Lie with Statistics: 9780393310726 - Darrell Huff"
[16]: https://www.horace.org/blog/wp-content/uploads/2012/05/How-to-Lie-With-Statistics-1954-Huff.pdf "How-to-Lie-With-Statistics-1954-Huff"
[17]: https://www.amazon.com/Signal-Noise-Many-Predictions-Fail-but/dp/0143125087 "The Signal and the Noise: Why So Many Predictions Fail- ..."
[18]: https://www.amstat.org/asa/files/pdfs/p-valuestatement.pdf "p-valuestatement.pdf"
[19]: https://pmc.ncbi.nlm.nih.gov/articles/PMC1182327/ "Why Most Published Research Findings Are False - PMC"
[20]: https://www.amazon.com/Thinking-Deciding-4th-Jonathan-Baron/dp/0521680433 "Amazon.com: Thinking and Deciding, 4th Edition"
[21]: https://www.cambridge.org/highereducation/books/thinking-and-deciding/5EA7EBEACA950A41646043CBC4D04886 "Thinking and Deciding | Cambridge Aspire website"
[22]: https://www.gradeworkinggroup.org/ "GRADE home"
[23]: https://ajph.aphapublications.org/doi/pdf/10.2105/AJPH.2008.156224 "Understanding Evidence-Based Public Health Policy"
[24]: https://www.bmj.com/content/372/bmj.n71 "The PRISMA 2020 statement: an updated guideline for ..."
[25]: https://books.google.com/books?id=4ZctAAAAQBAJ&printsec=frontcover&utm_source=chatgpt.com "Data Science for Business: What You Need to Know about ..."
