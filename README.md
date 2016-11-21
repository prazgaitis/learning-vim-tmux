# learning-vim-tmux
place to store vim and tmux things as I learn them

## Resizing panes
`Ctrl-a :resize-pane -R 10`

`Ctrl-a :resize-pane -L 10`

`Ctrl-a :resize-pane -D 10`

`Ctrl-a :resize-pane -U 10`

## After updating .bashrc file, respawn the pane! or else your new commands wont work.

`Ctrl-a :respawn-pane -k`

- The -k flag will kill the process in the pane and force tmux to read the updated bashrc file
