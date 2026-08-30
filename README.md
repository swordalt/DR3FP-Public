# DanceRail3 Fanmade Player

DanceRail3FanmadePlayer (DR3FP) is a fanmade chart player for the mobile rhythm game DanceRail3. It is a clean rewrite which uses no code from other projects, except for gameplay (the 'game' scene).<br>

<img width="1920" height="1080" alt="Screenshot" src="https://github.com/user-attachments/assets/415e2cd2-1546-4597-afc6-22913d50fd49" /><br>
*Gameplay, autoplay enabled, hit effects disabled.*

## Features
- Chart importer (from an archive). DR3FV-style manual import is still supported.
- Gameplay modifiers (support & difficulty mods) from the official game.
- Skill Check creator and customizer.
- Improved settings page with additional settings and tooltips.
- Offset wizard.
- Everything else from DR3FV.
- Fixes for bugs from DR3FV and DR3Viewer.

### Directories & Important Files
- `/songs`: Where songs are stored.
- `songlist.json`: JSON structured metadata for songs and charts.
- `skillcheck.json`: JSON structured skill check data.

## Renderer
DR3FP has a rendering application that can output a video of your chart. It can render at a higher resolution and framerate than your display. It offers better consistency and speed (potentially faster than real-time) compared to traditional screen recording. It is Windows-exclusive. Rendered videos are stored in the `/render` directory.<br>

You are required to download a FFMPEG executable (`ffmpeg.exe`) yourself and select its path in Settings. I recommend downloading one from [here](https://www.gyan.dev/ffmpeg/builds/).<br>

<img width="1917" height="1080" alt="Screenshot" src="https://github.com/user-attachments/assets/5226a5f0-e467-4e2f-95b1-a1f8ae7f192d" /><br>
*Render settings.*

<img width="1306" height="698" alt="Screenshot" src="https://github.com/user-attachments/assets/d7f16e61-f063-4ba7-94ab-f90a43e50816" /><br>
*A low-resolution render of Galaxy Collapse Tier20, a 7 minute song, completed in a minute and a half.*

## Downloads
Windows & Android: Download from [GitHub releases](https://github.com/swordalt/DR3FP-Public/releases).<br>
iOS: Not available yet.<br><br>

Renderer (Windows): Download from [GitHub releases](https://github.com/swordalt/DR3FP-Public/releases).

*Note: The renderer will likely not recieve as many updates since it doesn't affect gameplay functionality.*

## Source
The source code for this project is private due to DR3FV's source also being private.

## Attribution
- DR3FV by [JIMENGAME](https://github.com/JIMENGAME) (private project)
- [DanceRail3Viewer](https://github.com/lucarioex/DanceRail3Viewer) by [LucarioEX](https://github.com/lucarioex)<br>

Note: AI was used within this project to fix critical bugs and perform large operations.
