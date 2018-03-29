Spacemacs, VIM + Emacs Configuration

## Useful

- `SPC h d k` - Describes a key
- `SPC h k` - List current keybindings

## Notes

- Use `develop` branch currently, to get `Colemak` keybindings.

## Books

- Learning GNU Emacs

## AutoHotkey

To not swap Ctrl/Alt on Emacs.

```ahk
; This file by Alan J. Hogan, http://alanhogan.com/
; Switches the left Control and Alt keys.

SetTitleMatchMode, 2 ; This let's any window that partially matches the given name get activated
#IfWinActive, ubuntu
LCtrl::Ctrl
LAlt::Alt

#IfWinActive, emacs@
LCtrl::Ctrl
LAlt::Alt

#IfWinActive, PuTTY
LCtrl::Ctrl
LAlt::Alt

#IfWinActive, Chrome
LCtrl::Alt
LAlt::Ctrl
 
#If
LCtrl::Alt
LAlt::Ctrl
```
