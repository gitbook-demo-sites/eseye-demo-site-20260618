---
description: "A practical first-line troubleshooting path for device and router connectivity issues."
icon: stethoscope
---

# Troubleshoot device connectivity

Start with physical checks, then platform status, then network diagnostics. This keeps field teams from jumping straight into advanced network investigation when the cause may be local.

```mermaid
flowchart TD
    A[Device offline] --> B{SIM seated and active?}
    B -- No --> C[Fix SIM seating or activation]
    B -- Yes --> D{Signal and registration visible?}
    D -- No --> E[Check antennas, location, and network availability]
    D -- Yes --> F{Data path working?}
    F -- No --> G[Check APN, VPN, firewall, and cloud endpoint]
    F -- Yes --> H[Investigate application layer]
```

## Quick checks

- SIM is seated and activated.
- Antennas are attached and undamaged.
- Router status shows cellular registration.
- Infinity shows expected SIM status and recent activity.
- VPN, private APN, firewall, and cloud endpoints are reachable.

## Escalate with evidence

Capture router model, firmware version, SIM identifier, location, signal data, network state, recent changes, and timestamps before escalating.
