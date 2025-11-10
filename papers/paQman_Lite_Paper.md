# paQman: First Ever Qubic-Style Pac-Man Game  
**Featuring CFB as Pac-Man**

**Lite Paper v1.0**

---

## Executive Summary

**paQman** is a decentralized, on-chain arcade game designed to bring competitive, skill-based gameplay into the Qubic ecosystem. Players compete in high-score weekly tournaments using **Qubic tokens** as entry fees. Winners receive rewards automatically distributed by Qubic smart contracts, while a portion of every prize pool is burned or added to the liquidity pool of their choice—creating a **deflationary token economy**.

The project integrates a **shareholder IPO mechanism** allowing token holders to earn passive income from tournament activity:

- **75%** rewards go to players  
- **20%** to shareholders  
- **3%** to the development team  
- **2%** burned or added to liquidity

This merges the nostalgia of arcade gaming with blockchain efficiency and transparency.

> *“paQman turns tokens into power pellets — eat rewards, not inflation.”*

---

## Problem Statement

Blockchain gaming is rapidly growing, yet the **Qubic ecosystem lacks a high-performance, skill-based arcade title**.  
Most GameFi projects are collectible or low-skill lotteries. This leaves a gap for:

- Competitive, fast-paced gaming with provable fairness  
- Automated, trustless reward distribution  
- Tokenomics rewarding players, investors, and ecosystem growth  

Meanwhile, networks like Solana, Ethereum, and Binance Smart Chain host multiple arcade-style or leaderboard games. Without a flagship skill-based game, Qubic risks missing adoption and engagement from gamers and investors seeking transparent, fun, and profitable on-chain experiences.

---

## paQman Solution Overview

**paQman fills this gap by offering:**

- **Competitive arcade tournaments** – Players compete in single-session skill runs.  
- **Fully on-chain reward settlement** – Smart contracts handle winnings, burns, and shareholder payouts.  
- **Shareholder IPO integration** – Token holders earn from prize pools.  
- **Deflationary mechanics** – 2% of each prize pool is burned to increase scarcity.  
- **Playful Web3 theme** – Retro arcade energy with blockchain humor.

---

## Platform Design – Game Overview

### Gameplay

- **Objective:** Navigate mazes, collect points, and avoid AI “ghosts.”  
  Featuring **CFB** as Pac-Man, this ties into Qubic’s NFT marketplace and token promotion.

- **Single-session tournaments:** Sessions are recorded off-chain, hashed, and verified on-chain.  
  **Leaderboard scoring:** The top score each epoch earns the payout.

- **Fairness:** Sessions are cryptographically verified via Qubic contracts.

### Tournament Flow

1. Players connect their Qubic wallet.  
2. Select an active tournament and stake Qubic tokens.  
3. Game session begins; transcript hashes computed in real-time.  
4. Tournament ends automatically after the timer (epoch change).  
5. Smart contracts distribute:

   - **75%** → Top players  
   - **20%** → Shareholders  
   - **3%** → Dev team  
   - **2%** → Burned

> *Eat the dots, dodge the ghosts, grab the tokens — the blockchain is watching.*

---

## Tokenomics

| **Allocation** | **Percentage** | **Notes** |
|-----------------|----------------|------------|
| Player Rewards | 75% | Distributed to top players per epoch |
| Shareholders | 20% | Paid automatically per epoch |
| Dev Team | 3% | Development & ecosystem growth |
| Burn / Liquidity | 2% | Reduces supply or supports liquidity based on active communities (QUBIC, CFB, CODED, MATILDA, GARTH) |

**Entry Fee:** 10,000 Qubic per game  
**Payout Formula:** `Total Pool × Allocation % = Recipient Share`  
**Distribution:** Instantly triggered per game settlement  
**Deflation:** Burned tokens permanently removed or added to liquidity pool

---

## Smart Contract Architecture

### Core Contracts

- **Tournament Factory:** Creates tournaments and manages participation  
- **Tournament Instance:** Handles session validation, scores, and payouts  
- **IPO Shareholder Contract:** Credits passive income to token holders  
- **Oracle/RNG Contract:** Manages AI randomness and transcript validation  
- **Burn & Treasury Contract:** Automates burns and dev allocations

---

## Ecosystem Benefits

- **Onboarding:** Gamers automatically gain Qubic wallets/tokens  
- **Sustainability:** Deflation and dividends encourage long-term holding  
- **Skill-based engagement:** Keeps players active and competitive  
- **Community growth:** Playful branding fuels social virality

---

## Roadmap

| **Phase** | **Date** | **Milestone** |
|------------|-----------|---------------|
| Litepaper | Nov 2025 | Vision & Concept |
| Whitepaper | Dec 2025 | Full technical & economic specification |
| Smart Chain Dev | Q1 2026 | Tournament, IPO, and Reward Contracts |
| Off-chain Engine Beta | Q2 2026 | Simulated gameplay and transcript testing |
| Security Audit | Q2 2026 | External smart contract audits |
| Mainnet Launch | End Q2 2026 | paQman v1 live, automated tournaments |

---

## Security & Fairness

- **Cryptographically verified sessions** – Every run hashed and submitted on-chain  
- **Oracle RNG** – Verifies AI behavior and randomness  
- **Anti-cheat measures** – Off-chain logging prevents tampering  
- **Immutable rewards** – Smart contracts enforce final payouts

---

## Risk & Disclaimer

- Qubic tokens are used only for gameplay and rewards.  
- Market values may fluctuate.  
- paQman is not a financial security offering.  
- Smart contracts will undergo audits before mainnet.

---

## Links & Contact

- **X (Twitter):** Qub’zylthar Nexus  
- **Discord:** Qub’zylthar Nexus (Qubic)  

---

*paQman – Eat rewards, not inflation.*
