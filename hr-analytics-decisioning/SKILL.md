---
name: hr-analytics-decisioning
description: Translate HR and people questions into measurable variables, analytical designs, and decisions. Use with people-science-core-reasoning when turning business or HR questions into metrics, research designs, models, or decision systems based on workforce data.
license: MIT
---

# HR Analytics Decisioning Skill

**Builds on:** `people-science-core-reasoning`

Use this skill whenever the work involves translating a people-related question into data, metrics, analysis, or a decision system.

## Purpose

Help the agent move from vague HR questions to:

- Clear measurable variables
- Appropriate analytical designs
- Transparent interpretation
- Decisions that respect the limits of the data

This is not a statistics textbook. It is a decisioning layer that keeps analysis grounded in the Core Reasoning model.

## Core Translation Process

1. **Start with the decision** (from Core Reasoning)
2. **Identify the target behavior or outcome**
3. **Define the construct(s)** carefully
4. **Translate constructs into measurable variables**
5. **Choose an analytical design that can actually answer the question**
6. **State the assumptions required for causal or practical claims**
7. **Interpret within the limits of the design and data**
8. **Convert insight into a decision or a repeatable system**

## From Question to Variable

For every important construct, ask:

- What observable behavior or state does this represent?
- How will it be measured?
- What is the unit of analysis (person, team, role, time period)?
- What is the expected range, distribution, and missingness?
- What confounds or alternative explanations exist?

Avoid treating survey scores, ratings, or system flags as direct measures of deep psychological constructs without justification.

## Analytical Design Guardrails

- Prefer designs that match the causal or practical claim being made.
- Distinguish description, prediction, and explanation.
- Be explicit about selection effects, attrition, and missing data.
- Report practical significance alongside statistical significance.
- Prefer simpler transparent methods when they answer the question adequately.
- Never let model complexity substitute for understanding the problem.

## Common HR Analytics Pitfalls to Avoid

- Treating correlation as mechanism
- Using lagging indicators as if they were leading
- Ignoring range restriction or selection into the sample
- Over-interpreting single-item or low-reliability measures
- Presenting dashboards as decisions
- Building “predictive” models without a clear decision that will use the prediction
- Optimizing a metric that is easy to measure rather than the behavior that matters

## Output Structure for Analytics Work

When delivering analysis or recommendations:

1. **Decision the analysis is meant to inform**
2. **Target behavior / outcome**
3. **Constructs and their operational definitions**
4. **Data and design** (including limitations)
5. **Key findings** with evidence classification
6. **Alternative explanations**
7. **Implications for action**
8. **What should be monitored or tested next**
9. **Whether a repeatable decision rule or system is warranted**

## Integration with Core Reasoning

Run the full Core Reasoning sequence.  
This skill specializes the Evidence, Context, Alternatives, and Repeatability stages for quantitative people data.

## Guiding Principle

Good HR analytics starts with a decision worth making, not with a dataset worth analyzing.
