---
description: "Security patterns for private APN, VPN, IP controls, IMEI locking, and edge-to-cloud connectivity."
icon: shield-halved
---

# Security and private networking

Eseye's public product material highlights private APN, VPNs, pre-allocated IP addresses, IMEI locking, and firewall options for securing IoT connectivity from device to cloud.

## Common patterns

<table data-view="cards">
  <thead><tr><th></th><th></th><th></th></tr></thead>
  <tbody>
    <tr><td><strong>Private APN</strong></td><td>Keep device traffic away from the public internet where possible.</td><td>Best for managed device estates.</td></tr>
    <tr><td><strong>VPN connection</strong></td><td>Connect mobile network traffic into customer infrastructure.</td><td>Best for enterprise systems integration.</td></tr>
    <tr><td><strong>IMEI lock</strong></td><td>Bind connectivity to expected device hardware.</td><td>Best for reducing SIM misuse.</td></tr>
    <tr><td><strong>Firewall rules</strong></td><td>Limit traffic to known hosts, ports, and protocols.</td><td>Best for production hardening.</td></tr>
  </tbody>
</table>

## Review checklist

- Device identity and SIM identity are mapped.
- Traffic destinations are documented.
- Support teams can distinguish a network issue from a firewall or VPN issue.
- Logging and reporting are available before go-live.
