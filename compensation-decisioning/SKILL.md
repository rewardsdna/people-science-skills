---
name: compensation-decisioning
description: Apply compensation science to pay structures, internal equity, market positioning, incentives, and behavioral consequences. Use with people-science-core-reasoning when analyzing pay, designing salary bands, evaluating equity, modeling incentives, or deciding pay increases and total rewards.
license: MIT
---

# Compensation Decisioning Skill

**Builds on:** `people-science-core-reasoning`

Use this skill together with the Core Reasoning skill whenever the decision involves pay, total rewards, incentives, equity, or compensation philosophy.

## Purpose

Help the agent reason rigorously about compensation decisions by applying:

- Behavioral consequences of pay systems
- Internal equity vs market positioning
- Incentive design and unintended effects
- Evidence on what pay actually influences

This is not a “how to build a salary structure” manual. It is a decisioning layer that forces better questions and clearer mechanisms.

## Core Questions for Any Compensation Decision

Always start with the Core Reasoning sequence, then focus on these compensation-specific questions:

1. **What behavior are we trying to influence?**
   - Attraction, retention, effort, collaboration, skill acquisition, risk-taking, long-term orientation, etc.

2. **What is the actual mechanism?**
   - Is pay expected to work through fairness perceptions, opportunity cost, signaling, sorting, or reinforcement?
   - Distinguish stated preferences from observed responses.

3. **Internal equity vs external market**
   - How large is the tension between internal consistency and market rates?
   - Which matters more for the specific role and context?

4. **What are the unintended behavioral consequences?**
   - Gaming, reduced cooperation, short-termism, adverse selection, entitlement effects, etc.

## Key Distinctions

| Concept | Clarification |
|---------|---------------|
| Pay level | Absolute amount relative to market |
| Pay structure | Relativities, grades, bands, differentials |
| Pay mix | Base vs variable vs equity vs benefits |
| Internal equity | Consistency of pay for similar contribution / level / skill |
| External competitiveness | Position relative to relevant labor market |
| Compa-ratio | Actual pay / midpoint (or market reference) |
| Incentive intensity | Strength of link between performance and reward |

Treat each as a design choice with behavioral implications, not as an automatic best practice.

## Common Assumptions to Challenge

- “People leave primarily because of pay.”
- “High performers must receive larger increases.”
- “Market pricing alone produces fair outcomes.”
- “Variable pay always increases motivation.”
- “Equity creates long-term alignment.”
- “Transparency always improves fairness perceptions.”
- “Pay for performance is the same as meritocracy.”

Classify each claim (Strongly Supported / Supported / Plausible / Assumption / Unknown / Context-Dependent) using the Core Reasoning evidence framework.

## Incentive Design Guardrails

When designing or evaluating incentives:

- Specify the target behavior in observable terms.
- Identify what the incentive will *also* reward or punish.
- Consider measurement quality and gaming potential.
- Examine time horizon (short-term vs long-term behavior).
- Assess whether the incentive crowds out other motives.
- Evaluate distributional effects (who gains, who loses relative standing).

## Internal Equity Analysis

When examining equity:

- Define the relevant comparison group carefully.
- Separate legitimate differences (skill, performance, market, scarcity) from noise or bias.
- Prefer statistical controls and job evaluation logic over pure title matching.
- Report both raw and adjusted gaps where data allows.
- Distinguish fairness perceptions from statistical parity.

## Decision Output Format

When making a compensation recommendation, structure as:

1. **Decision being made**
2. **Target behavior(s)**
3. **Proposed mechanism** (how pay is expected to work)
4. **Evidence status** of the key assumptions
5. **Internal equity implications**
6. **Market positioning implications**
7. **Likely unintended consequences**
8. **What should be monitored or tested**
9. **Repeatable rule or principle** (if applicable)

## Integration with Core Reasoning

Always run the full Core Reasoning sequence first.  
This skill only adds the compensation-specific lenses and distinctions.

## Guiding Principle

Pay systems are behavioral systems. Design them as such.
