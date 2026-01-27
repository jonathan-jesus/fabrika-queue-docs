---
sidebar_position: 3
---

# User Interface

The Fabrika Queue interface is divided into three main areas:

## 1. Jobs List (Left Panel)

This panel displays all your queued projects.
*   **Job Item**: Represents a `.blend` file. Shows the filename and overall progress.
*   **Status Indicators**:
    *   ⚪ **Ready**: Waiting to start.
    *   🔵 **Running**: Currently processing.
    *   ⚫ **Completed**: Finished successfully.
    *   🔴 **Error**: Encountered an issue (check logs).
*   **Controls**: Use the buttons to `Start`, `Stop`, or `Remove` jobs.

![[image: Jobs list panel showing status indicators and controls]]

## 2. Properties Panel (Right Panel - Top)

Displays detailed settings for the selected Job or Task.

*   **Job Properties**: Read-only info about the `.blend` file (detected scenes, frame range).
*   **Task Properties**: Editable settings for the specific render task:
    *   **Render settings**: Switch rendering engine, media type format, output path.
    *   **Scene settings**: Select Scene, camera, frame range and resolution. <!--*   **View Layer**: Choose a specific view layer.-->

![[image: Properties panel showing job and task settings]]

## 3. Info Tabs (Right Panel - Bottom)

*   **Logs**: Shows the raw console output from Blender. Essential for debugging crashes and other errors.
*   **Output**: Shows previews of rendered files and provides quick access to the output directory.

![[image: Info tabs showing logs console and output preview]]
