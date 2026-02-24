---
sidebar_position: 3
---

# User Interface

The Fabrika Queue interface is divided into two main areas:

## 1. Jobs List

This panel displays all your queued projects.
*   **Job Item**: Represents a `.blend` file. Shows the filename, overall progress, and an **Estimated Time Remaining (ETR)** for running tasks.
*   **Status Indicators**:
    *   ⚪ **Editing**: Waiting to start or currently being configured.
    *   ⚪ **Queued**: Ready to begin rendering.
    *   🔵 **Rendering**: Currently processing.
    *   ⚫ **Completed**: Finished successfully.
    *   🟡 **Stopped**: Intentionally stopped by the user.
    *   🔴 **Error**: Encountered an issue (check logs).
    *   ⚪ **Reading File**: Initially reading properties from the `.blend` file.
*   **Controls**: Use the buttons to `Start`, `Stop`, or `Remove` jobs.

<!--
 ![[image: Jobs list panel showing status indicators and controls]]
 -->

## 2. Side Panel

### 2.1 Properties Panel

Displays detailed settings for the selected Job or Task.

*   **Job Properties**: Read-only info about the `.blend` file (detected scenes, frame range). You can also override the **Blender Version** used for this specific job here.
*   **Task Properties**: Editable settings for the specific render task. You can save and load these as **Presets** using the menu next to the header.
    *   **Render settings**: Select the rendering engine, **Media Type** (Image/Video), **Format** (e.g., PNG, OpenEXR for images), **Render Mode** (Single Frame or Animation), and output path.
    *   **Scene settings**: Select Scene, camera, frame range, **Frame Step** (render every Nth frame), and resolution. You can also quickly scale the resolution for test renders using the **Multiplicative Scale Menu** (e.g., 50%, 200%) next to the properties header. <!--*   **View Layer**: Choose a specific view layer.-->

<!--
 ![[image: Properties panel showing job and task settings]]
 -->

### 2.2 Logs Tab

*   **Logs**: Shows the raw console output from Blender. Essential for debugging crashes and other errors.

### 2.3 Output Tab

*   **Output**: Shows previews of rendered files and provides quick access to the output directory.

<!--
 ![[image: Info tabs showing logs console and output preview]]
 -->
