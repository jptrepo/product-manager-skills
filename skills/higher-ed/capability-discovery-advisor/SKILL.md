---
name: capability-discovery-advisor
description: Match IT requests to existing campus capabilities before building or buying new solutions. Ask questions about functional needs, then recommend existing tools, integration opportunities, or gaps requiring new investment.
type: interactive
---


## Purpose
Guide requestors and IT staff through discovering existing campus capabilities that might meet a need before approving new software purchases or development. Use this to reduce duplicate spending, maximize existing license utilization, identify integration opportunities, and surface genuine capability gaps requiring new investment.

This is not a simple lookup tool—it's a guided discovery process that translates user needs into functional capabilities, then maps those to existing campus solutions.

## Key Concepts

### The "We Already Have That" Problem
Common scenario:
- Unit requests new tool without knowing campus already has it
- IT discovers existing solution mid-evaluation (wasted time)
- Unit already committed to vendor (awkward situation)
- Or worse: Unit buys tool, IT discovers later (duplicate spending, security risk)

### Discovery Before Decision
This skill helps:
1. **Translate needs to capabilities** — "We need to track donors" → CRM capability
2. **Surface existing solutions** — "We have Salesforce for this"
3. **Evaluate fit** — Does existing tool meet all requirements?
4. **Identify gaps** — What's missing? Can it be configured? Must we buy new?
5. **Connect people** — "Talk to Development Office; they use this daily"

### Three Outcome Types

**Perfect Match**
- Existing campus capability meets all requirements
- Outcome: Use existing tool; no new purchase needed
- Example: Unit wants video conferencing; campus has Zoom enterprise license

**Close Match with Customization**
- Existing capability meets 80%+ of requirements
- Gap can be closed with configuration, training, or workaround
- Outcome: Extend existing tool; cheaper than new purchase
- Example: Campus LMS can be configured for continuing education use

**Genuine Gap**
- No existing capability comes close
- Requirements are unique or not covered by current portfolio
- Outcome: New purchase justified; document in capability inventory
- Example: Specialized lab equipment scheduling software

### Anti-Patterns (What This Is NOT)
- **Not "make it fit":** Don't force square pegs into round holes to avoid buying
- **Not IT gatekeeping:** Goal is best solution, not blocking all purchases
- **Not capability catalog search:** This is guided discovery, not self-service lookup
- **Not vendor favoritism:** Focus on capabilities, not protecting existing vendors

### When to Use This
- New IT request proposes specific product or capability
- Requestor asks "Do we have something that does X?"
- IT evaluating whether to approve new purchase
- Strategic planning: identifying capability gaps vs. underutilized tools

### When NOT to Use This
- Emergency compliance need (fast-track)
- Request is for access to known existing tool
- Renewal of existing subscription (not a new capability)

---

### Facilitation Source of Truth

Use [`workshop-facilitation`](../../workshop-facilitation/SKILL.md) as the default interaction protocol for this skill.

## Application

This interactive skill asks **4 adaptive questions** about functional needs, then recommends existing campus solutions or identifies genuine gaps.

---

### Question 1: What are you trying to accomplish?

**Agent asks:**
"What business or academic problem are you trying to solve?"

**Prompt for:**
- Specific workflows or tasks
- User roles involved
- Current pain points or workarounds
- Success criteria (what "better" looks like)

**Example good answers:**
- "Faculty need to survey students anonymously for course feedback, then export data to analyze trends across semesters"
- "Advisors need to track student appointments, notes, and referrals to other departments"
- "Development team needs to manage donor relationships and track gift campaigns"

**Example weak answers:**
- "We need Salesforce" (that's a product, not a need)
- "Better software" (too vague)

**Agent captures:** Functional requirements in capability terms

---

### Question 2: Who will use this and how many users?

**Agent asks:**
"Who are the primary users, and what's the scale of use?"

**Offer 4 enumerated options for scale:**

1. **Individual** — "1-5 users in one department"
2. **Unit-level** — "One department or college (10-50 users)"
3. **Multi-unit** — "Multiple departments (50-200 users)"
4. **Campus-wide** — "Institution-wide (200+ users)"

**Also ask:**
- User roles (faculty, staff, students, administrators)
- Frequency of use (daily, weekly, seasonal)
- Technical skill level (power users vs. occasional users)

**Why this matters:**
- Individual use might not warrant enterprise tool
- Campus-wide need might justify extending existing enterprise license
- Multi-unit use suggests checking if another unit already has this

---

### Question 3: What capabilities do you need?

**Agent asks:**
"What specific features or functions must this solution provide?"

**Categorize by capability type:**

**Data & Content Management:**
- Store/organize documents or records
- Search and retrieve information
- Version control or audit trail

**Communication & Collaboration:**
- Messaging or notifications
- Video/audio conferencing
- Shared workspaces or co-editing

**Workflow & Process:**
- Approval routing
- Task management
- Reporting and dashboards

**Integration & Data:**
- Connect to existing systems (LMS, SIS, HR, Finance)
- Import/export data
- API access

**Compliance & Security:**
- FERPA/HIPAA/IRB requirements
- Access control and permissions
- Audit logging

**Agent identifies:** Which capability categories are must-haves vs. nice-to-haves

---

### Question 4: Have you explored what's available on campus?

**Agent asks:**
"What have you already checked or tried?"

**Offer 4 enumerated options:**

1. **Haven't checked** — "Not sure where to look or what exists"
2. **Checked IT website** — "Looked at services catalog but didn't find a match"
3. **Asked colleagues** — "Other departments recommended [specific tool]"
4. **Tried existing tool** — "We found [X] but it doesn't do [Y]"

**If tried existing tool:**
- What specifically didn't work?
- Was it missing features, too complex, poor fit for workflow?
- Did you get training or support?

**Agent captures:** What's been ruled out and why

---

### Output: Recommend Solutions

**Agent provides one of three recommendation types:**

---

### Recommendation Type 1: Perfect Match (Use Existing)

**When to use:** Existing campus capability meets all must-have requirements

**Template:**
```
✅ **MATCH FOUND: [Existing Tool Name]**

**What it does:**
[Brief capability description matching stated needs]

**Why it's a good fit:**
- ✓ [Requirement 1] — [How tool addresses this]
- ✓ [Requirement 2] — [How tool addresses this]
- ✓ [Requirement 3] — [How tool addresses this]

**Access & Support:**
- **Who to contact:** [Department or IT contact]
- **How to get access:** [Process or link]
- **Training available:** [Resources]
- **Current users:** [Which units use this - for peer consultation]

**Next steps:**
1. Contact [person/team] to discuss your specific use case
2. Request demo or trial access
3. Identify if any configuration needed for your workflow
4. Get training (if needed)

**Cost:** $0 (included in existing campus license)
```

**Example:**
Unit wants survey tool → Recommend Qualtrics (campus enterprise license, IRB-approved, used by Psychology and Marketing departments)

---

### Recommendation Type 2: Close Match with Gap Analysis

**When to use:** Existing capability meets 70-90% of requirements; gap might be closeable

**Template:**
```
🔶 **CLOSE MATCH: [Existing Tool Name]**

**What it does:**
[Brief capability description]

**What it covers:**
- ✓ [Met requirement 1]
- ✓ [Met requirement 2]
- ✓ [Met requirement 3]

**Gap identified:**
- ⚠ [Unmet requirement] — [What's missing]

**Options to close the gap:**

**Option 1: Configure existing tool**
- [Describe how to adapt existing tool]
- Tradeoff: [Pros/cons]
- Effort: [Time/cost estimate]

**Option 2: Workaround with complementary tool**
- Use [existing tool A] for [functions X, Y]
- Use [existing tool B] for [function Z]
- Tradeoff: Two tools instead of one, but leverages existing licenses

**Option 3: Extend existing tool**
- Purchase add-on or advanced tier for existing tool
- Cost: [Estimate vs. cost of new standalone tool]
- Benefit: Integration with existing campus systems

**Option 4: Purchase new tool (if gap is critical)**
- Justification: [Why gap can't be closed with existing]
- Next steps: Full evaluation process

**Recommendation:**
[Agent suggests best option based on gap criticality, cost, and implementation effort]

**Next steps:**
1. Discuss gap criticality with requesting unit
2. Explore Option [X] feasibility with [team]
3. Pilot approach with small user group
4. Decision: Proceed with existing tool (with adjustments) or evaluate new purchase
```

**Example:**
Unit wants grant management system → Campus has basic module in finance system (meets 70% of need); could add specialized features or buy dedicated tool

---

### Recommendation Type 3: Genuine Gap (New Purchase Justified)

**When to use:** No existing campus capability comes close; requirements are genuinely unique

**Template:**
```
❌ **NO CLOSE MATCH FOUND**

**What we checked:**
- [Existing tool 1] — [Why it doesn't fit]
- [Existing tool 2] — [Why it doesn't fit]

**Why existing tools don't fit:**
- [Critical requirement not met]
- [Workflow mismatch]
- [Integration requirement not possible]

**Conclusion: New capability gap identified**

This appears to be a genuine need not covered by current campus capabilities.

**Recommended next steps:**

1. **Document requirements clearly**
   - Use IT request template to formalize needs
   - Identify must-haves vs. nice-to-haves
   - Define success criteria

2. **Market research**
   - Evaluate 3-5 vendor options
   - Check peer institutions (what do similar schools use?)
   - Consider build vs. buy tradeoffs

3. **Pilot approach**
   - Start with limited users/scope
   - Prove value before campus-wide investment
   - Document in capability inventory to prevent future duplication

4. **Governance routing**
   - [Recommend governance path based on scope/cost]
   - Budget approval needed
   - Implementation timeline

**Before proceeding:**
- Have you connected with peer institutions to see their solutions?
- Could this need be met with professional services instead of software?
- Is this a one-time project or ongoing operational need?
```

**Example:**
Specialized scientific equipment scheduling with lab safety protocols → No general-purpose tool meets niche requirements; specialized software justified

---

## Examples

### Example 1: Perfect Match (Video Conferencing)

**Request:** "Biology Department wants to buy Zoom licenses for virtual office hours."

**Discovery Questions:**
- Need: Hold virtual meetings with students, record sessions
- Users: 15 faculty members
- Capabilities: Video, screen sharing, recording, waiting room
- Checked: Didn't know campus licensing

**Recommendation:**
Perfect Match - Campus already has Zoom enterprise license for all faculty/staff. Department can use immediately at no cost. Contact IT for setup help.

**Outcome:** $2,000/year saved; no new purchase needed

---

### Example 2: Close Match (Survey Tool)

**Request:** "Admissions wants survey tool for prospective student feedback."

**Discovery Questions:**
- Need: Survey high school students, parents; collect contact info; track responses over time
- Users: 5 admissions staff
- Capabilities: Survey creation, email distribution, CRM integration preferred
- Checked: Found Qualtrics but wasn't sure about CRM integration

**Recommendation:**
Close Match - Qualtrics available campus-wide (survey need met). Gap: No native CRM integration. Options:
1. Export Qualtrics data to existing CRM manually (workaround)
2. Use Qualtrics + automation tool (Zapier) for integration
3. Evaluate CRM with built-in survey (bigger project)

**Recommended:** Option 1 or 2 to start; prove value before Option 3

**Outcome:** Use existing tool + lightweight integration; defer larger CRM evaluation

---

### Example 3: Genuine Gap (Lab Scheduling)

**Request:** "Chemistry needs lab equipment scheduling system with safety protocol tracking."

**Discovery Questions:**
- Need: Reserve equipment, track maintenance, enforce safety certifications, chemical inventory
- Users: 200 students + 20 faculty/staff
- Capabilities: Scheduling, certification verification, automated reminders, hazmat compliance
- Checked: Looked at general room scheduling tools; don't meet lab safety requirements

**Recommendation:**
Genuine Gap - Campus room scheduling tools are generic; don't handle safety certifications or equipment maintenance. Specialized scientific research management system justified.

**Next steps:**
1. Formal IT request with detailed requirements
2. Evaluate vendors (iLab, LabArchives, etc.)
3. Check peer institutions (what do similar research universities use?)
4. Budget approval needed ($15K-$30K/year for 200-person license)

**Outcome:** New purchase approved; added to capability inventory as "Research Lab Management"

---

## Common Pitfalls

### Pitfall 1: "We Already Have That" Gatekeeping
**Symptom:** IT forces poor-fit existing tools to avoid new purchases
**Consequence:** Frustration, shadow IT, productivity loss
**Fix:** Honest gap analysis; if existing tool truly doesn't fit, approve new purchase

### Pitfall 2: "Not Invented Here" Syndrome
**Symptom:** Units reject existing campus tools because they weren't involved in selection
**Consequence:** Duplicate spending, fragmented systems
**Fix:** Connect requestors with existing tool users for peer validation

### Pitfall 3: "Perfect is the Enemy of Good"
**Symptom:** Rejecting 90% fit because of one missing feature
**Consequence:** Expensive new purchase for marginal improvement
**Fix:** Cost-benefit analysis of gap criticality vs. workaround effort

### Pitfall 4: "The Capability Inventory Doesn't Exist"
**Symptom:** Can't match requests to existing tools because no one knows what campus has
**Consequence:** Discovery process takes weeks; requests stall
**Fix:** Build basic capability inventory (see `capability-inventory` skill) as foundation

### Pitfall 5: "Vendor Lock-In Bias"
**Symptom:** Recommending existing vendor's solution even when it's poor fit
**Consequence:** Shoehorning needs into wrong tool; user frustration
**Fix:** Capability-first evaluation; willingness to recommend new vendor when justified

---

## References

### Related Skills
- **`capability-inventory`** — Build searchable inventory of campus capabilities
- **`it-request-template`** — Capture functional requirements before discovery
- **`it-governance-advisor`** — Route decisions after capability discovery
- **`stakeholder-mapping-higher-ed`** — Identify who uses existing tools for consultation

### External Resources
- EDUCAUSE IT Service Management
- Software reuse and license optimization frameworks
- TechSoup for higher education technology resources
