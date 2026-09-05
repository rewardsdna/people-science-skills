---
name: hr-analytics-decisioning
description: Translate Human Resources and people analytics questions into measurable variables, analytical designs, statistical models, workforce metrics, and data-driven decisions. Use with people-science-core-reasoning when turning HR questions into research designs or decision systems.
license: MIT
---

# HR Analytics Decisioning Skill

**Builds on:** `people-science-core-reasoning`

Use this skill whenever the work involves translating a people-related question into data, metrics, analysis, or a decision system.

---

## Analytical Method & Statistical Discipline

Do not begin with the statistical model or machine learning algorithm.

1. **Clarify the decision**: What action will change based on this analysis?
2. **Define outcome & unit of analysis**: What is being measured, at what level (individual, team, org)?
3. **Examine causal mechanism**: What factors plausibly cause changes in this outcome?
4. **Audit data quality**: Check for missingness, measurement error, and selection bias.
5. **Select appropriate methodology**: Match statistical methods to data structure and research questions.
6. **Differentiate inference**: Clearly separate descriptive stats, predictive models, and causal inference.
7. **Evaluate practical significance**: Distinguish statistical significance ($p < 0.05$) from meaningful business impact.
8. **Translate to decision system**: Define reproducible workflows, monitoring feedback loops, and human oversight.

---

## Analytical Guardrails

- **Correlation vs. Causation**: Never present statistical association or predictive correlation as causal proof.
- **Model Simplification**: Prefer the simplest adequate analytical method. Do not use complex ML algorithms merely because they are available.
- **Psychological Caution**: Do not infer individual psychological traits or diagnose employees from workplace data.
- **Uncertainty Reporting**: Always report confidence, sample limitations, and context dependency.

---

## 🔬 Mandatory Output Section Requirement

Every response MUST include a dedicated section:

### 🔬 Evidence & Causal Discipline Audit
1. **Association vs. Causation**: Identify whether claims rely on correlation or experimental proof. Use associative language for observational data.
2. **Confounding & Reverse Causality**: Identify at least two plausible confounders, selection biases, or reverse causality vectors.
3. **Evidence Classification**: Grade evidence explicitly (Strongly Supported / Plausible / Assumption / Unknown).
