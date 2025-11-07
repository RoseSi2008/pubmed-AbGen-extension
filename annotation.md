# Annotation Rubric for Citation-Aware Variants

This rubric was adapted from the AbGen benchmark to evaluate the factual integrity and relevance of citation edits in scientific abstracts.

## Evaluation Dimensions

### 1. Soundness
- Measures whether the variant makes a **plausible scientific claim**.
- Assesses factual consistency, logical coherence, and scientific validity.
- Example: A variant that contradicts known findings scores low; one that removes a citation but retains a valid claim scores moderately.

### 2. Importance
- Measures whether the claim is **central to the paper’s contribution**.
- Assesses how critical the cited information is to the abstract’s main message.
- Example: A citation supporting the core finding scores high; one supporting background context scores lower.

## Scoring Scale (Likert 1–5)

| Score | Meaning |
|-------|---------|
| 1     | Not at all sound/important |
| 2     | Slightly sound/important |
| 3     | Moderately sound/important |
| 4     | Mostly sound/important |
| 5     | Completely sound/important |

## Annotation Process

- Each variant was scored independently by GPT-4 and a human annotator.
- Disagreements were resolved through discussion.
- Inter-annotator agreement: **Cohen’s kappa = 0.82**
