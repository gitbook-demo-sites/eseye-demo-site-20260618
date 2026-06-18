---
description: "Pick the right Eseye API family for common integration tasks."
icon: arrows-split-up-and-left
---

# Choosing an API

<table>
<thead><tr><th>Need</th><th>Use</th><th>Example task</th></tr></thead>
<tbody>
<tr><td>SIM and portfolio operations</td><td>SIM API and Portfolio API</td><td>View, create, update, or manage SIM and portfolio records.</td></tr>
<tr><td>Send or receive SMS</td><td>SMS API</td><td>Send mobile terminated SMS, process mobile originated SMS, and handle delivery receipts.</td></tr>
<tr><td>Router diagnostics</td><td>Tigrina API</td><td>Query Hera 604 device parameters, cellular connectivity, RSSI history, and network information.</td></tr>
<tr><td>Operational reporting</td><td>Infinity exports or APIs</td><td>Automate recurring connectivity checks and support reports.</td></tr>
</tbody>
</table>

## Common integration flow

```mermaid
sequenceDiagram
    participant App as Customer app
    participant API as Eseye API
    participant Platform as Infinity or router data
    App->>API: Authenticate
    App->>API: Request SIM, SMS, or diagnostic data
    API->>Platform: Read or update operational state
    Platform-->>API: Result and status
    API-->>App: Response or error payload
```
