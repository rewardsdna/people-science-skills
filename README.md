# People Science Skills

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Compatible-blue)

**Better questions → Better reasoning → Better decisions → Better decision systems.**

A collection of open agent skills that help AI systems reason more carefully about people, work, organizations, HR, compensation, talent, analytics, and workforce decisions.

These skills do **not** turn an agent into an "HR expert."  
They force better questions, clearer mechanisms, stronger evidence standards, scientific integrity, zero fluff, and transparent decision-making.

---

## 🚀 Quick Install

### Universal / CLI (Recommended)

Install via `skills` CLI:

```bash
# Interactive selection (pick skills from list)
npx skills add https://github.com/rewardsdna/people-science-skills

# Or install individual skills directly:
npx skills add https://github.com/rewardsdna/people-science-skills --skill people-science-core-reasoning
npx skills add https://github.com/rewardsdna/people-science-skills --skill compensation-decisioning
npx skills add https://github.com/rewardsdna/people-science-skills --skill hr-analytics-decisioning
npx skills add https://github.com/rewardsdna/people-science-skills --skill organizational-behavior-decisioning
```

### Manual Installation

Clone the repository and copy the target skill folder into your agent's skills directory:

```bash
# ~/.claude/skills/   (Claude / Claude Code)
# ~/.cursor/skills/   (Cursor)
# ~/.grok/skills/     (Grok)
# .agents/skills/     (Universal Agent Skills location)
```

---

## 📦 Skills Included

| Skill | Description | When to Use |
|-------|-------------|-------------|
| **[people-science-skills](./SKILL.md)** | Root Master Skill combining core reasoning and scientific integrity | Marketplace registration, indexers, and broad people decisions |
| **[people-science-core-reasoning](./skills/people-science-core-reasoning/)** | Foundational reasoning model for any people-related decision | Always — load this first for HR, talent, org behavior, or compensation questions |
| **[compensation-decisioning](./skills/compensation-decisioning/)** | Pay structures, internal equity, market positioning, incentives, and behavioral consequences | Analyzing or designing pay systems, equity, incentives, or total rewards |
| **[hr-analytics-decisioning](./skills/hr-analytics-decisioning/)** | Translating people questions into measurable variables, analytical designs, and decisions | Turning HR questions into metrics, research designs, models, or decision systems |
| **[organizational-behavior-decisioning](./skills/organizational-behavior-decisioning/)** | Distinguishing behavioral mechanisms from assumptions, evaluating culture, motivation, leadership, and interventions | Analyzing culture, engagement, motivation, team dynamics, leadership, or change interventions |

---

## 🧠 The 4 Core Pillars of Rigor

Every skill in this repository is built around four fundamental operational pillars:

```text
┌─────────────────────────┬─────────────────────────┬─────────────────────────┬─────────────────────────┐
│ 🔁 Scientific          │ ⚡ Cognitive           │ 🛡️ Hallucination        │ 💼 Executive            │
│    Repeatability        │    Efficiency           │    Prevention           │    Usability            │
├─────────────────────────┼─────────────────────────┼─────────────────────────┼─────────────────────────┤
│ • Evidence Gatekeeping  │ • Zero Consulting Fluff │ • No Fake Statistics    │ • BLUF Executive Summary│
│ • Deterministic Rules   │ • High Token Density    │ • Explicit Source Tags  │ • 3-Column Options Table│
│ • Pilot Requirements    │ • BLUF Formatting       │ • Anti-Pop-HR Exclusions│ • 30-60-90 Day Roadmap  │
└─────────────────────────┴─────────────────────────┴─────────────────────────┴─────────────────────────┘
```

### 1. 🔁 Scientific Repeatability & Evidence Gatekeeping
- **Requires Evidence Before Intervention**: Forbids recommending full-scale policy or reward overhauls without baseline empirical proof. Recommends Diagnostic Audits or Pilots when data is incomplete.
- **The Evidence Gatekeeper Condition**: Every recommendation specifies an explicit Gatekeeper Condition (*"Do NOT authorize full implementation of Intervention X until Data Benchmark Y is verified"*).
- **Correlation vs. Causation Filter**: Enforces associative language ("is correlated with") for observational workforce data.

### 2. ⚡ Cognitive Efficiency & Zero Consulting Boilerplate
- **Zero Filler**: Eliminates conversational fluff (*"In today's fast-paced corporate environment..."*) and starts responses immediately with the decision.
- **High Token-Density Formatting**: Uses structured Markdown tables, bulleted mechanisms, and bold key terms to maximize readability and inference speed.

### 3. 🛡️ Hallucination Prevention & Source Tagging
- **No Synthetic Statistics or Fake Citations**: Forbids generating fake percentages or fabricated academic studies.
- **Mandatory Source Tagging**: Classifies all claims into `[Empirical Consensus]`, `[User-Supplied Data]`, or `[Unverified Hypothesis]`.
- **Deliberate Exclusions**: Explicitly rejects Pop HR, Pop Psychology, vendor marketing reports, and LinkedIn influencer trends.

### 4. 💼 Executive Usability & Decision Mandate
- **Make an Actual Decision**: Rejects vague "it depends" hedging; forces a concrete **Recommended Decision**.
- **Mandatory 4-Part Output Structure**:
  1. **🎯 Executive Summary (BLUF)**: 2-sentence Bottom-Line Up Front with Gatekeeper Condition.
  2. **📊 Options & Decision Matrix**: 3-Column comparative table (`Option` | `Behavioral Mechanism` | `Key Risk & Trade-off`).
  3. **🔬 Evidence & Causal Discipline Audit**: Associative language check and evidence classification.
  4. **📅 30-60-90 Day Operational Roadmap**: Clear execution steps from audit $\rightarrow$ pilot $\rightarrow$ scaling.

---

## 🧪 Evaluation Suite (`evals/`)

This repository includes automated evaluation test cases in `evals/` to benchmark LLM reasoning:
- **`evals/reasoning.json`**: Evaluates causal logic, incentive mechanics, evidence gatekeeping, and decision systems.
- **`evals/scientific-integrity.json`**: Evaluates rejection of Pop HR, vendor claims, fake statistics, and LinkedIn myths.

---

## 📁 Repository Structure

```text
├── SKILL.md                                         # Root Master Skill (LobeHub / AgentSkill.sh)
├── README.md                                        # Repository Catalog
├── LICENSE                                          # MIT License
├── .gitignore
├── core/                                            # Shared Policy Framework
│   ├── reasoning-policy.md
│   ├── evidence-policy.md
│   ├── scientific-integrity.md
│   └── repeatability-policy.md
├── skills/                                          # Standardized Skill Modules
│   ├── people-science-core-reasoning/
│   ├── compensation-decisioning/
│   ├── hr-analytics-decisioning/
│   └── organizational-behavior-decisioning/
└── evals/                                           # Evaluation & Benchmark Suite
    ├── reasoning.json
    └── scientific-integrity.json
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).