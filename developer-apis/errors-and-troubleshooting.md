---
description: "Normalize API error handling and escalation evidence across API families."
icon: triangle-exclamation
---

# Errors and troubleshooting

A good API docs migration should centralize common error behavior so each API family does not repeat the same support guidance.

## Minimum evidence for support

- API family and endpoint.
- Timestamp and timezone.
- Request identifier if available.
- SIM, portfolio, router, or MSISDN identifier.
- Response status and returned error code.
- Whether the issue reproduces in an API client.

<details>
<summary>Example support note template</summary>

```text
API family:
Endpoint:
Environment:
Timestamp:
Identifier:
Expected result:
Actual result:
Returned error:
Recent changes:
```
</details>

{% hint style="success" %}
This page is a good candidate for reusable content across SIM, SMS, and Tigrina API sections.
{% endhint %}
