
Kitty Terminal — Shortcut Keymap Sheet


🗂️ Tabs


Shortcut	                  Action
Ctrl + T	                  New tab
Ctrl + Shift + T           	  New tab (with current working directory)
Ctrl + Q	                  Close tab
Ctrl + Shift + Q	          Close tab
Ctrl + N	                  Next tab
Ctrl + P	                  Previous tab
Ctrl + Shift + ]        	  Next tab
Ctrl + Shift + [	          Previous tab
Ctrl + R	                  Rename current tab


🪟 Windows

Shortcut	                  Action
Ctrl + Shift + Enter	      New window
Ctrl + Shift + V	     	New window ⚠️
Ctrl + Shift + H	     	New window
Ctrl + Shift + W		     Close window
Ctrl + Alt + Shift + ←		     Previous window
Ctrl + Alt + Shift + →		     Next window
🔤 Font Size
Shortcut	Action
Ctrl + =	Increase font size
Ctrl + -	Decrease font size
Ctrl + 0	Restore font size
Ctrl + Shift + =	Increase font size (alt)
Ctrl + Shift + -	Decrease font size (alt)
📋 Clipboard
Shortcut	Action
Ctrl + Shift + C	Copy to clipboard
Ctrl + Shift + V	Paste from clipboard ⚠️
Shift + Insert	Paste from selection
📜 Scrolling
Shortcut	Action
Ctrl + Shift + ↑	Scroll line up
Ctrl + Shift + ↓	Scroll line down
Ctrl + Shift + Page Up	Scroll page up
Ctrl + Shift + Page Down	Scroll page down
Ctrl + Shift + Home	Scroll to home
Ctrl + Shift + End	Scroll to end
🧹 Terminal
Shortcut	Action
Ctrl + Shift + K	Clear terminal
🌫️ Opacity (Dynamic Transparency)
Shortcut	Action
Alt + A	Increase background opacity (+0.05)
Alt + S	Decrease background opacity (−0.05)
Alt + R	Reset background opacity (0.85)
🚫 Disabled Shortcuts
Shortcut	Action	Reason
Ctrl + Shift + ←	no_op	Conflict avoidance
Ctrl + Shift + →	no_op	Conflict avoidance
Shift + ←	no_op	Conflict avoidance
Shift + →	no_op	Conflict avoidance
⚠️ Conflicts & Warnings
Issue	Details
Ctrl + Shift + V	Bound to both new_window and paste_from_clipboard. The later definition wins (paste), but this is ambiguous — resolve to one action.
Ctrl + Q vs Ctrl + Shift + Q	Both close tabs. Ctrl + Q is non-standard; typically used for quitting apps.
Ctrl + Shift + H	Opens a new window instead of the conventional horizontal split.
Ctrl + R	Renames tab (overrides shell history search in some terminals).
Ctrl + N / Ctrl + P	Next/previous tab (overrides shell readline navigation).
