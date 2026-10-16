# USDT Whale (USDTW) — Whitepaper

**Version 1.0 · October 2026**

## Abstract

USDT Whale (USDTW) is a fixed-supply settlement token deployed
simultaneously on Solana and Tron. 80,000,000 USDTW were minted
once on each network — a hard total of 160,000,000 tokens — and no
more can ever be created. Mint and freeze authorities are permanently
revoked on both chains, verifiable on-chain by any party.

## 1. Overview

USDTW is designed as a settlement and payment token for cross-chain
transfers and peer-to-peer value exchange, operating on two of the
lowest-cost networks available:

- **Solana** — sub-second finality, fractions of a cent per transfer
- **Tron** — near-zero fees for TRC-20 transfers, wide exchange and
  wallet support

The same name, symbol, and supply law apply on both chains.

## 2. Token Specifications

| Property          | Solana                     | Tron (TRC-20)             |
|-------------------|----------------------------|---------------------------|
| Name              | USDT Whale                 | USDT Whale                |
| Symbol            | USDTW                      | USDTW                     |
| Decimals          | 6                          | 6                         |
| Total supply      | 80,000,000                 | 80,000,000                |
| Contract          | AFNnpqWGngEe8FUrwcc7kPb2ooXZP9u6dzbfehBnoBT | TEXzwNmm6n29QcZVjhZZ6FU7wT53PbXnT8 |

Combined maximum supply across both networks: **160,000,000 USDTW**.

## 3. Fixed Supply & Security

- All tokens were minted in a single issuance at launch (2026-10-07).
- The mint authority is revoked: no additional USDTW can ever be
  created on either network.
- The freeze authority is revoked: token holders cannot be frozen or
  confiscated by the issuer. Holders have unconditional control of
  their balances.
- Both revocations are verifiable on-chain via the explorers listed
  in Section 6.

## 4. Markets & Liquidity

USDTW trades on decentralized exchanges on both networks:

- **Tron — SunSwap v2 pair (USDTW/WTRX)**, live and settled
  by market activity near a $1.00 reference price.
- **Solana — Raydium CPMM pool (USDTW/SOL)**, providing
  SOL-side liquidity for the network.

Current market data is available on DEX screeners and on the
project website.

## 5. Supply Verification

Public, always-on endpoints verify the supply without trusting
any party's word:

- Total supply (JSON): https://afritz77.github.io/usdt-token/total-supply.json
- Circulating supply (text): https://afritz77.github.io/usdt-token/circulating-supply.txt

## 6. Official Links

- Website: https://afritz77.github.io/usdt-token/
- Solana explorer: https://solscan.io/token/AFNnpqWGngEe8FUrwcc7kPb2ooXZP9u6dzbfehBnoBT
- Tron explorer: https://tronscan.io/#/token20/TEXzwNmm6n29QcZVjhZZ6FU7wT53PbXnT8
- X / Twitter: https://x.com/asilimeme

## 7. Distribution

The majority of supply is retained in project treasuries on each
network and is released into circulation through market activity
and distribution over time. Circulating supply figures are
published at the endpoints in Section 5.

---

*USDT Whale is a fixed-supply token. Nothing in this document
constitutes financial advice or a guarantee of price performance.
Supply, authorities, and contract addresses are verifiable
on-chain at any time.*
