# CMAC — Cursed Fight Club
### 清迈国际咒术高专 · Official Server Ver 2.4 — JJK DLC

> *"Somewhere in Chiang Mai, cursed energy flows through every punch, every word, every bad memory. Six nations. One school. Infinite grudges."*

---

## 📖 Overview

**CMAC: Cursed Fight Club** is a browser-based tactical RPG battle game set in the **Chiang Mai Academy of Cursed Arts (CMAC)** — a chaotic international sorcery school inspired by the *Jujutsu Kaisen* universe. Build a team of cursed-energy wielders, draft your roster, and fight turn-based battles using unique skills, domains, and reminisce abilities.

The game is a **single HTML file** — no installation, no server. Just open `index.html` in your browser.

---

## 🎮 Game Modes

| Mode | Description |
|------|-------------|
| ⚔ **Versus Mode** | Draft 4 characters for your team vs. an AI-drafted enemy team, then battle turn-by-turn |
| 📖 **Story Mode** | Play through the CMAC Chronicles — Season 1 chapter by chapter |
| 📜 **World Lore** | Read full character dossiers and backstory for every fighter |

---

## ⚙️ How to Play

### Draft Phase
1. Select **4 characters** for your team from the roster.
2. The enemy AI will auto-draft 4 characters with role-balanced selection.
3. Once both teams are set, hit **START BATTLE**.

### Battle Phase
- Turns are randomised each round, interleaving player and enemy characters.
- Each character has:
  - **HP** — health pool (1000 base)
  - **Stamina (STA)** — spent to use skills; regenerates +1 each turn
  - **Trigger (TRG)** — fills as you use skills; reach 10 to unlock your Ultimate
- On your turn, choose a **Skill**, **Ultimate** (if TRG ≥ 10), **Reminisce** (once per battle), or **End Turn**.
- Select a target when prompted (enemy, ally, or auto-targeting for AOE skills).

### Status Effects
| Icon | Effect |
|------|--------|
| 💫 Stun | Character skips their turn |
| 📖 Fate | 60% chance to skip action + true damage |
| 🔒 Lock | Can only use Skill 1 |
| 💰 Bribed | Temporarily fights for the other side |
| 🥐 Shield | Absorbs one incoming magic/ranged hit |
| 🍟 Fries Mark | Target takes +20% damage per stack (max 3) |
| 🔥 DOT | Magic damage-over-time each turn |

---

## 🧑‍🤝‍🧑 Roster — All 17 Characters

### The Back Mountain Brotherhood (後山兄弟)

| Character | Role | Grade | Technique |
|-----------|------|-------|-----------|
| **Zane** — The Archivist | Buff/Support | Special | Memory Projection (回想操術) |
| **Harrison** — The Thief | ATK | 1 | Grand Larceny Theory (強奪の理) |
| **Lucas** — The Countercurse | ATK | 1 | Countercurse Chain (反撃の咒言) |
| **Vincent** — Unstoppable Force | ATK | 1 | Iron Arm Theory (剛腕の理) |
| **Feliz** — The Signal | Buff | 2 | Lonely Resonance (孤獨の共鳴) |

### Extended Roster

| Character | Role | Grade | Technique |
|-----------|------|-------|-----------|
| **Jeff** — Candy Heart | Support | 1 | Sweet Bite Healing (甘噛みの癒し) |
| **Jake** — The Shutter | ATK | 1 | Sniper's Poem (狙撃の詩) |
| **Cici** — The Proof | Control | 1 | Paradox Fist Theory (逆説の拳理) |
| **Trex** — The Middleman | Control | 2 | Commercial Soul Curse (商魂の呪) |
| **Michelle** — The House Always Wins | Control | Special | Extravagance Theory (奢靡の理) |
| **Charlotte** — The Echo | Buff/Support | 1 | Resonance Rebirth (共鳴の再誕) |
| **LJ** — The Detonator | ATK | 1 | Verbal Chain Curse (暴言の連鎖) |
| **Madame** — La Gastronomie | Support/ATK | Special | Gourmet Cursed Art (美食呪法) |
| **Woojoo** — The Tower | Control/ATK | 1 | Giant's Cage (巨人の檻) |
| **Chogun** — The Paratrooper | ATK | 1 | Airborne Warfare (空降戦法) |
| **Ichigatsu** — The Formula | Control | Special | Analytic Formula (解析構式) |
| **Lin Zhaofu** — The Loop | Control | Special | Spacetime Reversal (時空逆転) |

---

## 🌟 Notable Synergies

- **Charlotte + Zane** — Passive bond: both gain +20% max HP. Charlotte's `Double Spin` ultimate deals increased damage when Zane is on the same team.
- **Cici + Michelle** — Probability manipulation collaboration; their kits complement each other perfectly.
- **LJ + Cici + Charlotte (LCC Formation)** — Harmonic resonance between their three techniques. Responsible for the absence of Training Hall B's east wall.

---

## 🃏 Skill System

Each character has:
- **3 Skills** — increasing in power and stamina cost (1–4 STA). Using skills fills the Trigger gauge.
- **1 Ultimate (Domain/Spirit)** — unleashed at TRG ≥ 10.
- **1–2 Reminisce Abilities** — free-use, one-time-per-battle abilities rooted in each character's backstory.

### Skill Types
| Type | Description |
|------|-------------|
| `physical` | Melee/physical damage |
| `magic` | Cursed energy damage (blocked by Croissant Shield) |
| `heal` | Restores HP to allies |
| `buff` | Positive effects on self or allies |
| `control` | Debuffs or status effects on enemies |
| `mixed` | Combines multiple damage types |

---

## 🏫 Lore Summary

### The Academy
Hidden in Chiang Mai's old city, CMAC was founded as a joint initiative between the Japanese Jujutsu Council and the Southeast Asian Cursed Spirit Bureau. It quickly became a refuge for students too dangerous, too unruly, or too strange for their home institutions. Director Zhang Wei describes his job as *"containing seventeen separate natural disasters simultaneously."*

### The Back Mountain (後山)
Behind the main campus lies an untamed jungle ridge — no faculty, no rules. The original five (Zane, Harrison, Lucas, Vincent, Feliz) were all expelled from the dorms in the same week and ended up here. By the time their dorm privileges were reinstated, none of them wanted to go back.

---

## 🛠️ Technical Details

- **Single-file app** — all logic in `index.html` (HTML + CSS + vanilla JS)
- **No dependencies** — no frameworks, no build step, no server
- **Fonts** — Bebas Neue, Space Mono, Noto Sans JP (Google Fonts CDN)
- **Browser** — any modern browser

---

## 🚀 Getting Started

```bash
git clone https://github.com/Terrarioz/cmis.git
open index.html
