# screen

```bash
$ screen -list
There is a screen on:
10504.pts-13.prod151    (Attached)
1 Socket in /var/run/screen/S-dboukari.

$ screen -x  10504.pts-13.prod151       --> Attach to windows

screen -S ppaxisdb03fv -X quit          --> Kill a session


CTRL + A C                              --> New windows

#Resize height
CTRL a : resize 10

#Resize width horizontal
CTRL a : resize -h 10

CTRL + A SHIFT 0                        --> Switch to other windows
CTRL + A SHIFT 1
CTRL + A SHIFT 2
CTRL + A SHIFT 3

CTRL + a ESC PAGEUP PAGEDOWN                    --> Scroll into windows

C-a C-d     (detach)      Detach screen from this terminal.
C-a D D     (pow_detach)  Detach and logout.
C-a C-w     (windows)     Show a list of window.
C-a C-d     (detach)      Detach screen from this terminal.
C-a D D     (pow_detach)  Detach and logout.

#Create a new Session
screen -S mySession

To split Verticaly
CTRL+a ALTGR+|                          --> split horizontal
  CTRL+a TAB                              --> Move to other window
  CRTL+a c                                  --> Create a new terminal in the region

To split Horizontaly
CTRL+a SHIFT+S                          --> split Verticaly
  CTRL+a TAB                              --> Move to other window
  CRTL+a c                                  --> Create a new terminal in the region

CTRL+a X                               --> Remove the current region
CTRL+a Q                               --> Remove All regions
```
