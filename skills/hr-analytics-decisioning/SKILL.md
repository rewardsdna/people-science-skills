---
name: hr-analytics-decisioning
description: Translate Human Resources and people analytics questions into measurable variables, analytical designs, statistical models, workforce metrics, and data-driven decisions. Use with people-science-core-reasoning when turning HR questions into research designs or decision systems.
license: MIT
---

# HR Analytics Decisioning Skill

**Builds on:** `people-science-core-reasoning`

Use this skill whenever the work involves translating a people-related question into data, metrics, analysis, or a decision system.

---

## 🎯 Executive Usability Mandate

1. **Zero Consulting Boilerplate**: Start responses immediately with the analytical decision and metric design.
2. **Make an Actual Decision**: Recommend a specific analytical model or research design. Specify the decision threshold.
3. **No Synthetic Statistics**: Never fabricate statistical results or data outputs.

---

## 🔬 Mandatory Required Output Structure

Every response MUST follow this structure:

### 1. 🎯 Executive Summary (BLUF)
- **Recommended Analytical Decision**: [Clear 1-sentence decision]
- **Unit of Analysis & Metric**: [Individual / Team / Org metric definition]
- **Key Data Risk**: [Confounding, selection bias, or missing data risk]

### 2. 📊 Analytical Options & Decision Matrix
| Analytical Option | Primary Statistical Mechanism | Key Risk & Confounder | Recommendation Tier |
|---|---|---|---|
| **Option A (Simple Parsimonious Model)** | [Mechanism] | [Risk] | ✅ Recommended |
| **Option B (Predictive ML Model)** | [Mechanism] | [Black-box risk] | ⚠️ Secondary |
| **Option C (Raw Unadjusted Averages)** | [Mechanism] | [Selection bias] | ❌ Rejected |

### 3. 🔬 Evidence & Causal Discipline Audit
1. **Association vs. Causation**: Explicitly separate correlation from causal inference.
2. **Confounding & Selection Bias**: Identify at least two confounders or reverse causality vectors.
3. **Evidence Classification**: Grade evidence explicitly (Strongly Supported / Plausible / Assumption / Unknown).

### 4. 📅 30-60-90 Day Analytical Roadmap
- **Days 1–30**: Data quality audit, missingness check, and unit of analysis alignment.
- **Days 31–60**: Execute analytical model and robustness validation.
- **Days 61–90**: Establish automated reproducible pipeline, monitoring dashboard, and human oversight.
