# Omarchy
## My notes for Omarchy<br />

## Objective
Create a bind so that CTRL left/right [cursor key] moves to the next and previous workspace.
## File
nano ~/.config/hypr/bindings.lua
## Additions

# Moving using CTRL and Left/Right Cursor Keys
o.bind("CTRL + RIGHT", "Next workspace", hl.dsp.focus({ workspace = "e+1" }))

o.bind("CTRL + LEFT", "Previous workspace", hl.dsp.focus({ workspace = "e-1" }))
