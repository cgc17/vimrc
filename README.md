# vimrc
my vimrc

    set number
    set autoindent
    set tabstop=4
    set expandtab
    set shiftwidth=4
    syntax on
    imap <S-Tab> <Esc><<i
    
    
    if has('gui_running')
        "set guioptions-=T  " no toolbar
        colorscheme desert
        set guifont=Consolas:h10:cANSI
    endif
