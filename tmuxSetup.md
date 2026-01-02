# My tmux configuration settings
I made this configuration using https://tmuxai.dev/

## Install Tmux on your machine

## Install Tmux Plugin Manager
To setup tmux plugin manager use:
```bash
    git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
here is [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm)

## My Config File
Here is the [Configuration File](scripts/tmux.conf)

## My Customization
```vim
    " For making the terminal colors the same as my normal terminal
    set -g default-terminal "xterm-256color"
    " This made the space in copy mode start selecting 
    set -g mode-keys vi
```
