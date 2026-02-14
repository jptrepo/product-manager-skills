---
name: it-governance-advisor
description: Guide IT staff and requestors through decentralized higher education governance structures. Ask adaptive questions about request type, stakeholder complexity, and urgency, then recommend optimal routing and decision paths.
type: interactive
---


## Purpose
Guide IT staff and requestors through complex, decentralized higher education governance structures by asking adaptive questions about request characteristics, then recommending optimal routing paths, stakeholder engagement strategies, and decision-making processes. Use this to avoid governance bottlenecks, ensure appropriate review, and build transparency in IT decision-making.

This is not an org chart—it's a decision guide that matches requests to governance processes based on scope, impact, and strategic alignment.

## Key Concepts

### The Decentralized Governance Challenge
Higher education IT governance differs from corporate IT:
- **Shared governance culture:** Faculty, staff, and administration share decision authority
- **Decentralized funding:** Units may have their own budgets and priorities
- **Academic freedom:** Faculty autonomy in teaching/research tool selection
- **Committee-based decisions:** Approval often requires multiple stakeholder groups
- **Slow consensus-building:** Academic culture values thorough deliberation over speed

Common governance anti-patterns:
- **Black box decisions:** IT decides in isolation; stakeholders surprised
- **Committee death spiral:** Every request goes to every committee
- **Bottleneck gatekeeper:** One person/group approves everything
- **Shadow governance:** Real decisions happen offline; formal process is theater

### Governance Routing Decision Tree
Route requests based on three dimensions:

**1. Scope**
- **Unit-specific:** Affects one department/college
- **Multi-unit:** Affects 2-5 departments
- **Campus-wide:** Affects entire institution

**2. Strategic Impact**
- **Operational:** Supports existing processes
- **Tactical:** Improves efficiency or capabilities
- **Strategic:** Changes institutional direction or competitive position

**3. Resource Requirements**
- **Low:** < $10K, < 1 FTE month, existing infrastructure
- **Medium:** $10K-$100K, 1-6 FTE months, some new infrastructure
- **High:** > $100K, > 6 FTE months, significant new infrastructure

### Common Governance Paths

**Fast Track (Days to Weeks)**
- Unit-specific, operational, low resource
- Example: Department wants existing campus LMS for one course
- Route: IT liaison → Department approval → Provision access

**Standard Review (Weeks to Months)**
- Multi-unit or tactical, medium resource
- Example: College wants new student advising software
- Route: IT intake → Stakeholder discovery → Domain team evaluation → Budget approval → Implementation

**Strategic Review (Months to Year)**
- Campus-wide or strategic, high resource
- Example: University-wide ERP replacement
- Route: Strategic IT plan → Governance committee → Budget cycle → RFP → Selection committee → Implementation

### Anti-Patterns (What This Is NOT)
- **Not a bureaucracy generator:** Fast-track when appropriate; not every request needs committees
- **Not abdication of responsibility:** Governance doesn't mean avoiding decisions
- **Not one-size-fits-all:** Different requests need different processes
- **Not stakeholder avoidance:** Engaging stakeholders early prevents downstream problems

### When to Use This
- New IT request arrives; unclear where to route it
- Request stuck in governance limbo; need to unstick process
- Multiple stakeholders disagree; need escalation path
- Large request requires formal approval; need to map decision journey

### When NOT to Use This
- Emergency incidents (use incident response)
- Routine operations (use standard procedures)
- Pre-approved projects (use project management)

---

### Facilitation Source of Truth

Use [`workshop-facilitation`](../../workshop-facilitation/SKILL.md) as the default interaction protocol for this skill.

It defines:
- session heads-up + entry mode (Guided, Context dump, Best guess)
- one-question turns with plain-language prompts
- progress labels (for example, Context Q1/5)
- interruption handling and pause/resume behavior
- numbered recommendations at decision points
- quick-select numbered response options for regular questions (include `Other (specify)` when useful)

This file defines the domain-specific assessment content. If there is a conflict, follow this file's domain logic.

## Application

This interactive skill asks **5 adaptive questions**, offering **3-5 enumerated options** at each step, then recommends governance routing and stakeholder engagement strategy.

---

### Question 1: Request Scope

**Agent asks:**
"What is the scope of this IT request?"

**Offer 4 enumerated options:**

1. **Unit-specific** — "Affects one department, college, or administrative unit only"
2. **Multi-unit** — "Affects 2-5 departments or crosses college/division boundaries"
3. **Campus-wide** — "Affects entire institution or will be offered/required for all users"
4. **Not sure** — "Need help determining who might be affected"

**Or describe your scope assessment.**

**User response:** [Selection or custom]

---

### Question 2: Strategic Impact

**Agent asks:**
"How does this request align with institutional strategy?"

**Offer 4 enumerated options:**

1. **Operational** — "Supports existing workflows; fixes problems; maintains status quo"
2. **Tactical** — "Improves efficiency, capabilities, or user experience within existing strategic direction"
3. **Strategic** — "Enables new institutional priorities, competitive positioning, or major process change"
4. **Compliance/Risk** — "Required by regulation, accreditation, or mitigates significant risk"

**Or describe the strategic context.**

**User response:** [Selection or custom]

---

### Question 3: Resource Requirements

**Agent asks:**
"What level of resources will this request require?"

**Offer 4 enumerated options:**

1. **Low** — "< $10K, < 1 month IT effort, uses existing infrastructure"
2. **Medium** — "$10K-$100K, 1-6 months IT effort, some new infrastructure or integration"
3. **High** — "> $100K, > 6 months IT effort, significant new infrastructure or organizational change"
4. **Unknown** — "Haven't scoped this yet; need feasibility assessment"

**Or describe known resource requirements.**

**User response:** [Selection or custom]

---

### Question 4: Stakeholder Complexity

**Agent asks:**
"What is the stakeholder environment for this request?"

**Offer 4 enumerated options:**

1. **Simple** — "One requesting unit, clear decision-maker, minimal dependencies"
2. **Moderate** — "Multiple stakeholders within one area (e.g., college-level), some dependencies"
3. **Complex** — "Cross-functional stakeholders (academic + admin + IT), competing priorities"
4. **Highly political** — "Sensitive topic, history of disagreement, requires careful change management"

**Or describe the stakeholder situation.**

**User response:** [Selection or custom]

---

### Question 5: Urgency & Timeline

**Agent asks:**
"What is driving the timeline for this request?"

**Offer 5 enumerated options:**

1. **Critical** — "Legal/compliance deadline, major disruption if delayed"
2. **High urgency** — "Academic calendar constraint (e.g., must launch before fall semester)"
3. **Moderate** — "Business need with flexible timeline (can wait for next budget cycle)"
4. **Low** — "Strategic initiative with long planning horizon"
5. **Opportunistic** — "No specific driver, but would be valuable if timing works"

**Or describe what's driving the timeline.**

**User response:** [Selection or custom]

---

### Output: Recommend Governance Path

**Agent synthesizes answers and provides:**

**1. Recommended Governance Route**

Based on scope, impact, and resources, recommend one of:

**Fast Track Route** (Days to weeks)
- **When to use:** Unit-specific, operational/tactical, low resource, simple stakeholders
- **Process:**
  1. IT liaison reviews request
  2. Unit leadership approves budget (if needed)
  3. IT provisions and implements
  4. Notify governance committee (FYI only)
- **Example:** Department requests access to existing campus survey tool

**Standard Review Route** (Weeks to months)
- **When to use:** Multi-unit OR tactical/strategic OR medium resource
- **Process:**
  1. IT intake and scoping
  2. Stakeholder discovery meetings
  3. Domain team (academic systems, admin systems, etc.) evaluates
  4. Budget approval from appropriate level
  5. Implementation planning
  6. Regular status updates to governance committee
- **Example:** College wants new student advising system

**Strategic Review Route** (Months to year)
- **When to use:** Campus-wide OR strategic OR high resource OR highly political
- **Process:**
  1. Align with strategic IT planning cycle
  2. Technology governance committee review
  3. Stakeholder working group formation
  4. Requirements gathering across units
  5. Business case development
  6. Budget cycle approval (may span fiscal years)
  7. Vendor selection (if applicable)
  8. Implementation governance structure
- **Example:** University-wide ERP replacement

**Compliance Fast Track** (Expedited)
- **When to use:** Compliance/risk driven, regardless of scope
- **Process:**
  1. Risk assessment and compliance verification
  2. Expedited governance committee review
  3. Emergency budget allocation (if needed)
  4. Implementation with audit trail
  5. Retrospective governance review
- **Example:** FERPA compliance gap requires immediate remediation

---

**2. Recommended Stakeholder Engagement**

Based on stakeholder complexity:

**Simple Stakeholders:**
- Direct communication with requesting unit
- IT liaison as primary contact
- Decision: Unit leader + IT manager

**Moderate Stakeholders:**
- Initial discovery meeting with requesting unit
- Identify affected parties via stakeholder mapping
- Present options and tradeoffs
- Decision: Domain governance team + budget authority

**Complex Stakeholders:**
- Form working group with representatives from affected areas
- Multiple discovery sessions
- Pilot with subset of stakeholders
- Build consensus through iterative feedback
- Decision: Technology governance committee + cabinet-level sponsor

**Highly Political:**
- Executive sponsor required (CIO, Provost, etc.)
- Careful change management planning
- One-on-one stakeholder meetings before group sessions
- Address concerns privately before public decisions
- Communication strategy planning
- Decision: President's cabinet or equivalent

---

**3. Next Steps & Timeline**

Provide specific actions with estimated timelines based on selected route.

---

**4. Risk Flags & Mitigation**

Based on answers, identify risks and suggest mitigation strategies.

---

## Examples

### Example 1: Fast Track (Department LMS Use)

**Scenario:** History Department wants to use Canvas (campus LMS) for new course.

**Answers:**
- Scope: Unit-specific
- Impact: Operational
- Resources: Low (existing system)
- Stakeholders: Simple
- Urgency: Moderate (semester start)

**Recommendation:**
Fast Track Route - IT liaison confirms Canvas access, department approves, training provided. Timeline: 1-2 weeks.

---

### Example 2: Strategic Review (Campus-Wide CRM)

**Scenario:** University wants enterprise CRM for enrollment, alumni relations, and development.

**Answers:**
- Scope: Campus-wide
- Impact: Strategic
- Resources: High ($2M, 2-year implementation)
- Stakeholders: Highly political
- Urgency: Low (multi-year initiative)

**Recommendation:**
Strategic Review Route - Form governance structure with executive sponsor, working groups, phased approach. Timeline: 1-2 years.

---

## Common Pitfalls

### Pitfall 1: "Everything Goes to Committee"
**Symptom:** All requests go through full governance review
**Consequence:** Backlogs, frustration, shadow IT
**Fix:** Use tiers to fast-track simple requests

### Pitfall 2: "The Black Box"
**Symptom:** Requests disappear with no status updates
**Consequence:** Distrust, end-runs around process
**Fix:** Transparent tracking, regular updates, clear timelines

---

## References

### Related Skills
- **`it-request-template`** — Standardize intake before governance routing
- **`capability-inventory`** — Check existing solutions before governance review
- **`stakeholder-mapping-higher-ed`** — Identify stakeholders for complex governance
- **`communication-strategy-advisor`** — Craft messages for political governance situations
- **`priority-alignment-advisor`** — Align unit priorities with campus IT capacity

### External Resources
- EDUCAUSE IT Governance frameworks
- COBIT governance model for higher education
