# 🐉 Dragon Prime: Fusion TCG

[![License: MIT](https://img.shields.io/badge/License-MIT-amber.svg)](LICENSE)
[![Blockchain: WAX](https://img.shields.io/badge/Blockchain-WAX-orange.svg)](https://wax.io)
[![Hosting: GitHub Pages](https://img.shields.io/badge/Hosting-GitHub%20Pages-blue.svg)](https://pages.github.com)

> **"Gather Essence. Fuse Eggs. Claim Prime Glory."**

Welcome to the official web application and alchemy simulator for **Dragon Prime: Fusion TCG**, a Web3 Trading Card Game built on the **WAX Blockchain**. Burn Mysterious Dragon Essence, hatch ancient metallic eggs, and fuse matching tiers to summon legendary dragon wyrms!

---

## 📜 Table of Contents
- [Overview & Lore](#-overview--lore)
- [Game Loop & Mechanics](#-game-loop--mechanics)
- [Probability Weights & Math](#-probability-weights--math)
- [Collection Assets](#-collection-assets)
- [Web Application Features](#-web-application-features)
- [Getting Started & Local Setup](#-getting-started--local-setup)
- [Deployment](#-deployment)
- [License](#-license)

---

## 🌌 Overview & Lore

In the primordial realm of **Dragon Prime**, ancient draconic power slumbers inside crystallised **Mysterious Dragon Essence**. Alchemists and dragon tamers across the WAX blockchain collect and burn this Essence in the elemental crucible to forge metallic eggs. Through sequential tier fusions—combining bronze, silver, and gold lineages—players awaken fierce dragon wyrms culminating in the mythical **Platinum Dragon**.

---

## 🔄 Game Loop & Mechanics

1. **Essence Acquisition:** Acquire *Mysterious Dragon Essence* (via primary WAX drops or the dApp web store for 3 WAXP).
2. **RNG Egg Unboxing:** Burn **3x Mysterious Dragon Essence** to roll for a random Metallic Egg drop.
3. **Metallic Egg Fusion:** Combine **3x matching Metallic Eggs** to upgrade to higher-tier eggs or hatch combat-ready Dragon Wyrms.
4. **On-Chain Vaulting:** Trade, collect, or stake your hatched Dragons and Platinum Eggs on AtomicHub.

---

## 📊 Probability Weights & Math

### 1. Essence Unboxing (Burn 3x Essence)
| Result Outcome | Rarity Tier | Drop Chance (%) |
| :--- | :--- | :--- |
| **Bronze Dragon Egg** | Common | **75.0%** |
| **Silver Dragon Egg** | Uncommon | **19.5%** |
| **Gold Dragon Egg** | Rare | **5.0%** |
| **Platinum Dragon Egg** | Legendary | **0.5%** |

### 2. Egg Fusion & Hatching Recipes
| Input Recipe | Possible Outcomes & Drop Chances |
| :--- | :--- |
| **Burn 3x Bronze Eggs** | **65%** Silver Egg \| **30%** Bronze Dragon \| **5%** Gold Egg |
| **Burn 3x Silver Eggs** | **60%** Gold Egg \| **35%** Silver Dragon \| **5%** Platinum Egg |
| **Burn 3x Gold Eggs** | **75%** Gold Dragon \| **15%** Platinum Egg \| **10%** Platinum Dragon |

---

## 🃏 Collection Assets

The `dragonprime1` collection features 9 official asset templates under the `dragonsandeggs` schema:

| Asset Name | Category | Rarity | Supply Cap | Burnable |
| :--- | :--- | :--- | :--- | :--- |
| **Mysterious Dragon Essence** | Essence | Common | Infinite | Yes |
| **Bronze Dragon Egg** | Egg | Common | Infinite | Yes |
| **Silver Dragon Egg** | Egg | Uncommon | Infinite | Yes |
| **Gold Dragon Egg** | Egg | Rare | Infinite | Yes |
| **Platinum Dragon Egg** | Egg | Legendary | **Capped (100)** | Yes |
| **Bronze Dragon** | Creature | Common | Dynamic | Yes |
| **Silver Dragon** | Creature | Uncommon | Dynamic | Yes |
| **Gold Dragon** | Creature | Rare | Dynamic | Yes |
| **Platinum Dragon** | Creature | Legendary | Dynamic | Yes |

---

## ✨ Web Application Features

- **Multi-Wallet WAX Authentication:** Seamlessly log in using **MyCloud Wallet** (`waxjs`) or **Anchor Wallet**.
- **On-Chain WAX Purchases:** Directly buy *Mysterious Dragon Essence* for 3 WAXP token transfers.
- **Interactive Alchemy Simulator:** Test unboxing rolls and fusion blends in real-time with an activity terminal log.
- **Card Compendium:** View full card artwork, stats, rarity classifications, and lore.
- **Zero Build Tools Required:** Pure, lightweight single-file HTML5, Tailwind CSS (via CDN), and JavaScript.

---

## 🛠️ Getting Started & Local Setup

### Prerequisites
- Any modern web browser (Chrome, Brave, Firefox, Edge).
- A WAX Cloud Wallet or Anchor Wallet for on-chain testing.

### Running Locally
1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git](https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git)
