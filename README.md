# Poké Tekken

A colorful, **tablet-friendly** Tekken-style fighting game — with Pokémon fighters instead of the usual cast.

**Play now:** [https://luvbuniz.github.io/poke-tek/](https://luvbuniz.github.io/poke-tek/)

---

## About

Poké Tekken is a fan-made browser fighter built as a single HTML page. Pick a Pokémon, battle best-of-3 rounds, fill your super meter, and unleash specials. Big on-screen buttons and swipe controls make it easy to play on phones and tablets.

This is an unofficial fan project for fun — not affiliated with Nintendo, Game Freak, Creatures, Bandai Namco, or The Pokémon Company.

## Features

- 8 playable fighters (Pikachu, Charizard, Blastoise, Venusaur, Gengar, Lucario, Machamp, Eevee)
- Punch, kick, special, super, block, and jump
- Health bars, super meter, rounds, and timer
- vs CPU or local 2-player
- Built-in sound effects and light music (Web Audio)
- Large touch controls for tablets

## How to play

1. Open the live link above (or open `index.html` locally).
2. Choose **vs CPU** or **2 Players**.
3. Pick your fighter(s) and tap **Fight!**
4. Use the big buttons (or keyboard) to battle.

| Action | Touch | Player 1 keys | Player 2 keys |
|--------|-------|---------------|---------------|
| Move | ◀ ▶ buttons / swipe | A D | ← → |
| Jump | ▲ / swipe up | W | ↑ |
| Punch | 👊 | F | K |
| Kick | 🦵 | G | L |
| Special | ✨ | R | O |
| Super | 💥 | T | P |
| Block | 🛡 | S | ↓ |

Land hits to fill the orange super bar, then fire **Special** or **Super** moves.

## Run locally

```bash
git clone https://github.com/luvbuniz/poke-tek.git
cd poke-tek
# open index.html in a browser
```

## Tech

- Pure HTML, CSS, and JavaScript (no build step)
- Canvas arena rendering
- Web Audio API for SFX and music
- Responsive layout for phones, tablets, and desktops

## License

Free to play and share. Fan project — Pokémon and Tekken names/characters belong to their respective owners.