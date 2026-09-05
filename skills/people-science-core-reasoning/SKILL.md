---
name: people-science-core-reasoning
description: Core reasoning skill for people, work, organizations, HR, compensation, talent, and organizational behavior decisions. Use whenever an agent answers questions, analyzes problems, or designs decisions involving people. Grounds reasoning in human behavior, first principles, and evidence rather than conventional HR practices.
license: MIT
---

# People Science Skills — Core Reasoning Skill (v0.1)

## Purpose

Use this skill whenever an AI agent is helping answer a question, analyze a problem, or design a decision involving people, work, organizations, HR, compensation, talent, or organizational behavior.

The purpose is **not** to make the agent behave like an HR expert.  
The purpose is to help the agent **reason better** about people-related decisions.

## Core Philosophy

Better HR decisions begin with better questions.

People are complex. Organizations are complex.  
HR decisions should therefore be grounded in:

1. Human Behavior & Psychology
2. First-Principles Thinking
3. Evidence & Empirical Research

Everything else is an output.  
Models, frameworks, analyses, recommendations, policies, interventions, and decision systems should emerge from these foundations rather than replace them.

## The Core Reasoning Model

For people-related decisions, reason through this sequence:

**Question → Behavior → First Principles → Evidence → Context → Alternatives → Trade-offs → Decision → Repeatability**

Do not automatically follow conventional HR practices merely because they are common.

### 1. QUESTION

First identify the decision that actually needs to be made.

Ask:
- What are we trying to decide?
- Why does the decision matter?
- What outcome are we trying to influence?
- Who or what is affected?
- What information is available?
- What constraints exist?

Distinguish between:
- the stated question
- the underlying problem
- the actual decision

Do not solve a more convenient question simply because it is easier to answer.

**Example**  
Stated question: "How can we improve employee engagement?"

Possible underlying decisions:
- Should we change manager practices?
- Should we change job design?
- Should we change rewards?
- Should we change workload?
- Should we improve communication?
- Should we measure engagement differently?

The first task is therefore to identify what decision is actually being considered.

### 2. BEHAVIOR

Translate abstract HR concepts into observable behavior whenever possible.

Ask:
- What are people actually doing?
- What behavior needs to change?
- What behavior is currently being reinforced?
- What behavior is being discouraged?
- What choices are people making?
- What environmental conditions influence those choices?

Do not assume that an HR construct automatically explains behavior.

For example: "Low engagement" is not itself an explanation. Investigate what observable behaviors or experiences are represented by the measure.

Possible behaviors may include:
- reduced discretionary effort
- lower participation
- increased absence
- reduced collaboration
- reduced persistence
- increased job searching
- lower manager interaction

### 3. FIRST-PRINCIPLES THINKING

Separate fundamental mechanisms from inherited assumptions.

Ask: What must actually be true for this explanation to work?

Challenge statements such as:
- "Employees are motivated by money."
- "People leave because of compensation."
- "More training improves performance."
- "High performers should receive larger increases."
- "Engagement causes retention."
- "Employees want flexibility."
- "Managers need more accountability."

Treat these as hypotheses, not facts.

Break the problem into its fundamental components.  
Prefer "What causes the behavior?" over "What does HR normally do about this?"

### 4. EVIDENCE

Distinguish what is known from what is assumed.

Classify important claims as:

| Classification | Meaning |
|----------------|---------|
| Strongly Supported | Consistent with substantial and credible empirical evidence |
| Supported | Evidence exists but has meaningful limitations or context dependencies |
| Plausible | Consistent with theory, limited evidence, or reasonable mechanisms, but not sufficiently established |
| Assumption | A premise supplied by the user, organization, or analysis that has not been independently established |
| Unknown | Insufficient evidence to make a reliable determination |
| Context-Dependent | The answer cannot reasonably be determined without organizational or situational information |

Do not manufacture certainty.

When evidence is available, prefer:
- empirical research
- systematic reviews
- meta-analyses
- high-quality organizational data
- well-designed experiments
- quasi-experimental evidence
- credible longitudinal studies

Be cautious with:
- anecdotes
- unsupported expert claims
- correlations presented as causes
- small or biased samples
- generic "best practices"
- vendor claims
- isolated case studies

### 5. STATISTICAL AND ANALYTICAL DISCIPLINE

When quantitative evidence is involved:
- Inspect the data before interpreting it.
- Understand the unit of analysis.
- Check sample size and missingness.
- Examine distributions where relevant.
- Distinguish correlation from causation.
- Consider confounding variables.
- Consider selection effects.
- Consider measurement quality.
- Report uncertainty where meaningful.
- Distinguish statistical significance from practical significance.
- Prefer simple methods when they adequately answer the question.
- Do not use model complexity as a substitute for understanding the problem.

Never infer more than the data can support.

### 6. CONTEXT

Human behavior occurs within systems.

Consider relevant contextual factors such as:
- organizational structure
- leadership
- managers
- job design
- workload
- resources
- incentives
- norms
- culture
- power
- policies
- labor market
- employee characteristics
- organizational strategy
- technology
- timing
- economic conditions

Do not assume that a finding observed in one population or organization will automatically generalize to another.

Ask: What would have to be true in this context for the conclusion to hold?

### 7. ALTERNATIVE EXPLANATIONS

Before accepting a preferred explanation, identify plausible alternatives.

Ask: What else could explain this observation?

For important decisions, consider at least one credible competing explanation when appropriate.

**Example**  
Observation: Employees receiving lower pay increases are more likely to leave.

Possible explanations include:
- lower pay causes turnover
- poor performers receive lower increases and are also more likely to leave
- employees with scarce external opportunities receive higher increases
- managers allocate increases differently
- tenure or job level affects both pay increases and turnover
- employees who intend to leave behave differently before the pay decision

Do not confuse an observed association with the mechanism producing it.

### 8. TRADE-OFFS AND UNINTENDED CONSEQUENCES

Every intervention can change behavior in more than one way.

Before recommending an intervention, ask:
- What behavior might this encourage?
- What behavior might it discourage?
- Who benefits?
- Who may be disadvantaged?
- What unintended behavior could emerge?
- What might employees optimize for?
- Could the intervention undermine another organizational objective?
- What happens if people respond strategically?

A successful intervention is not simply one that improves the target metric. It should also be evaluated for its broader behavioral and organizational consequences.

### 9. DECISION

Only after considering behavior, first principles, evidence, context, alternatives, and trade-offs should the agent recommend an action.

A recommendation should distinguish between:
- **What the evidence suggests** — What we have good reason to believe.
- **What depends on assumptions** — What must be true for the recommendation to work.
- **What requires organizational judgment** — What evidence cannot determine by itself.
- **What should be tested** — What remains uncertain and can reasonably be investigated.

The agent should make the reasoning visible.  
Do not present a recommendation as inevitable when reasonable alternatives exist.

### 10. REPEATABILITY

When a decision will occur repeatedly, consider whether the reasoning can be converted into a repeatable decision system.

A decision system may include:
- definitions
- inputs
- metrics
- rules
- thresholds
- models
- workflows
- exception handling
- human review
- documentation
- monitoring
- feedback loops

A one-off analysis answers: "What should we do this time?"  
A decision system helps answer: "How should we make this type of decision repeatedly?"

Do not automate judgment merely because a process can be automated.  
Automate consistency where appropriate while preserving human judgment where context matters.

## HUMAN JUDGMENT

Evidence informs decisions. Evidence does not eliminate judgment.

Where evidence is incomplete, ambiguous, conflicting, or context-dependent:
1. make the uncertainty visible
2. identify the relevant assumptions
3. explain the trade-offs
4. preserve appropriate human judgment

Do not hide uncertainty behind numerical precision or authoritative language.

## BEHAVIORAL SCIENCE GUARDRAILS

When reasoning about people:
- Do not diagnose individuals from workplace behavior or organizational data.
- Do not infer personality from isolated observations.
- Do not reduce complex behavior to a single psychological trait.
- Consider situational explanations alongside individual explanations.
- Distinguish constructs from labels.
- Do not present psychological theories as established facts without appropriate evidence.
- Avoid deterministic claims about human behavior.
- Recognize that people adapt to incentives, systems, rules, and measurement.
- Consider strategic responses to interventions.
- Consider differences between stated preferences and observed behavior.
- Avoid assuming that what people say causes behavior is necessarily the mechanism causing behavior.

## HR PRACTICE GUARDRAILS

Do not treat common HR practices as self-validating.

"Industry standard" does not mean:
- scientifically supported
- causally effective
- appropriate for every organization
- optimal for the stated objective

When a conventional practice is proposed, ask:  
What problem is this practice intended to solve?  
Then ask:  
What evidence suggests that this mechanism actually solves that problem?

## OUTPUT PRINCIPLE

The agent should optimize for:

**Clarity + Evidence + Practicality + Transparency + Repeatability**

not:

**Complexity + Authority + Certainty**

A simple decision supported by strong reasoning is preferable to a sophisticated framework with weak foundations.

## DEFAULT RESPONSE STRUCTURE

When appropriate, structure reasoning as:

1. **The question** — What decision are we actually trying to make?
2. **The behavior** — What human behavior matters?
3. **The mechanism** — What could plausibly explain that behavior?
4. **The evidence** — What do we know, and how strong is the evidence?
5. **The context** — What organizational conditions matter?
6. **Alternatives** — What else could explain the observation?
7. **Trade-offs** — What could happen if we intervene?
8. **Decision** — What should we do given the evidence and context?
9. **Repeatability** — Can the reasoning be converted into a consistent decision process?

Use only the sections necessary for the problem. Do not mechanically display every section for simple questions.

## THE CORE RULE

When faced with an HR question:

- Do not start with the HR practice. Start with the question.
- Then: Do not start with the solution. Start with the behavior.
- Then: Do not start with convention. Start with first principles.
- Then: Do not start with belief. Start with evidence.
- Finally: Do not stop at analysis. Translate good reasoning into a practical decision.
- And where the decision repeats: Turn good reasoning into a transparent and repeatable decision system.

## Guiding Principle

**Better questions → Better reasoning → Better decisions → Better decision systems.**
