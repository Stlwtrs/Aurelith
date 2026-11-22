# Aurelith, the Molten Sovereign

A five-phase bullet-hell boss fight that runs in the browser, built to resemble [AuricOS](https://github.com/Stlwtrs/AuricOS) the OS I am currently building. One HTML file, no dependencies, no assets: the pixel-art arena is drawn on a low-resolution canvas and scaled up with hard edges, and the soundtrack is synthesized live with the Web Audio API.

**Play:** open `index.html` in a desktop browser. It needs a keyboard and mouse.

**Disclaimer:** It is meant to be **EXTREMELY** difficult and is meant to be a serious challenge. If you get stressed out and frustrated while trying to beat it that's a good thing it's doing its job lol.

## Controls

| Key | Action |
|---|---|
| `A` / `D` | Move |
| `Space` | Jump; hold to fly (the wing meter refills on the ground) |
| `S` | Fall faster, drop through platforms |
| `Shift` | Dash, with a brief moment of invincibility |
| Mouse | Aim; hold left click to fire |
| `Q` | Healing draught (long cooldown) |
| `Esc` | Pause |
| `M` | Mute |

## The Fight

| Phase | Name | What happens |
|---|---|---|
| 1 | Molten Hymn | Aimed volleys, spirals, golden rain and charging dashes |
| 2 | Twin Shards | Two orbiting crown shards fire crossfire and beams; she takes reduced damage until both break |
| 3 | Gilded Deluge | She becomes untouchable and floods the arena. Survive the timer |
| 4 | Chain Serpent | A serpent of gold plates hunts you; she is shielded until it dies |
| 5 | Desperation | Her shell shatters. Sweeping beams, teleport bursts, novas |

**Difficulty:** Normal (forgiving), Expert, and Sovereign, which is tuned to be comparable to the hardest modded Terraria boss fights: five or six hits and you're done. Best times are saved in your browser.

## Soundtrack

An original symphonic metal score in D minor at 172 BPM, written as note data in the source and played by synthesized instruments: double-tracked distorted rhythm guitars, bass, drums, lead guitars with bends, vibrato and harmonies, and an orchestra of strings, spiccato runs, low brass, timpani and choir. It's written to sound like despair: falling melodies, a Phrygian E-flat chord, and phrases that end unresolved. Each phase has its own section, ending in a neoclassical guitar solo and a final chorus forced up a strained half step. Only the very last chord of the victory theme turns major.

The tempo, key and overall shape (quiet intro, swell, full-band drop, a big chorus, an intense middle, a returning chorus, quiet ending) were modeled on measurements of *credits song for my death but im the final boss* by Astron. No melodies, riffs or audio from that song are used.

## Credits

Original boss, art, writing and music. No Terraria or Calamity Mod assets, characters or music although inspired by them. Built with help from Claude (Anthropic's AI assistant).
