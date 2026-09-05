---
name: people-science-skills
description: Core reasoning skill and collection for people, work, organizations, HR, compensation, talent, analytics, and organizational behavior decisions. Grounds agent reasoning in human behavior, first principles, and empirical evidence.
license: MIT
metadata:
  owner: rewardsdna
  version: "0.1.0"
---

# People Science Skills — Core Reasoning & Decision Framework

This repository provides evidence-based People, HR, and Organizational decision skills. The collection includes specialized skills for core reasoning, compensation decisioning, HR analytics, and organizational behavior.

**Use the specialized skill relevant to your task:**
- **[people-science-core-reasoning](./skills/people-science-core-reasoning/SKILL.md)**: Foundational behavioral reasoning and first-principles thinking for any people-related decision.
- **[compensation-decisioning](./skills/compensation-decisioning/SKILL.md)**: Pay structures, market positioning, incentives, pay equity, and total rewards.
- **[hr-analytics-decisioning](./skills/hr-analytics-decisioning/SKILL.md)**: Workforce metrics, statistical modeling, research designs, and data analysis.
- **[organizational-behavior-decisioning](./skills/organizational-behavior-decisioning/SKILL.md)**: Workplace culture, motivation, team dynamics, leadership, and change interventions.

When loaded as a master skill, apply the core philosophy, reasoning model, and scientific integrity guardrails below.

---

## 🎯 Executive Usability & Decision Mandate

1. **Zero Consulting Boilerplate**: Start responses immediately with the answer. Eliminate generic introductory filler ("In today's fast-paced corporate environment...") and conversational fluff.
2. **Make an Actual Decision (No Premature Jumps)**: Do not hide behind vague "it depends" hedging. State an explicit **Recommended Decision**. If baseline data or evidence is missing, do NOT jump prematurely to a full-scale policy/compensation change; recommend a **Diagnostic Audit** or **Small-Scale Pilot** as the primary decision.
3. **The Evidence Gatekeeper Condition**: Every recommendation MUST specify an explicit Gatekeeper Condition: *"Do NOT authorize full implementation of [Intervention X] until [Data Point Y] is verified."*
4. **No Synthetic Statistics**: Never fabricate numerical statistics or fake study citations. Tag evidence explicitly as `[Empirical Consensus]`, `[User-Supplied Data]`, or `[Unverified Hypothesis]`.

---

## Core Philosophy & Reasoning Sequence

Better HR decisions begin with better questions. Ground reasoning in:
1. **Human Behavior & Psychology**
2. **First-Principles Thinking**
3. **Evidence & Empirical Research**

Reason through the 9-step sequence:
**Question → Behavior → First Principles → Evidence → Context → Alternatives → Trade-offs → Decision → Repeatability**

---

## 🔬 Mandatory Required Output Structure

Every comprehensive output produced using this skill MUST follow this structure:

### 1. 🎯 Executive Summary (BLUF)
- **Recommended Decision**: [Clear 1-sentence decision; Diagnostic Audit / Pilot if data is incomplete]
- **Behavioral Rationale**: [Primary psychological/behavioral mechanism]
- **Gatekeeper Condition**: [Explicit condition required before full rollout]

### 2. 📊 Options & Decision Matrix
Present alternatives in a 3-column table:
| Option | Primary Behavioral Mechanism | Key Risk & Trade-off | Recommendation Tier |
|---|---|---|---|
| **Option A (Recommended)** | [Mechanism] | [Risk] | ✅ Recommended |
| **Option B (Alternative)** | [Mechanism] | [Risk] | ⚠️ Secondary |
| **Option C (Status Quo)** | [Mechanism] | [Risk] | ❌ Rejected |

### 3. 🔬 Evidence & Causal Discipline Audit
- **Association vs. Causation**: Identify whether claims rely on correlation or experimental proof. Use associative language ("is correlated with") for non-experimental data.
- **Confounding & Reverse Causality**: Identify at least two plausible confounders or selection biases.
- **Evidence Tiers & Gatekeeper**: Explicitly grade evidence (Strongly Supported / Plausible / Assumption / Unknown) and state the baseline data requirement.

### 4. 📅 30-60-90 Day Operational Roadmap
- **Days 1–30**: Baseline audit, data checks, and Gatekeeper verification.
- **Days 31–60**: Pilot intervention on target cohort.
- **Days 61–90**: Impact evaluation, Goodhart's Law audit, and process scaling.

---

## Scientific Integrity Guardrails

**Do NOT use the following as substitutes for scientific evidence:**
- **Pop HR**: Universal "best practices", fashionable trends, generic engagement formulas, generational narratives.
- **Pop Psychology**: Viral psychological labels, unsupported personality tests, simplistic neuroscience claims, casual diagnostics.
- **Vendor Marketing Material**: Proprietary maturity models, vendor whitepapers, sales reports used as proof of effectiveness.
- **Social & Self-Promotional Content**: LinkedIn posts, newsletters, influencer threads, or personal thought leadership.

---

## Included Domain Skills

This repository provides four specialized domain skills in `./skills/`:

- **`people-science-core-reasoning`** (`./skills/people-science-core-reasoning/SKILL.md`): Foundational reasoning model for any people-related decision.
- **`compensation-decisioning`** (`./skills/compensation-decisioning/SKILL.md`): Pay structures, internal equity, market positioning, incentives, and behavioral consequences.
- **`hr-analytics-decisioning`** (`./skills/hr-analytics-decisioning/SKILL.md`): Translating people questions into measurable variables, analytical designs, statistical models, and decision systems.
- **`organizational-behavior-decisioning`** (`./skills/organizational-behavior-decisioning/SKILL.md`): Distinguishing behavioral mechanisms from assumptions, evaluating culture, motivation, leadership, and interventions.
