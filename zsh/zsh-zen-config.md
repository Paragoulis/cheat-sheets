# Zensh

### Inspired by Dreams of Autonomy [YouTube Channel](https://www.youtube.com/@dreamsofautonomy).

## Getting Started
```
$ chsh $USER
...
New shell [/bin/bash]: /bin/zsh
Shell changed.
```
```
$ echo $SHELL
/bin/zsh
```
```
$ mv ~/.zshrc ~/.zshrc.bak
$ clear
$ touch ~/.zshrc
```
## Plugin Manager - Zinit
[Zinit install](https://github.com/zdharma-continuum/zinit?tab=readme-ov-file#install)

```
$ zinit status
```

## Zenful Prompt
ohmyposh
TODO

## Big Three Plugins
```
zinit light zsh-users/zsh-syntax-highlighting
zinit light zsh-users/zsh-completions
zinit light zsh-users/zsh-autosuggestions
```
## Keybindings
```
bindkey -e
bindkey '^p' history-search-backward
bindkey '^n' history-search-forward
bindkey '^[w' kill-region
```
| key | description |
| --- | --- |
| ⌃f | Accepting suggestion |
| ⌃b | Moving backwards |
| ⌃f | Moving forwards |
| ⌃a | Jump to the start |
| ⌃e | Jump to the end| 
| ⌃p | Backward suggestion history |
| ⌃n | Forward suggestion history |
| ⌃w | Kill region |

## Snippets
| Snippet | description | link |
| --- | --- | --- |
| OMZP::archlinux | ohmyzsh archlinux plugin | [archlinux](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/archlinux) |
| OMZP::command-not-found | ohmyzsh command-not-found plugin | [command-not-found](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/command-not-found) |
| OMZP::git | ohmyzsh git plugin | [git](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git) |
| OMZP::sudo | ohmyzsh sudo plugin | [sudo](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/sudo) | 

## Basic Completion Sytling
Case-insensitive
```
zstyle ':completion:*' matcher-list 'm:{a-z}={A-Za-z}'
```

Colors
```
zstyle ':completion:*' list-colors "${(s.:.)LS_COLORS}"
```
## Fzf and Advanced Completion Styling
fzf - [GitHub](https://github.com/junegunn/fzf?tab=readme-ov-file#installation)

fzf-tab - zinit
```
zinit light Aloxaf/fzf-tab
```
fzf-tab - completion
```
zstyle ':completion:*' menu no
```
fzf-preview - completion
```
zstyle ':fzf-tab:complete:cd:*' fzf-preview 'ls --color $realpath'
```

## Better cd command
zoxide - [GitHub](https://github.com/ajeetdsouza/zoxide)

Shell integration
```
eval "$(zoxide init --cmd cd zsh)"
```

fzf-preview - completion
```
zstyle ':fzf-tab:complete:__zoxide_z:*' fzf-preview 'ls --color $realpath'
```







