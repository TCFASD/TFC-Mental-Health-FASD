# Billing Section Rewrite — Working Draft

**Date drafted:** 2026-05-06
**Status:** All Billing subsections proposed and approved by Tamra. **Edits NOT YET applied to the manual.** This file is the source of truth for tomorrow's edit pass.

---

## How to use this file

When you resume tomorrow, ask Claude to:
1. Read this file in full.
2. Apply the approved rewrites to `FASD_Mental_Health_Onboarding_Manual_REVISED.docx` in the order listed below.
3. Update `questions.docx` if any new questions come up during the edit.

Two items still PENDING external answers from Charmian — they remain flagged in the manual rather than blocking the rewrite. (BPS / IDA reassessment cycle was resolved 2026-05-07: anniversary year, not fiscal year.)

---

## Files modified during the 2026-05-06 session

- `questions.docx` — 2 new bullets under "For Charmian":
  - "Sarasota funds and Mental Health treatment?"
  - "BPS / IDA reassessment cycle — state fiscal year vs. anniversary date" (with full context on what to ask)
- `~/.claude/.../memory/feedback_clinician_language.md` (new) — preference saved: brief, plain-language, action-first; reuse existing tight wording
- `~/.claude/.../memory/MEMORY.md` — pointer added for the new preference

**No changes to the manual file itself this session.** The user's pre-session reorganization notes (the "@Claude" block, intern codes list, conflict log) remain in place; everything else below is proposed-only.

---

## New Billing section structure (approved order)

| New § | Subsection | Source / status |
|---|---|---|
| 3.1 | Billing Absolutes | Existing, unchanged |
| 3.2 | Service Codes | Existing + Group Therapy row filled in |
| 3.3 | Intern Service Codes | NEW table |
| 3.4 | Z Codes | Existing + 1 framing sentence |
| 3.5 | Optimizing Billing | Existing minus Sarasota inline bullet |
| 3.6 | Who Can Bill What | Moved from §6 Assessments, reframed billing-first |
| 3.7 | Timeline for Billing | Consolidated from §6 + §7 + new TP-signature best-practice callout |
| 3.8 | Sarasota County Funds | Promoted from inline bullet; details PENDING Charmian |
| 3.9 | Insurance Requirements | Moved from §6 |
| 3.10 | Payor Usage | Existing, reorganized by payor; H2019 backup PENDING |
| Appendix D | Sources & Regulatory References | NEW |

Note: the previous draft's §3.10 (FASD Client Billing Workflow) is **deleted entirely**. Its content is replaced by the existing "Special Considerations with FASD Evaluations" subsection in §6 plus 2 new documentation bullets.

---

## §3.1 Billing Absolutes — KEEP UNCHANGED

The existing 4-rule table stands as-is:

> **BILLING ABSOLUTES — NO IFS, ANDS, OR BUTS**
> Rule #1. No client can be seen until consents are signed.
> Rule #2. The assessment is always billed first. Nothing else can be billed before it. (ITXXCC and CCM are exceptions because they are not billable codes — see the Service Codes in §3.2.)
> Rule #3. You must complete a Treatment Plan within 10 calendar days from the date of the assessment, and the caregiver must sign it. (Per Rule 65D-30.0044, F.A.C. Note: this is calendar days, not business days.)
> Rule #4. You must track when documents expire and cannot see clients until they have been renewed. This applies to consents, assessments, treatment plans, and treatment plan reviews.

---

## §3.2 Service Codes — UPDATE GROUP THERAPY ROW

Lead-in paragraph: keep as-is.

Existing 14 code rows: keep verbatim.

NOTE bullets (Medicaid 104 units cap, phone-only not reimbursable per Rule 59G-1.057): keep verbatim.

**ONE CHANGE:** the Group Therapy row.

| Code | Service | Limits / Notes |
|---|---|---|
| H2019 HQ | Group Therapy | Maximum 156 quarter-hour units (39 hours) per recipient per state fiscal year. In-person only — Medicaid does not reimburse telehealth groups. Cannot bill group and individual on the same day. |

**APPLIED 2026-05-07.** Replaces the prior placeholder ("Workflow and same-day-as-individual rule pending — see questions.docx"). The "Group + Individual on the same day" bullet has been removed from questions.docx.

---

## §3.3 Intern Service Codes — NEW SUBSECTION — APPLIED 2026-05-07

**Lead-in paragraph:**

> **Intern Service Codes**
>
> Interns track their work using the codes below. The IN suffix tells the EHR that the service is non-billable, so nothing flows to a payor. Use these codes when assigning a case to an intern. The payor depends on the program: for OPMH and FASD, use Non-Payor (intern, high-copay/deductible cases); for SBMH, the work is logged under the school grant. Even though no real dollars are attached, the same compliance and documentation standards apply — a CFARS, BPS, IDA, treatment plan, or DAP note must be completed to the same standard as the licensed clinician's work.

**Table:**

| Code | Service | Units (per recipient per state fiscal year) |
|---|---|---|
| NON-PAYOR | Consult / Mentor / CCM / ITXXCC | 25 |
| H0031 IN | CFARS — Limited Functional Assessment | 3 |
| H0031 HN IN | PSY (Biopsychosocial Assessment) | 1 |
| H0031 HO IN | IDA, new patient | 1 |
| H0031 TS IN | IDA, established patient | 1 |
| H0032 IN | Master Treatment Plan | 1 |
| H0032 TS IN | Treatment Plan Review | 4 |
| H2019 HR IN | Individual / Family Therapy | 200 |
| H2019 HQ IN | Group Therapy | 156 |

---

## §3.4 Z Codes — ADD ONE FRAMING SENTENCE — APPLIED 2026-05-07

Add this one sentence at the top of the existing §3.4:

> Z codes are ICD-10 codes that describe a circumstance or relational issue (e.g., parent-child conflict, family disruption) rather than a billable mental-health diagnosis.

Existing 2 bullets stay verbatim:
- Z codes are not billable codes and cannot serve as the primary diagnosis if the client has insurance coverage.
- If a Z code is the sole diagnosis, consult with your supervisor before submitting any notes.

---

## §3.5 Optimizing Billing — KEEP 4 BULLETS, REMOVE 1 INLINE BULLET — APPLIED 2026-05-07

Keep these 4 bullets (with one minor wording fix on bullet 3):

> - Therapy unit rounding: round based on actual service time. If the last digit of total minutes is 7 or less, round down; if 8 or more, round up. Example: 37 minutes = 2 units; 38 minutes = 3 units.
> - You can bill an individual session and an IDA/BPS on the same day. To do that, schedule 1.5–2 hours so there is no scheduling conflict. If you block 2 hours, that time belongs to that family — they can leave early and you can use the remainder to write reports or score inventories, but you cannot book another client on top.
> - Another option: a clinician can bill all three of the following on the same day: ONE PSY (H0031 HN) or IDA (H0031 HO/TS) — 1 unit, ONE TP (H0032) — 1 unit, ONE CFARS (H0031) — 1 unit. Medicaid only; client must be present.
> - Treatment Plan and individual therapy (ITX) can be billed on the same day, but you can only bill the total time the family was with you. Example: 50 minutes total = 1 hour TP (rounded). 1 hour 15 minutes total = 1 hour TP plus a 15-minute DAP note.

**REMOVE** the "@Claude, this can be with billing…" Sarasota County paragraph that's currently the 5th bullet here. Its content moves to §3.8 Sarasota County Funds.

---

## §3.6 Who Can Bill What — MOVE FROM §6, REWRITE FOR BILLING FRAME

Source: paragraphs currently at §6 Assessments (Who Can Bill What subsection).

**New text:**

> **3.6 Who Can Bill What**
>
> Eligibility to bill a service depends on the clinician's credentials and on who was in the room. Apply these rules before billing any service:
>
> - **To bill any service:** the therapist must meet with the child and caregiver together. If the child was not present, the service is not billable.
> - **To bill an assessment:** the diagnosis must be confirmed by a licensed clinical therapist. A bachelor's-level employee or intern can collect the data, but the diagnosis on the bill must be signed off by a licensed clinician.
> - **BPS vs. IDA:** a bachelor's-level employee or intern can bill a BPS, but cannot bill an IDA. When a non-licensed clinician bills the BPS, a master's-level clinician must complete the Treatment Plan within the 10-day window. If no master's-level therapist is available to pick up the case immediately, we are at risk of falling out of compliance with the Treatment Plan deadline.

The "Who Can Bill What" subsection in §6 is removed (content moves here).

---

## §3.7 Timeline for Billing — NEW CONSOLIDATED SUBSECTION

Pulls timing rules from §6 and §7 into a single billing-driven subsection.

> **3.7 Timeline for Billing**
>
> This section consolidates the timing rules that govern what you can bill and when. Every milestone has a hard deadline tied to compliance.
>
> **Assessment Timeline**
> - Assessments must be completed within 5 business days of the first appointment.
> - Bill the assessment during the first meeting. Have the caregiver bring the child, talk briefly about urgent concerns, and complete your parent-child observation.
> - After this first hour, make a provisional diagnosis. This appointment starts the 5-business-day timeline.
> - If the first session runs longer than one hour, bill the remaining time as therapy (15/30/45/60 minutes). If the client has Sunshine, you can bill the extra time to T1023 instead of therapy.
> - If needed, schedule a second session (parent only, in office or via Zoom) ideally within the same week so you can meet the 5-business-day window. Bill this as a therapy session (DAP note) under the child's provisional diagnosis.
>
> **Treatment Plan Deadline**
> - The Treatment Plan must be completed and reviewed with the caregiver within the 10-calendar-day window from the date of the assessment.
> - The caregiver's signature does NOT have to be received within the 10-calendar-day window.
> - **Best practice:** secure the caregiver's signature as close to the Treatment Plan date as possible. The 10-day rule allows the signature to come later, but prioritizing it prevents compliance gaps if the family disengages or the case is audited.
> - If the caregiver cancels, reschedules, cancels again, and the TP slips past 10 days, make sure there is a no-show note. That becomes part of the clinical record. No separate memo to chart is needed.
> - Because the plan is completed quickly, you may have a provisional diagnosis or treatment goal. You can make an addendum or revise at the Treatment Plan Review. Diagnoses can only be changed at Treatment Plan Reviews or Assessments.
>
> **Example Timeline**
> - Assessment completed 9/01/25.
> - Next session, Treatment Plan, on 9/08/25.
> - Therapy sessions (DAP notes) can begin any time after 9/08/25.
> - Addendums can change diagnosis or goals if needed.
> - Treatment Plan Reviews every 90 days (see review cadence below).
>
> **Treatment Plan Review Cadence**
> - **Practice expectation at TFC: every 90 days / 3 months.** Reviewing on this cadence keeps the family eligible for continued services and extends the time you can work with them.
> - **Compliance floor: at least every 6 months**, with a maximum of 4 reviews per recipient per state fiscal year.
> - Once the plan is done, put the review date on your calendar.
>
> **Billing Rules for Treatment Plans**
> - Treatment Plan and Treatment Plan Review do NOT require the child to be present, but a caregiver must be.
> - The therapist's signature must match the date of service. The parent's signature date does NOT have to match the day you bill it.
> - Billing for the treatment-plan session is based on the actual session. Insurance requires you to provide the service and type it up within the allotted timeframe. If the meeting runs over (say 1.5 hours), you can bill a TP and therapy.

**Source paragraphs being moved/consolidated:**
- §6 paragraphs 240–245 (Assessment Timeline)
- §7 paragraphs 279–284 (Treatment Plan Deadline)
- §7 paragraphs 285–290 (Example Timeline)
- §7 paragraphs 283 + 309 (Review Cadence — both bullets)
- §7 paragraphs 302–305 (Billing Rules for TP)

**What stays behind in §6:** Required Elements at Assessment (BSE, CFARS, child must be present).
**What stays behind in §7:** Overview and Compliance, What the TP Session Looks Like, Required Content and Signatures (minus the every-3-months/every-6-months bullet which moves here), FOXIT signing workflow, "Treatment planning is a collaborative process" line.

---

## §3.8 Sarasota County Funds — NEW SUBSECTION (PENDING Charmian)

> **3.8 Sarasota County Funds**
>
> The Florida Center receives funding from Sarasota County that supplements what Medicaid and commercial insurance reimburse. These funds cover FASD-related services that insurance does not pay for — including FASD consult, case management, mentor work, and continued therapy after Medicaid units have been exhausted.
>
> **Eligibility:** Sarasota County residents only. These funds are not available for clients outside the county.
>
> **Billing:** when a service draws on County funding, the payor is **G-Fetal Alcohol – County**. For the rules on when to select G-Fetal Alcohol – County versus G-Fetal Alcohol – Srq Office, see §3.10 Payor Usage.

PENDING items (in questions.docx, "For Charmian" — bullet "Sarasota funds and Mental Health treatment?"):
- Full list of services covered
- Annual amount or budget cap
- Who approves use
- Who to contact for availability

---

## §3.9 Insurance Requirements — MOVE FROM §6, MARK PENDING

> **3.9 Insurance Requirements**
>
> **Medicaid**
> - A BPS or IDA is billed event-based, not by the 60-minute / quarter-hour maximum that applies to individual or family therapy sessions. Longer sessions are appropriate when the assessment requires it.
> - The Treatment Plan is also event-based, not billed by time.
> - **Reassessment cycle:** Another BPS or IDA cannot be conducted until one year from the original completion date (anniversary date). The Lauris reminder triggers on this anniversary cycle.
>
> **Commercial / Private Insurance**
> - For all insured clients, ensure an IDA or BPS is on file — insurance requires a billable diagnosis, which comes from these forms.
> - Commercial insurance does not have a Treatment Plan code. Look at the authorization for what is covered (typically Assessment and Therapy). The ITP is still required and logged under Non-Payor.
> - For private insurance, check with Durae on unit availability for assessment, treatment plan, and treatment. Each insurer varies; confirm before starting the case.

The §6 Insurance Requirements subsection is removed (content moves here). The Outcomes bullets currently grouped under it stay in §6.

---

## §3.10 Payor Usage — REORGANIZE EXISTING (renumbered from §3.12)

> **3.10 Payor Usage**
>
> Two FASD payors are available. Use this guide to pick the right one. If your situation isn't covered here, check with Charmian.
>
> **G-Fetal Alcohol – County** — Sarasota County clients only.
> - Mental Health intervention with an established Sarasota County client.
> - Evaluation for a confirmed Sarasota County resident (used by the evaluation team).
>
> **G-Fetal Alcohol – Srq Office** — the default for everything else.
> - Any FASD client not covered by the County payor above.
> - The only payor to use with a "FASD Unassigned Client."
> - Backup when a Sarasota County client is running out of Medicaid units and additional units aren't approved. ⚠ *(H2019 specifically under this scenario is PENDING — see questions.docx, "For Charmian.")*

---

## §6 Special Considerations with FASD Evaluations — KEEP USER'S WORDING + ADD 2 BULLETS, REMOVE SOURCE LINE

User's existing 4-line subsection stays verbatim **except** the source line is removed (moves to Appendix D):

> **Special Considerations with FASD Evaluations**
>
> FASD eval within 6 months can be used instead of a BPS.
> Go straight to Treatment Plan at the first session.
> If an FASD evaluation was done within more than the 6 month time period, a BPS or IDA will be required to begin treatment.

**Add at the bottom of this subsection:**

> **When you use the FASD evaluation as the assessment of record:**
> - Keep the FASD Clinic Evaluation in the client chart, with the date and signing practitioner visible.
> - Add a note that you're using the FASD evaluation as the assessment of record and that its findings support medical necessity for the plan.

---

## §3.10 (former) FASD Client Billing Workflow Protocol — DELETE ENTIRELY

The standalone FASD Billing Workflow section (currently between §3.8 and §3.9 in the existing manual, originally Heading 1) is **deleted**.

Reason: the FASD pathway is short enough to live inside §6 Special Considerations (4 lines + 2 documentation bullets). The unique billing rules from this section either live in §3.7 (review cadence) and §3.9 (reassessment cycle), or aren't needed because BSE has been removed from the FASD pathway entirely.

---

## Appendix D. Sources and Regulatory References — NEW APPENDIX

Place after Appendix C (Key Contacts), before any back-matter.

> **Appendix D. Sources and Regulatory References**
>
> Quick reference for the rules cited throughout this manual. Clinicians don't see citations in the body; sources live here for compliance review, audit prep, and supervisor reference.
>
> **Florida Medicaid Community Behavioral Health Services Coverage and Limitations Handbook (March 2014)**
> - Page 2-2: General assessment requirement — assessment within the last 6 months
> - Page 2-7: Brief Behavioral Health Status Examination — basis for the 6-month FASD eval rule (§6 Special Considerations)
> - Page 2-9: In-depth Assessment (IDA)
> - Page 2-11: Bio-psychosocial Evaluation (BPS)
> - Pages 2-13 to 2-16: Treatment Plan Development and Modification
>
> **Florida Administrative Code**
> - Rule 59G-4.028 — Behavioral Health Assessment Services
> - Rule 59G-1.057 — Telemedicine (basis for the no-phone-only rule)
> - Rule 65D-30.0044 — Treatment Plan within 10 calendar days
>
> **Florida Medicaid Community Behavioral Health Fee Schedule** (current state fiscal year)
>
> **Companion files in this folder**
> - Florida_Medicaid_Telehealth_Statewide_Service.docx
> - Medicaid Handbook.pdf (in "Review of power point" subfolder)

---

## Two PENDING items awaiting Charmian

These remain flagged in the manual; they don't block the rewrite.

1. **Sarasota County funds** — full coverage list, annual cap, approver, contact. Affects §3.8.
2. **H2019 under "G-Fetal Alcohol-Srq Office"** when out of units and additional units cannot be approved. Affects §3.10 Payor Usage.

Both are in `questions.docx` under the "For Charmian" heading.

**Resolved 2026-05-07:** BPS / IDA reassessment cycle — using anniversary year (one year from original completion date), not state fiscal year. Reason: clinicians are more familiar with anniversary tracking; fiscal-year framing would confuse staff. Lauris reminder already triggers on the anniversary cycle.

---

## Plan for tomorrow's session

1. Read this file.
2. Apply Billing rewrites in this order (lowest risk first):
   - Update the H2019 HQ row in §3.2 Service Codes table (in-place edit)
   - Add the framing sentence to §3.4 Z Codes
   - Insert §3.3 Intern Service Codes table between §3.2 and §3.4
   - Remove the Sarasota inline bullet from §3.5 Optimizing Billing
   - Build §3.6 Who Can Bill What in Billing; remove from §6
   - Build §3.7 Timeline for Billing in Billing; remove source content from §6 and §7
   - Build §3.8 Sarasota County Funds
   - Build §3.9 Insurance Requirements; remove from §6
   - Reorganize §3.10 Payor Usage (currently §3.12)
   - Delete the FASD Client Billing Workflow Protocol section
   - Add 2 documentation bullets + remove source line in §6 Special Considerations
   - Add Appendix D
3. Renumber Billing subsections cleanly (3.1 → 3.10, no gaps).
4. Verify nothing was lost — diff against backup if needed.
5. Continue with the next major section per the user's reorganization plan: FASD Catchment Area, then Choosing the Billing Client (Child vs. Adult), then Referral to Mental Health.

---

## Reorganization plan beyond Billing (from user's "@Claude" block at top of manual)

For reference, the full sectioning the user wants (in order) — Billing is the only section worked in detail so far:

1. Welcome
2. Billing (THIS SECTION, drafted)
3. FASD Catchment Area
4. Choosing the Billing Client (Child vs. Adult)
5. Referral to Mental Health
6. Intake (Insurance Verification, What Intake does before reaching the therapist, Unit Availability)
7. Before the First Session
8. The First Session (with Confidentiality/Informed Consent, Outcome Measures as subheads)
9. Treatment Plans
10. DAP Notes
11. Closing a Case
12. Client Transfers + Dual Enrollment combined
13. Supervision and Case Consultation (incl. reflective supervision)
14. Groups
15. Supervising Intern
16. Additional Supports (in-house + community; condense "FASD Families May Need More")
17. Lauris / Lauris Reports
18. CAQH
19. Registered Interns: Logging Supervision Hours

Appendices: A (Onboarding Handouts), B (Resources/Recordings/Examples), C (Key Contacts), D (Sources — NEW).
