# Before
<img src="https://github.com/dp-sys/pendrive_icon_Change/blob/main/before.png">

# After
<img src="https://github.com/dp-sys/pendrive_icon_Change/blob/main/after.png">
## Steps to change pendrive icon (icon remains on different PCs):
- Choose the image you want as the pendrive icon.
- Ensure the image is in 256x256 resolution and convert it to `.ico` format.
  - Tip: Use a file name without spaces.
- Place the `.ico` file in the root directory of the pendrive.
- Open Notepad and paste the following two lines:

[Autorun]

Icon=icoName.ico

- Replace icoName.ico with the actual name of your .ico file.
-  and save it as `Autorun.inf` in the root dir of your pendrive, When saving, select 'All files' in 'Save as type' in notepad to avoid saving it as .txt.
-  Set both icoName.ico and Autorun.inf to 'Read-only' and 'Hidden' to prevent accidental deletion.
-  All done. now safely eject the pendrive and insert again to see changes in the pendrive icon
