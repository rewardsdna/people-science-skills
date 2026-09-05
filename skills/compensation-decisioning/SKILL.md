---
name: compensation-decisioning
description: Apply compensation science to Human Resources, pay structures, internal equity, market positioning, incentives, bonuses, salary bands, total rewards, and behavioral consequences. Use with people-science-core-reasoning when analyzing pay, designing salary structures, evaluating pay equity, or modeling incentives.
license: MIT
---

# Compensation Decisioning Skill

**Builds on:** `people-science-core-reasoning`

Use this skill together with the Core Reasoning skill whenever the decision involves pay, total rewards, incentives, equity, or compensation philosophy.

---

## 🎯 Executive Usability & Decision Mandate

1. **Zero Consulting Boilerplate**: Start responses immediately with the pay decision. Forbid conversational filler.
2. **Make an Actual Decision (No Premature Restructuring)**: State an explicit **Recommended Compensation Decision**. If internal pay equity data or benchmark complexity is unverified, do NOT jump prematurely to a full-scale pay restructure; recommend a **Pay Equity & Benchmark Audit** or **Targeted Cohort Pilot** as the primary decision.
3. **The Evidence Gatekeeper Condition**: Every recommendation MUST specify an explicit Gatekeeper Condition: *"Do NOT authorize full implementation of [Pay Restructure X] until [Compensation Data Point Y] is verified."*
4. **No Synthetic Statistics**: Never fabricate percentage figures or benchmark survey data.

---

## 🔬 Mandatory Required Output Structure

Every response MUST follow this structure:

### 1. 🎯 Executive Summary (BLUF)
- **Recommended Compensation Decision**: [Clear 1-sentence decision; Audit / Pilot if data is incomplete]
- **Incentive Behavioral Mechanism**: [How compensation alters behavior vs. non-monetary factors]
- **Gatekeeper Condition**: [Explicit data point required before full rollout]

### 2. 📊 Compensation Options & Decision Matrix
| Option | Primary Behavioral Mechanism | Key Risk & Trade-off | Recommendation Tier |
|---|---|---|---|
| **Option A (Targeted Pay Adjustment)** | [Mechanism] | [Risk] | ✅ Recommended |
| **Option B (Variable Incentive)** | [Mechanism] | [Risk] | ⚠️ Secondary |
| **Option C (Across-the-Board Raise)** | [Mechanism] | [Risk] | ❌ Rejected |

### 3. 🔬 Evidence & Causal Discipline Audit
1. **Association vs. Causation**: Audit observational pay data. Use associative language.
2. **Confounding & Reverse Causality**: Identify at least two confounders (e.g., role complexity, baseline performance, market rate shifts).
3. **Evidence Tiers & Gatekeeper**: Grade evidence explicitly (Strongly Supported / Plausible / Assumption / Unknown) and state the baseline data requirement.

### 4. 📅 30-60-90 Day Implementation Roadmap
- **Days 1–30**: Pay equity, internal alignment, and Gatekeeper verification.
- **Days 31–60**: Pilot compensation structure on target benchmark roles.
- **Days 61–90**: Evaluate retention impact, budget sustainability, and Goodhart's Law gaming.
