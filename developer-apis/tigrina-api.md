---
description: "Query Hera 604 device parameters, cellular data, RSSI history, and network information."
icon: router
---

# Tigrina API

The Tigrina API enables access to Hera 604 router information, including device parameters, cellular connectivity information, RSSI history, and network information.

## Representative requests

- `POST /Japi/Diam/login`
- `GET /Japi/Diam/getCellularInformation`
- `GET /Japi/Diam/getCellularRSSIHistory`
- `GET /Japi/Diam/getNetworkInformation`

## Diagnostic workflow

```mermaid
flowchart TD
    Issue[Router issue reported] --> Login[Authenticate to Tigrina]
    Login --> Cellular[Get cellular information]
    Cellular --> RSSI[Review RSSI history]
    RSSI --> Network[Get network information]
    Network --> Decide{Likely root cause?}
    Decide --> Field[Field hardware check]
    Decide --> NetworkOps[Network or APN investigation]
    Decide --> App[Application or cloud investigation]
```

{% hint style="info" %}
Pair Tigrina diagnostics with the [troubleshooting device connectivity](https://app.gitbook.com/s/XSPACE_HARDWARE/troubleshoot-device-connectivity) flow so support can move from API evidence to field action.
{% endhint %}
