---
sidebar_position: 2
---

# Getting Started

This guide will walk you through your first render job with Fabrika Queue.

## 1. Add a Project

1.  Click the **Add Job** or the **+** button.
2.  Navigate to your project folder and select a Blender file (`.blend`).
3.  The file will appear in the **Jobs List** on the left.

![[image: Jobs list showing a newly added Blender project file]]

## 2. Configure a Task

1.  Expand the job you just added.
2.  You can create new tasks using the **+ Add Task** button or **Duplicate** an existing one.
3.  Click to select the task and edit its properties in the **Right panel**. Look for the **Render Settings** and the **Scene Settings** sections.

![[image: Properties panel showing task configuration options like frame range and output format]]

## 3. Start Rendering

1.  Click the **Play** button on the Task item or the Job item.
    *   Starting a **Job** will run all its enabled tasks sequentially.
2.  The status indicator will turn **Blue** (Running).
3.  Switch to the **Logs** tab to see real-time output from Blender.
    *   **Filtering**: Selecting a **Job** displays logs for all its tasks. Selecting a specific **Task** filters the view to show only that task's output.

![[video: Demonstration of starting a render job and viewing the real-time logs]]

## 4. View Results

Once the render is complete:
1.  The task status will turn **Completed**.
2.  Go to the **Output** tab to see a preview of the rendered image/video.
3.  Click **Open Folder** to view the files in your file explorer.

![[image: Output tab showing a preview of the rendered image]]
