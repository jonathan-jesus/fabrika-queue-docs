---
sidebar_position: 4
---

# Troubleshooting

## Common Issues

### "Blender executable not found"
*   **Cause**: The path to Blender in incorrect. (the blender version/installation could be removed)
*   **Fix**: Go to Settings and browse to the correct `blender.exe` (Windows) or binary for that version or remove the incorrect path.

<!--
 ![[image: Settings dialog highlighting the Blender path input field]]
-->


### "Job file not found"
*   **Cause**: The source `.blend` file was moved, renamed, or deleted.
*   **Fix**: Restore the file to its original location or remove the job from the queue and add it again from the new location.

## Logs

Fabrika Queue captures all standard output from Blender. If you report a bug, please include the relevant section from the **Logs** tab.
