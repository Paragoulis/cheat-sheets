# Tmux
Inspired by Dreams of Autonomy YouTube Channel.

## Getting Started
[Tmux plugin manager](https://github.com/tmux-plugins/tpm)

```
$ touch ~/.config/tmux/tmux.conf
```

Edit tmux.conf
```
set -g @plugin 'tmux-plugin/tpm'
set -g @plugin 'tmux-plugin/tmux-sensible'

run '~/.tmux/plugins/tpm/tpm'
```
Save
```
$ tmux
```
```
$ tmux source ~/.config/tmux/tmux.conf
```

## Better Navigation
[Vim Tmux Navigator](https://github.com/christoomey/vim-tmux-navigator)

```
...
set -g @plugin 'christoomey/vim-tmux-navigator'
...
```
This plugin provides the following mappings which allow you to move between Vim panes and tmux splits seamlessly.

| key | description |
| --- | --- |
| ctrl-h | Left |
| ctrl-j | Down  |
| ctrl-k | Up |
| ctrl-l | Right |

Shift Alt vim keys to switch windows
| key | description |
| --- | --- |
| shift-alt-h | Previous window |
| shift-alt-j | Next window |

```
# Shift Alt vim keys to switch windows
bind -n M-H previous-window
bind -n M-L next-window
```

[Tmux Cheat Sheet](https://tmuxcheatsheet.com/)


## Colors
```
# Set true color
set-option -sa terminal-overrides ",xterm*:Tc"
...
```

## Theme
```
...
set -g @catppuccin_flavour 'mocha'
...
set -g @plugin 'dreamsofcode-io/catppuccin-tmux'
...
```

## Mouse Support
```
...
# Mouse support
set -g mouse
...
```

## Yanking
```
...
set -g @plugin 'tmux-plugin/tmux-yank'
...
# set vi-mode
set-window-option -g mode-keys vi
# keybindings
bind-key -T copy-mode-vi v send-keys -X begin-selection
bind-key -T copy-mode-vi C-v send-keys -X rectangle-toggle
bind-key -T copy-mode-vi y send-keys -X copy-selection-and-cancel
...
```

## Current working directory
```
...
bind '"' split-window -v -c "#{pane_current_path}"
bind % split-window -h -c "#{pane_current_path}"
...
```


