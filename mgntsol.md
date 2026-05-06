# mgntSOL — Liquid Staking

mgntSOL is Magnet Finance's liquid staking token. Stake SOL, receive mgntSOL, and remain fully liquid across the Solana DeFi ecosystem — without sacrificing staking yield.

Built on **Sanctum** infrastructure, mgntSOL is a first-class LST on Solana with deep liquidity and exchange-rate integrity.

---

## Contract Address

**mgntSOL Mint:** `mgntr7GPnAM6g5cDYMAmjbLvNmbfG3cN1pjAvbnWVKK`

| Parameter | Value |
|-----------|-------|
| Decimals | 9 |
| Infrastructure | Sanctum |
| Liquidity | Meteora DLMM pool (mgntSOL/SOL) |
| Pool Fee | 1bps base fee, dynamic fees enabled |
| Meteora Pool | `8j7Sk4Q8LcnadMf9T9TRBYePhJaouxi5K2tx3ZQRXDYo` |

---

## How It Works

1. **Stake SOL** → receive mgntSOL at the current exchange rate
2. **mgntSOL accrues value** as Solana staking yield accumulates — the exchange rate of mgntSOL:SOL increases over time
3. **Remain liquid** — mgntSOL is freely transferable and usable across DeFi protocols on Solana
4. **Unstake anytime** — redeem mgntSOL for SOL through Sanctum or swap through Meteora

Yield is variable and derived from Solana validator rewards. No fixed APY is guaranteed.

---

## Meteora DLMM Liquidity Pool

Magnet Finance provides concentrated liquidity for mgntSOL/SOL through a Meteora DLMM pool:

- **Configuration locked:** March 2026
- **Fee tier:** 1bps base fee with dynamic fees enabled
- **Shape:** Curve
- **Initial liquidity:** 3 SOL + 3 mgntSOL
- **Manager:** Treasury multisig (`MGNT3FLU58jFTuFisoHUGkVdzT2x5LnF68qMhgjJ3E7`)

The DLMM pool provides tight spreads around the mgntSOL/SOL exchange rate, enabling efficient swaps with minimal price impact.

---

## mgntSOL and the Season 1 Points Campaign

Holding mgntSOL is the primary way to earn **Season 1 Genesis Points**:

**Formula:** `mgntSOL balance × 10 pts/hr`

- Balances are scanned every 5 minutes
- Points displayed to 3 decimal places, no rounding
- Points translate directly to future protocol rewards

---

## On-Chain Verification

- **Solscan:** [solscan.io/token/mgntr7GPnAM6g5cDYMAmjbLvNmbfG3cN1pjAvbnWVKK](https://solscan.io/token/mgntr7GPnAM6g5cDYMAmjbLvNmbfG3cN1pjAvbnWVKK)
- **Sanctum:** [app.sanctum.so/stake/mgntSOL](https://app.sanctum.so/stake/mgntSOL)
- **Update Authority:** `MGNT3FLU58jFTuFisoHUGkVdzT2x5LnF68qMhgjJ3E7`

---

## Note on isMutable

mgntSOL's metadata is intentionally kept mutable to allow future metadata updates (logo, description, etc.). This is standard practice for LSTs and is not a security concern. The update authority is held in the treasury multisig secured by Squads Protocol and a Ledger Nano S Plus.
