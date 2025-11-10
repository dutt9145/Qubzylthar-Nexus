[paQman_Lite_Paper.md](https://github.com/user-attachments/files/23459644/paQman_Lite_Paper.md)
-   ![](media/image1.png){width="1.6468613298337709in"
    height="0.5084273840769904in"}![](media/image2.png){width="1.575596019247594in"
    height="0.6324573490813649in"}![](media/image3.png){width="1.5064555993000874in"
    height="0.6313823272090988in"}![](media/image4.png){width="1.4817661854768154in"
    height="0.5927066929133858in"}**paQman: First Ever Qubic-style,
    Pacman game, featuring CFB as Pacman**

```{=html}
<!-- -->
```
-   **Lite Paper v1.0**

-   **Executive Summary:**

    -   paQman is a decentralized, on-chain arcade game designed to
        bring competitive skill-based gameplay into the Qubic ecosystem.
        Players compete in a high-score weekly tournament, using or
        paying in **Qubic tokens** as entry fees. Winners receive
        rewards automatically distributed by Qubic smart contracts,
        while a portion of every prize pool is burned or added to the
        liquidity pool of their choice, creating a deflationary token
        economy for the ecosystem.

    -   The project integrates a **shareholder IPO mechanism** that
        allows token holders to earn passive income from tournament
        activity. With **75% of rewards going to players, 20% to
        shareholders, 3% to the development team, and 2% burned or added
        to the liquidity pool**, paQman combines the nostalgia of
        classic arcade gaming with the efficiency and transparency of
        blockchain.

    -   Playful Web3 lore: *"paQman turns tokens into power pellets ---
        eat rewards, not inflation."*

-   **Problem Statement:**

> Blockchain gaming is rapidly growing, yet the Qubic ecosystem lacks a
> high-performance, skill-based arcade title. Most GameFi
> implementations are either collectible-driven or low-skill lottery
> models. This leaves a gap for:

-   Competitive, fast-paced gaming with provable fairness

-   Automated, trustless reward distribution

-   Tokenomics that reward players, investors, and ecosystem health

> Meanwhile, networks like Solana, Ethereum, and Binance Smart Chain
> host multiple arcade-style or leaderboard games. Without a flagship
> skill-based game, Qubic risks missing adoption and engagement from
> gamers and investors seeking transparent, fun, and profitable on-chain
> experiences.

## paQman Solution Overview

> paQman fills this gap by providing:

-   **Competitive arcade tournaments** -- Players compete in
    single-session skill runs.

-   **Fully on-chain reward settlement** -- Qubic smart contracts
    automatically distribute winnings, burn tokens, and credit
    shareholders.

-   **Shareholder IPO integration** -- Token holders passively earn a
    portion of all tournament prize pools.

-   **Deflationary mechanism** -- 2% of each prize pool is burned,
    reducing supply and increasing token scarcity.

-   **Lighthearted Web3 theme** -- Retro arcade flavor blended with
    blockchain humor, enhancing community engagement.

```{=html}
<!-- -->
```
-   **Platform Design -- Game Overview:**

### [4.1 Gameplay]{.underline}

-   **Objective:** Players navigate mazes, collect points, avoid AI
    "ghosts," and complete sessions in limited survival timeframes. As
    CFB being "pacman," this creates a nice gesture to the NFT
    marketplace and markets the CFB token as well.

-   **Single-session tournaments:** Each game session is over depending
    on the overall status of the game, and is recorded off-chain with a
    hashed transcript submitted on-chain.\
    **Leaderboard scoring:** The player with the highest score at the
    end of the epoch receives the reward payout automatically.

-   **Fairness:** All game sessions are cryptographically verified via
    Qubic smart contracts.

### [4.2 Tournament Flow]{.underline}

-   Players connect their Qubic wallet.

-   Select an active tournament and stake the entry fee in **Qubic
    tokens**

-   Game session begins; transcript hashes are computed in real-time.

-   Tournament ends automatically after the timer expires(epoch change)

-   Smart contracts calculate payouts and distribute rewards:

    -   **[75% to top players]{.underline}**

    -   **[20% to shareholders]{.underline}**

    -   **[3% to the Development team]{.underline}**

    -   **[2% Burned]{.underline}**

[*Playful flavor:* *"Eat the dots, dodge the ghosts, grab the tokens ---
the blockchain is watching."*]{.underline}

-   **Tokenomics**

  ----------------------- ----------------------- -----------------------
  **Allocation**          **Percentage**          **Notes**

  Player Rewards          75%                     Distributed to
                                                  top-scoring players per
                                                  epoch

  Shareholders            20%                     Paid automatically to
                                                  IPO holders per epoch

  Dev Team                3%                      Development,
                                                  maintenance, and
                                                  ecosystem growth.

  Burn or add to Qswap    2%                      Permanently reduces
  liquidity                                       supply to drive
                                                  deflation, based on the
                                                  community that plays
                                                  the most games (QUBIC,
                                                  CFB, CODED, MATILDA,
                                                  GARTH)
  ----------------------- ----------------------- -----------------------

-   Entry fees: Each game requires a fixed (10,000) Qubic buy-in.

-   Payout formula: Total Pool × Allocation % = Recipient Share

-   Distribution frequency: Each game settlement triggers instant
    distribution on-chain toward the epoch pot winnings

-   Deflation: Burned tokens are permanently removed from circulation,
    enhancing scarcity and value. Or added to the liquidity pool of the
    winning community

## Smart Contract Architecture

-   ## Contract Modules

    -   **Tournament Factory Contract** -- Creates new tournaments,
        records metadata, and manages player participation.

    -   **Tournament Instance Contract** -- Handles session validation,
        score recording, and reward distribution.\
        **IPO Shareholder Contract** -- Tracks token holder balances and
        credits passive income from tournament revenue.

    -   **Oracle / RNG Contract** -- Ensures fairness in AI "ghost"
        behaviors, seed generation, and off-chain transcript validation.

    -   **Burn & Treasury Contract** -- Manages the automatic burn and
        dev treasury allocation.

-   ## Ecosystem Benefits

    -   **Onboarding new Qubic users** -- Gamers entering paQman
        naturally acquire Qubic wallets and tokens.

    -   **Sustainable tokenomics** -- Burned tokens create scarcity;
        shareholder dividends encourage long-term holding.

    -   **Skill-based engagement** -- Competitive gameplay keeps players
        returning, increasing transaction volume and ecosystem activity.

    -   **Community-driven adoption** -- Playful Web3 theme encourages
        viral sharing and social engagement.

-   Roadmap

  ----------------------- ----------------------- -----------------------
  **Phase**               **Date**                **Milestone**

  Litepaper               November 2025           Vision and Concept

  Whitepaper              December 2025           Full technical and
                                                  economic specification

  Smart Chain Development Q1 2026                 Tournament + IPO +
                                                  Reward Contracts

  Off-chain Engine Beta   Q2 2026                 Stimulated gameplay
                                                  engine and hashed
                                                  transcript testing

  Security Audit          Q2 2026                 External audit of
                                                  contracts and reward
                                                  from the dev team

  Mainnet Launch          End of Q2 2026          paQman v1 live,
                                                  automated tournaments
                                                  and payouts
  ----------------------- ----------------------- -----------------------

-   ## Security & Fairness

    -   **Cryptographically verified sessions:** All player game
        sessions are hashed and submitted to on-chain contracts.

    -   **Oracle RNG verification:** Randomized AI patterns and seed
        generation are verified by decentralized oracles.

    -   **Anti-cheat measures:** Off-chain engine logs gameplay events,
        preventing replay attacks and tampering.\
        **Immutable rewards:** Once a tournament ends, payouts are final
        and enforced by Qubic contracts.

-   ## Risk & Disclaimer

```{=html}
<!-- -->
```
-   Qubic tokens are used for gameplay fees and reward distribution
    only.

-   Market value of tokens may fluctuate due to external factors.

-   The project does not constitute a financial security offering;
    players participate at their own discretion.

-   Smart contracts are tested but may contain bugs; audits are planned
    before mainnet launch.

## Links and Contact Information

-   Qub\'zylthar Nexus X account

-   Qub\'zylthar Nexus Discord Channel (Qubic)

