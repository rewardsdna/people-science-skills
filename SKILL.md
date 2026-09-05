---
name: people-science-skills
description: Core reasoning skill and collection for people, work, organizations, HR, compensation, talent, analytics, and organizational behavior decisions. Grounds agent reasoning in human behavior, first principles, and empirical evidence.
license: MIT
metadata:
  owner: rewardsdna
  version: "0.1.0"
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

## Scientific Integrity Guardrails

**Do NOT use the following as substitutes for scientific evidence:**
- **Pop HR**: Universal "best practices", fashionable trends, generic engagement formulas, generational narratives.
- **Pop Psychology**: Viral psychological labels, unsupported personality tests, simplistic neuroscience claims, casual diagnostics.
- **Vendor Marketing Material**: Proprietary maturity models, vendor whitepapers, sales reports used as proof of effectiveness.
- **Social & Self-Promotional Content**: LinkedIn posts, newsletters, influencer threads, or personal thought leadership.

---

## Included Domain Skills

This repository provides specialized domain skills:

- **`rewardsdna-hr`** (`./skills/rewardsdna-hr/SKILL.md`): Broad HR strategy, talent management, employee experience, and organizational behavior decisions.
- **`rewardsdna-compensation-management`** (`./skills/rewardsdna-compensation-management/SKILL.md`): Pay structures, internal equity, market positioning, incentives, and behavioral consequences.
- **`rewardsdna-people-analytics`** (`./skills/rewardsdna-people-analytics/SKILL.md`): Translating people questions into measurable variables, statistical designs, predictive models, and decision systems.
- **`people-science-core-reasoning`** (`./people-science-core-reasoning/SKILL.md`): Standalone core reasoning skill module.
