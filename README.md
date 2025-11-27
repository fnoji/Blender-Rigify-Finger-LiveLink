# VMC to Rigify Finger Live Link

A Blender addon that links VMC (Virtual Motion Capture) protocol bone rotations to Rigify rigs, with a focus on accurate finger tracking and granular control.

## Features
- **Live Linking**: Receives VMC protocol data via OSC and applies it to Rigify armatures in real-time.
- **Finger Precision**: Dedicated controls for finger and thumb axis mapping, inversion, and sensitivity.
- **Recording**: Built-in recording functionality, with support for simultaneous recording with the Xsens MVN Blender Plugin.
- **Presets**: Save and load configuration presets for different rig standards.

## Installation
1. Download the release zip file.
2. Open Blender and go to **Edit > Preferences > Add-ons**.
3. Click **Install...** and select the zip file.
4. Enable the addon **Animation: VMC to Rigify Finger Live Link**.

## Basic Usage
1. **Configuration**:
   - Open the sidebar (N-panel) and find the **Finger Link** tab.
   - Set the **Port** to match your VMC sender (default: 39539).
   - Select your Rigify armature in the **Target Rig** field.
2. **Start Linking**:
   - Click **Start VMC Link**.
3. **Calibration (Binding)**:
   - To align the rig with the input data, click **Bind Left** or **Bind Right** while holding a neutral pose.
   - Use **Reset Left** / **Reset Right** to clear the binding if the offsets become incorrect.
4. **Recording**:
   - Use the **Recording** panel to capture the motion to keyframes.
   - If you have the Xsens MVN plugin installed, you can enable **Sync with Xsens (MVN)** to start/stop both recordings simultaneously.

## Supported Hardware & Software
This addon is designed to support finger tracking information from any source that complies with the VMC Protocol.

**Verified Configurations:**
- **UDCAP Glove**
- **Leap Motion** (via VSeeFace)

## Compatibility & Presets
The standard default settings are tuned for the following rig types:
- **Unity Humanoid based Genshin Rig**: [Addons-And-Tools-For-Blender-miHoYo-Shaders](https://github.com/michael-gh1/Addons-And-Tools-For-Blender-miHoYo-Shaders)
- **PMX Models rigged with MMR (MikuMikuRig)**: [MikuMikuRig](https://github.com/XiaoFFGe/MikuMikuRig)

## Contact & Support
For inquiries, please visit: **[fnoji.com/link](https://fnoji.com/link)**

You can also join the Discord server:
**Hoyo Animation Creator**: [discord.gg/S84ndUmGTq](https://discord.gg/S84ndUmGTq)

---
Author: fnoji
