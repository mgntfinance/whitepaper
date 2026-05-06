---
description: The core innovation of Magnet Finance — revenue routed by character to match the token that earned it.
---

# Magnetic Polarity Revenue Routing

Most DeFi protocols generate real revenue. Almost none of it routes back to token holders in a structured, token-specific way. Magnet Finance is the first protocol to solve this by matching the *character* of each revenue stream to the *character* of each token.

## The Core Mechanic

Revenue is not pooled and distributed generically. It is **routed by character** — swap fees to utility token holders, LP yield to volume token holders, treasury yield to scarcity token holders.

This creates alignment between what a token *is* and what it *earns*.

## Three Revenue Streams

| Stream | Source | Mechanism |
|--------|--------|-----------|
| **Swap Fees** | Magnetic Swap (Jupiter v6) | 30bps platform fee on every swap, routed to treasury |
| **LP Yield** | Meteora DLMM concentrated liquidity | mgntSOL/SOL pool generates fee revenue from trading volume |
| **Treasury Yield** | Diversified yield positions | Presale capital deployed across lending, external LP, and yield strategies |

## Two-Tier Distribution — The Weekly Magnetic Epoch

Every 7 days, all protocol revenue is tallied across the three streams and distributed on-chain in two tiers.

### Tier 1 — Base Layer (every holder, no exceptions)

A fixed percentage of total protocol revenue distributes **proportionally to ALL $MGNT, pMGNT, and nMGNT holders** every epoch, regardless of polarity or staking status. Every token holder earns something. No one gets zero.

This is the safety net — the guaranteed floor of participation for anyone who holds any Magnet Finance token.

### Tier 2 — Polarity Amplifiers (upside by token type)

The remaining revenue routes by source to the matching token:

| Token | Amplifier Source | Logic |
|-------|-----------------|-------|
| **$MGNT** | Swap fee revenue | Core utility token earns from core protocol activity |
| **pMGNT** | LP yield | Positive polarity / volume token earns from volume-driven yield |
| **nMGNT** | Treasury yield | Negative polarity / scarcity token earns from long-duration compounding |

## Staking is Always Double-Up, Never a Sacrifice

Staking $MGNT to receive pMGNT or nMGNT is **always additive**. Holders never lose their base layer or swap fee amplifier position by staking.

| Position | Base Layer | Swap Fee Amplifier | Polarity Amplifier |
|----------|-----------|-------------------|-------------------|
| Unstaked $MGNT | ✅ | ✅ | ❌ |
| Staked → pMGNT | ✅ | ✅ | ✅ (LP yield) |
| Staked → nMGNT | ✅ | ✅ | ✅ (Treasury yield) |

Lock duration multiplies amplifier weight. The longer you lock, the more you earn. Earnings vest only if staked through the full weekly epoch snapshot.

## Why This Is Novel

No other DeFi protocol routes revenue by stream character to token character. Existing approaches fall into one of three failure modes:

1. **No distribution** — revenue sits in treasury, holders earn nothing
2. **Generic pooling** — all revenue pooled, all tokens earn identically regardless of design
3. **Inflationary rewards** — new token supply printed to reward holders, diluting value in the process

Magnetic Polarity Revenue Routing does none of these. It distributes real protocol revenue, routes it specifically, and burns a portion of every distribution — compressing supply while distributing yield simultaneously.

## The Epoch Cycle

Every weekly Magnetic Epoch follows the same on-chain sequence:

1. Revenue tallied across all three streams
2. Base Layer percentage distributed proportionally to all holders
3. Polarity amplifiers distributed by stream to matching token holders
4. Burn portion executed on-chain (publicly verifiable)
5. Epoch closes, new epoch begins

All transactions are publicly verifiable on Solana mainnet.

{% hint style="info" %}
**Telegram:** [t.me/MGNTFinancePublic](https://t.me/MGNTFinancePublic)
{% endhint %}
