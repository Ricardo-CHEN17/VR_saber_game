# VR Saber Game

A desktop VR rhythm/action game build created with Unity and SteamVR.

## Overview

This repository currently contains a playable Windows build of the game (not the full Unity source project). Players use VR controllers to interact with the environment and perform core gameplay actions such as movement, turning, and UI interaction.

## Gameplay Demo

| Demo 1 | Demo 2 |
| --- | --- |
| ![Gameplay Demo 1](<Desktop Screenshot 2026.01.03 - 19.37.19.06.png>) | ![Gameplay Demo 2](<Desktop Screenshot 2026.01.03 - 19.39.09.82.png>) |
| ![Gameplay Demo 3](<Desktop Screenshot 2026.01.03 - 19.40.28.92.png>) | ![Gameplay Demo 4](<Desktop Screenshot 2026.01.03 - 19.41.52.38.png>) |

## Build Contents

- `VR Saber/My project.exe`: Main game executable
- `VR Saber/My project_Data/`: Unity data files
- `VR Saber/My project_Data/StreamingAssets/SteamVR/`: SteamVR action and controller binding files

## Requirements

- Windows 10 or Windows 11 (64-bit)
- Steam installed
- SteamVR installed and running
- A VR-ready GPU and CPU
- A supported VR headset and controllers

## Supported Headsets / Controller Profiles

Default SteamVR bindings are included for multiple device profiles, including:

- Oculus Touch
- Valve Index (Knuckles)
- HTC Vive / Vive Pro / Vive Cosmos
- Windows Mixed Reality (Holographic Controller)

Note: Final behavior depends on your active SteamVR runtime, current binding configuration, and hardware setup.

## How to Run

1. Start Steam.
2. Launch SteamVR and confirm your headset/controllers are tracked.
3. Open the `VR Saber` folder.
4. Run `My project.exe`.
5. If prompted by Windows Firewall, allow access on private networks.

## Controls (SteamVR Actions)

This build is configured with a default SteamVR action set containing these core actions:

- Interact UI
- Teleport
- Grab (Pinch / Grip)
- Snap Turn Left / Right
- Haptic Output

Controller-specific button mappings can be reviewed or customized in SteamVR:

1. Open SteamVR Settings.
2. Go to Controller Bindings.
3. Select this application.
4. Choose or edit the active binding profile.

## Troubleshooting

- If the game opens on desktop but not in VR:
  - Ensure SteamVR is already running before launching the executable.
- If controllers do not respond:
  - Recheck the active binding profile in SteamVR Controller Bindings.
- If performance is unstable:
  - Lower SteamVR render resolution and close background GPU-heavy applications.
- If startup fails:
  - Install/update Microsoft Visual C++ Redistributables and GPU drivers.

## Notes for Developers

- This repository appears to include a built player package, not editable Unity scene/source files.
- To continue feature development, you will need the original Unity project source.

## License

No license file is currently provided in this repository. Add a license before public distribution.

## Authors
Yijin Chen
Jiabao Cao