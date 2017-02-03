# vimrc
my vimrc


    set number
    set autoindent
    set tabstop=4
    set expandtab
    set shiftwidth=4
    "set clipboard=unnamed
    syntax on
    set cursorline


    if has('gui_running')
        set guioptions-=T  " no toolbar
        colorscheme desert
        set guifont=Consolas:h10:cANSI
    endif

    execute pathogen#infect()
    let g:rainbow_active = 1 "0 if you want to enable later via :RainbowToggle
