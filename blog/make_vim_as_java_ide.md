### make vim as a java ide

#### plugins
use dein as plugin manager

1. deoplete.nvim/neocomplete.vim

Install

```vim
call dein#add('Shougo/deoplete.nvim',{'on_event' : 'InsertEnter'})
```

2. vim-javacomplete2

Install and configuration

```vim
autocmd FileType java setlocal omnifunc=javacomplete#Complete
```

3. neomake
4. tagbar
5. unite
6. vimfiler


