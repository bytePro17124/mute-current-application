# mute-current-application
Autohotkey script to mute the current application by pressing Shift+F1. This will ONLY mute the application that is in focus, leaving all background applications still audible.

Temporarily mute the current application by pressing Shift+F2. This will mute the current application for 2 minutes (120000ms). Change this number in the code if you would like a different amount of mute time.

Shift+F1 is no good for you? 
[Keybinding can be changed here](AHK/mute_current_application.ahk#L4) 

To do this, you'll need to download a copy of Autohotkey yourself, download source files, make the neccesary changes, and then compile them. Or ask a friend who knows these kinda things to do it for you.

Syntax tips:

Alt = '!'

Control = '^'

Shift = '+'

+F1   then becomes Shift+F1 on keyboard.

^m    then becomes Control+M on keyboard.

^+m 	then becomes control + shift + m on keyboard


It is possible to stack multiple keybinds on top of each other to all perform the same action.
