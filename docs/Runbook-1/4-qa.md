# 4. QA

## 4.1 QA (Internal)

### 4.1.1 Create UAT Tracker

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | 0.5                   |                              |

Build a UAT tracker that maps test cases to BRW requirements and
expected outputs, with evidence fields, severity and resolution owner
for each item. Use the tracker to run daily UAT stand-ups, capture
client observations and confirm fixes with retests. Require client
sign-off per module to move to final approval.

Note: include data-validation test cases.

### 4.1.2 Self Review

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | 2 days                | — (Asset not required)       |

During self-review, the IC executes the full test checklist, fixes
trivial issues and logs defects with reproduction steps and screenshots.
Escalate architecture or dev-level defects promptly with a remediation
ETA and confirm fixes once validated. Document any test deviations and
lessons learned for the peer review.

### 4.1.3 Peer Review

| Owner            | Time Duration (hours) | Assets (attach if available) |
|------------------|-----------------------|------------------------------|
| Peer reviewer IC | TBD                   | Peer review checklist        |

Assign a peer reviewer to validate configurations, dashboards, access
controls and data accuracy; the reviewer should produce a concise
remediation plan with owners and deadlines. Ensure the original IC or
reviewer verifies fixes and updates the UAT tracker before moving to
external UAT. Keep peer review artifacts linked in the project folder
for audit.

## 4.2 UAT (External)

### 4.2.1 Platform Configuration Initial Review/UAT Kickoff

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | 0.75                  | UAT Tracker                  |

Kick off client UAT, demonstrate configurations and hand over UAT
tracker; ensure client test accounts are provisioned. Warning: validate
client user roles before UAT.

### 4.2.2 UAT Check-in sessions

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Facilitate client check‑ins, collect feedback and log issues for triage.

### 4.2.3 Final Configuration Review & Approval

| Owner      | Time Duration (hours) | Assets (attach if available) |
|------------|-----------------------|------------------------------|
| IC; Client | TBD                   | — (Asset not required)       |

Obtain client sign‑off on final configuration and close all UAT items
before go‑live. Caution: critical unresolved items must be agreed upon
and scheduled.