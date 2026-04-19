# Amazon CloudWatch (amazon-cloudwatch)
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
