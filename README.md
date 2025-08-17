# Omarchy
## My notes for Omarchy<br />

## Objective
Create a bind so that CTRL left/right [cursor key] moves to the next and previous workspace.
## File
.local/share/omarchy/default/hypr/binding/tiling.conf
## Additions
bindd = CTRL, left, Switch to workspace, workspace, -1
bindd = CTRL, right, Switch to workspace, workspace, +1
