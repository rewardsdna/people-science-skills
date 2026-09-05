# People Science Skills

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Compatible-blue)

**Better questions → Better reasoning → Better decisions → Better decision systems.**

A collection of open agent skills that help AI systems reason more carefully about people, work, organizations, HR, compensation, talent, analytics, and workforce decisions.

These skills do **not** turn an agent into an "HR expert."  
They force better questions, clearer mechanisms, stronger evidence standards, scientific integrity, and transparent decision-making.

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

## 🧠 Core Philosophy & Scientific Integrity

People and organizations are complex systems. Good decisions start with better questions and are grounded in:

1. **Human Behavior & Psychology**
2. **First-Principles Thinking**
3. **Evidence & Empirical Research**

### The Reasoning Sequence

> **Question → Behavior → First Principles → Evidence → Context → Alternatives → Trade-offs → Decision → Repeatability**

### Scientific Integrity Guardrails

This project deliberately excludes pop HR, pop psychology, vendor marketing material, content marketing, and social media popularity as substitutes for empirical evidence:
- **No Pop HR**: Rejects universal "best practice" formulas and generational stereotypes.
- **No Pop Psychology**: Rejects viral diagnostic labels and unvalidated personality tests.
- **No Vendor Marketing**: Rejects sales reports and vendor maturity models as empirical proof.
- **Statistical Discipline**: Forces clear separation of correlation vs. causation.

---

## 🧪 Evaluation Suite (`evals/`)

This repository includes automated evaluation test cases in `evals/` to benchmark LLM reasoning:
- **`evals/reasoning.json`**: Evaluates causal logic, incentive mechanics, and decision systems.
- **`evals/scientific-integrity.json`**: Evaluates rejection of Pop HR, vendor claims, and LinkedIn myths.

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