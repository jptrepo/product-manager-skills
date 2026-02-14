# Using Higher Education IT Skills

**A practical guide for IT teams, governance committees, and academic units**

---

## Who Should Use These Skills?

### IT Leadership & Governance
- CIOs and IT directors managing decentralized environments
- Technology governance committee members
- IT portfolio managers

### IT Service Teams
- IT liaisons to academic/administrative units
- Service desk managers handling requests
- Enterprise systems teams evaluating new tools

### Academic & Administrative Units
- Department chairs and deans requesting IT support
- Administrative leaders proposing new systems
- Faculty members with technology needs

---

## Quick Start: Three Common Scenarios

### Scenario 1: "A Department Just Requested New Software"

**You need:** A systematic way to evaluate and route this request

**Start here:**
1. Use [`it-request-template`](it-request-template/SKILL.md) to gather structured information
2. Run [`capability-discovery-advisor`](capability-discovery-advisor/SKILL.md) to check existing campus tools
3. Use [`it-governance-advisor`](it-governance-advisor/SKILL.md) to determine routing path

**Example prompt to AI agent:**
```
"A department submitted a request for project management software. 
Using the IT Request Template skill, guide me through gathering 
the necessary information, then help me determine if we already 
have a campus solution that meets their needs."
```

**Outcome:** Within 30 minutes, you'll know:
- Whether existing campus tools meet the need
- What governance path this should follow
- Who needs to be involved in the decision

---

### Scenario 2: "We Keep Buying Duplicate Software"

**You need:** A capability inventory and discovery process

**Start here:**
1. Build a [`capability-inventory`](capability-inventory/SKILL.md) of existing campus tools
2. Train IT liaisons to use [`capability-discovery-advisor`](capability-discovery-advisor/SKILL.md)
3. Require requestors to document their inventory search

**Example prompt to AI agent:**
```
"Using the Capability Inventory skill, help me create a searchable 
catalog of our campus IT capabilities organized by function 
(not just product names). Start with our enterprise licenses."
```

**Outcome:** Within 2-4 weeks, you'll have:
- Searchable inventory of campus capabilities
- Process to check inventory before new purchases
- Visibility into underutilized licenses

---

### Scenario 3: "Requests Disappear Into a Black Hole"

**You need:** A transparent intake and routing workflow

**Start here:**
1. Implement [`it-intake-and-routing-process`](it-intake-and-routing-process/SKILL.md) workflow
2. Commit to response timelines (3-5 days acknowledgment)
3. Provide regular status updates

**Example prompt to AI agent:**
```
"Using the IT Intake and Routing Process workflow, help me 
design a transparent request tracking system that shows requestors 
where their request is in the evaluation process and what's next."
```

**Outcome:** Within 1-2 months, you'll have:
- Defined intake and routing process
- Clear timelines for each path (fast-track, standard, strategic)
- Regular communication with requestors

---

## Skill Combinations for Common Tasks

### Task: Evaluate a New IT Request

**Skills to use in sequence:**

1. **`it-request-template`** — Capture structured information
   - Gather problem statement, stakeholders, timeline, constraints
   - Ensure completeness before evaluation begins

2. **`capability-discovery-advisor`** — Check existing campus tools first
   - Match functional needs to existing capabilities
   - Identify perfect match, close match, or genuine gap

3. **`it-governance-advisor`** — Determine appropriate routing
   - Fast-track, standard review, or strategic review
   - Identify stakeholders and decision-makers
   - Set timeline expectations

4. **`it-intake-and-routing-process`** — Execute full workflow
   - Stage 1-5 orchestration
   - Status tracking and communication

**Time investment:** 1-2 hours for initial evaluation; ongoing for governance process

---

### Task: Build Governance Transparency

**Skills to use:**

1. **`capability-inventory`** — Make existing tools discoverable
2. **`it-governance-advisor`** — Document governance paths and criteria
3. **`it-intake-and-routing-process`** — Transparent workflow with status updates

**Transparency mechanisms:**
- Public capability inventory (what we have)
- Published governance criteria (how decisions are made)
- Request tracking dashboard (where requests are in process)

---

### Task: Reduce Shadow IT

**Skills to use:**

1. **`capability-inventory`** — Document what exists (including shadow IT discovered)
2. **`capability-discovery-advisor`** — Proactive matching before units buy on their own
3. **`it-request-template`** — Lower friction for formal requests

**Root causes of shadow IT:**
- Units don't know what campus has
- IT request process too slow or opaque
- Existing tools don't meet needs (genuine gaps)

**How these skills help:**
- Make existing tools discoverable → Reduce "we didn't know"
- Transparent routing with timelines → Reduce "it takes forever"
- Honest gap analysis → Approve genuine needs faster

---

## AI Agent Usage Tips

### With Claude (Desktop, Web, or Code)

**Load a skill:**
```
"Load the IT Governance Advisor skill from skills/higher-ed/it-governance-advisor/SKILL.md"
```

**Apply the skill:**
```
"Using the IT Governance Advisor skill, help me determine 
the right governance path for a college-level request for 
new student advising software with an estimated cost of $40K."
```

**Combine multiple skills:**
```
"First use the Capability Discovery Advisor to check existing 
tools, then use the IT Governance Advisor to recommend a 
routing path for this request."
```

---

### With ChatGPT or Codex

**Upload skill file as context:**
- Copy skill file content
- Paste into conversation or upload as file
- Reference the skill in your prompt

**Example:**
```
"I've uploaded the IT Request Template skill. Please guide me 
through filling it out for a faculty request to use a specific 
research data collection tool."
```

---

### For Non-Technical Users

**Simple approach:**
1. Open conversation with AI agent
2. Copy/paste the skill content you need
3. Say: "Using this framework, help me with [your specific task]"

**Example:**
```
[Paste IT Request Template skill]

"Using this template, help me fill out a request for video 
conferencing software for my department's virtual office hours."
```

---

## Integration with Existing IT Processes

### ITIL or IT Service Management

These skills complement ITIL practices:

- **Service Request Management:** `it-request-template` standardizes intake
- **Service Catalog Management:** `capability-inventory` is your catalog
- **Change Management:** Governance routing for significant changes
- **Portfolio Management:** Strategic review process for major investments

---

### Technology Governance Committees

Use these skills to:

**Prepare for committee meetings:**
- `it-request-template` ensures complete information
- `capability-discovery-advisor` identifies if new capability is genuinely needed
- `it-governance-advisor` pre-filters requests by appropriate review level

**Communicate decisions:**
- Clear rationale for approve/defer/decline
- Reference capability gaps or existing solutions
- Document for future similar requests

**Track portfolio:**
- `capability-inventory` shows current state
- Request tracking shows pipeline
- Strategic review process aligns with budget cycles

---

### Budget Planning

Connect skills to budget process:

**Annual planning:**
- Strategic review requests align with budget cycle
- `capability-inventory` shows existing commitments
- Request backlog informs new investment priorities

**Mid-year requests:**
- Fast-track for low-cost items within approved budgets
- Standard review for unplanned medium investments
- Strategic review delays high-cost items to next cycle

---

## Training Your IT Team

### For IT Liaisons

**Core skills to master:**
1. `it-request-template` — How to gather complete information
2. `capability-discovery-advisor` — How to match needs to existing tools
3. Basic governance routing rules

**Training approach:**
- 2-hour workshop covering all three skills
- Practice with 3-5 real requests
- Reference guide for common scenarios

---

### For Service Desk Staff

**Focus on:**
- Distinguishing break/fix (help desk) from project requests (use template)
- Initial triage and routing
- When to escalate to IT liaison or governance

---

### For Governance Committee Members

**Focus on:**
- Understanding governance paths (fast-track vs. standard vs. strategic)
- Reading capability discovery findings
- Making decisions with incomplete information (when to ask for more vs. decide)

---

## Measuring Success

### Metrics to Track

**Request processing:**
- Time to acknowledgment (target: 3 days)
- Time to initial assessment (target: 10 days)
- Time to decision by governance path:
  - Fast-track: 1-2 weeks
  - Standard: 4-8 weeks
  - Strategic: 3-12 months

**Capability reuse:**
- % of requests resolved with existing campus tools
- Reduction in duplicate software purchases
- Increase in utilization of underutilized licenses

**Transparency:**
- Requestor satisfaction with communication
- % of requests with regular status updates
- Reduction in shadow IT purchases

---

### Before/After Comparison

**Before these skills:**
- Requests arrive in many formats (email, meetings, phone)
- Unknown whether existing tools meet needs
- Unclear routing and timelines
- Requests disappear into "black hole"
- Duplicate purchases common

**After implementing:**
- Standardized intake via template
- Capability check happens first
- Clear governance paths with timelines
- Regular status updates
- Reduced duplicate spending

---

## Common Questions

### Q: Do all requests need to use the formal template?

**A:** No. Use tiered approach:
- **Informal inquiries:** IT liaison can fill out template on behalf of requestor
- **Access to existing tools:** Simplified request (not full template)
- **Strategic initiatives:** Full template plus additional documentation

---

### Q: What if a unit rejects our existing tool suggestion?

**A:** Use `capability-discovery-advisor` to do honest gap analysis:
- If existing tool truly doesn't fit → Approve new purchase
- If gap is configuration/training → Help them succeed with existing
- If preference not necessity → Have budget/priority conversation

---

### Q: How do we handle emergency requests?

**A:** Use Compliance Fast Track path:
- Immediate risk assessment
- Expedited governance review
- Implement quickly
- Retrospective review to prevent future emergencies

---

### Q: What if requestor bought software before coming to IT?

**A:** Retrofit governance:
- Use template to document what was purchased and why
- Assess risk (security, compliance, support)
- Add to capability inventory (prevent future duplication)
- Address root cause: Why did they bypass IT?

---

## Getting Started Checklist

**Week 1: Foundation**
- [ ] Review all 7 higher-ed skills
- [ ] Identify 2-3 pilot requests to process through new workflow
- [ ] Brief IT leadership on approach

**Week 2-3: Capability Inventory**
- [ ] Document top 20 enterprise licenses and campus-wide systems
- [ ] Make searchable (even simple spreadsheet to start)
- [ ] Link in request template

**Week 4-5: Process Launch**
- [ ] Train IT liaisons on request template and capability discovery
- [ ] Publish governance criteria and timelines
- [ ] Communicate new process to campus

**Week 6-8: Pilot and Refine**
- [ ] Process 5-10 requests through new workflow
- [ ] Gather feedback from requestors and IT staff
- [ ] Adjust timelines and communication cadence

**Month 3+: Scale and Optimize**
- [ ] Expand capability inventory
- [ ] Measure metrics (time to decision, duplicate spending reduction)
- [ ] Refine governance paths based on experience

---

## Resources & Support

### Within This Repository
- [Main README](../../README.md) — Overview of all PM skills
- [Contributing Guide](../../CONTRIBUTING.md) — How to suggest improvements
- [Core PM Skills](../../) — Many apply to higher ed (problem statements, user stories, discovery interviews)

### External Resources
- **EDUCAUSE:** Higher ed IT leadership and governance resources
- **CIO Forums:** Peer institution governance practices
- **ITIL for Higher Ed:** Service management frameworks

---

## Questions or Feedback?

- **GitHub Issues:** Suggest improvements to higher-ed skills
- **LinkedIn:** Connect with contributors and other higher ed IT leaders
- **Community:** Share your implementation experiences

---

**Built on the Product Manager Skills framework by Dean Peters, adapted for higher education IT governance.**

*Helping academic institutions build transparent, efficient IT governance.*
