---
sidebar_position: 2
title: 1. Pre-Plan
---

# 1. Pre-Plan

## 1.1 Identify Pre-requisites

### 1.1.1 Pre-work for S2S call - Client Research

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | 0.5                   | — (Asset not required)       |

Perform client research including SOW, SPW, LOF and industry best
practices to prepare for the Sales→Service (S2S) call and to shape
discovery questions.

Note: treat this as mandatory preparatory work to capture gaps in
pre-sales artifacts.

### 1.1.2 Pre-work for S2S call – SOW Review

| Owner  | Time Duration (hours) | Assets (attach if available)  |
|--------|-----------------------|-------------------------------|
| IC; EM | 0.5                   | <span class="mark">SOW</span> |

Obtain the SOW from EM/Accounts and validate scope items relevant to
Listening Insights; record missing PBUCs and scope clarifications.

**Note:** New SOWs may omit PBUCs compared to previous versions —
escalate to EM for clarification.

### 1.1.3 Pre-work for S2S call – SPW Review

| Owner | Time Duration (hours) | Assets (attach if available) |
|----|----|----|
| IC; EM | 0.5 | [‎Custom Fields Configurations \| Sprinklr Help Center](https://www.sprinklr.com/help/articles/custom-fields/custom-fields-configurations/645224f7f65d86626c824a91) |

Obtain the SPW documentation from EM/Accounts and review technical and
scope assumptions to inform the solution design.

Note: Capture any deviations from standard scope to feed into BRW.

### 1.1.4 Pre-work for S2S call – LOF Collection

| Owner | Time Duration (hours) | Assets (attach if available)  |
|-------|-----------------------|-------------------------------|
| IC    | 0.5                   | <span class="mark">LOF</span> |

Obtain signed LOF and confirm commercial or legal constraints that may
impact data collection or integrations.

Note: ensure LOF aligns with SOW and SPW.

### 1.1.5 Pre-work for S2S call - TDD

| Owner            | Time Duration (hours) | Assets (attach if available) |
|------------------|-----------------------|------------------------------|
| SC; Account Team | TBD                   |                              |

Collect TDD artifacts from the technical win to capture integration
details and technical constraints for data pipelines.

Note: include any API contract or transformation requirements.

### 1.1.6 Pre-work for S2S call - S2D Validation

| Owner | Time Duration (hours) | Assets (attach if available) |
|----|----|----|
| IC | 0.5 | <span class="mark">S2D</span> <span class="mark">Doc</span> |

Review the S2D provided by Accounts and reconcile it with the Listening
Insights scope; update any missing fields such as topics, keyword lists,
or reporting KPIs. Capture discrepancies in a short issues list and
assign owners to resolve them before discovery. Preserve a copy of the
updated S2D in the project assets for traceability.

Note: maintain a single combined S2D + S2S document if feasible.

### 1.1.7 S2S Meeting and handover

| Owner                 | Time Duration (hours) | Assets (attach if available) |
|-----------------------|-----------------------|------------------------------|
| Accounts Team; IC; PM | 1                     |                              |

Run the Sales→Service handover meeting to transfer deal-level details,
agreed use cases and any custom commitments; confirm which use cases
were sold and capture model or licensing expectations. Record action
items (missing documents, technical contacts, access requirements) and
assign owners with due dates. Use the S2S checklist as the authoritative
handover artifact and store a signed copy in the project folder.

**Note**: Capture decisions on models, KPIs and any exclusions.

## 1.2 Platform Readiness

### 1.2.1 Platform access

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | 0.5                   | — (Asset not required)       |

Verify that all implementation team members have tenant access and that
required modules (Listening, Quick Search, Dashboards, FPDI) are enabled
for the environment. If access gaps exist, open named access requests
and track completion; validate by performing a short checklist: login,
open topic manager, run a saved query and export a widget. Log any
module limitations found and route to the PM for procurement or DP
requests.

**Warning:** Lack of module access will block many build tasks; resolve
access before build begins.

## 1.3 Blueprint Deployment

### 1.3.1 Hygiene Check

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | 0.5                   | — (Asset not required)       |

Audit blueprint deployments in the tenant for unnecessary defaults,
undeletable topics or other artifacts that could confuse configuration
(for example, default Product/Brand topic groups). List items to keep,
hide or document as exceptions; where undeletable defaults cause noise,
create mitigation documentation explaining intended behavior. Confirm
blueprints match BRW expectations and that DPs required by the blueprint
are recorded.

## 1.4 PDQ

### 1.4.1 Prepare PDQ

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | 0.25                  |                              |

Pre-fill the PDQ from S2D and S2S findings to collect required inputs
(data sources, languages, expected location granularity) ahead of
discovery. Highlight any fields that need client confirmation and mark
optional sections clearly so the client knows which inputs are critical
versus advisory. Use the completed PDQ to accelerate discovery and
reduce back-and-forth.

Note: some ICs treat PDQ as optional and collect during discovery—choose
approach per engagement.

### 1.4.2 Share PDQ before Discovery meeting

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | 0.25                  |                              |

Send the PDQ to client stakeholders at least 48 hours before discovery
with explicit instructions on required owners and sections to complete.
Call out language coverage, data refresh expectations, and whether FPDI
or AI features are expected to be used. Track responses and escalate
missing inputs before the scheduled discovery to avoid follow-up delays.

Note: follow up if client does not return PDQ before the meeting.