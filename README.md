* 下载Bundle:
    `git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`
    
* 修改配置：
    `cp vimrc ~/.vimrc`
    
* 安装插件：
    打开vim,执行`:BundleInstall`

* 如果vim配色方案在tmux下显示有问题，可以在~/.bash_profile中添加`alias tmux='tmux -2'`
* vim插件如果在git commit的时候不生效执行`git config --global core.editor vim`
