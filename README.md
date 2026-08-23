# GitOps Compliance Pipeline with Falco

Continuous Runtime Compliance auditing and kernel-level event stream detection using Sysdig Falco.

## 🛡️ Core Compliance Features
1. **Runtime Protection:** Real-time monitoring of sensitive system file write calls (`/usr/bin`, `/host`).
2. **CIS Benchmarks Audit:** Continuous evaluation of running workloads against critical enterprise compliance metrics.
3. **Automated Alerts:** Implements declarative threat definitions targeting container-breakout vectors.

## 🪓 Project File Structure
- `falco-rules.yaml`: Declarative Falco threat rules capturing security events and severity triggers at the kernel layer.
-
