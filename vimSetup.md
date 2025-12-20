# Setting up Vim for myself

## First Install Vim on you machine
Here you go [Vim](https://www.vim.org/). Enjoy :)

## Now its time to install vim-plug to start installing plug-ins

using this link follow the installation guide [vim-plug](https://github.com/junegunn/vim-plug)

After installing you will need to edit your plugins in the ~/.vimrc

here is my [.vimrc](scripts/vimrc) file

Reload the file or restart Vim, then you can,

- ``:PlugInstall`` to install the plugins

- ``:PlugUpdate`` to install or update the plugins

- ``:PlugDiff`` to review the changes from the last update

- ``:PlugClean`` to remove plugins no longer in the list

### Reloading vimrc file
You can use ``:source ~/.vimrc`` to reload the vimrc file