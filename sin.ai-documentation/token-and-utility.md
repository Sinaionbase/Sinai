---
description: >-
  Token allocation, liquidity structure and planned vesting framework for the
  QAA SI ecosystem.
icon: coins
---

# Token & Utility

The QAA SI token is intended to support the broader agent ecosystem. Token utility will be documented alongside implemented product functionality so that ecosystem claims remain tied to concrete technical use cases.

{% hint style="info" %}
**Current tokenomics framework:** Total supply is **1,000,000,000 tokens**. Allocation percentages below reconcile to 100%. Vesting and liquidity deployment details are shown at the level currently defined; exact dates, wallet addresses and execution parameters can be added once finalized.
{% endhint %}

## Token allocation

| Allocation                       |    Share |            Tokens |
| -------------------------------- | -------: | ----------------: |
| **Liquidity Allocation — Total** |  **50%** |   **500,000,000** |
| **Community / Airdrops**         |  **10%** |   **100,000,000** |
| **Team**                         |   **3%** |    **30,000,000** |
| **Ecosystem / Development**      |  **17%** |   **170,000,000** |
| **Marketing / Growth**           |  **10%** |   **100,000,000** |
| **Treasury**                     |  **10%** |   **100,000,000** |
| **Total**                        | **100%** | **1,000,000,000** |

## Liquidity structure

The **50% liquidity allocation** is planned to be deployed in stages rather than entering the pool all at once.

| Liquidity component                | Share of total supply |          Tokens | Planned treatment                                                                                    |
| ---------------------------------- | --------------------: | --------------: | ---------------------------------------------------------------------------------------------------- |
| **Initial DEX Liquidity — Launch** |               **10%** | **100,000,000** | Added at launch and subject to the planned liquidity-lock framework.                                 |
| **Future Liquidity Reserve A–D**   |               **40%** | **400,000,000** | Split across four future liquidity tranches. Planned for deployment only after a **12-month cliff**. |
| **Liquidity Allocation — Total**   |               **50%** | **500,000,000** | Initial launch liquidity plus future tranches A–D.                                                   |

Future liquidity tranches are planned to be paired with **ETH** when added to the liquidity pool. The intention is to provide both assets at the then-current pool ratio so that the liquidity addition itself does not intentionally reset the pool price.

{% hint style="info" %}
Adding liquidity proportionally can reduce direct price distortion from the liquidity-addition transaction itself, but it **cannot guarantee an unchanged market price**. Market activity, pool conditions, fees, slippage and execution conditions may still affect price.
{% endhint %}

## Locking & vesting

| Allocation                        | Locking / vesting framework                                                                                                                                                                                                                                                 |
| --------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Initial DEX Liquidity**         | Initial launch liquidity is planned to be locked using **UNCX**. The final lock evidence and exact lock terms will be published once the pool is created.                                                                                                                   |
| **Future Liquidity A–D**          | **12-month cliff** before planned deployment. The four tranche sizes, timing and corresponding ETH contributions will be documented before execution.                                                                                                                       |
| **Team — 3%**                     | The full **3% team allocation** is planned to be locked through **PinkLock** with a **6-month cliff**, followed by **12 months of vesting**.                                                                                                                                |
| **Community / Airdrops — 10%**    | The full **10% community / airdrops allocation** is planned to be locked through **PinkLock** with a **12-month cliff**, followed by **6 months of vesting**.                                                                                                               |
| **Ecosystem / Development — 17%** | The full **17% ecosystem / development allocation** is planned to be locked through **PinkLock** with a **12-month cliff**, followed by **6 months of vesting**.                                                                                                            |
| **Marketing / Growth — 10%**      | **5% of total supply** from the marketing / growth allocation is planned to be locked through **PinkLock** with a **6-month cliff**, followed by vesting. The vesting duration for this locked portion will be added once finalized.                                        |
| **Treasury — 10%**                | **8% of total supply** from the treasury allocation is planned to be locked through **PinkLock** with a **12-month cliff**, followed by **6 months of vesting**. The remaining **2%** treasury allocation is not included in this PinkLock schedule unless later specified. |

## Wallet & lock verification

The relevant wallet addresses, liquidity-pool address, direct lock records and BaseScan verification links can be added here as soon as the wallets, pool and lock positions have been created.

| Allocation                       | Wallet / pool address                     | Lock / verification                                                                                        | BaseScan verification                          |
| -------------------------------- | ----------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| **Initial DEX Liquidity**        | `TBD — add liquidity pool address`        | [https://app.uncx.network/](https://app.uncx.network/) — direct UNCX lock link: `TBD`                      | `TBD — add BaseScan pool / transaction link`   |
| **Future Liquidity Reserve A–D** | `TBD — add reserve wallet / pool address` | [https://www.pinksale.finance/pinklock/](https://www.pinksale.finance/pinklock/) — direct lock link: `TBD` | `TBD — add BaseScan wallet / transaction link` |
| **Team**                         | `TBD — add wallet address`                | [https://www.pinksale.finance/pinklock/](https://www.pinksale.finance/pinklock/) — direct lock link: `TBD` | `TBD — add BaseScan wallet / transaction link` |
| **Community / Airdrops**         | `TBD — add wallet address`                | [https://www.pinksale.finance/pinklock/](https://www.pinksale.finance/pinklock/) — direct lock link: `TBD` | `TBD — add BaseScan wallet / transaction link` |
| **Ecosystem / Development**      | `TBD — add wallet address`                | [https://www.pinksale.finance/pinklock/](https://www.pinksale.finance/pinklock/) — direct lock link: `TBD` | `TBD — add BaseScan wallet / transaction link` |
| **Marketing / Growth**           | `TBD — add wallet address`                | [https://www.pinksale.finance/pinklock/](https://www.pinksale.finance/pinklock/) — direct lock link: `TBD` | `TBD — add BaseScan wallet / transaction link` |
| **Treasury**                     | `TBD — add wallet address`                | [https://www.pinksale.finance/pinklock/](https://www.pinksale.finance/pinklock/) — direct lock link: `TBD` | `TBD — add BaseScan wallet / transaction link` |

{% hint style="info" %}
**UNCX:** [https://app.uncx.network/](https://app.uncx.network/)\
**PinkLock:** [https://www.pinksale.finance/pinklock/](https://www.pinksale.finance/pinklock/)\
**BaseScan:** [https://basescan.org/](https://basescan.org/)\
Once each position is created, the corresponding address, direct lock or deployment verification link and BaseScan link should be published in the table above.
{% endhint %}

{% hint style="warning" %}
The framework above reflects the current plan. Exact start dates, unlock dates, vesting intervals, wallet addresses, liquidity-pool addresses and direct verification links should only be treated as final once the relevant contracts, wallets, pool and locks have been created and independently verified.
{% endhint %}

## Utility framework

Potential utility areas may include ecosystem access, agent-related services, incentives, governance or other platform mechanisms where there is a defined technical role. Each utility claim should ultimately map to an implemented product function or smart-contract mechanism.

## Security audit & certification

A **CertiK smart-contract audit and security review is planned after the token contract has been created and finalized**. The audit status, verified report link, scope and any relevant certification details will be published here once the review has been completed.

| Security verification            | Status                                      |
| -------------------------------- | ------------------------------------------- |
| **CertiK audit / certification** | **Planned — after token contract creation** |

{% hint style="info" %}
The project will only describe a CertiK audit as completed or certified after an official, independently verifiable report is available.
{% endhint %}

## Transparency standard

Before launch, the documentation should publish the official token contract, relevant allocation wallets, liquidity-pool details, UNCX lock evidence, future-liquidity tranche details, PinkLock verification links, BaseScan verification links, any vesting contracts or schedules, and the official security-audit report where applicable so these items can be independently verified.

{% hint style="warning" %}
Nothing on this page should be interpreted as a promise of price appreciation, yield or investment return. Utility documentation describes intended ecosystem function, not market performance.
{% endhint %}
