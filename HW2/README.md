# VR Game Project - Homework Assignment 2

## Overview
This project is a Virtual Reality (VR) game created using Unreal Engine's VR template. It incorporates interactive elements, spatial UI, and gameplay mechanics to provide an engaging VR experience. The project is configured to support the Meta Quest 3 HMD.

## Features
1. **VR Game Template**:
   - Created a new VR project using Unreal Engine's VR template with starter assets.
   - Configured to work with Meta Quest 3 VR.
   - Default VR player pawn is used for the gameplay experience.

2. **Custom Level Design**:
   - Developed a new level populated with static mesh objects for decoration.
   - Configured the level to use the VR gamemode.

3. **Teleportation**:
   - Implemented a teleportation area using a navigation volume and static mesh.
   - Allows players to navigate the environment via teleportation mechanics.

4. **Interactive Grab Mechanics**:
   - Added three unique grab interactables:
     - Sphere, Square, and Cylinder.
   - All interactables use simulated physics and gravity.
   - Notable behavior: The cylinder may roll away before being grabbed, showcasing the integrated physics system.

5. **Pistol Blueprint**:
   - Spatial UI successfully added to display the ammo count.
   - **Known Issue**: Ammo count is currently static and not dynamic.
   - Delayed reload functionality was not implemented.

6. **Target Mechanics**:
   - Five targets resembling croissants were added to the level.
   - Targets are supposed to:
     - Keep track of hit counts (currently not working as intended).
     - Change material color after being hit.
     - Be destroyed upon reaching the hit threshold.
   - **Known Issue**: Targets are not registering hits or being destroyed as expected.

7. **Level Progress Tracking**:
   - A basic level with functional gameplay and elements is included.
   - Winning and progression mechanics are rudimentary but present.

## Installation
1. Ensure Unreal Engine is installed on your computer.
2. Clone or download the project files into your Unreal Engine projects directory.
3. Open the project using Unreal Engine.

## Setup
1. **VR HMD Configuration**:
   - Connect and configure your Meta Quest 3 VR headset within Unreal Engine.
   - Navigate to "Edit > Plugins" and ensure VR-related plugins are enabled.

2. **Teleportation**:
   - Verify that the navigation volumes and teleportation areas are set correctly.

3. **Interactive Grab Mechanics**:
   - Ensure all grab interactables have the grab component and proper physics settings.

4. **Pistol Blueprint**:
   - The spatial UI is functional but currently static.
   - Requires debugging for dynamic ammo count and delayed reload functionality.

5. **Target Mechanics**:
   - Targets require adjustments to projectile settings for proper hit detection and destruction behavior.

## Known Issues
1. **Pistol Blueprint**:
   - Ammo count does not decrease dynamically.
   - Delayed reload functionality is not implemented.

2. **Target Mechanics**:
   - Targets are not registering hits or being destroyed as expected.
   - Possible issue with projectile settings that need modification.

3. **Grabbable Objects**:
   - The cylinder may roll away, making it challenging to grab.

## Future Enhancements
- Resolve issues with dynamic ammo tracking and delayed reload functionality.
- Debug and optimize target mechanics for hit registration and destruction.
- Expand the level design for a richer gameplay experience.

## Controls
- **Teleportation**: Use the VR controller to select and teleport to a target location.
- **Grab**: Use the grab button to interact with objects.
- **Shoot**: Use the trigger button to fire the pistol (ammo tracking incomplete).
- **Reload**: Reload functionality is not currently implemented.

## Credits
This project was developed as part of Homework Assignment 2 for CS 310H. Unreal Engine's VR template and assets were used as a foundation.

## Notes
While many project milestones were achieved, some features require additional debugging and refinement for full functionality.

## Link
https://www.youtube.com/watch?v=hNDD2gjrnMI
