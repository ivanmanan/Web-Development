# Gnome Settings
Hotkeys: _Alt+F2_
## gnome-control-center
### At Default Keyboard:
Move to workspace above: _Super+Q_

Move to workspace below: _Super+W_

### At Custom Keyboard:
Pause Spotify Song - F10 - _dbus-send --print-reply --dest=org.mpris.MediaPlayer2.spotify /org/mpris/MediaPlayer2 org.mpris.MediaPlayer2.Player.PlayPause_

Previous Spotify Song - F11 - _dbus-send --print-reply --dest=org.mpris.MediaPlayer2.spotify /org/mpris/MediaPlayer2 org.mpris.MediaPlayer2.Player.Previous_

Next Spotify Song - F12 - _dbus-send --print-reply --dest=org.mpris.MediaPlayer2.spotify /org/mpris/MediaPlayer2 org.mpris.MediaPlayer2.Player.Next_

Terminal - Alt+t - _terminator_

Chromium - Alt+g - _chromium_

### At Details:
Device name: thinkpad

Default Applications: Chromium, Audacious

## gnome-tweak-tool
### Gnome Extensions:
Google search _gnome shell extensions_

### Appearance:
Global Dark Theme: ON

### Fonts:
Adjust scaling factor as necessary

On 1440p: Leave HDPi as 2 in Windows and scaling factor as 0.85 in Fonts; Must edit GRUB Bootloader config file separately;

### Keyboard and Mouse:
Switch between overview and desktop: _Right Super_

Reasoning: We do not want to accidentally press _Super_ to bring up overview. We should only need to press _Super+s_ to bring overview

### Typing:
At 'Ctrl Key Position' - Only check these two boxes: 'Caps Lock as Ctrl' AND 'Swap Ctrl and Caps Lock'

### Workspaces:
Workspace Creation: Dynamic

Workspaces only on primary display: ON

### Extensions:
Activities Configurator - Turn these ON: Hide Icon, Remove Activities Button, Disable Hot Corner, Hide Panel Rounded Corners, Hide Application Menu Button Icon

Alternate Tab - ON - Present windows as: Thumbnail and application icon; Show only windows in the current workspace

Desktop Scroller - ON - Wallpaper Scrolling: ON; Enabled Edges: LEFT, RIGHT, TOP

Dropdown Terminal - ON

Hide Top Bar - ON - Only change Keyboard Shortcuts - key that triggers the bar to be shown: _Super+E_; Pressing the shortcut again rehides the panel: ON

Native Window Placement: ON

No topleft hot corner: ON

Removable Drive Menu: ON

Top Panel workspace scroll: ON

## dconf-editor
### Save gnome-sessions:
/org/gnome/gnome-session/

open up auto-save-session

change value to true