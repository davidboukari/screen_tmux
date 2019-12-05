# Cmd tmux

```bash
$ tmux new  -s myname
$ tmux ls                               --> list all session
$ tmux a                                --> Attach to the default session
$ tmux a  -t 1                          --> Attach to a session
$ tmux kill-session -t myname

CTRL+b $ sessionname                    --> Change/Rename the session
CTRL+b s                                --> List Session
CTRL+b shift %                          --> Split window vertically
CTRL+b "                                --> Split window horizontaly
CTRL+b o                                --> Next Window

CTRL+b z                                --> Fullscreen Windows Session
CTRL+b + (                              --> Previous tmux session
CTRL+b + )                              --> Next tmux session
CTRL+b ALTGR + [                        --> Scroll into window

CTRL+b <-                               --> Go to window left
CTRL+b ->                               --> Go to window right

CTRL+b+<-                               --> resize window
CTRL+b+->                               --> resize window

in the session:
$ tmux detach                           --> Detach from the current session
$ tmux attach                           --> Attach to the current session

To copy into buffer
CTRL+b ALTGR+[  SPACE  ENTER

To paste from buffer
CTRL+b ALTGR+]

CTRL+b : source-file <file>
CTRL+b : show-buffer
CTRL+b : list-buffer
```
