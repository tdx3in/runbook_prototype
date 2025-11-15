# 2. Plan

## 2.1 BRW Readiness

### 2.1.1 Pre-fill BRW

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | 0.5                   |                              |

Populate BRW with pre-collected artifacts (users, emails, PDQ inputs,
sample topics and dashboard names) so discovery can focus on
confirmations and decisions. Validate field formats, custom field names
and hierarchy expectations against PDQ and S2D to avoid downstream
mapping issues. Attach sample records and assign owners for any missing
items before build.

Note: ensure fields align with discovery outputs.

## 2.2 Discovery Meeting

### 2.2.1 Discovery Meeting - Listening Insights

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | 1                     |                              |

Conduct a structured discovery to confirm use cases, topic scope, data
sources, reporting needs, and user personas; record decisions and open
actions in meeting minutes. Use the BRW and PDQ as the working document
to capture final choices and dependencies such as required SVs or FPDI
schedules. End the meeting with a clear list of next steps, owners and
timelines.

Note: brief themes/topics discussion is often sufficient—capture
follow-ups for detailed configuration.

## 2.3 BRW Discussions

### 2.3.1 Users

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | 3                     |                              |

Collect the list of users and personas including emails, roles and
required permissions; map these to dashboard access and topic
responsibilities. Identify any cross-team access needs (e.g., shared
reporting with Care or Marketing) and record provisioning steps. Save a
CSV or BRW export to drive provisioning during build.

Note: there are no fixed Location‑Insights personas—define roles per
client.

### 2.3.2 Use-cases

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Identify and document client use cases in BRW to drive topic and
dashboard design.

Note: map each use case to expected dashboards and alerting rules.

### 2.3.3 Topics

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Create topics for each topic group and update settings as per discovery;
keep topic creation efficient for later optimization.

Note: topics/themes discussion can be brief in discovery—capture details
for follow-up.

### 2.3.4 Themes

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Collect theme names, tags and query patterns for theme library creation.

Note: themes will help with repeated analysis—capture sample tags.

### 2.3.5 Keyword Lists

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Create keyword lists per use case and tag them for reusability in
query-based topics. Caution: observe limits on number of keywords and
lists.

### 2.3.6 Domains (News)

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Capture news domains, blogs, forums and other editorial sources; mark
each source for Source Verification and include sample URLs and
ownership proof where needed. Raise SV requests early and communicate
the expected verification timeline to the client; prepare fallback
ingestion plans for critical sources that may remain unverified.
Validate domain extracts with sample pulls once verification completes.

### 2.3.7 Profiles - For Influencer Monitoring

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Collect influencer profiles if influencer monitoring is required and
create profile lists for monitoring.

Note: capture verification and access steps for each profile.

### 2.3.8 Audience Studies

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Obtain audience study criteria and required segments to support Audience
Insights and segmentation reporting.

### 2.3.9 Dashboards

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | KB LINK                      |

Gather dashboard names, metrics, sharing and scheduled exports
requirements; collect any client reports to replicate.

Note: clarify KPIs, scheduling needs and whether custom dashboards are
required.

### 2.3.10 BRW Check-ins

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   | — (Asset not required)       |

Run iterative BRW check‑ins with the client to finalize fields and
mappings; document changes after each session.

### 2.3.11 BRW - Final Review & Approval

| Owner | Time Duration (hours) | Assets (attach if available) |
|-------|-----------------------|------------------------------|
| IC    | TBD                   |                              |

Obtain formal BRW sign‑off from client and internal stakeholders before
build starts. Warning: do not proceed to bulk imports or DP activations
without sign‑off.