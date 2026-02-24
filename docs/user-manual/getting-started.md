---
sidebar_position: 2
---

# Getting Started

This guide will walk you through your first render job with Fabrika Queue.

## 1. Add a Project

1.  Click the **Add Job** or the **+** button or drag and drop a Blender file (`.blend`) into the **Jobs List**.
<img src="../img/screenshots/adding-job.jpg" alt="Adding a job to the queue" width="600" />
2.  The file will appear in the **Jobs List** on the left.
<img src="../img/screenshots/job-added.jpg" alt="Job added to the queue" width="600" />

## 2. Configure a Task

1.  Expand the job you just added.
2.  You can create new tasks using the **+ Add Task** button or **Duplicate** (⋮ menu or Shift+D) an existing one.
3.  Click to select the task and edit its properties in the **Right panel**. Look for the **Render Settings** and the **Scene Settings** sections.
    *   **Tip (Override Presets):** You can save your configured settings as a preset by clicking the presets icon (sliders) next to "Task Properties". This allows you to quickly apply the same render and scene settings to other tasks.

<img src="../img/screenshots/main-area-03.jpg" alt="Task properties" />

## 3. Start Rendering

1.  Use the **Start Queue** button in **Queue Actions** on the top right. This will process all queued tasks.
2.  The status indicator will turn **Green** (Rendering).
<img src="../img/screenshots/main-area-02.jpg" alt="Starting a render job" />
3.  You can switch to the **Logs** tab to see real-time output from Blender.
    <!-- *   **Filtering**: Selecting a **Job** displays logs for all its tasks. Selecting a specific **Task** filters the view to show only that task's output. -->

## 4. View Results

Once the render is complete:
1.  The task status will turn **Completed**.
<img src="../img/screenshots/render-output.jpg" alt="Render output" />
2.  Go to the **Output** tab to see a preview of the rendered image/video.
3.  Click **Open Folder** to view the files in your file explorer.
