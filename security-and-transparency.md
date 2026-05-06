---
description: How Magnet Finance secures protocol funds, manages authority, and maintains transparency.
---

# Security and Transparency

## Treasury Security

The Magnet Finance treasury is secured through a multi-layered approach combining hardware security and multi-signature authorization.

**Primary security:**
* **Squads Protocol** — multisig smart contract on Solana
* **Ledger Nano S Plus** — hardware wallet for all transaction signing
* **Treasury wallet:** `MGNT3FLU58jFTuFisoHUGkVdzT2x5LnF68qMhgjJ3E7`

All treasury transactions require multisig approval and hardware wallet confirmation. No single key can move treasury funds.

## Token Authority

### $MGNT
* **Update Authority:** `MGNT3FLU58jFTuFisoHUGkVdzT2x5LnF68qMhgjJ3E7` (treasury multisig)
* **Mint Authority:** Controlled by treasury multisig
* **Freeze Authority:** None — token cannot be frozen

The `isMutable` flag on the $MGNT metadata is intentionally kept mutable to allow future metadata updates (logo, description, links) as the protocol develops. This is a UX decision, not a security risk — it does not affect token supply, ownership, or transfer mechanics.

### mgntSOL
* **Mint:** `mgntr7GPnAM6g5cDYMAmjbLvNmbfG3cN1pjAvbnWVKK`
* Built on Sanctum infrastructure with their established validator delegation and security model

## Core Contributors Lock

The Core Contributors allocation (50% of $MGNT max supply) is secured in an on-chain escrow with:

* **12-month cliff** — no tokens unlock for the first 12 months
* **24-month linear vest** — tokens vest linearly over 24 months following the cliff
* **Full vest completion:** June 2030
* **Escrow address:** `62HjS598jzANCexVzkxjLmttXXLzyvNVmCc1BiJsggmJ`

This is verifiable on-chain. No early access. No override mechanism.

## On-Chain Verifiability

All Magnet Finance protocol actions are verifiable on Solana mainnet:

* Every weekly epoch distribution is a public on-chain transaction
* Every $MGNT burn is verifiable on Solscan
* Every treasury transaction requires multisig approval and is publicly visible
* The mgntSOL/SOL DLMM pool is publicly viewable on Meteora

## Metadata Storage

Token metadata is hosted on IPFS via Pinata:

* $MGNT metadata URI: `https://purple-adverse-pony-836.mypinata.cloud/ipfs/bafkreidtppvninlmraag7urhhurili62we4mgeeuy6frlv4x4knfjxtike`

## Smart Contract Risk

Magnet Finance uses established, audited infrastructure where possible:

* **Sanctum** — established LST infrastructure on Solana
* **Meteora DLMM** — established concentrated liquidity protocol
* **Jupiter v6** — established swap aggregator
* **Squads Protocol** — established multisig infrastructure

Season 2 staking contracts will be developed with security reviews prior to deployment.

{% hint style="info" %}
**Telegram:** [t.me/MGNTFinancePublic](https://t.me/MGNTFinancePublic)
{% endhint %}
