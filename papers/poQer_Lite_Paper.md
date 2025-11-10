# poQer: The First On-Chain Poker Platform on Qubic  
**Lite Paper v1.0**

---

## Executive Summary

**Poker** remains the most recognized and celebrated card game worldwide.  
**poQer** aims to become the first — and most prominent — on-chain poker game within the **Qubic** ecosystem, combining blockchain transparency with competitive gameplay.

Leveraging **Qubic smart contracts**, poQer introduces:

- Decentralized **Initial Public Offerings (IPOs)** for investor participation  
- **Passive income** for shareholders  
- **Deflationary tokenomics** via automatic burn mechanisms  

> *Get ready to show your poQer face — where strategy meets innovation on-chain.*

---

## Problem Statement

The global expansion of online gaming and gambling has created massive demand for **fairness, transparency, and provable outcomes** — areas where traditional platforms still fall short.

While **blockchain** technology enables these features, the **Qubic** ecosystem currently lacks a native poker platform. Competing chains like **Solana**, **Ethereum**, and **Binance Smart Chain** already host several on-chain card games.

**poQer** fills this gap — offering fair play, verifiable smart contracts, and real economic incentives built directly on **Qubic**.

---

## Platform Design – Game Overview

### Gameplay Overview

**poQer v1.0** is based on **Texas Hold’em**, the most popular poker variant globally.

#### Table Tiers

| **Table** | **Buy-In (Qubic)** |
|------------|--------------------|
| Paedocypris | 1 M |
| Ichthyosaur | 5 M |
| Megalodon | 10 M |
| Livyatan | 25 M |

- Max **9 players** per table, minimum **5 players** to start  
- Tournaments run **24/7**, each lasting **up to 3 hours**
- Ends when:
  - The timer expires → *player with the most earnings wins*  
  - One player collects all chips in play  

---

### Tournament Entry Flow

1. **Visit the poQer website**
2. **Connect your Qubic wallet** (via WalletConnect)
3. **Select an open table** from the lobby

**Seat Rules:**
- Each table has a **30-minute fill window**
- Minimum 5 players required to start  
- If fewer than 5 players, the timer resets and players remain seated  
- Once started, tables are locked — no late entries  
- New tables automatically spawn as others begin  

**Additional Rules:**
- Buy-ins are **locked** upon entry and cannot be withdrawn  
- **No rebuys** permitted  
- Disconnected players may submit a **refund ticket** with transaction ID and wallet address (subject to honesty-based refund pool)

---

## Revenue Model & Distribution

Every tournament uses **Qubic smart contracts** for **automated payouts** and **transparent fee distribution**.

### Payout Breakdown

| **Recipient** | **Percentage** |
|----------------|----------------|
| Winner | 75% |
| Shareholders | 20% |
| Team | 3% |
| Burn | 2% |

---

### Example Payouts

| **Players** | **Buy-In (QUS)** | **Pot Total** | **Winner (75%)** | **Shareholders (20%)** | **Team (3%)** | **Burn (2%)** |
|--------------|------------------|----------------|------------------|------------------------|----------------|----------------|
| 8 | 1 M | 8 M | 6 M | 1.6 M | 0.24 M | 0.16 M |
| 7 | 5 M | 35 M | 26.25 M | 7 M | 1.05 M | 0.7 M |
| 9 | 10 M | 90 M | 67.5 M | 18 M | 2.7 M | 1.8 M |
| 5 | 25 M | 250 M | 187.5 M | 38 M | 7.5 M | 5 M |

**Total Example (4 Tournaments per Epoch)**  
- Winners: 287.25 M QUS  
- Shareholders: 64.6 M QUS  
- Team: 11.79 M QUS  
- Burn: 7.66 M QUS  

> This model enables **passive yield** for investors while ensuring a **deflationary burn cycle** that strengthens Qubic’s long-term token value.

---

## Technical Design & Smart Contract Integration

poQer runs entirely through **auditable Qubic smart contracts**, ensuring fairness and automation.

| **Module** | **Purpose** |
|-------------|-------------|
| **IPO Contract** | Manages share distribution and dividend payouts |
| **Tournament Factory** | Deploys/manages tournaments with defined parameters |
| **Tournament Contract** | Handles buy-ins, validation, and payouts |
| **Revenue Manager** | Allocates winnings, fees, and burns |
| **Oracle Layer** | Provides verifiable RNG for dealing cards |

All on-chain activity is transparent and verifiable in real time.

---

## Tokenomics

- **Native Currency:** QUBIC  
- **Shareholder Rewards:** 20% of each tournament pot  
- **Deflationary Mechanism:** 2% burned from every prize pool  
- **IPO Participation:** Revenue-based passive income  
- **No Transaction Fees:** Feeless Qubic architecture for fast settlement  

> The poQer model strengthens Qubic’s **deflationary token supply** while drawing new liquidity and participants through gaming utility.

---

## Security & Fairness

- **Provable Fairness:** Commit-reveal and RNG oracles ensure unbiased card distribution  
- **Immutable Logic:** All funds handled by audited smart contracts  
- **Non-Custodial:** Player funds remain locked in escrow until automatic payout  
- **Transparency:** Every game and payout verifiable on-chain  
- **Anti-Cheat:** Gameplay logs, session hashing, and audit trails prevent manipulation  

---

## Roadmap

| **Milestone** | **Timeline** | **Description** |
|----------------|--------------|-----------------|
| Lite Paper v1.0 | Nov 2025 | Initial Concept Release |
| White Paper v1.0 | Dec 2025 | Full technical & economic documentation |
| Proposal Submission | Q1 2026 | Governance submission to Qubic ecosystem |
| Development & Testing | Q2 2026 | Smart contract coding, alpha testing, audits |
| Launch | Mid 2026 | Public release of poQer platform |

---

## Summary & Benefits

- Supports Qubic’s **deflationary tokenomics**  
- Generates **passive income** for IPO shareholders  
- Onboards **new users and investors** through gaming  
- Transparent, auditable gameplay powered by smart contracts  
- Modular scalability for long-term growth  

> **poQer** stands at the intersection of gaming, finance, and decentralized technology — redefining poker for the Web3 era.

---

## Links & Contact

- **X (Twitter):** Qub’zylthar Nexus  
- **Discord:** Qub’zylthar Nexus (Qubic)
