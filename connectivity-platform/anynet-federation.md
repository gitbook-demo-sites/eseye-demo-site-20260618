---
description: "How Eseye's mobile network federation supports global IoT deployments."
icon: globe
---

# AnyNet Federation

The AnyNet Federation is Eseye's model for global IoT connectivity: a managed network ecosystem that gives devices access to many network options without customers having to negotiate and operate every carrier relationship themselves.

## When it matters

- Devices ship across multiple countries or regions.
- Permanent roaming creates regulatory or availability risk.
- A deployment needs multiple network choices in each market.
- The operations team wants one commercial and support relationship.

```mermaid
flowchart LR
    Device[IoT device] --> SIM[AnyNet+ SIM or eSIM]
    SIM --> Rules[Connectivity rules]
    Rules --> Local[Localized network access]
    Rules --> Roaming[Roaming partners]
    Local --> Infinity[Infinity platform]
    Roaming --> Infinity
```

## Deployment guidance

{% stepper %}
{% step %}
## Confirm target countries

List launch markets, expected device volumes, data usage, and regulatory constraints.
{% endstep %}

{% step %}
## Pick the connectivity model

Choose the SIM, eSIM, profile, and failover pattern that fits the device lifetime.
{% endstep %}

{% step %}
## Define operating rules

Document network preference, alert thresholds, localization requirements, and escalation paths.
{% endstep %}
{% endstepper %}

## Where to go next

- Review [AnyNet+ SIMs and profiles](anynet-sims-and-profiles.md).
- Set operational controls in [Infinity platform](infinity-platform.md).
- For device-side choices, see [Hera router overview](https://app.gitbook.com/s/kpggc3qX0IYi8Lu0z7Tm/product-families/hera-router-overview).
