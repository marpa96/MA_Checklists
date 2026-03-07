# Fuel QC — Monthly Inspection Checklist
**Version:** v1.1
**Updated:** 2026-03-07  
**Duration:** 01:15

---

## Metadata

**Purpose**  
Complete the monthly equipment, fuel-quality, placard, safety, and function checks for a refueler.

**Trigger**  
Monthly due date for the unit in JQC / MX dashboard.

**Owner**  
Fuel QC / Supervisor

**Required Items**  
Millipore / membrane kit, free-water kit, nozzle tools, multimeter if needed, recirculation setup, inspection access, PPE

**Inputs**  
Truck ID, monthly record, hose certification file, placard standard, monthly due status

**Outputs**  
Monthly inspection completed or escalated with discrepancy

**Stop Conditions**  
Fuel contamination, failed E-stop / dead man criteria, damaged hose, missing placards, failed safety equipment

---

## PREP

**Objective**  
Confirm the unit, due status, and tools before starting the monthly.

**Checklist**

- [ ] Truck ID                          Confirmed
- [ ] Monthly record                    Open
- [ ] PPE                               Present
- [ ] Fuel test kit                     Ready
- [ ] Recirculation setup               Ready
- [ ] Access to tank top                Verified

---

## FUEL QUALITY

**Objective**  
Complete the monthly fuel-quality checks.

**Checklist**

- [ ] Filter membrane test              Complete
- [ ] Membrane result                   Observed
- [ ] Free-water test                   Complete
- [ ] Free-water result                 Observed
- [ ] Third Defense water system        N/A → Quarterly only

### DECISION: Did fuel-quality testing show contamination or abnormal result?

**YES**
- Stop use of affected unit
- Escalate to supervisor
- RECORD: Log discrepancy

**NO**
- Continue monthly inspection

---

## NOZZLES / HOSES / PLACARDS

**Objective**  
Verify nozzle screens, hose condition, and required markings.

**Checklist**

- [ ] Nozzle                            Checked

    - [ ] Screens removed               Complete
    - [ ] Debris                        None
    - [ ] Cleaning                      Complete / N/A

- [ ] Hose                              Checked

    - [ ] Full length inspected         Complete
    - [ ] Abrasions                     None
    - [ ] Bubbles                       None
    - [ ] Cracks                        None
    - [ ] Expiration entry              N/A → Controlled by separate audit

- [ ] Placards                          Verified

    - [ ] Flammable placard             Verified
    - [ ] No smoking placard            Verified
    - [ ] UN 1863 marking               Verified
    - [ ] Double diamond                Verified
    - [ ] Jet A labels                  Verified
    - [ ] Four-side labeling            Verified
    - [ ] Stop labels                   Verified
    - [ ] Fire extinguisher labels      Verified

### DECISION: Is any hose damaged or placard missing?

**YES**
- Escalate to supervisor
- RECORD: Log discrepancy
- Hold unit as directed

**NO**
- Continue monthly inspection

---

## METER / FIRE EQUIPMENT

**Objective**  
Verify meter seals and extinguisher condition.

**Checklist**

- [ ] Meter calibration seal            Verified
- [ ] Seal year / color                 Checked
- [ ] Seal condition                    Good
- [ ] Fire extinguisher count           Verified → Two per truck
- [ ] Extinguisher annual tag           Checked
- [ ] Extinguisher monthly tag          Checked
- [ ] Extinguisher tamper seal          Verified
- [ ] Extinguisher pin                  Verified
- [ ] Extinguisher charge               Full
- [ ] Extinguisher instructions         Legible

---

## E-STOPS / DEAD MAN

**Objective**  
Verify shutdown performance during recirculation.

**Checklist**

- [ ] Single-point hookup               Set
- [ ] Recirculation flow                Started
- [ ] Flow stabilized                   Verified
- [ ] Dead man test                     Complete
- [ ] Dead man rollover                 Logged
- [ ] E-stop test                       Complete
- [ ] E-stop rollover                   Logged
- [ ] Flow rate                         Logged
- [ ] Rollover limit                    Verified → ≤ 5% of flow rate
- [ ] System result                     Checked

### DECISION: Did dead man or E-stop exceed 5% rollover?

**YES**
- Truck out of service                  Escalated
- RECORD: Log discrepancy
- Follow return-to-service process

**NO**
- Continue monthly inspection

---

## TANK / VENTS / DRAINS

**Objective**  
Inspect internal and external truck tank condition.

**Checklist**

- [ ] Tank top opened                   Complete
- [ ] Tank interior                     Inspected
- [ ] Sediment                          None
- [ ] Microbes / bacteria               None observed
- [ ] Free-standing water               None
- [ ] Dome cover seals                  Checked
- [ ] Vent condition                    Checked
- [ ] Dry rot                           None
- [ ] Trough drains                     Checked
- [ ] Drain obstructions                None

---

## FSII / PRIST

**Objective**  
Verify FSII injection is within the accepted range.

**Checklist**

- [ ] FSII test mode                    Set
- [ ] Valves for test path              Verified
- [ ] Prist sample volume               Logged
- [ ] Reference fuel quantity           Verified → 100 gallons
- [ ] FSII concentration                Calculated
- [ ] FSII limit                        Verified → 0.10% to 0.15%
- [ ] Approx. mL range                  Checked → ~390 to 450 mL

### DECISION: Is FSII concentration outside 0.10%–0.15%?

**YES**
- Escalate to supervisor
- RECORD: Log discrepancy
- Hold unit as directed

**NO**
- Continue monthly closeout

---

## EXCEPTIONS

**Objective**  
Capture recurring monthly exceptions tied to specific trucks.

<details>
<summary>Truck 521 — pneumatic E-stop behavior</summary>

- [ ] 521 air-operated system           Noted
- [ ] E-stop adjustment                 N/A → No practical adjustment
- [ ] Repeat over-limit tendency        Observed
- [ ] Supervisor review                 Required

</details>

<details>
<summary>Lift platform item</summary>

- [ ] Lift platform                     N/A → No trucks equipped

</details>

---

## CLOSEOUT

**Objective**  
Submit the monthly and document issues correctly.

**Checklist**

- [ ] Monthly sections                  Complete
- [ ] N/A items                         Marked
- [ ] RECORD: Discrepancies             Logged
- [ ] Monthly submission                Complete
- [ ] MX dashboard status               Verified

---

## Change Log

**v1.0**

- Added monthly fuel-quality and function checks
- Added FSII / Prist range verification
- Added truck-specific 521 exception note
