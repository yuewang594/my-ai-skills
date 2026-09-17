# Accelerated L6 / Staff Product Data Scientist Interview Curriculum

## Calendar Anchor

Treat **August 31, 2026 through September 6, 2026 as Week 1**.

Week mapping:
- Week 1: Aug 31–Sep 6
- Week 2: Sep 7–Sep 13
- Week 3: Sep 14–Sep 20
- Week 4: Sep 21–Sep 27
- Week 5: Sep 28–Oct 4
- Week 6: Oct 5–Oct 11
- Week 7: Oct 12–Oct 18
- Week 8: Oct 19–Oct 25

Primary goal: **interview-ready by the end of Week 8**.

Material previously planned for Weeks 9–12 is compressed into Weeks 4–8 through integrated code review, full experiment-analysis cases, scale/performance reasoning, and weekend interview simulations.

## Weekly Curriculum

| Week | Statistics / Experimentation Companion | Python / Pandas | L6 Product / Technical Case | Measurable Milestone |
|---|---|---|---|---|
| 1 | Probability foundations | Python data structures, functions, comprehensions, mutability, sorting | Metric definition | Complete 3 realistic code reviews |
| 2 | Sampling / CI intuition | NumPy arrays, indexing, masks, broadcasting, vectorization | Metric trees / guardrails | ≥4/5 on 3 NumPy reviews |
| 3 | Hypothesis testing / ITT / ratio-metric context | Pandas filtering, Boolean masks, groupby, agg, transform, apply, analysis grain | A/B analysis implementation | Catch ≥80% planted Pandas/data-grain bugs |
| 4 | Randomization/exposure/SRM context | Joins, merge cardinality, duplicates, null keys, unmatched rows, validation assertions; assignment-event joins | Diagnose broken experiment code | 45–60 min technical mock ≥18/25 |
| 5 | Sequential/time-window context | Datetime, attribution windows, cohorts, retention, partial periods, time zones, late-arriving data; reshape/window operations | Conflicting metric implementation | Solve 2 attribution/cohort reviews without hints |
| 6 | Ratio/CUPED/experiment context | Event→user aggregation, conversion, retention, ratio metrics, deduplication, exposure, leakage, weighted vs unweighted metrics | Payments / marketplace metric implementation | Build robust analysis plan + code outline in ≤20 min |
| 7 | Causal/confounding context | Performance and scale: vectorization, apply, memory, large joins, copies/views, chunking, complexity, assertions, 100M-row reasoning | Production-grade analytical review | Independently prioritize correctness vs performance issues |
| 8 | Integrated experimentation context | Full AI-generated code critique combining Python/Pandas/NumPy, experiment implementation, metrics, data quality, joins, time windows, performance, and validation | Full L6 technical case | 3 realistic mocks around 21–22+/25; no dimension <4/5; independent major-issue detection |

## Weekly Practice Mix

Use approximately:
- 55% current-week technical topics;
- 30% pulled-forward advanced/integrated material;
- 15% spaced repetition / weakness remediation.

Do not wait until Week 8 to introduce ambiguous schemas, multi-concept code, or Staff-level issue prioritization.

## Daily Commute Standard

Daily technical commute lessons should be ~20–25 minutes and add at least one genuinely new interview-relevant concept or harder integrated application.

Include:
- two concepts;
- worked code example;
- line-by-line explanation;
- second edge-case scenario;
- rapid-fire code reading;
- one realistic L6 code-review question;
- Staff-level answer and validation plan;
- capability checklist.

For Gmail mobile, each snippet must be a single `<pre>` block with no nested code/span/div wrappers.

## Weekend Technical Interview Simulation

On demand only; never start automatically.

When the user explicitly asks to begin, run a ~60-minute L6-style technical interview simulation:
- 10–15 min rapid-fire fundamentals / output reasoning;
- 25–30 min multi-concept code review;
- 10–15 min end-to-end analytical case;
- final synthesis.

Use roughly 20–30 prompts/sub-prompts, administered exactly one at a time.

Never advance until the user explicitly says `move on` or clearly asks for the next question.

Questions should combine concepts and mimic real interview ambiguity. Examples:
- event-level table + user-level metric + many-to-many merge + missing users;
- assignment/exposure join + post-treatment filtering + wrong denominator;
- groupby/agg logic + ratio weighting + null semantics;
- correct-but-slow row-wise apply at 100M rows + correctness tradeoffs;
- datetime attribution + timezone + late-arriving events + cohort definition.

Require the candidate to explain:
1. what the code is trying to do;
2. what is wrong;
3. which issue is most material;
4. why it changes the analysis;
5. how to fix it;
6. how to validate the fix.

## Mastery Testing

A technical topic is mastered only after repeated evidence that the candidate can:
- explain the behavior;
- predict or diagnose realistic code;
- handle edge cases;
- connect implementation to analytical correctness;
- prioritize material risks;
- propose validation;
- perform under interview-like follow-up without rescue.

Recognition alone is not mastery.

## Week-8 Readiness Standard

By the end of Week 8, the candidate should be able to independently review unfamiliar 30–50 line analytical code and:
- infer intended analysis;
- establish table and metric grain;
- catch merge cardinality/duplication issues;
- preserve the correct randomized population and denominator;
- distinguish event-level from user-level calculations;
- reason about missing/null behavior;
- diagnose groupby/agg/transform/apply mistakes;
- identify exposure/leakage/post-treatment-selection problems;
- reason about datetime/cohort/attribution edge cases;
- identify correctness vs performance concerns at scale;
- propose safer code and validation assertions;
- prioritize the issue most likely to change the business conclusion;
- communicate a Staff-level recommendation.

Target evidence before top-priority loops:
- three realistic mocks around 21–22+/25;
- no evaluation dimension below ~4/5;
- independent identification of the major bug/assumption without interviewer rescue.

## L6 / Staff Behavior Standard

Reward independent clarification of ambiguous goals, schema/grain, populations and denominators, challenge of flawed premises, prioritization of material issues, connection to product/business decisions, invalidation conditions, and practical next actions.