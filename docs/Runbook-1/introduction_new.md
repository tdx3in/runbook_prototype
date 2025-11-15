---
sidebar_position: 1
title: Introduction
---
# Introduction

Listening Insights on the Sprinklr platform provides centralized social
listening and research capabilities that surface actionable insights
from billions of conversations across social media, news, blogs, forums,
video, and other sources. The product includes Quick Search (formerly
Listening Explorer), a fast query-driven dashboard for building and
modifying research queries, exploring results with advanced search
operators, and accessing Research Query dashboards; Quick Search
requires appropriate Explorer permissions and supports multiple source
types and advanced operators for precise analysis.

This Runbook provides a structured implementation guide for deploying,
configuring, and operationalizing the Listening Insights for Sprinklr
platform. It outlines all key phases, tasks, roles, responsibilities,
deliverables, and RACI for the Client, Implementation Partner, and
Sprinklr.

The document follows a clear phase-wise workflow, starting from
**Pre-Plan** activities and progressing through **Plan, Build, QA,
Educate, Go-Live, and Empower**.

The **Master Table**, presented in the following sections, serves as the
starting point for understanding the workflow: who does what, in what
order, and what each role needs to provide or prepare to ensure a smooth
and successful implementation.

Before using the table, refer to the **Roles and Ownership”** section to
familiarize yourself with all roles, their organizations, and primary
responsibilities. This will help you quickly interpret the Master Table
and understand the contributions of each role throughout the project.

The Master Table consolidates this information into a single reference
point, showing:

- **Who is responsible for each task** (R)

- **Who is accountable, consulted, or informed** (A, C, I)

- **Deliverables or inputs required from each role**

- **The organization the role comes from** (“From”)

- **The sequence of activities** to maintain alignment with the overall
  project plan

This structure enables both the **Client and Implementation Partner** to
execute efficiently while leveraging **Sprinklr’s guidance and best
practices**.

### Acronyms

Following are some of the acronyms that are used across this document
and their expansion.

| Acronym | Expansion                        |
|---------|----------------------------------|
| DP      | Dynamic Properties               |
| FPDI    | Flexible Platform Data Ingestion |
| UAT     | User Acceptance Testing          |
| BRW     | Business Requirements Workbook   |
| SOW     | Statement of Work                |
| SPW     | Solution Project Workbook        |
| LOF     | Level of Effort                  |
| TDD     | Technical Design Document        |
| PDQ     | Pre-Discovery Questionnaire      |
| BAU     | Business As Usual                |

## Roles and Ownership

This table lists all the key roles involved in the Sprinklr
implementation, along with the organization they belong to (**From**)
and their primary responsibilities. The acronyms used in the Master
Table are explained here to help you quickly identify each role and
understand their contributions throughout the project.

**Table 1: Roles and Ownership**

<table>
<colgroup>
<col style={{"width":"20%"}} />
<col style={{"width":"18%"}} />
<col style={{"width":"18%"}} />
<col style={{"width":"43%"}} />
</colgroup>
<thead>
<tr>
<th>Acronym</th>
<th>Full Form</th>
<th>From / Organization</th>
<th>Key Responsibilities</th>
</tr>
</thead>
<tbody>
<tr>
<td>IC (Implementation Consultant)</td>
<td>Implementation Consultant</td>
<td>Implementation Partner/Sprinklr</td>
<td>Configure platform components; build and validate workflows; produce
technical deliverables; run workshops and knowledge transfer; perform
unit testing</td>
</tr>
<tr>
<td>EM (Engagement Manager)</td>
<td>Engagement Manager</td>
<td>Sprinklr</td>
<td>Drive overall engagement delivery; approve major deliverables;
resolve scope or resource escalations; maintain client
communications</td>
</tr>
<tr>
<td>PM (Project/Product Manager)</td>
<td><p>Project Manager</p>
<p>Product Manager</p></td>
<td>Sprinklr</td>
<td>Plan and track schedules; manage dependencies and risks; coordinate
resources and status reporting; enforce milestone sign-offs</td>
</tr>
<tr>
<td>SC (Solution Consultant / Specialist)</td>
<td>Solution Consultant / Specialist</td>
<td>Sprinklr</td>
<td>Provide product architecture and technical design; validate solution
fit; advise on complex configurations and integrations; sell
solutions/products</td>
</tr>
<tr>
<td>Account Team</td>
<td>Account Team</td>
<td>Sprinklr</td>
<td>Validate business requirements; secure stakeholder approvals;
coordinate commercial or contractual inputs; communicate status to
client execs</td>
</tr>
<tr>
<td>Client</td>
<td>Client Business Stakeholders</td>
<td>Client</td>
<td>Provide business requirements and access; review and approve
deliverables; participate in workshops and UAT; adopt configured
solution</td>
</tr>
<tr>
<td>Vendor / Platform Team</td>
<td>Vendor / Platform Team</td>
<td>Sprinklr</td>
<td>Provide platform-level approvals, technical escalation, and
product/ML team inputs</td>
</tr>
</tbody>
</table>

## Master Table 

### How to Read and Use the Master Table

The Master Table consolidates all phases, tasks, roles,
responsibilities, deliverables, RACI, and checkpoints into a single
reference point. This section explains how to interpret the table
effectively, understand the workflow, and identify what each role is
expected to do. By following these instructions, readers can quickly
grasp task ownership, dependencies, required inputs, and the sequence of
activities for a smooth implementation.

Detailed descriptions, a step-by-step break up, and links to assets that
will assist you with these are available in the following sections for
execution guidance.

### Understanding Table Columns

- **Phase:** Refer to these rows to follow the workflow in the correct
  sequence.

- **Responsible:** Indicates the team that is responsible for executing
  the task. Full forms of acronyms (IC, EM, PM, SC, etc.) are explained
  in the “Roles and Ownership” table.

- **Description:** Describes the task summary.

- **Deliverable / Input:** Shows the expected output or the required
  input for the task.

- **RACI:** Indicates whether a role is Responsible, Accountable,
  Consulted, or Informed for the task:

  - **R = Responsible →** Executes the task

  - **A = Accountable →** Ultimately answerable; signs off

  - **C = Consulted →** Provides input or expertise

  - **I = Informed →** Needs updates

- **Checkpoint / Pre-requisite:** Specifies actionable requirements,
  approvals, or conditions that must be completed before moving to the
  next task. Example: *“Must complete research and share notes with
  EM”*. These checkpoints act as **phase-gates** to ensure proper
  sequencing and reduce the risk of missed dependencies.

**Table 2: Master Table**

<table style={{"width":"100%"}}>
<colgroup>
<col style={{"width":"13%"}} />
<col style={{"width":"36%"}} />
<col style={{"width":"16%"}} />
<col style={{"width":"10%"}} />
<col style={{"width":"12%"}} />
<col style={{"width":"9%"}} />
</colgroup>
<thead>
<tr>
<th style={{"textAlign":"center"}}>Responsible</th>
<th style={{"textAlign":"center"}}>Task Description</th>
<th style={{"textAlign":"center"}}>Deliverable / Input</th>
<th style={{"textAlign":"center"}}>RACI</th>
<th style={{"textAlign":"center"}}>Checkpoint / Pre-requisite</th>
<th style={{"textAlign":"center"}}>Duration (hours)</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="6" style={{"textAlign":"center"}}>Pre-Plan phase</td>
</tr>
<tr>
<td style={{"textAlign":"center"}}>Implementation Consultant (IC)</td>
<td style={{"textAlign":"center"}}>Client pre‑work: research
SOW/SPW/LOF/TDD/S2D and prepare PDQ</td>
<td style={{"textAlign":"center"}}>Research summary; PDQ draft; S2S
notes</td>
<td style={{"textAlign":"center"}}><p>R: IC;</p>
<p>A: EM;</p>
<p>C: SC;</p>
<p>I: Client</p></td>
<td style={{"textAlign":"center"}}>Complete research and share with EM; PDQ
pre-filled before Discovery</td>
<td style={{"textAlign":"center"}}>2.5 (explicit) + TDD (TBD)</td>
</tr>
<tr>
<td style={{"textAlign":"center"}}>Engagement Manager (EM)</td>
<td style={{"textAlign":"center"}}>Review/approve IC pre‑work and
coordinate S2S handover</td>
<td style={{"textAlign":"center"}}>Reviewed notes; S2S agenda &amp; meeting
notes</td>
<td style={{"textAlign":"center"}}><p>R: IC;</p>
<p>A: EM;</p>
<p>C:Accounts</p></td>
<td style={{"textAlign":"center"}}>Receive IC research and accept S2S
outputs</td>
<td style={{"textAlign":"center"}}>0.5</td>
</tr>
<tr>
<td style={{"textAlign":"center"}}>Accounts / PM / Client</td>
<td style={{"textAlign":"center"}}>Provide contractual and access
artifacts</td>
<td style={{"textAlign":"center"}}>SOW/SPW/LOF/TDD; tenant access</td>
<td style={{"textAlign":"center"}}><p>R/A: Client; C:Accounts</p>
<p>I: IC/EM</p></td>
<td style={{"textAlign":"center"}}>Provide all documents and tenant access
before platform readiness</td>
<td style={{"textAlign":"center"}}>Varies</td>
</tr>
<tr>
<td style={{"textAlign":"center"}}>Implementation Consultant (IC)</td>
<td style={{"textAlign":"center"}}>Platform readiness &amp; blueprint
hygiene: access checks, module enablement, record DPs</td>
<td style={{"textAlign":"center"}}>Platform readiness checklist; blueprint
hygiene list; DP matrix</td>
<td style={{"textAlign":"center"}}><p>R: IC;</p>
<p>A: PM (access);</p>
<p>C: SC;</p>
<p>I: EM</p></td>
<td style={{"textAlign":"center"}}>Access and blueprint hygiene confirmed
before Build</td>
<td style={{"textAlign":"center"}}>1.0</td>
</tr>
<tr>
<td colspan="6" style={{"textAlign":"center"}}>Plan phase</td>
</tr>
<tr>
<td style={{"textAlign":"center"}}>Implementation Consultant (IC)</td>
<td style={{"textAlign":"center"}}>BRW &amp; Discovery: prefill BRW, run
discovery, capture users/use‑cases/topics/themes/keywords/domains</td>
<td style={{"textAlign":"center"}}>BRW draft/final; Discovery notes;
workshop inputs</td>
<td style={{"textAlign":"center"}}><p>R: IC;</p>
<p>A: EM; Client (approval)</p>
<p>C: SC</p></td>
<td style={{"textAlign":"center"}}>PDQ approved and Discovery
completed</td>
<td style={{"textAlign":"center"}}>5.5 (explicit) + TBD</td>
</tr>
<tr>
<td style={{"textAlign":"center"}}>Client</td>
<td style={{"textAlign":"center"}}>Participate in Discovery and approve
BRW/use‑cases</td>
<td style={{"textAlign":"center"}}>Workshop inputs; approved BRW; signed
use‑cases</td>
<td style={{"textAlign":"center"}}>R/A: Client; C: IC/EM</td>
<td style={{"textAlign":"center"}}>Attend Discovery and sign off BRW before
Build</td>
<td style={{"textAlign":"center"}}>Varies</td>
</tr>
<tr>
<td colspan="6" style={{"textAlign":"center"}}>Build phase</td>
</tr>
<tr>
<td style={{"textAlign":"center"}}>Implementation Consultant (IC)</td>
<td style={{"textAlign":"center"}}>Core build: DP activation, Quick Search,
topics, themes, dashboards, widgets, Smart Insights, alerts</td>
<td style={{"textAlign":"center"}}>DP matrix; Query library; Topics/Themes;
Dashboards; Alert configs</td>
<td style={{"textAlign":"center"}}><p>R: IC;</p>
<p>A: EM (build approval); C: SC;</p>
<p>I: Client</p></td>
<td style={{"textAlign":"center"}}>Approved BRW and necessary SVs before
bulk imports/DP activations</td>
<td style={{"textAlign":"center"}}>6.5 (explicit) + TBD</td>
</tr>
<tr>
<td style={{"textAlign":"center"}}>Solution Consultant / Sprinklr (SC)</td>
<td style={{"textAlign":"center"}}>Product guidance and approvals: TDD
input, source verification, escalations</td>
<td style={{"textAlign":"center"}}>TDD artifacts; approved sources; expert
input</td>
<td style={{"textAlign":"center"}}><p>C/A: SC (product actions);</p>
<p>R: IC executes</p></td>
<td style={{"textAlign":"center"}}>SC guidance and approvals available when
required</td>
<td style={{"textAlign":"center"}}>TBD</td>
</tr>
<tr>
<td style={{"textAlign":"center"}}>Implementation Consultant (IC)</td>
<td style={{"textAlign":"center"}}>FPDI &amp; data pipelines: templates,
mapping, test ingests, function mapping</td>
<td style={{"textAlign":"center"}}>FPDI templates; mapping sheets;
ingestion logs</td>
<td style={{"textAlign":"center"}}><p>R: IC;</p>
<p>C: SC;</p>
<p>I: Client</p></td>
<td style={{"textAlign":"center"}}>BRW field mappings approved;
DP/permissions as required</td>
<td style={{"textAlign":"center"}}>TBD</td>
</tr>
<tr>
<td style={{"textAlign":"center"}}>Implementation Consultant (IC)</td>
<td style={{"textAlign":"center"}}>Integrations and automation: API
integrations, file transfer (FTP/SFTP/S3), exports</td>
<td style={{"textAlign":"center"}}>Integration configs; protocol docs;
export schedules</td>
<td style={{"textAlign":"center"}}><p>R: IC;</p>
<p>C: SC;</p>
<p>I: PM/Client</p></td>
<td style={{"textAlign":"center"}}>Integration requirements in BRW/TDD;
security approvals</td>
<td style={{"textAlign":"center"}}>TBD</td>
</tr>
<tr>
<td style={{"textAlign":"center"}}>Implementation Consultant (IC)</td>
<td style={{"textAlign":"center"}}>Exports, external sharing and PII
handling</td>
<td style={{"textAlign":"center"}}>Export configs; sample exports; PII
policy notes</td>
<td style={{"textAlign":"center"}}><p>R: IC;</p>
<p>A: Client for PII;</p>
<p>C: SC</p></td>
<td style={{"textAlign":"center"}}>PII policy confirmed before masked
exports; export constraints validated</td>
<td style={{"textAlign":"center"}}>TBD</td>
</tr>
<tr>
<td colspan="6" style={{"textAlign":"center"}}>QA phase</td>
</tr>
<tr>
<td style={{"textAlign":"center"}}>Implementation Consultant (IC)</td>
<td style={{"textAlign":"center"}}>Internal QA: UAT tracker, IC
self‑review, peer review, defect logging</td>
<td style={{"textAlign":"center"}}>UAT tracker; defect log; peer review
notes</td>
<td style={{"textAlign":"center"}}><p>R: IC; Peer reviewer;</p>
<p>I: EM</p></td>
<td style={{"textAlign":"center"}}>Build phase completed and evidence
linked</td>
<td style={{"textAlign":"center"}}>0.5 (tracker) + 2 days self‑review +
peer (TBD)</td>
</tr>
<tr>
<td style={{"textAlign":"center"}}>Engagement Manager (EM) / Client</td>
<td style={{"textAlign":"center"}}>External UAT: kickoff, client check‑ins,
triage defects and obtain sign‑off</td>
<td style={{"textAlign":"center"}}>UAT tracker; UAT sign‑off; defect
closure evidence</td>
<td style={{"textAlign":"center"}}><p>R: IC;</p>
<p>A: EM;</p>
<p>R/A: Client</p></td>
<td style={{"textAlign":"center"}}>Internal QA and peer review closed
before external UAT</td>
<td style={{"textAlign":"center"}}>0.75 (kickoff) + TBD sessions</td>
</tr>
<tr>
<td colspan="6" style={{"textAlign":"center"}}>Educate phase</td>
</tr>
<tr>
<td style={{"textAlign":"center"}}>Trainer / IC</td>
<td style={{"textAlign":"center"}}>Training: create plan, deliver sessions,
record and capture attendance</td>
<td style={{"textAlign":"center"}}>Training plan; deck; recordings;
attendance</td>
<td style={{"textAlign":"center"}}><p>R: Trainer/IC; A: EM;</p>
<p>R: Client (attend)</p></td>
<td style={{"textAlign":"center"}}>QA and UAT sign‑off before training</td>
<td style={{"textAlign":"center"}}>2.0 (plan) + session time (TBD)</td>
</tr>
<tr>
<td colspan="6" style={{"textAlign":"center"}}>Go-Live phase</td>
</tr>
<tr>
<td style={{"textAlign":"center"}}>Implementation Consultant (IC)</td>
<td style={{"textAlign":"center"}}>Go‑Live runbook &amp; execution:
pre‑push checks, enable topics, monitor &amp; support</td>
<td style={{"textAlign":"center"}}>Go‑Live plan; checklist; monitoring
logs; sign‑offs</td>
<td style={{"textAlign":"center"}}><p>R: IC;</p>
<p>A: EM;</p>
<p>A: Client (final approval); C: SC</p></td>
<td style={{"textAlign":"center"}}>Training complete; Go‑Live readiness
approval</td>
<td style={{"textAlign":"center"}}>1.0 (planning) + 0.5 (enable
topics)</td>
</tr>
<tr>
<td colspan="6" style={{"textAlign":"center"}}>Empower phase</td>
</tr>
<tr>
<td style={{"textAlign":"center"}}>Implementation Consultant (IC) /
Success</td>
<td style={{"textAlign":"center"}}>Empower &amp; transition: create empower
tracker, run sessions, handover to Success</td>
<td style={{"textAlign":"center"}}>Empower tracker; handover pack; adoption
metrics; Success acceptance</td>
<td style={{"textAlign":"center"}}><p>R: IC;</p>
<p>A: EM;</p>
<p>C: Success; I: Client;</p>
<p>C: SC</p></td>
<td style={{"textAlign":"center"}}>Successful Go‑Live and acceptance of
Go‑Live deliverables</td>
<td style={{"textAlign":"center"}}>7.0 (tracker) + session time (TBD)</td>
</tr>
</tbody>
</table>