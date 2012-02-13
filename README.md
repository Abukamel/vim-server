# VIM for Server Editor

VIM configuration for editing several files inside server (Ubuntu, Debian, Redhat, etc).

It's coming with several features : 

1. Commenter ( ``:gc``)

2. Support highlighting for several files ( sh, py, php and many else! )

3. Use Space and Backspace for Page-Down/Page-up shortcuts.

4. CTRL + V for paste mode

# Installation

It using Vundle for manage all plugin. So, I assume you have git installed.

```
cd ~/
git clone git://github.com/yodiaditya/vim-server.git
ln -s ~/vim-server/.vim ~/.vim
ln -s ~/vim-server/.vimrc ~/.vimrc
git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
```

Now, edit ~/.vimrc using VIM and do ``:BundleInstall`` to start downloading.

# Why you should use this ?

It help you while editing many files inside server through SSH.


