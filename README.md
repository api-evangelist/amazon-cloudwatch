# Amazon CloudWatch (amazon-cloudwatch)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Amazon CloudWatch is an intelligent observability platform providing complete visibility into performance, availability, and security across your entire technology stack. Monitor applications, infrastructure, and workloads with unified metrics, logs, and traces plus AI-powered insights.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-cloudwatch/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, CloudWatch, Monitoring, Observability, Metrics, Logs

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon CloudWatch API
API for publishing metrics, creating alarms, managing dashboards, querying logs, and configuring observability for AWS resources and applications.

**Human URL:** [https://aws.amazon.com/cloudwatch/](https://aws.amazon.com/cloudwatch/)

#### Tags:

 - AWS, CloudWatch, Monitoring, Observability

#### Properties

- [Documentation](https://docs.aws.amazon.com/AmazonCloudWatch/latest/APIReference/)
- [OpenAPI](openapi/amazon-cloudwatch-openapi.yml)
- [APIReference](https://docs.aws.amazon.com/AmazonCloudWatch/latest/APIReference/)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/cloudwatch/)
- [SpectralRules](rules/amazon-cloudwatch-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-cloudwatch-vocabulary.yaml)
- [NaftikoCapability](capabilities/observability.yaml)

## Features

| Name | Description |
|------|-------------|
| Unified Observability | Monitor metrics, logs, and traces in one interface for complete system visibility. |
| AI-Powered Insights | Detect anomalies and investigate issues using AI-powered CloudWatch Investigations. |
| Dashboards | Create custom dashboards with pre-built and customizable metric visualizations. |
| Alarms | Set threshold-based alarms on any metric to trigger automated actions. |
| Log Insights | Analyze log data with SQL and natural language queries using CloudWatch Logs Insights. |
| OpenTelemetry Integration | Ingest OpenTelemetry data alongside native AWS metrics and traces. |

## Use Cases

| Name | Description |
|------|-------------|
| Infrastructure Monitoring | Monitor EC2, RDS, Lambda, and other AWS resources with built-in metrics. |
| Application Performance | Track application performance metrics and detect latency or error rate spikes. |
| Log Analysis | Aggregate and query application logs for troubleshooting and analytics. |
| Automated Remediation | Trigger auto-scaling, Lambda functions, or SNS alerts based on metric alarms. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon EC2 | Monitor EC2 instance performance metrics including CPU, network, and disk. |
| AWS Lambda | Monitor Lambda invocations, errors, and duration metrics automatically. |
| Amazon Prometheus | Ingest Prometheus metrics into CloudWatch for unified monitoring. |
| Grafana | Connect CloudWatch data sources to Grafana dashboards. |
| AWS X-Ray | Correlate traces from X-Ray with CloudWatch metrics and logs. |

## Artifacts

### OpenAPI

- [Amazon CloudWatch API](openapi/amazon-cloudwatch-openapi.yml)

### JSON Schema

- [GetMetricDataResponse](json-schema/cloudwatch-get-metric-data-response-schema.json)
- [GetMetricStatisticsResponse](json-schema/cloudwatch-get-metric-statistics-response-schema.json)
- [ListMetricsResponse](json-schema/cloudwatch-list-metrics-response-schema.json)
- [DescribeAlarmsResponse](json-schema/cloudwatch-describe-alarms-response-schema.json)
- [PutDashboardResponse](json-schema/cloudwatch-put-dashboard-response-schema.json)

### JSON-LD

- [Amazon CloudWatch Context](json-ld/amazon-cloudwatch-context.jsonld)

## Capabilities

### Shared Per-API Definitions

- [Amazon CloudWatch](capabilities/shared/cloudwatch.yaml) — 8 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Observability and Monitoring](capabilities/observability.yaml) | Amazon CloudWatch | 8 | Operations Engineer |

## Vocabulary

- [Amazon CloudWatch Vocabulary](vocabulary/amazon-cloudwatch-vocabulary.yaml) — Unified taxonomy covering operations, workflows, and personas

## Rules

- [Amazon CloudWatch Spectral Rules](rules/amazon-cloudwatch-spectral-rules.yml) — 19 rules enforcing Amazon CloudWatch API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
