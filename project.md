---
layout: page
title: Project
description: Course policies and information.
---


# Course project

- TOC
{:toc}

All students will write a **mini-paper** as a final project—empirical, theoretical, or both—using the
[NeurIPS conference format](https://media.neurips.cc/Conferences/NeurIPS2025/Styles.zip).

## Working in groups
- You may work solo or in groups of **up to three** (special permission required to exceed).
- Effort scales with team size (2× for two authors; 3× for three).
- Include a **contributions paragraph** naming each author’s concrete contributions.
- Paper length is **3 + *n*** pages (where *n* = group size), **excluding** references and the contributions paragraph.

## Milestones

| Date        | Deliverable | Points |
|-------------|-------------|-------------|
| **Oct 12**  | Project matching spreadsheet | 3 points |
| **Oct 31**  | 1–2 page progress report | 7 points |
| **Dec 4**   | In-class presentation | 10 points |
| **Dec 12**  | Final report | 20 points |

---
## Project matching spreadsheet (3 pts)

Each student will add information about topics they find interesting to a project matching spreadsheet. The course staff won't match students, but the goal is that this process will help students find others with similar interests.

---

## Progress report (7 pts)

Each group will submit a short progress report of 1-2 pages. Describe your project and partial progress. Your writeup should include answers (implicitly or explicitly) to the following simplified version of the [Heilmeier Catechism](https://stanfordh4d.substack.com/p/technology-transfer-for-defense-leveraging):
- What are you trying to do?
- How is it done today, and what are the limitations?
- What’s new in your idea, and why might it succeed?
- If successful, what difference will it make?
- What’s the first thing you will try or have already tried to test the idea? Include any initial progress you've made so far.

---

## Final project grading: Course relevance
The final project is graded out of 30 points (10 for the in-class presentation and 20 for the final report). Naturally, the project must be clearly about AI for algorithmic reasoning & optimization. Projects **not related to the course will receive 0 of the 30 final project points**.

In-scope examples include:
- Algorithmic reasoning as a lens to understand ML models (aligning with the lectures from **10/7–10/16**)
- ML for graph/constraint/NP-hard problems (aligning with lectures **10/21–10/30**)
- Learning to formalize optimization problems (aligning with lecture **11/6**)
- ML to guide/configure solvers (aligning with lectures **11/11, 11/13**)
- Theoretical guarantees for learned algorithms/heuristics (aligning with lectures **11/18, 11/20**)

You will receive feedback about whether your project is in-scope when you turn in your progress report and will have the opportunity to turn in a revision if not.

---

## Final paper: Novelty & insight (10 pts)

### Originality (3 pts)

Examples include:
- New algorithm or heuristic
- New theoretical result
- New problem formulation/evaluation/analysis protocol or benchmark
- New combination of known elements that yields a surprising result

| Score | Description |
|---:|---|
| **3** | Clear novelty with strong supporting evidence. |
| **2** | Straight-forward extension of an existing idea. |
| **1** | Minor variation/ablation; weak distinction from prior work. |
| **0** | No identifiable novelty. |

### Depth of analysis (3 pts)

You should include a coherent analysis that explains how and why your idea works or fails. Tools to illustrate depth include:
- Ablations isolating methodological components
- Fair baselines/metrics (e.g., both classical and learned methods)
- Generalization tests (e.g., out-of-distribution instances)
- Thorough proofs
- Counterexamples/failure modes (e.g., why a hypothesized theorem doesn't hold)
(Not all depth tools will be relevant to all projects.)

| Score | Description |
|---:|---|
| **3** | Relevant depth tools executed well. |
| **2** | Some depth but gaps (e.g., missing ablation or weak baselines). |
| **1** | Superficial analysis; results reported with little interpretation. |
| **0** | No analysis beyond raw outcomes. |

### Potential impact (2 pts)

It should be clear who benefits from your contributions and how. Impact can come in many different forms, including:
- **Methodolgical:** E.g., improves solution quality/gap, runtime, etc.
- **Theoretical:** E.g., clarifies when/why learned components help or fail.

| Score | Description |
|---:|---|
| **2** | Clear, well-argued value to a broader community. |
| **1** | Some value but narrow or under-substantiated. |
| **0** | Unclear who benefits or how. |

### Future work (2 pts)

Include specific, realistic next steps.

| Score | Description |
|---:|---|
| **2** | Specific 2–3 next steps. |
| **1** | Plausible but high-level ideas with limited detail. |
| **0** | Vague or no future work. |

---

## Final paper: Writing & completeness (10 pts)

**Any hallucinated reference will result in 0 out of 10 points for this section.** “Hallucinated” includes any citation that cannot be verified or misrepresents bibliographic details (incorrect title, author list, venue, or year). Citing arXiv is fine, but if the paper appeared in a conference/journal, it's preferable to cite the conference/journal version.

### Structure & formatting (2 pts)

Your report should comply with the required structure.

| Score | Description |
|---:|---|
| **2** | NeurIPS format; within 3 + n pages (references/contributions excluded); clear sectioning; specific contributions paragraph (if applicable). |
| **1** | Slightly under length; contributions paragraph vague. |
| **0** | Major non-compliance with formatting instructions. |

### Problem formulation (2 pts)

It should be clear exactly what problem you solved and under what assumptions.

| Score | Description |
|---:|---|
| **2** | Precise definitions, assumptions, objectives, and evaluation setup (if applicable). |
| **1** | Mostly clear but some missing assumptions/ambiguity. |
| **0** | Unclear scope; it’s not obvious what is solved or proved. |

### Related work (2 pts)

The report should have accurate positioning and proper attribution.

| Score | Description |
|---:|---|
| **2** | Accurate/sufficient citations; clear where prior methods fall short. |
| **1** | Coverage OK but thin; shortcomings of prior work unclear. |
| **0** | Missing or very weak context. |

### Readability (2 pts)

The writing, notation, and figures should be clear.

| Score | Description |
|---:|---|
| **2** | Clear narrative; consistent notation; legible, labeled figures/tables referenced in text. |
| **1** | Understandable but with jargon jumps/undefined symbols or hard-to-read figures. |
| **0** | Disorganized; illegible figures; math without explanation. |

### Reproducibility (2 pts)

The reader should be able to re-run your experiments or verify your proofs. Examples include:
- **Empirical:** runnable code + configs (public repo or share privately with the course staff's GitHub handles **vitercik** and **zzyunzhi**); data sources/creation, seeds, splits, metrics, hardware, hyperparams; clear how to reproduce each table/figure.  
- **Theoretical:** complete proofs (appendix allowed); assumptions stated; auxiliary lemmas included or cited clearly (e.g., Lemma 3.5 by Vitercik et al., '25).

| Score | Description |
|---:|---|
| **2** | Readers can reproduce or check results/proofs. |
| **1** | Partially reproducible (e.g., missing seeds/configs/proof details). |
| **0** | Not reproducible; key details missing. |

---

## Final presentation (10 pts)

### Problem & context (3 pts)

It should be clear exactly what problem you solved.


| Score | Description |
|---:|---|
| **3** | Plain-English problem statement with sufficient context for the audience to follow. |
| **2** | Mostly clear; minor jargon/assumption jumps. |
| **1** | Major use of jargon. |
| **0** | Totally unclear what the talk is about or why it belongs here. |

### Method (3 pts)

Your method should be clearly explained.

| Score | Description |
|---:|---|
| **3** | Right level of explanation; key definitions/assumptions mentioned; notation defined on first use. |
| **2** | Understandable but skips a few definitions. |
| **1** | Heavy jargon; key steps left implicit. |
| **0** | Method/evidence largely unexplained. |

### Takeaways of results (2 pts)

The "so-what" should be clear, as should the potential impact.

| Score | Description |
|---:|---|
| **2** | Clear “so-what” and interpretation of the results. |
| **1** | Numbers/theorems with little interpretation. |
| **0** | No takeaways beyond raw results. |

### Delivery (2 pts)

Emphasize slide readability, pacing, timing, and Q&A.

| Score | Description |
|---:|---|
| **2** | Clean slides (large fonts, consistent notation); one idea per slide; confident delivery (not script-reading); on time (±30s); handles Q&A well. |
| **1** | Minor readability/pacing issues; slight over/underrun (≤1 min). |
| **0** | Illegible figures/text; >1 min over; unable to answer basic questions. |
