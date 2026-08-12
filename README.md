# Omarchy
## My notes for Omarchy<br />

## Objective
Create a bind so that CTRL left/right [cursor key] moves to the next and previous workspace.
## File
.local/share/omarchy/default/hypr/binding/tiling-v2.conf
## Additions

# Moving using CTRL and Left/Right Cursor Keys
bindd = CTRL, left, Switch to workspace, workspace, -1<br />
bindd = CTRL, right, Switch to workspace, workspace, +1

# Using swaylock and CTRL + l to lock the screen with an image
bindd = CTRL, L, swaylock, exec, swaylock -i /home/paulmellors/Downloads/2322646.jpg

# Increasing and Decreasing the volume using CTRL + PgUP/PgDOWN in +/- 1 intervals.
bindd = CTRL, page_down, Increase volume, exec, swayosd-client --output-volume +1
bindd = CTRL, page_up, Decrease volume, exec, swayosd-client --output-volume -1
