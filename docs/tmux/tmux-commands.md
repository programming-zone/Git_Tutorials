## **TMUX**

==========================================
                  tmux
==========================================

### Shortcuts:

- split window by column : ctrl + b then %
- split window by row : ctrl + b then "
- scroll in tmux: ctrl + b then [
- new window : ctrl + b then c
- close current window : ctrl + b then &
- switch between windows : ctrl + b then [0-9]
- switch between sessions : ctrl + b then s
- dettach from tmux : ctrl + b then d

### Commands:
- attach to a sessions : `tmux attach -t [sessions_name]`
- start new sessions : `tmux new -s [sessions_name]`
- list sessions : `tmux list-sessions`
- rename a session : `tmux rename-session -t [old_sessions_name] [new_sessions_name]`
- list-windows : `tmux list-windows`
- rename-window: `tmux -t [old_window_name] [new_window_name]`

### Commands inside **tmux** :

ctrl + b then type

Resize window:

`:resize-pane -D [cell_size]` (Resizes the current pane down by 1 cell)

`:resize-pane -U [cell_size]` (Resizes the current pane upward by 1 cell)

`:resize-pane -L [cell_size]` (Resizes the current pane left by 1 cell)

`:resize-pane -R [cell_size]` (Resizes the current pane right by 1 cell)
