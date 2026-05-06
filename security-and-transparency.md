# Security and Transparency

Magnet Finance is built with a security-first approach. Every significant asset is protected by multi-signature controls, hardware security, and on-chain transparency. All protocol activity is publicly verifiable.

---

## Treasury Security

The protocol treasury is secured by a **Squads Protocol multisig** requiring multiple signatures to execute any transaction.

**Treasury wallet:** `MGNT3FLU58jFTuFisoHUGkVdzT2x5LnF68qMhgjJ3E7`

- All treasury transactions require multisig approval
- Primary signer uses a **Ledger Nano S Plus** hardware wallet
- Treasury is the update authority for all Magnet Finance token metadata
- All treasury activity is publicly viewable on-chain

---

## Token Security

### $MGNT
- **Mint authority:** Renounced after presale minting — no new $MGNT can ever be created beyond the presale allocation
- **Freeze authority:** Renounced
- **Metadata update authority:** Treasury multisig
- **Max supply:** 36,900,000 — enforced on-chain, permanent

### mgntSOL
- **Infrastructure:** Sanctum — audited LST infrastructure used by the broader Solana ecosystem
- **isMutable:** Intentionally kept mutable for future metadata updates (logo, description). This is standard practice for LSTs and is not a security concern.
- **Update authority:** Treasury multisig (`MGNT3FLU58jFTuFisoHUGkVdzT2x5LnF68qMhgjJ3E7`)

---

## Core Contributors Lock

All core contributor tokens are locked under a structured vesting schedule:

| Parameter | Value |
|-----------|-------|
| Cliff | 12 months |
| Vesting | 24-month linear after cliff |
| Vesting end | June 2030 |
| Lock escrow | `62HjS598jzANCexVzkxjLmttXXLzyvNVmCc1BiJsggmJ` |

No contributor tokens are accessible before June 2027. This structure ensures the team's interests are fully aligned with long-term protocol health.

---

## On-Chain Transparency

Every Magnet Finance protocol action is publicly verifiable on Solana:

| Item | Link |
|------|------|
| $MGNT token | [solscan.io/token/PWFsq6a5LbtqpJfNSvNmchDqSnLB5hTA6mAr3Kj1qHg](https://solscan.io/token/PWFsq6a5LbtqpJfNSvNmchDqSnLB5hTA6mAr3Kj1qHg) |
| mgntSOL token | [solscan.io/token/mgntr7GPnAM6g5cDYMAmjbLvNmbfG3cN1pjAvbnWVKK](https://solscan.io/token/mgntr7GPnAM6g5cDYMAmjbLvNmbfG3cN1pjAvbnWVKK) |
| Treasury wallet | [solscan.io/account/MGNT3FLU58jFTuFisoHUGkVdzT2x5LnF68qMhgjJ3E7](https://solscan.io/account/MGNT3FLU58jFTuFisoHUGkVdzT2x5LnF68qMhgjJ3E7) |
| Contributors lock | [solscan.io/account/62HjS598jzANCexVzkxjLmttXXLzyvNVmCc1BiJsggmJ](https://solscan.io/account/62HjS598jzANCexVzkxjLmttXXLzyvNVmCc1BiJsggmJ) |
| Meteora DLMM pool | [solscan.io/account/8j7Sk4Q8LcnadMf9T9TRBYePhJaouxi5K2tx3ZQRXDYo](https://solscan.io/account/8j7Sk4Q8LcnadMf9T9TRBYePhJaouxi5K2tx3ZQRXDYo) |

---

## Metadata Storage

Token metadata URIs are hosted on Pinata/IPFS:

- **$MGNT metadata:** `https://purple-adverse-pony-836.mypinata.cloud/ipfs/bafkreidtppvninlmraag7urhhurili62we4mgeeuy6frlv4x4knfjxtike`
- Metadata is immutable once published to IPFS — content cannot be silently changed

---

## Disclosure

Magnet Finance is a pre-TGE protocol currently in active development. The information in this whitepaper represents the current state of the protocol and its intended design. Nothing herein constitutes financial advice. Participation in DeFi protocols carries risk. Always do your own research.
