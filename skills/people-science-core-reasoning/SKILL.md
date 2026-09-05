---
name: people-science-core-reasoning
description: Core reasoning skill for Human Resources (HR), compensation, talent management, workforce decisions, and organizational behavior. Use whenever an agent answers questions, analyzes problems, or designs decisions involving people. Grounds reasoning in human behavior, first principles, and evidence rather than conventional HR practices.
license: MIT
---

# People Science Skills — Core Reasoning Skill

## Purpose

Use this skill whenever an AI agent is helping answer a question, analyze a problem, or design a decision involving people, work, organizations, HR, compensation, talent, or organizational behavior.

The purpose is **not** to make the agent behave like an HR expert.  
The purpose is to help the agent **reason better** about people-related decisions.

---

## Core Philosophy

Better HR decisions begin with better questions.

People and organizations are complex. HR decisions should therefore be grounded in:

1. **Human Behavior & Psychology**
2. **First-Principles Thinking**
3. **Evidence & Empirical Research**

Everything else (frameworks, models, recommendations, policies) is an *output* of this reasoning, not a starting point.

---

## The Core Reasoning Sequence

**Question → Behavior → First Principles → Evidence → Context → Alternatives → Trade-offs → Decision → Repeatability**

### 1. QUESTION
First identify the decision that actually needs to be made.
Distinguish between the stated question, the underlying problem, and the actual decision.

### 2. BEHAVIOR
Identify the human behavior involved.
Describe behavior in observable terms rather than abstract labels (e.g., "employees leaving within 90 days" instead of "low engagement").

### 3. FIRST PRINCIPLES
Deconstruct the problem into fundamental mechanisms:
Incentives, information, capability, environment, social dynamics, and psychological needs (autonomy, competence, belonging, fairness).

### 4. EVIDENCE & CAUSAL DISCIPLINE
Evaluate empirical evidence.
Never confuse observational correlation with causal proof. Use associative language ("is correlated with") rather than causal verbs ("drives", "causes") for non-experimental data.
Audit for hidden confounders, selection bias, and reverse causality.

### 5. CONTEXT
Analyze situational context: organization size, stage, culture, industry, labor market, and boundary conditions.

### 6. ALTERNATIVES
Generative exploration of options. Avoid binary choices; generate multiple plausible interventions.

### 7. TRADE-OFFS
Analyze unintended consequences (cost, complexity, fairness, gaming, morale).

### 8. DECISION
Formulate a clear recommendation with rationale and risk mitigations.

### 9. REPEATABILITY
Ensure system repeatability: define metrics, monitoring, and feedback loops.

---

## 🔬 Mandatory Output Section Requirement

Every response MUST include a dedicated section:

### 🔬 Evidence & Causal Discipline Audit
1. **Association vs. Causation**: Identify whether claims rely on correlation or experimental proof. Use associative language for observational data.
2. **Confounding & Reverse Causality**: Identify at least two plausible confounders or selection biases.
3. **Evidence Classification**: Grade evidence explicitly (Strongly Supported / Plausible / Assumption / Unknown).

---

## Scientific Integrity Guardrails

**Do NOT use the following as substitutes for scientific evidence:**
- **Pop HR**: Universal "best practices", fashionable trends, generic formulas, generational myths.
- **Pop Psychology**: Viral psychological labels, unsupported personality tests, casual diagnostics.
- **Vendor Marketing Material**: Proprietary maturity models, vendor whitepapers, sales reports used as proof.
- **Social Content**: LinkedIn posts, newsletters, influencer threads, or personal thought leadership.
