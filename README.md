## ideavimrc

### 概述

本仓库主要记录个人使用JetBrains系列的快捷键配置，主要参考 https://github.com/MarcoIeni/intellimacs

### 使用

- 安装IdeaVim插件
- git clone git@github.com:haormj/ideavimrc.git
- 在home目录下创建.ideavimrc文件
    ```
    cd $HOME
    cat > .ideavimrc <<EOF
    source ./ideavimrc/ideavimrc
    EOF
    ```

### 修改

- 上述配置只是能够修改editor中的快捷键，对于编辑器中的一些是无用的
- C-f：我个人习惯是前进一个字符，将Editor Actions -> Right 增加 C-f 快捷键
