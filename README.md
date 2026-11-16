# Poorva Barve

I study how to evaluate AI agents when the specifications, data definitions, or benchmarks they rely on are unreliable. I’m applying to PhD programs for Fall 2027.

[ORCID](https://orcid.org/0009-0009-0312-4125) · [LinkedIn](https://www.linkedin.com/in/poorvabarve/) · [Email](mailto:poorvabarve@gmail.com)

## Independent research

### When the Semantic Layer Is Wrong

I ran 1,512 single-turn text-to-SQL trials across three LLMs using 24 controlled faults in an Apache Ossie semantic layer. The models had no access to tools during the trials. Models followed plausible but incorrect business definitions in 46–73% of trials, and pooled accuracy fell 26 percentage points below the no-layer baseline.

[Preprint](https://doi.org/10.5281/zenodo.23940769) · [Code and results](https://github.com/barveP/semantic-layer-trust-paper)

### How Much Does a Parity Experiment Prove?

I analyzed 58 published comparisons between original and ported benchmarks in Harbor, the evaluation framework behind Terminal-Bench. The range-overlap rule passed 57 comparisons, including one with a 15.6-point gap. Only 22 comparisons showed equivalence within 3 points. Under review at the AGENT workshop at ICSE 2027.

[Preprint](https://doi.org/10.5281/zenodo.24075880) · [Code and results](https://github.com/barveP/benchmark-port-parity-study)

### Specification drift

I’m studying how implementation changes can leave accepted requirements stale and whether automated checks can flag that drift during code review.

## Open-source contributions

- **Apache Ossie.** Fixed semantic model parsing, serialization, and conversion bugs that could silently change metric definitions. Four merged pull requests. [#618](https://github.com/apache/ossie/pull/618) · [#388](https://github.com/apache/ossie/pull/388) · [#377](https://github.com/apache/ossie/pull/377) · [#619](https://github.com/apache/ossie/pull/619)
- **pytest.** Fixed doctest flags leaking between docstrings and made cache write failures emit warnings. Two merged pull requests. [#15033](https://github.com/pytest-dev/pytest/pull/15033) · [#15044](https://github.com/pytest-dev/pytest/pull/15044)
- **OpenHands.** Proposed changes to preserve symlinks during file edits and reject invalid UTF-8 before writing. Two open pull requests. [#5097](https://github.com/OpenHands/software-agent-sdk/pull/5097) · [#5109](https://github.com/OpenHands/software-agent-sdk/pull/5109)

## Teaching

I was a graduate teaching assistant at Northeastern University in 2025. For **CS 3500 Object-Oriented Design**, I ran Java labs for 28 students, graded assignments, and held office hours. For **CS 4973 Cloud Computing**, I designed a three-tier AWS lab and graded labs and assignments for a class of 39.

## Selected projects

- **Oral cancer gene expression classifier.** Compared classifiers for distinguishing oral squamous cell carcinoma from normal tissue using public GEO microarray data. [Repository](https://github.com/barveP/oral-cancer-gene-expression-classifier)
- **Oral microbiome analysis.** Built a Python and R pipeline for exploring periodontal microbiome diversity using simulated abundance data. [Repository](https://github.com/barveP/oral-microbiome-analysis)
- **Chat with Data.** Built a Slack integration for Snowflake Cortex that returns the generated SQL and full results alongside answers. [Repository](https://github.com/barveP/Snowflake-Cortex-Slack-Integration)

I earned an M.S. in Computer Science from Northeastern University in 2026 and worked as a dentist before moving into computer science.
