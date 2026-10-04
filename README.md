# GitOps Compliance Pipeline with Falco

A hands-on runtime-security lab using Sysdig Falco to detect suspicious container and filesystem activity.

## What this project demonstrates

- **Runtime detection:** Falco rules for unauthorized writes below protected binary paths.
- **Container security:** A rule targeting write activity under `/host`, representing a container-breakout detection scenario.
- **Declarative security:** Detection logic is stored as version-controlled YAML and can be incorporated into a GitOps workflow.
- **Severity and tagging:** Rules classify critical events and attach security/compliance tags.

## Files

| File | Purpose |
|---|---|
| `falco-rules.yaml` | Custom Falco detection rules |

## Detection flow

`Container / Host Event → Falco Rule → CRITICAL Alert → Investigation / Response`

> **Scope:** These rules demonstrate detection logic. They do not by themselves provide complete CIS compliance, automatic remediation, or guaranteed container-breakout prevention.

## Skills demonstrated

Falco · Kubernetes security concepts · Runtime Security · Linux events · Container Security · GitOps · DevSecOps
