# 🐉 Dragon Prime: Fusion TCG

[![License: MIT](https://img.shields.io/badge/License-MIT-amber.svg)](LICENSE)
[![Blockchain: WAX](https://img.shields.io/badge/Blockchain-WAX-orange.svg)](https://wax.io)
[![Hosting: GitHub Pages](https://img.shields.io/badge/Hosting-GitHub%20Pages-blue.svg)](https://pages.github.com)

> **"Gather Essence. Fuse Eggs. Claim Prime Glory."**

Welcome to the official repository and handbook for **Dragon Prime: Fusion TCG**, a Web3 Trading Card Game built entirely on the **WAX Blockchain** leveraging **AtomicHub** and **NeftyBlocks** without a custom database or game server.

---

## 📜 Table of Contents
- [Realm Lore & Origins](#-realm-lore--origins)
- [Game Loop & Mechanics](#-game-loop--mechanics)
- [Economic Valuation Matrix](#-economic-valuation-matrix)
- [Collection Assets & Templates](#-collection-assets--templates)
- [Getting Started & Setup Guide](#-getting-started--setup-guide)
- [Deployment via GitHub Pages](#-deployment-via-github-pages)
- [License](#-license)

---

## 🌌 Realm Lore & Origins

In the primordial era of the WAX realm, raw elemental energy condensed into crystalline shards known as **Mysterious Dragon Essence**. Alchemists discovered that when this essence is subjected to extreme heat in the fusion crucible, it crystallizes into metallic containment shells—the legendary **Dragon Eggs**.

Forged through meticulous tier-based blending, these eggs hatch into formidable dragon wyrms. Each progressive tier—from the steadfast Bronze to the mythic Platinum apex—requires smart resource management and strategic trading from tamers across the blockchain.

---

## 🔄 Game Loop & Mechanics

1. **Acquire Essence:** Purchase *Mysterious Dragon Essence* directly via AtomicHub Drops for **0.05 WAX**.
2. **RNG Unboxing:** Burn **3x Mysterious Dragon Essence** in NeftyBlocks to roll for random metallic eggs.
3. **Tier Fusions:** Combine **3x matching Metallic Eggs** or creatures in NeftyBlocks blends to upgrade your portfolio and summon powerful dragon combatants.
4. **Secondary Trading:** Trade duplicates and rare pulls on the AtomicHub Marketplace, earning creator royalties on every transaction.

---

## 📊 Economic Valuation Matrix

Priced for maximum liquidity, high trading volume, and player accessibility:

| Asset Name | Classification | Scaling Rule | Target Value (WAX) |
| :--- | :--- | :--- | :--- |
| **🧪 Mysterious Dragon Essence** | Essence | Base Unit (Primary Drop) | **0.05 WAX** |
| **🥉 Bronze Dragon Egg** | Egg (Common) | 3x Essence + RNG Markup | **0.20 WAX** |
| **🥈 Silver Dragon Egg** | Egg (Uncommon) | 3x Bronze Eggs + Markup | **0.75 WAX** |
| **🥇 Gold Dragon Egg** | Egg (Rare) | 3x Silver Eggs + Markup | **3.00 WAX** |
| **⚪ Platinum Dragon Egg** | Egg (Legendary) | 3x Gold Eggs + Scarcity (Cap: 100) | **12.00 WAX** |
| **🐉 Bronze Dragon** | Creature | Slightly > 3x Bronze Eggs | **0.70 WAX** |
| **🐉 Silver Dragon** | Creature | Slightly > 3x Silver Eggs | **2.50 WAX** |
| **🐉 Gold Dragon** | Creature | Slightly > 3x Gold Eggs | **10.00 WAX** |
| **👑 Platinum Dragon** | Apex Creature | Slightly > 3x Platinum Eggs | **40.00 WAX** |

---

## 🃏 Collection Assets & Templates

Managed inside the `dragonprime1` collection under the `dragonsandeggs` schema:

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

## 🛠️ Getting Started & Setup Guide

1. **AtomicHub Creator Setup:** Create your collection (`dragonprime1`), schema (`dragonsandeggs`), and asset templates.
2. **Primary Drops:** Set up a drop for *Mysterious Dragon Essence* at **0.05 WAX**.
3. **NeftyBlocks Blends:** Configure your unboxing RNG blend and tier upgrade blends.
4. **Deploy Handbook:** Push your `index.html` (this repository) to GitHub Pages so players can read the lore and pricing matrix.

---

## 🌐 Deployment via GitHub Pages

1. Go to your GitHub repository **Settings** $\rightarrow$ **Pages**.
2. Set **Branch** to `main` and folder to `/ (root)`.
3. Click **Save** to publish your lore guide live.

---

## 📜 License

Distributed under the MIT License. See [`LICENSE`](LICENSE) for more information.
