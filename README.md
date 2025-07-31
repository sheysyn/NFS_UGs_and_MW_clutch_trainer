# Description

>It's a Cheat Engine (ver.46 and newer) project with a Lua script inside.

>This project is based on source code published under the MIT license.
Slightly modified, based on the source code from: https://github.com/clod44/NFSU2Clutch

>The differences in the code for various parts are only the values
in the pointers and some comments in the console.

# How to download

>Download the repo by clicking the green "Code" button and then selecting "Download ZIP".

>Extract the files from the archive.

# Changing bindings or entire code.

>Open the .CT file (Cheat Engine) file with a text editor.

>Press Ctrl + F and enter "Custom block" in the search window, then press "Find".

>Read the comments and make your decisions.

>If it causes lag, look a bit lower in the code and read following comments.

# How to use

>Launch the game.

>Make sure that your in-game gearbox type is manual or script won't work.

>Open the .CT (Cheat Engine) file.

>In Cheat Engine, click the "Execute" button on the small window
with 3 buttons (not in the console that appears).

>If the console looks ok (note: even if you changed key bindings
in the text editor, it will still show default keys), click "Start" on the same small window.

>If it says "Started," try pressing your key bindings in-game.

>You also have "Zero shifting delay" in Cheat Engine window,
to remove delay between shifts or restore it to its original state.
It's very noticeable in both parts of Undergound,
but in Most Wanted I didn't notice much of a difference,
so the feature isn't there, because it doesn't really make much sense (the game already uses
zero shifting delay; although it sounds like it isn't, you still gain speed while the engine produces no sound).

>That's it — enjoy!

>To stop, click "Stop" on Cheat Engine's small window (where you clicked "Start" and "Execute").

>You can shift gears using your custom binds only if the clutch button is pressed.

>You can still use the game's default gear change buttons
(which is easier during drag races), and they don't require holding the clutch.

# What does it do

>Activating clutch shifts your car's gear to Neutral while you can still change gears in the background.

>Releasing the clutch shifts back to whatever gear you moved your shift to.

>It also removes delay between shifts.

# Notes

>Try not to overlap your in-game keybinds with script keybinds.

>Known bugs: in Underground 2 if you enter the map mode and exit
from there the game will think that you are still in pause mode,
so to fix this, pause the game (esc button) and simply return
from pause mode to the game, this will return control to the script.
This may also work for other situations if you find something similar.

>You can hold down your gear shift key before pressing clutch.
It will register as a shift after clutch is pressed, but it
won't work more than once — it's a kind of prepared shift.
