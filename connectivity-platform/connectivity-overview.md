---
description: "Design how data moves from devices into networks, cloud services, and business systems."
icon: network-wired
---

# Connectivity overview

When you design an IoT deployment, you need to decide how device data moves from the edge into your network, applications, and operational workflows.

## Design questions

{% columns %}
{% column %}
### Device and network

- Which radio technology does the device use?
- Which countries will devices operate in?
- What happens when the preferred network is unavailable?
- What data usage pattern is expected?
{% endcolumn %}

{% column %}
### Platform and operations

- Who monitors connection health?
- Which alerts should trigger support action?
- Which systems need usage or diagnostic data?
- Which API workflows should be automated?
{% endcolumn %}
{% endcolumns %}

## Suggested architecture

```mermaid
sequenceDiagram
    participant Device
    participant Network as Local or roaming network
    participant Infinity
    participant Cloud as Customer cloud
    Device->>Network: Connect and send data
    Network->>Infinity: Connectivity and usage events
    Infinity->>Cloud: Reports, alerts, and API data
    Cloud->>Infinity: Lifecycle and control actions
```
