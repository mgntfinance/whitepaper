# Revenue Model

Magnet Finance generates protocol revenue from three distinct streams. Each stream has a different economic character — and each routes to the token polarity that best matches it through the **Magnetic Polarity Revenue Routing** mechanic.

---

## The Three Revenue Streams

### 1. Swap Fees — Magnetic Swap

**Source:** Every swap routed through Magnetic Swap (Jupiter v6 API)
**Fee:** 30 basis points (0.30%) platform fee, routing to treasury
**Character:** High-frequency, volume-driven — scales directly with swap activity

Magnetic Swap is live at [mgntfinance.com/swap](https://mgntfinance.com/swap). Every swap of SOL, USDC, USDT, or mgntSOL through the Magnet Finance frontend generates 30bps in treasury revenue.

A portion of swap fee revenue funds weekly $MGNT buybacks. The remainder routes to the swap fee amplifier for $MGNT holders via the Base Layer + Polarity Amplifier distribution.

**Jupiter referral account:** `3zLDqUpbeRSUT7WhzL7pnVe7jCyPW5g8MFKJmv5MVP8y`

---

### 2. LP Yield — Meteora DLMM

**Source:** Concentrated liquidity positions in the mgntSOL/SOL Meteora DLMM pool
**Character:** Continuous, position-driven — scales with pool utilization and fee tier

The protocol provides liquidity in the mgntSOL/SOL DLMM pool and earns LP fees from every swap through that pool. LP yield routes to the **pMGNT polarity amplifier** — the positive polarity token earns from the volume-driven side of the ecosystem.

**Pool address:** `8j7Sk4Q8LcnadMf9T9TRBYePhJaouxi5K2tx3ZQRXDYo`

---

### 3. Treasury Yield — Diversified Positions

**Source:** Diversified yield strategies funded by presale proceeds
**Character:** Long-duration, compounding — scales with treasury size and deployment efficiency

Presale capital is deployed across diversified on-chain yield positions: lending protocols, external LP positions, and yield strategies. Treasury yield routes to the **nMGNT polarity amplifier** — the negative polarity token earns from the long-duration, compounding side of the treasury.

> Treasury yield positions are deployed post-presale completion.

---

## Weekly Magnetic Epoch Distribution

Every 7 days, all revenue is tallied and distributed on-chain in two tiers:

**Tier 1 — Base Layer:**
A fixed percentage of total revenue distributes proportionally to all $MGNT, pMGNT, and nMGNT holders. No holder earns zero.

**Tier 2 — Polarity Amplifiers:**
The remaining revenue routes by source to the matching token polarity:

| Revenue Source | Routes To |
|---------------|-----------|
| Swap fees | $MGNT holders (swap fee amplifier) |
| LP yield | pMGNT holders (LP yield amplifier) |
| Treasury yield | nMGNT holders (treasury yield amplifier) |

---

## Burn Mechanics

Revenue distribution is paired with continuous supply compression:

| Token | Burn Mechanism |
|-------|---------------|
| $MGNT | Weekly buybacks from swap fee revenue, burned on-chain |
| pMGNT | 0.5% of every transfer is burned |
| nMGNT | 1.5% of every transfer is burned |

All three token supplies compress simultaneously, regardless of which token you hold. The Magnet Finance ecosystem becomes more deflationary over time as protocol activity increases.

---

## Revenue Growth

As the protocol scales, all three streams grow:

- **More swap volume** → more swap fees → more $MGNT buybacks + larger swap fee amplifier
- **More LP depth** → more LP fee revenue → larger pMGNT amplifier
- **Larger treasury** → more yield positions → larger nMGNT amplifier

Every token polarity benefits from protocol growth — just in the way that matches its character.
