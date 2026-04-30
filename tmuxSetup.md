# My tmux configuration settings
I made this configuration using https://tmuxai.dev/

## Install Tmux on your machine
Here is a guid on [how to install tmux](https://tmuxcheatsheet.com/how-to-install-tmux/)

## Install Tmux Plugin Manager
To setup tmux plugin manager use:
```bash
    git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
To install Plugins use in tmux press ``prefix`` + ``I`` to fetch the plugin.

here is [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm)

## My Config File

Here is my [Configuration File](scripts/tmux.conf)

To link the config file use the following cmd:

```bash
    ln -s ./scripts/tmux.conf ~/.tmux.conf
```

## My Customization
```vim
    " For making the terminal colors the same as my normal terminal
    set -g default-terminal "xterm-256color"
    " This made the space in copy mode start selecting 
    set -g mode-keys vi
```
