---
description: Swap instantly across Solana. Powered by Jupiter. Every swap funds the protocol.
---

# Magnetic Swap

Magnetic Swap is Magnet Finance's native swap hub — a Jupiter v6-powered exchange interface live at **mgntfinance.com/swap**. Every swap on Magnetic Swap generates revenue for the protocol and earns points for the swapper.

## How It Works

Magnetic Swap routes through the **Jupiter v6 API** — the leading swap aggregator on Solana. Jupiter finds the best available route across all Solana DEXes and liquidity sources, ensuring users always receive optimal pricing.

On top of Jupiter's routing, Magnet Finance applies a **30bps platform fee** on every swap. This fee routes directly to the Magnet Finance treasury and feeds into the protocol's swap fee revenue stream.

## Available Tokens

Current swap pairs available on Magnetic Swap:

* SOL
* USDC
* USDT
* mgntSOL

$MGNT will be added to Magnetic Swap following the TGE.

## Platform Fee

**Fee:** 30bps (0.30%) on every swap  
**Destination:** Magnet Finance treasury  
**Distribution:** Routed to $MGNT holders via swap fee amplifier in the Weekly Magnetic Epoch

This creates a direct link between swap activity and $MGNT holder earnings. More volume = more swap fee revenue = stronger swap fee amplifier for $MGNT holders.

## Jupiter Integration Details

| Parameter | Value |
|-----------|-------|
| API | Jupiter v6 REST API |
| Endpoint | `quote-api.jup.ag/v6` |
| Platform Fee | 30bps (`platformFeeBps: 30`) |
| Referral Account | `3zLDqUpbeRSUT7WhzL7pnVe7jCyPW5g8MFKJmv5MVP8y` |
| Referral Link | [jup.ag/?ref=j7k62o1lad32](https://jup.ag/?ref=j7k62o1lad32) |

## Season 1 Points

Swap volume on Magnetic Swap earns **Season 1 Genesis Points**, contributing to your leaderboard position alongside mgntSOL holding.

## Future: Cross-Chain Swap

Magnet Finance's Magnetic Swap roadmap includes cross-chain swap capability via aggregator SDK integration (Li.Fi, Rango, or Squid Router), expanding access beyond Solana to EVM and Sui networks.

Cross-chain expansion is a Season 2+ target. Current focus is Solana-native swap volume.

{% hint style="info" %}
**Telegram:** [t.me/MGNTFinancePublic](https://t.me/MGNTFinancePublic)
{% endhint %}
