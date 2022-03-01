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
- C-o：个人习惯是回到上一个位置，将编辑器使用的快捷键去除掉
- C-l：个人习惯是将当前鼠标位置内容移动到屏幕中间

### 小技巧

- 为了将编辑器的快捷键修改为你喜欢的样式，首先你需要知道编辑器具体的action，我个人是会安装vim插件，输入`:actionlist`会返回当前编辑器中所有的命令，这样你就可以随意定义快捷键了，在本仓库的目录下个人也保存了一份
- 默认markdown是未开启mermaid模式，可以参考[文档](https://www.jetbrains.com/help/idea/markdown.html#diagrams)开启
