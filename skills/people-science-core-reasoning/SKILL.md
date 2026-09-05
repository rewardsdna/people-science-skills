---
name: people-science-core-reasoning
description: Core reasoning skill for Human Resources (HR), compensation, talent management, workforce decisions, and organizational behavior. Use whenever an agent answers questions, analyzes problems, or designs decisions involving people. Grounds reasoning in human behavior, first principles, and evidence rather than conventional HR practices.
license: MIT
---

# People Science Skills — Core Reasoning Skill

## Purpose

Use this skill whenever an AI agent is helping answer a question, analyze a problem, or design a decision involving people, work, organizations, HR, compensation, talent, or organizational behavior.

The purpose is **not** to make the agent behave like a conventional HR consultant.  
The purpose is to help the agent **make actionable, evidence-based decisions** about people.

---

## 🎯 Executive Usability & Decision Mandate

1. **Zero Consulting Boilerplate**: Start responses immediately with the decision. Forbid conversational filler ("In today's fast-paced environment...").
2. **Make an Actual Decision (No Premature Jumps)**: State an explicit **Recommended Decision**. If baseline data or evidence is missing, do NOT jump prematurely to a full-scale policy change; recommend a **Diagnostic Audit** or **Small-Scale Pilot** as the primary decision.
3. **The Evidence Gatekeeper Condition**: Every recommendation MUST specify an explicit Gatekeeper Condition: *"Do NOT authorize full implementation of [Intervention X] until [Data Point Y] is verified."*
4. **No Synthetic Statistics**: Never fabricate percentage figures or fake study citations. Tag claims (`[Empirical Consensus]`, `[User-Supplied Data]`, `[Unverified Hypothesis]`).

---

## The Core Reasoning Sequence

**Question → Behavior → First Principles → Evidence → Context → Alternatives → Trade-offs → Decision → Repeatability**

---

## 🔬 Mandatory Required Output Structure

Every comprehensive response MUST follow this structure:

### 1. 🎯 Executive Summary (BLUF)
- **Recommended Decision**: [Clear 1-sentence decision; Diagnostic Audit / Pilot if data is incomplete]
- **Behavioral Rationale**: [Primary psychological/behavioral mechanism]
- **Gatekeeper Condition**: [Explicit condition required before full rollout]

### 2. 📊 Options & Decision Matrix
| Option | Primary Behavioral Mechanism | Key Risk & Trade-off | Recommendation Tier |
|---|---|---|---|
| **Option A (Recommended)** | [Mechanism] | [Risk] | ✅ Recommended |
| **Option B (Alternative)** | [Mechanism] | [Risk] | ⚠️ Secondary |
| **Option C (Status Quo)** | [Mechanism] | [Risk] | ❌ Rejected |

### 3. 🔬 Evidence & Causal Discipline Audit
1. **Association vs. Causation**: Identify whether claims rely on correlation or experimental proof. Use associative language for observational data.
2. **Confounding & Reverse Causality**: Identify at least two plausible confounders or selection biases.
3. **Evidence Tiers & Gatekeeper**: Grade evidence explicitly (Strongly Supported / Plausible / Assumption / Unknown) and state the baseline data requirement.

### 4. 📅 30-60-90 Day Operational Roadmap
- **Days 1–30**: Baseline audit, data checks, and Gatekeeper verification.
- **Days 31–60**: Pilot intervention on target cohort.
- **Days 61–90**: Impact evaluation, Goodhart's Law audit, and process scaling.

---

## Scientific Integrity Guardrails

**Do NOT use the following as substitutes for scientific evidence:**
- **Pop HR**: Universal "best practices", fashionable trends, generic formulas, generational myths.
- **Pop Psychology**: Viral psychological labels, unsupported personality tests, casual diagnostics.
- **Vendor Marketing Material**: Proprietary maturity models, vendor whitepapers, sales reports used as proof.
- **Social Content**: LinkedIn posts, newsletters, influencer threads, or personal thought leadership.
