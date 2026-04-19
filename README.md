# Amazon EventBridge Scheduler (amazon-eventbridge-scheduler)
Amazon EventBridge Scheduler is a fully managed, serverless scheduler that enables you to create, run, and manage tasks from one central, managed service. With EventBridge Scheduler, you can create millions of schedules using cron and rate expressions.

**URL:** [https://aws.amazon.com/eventbridge/scheduler/](https://aws.amazon.com/eventbridge/scheduler/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Amazon Web Services, AWS, Cron, Event-Driven, Scheduling, Serverless

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon EventBridge Scheduler API
API for creating, updating, and managing scheduled tasks using cron expressions, rate expressions, and one-time schedules at scale.

**Human URL:** [https://aws.amazon.com/eventbridge/scheduler/](https://aws.amazon.com/eventbridge/scheduler/)

#### Tags:

 - Cron, Event-Driven, Scheduling, Serverless

#### Properties

- [Documentation](https://docs.aws.amazon.com/scheduler/latest/UserGuide/)
- [OpenAPI](openapi/amazon-eventbridge-scheduler-openapi.yml)
- [APIReference](https://docs.aws.amazon.com/scheduler/latest/APIReference/)
- [GettingStarted](https://aws.amazon.com/eventbridge/scheduler/)
- [Pricing](https://aws.amazon.com/eventbridge/pricing/)
- [FAQ](https://aws.amazon.com/eventbridge/faqs/)
- [JSONSchema](json-schema/amazon-eventbridge-scheduler-action-after-completion-schema.json)
- [JSONSchema](json-schema/amazon-eventbridge-scheduler-assign-public-ip-schema.json)
- [JSONSchema](json-schema/amazon-eventbridge-scheduler-aws-vpc-configuration-schema.json)
- [JSONLD](json-ld/amazon-eventbridge-scheduler-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [DeveloperPortal](https://aws.amazon.com/eventbridge/)
- [Documentation](https://docs.aws.amazon.com/eventbridge/)
- [Blog](https://aws.amazon.com/blogs/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/scheduler/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Support](https://aws.amazon.com/support/)
- [FAQ](https://aws.amazon.com/eventbridge/faqs/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Compliance](https://aws.amazon.com/compliance/)
- [Security](https://aws.amazon.com/security/)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/eventbridge)
- [KnowledgeCenter](https://repost.aws/knowledge-center)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| Cron and Rate Scheduling | Schedule tasks using flexible cron expressions or simple rate expressions |
| One-Time Schedules | Create one-time schedules for future tasks with precise timing |
| Schedule Groups | Organize schedules into groups for bulk management and operations |
| Flexible Time Windows | Allow schedules to run within flexible time windows for load distribution |
| Timezone Support | Specify schedules in any timezone for global deployments |

## Use Cases

| Name | Description |
|------|-------------|
| Batch Job Scheduling | Schedule periodic data processing and ETL batch jobs |
| Report Generation | Automatically generate and deliver reports on a schedule |
| Resource Cleanup | Schedule automatic cleanup of temporary resources and old data |
| Reminder Notifications | Send scheduled notifications and reminders to users |

## Integrations

| Name | Description |
|------|-------------|
| AWS Lambda | Invoke Lambda functions on a schedule |
| Amazon SQS | Send messages to SQS queues at scheduled intervals |
| AWS Step Functions | Start Step Functions state machine executions on a schedule |
| Amazon ECS | Run ECS tasks on a scheduled basis |
| Amazon EventBridge | Send events to EventBridge event buses on a schedule |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-eventbridge-scheduler](openapi/amazon-eventbridge-scheduler-openapi.yml)

### JSON Schema

- [amazon-eventbridge-scheduler-action-after-completion](json-schema/amazon-eventbridge-scheduler-action-after-completion-schema.json)
- [amazon-eventbridge-scheduler-assign-public-ip](json-schema/amazon-eventbridge-scheduler-assign-public-ip-schema.json)
- [amazon-eventbridge-scheduler-aws-vpc-configuration](json-schema/amazon-eventbridge-scheduler-aws-vpc-configuration-schema.json)
- [amazon-eventbridge-scheduler-capacity-provider](json-schema/amazon-eventbridge-scheduler-capacity-provider-schema.json)
- [amazon-eventbridge-scheduler-capacity-provider-strategy-item-base](json-schema/amazon-eventbridge-scheduler-capacity-provider-strategy-item-base-schema.json)
- [amazon-eventbridge-scheduler-capacity-provider-strategy-item](json-schema/amazon-eventbridge-scheduler-capacity-provider-strategy-item-schema.json)
- [amazon-eventbridge-scheduler-capacity-provider-strategy-item-weight](json-schema/amazon-eventbridge-scheduler-capacity-provider-strategy-item-weight-schema.json)
- [amazon-eventbridge-scheduler-capacity-provider-strategy](json-schema/amazon-eventbridge-scheduler-capacity-provider-strategy-schema.json)
- [amazon-eventbridge-scheduler-client-token](json-schema/amazon-eventbridge-scheduler-client-token-schema.json)
- [amazon-eventbridge-scheduler-conflict-exception](json-schema/amazon-eventbridge-scheduler-conflict-exception-schema.json)
- *...and 107 more*

### JSON Structure

- [amazon-eventbridge-scheduler-action-after-completion](json-structure/amazon-eventbridge-scheduler-action-after-completion-structure.json)
- [amazon-eventbridge-scheduler-assign-public-ip](json-structure/amazon-eventbridge-scheduler-assign-public-ip-structure.json)
- [amazon-eventbridge-scheduler-aws-vpc-configuration](json-structure/amazon-eventbridge-scheduler-aws-vpc-configuration-structure.json)
- [amazon-eventbridge-scheduler-capacity-provider-strategy-item-base](json-structure/amazon-eventbridge-scheduler-capacity-provider-strategy-item-base-structure.json)
- [amazon-eventbridge-scheduler-capacity-provider-strategy-item](json-structure/amazon-eventbridge-scheduler-capacity-provider-strategy-item-structure.json)
- [amazon-eventbridge-scheduler-capacity-provider-strategy-item-weight](json-structure/amazon-eventbridge-scheduler-capacity-provider-strategy-item-weight-structure.json)
- [amazon-eventbridge-scheduler-capacity-provider-strategy](json-structure/amazon-eventbridge-scheduler-capacity-provider-strategy-structure.json)
- [amazon-eventbridge-scheduler-capacity-provider](json-structure/amazon-eventbridge-scheduler-capacity-provider-structure.json)
- [amazon-eventbridge-scheduler-client-token](json-structure/amazon-eventbridge-scheduler-client-token-structure.json)
- [amazon-eventbridge-scheduler-conflict-exception](json-structure/amazon-eventbridge-scheduler-conflict-exception-structure.json)
- *...and 107 more*

### JSON-LD

- [amazon-eventbridge-scheduler](json-ld/amazon-eventbridge-scheduler-context.jsonld)

### Examples

- [amazon-eventbridge-scheduler-action-after-completion](examples/amazon-eventbridge-scheduler-action-after-completion-example.json)
- [amazon-eventbridge-scheduler-assign-public-ip](examples/amazon-eventbridge-scheduler-assign-public-ip-example.json)
- [amazon-eventbridge-scheduler-aws-vpc-configuration](examples/amazon-eventbridge-scheduler-aws-vpc-configuration-example.json)
- [amazon-eventbridge-scheduler-capacity-provider](examples/amazon-eventbridge-scheduler-capacity-provider-example.json)
- [amazon-eventbridge-scheduler-capacity-provider-strategy](examples/amazon-eventbridge-scheduler-capacity-provider-strategy-example.json)
- [amazon-eventbridge-scheduler-capacity-provider-strategy-item-base](examples/amazon-eventbridge-scheduler-capacity-provider-strategy-item-base-example.json)
- [amazon-eventbridge-scheduler-capacity-provider-strategy-item](examples/amazon-eventbridge-scheduler-capacity-provider-strategy-item-example.json)
- [amazon-eventbridge-scheduler-capacity-provider-strategy-item-weight](examples/amazon-eventbridge-scheduler-capacity-provider-strategy-item-weight-example.json)
- [amazon-eventbridge-scheduler-client-token](examples/amazon-eventbridge-scheduler-client-token-example.json)
- [amazon-eventbridge-scheduler-conflict-exception](examples/amazon-eventbridge-scheduler-conflict-exception-example.json)
- *...and 107 more*

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [EventBridge Scheduler](capabilities/shared/api.yaml) — 12 operations

### Workflow Capabilities

| Workflow | Tools | Persona |
|----------|-------|---------|
| [Amazon EventBridge Scheduler Management](capabilities/amazon-eventbridge-scheduler-capability.yaml) | 12 | Cloud Architect |

## Vocabulary

- [Amazon EventBridge Scheduler Vocabulary](vocabulary/amazon-eventbridge-scheduler-vocabulary.yaml) — Unified taxonomy mapping 0 resources, 7 actions, 1 workflows, and 2 personas

## Rules

- [amazon-eventbridge-scheduler-spectral-rules.yml](rules/amazon-eventbridge-scheduler-spectral-rules.yml) — 0 rules enforcing Amazon EventBridge Scheduler API conventions

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
