---
layout: page
title: Project
description: >-
    Course policies and information.
---

# Course project

All students in the class will write a "mini-paper" as a final project, which can be empirical, theoretical, or both. Students should write up the results in the [NeurIPS conference format](https://media.neurips.cc/Conferences/NeurIPS2025/Styles.zip).

## Working in groups
- Students are welcome to work in groups on the final project.
- Groups should include at most three students (except with special permission).
- I will expect a group of two students to put twice as much work into the final project than for a sole-author project, and similarly for groups of three.
- Students in groups are required to include a “contributions” paragraph in their paper that concretely lists each author's contributions.
- The paper length for a final project write-up is 3 + n where n is the number of people in the group that worked on the project, not including references or the contributions paragraph.

## Milestones
- **October 12**: Each student will add information about topics they find interesting to a project matching spreadsheet.
- **October 31**: Each group will submit a short progress report of 1-2 pages. Describe your project and partial progress. Your writeup should include answers (implicitly or explicitly) to the following simplified version of the [Heilmeier Catechism](https://stanfordh4d.substack.com/p/technology-transfer-for-defense-leveraging):
  - What are you trying to do?
  - How is it done today, and what are the limitations?
  - What’s new in your idea, and why might it succeed?
  - If successful, what difference will it make?
  - What’s the first thing you will try or have already tried to test the idea? Include any initial progress you've made so far.
- **December 4**: Each group will present their final project during class.
- **December 12**: Each group will submit their final report.

## Grading rubric
- **Project matching spreadsheet**: 3 points.
- **Progress report**: 7 points.

### Final project grading
#### Course relevance

Naturally, the project must be clearly about AI for algorithmic reasoning & optimization. Projects **not related to the course will receive 0 of the 30 project points** (this would be like turning in your physics problem set to your literature course and expecting credit).

**Examples of in-scope topics (by lecture alignment):**
- Algorithmic reasoning as a lens to understand ML models (aligns with **10/7–10/16** lectures)
- ML for graph/constraint/NP-hard problems (aligns with **10/21–10/30**)
- Learning to formalize optimization problems (aligns with **11/6**)
- ML to guide/configure solvers (aligns with **11/11, 11/13**)
- Theoretical guarantees for learned algorithms/heuristics (aligns with **11/18, 11/20**)


#### Final paper: Novelty & insight (10 pts)

##### Originality (3 points)
**Examples include:**
- New algorithm or heuristic  
- New theoretical result  
- New problem formulation/evaluation/analysis protocol or benchmark  
- New combination of known elements that yields a surprising conceptual advance

**Scoring examples**
- **3:** Clear, defensible novelty claim and strong evidence for it.
- **2:** Incremental extension with some new idea (e.g., small twist on an existing approach) or new benchmark without sharp insight.
- **1:** Minor variation/ablation; weak distinction from prior work.
- **0:** No identifiable novelty.

##### Depth of analysis (3 points)
**Depth tools include:**
- Ablations isolating methodological components  
- Fair baselines/metrics (e.g., both classical and learned methods)  
- Generalization tests (e.g., out-of-distribution instances)  
- Counterexamples/failure modes

**Scoring examples**
- **3:** Relevant depth tools above are executed well; clear explanation of what drove gains/losses; limitations surfaced.
- **2:** Some depth but gaps (e.g., missing ablation or weak baselines).
- **1:** Superficial analysis without any depth example executed well; results reported without any interpretation.
- **0:** No analysis beyond raw outcomes.

##### Potential impact (2 points)
**Impact can be:**
- **Practical:** improves solution quality/gap, runtime, etc.  
- **Scientific:** clarifies when/why learned components help or fail; new phenomena uncovered.  
- **Methodological:** benchmark/metric/protocol that others can reuse; clean baselines that become reference points.

**Scoring examples**
- **2:** Clear, well-argued value.
- **1:** Some value but narrow or not well substantiated.
- **0:** Unclear who benefits or how.

##### Future work (2 points)
- **1:** Specific 2–3 steps (e.g., “extend proof from bipartite to general graphs by doing X; likely obstacle: lemma Y likely fails,” or “integrate with Gurobi; likely obstacle: distribution shift”).
- **0:** Vague or no future work.

---

#### Final paper: Writing & completeness (10 pts)

Any hallucinated reference results in an automatic 0/10 for this section. “Hallucinated” includes any citation that cannot be verified or that misrepresents bibliographic details, i.e., incorrect title, author list, venue, or year. Citing arXiv is fine, although if the paper appeared in a conference/journal, that reference is preferable.

##### Structure & formatting
**Scoring examples**
- **2:** NeurIPS format followed; within 3 + n pages (refs/contributions not counted); clear sectioning; contributions paragraph (if applicable) present and specific.
- **1:** Vague contributions paragraph.
- **0:** Major non-compliance (e.g., egregious length, missing core sections).

##### Problem formulation & scope (2 points)
**Scoring examples**
- **2:** Precise problem/task definition, assumptions, objectives, and evaluation setup. Terms defined on first use.
- **1:** Mostly clear but some missing assumptions or ambiguous setup.
- **0:** Unclear task/scope; reader cannot tell what is being solved or proved.

##### Context & related work (quality, not novelty) (2 points)
**Scoring examples**
- **2:** Concise positioning; citations accurate and sufficient; clear where previous methods have fallen short.
- **1:** Coverage OK but thin. Not clear where previous methods have fallen short.
- **0:** Missing/very weak context.

##### Exposition & readability (2 points)
- **2:** Clear narrative; consistent notation; figures/tables are legible, labeled, and referenced in text.
- **1:** Understandable but with jargon jumps, undefined symbols, or hard-to-read figures.
- **0:** Disorganized; figures illegible; heavy copy-pasting of math without explanation.

##### Reproducibility & artifacts (2 points)
Examples of include:
**Empirical:** runnable code+configs (e.g., public repo or share a private repo with Ellen — GitHub handle **vitercik** — and Yunzhi — GitHub handle **zzyunzhi**); data sources/creation, instance seeds, train/val/test splits, metrics, hardware, hyperparams. It should be clear how to reproduce each table/figure.  
**Theoretical:** complete proofs (appendix allowed), statement of assumptions; auxiliary lemmas included or cited with exact location.

**Scoring examples**
- **2:** Meets the above; readers can reproduce or check results/proofs.
- **1:** Partially reproducible (missing seeds/configs/proof details).
- **0:** Not reproducible; key details missing.

#### Final Presentation (10 pts)

##### Problem & context (2 points)
**Scoring examples**
- **2:** Plain-English problem statement, audience-appropriate context, course fit is explicit.
- **1:** Mostly clear, minor jargon/assumption jumps.
- **0:** Hard to tell what the talk is about or why it belongs here.

##### Method/contributions (3 points)
**Scoring examples**
- **3:** Approaches explained at the right level (diagrams, small example), key choices/assumptions surfaced, notation defined on first use.
- **2:** Understandable but skips a few definitions.
- **1:** Heavy jargon or slide-reading; audience must infer key steps.
- **0:** Method/evidence largely unexplained.

##### Interpretation and takeaways (3 points)
**Scoring examples**
- **3:** Concise “so-what,” limitations/assumptions stated, fair comparison framing (what was/wasn’t tested or proved).
- **2:** Main message present but caveats thin or buried.
- **1:** Numbers/theorems shown with little interpretation.
- **0:** No takeaways beyond raw results.

##### Visuals & structure (2 points)
**Scoring examples**
- **2:** Clean slides (e.g., aim for ≥24pt fonts, consistent notation), one idea per slide, confident delivery (not reading from a script), on time (±30s), handles Q&A well.
- **1:** Minor readability or pacing issues; slight over/underrun (≤1 min).
- **0:** Illegible figures/text, >1 min over, or unable to field basic questions.