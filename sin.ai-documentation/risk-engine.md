---
description: >-
  The control layer designed to constrain autonomous trading before an order
  reaches an exchange.
icon: shield-halved
---

# Risk Engine

The Risk Engine is intended to act as an independent control boundary between an agent's trading decision and execution.

The core principle is simple: **an agent may identify an opportunity without automatically being allowed to act on it.**

```mermaid
flowchart TD
    A[Proposed Trade] --> B{Permission Check}
    B -->|Fail| X[Reject]
    B -->|Pass| C{Exposure Check}
    C -->|Fail| X
    C -->|Pass| D{Position / Order Limits}
    D -->|Fail| X
    D -->|Pass| E{Market / Strategy Rules}
    E -->|Fail| X
    E -->|Pass| F[Approved for Execution]
```

## Control categories

| Control                  | Purpose                                                         |
| ------------------------ | --------------------------------------------------------------- |
| Account permissions      | Restrict what an agent is allowed to do on a connected account. |
| Position limits          | Cap the size of a single position or order.                     |
| Portfolio exposure       | Constrain aggregate risk across positions or assets.            |
| Asset / venue allowlists | Restrict trading to approved markets or exchanges.              |
| Strategy constraints     | Prevent actions outside the configured trading policy.          |
| Emergency controls       | Pause or disable trading when predefined conditions are met.    |

## Hard limits vs. agent judgment

Risk controls should not rely only on model judgment. Where possible, critical rules should be enforced as deterministic constraints outside the reasoning layer.

{% columns %}
{% column width="50%" %}
### Agent judgment

Useful for interpreting market context, weighing evidence, and proposing an action.
{% endcolumn %}

{% column width="50%" %}
### Hard controls

Useful for permissions, exposure ceilings, forbidden actions, account-level limits, and emergency shutdown behavior.
{% endcolumn %}
{% endcolumns %}

## Emergency stop

A mature deployment should provide a clear way to stop new trading activity. The exact implementation — for example user pause, account disconnect, policy lock, or automated circuit breaker — will be documented once finalized.

{% hint style="danger" %}
A risk engine reduces operational risk; it cannot eliminate trading losses, model errors, exchange failures, slippage, or extreme market events.
{% endhint %}

See what happens inside the agent before and after the risk check →
