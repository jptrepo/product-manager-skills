# Example: Using Higher Ed Skills to Evaluate a Software Request

**Scenario:** The Psychology Department has submitted a request for survey software for research studies.

---

## Step 1: Structured Intake (5 minutes)

**Use:** `it-request-template/SKILL.md`

**AI Agent Prompt:**
```
Using the IT Request Template skill, help me ensure I have complete 
information from the Psychology Department about their survey software request.
```

**Template Filled Out:**
- **Requestor:** Dr. Sarah Chen, Psychology Department Chair
- **Problem:** Faculty use free tools that don't meet IRB requirements; compliance risk
- **Desired Outcomes:** IRB-compliant surveys, FERPA-compliant storage, SPSS export
- **Users:** 15 faculty + 30 graduate students
- **Timeline:** Needed before fall semester research projects begin (3 months)
- **Existing Solutions Check:** "We looked but weren't sure what campus has"

**Status:** ✅ Complete information captured

---

## Step 2: Capability Discovery (15 minutes)

**Use:** `capability-discovery-advisor/SKILL.md`

**AI Agent Prompt:**
```
Using the Capability Discovery Advisor, help me determine if our campus 
already has survey software that meets the Psychology Department's needs 
for IRB-compliant research data collection.
```

**Agent asks:**
1. What are you trying to accomplish?
   → "IRB-compliant survey creation and data collection for research"

2. Who will use this and scale?
   → "Department-level: 15 faculty, 30 grad students"

3. What capabilities needed?
   → Must-haves: Survey creation, IRB compliance, FERPA storage, data export
   → Nice-to-haves: Advanced logic, mobile-friendly

4. What has been explored?
   → "Requestor looked but wasn't sure what exists on campus"

**Agent checks capability inventory:**

**FINDING: Perfect Match! ✅**

Campus has **Qualtrics** enterprise license:
- ✅ IRB-approved for human subjects research
- ✅ FERPA-compliant data storage
- ✅ Export to SPSS, CSV, Excel
- ✅ Already used by Marketing and Sociology departments
- ✅ Campus-wide license: unlimited users
- ✅ Training workshops offered monthly

**Recommendation:** Use existing Qualtrics; no new purchase needed

---

## Step 3: Governance Routing (10 minutes)

**Use:** `it-governance-advisor/SKILL.md`

**AI Agent Prompt:**
```
Using the IT Governance Advisor, determine the appropriate routing path 
for granting the Psychology Department access to our existing Qualtrics license.
```

**Agent asks:**
1. Scope? → Unit-specific (one department)
2. Strategic impact? → Operational (supporting existing research)
3. Resource requirements? → Low (existing system, no cost)
4. Stakeholder complexity? → Simple (one department, IT provisioning)
5. Urgency? → Moderate (3 months to fall semester)

**Agent recommends: FAST TRACK**

**Process:**
1. IT liaison confirms Qualtrics capabilities meet needs
2. Psychology Department approves $0 cost
3. IT provisions access and schedules training
4. Notify governance committee (FYI only)

**Timeline:** 1-2 weeks

---

## Step 4: Communication & Implementation (1 week)

**Response to Psychology Department:**

```
Subject: IT Request Approved - Research Survey Software (REQ-2024-042)

Dear Dr. Chen,

Good news! We can meet your survey research needs with our existing 
campus Qualtrics license.

**Solution:**
Qualtrics enterprise license (already available on campus)

**Why this works:**
✓ IRB-approved for human subjects research
✓ FERPA-compliant data storage
✓ Export formats you need (SPSS, CSV, Excel)
✓ Mobile-friendly and advanced survey logic
✓ No additional cost to your department
✓ Peer departments (Marketing, Sociology) already using successfully

**Next Steps:**
1. We will provision Qualtrics access for your 15 faculty (this week)
2. Graduate students can request access via IT portal
3. Monthly training workshops available (next session: Aug 15)
4. Research IT will contact you to discuss IRB approval workflow

**Timeline:**
- Access provisioned: Within 3 business days
- Training session: Aug 15 or on-demand
- Ready for fall research: Well ahead of your deadline

**Contact for support:**
research-it@university.edu

You'll save ~$3,000/year vs. purchasing separate licenses, and your 
research will be compliant from day one.

Thank you,
Academic IT Team
```

---

## Outcome Summary

**Time Invested:**
- Intake: 5 minutes
- Capability discovery: 15 minutes
- Governance routing: 10 minutes
- Communication: 5 minutes
- **Total: 35 minutes**

**Results:**
- ✅ Perfect match found with existing campus capability
- ✅ $3,000/year saved (vs. new purchase)
- ✅ Requestor gets solution within 1 week (vs. 2-3 months for new procurement)
- ✅ Compliance requirements met immediately
- ✅ Increased utilization of existing enterprise license

**Process Quality:**
- Transparent timeline communicated upfront
- Existing tool validated against requirements
- Peer users identified for consultation
- Training resources provided
- Decision documented for future similar requests

---

## What If Discovery Had Found No Match?

**If Qualtrics didn't exist on campus:**

1. **Capability Discovery** would identify genuine gap
2. **Governance Advisor** would route to Standard Review (new purchase, department-level, medium cost)
3. **Process:**
   - Week 1-2: Evaluate 2-3 survey tool vendors
   - Week 3-4: Check peer institutions (what do similar research universities use?)
   - Week 5-6: Psychology Department budget approval
   - Week 7-8: License purchase and provisioning
   - Total: 8 weeks
4. **Communication:** Clear timeline set; Psychology knows to expect 8 weeks, not 1 week

**Key Difference:** 
Discovery process saves time when matches exist AND sets realistic expectations when new purchases are needed.

---

## Lessons Learned

**For IT Teams:**
1. **Always check inventory first** — Saves time and money
2. **Connect requestors with existing users** — Peer validation builds confidence
3. **Fast-track when appropriate** — Not everything needs committee approval
4. **Transparent communication** — Clear timeline, rationale, and next steps

**For Requestors:**
1. **Use the template** — Complete information enables faster evaluation
2. **Check capability inventory** — You might be surprised what campus already has
3. **Trust the process** — Fast-track takes 1-2 weeks; worth it vs. buying on own

**For Governance:**
1. **Document decisions** — Future similar requests can reference this one
2. **Update capability inventory** — Add Psychology as Qualtrics user
3. **Measure success** — Track duplicate spending prevented

---

**This example demonstrates the complete higher-ed skills framework in action.**

