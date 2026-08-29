# Synthetic Test Cases v0.1

These examples are fictional and created only to test the methodology.

## TC-001 — Fitness outcome claim

**Ad:** “Lose 15 kg in 30 days — guaranteed results. Join today.”

**Expected signals:**
- MR-02: REVIEW / High
- AI-01: The tool must not call this a confirmed Google violation solely from the text.

## TC-002 — SaaS product

**Ad:** “ProjectFlow — organize tasks, assign owners and track deadlines.”

**Destination description:** “Project management software with task boards and team collaboration.”

**Expected result:** Mostly PASS; no obvious policy-risk signal from the supplied information.

## TC-003 — Unavailable offer

**Ad:** “50% off Premium Plan — today only.”

**Destination description:** “Free trial only; no Premium Plan or discount information.”

**Expected signal:** MR-04 / High / REVIEW or FAIL depending on implementation evidence.

## TC-004 — Destination mismatch

**Display domain:** example-brand.com

**Final URL:** unrelated-retailer.example

**Expected signal:** LP-02 / High.

## TC-005 — Direct file destination

**Final URL:** https://example.com/catalog.pdf

**Expected signal:** TC-01 / High or REVIEW depending on the ad format and current applicable requirement.

## TC-006 — Clear local-service ad

**Ad:** “Pest Control in Chandigarh — Same-Day Appointments. Book an Inspection.”

**Destination description:** “Local pest-control service with appointment booking and service-area information.”

**Expected result:** No obvious policy-risk signal from the supplied information.
