oh-my-zsh_iterm_dircolors
=========================
# 安装iterm oh-my-zsh dircolor
1. 第一步： 下载 oh-my-zsh-powerline-theme

  https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme.git

2. 进行安装

  此时需要配置 .zshrc

  修改设置 ZSH_THEME="powerline"

3.   第二步 需要修改文件夹颜色

  需要下载dircolors-solarized

  https://github.com/seebi/dircolors-solarized.git

    $ brew install coreutils

    $ git clone https://github.com/seebi/dircolors-solarized.git

    $ mv ./dircolors-solarized/dircolors.ansi-universal ~/.dircolors-solarized

  Terminal 安装在

  $ vim ~/.bash_profile

   iTerm 安装在

   $ vim .zshrc

  都添加如下代码

   `eval "$(gdircolors ~/.dircolors-solarized)"
alias ls='gls --color=auto`

4. Powerline fonts字体安装

  下载：

  https://github.com/Lokaltog/powerline-fonts.git
  进行安装
