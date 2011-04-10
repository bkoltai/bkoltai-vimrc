# Benji's vim config
## Adapted from Ricky Mondello, Marshal Moutenot, and Phil Tang
## About

This is the vim file that I use for all of my vim configurations.  Some key features are:

* **Tab complete support for various file types** 
* Sunburst and Peaksea color schemes
* Added mouse support for vim in terminal
* Intuitive file navigation
* Much more... See vimrc for specifics

Thanks to Mike, this project uses Pathogen, [a nice way of maintaining vim plugins](http://tammersaleh.com/posts/the-modern-vim-config-with-pathogen). Among the included plugins are [NERD Tree](http://www.vim.org/scripts/script.php?script_id=1658), a file explorer, and Snipmate, a way of bringing Textmate-style snippets to vim.

## Installation

	cd ~
	cp -r .vim .vim-backup
	git clone https://github.com/bkoltai/bkolta-vim.git
	mv bkoltai-vim .vim
	ln .vim/vimrc .vimrc

That should be it!
