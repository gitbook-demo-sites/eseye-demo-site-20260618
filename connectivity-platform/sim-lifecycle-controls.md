---
description: "A practical operating model for provisioning, activating, monitoring, and retiring SIMs."
icon: rotate
---

# SIM lifecycle controls

A global IoT estate needs a consistent lifecycle model. SIM status, billing state, device assignment, profile status, and country availability all need clear ownership.

## Lifecycle stages

```mermaid
stateDiagram-v2
    [*] --> Ordered
    Ordered --> Provisioned
    Provisioned --> Activated
    Activated --> Suspended
    Suspended --> Activated
    Activated --> Retired
    Retired --> [*]
```

## Controls to document

- Who can activate a SIM?
- What evidence is required before suspending or retiring?
- Which status changes should alert support or customer success?
- Which reports feed finance, support, and customer-facing reviews?

{% hint style="success" %}
This is a strong candidate for authenticated customer-only docs in a second pass because lifecycle rules often vary by contract, device estate, and support model.
{% endhint %}
