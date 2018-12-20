# vim

Creare la cartella vim nella home directory
```
$ mkdir vim
```
scaricare il file `vimrc` nella cartella `vim`
```
$ git clone https://github.com/giacfuria/vim.git
```
creare il link con il vero file di configurazione
```
$ ln -s ~/.vim/vimrc ~/.vimrc
```
Contenuto del file `vimrc`
```javascript {.line-numbers}
set number
syntax enable
set tabstop=4
filetype indent on
set showmatch
```
