---
sidebar_position: 1
---

# Installation

## System Requirements

Before installing Fabrika Queue, ensure your system meets the following requirements:

*   **Operating System**: Windows 10/11 *(Linux support is expected in March/2026, macOS support is coming soon)*.
*   **Blender**: **Blender 3.0 or later** must be installed and accessible.
    *   Fabrika Queue relies on the `blender` executable to perform renders.

## Download

**[Get the latest version of Fabrika Queue from Gumroad](https://1480052920180.gumroad.com/l/fabqueue)**.

## Installing Fabrika Queue

### Windows

1.  **Installer**: Run the `.exe` file and follow the on-screen instructions.
2.  **Portable**: Extract the `.zip` file to a folder of your choice and run `fabrika_queue.exe`.
3.  Once installed, launch **Fabrika Queue** from the Start menu.

## First Launch Configuration

Upon first launch, you may need to specify the path to your Blender executable if it's not detected automatically. **Fabrika Queue allows you to register multiple Blender versions** (e.g., Blender 3.6, Blender 4.0) and choose which one to use for each job.

1.  Go to **Settings** (Gear icon).
2.  Locate the **Blender Paths** section.
3.  Click the **Add** (+) button.
4.  Browse and select your `blender.exe`.
5.  Repeat these steps to add as many Blender versions as you need.
<img src="../img/screenshots/settings-blender-instances.jpg" alt="Add exe startup" />

### Automatic Version Detection

If you have multiple Blender versions installed and configured, Fabrika Queue automatically detects the Blender version used in the last save of each `.blend` file. If that version is configured in your settings, it will be used for the render job. Otherwise, the app will fall back to your **Default** version.