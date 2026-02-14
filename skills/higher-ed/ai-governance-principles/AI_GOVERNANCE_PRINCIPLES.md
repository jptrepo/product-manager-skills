# AI Governance Principles for Higher Education

**A rubric for evaluating AI-related IT requests in academic institutions**

---

## Purpose

This document establishes governance principles and evaluation criteria for AI-related technology requests in higher education environments. Use this as a rubric when any request involves artificial intelligence capabilities, machine learning systems, or AI-powered tools. **All AI requests require review and sign-off by the AI Governance Committee.**

---

## What Qualifies as an "AI Request"

A request requires AI committee review if it involves:

- **Generative AI tools** (text, image, video, code generation)
- **Machine learning systems** (predictive analytics, recommendation engines, automated decision-making)
- **Natural language processing** (chatbots, virtual assistants, sentiment analysis)
- **Computer vision** (facial recognition, image analysis, object detection)
- **AI-powered automation** (robotic process automation with learning capabilities)
- **Third-party AI services** (APIs, SaaS tools with AI features)
- **Research AI infrastructure** (GPU clusters for AI/ML workloads)

---

## AI Governance Committee Review Process

### When AI Committee Review is Required

**Mandatory Review:**
- New AI tool or service procurement
- Expansion of existing AI tool to new use cases
- AI systems handling student data, faculty research data, or sensitive information
- AI tools with public-facing interfaces
- AI research infrastructure exceeding $10K

**Expedited Review (Fast-track with AI approval):**
- Access to approved campus AI tools for standard use cases
- AI tools for individual faculty research (non-human subjects)
- AI development environments for coursework

---

## Evaluation Rubric

The AI Committee evaluates requests using **six dimensions**. Each dimension is scored 1-3, and requests must meet threshold criteria for approval.

---

### 1. Educational & Research Value

**Purpose:** Does this AI capability advance the institution's academic mission?

| Score | Criteria |
|-------|----------|
| **High (3)** | Directly supports teaching, learning outcomes, or research breakthroughs |
| **Medium (2)** | Supports operational efficiency for academic units; indirect benefit |
| **Low (1)** | Administrative convenience only; no clear educational value |

**Key Questions:**
- What educational or research problem does this solve?
- How will student learning or faculty research improve?
- Will this advance institutional research capabilities?

---

### 2. Data Privacy & Security

**Purpose:** Does this protect student, faculty, and institutional data appropriately?

| Score | Criteria |
|-------|----------|
| **High (3)** | No PII/FERPA data; on-premises or federated learning; institutional data control |
| **Medium (2)** | FERPA-compliant third-party; BAA in place; data anonymization; clear retention policy |
| **Low (1)** | PII sent to third-party; unclear governance; no retention guarantees |

**Key Questions:**
- What data will the AI system access?
- Where is data processed and stored?
- Does vendor comply with FERPA, HIPAA (if applicable)?
- Can we delete data on request?
- Is data used to train vendor models?

**Red Flags:**
- Vendor retains rights to use institutional data for training
- Data sent to foreign jurisdictions with weak privacy laws
- No Business Associate Agreement (BAA) when handling protected data

---

### 3. Algorithmic Fairness & Bias

**Purpose:** Does this AI system treat all users equitably?

| Score | Criteria |
|-------|----------|
| **High (3)** | Bias audit completed; disparate impact analysis; human review; explainable AI |
| **Medium (2)** | Vendor transparency on training data; bias mitigation documented; appeal process |
| **Low (1)** | No bias assessment; black box algorithm; automated decisions without oversight |

**Key Questions:**
- Has the AI been tested for bias (race, gender, socioeconomic status, disability)?
- What training data was used?
- Are AI decisions explainable?
- Is there human oversight for high-stakes decisions?
- Can users appeal AI-generated outcomes?

**High-Risk Use Cases Requiring Enhanced Review:**
- Admissions or enrollment decisions
- Financial aid allocation
- Academic integrity detection
- Student success prediction
- Faculty hiring recommendations

---

### 4. Transparency & Explainability

**Purpose:** Can users understand how the AI works?

| Score | Criteria |
|-------|----------|
| **High (3)** | Open-source model; institutional documentation; user training; clear disclosure |
| **Medium (2)** | Vendor provides model cards; general explanation; users notified of AI use |
| **Low (1)** | Proprietary black box; no user notification; unclear decision-making |

**Disclosure Requirements:**
- Students must be notified if AI is used in grading or assessment
- Faculty must be informed if AI analyzes teaching effectiveness
- Research subjects must consent if AI processes their data
- Public-facing AI must identify as AI

---

### 5. Vendor Viability & Support

**Purpose:** Is this a sustainable, supportable solution?

| Score | Criteria |
|-------|----------|
| **High (3)** | Established vendor with higher-ed focus; responsive support; peer institutions use |
| **Medium (2)** | Emerging vendor with some higher-ed clients; adequate support |
| **Low (1)** | Startup with no higher-ed experience; unclear longevity; poor support |

**Key Questions:**
- How long has vendor been in business?
- Do peer institutions use this successfully?
- What is vendor's financial stability?
- What support SLAs are provided?

**Due Diligence Sources:**
- Educause AI Landscape review
- Internet2 community recommendations
- Peer institution reference checks (3+ similar institutions)

---

### 6. Institutional Control & Exit Strategy

**Purpose:** Can we maintain control and exit cleanly if needed?

| Score | Criteria |
|-------|----------|
| **High (3)** | Self-hosted or hybrid; data export available; no vendor lock-in |
| **Medium (2)** | Cloud-hosted with data portability; manageable transition |
| **Low (1)** | Vendor lock-in; proprietary format; no data export |

**Key Questions:**
- Can we export our data if we leave?
- Are there alternative vendors?
- What is the cost and complexity of switching?
- Do we own the AI-generated outputs?

---

## Scoring and Decision Framework

Each dimension scored 1-3 (Low, Medium, High). **Maximum score: 18**

| Total Score | Decision | Notes |
|-------------|----------|-------|
| **15-18** | **Approved** | Meets all or most criteria; low risk |
| **12-14** | **Conditional Approval** | Require mitigation plan for low-scoring dimensions |
| **9-11** | **Requires Enhancement** | Significant gaps; vendor must address concerns |
| **< 9** | **Not Approved** | Does not meet institutional standards |

**Special Cases:**
- **Data Privacy & Security = 1:** Automatic rejection unless compliance plan provided
- **Algorithmic Fairness & Bias = 1:** Rejection for high-stakes use cases

---

## Pre-Approved AI Tools (Fast-Track)

| Tool | Use Case | Restrictions |
|------|----------|--------------|
| **ChatGPT Enterprise** | Faculty research/course prep | No student PII, no grading |
| **GitHub Copilot** | Code assistance for CS courses | Instructor must disclose in syllabus |
| **Grammarly for Education** | Writing assistance | No thesis/dissertation content |

---

## Request Evaluation Workflow

```
Request Submitted → AI Committee Intake → Rubric Evaluation → 
Committee Decision → Implementation (if approved)
```

**Timeline:**
- **Standard Review:** 2-4 weeks
- **Expedited Review:** 1 week
- **Complex Review:** 4-8 weeks

---

## Example: AI Proctoring Software

| Dimension | Score | Rationale |
|-----------|-------|-----------|
| Educational Value | 2 | Supports exam integrity, doesn't improve learning |
| Data Privacy | 2 | FERPA-compliant but facial data to vendor cloud |
| Algorithmic Fairness | 1 | Known bias against students of color |
| Transparency | 2 | Vendor provides explanation but proprietary |
| Vendor Viability | 3 | Established, widely used |
| Control | 2 | Vendor lock-in but data export available |

**Total: 12 / 18** — **Conditional Approval**

**Required Mitigations:**
1. Vendor must conduct bias audit with our student demographics
2. Provide non-AI proctoring alternative for students who opt out
3. Disclose AI proctoring in syllabus
4. Faculty must review all AI flags before academic integrity action

---

## Ongoing Governance

- **Annual AI Review:** All approved tools reviewed yearly
- **Incident Reporting:** Report bias, breaches, vendor changes immediately
- **AI Registry:** All approved tools documented with restrictions

---

## References

### Related Skills
- **`it-request-template`** — Capture AI component in initial intake
- **`vendor-research`** — Evaluate using Educause, Internet2, peers
- **`it-governance-advisor`** — Route AI requests to committee
- **`risk-assessment-higher-ed`** — Assess broader IT risks

### External Resources
- EDUCAUSE AI Landscape
- Internet2 AI Community
- Partnership on AI (algorithmic fairness)
- NIST AI Risk Management Framework

---

**Version 1.0 | Last Updated: February 2026 | Owner: AI Governance Committee**

**This rubric must be referenced for all IT requests involving AI capabilities.**
