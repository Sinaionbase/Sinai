---
description: >-
  Security boundaries, contract transparency and verification standards across
  Qaa Si.
icon: shield-check
---

# Security & Transparency

Security documentation is treated as part of the product specification rather than as a marketing claim.

## Security model

| Area                      | Principle                                                                                                  |
| ------------------------- | ---------------------------------------------------------------------------------------------------------- |
| **Agent permissions**     | Agents should receive only the tools and access required for the current task.                             |
| **Consequential actions** | Wallet, credential and external side-effect operations should require explicit authorization boundaries.   |
| **Secrets**               | Sensitive credentials should not be exposed to unnecessary components or persisted without a defined need. |
| **Verification**          | Execution results should be checked before a workflow is reported as complete.                             |
| **On-chain controls**     | Administrative permissions and control mechanisms should be documented for deployed contracts.             |

## Token and contract transparency

Once deployed, the documentation should identify the official token contract, relevant administrative permissions, treasury addresses and any contracts responsible for vesting or liquidity management.

## Team token vesting

Team allocations are intended to use a defined vesting structure. Final allocation, cliff, unlock frequency and vesting duration will be published only when tokenomics are finalized.

## Liquidity

If liquidity is described as locked, the lock provider or mechanism, relevant position or transaction identifiers and lock duration should be published so users can independently verify the claim.

## Audits

An audit is described as **completed** only when a genuine third-party report exists. A published report should identify its scope, date and the contract version that was reviewed.

{% hint style="warning" %}
An audit reduces specific classes of risk; it does not guarantee that a smart contract, protocol or economic mechanism is risk-free.
{% endhint %}

## AI-agent security

AI-agent security includes permission boundaries, tool restrictions, transaction authorization, protection of sensitive credentials, prompt-injection resistance and explicit confirmation for consequential operations.
