# jupyter-neosnippets-pymolpysnips
PyMOL Python snippet library to edit live Jupyter notebook cells with vim or neovim using the neosnippets plugin and the browser plugin GhostText

## Installation

I assume that the `neosnippets` plugin has already been properly installed.
The snippets are stored in a single file called `python.snippets`.
I store this file in a folder called `~/.vim/my-snippets/neosnippets`.
You may have to concatenate the `python.snippets` with an existing `python.snippets` file.

## Note

Some snippets depend on some pymolshortcuts.
Add the [pymolshortcuts.py](https://github.com/MooersLab/pymolshortcuts) file to your working directory.
