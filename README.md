# dotfiles

for Mac.

## 注意事项

首先，更新所有submodule:

    $ git submodule update --init

如果需要强制建立软连接(以vim为例):

    $ make vim force=1

## vim

1. 系统依赖: ctags, GNU GLOBAL

2. Mac安装ctags:

    * Download ctags from <http://ctags.sourceforge.net/>
    * extract it, and

    ```
    $ ./configure
    $ sudo make install
    ```

    * or you can use brew

    ```
    $ brew install ctags
    ```

3. Mac安装GNU GLOBAL

    * Getting GLOBAL from <http://www.gnu.org/software/global/download.html> and install it
    * or you can use brew

    ```
    $ brew install global
    ```

4. 由于要使用ycm，所以确保你的vim的版本在7.3.584及以上并且支持python2，如果不满足要求的话需要重新编译vim

4. then:

    ```
    $ make vi
    ```

## iterm2

     $ make iterm2

然后安装iterm2/badwolf.itermcolors

# git

     $ make git

## tmux

     $ make tmux

## zsh

     $ make zsh

## reference

*最初阅读并参考了hit9的文章和dotfiles，特此表示感谢*

