---
layout: page
title: Project
description: Course policies and information.
---

# Course project

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
## Project matching spreadsheet

Each student will add information about topics they find interesting to a project matching spreadsheet. The course staff won't match students, but the goal is that this process will help students find others with similar interests.

## Progress report

Each group will submit a short progress report of 1-2 pages. Describe your project and partial progress. Your writeup should include answers (implicitly or explicitly) to the following simplified version of the [Heilmeier Catechism](https://stanfordh4d.substack.com/p/technology-transfer-for-defense-leveraging):
- What are you trying to do?
- How is it done today, and what are the limitations?
- What’s new in your idea, and why might it succeed?
- If successful, what difference will it make?
- What’s the first thing you will try or have already tried to test the idea? Include any initial progress you've made so far.

## Final project grading

> ### Course relevance
> Projects must clearly center on **AI for algorithmic reasoning & optimization**.  
> Work **not related to the course will receive 0/30 project points**.
>
> In-scope examples (by lecture alignment):
> - Algorithmic reasoning as a lens to understand ML models (**10/7–10/16**)
> - ML for graph/constraint/NP-hard problems (**10/21–10/30**)
> - Learning to formalize optimization problems (**11/6**)
> - ML to guide/configure solvers (**11/11, 11/13**)
> - Theoretical guarantees for learned algorithms/heuristics (**11/18, 11/20**)

### Final paper: Novelty & insight (10 pts)

#### Originality (3 pts)
Examples include:
- New algorithm or heuristic
- New theoretical result
- New problem formulation/evaluation/analysis protocol or benchmark
- New combination of known elements that yields a surprising conceptual advance

| Score | Description |
|---:|---|
| **3** | Clear, defensible novelty claim with strong supporting evidence. |
| **2** | Incremental extension with some new idea, or a new benchmark without sharp insight. |
| **1** | Minor variation/ablation; weak distinction from prior work. |
| **0** | No identifiable novelty. |

#### Depth of analysis (3 pts)
Tools to illustrate depth include:
- Ablations isolating methodological components
- Fair baselines/metrics (e.g., both classical and learned methods)
- Generalization tests (e.g., out-of-distribution instances)
- Counterexamples/failure modes

| Score | Description |
|---:|---|
| **3** | Relevant depth tools executed well; clear explanation of what drove gains/losses; limitations surfaced. |
| **2** | Some depth but gaps (e.g., missing ablation or weak baselines). |
| **1** | Superficial analysis; results reported with little interpretation. |
| **0** | No analysis beyond raw outcomes. |

#### Potential impact (2 pts)
Impact can be:
- **Practical:** improves solution quality/gap, runtime, etc.
- **Scientific:** clarifies when/why learned components help or fail; new phenomena uncovered.
- **Methodological:** benchmark/metric/protocol that others can reuse; clean baselines that become reference points.

| Score | Description |
|---:|---|
| **2** | Clear, well-argued value to a broader community. |
| **1** | Some value but narrow or under-substantiated. |
| **0** | Unclear who benefits or how. |

#### Future work (2 pts)
| Score | Description |
|---:|---|
| **2** | Specific 2–3 next steps with success criteria and known obstacles. |
| **1** | Plausible but high-level ideas with limited detail. |
| **0** | Vague or no future work. |

---

## Final paper: Writing & completeness (10 pts)

> ### Reference integrity
> **Any hallucinated reference ⇒ 0/10 for this section.**  
> “Hallucinated” includes any citation that cannot be verified or misrepresents bibliographic details (incorrect title, author list, venue, or year).  
> Citing arXiv is fine, but if the paper appeared in a conference/journal, it's preferable to cite the conference/journal version.

#### Structure & formatting (2 pts)
| Score | Description |
|---:|---|
| **2** | NeurIPS format; within 3 + n pages (references/contributions excluded); clear sectioning; specific contributions paragraph (if applicable). |
| **1** | Slightly under length; contributions paragraph vague. |
| **0** | Major non-compliance with formatting instructions. |

#### Problem formulation & scope (2 pts)
| Score | Description |
|---:|---|
| **2** | Precise task definition, assumptions, objectives, and evaluation setup; terms defined on first use. |
| **1** | Mostly clear but some missing assumptions/ambiguity. |
| **0** | Unclear scope; it’s not obvious what is solved or proved. |

#### Context & related work (quality, not novelty) (2 pts)
| Score | Description |
|---:|---|
| **2** | Concise positioning vs. closest work; accurate/sufficient citations; clear where prior methods fall short. |
| **1** | Coverage OK but thin; shortcomings of prior work unclear. |
| **0** | Missing or very weak context. |

#### Exposition & readability (2 pts)
| Score | Description |
|---:|---|
| **2** | Clear narrative; consistent notation; legible, labeled figures/tables referenced in text. |
| **1** | Understandable but with jargon jumps/undefined symbols or hard-to-read figures. |
| **0** | Disorganized; illegible figures; math pasted without explanation. |

#### Reproducibility & artifacts (2 pts)
Examples include:
**Empirical:** runnable code + configs (public repo or share privately with the course staff's GitHub handles **vitercik** and **zzyunzhi**); data sources/creation, seeds, splits, metrics, hardware, hyperparams; clear how to reproduce each table/figure.  
**Theoretical:** complete proofs (appendix allowed); assumptions stated; auxiliary lemmas included or cited clearly (e.g., Lemma 3.5 by Vitercik et al., '25).

| Score | Description |
|---:|---|
| **2** | Readers can reproduce or check results/proofs. |
| **1** | Partially reproducible (e.g., missing seeds/configs/proof details). |
| **0** | Not reproducible; key details missing. |

---

## Final presentation (10 pts)

#### Problem & context (2 pts)
| Score | Description |
|---:|---|
| **2** | Plain-English problem statement; audience-appropriate context. |
| **1** | Mostly clear; minor jargon/assumption jumps. |
| **0** | Unclear what the talk is about or why it belongs here. |

#### Method/contributions (3 pts)
| Score | Description |
|---:|---|
| **3** | Right level of explanation; key choices/assumptions surfaced; notation defined on first use. |
| **2** | Understandable but skips a few definitions. |
| **1** | Heavy jargon or slide-reading; key steps left implicit. |
| **0** | Method/evidence largely unexplained. |

#### Interpretation & takeaways (3 pts)
| Score | Description |
|---:|---|
| **3** | Clear “so-what”; limitations/assumptions stated; fair comparison framing (what was/wasn’t tested or proved). |
| **2** | Main message present but caveats thin/buried. |
| **1** | Numbers/theorems with little interpretation. |
| **0** | No takeaways beyond raw results. |

#### Visuals & structure (2 pts)
| Score | Description |
|---:|---|
| **2** | Clean slides (aim for large fonts, consistent notation); one idea/slide; confident delivery (not script-reading); on time (±30s); handles Q&A well. |
| **1** | Minor readability/pacing issues; slight over/underrun (≤1 min). |
| **0** | Illegible figures/text; >1 min over; unable to answer basic questions. |
