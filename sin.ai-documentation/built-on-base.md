---
description: >-
  Planned Base blockchain foundation and how official deployments will be
  verified.
icon: hexagon-nodes
---

# Built on Base

Qaa Si is planned to use **Base** as its blockchain foundation for future on-chain ecosystem components.

Blockchain infrastructure can provide transparent transaction settlement, token ownership and auditable smart-contract state. The documentation will distinguish between project plans and contracts that are actually deployed and verified.

## Deployment information

When available, this page will publish the authoritative technical references for:

| Item            | Publication standard                                        |
| --------------- | ----------------------------------------------------------- |
| Network / chain | Exact network identification and deployment environment     |
| Token contract  | Official address and verified explorer reference            |
| Smart contracts | Contract purpose, version and administrative permissions    |
| Treasury        | Official addresses and documented control model             |
| Vesting         | Contract addresses, allocation rules and unlock mechanics   |
| Liquidity       | Relevant pool / position information and any lock mechanism |

## Verification model

{% stepper %}
{% step %}
### Official publication

A deployment detail is published through verified Qaa Si documentation or another official channel.
{% endstep %}

{% step %}
### On-chain verification

Users can independently inspect the corresponding contract or transaction on Base infrastructure.
{% endstep %}

{% step %}
### Documentation match

The address, version and described permissions must match the deployed implementation.
{% endstep %}
{% endstepper %}

{% hint style="danger" %}
No token contract, treasury address or liquidity claim should be considered official solely because it uses the Qaa Si name. Verify against the official documentation before interacting with any on-chain component.
{% endhint %}
