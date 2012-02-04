# Installation #

1.  Install Node.js (see https://github.com/joyent/node/wiki/Installation)
2.  Install npm (see https://github.com/isaacs/npm#readme)
3.  Install node-jslint by `npm install jslint -g`
4.  Enable vim ftplugin and put the stuff under ftplugin/ of this repository into your .vim/ftplugin/ directory
5.  Enjoy :)

# Introduction #

A Vim filetype plugin for javascript that uses node-jslint as the linter.
The output of node-jslint is fed into the quickfix list of Vim.

# Implementation reference #

- http://technotales.wordpress.com/2011/05/21/node-jslint-and-vim/
- https://github.com/nvie/vim-pyflakes
