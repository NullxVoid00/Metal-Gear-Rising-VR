# Metal Gear Rising: Revengeance VR

**In development · No public mod release yet · PC VR**

An experimental **Metal Gear Rising: Revengeance** VR project exploring how its cutting, Blade Mode and core-grab mechanics could translate to tracked controllers. The current work has two distinct parts: a campaign-screen companion and a standalone VR combat test arena.

[Future downloads & release notes](https://github.com/NullxVoid00/Metal-Gear-Rising-VR/releases) · [Report an issue](https://github.com/NullxVoid00/Metal-Gear-Rising-VR/issues) · [Abyssal Light Games](https://nullxvoid00.github.io/)

## Release status

This is the public project and future release hub. **There is no downloadable mod build published here yet.** The repository currently contains project information and release documentation; GitHub's **Code → Download ZIP** downloads those documents, not an installable mod.

When a build is ready, its installer or archive, supported game version, controls, installation steps and known issues will be published under [Releases](https://github.com/NullxVoid00/Metal-Gear-Rising-VR/releases). Use **Watch → Custom → Releases** to follow future downloads. No release date is announced.

## What is being developed

| Area | Current development work |
| --- | --- |
| **Campaign-screen companion** | The actual game appears on an adjustable flat screen in VR. Touch controls map to the original game controller; the local notes record user-confirmed working controls. |
| **Standalone VR arena** | A separate stereo arena contains a tracked katana/hand, deliberate sword gestures, slow-motion experiments, core exposure/grab/pull and haptics. |
| **Renderer research** | Game-camera and Direct3D 9 capture work exists, but the experimental campaign stereo replay is not a usable conversion. |

## Target setup

- **Game / platform:** Windows Steam edition of Metal Gear Rising: Revengeance. The original game is a 32-bit Direct3D 9 application; this project uses a custom companion and renderer investigation.
- **VR setup:** Quest 3 with Touch controllers through Virtual Desktop / VDXR is the documented development setup.
- **Game ownership:** Supply your own required game files. No commercial game data, ROM, disc image, BIOS or save data is provided by this repository.

## Development controls

These are the current documented starting mappings, not a finalized release manual. The instructions shipped with a future build take precedence.

| Input | Action |
| --- | --- |
| Campaign: left / right stick | Original movement / camera or Blade Mode aim |
| Campaign: right trigger / right grip | Light / heavy attack with default game bindings |
| Campaign: left trigger / left grip | Blade Mode / Ninja Run with default bindings |
| Campaign: left stick click | Recenter the spatial screen |
| Arena: tracked right hand / left grip | Katana gesture / exposed core grab |

## Known limitations and next work

- The campaign image is flat. Native stereo depth and motion-controlled campaign sword combat are not implemented.
- The standalone arena uses placeholder geometry and is not the original game campaign.
- Campaign damage, enemy behavior, parrying, bosses and movement have not been integrated with the arena mechanics.
- Experimental stereo replay has failed visual testing and must not be presented as completed VR gameplay.

Builds, automated checks and desktop captures do not by themselves establish headset comfort, full-game compatibility or a release-ready experience. The descriptions above distinguish implemented development work from unfinished work.

## Installing a future release

Installation instructions will accompany each published build. Until then, there is no supported public installation procedure or binary to download from this repository. Game-version and runtime requirements may change as development continues.

## Feedback

Use [Issues](https://github.com/NullxVoid00/Metal-Gear-Rising-VR/issues) for questions or reports. For a future build, include its version, game version, headset/runtime and clear reproduction steps. Remove personal paths and private information from logs, and do not attach game files or saves.

## Credits

VR project by **NullxVoid / Abyssal Light Games**. This is an unofficial fan project and is not affiliated with or endorsed by the original game's creators or publishers.

Original games, names and assets belong to their respective owners. Upstream code and dependencies retain their own licenses. Future distributions will include the applicable notices and source obligations; this documentation hub does not relicense upstream or game material.

## Maintaining releases

See the [release guide](docs/RELEASE_GUIDE.md) and [release notes template](docs/RELEASE_TEMPLATE.md).

*Project information reviewed 2026-11-16 against local development documentation. This date is not a release or headset-certification date.*
