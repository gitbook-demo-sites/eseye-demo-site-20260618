---
description: "Send and receive SMS messages to and from SMS-capable devices."
icon: message
---

# SMS API

The SMS API enables mobile terminated and mobile originated SMS workflows for SMS-capable devices over internet and cellular networks.

## Supported patterns

<table data-view="cards">
  <thead><tr><th></th><th></th><th></th></tr></thead>
  <tbody>
    <tr><td><strong>Mobile terminated SMS</strong></td><td>Send an SMS message to a device.</td><td>Useful for commands, wake-up flows, and operational messaging.</td></tr>
    <tr><td><strong>Mobile originated SMS</strong></td><td>Receive messages sent from a device.</td><td>Useful for device events and simple telemetry flows.</td></tr>
    <tr><td><strong>Delivery receipts</strong></td><td>Receive delivery status for MT and MO messages.</td><td>Useful for auditability and retry handling.</td></tr>
  </tbody>
</table>

## Error handling

The source docs describe XML-formatted error codes and messages. A production GitBook version should include a normalized error table and example payloads.
