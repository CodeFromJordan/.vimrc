set nocompatible " Get rid of Vi compatibility

syntax on " Turn on code syntax highlighting

" Turn off Vim's automatic backup features
set nobackup
set nowritebackup
set noswapfile

colorscheme slate " Set default colour scheme

" Make tabbing better (any only 4 spaces)
set tabstop=4 " Tab spacing
set shiftwidth=4 " Indent by 4 spaces
set softtabstop=4
set expandtab " Use spaces instead of tabs
set smarttab " Tabs at start of line, spaces elsewhere. Can delete tabs using backspace
set shiftround " Always indent to nearest tab stop
set autoindent " Automatically indent new lines
set smartindent " Match indenting on new lines

" Make search better
set ignorecase " Case insensitive search
set smartcase " If there are uppercase letters, become case-sensitive.
set incsearch " Live incremental searching
set showmatch " Live match highlighting
set hlsearch " Highlight matches
