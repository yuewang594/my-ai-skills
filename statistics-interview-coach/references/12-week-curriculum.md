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

Material originally reserved for Weeks 9–12 should be pulled forward into Weeks 4–8 through integrated cases, spaced repetition, and weekend interview simulations.

## Weekly Curriculum

| Week | Statistics / Experimentation | Python / Technical Companion | L6 Product Case | Measurable Milestone |
|---|---|---|---|---|
| 1 | Probability, conditional probability, expectation, variance, common distributions | Python foundations | Metric definition | ≥80% fundamentals; explain core probability intuitively |
| 2 | Sampling, CLT, SE, confidence intervals | NumPy foundations | Metric trees / guardrails | Explain CI correctly in <2 min; distinguish SD vs SE |
| 3 | Hypothesis tests, p-values, Type I/II, power, MDE; intro multiple testing, CUPED, ratio metrics/delta method, ITT/exposure | Pandas core | A/B design | ≥85% inference questions; independently identify main experiment assumption |
| 4 | Randomization, exposure, SRM, ITT, guardrails, experiment debugging; intro interference/cluster issues | Joins/cardinality | Diagnose broken experiment | 45–60 min mock ≥18/25; no major experiment-validity issue missed |
| 5 | Sequential testing, peeking, multiple testing, novelty/carryover, heavy tails, bootstrap vs delta method, time-window issues | Datetime/cohorts | Conflicting launch metrics | Explain stopping/peeking risks and choose inference method without hints |
| 6 | CUPED deeper, regression adjustment, ratio metrics, variance reduction, HTE, practical vs statistical significance | Metric implementation | Payments/marketplace metric design | Build experiment + metrics + inference plan in ≤20 min |
| 7 | Regression intuition, confounding, Simpson's paradox, selection bias, DiD, matching, sensitivity | Performance/scale | Causal reasoning without clean experiment | Identify causal limitations and viable design unprompted in ≥4/5 cases |
| 8 | Integrated experiment diagnostics, interference/network effects, cluster experiments, decision under uncertainty, rapid recall | Full analysis/code critique | Full L6 product analytics case | 3 realistic mocks around 21–22+/25; no dimension <4/5; independent major-issue detection |

## Weekly Practice Mix

Use approximately:
- 60% current-week material;
- 25% pulled-forward advanced material;
- 15% spaced repetition / weakness remediation.

Do not wait until Week 8 to introduce ambiguity or integrated reasoning.

## Daily Commute Standard

Daily Stats commute lessons should be ~20–25 minutes and add at least one genuinely new interview-relevant concept or harder application.

Include:
- two concepts;
- two worked examples;
- one derivation/formula intuition when useful;
- rapid-fire recall;
- one realistic L6 question;
- Staff-level answer;
- capability checklist.

## Weekend Stats Interview Simulation

On demand only; never start automatically.

Each weekend, when the user explicitly asks to begin, run a ~60-minute L6-style Stats interview simulation:
- 10–15 min rapid fire;
- 25–30 min multi-concept questions;
- 10–15 min end-to-end case;
- final synthesis.

Use roughly 20–30 prompts/sub-prompts, administered exactly one at a time.

Never advance until the user explicitly says `move on` or asks for the next question.

Questions should combine concepts and mimic real interview ambiguity. Examples:
- ITT + exposure + ratio metric + CI + guardrail + launch decision;
- power + peeking + CUPED + practical significance;
- SRM + join/data-quality issue + causal interpretation;
- interference + cluster randomization + metric design.

## Statistics Mastery Testing

A topic is mastered only after repeated evidence that the candidate can:
1. explain it accurately;
2. apply it in a realistic scenario;
3. recognize it when unnamed;
4. identify a failure mode;
5. connect it to a decision;
6. defend the reasoning under follow-up.

Recognition alone is not mastery.

## Week-8 Readiness Standard

By the end of Week 8, the candidate should be able to independently:
- clarify the product decision and estimand;
- define population, unit, denominator, and metrics;
- diagnose randomization/exposure/SRM issues;
- choose appropriate inference for means, ratios, heavy tails, and adjusted estimators;
- reason about power, peeking, multiple testing, CUPED, and confidence intervals;
- identify causal threats and interference;
- separate statistical significance from practical significance;
- prioritize the most material issue;
- explain what could invalidate the conclusion;
- recommend what the team should do next.

Target evidence before top-priority loops:
- three realistic mocks around 21–22+/25;
- no evaluation dimension below ~4/5;
- independent identification of the major assumption or decision risk without interviewer rescue.