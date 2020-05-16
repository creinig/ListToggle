ListToggle
==========

A simple vim plugin for toggling the display of the quickfix list and the
location-list. Install it with [Vundle][] or [Pathogen][] (I recommend Vundle).

This fork does not set any keybindings, only provides the toggle commands. You
can define mappings yourself like this:

    nnoremap <leader>ll :LToggle " toggle location list
    nnoremap <leader>qq :QToggle " toggle quickfix list

Here's how you can set the height (in number of lines) of the spawned window:

    let g:lt_height = 10

[vundle]: https://github.com/gmarik/vundle#about
[pathogen]: https://github.com/tpope/vim-pathogen#pathogenvim

