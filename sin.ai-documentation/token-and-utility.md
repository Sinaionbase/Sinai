---
description: >-
  Token allocation, liquidity structure and planned vesting framework for the
  Qaa Si ecosystem.
icon: coins
---

# Token & Utility

The Qaa Si token is intended to support the broader agent ecosystem. Token utility will be documented alongside implemented product functionality so that ecosystem claims remain tied to concrete technical use cases.

{% hint style="info" %}
**Current tokenomics framework:** Total supply is **1,000,000,000 tokens**. Allocation percentages below reconcile to 100%. Vesting, wallet and liquidity-lock details are shown at the level currently defined; exact dates, addresses and execution parameters will be added once finalized.
{% endhint %}

## Token allocation

| Allocation                   |    Share |            Tokens |
| ---------------------------- | -------: | ----------------: |
| **Liquidity Pool**           |  **50%** |   **500,000,000** |
| **Future Liquidity Reserve** |  **10%** |   **100,000,000** |
| **Staking Rewards**          |   **5%** |    **50,000,000** |
| **Community / Airdrops**     |   **7%** |    **70,000,000** |
| **Team**                     |   **3%** |    **30,000,000** |
| **Ecosystem / Development**  |  **10%** |   **100,000,000** |
| **Marketing / Growth**       |   **5%** |    **50,000,000** |
| **Treasury**                 |  **10%** |   **100,000,000** |
| **Total**                    | **100%** | **1,000,000,000** |

This structure keeps half of the total supply dedicated to the primary liquidity pool while separating future liquidity, staking incentives and treasury reserves into clearly identifiable allocations.

## Liquidity structure

| Item                         | Share of total supply |          Tokens | Planned treatment                                                                                                                                                                |
| ---------------------------- | --------------------: | --------------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Liquidity Pool**           |               **50%** | **500,000,000** | Allocated to DEX liquidity and intended to be secured through a publicly verifiable liquidity-lock structure once the pool is created.                                           |
| **Future Liquidity Reserve** |               **10%** | **100,000,000** | Reserved exclusively for future liquidity needs. Any deployment should be documented before execution, including wallet source, amount, paired asset and transaction references. |

Liquidity deployment requires both sides of the trading pair. Final pool composition, paired ETH, initial price, pool address, LP position and lock evidence will therefore only be treated as final when the actual deployment is completed and publicly verifiable.

{% hint style="info" %}
Liquidity allocations can support market depth, but they **do not guarantee price stability, trading depth, or protection from volatility**. Any future-liquidity deployment should be transparent and independently verifiable on-chain.
{% endhint %}

## Staking rewards

The **5% staking rewards allocation** is reserved for potential ecosystem staking incentives. Reward mechanics, eligibility, duration, emission rate and smart-contract implementation should only be presented as active once they are finalized, deployed and verifiable.

{% hint style="warning" %}
The staking allocation does not represent a promise of yield or return. Any future staking program will require separately published terms, smart-contract details and risk disclosures.
{% endhint %}

## Locking, vesting & custody

| Allocation                         | Planned control framework                                                                                                                                                       |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Liquidity Pool — 50%**           | The resulting LP position is planned to be locked using **UNCX** or another publicly verifiable liquidity-lock mechanism. Pool and lock details will be published once created. |
| **Future Liquidity Reserve — 10%** | Should remain segregated from operational wallets and preferably held under multisig custody until used for documented liquidity purposes.                                      |
| **Staking Rewards — 5%**           | Should remain in a dedicated allocation wallet or smart contract and only be distributed according to published staking rules once implemented.                                 |
| **Team — 3%**                      | The full team allocation is planned to be locked through **PinkLock** with a **6-month cliff**, followed by **12 months of vesting**.                                           |
| **Community / Airdrops — 7%**      | Distribution should follow published campaign rules and schedules, with undistributed balances remaining publicly traceable on-chain.                                           |
| **Ecosystem / Development — 10%**  | Planned **12-month cliff**, followed by **12 months of vesting**. A multisig wallet is recommended for operational custody before or between scheduled releases.                |
| **Marketing / Growth — 5%**        | Planned **6-month cliff**, followed by **12 months of vesting**. A multisig wallet is recommended for operational custody.                                                      |
| **Treasury — 10%**                 | Treasury custody should use a multisig wallet with publicly documented control policies. A vesting or release schedule can be added once finalized.                             |

## Wallet & lock verification

The relevant wallet addresses, liquidity-pool address, multisig addresses, staking contracts, direct lock records and BaseScan verification links will be added once they exist.

| Allocation                   | Wallet / pool address                  | Lock / custody verification                                                                                          | BaseScan verification                          |
| ---------------------------- | -------------------------------------- | -------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| **Liquidity Pool**           | `TBD — add liquidity pool address`     | [https://app.uncx.network/](https://app.uncx.network/) — direct LP lock link: `TBD`                                  | `TBD — add BaseScan pool / transaction link`   |
| **Future Liquidity Reserve** | `TBD — add multisig reserve address`   | `TBD — publish multisig / reserve verification`                                                                      | `TBD — add BaseScan wallet / transaction link` |
| **Staking Rewards**          | `TBD — add staking allocation address` | `TBD — publish staking contract / custody verification`                                                              | `TBD — add BaseScan wallet / transaction link` |
| **Team**                     | `TBD — add wallet address`             | [https://www.pinksale.finance/pinklock/](https://www.pinksale.finance/pinklock/) — direct vesting / lock link: `TBD` | `TBD — add BaseScan wallet / transaction link` |
| **Community / Airdrops**     | `TBD — add wallet address`             | `TBD — publish distribution / custody evidence`                                                                      | `TBD — add BaseScan wallet / transaction link` |
| **Ecosystem / Development**  | `TBD — add multisig / vesting address` | `TBD — publish multisig and vesting verification`                                                                    | `TBD — add BaseScan wallet / transaction link` |
| **Marketing / Growth**       | `TBD — add multisig / vesting address` | `TBD — publish multisig and vesting verification`                                                                    | `TBD — add BaseScan wallet / transaction link` |
| **Treasury**                 | `TBD — add multisig address`           | `TBD — publish multisig verification`                                                                                | `TBD — add BaseScan wallet / transaction link` |

{% hint style="info" %}
**UNCX:** [https://app.uncx.network/](https://app.uncx.network/)\
**PinkLock:** [https://www.pinksale.finance/pinklock/](https://www.pinksale.finance/pinklock/)\
**BaseScan:** [https://basescan.org/](https://basescan.org/)\
Once each position is created, the corresponding address and direct verification link should be published here.
{% endhint %}

{% hint style="warning" %}
The framework above reflects the current plan. Exact lock durations, unlock dates, staking parameters, wallet addresses, pool parameters and direct verification links should only be treated as final once the relevant contracts, wallets, pool and locks have been created and independently verified.
{% endhint %}

## Utility framework

Potential utility areas may include ecosystem access, agent-related services, staking incentives, governance or other platform mechanisms where there is a defined technical role. Each utility claim should ultimately map to an implemented product function or smart-contract mechanism.

## Security audit & certification

A **CertiK smart-contract audit and security review is planned after the token contract has been created and finalized**. The audit status, verified report link, scope and any relevant certification details will be published here once the review has been completed.

| Security verification            | Status                                      |
| -------------------------------- | ------------------------------------------- |
| **CertiK audit / certification** | **Planned — after token contract creation** |

{% hint style="info" %}
The project will only describe a CertiK audit as completed or certified after an official, independently verifiable report is available.
{% endhint %}

## Transparency standard

Before launch, the documentation should publish the official token contract, relevant allocation wallets, liquidity-pool details, future-liquidity reserve address, staking details where applicable, UNCX lock evidence, PinkLock verification links, multisig addresses, BaseScan verification links, any vesting contracts or schedules, and the official security-audit report where applicable so these items can be independently verified.

{% hint style="warning" %}
Nothing on this page should be interpreted as a promise of price appreciation, yield or investment return. Utility documentation describes intended ecosystem function, not market performance.
{% endhint %}
