---
name: people-science-skills
description: Core reasoning skill and framework for people, work, organizations, HR, compensation, talent, analytics, and organizational behavior decisions. Grounds agent reasoning in human behavior, first principles, and empirical evidence.
license: MIT
---

# People Science Skills — Core Reasoning & Decision Framework

## Purpose

Use this skill whenever an AI agent is helping answer a question, analyze a problem, or design a decision involving people, work, organizations, HR, compensation, talent, analytics, or organizational behavior.

The purpose is **not** to make the agent behave like a conventional HR expert.  
The purpose is to help the agent **reason better** about people-related decisions.

---

## Core Philosophy

Better HR decisions begin with better questions.

People and organizations are complex systems. HR decisions should therefore be grounded in:

1. **Human Behavior & Psychology**
2. **First-Principles Thinking**
3. **Evidence & Empirical Research**

Everything else is an output. Models, frameworks, analyses, recommendations, policies, interventions, and decision systems should emerge from these foundations rather than replace them.

---

## The Core Reasoning Model

For any people-related decision, reason through this 9-step sequence:

**Question → Behavior → First Principles → Evidence → Context → Alternatives → Trade-offs → Decision → Repeatability**

Do not automatically follow conventional HR practices merely because they are common.

### 1. QUESTION
Identify the decision that actually needs to be made.
- Distinguish the **stated question**, the **underlying problem**, and the **actual decision**.
- Do not solve a convenient question simply because it is easier to answer.

### 2. BEHAVIOR
Identify the human behavior involved.
- What are people actually doing, feeling, perceiving, or deciding?
- Describe behavior in observable terms rather than abstract labels (e.g., "employees leaving within 90 days" instead of "low engagement").

### 3. FIRST PRINCIPLES
Deconstruct the problem into fundamental mechanisms:
- Incentives & rewards
- Information & expectations
- Capability & resources
- Environment & constraints
- Social dynamics & norms
- Psychological needs (autonomy, competence, belonging, fairness)

### 4. EVIDENCE
Evaluate available empirical evidence:
- What research exists on this mechanism?
- What internal data exists?
- Distinguish between strong empirical evidence, weak correlation, anecdotal practice, and unexamined assumption.

### 5. CONTEXT
Analyze situational context:
- Organization size, stage, culture, industry, labor market, and constraints.
- Why a solution works in one context does not guarantee it works in another.

### 6. ALTERNATIVES
Generative exploration of options:
- Avoid binary choices (e.g., "should we do X or not?").
- Generate multiple plausible interventions or policy designs.

### 7. TRADE-OFFS
Analyze unintended consequences:
- Every intervention creates trade-offs (cost, complexity, fairness, gaming, morale).
- Make trade-offs explicit rather than hidden.

### 8. DECISION
Formulate a clear recommendation:
- State the proposed decision, rationale, expected behavioral impact, and risk mitigations.

### 9. REPEATABILITY
Ensure system repeatability:
- Define how success will be measured, monitored, and adjusted over time.

---

## Included Companion Skills

This repository includes specialized companion skills for deep-dive decision areas:

- **`people-science-core-reasoning`** (`./people-science-core-reasoning/`): Foundational reasoning model.
- **`compensation-decisioning`** (`./compensation-decisioning/`): Pay structures, internal equity, market positioning, incentives, and behavioral consequences.
- **`hr-analytics-decisioning`** (`./hr-analytics-decisioning/`): Translating people questions into measurable variables, analytical designs, and decision systems.
- **`organizational-behavior-decisioning`** (`./organizational-behavior-decisioning/`): Distinguishing behavioral mechanisms from assumptions, evaluating culture, motivation, leadership, and interventions.

---

## Core Guardrails for AI Agents

1. **Never recommend policies based purely on "best practices" without explaining the underlying behavioral mechanism.**
2. **Always separate correlation from causation when analyzing HR metrics.**
3. **Make assumptions explicit and identify missing data required for confident decisions.**
4. **Consider long-term behavioral side-effects (gaming, moral hazard, demotivation) for every incentive or rule change.**
