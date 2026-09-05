# People Science Skills — Core Reasoning Skill

**Better questions → Better reasoning → Better decisions → Better decision systems.**

This is a foundational agent skill for anyone working with AI on people-related decisions: HR, compensation, talent, organizational behavior, workforce analytics, and people strategy.

It does **not** turn the agent into an “HR expert.”  
It forces the agent to reason more carefully, rigorously, and transparently about people.

## When to use this skill

Load this skill whenever the task involves:

- People, work, or organizations
- HR, compensation, talent, or workforce decisions
- Organizational behavior or people analytics questions
- Designing policies, interventions, or decision systems that affect employees

## Core Philosophy

People and organizations are complex.  
Good decisions start with better questions and are grounded in:

1. Human Behavior & Psychology  
2. First-Principles Thinking  
3. Evidence & Empirical Research

Everything else (frameworks, models, recommendations, policies) is an *output* of this reasoning, not a starting point.

## The Reasoning Sequence

**Question → Behavior → First Principles → Evidence → Context → Alternatives → Trade-offs → Decision → Repeatability**

The skill systematically challenges conventional HR practices, forces distinction between constructs and observable behavior, demands evidence classification, surfaces alternative explanations, and evaluates trade-offs and unintended consequences.

## Key Guardrails

- Do not diagnose individuals from workplace data
- Do not treat “industry standard” as scientific validation
- Prefer observable behavior over abstract constructs
- Make uncertainty and assumptions visible
- Preserve human judgment where evidence is incomplete

## Installation

### One-command (recommended)

```bash
npx skills add https://github.com/rewardsdna/people-science-skills --skill people-science-core-reasoning
```

### Manual

Copy the `people-science-core-reasoning/` folder into your agent’s skills directory:

| Agent              | Path                          |
|--------------------|-------------------------------|
| Claude / Claude Code | `~/.claude/skills/` or `.claude/skills/` |
| Cursor             | `~/.cursor/skills/` or `.cursor/skills/` |
| Grok / xAI         | `~/.grok/skills/` or `.grok/skills/` |
| Codex / others     | `.agents/skills/` or check docs |

## Structure

```
people-science-core-reasoning/
├── SKILL.md          # Full reasoning instructions (loaded by agents)
└── README.md         # This file
```

## Version

v0.1 — Core Reasoning Skill

## License

MIT

## Guiding Principle

Better questions → Better reasoning → Better decisions → Better decision systems.
