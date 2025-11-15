# Introduction

This Runbook provides a structured implementation guide for deploying,
configuring, and operationalizing the Sprinklr platform. It outlines all
key phases, tasks, roles, responsibilities, deliverables, and RACI for
the **Client, Implementation Partner, and Sprinklr**.

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

## Roles and Ownership

This table lists all the key roles involved in the Sprinklr
implementation, along with the organization they belong to (**From**)
and their primary responsibilities. The acronyms used in the Master
Table are explained here to help you quickly identify each role and
understand their contributions throughout the project.

**Table 1: Roles and Ownership**

| Acronym | Full Form | From / Organization | Key Responsibilities |
|----|----|----|----|
| IC (Implementation Consultant) | Implementation Consultant | Implementation Partner | Executes the work: configures platform, prepares deliverables, runs workshops |
| EM (Engagement Manager) | Engagement Manager | Implementation Partner | Oversees tasks, ensures completion, approves deliverables |
| PM (Project Manager) | Project Manager | Implementation Partner | Manages timelines, coordinates tasks, monitors overall project progress |
| SC (Solution Consultant / Specialist) | Solution Consultant / Specialist | Sprinklr | Provides product-specific guidance, technical expertise, and best practices |
| Account Team | Client-side Account Team | Client | Approves business requirements, communicates updates to stakeholders |
| Client | Client Business Stakeholders | Client | Provides requirements, approves deliverables, adopts platform |
| Sprinklr | Vendor / Platform Team | Sprinklr | Provides technical guidance, platform approvals, and escalations |

## Master Table 

### How to Read and Use the Master Table

The Master Table consolidates all phases, tasks, roles,
responsibilities, deliverables, RACI, and checkpoints into a single
reference point. This section explains how to interpret the table
effectively, understand the workflow, and identify what each role is
expected to do. By following these instructions, readers can quickly
grasp task ownership, dependencies, required inputs, and the sequence of
activities for a smooth implementation.

#### Understanding Table Columns

- **Phase and Step:** Refer to these columns to follow the workflow in
  the correct sequence.

- **Role:** Indicates who is responsible for executing the task. Full
  forms of acronyms (IC, EM, PM, SC, etc.) are explained in the “Role
  Acronyms & From” section.

- **From:** Shows the organization the role belongs to (Client,
  Implementation Partner, or Sprinklr).

- **Responsibility / Task:** Describes what the role must do for the
  task.

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

#### Understanding Roles and RACI

The following logic was applied when mapping roles and assigning RACI in
the Master Table:

- **IC (Implementation Consultant)** → Responsible for executing the
  tasks, preparing deliverables, and running workshops.

- **EM (Engagement Manager)** → Accountable for oversight, approvals,
  and ensuring tasks are completed according to plan.

- **Client (Business Stakeholders)** → Responsible for providing inputs
  and information; Accountable for approvals and sign-offs.

- **SC (Solution Consultant / Specialist)** → Consulted for
  product-specific guidance and technical expertise; occasionally
  Accountable for tasks only Sprinklr can perform.

- **PM (Project Manager)** → Can be included to coordinate timelines,
  dependencies, and overall project tracking.

- **Account Team (Client-side)** → Provides oversight, communicates
  updates to stakeholders, and supports approvals.

**Table 2: Master Table**

| Phase | Step | Role | From | Responsibility / Task | Deliverable / Input | RACI | Checkpoint / Pre-requisite |
|----|----|----|----|----|----|----|----|
| Pre-Plan | 1 | IC | Implementation Partner | Conduct background research on client org, SOW, SPW, LOF, TDD | Research summary | R | Must complete research and share notes with EM |
| Pre-Plan | 2 | EM | Implementation Partner | Review IC’s pre-work | Reviewed notes | A | Must receive IC research before approval |
| Pre-Plan | 3 | Client | Client | Provide SOW, SPW, LOF, TDD, platform access | Documents & access | R/A | Must provide all documents and access before platform readiness |
| Pre-Plan | 4 | SC | Sprinklr | Provide guidance on pre-work | Expert input | C | Must confirm pre-work guidance is received before S2S meeting |
| Pre-Plan | 5 | IC + EM | Implementation Partner | Attend S2S kickoff/handover meeting | Agenda & meeting notes | R/A (IC executes, EM accountable), C (SC) | Must complete all pre-work steps (1–4) |
| Pre-Plan | 6 | IC | Implementation Partner | Validate platform readiness checklist | Platform readiness checklist | R | Must complete S2S meeting and verify platform access |
| Pre-Plan | 7 | Client | Client | Approve platform access and readiness | Access approvals | A | Must approve platform readiness before PDQ preparation |
| Pre-Plan | 8 | IC | Implementation Partner | Prepare PDQ (Pre-Discovery Questionnaire) | PDQ draft | R | Must complete platform readiness validation |
| Pre-Plan | 9 | Client | Client | Review & provide feedback on PDQ | Completed PDQ | A | Must review and approve PDQ before Discovery session |
| Plan | 10 | IC | Implementation Partner | Prepare and run Discovery sessions | Discovery session notes | R | Must complete PDQ approval |
| Plan | 11 | Client | Client | Participate in Discovery workshops | Workshop inputs | R | Must attend Discovery sessions |
| Plan | 12 | IC | Implementation Partner | Capture requirements: users, dashboards, topics, themes | BRW draft | R | Must complete Discovery sessions |
| Plan | 13 | EM | Implementation Partner | Review and approve BRW/Blueprint | Finalized BRW/Blueprint | A | Must review BRW draft from IC before client review |
| Plan | 14 | Client | Client | Approve BRW/Blueprint | Signed-off BRW | A | Must approve BRW before Build phase begins |
| Plan | 15 | SC | Sprinklr | Provide technical clarifications | Expert input | C | Must provide guidance as needed during BRW finalization |
| Plan | 16 | IC | Implementation Partner | Document use-cases, user profiles, dashboards | BRW sections | R | Must capture all requirements from client feedback |
| Plan | 17 | Client | Client | Validate and approve documented use-cases | Approved use-cases | A | Must approve use-cases before Build tasks start |
| Build | 18 | IC | Implementation Partner | Activate Dynamic Properties (DP) | DP configured | R | Must have approved BRW/Blueprint |
| Build | 19 | IC | Implementation Partner | Validate Quick Search functionality | Quick Search test results | R | Must complete DP activation |
| Build | 20 | IC | Implementation Partner | Raise Source Verification requests | Verification request logs | R | Must complete Quick Search validation |
| Build | 21 | SC | Sprinklr | Approve source verification if required | Approved sources | A/C | Must approve source verification before topic/library configuration |
| Build | 22 | IC | Implementation Partner | Configure Trending Topics, Topics & Topic Library | Topics configured | R | Must complete source verification approvals |
| Build | 23 | IC | Implementation Partner | Create Theme Library & optimize | Themes configured | R | Must complete topic configuration |
| Build | 24 | IC | Implementation Partner | Configure Listening & Engagement Dashboards | Dashboards ready | R | Must complete theme library creation |
| Build | 25 | IC | Implementation Partner | Validate Smart Insights placement | Smart Insights configured | R | Must complete dashboard configuration |
| Build | 26 | IC | Implementation Partner | Set up Audience Insights, Conversation Insights | Reports configured | R | Must validate Smart Insights |
| Build | 27 | IC | Implementation Partner | Set up Alerts, Scheduled Exports, Persona Apps | Alerts & exports configured | R | Must complete Audience/Conversation Insights setup |
| Build | 28 | IC | Implementation Partner | Configure Data Pipelines & FPDI | Data ingestion ready | R | Must complete Alerts setup |
| Build | 29 | EM | Implementation Partner | Review & approve build deliverables | Approval of build | A | Must approve all Build tasks (18–28) |
| Build | 30 | Client | Client | Validate platform setup & configuration | Sign-off on build | A | Must validate Build outputs |
| QA | 31 | IC | Implementation Partner | Create UAT tracker & perform self-review | UAT tracker | R | Must have Build phase completed |
| QA | 32 | IC | Implementation Partner | Peer review of configurations | Peer review notes | R | Must complete self-review |
| QA | 33 | EM | Implementation Partner | Oversee QA activities | QA sign-off | A | Must complete peer review |
| QA | 34 | Client | Client | Participate in UAT & provide feedback | UAT approval | R/A | Must participate in QA review |
| QA | 35 | SC | Sprinklr | Consult for product issues during QA | Expert input | C | Must provide guidance during QA if issues arise |
| Educate | 36 | IC | Implementation Partner | Prepare training plan & conduct sessions | Training materials & sessions | R | Must complete QA phase |
| Educate | 37 | EM | Implementation Partner | Oversee training & adoption | Training completion sign-off | A | Must approve training before Go-Live |
| Educate | 38 | Client | Client | Attend training sessions | Training attendance | R | Must participate in training |
| Go-Live | 39 | IC | Implementation Partner | Execute Go-Live plan | Go-Live checklist | R | Must complete Educate phase and training |
| Go-Live | 40 | EM | Implementation Partner | Approve Go-Live readiness | Go-Live approval | A | Must approve Go-Live readiness checklist |
| Go-Live | 41 | Client | Client | Confirm readiness & approve Go-Live | Go-Live sign-off | A | Must approve Go-Live readiness |
| Go-Live | 42 | SC | Sprinklr | Provide product support during Go-Live | Support input | C | Must be available during Go-Live |
| Empower | 43 | IC | Implementation Partner | Conduct Empower sessions & track adoption | Empower tracker & sessions | R | Must complete Go-Live successfully |
| Empower | 44 | EM | Implementation Partner | Review adoption & success | Approval of empowerment completion | A | Must verify IC’s empowerment tracking |
| Empower | 45 | Client | Client | Participate in sessions & adoption activities | Feedback & adoption metrics | R | Must attend Empower sessions |
| Empower | 46 | SC | Sprinklr | Provide guidance & product insights | Expert input | C | Must provide guidance during Empower sessions if needed |