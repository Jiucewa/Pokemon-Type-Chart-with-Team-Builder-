# Pokémon Type Chart with Team Builder

> A fully interactive, zero-dependency web app to master type matchups and build balanced teams.

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://jiucewa.github.io/Pokemon-Type-Chart-with-Team-Builder-/)
[![Made with](https://img.shields.io/badge/made%20with-HTML%2FCSS%2FJS-blue)](https://github.com/Jiucewa/Pokemon-Type-Chart-with-Team-Builder-)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**Live Demo:** https://jiucewa.github.io/Pokemon-Type-Chart-with-Team-Builder-/

---

## Overview

Built as a single HTML file with no external libraries, this tool combines two essential competitive Pokémon utilities into one polished interface. Designed for fast lookups during team building and battle prep.

## Features

### 1. Complete 18×18 Type Chart
- Visual grid for all attacking vs defending types
- Color-coded effectiveness:
    - 🟢 Green = Super effective (2×)
    - 🟠 Orange = Not very effective (0.5×)
    - ⚫ Gray = No effect (0×)
    - Includes 4× and 0.25× indicators
- Hover to highlight row/column
- Tooltips with plain English explanations
- Fully keyboard-navigable

### 2. Smart Team Builder
- Configure up to 6 Pokémon with primary + secondary types
- Real-time defensive profile calculation
- Auto-aggregates weaknesses, resistances, and immunities across your whole team
- **Coverage warnings** — e.g., "Your team has 3 Pokémon weak to Ground!"
- Helps spot shared vulnerabilities before you battle

## Screenshots

<img width="1170" height="932" alt="image" src="https://github.com/user-attachments/assets/69f5158f-015a-4d7c-8098-e63f790f7974" />
<img width="1170" height="804" alt="image" src="https://github.com/user-attachments/assets/7fb4baba-85bd-421e-8720-b6fb38e19d90" />

## Tech Stack

- **HTML5** — semantic structure
- **CSS3** — Grid, Flexbox, custom properties for theming
- **Vanilla JavaScript** — no frameworks, no APIs, works offline

## How to Run

1. Clone the repo
   ```bash
   git clone https://github.com/Jiucewa/Pokemon-Type-Chart-with-Team-Builder-.git

