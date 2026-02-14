---
name: project-charter-higher-ed
description: Create project charters for higher education IT initiatives using interactive questioning to gather requirements. Leverage AI tools like AskUserQuestion for structured dialogue with stakeholders. Use for approved projects requiring formal documentation.
type: component
---


## Purpose
Create comprehensive project charters for higher education IT initiatives through structured, interactive dialogue with stakeholders. Use this to transform approved IT requests into actionable project plans with clear scope, objectives, stakeholders, success criteria, and risk mitigation. **This skill emphasizes using AI-assisted interactive questioning (such as Anthropic's AskUserQuestion tool) to efficiently gather complete requirements.**

This is not a waterfall project plan—it's a living charter that establishes shared understanding between IT, requestors, and stakeholders before implementation begins.

## Key Concepts

### Using Interactive AI Tools for Charter Creation

**Anthropic's AskUserQuestion Tool:**
Claude models can use the `AskUserQuestion` tool to conduct structured dialogues that gather complete information efficiently. This is particularly valuable for:
- **Requirements gathering** (asking clarifying questions iteratively)
- **Stakeholder identification** (probing for affected parties)
- **Risk identification** (surfacing concerns through dialogue)
- **Constraint discovery** (uncovering hidden constraints)

**How it works:**
1. Agent asks focused question
2. User responds with their knowledge
3. Agent synthesizes response and asks follow-up
4. Process continues until complete picture emerges
5. Agent drafts charter from gathered information

**Benefits vs. static template:**
- Adaptive questions based on previous answers
- Catches incomplete responses in real-time
- Probes ambiguities immediately
- More conversational, less interrogative
- Faster than back-and-forth email threads

### When to Use Interactive Questioning

**Ideal for:**
- Complex projects with multiple stakeholders
- Projects where requirements are unclear
- First-time requestors unfamiliar with IT processes
- Cross-functional projects requiring alignment
- Projects with significant organizational change

**Not necessary for:**
- Simple, well-defined projects
- Repeat projects (use previous charter as template)
- Projects where all information already documented

---

## Application: Interactive Charter Creation

### Step-by-Step Dialogue Process

**AI Agent Prompt to Start:**
```
"Using the Project Charter Higher Ed skill, help me create a project charter 
for [brief project description]. Use interactive questioning to gather 
complete requirements from stakeholders."
```

---

### Phase 1: Project Context (3-4 questions)

**Q1: "What is the approved IT request this charter is for?"**
- Looks for: Request ID, governance decision, any conditions

**Q2: "What problem does this project solve and who is affected?"**
- Looks for: Pain points, user population, current impact

**Q3: "What governance decisions or constraints apply?"**
- Looks for: Budget limits, timeline requirements, compliance needs

**Example Dialogue:**
```
Agent: "What is the approved IT request this charter is for?"

User: "REQ-2024-042: Psychology Dept requested survey software. 
We found they can use existing Qualtrics license."

Agent: "What problem prompted this request?"

User: "Faculty use free tools that don't meet IRB requirements. 
15 faculty and 30 grad students affected. They spend 2-3 hours 
per study on IRB approval."

Agent: "Were there any conditions from the governance review?"

User: "Fast-track approved. No cost. Must provide IRB-compliant 
training before granting access."
```

---

### Phase 2: Objectives & Scope (4-5 questions)

**Q4: "What are the specific, measurable objectives?"**
- Probes for: Quantifiable outcomes, timelines, success indicators

**Q5: "What is IN scope vs. OUT of scope?"**
- Probes for: Features, user populations, integrations, support level

**Q6: "What timeline constraints exist?"**
- Probes for: Academic calendar, compliance deadlines, user availability

**Example Dialogue with Follow-ups:**
```
Agent: "What are the specific objectives for this project?"

User: "Get faculty access to Qualtrics."

Agent: "Let's make that more specific. How many users need access, 
and by when?"

User: "15 faculty plus 30 grad students, by August 15."

Agent: "What will success look like 3 months after launch?"

User: "80% of faculty using Qualtrics for their research studies, 
and IRB approval time drops from 2.5 hours to under 30 minutes."

Agent: "Excellent. Now for scope - what will this project include 
vs. what it won't include?"

User: "We'll provision access, integrate SSO, and do group training. 
We won't migrate old data or do one-on-one training."
```

---

### Phase 3: Stakeholders (3-4 questions)

**Q7: "Who are the key stakeholders?"**
- Probes for: Sponsor, users, decision-makers, affected parties

**Q8: "Who has decision authority for this project?"**
- Probes for: Scope changes, go-live approval, conflict resolution

**Q9: "Who else might be impacted that we haven't mentioned?"**
- Probes for: Hidden stakeholders (compliance, security, etc.)

**Example Dialogue:**
```
Agent: "Who is the project sponsor?"

User: "Dr. Sarah Chen, Psychology Department Chair."

Agent: "Who else needs to be involved? Think about users, 
decision-makers, and anyone affected by this change."

User: "The 45 users, our IT lead John Smith, and probably 
someone from the IRB office."

Agent: "Good. Who from the IRB office should we include?"

User: "Dr. Maria Garcia - she's the IRB liaison."

Agent: "Who will approve the go-live decision?"

User: "IT manager confirms technical readiness, Department 
Chair confirms users are ready."

Agent: "Anyone else who might care about this? Security, 
compliance, other departments?"

User: "Oh, Faculty Development should help with training - 
Jane Doe can co-facilitate."
```

---

### Phase 4: Success Criteria (2-3 questions)

**Q10: "How will we measure success?"**
- Probes for: Specific metrics, measurement dates, who tracks them

**Q11: "What must be true before we launch?"**
- Probes for: Acceptance criteria, testing requirements

**Example Dialogue:**
```
Agent: "How will we know this project succeeded?"

User: "When faculty are using Qualtrics."

Agent: "Let's make that measurable. What percentage of faculty 
using Qualtrics would indicate success, and by when?"

User: "80% adoption by December 15."

Agent: "Great. Any other success metrics?"

User: "IRB approval time should drop to under 30 minutes average, 
and 100% of studies should use approved tools."

Agent: "Before we launch, what must be ready?"

User: "SSO needs to work, IRB compliance docs approved, training 
materials reviewed, help desk briefed."
```

---

### Phase 5: Risks (2-3 questions)

**Q12: "What could go wrong with this project?"**
- Probes for: Technical, organizational, timeline risks

**Q13: "How will we mitigate each risk?"**
- Probes for: Specific mitigation actions, owners

**Example Dialogue:**
```
Agent: "What could go wrong with this project?"

User: "Um, maybe users won't show up for training?"

Agent: "That's one. What else? Think about technical issues, 
timing problems, or organizational resistance."

User: "SSO integration could have delays. Users might keep 
using their old tools out of habit."

Agent: "For the training attendance risk, how can we mitigate that?"

User: "Offer multiple sessions and record them. Also get the 
department chair to emphasize importance."

Agent: "And for the SSO delays?"

User: "Start that work immediately. Have a manual login backup 
plan if SSO isn't ready by launch."
```

---

### Phase 6: Resources & Communication (2-3 questions)

**Q14: "What resources are needed?"**
- Probes for: IT hours, budget, training time, vendor support

**Q15: "How will we keep stakeholders informed?"**
- Probes for: Update frequency, format, escalation paths

---

### Phase 7: Agent Synthesizes Charter

After completing the dialogue, the agent drafts a complete charter incorporating all gathered information:

```markdown
# Project Charter: Psychology Department Qualtrics Access

**Project ID:** REQ-2024-042  
**Charter Date:** August 1, 2024  
**Project Manager:** John Smith (Academic IT)  
**Sponsor:** Dr. Sarah Chen (Psychology Dept Chair)

## Project Overview
[Synthesized from Phase 1 responses]

## Problem Statement
[From Q2]

## Objectives
[From Q4-Q5, made specific and measurable]

## Scope
**IN SCOPE:** [From Q5]
**OUT OF SCOPE:** [From Q5]

## Stakeholders
[From Q7-Q9, with roles and responsibilities]

## Success Criteria
[From Q10-Q11, with metrics and timelines]

## Timeline & Milestones
[From Q6 and project objectives]

## Risks & Mitigation
[From Q12-Q13]

## Resources
[From Q14]

## Communication Plan
[From Q15]

## Approvals
[Signature section for stakeholders]
```

---

## Using AskUserQuestion: Best Practices

### For AI Agents

**Do:**
- Ask one focused question at a time
- Use follow-up questions to clarify vague responses
- Probe for specifics ("Who specifically?", "How will we measure?")
- Synthesize responses before asking next question
- Confirm understanding before moving to next section

**Don't:**
- Ask multiple unrelated questions at once
- Accept vague responses without clarification
- Skip sections if user seems uncertain
- Generate charter without complete information

**Example of Good Follow-up:**
```
User: "We need better software."
Agent: "Let's be more specific. What tasks will users be able to 
do with this software that they can't do now?"
```

### For Users Working with AI Agents

**Do:**
- Answer as specifically as possible
- Say "I don't know" if you lack information (agent will help identify who knows)
- Ask agent to rephrase if question is unclear
- Request to revisit earlier sections if you remember something

**Don't:**
- Rush through questions to "finish faster"
- Guess at information you're unsure of
- Skip stakeholder identification
- Accept your first answer if agent probes for more detail

---

## Examples

### Example 1: Complex AI Project Charter Created via Dialogue

**Project:** AI-powered tutoring platform for Math Department

**Dialogue Duration:** 20 minutes (15 questions)

**Key Clarifications from Interactive Process:**
- User initially forgot AI committee ongoing monitoring requirement (agent probed: "Any governance conditions?")
- Agent probed for measurable success criteria → user added learning outcome measurement
- Agent surfaced risk: "What if students distrust AI feedback?" → Added mitigation: opt-in pilot with peer comparison
- Agent identified missing stakeholder: Accessibility office (for screen reader compatibility)

**Result:** Complete charter with AI governance requirements, measurable outcomes, and comprehensive stakeholder list

**Time Saved:** 20-minute dialogue vs. 1 week of email exchanges

---

### Example 2: Technical Integration Project

**Project:** HR-Finance system integration

**Dialogue Duration:** 15 minutes (12 questions)

**Key Clarifications:**
- Agent: "What happens if sync fails?" → User added automated alerting requirement
- Agent: "Who approves data mapping rules?" → Clarified joint approval (HR + Finance)
- Agent surfaced missing stakeholder: General Counsel (data privacy review needed)

**Result:** Charter with complete failure scenarios, clear approval paths, compliance review

---

## When to Use Full Interactive Process vs. Template

**Use Interactive Dialogue When:**
- First-time requestor (needs guidance)
- Complex stakeholder environment
- Ambiguous requirements
- High-risk project
- Cross-functional dependencies

**Use Static Template When:**
- Repeat project (similar to previous)
- Experienced requestor
- Simple, well-defined scope
- Low-risk, single-unit project

**Hybrid Approach:**
- Start with template pre-filled from IT request
- Use interactive dialogue to fill gaps and clarify ambiguities
- Most efficient for standard projects with some complexity

---

## Common Pitfalls

### Pitfall 1: "AI Just Fills Out Template"
**Symptom:** Using AI to populate fields without dialogue
**Consequence:** Miss nuances, incomplete information, no stakeholder discovery
**Fix:** Use AI's interactive questioning capability, not just text generation

### Pitfall 2: "One Question Per Section"
**Symptom:** Rigid adherence to question list without follow-ups
**Consequence:** Accept vague responses, miss details
**Fix:** Agent should probe until response is specific and measurable

### Pitfall 3: "User Doesn't Know = Skip It"
**Symptom:** User lacks information, section left blank
**Consequence:** Incomplete charter, surprises mid-project
**Fix:** Agent should identify who has information and suggest including them

### Pitfall 4: "Charter Created Without Stakeholders"
**Symptom:** IT creates charter alone, sends to requestor for signature
**Consequence:** Requestor surprised by scope, doesn't own outcomes
**Fix:** Conduct interactive dialogue with requestor and key stakeholders present

---

## Integration with Other Skills

**Prerequisites:**
- **`it-request-template`** — Charter builds on approved request
- **`it-governance-advisor`** — Governance approval before charter

**Parallel Use:**
- **`stakeholder-mapping-higher-ed`** — Deep stakeholder analysis for complex projects
- **`risk-assessment-higher-ed`** — Detailed risk assessment

**Downstream:**
- Charter feeds into project execution
- Success criteria inform project evaluation
- Risk mitigation plans guide implementation

---

## References

### Related Skills
- **`it-request-template`** — Initial request captured here
- **`stakeholder-mapping-higher-ed`** — Detailed stakeholder analysis
- **`risk-assessment-higher-ed`** — Comprehensive risk assessment
- **`it-governance-advisor`** — Routing before charter creation
- **Core PM Skills:** `problem-statement`, `user-story` — Applicable techniques

### External Resources
- PMI Project Charter Guide
- PMBOK Guide (Project Management Body of Knowledge)
- Agile Project Charter templates

### AI Tool Documentation
- **Anthropic Claude:** AskUserQuestion tool for structured dialogue
- **OpenAI ChatGPT:** Conversational prompting techniques
- **Other AI Agents:** Adapt interactive approach to available capabilities

---

**This skill demonstrates how AI-assisted interactive questioning (like Anthropic's AskUserQuestion) makes charter creation faster, more complete, and more collaborative than traditional static templates.**
