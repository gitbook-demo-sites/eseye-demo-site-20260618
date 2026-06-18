---
description: "Document credentials, environments, response formats, and support boundaries before production use."
icon: key
---

# Authentication and environments

A full migration should replace this starter page with Eseye's exact credential, endpoint, and environment details. For the demo, this page shows the shape GitBook should use.

## Before production

- Store credentials in a secrets manager.
- Keep test and production credentials separate.
- Log request IDs, timestamps, SIM identifiers, router identifiers, and response codes.
- Define who owns API credential rotation.

{% hint style="danger" %}
Never copy live API credentials into docs, tickets, GitHub issues, or AI prompts. Use placeholders and link to the secure credential process instead.
{% endhint %}

## Example placeholder

{% tabs %}
{% tab title="cURL" %}
```bash
curl --request GET "https://api.example.eseye.invalid/status"   --header "Authorization: Bearer $ESEYE_API_TOKEN"
```
{% endtab %}

{% tab title="Node.js" %}
```javascript
const response = await fetch('https://api.example.eseye.invalid/status', {
  headers: { Authorization: `Bearer ${process.env.ESEYE_API_TOKEN}` }
});
```
{% endtab %}
{% endtabs %}
