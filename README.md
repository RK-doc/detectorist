# Detectorist

A short 2D metal-detecting game about the quiet joys of sweeping a Bohemian meadow — and the very loud consequences of being caught doing it.

**[Play →](https://rk-doc.github.io/detectorist/)**

## The game

You have a metal detector, a pouch, and a field that isn't yours. Sweep it, read the ground by ear, and fill the pouch with lost coins, brooches, and the occasional Roman surprise. Then slip out through the gate before Farmer Kubát catches you knee-deep in his soil.

Two loops sit on top of each other. The **calm loop** is walking, sweeping, listening for a rise in the detector tone, pinpointing, and digging. The **tense loop** is Kubát's vision cone drifting across the field on his patrol — get seen digging and his suspicion climbs fast. Once it maxes out, he shouts and charges with a pitchfork. You can outrun him, but stamina runs out in about three seconds.

## Controls

| Key | Action |
|---|---|
| `W A S D` / arrow keys | Walk |
| `Shift` | Sprint (drains stamina) |
| `Space` | Pinpoint a signal, then press again to dig |

Head south through the gate opening in the hedge to bank your finds.

## The catalogue

Twelve possible finds, weighted so junk is common and rarities are lucky days.

| Find | Value | Notes |
|---|---:|---|
| Roman fibula | 240 Kč | Verdigris on bronze. A very good day. |
| Silver brakteát | 165 Kč | Přemyslid, stamped on one side only |
| Silver kreuzer | 95 Kč | Austrian Empire, Franz I |
| Bronze belt buckle | 48 Kč | The pin long gone |
| Brass thimble | 22 Kč | Dented on one side |
| Livery button | 18 Kč | A little brass sun |
| Musket ball | 10 Kč | Lead, ~18th century |
| Copper heller | 4 Kč | Barely worth the sweat |
| Rusty nail | — | Iron. Should have discriminated. |
| Foil scrap | — | The bane of it all |
| Shotgun cartridge | — | Kubát has been here recently |
| Ring pull | — | A modern beer can's calling card |

## Playing locally

The game is a single self-contained HTML file. Clone the repo and open `index.html` in any modern browser — no build step, no server, no dependencies.

```bash
git clone git@github.com:RK-doc/detectorist.git
cd detectorist
# then open index.html in a browser
```

The only external resource is Google Fonts (Fraunces + Inter). Everything else — canvas rendering, WebAudio detector tones, farmer AI — is in the one file.

## Hosting on GitHub Pages

In the repo Settings → Pages, deploy from `main` branch, root folder. The game will be live at `https://rk-doc.github.io/detectorist/` within a minute or two.

## License

MIT — see [LICENSE](LICENSE).
