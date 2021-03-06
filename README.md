---
label: Welcome to Baselime
icon: home
---
# Welcome to Baselime

[Baselime](https://baselime.io) is an Observability as Code platform based on OpenTelemetry that makes it easy for your team to resolve incidents and performance bottlenecks in your serverless applications.

Baselime currently supports serverless services on [AWS](https://aws.amazon.com/).

![](./assets/images/cli.svg)

---

## Events, Logs, Metrics and Traces

Your serverless runtime and infrastructure emit telemetry data in various formats. That's usually the missing context when debugging defects and incidents. Baselime doesn't re-invent the wheel. Data is gathered in your serverless application from:
- Direct integration with AWS services through CloudFormation
- OpenTelemetry to capture runtime traces
- Logs and Metrics from CloudWatch

---

## Baselime Data Storage

Baselime [securely stores](./security/overview.md) your telemetry data per namespace. A namespace is typically a Lambda function. Namespaces help partition your data and facilitate querying your data.

---

## Observability as Code

Typically, monitoring and observability solutions let you define your configurations in web-based user interfaces.

On Baselime, you define your observability configurations in human-readable declarative configuration files. This allows you to create a blueprint that you can version, share and re-use. On Baselime, observability is a first-class citizen of your software development process.

The primary user interface with Baselime is the [Baselime CLI](./cli/install.md).

---

## Queries, Alerts and Dashboard

Query your data, using any of the Baselime clients, to get a deeper understanding of your production systems. Create and share alerts and dashboard based on the results of your queries.

---

## Collaboration

Baselime is built for **teams**. Collaborate with your team on the findings and learnings from your queries and dashboards.

---

## Made for Developers

Monitoring and observability platforms are usually built with operations professionals as primary users; Baselime puts the developer at the center of the observability efforts of your teams.

---

```js # :icon-code: quick-start.js
if(baselime.use === "first-time") {
  return quickStart();
}
```
