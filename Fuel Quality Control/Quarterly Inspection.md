# Fuel QC — Quarterly Inspection Checklist

**Version:** v1.0  
**Updated:** 2026-03-07  
**Duration:** 00:45

---

## Metadata

**Purpose**  
Complete the quarterly vehicle, pressure-control, water-defense, valve, interlock, and DP-limiting checks.

**Trigger**  
Quarterly due date for the unit in MX dashboard.

**Owner**  
Fuel QC / Supervisor

**Required Items**  
Recirculation setup, truck access, control access, MX dashboard record

**Inputs**  
Truck ID, quarterly record, unit-specific equipment configuration

**Outputs**  
Quarterly inspection completed, N/A items marked correctly, discrepancies logged

**Stop Conditions**  
Failed internal valve check, failed interlock override, failed DP-limiting test, unsafe vehicle condition

---

## PREP

**Objective**  
Confirm the truck configuration and due items before inspection.

**Checklist**

- [ ] Truck ID Confirmed
- [ ] Quarterly record Open
- [ ] Unit configuration Reviewed
- [ ] Recirculation setup Ready
- [ ] Water-defense item Applicable check planned
- [ ] DP-limiting device Applicability reviewed

---

## CORE

**Objective**  
Complete the quarterly checks required for the specific unit.

**Checklist**

- [ ] Basic vehicle inspection Complete
- [ ] Pressure controls Checked
- [ ] Third Defense water system Checked
- [ ] Internal valve check Complete
- [ ] Pre-check lever function Verified
- [ ] Fuel stop on pre-check Verified
- [ ] Interlock override Checked
- [ ] Drive override with hose out Verified

### DECISION: Did internal valve or interlock override fail?

**YES**

- Escalate to supervisor
- RECORD: Log discrepancy
- Hold unit as directed

**NO**

- Continue quarterly inspection

---

## DP LIMITING DEVICE

**Objective**  
Test the DP shutdown feature on equipped trucks only.

**Checklist**

- [ ] DP limiting device Applicability checked
- [ ] 5250 device presence Verified
- [ ] 521 device presence N/A
- [ ] J52 device presence N/A
- [ ] J50 device presence N/A
- [ ] Recirculation flow Started
- [ ] Blue test button Activated
- [ ] DP spike to 15 Verified
- [ ] Automatic fueling shutdown Verified
- [ ] Small discharge observed Noted

### DECISION: Is this truck equipped with a DP limiting device?

**YES**

- Perform DP shutdown test
- Verify shutdown at 15 DP

**NO**

- Mark item N/A

### DECISION: Did equipped truck fail shutdown at 15 DP?

**YES**

- Escalate to supervisor
- RECORD: Log discrepancy
- Hold unit as directed

**NO**

- Continue quarterly closeout

---

## REFERENCES

**Objective**  
Capture the truck-specific applicability rules used during the quarterly.

**Checklist**

- [ ] 5250 DP limiting device Noted → Equipped
- [ ] 521 DP limiting device Noted → Not equipped
- [ ] J52 DP limiting device Noted → Not equipped
- [ ] J50 DP limiting device Noted → Not equipped

---

## CLOSEOUT

**Objective**  
Submit the quarterly with correct N/A handling and discrepancy logging.

**Checklist**

- [ ] Quarterly items Complete
- [ ] Non-applicable items Marked N/A
- [ ] RECORD: Discrepancies Logged
- [ ] Quarterly submission Complete
- [ ] MX dashboard status Verified

---

## Change Log

**v1.0**

- Added quarterly control and valve checks
- Added DP-limiting device applicability logic
- Added truck-by-truck N/A references
