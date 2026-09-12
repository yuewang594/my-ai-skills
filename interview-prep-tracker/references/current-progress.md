# Current Interview Prep Progress

_Last updated: 2026-09-11_

This file is the durable source of truth for the user's current mastery state. Update it after meaningful Statistics Interview Coach or Technical Interview Coach sessions when there is enough evidence for a level change.

Mastery scale:

- ⬜ Not Started = 0
- 🟡 Learned = 1
- 🔵 Practiced = 2
- 🟢 Interview Ready = 3

Baseline philosophy: conservative. A topic is not promoted just because it was mentioned. Existing professional experience alone does not automatically count as interview-prep evidence unless demonstrated in practice.

## Baseline Summary

| Metric | Baseline |
|---|---:|
| Total tracked concepts | 140 |
| 🟢 Interview Ready | 24 |
| 🔵 Practiced | 38 |
| 🟡 Learned | 26 |
| ⬜ Not Started | 52 |
| Curriculum Coverage | 88 / 140 = 62.9% |
| Weighted Interview Mastery | 174 / 420 = 41.4% |

Coverage means the concept has at least reached Learned. Mastery is weighted and should not be interpreted as a probability of passing an interview.

## Statistics — Probability and Foundations

| Concept | Status |
|---|---|
| Expectation | 🟡 |
| Variance | 🔵 |
| Standard deviation | 🔵 |
| Covariance | ⬜ |
| Conditional probability | ⬜ |
| Bayes' theorem | ⬜ |
| Law of Total Expectation | ⬜ |
| Law of Total Variance | ⬜ |
| Common probability distributions | 🟡 |
| Sampling distributions | 🟡 |
| Law of Large Numbers | 🟡 |
| Central Limit Theorem | 🟡 |

## Statistics — Inference

| Concept | Status |
|---|---|
| Standard error | 🔵 |
| Confidence intervals | 🟢 |
| Confidence interval interpretation | 🟢 |
| Relationship between CI width, variance, and sample size | 🔵 |
| Null and alternative hypotheses | 🔵 |
| p-values | 🟢 |
| Significance level / alpha | 🟡 |
| Type I error | 🟡 |
| Type II error | 🟡 |
| Statistical power | 🟡 |
| Minimum Detectable Effect | ⬜ |
| Sample-size calculations | ⬜ |
| One-sided vs two-sided tests | ⬜ |
| t-tests | ⬜ |
| z-tests | ⬜ |
| Multiple testing | ⬜ |
| Bootstrap | ⬜ |
| Permutation tests | ⬜ |
| Bayesian inference basics | ⬜ |
| Regression to the mean | ⬜ |

## Experimentation

| Concept | Status |
|---|---|
| Randomization | 🟡 |
| Treatment assignment | 🔵 |
| Unit of randomization | 🟡 |
| Unit of analysis | 🔵 |
| A/A tests | ⬜ |
| Experiment validity | 🔵 |
| Sample Ratio Mismatch | 🟡 |
| Power analysis | 🟡 |
| Experiment duration | ⬜ |
| Stopping rules | ⬜ |
| Sequential testing / peeking | ⬜ |
| CUPED / variance reduction | ⬜ |
| Novelty effects | ⬜ |
| Primacy effects | ⬜ |
| Network / interference effects | ⬜ |
| Heterogeneous treatment effects | ⬜ |
| Noncompliance | ⬜ |
| Intention-to-treat | 🟡 |
| Treatment-on-the-treated | ⬜ |
| Missing data | 🟡 |
| Attrition | ⬜ |
| Guardrail metrics | 🔵 |
| Delayed exposure | 🔵 |
| Treatment contamination | 🔵 |

## Product Metrics

| Concept | Status |
|---|---|
| Correct metric denominator | 🟢 |
| User-level vs event-level metrics | 🟢 |
| Conversion-rate construction | 🟢 |
| Revenue per user vs revenue per transaction | 🔵 |
| Repeated-event bias | 🟢 |
| Heavy-user bias | 🔵 |
| Metric decomposition | 🟡 |
| Funnel metrics | 🟡 |
| Ratio metrics | 🟡 |
| Exposure metrics | 🔵 |
| Leading vs lagging metrics | ⬜ |
| Guardrail selection | 🔵 |

## Python Foundations

| Concept | Status |
|---|---|
| Lists | ⬜ |
| Tuples | ⬜ |
| Dictionaries | 🟡 |
| Sets | ⬜ |
| Conditional logic | ⬜ |
| Loops | ⬜ |
| Functions | ⬜ |
| Function arguments | ⬜ |
| Classes vs functions | 🟡 |
| Lambda functions | ⬜ |
| Comprehensions | ⬜ |
| Exception handling | ⬜ |
| Mutability | ⬜ |
| Object references | ⬜ |
| Copying | ⬜ |
| Basic time and space complexity | ⬜ |

## Pandas

| Concept | Status |
|---|---|
| DataFrame filtering | 🔵 |
| Boolean masks | 🔵 |
| groupby() | 🔵 |
| agg() | 🔵 |
| Named aggregation | 🔵 |
| as_index | 🔵 |
| Multi-column grouping | 🔵 |
| User-level aggregation | 🟢 |
| merge() | 🔵 |
| Join cardinality | 🟢 |
| One-to-many joins | 🟢 |
| Many-to-many joins | 🟡 |
| Duplicated rows after joins | 🟢 |
| transform() | ⬜ |
| apply() | ⬜ |
| pivot_table() | ⬜ |
| Missing values | 🔵 |
| Deduplication | 🟡 |
| Datetime operations | ⬜ |
| Sorting | 🟡 |
| Ranking | ⬜ |
| Window functions | ⬜ |
| Rolling calculations | ⬜ |
| concat() | ⬜ |
| Vectorization | ⬜ |
| Pandas performance traps | ⬜ |

## Data-Grain Reasoning

| Concept | Status |
|---|---|
| Identifying table grain | 🟢 |
| Identifying metric grain | 🟢 |
| Recognizing event vs user datasets | 🟢 |
| Identifying accidental row multiplication | 🟢 |
| Aggregation before joins | 🔵 |
| Denominator correctness | 🟢 |
| Repeated-event bias | 🟢 |
| Deduplication logic | 🔵 |
| Interpreting one-to-many relationships | 🟢 |

## Code Review Competencies

| Concept | Status |
|---|---|
| Logical bugs | 🔵 |
| Data-grain bugs | 🟢 |
| Incorrect joins | 🟢 |
| Denominator mistakes | 🟢 |
| Silent duplication | 🟢 |
| Incorrect aggregations | 🟢 |
| Missing edge cases | 🔵 |
| Null-handling problems | 🔵 |
| Misleading variable names | 🟡 |
| Inefficient implementations | 🟡 |
| Assumptions that may fail in production | 🔵 |

## Staff/L6 Evaluation Layer

| Concept | Status |
|---|---|
| Assumption identification | 🔵 |
| Ambiguity detection | 🔵 |
| Metric-design judgment | 🔵 |
| Experiment diagnosis | 🔵 |
| Tradeoff reasoning | 🔵 |
| Edge-case thinking | 🔵 |
| Ability to ask the right follow-up question | 🟡 |
| Clear reasoning communication | 🔵 |
| Business and product interpretation | 🔵 |
| Ability to distinguish statistical significance from practical significance | 🟢 |

## Evidence Behind the Baseline

Strongest demonstrated evidence so far:

- Correctly explained frequentist p-value interpretation and rejected the misconception that p < 0.05 means a 95%+ probability that treatment works.
- Correctly reasoned about confidence intervals that include zero, CI width, uncertainty, standard deviation versus standard error, and practical versus statistical significance.
- Correctly identified user-level versus event-level metric grain and denominator problems in conversion and revenue metrics.
- Correctly identified one-to-many join row multiplication and its downstream metric bias.
- Successfully used and explained Pandas filtering, groupby, agg, named aggregation, multi-column grouping, and user-level aggregation.
- Demonstrated strong code-review reasoning around join cardinality, missing denominators, data contracts, missing keys / None, dropna / fillna semantics, and safe transformations.
- Demonstrated experiment-diagnosis reasoning around contamination, delayed exposure, guardrails, unexpected treatment/control behavior, and rollout decisions.

## Highest-Priority Gaps

Current high-ROI gaps for Staff/L6 Product Data Scientist interviews:

1. Statistical power → MDE → sample-size calculations as one connected system.
2. Hypothesis-test selection: t-test, z-test, one-sided vs two-sided tests.
3. Multiple testing and sequential testing / peeking.
4. Experiment design failure modes: SRM, stopping rules, CUPED, novelty/interference.
5. Pandas transform, apply, pivot_table, window functions, ranking, and rolling operations.
6. Python reasoning topics: mutability, references/copying, function arguments, comprehensions, and basic complexity.

## Next Recommended Milestone

Before moving the overall prep into heavy mock-interview mode, target:

- Stats: make power/MDE/sample sizing 🔵 or better.
- Experimentation: make SRM and stopping/sequential testing 🔵 or better.
- Pandas: make merge/join/data-grain reasoning consistently 🟢 and add transform/window-function fluency.
- Python: establish at least 🟡 evidence for core language reasoning topics without turning prep into syntax memorization.
