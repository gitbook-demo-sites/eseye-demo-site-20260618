---
description: "Use the SIM API family for SIM and portfolio operations."
icon: sim-card
---

# SIM API

The source docs describe the SIM API family and related portfolio endpoints. In this demo, the SIM API is framed around operational automation rather than static endpoint lists.

## Common workflows

- Look up SIM status and metadata.
- List SIMs by portfolio, deployment, or customer account.
- Trigger or record lifecycle actions.
- Reconcile operational state with internal systems.

{% hint style="info" %}
If Eseye provides an OpenAPI spec for the SIM API, GitBook can auto-generate operation pages while keeping this overview as the human explanation layer.
{% endhint %}

## Operational pattern

```mermaid
flowchart LR
    CRM[Customer system] --> Job[Scheduled sync]
    Job --> SIM[SIM API]
    SIM --> State[SIM status and portfolio data]
    State --> Report[Support and operations report]
```
