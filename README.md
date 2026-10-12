Kitty Terminal Configuration — README

A Kitty terminal configuration focused on usability, transparency, and efficient keyboard-driven navigation.
1. Theme & Shell Integration
Setting	Value	Description
include	current-theme.conf	Loads an external theme file for colors.
shell_integration	no-sudo	Enables shell integration but disables sudo password prompting.
term	xterm-256color	Sets the terminal type reported to applications.
2. Fonts
Setting	Value	Description
font_size	19.0	Base font size.
font_family	"JetBrainsMono Nerd Font"	Primary font (fixed typo from ont_family).
bold_font	auto	Automatically selects bold variant.
italic_font	auto	Automatically selects italic variant.
bold_italic_font	auto	Automatically selects bold-italic variant.
3. Transparency
Setting	Value	Description
background_opacity	0.9	90% opaque background.
dynamic_background_opacity	yes	Allows changing opacity at runtime via shortcuts.
4. Layout
Setting	Value	Description
enabled_layouts	tall,*	Uses the "tall" layout as default; * allows all other layouts.
5. Windows
Setting	Value	Description
window_border_width	2pt	Border thickness around windows.
6. Tab Bar
Setting	Value	Description
tab_bar_style	powerline	Powerline-style tab bar.
active_tab_background	#444444	Background color of the active tab.
active_tab_foreground	#5fd700	Text color of the active tab.
tab_bar_margin_height	0.0 2.0	Top/bottom margin for the tab bar.
tab_bar_margin_color	#4f4f4f	Color of the tab bar margin.
tab_activity_symbol	*	Symbol shown when a tab has activity.
7. Cursor
Setting	Value	Description
cursor_trail	1	Enables a short cursor trail.
cursor_shape	block	Block-shaped cursor.
8. Keyboard Shortcuts
8.1 Unbound / Disabled Shortcuts
Shortcut	Action	Notes
ctrl+shift+left	no_op	Disabled to avoid conflicts.
ctrl+shift+right	no_op	Disabled.
shift+left	no_op	Disabled.
shift+right	no_op	Disabled.

    Note: forward is not a valid Kitty action. no_op is used instead.

8.2 Tab Navigation
Shortcut	Action
ctrl+shift+[	Previous tab
ctrl+shift+]	Next tab
ctrl+alt+shift+left	Previous window
ctrl+alt+shift+right	Next window
8.3 Window Management
Shortcut	Action
ctrl+shift+enter	New window
ctrl+shift+v	New window
ctrl+shift+h	New window
ctrl+shift+w	Close window
ctrl+shift+q	Close tab
8.4 Tab Management
Shortcut	Action
ctrl+t	New tab
ctrl+shift+t	New tab with current working directory
ctrl+r	Rename current tab (set_tab_title)
ctrl+n	Next tab
ctrl+p	Previous tab
ctrl+q	Close tab
8.5 Font Size Controls
Shortcut	Action
ctrl+equal	Increase font size
ctrl+minus	Decrease font size
ctrl+0	Restore font size
ctrl+shift+equal	Increase font size (alternative)
ctrl+shift+minus	Decrease font size (alternative)
8.6 Clipboard
Shortcut	Action
ctrl+shift+c	Copy to clipboard
ctrl+shift+v	Paste from clipboard
shift+insert	Paste from selection
8.7 Scrolling
Shortcut	Action
ctrl+shift+up	Scroll line up
ctrl+shift+down	Scroll line down
ctrl+shift+page_up	Scroll page up
ctrl+shift+page_down	Scroll page down
ctrl+shift+home	Scroll to home
ctrl+shift+end	Scroll to end
8.8 Clear Terminal
Shortcut	Action
ctrl+shift+k	Clear terminal
8.9 Opacity Controls
Shortcut	Action
alt+a	Increase background opacity by 0.05
alt+s	Decrease background opacity by 0.05
alt+r	Reset background opacity to 0.85
9. Performance
Setting	Value	Description
sync_to_monitor	no	Disables sync to monitor; fixes freezing issues.
repaint_delay	10	Repaint delay in milliseconds.
input_delay	3	Input delay in milliseconds.
10. Miscellaneous
Setting	Value	Description
scrollback_lines	2000	Number of scrollback lines to keep.
scrollback_pager	less +G -Rn	Pager used for scrollback (note: the original file has a copy-paste artifact clude current-theme.conf appended — should be removed).
