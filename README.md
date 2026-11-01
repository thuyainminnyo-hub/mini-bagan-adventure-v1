# Mini Bagan Adventure V1

A mobile-first Three.js player movement prototype.

## Current prototype
- Synthetic Bagan-inspired courtyard with pagoda structures, trees and a local guide NPC
- Touch joystick movement and run control
- Drag-to-rotate camera
- Basic circular collision around pagodas and trees
- NPC talk interaction
- FPS and player-coordinate HUD

## Important scope note
This is a **synthetic demo world**. It does not yet use live OpenStreetMap data and is not yet integrated with the KMH 3D City Map or KMH OIA. Those integrations are planned behind an adapter/API boundary.

## Run
Open the GitHub Pages site over HTTPS on a modern mobile browser. An internet connection is required to load Three.js r160 from jsDelivr.

## Controls
- Drag the lower-left joystick to move
- Drag the open scene area to rotate the camera
- Hold RUN to move faster
- Press TALK near the guide NPC

## QA status
Source uploaded; browser execution and Android performance QA are still pending. Please record device, browser version, FPS, heat, battery use, and any crashes during a 5-minute test.

## Planned next steps
1. Verify browser execution and fix any runtime issues
2. Run Android folded/unfolded and 5-minute performance QA
3. Add save/load and mission flow
4. Integrate real Bagan map data through a separate world adapter
