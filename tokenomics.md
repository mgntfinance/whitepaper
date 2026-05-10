# Tokenomics

$MGNT has a fixed maximum supply of **36,900,000 tokens**. The supply is fully defined at deployment -- no new $MGNT can ever be created. Mint authority is renounced after presale minting.

---

## Supply Allocation

| Allocation | Tokens | % of Supply | Notes |
|---|---|---|---|
| Presale | 3,690,000 | 10% | Four tiers: Genesis / Community / Whitelist / Public |
| DEX Liquidity | 1,000,000 | 2.71% | Seeded post-presale at TGE |
| Core Contributors | 1,360,110 | 3.69% | 12-month cliff + 24-month linear vest to June 2030 |
| Ecosystem & Community | 12,000,000 | 32.52% | Rewards, grants, community incentives -- long-term release |
| Protocol Treasury | 4,500,000 | 12.20% | Controlled by treasury multisig; used for operations and yield deployment |
| Long-Term Reserve | 14,349,890 | 38.89% | Locked; 50% of max supply unlocks over 15 years |

{% hint style="info" %}
**No inflation. Ever.** The 36,900,000 supply ceiling is enforced on-chain. Weekly buybacks actively reduce circulating supply over time.
{% endhint %}

---

## Presale Structure

| Tier | Price | Allocation | Wallet Cap | TGE Unlock | Vesting |
|---|---|---|---|---|---|
| Genesis | $0.10 | 553,500 MGNT (15%) | $500 | 10% | 9 months linear |
| Community | $0.15 | 922,500 MGNT (25%) | $1,500 | 15% | 6 months linear |
| Whitelist | $0.20 | 1,107,000 MGNT (30%) | $2,500 | 20% | 4 months linear |
| Public | $0.25 | 1,107,000 MGNT (30%) | $10,000 | 25% | 3 months linear |

**Total presale raise target:** ~$691,875
**Blended average price:** ~$0.188
**Implied FDV at public price:** ~$6.93M

---

## Contributors Lock

All core contributor tokens are locked under a structured vesting schedule with no early access:

| Parameter | Value |
|---|---|
| Cliff | 12 months |
| Vesting | 24-month linear after cliff |
| Vesting end | June 2030 |
| Lock escrow | `62HjS598jzANCexVzkxjLmttXXLzyvNVmCc1BiJsggmJ` |

No contributor tokens are accessible before **June 2027**.

---

## Deflationary Pressure

Supply does not just hold flat -- it actively compresses over time:

- **$MGNT:** Weekly buybacks funded by a portion of swap fee revenue, burned on-chain every Magnetic Epoch
- **pMGNT:** 0.5% burn on every transfer
- **nMGNT:** 1.5% burn on every transfer

The more the protocol is used, the more aggressively all three supplies compress. This is structural, not discretionary.