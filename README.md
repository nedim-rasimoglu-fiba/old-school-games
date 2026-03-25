# Old School Games

Single HTML files — each one a fully playable recreation of a classic game from the golden age of arcade and home console gaming. No dependencies, no installs. Just open in a browser and play.

---

## 🎮 Games

### [Tank 99 / Battle City](./tank99.html)

**Play it:** [nedim-rasimoglu-fiba.github.io/old-school-games/tank99.html](https://nedim-rasimoglu-fiba.github.io/old-school-games/tank99.html)

#### History

Tank 99 traces its roots to **Tank**, a 1974 arcade game developed by Kee Games (a subsidiary of Atari). It was one of the earliest games to use ROM chips for storing sprite graphics and introduced the concept of tank-vs-tank combat on a grid-based battlefield. The game was a commercial hit in arcades and laid the groundwork for an entire genre.

The concept was refined and popularized by **Battle City**, released by **Namco in 1985** for the Nintendo Famicom (NES). Battle City became one of the most beloved games on the platform, particularly in Japan and across Asia and Eastern Europe, where it achieved near-legendary status. The premise was simple and addictive: pilot a tank, defend your Eagle base at the bottom of the map, and destroy all enemy tanks before they reach and destroy it. Levels featured destructible brick walls, indestructible steel barriers, forests, and water — each element adding strategic depth to what appeared at first glance to be a straightforward shooter.

A variation called **Tank 1990** (also known as "90 Tank" or "Battle City 90") became especially iconic in Eastern European and former Soviet markets, distributed on Famicom clone cartridges. It is still fondly remembered by an entire generation as one of the defining gaming experiences of their childhood.

#### What This Recreation Brings

This is a faithful single-file HTML5 + Canvas recreation of the Battle City / Tank 99 experience, built from scratch with modern web technologies. It captures the spirit of the original while adding quality-of-life features:

- **Grid-based movement** — tanks move cell-to-cell on a 13×13 grid with smooth interpolation, just like the original
- **Destructible terrain** — brick walls crumble under fire; steel walls hold firm
- **Enemy AI** — enemies patrol, hunt, and fire with configurable speed and aggression
- **Power-ups** — collectible stars, shields, timers, and more
- **Spawn cooldown** — enemies flash and are invulnerable briefly after spawning, true to the original feel
- **God Mode** — toggle invincibility on the fly, with the Eagle automatically fortified by indestructible steel walls
- **Fully configurable** — adjust player speed, enemy speed, bullet speed, and fire rates via sliders before or during gameplay
- **Passive/no-aggro enemy toggle** — turn off enemy shooting or movement independently for testing and fun
- **2-Player local & multiplayer** — WebRTC peer-to-peer multiplayer with host/join via copy-paste signaling (no server required)
- **Zero dependencies** — one `.html` file, open in any modern browser

#### Controls

| Action | Key |
|---|---|
| Move | Arrow Keys / WASD |
| Fire | Space |
| Toggle Invincibility | I |
| Start Game | Enter |

---

*More classic games coming soon.*
