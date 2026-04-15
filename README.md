# LLM-Assisted-Code-Smell-Severity-Scoring-Challenge-
This competition required us to reason like an experienced software engineer evaluating technical debt, which is where LLM code understanding capabilities are essential.

# Overview
Given a Python code snippet seeded with a specific code smell, predict the severity score of that smell on a 1–5 ordinal scale (1=negligible, 5=critical). The task requires nuanced code comprehension: two snippets with the same smell type and similar line count may have drastically different severity based on how the smell manifests — its structural depth, interaction with control flow, state mutation risk, and maintenance cost.

This is not a pattern-matching task. Severity prediction requires reasoning like an experienced software engineer evaluating technical debt, which is where LLM code understanding capabilities are essential. Static analysis features (nesting depth, line count, cyclomatic complexity) are provided as weak auxiliary signals, but are insufficient to determine severity alone.
