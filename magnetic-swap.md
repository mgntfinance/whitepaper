# Magnetic Swap

Magnetic Swap is Magnet Finance's native swap hub — powered by Jupiter v6 aggregation and live on Solana mainnet. Every swap through Magnetic Swap generates protocol revenue that flows directly into the weekly Magnetic Epoch distribution.

**Live at:** [mgntfinance.com/swap](https://mgntfinance.com/swap)

---

## How It Works

Magnetic Swap routes trades through Jupiter v6, giving users access to the best prices across all Solana DEX liquidity. On top of Jupiter's routing, Magnet Finance adds a **30bps platform fee** on each swap, which routes to the protocol treasury.

- Best execution via Jupiter's aggregated liquidity
- 30bps platform fee to treasury on every swap
- No additional slippage beyond Jupiter's standard routing
- Available tokens: SOL, USDC, USDT, mgntSOL (more post-TGE)

---

## Revenue Impact

Swap fees are the core driver of $MGNT deflationary pressure:

1. Swap fee revenue accumulates in the treasury
2. Every weekly Magnetic Epoch, a portion funds $MGNT buybacks on the open market
3. Bought-back $MGNT is burned on-chain
4. The remaining swap fee revenue routes to $MGNT holders via the swap fee amplifier

**More swap volume → more buyback pressure → more $MGNT deflation.**

---

## Season 1 Points

Swap volume through Magnetic Swap earns **Season 1 Genesis Points** in addition to the base mgntSOL holding points. Every swap contributes to your leaderboard position.

---

## Jupiter Integration

Magnetic Swap is built on Jupiter v6 REST API:

| Parameter | Value |
|-----------|-------|
| API endpoint | `quote-api.jup.ag/v6` |
| Platform fee | `platformFeeBps: 30` |
| Referral account | `3zLDqUpbeRSUT7WhzL7pnVe7jCyPW5g8MFKJmv5MVP8y` |
| Referral link | [jup.ag/?ref=j7k62o1lad32](https://jup.ag/?ref=j7k62o1lad32) |

---

## Roadmap

**Coming in Phase 1.5 / Season 2:**
- Jupiter DCA integration — automated dollar-cost averaging into any Solana token
- Active Orders tab — view and manage open DCA positions
- Cross-chain swap via aggregator SDK (Li.Fi, Rango, or Squid Router)
- EVM and Sui swap support

---

## Using Magnetic Swap

1. Connect your Solana wallet at [mgntfinance.com/swap](https://mgntfinance.com/swap)
2. Select input and output tokens
3. Review the quoted rate and estimated output
4. Approve the transaction in your wallet

The 30bps platform fee is automatically deducted from the swap output and routed to the Magnet Finance treasury. No additional steps required.
