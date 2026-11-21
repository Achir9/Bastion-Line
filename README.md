# Bastion Lines

Bastion Lines is a single-player tower defense game built with HTML, CSS, and JavaScript. Deploy troops, traps, and spells across two lanes to break the computer opponent's defenses.

## Play locally

Open `index.html` in a modern browser. The game has no external dependencies and runs offline.

## How to play

1. Select one of the ten cards and choose **Deploy left** or **Deploy right**. Your first deployment starts the match.
2. Use regenerating energy to deploy more cards. Each card shows its energy cost and tactical role.
3. Break a lane tower to expose the enemy core. Destroy the core to win. At 2:30, the side with more core health wins. Equal health is a draw.
4. Use **New match** to restart, **Sound on** to mute, or **Export HTML** to download a fresh copy.

## Card roster

| Card | Energy | Role |
| --- | ---: | --- |
| Shieldguard | 3 | High-health frontline |
| Longbow | 3 | Ranged anti-air |
| Twin Runners | 2 | Fast pair of attackers |
| Mortar Crew | 4 | Ground splash damage |
| Sky Wasp | 3 | Flying attacker |
| Breach Ram | 4 | Structure attacker |
| Pikewarden | 3 | Anti-air and ram counter |
| Field Medic | 3 | Heals friendly troops |
| Arc Mine | 2 | Ground trap |
| Ember Volley | 4 | Lane-wide strike |

## Tools

- HTML and CSS structure and style the game interface.
- JavaScript runs combat, energy, the computer opponent, and the export.
- Canvas draws the pixel-art battlefield and troop sprites.
- Web Audio synthesizes card and combat sounds.
- ChatGPT assisted with implementation, visual revisions, and testing.

## Publish on GitHub Pages

Upload `index.html`, `README.md`, `LICENSE`, and `.nojekyll` to the root of a public repository. In **Settings → Pages**, choose **Deploy from a branch**, then **main** and **/(root)**. Save the settings and use the URL shown on the Pages settings screen after deployment.

## License

MIT. See [LICENSE](LICENSE).
