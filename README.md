
## Vim and Vundle
Install vundle from git:

https://github.com/VundleVim/Vundle.vim

*git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim*

Open vim and run :PluginInstall

The .vimrc in this repo should have all the key plugins, (ycmd server?)

## Git aliases
add into the [alias] section of git config -e

*[user]
	email = pgrimes1991@yahoo.com
	name = Patrick Grimes
[core]
	editor = vim
[alias]
	s = status
	c = commit
	unstage = reset HEAD --
	a = add
	b = branch
	ch = checkout
*
