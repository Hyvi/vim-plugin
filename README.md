vim配置,持续更新

# Vim Install 
子标题为各个插件的安装注意项。 

## vundle 安装
```bash 
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

##  ftplugin
目录下是各种文件类型的配置, 安装方式如下
```bash 
git clone https://github.com/Hyvi/vim-plugin.git
# 或者mv vim-plugin/ftpugin ~/.vim/
ln -s vim-plugin/ftplugin ~/.vim/ftplugin
````

## YouCompleteMe
PS: 使用 vim-go 本身自动完成功能，支持Golang代码完成
```bash
python3.7  install.py 
```

## tagbar 

### lvht/tagbar-markdown
tagbar 本身支持 markdown, [ wiki markdown ](https://github.com/majutsushi/tagbar/wiki#markdown)，但是在UI上有点差，比如tagbar-markdown.  

- tagbar-markdown 需要Php的支持. 



# zshrc
记录 zsh + oh-my-zsh 的安装和使用

## zsh completion(compinit / compaudit)

> zsh compinit: insecure directories, run compaudit for list.  Ignore insecure directories and continue [y] or abort compinit [n]? y

[https://stackoverflow.com/questions/13762280/zsh-compinit-insecure-directories]  

```bash 
sudo chmod -R 755 /usr/local/share/zsh
sudo chown -R root:staff /usr/local/share/zsh
```

## zsh-autosuggestions
[https://github.com/zsh-users/zsh-autosuggestions#usage] 


# 参考

sebdah's nvim configuration  
https://github.com/sebdah/dotfiles/blob/ab2c2357a6853a29010762a45610b2ab31c71eb5/config/nvim/init.vim  

