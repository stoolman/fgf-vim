1. 安装git

```
sudo apt-get isntall git
git config --global user.name "username"
git config --global user.email "username@company.com"
git config --global url.ssh://username@hmi-gerrit.it.chehejia.com:29418/.insteadOf ssh://192.168.4.101:29418
git config --global core.editor "vim"
git config --global color.ui "auto"
git config --global merge.tool "vimdiff"
git config --global commit.template "~/.gitmessage"
```

2. 配置vim

- 安装vim：sudo apt-get install vim
- 安装ctags：sudo apt-get install ctags
- 安装插件管理工具：[vundle][https://github.com/VundleVim/Vundle.vim]
- 安装插件管理工具vundle；配置.vimrc设置插件配色； git@github.com:stoolman/fgf-vim.git

3. 生成秘钥

ssh-keygen -t rsa -C [username@company.com](mailto:username@company.com)

4. 下载repo


```
curl https://mirrors.tuna.tsinghua.edu.cn/git/git-repo -o repo
chmod +x repo
```

