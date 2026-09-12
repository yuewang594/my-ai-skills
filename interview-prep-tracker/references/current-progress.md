# Current Interview Prep Progress

_Last updated: 2026-09-12_

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
| 🔵 Practiced | 48 |
| 🟡 Learned | 17 |
| ⬜ Not Started | 51 |
| Curriculum Coverage | 89 / 140 = 63.6% |
| Weighted Interview Mastery | 185 / 420 = 44.0% |

Coverage means the concept has at least reached Learned. Mastery is weighted and should not be interpreted as a probability of passing an interview.

## Statistics — Probability and Foundations

| Concept | Status |
|---|---|
| Expectation | 🔵 |
| Variance | 🔵 |
| Standard deviation | 🔵 |
| Covariance | ⬜ |
| Conditional probability | ⬜ |
| Bayes' theorem | ⬜ |
| Law of Total Expectation | ⬜ |
| Law of Total Variance | ⬜ |
| Common probability distributions | 🔵 |
| Sampling distributions | 🔵 |
| Law of Large Numbers | 🔵 |
| Central Limit Theorem | 🔵 |

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
| Multiple testing | 🟡 |
| Bootstrap | ⬜ |
| Permutation tests | ⬜ |
| Bayesian inference basics | ⬜ |
| Regression to the mean | ⬜ |

## Experimentation

| Concept | Status |
|---|---|
| Randomization | 🔵 |
| Treatment assignment | 🔵 |
| Unit of randomization | 🔵 |
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
| Metric decomposition | 🔵 |
| Funnel metrics | 🟡 |
| Ratio metrics | 🔵 |
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
| Ability to ask the right follow-up question | 🔵 |
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
- In the 2026-09-12 Week 1-2 Stats assessment, independently handled expectation, Bernoulli/binomial variance, sampling-distribution calculations, LLN vs CLT, standard error, confidence intervals, metric decomposition, ratio metrics, randomization, unit of randomization/analysis, and Staff-level launch tradeoffs.
- Correctly identified a 20-country multiple-testing problem and quantified the approximate family-wise false-positive probability.

## Current Review Flags — 2026-09-12 Weekly Stats Assessment

### Weak

- **Bayes / base-rate reasoning:** Correctly chose the low-posterior direction but could not independently explain why rare prevalence can make false positives dominate true positives.
- **Sampling bias vs precision:** Incorrectly concluded that a large biased sample with small SE was trustworthy. Must distinguish precision from representativeness/bias.
- **Bias-variance tradeoff / MSE:** Initially preferred an unbiased high-variance estimator over a slightly biased low-variance estimator without comparing total error.
- **ITT vs exposed-user analysis:** Initially wanted to filter to users who actually saw treatment; after teaching, correctly applied ITT in a follow-up. Needs fresh independent retest before promotion.

### Uncertain

- **CLT assumptions under heavy tails:** Correctly recognized that n=30 may be insufficient for a highly skewed metric, but suggested repeated sampling rather than focusing on larger n / robust inference for the actual experiment.
- **Differential attrition / missing outcomes:** Product response appropriately prioritized pausing a treatment-caused bug, but statistical implications of arm-specific missingness need more practice.
- **Robust inference for outliers:** Strong diagnosis of power-user effects, but post-hoc winsorization should not be the default; needs more practice with pre-specified robust methods and sensitivity analysis.

### Needs Review

- **Expected value wording:** Expectation is a long-run average across repeated samples, not a guarantee for a single sample.
- **Sampling distribution terminology:** Distinguish a binomial count distribution from the sampling distribution of a sample proportion.
- **CLT vs LLN wording:** CLT concerns the shape/spread of a sampling distribution; LLN concerns convergence of the sample mean to the population mean.
- **Frequentist CI interpretation:** Avoid assigning a 95% probability to the fixed parameter after observing the interval, and do not infer probability from how much of a CI lies above zero.
- **Unbiasedness vs precision:** Unbiased means correct on average; it does not imply any one estimate is close to the truth.
- **Precision vs accuracy/bias:** Larger n mainly improves precision; it does not automatically remove systematic bias.
- **z-score / significance arithmetic:** One arithmetic miss on a 2 pp effect with 1 pp SE; z should be 2.0, roughly significant at the two-sided 5% level.
- **Large sample vs peeking:** A large pre-planned sample does not itself inflate Type I error; repeated peeking / optional stopping without correction does.
- **Inconclusive vs no effect:** Wide CIs containing zero imply insufficient evidence, not proof that the true effect is zero.

## Highest-Priority Gaps

Current high-ROI gaps for Staff/L6 Product Data Scientist interviews:

1. Bayes / conditional probability / base-rate reasoning and sampling bias vs precision.
2. Bias-variance tradeoff, MSE, and the distinction between unbiasedness, precision, and accuracy.
3. ITT, noncompliance, exposed-user selection, and differential attrition.
4. Statistical power → MDE → sample-size calculations as one connected system.
5. Hypothesis-test selection: t-test, z-test, one-sided vs two-sided tests.
6. Multiple testing and sequential testing / peeking.
7. Experiment design failure modes: SRM, stopping rules, CUPED, novelty/interference.
8. Pandas transform, apply, pivot_table, window functions, ranking, and rolling operations.
9. Python reasoning topics: mutability, references/copying, function arguments, comprehensions, and basic complexity.

## Next Recommended Milestone

Before moving the overall prep into heavy mock-interview mode, target:

- Stats: retest Bayes/base rates, sampling bias vs precision, and bias-variance/MSE; then make power/MDE/sample sizing 🔵 or better.
- Experimentation: independently retest ITT/post-treatment selection; make SRM and stopping/sequential testing 🔵 or better.
- Pandas: make merge/join/data-grain reasoning consistently 🟢 and add transform/window-function fluency.
- Python: establish at least 🟡 evidence for core language reasoning topics without turning prep into syntax memorization.
