# 🚀 ARES-1 Colony Command

> A space colony survival simulation set on Mars. Manage resources, make critical decisions, and keep your crew alive for 100 Martian sols.

![Mars Colony](https://img.shields.io/badge/platform-browser-blue?style=flat-square)
![Language](https://img.shields.io/badge/built%20with-HTML%20%2F%20CSS%20%2F%20JS-orange?style=flat-square)
![Challenge](https://img.shields.io/badge/Flavortown-Challenger%20Center-red?style=flat-square)

---

## 🌑 About

**ARES-1 Colony Command** is a browser-based survival management game where you play as the commander of humanity's first permanent Mars colony. Every sol (Martian day), your colony consumes oxygen, food, water, and power. Random crisis events hit — dust storms, equipment failures, crew conflicts, oxygen leaks — and you must make tough decisions to keep everyone alive.

Survive all **100 sols** to establish the colony. Lose a resource or your entire crew and the mission fails.

---

## 🎮 How to Play

1. **Open `mars-colony.html`** in any modern browser — no install needed
2. **Read the event cards** at the bottom of the screen each sol
3. **Choose a response** — each choice has tradeoffs (saving power might hurt morale, etc.)
4. **Click "NEXT SOL"** to advance the day and trigger passive resource drain
5. **Survive 100 sols** to win

### Win Condition
Reach **Sol 100** with at least one crew member alive.

### Lose Conditions
- All crew members die
- Oxygen depletes to zero
- Both food and morale hit zero simultaneously

---

## ⚙️ Systems

| System | Description |
|--------|-------------|
| 🫁 Oxygen | Consumed by crew each sol. Leak events drain it fast. |
| 🌾 Food | Greenhouse produces it; contamination and storms threaten it. |
| 💧 Water | Extracted by the ice drill. Equipment failure = crisis. |
| ⚡ Power | Solar arrays. Dust storms cut output significantly. |
| 💚 Morale | Low morale leads to poor crew performance and health decline. |

---

## 👨‍🚀 Crew

Your colony starts with 5 specialists:
- **CDR Chen** — Commander
- **Dr. Patel** — Scientist
- **Eng. Mars** — Engineer
- **Med. Okafor** — Medic
- **Plt. Novak** — Pilot

Each crew member has individual health. Resource shortages damage all living crew. A crew member at 0 health dies permanently.

---

## 🏗️ Colony Buildings

| Building | Function |
|----------|----------|
| 🏠 Habitat | Crew living quarters — central to morale |
| ☀️ Solar Array | Primary power source |
| 🌱 Greenhouse | Food production |
| 💧 Ice Drill | Water extraction |
| 📡 Comms | Earth communications |
| 🔬 Lab | Science & research score bonuses |

---

## 🎲 Events

10 unique crisis events with multiple response choices, including:

- **Solar Flare** — shelter the crew or risk radiation damage
- **Dust Storm** — prep batteries or launch a research probe
- **Oxygen Leak** — seal the breach or send an EVA team
- **Fungal Contamination** — quarantine the greenhouse or study the organism
- **Equipment Failure** — emergency repair or ration resources
- **Crew Conflict** — mandatory rest, extra rations, or ignore it
- **Resupply Pod** — choose what Earth sends you
- **Subsurface Discovery** — drill for samples or log and continue
- **Power Surge** — bypass the grid or shut down systems
- **Water Contamination** — run the purifier or use emergency reserves

---

## 🆕 New Features

- **⬆️ Upgrades System** — Spend mission score to permanently upgrade 8 colony buildings with resource bonuses each sol
- **🎮 Difficulty Modes** — Choose Easy, Normal, or Hard before each mission with different drain rates and starting resources

---

## 🛠️ Tech Stack

- Pure **HTML / CSS / JavaScript** — zero dependencies, zero frameworks
- Retro **CRT mission control** aesthetic with scanline overlay
- **CSS animations** for floating buildings, shimmer bars, dust storms
- Google Fonts: `Orbitron`, `Share Tech Mono`, `VT323`

---

## 🚀 Running Locally

Just open the file — no server needed:

```bash
# Clone the repo
git clone https://github.com/lambo7/mars-colony-game_hackclub.git

# Open in browser
open mars-colony.html
# or double-click the file
```

---

## 🌐 Play Online

Hosted on GitHub Pages: `https://lambo7.github.io/mars-colony-game_hackclub/mars-colony.html`

---

## 📋 Submitted To

[Flavortown — Challenger Center Sidequest](https://flavortown.hackclub.com/sidequests/challenger)
Build a space-themed project for the Challenger Center space challenge.

---

## 📄 License

MIT — free to use, modify, and share.
