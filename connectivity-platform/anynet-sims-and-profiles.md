---
description: "Understand physical SIMs, embedded SIMs, iSIMs, eUICC, and multi-IMSI profile strategy."
icon: sim-card
---

# AnyNet+ SIMs and profiles

Eseye's AnyNet+ SIMs combine eUICC and multi-IMSI concepts so IoT devices can connect across markets and adapt over time. The source docs also point customers to physical SIM form factors, embedded SIMs, and iSIMs.

<table data-view="cards">
  <thead><tr><th></th><th></th><th></th></tr></thead>
  <tbody>
    <tr><td><strong>Physical SIM</strong></td><td>Best for prototypes, pilots, and hardware that expects removable SIMs.</td><td>Validate form factor and adapter fit early.</td></tr>
    <tr><td><strong>Embedded SIM</strong></td><td>Best for productized devices where tamper resistance and manufacturing simplicity matter.</td><td>Plan profile management before production.</td></tr>
    <tr><td><strong>iSIM</strong></td><td>Best for compact or integrated device designs where SIM functionality is built into the chipset.</td><td>Coordinate module and firmware readiness.</td></tr>
  </tbody>
</table>

{% hint style="warning" %}
SIM choice is not just a procurement detail. It affects certification, profile management, field replacement, and how the device behaves during network outages.
{% endhint %}

## Related tasks

- Review SIM part numbers and superseded variants before ordering.
- Confirm network access, roaming, and localization rules for each launch country.
- Use Infinity reporting to monitor activation, usage, and estate health.
