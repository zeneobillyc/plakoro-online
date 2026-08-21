# Plakoro Online - PvE Dice Pokémon Game

A web-based PvE dice Pokémon game based on the official Plakoro rules.

## Features

- **12 Pokémon** from official data (all 120 HP)
- **Energy Dice System**: 3 dice × 6 faces (4 single + 2 duo, same element allowed)
- **Character Die**: 6 faces with 6 orientations (standing, upside-down, etc.)
- **Battle System**: Turn-based with energy dice rolling
- **Sudden Death**: After 30 turns, increasing damage each turn
- **Cooldown System**: Can't use same move twice in a row
- **Weakness System**: +20 damage for hitting weakness

## Local Development

```bash
npm install
npm start
# Open http://localhost:8080
```

## Deployment

Deploy to Vercel:
1. Connect GitHub repo to Vercel
2. Deploy - no config changes needed

## Game Rules

1. Select Pokémon → Choose 4 moves → Configure energy dice (3 dice × 6 faces)
4. Battle: Select move → Roll energy dice → Check cost → Roll character die → Apply damage
5. First to 0 HP loses
6. After 30 turns: Sudden Death (increasing damage each turn)

## Tech Stack

- Vanilla HTML/CSS/JS (single file)
- Node.js server for static hosting
- Vercel deployment ready
