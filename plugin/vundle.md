## 安装插件管理工具 ##
 ```git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim```
## 配值插件 ##
```vim ~/.vimrc
set rtp+=~/.vim/bundle/Vundle.vim

call vundle#begin('~/.vim/plugged')
Plugin 'python-mode/python-mode'
Plugin 'Valloric/YouCompleteMe'
call vundle#end()
```

## 安装插件 ##
```
vim
:VundleInstall 
```
