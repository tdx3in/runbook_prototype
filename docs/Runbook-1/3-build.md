# 3. Build

## 3.1 Dynamic Properties (DP) Activation

### 3.1.1 DP Activation

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | 0.5                   |                              |

Catalog required Dynamic Properties for the engagement, verify whether
each DP exists in the tenant and raise activation requests for missing
ones with clear justification. Test DP behaviors in a sandbox
post-activation to confirm feature enablement and document DP IDs and
scope for change control. Keep a DP matrix that maps each DP to the
feature it enables and the rollback process if needed.

Note: identify which DPs are already part of standard deployments.

## 3.2 Quick Search

### 3.2.1 Quick Search access and compatibility check

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | 6                     | KB LINK;                     |

Confirm access to Quick Search and test key query constructs and
research dashboards for compatibility with the client’s use cases.
Validate limitations (e.g., FPDI, themes, advanced operators) and record
any restrictions that impact the proposed design. Save representative
queries as examples and assign an owner for ongoing refinement.

Note: Quick Search has limitations around FPDI, authenticated owned
data, themes and advanced operators.

### 3.2.2 Create a query and check if you are able to pull mentions

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB LINK                      |

Build and execute representative queries using the keyword lists and
operators agreed in discovery; measure mention volume, language
distribution and noise level. Iterate the queries to reduce false
positives and capture sample outputs for client review. Save validated
queries and link them to Research Query Dashboards for reuse.

Note: save queries and test across Research Query Dashboards.

### 3.2.3 Save queries and open on Research Query Dashboards

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB LINK                      |

Save validated queries and confirm they appear correctly in Research
Query Dashboards for reuse and reporting.

## 3.3 Source Verification

### 3.3.1 Raise Source Verification requests

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB LINK                      |

Submit Source Verification requests for all domains and sources captured
during discovery, including required proofs of ownership or access.
Track progress in a verification tracker, update the client on expected
SLAs and sequence ingestion plans based on verification outcomes. Once
verified, validate ingestion through sample pulls and reconcile counts
with expectations.

## 3.4 Trending Topics

### 3.4.1 Ensure Trending Topics is available

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB LINK                      |

Verify Trending Topics feature availability and regional coverage; test
sample regions and sample posts to validate expected output.

## 3.5 Sources

### 3.5.1 Validate source exhaustiveness and compatibility

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB LINK                      |

Confirm coverage across social, editorial, forums, reviews and podcasts
as required by client; document any gaps and proposed alternates.
Caution: incomplete source coverage will affect downstream insights.

## 3.6 Keyword Lists

### 3.6.1 Create Keyword Lists per use case

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB Link                      |

Create and maintain keyword lists per use case, tagged with owner and
priority, and test them iteratively against sample queries to reduce
noise. Document limits and provide guidance for splitting oversized
lists; include a short maintenance policy describing who updates lists
and how changes are validated. Deliver a consolidated keyword registry
as a project asset.

Note: track keyword and list limits and optimize lists for performance.

### 3.6.2 Note limitations of keywords and lists

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Document platform limits around keyword counts and list counts; adjust
designs accordingly to avoid truncation or failure.

## 3.7 Topic & Topic Library

### 3.7.1 Query-based Listening using Keyword Lists

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB LINK                      |

Design query-based topics using the vetted keyword lists and appropriate
filters; for each topic, document query logic, sample false positives
and remediation steps. Use topic templates for bulk updates (languages,
sources) and maintain a mapping from topics → dashboards → use cases for
traceability. Schedule a short optimization cycle after initial
collection to refine precision.

### 3.7.2 Account-based Listening

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Ensure client accounts are connected and validated for account-based
listening use cases.

### 3.7.3 Profile-based Listening

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Create profile lists for influencer and executive monitoring; validate
profile connectivity and data freshness.

### 3.7.4 Domain-based Listening

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Add source-verified domain lists to topics to enable domain-based
listening across verified sources.

### 3.7.5 Location-based Listening

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Configure location-based listening to capture mentions tied to
geographic or business locations when required by the use case.

### 3.7.6 Use Topic Template to create/update topics

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | Topic Templates              |

Leverage topic templates for bulk updates to topics (sources, languages)
to accelerate large-scale configurations.

### 3.7.7 Optimize Topic Library

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Refine and optimize topic library for quick curation and reduce noise in
topic outputs.

## 3.8 Theme & Theme Library

### 3.8.1 Create Theme Library

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB LINK                      |

Build a theme library to enable rapid theme creation and reuse across
topics and dashboards.

### 3.8.2 Use Theme Importer for bulk updates

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | Theme Importer               |

Use the Theme Importer to create or update multiple themes at once,
reducing manual effort.

## 3.9 Listening Dashboards

### 3.9.1 Note limitations of Smart Insights and exports

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB LINK                      |

Design dashboards with Smart Insights and export constraints in mind;
document widget-level Smart Insights behavior and file-size limits for
scheduled exports. Where Smart Insights is suboptimal for a widget,
provide an alternate analysis plan or manual checks. Validate scheduled
exports with sample runs and confirm sharing and access permissions.

### 3.9.2 Validate Actions on Dashboards

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Confirm all expected actions (share, export, drill-down) are available
on dashboards and accessible to right user groups.

### 3.9.3 Create widgets with required metrics

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Build required widgets (bar chart, table, etc.) using available metrics
and dimensions; validate display and drill-downs.

### 3.9.4 Share dashboards with correct users

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Ensure dashboards are shared to correct users/user‑groups and scheduled
exports configured as requested.

## 3.10 Engagement Dashboards

### 3.10.1 Create listening columns in engagement dashboards

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB Link                      |

Create listening alert columns in Engagement dashboards so alerts
populate action cards for analysts.

Note: define alert sources and owners.

### 3.10.2 Create listening alert columns

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB Link                      |

Add alert columns for listening-specific alerts and verify alert card
actions are functioning.

## 3.11 First Party Data Ingestion (FPDI)

### 3.11.1 Confirm FPDI data availability and formats

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB LINK                      |

Verify FPDI input templates meet expected schema and run a small test
ingest to validate mapping, mention counting and error handling. Map
FPDI fields to platform fields, confirm refresh cadence, and align
quotas with the client as every FPDI row counts as a mention. Include
PII handling guidance and define owner responsibilities for template
maintenance.

Note: every row in FPDI will count as a single mention—plan quotas
accordingly.

### 3.11.2 Ensure mapping with custom/standard fields

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Map FPDI fields to platform fields and validate data types and counts.

### 3.11.3 Importing data in FPDI

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Execute FPDI imports and validate ingestion logs for errors.

### 3.11.4 Create and Import Data Template

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | FPDI Template                |

Prepare FPDI templates and test with sample data before full ingestion.

### 3.11.5 Import and use Function Mapping

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Implement function mapping for FPDI as required by client’s data
transformations.

## 3.12 File Transfer Automation

### 3.12.1 Confirm file transfer protocol for automation

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB Link                      |

If automation requested, confirm protocol (FTP, SFTP, S3) and setup
external storage for exports.

Note: document security controls and rotation policy.

## 3.13 Smart Insights

### 3.13.1 Validate Smart Insights placement and signals

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB LINK                      |

Ensure Smart Insights appear at the correct widget level and accurately
detect anomalies; tune parameters if needed.

## 3.14 Smart Theme Explorer

### 3.14.1 Create Themes from clusters

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB LINK                      |

Use Smart Theme Explorer to generate themes from clusters and extract
cluster keywords for theme generation.

### 3.14.2 Compare cluster groups

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Compare two cluster groups to analyze differences and validate cluster
stability.

### 3.14.3 Note Smart Theme Explorer limitations

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Document limits on mention volume, supported languages and cluster
counts to set realistic expectations.

## 3.15 Audience Insights

### 3.15.1 Create Followers Network Report

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB LINK                      |

Run Followers Network report to derive audience insights and inform
segmentation and targeting.

### 3.15.2 Create Audience Study

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Design and execute custom audience studies per client requirements.

### 3.15.3 Create Profile Impersonation Report

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Generate profile impersonation reports where required for security or
monitoring use cases.

## 3.16 Conversation Insights

### 3.16.1 Get permissions and access report tools

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB LINK                      |

Obtain permissions to use Launchpad and Record Manager to create
Conversation Insights reports.

### 3.16.2 Create a Conversation Insights Report

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Build Conversation Insights report to surface thematic narratives and
trends from conversations.

## 3.17 Dashboard & Widget Exports

### 3.17.1 Export data from Dashboards & widgets

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB Link                      |

Configure and validate export formats (PDF, Excel, PNG, CSV) and
scheduled export behavior; test sample exports for layout.

### 3.17.2 External link sharing

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Enable and test external link sharing for dashboards and confirm access
controls.

## 3.18 Alerts & Distribution

### 3.18.1 Permissions for Alert Managers

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB LINK                      |

Assign Alert Manager permissions and document notification channels
(mobile, SMS, email).

Note: define owner responsibilities for alert triage.

### 3.18.2 Creating Alerts from Alert Manager

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Configure alerts in Alert Manager and validate sample triggers for
expected behavior.

### 3.18.3 Create Alerts from Widget Level

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Enable widget-level alerts and verify alert payloads and actions.

### 3.18.4 Create alerts from Rule Engine

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Design and test rules to auto-create alerts based on conditions and
thresholds.

### 3.18.5 Create an Automatic Alerts column

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Add alert columns that automatically populate with alert cards for
real-time monitoring.

## 3.19 Scheduled Exports

### 3.19.1 Set up automated exports

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB LINK                      |

Configure scheduled exports for Listening dashboards to meet stakeholder
cadence in selected formats.

### 3.19.2 Handling of PII data

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Discuss and implement PII masking only if SOW specifies or a DP is
enabled; ensure compliance with data protection requirements. Warning:
treat PII handling as a blocker until policy confirmed.

### 3.19.3 Raise support ticket for addressing limitations

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Raise support tickets for platform limitations identified during
testing; track response and fixes.

## 3.20 Persona Apps

### 3.20.1 Use Persona App best practices

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB LINK                      |

Recommend Persona Apps for single-module use cases; test cross-module
flows thoroughly before demos.

## 3.21 Data Pipelines

### 3.21.1 Set up API Integrations

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB LINK                      |

Configure data engine pipelines and API integrations to ingest external
sources; validate endpoints and auth.

Note: document transformation logic.

### 3.21.2 Import data through Data Pipelines

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Execute pipeline imports and validate data mapping and freshness.