---
name: capability-inventory
description: Document existing campus IT capabilities, software, and services to prevent duplicate requests and enable reuse. Use this to build transparency, connect requestors with existing solutions, and inform governance decisions.
type: component
---


## Purpose
Create and maintain a searchable inventory of campus IT capabilities, software licenses, and services to prevent duplicate requests, enable cross-unit discovery, and inform IT governance decisions. Use this to answer "Do we already have something that does this?" before evaluating new requests, reduce shadow IT, and maximize return on existing investments.

This is not a detailed technical catalog—it's a capability-focused discovery tool that helps non-technical requestors find what's already available.

## Key Concepts

### The Discovery Problem
In decentralized higher ed environments:
- **Units don't know what exists:** History Department doesn't know Engineering has a survey tool
- **Licenses underutilized:** Campus pays for enterprise software used by only one unit
- **Duplicate spending:** Multiple units buy the same capability under different names
- **Integration nightmares:** Disparate tools create data silos and manual workarounds
- **Lost institutional knowledge:** When someone leaves, their tool knowledge goes with them

A capability inventory solves this by:
- **Making capabilities discoverable** by function, not just product name
- **Showing who uses what** to enable peer consultation
- **Identifying underutilized licenses** for expansion before new purchases
- **Surfacing integration patterns** to inform compatibility decisions

### Inventory Dimensions
Track three levels of detail:

**Level 1: Capability Categories (What it does)**
- Communication & Collaboration
- Learning & Course Management
- Student Services
- Research & Data Collection
- Administrative Operations
- Analytics & Reporting
- Security & Compliance

**Level 2: Specific Capabilities (Functional use cases)**
- Video conferencing
- Survey creation
- Grant management
- Budget tracking
- Document signing
- Data visualization

**Level 3: Products/Services (Actual tools)**
- Zoom (video conferencing)
- Qualtrics (survey creation)
- InfoEd (grant management)
- Workday (budget tracking)

### Anti-Patterns (What This Is NOT)
- **Not a technical architecture diagram:** Focus on capabilities, not infrastructure
- **Not a vendor catalog:** Group by function, not alphabetical product list
- **Not static documentation:** Must be maintained as systems change
- **Not IT-only knowledge:** Include shadow IT and unit-managed tools

### When to Use This
- Evaluating new IT requests (check existing capabilities first)
- Onboarding new faculty or staff (what tools are available?)
- Budget planning (identify underutilized licenses)
- Vendor consolidation initiatives (where do we have overlaps?)
- Strategic IT planning (where are capability gaps?)

### When NOT to Use This
- Break/fix support (use service catalog)
- Detailed technical specifications (use architecture documentation)
- Compliance audits (use security inventory)

---

## Application

### Step 1: Structure the Inventory

**Option A: Spreadsheet (Quick Start)**
Simple Google Sheet or Excel file with these columns:

| Capability Category | Specific Capability | Product/Service Name | Description | License Type | Primary Users | Contact | Status | Notes |
|-------------------|-------------------|---------------------|-------------|--------------|---------------|---------|--------|-------|
| Communication | Video Conferencing | Zoom | Enterprise video meetings | Campus-wide | All faculty/staff | IT Support | Active | Education license, 300 participant limit |
| Research | Survey Creation | Qualtrics | Online surveys & forms | Campus-wide | Faculty/staff | Research IT | Active | IRB-approved for research use |
| Administrative | Budget Management | Workday Financial | Budget planning & tracking | Campus-wide | Business officers | Finance IT | Active | Integration with HR system |

**Option B: Searchable Database (Scalable)**
Use a simple database (Airtable, Notion, SharePoint) with:
- **Search by capability:** "I need to create surveys" → Shows Qualtrics, Microsoft Forms, Google Forms
- **Filter by license:** Campus-wide vs. Department-specific
- **Tag by use case:** Research, Teaching, Administration
- **Link to documentation:** Quick start guides, training materials

---

### Step 2: Populate Initial Content

**Data collection methods:**

1. **IT-managed systems (Easy)**
   - Enterprise licenses (ERP, LMS, email, etc.)
   - Centrally purchased software
   - Campus-wide services

2. **Department-managed systems (Harder)**
   - Survey academic units: "What software do you purchase or manage?"
   - Review departmental budgets for software spending
   - Ask IT liaisons in each college/division

3. **Shadow IT discovery (Hardest)**
   - Review credit card statements for SaaS subscriptions
   - Survey faculty/staff: "What tools do you pay for personally for work use?"
   - Check app integrations with known systems (e.g., what connects to Google Workspace?)

**Start with the easy wins:** Document IT-managed systems first, then expand incrementally.

---

### Step 3: Make It Discoverable

**Minimum viable inventory launch:**

1. **Create simple search interface**
   - Web page or shared document
   - Organized by capability category
   - Search box or table of contents

2. **Promote it in request process**
   - Link in IT request template ("Before requesting new software, check our capability inventory")
   - Require requestors to document what they found (or didn't find)

3. **Enable feedback loop**
   - "Don't see what you need? Click here to suggest an addition."
   - "Found an error? Report it here."

**Example structure:**

```markdown
# Campus IT Capability Inventory

**Need software or a tool? Check here first to see if we already have it.**

## How to Use This
1. Browse by category below OR use Ctrl+F to search for a capability
2. If you find something that might work, contact the listed owner
3. If you don't find what you need, submit an IT request

---

## Communication & Collaboration

### Video Conferencing
- **Zoom** (Campus-wide)
  - Purpose: Video meetings, webinars, virtual office hours
  - License: Education account, 300 participants
  - Access: All faculty/staff via SSO
  - Support: help@university.edu
  - Documentation: [link]

- **Microsoft Teams** (Campus-wide)
  - Purpose: Team collaboration, chat, video calls
  - License: Included with Microsoft 365
  - Access: All faculty/staff/students
  - Support: help@university.edu
  - Documentation: [link]

### Document Collaboration
- **Google Workspace** (Campus-wide)
  - Purpose: Docs, Sheets, Drive, shared folders
  - Access: All community members with university email
  - Support: help@university.edu

- **Microsoft 365** (Campus-wide)
  - Purpose: Word, Excel, PowerPoint, OneDrive
  - Access: All community members
  - Support: help@university.edu

---

## Research & Data Collection

### Survey Tools
- **Qualtrics** (Campus-wide)
  - Purpose: Surveys, forms, research data collection
  - License: Enterprise license, unlimited users
  - IRB approved: Yes (for human subjects research)
  - Access: Request via [link]
  - Training: Monthly workshops
  - Contact: research-it@university.edu

- **REDCap** (Available to research faculty)
  - Purpose: Clinical research data capture, secure databases
  - License: Free, open-source, hosted by Health Sciences IT
  - IRB approved: Yes
  - Access: Request via Health Sciences IT
  - Contact: healthsci-it@university.edu

---

## Learning & Course Management

### Learning Management Systems
- **Canvas** (Primary LMS)
  - Purpose: Course sites, assignments, grades
  - Access: All instructors, automatic enrollment
  - Support: teaching-support@university.edu
  - Training: Faculty workshops each semester

### Lecture Capture
- **Panopto** (Campus-wide)
  - Purpose: Record lectures, create video libraries
  - Access: All instructors
  - Integration: Auto-uploads to Canvas
  - Support: teaching-support@university.edu
```

---

### Step 4: Keep It Current

**Maintenance rhythm:**

- **Monthly:** Add new IT-managed systems and updates
- **Quarterly:** Review with department liaisons for changes
- **Annually:** Comprehensive review; remove retired systems

**Update triggers:**
- New enterprise license purchased
- System decommissioned
- License expansion (e.g., campus-wide → department-specific)
- User feedback about missing capabilities

**Ownership:**
- **Content owner:** IT leadership or governance committee
- **Maintainers:** IT liaisons in each functional area
- **Contributors:** Anyone can suggest additions

---

## Examples

### Example 1: Request Deflection (Good Outcome)

**Request:** "English Department wants to buy a video conferencing tool for virtual office hours."

**Capability inventory check:** Shows Zoom and Microsoft Teams both available campus-wide

**IT response:** "We have two video conferencing options available at no additional cost:
- Zoom: Best for scheduled meetings, webinars
- Teams: Best for ongoing team collaboration, integrated with Office 365

Would you like a training session to help you set up virtual office hours in either platform?"

**Outcome:** No new purchase needed; department uses existing tool; IT provides training

---

### Example 2: License Optimization

**Inventory reveals:** Qualtrics enterprise license paid by central IT, but only used by Psychology and Marketing departments (20 users out of 500 potential users)

**Action:** 
- IT communicates Qualtrics availability to all departments
- Creates quick-start guide and training series
- Usage grows to 150 users across campus
- ROI on existing license increases dramatically

**Outcome:** Better utilization of existing investment; other units avoid buying redundant survey tools

---

### Example 3: Strategic Vendor Consolidation

**Inventory shows:**
- 12 different project management tools across campus
- Annual cost: $47,000 total
- No integration between them
- Duplicate training costs

**Governance decision:**
- Evaluate top 3 tools (most users, best features)
- Select one for campus-wide standard
- Negotiate enterprise pricing: $18,000/year
- Migrate users over 12 months
- Savings: $29,000/year + reduced support complexity

**Outcome:** Inventory enabled data-driven consolidation decision

---

### Example 4: Shadow IT Discovery

**During inventory process, discovered:**
- 17 faculty paying for Dropbox Pro personally ($119/year each)
- Total spend: $2,023/year in duplicate of existing Google Drive and OneDrive licenses

**IT action:**
- Communicated free alternatives in capability inventory
- Offered migration assistance
- Saved faculty $2,000/year
- Reduced security risk (personal accounts outside institutional control)

---

## Common Pitfalls

### Pitfall 1: "The Catalog of Everything"
**Symptom:** Inventory lists every technical detail; overwhelming for non-technical users
**Consequence:** No one uses it; requests don't reference it
**Fix:** Keep it capability-focused and jargon-free; link to detailed docs for technical users

### Pitfall 2: "Build It and They Will Come"
**Symptom:** Inventory created but never promoted or integrated into processes
**Consequence:** Sits unused; duplicate requests continue
**Fix:** Embed in request process; require requestors to document their inventory search

### Pitfall 3: "IT Knows Best"
**Symptom:** Only IT-managed systems included; ignoring department-specific tools
**Consequence:** Incomplete picture; missed opportunities for reuse
**Fix:** Actively survey academic/admin units; include shadow IT once discovered

### Pitfall 4: "Stale Data"
**Symptom:** Inventory never updated; links dead, systems retired but still listed
**Consequence:** Loss of trust; users stop checking
**Fix:** Assign maintenance owners; quarterly review cycle; easy feedback mechanism

### Pitfall 5: "Product Names Only"
**Symptom:** Organized alphabetically by vendor/product name (e.g., "Qualtrics" under Q)
**Consequence:** Users don't know to look for "Qualtrics" when they need "survey tool"
**Fix:** Organize by capability first; make product name secondary

---

## References

### Related Skills
- **`it-request-template`** — Require capability check before new requests
- **`capability-discovery-advisor`** — Interactive guide to match requests with existing capabilities
- **`it-governance-advisor`** — Use inventory to inform governance decisions
- **`risk-assessment-higher-ed`** — Assess security/compliance risks of shadow IT discovered in inventory

### External Resources
- EDUCAUSE IT Service Management resources
- ITIL Service Catalog practices
- Technology Business Management (TBM) frameworks for IT portfolio management
