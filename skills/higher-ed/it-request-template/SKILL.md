---
name: it-request-template
description: Standardized template for IT project requests in higher education. Captures scope, stakeholders, alignment with campus priorities, and existing capability checks. Use to reduce ambiguity and enable consistent evaluation.
type: component
---


## Purpose
Create standardized IT project requests that capture essential information for evaluation, routing, and prioritization in decentralized higher education environments. Use this to reduce ambiguous requests, enable consistent evaluation across units, identify opportunities to leverage existing capabilities, and facilitate transparent governance decisions.

This is not a procurement form—it's a structured conversation starter that ensures IT and requesting units have shared context before evaluating feasibility, priority, and approach.

## Key Concepts

### The Higher Ed IT Request Challenge
In decentralized campus environments, requests often arrive with:
- Unclear scope or objectives
- No knowledge of existing campus capabilities
- Misalignment with strategic priorities
- Missing stakeholder context
- Unrealistic timelines or resource expectations

A structured request template addresses these by:
- **Standardizing information collection** across all units
- **Surfacing existing solutions** before creating new ones
- **Clarifying impact and urgency** for prioritization
- **Identifying stakeholders** early for governance routing
- **Setting realistic expectations** about evaluation timelines

### Template Sections
1. **Requestor Information** — Who is asking, from which unit
2. **Request Summary** — Brief description of need
3. **Problem Statement** — What problem this solves (not the solution)
4. **Desired Outcomes** — Success criteria from user perspective
5. **Stakeholders & Impact** — Who is affected, how many users
6. **Existing Solutions Check** — What has been explored already
7. **Timeline & Urgency** — When needed, consequences of delay
8. **Strategic Alignment** — Connection to campus goals
9. **Constraints** — Budget, compliance, integration requirements
10. **Next Steps Expected** — What requestor expects IT to do

### Anti-Patterns (What This Is NOT)
- **Not a technical specification:** Focus on outcomes, not implementation details
- **Not a guarantee of approval:** This is the start of evaluation, not a commitment
- **Not a procurement form:** This precedes vendor selection or budgeting
- **Not a one-way demand:** It's a conversation starter, not a work order

### When to Use This
- Academic unit requests new software or system
- Administrative department needs IT project support
- Faculty member proposes technology initiative
- Compliance or regulatory change requires IT response

### When NOT to Use This
- Break/fix IT support tickets (use help desk)
- Routine maintenance or renewals (use operations process)
- Emergency security issues (use incident response)
- Projects already in flight (use project tracking)

---

## Application

### Step 1: Provide the Template
Share this template with requestors (as a form, document, or conversation guide):

```markdown
# IT Project Request Template

## 1. Requestor Information
- **Name:**
- **Unit/Department:**
- **Role:**
- **Contact Email:**
- **Submission Date:**

---

## 2. Request Summary
[One-paragraph description of what you're requesting]

---

## 3. Problem Statement
**What problem are you trying to solve?**
- Who experiences this problem?
- What is the impact of not solving it?
- How do you currently work around it?

---

## 4. Desired Outcomes
**If this request is fulfilled, what will be different?**
- What will users be able to do that they can't do now?
- What metrics would improve (time saved, errors reduced, etc.)?
- What success looks like in 6 months?

---

## 5. Stakeholders & Impact
- **Primary users:** [Who will use this daily?]
- **Secondary stakeholders:** [Who else is affected?]
- **Number of users:** [Estimated user count]
- **Units involved:** [Other departments/colleges that might care]

---

## 6. Existing Solutions Check
**Have you checked if this capability already exists on campus?**
- [ ] Searched campus IT services catalog
- [ ] Asked colleagues in other departments
- [ ] Consulted with IT liaison or support team
- [ ] Explored existing systems (list what you found):

**If yes, why don't existing solutions work?**

---

## 7. Timeline & Urgency
- **When is this needed?** [Date or semester]
- **What drives this timeline?** [External deadline, academic calendar, compliance, etc.]
- **What happens if delayed?** [Consequences]

**Urgency level (select one):**
- [ ] **Critical:** Legal/compliance requirement, major impact if delayed
- [ ] **High:** Significant workflow disruption, affects many users
- [ ] **Moderate:** Important but can be phased in over time
- [ ] **Low:** Nice to have, flexible timeline

---

## 8. Strategic Alignment
**How does this align with campus priorities?**
- [ ] Supports student success or retention
- [ ] Improves operational efficiency
- [ ] Addresses compliance or risk
- [ ] Enhances research capabilities
- [ ] Advances diversity, equity, or accessibility
- [ ] Aligns with strategic plan goal: [specify]

---

## 9. Constraints
**Are there specific requirements or limitations?**
- **Budget:** [Known funding source or limit]
- **Integration:** [Must work with these existing systems]
- **Compliance:** [FERPA, accessibility, security requirements]
- **Vendor preference:** [If any, and why]

---

## 10. Next Steps Expected
**What are you expecting from IT?**
- [ ] Feasibility assessment
- [ ] Cost estimate
- [ ] Recommendation of existing solution
- [ ] Vendor evaluation
- [ ] Project scoping and timeline
- [ ] Other: [describe]

---

**For IT Use Only:**
- **Request ID:**
- **Received Date:**
- **Assigned To:**
- **Status:**
- **Estimated Review Date:**
```

---

### Step 2: Intake and Initial Review
When a request arrives:

1. **Completeness check:** Are all required sections filled out?
   - If incomplete → Return to requestor with specific gaps
   - If complete → Proceed to step 2

2. **Capability match:** Does this overlap with existing campus solutions?
   - Check capability inventory (see `capability-inventory` skill)
   - If match exists → Route to that service owner for consultation
   - If new → Proceed to step 3

3. **Initial categorization:**
   - **Type:** New system, enhancement, integration, policy change
   - **Scope:** Single unit, multi-unit, campus-wide
   - **Complexity:** Simple (days), Medium (weeks), Complex (months)

4. **Governance routing:** Where should this be evaluated?
   - IT leadership review
   - Technology governance committee
   - Specific domain team (academic systems, admin systems, infrastructure)
   - Cross-functional working group

---

### Step 3: Communicate Next Steps
Reply to requestor within **3-5 business days** with:

**Template response:**
```markdown
Thank you for submitting your IT request for [brief description].

**Request ID:** [assigned number]
**Status:** Under Review

**Next Steps:**
1. [Action]: [e.g., "We will evaluate existing campus LMS capabilities"]
2. [Timeline]: [e.g., "Initial assessment by March 15"]
3. [Meeting]: [If needed, propose discovery meeting]

**Assigned Contact:** [Name and email]

**What to expect:**
- Initial feasibility assessment: [date]
- Recommendation or scoping meeting: [date range]
- Decision on next steps: [date range]

We will keep you updated as we progress through the evaluation.

[IT Contact Name]
[Title]
```

---

### Step 4: Track and Follow Up
Use a simple tracking system:

| Request ID | Unit | Summary | Status | Priority | Next Action | Owner |
|-----------|------|---------|--------|----------|-------------|-------|
| REQ-001 | History | LMS upgrade | In Review | High | Eval existing options | J. Smith |
| REQ-002 | Finance | Budget tool | Scoping | Medium | Discovery meeting | K. Jones |

**Status values:**
- **Received** → Initial review in progress
- **In Review** → Detailed evaluation underway
- **Scoping** → Defining project details with requestor
- **Approved** → Moving to implementation planning
- **Deferred** → Lower priority, revisit later
- **Closed - Alt Solution** → Existing capability meets need
- **Closed - Declined** → Not feasible or not aligned

---

## Examples

### Example 1: Good Request (Complete and Clear)

**Request Summary:**
"The Psychology Department needs a survey and data collection platform for research studies that complies with IRB and FERPA requirements."

**Problem Statement:**
"Psychology faculty currently use free survey tools that don't meet IRB data security requirements. Each faculty member uses different tools, creating compliance risk and making cross-study analysis difficult. We spend 2-3 hours per study navigating IRB approval for inadequate tools."

**Desired Outcomes:**
- IRB-compliant survey tool approved for human subjects research
- Centralized data storage meeting FERPA requirements
- Ability to export data in common formats (CSV, SPSS)
- Training resources for faculty and graduate students

**Existing Solutions Check:**
"We found Qualtrics is available campus-wide but weren't sure if it meets IRB requirements. We also heard Engineering uses REDCap but don't know if we can access it."

**Strategic Alignment:**
Supports research excellence (strategic plan goal 2) and compliance with federal research regulations.

**Next Steps Expected:**
Guidance on which existing tools are IRB-compliant, or recommendation for new platform if current options don't meet needs.

**Why this is good:**
- Clear problem statement (compliance risk, faculty time waste)
- Measurable outcomes (time saved, IRB approval)
- Checked for existing solutions and named specific tools
- Realistic expectations for next steps
- Explicit compliance requirements

---

### Example 2: Weak Request (Incomplete and Solution-Focused)

**Request Summary:**
"We need Salesforce."

**Problem Statement:**
"Our department doesn't have good CRM software."

**Desired Outcomes:**
"Be able to track contacts better."

**Existing Solutions Check:**
[Left blank]

**Why this is weak:**
- Jumps to specific vendor without explaining need
- Vague problem ("not good" is subjective)
- No stakeholder context (who needs this, how many users)
- No exploration of existing campus capabilities
- Unclear success criteria ("better" is not measurable)

**How IT should respond:**
Return the form with guidance:
"Thank you for your request. To help us evaluate the best solution, please provide:
1. Specific workflows or tasks you're trying to support
2. Number of users and use cases
3. What you've already tried or explored
4. Success metrics (e.g., time saved, conversion rates)

We also have Microsoft Dynamics available campus-wide for CRM use—have you evaluated whether this meets your needs?"

---

### Example 3: Discovery Leads to Existing Solution

**Request Summary:**
"Student Affairs needs a mobile app for campus event notifications and student engagement."

**Evaluation reveals:**
- Campus already has a mobile app platform through University Relations
- Student Affairs wasn't aware of its capabilities
- Existing platform can add new modules

**Outcome:**
- Request closed with alternative solution
- Student Affairs connected with University Relations
- New module added to existing app (faster and cheaper than new build)
- Process identified gap in campus capability communication

**Lesson:**
The request template surfaced an opportunity to leverage existing infrastructure, avoiding duplicate spending and fragmented user experience.

---

## Common Pitfalls

### Pitfall 1: "IT as Order-Taker"
**Symptom:** Accepting all requests without evaluation or prioritization
**Consequence:** IT overwhelmed, strategic initiatives delayed, no transparency
**Fix:** Use this template to gather enough context for governance decisions; not all requests will proceed

### Pitfall 2: "Black Hole Intake"
**Symptom:** Requests submitted but never acknowledged or updated
**Consequence:** Frustration, shadow IT, loss of trust
**Fix:** Commit to 3-5 day initial response; provide status updates every 2-4 weeks

### Pitfall 3: "Technical Interrogation"
**Symptom:** Template becomes overly technical, scares away requestors
**Consequence:** Requests go around formal process
**Fix:** Keep template focused on outcomes and impact, not technical details

### Pitfall 4: "Checkbox Theatre"
**Symptom:** Template exists but responses aren't actually used in decisions
**Consequence:** Requestors fill it out perfunctorily, real conversations happen offline
**Fix:** Explicitly show how template responses inform governance decisions; share examples

### Pitfall 5: "One Size Fits All"
**Symptom:** Same template for a faculty member requesting Zoom and a major ERP system replacement
**Consequence:** Major projects underdocumented, minor requests overdocumented
**Fix:** Create lightweight and comprehensive versions; offer guidance on which to use

---

## References

### Related Skills
- **`capability-inventory`** — Document existing campus capabilities to match against requests
- **`it-governance-advisor`** — Navigate routing and decision processes for requests
- **`capability-discovery-advisor`** — Match requests to existing solutions before building new
- **`stakeholder-mapping-higher-ed`** — Identify all stakeholders affected by a request
- **`project-charter-higher-ed`** — Develop full project charter after request is approved

### External Resources
- EDUCAUSE IT Governance resources
- ITIL Service Request Management practices
- Gartner IT Portfolio Management frameworks
