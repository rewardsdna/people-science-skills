# Universal / most common
npx skills add https://github.com/YOUR-USERNAME/people-science-skills --skill people-science-skills

# Or simply clone and copy the folder into:
# ~/.claude/skills/   (Claude / Claude Code)
# ~/.cursor/skills/   (Cursor)
# ~/.grok/skills/     (Grok)
# .agents/skills/     (many other agents)


![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Compatible-blue)



-----------


Suggested topics / tags:
textagent-skills
skill-md
hr
people-analytics
compensation
organizational-behavior
talent
workforce
decision-making
behavioral-science



# People Science Skills

**Better questions → Better reasoning → Better decisions → Better decision systems.**

A collection of agent skills that help AI systems reason more carefully about people, work, organizations, HR, compensation, talent, and workforce decisions.

These skills do **not** turn an agent into an “HR expert.”  
They force better questions, clearer mechanisms, stronger evidence standards, and more transparent decision-making.

## Skills Included

| Skill | Description | When to use |
|-------|-------------|-------------|
| **[people-science-core-reasoning](./people-science-core-reasoning/)** | Foundational reasoning model for any people-related decision | Always — load this first for HR, talent, org behavior, or compensation questions |
| **[compensation-decisioning](./compensation-decisioning/)** | Pay structures, internal equity, market positioning, incentives, and behavioral consequences | Analyzing or designing pay systems, equity, incentives, or total rewards |
| **[hr-analytics-decisioning](./hr-analytics-decisioning/)** | Translating people questions into measurable variables, analytical designs, and decisions | Turning HR questions into metrics, research designs, models, or decision systems |

## Core Philosophy

People and organizations are complex.  
Good decisions start with better questions and are grounded in:

1. **Human Behavior & Psychology**
2. **First-Principles Thinking**
3. **Evidence & Empirical Research**

Everything else — frameworks, models, policies, recommendations — is an *output* of this reasoning, not a starting point.

### The Reasoning Sequence

**Question → Behavior → First Principles → Evidence → Context → Alternatives → Trade-offs → Decision → Repeatability**

## Installation

### One-command (recommended)

```bash
# Install the core skill
npx skills add https://github.com/YOUR-USERNAME/people-science-skills --skill people-science-core-reasoning

# Install the companions
npx skills add https://github.com/YOUR-USERNAME/people-science-skills --skill compensation-decisioning
npx skills add https://github.com/YOUR-USERNAME/people-science-skills --skill hr-analytics-decisioning