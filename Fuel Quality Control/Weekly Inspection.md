# Fuel QC — Weekly Inspection Checklist

**Version:** v1.0  
**Updated:** 2026-03-07  
**Duration:** 00:20

---

## Metadata

**Purpose**  
Complete required weekly bonding and corrected DP inspection items within the allowed ATA 103 window.

**Trigger**  
Weekly due window opens for the unit.

**Owner**  
Fuel QC / Supervisor

**Required Items**  
Multimeter, JQC access, daily inspection data, truck ID

**Inputs**  
Last weekly date, due window, daily DP and GPM data, fueling activity

**Outputs**  
Weekly inspection completed, marked good/bad, or closed with NU where applicable

**Stop Conditions**  
Static resistance over limit, failed corrected DP criteria, no access to required readings

---

## PREP

**Objective**  
Confirm the weekly is due and the correct source data is available.

**Checklist**

- [ ] Truck ID Confirmed
- [ ] Weekly due window Verified
- [ ] Calendar-day tolerance Noted → ±1 day from last weekly
- [ ] Daily source data Reviewed
- [ ] Multimeter Ready
- [ ] JQC weekly record Open

---

## STATIC TEST

**Objective**  
Verify bonding cable resistance is within limit.

**Checklist**

- [ ] Meter lead to clamp Set
- [ ] Meter lead to bare metal Set
- [ ] Non-painted metal point Verified
- [ ] Static resistance Logged
- [ ] Static limit Verified → ≤ 25.0 ohms
- [ ] Static condition Good

### DECISION: Is static resistance above 25.0 ohms?

**YES**

- Fail weekly static
- Escalate to supervisor
- RECORD: Log discrepancy

**NO**

- Continue weekly inspection

---

## CORRECTED DP

**Objective**  
Use daily fueling data to complete the weekly corrected DP entry when available.

**Checklist**

- [ ] Daily DP value Retrieved
- [ ] Daily GPM value Retrieved
- [ ] Corrected DP Calculated → System
- [ ] Corrected DP limit Verified → ≤ 15
- [ ] Flow basis Selected
- [ ] Manufacturing procedure Used → Aircraft fueling
- [ ] Max flow Used → Recirculation only
- [ ] Weekly DP status Logged

### DECISION: Was there qualifying fueling data inside the weekly window?

**YES**

- Enter DP and GPM
- Select correct flow basis
- Submit weekly

**NO**

- Leave corrected DP as NU
- Submit weekly with static complete

### DECISION: Was the data taken during recirculation?

**YES**

- Use Max Flow

**NO**

- Use Manufacturing Procedure

---

## CLOSEOUT

**Objective**  
Submit the weekly with the correct combination of static and corrected DP results.

**Checklist**

- [ ] Static section Complete
- [ ] Corrected DP section Complete / N/A
- [ ] Weekly submission Complete
- [ ] Completed-side status Verified

---

## Change Log

**v1.0**

- Added ATA 103 weekly window rule
- Added static resistance criteria
- Added corrected DP source-data logic
