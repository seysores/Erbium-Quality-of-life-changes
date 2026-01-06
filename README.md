# Erbium

Erbium is a WIP universal gameserver for Fortnite.

[**Join the Discord!**](https://discord.gg/WxNEGBxfKq)

## Features

1. UI Redesign
- Dark gray + purple color scheme for a sleeker, modern look.
- Styled buttons, sliders, headers, and tabs to match the theme.
- Removed default window title ("Erbium") while keeping all window functionality.
- Console input and execute button redesigned to appear in the same row for easier command execution.

<div align="left">
  <img height="580" src="https://i.imgur.com/k0rFg6B.png" style="border-radius: 50px;" />
</div>

2. Launch Animation & Tab Flow
- Added launching animation on the server status text while initializing.
- Tabs are hidden until the server has finished launching:
  - Erbium and Other are always visible.
  - Zone, Events, Dump, and LateGame only appear after the server is ready.
- Smooth transitions between server states (Launching..., Joinable!, Match Started).

3. Lategame Adjustments (CREDITS [@DUCKI67](https://github.com/Ducki67/))
- Added options for LateGame settings, including:
  - Zone phase selection (1–7)
  - Long zone toggle for extended timers
- Designed to support newer versions and higher-tier weapons.

4. Tabs Overview
- Erbium Tab: Core server status, player count, playlist info, elapsed time.
- Other Tab: Miscellaneous toggles (infinite mats, ammo, inventory) and build/floor management.
- Dump Tab: Export items and playlists to text files for reference.
- LateGame Tab: Additional gameplay tweaks for advanced scenarios.
- Loot Tab (planned): GUI interface to spawn items for players (uses existing giveitem logic).

5. Console & Command Integration
- Console command box is compact and aligned with the execute button.
- Supports all existing commands like giveitem and sethealth.
- Commands execute exactly as in-game console, ensuring safe and consistent behavior.

- ⬆️ 5. IS PLANNED

Installation & Setup

1. Compile the project as usual with your VSC 2022
2. Launch the server via project reboot:
   - The GUI will automatically scale for your monitor DPI.
   - The server status will show Launching... until ready, then tabs unlock.

Notes

- The redesign focuses solely on UI/UX and workflow improvements, no gameplay logic has been altered beyond LateGame enhancements.
- Some advanced tabs (like Players / health display) are not yet fully implemented.

Contributing

If you want to improve the UI further or add new tab functionality:
- Follow the current style (dark gray + purple, rounded elements, consistent spacing).
- Keep all console logic consistent with existing giveitem / sethealth commands.
