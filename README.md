# dwm-nmugi  

## About

This is a customized version of [DistroTube's DWM](https://gitlab.com/dwt1/dwm-distrotube.git).

## Dependencies

- Fonts : SauceCodePro,Mononoki,Hack,JoyPixels
- Terminal : Alacritty
- Utilities : scrot, xclip
- Suckless : [dmenu-dt](https://gitlab.com/dwt1/dmenu-distrotube),[sl-dt](https://gitlab.com/dwt1/st-distrotube),slstatus

## Keybindings

### Main keybindings

Keybinding| Action
---|---
| MODKEY + SHIFT + RETURN         | opens terminal (alacritty) 
| MODKEY + RETURN | opens run launcher (dmenu)
| MODKEY + SHIFT + c      | closes window with focus                                     
| MODKEY + SHIFT + r      | restarts dwm                                                 
| MODKEY + SHIFT + q      | quits dwm                                                    
| MODKEY + b              | hides the bar                                                
| MODKEY + 1-9            | switch focus to workspace (1-9)                              
| MODKEY + SHIFT + 1-9    | send focused window to workspace (1-9)                       
| MODKEY + j              | focus stack +1 (switches focus between windows in the stack) 
| MODKEY + k              | focus stack -1 (switches focus between windows in the stack) 
| MODKEY + SHIFT + j      | rotate stack +1 (rotates the windows in the stack)           
| MODKEY + SHIFT + k      | rotate stack -1 (rotates the windows in the stack)           
| MODKEY + h              | setmfact -0.05 (expands size of window)                      
| MODKEY + l              | setmfact +0.05 (shrinks size of window)                      
| MODKEY + .              | focusmon +1 (switches focus next monitors)                   
| MODKEY + ,              | focusmon -1 (switches focus to prev monitors)                

### Layout controls

| Keybinding             | Action                  |
|------------------------|-------------------------|
| MODKEY + d             | row layout              |
| MODKEY + i             | column layout           |
| MODKEY + TAB           | cycle layout (-1)       |
| MODKEY + SHIFT + TAB   | cycle layout (+1)       |
| MODKEY + SPACE         | change layout           |
| MODKEY + SHIFT + SPACE | toggle floating windows |
| MODKEY + t             | layout 1                |
| MODKEY + f             | layout 2                |
| MODKEY + m             | layout 3                |
| MODKEY + g             | layout 4                |

## Application controls

Keybinding |Action
------|------
MODKEY + SHIFT + d | Open Discord
MODKEY + SHIFT + e | Open File Browser : Thunar
MODKEY + SHIFT + f | Open Browser : Firefox
MODKEY + SHIFT + k | Open Password manager : Keepass
MODKEY + SHIFT + m | Open Music player : Cantata
MODKEY + SHIFT + o | Open Second Brain : Obsidian
MODKEY + SHIFT + s | Utility : Screenshot - Scrot
MODKEY + SHIFT + t | Open Telegram

## Misc 

**Autostart** : Place the autostart.sh in /home/.dwm 

**Scrot** : Screenshot utility since none of the other played too well with dwm. It saves pictures to ~/Pictures/Scrot