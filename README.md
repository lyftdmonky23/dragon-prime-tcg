# Dragon Prime: Fusion TCG — Economy & Technical Specification

Welcome to the official repository for **Dragon Prime: Fusion TCG**, a deflationary, burn-to-mint Trading Card Game built on the WAX blockchain using AtomicAssets.

---

## 📌 Ecosystem Parameters

| Parameter | Value |
| :--- | :--- |
| **WAX Collection** | `dragonprime1` |
| **Schema Name** | `dragoneggs` |
| **Secondary Market Royalties** | `3.5%` (Locked) |
| **Drop & Blending Platform** | MintyBlocks / NeftyFusion Protocol |
| **Base Reagent Cost** | `2.00 WAX` per Mysterious Dragon Essence |

---

## 🔮 Schema Attributes (Static & Immutable)

All NFTs in the `dragoneggs` schema utilize the following standardized immutable attributes:

* `name` *(String)* — Card Name
* `img` *(String)* — IPFS Artwork Hash
* `category` *(String)* — Card Category (`Essence`, `Egg`, `Dragon`)
* `tier` *(String)* — Tier Grade (`Base`, `Incubation`, `Bronze`, `Silver`, `Gold`, `Platinum`)
* `description` *(String)* — Lore and mechanics description text

---

## ⚔️ Evolution & Synthesis Flow

The game economy is powered by a progressive burn mechanism. Players purchase base reagents and blend them up through six sequential tiers:
