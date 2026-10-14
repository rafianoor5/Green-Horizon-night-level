# 🌱 Green Horizon

A side-scrolling browser game where you play a tiny sprout spirit. Collect glowing seeds, dodge angry smog monsters, and watch a polluted world turn green again: the sky clears, the sun rises, and dead trees grow back to life.

Built with plain HTML, CSS and JavaScript (HTML5 Canvas). No libraries needed.

**Play it online:** _add your GitHub Pages link here once it is deployed_

## Screenshots

**Start screen**

![Start screen](screenshots/menu.png)

**Gameplay: the world starts grey and smoggy**

![Gameplay](screenshots/gameplay.png)

**Game over: the more seeds you plant, the greener the world gets**

![Game over screen](screenshots/game-over.png)

<!-- Add a screenshot of the night level and power-ups, save it as screenshots/night.png, then replace this line with: ![Night level](screenshots/night.png) -->

## How to play

| Control | Action |
| --- | --- |
| `Space` / `↑` / `W` / tap | Jump (you can double-jump) |
| `P` | Pause / resume |
| `M` | Mute / unmute sound |

- Collect **seeds** to make the horizon greener.
- Avoid the **smog monsters**. You have 3 hearts.
- Pick up a **blue shield bubble** for 5 seconds of protection. Smog you touch is destroyed.
- Pick up a **red magnet** to pull nearby seeds toward you for 6 seconds.
- After **50 seeds** night falls, with stars, a moon and fireflies. At 100 seeds the day returns, and it keeps alternating.
- The game gets faster the more seeds you collect. Your best score is saved in your browser.

## How to run

1. Download or clone this repo.
2. Open `index.html` in your browser.

That's it. You can also use the Live Server extension in VS Code.

## Features

- Parallax hills, clouds and a rising sun
- World that changes from smoggy to green as you collect seeds
- Day and night cycle with stars, moon and fireflies
- Shield and magnet power-ups, each with a timer
- Sound effects made with the Web Audio API (jump, seed, hit, game over)
- Pause and mute controls
- Squash-and-stretch character animation and particle effects
- Double jump, lives, speed increase and a saved high score

## Update log

- **Week 1:** Started the project: canvas game, parallax world, seeds, smog, README.
- **Week 2:** Sound effects, pause and mute, shield power-up.
- **Week 3:** Night level and magnet power-up.

## Ideas I plan to add

- Power-up timer bars and best score on screen
- New smog enemy types
- Mobile-friendly controls
- Boss fight and new biomes

## Credits

The starting version of this game and several features (sound effects, pause and mute, the shield and magnet power-ups, and the night level) were written with help from Claude (an AI assistant). I read through the code, tested it and made changes to it in VS Code. _Edit this line to list the specific parts you wrote or changed yourself._
