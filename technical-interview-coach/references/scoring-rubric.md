# Technical Interview Coach Scoring Rubric

## Overview

Score each interview response on five dimensions from 1 to 5.

Maximum score: 25.

The rubric should distinguish someone who can produce a technically correct answer from someone who demonstrates Staff-level judgment.

## 1. Technical Correctness

### 5 — Excellent
Reasoning is technically correct, precise, and complete. Important assumptions are stated explicitly.

### 4 — Strong
Core answer is correct with only minor omissions that do not materially affect the conclusion.

### 3 — Adequate
Generally correct but contains meaningful gaps, imprecision, or relies on unstated assumptions.

### 2 — Weak
Some correct ideas, but major reasoning or implementation problems remain.

### 1 — Incorrect
Fundamental misunderstanding or conclusion is materially wrong.

## 2. Edge-Case Awareness

### 5 — Excellent
Identifies the important edge cases, prioritizes them by materiality, and explains their consequences.

### 4 — Strong
Finds most important edge cases but misses one or does not fully prioritize them.

### 3 — Adequate
Recognizes obvious edge cases but misses subtle or realistic failure modes.

### 2 — Weak
Only notices issues after prompting or focuses mainly on superficial concerns.

### 1 — Poor
Assumes the happy path and fails to consider material failure modes.

## 3. Statistical / Data Reasoning

### 5 — Excellent
Correctly defines populations, denominators, assumptions, estimands, metrics, and inference. Connects data-generating process to interpretation.

### 4 — Strong
Sound reasoning with small omissions around assumptions or interpretation.

### 3 — Adequate
Can perform the analysis but does not consistently reason about how the data was generated or what can invalidate the result.

### 2 — Weak
Uses methods mechanically or makes questionable analytical assumptions.

### 1 — Poor
Fundamental statistical or analytical reasoning is incorrect.

## 4. Communication

### 5 — Excellent
Structured, concise, easy to follow, and prioritizes the most important issue first. Can explain both technically and to a product stakeholder.

### 4 — Strong
Clear and structured with occasional unnecessary detail or minor ambiguity.

### 3 — Adequate
Understandable but somewhat meandering, unprioritized, or incomplete.

### 2 — Weak
Difficult to follow or mixes major and minor issues without structure.

### 1 — Poor
Unable to communicate the reasoning coherently.

## 5. Staff-Level Judgment

### 5 — Excellent
Challenges flawed premises, prioritizes risks, proposes practical validation, understands tradeoffs, and connects technical findings to product decisions and business impact.

### 4 — Strong
Demonstrates good senior judgment and some Staff-level thinking, with minor gaps in prioritization or broader implications.

### 3 — Adequate
Technically capable but primarily executes the requested analysis rather than reframing or challenging it when needed.

### 2 — Weak
Focuses narrowly on implementation and misses important decision or product implications.

### 1 — Poor
Treats the problem as a mechanical exercise without considering whether the analysis is appropriate or useful.

## Overall Score

### 22–25 — Strong Staff
Consistently demonstrates the technical depth and judgment expected of a Staff Data Scientist.

### 18–21 — Competitive, with gaps
Likely strong Senior / emerging Staff performance. Identify the specific dimensions preventing consistent Staff-level performance.

### 14–17 — Senior-level but not yet Staff interview-ready
Core skills exist, but reasoning, edge-case detection, communication, or judgment requires meaningful improvement.

### Below 14 — Foundational gaps
Prioritize targeted remediation before increasing interview difficulty.

## Feedback Format

After a substantial exercise, provide:

- Technical correctness: X/5
- Edge-case awareness: X/5
- Statistical/data reasoning: X/5
- Communication: X/5
- Staff-level judgment: X/5
- Total: X/25

Then give three sections:

### What you did well
Only specific observations supported by the answer.

### What would hurt you in an interview
Prioritize the 1–3 most material weaknesses. Do not produce a long list of minor issues.

### Stronger Staff-level answer
Show how the response could be structured and reasoned more effectively.

End with one follow-up question unless the session is explicitly over.

## Weakness Tracking

Record recurring problems conceptually, for example:
- p-value interpretation
- confidence interval interpretation
- sequential testing
- multiple comparisons
- exposure definition
- denominator selection
- join cardinality
- index alignment
- missing-data handling
- time-window logic
- prioritization
- stakeholder communication

A single mistake is not automatically a weakness. Treat something as recurring after it appears multiple times or reflects a clear conceptual misunderstanding.
