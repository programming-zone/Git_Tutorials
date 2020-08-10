## **TMUX**

### Shortcuts:

- split pane by column : ctrl + b then %
- split pane by row : ctrl + b then "
- last pane : ctrl + b ;
- swap pane: ctrl + b o 
- show panes numbers: ctrl + b q
- display pane number: ctrl + b q
- kill pane : ctrl + b x
- toggle pane layouts: ctrl + b [space]
- scroll in tmux: ctrl + b then [
- new window : ctrl + b then c
- last (previously used) window: ctrl + b then l
- rename a window: ctrl + b then ,
- previous window : ctrl + b then p
- next window : ctrl + b then n
- list windows : ctrl + b w 
- find window : ctrl + b f
- move window to selected index number : ctrl + b . 
- close current window : ctrl + b then &
- switch between windows : ctrl + b then [0-9]
- switch between sessions : ctrl + b then s
- rename sessions name : ctrl + b $
- dettach from tmux : ctrl + b then d
- big clock : ctrl + b t
- help : ctrl + b ?
- prompt: ctrl + b :

### Commands:
- kill tmux and all everything: `tmux kill-server`
- list sessions : `tmux ls`
- attach to a sessions : `tmux attach -t [session_name]` or `tmux a -t [session_name]`
- start new sessions : `tmux new -s [session_name]`
- delete a session: `tmux kill-session -t [session_name]`
- list sessions : `tmux list-sessions`
- rename a session : `tmux rename-session -t [old_sessions_name] [new_sessions_name]`
- list-windows : `tmux list-windows`
- delete a window: `tmux kill-window -t [window_name]`
- rename-window: `tmux -t [old_window_name] [new_window_name]`

### Commands inside **tmux** :

ctrl + b then type

new session : `: new [session_name]`

Resize window:

`:resize-pane -D [cell_size]` (Resizes the current pane down by 1 cell)

`:resize-pane -U [cell_size]` (Resizes the current pane upward by 1 cell)

`:resize-pane -L [cell_size]` (Resizes the current pane left by 1 cell)

`:resize-pane -R [cell_size]` (Resizes the current pane right by 1 cell)

Turn on all pane sync in tmux:

    `:setw synchronize-panes on`

Turn off pane sync in tmux:

    `:setw synchronize-panes off`

