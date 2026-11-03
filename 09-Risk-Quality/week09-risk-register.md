# Risk Register: RCHN Patient Intake and Scheduling System

**Consultant:** Raian Hammad
**Role:** Associate Consultant, NovaTech Consulting
**Engagement:** Regional Care Health Network (RCHN)
**Date:** November 3, 2026

---

## Risk Entries

### Risk 1
**Description:** If staff are unavailable for training, then the rollout schedule may be delayed.
**Probability:** High
**Impact:** Medium
**Score:** 6
**Response Strategy:** Mitigate. Schedule extra training sessions if staff are unavailable.
**Trigger:** Staff miss scheduled training.
**Owner:** Project Manager, because they coordinate training and the schedule.

### Risk 2
**Description:** If clinics cannot follow the same intake workflow, then system requirements may need to change.
**Probability:** Medium
**Impact:** High
**Score:** 6
**Response Strategy:** Mitigate. Review clinic workflows and adjust requirements if needed.
**Trigger:** A clinic reports that the standard workflow does not meet its needs.
**Owner:** Product Owner, because they help ensure the system meets clinic needs.

### Risk 3
**Description:** If additional appointment data errors occur during migration, then patients may experience scheduling problems.
**Probability:** High
**Impact:** High
**Score:** 9
**Response Strategy:** Mitigate. Check migrated appointment data, correct errors, and test again.
**Trigger:** Additional data errors are found during migration or testing.
**Owner:** Developer, because they can investigate and fix data problems with the IT team.

### Risk 4
**Description:** If important acceptance tests cannot be completed successfully, then the system launch may be delayed.
**Probability:** Medium
**Impact:** High
**Score:** 6
**Response Strategy:** Avoid. Delay the affected launch until critical tests are completed successfully.
**Trigger:** Important acceptance tests fail or remain incomplete near launch.
**Owner:** Product Owner, because they check acceptance requirements.

### Risk 5
**Description:** If the scheduling module has unresolved technical problems, then clinic operations may be disrupted.
**Probability:** Medium
**Impact:** High
**Score:** 6
**Response Strategy:** Mitigate. Test the scheduling module and fix technical problems before launch.
**Trigger:** Testing finds system errors or failures.
**Owner:** Developer, because they investigate technical problems.

---

## Bring Forward

**Week 5 assumptions:**
1. Staff at all six clinics will be available for training.
2. The six clinics will be able to follow the same intake and scheduling workflow.

**Week 7 backlog item:** Standardize patient intake fields across all six clinics (RCHN-101). Verify its priority against your Week 7 backlog.

**Week 8 schedule item:** User Acceptance Testing (UAT), predecessor 3.2, planned weeks 12–13.

## Assumption Connection

Risk 1 connects to my Week 5 assumption about staff availability. If this is wrong, training and rollout may be delayed.

Risk 2 connects to my Week 5 assumption about a shared workflow. If this is wrong, requirements and scope may need to change.

## Score Justification

For Risk 1, I chose High probability because two clinics have not finished training. I chose Medium impact because training problems could cause delays and confusion.

For Risk 3, I chose High probability because appointment data problems have already been found, and more errors could appear. I chose High impact because incorrect information could affect patients and clinic operations.

## Risk Reflection

### Highest Priority Risk and Project Impact

Risk 3 has the highest score of 9. Additional appointment data errors could affect quality by causing scheduling mistakes, delay the launch through extra testing, and reduce patient and staff trust.

### Risk Versus Issue

Risk 1: More staff may be unavailable for training.
Risk 2: Some clinics may not be able to use the same workflow.
Risk 3: More appointment data errors may appear.
Risk 4: Important acceptance tests may fail.
Risk 5: The scheduling module may develop technical problems.

Some appointment data errors and unfinished training and testing are already known issues. My risks focus on what could happen next.

This matters because issues need action now, while risks need planning and monitoring.
