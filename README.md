# learning-vim-tmux
place to store vim and tmux things as I learn them

## Moving around
- beginning of file: `gg`
- end of file: `G`
- End of line: `$`
- beginning of next word: `w`
- beginning of current word: `b`

## Deleting
- `d` and then a movement command, eg `dG` to delete until end of file
- Deleting until a character: `dt<char>`
- Deleting until and including character: `df<char>`
-
## Resizing panes
`Ctrl-a :resize-pane -R 10`

`Ctrl-a :resize-pane -L 10`

`Ctrl-a :resize-pane -D 10`

`Ctrl-a :resize-pane -U 10`

#### Maximize the current pane
`Ctrl-a z`

## After updating .bashrc file, respawn the pane! or else your new commands wont work.

`Ctrl-a :respawn-pane -k`

- The -k flag will kill the process in the pane and force tmux to read the updated bashrc file

